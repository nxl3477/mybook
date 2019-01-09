# Karma
Karma是Testacular的新名字，在2012年google开源了Testacular，2013年Testacular改名为Karma。Karma是一个让人感到非常神秘的名字，表示佛教中的缘分，因果报应，比Cassandra这种名字更让人猜不透！


Karma是一个基于Node.js的JavaScript测试执行过程管理工具（Test Runner）。该工具可用于测试所有主流Web浏览器，也可集成到CI（Continuous integration）工具，也可和其他代码编辑器一起使用。这个测试工具的一个强大特性就是，它可以监控(Watch)文件的变化，然后自行执行，通过console.log显示测试结果。


## 我什么时候应该使用Karma
* 你想在真实的浏览器中测试代码。
* 你想在多个浏览器（桌面，手机，平板电脑等）测试代码。
* 你想在开发过程中在本地执行你的测试。
* 您想要在持续集成服务器上执行测试。
* 你想在每次保存时执行你的测试。
* 你爱你的终端(命令行)。
* 你不想让你的（测试）生活陷入困境。
* 你想使用 Istanbul 自动生成覆盖率报告。
* 你想为你的源文件使用RequireJS。！


## 命令相关

#### 🏤初始化项目
> karma init

初始化后会在项目目录中生成一个`karma.config.js`文件，可定制化配置

#### 💉运行测试
> karma start

### 环境依赖
* 🔥**karma**
  1. karma-cli -g
  2. karma
* 📃**断言库**
  1. karma-jasmine
  2. jasmine-core

* 🌗**覆盖率**
  1. karma-coverage

* 👻**无头浏览器**
  1. phantom
   

* 👀**可视化浏览器界面**
  1. karma-phantomjs-launcher

## 安装流程指引
* [karma安装流程](../code/karma-demo/安装流程.md)
