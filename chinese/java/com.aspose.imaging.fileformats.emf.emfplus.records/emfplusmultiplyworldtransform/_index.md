---
title: "EmfPlusMultiplyWorldTransform"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusMultiplyWorldTransform 记录将当前世界空间变换乘以指定的变换矩阵。"
type: docs
weight: 41
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusmultiplyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusMultiplyWorldTransform extends EmfPlusTerminalServerRecordType
```

EmfPlusMultiplyWorldTransform 记录将当前世界空间变换乘以指定的变换矩阵。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusMultiplyWorldTransform(EmfPlusRecord source)](#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusMultiplyWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getPostMultipliedMatrix()](#getPostMultipliedMatrix--) | 获取一个值，指示是否为[post multiplied matrix]。 |
| [getMatrixData()](#getMatrixData--) | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象定义乘法矩阵。 |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象定义乘法矩阵。 |
### EmfPlusMultiplyWorldTransform(EmfPlusRecord source) {#EmfPlusMultiplyWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusMultiplyWorldTransform(EmfPlusRecord source)
```


初始化 `EmfPlusMultiplyWorldTransform` 类的新实例。

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
### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象定义乘法矩阵。

值：矩阵数据。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），该对象定义乘法矩阵。

值：矩阵数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

