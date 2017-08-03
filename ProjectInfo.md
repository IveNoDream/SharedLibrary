# SharedLibrary
共享图书馆

#书籍信息
Class Book
	--书籍编号(KEY)
	--书名
	--作者
	--出版社
	--出版年份
	--印刷
	--发行
	--定价

#图书馆书籍信息
Class LibBook
	--书籍内部编号(KEY)
	--图书基本信息(Class Book)	
	--录入时间
	--图书位置信息(图书管地址/书架位置)
	--当前状态(待借/借出/逾期/丢失)
	--借阅记录(多条)

#借阅记录
Class LibRecord
	--书籍内部编号(LibBook)
	--借出者个人信息(Customers)
	--

#借阅人信息
Class Customer
	--ID
	--姓名(昵称)
	--头像
	--实名认证(身份证-公安部)
	--绑定手机
	--信用积分
	--我的钱包
	--我的借阅(LibBooks)
	--是否会员
	--推送消息(保留)
 

#我的钱包
Class Wallet
	--余额(Balance)
	--押金()
	--优惠券()
	--

