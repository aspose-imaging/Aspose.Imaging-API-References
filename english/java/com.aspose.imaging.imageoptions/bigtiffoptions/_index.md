---
title: BigTiffOptions
second_title: Aspose.Imaging for Java API Reference
description: The BigTiff image options.
type: docs
weight: 11
url: /java/com.aspose.imaging.imageoptions/bigtiffoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase), [com.aspose.imaging.imageoptions.TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions)
```
public final class BigTiffOptions extends TiffOptions
```

The BigTiff image options.
## Constructors

| Constructor | Description |
| --- | --- |
| [BigTiffOptions(int expectedFormat)](#BigTiffOptions-int-) | Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class. |
| [BigTiffOptions(TiffOptions options)](#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-) | Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class. |
| [BigTiffOptions(TiffDataType[] tags)](#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class. |
| [BigTiffOptions(int expectedFormat, int byteOrder)](#BigTiffOptions-int-int-) | Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class. |
## Methods

| Method | Description |
| --- | --- |
| [deepClone()](#deepClone--) | Clones this instance. |
### BigTiffOptions(int expectedFormat) {#BigTiffOptions-int-}
```
public BigTiffOptions(int expectedFormat)
```


Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class. By default little endian convention is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected Tiff file format. |

### BigTiffOptions(TiffOptions options) {#BigTiffOptions-com.aspose.imaging.imageoptions.TiffOptions-}
```
public BigTiffOptions(TiffOptions options)
```


Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| options | [TiffOptions](../../com.aspose.imaging.imageoptions/tiffoptions) | The options source. |

### BigTiffOptions(TiffDataType[] tags) {#BigTiffOptions-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public BigTiffOptions(TiffDataType[] tags)
```


Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | The tags for options initialization. |

### BigTiffOptions(int expectedFormat, int byteOrder) {#BigTiffOptions-int-int-}
```
public BigTiffOptions(int expectedFormat, int byteOrder)
```


Initializes a new instance of the [BigTiffOptions](../../com.aspose.imaging.imageoptions/bigtiffoptions) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| expectedFormat | int | The expected Tiff file format. |
| byteOrder | int | The tiff file format byte order to use. |

### deepClone() {#deepClone--}
```
public ImageOptionsBase deepClone()
```


Clones this instance.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Returns a deep clone.
