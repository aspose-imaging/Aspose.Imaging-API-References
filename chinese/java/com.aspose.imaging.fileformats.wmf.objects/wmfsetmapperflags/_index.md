---
title: "WmfSetMapperFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "META_SETMAPPERFLAGS 记录定义字体映射器在将逻辑字体映射到物理字体时使用的算法。"
type: docs
weight: 78
url: /zh/java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

META\_SETMAPPERFLAGS 记录定义了字体映射器在将逻辑字体映射到物理字体时使用的算法。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | 获取或设置映射器的值。 |
| [setMapperValues(int value)](#setMapperValues-int-) | 获取或设置映射器的值。 |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


获取或设置映射器的值。

值：字体映射器尝试将字体的宽高比匹配到当前设备的宽高比。如果第零位被设置，映射器仅选择匹配的字体。

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


获取或设置映射器的值。

值：字体映射器尝试将字体的宽高比匹配到当前设备的宽高比。如果第零位被设置，映射器仅选择匹配的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

