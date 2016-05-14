# gdal_UI——基于遥感数据的河道水质监控系统
============
2016-5-14  
程序结构  
gdal_UI  

> data #存放数据  
 	> water.db #数据库文件  
> code #存放代码  
	>> model #每个模块的头文件代码  
		>>> 遥感图像模块.py  
		>>> 图像分析模块.py  
		>>> 水质数据模块.py  
		>>> 无人机模块.py  
		>>> 用户登陆模块.py  
 	>> function #子功能函数  
 		>>> 数据库操作.py  
 		>>> 遥感图像读取.py  
 		>>> pandas操作.py  
 		>>> 经纬度坐标操作.py  
 		>>> 水质数据操作.py  
 		>>> md5加密.py  
 		>>> 视频录像操作.py  
 	>> ui #UI框架  
 		>>> 框架  
