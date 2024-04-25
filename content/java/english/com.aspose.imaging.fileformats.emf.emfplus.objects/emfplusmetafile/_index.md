---
title: EmfPlusMetafile
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusMetafileData object specifies a metafile that contains a graphics image
type: docs
weight: 55
url: /com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

The EmfPlusMetafileData object specifies a metafile that contains a graphics image
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Initializes a new instance of the `EmfPlusMetafile` class. |
## Methods

| Method | Description |
| --- | --- |
| [getType()](#getType--) | Gets or sets 32-bit unsigned integer that specifies the type of metafile that is embedded in the MetafileData field. |
| [setType(int value)](#setType-int-) | Gets or sets 32-bit unsigned integer that specifies the type of metafile that is embedded in the MetafileData field. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Gets or sets 32-bit unsigned integer that specifies the size in bytes of the metafile data in the MetafileData field |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Gets or sets 32-bit unsigned integer that specifies the size in bytes of the metafile data in the MetafileData field |
| [getMetafileData()](#getMetafileData--) | Gets or sets variable-length data that specifies the embedded metafile. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Gets or sets variable-length data that specifies the embedded metafile. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Initializes a new instance of the `EmfPlusMetafile` class.

### getType() {#getType--}
```
public int getType()
```


Gets or sets 32-bit unsigned integer that specifies the type of metafile that is embedded in the MetafileData field. This value MUST be defined in the MetafileDataType enumeration (section 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets 32-bit unsigned integer that specifies the type of metafile that is embedded in the MetafileData field. This value MUST be defined in the MetafileDataType enumeration (section 2.1.1.21).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Gets or sets 32-bit unsigned integer that specifies the size in bytes of the metafile data in the MetafileData field

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Gets or sets 32-bit unsigned integer that specifies the size in bytes of the metafile data in the MetafileData field

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Gets or sets variable-length data that specifies the embedded metafile. The content and format of the data can be different for each metafile type.

Graphics images are specified by EmfPlusImage objects (section 2.2.1.4). An EmfPlusMetafile object MUST be present in the ImageData field of an EmfPlusImage object if ImageTypeMetafile is specified in its Type field. This object is generic and is used for different types of data, including: A WMF metafile [MS-WMF]; WMF metafile which can be placed; An EMF metafile [MS-EMF]; An EMF+ metafile that specifies graphics operations with EMF+ records only; and An EMF+ metafile that specifies graphics operations with both EMF+ and EMF records. See section 2.2.2 for the specification of additional structure objects.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Gets or sets variable-length data that specifies the embedded metafile. The content and format of the data can be different for each metafile type.

Graphics images are specified by EmfPlusImage objects (section 2.2.1.4). An EmfPlusMetafile object MUST be present in the ImageData field of an EmfPlusImage object if ImageTypeMetafile is specified in its Type field. This object is generic and is used for different types of data, including: A WMF metafile [MS-WMF]; WMF metafile which can be placed; An EMF metafile [MS-EMF]; An EMF+ metafile that specifies graphics operations with EMF+ records only; and An EMF+ metafile that specifies graphics operations with both EMF+ and EMF records. See section 2.2.2 for the specification of additional structure objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[] |  |

