bootloader的描述，和PC启动的对比，参考“嵌入式系统原理与应用“Page64




[U-boot官网](http://www.denx.de/en/News/WebHome)

[U-Boot源代码下载地址](ftp://ftp.denx.de/pub/u-boot/)

[用git下载最新的uboot代码](http://www.crifan.com/use_git_download_clone_latest_uboot_sourcecode/)

烧写uboot的步骤：  
参考<mini2440用户手册>，第三章，备份和恢复系统 3.2安装Linux部分
step1：x 擦除 nandflash  
step2：f format nand  
step3：v 下载uboot.bin  



uboot代码走读(v2009.11)：  
[cpu/arm920t/start.S](./start.S)

#include <common.h> //whereis?
#include <config.h> //whereis?




_undefined_instruction:	.word undefined_instruction
这句话的意思是在_undefined_instruction标号处定一个32bit的word，值为undefined_instruction，undefined_instruction在后面的标号处定义 













免费下载地址在 http://linux.linuxidc.com/

用户名与密码都是www.linuxidc.com

具体下载目录在 /pub/u-boot/

或 http://linux.linuxidc.com/pub/u-boot/

用户名与密码都是www.linuxidc.com
