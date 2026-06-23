---
title: "EmfModifyWorldTransform"
second_title: "Aspose.Imaging for Java API 参考"
description: "EMR_MODIFYWORLDTRANSFORM 记录修改了回放设备上下文中当前的世界空间到页面空间的变换。"
type: docs
weight: 73
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

EMR\_MODIFYWORLDTRANSFORM 记录修改回放设备上下文中当前的世界空间到页面空间的变换。

有关变换和坐标空间的更多信息，请参阅 [MSDN-WRLDPGSPC]。有关其他变换记录类型的规范，请参见第 2.3.12 节。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | 初始化 `EmfModifyWorldTransform` 类的新实例。 |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | 初始化 `EmfModifyWorldTransform` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | 获取或设置一个 32 位无符号整数，指定 Xform 中指定的变换的使用方式。 |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | 获取或设置一个 32 位无符号整数，指定 Xform 中指定的变换的使用方式。 |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


初始化 `EmfModifyWorldTransform` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | 来源。 |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


初始化 `EmfModifyWorldTransform` 类的新实例。

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


获取或设置一个 32 位无符号整数，指定 Xform 中指定的变换的使用方式。该值必须位于 ModifyWorldTransformMode 枚举中（第 2.1.24 节）。

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


获取或设置一个 32 位无符号整数，指定 Xform 中指定的变换的使用方式。该值必须位于 ModifyWorldTransformMode 枚举中（第 2.1.24 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

