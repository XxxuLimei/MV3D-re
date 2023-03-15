# MV3D-re
复现MV3D  
----------------  
0315：  
1. 安装cnpy库，将lidar的.bin文件转为python可读取的.npy文件，步骤如下：  
- 下载[cnpy](https://github.com/rogersce/cnpy)库  
- 新建一个build文件夹  
- 在文件夹下进行cmake，`cmake + cnpy的cmakelist的path`
- `make`  
- `sudo make install`  
详细终端信息见cnpy.log文件  
