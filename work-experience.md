以下是我这是我所有的项目经历


制作了一个英语学习软件
具体的痛点:
总是花很多时间在已经记过的单词上耗费太多精力,非常不体面。

具体的功能：
将英语6级所需的单词存入到软件中（软件中有三个库"已记住库"，"未记住库"和"工作记忆库"）
让使用者先过一遍所有的单词
让使用者自行决定将哪些单词移入到未记住库，从而将单词分成两个部分。
使用者的最终目标就是将未记住库的所有单词转化成已记住库里面的。从而实现记住所有英语6级单词。
使用者可以先将单词转化到工作记忆库中,逐步完成记住所有的英语6级单词。

所需要的关键技术:
批量获取所有单词的音频信息。(使用爬虫技术)



制作了一个做一个万能答题的程序(可惜中道崩阻)
具体痛点：
精力老是被那些bullshit的答题分散(为了各种各样的沙比二课分啥的，无意义又浪费时间，拆散精力。)
具体功能：
目标的平台是问卷星。
搜集问卷星的各种答题类型，单选题，多选题，简答题，摸清楚答题逻辑指挥程序能够自如的选择和填写。

所需要的关键技术：
接入AI大模型，让AI大模型来根据题目内容来给出答案。
然后让程序作答。

中途放弃原因:
python程序不够稳定，不够适配网页语言

改进方案：
使用浏览器插件的形式应该可以进行



制作了一个企业财务统计程序
具体痛点：传统的财务统计需要复杂的步骤，各种各样的函数，非常不体面。
具体功能：
了解清楚一个财务统计的整个步骤之后，使用Python来自动化，一步到位，输入原数据，点击运行结果出来。

所需要的关键技术：
pandas



制作了一个具体自动处理发货标签的程序。
具体痛点：常规的处理发货标签要手动的删除相对应的不应该出现在标签上的信息,标签量一旦多起来就非常耗时耗力。(因为标签是PDF的，没办法用搜索替换来常规处理)
具体功能：
找到相对应的关键字段并定位，用一个白色方块儿精准覆盖

所需要的关键技术：
PyMuPDF库



制作了一个跨境电商自动统计OMS库存(库存数和在途数)的浏览器插件
具体痛点:原OMS平台没有常规的直接导出数据的操作,需要人工一个个复制粘贴，各种数据到excel表格里面,非常耗时耗力还容易出错。
具体功能：
使用浏览器插件来直接获取原库存数的对应数据
使用Python代码将获取到的数据填入到相应的表格中。

需要的关键技术:
模拟鼠标悬浮获取ajax请求

做一个跨境电商自动发货的插件
具体痛点：店小秘常规发货没能做的非常好，每个商品都需要人工单独点击一系列操作而发货，耗时耗力，还很折磨人。
具体功能：
记录下常人常规的点击流程
模仿人的点击行为，完成所有商品的发货操作



做了一个统计发货个数的插件。
具体痛点：跨境电商的一个运营任务就是统计每天的发货数量完成表格的填写，耗时耗力还容易出错。
具体功能：
直接使用浏览器插件批量获取发货信息统计，具体产品的数量，填入具体表格中

做了一个上架产品时批量填写信息的插件。
具体痛点：有一个Sb老板压榨的员工给3000块。员工当牛做马，随用随弃，我不幸运在这个公司上做了一周(然后主动辞职。)，一个主要的工作内容内容是将其他商家商品上架到自己的商店上
其中需要填写非常多重复的信息(产品的重量,产品的规格等。)
具体功能：
直接写一个浏览器插件，自动填写完所有的信息，然后点击发布就行了(这个sb老板不懂留人才,只会画大饼)



做了一个自动打开多个网站的浏览器插件
具体痛点：日常工作生活中，有时候需要打开网站，以完成各种各样的工作和学习生活，搜索点击有点耗时耗力，直接存储到网址的信息，批量打开。
具体功能：
在谷歌或微软浏览器上安装插件，输入各种各样的网址，保存网址，下次打开的时候一键开启多个网站。
(已经上架闲鱼，可以在在闲鱼上搜索docyeye来支持！)



做了一个加速视频，可以加速到10倍速的插件。
具体痛点：想要快速的过一遍整个视频内容，而不想花长时间在这个视频上。
具体功能:
在谷歌或微软浏览器上安装插件,打开有视频的网页，点击插件可以调整倍速。

(已经上架闲鱼，可以在闲鱼上搜索。docyeye来支持！)



做了一个自动向boss直聘上招聘信息，发打招呼信息的插件(是我比较得意的作品，哈哈哈!)
具体痛点：凭什么只有老板能发招募信息让员工来找，员工只能一个个点打招呼信息？
具体功能：
自己设置好相应的岗位要求薪资水平和相应的城市编辑好相应的打招呼信息，使用浏览器插件像这些招聘信息，批量发消息，增加自己求职成功的概率！

（新上架闲鱼，可以在闲鱼上搜索docyeye来支持！）

做了一个自动切分字幕的软件。
具体痛点：个人在做视频做字幕的时候，需要花费大量的时间去切分字幕分配时间，而且高度重复，繁琐。
具体功能：
就是通过一大段口播文案，然后接入AI来自动切分这些口播文案成为适合在视频上展示的一段又一段的字幕文本。翻译之后，根据用户的要求，根据中文还是英文来生成相应的时间戳，保证每一段字幕拥有相对应的显示时长。最终的结果就是生成中英文两段SRT格式的字幕文件，可以直接输入到剪映中生成字幕。
（已经上架闲鱼，可以在闲鱼上搜索docyeye来支持）




