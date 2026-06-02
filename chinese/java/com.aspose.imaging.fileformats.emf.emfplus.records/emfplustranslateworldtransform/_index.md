---
title: "EmfPlusTranslateWorldTransform"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusTranslateWorldTransform 记录对当前世界空间变换执行平移操作。"
type: docs
weight: 72
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplustranslateworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusTranslateWorldTransform extends EmfPlusTerminalServerRecordType
```

该 EmfPlusTranslateWorldTransform 记录对当前世界空间变换执行平移操作。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusTranslateWorldTransform(EmfPlusRecord source)](#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusTranslateWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | 获取一个值，指示是否为 [post multiplied matrix]。 |
| [getDx()](#getDx--) | 获取或设置一个 32 位浮点值，定义水平距离。 |
| [setDx(float value)](#setDx-float-) | 获取或设置一个 32 位浮点值，定义水平距离。 |
| [getDy()](#getDy--) | 获取或设置一个 32 位浮点值，定义垂直距离。 |
| [setDy(float value)](#setDy-float-) | 获取或设置一个 32 位浮点值，定义垂直距离。 |
### EmfPlusTranslateWorldTransform(EmfPlusRecord source) {#EmfPlusTranslateWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusTranslateWorldTransform(EmfPlusRecord source)
```


初始化 `EmfPlusTranslateWorldTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getPostMultipliedMatrix() {#getPostMultipliedMatrix--}
```
public boolean getPostMultipliedMatrix()
```


获取一个值，指示是否为 [post multiplied matrix]。如果设置，则变换矩阵应后乘。如果清除，则应前乘。

值：如果为 [post multiplied matrix] 则为 `true`；否则为 `false`。

**Returns:**
boolean
### getDx() {#getDx--}
```
public float getDx()
```


获取或设置一个 32 位浮点值，定义水平距离。平移通过从 dx 和 dy 字段构建新的世界变换矩阵来执行。

值：dx。

**Returns:**
float
### setDx(float value) {#setDx-float-}
```
public void setDx(float value)
```


获取或设置一个 32 位浮点值，定义水平距离。平移通过从 dx 和 dy 字段构建新的世界变换矩阵来执行。

值：dx。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

### getDy() {#getDy--}
```
public float getDy()
```


获取或设置一个 32 位浮点值，定义垂直距离。

值：dy。

**Returns:**
float
### setDy(float value) {#setDy-float-}
```
public void setDy(float value)
```


获取或设置一个 32 位浮点值，定义垂直距离。

值：dy。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | float |  |

