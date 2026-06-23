---
title: "EmfSetArcDirection"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR\\_SETARCDIRECTION 记录指定用于弧和矩形输出的绘图方向。"
type: docs
weight: 118
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfsetarcdirection/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfSetArcDirection extends EmfStateRecordType
```

EMR\_SETARCDIRECTION 记录指定用于弧线和矩形输出的绘制方向。

EMR\_SETARCDIRECTION 记录影响以下记录的绘制方向： - EMR\_ARC (section 2.3.5.2) - EMR\_ARCTO (section 2.3.5.3) - EMR\_CHORD (section 2.3.5.4) - EMR\_ELLIPSE (section 2.3.5.5) - EMR\_PIE (section 2.3.5.15) - EMR\_RECTANGLE (section 2.3.5.34) - EMR\_ROUNDRECT (section 2.3.5.35)
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfSetArcDirection(EmfRecord source)](#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfSetArcDirection` 类的新实例。 |
| [EmfSetArcDirection()](#EmfSetArcDirection--) | 初始化 `EmfSetArcDirection` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getArcDirection()](#getArcDirection--) | 获取或设置指定弧方向的 32 位无符号整数。 |
| [setArcDirection(int value)](#setArcDirection-int-) | 获取或设置指定弧方向的 32 位无符号整数。 |
### EmfSetArcDirection(EmfRecord source) {#EmfSetArcDirection-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfSetArcDirection(EmfRecord source)
```


初始化 `EmfSetArcDirection` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfSetArcDirection() {#EmfSetArcDirection--}
```
public EmfSetArcDirection()
```


初始化 `EmfSetArcDirection` 类的新实例。

### getArcDirection() {#getArcDirection--}
```
public int getArcDirection()
```


获取或设置指定弧方向的 32 位无符号整数。该值必须位于 ArcDirection 枚举中（第 2.1.2 节）。默认方向为逆时针。

**Returns:**
int
### setArcDirection(int value) {#setArcDirection-int-}
```
public void setArcDirection(int value)
```


获取或设置指定弧方向的 32 位无符号整数。该值必须位于 ArcDirection 枚举中（第 2.1.2 节）。默认方向为逆时针。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

