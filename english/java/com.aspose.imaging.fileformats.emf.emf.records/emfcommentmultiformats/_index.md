---
title: EmfCommentMultiFormats
second_title: Aspose.Imaging for Java API Reference
description: The EMR_COMMENT_MULTIFORMATS record specifies an image in multiple graphics formats.
type: docs
weight: 30
url: /java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentmultiformats/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentMultiFormats extends EmfCommentPublicRecordType
```

The EMR\_COMMENT\_MULTIFORMATS record specifies an image in multiple graphics formats.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfCommentMultiFormats(EmfRecord source)](#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Initializes a new instance of the `EmfCommentMultiFormats` class. |
## Methods

| Method | Description |
| --- | --- |
| [getOutputRect()](#getOutputRect--) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle, in logical coordinates. |
| [setOutputRect(Rectangle value)](#setOutputRect-com.aspose.imaging.Rectangle-) | Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle, in logical coordinates. |
| [getAFormats()](#getAFormats--) | Gets or sets a CountFormats length array of graphics formats, specified by EmrFormat objects (section 2.2.4), in order of preference |
| [setAFormats(EmfFormat[] value)](#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---) | Gets or sets a CountFormats length array of graphics formats, specified by EmrFormat objects (section 2.2.4), in order of preference |
| [getFormatData()](#getFormatData--) | Gets or sets a variable-length array of bytes of image data for all graphics formats contained in this record. |
| [setFormatData(byte[][] value)](#setFormatData-byte-----) | Gets or sets a variable-length array of bytes of image data for all graphics formats contained in this record. |
### EmfCommentMultiFormats(EmfRecord source) {#EmfCommentMultiFormats-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentMultiFormats(EmfRecord source)
```


Initializes a new instance of the `EmfCommentMultiFormats` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | The source. |

### getOutputRect() {#getOutputRect--}
```
public Rectangle getOutputRect()
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle, in logical coordinates.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setOutputRect(Rectangle value) {#setOutputRect-com.aspose.imaging.Rectangle-}
```
public void setOutputRect(Rectangle value)
```


Gets or sets a WMF RectL object ([MS-WMF] section 2.2.2.19) that specifies the output rectangle, in logical coordinates.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAFormats() {#getAFormats--}
```
public EmfFormat[] getAFormats()
```


Gets or sets a CountFormats length array of graphics formats, specified by EmrFormat objects (section 2.2.4), in order of preference

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat[]
### setAFormats(EmfFormat[] value) {#setAFormats-com.aspose.imaging.fileformats.emf.emf.objects.EmfFormat---}
```
public void setAFormats(EmfFormat[] value)
```


Gets or sets a CountFormats length array of graphics formats, specified by EmrFormat objects (section 2.2.4), in order of preference

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfFormat\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfformat) |  |

### getFormatData() {#getFormatData--}
```
public byte[][] getFormatData()
```


Gets or sets a variable-length array of bytes of image data for all graphics formats contained in this record. The size of the data for each image is provided by the DataSize field in the corresponding EmrFormat object. Thus, the total size of this field is the sum of DataSize values in all EmrFormat objects. The graphics format of the data for each image is specified by the Signature field in the corresponding EmrFormat object.

**Returns:**
byte[][]
### setFormatData(byte[][] value) {#setFormatData-byte-----}
```
public void setFormatData(byte[][] value)
```


Gets or sets a variable-length array of bytes of image data for all graphics formats contained in this record. The size of the data for each image is provided by the DataSize field in the corresponding EmrFormat object. Thus, the total size of this field is the sum of DataSize values in all EmrFormat objects. The graphics format of the data for each image is specified by the Signature field in the corresponding EmrFormat object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | byte[][] |  |

