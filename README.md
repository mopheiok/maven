# maven
编译打包整个工程及各个module

mvn clean package

仅打包core、service两个模块，而不打包其他模块。且root-project不会编译不会生成target路径

mvn -pl core,service clean package
