> 以下的三层架构都指的是mapper、service、controller

## **MVVM 与 三层架构 + 前端的对应关系**

| **MVVM 组件** | **三层架构 + 前端**  | **说明**                                                     |
| ------------- | -------------------- | ------------------------------------------------------------ |
| **Model**     | **Mapper + Service** | Model 在 MVVM 中代表数据和业务逻辑，对应到后端的三层架构中，Mapper 负责数据访问，Service 负责业务逻辑。 |
| **ViewModel** | **Controller**       | ViewModel 是 View 和 Model 之间的桥梁，负责将数据转换为前端可用的形式。Controller 在后端中负责接收请求、调用 Service，并返回数据给前端，类似于 ViewModel 的角色。 |
| **View**      | **前端（UI 层）**    | View 在 MVVM 中是用户界面，对应到前端部分，负责展示数据和接收用户输入。 |

---

### 1. **详细对应关系**

#### **(1) Model 对应 Mapper + Service**
- **Model 的职责**：在 MVVM 中，Model 负责管理应用程序的数据和业务逻辑。
- **Mapper 的职责**：在后端三层架构中，Mapper（或 DAO 层）负责与数据库交互，获取和存储数据。
- **Service 的职责**：Service 层负责实现业务逻辑，处理来自 Controller 的请求，并调用 Mapper 获取或操作数据。
- **对应关系**：Model 的功能由 Mapper 和 Service 共同实现。Mapper 提供数据访问能力，Service 提供业务逻辑处理能力。

#### **(2) ViewModel 对应 Controller**
- **ViewModel 的职责**：在 MVVM 中，ViewModel 负责将 Model 中的数据转换为 View 可以使用的形式，并处理 View 的交互逻辑。
- **Controller 的职责**：在后端三层架构中，Controller 负责接收前端的请求，调用 Service 处理业务逻辑，并将结果返回给前端。
- **对应关系**：Controller 类似于 ViewModel，它作为后端与前端的桥梁，将后端的数据（来自 Service）转换为前端需要的格式（如 JSON），并返回给前端。

#### **(3) View 对应前端（UI 层）**
- **View 的职责**：在 MVVM 中，View 负责展示数据和接收用户输入。
- **前端（UI 层）的职责**：前端负责渲染页面、展示数据，并将用户操作发送到后端（Controller）。
- **对应关系**：View 对应前端部分，前端通过调用后端接口（Controller）获取数据，并将数据绑定到 UI 上。

---

### 2. **数据流对比**

#### **MVVM 数据流**
1. **View → ViewModel**：用户在前端（View）操作，触发事件，事件被传递到 ViewModel。
2. **ViewModel → Model**：ViewModel 调用 Model 获取或更新数据。
3. **Model → ViewModel**：Model 将数据返回给 ViewModel。
4. **ViewModel → View**：ViewModel 更新数据，并通过数据绑定机制自动更新 View。

#### **三层架构 + 前端数据流**
1. **前端 → Controller**：用户在前端操作，触发请求，请求被发送到后端的 Controller。
2. **Controller → Service**：Controller 调用 Service 处理业务逻辑。
3. **Service → Mapper**：Service 调用 Mapper 访问数据库。
4. **Mapper → Service**：Mapper 将数据返回给 Service。
5. **Service → Controller**：Service 将处理后的数据返回给 Controller。
6. **Controller → 前端**：Controller 将数据返回给前端，前端渲染页面。

---

### 3. **代码示例对比**

#### **MVVM 示例（前端框架如 Vue.js）**
```javascript
// Model (模拟数据)
const model = {
  data: [],
  fetchData() {
    // 模拟从后端获取数据
    this.data = [{ id: 1, name: "Alice" }, { id: 2, name: "Bob" }];
  }
};

// ViewModel
const viewModel = {
  users: [],
  loadData() {
    model.fetchData();
    this.users = model.data;
  }
};

// View (Vue.js)
new Vue({
  el: '#app',
  data: {
    users: []
  },
  created() {
    viewModel.loadData();
    this.users = viewModel.users;
  }
});
```

#### **三层架构 + 前端示例**
```java
// Controller (Spring Boot)
@RestController
@RequestMapping("/users")
public class UserController {
    @Autowired
    private UserService userService;

    @GetMapping
    public List<User> getUsers() {
        return userService.getAllUsers();
    }
}

// Service
@Service
public class UserService {
    @Autowired
    private UserMapper userMapper;

    public List<User> getAllUsers() {
        return userMapper.selectAllUsers();
    }
}

// Mapper (MyBatis)
@Mapper
public interface UserMapper {
    List<User> selectAllUsers();
}
```

```javascript
// 前端 (Vue.js)
new Vue({
  el: '#app',
  data: {
    users: []
  },
  created() {
    // 调用后端接口获取数据
    fetch('/users')
      .then(response => response.json())
      .then(data => {
        this.users = data;
      });
  }
});
```

---

### 4. **总结**
- **Model** 对应后端的 **Mapper + Service**，负责数据访问和业务逻辑。
- **ViewModel** 对应后端的 **Controller**，负责将数据转换为前端可用的形式。
- **View** 对应 **前端（UI 层）**，负责展示数据和接收用户输入。



## **MVP 与 三层架构 + 前端的对应关系**

| **MVP 组件**  | **三层架构 + 前端**  | **说明**                                                     |
| ------------- | -------------------- | ------------------------------------------------------------ |
| **Model**     | **Mapper + Service** | Model 在 MVP 中代表数据和业务逻辑，对应到后端的三层架构中，Mapper 负责数据访问，Service 负责业务逻辑。 |
| **View**      | **前端（UI 层）**    | View 在 MVP 中是用户界面，负责展示数据和接收用户输入，对应到前端部分。 |
| **Presenter** | **Controller**       | Presenter 在 MVP 中负责处理 UI 逻辑，对应到后端的 Controller，负责接收前端请求、调用 Service，并返回数据给前端。 |

---

### 1. **详细对应关系**

#### **(1) Model 对应 Mapper + Service**
- **Model 的职责**：在 MVP 中，Model 负责管理应用程序的数据和业务逻辑。
- **Mapper 的职责**：在后端三层架构中，Mapper（或 DAO 层）负责与数据库交互，获取和存储数据。
- **Service 的职责**：Service 层负责实现业务逻辑，处理来自 Controller 的请求，并调用 Mapper 获取或操作数据。
- **对应关系**：Model 的功能由 Mapper 和 Service 共同实现。Mapper 提供数据访问能力，Service 提供业务逻辑处理能力。

#### **(2) View 对应前端（UI 层）**
- **View 的职责**：在 MVP 中，View 负责展示数据和接收用户输入。
- **前端（UI 层）的职责**：前端负责渲染页面、展示数据，并将用户操作发送到后端（Controller）。
- **对应关系**：View 对应前端部分，前端通过调用后端接口（Controller）获取数据，并将数据绑定到 UI 上。

#### **(3) Presenter 对应 Controller**
- **Presenter 的职责**：在 MVP 中，Presenter 负责处理 UI 逻辑，接收 View 的输入，调用 Model 获取数据，并将数据返回给 View。
- **Controller 的职责**：在后端三层架构中，Controller 负责接收前端的请求，调用 Service 处理业务逻辑，并将结果返回给前端。
- **对应关系**：Presenter 类似于 Controller，它作为后端与前端的桥梁，将后端的数据（来自 Service）转换为前端需要的格式（如 JSON），并返回给前端。

---

### 2. **数据流对比**

#### **MVP 数据流**
1. **View → Presenter**：用户在前端（View）操作，触发事件，事件被传递到 Presenter。
2. **Presenter → Model**：Presenter 调用 Model 获取或更新数据。
3. **Model → Presenter**：Model 将数据返回给 Presenter。
4. **Presenter → View**：Presenter 将数据返回给 View，View 更新 UI。

#### **三层架构 + 前端数据流**
1. **前端 → Controller**：用户在前端操作，触发请求，请求被发送到后端的 Controller。
2. **Controller → Service**：Controller 调用 Service 处理业务逻辑。
3. **Service → Mapper**：Service 调用 Mapper 访问数据库。
4. **Mapper → Service**：Mapper 将数据返回给 Service。
5. **Service → Controller**：Service 将处理后的数据返回给 Controller。
6. **Controller → 前端**：Controller 将数据返回给前端，前端渲染页面。

---

### 3. **代码示例对比**

#### **MVP 示例（前端框架如 React）**
```javascript
// Model (模拟数据)
class Model {
  fetchData() {
    // 模拟从后端获取数据
    return Promise.resolve([{ id: 1, name: "Alice" }, { id: 2, name: "Bob" }]);
  }
}

// Presenter
class Presenter {
  constructor(view, model) {
    this.view = view;
    this.model = model;
  }

  loadData() {
    this.model.fetchData().then(data => {
      this.view.displayData(data);
    });
  }
}

// View (React)
class View extends React.Component {
  constructor(props) {
    super(props);
    this.state = { users: [] };
    this.presenter = new Presenter(this, new Model());
  }

  displayData(data) {
    this.setState({ users: data });
  }

  componentDidMount() {
    this.presenter.loadData();
  }

  render() {
    return (
      <ul>
        {this.state.users.map(user => (
          <li key={user.id}>{user.name}</li>
        ))}
      </ul>
    );
  }
}
```

#### **三层架构 + 前端示例**
```java
// Controller (Spring Boot)
@RestController
@RequestMapping("/users")
public class UserController {
    @Autowired
    private UserService userService;

    @GetMapping
    public List<User> getUsers() {
        return userService.getAllUsers();
    }
}

// Service
@Service
public class UserService {
    @Autowired
    private UserMapper userMapper;

    public List<User> getAllUsers() {
        return userMapper.selectAllUsers();
    }
}

// Mapper (MyBatis)
@Mapper
public interface UserMapper {
    List<User> selectAllUsers();
}
```

```javascript
// 前端 (React)
class App extends React.Component {
  constructor(props) {
    super(props);
    this.state = { users: [] };
  }

  componentDidMount() {
    // 调用后端接口获取数据
    fetch('/users')
      .then(response => response.json())
      .then(data => {
        this.setState({ users: data });
      });
  }

  render() {
    return (
      <ul>
        {this.state.users.map(user => (
          <li key={user.id}>{user.name}</li>
        ))}
      </ul>
    );
  }
}
```

---

### 4. **总结**
- **Model** 对应后端的 **Mapper + Service**，负责数据访问和业务逻辑。
- **View** 对应 **前端（UI 层）**，负责展示数据和接收用户输入。
- **Presenter** 对应后端的 **Controller**，负责处理 UI 逻辑，并将数据返回给前端。

通过这种对应关系，可以将 MVP 的思想应用到传统的三层架构中，实现前后端分离和清晰的职责划分。与 MVVM 相比，MVP 更强调 **Presenter** 对 UI 逻辑的控制，适合需要更精细控制 UI 交互的场景。