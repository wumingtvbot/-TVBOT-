申明：无名TVbot信号接收器永久免费使用，禁止倒卖！

一、功能介绍

1、根据tradingview发送的信号自动买卖平仓

2、接入平台

暂时只接入欧易okx，后期接入币安等其它交易所

3、可以自定义币种，也根据tradingview发送的币种自动下单，无需在客户端单独设置币种（暂时只支持永续合约）

4、持仓模式支持全仓，逐仓

5、下单方式：支持市价和限价下单

6、智能对接，保存配置后在弹窗把代码复制到tradingview警报窗口软件自动判断开平仓信号（只需要复制一次，如果后期改动其它配置，无需在复制代码到警报中）

7、加仓保护，勾选后同一个方向的信号只处理一次

举例：假设第一次给的信号是buy, 第二次tradingview再发送buy （如果打开加仓保护，客户端在不在执行下单操作，反之就继续买入）

8、通信秘钥，这个需要大家自定义，防止别人恶意post你的服务器

9、止盈止损功能。很简单就不介绍了。输入1就代表1%，

钉钉推送，如果勾选，tradingview发送信号，开平仓操作将通过钉钉推送给您

二特色用法

软件支持多用户操作，您在文件夹的API里面增加几个账号，同一信号就可以几账号同时下单，（因高并发问题，和服务器性能问题，一般推荐在100个账号内）

说这么多的原因，你懂的，如果你的策略好，可以让其它人跟单，只需要对方提供给您api，如果消息要推送给对方，也需要提供钉钉api。
