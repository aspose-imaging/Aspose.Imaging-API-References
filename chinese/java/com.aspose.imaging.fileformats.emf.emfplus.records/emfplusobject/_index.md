---
title: "EmfPlusObject"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusObject 记录指定用于图形操作的对象。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

EmfPlusObject 记录指定用于图形操作的对象。对象定义可以跨多个记录，这由 Flags 字段的值指示。

EmfPlusObject 记录是通用的；它用于所有类型的对象。特定对象类型的值包含在 ObjectData 字段中。管理图形对象的概念模型在《Managing Graphics Objects》（第 3.1.2 节）中描述。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | 初始化 `EmfPlusObject` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [isContinuable()](#isContinuable--) | 获取或设置一个值，指示此实例是否可继续。 |
| [setContinuable(boolean value)](#setContinuable-boolean-) | 获取或设置一个值，指示此实例是否可继续。 |
| [getObjectType()](#getObjectType--) | 获取或设置对象的类型。 |
| [setObjectType(byte value)](#setObjectType-byte-) | 获取或设置对象的类型。 |
| [getObjectId()](#getObjectId--) | 获取或设置对象标识符。 |
| [setObjectId(byte value)](#setObjectId-byte-) | 获取或设置对象标识符。 |
| [getTotalObjectSize()](#getTotalObjectSize--) | 获取或设置对象的总大小。 |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | 获取或设置对象的总大小。 |
| [getObjectData()](#getObjectData--) | 获取或设置一个字节数组，包含 Flags 字段中指定的对象类型的数据。 |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | 获取或设置一个字节数组，包含 Flags 字段中指定的对象类型的数据。 |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


初始化 `EmfPlusObject` 类的新实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | 来源。 |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


获取或设置一个值，指示此实例是否可继续。表示对象定义在下一个 EmfPlusObject 记录中继续。此标志在定义对象的最终记录中永不设置。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


获取或设置一个值，指示此实例是否可继续。表示对象定义在下一个 EmfPlusObject 记录中继续。此标志在定义对象的最终记录中永不设置。

值：如果此实例已压缩则为 `true`；否则为 `false`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


获取或设置对象的类型。

值：对象的类型。

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


获取或设置对象的类型。

值：对象的类型。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


获取或设置对象标识符。EMF+ 对象表中与此记录创建的对象关联的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


获取或设置对象标识符。EMF+ 对象表中与此记录创建的对象关联的索引。该值必须在 0 到 63（含）之间。

值：对象标识符。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


获取或设置对象的总大小。如果记录是可继续的，当继续位被设置时，此字段将出现。可继续的对象具有多个 EMF+ 记录，起始于 EmfPlusContineudObjectRecord。每个 EmfPlusContinuedObjectRecord 都会包含 TotalObjectSize。读取完 TotalObjectSize 指定的字节数后，下一条 EMF+ 记录将不再视为该继续对象的一部分。

值：对象的总大小。

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


获取或设置对象的总大小。如果记录是可继续的，当继续位被设置时，此字段将出现。可继续的对象具有多个 EMF+ 记录，起始于 EmfPlusContineudObjectRecord。每个 EmfPlusContinuedObjectRecord 都会包含 TotalObjectSize。读取完 TotalObjectSize 指定的字节数后，下一条 EMF+ 记录将不再视为该继续对象的一部分。

值：对象的总大小。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


获取或设置一个字节数组，包含 Flags 字段中指定的对象类型的数据。数据的内容和格式可能因对象类型而异。有关更多信息，请参阅第 2.2.1 节中的各个对象定义。

值：对象数据。

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


获取或设置一个字节数组，包含 Flags 字段中指定的对象类型的数据。数据的内容和格式可能因对象类型而异。有关更多信息，请参阅第 2.2.1 节中的各个对象定义。

值：对象数据。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

