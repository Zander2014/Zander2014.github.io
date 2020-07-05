---
title: 使用GitHub搭建自己的Blog
description: 大家好，我是一个小马农，相信大家在打开我这华丽的博客时，就已经迫不及待的想问"哥，这是怎么弄的，太炫了，花了多少钱？我也想整一个。"

别急嘛大兄弟，今天你既然来了，哥也知道你的心思，这就慢慢的给你道来，这个炫酷的blog不花一分钱，动动手指，你就拥有。
categories:
 - blog
tags:
---

# 写在前面的废话

大家好，我是一个小马农，相信大家在打开我这华丽的博客时，就已经迫不及待的想问"哥，这是怎么弄的，太炫了，花了多少钱？我也想整一个。"

别急嘛大兄弟，今天你既然来了，哥也知道你的心思，这就慢慢的给你道来，这个炫酷的blog不花一分钱，动动手指，你就拥有。

# 关于Github Pages

就是这个啦，Github Pages，我们用它提供的服务来搭建自己的博客，它就相当于一个免费的服务器。

- **好处**：

  完全免费、不需要维护、随意DIY主题，默认Https，可绑定自己的域名，总之简单的操作之后，你只管写你的文章就好。

- **限制：**

  仓库（也就是你的网站）不要超过1G，不要频繁提交更新（<=10次/小时），每个月带宽上限100G。总之作为一个小型个人博客来说完全够用，如果不够用，那么恭喜你已经小有成就，花点钱自己搭建的服务也是小case了。

# 关于Jekyll

有了服务器，我们用什么来写自己的blog界面呢？以前用过WordPress或者其他前端框架的都知道，要有一个框架来写，要不然自己纯手工造轮子有多麻烦。

当当当当！**Jekyll**就是这样一个框架啦，可以去官网([中文](http://jekyllcn.com/)/[English](https://jekyllrb.com/))自行学习如何搭建环境、创建网站、寻找模板资源等等。

#### 好处：

Github Pages原生支持的框架，生成的是纯静态网站，上手简单，出问题会少一点，解决问题也会快一点。除了官网的资源外，还可以在Github上找到很多开源的模板（怎么找？当然是搜关键字找啦！每个人的口味都不一样，我就不举例子了）。

#### 限制：

其实也没什么限制，就是官网的模板说实话，风格偏国外风，想挑出几个能接受的还真不多，当然我们也可以选择其他静态模板框架，比如[Hexo](https://hexo.io/zh-cn/)、[Hugo](https://www.gohugo.org/)、[Pelican](https://www.pelican.com/us/en/)、[Gridea](https://gridea.dev/)，使用方法可以参考官方的，也可以自己搜一些博客学学，再或者找一些[H5模板](https://html5up.net/)也可以。

# 关于NexT

[NexT](https://simpleyyt.com/jekyll-theme-next/)，就是我这个网站选择的一个Jekyll的模板，它之前有hexo的版本，后来改写了Jekyll的版本，这个模板的风格相信大家现在已经看到了，话不多说，想自己搭建的就去[官方教程](http://theme-next.simpleyyt.com/getting-started.html#search-system-algolia)看看，剩下的人，跟我走。

# 开始搭建Blog

### 登录github

什么？你还没有这个**大型同性交友网站**的账号？没有注册过的同学抓紧去[官网](https://github.com/)注册，并登录。

有关注册时相关信息的填写，以及登录后个人信息的补全，就不一一介绍了，相信每天上网的你们，都开始要搭建自己的博客了，这些流程已经烂熟于心了。

### 新建Repository

1. ##### 选择New repository

   页面右上角有个"+"号，点击后在弹窗中选择New repository

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704105110504.png" alt="image-20200704105110504" style="zoom:50%;" />

2. ##### 填写Repository name

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704112057813.png" alt="image-20200704112057813" style="zoom:30%;" />

   **注意：**填写1处的Repository name，格式为xxx.github.io，xxx就是你的用户名，比如我的就是Zander2014.github.io，xxx必须和你的用户名匹配，也就是说，一个账户只能在Github上创建一个blog仓库。

   然后点击2处的Create repository按钮，仓库就创建成功了。

### 进入Setting设置GitHub Pages

1. 不出意外的话，界面会自动跳到你的仓库首页，此时选择Setting界面。

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704112646144.png?lastModify=1593922858" alt="image-20200704112646144" style="zoom:50%;" />

2. 然后往下翻，会看到GitHub Pages，点击Choose a theme

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/1.jpeg?lastModify=1593922858" alt="img" style="zoom:50%;" />

3. 进入主题界面，选择一个自己喜欢的主题（其实没几个主题，相信你都不会喜欢，先随便选一个看的过去的吧一，后面再替换自己喜欢的模板），点击Select Theme

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704114529056.png?lastModify=1593922858" alt="image-20200704114529056" style="zoom:50%;" />

4. 随后跳转到一个界面，然后往下翻，点击Commit changes

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704114814452.png?lastModify=1593922858" alt="image-20200704114814452" style="zoom:50%;" />

### 查看blog

到此你的网站就搭建好了，直接访问你之前填写的地址就好了，比如我的zander2014.github.io

<img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704120056950.png" alt="image-20200704120056950" style="zoom:50%;" />

然后在自己的Github->Code界面写自己的文章就好了

此处只是一个讲解的例子，便于理解github上文件是什么回事，可以跳过

1. 比如我点击Add file，这里可以选择直接创建(Create new file)或者上传文件(upload files)，我选择直接创建一个，会跳到一个编辑界面，

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704121009196.png" alt="image-20200704121009196" style="zoom:30%;" />

2. 然后随便写点东西，起名test.html，文件内容支持markdown文件格式（md规则需要自己学习一下，也可以下相关软件，操作更方便），点击页面下面Commit new file按钮，回到首页，看见多了一个test.html的文件

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704120508826.png" alt="image-20200704120508826" style="zoom:30%;" />

3. 此时我们在浏览器访问zander2014.github.io/test.html

<img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704121349603.png" alt="image-20200704121349603" style="zoom:50%;" />

大概知道是什么意思了吧，GitHub->Code界面，就是你Zander2014.github.io的根地址，默认会访问index.md，剩下的就是你怎么创建文件的目录结构，怎么访问就好了。

# 网站同步

手动创建上传文件，我们会怀疑人生的，而且还没办法控制版本，所以我们需要借助**版本控制工具去管理**，其实就是用**Git**，对Git不熟的同学快去[官网](https://git-scm.com/)，或者[大神的网站](https://www.liaoxuefeng.com/wiki/896043488029600)去学习。

那么操作方式也有两种：

- 命令行（需要先安装好git环境，然后在终端使用git命令，大神一般都用这个）
- 客户端（也就是图形界面的方式管理命令，小白一般都用这个）

### 命令行方式

1. 打开Terminal(终端)，进入你自己想存放网站的目录（比如我就在我的用户主目录）

2. 新建一个目录，用来存放我的网站仓库（比如我创建一个blog），进入blog目录

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/截屏2020-07-04 下午12.32.13.png" alt="截屏2020-07-04 下午12.32.13" style="zoom:50%;" />

3. 克隆我的网站仓库到blog目录

点击Code按钮，弹框中2处，可以切换使用https还是ssh的方式，然后点击3处的图标复制地址。

<img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704123046772.png" alt="image-20200704123046772" style="zoom:50%;" />

因为ssh涉及到[创建密钥和添加密钥](https://docs.github.com/cn/github/authenticating-to-github/connecting-to-github-with-ssh)的一些步骤，我们就使用https的地址，使用简单，``git clone https://github.com/Zander2014/Zander2014.github.io.git``

<img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200705114901940.png" alt="image-20200705114901940" style="zoom:50%;" />

在我们克隆好的目录中，我们可以创建文件，提交文件等等，主要用到的命令无非就是下面几个：

``git add（添加文件到本地仓库）``

``git commit（提交文件到本地仓库）``

``git push（推送本地仓库文件到远程仓库，也就是传到github上）``

``git pull（从远程仓库拉取文件到本地仓库）``

### 客户端方式

官方客户端 https://desktop.github.com/

其他客户端，比如[Sourcetree](https://confluence.atlassian.com/get-started-with-sourcetree/)等。

这些客户端都有图形界面，有入门教程，很简单，照着学一学就会了。

# 安装NexT

1. 确保已安装`Ruby 2.1.0` 或更高版本：

   ```
   $ ruby --version
   ```

   如果没安装过，使用homebrew去安装，执行``brew install ruby``

   如果homebrew安装很慢的话，可能是资源的问题，使用镜像资源会快很多，[使用方法](https://segmentfault.com/a/1190000021360086)

2. 安装`Bundler`：

   ```
   $ gem install bundler
   ```

   如果报错 

   ``ERROR:  While executing gem ... (Gem::FilePermissionError)
       You don't have write permissions for the /Library/Ruby/Gems/2.6.0 directory.``

   这是权限问题，我们可以直接在命令前加sudo，``sudo gem install bundler ``

3. 下载 NexT 主题：

   ```
   $ git clone https://github.com/Simpleyyt/jekyll-theme-next.git
   //可以用命令clone到本地，也可以直接下载项目
   ```

   因为我们已经创建好了自己的仓库，所以我们把下载好的NexT资源，全部拷贝到我们的仓库目录中去，拷贝到同级，会覆盖之前的一个_config.yml文件，选择替换，也就是像下面这样，

   <img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704222606726.png" alt="image-20200704222606726" style="zoom:30%;" />

   然后进入我们的仓库目录

   ```
   $ cd Zander2014.github.io
   ```

4. 安装依赖：

   ```
   $ bundle install
   ```

5. 运行 Jekyll：

   ```
   $ bundle exec jekyll server
   ```

此时即可使用浏览器访问 `http://localhost:4000`，检查站点是否正确运行。

之后把代码提交到远程GitHub仓库，就可以在浏览器输入zander2014.github.io看见了



**如果需要使用其他模板的话，每个资源都有他们的使用方法，具体参考模板的教程就可以了，大致流程一样，下载资源、替换资源、运行就好了**



# 写Blog

现在你只需要找一个趁手的 Markdown 编辑器：[Typora](https://typora.io/)、[熊掌记](https://bear.app/cn/)、[印象笔记](https://www.yinxiang.com/)、[zen](https://zen.unit.ms/)、[有道云笔记](http://note.youdao.com/WAP/intro/)、[Ulysses](https://ulysses.app/)。

在电脑上编辑你的文章，然后放到仓库项目中的 _posts 文件夹里，并使用前面提到的两种方式将文章同步到 GitHub 上即可。

**注意：**

- **文件格式：**年-月-日-标题.markdown

- **文章内容顶部**：必须有下面的 YAML 头信息：

  ```
  ---
  layout: post
  title: Blogging Like a Hacker
  ---
  ```


# 一些问题

### 本地图片

我们在md软件插入一张图片，会根据软件的设置(我使用的是Typora，设置图片存放在文章同级目录下的同名.assets下)，src=图片的相对路径

```html
<img src="使用GitHub搭建自己的Blog.assets/image-20200704105110504.png" alt="image-20200704105110504" style="zoom:50%;" />
```

此时我们在Typora中看到是没问题的，但当我们部署jekyll本地服务后，打开我们的文章

``http://127.0.0.1:4000/blog/xxx``发现图片都显示，当然不会显示，因为服务器找不到我们的图片。

我们可以选择把本地的图片文件夹复制一份到服务器资源文件中Assets，然后使用

```html
<img src="{{site.url}}/assets/imgs/使用GitHub搭建自己的Blog.assets/image-20200704105110504.png" alt="image-20200704105110504" style="zoom:50%;">
```

这样图片就能正常显示了，``site.url``是在_config.yml中配置的url，指向的也就是根目录。

可是这样只能在本地Typora显示，或者在服务器显示，总之还是有不少问题，改图片路径也麻烦。

最方便的是选择第三方的图床工具，也就是我们把图片上传上去，然后使用他们提供的图片网络地址：如http://xxx.jpg，这样肯定在哪都能正常访问，但是是需要付费的

可以在这里找一些图床来做[盘点国内免费好用的图床](https://zhuanlan.zhihu.com/p/35270383)

目前我没有使用图床工具，麻烦就先麻烦一点吧，日后觉得不方便再解决图床的问题。

### 绑定自己的域名

目前我还没有绑定域名，需要自己到阿里云或者万网申请自己的域名，这个当然是付费的，然后和Github Pages的地址绑定在一起，就可以直接使用自己的域名来访问博客了，更炫酷一点。而且七牛云这些图床工具，也是需要备案域名来提供稳定服务的，后续都还是弄一下比较方便。