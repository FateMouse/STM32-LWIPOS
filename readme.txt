
本实验将实现如下功能：本实验为ENC28J60网络模块配套例程，本例程默认使用精英STM32F103开发板，如果要在其他开发板是使用ENC28J60模块的话请自行需改驱动程序。本实验网络协议栈使用的LWIP,版本为1.4.1。默认开启了DHCP，将开发板连接到路由器上以后就会自动获取IP地址，当DHCP失败以后就会使用默认IP地址，默认IP地址为：192.168.1.30。DHCP成功后就可以在电脑上通过ping命令来测试LWIP移植是否成功。

注意：本例程是不带UCOS的LWIP移植,本例程为MiniSTM32开发板ENC28J60网络实验例程。


            	广州市星翼电子科技有限公司
                电话：020-38271790
                传真：020-36773971
	       	购买：http://shop62103354.taobao.com
                      http://shop62057469.taobao.com
                公司网站：www.alientek.com
         	技术论坛：www.openedv.com
