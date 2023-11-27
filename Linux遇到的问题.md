linux可能遇到的常见问题
问题一：系统无法正常启动或运行，提示系统所在的分区硬盘找不到，提示以下原因：
/dev/Centos/root does not exist   
 /dev/centos/swap does not exist   
/dev/mapper/centos-root does not exist
解决办法：
（1）将安装有系统的硬盘重新插拔一下，可能为装有系统的硬盘没有挂载上，导致系统启动失败
（2）如以上办法还不能解决，则进入BIOS界面，找到SATA设置界面，将硬盘控制器的模式从RAID改为AHCI模式
