# 单一职责原则

Single Responsibility Principle（SRP），一个类或模块只负责完成一个职责或功能。

## 判断标准

- 类中的代码行数、函数或属性过多，会影响代码的可读性和可维护性，就需要考虑是否要拆分。
- 类依赖的其他类过多，不符合高内聚、低耦合设计思想。
- 私有方法过多，需要考虑是否可以将私有方法抽取到其他类中，变为公有方法，提高复用性。
- 如果类的名字比较难起，要考虑职责是否单一。
- 类中的大部分方法都是在处理其中的几个属性，就要考虑对应的属性是否可以抽取为单独的类。

## 注意

- 类的职责并不是越单一越好，拆分的过于单一降低了内聚性，也会影响代码的可维护性。