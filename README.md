学习笔记
#Week01 作业题目（周四）：

1. （选做）、自己写一个简单的 Hello.java，里面需要涉及基本类型，四则运行，if 和 for，然后自己分析一下对应的字节码，有问题群里讨论。
2. （必做）、自定义一个 Classloader，加载一个 Hello.xlass 文件，执行 hello 方法，此文件内容是一个 Hello.class 文件所有字节（x=255-x）处理后的文件。文件群里提供。
       本地运行结果
       "C:\Program Files\Java\jdk1.8.0_171\bin\java" -Didea.launcher.port=7533 "-Didea.launcher.bin.path=C:\Program Files (x86)\JetBrains\IntelliJ IDEA 2016.2.4\bin" -Dfile.encoding=UTF-8 -classpath "C:\Program Files\Java\jdk1.8.0_171\jre\lib\charsets.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\deploy.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\access-bridge-64.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\cldrdata.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\dnsns.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\jaccess.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\jfxrt.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\localedata.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\nashorn.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\sunec.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\sunjce_provider.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\sunmscapi.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\sunpkcs11.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\ext\zipfs.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\javaws.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\jce.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\jfr.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\jfxswt.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\jsse.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\management-agent.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\plugin.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\resources.jar;
       C:\Program Files\Java\jdk1.8.0_171\jre\lib\rt.jar;
       G:\idea-workspace\lwn-high-java-learn\target\classes;
       C:\Program Files (x86)\JetBrains\IntelliJ IDEA 2016.2.4\lib\idea_rt.jar" com.intellij.rt.execution.application.AppMain com.jerry.learn.HelloClassLoader
       Hello, classLoader!

       Process finished with exit code 0
3. （必做）、画一张图，展示 Xmx、Xms、Xmn、Meta、DirectMemory、Xss 这些内存参数的关系。
4. （选做）、检查一下自己维护的业务系统的 JVM 参数配置，用 jstat 和 jstack、jmap 查看一下详情，并且自己独立分析一下大概情况，思考有没有不合理的地方，如何改进。
注意：如果没有线上系统，可以自己 run 一个 web/java 项目。