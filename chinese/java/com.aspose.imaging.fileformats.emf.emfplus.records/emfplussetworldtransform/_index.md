---
title: "EmfPlusSetWorldTransform"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "该 EmfPlusSetWorldTransform 记录根据指定变换矩阵中的值设置世界变换。"
type: docs
weight: 68
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplussetworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusTerminalServerRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusterminalserverrecordtype)
```
public final class EmfPlusSetWorldTransform extends EmfPlusTerminalServerRecordType
```

该 EmfPlusSetWorldTransform 记录根据指定变换矩阵中的值设置世界变换。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusSetWorldTransform(EmfPlusRecord source)](#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusSetWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getMatrixData()](#getMatrixData--) | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），定义新的当前世界变换。 |
| [setMatrixData(Matrix value)](#setMatrixData-com.aspose.imaging.Matrix-) | 获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），定义新的当前世界变换。 |
### EmfPlusSetWorldTransform(EmfPlusRecord source) {#EmfPlusSetWorldTransform-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusSetWorldTransform(EmfPlusRecord source)
```


初始化 `EmfPlusSetWorldTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 源。 |

### getMatrixData() {#getMatrixData--}
```
public Matrix getMatrixData()
```


获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），定义新的当前世界变换。

值：矩阵数据。

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setMatrixData(Matrix value) {#setMatrixData-com.aspose.imaging.Matrix-}
```
public void setMatrixData(Matrix value)
```


获取或设置一个 EmfPlusTransformMatrix 对象（第 2.2.2.47 节），定义新的当前世界变换。

值：矩阵数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

