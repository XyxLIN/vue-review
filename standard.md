### 前端开发规范

在开发过程中，代码规范是及其重要的, 为以后的更新维护带来极大的便利！

GP8国际经济贸易科技互联有限公司 - 前端组长 （7）

需要制定一套规范，达到200人写代码合起来和一个人写的一样。

规范类型：

1. 项目结构... 

2. 开发环境 ... gulp / webpack ... 

3. 工作规范

    git 使用规范  分支命名....

    周报 / 日报....

    文档编写规范 （ 接口开发文档，需求文档，测试文档 ... 交接文档 ） 

4. 代码规范

    HTML：

    [命名](https://wenku.baidu.com/view/57fd7af4f12d2af90242e6fb.html)

    CSS:

    scss...  base.scss reset.scss ; mixins.scss, common.scss, .....


    HTML和CSS命名，采用BEM命名规范

    [参考文献](https://wenku.baidu.com/view/57fd7af4f12d2af90242e6fb.html)

    BEM的意思就是块（block）、元素（element）、修饰符（modifier）,是由Yandex团队提出的一种前端命名方法论。这种巧妙的命名方法让你的CSS类对其他开发者来说更加透明而且更有意义。BEM命名约定更加严格，而且包含更多的信息，它们用于一个团队开发一个耗时的大项目。

    BEM规范，要求我们对元素的命名应该将其根据意义拆分成最多三个部分，最少一个部分

    连接element的时候，用__,连接modifier的时候，用--....

    



    JAVASCRIPT： 

    变量命名规范：

        全局变量： var banner_bullets =...; var comment_list_content = ....

        局部变量： let _selector = ... ; let _options_default = ....

        dom    :  let o_div = ....;

        常量   ：  const INCREMENT = ...; const INCREMENT_NUMBER = ....

        函数命名： getUserInfo () {  } ...

        类     ： class ProductDetail {  } ...

    编写规范：

        推荐大家遵循  ESLint规范  

        [简要规范说明] (https://www.cnblogs.com/ignacio/p/6908679.html)