第三章 高级装配
    3.1环境与profile
        @Porfile    spring3.1 类级别 spring 3.2方法级别
    3.2条件化的bean
        @Conditonal spring4
        基于@conditional重构@profile
    3.3处理自动装配得歧义性
        @Primary 首选bean 两个或更多的首选bean,也会有歧义性
        @Qualifier("beanId") 基于beanId的限定符 ->面向特性的限定符
        @自定义限定符注解
    3.4bean的作用域
        @Scope
        作用于代理
    3.5运行时注入
        Environment类
        属性占位符 参考网址http://jinnianshilongnian.iteye.com/blog/2000183
            @PropertySource
        SpEL