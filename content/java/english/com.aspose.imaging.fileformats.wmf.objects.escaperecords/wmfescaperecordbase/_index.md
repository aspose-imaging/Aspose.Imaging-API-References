---
title: WmfEscapeRecordBase
second_title: Aspose.Imaging for Java API Reference
description: The escape record base.
type: docs
weight: 12
url: /com.aspose.imaging.fileformats.wmf.objects.escaperecords/wmfescaperecordbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfEscapeRecordBase extends WmfObject
```

The escape record base.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfEscapeRecordBase()](#WmfEscapeRecordBase--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getByteCount()](#getByteCount--) | Gets or sets the byte count. |
| [setByteCount(int value)](#setByteCount-int-) | Gets or sets the byte count. |
| [getData()](#getData--) | Gets or sets the data. |
| [setData(byte[] value)](#setData-byte---) | Gets or sets the data. |
| [getChecked()](#getChecked--) | Gets a value indicating whether this `WmfEscapeRecordBase` is checked. |
| [setChecked(boolean value)](#setChecked-boolean-) | Gets a value indicating whether this `WmfEscapeRecordBase` is checked. |
### WmfEscapeRecordBase() {#WmfEscapeRecordBase--}
```
public WmfEscapeRecordBase()
```


### getByteCount() {#getByteCount--}
```
public int getByteCount()
```


Gets or sets the byte count.

Value: A 16-bit unsigned integer that specifies the size, in bytes, of the record data that follows. This value MUST be 34 plus the value of the EnhancedMetafileDataSize field.

**Returns:**
int
### setByteCount(int value) {#setByteCount-int-}
```
public void setByteCount(int value)
```


Gets or sets the byte count.

Value: A 16-bit unsigned integer that specifies the size, in bytes, of the record data that follows. This value MUST be 34 plus the value of the EnhancedMetafileDataSize field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Gets or sets the data.

Value: The data.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Gets or sets the data.

Value: The data.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

### getChecked() {#getChecked--}
```
public boolean getChecked()
```


Gets a value indicating whether this `WmfEscapeRecordBase` is checked.

Value: `true` if checked; otherwise, `false`.

**Returns:**
boolean
### setChecked(boolean value) {#setChecked-boolean-}
```
public void setChecked(boolean value)
```


Gets a value indicating whether this `WmfEscapeRecordBase` is checked.

Value: `true` if checked; otherwise, `false`.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

