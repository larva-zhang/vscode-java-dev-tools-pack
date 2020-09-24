# Java Dev Tools Pack
Java开发常用的VS Code扩展集合。

## 已包含扩展集合
列表以[extension displayName]()`extension identifier`描述的形式排列。
> identifier由publisher.extensionName组成。

### General

* [Material Icon Theme](https://marketplace.visualstudio.com/items?itemName=PKief.material-icon-theme) `PKief.material-icon-theme` Material Design风格的图标集
* [XML Tools](https://marketplace.visualstudio.com/items?itemName=DotJoshJohnson.xml) `DotJoshJohnson.xml` XML Formatting, XQuery, and XPath Tools for Visual Studio Code
* [YAML](https://marketplace.visualstudio.com/items?itemName=redhat.vscode-yaml) `redhat.vscode-yaml` Red Hat出品的YAML语言支持扩展
* [Properties To Yaml](https://marketplace.visualstudio.com/items?itemName=tanaka-x.prop2yaml) `tanaka-x.prop2yaml` Convert properties to yaml
* [Markdown Preview Enhanced](https://marketplace.visualstudio.com/items?itemName=shd101wyy.markdown-preview-enhanced) `shd101wyy.markdown-preview-enhanced` 强大的Markdown扩展，支持实时预览、plantUML/mermaid渲染、PDF导出、TOC自动生成等功能
* [AsciiDoc](https://marketplace.visualstudio.com/items?itemName=asciidoctor.asciidoctor-vscode) `asciidoctor.asciidoctor-vscode` 支持asciidoc语法高亮、实时预览、PDF导出等功能
* [PlantUML](https://marketplace.visualstudio.com/items?itemName=jebbs.plantuml) `jebbs.plantuml` 提供PlantUML支持
* [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode) `esbenp.prettier-vscode` 通过将代码转成AST然后进行格式化，该扩展只是提供了一个顶层抽象，针对不同的语言有不同的底层实现
* [Beautify](https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify) `HookyQR.beautify` 提供js、json、css、html格式化功能
* [Todo Tree](https://marketplace.visualstudio.com/items?itemName=Gruntfuggly.todo-tree) `Gruntfuggly.todo-tree` 支持`TODO`和`FIXME`的语法高亮，同时提供一个Tree View展示workspace中的所有TODO
* [Settings Sync](https://marketplace.visualstudio.com/items?itemName=Shan.code-settings-sync) `Shan.code-settings-sync` 将vs code配置同步到github

### SCM
* [GitLens](https://marketplace.visualstudio.com/items?itemName=eamodio.gitlens) `eamodio.gitlens` VS Code上最流行的Git扩展，支持Git Blame、Git Hisotry、Branch等所有需要的功能除了git log graph
* [Git History](https://marketplace.visualstudio.com/items?itemName=donjayamanne.githistory) `donjayamanne.githistory` 提供git log view、compare、brach、tag、merge、rabase等功能，相较GitLens缺少了blame功能，但是提供了Git Log Graph
* [Project Manager](https://marketplace.visualstudio.com/items?itemName=alefragnani.project-manager) `alefragnani.project-manager` 提供Project管理视图，支持workspace概念
* [gitignore](https://marketplace.visualstudio.com/items?itemName=codezombiech.gitignore) `codezombiech.gitignore` 支持`.gitignore`文件，同时支持从[github/gitignore](https://github.com/github/gitignore)仓库下载模板。

### Java Lang

* [Language Support for Java(TM) by Red Hat](https://marketplace.visualstudio.com/items?itemName=redhat.java) `redhat.java` Red Hat官方出品的Java语言支持扩展，底层的语言服务器是Eclipse JDT Language Server
* [Debugger for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-debug) `vscjava.vscode-java-debug` Microsoft官方出品的Java Debug Server，是基于Red Hat的Java Language Support扩展的扩展
* [Java Test Runner](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-test) `vscjava.vscode-java-test` Microsoft官方出品的Java单元测试扩展，支持Junit4.x、Junit5.x以及TestNG
* [Maven for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-maven) `vscjava.vscode-maven` Microsoft官方出品的Maven扩展，支持POM文件编辑、Maven Plugin Goals运行等功能
* [Project Manager for Java](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-dependency) `vscjava.vscode-java-dependency` Microsoft官方出品的Java Project View扩展，提供了class快速创建、Jar包导出、依赖管理等功能
* [Visual Studio IntelliCode](https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode) `VisualStudioExptTeam.vscodeintellicode` Microsoft官方出品的代码智能提示扩展
* [Java IDE](https://marketplace.visualstudio.com/items?itemName=YouMayCallMeV.vscode-java-saber) `YouMayCallMeV.vscode-java-saber` 提供部分类似Eclipse和IDEA的功能，例如创建文件、生成Getter Setter、生成Java Doc等
* [Java Decompiler](https://marketplace.visualstudio.com/items?itemName=dgileadi.java-decompiler) `dgileadi.java-decompiler` Java `.class`文件反编译扩展，依赖Language Support for Java(TM) by Red Hat扩展
* [Lombok Annotations Support for VS Code](https://marketplace.visualstudio.com/items?itemName=GabrielBB.vscode-lombok) `GabrielBB.vscode-lombok` 提供Lombok框架支持
* [Java Code Generators](https://marketplace.visualstudio.com/items?itemName=sohibe.java-generate-setters-getters) `sohibe.java-generate-setters-getters` 自动生成Getter、Setter、ToString、Equals And Hashcode、Constructor方法
* [vsc-mybatis](https://marketplace.visualstudio.com/items?itemName=niko.vsc-mybatis) `niko.vsc-mybatis` 支持Myabtis Mapper在Java文件和XML文件之间来回跳转
* [Gradle Language Support](https://marketplace.visualstudio.com/items?itemName=naco-siren.gradle-language) `naco-siren.gradle-language` 支持gradle文件语法高亮、智能提示
* [Gradle Tasks](https://marketplace.visualstudio.com/items?itemName=richardwillis.vscode-gradle) `richardwillis.vscode-gradle` grale task 运行管理

### Spring Support
* [Spring Boot Tools](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-spring-boot) `Pivotal.vscode-spring-boot` Pivotal官方出品的Spring应用程序扩展，提供对Spring Application开发的一系列支持，包含Spring注解支持、`.properties`、`.yml`文件格式高亮等
* [Spring Initializr Java Support](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-initializr) `vscjava.vscode-spring-initializr` Microsoft官方出品的[https://start.spring.io/](https://start.spring.io/)扩展，免去浏览器访问
* [Spring Boot Dashboard](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-spring-boot-dashboard) `vscjava.vscode-spring-boot-dashboard` Microsoft官方出品的Spring Boot应用程序启动入口管理界面扩展，支持Spring Boot应用程序快速启停以及Debug功能

### Servlet Support
* [Tomcat for Java](https://marketplace.visualstudio.com/items?itemName=adashen.vscode-tomcat) `adashen.vscode-tomcat` Tomcat Server管理界面，支持快速启停、debug等功能
* [Jetty for Java](https://marketplace.visualstudio.com/items?itemName=summersun.vscode-jetty) `summersun.vscode-jetty` Jetty Server管理界面，支持快速启停、debug等功能

### Linter

* [SonarLint](https://marketplace.visualstudio.com/items?itemName=SonarSource.sonarlint-vscode) `SonarSource.sonarlint-vscode` Sonar代码静态扫描扩展
* [Java P3C Checker](https://marketplace.visualstudio.com/items?itemName=Rectcircle.vscode-p3c) `Rectcircle.vscode-p3c` 阿里巴巴Java编程规范 (P3C/阿里巴巴Java开发手册) 规约检查

### Datebase
* [SQLTools](https://marketplace.visualstudio.com/items?itemName=mtxr.sqltools) `mtxr.sqltools` SQL runner、Connection Expoler等功能


## 未包含扩展集合

### 谨慎使用扩展集合
该列表中的是一些有缺陷（已不维护/很久未更新/功能不完善/某些功能有bug）的扩展，但是目前也没有能匹配的替代品，请在评估风险后使用。
* [Java Server Pages (JSP)](https://marketplace.visualstudio.com/items?itemName=pthorsson.vscode-jsp) `pthorsson.vscode-jsp` 提供JSP语法支持
    > 注意：该扩展已处于未维护状态。
* [Java Properties](https://marketplace.visualstudio.com/items?itemName=ithildir.java-properties) `ithildir.java-properties` 提供`.properties`文件语法高亮
* [redis explorer](https://marketplace.visualstudio.com/items?itemName=Pool.redisexplorer) `Pool.redisexplorer` VS Code目前唯一支持cluster的redis扩展，但是修改list、set、hash这些数据结构时有缺陷


## 参考Extension Pack
* [Java Extension Pack](https://marketplace.visualstudio.com/items?itemName=vscjava.vscode-java-pack)
* [Java Development Extensions Pack](https://marketplace.visualstudio.com/items?itemName=ricardo-emerson.java-development-extensions-pack&ssr=false)
* [Java Server Extension Pack](https://marketplace.visualstudio.com/items?itemName=SummerSun.vscode-java-server-pack)
* [Spring Boot Extension Pack](https://marketplace.visualstudio.com/items?itemName=Pivotal.vscode-boot-dev-pack)
* [Git Extension Pack](https://marketplace.visualstudio.com/items?itemName=donjayamanne.git-extension-pack)
* [Gradle Extension Pack](https://marketplace.visualstudio.com/items?itemName=richardwillis.vscode-gradle-extension-pack)

## License
This project is available under MIT License. See [LICENSE](LICENSE).