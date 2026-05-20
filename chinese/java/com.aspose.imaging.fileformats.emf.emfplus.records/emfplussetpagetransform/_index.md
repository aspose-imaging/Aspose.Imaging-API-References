---
title: "EmfPlusSetPageTransform"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusSetPageTransform 记录指定用于将页面空间坐标转换为设备空间坐标的缩放因子和单位。"
type: docs
weight: 61
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetpagetransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetPageTransform extends EmfPlusTerminalServerRecordType
```

该 EmfPlusSetPageTransform 记录指定用于将页面空间坐标转换为设备空间坐标的缩放因子和单位。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetPageTransform(EmfPlusRecord source)](#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetPageTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPageUnit()](#getPageUnit--) | 获取页面空间坐标的计量单位，来自 UnitType 枚举（第 2.1.1.33 节）。 |
| [getPageScale()](#getPageScale--) | 获取或设置一个 32 位浮点值，指定将页面空间坐标转换为设备空间坐标的比例因子。 |
| [setPageScale(float value)](#setPageScale-float-) | 获取或设置一个 32 位浮点值，指定将页面空间坐标转换为设备空间坐标的比例因子。 |
### EmfPlusSetPageTransform(EmfPlusRecord source) {#EmfPlusSetPageTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetPageTransform(EmfPlusRecord source)
```


初始化 `EmfPlusSetPageTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getPageUnit() {#getPageUnit--}
```
public int getPageUnit()
```


获取页面空间坐标的计量单位，来自 UnitType 枚举（第 2.1.1.33 节）。此值不应为 UnitTypeDisplay 或 UnitTypeWorld。

值：页面单位。

**Returns:**
int
### getPageScale() {#getPageScale--}
```
public float getPageScale()
```


获取或设置一个 32 位浮点值，指定将页面空间坐标转换为设备空间坐标的比例因子。

值：页面比例。

**Returns:**
float
### setPageScale(float value) {#setPageScale-float-}
```
public void setPageScale(float value)
```


获取或设置一个 32 位浮点值，指定将页面空间坐标转换为设备空间坐标的比例因子。

值：页面比例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

