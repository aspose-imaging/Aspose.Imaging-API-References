---
title: "EmfSetWorldTransform 类"
type: docs
weight: 1370
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/
---

**Summary:** The EMR_SETWORLDTRANSFORM record specifies a transform for the current world-space to page space transform in the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.records](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/)

**Full Name:** aspose.imaging.fileformats.emf.emf.records.EmfSetWorldTransform

**Inheritance:** EmfTransformRecordType

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [EmfSetWorldTransform()](#EmfSetWorldTransform__1) | 初始化 [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) 类的新实例。 |
| [EmfSetWorldTransform(source)](#EmfSetWorldTransform_source_2) | 初始化 [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| size | int | r/w | 获取或设置记录的大小 |
| type | [EmfRecordType](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/) | r/w | 获取或设置类型。 |
| xform | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | 获取或设置 XForm 对象（第 2.2.28 节），该对象定义了从世界空间到页面空间的变换。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [create_from_record(source)](#create_from_record_source_1) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |
| [create_from_type(type)](#create_from_type_type_2) | 初始化 [EmfRecord](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfrecord/) 类的新实例。 |


### Constructor: EmfSetWorldTransform() {#EmfSetWorldTransform__1}


```
 EmfSetWorldTransform() 
```

初始化 [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) 类的新实例。

### Constructor: EmfSetWorldTransform(source) {#EmfSetWorldTransform_source_2}


```
 EmfSetWorldTransform(source) 
```

初始化 [EmfSetWorldTransform](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfsetworldtransform/) 类的新实例。

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


