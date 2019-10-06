# UML建模语言
1. 活动图，它表示一个过程或数据处理中所涉及的活动。
2. 用例图，它表示一个系统和它所处环境之间的交互。
3. 时序图，它表示参与者和系统之间以及系统各部分之间的交互。
4. 类图，它表示系统中的对象类以及这些类之间的联系。
5. 状态图，它表示系统是如何响应内部和外部事件的。

## 类图

1. 泛化（继承），抽象出更一般的类（比如动物，汽车，房子）来表示一个实体。
2. 关联，表示两个类是1对1，1对N的关系。代码体现：成员变量
3. 聚合，聚合是关联关系的一种。现实世界的对象可能由不同的对象组合而成，比如一个学习包是由课本，PPT讲义，课后习题组成。学习包和课本是整体与部分的关系，但是部分（课本）可以离开整体（学习包）而单独存在。
4. 组合，组合是关联关系的一种。是整体与部分的关系，但部分不能离开整体而单独存在。如公司和部门是整体和部分的关系，没有公司就不存在部门。
5. 实现，表示某个类实现某个接口。
6. 依赖，是一种使用的关系，即一个类的实现需要另一个类的协助。代码体现：局部变量、方法的参数或者对静态方法的调用。

![类图示例](http://www.plantuml.com/plantuml/png/SoWkIImgAStDuKhEIImkLd1EBEBAp2j9BKfBJ4vL22hDg-O24XhfYSNvEPbvgPfSjLmkHPbbgKKAkdOARgb5HOb5cLOAJritlsYSef02aYbMiEE2IYZa0nM5PwIcvYXOARnedFLqGeT2Hc9Pge89K0tG9fiQNLs48SztBt_MkL_ZsURPJtkcQIhOW2nMiAdHqmEg15gnRjxplWr0KPXJ56pqz40Ej59uic_kYwtJW59SJrlNFEtVeQ05jFPbyugNqrSeW8nj0ThxVayFHEJvijrFzpH053xPqVkYUU_pxZNFLtS_NJlZwPmLG6LW1-O17UYGcfS231W0)

