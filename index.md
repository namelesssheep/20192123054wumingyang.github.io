# github的初使用
###### github的注册
***1.如何打开github***
在浏览器搜索github或者直接输入https://github.com/进入官网
进入之后会显示这个画面!![捕获2](https://user-images.githubusercontent.com/94816263/142983728-d70b194f-69db-4dcf-8747-6217a39b4272.PNG)

点击右上角sign up进行注册
填写用户名注册邮箱和密码

![捕获3](https://user-images.githubusercontent.com/94816263/142984313-a2b4d759-4967-4c0b-b2c1-646dd0d366ab.PNG)

![捕获2](https://user-images.githubusercontent.com/94816263/142983880-355bc6a9-f2f3-4de3-a340-9fcde68481ef.PNG)

**昵称:昵称要合法且没有被他人使用过,如果被使用过会出现Username is already taken.只能换一个昵称注册,昵称只能出现字母、数字、短横线，不能使用下划线。并且开头也不能使用短横线(-).也不能使用中文昵称.**

**邮箱:要填写合法邮箱，并且是未在 GitHub 注册过的邮箱，否则会弹出错误提示.**

**密码:至少7个字符,它会提示你安全程度,越复杂越安全,但前提要记得住!!**

![4](https://user-images.githubusercontent.com/94816263/142983925-af0191fe-fdfe-42ab-a8d6-dc885a21100a.PNG)


注册完成后会提示你验证邮箱,登录你的邮箱以后查看验证码,填写验证码完成验证.
以上步骤都完成了以后点击sign in登录你的GitHub账号



***2.开始建库***

点击左边上方绿色的new符号

![5](https://user-images.githubusercontent.com/94816263/142983994-730ce112-6ba6-40db-aff6-35964115fe38.PNG)


弹出create repository 这个界面,创建名字,接着选择public(公开的)或者private(私人的),最后点击最下方的create repository,就完成建仓库啦!

![6](https://user-images.githubusercontent.com/94816263/142984061-b3dace41-5d1a-4c0d-8336-92b297da7b61.PNG)


***3.仓库的文件上传***

新建一个仓库,和上面那个步骤一样.创建完以后,显示这个界面

![6](https://user-images.githubusercontent.com/94816263/142984121-7d3d863a-d05f-4f4b-a666-81b6146bd335.PNG)


点击第二行的README按钮,然后什么都不用填,点击最下面的commit new file

![7](https://user-images.githubusercontent.com/94816263/142984147-fac0ce82-a439-4f8a-9501-f678485ee634.PNG)
![8](https://user-images.githubusercontent.com/94816263/142984181-f9ac2830-9d8a-4003-8fd9-874bf3c30c78.PNG)


然后点击add file,选择upload file.

![9](https://user-images.githubusercontent.com/94816263/142984232-302bb7c9-24e3-4598-8fb1-7d61484cde15.PNG)
![10](https://user-images.githubusercontent.com/94816263/142984245-5bedc751-a993-4658-b99d-58dedeac8a18.PNG)


选择choose your files就可以上传图片等文件,最后点击commit changes就完成上传了.

![11](https://user-images.githubusercontent.com/94816263/142984263-b7ffad42-5b97-48f5-9c30-33b09fdb4c4f.PNG)


***4.仓库的文件下载***

一步先在GitHub上找到你要下载的东西，第二步就是下载东西,在左上方search处搜索自己要下的东西点击clone or download 选择download zip就可以了.

# 5.github用例图
***1.情景说明:***

GitHub是一个面向开源及私有软件项目的托管平台，因为只支持git作为唯一的版本库格式进行托管，故名GitHub。简单来说，GitHub是一个代码托管云服务网站，帮助开发者存储和管理其项目源代码，且能够追踪、记录并控制用户对其代码的修改。甚至你可以简单粗暴的把它当作一个网盘，用来存储任何东西。

***2.确定参与者***

系统主要有三类参与者,分别是用户,管理员与信用github数据库系统,其中用户包括游客与注册用户,表示为参与者的泛化关系.

***3.确定用例***

在本系统中,游客可以注册账号查看git hub主页；注册用户可以登录、注册、new、New repository (project)、Import repository、new organization、new gist、your profile、your codespaces、your gists、Your stars、already、your project、Upqrade 、your repositories、feature preview、help、settings、sign out、下载、上传、查询、修改代码、删除、搜索其他用户公开资源代码、留言、下载代码、查看库等；管理员可以维护数据库、用户管理等；github数据库系统可以存储用户数据等。

![确定参与者](https://user-images.githubusercontent.com/94816263/142986607-ff57f968-06cf-4fa1-9e1a-c49dd42a401c.jpg)

![确定用例](https://user-images.githubusercontent.com/94816263/142986634-5ca46ebb-09b8-4b83-ac1f-7daa100c118d.jpg)

![系统最终用例图](https://user-images.githubusercontent.com/94816263/142986643-d9237e8f-ebdc-4299-80c8-4405ef403a84.png)

***用例图说明（部分）***

![@9T~(G1832UR_B%U$PTG6WV](https://user-images.githubusercontent.com/94816263/142987943-9740333c-3016-41c6-903d-4f6071f62653.jpg)
![`A80 E494V68V`S 2D Q{C2](https://user-images.githubusercontent.com/94816263/142987956-de69c603-dd83-4834-9a81-cbb600de7859.jpg)
![JMT3L B`010Z7U{KS9L4TK8](https://user-images.githubusercontent.com/94816263/142988084-bfa795a2-4016-4ccd-8147-0799aed2bccb.jpg)


# 遇到了一个大问题

***图片上传了在网页打开时无法显示***

在学习使用GitHub中，查询了如何上传图片，网上教程上面说的时候，新建一个仓库，然后上传图片就可以了，写博客的时候就可以复制仓库图片的链接使用那张图片，但是写完博客了以后再打开博客，就只能先是文字不能显示图片，根据网上教程，说是域名污染问题，但是修改了文件也无济于事，甚至连github都无法打开。和同学讨论了以后发现只要复制图片在写博客的时候粘贴就可以了就可以自动生成图片的代码和地址，最终解决了这个问题，github还是很人性化的！！！

# 通信图和顺序图的简单实践


上述内容简单说明了用例图以及对github的初步分析，经过半个月时间的学习后，掌握了通信图和顺序图。此次便针对github的三个功能：（1）Repositories(仓库)项目代码托管功能；（2）版本管理功能；（3）代码查找功能。进行简单的业务分析，并绘画出通信图和顺序图，接下来就让我们一起来康康成果吧！

# Repositories(仓库)项目代码托管功能
仓库托管功能顺序图：
建模思路及流程
首先先确定参与交互的对象。该交互由用户发起，因此作为参与者是这个交互过程的发起者，然后以此调整好对象顺序（用户，登陆界面，后台数据库，用户界面，仓库，git托管，工作区，暂存区，本地区）。
![image](https://user-images.githubusercontent.com/94336132/145986382-940fa966-8dce-45e6-924f-83a69da8c1f9.png)

 在添加消息的传递，以传递的消息从而添加激活。 
![image](https://user-images.githubusercontent.com/94336132/145986477-59d94e6b-e972-483d-8bbf-a6a1adccb2ff.png)

从图中不难得出：用户通过自己注册的github账号登录后，可以新建仓库，在新建的仓库中可以添加代码，并对添加的代码进行修改、删除等操作，同时可以通过git代码托管进行管理自己的代码。可以编辑代码，临时存储代码，或者把代码存在本地，在代码版本跟新时也会同步修改你的代码


仓库托管功能通信图：
建模思路及流程
首先先确定参与交互的对象。参与该用例交互过程的对象有
用户，登陆界面，用户界面，仓库管理界面（仓库存储，仓库管理），代码管理界面（版本更新，本地存储，临时存储，编辑代码）。 
![image](https://user-images.githubusercontent.com/94336132/145987636-6659cd4b-ebdf-452b-9b6d-7c3969347595.png)

确定参与交互的对象之后，在有联系和消息传递的对象之间添加链。 
![image](https://user-images.githubusercontent.com/94336132/145987686-f61e70a1-129b-4692-8e7c-2c63f2b27470.png)

最后再在链上按顺序添加消息。
 
![image](https://user-images.githubusercontent.com/94336132/145987740-28927b04-07b5-4773-b9d6-4487cfa0b880.png)

梳理出对象之间发送消息的顺序如下：用户登录后发出创建仓库请求消息，创建新仓库后可以创建新项目，仓库可以存储代码和管理代码，通过用户写入代码可以存储，用户修改也可以，也可以用git管理代码，可以跟新代码版本，编辑代码等操作。


# 版本管理功能

版本管理功能顺序图：
建模思路及流程
首先先确定参与交互的对象。该交互由用户发起，因此作为参与者是这个交互过程的发起者，然后以此调整好对象顺序（用户，本地版本库，权限控制，远端仓库，数据备份，版本管理，历史记录）。
 ![image](https://user-images.githubusercontent.com/94336132/145988785-7bfb0614-d96e-4e22-b1b2-b46bf9ede6e7.png)

再添加消息的传递，以传递的消息从而添加激活。
 
![image](https://user-images.githubusercontent.com/94336132/145988852-4c614424-bb4b-40de-8709-99b66732992e.png)

其交互过程如下：用户通过本地版本库向权限控制功能模块申请修改权限，权限控制功能模块权限获取成功后，本地版本库会与远端仓库进行连接，远端仓库就会收到本地版本库当前版本信息，并之后向数据备份功能模块传输当前版本信息。并把当前版本信息录入历史记录模块。最后远端仓库与版本管理模块进行功能比对，之后版本管理功能模块将最新版本信息内容发送到远端仓库.最后由远端仓库发送给本地版本库进行更新.


版本管理功能通信图：
建模思路及流程
首先先确定参与交互的对象。参与该用例交互过程的对象有
用户，本地版本库函，权限控制界面，远端库，版本管理界面（协同修改，数据备份，分支管理，历史信息查询）。
![image](https://user-images.githubusercontent.com/94336132/145988952-6442bb27-f617-4879-9bde-c38c2a1711db.png)

 确定参与交互的对象之后，在有联系和消息传递的对象之间添加链。 
 ![image](https://user-images.githubusercontent.com/94336132/145988970-d4e93eac-ba20-4f9d-8df6-c8b58d74d3d8.png)

最后再在链上按顺序添加消息。
 ![image](https://user-images.githubusercontent.com/94336132/145988997-1ba48ff9-a3d2-402c-9d6d-71dcb8d3602e.png)


梳理出对象之间发送消息的顺序如下：用户通过本地版本库像权限控制模块申请修改权限的消息，通过申请则像远端仓库进行发送连接的消息，然后远端仓库与本地版本库建立联系，之后远端仓库像版本管理功能模块发送核对版本信息，核对完成之后版本管理功能模块向远端仓库发送新版本信息内容，用户可通过版本管理来使用协同修改，数据备份，分支管理，历史信息查询功能。


#  代码查找功能

代码查找功能顺序图：
建模思路及流程
首先先确定参与交互的对象。该交互由用户发起，因此作为参与者是这个交互过程的发起者，然后以此调整好对象顺序（用户，Github用户界面，代码查找界面，公开代码显示界，代码详情）。 
![image](https://user-images.githubusercontent.com/94336132/145989191-3bb35c6d-d32a-44b6-ae24-fe49462bce22.png)

在添加消息的传递，以传递的消息从而添加激活。
 ![image](https://user-images.githubusercontent.com/94336132/145989229-19bd2abc-f1c1-4aeb-945a-790c4ead7df7.png)

其交互过程如下：客户登录后进入Github用户界面，通过Github用户界的代码查找界面通过关键词搜索公开代码，在公开代码显示界面用户可以点击代码即可查看代码详情。



代码查找功能通信图：
建模思路及流程
首先先确定参与交互的对象。参与该用例交互过程的对象有用户，Github用户界面，代码查找显示界面。 
![image](https://user-images.githubusercontent.com/94336132/145989275-31bb89bd-e9b9-449b-830a-78605aa0e978.png)

确定参与交互的对象之后，在有联系和消息传递的对象之间添加链。 
![image](https://user-images.githubusercontent.com/94336132/145989317-3f4f4941-d759-4165-8eee-0025e7bd46fe.png)

最后再在链上按顺序添加消息。
![image](https://user-images.githubusercontent.com/94336132/145989345-0f76677f-5af3-4427-826e-80b84e27c781.png)

 
梳理出对象之间发送消息的顺序如下：用户申请登录的消息，然后进入Github主界面，点击搜索界面，可以在搜索界面按条件查找代码，发送了查找的消息，到达公开代码显示界面，点击想要查找的代码发送了信息，可以查看代码内容。





