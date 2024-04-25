---
title: WmfSetLayout
second_title: Aspose.Imaging for Java API Reference
description: The META_SETLAYOUT record defines the layout orientation in the playback     device context.
type: docs
weight: 76
url: /com.aspose.imaging.fileformats.wmf.objects/wmfsetlayout/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfSetLayout extends WmfObject
```

The META\_SETLAYOUT record defines the layout orientation in the playback device context. The layout orientation determines the direction in which text and graphics are drawn
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfSetLayout()](#WmfSetLayout--) |  |
## Methods

| Method | Description |
| --- | --- |
| [getLayoutMode()](#getLayoutMode--) | Gets or sets the LayoutMode. |
| [setLayoutMode(int value)](#setLayoutMode-int-) | Gets or sets the LayoutMode. |
### WmfSetLayout() {#WmfSetLayout--}
```
public WmfSetLayout()
```


### getLayoutMode() {#getLayoutMode--}
```
public int getLayoutMode()
```


Gets or sets the LayoutMode.

Value: The layout of text and graphics. This MUST be one of the values in the Layout Enumeration (section 2.1.1.13).

**Returns:**
int
### setLayoutMode(int value) {#setLayoutMode-int-}
```
public void setLayoutMode(int value)
```


Gets or sets the LayoutMode.

Value: The layout of text and graphics. This MUST be one of the values in the Layout Enumeration (section 2.1.1.13).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

