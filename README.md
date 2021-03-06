### 1、基础框架部分：

通过springboot+maven+MBG+html快速开发一个基础版本商品秒杀系统，包括用户注册、登录、验证、下单等功能。

### 2、**压测：**Jmeter压测

从基础版本开始尝试优化并压测，查看性能。

### 3、优化部分：

1. **优化接口：**扩展分布式系统，添加Nginx负载均衡、多级缓存、异步消息队列、分布式会话管理、优化系统的查询商品接口、下单减库存接口、增加销量接口，提升响应速度。
2. **压力泄洪：**令牌桶算法、阻塞队列线程池保护服务器，压力泄洪。
3. **防止攻击：**动态返回模糊数字验证码给前端验证防止服务器被攻击。
4. **主要使用技术：** Jmeter、Spring Boot、Nginx、Guava、MySQL、Redis数据库、RocketMQ、令牌桶、阻塞队列线程池、Mybatis、MBG逆向工程，Maven自动化构建工具等技术。