---
title: "EmfPlusClear"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "EmfPlusClear 记录清除输出坐标空间并使用背景颜色和透明度进行初始化。"
type: docs
weight: 12
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

EmfPlusClear 记录清除输出坐标空间并使用背景颜色和透明度进行初始化。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusClear` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | 获取或设置颜色。 |
| [setArgb32Color(int value)](#setArgb32Color-int-) | 获取或设置颜色。 |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


初始化 `EmfPlusClear` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


获取或设置颜色。一个定义屏幕绘制颜色的 EmfPlusARGB 对象（第 2.2.2.1 节）。所有颜色均采用 [IEC-RGB] 指定，除非另有说明。

值：颜色。

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


获取或设置颜色。一个定义屏幕绘制颜色的 EmfPlusARGB 对象（第 2.2.2.1 节）。所有颜色均采用 [IEC-RGB] 指定，除非另有说明。

值：颜色。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

