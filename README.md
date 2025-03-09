# raspberry_backup

1、tf卡备份

​	使用back.sh



2、usb备份

​	使用back_u.sh



### 使用方法： 

step1：下载脚本文件back.sh到Linux系统中

step2：把需要备份的SD卡插入Linux系统中，用 df -h 命令查询下 SD 卡对应的设备名。

step3：进入脚本文件 back.sh 所在目录，只需要下面两行命令即可完成 SD 卡备份，最终 img 文件会生成在当前文件夹下（*.img）。

sudo chmod +x rpi-backup.sh #需要赋可执行权限

.
