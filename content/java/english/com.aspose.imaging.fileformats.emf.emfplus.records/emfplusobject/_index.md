---
title: EmfPlusObject
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusObject record specifies an object for use in graphics operations.
type: docs
weight: 42
url: /com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobject/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusObjectRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusobjectrecordtype)
```
public final class EmfPlusObject extends EmfPlusObjectRecordType
```

The EmfPlusObject record specifies an object for use in graphics operations. The object definition can span multiple records, which is indicated by the value of the Flags field.

The EmfPlusObject record is generic; it is used for all types of objects. Values that are specific to particular object types are contained in the ObjectData field. A conceptual model for managing graphics objects is described in Managing Graphics Objects (section 3.1.2).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusObject(EmfPlusRecord source)](#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Initializes a new instance of the `EmfPlusObject` class. |
## Methods

| Method | Description |
| --- | --- |
| [isContinuable()](#isContinuable--) | Gets or sets a value indicating whether this instance is continuable. |
| [setContinuable(boolean value)](#setContinuable-boolean-) | Gets or sets a value indicating whether this instance is continuable. |
| [getObjectType()](#getObjectType--) | Gets or sets the type of the object. |
| [setObjectType(byte value)](#setObjectType-byte-) | Gets or sets the type of the object. |
| [getObjectId()](#getObjectId--) | Gets or sets the object identifier. |
| [setObjectId(byte value)](#setObjectId-byte-) | Gets or sets the object identifier. |
| [getTotalObjectSize()](#getTotalObjectSize--) | Gets or sets the total size of the object. |
| [setTotalObjectSize(int value)](#setTotalObjectSize-int-) | Gets or sets the total size of the object. |
| [getObjectData()](#getObjectData--) | Gets or sets an array of bytes that contains data for the type of object specified in the Flags field. |
| [setObjectData(EmfPlusGraphicsObjectType value)](#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-) | Gets or sets an array of bytes that contains data for the type of object specified in the Flags field. |
### EmfPlusObject(EmfPlusRecord source) {#EmfPlusObject-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusObject(EmfPlusRecord source)
```


Initializes a new instance of the `EmfPlusObject` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | The source. |

### isContinuable() {#isContinuable--}
```
public boolean isContinuable()
```


Gets or sets a value indicating whether this instance is continuable. Indicates that the object definition continues on in the next EmfPlusObject record. This flag is never set in the final record that defines the object.

Value: `true` if this instance is compressed; otherwise, `false`.

**Returns:**
boolean
### setContinuable(boolean value) {#setContinuable-boolean-}
```
public void setContinuable(boolean value)
```


Gets or sets a value indicating whether this instance is continuable. Indicates that the object definition continues on in the next EmfPlusObject record. This flag is never set in the final record that defines the object.

Value: `true` if this instance is compressed; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### getObjectType() {#getObjectType--}
```
public byte getObjectType()
```


Gets or sets the type of the object.

Value: The type of the object.

**Returns:**
byte
### setObjectType(byte value) {#setObjectType-byte-}
```
public void setObjectType(byte value)
```


Gets or sets the type of the object.

Value: The type of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getObjectId() {#getObjectId--}
```
public byte getObjectId()
```


Gets or sets the object identifier. The index in the EMF+ Object Table to associate with the object created by this record. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Returns:**
byte
### setObjectId(byte value) {#setObjectId-byte-}
```
public void setObjectId(byte value)
```


Gets or sets the object identifier. The index in the EMF+ Object Table to associate with the object created by this record. The value MUST be zero to 63, inclusive.

Value: The object identifier.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte |  |

### getTotalObjectSize() {#getTotalObjectSize--}
```
public int getTotalObjectSize()
```


Gets or sets the total size of the object. If the record is continuable, when the continue bit is set, this field will be present. Continuing objects have multiple EMF+ records starting with EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+ record will not be treated as part of the continuing object.

Value: The total size of the object.

**Returns:**
int
### setTotalObjectSize(int value) {#setTotalObjectSize-int-}
```
public void setTotalObjectSize(int value)
```


Gets or sets the total size of the object. If the record is continuable, when the continue bit is set, this field will be present. Continuing objects have multiple EMF+ records starting with EmfPlusContineudObjectRecord. Each EmfPlusContinuedObjectRecord will contain a TotalObjectSize. Once TotalObjectSize number of bytes has been read, the next EMF+ record will not be treated as part of the continuing object.

Value: The total size of the object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getObjectData() {#getObjectData--}
```
public EmfPlusGraphicsObjectType getObjectData()
```


Gets or sets an array of bytes that contains data for the type of object specified in the Flags field. The content and format of the data can be different for each object type. See the individual object definitions in section 2.2.1 for additional information.

Value: The object data.

**Returns:**
[EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
### setObjectData(EmfPlusGraphicsObjectType value) {#setObjectData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType-}
```
public void setObjectData(EmfPlusGraphicsObjectType value)
```


Gets or sets an array of bytes that contains data for the type of object specified in the Flags field. The content and format of the data can be different for each object type. See the individual object definitions in section 2.2.1 for additional information.

Value: The object data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype) |  |

