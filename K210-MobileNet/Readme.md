# K210-MobileNet 垃圾分类实现  
## 使用方法:  
1. 刷入 `minimum_with_kmodel_v4_support` 或更高级的Maixpy固件, 建议使用 `openmv_kmodel_v4_with_ide_support` 版本。  
2. 将 `Garbage.kmodel` 刷入SD卡或者 `0x500000` 等可用地址。  
3. 将 `Classify.py` 刷入 `boot.py`。  
4. 重启即可。  