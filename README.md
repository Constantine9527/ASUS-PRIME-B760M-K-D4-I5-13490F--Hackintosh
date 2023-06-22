# ASUS-PRIME-B760M-K-D4-I5-13490F--Hackintosh

参考视频，了解OC和EFI：https://www.bilibili.com/video/BV1yq4y1o7cT/?p=14&vd_source=6097bb3ee037e477e7f352c666113bc7  
参考文档：http://apple.sqlsec.com  
安装的系统是Big Sur11.7   

####机器配置
>主板：华硕PRIME B760M-K D4  
>处理器：I5-13490F  
>内存：光威 DDR4 3200 32G  
>显卡：RX5600XT  
>存储：三星980 1T  
>网卡：奋威T919  

##遇到的问题  
>1.蓝牙无法打开  
>重新定制了USB，替换了UTBMap.kext，如何定制USB，参考：http://apple.sqlsec.com，这里可以搜索。  

##简单的记录一下步骤：
1.下载Big Sur安装包，我这里使用白苹果下载的，没有白苹果可以在微信搜：黑果小兵，赞助他之后给你发下载地址。  
2.参考此文档使用命令将系统写入到U盘里：https://support.apple.com/zh-cn/HT201372    
3.定制USB，参考：https://apple.sqlsec.com/6-%E5%AE%9E%E7%94%A8%E5%A7%BF%E5%8A%BF/6-1/ 不定制，蓝牙可能出问题。  
4.使用MountEFI在Mac里显示EFI分区，然后将EFI文件夹复制到EFI分区里。  
5.安装系统，安装后，参考国光的文档优化引导。  


#感谢国光大佬！
