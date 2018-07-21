# BD_STTP_2018
### Big Data Short Term Training Programme 2018

此存储库包含用于设置程序期间使用的大数据技术堆栈的脚本。

### Usage
打开终端窗口并按照以下步骤操作：
1. 克隆此存储库  
   `git clone --depth 1 "https://github.com/Zhang-Ren-Jie/BD_STTP_2018"`
2. 进入目录  
   `cd BD_STTP_2018`
3. 设置文件模式（获取运行权限）  
   `chmod +x *.sh`
4. 运行所需的安装脚本  
   例如，如果您希望安装Hadoop使用 `./InstallHadoop.sh`  
   安装包为`http://www.eu.apache.org/dist/hadoop/common/stable/` 下第一个包！  
   安装路径`/usr/local/hadoop`  
   环境变量为用户变量`~/.bashrc`  
   如有需求可自行更改！！！  

这些脚本自动负责下载和解压缩最新的二进制文件和基本配置。  
在安装过程中可能会要求您输入用户帐户密码。  
此脚本仅为小白提供测试环境。（使用前查看端口是否被占用，尽量避免端口冲突）  

---
_注意：请不要“sudo”以上命令._
