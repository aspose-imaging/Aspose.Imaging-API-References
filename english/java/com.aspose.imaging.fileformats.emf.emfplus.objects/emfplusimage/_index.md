---
title: EmfPlusImage
second_title: Aspose.Imaging for Java API Reference
description: The EmfPlusImage object specifies a graphics image in the form of a bitmap or metafile.
type: docs
weight: 47
url: /java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

The EmfPlusImage object specifies a graphics image in the form of a bitmap or metafile.
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getImageData()](#getImageData--) | Gets or sets the Image data Variable-length data that defines the image data specified in the Type field. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Gets or sets the Image data Variable-length data that defines the image data specified in the Type field. |
| [getType()](#getType--) | Gets or sets image type A 32-bit unsigned integer that specifies the type of data in the ImageData field. |
| [setType(int value)](#setType-int-) | Gets or sets image type A 32-bit unsigned integer that specifies the type of data in the ImageData field. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Gets or sets the Image data Variable-length data that defines the image data specified in the Type field. The content and format of the data can be different for every image type.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Gets or sets the Image data Variable-length data that defines the image data specified in the Type field. The content and format of the data can be different for every image type.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Gets or sets image type A 32-bit unsigned integer that specifies the type of data in the ImageData field. This value MUST be defined in the ImageDataType enumeration (section 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets or sets image type A 32-bit unsigned integer that specifies the type of data in the ImageData field. This value MUST be defined in the ImageDataType enumeration (section 2.1.1.15).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

