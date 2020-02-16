# HttpRunner实践

## 参考资料
1. [HttpRunner V2.x 中文使用文档](https://cn.httprunner.org/)


## 环境安装
    1. 安装Python3.4及以上版本，推荐用[Anaconda](https://www.anaconda.com/)来对Python进行版本以及包的管理
    2. 启动一个Anaconda环境并执行 `pip install httprunner`
    3. 执行 `hrun -V` 和 `har2case -V`，如正常输出，则说明已安装成功
*如有疑问可参考[安装说明](https://cn.httprunner.org/Installation/)*


## 基本概念
    1. 接口
    就是平时我们所说的接口，例如Dubbo接口，HTTP接口等，在HttpRunner的概念层次中，它是最基本的。目前在开发阶段，我们编写的测试调试还是会以它为主

    2. 测试用例
    一个测试用例由若干步骤构成，每个步骤中可以引用我们定义好接口。测试用例的编写最重要的一个原则就是：能够独立运行，不存在对别的测试用例的依赖

    3. 测试场景
    就是测试用例的集合
简而言之，测试场景包含若干测试用例，测试用例由若干测试步骤组成，每个测试步骤可以引用接口
*更加详细的叙述可参考[名词解释](https://cn.httprunner.org/concept/nominal/)和[测试用例分层](https://cn.httprunner.org/prepare/testcase-layer/)*



## 通过目录结构来看一下




## 规范