# Design Patterns in Rust

- [Design Patterns - Wikipedia](https://en.wikipedia.org/wiki/Design_Patterns)
- [Design Patterns: Elements of Reusable Object-Oriented Software](https://www.goodreads.com/book/show/85009.Design_Patterns)
- [Head First Design Patterns](https://www.goodreads.com/book/show/58128.Head_First_Design_Patterns)
- [Design Patterns in Rust](https://refactoring.guru/design-patterns/rust)
- [Rust Design Patterns](https://rust-unofficial.github.io/patterns/)
-
- 设计模式（Design Patterns）是一套被反复使用、多数人知晓的、经过分类编目的、代码设计经验的总结。
- 23 种经典的设计模式

## Creational Patterns 创建型设计模式

### Abstract Factory 抽象工厂模式

### Builder 建造者模式

### Factory Method 工厂方法模式

### Prototype 原型模式

### Singleton 单例模式

## Structural Patterns 结构型设计模式

### Adapter Pattern 适配器模式

### Bridge 桥接模式

### Composite 组合模式

### Decorator 装饰者模式

### Facade 外观模式

### Flyweight 享元模式

### Proxy 代理模式

## Behavioral Patterns 行为型设计模式

### Chain of Responsibility 职责链模式

### Command 命令模式

### Interpreter 解释器模式

### Iterator 迭代器模式

### Mediator 中介者模式

### Memento 备忘录模式

### Observer 观察者模式

### State 状态模式

- The `state pattern` is an object-oriented design pattern. The crux of the pattern is that we define a set of states a value can have internally. The states are represented by a set of `state objects`, and the value's behavior changes based on its state.
- The advantage of using the `state pattern` is that, when the business requirements of the program change, we won't need to change the code of the value holding the state or the code that uses the value. We'll only need to update the code inside one of the state objects to change its rules or perhaps add more state objects.

### Strategy 策略模式

- There is no need for the strategy pattern in Rust because we can just use `trait`s.

### Template Method 模板方法模式

### Visitor 访问者模式
