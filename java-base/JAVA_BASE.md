**java语言**
    面对对象编程（同C++）
    三大特性：封装、继承、多态
    **封装**
        利用抽象数据类型将数据跟基于数据的操作封装在一起，数据保存在结构内部，不对外暴露，尽可能的隐藏内部细节实现，提供
    具体的动作接口给外部使用。
        例子：
        class Cat {
            private String name;
            private String sex;
            // 公共方法
            public String getName() {
                return name;
            }
        }
    **继承**
        is A，例如 Cat与Animal就是一种is A的关系，cat是animal的一种，就可以说cat继承了Animal（关键字 extends）
    但是，继承关系，子类只能继承父类的共有属性。
        并且，继承需要满足 里氏替换原则，即子类对象可以替换掉所有父类对象（父类引用指向子类对象，也就是所谓的'上转型'）
    **多态**
            
    