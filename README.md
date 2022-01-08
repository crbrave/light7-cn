# light7 - a light H5 UI lib for webapp
[![Join the chat at https://gitter.im/lihongxun945/light7](https://badges.gitter.im/lihongxun945/light7.svg)](https://gitter.im/lihongxun945/light7?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
[![npm version](https://img.shields.io/npm/v/light7.svg)](https://www.npmjs.com/package/light7)

简单易用的h5 UI库，是从 [SUI Mobile](https://github.com/sdc-alibaba/SUI-Mobile) Fork 出来的一个版本。 官网地址： [http://www.light7.org/](http://www.light7.org/)


**中文官网已备案通过，地址 [http://light7.cn/](http://light7.cn/) **

# 下载

建议下载源码自行编译。如果不想编译，你也可以直接切换到 `build` 分支，这个分支包含全部的编译后的JS,CSS和文档。或者直接点击 [这里下载](https://github.com/lihongxun945/light7/archive/build.zip).

# grunt 配置

- Install `grunt` first, see [Grunt](http://gruntjs.com/) for how to install and use grunt, if you have never used grunt before.
- Then, run `npm install` under the root dir of this repo. This command will install the nodejs packages required by grunt.
- Now, you can run `grunt` to compile the source file.


# 离线文档


你可以直接在nginx之类的服务器中打开 `_site` 目录。
安装ruby链接 https://rubyinstaller.org/downloads/ 版本需要是3.0之前 如2.7  需要带 WITH DEVKIT
或者执行 `jekyll serve` 打开本地服务器. 如果你的系统中没有ruby，请先[安装ruby](https://www.ruby-lang.org/en/documentation/installation/)。然后再安装 `jekyll` 和 `rouge` （执行 `gem install jekyll` 和 `gem install rouge`）。
如果发现 `gem install` 失败，可能是因为 gem 服务器被和谐，参考[淘宝gem镜像](https://ruby.taobao.org/)

# 兼容性

兼容 iOS 6+，Android 4.0+


# 联系方式

- 请加QQ群 255389987
- 有比较丰富的手机H5开发经验且对这个项目感兴趣的同学可以加群，然后加群主联系。

# 关于作者

前知乎前端工程师，前阿里巴巴国际UED前端, 在阿里主要负责 [SUI Mobile](https://github.com/sdc-alibaba/SUI-Mobile) 和 [Framework7-Plus](https://github.com/sdc-fe/Framework7-Plus) 以及 [Framework7](http://framework7.taobao.org/) 。博客地址：http://blog.csdn.net/lihongxun945?viewmode=contents。

# 关于 f7, sui 和 light7

很多人没搞清楚这三者的关系。

F7 是国外大神写的一个UI库。SUI 是我在阿里的时候基于F7改造的，主要是提升兼容性以及更轻量化。

现在因为离职了，不方便继续改阿里的东西。 所以从SUI fork出了一个新的 light7。以后我个人只会维护 light7, SUI 属于阿里巴巴国际UED团队。

*尊重版权，上述提到的 SUI Mobile & Framework7-cn 版权均归阿里巴巴国际UED团队*。
