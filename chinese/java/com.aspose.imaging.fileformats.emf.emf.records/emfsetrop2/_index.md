---
title: "EmfSetRop2"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_SETROP2 记录定义了二进制光栅操作模式。"
type: docs
weight: 137
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetrop2/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetRop2 extends EmfStateRecordType
```

该 EMR\_SETROP2 记录定义二进制光栅操作模式。

二进制光栅操作混合模式定义了在使用当前画笔绘制时如何组合源颜色和目标颜色。混合模式是二进制光栅操作代码，表示两个变量的所有可能布尔函数，使用二进制操作 AND、OR 和 XOR（异或），以及一元操作 NOT。该混合模式仅适用于光栅设备；在矢量设备上不可用。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetRop2(EmfRecord source)](#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetRop2` 类的新实例。 |
| [EmfSetRop2()](#EmfSetRop2--) | 初始化 `EmfSetRop2` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getRop2Mode()](#getRop2Mode--) | 获取或设置一个 32 位无符号整数，指定光栅操作模式，并且必须位于 WMF Binary Raster Op 枚举（[MS-WMF] 第 2.1.1.2 节）中。 |
| [setRop2Mode(int value)](#setRop2Mode-int-) | 获取或设置一个 32 位无符号整数，指定光栅操作模式，并且必须位于 WMF Binary Raster Op 枚举（[MS-WMF] 第 2.1.1.2 节）中。 |
### EmfSetRop2(EmfRecord source) {#EmfSetRop2-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetRop2(EmfRecord source)
```


初始化 `EmfSetRop2` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetRop2() {#EmfSetRop2--}
```
public EmfSetRop2()
```


初始化 `EmfSetRop2` 类的新实例。

### getRop2Mode() {#getRop2Mode--}
```
public int getRop2Mode()
```


获取或设置一个 32 位无符号整数，指定光栅操作模式，并且必须位于 WMF Binary Raster Op 枚举（[MS-WMF] 第 2.1.1.2 节）中。

**Returns:**
int
### setRop2Mode(int value) {#setRop2Mode-int-}
```
public void setRop2Mode(int value)
```


获取或设置一个 32 位无符号整数，指定光栅操作模式，并且必须位于 WMF Binary Raster Op 枚举（[MS-WMF] 第 2.1.1.2 节）中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

