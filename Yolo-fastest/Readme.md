# yolo-fastest 垃圾分类实现  
## 使用方法  
1. 安装 Cuda 和 Cudnn 。  
2. 安装 [vcpkg](https://github.com/microsoft/vcpkg)  
3. 安装 [Darknet](https://github.com/AlexeyAB/darknet)  
4. cd到本文件夹  
5. 执行以下语句:  
```
darknet detector demo .\train.data .\yolo-fastest.cfg .\yolo-fastest.weights -c 0
```
即可。  

## 训练方法  
参考 [Darknet说明文档](https://github.com/AlexeyAB/darknet)  