## Objective-C Tips

1. Objective-C 起源于 SmallTalk，它们都采用消息结构
2. 在类的头文件中，尽量少引入其他头文件
3. 多用字面量语法，少用与之等价的方法
4. 多用类型常量，少用#define 预处理指令
5. 用枚举表示状态、选项、状态码
6. 属性用于封装对象中的数据
7. 在对象内部尽量直接访问实例变量
8. 对象等同性
9. 以“类族模式”隐藏实现细节
10. 在既有类中使用管理对象，以存储自定义数据
11. objc_msgSend 的作用
12. 消息转发机制
13. 用“方法调配技术”调试“黑盒方法”
14. 类对象
15. 用前缀避免命名空间冲突
16. 提供全能初始化方法
17. 实现 description 方法
18. 尽量使用不可变对象
19. 使用清晰而协调的命名方式
20. 为私有方法加前缀
21. Objective-C错误模型
22. NSCopying协议：使自己的类支持拷贝
23. 通过委托与数据源协议进行对象间通信
24. 将类的实现代码分散到便于管理的数个分类中
25. 总是为第三方类的分类名称加前缀
26. 不要在分类中声明属性
27. 使用 class-continuation 分类隐藏实现细节
28. 通过协议提供匿名对象
29. 引用计数
30. 以 ARC 简化引用计数
31. 在 dealloc 方法中只释放引用并解除监听
32. 编写“异常安全代码”时注意内存管理问题
33. 以弱引用避免保留环
34. 以”自动释放池块“降低内存峰值
35. 用“僵尸对象”调试内存管理问题
36. 不要使用 retainCount
37. 块
38. 为常用的块类型创建 typedef
39. 用 handler 块降低代码分散程度
40. 用块引用其所属对象时，避免出现保留环
41. 多用派发队列，少用同步锁
42. 多用 GCD，少用 performSelector（易导致内存泄露）
43. GCD 及操作队列的使用时机
44. 通过 Dispatch Group 机制，根据系统资源状况来执行任务
45. 使用 dispatch_once 来执行只需运行一次的线程安全代码
46. 不要使用dispatch_get_current_queue
47. 熟悉系统框架
48. 多用块枚举，少用 for 循环
49. 对自定义其内存管理语义的 collection 使用无缝桥接
50. 构建缓存时使用 NSCache
51. 精简 initialize 与 load 的实现代码
52. NSTimer 会保留其目标对象