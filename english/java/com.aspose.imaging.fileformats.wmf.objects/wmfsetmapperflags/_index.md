---
title: WmfSetMapperFlags
second_title: Aspose.Imaging for Java API Reference
description: The META_SETMAPPERFLAGS record defines the algorithm that the font     mapper uses when it maps logical fonts to physical fonts.
type: docs
weight: 78
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmfsetmapperflags/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetMapperFlags extends WmfObject
```

The META\_SETMAPPERFLAGS record defines the algorithm that the font mapper uses when it maps logical fonts to physical fonts.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfSetMapperFlags()](#WmfSetMapperFlags--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getMapperValues()](#getMapperValues--) | Gets or sets the mapper values. |
| [setMapperValues(int value)](#setMapperValues-int-) | Gets or sets the mapper values. |
### WmfSetMapperFlags() {#WmfSetMapperFlags--}
```
public WmfSetMapperFlags()
```


### getMapperValues() {#getMapperValues--}
```
public int getMapperValues()
```


Gets or sets the mapper values.

Value: The font mapper attempts to match a font aspect ratio to the current device aspect ratio. If bit zero is set, the mapper selects only matching fonts.

**Returns:**
int
### setMapperValues(int value) {#setMapperValues-int-}
```
public void setMapperValues(int value)
```


Gets or sets the mapper values.

Value: The font mapper attempts to match a font aspect ratio to the current device aspect ratio. If bit zero is set, the mapper selects only matching fonts.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

