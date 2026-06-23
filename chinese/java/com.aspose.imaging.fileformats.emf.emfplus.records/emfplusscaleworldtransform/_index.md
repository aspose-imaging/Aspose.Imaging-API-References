---
title: "EmfPlusScaleWorldTransform"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。"
type: docs
weight: 52
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusscaleworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusScaleWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusScaleWorldTransform 记录对当前世界空间变换执行缩放。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusScaleWorldTransform(EmfPlusRecord source)](#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusScaleWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | 获取一个值，指示是否为[post multiplied matrix]。 |
| [getSx()](#getSx--) | 获取或设置定义水平缩放因子的 32 位浮点值。 |
| [setSx(float value)](#setSx-float-) | 获取或设置定义水平缩放因子的 32 位浮点值。 |
| [getSy()](#getSy--) | 获取或设置定义垂直缩放因子的 32 位浮点值。 |
| [setSy(float value)](#setSy-float-) | 获取或设置定义垂直缩放因子的 32 位浮点值。 |
### EmfPlusScaleWorldTransform(EmfPlusRecord source) {#EmfPlusScaleWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusScaleWorldTransform(EmfPlusRecord source)
```


初始化 `EmfPlusScaleWorldTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


获取指示是否为 [post multiplied matrix] 的值。如果设置，则应对变换矩阵进行后乘。如果未设置，则应进行前乘。

值：`true` 表示[post multiplied matrix]；否则为 `false`。

**Returns:**
boolean
### getSx() {#getSx--}
```
public float getSx()
```


获取或设置定义水平缩放因子的 32 位浮点值。缩放通过从 Sx 和 Sy 字段值构建新的变换矩阵来执行，如下表所示。 ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- 图 3：缩放变换矩阵

**Returns:**
float
### setSx(float value) {#setSx-float-}
```
public void setSx(float value)
```


获取或设置定义水平缩放因子的 32 位浮点值。缩放通过从 Sx 和 Sy 字段值构建新的变换矩阵来执行，如下表所示。 ----------------- | Sx | 0 | 0 | | 0 | Sx | 0 | ----------------- 图 3：缩放变换矩阵

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

### getSy() {#getSy--}
```
public float getSy()
```


获取或设置定义垂直缩放因子的 32 位浮点值。

**Returns:**
float
### setSy(float value) {#setSy-float-}
```
public void setSy(float value)
```


获取或设置定义垂直缩放因子的 32 位浮点值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

