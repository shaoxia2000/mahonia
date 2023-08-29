# mahonia
Automatically exported from code.google.com/p/mahonia
qq纯真数据库 qqwry.dat 操作！
	ip := qqwry.NewQQwry("qqwry.dat")
	ip.Find("1.58.162.32")
	fmt.Println("归属地：", ip.Ip, ip.Country, ip.City)
