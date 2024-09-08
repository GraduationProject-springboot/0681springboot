# [首页查询更多项目](https://github.com/GraduationProject-springboot) 包安装运行


# 0681springboot原创歌曲分享平台--论文

![picture](https://raw.githubusercontent.com/GraduationProject-springboot/.github/main/img/wx.png)

### 点击播放视频 ▼
[![Watch the video](https://i.sstatic.net/Vp2cE.png)](https://www.bilibili.com/video/BV14HerezEwW?p=35)


# 绪论
## 1.1课题背景
随着科学技术发展，电脑已成为人们生活中必不可少的生活办公工具，在这样的背景下，网络技术被应用到各个方面，为了提高办公生活效率，网络信息技术飞速发展。在这样的背景下人类社会进入了全新的信息化的时代。原创歌曲分享信息管理一直是信息管理的一大难题，原创歌曲分享数量多，此时寻找有效便捷的原创歌曲分享信息管理方法就是当务之急。而日趋成熟的计算机信息管理技术便成为解决这一难题的唯一之选。如今计算机信息管理技术来处理原创歌曲分享信息管理早已游刃有余，其实信息管理技术已经渗透到各个行业的信息控制管理当中，且有着举足轻重的地位。而随着现代化社会主义不断进步，普通群众生活水平有了大幅提高，很多方面都在网络上去实现，从而网络也就成为了最直接、即方便又快捷的接入口。

使用原创歌曲分享平台相对传统歌曲分享信息管理方式具备很多优点：首先可以大幅提高原创歌曲分享信息检索，只需输入原创歌曲分享相关信息就能在数秒内反馈想要的结果；其次可存储大量的原创歌曲分享信息，同时原创歌曲分享信息安全性有更高的保障；相比纸质文件来管理原创歌曲分享信息，原创歌曲分享平台更节省空间人力资源。这些优点很大程度提高了运营效率并节约了运营成本。因此，原创歌曲分享平台对原创歌曲分享信息非常必要进行有效管理，不仅提高了原创歌曲分享管理效率，增加了用户信息安全性，方便及时反馈信息给管理员，增加了与管理员之间的互动交流，更能提高大家的体验强度。

平台为了数据库结构的灵活性选择MySQL来设计，而java技术，B/S架构则保证了较高的平台适应性。本文主要介绍了平台开发背景，需要完成的功能与开发过程，说明平台设计重点与设计思想。
## 1.2课题研究现状
现今，越来越多的人乐于选择一项合适的管理方案，但是普通用户往往受到管理经验的限制，这时原创歌曲分享的崛起，大量原创歌曲分享制度进入人们生活，而原创歌曲分享平台无疑是原创歌曲分享管理的最好制度，在这样成功的管理模式背景下，不仅原创歌曲分享数量越来越多，原创歌曲分享信息也越来越多。但是随着原创歌曲分享信息的增多，原创歌曲分享的管理成为了一个难题。高效便捷地管理原创歌曲分享成为了转变管理模式，与时代兼容的当务之急。

原创歌曲分享平台，为了随时随地查看原创歌曲分享信息提供了便捷的方法，更重要的是大大的简化了管理员管理原创歌曲分享信息的方式方法，更提供了其他想要了解原创歌曲分享信息及运作情况以及挑选方便快捷的可靠渠道。相比于传统原创歌曲分享信息管理方法，这样的电子信息管理更为简洁方便，在原创歌曲分享维护信息反馈和处理原创歌曲分享意见方面也有得天独厚的优势。

原创歌曲分享平台能做到的不仅是大大简化管理员的信息管理工作，在提高原创歌曲分享管理效率的同时还能缩减开支，更能在数字化的平面网络上将原创歌曲分享最好的一面展示给用户和潜在用户，而这个平台在带给原创歌曲分享全新用户信息管理统计和分类的同时，还成为日后原创歌曲分享平台制定管理方式的重要数据参考。过程永远比结果重要。毕业设计是大学生活中最为浓墨重彩的一笔，在这个过程中不仅学到更为全面的书本和实践知识，更让我感受到了浓浓的同窗之情及师生情。这个平台成为原创歌曲分享管理者最不可或缺的内容。尽管目前大部分已经将原创歌曲分享平台投入使用，但是人们对于平台要求也变得越来越高，大部分平台已经能完美处理各类信息，但是为了更好地契合原创歌曲分享运作路线，各个要求都有所不同，个性化也是管理平台十分重要的一点，所以都希望自己能有一个个性化定制的原创歌曲分享平台，但这又涉及到成本控制问题，目前定制一个平台价值不菲，但是如果有这样一个可以根据需求自己制定页面和内容的原创歌曲分享平台就可以大大缩减开支，但是凭借目前自身技术恐怕难以实现，不过让平台可二次设计却是有可能实现的。随着原创歌曲分享规模的不断扩大，用户信息共享也成一种趋势。原创歌曲分享的发展也证明了平台管理在不断发展进步，各种理念也越来越先进，对各方面的要求也变得越来越高，原创歌曲分享完全可以在进入页面时发布各类信息进行推荐交流。
## 1.3初步设计方法与实施方案
软件体系结构方案：由于本平台需要在不同设备上都能运行，而且电脑配置要求也要越低越好，为了实现这一要求，经过考虑B/S结构成为最佳之选。使用B/S结构的平台可以几乎在任何电脑上运行，只要浏览器可以正常工作就可以正常运行该平台，而且后期维护及二次修改较为容易，符合要求。

操作平台方案：Windows10操作平台，该平台是目前微软公司推出的最新平台，目前大多数市面上的电脑都使用该平台，并且该平台功能完善，兼容性好。开发工具：选用My Eclipse。java开发技术。
## 1.4本文研究内容
本文主要划分成7大部分：

第一部分为绪论，主要介绍了目前电脑技术发展状况、原创歌曲分享行业发展阶段，分析当前原创歌曲分享平台弊端以及使用信息技术来管理原创歌曲分享信息的好处。

第二部分为相关技术简介，主要介绍了各技术的发展历程，技术发展现状，技术优点以及选用该技术的原因等。

第三部分为平台分析，主要分析了软件设计所需要的功能。

第四部分为平台设计，主要进行了平台的架构设计、数据库设计。

第五部分为平台详细设计。

第六部分为平台调试与测试，利用测试方法进行可行性测试、性能测试、平台测试等。

第七部分为总结与致谢，主要总结了程序设计的完成过程及完成情况，比对完成设计过程中施以援手的同学和老师表达中心的感谢和祝愿。
































# 2 平台开发环境
## 2.1JAVA简介
JavaScript是一种网络脚本语言，广泛运用于web应用开发，可以用来添加网页的格式动态效果，该语言不用进行预编译就直接运行，可以直接嵌入HTML语言中，写成js语言，便于结构的分离，支持多种浏览器可以在多平台下运行。它具有三个不同的体系，分别为J2SE、J2EE、J2ME。Java 语言比较容易理解，而且也容易学习和上手，其语法与C语言和C++语言很相似，它可以自动的处理废料，而且不会受到内存的影响。

Java 程序被编译后形成的class 文件，这样就能够实现在多平台中正常运行。Java语言支持多个线程同吋执行，Java程序所需要的类能够动态的或者通过网络被载入到运行环境。Java开发工具支持JavaJDK7\8,开发集成环境IDE为Eclipse。
## 2.2MyEclipse环境配置
安装完MyEclipse后选择myeclipse“Window->Preferences”

（1）配置myeclipse的jre为sun的jdk，不要用myeclipse的默认jdk：

选择“java->Installed JREs”,勾中里面的“jdk1.7”.

（2）配置编译的级别为6.0：

选择“Compiler->Compiler compliance level”的值为“6.0”。

（3）配置myeclipse的默认的文件编码格式为“UTF-8”：

`   `选择“General->Workspace”，选中“Text file encod”下面的“Other”，设置里面的值为“UTF-8”。

（4）去掉myeclipse的JSP的验证：

选择“MyEclipse->Validation”,将“Build”列的所有勾都给去掉,这样在编译时因为避免了jsp的验证，所以编译的速度会快很多。
## 2.3B/S结构简介
随着软件平台的不断改进和升级，B/S结构产品更为方便的特征体现地十分明显。对于一个中等偏大的公司来说，如果平台管理员每天要在很多台电脑之间来回查看，不断奔走，那么效率和工作量就会变得很低，但是如果使用了B/S结构，那么管理员只要对服务器进行管理就够了。

B/S结构最大的优点它不需要安装任何的软件，它所有的用户端就只是浏览器，所以只要有一台电脑并且可以上网就可以解决所有问题，用户端可以完全地不用管理员维护。无论使用平台的使用者是什么样的规模，也不管分支有多么的庞大，都不会对维护和升级的工作量造成影响，所有的维护和升级只需要操作服务器。随着B/S结构的不断发展，使用的人也不断增加，从而带动了AJAX技术的发展，和B/S结构一样，它也能在用户端上处理程序，这便缓解了服务器的负担，提高了交互性，而且实现了局部实时刷新。
## 2.4MySQL数据库
MySQL数据库使用的语言是SQL语言。MySQL在保存数据时是根据数据的类型和特征分开保存在不同的表中，这样当用户在需要调用的数据时，就不再需要花费大量时间去寻找数据了，只要找到对应的表，就可以找到需要的数据了。MySQL可以完美的实现对于数据库的基本操作。因为 MySQL 数据库的占用的内存少，运行快，成本低，源代码开放，可移植性强，所以越来越多的数据来源简单的项目的开发都会选择 MySQL作为数据库，而MySQL也变得越来越流行。

MySQL 有很多特性，如可移植性，多线程，灵活性等，在很多操作平台中都可以运行。它可以实现在多个线程并发执行的技术；支持MyISAM、innoDB、MEMORY、ARCHIVE四种存储引擎，而且可以使用大型数据库，为用户提供许多使用数据库的工具，比如建模工具，管理工具等。在 WEB方面的应用MySQL是最好的。
## 2.5SPRINGBOOT框架
SpringBoot是一个全新开源的轻量级框架。基于Spring4.0设计，其不仅继承了Spring框架原来有的优秀特性，而且还通过简化配置文件来进一步简化了Spring应用的整个搭建以及开发过程。另外在原本的Spring中由于随着项目的扩大导入的jar包数量越来越大，随之出现了jar包版本之间的兼容性问题，而此时SpringBoot通过集成大量的框架使得依赖包的版本冲突，以及引用的不稳定性问题得到了很好的解决。

SpringBoot可以看做是Spring的加强版本，但实质上都是Spring的相关技术，有了这些优秀的开源框架，程序员在开发过程中将事半功倍。



# 3 平台分析
## 3.1平台可行性分析
### 3.1.1经济可行性
由于本平台是作为毕业设计平台，且平台本身存在一些技术层面的缺陷，并不能直接用于商业用途，只想要通过该平台的开发提高自身学术水平，不需要特定服务器等额外花费。所有创造及工作过程仅需在个人电脑上就能实现，使用到的软件大多为开源软件，所以经济成本并不高，可以轻易实现。
### 3.1.2技术可行性
本平台的开发使用java作为平台开发的开发语言，而B/S结构决定了本平台的兼容性和多用户可操作性，此外选择MySQL作为数据库不仅提高了数据安全性更保障了数据的可操作性。
### 3.1.3运行可行性
本平台作为以java作为开发语言的平台，而且选用B/S结构则决定了要操作本平台仅需要占用很小的资源，并没有过多地硬件配置要求，目前市面上只要能正常运行浏览器的个人电脑都可以正常运行使用该平台。

经过总结，本平台在经济方面、技术方面、运行方面的条件都得以满足，为此平台的开发具备了可行性条件。
## 3.2 平台现状分析
平台使用用户的数量直接决定了用户信息管理者的工作量，毫无疑问，平台管理者的工作量较大较繁琐。通过总结出平台当前对用户管理的工作状态得以下分析：

(1)统筹规划，如果平台在信息化管理中不够全面，缺少综合性、平台性、整体性，那不可避免的需要投入大量人力物力来规划整理信息。引入信息化管理方式无疑可以达到节省信息管理成本的目的不仅减少资源浪费还可以使原创歌曲分享信息变得井井有条，成为市场竞争中的一大优势。

(2)要循序渐进，做事不能心急，一步一个脚印，都不可能一步到位，就算信息管理平台也一样，要让平台发挥最大效率还是应该多调研，多听取用户和管理者的意见，并进行必要的统筹规划，有组织有目的地设计平台功能，团结各个部门发挥主观能动性。

(3)信息安全措施不到位

隐私权神圣不可侵犯，这是中华人民共和国宪法赋予我们的权利，人和人都不能侵犯我们的正当权益，而网络用户信息管理存在极大安全隐患，信息泄露的案列不在少数，加强信息安全措施是完善网络信息管理过程中不可避免的一环。

(4)资源不能充分共享

资源共享是网络的一大特点，没有共享就没有社交，网络也就失去了他应有的魅力，如果能够实现用户信息共享，无疑对于医院的发展存在不可或缺的帮助。

(5)现有平台可扩展性不高。

如今科学技术发展飞速，随着而来的就是技术更新，那势必会给软件更新带来挑战，因此，平台必须具备良好的开放性和可扩充性，为了不落后于时代，这是必备特色之一。

基于上述分析，原创歌曲分享平台应该切合实际，做到确实有效，集体表现为：一是平台能够整理并集合归类用户信息，防止用户信息混乱，难以整理；二是平台要安全稳定，不能泄露用户信息，造成隐私泄露，不仅伤害用户利益更是对经营者名誉的损毁；三是平台要具有良好的开放性，不仅要方便定期的维护维修，更要方便及时增加新功能，保证先进的时代契合性。经过详细的讨论论证，确定平台的总体要求。
## 3.3功能需求分析
平台功能需求分析是通过软件开发者在参与市场调研，与原创歌曲分享管理者及原创歌曲分享交流后经过详细缜密的思考，再讨论研究后得出的初步平台开发所需实现功能。这是开发平台的开始，也是相当关键的一步，如果不在这个阶段制定平台所需模块，日后会带来不必要的麻烦。因此，必须严肃认真，全身心投入去做好这个步骤。

本平台采用从上往下的步骤开发，基本功能如下：

本课题要求实现一套原创歌曲分享平台，平台主要包括（管理员和用户）两个模块等功能。 

（1）管理员用例图如下所示：

![](/md/blog.007.png)

图3-1管理员用例图

（2）用户用例图如下所示：

![](/md/blog.008.png)

图3-2用户用例图
## 3.4平台设计规则与运行环境
软件平台的优劣很大程度上是由平台设计的完善与否决定的。世间万物都必须遵循生老病死的法则，这是大自然的规则不能违反，软件设计也一样需要遵循平台设计规则。因此，在设计过程中必须遵循平台设计规则。

规则如下：

简单性：为了扩大平台使用者的受众面，平台设计应该本着操作越简单约好的原则，这样不仅能提高平台的使用率更能够扩大平台使用面。

针对性：一个平台针对性越强，所能提供的功能必然越完善，用户体验肯定更好，所以应该明确指定平台针对性。

实用性：实用永远是检验一个平台是否成功的唯一标准，使用的语言再高端，使用的结构再新颖但不能满足管理员和用户的要求那就是失败。

运行环境：

本平台是利用B/S结构来开发的，数据库在服务器上进行部署MySQL即可。
## 3.5平台流程分析
### 3.5.1操作流程
平台登录流程图，如图所示：

![](/md/blog.009.png)

图3-3登录流程图
### 3.5.2添加信息流程
添加信息流程图，如图所示：

![](/md/blog.010.png)

图3-4添加信息流程图
### 3.5.3删除信息流程
删除信息流程图，如图所示：

![](/md/blog.011.png)

图3-5删除信息流程图



# 4 平台设计
## 4.1平台设计主要功能
通过市场调研及咨询研究，了解了原创歌曲分享平台及管理者的使用需求，于是制定了管理员和用户等模块。功能结构图如下所示：

![](/md/blog.012.png)

图4-1平台功能结构图
## 4.2数据库设计
### 4.2.1数据库设计规范
数据可设计要遵循职责分离原则，即在设计时应该要考虑平台独立性，即每个平台之间互不干预不能混乱数据表和平台关系。

数据库命名也要遵循一定规范，否则容易混淆，数据库字段名要尽量做到与表名类似，多使用小写英文字母和下划线来命名并尽量使用简单单词。
### 4.2.2E/R图
用户注册E/R图，如下所示：

![](/md/blog.013.png)

` `图4-2用户注册E/R图

音乐分享管理E/R图，如下所示：

![](/md/blog.014.png)

图4-3音乐分享管理E/R图
### 4.2.3数据表
本平台采用的是MySQL存储数据，平台中使用到的主要数据表的具体展示部分如下所示。

表4-1：举报

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yinlemingcheng|varchar|200|音乐名称|||
|fabushijian|date||发布时间|||
|shipinjianjie|longtext|4294967295|视频简介|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|jubaoyuanyin|varchar|200|举报原因|||
|liyou|longtext|4294967295|理由|||
|sfsh|varchar|200|是否审核||否|
|shhf|longtext|4294967295|审核回复|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicknum|int||点击次数||0|
|userid|bigint||用户id|||

表4-2：音乐分享评论表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|refid|bigint||关联表id|||
|userid|bigint||用户id|||
|nickname|varchar|200|用户名|||
|content|longtext|4294967295|评论内容|||
|reply|longtext|4294967295|回复内容|||

表4-3：配置文件

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|name|varchar|100|配置参数名称|||
|value|varchar|100|配置参数值|||

表4-4：用户

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yonghuzhanghao|varchar|200|用户账号|||
|mima|varchar|200|密码|||
|yonghuxingming|varchar|200|用户姓名|||
|touxiang|varchar|200|头像|||
|xingbie|varchar|200|性别|||
|nianling|varchar|200|年龄|||
|lianxidianhua|varchar|200|联系电话|||

表4-5：音乐分享

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yinlefenlei|varchar|200|音乐分类|||
|yinlemingcheng|varchar|200|音乐名称|||
|yinleshipin|varchar|200|音乐视频|||
|quyu|varchar|200|区域|||
|shipinfengmian|varchar|200|视频封面|||
|fabushijian|date||发布时间|||
|geci|varchar|200|歌词|||
|jianjie|longtext|4294967295|简介|||
|chuangzuobeijing|longtext|4294967295|创作背景|||
|yonghuzhanghao|varchar|200|用户账号|||
|yonghuxingming|varchar|200|用户姓名|||
|thumbsupnum|int||赞||0|
|crazilynum|int||踩||0|
|clicktime|datetime||最近点击时间|||
|clicknum|int||点击次数||0|
|userid|bigint||用户id|||

表4-6：音乐分类

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|yinlefenlei|varchar|200|音乐分类|||

表4-7：用户表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|username|varchar|100|用户名|||
|password|varchar|100|密码|||
|role|varchar|100|角色||管理员|
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|

表4-8：token表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|userid|bigint||用户id|||
|username|varchar|100|用户名|||
|tablename|varchar|100|表名|||
|role|varchar|100|角色|||
|token|varchar|200|密码|||
|addtime|timestamp||新增时间||CURRENT\_TIMESTAMP|
|expiratedtime|timestamp||过期时间||CURRENT\_TIMESTAMP|

表4-9：收藏表

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|userid|bigint||用户id|||
|refid|bigint||收藏id|||
|tablename|varchar|200|表名|||
|name|varchar|200|收藏名称|||
|picture|varchar|200|收藏图片|||
|type|varchar|200|类型(1:收藏,21:赞,22:踩)||1|
|inteltype|varchar|200|推荐类型|||

表4-10：音乐资讯

|字段名称|类型|长度|字段说明|主键|默认值|
| :-: | :-: | :-: | :-: | :-: | :-: |
|id|bigint||主键|主键||
|addtime|timestamp||创建时间||CURRENT\_TIMESTAMP|
|title|varchar|200|标题|||
|introduction|longtext|4294967295|简介|||
|picture|varchar|200|图片|||
|content|longtext|4294967295|内容|||










# 5 平台实现
## 5.1平台功能模块
原创歌曲分享平台，在平台首页可以查看首页，音乐分享，音乐资讯，个人中心，后台管理等内容，并进行详细操作；如图5-1所示。

![cfcf04d9b4ee6eb51457de2b209d4f6](/md/blog.015.jpeg)

图5-1平台首页界面图

用户注册，在用户注册页面通过填写用户账号,密码,确认密码,用户姓名，年龄，联系电话等信息进行注册操作，如图5-2所示。

![8ddb818b3d2f5a605bf48ca94605ae0](/md/blog.015.jpeg)

图5-2用户注册界面图

音乐分享，在音乐分享页面可以查看音乐分类，区域，发布时间，简介，用户账号，用户姓名，点击次数，歌词等内容，还可以进行收藏，点赞，举报等操作；如图5-3所示。

![ff14f739cf0f26933bd41dbfefbdb6f](/md/blog.015.jpeg)

图5-3音乐分享界面图

个人中心，在个人中心页面通过填写用户账号，密码，用户姓名，上传图片，性别，年龄。联系电话等内容进行更新信息，还可以根据需要对我的收藏进行相对应操作，如图5-4所示。

![ba5019705f586cae624a56e8612f461](/md/blog.015.jpeg)

图5-4个人中心界面图

## 5.2后台功能模块
平台登录，通过填写注册时输入的用户名、密码、选择角色等信息进行登录操作，如图5-5所示。

![cacca5a0c45b236187a1c520cf6bd94](/md/blog.015.jpeg)

图5-5平台登录界面图

### 5.2.1管理员功能模块
管理员登录进入平台可以查看首页，个人中心，用户管理，音乐分类管理，音乐分享管理，举报管理，平台管理等功能，并进行详细操作，如图5-6所示。

![6f23c7c4fb49c0401bb8544c4be202a](/md/blog.015.jpeg)

图5-6管理员功能界面图

用户管理；在用户管理页面中可以查看索引,用户账号，用户姓名，头像，性别，年龄，联系电话等内容，并进行详情，修改和删除等操作；如图5-7所示。

![3949e07044a3e748e9aeaca6782def2](/md/blog.015.jpeg)

图5-7用户管理界面图

音乐分类管理；在音乐分类管理页面中可以查看索引,和音乐分类并进行修改和删除等操作；如图5-8所示。

![3e739a04d8a138de4f7fa03a746c383](/md/blog.015.jpeg)

图5-8音乐分类管理界面图

音乐分享管理；在音乐分享管理页面中可以查看索引,音乐分类，音乐名称，音乐视频，区域，视频封面，发布时间，歌词，用户账号，用户姓名等内容，并进行详情，修改，查看评论和删除操作；如图5-9所示。

![fe35d319e753cad182a6c93d7dd013a](/md/blog.015.jpeg)

图5-9音乐分享管理界面图

举报管理；在举报管理页面中可以查看索引,音乐名称，发布时间，用户账号，用户姓名，举报原因，审核回复，审核状态，审核等内容，并进行详情，修改，删除操作；如图5-10所示。

![16105899882ac98636c3ef223a565dc](/md/blog.015.jpeg)

图5-10举报管理界面图

系统管理；在音乐咨讯管理页面中可以查看索引,标题和图片等内容，并进行详情，修改和删除操作；如图5-11所示。

![fdd2a84126ed3349b77dc26b099b0dc](/md/blog.015.jpeg)

图5-11系统管理界面图
### 5.2.2用户功能模块
用户登录进入平台可以查看首页，个人中心，音乐分享管理，举报管理，我的收藏管理等功能，并根据需要进行详细操作，如图5-12所示。

![b839518dc076be2c9ccb97e7f63f64d](/md/blog.015.jpeg)

图5-12用户功能界面图

音乐分享管理；在音乐分享管理页面中可以查看索引,音乐分类，音乐名称，音乐视频，区域，视频封面，发布时间，歌词，用户账号，用户姓名等内容，并进行详情，修改，查看评论和删除操作；如图5-13所示。

![e8213cd2075b07d54b94a6c73d08872](/md/blog.015.jpeg)

图5-13音乐分享管理界面图

我的收藏管理；在我的收藏管理页面中可以查看索引,收藏名称，收藏图片等内容，并进行详情，修改，删除操作；如图5-14所示。

![608f681d1c7f752052ad69543050649](/md/blog.015.jpeg)

图5-14我的收藏管理界面图





# 6 平台测试
平台测试是软件开发过程中最后一步，但也是不可或缺的重要的一步，没有人可以保证一次性编写完成的平台不会出错，而平台测试就是将自己开发的平台成为成品前的最后一步。在测试过程中需要进行严谨细致的测试，要尽可能全面地在不同情况下运行该平台，排除一切出现错误的可能。

该平台的平台测试主要包括功能测试，可用性测试，维护测试，性能测试等部分，测试结果如下：
## 6.1功能测试
功能测试包含了适用性，准确性，可操作性，依从性，安全性等五个项目。

本平台功能测试如表6.1所示：

表6.1  平台功能测试

|内容|结果|
| :-: | :-: |
|依从性|正常|
|安全性|正常|
|可操作性|正常|
|适用性|正常|
|准确性|正常|
## 6.2可用性测试
可用性测试用于检测平台的可操作性，可理解性，可学习性等方面内容。具体测试方面如表6.2所示。

可用性测试是用来检测平台的操作性，理解性，学习性等方面内容。如下表所示。

表6.2可用性测试

|测试项|测试人员的评价|
| :-: | :-: |
|操作流程是否合理|是|
|所需数据项是否正确显示|是|
|模块布局是否协调，合理 |是|
|模块、提示内容等文字描述是否正确|是|
|对选中项能否发生对应切换|是|
|操作方式是否简单|是|
|窗口移动、缩放、关闭等操作是否正常|是|
|操作是否流畅|是|
## 6.3 性能测试
性能测试主要通过模拟平台运行环境来测试该平台是否能达到顾客期待。他的重要技术指标是平台的运行速度、网络的响应时间和支持并发节点数。

1）平台运行速度：得益于B/S架构，该平台能在不同配置电脑上运行并无明显卡顿，滞后，完全符合用户要求。

2）网络响应时间：网络响应时间主要包括网络最小响应时间、平均响应时间、最大响应时间三个参数。经过测试，在正常网络运营状态下，局域网内响应时间三参数为：1/2/5s，外网响应时间三参数为3/7/12s，符合用户需求，属于用户心理可承受范围。

3）支持并发节点数：经过模拟环境测试，本平台在并发节点达45个时，网络运营速度会发生较大波动，延迟时间10秒左右，符合用户需求。
## 6.4测试结果分析
经过以上测试的结果进行分析，本平台能够在不同电脑上使用运行，具备一定安全性，用户信息不易泄露，能够日后再增删功能，能够实现所有功能，产品运行性能良好，能达到毕业设计要求。
# 结 论
本文主要根据目前信息技术发展现状结合人们对于原创歌曲分享态度的转变引出开发原创歌曲分享平台的必要性。然后根据管理员和用户需求指定需求分析和可行性分析，并介绍应用到的相应技术，包括java技术，B/S结构等文中已做相关介绍和科普，然后展示相关模块完成的实现代码和截图，并做相关测试确保程序能正常运行。

本设计所实现的是一个原创歌曲分享平台，该平台严格按照需求分析制作相关模块，并利用所学知识尽力完成，但是本人由于学识浅薄，无法真正做到让该程序可以投入市场使用，仅仅简单实现部分功能，希望日后还能改善。

本平台具有以下优点：

该平台具有较高的适用性，选用B/S结构，可以在绝大部分个人平台上使用该平台。

平台将用户权限进行划分，管理员和用户都能看到及操作的信息不一样，两者具备不同的操作权限。

该平台操作界面简单明了，大部分人都可以正常使用。

但也存在以下问题需要改进：

运行时窗口不能被刷新，可以改进。

平台过于简单，显示的信息有限。

不能添加多个管理员账号，如果可以则将利于发展原创歌曲分享规模，便于原创歌曲分享信息集中管理。

不能实时预约接待消息，容易被忽视，不利于管理员服务用户。
#











