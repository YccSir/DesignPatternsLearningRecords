- 提出问题:如果在不同地区想开不同的PizzaStore,且每个PizzaStore可能会有Pizza的不同制作方式,甚至不同种类,如果按照SimpleFactory的话,就得在每个地区建一个工厂,一个PizzaStore
这样会极大增加类的数量.
- 那么,我们可以使用框架:
  将store和创建产品绑在一起的同时,又保留一定的弹性.
  在本例中,工厂方法模式通过PizzaStore实现,即一个Store就是一个创建者(工厂),而不是像简单工厂那样,有一个Factory和一个Store.
- 这样的不足之处在于:
    实际上客户还是得显示的指定调用的工厂类
- 工厂方法模式:
    - 定义: 让子类决定对象的创建,来达到对象封装的目的.工厂方法把实例化过程推迟到子类.
    - 从形式上看,没有工厂factory,只有创建者Store.
    - 这样是针对接口编程,而不是针对实现编程.


