大家好，今天给大家演示一下微信智能问答机器人，如果你是一个社群工作者、拼团团长、业务群运营经理，使用这个项目可以帮助你解决一些重复性问答。
QA系统由微信开放对话平台提供，由后台系统可以操作，数据存储和配置使用维格表实现。
下面为大家演示几个核心功能：
一 到货信息看板和自动问答
二 通知公告自动问答
先看一下效果，群成员在群内发送问题内容，机器会将包含链接的回答内容自动回复发送，点击链接可以查看详情
实现以上功能很简单，下面我来实际操作演示一下
首先，我们需要在维格表后台发布一条公告，我们以核酸检测通知为例，选择发布日期、填写发布内容和发布者，提交之后，通知内容可以在列表中显示
然后，我们再继续添加一个商品，输入商品名称苹果，提交，苹果被添加到商品列表
接着，我们继续添加一条到货信息，选择日期，选择商品，商品可以选择多个，设置状态为待发货，提交之后，我们在到货信息列表中可以看到相关信息，可以以不同的视图模式显示
以上信息创建完毕后，我们在问答系统中配置相应问题，这样机器人就可以在群内自动回复了
复制一下到货信息列表的分享链接地址，在问答系统中创建一个问题 问题的内容是 ”什么时候到货“，把刚刚复制的链接替换到问题的回复内容中
选择相似问题，系统推荐，系统会自动推荐一些相似的问题，按需要进行勾选，保存一下
继续添加一个社区通知问答，到问题表中复制通知公告的分享链接地址，编辑社区通知问题，将链接替换到问题答案中，保存问题
以上，我们已经添加了 ”什么时候到货“和”社区通知“ 两个问题，
问题保存后需要发布上线一下，点击左侧的发布管理 上线发布 发布，提示发布成功后，我们在微信群众看一下效果
发送消息内容  社区公告，机器人会自动返回回答内容；
发送 什么时候到货，机器人自动回复到货信息
点击回复中的链接地址，就可以查看相关内容了，在电脑网页中的显示是这样，卡片形式，很清晰明了
我们切换到手机模式看一下，卡片视图，也不错
只需要以上简单几步，就完成了两个自动通知场景的构建，欢迎大家进一步关注Wechat Openai QA Bot项目，如果觉得可以，给一个star