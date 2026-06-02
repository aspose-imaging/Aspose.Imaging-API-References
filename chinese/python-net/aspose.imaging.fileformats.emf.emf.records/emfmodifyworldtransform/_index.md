---
title: "EmfModifyWorldTransform 类"
type: docs
weight: 640
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---

**Summary:** The EMR_MODIFYWORLDTRANSFORM record modifies the current world-space to page-space<br/>            transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfModifyWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform__1) | 初始化 [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) 类的新实例。 |
| [EmfModifyWorldTransform(source)](#EmfModifyWorldTransform_source_2) | 初始化 [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| modify_world_transform_mode | [EmfModifyWorldTransformMode](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmodifyworldtransformmode/) | r/w | 获取或设置一个 32 位无符号整数，指定<br/>            Xform 中指定的变换如何使用。此值必须位于<br/>            ModifyWorldTransformMode 枚举中（第 2.1.24 节）。 |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置 XForm 对象（第 2.2.28 节），该对象定义了从世界空间到页面空间的变换。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfModifyWorldTransform() {#EmfModifyWorldTransform__1}


```
 EmfModifyWorldTransform() 
```

初始化 [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) 类的新实例。

### Constructor: EmfModifyWorldTransform(source) {#EmfModifyWorldTransform_source_2}


```
 EmfModifyWorldTransform(source) 
```

初始化 [EmfModifyWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

### Method: create_from_record(source)  [static] {#create_from_record_source_1}


```
 create_from_record(source) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| source | [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) | 来源。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


### Method: create_from_type(type)  [static] {#create_from_type_type_2}


```
 create_from_type(type) 
```

初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。

**Parameters:**

| 参数 | Type | Description |
| :- | :- | :- |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | 记录类型。 |

**Returns**

| Type | Description |
| :- | :- |
| [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) |  |


