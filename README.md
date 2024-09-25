# study_daily
## week1(只是叫week1，具体持续时间视各位完成情况)
### 学习目标
* 搭建起基本的开发环境
* 初步使用提高效率的开发工具
### 具体任务
#### 开发环境(以下部分任选其一即可，当然小孩子才做选择，大人全都要)
* 下载个IDE
  这个方法最简单了，也就不多介绍了，各位书上提到的vitual C++6.0现在叫virtual studio ，没错，教科书推荐各位用1998年的IDE
* vscode + MinGW
  vscode只是一个开源的文本编辑器，定位类似记事本，但是它搭配上各种插件就变成超级IDE了，你可用它写任何语言
  各位在windows上运行c程序需要编译器，vscode没有内置，所以各位需要自行安装，minGW是一个开源项目，将gcc编译器移植到windows平台，自行搜索解决即可
* vscode + wsl
  没什么比GNU更cool的事情了，你的linux之旅不必等到高年级的选修课才开始，无穷无尽有趣的自由软件等着各位来探索...你敢相信安装软件只需要输入一条命令么？
  vscode安装wsl扩展后即可连接linux子系统，这也太好用了吧
#### 学习并使用的工具
* vim
  vim是一个文本编辑器，其宗旨是不使用鼠标，单纯依靠键盘来完成全部操作，vim用的好的人那真是键盘敲的劈里啪啦，增删改查快得飞起，学习使用vim主要还是它太常用了，一般在服务器编辑文件都是vim或者vi，
  当然，vim也可以像vscode那样用各种扩展配置成超级IDE，各位有兴趣自行探索，推荐一个开源项目叫lazyvim
  如果你刚开始接触vim，可以在linux终端下输入vimtutor来完成这个vim入门小游戏
* git
  git是一个版本控制工具，简单来说就打游戏存档，啥时候bug多到改不过来了回个档，多人协作的时候方便分工，这个系统学习可以参考[The Missing Semester of Your CS Education](https://missing-semester-cn.github.io/2020/version-control/),简单使用会克隆提交就行了
* shell
   终端里面也运行了一门语言叫shell，windows有powershell，linux的多了，bash,zsh,fish...各位刚下载linux使用的一般是bash，用shell可以执行各种操作，就像各位用鼠标操作文件一样，其实这才是计算机最开始的交互模式，图形化是后来才有的
   如果你刚开始接触linux，那么[linux101](https://101.ustclug.org/)会帮到你很多
* 使用编译器编译源代码
  推荐在linux环境下使用gcc，想玩的花点的同学可以使用make或者cmake这种工具，什么？你怎么知道我的linux本来没有这个东西,然后我一句话给它装好了
### 参考文献
* 主要依照The Missing Semester of Your CS Education,将一些可能需要的开发工具融入日常学习使用，提高效率
  
* 其它
