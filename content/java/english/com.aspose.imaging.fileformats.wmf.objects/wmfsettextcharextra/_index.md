---
title: WmfSetTextCharExtra
second_title: Aspose.Imaging for Java API Reference
description: The META_SETTEXTCHAREXTRA record defines inter-character spacing for     text justification in the playback device context.
type: docs
weight: 86
url: /com.aspose.imaging.fileformats.wmf.objects/wmfsettextcharextra/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetTextCharExtra extends WmfObject
```

The META\_SETTEXTCHAREXTRA record defines inter-character spacing for text justification in the playback device context. Spacing is added to the white space between each character, including `` characters, when a line of justified text is output.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfSetTextCharExtra()](#WmfSetTextCharExtra--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getCharExtra()](#getCharExtra--) | Gets or sets the character extra. |
| [setCharExtra(int value)](#setCharExtra-int-) | Gets or sets the character extra. |
### WmfSetTextCharExtra() {#WmfSetTextCharExtra--}
```
public WmfSetTextCharExtra()
```


### getCharExtra() {#getCharExtra--}
```
public int getCharExtra()
```


Gets or sets the character extra.

Value: The amount of extra space, in logical units, to be added to each character. If the current mapping mode is not MM\_TEXT, this value is transformed and rounded to the nearest pixel. For details about setting the mapping mode, see META\_SETMAPMODE (section 2.3.5.17).

**Returns:**
int
### setCharExtra(int value) {#setCharExtra-int-}
```
public void setCharExtra(int value)
```


Gets or sets the character extra.

Value: The amount of extra space, in logical units, to be added to each character. If the current mapping mode is not MM\_TEXT, this value is transformed and rounded to the nearest pixel. For details about setting the mapping mode, see META\_SETMAPMODE (section 2.3.5.17).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

