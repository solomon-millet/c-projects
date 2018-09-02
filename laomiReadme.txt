

晓超米提醒：

	所有的测试请进入linux系统的字符界面测试。
	
	操作frambuffer时，注意如果显示图像有问题。那么需要校正
	获得的屏幕分辨率的x坐标精度。

	可以尝试：

	xres = xxx.xres + 10;

	或

	xres = xxx.xres + 42;
