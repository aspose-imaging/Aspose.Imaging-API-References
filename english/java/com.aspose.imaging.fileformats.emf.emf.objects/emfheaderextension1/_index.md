---
title: EmfHeaderExtension1
second_title: Aspose.Imaging for Java API Reference
description: The HeaderExtension1 object defines the first extension to the EMF metafile header.
type: docs
weight: 18
url: /java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

The HeaderExtension1 object defines the first extension to the EMF metafile header. It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL [OPENGL] records (section 2.3.9).
## Constructors

| Constructor | Description |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Gets or sets a 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Gets or sets a 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Gets or sets a 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Gets or sets a 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. |
| [getBOpenGl()](#getBOpenGl--) | Gets or sets a 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Gets or sets a 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Gets or sets a 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the size of the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Gets or sets a 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Gets or sets a 32-bit unsigned integer that specifies the offset to the PixelFormatDescriptor object. This MUST be 0x00000000 if no pixel format is set.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Gets or sets a 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. 0x00000000 OpenGL records are not present in the metafile. 0x00000001 OpenGL records are present in the metafile.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Gets or sets a 32-bit unsigned integer that indicates whether OpenGL commands are present in the metafile. 0x00000000 OpenGL records are not present in the metafile. 0x00000001 OpenGL records are present in the metafile.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

