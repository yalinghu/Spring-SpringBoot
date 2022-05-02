# Spring&SpringBoot

Spring是一个轻量级Java开发框架，Spring可以做很多事情，它为企业级开发提供给了丰富的功能，但是这些功能的底层都依赖于它的两个核心特性，也就是**依赖注入（dependency injection，DI）和面向切面编程（aspect-oriented programming，AOP）**。  Spring 总共大约有 20 个模块， 由 1300 多个不同的文件构成。 而这些组件被分别整合在:  
  - 核心容器（Core Container）  
  - AOP（Aspect Oriented Programming）  
  - 设备支持（Instrmentation）   
  - 数据访问与集成（Data Access/Integeration）   
  - Web  
  - 消息（Messaging）   
  - Test  
   
什么是Spring Beans？
Spring beans：提供了BeanFactory，是工厂模式的一个经典实现，Spring将管理对象称为Bean。*（可以把Spring容器理解成一个大型工厂，Bean就是该工厂的产品，工厂(Spirng容器)里能生产出来什么样的产品（Bean），完全取决于配置文件中的配置。而这个配置是由开发人员创建和维护的，而在SpringBoot里面已经通过注解来实现，常用的bean注解有@Controller,@Service,@Component,还有@Configuration（bean的配置类））*  

详细笔记可参考：https://github.com/dunwu/spring-tutorial/blob/master/docs/core/Spring%E4%BE%9D%E8%B5%96%E6%B3%A8%E5%85%A5.md





