# 伪 DC 调光
当亮度设置低于某值时，拦截硬件亮度下调，并对应修改极暗模式的压暗强度。  
直接拖动系统亮度条即可自动调节，也不影响截图的亮度。

## 修改
针对OxygenOS和ColorOS的AOD息屏添加了一个修复功能。当显示状态为DOZE或DOZE_SUSPEND时也禁用伪DC。
在 Oneplus 13T (13s) OxygenOS 15 上测试通过。

## 来源
本仓库复刻自https://github.com/ztc1997/FakeDCBacklight
和https://github.com/yuhe955520/FakeDCBacklight
