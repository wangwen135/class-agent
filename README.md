# java 代理工具

## 功能

### 1、 类加载情况
输出当前系统所加载的所有类和类的资源路径

### 2、 输出Class
输出指定类（匹配类名称）的Class文件到指定的问题

### 3、 调试（没做完）
输出指定的调用链 和 参数 

## 用法

在启动脚本上加上：
```
java -javaagent:class-agent-0.0.1-SNAPSHOT.jar -cp runner-0.0.1-SNAPSHOT.jar com.wwh.runner.EmptyRunner

//指定参数的
java -javaagent:class-agent-0.0.1-SNAPSHOT.jar=/opt/xxx/out -cp runner-0.0.1-SNAPSHOT.jar com.wwh.runner.EmptyRunner

```