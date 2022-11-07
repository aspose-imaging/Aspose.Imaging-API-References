---
title: WmfFillRegion
second_title: Aspose.Imaging for Java API Reference
description: The META_FILLREGION record fills a region using a specified brush.
type: docs
weight: 37
url: /java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

The META\_FILLREGION record fills a region using a specified brush.
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Initializes a new instance of the `WmfFillRegion` class. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Initializes a new instance of the `WmfFillRegion` class. |
## Methods

| Method | Description |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Gets or sets the index of the region. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Gets or sets the index of the region. |
| [getBrushIndex()](#getBrushIndex--) | Gets or sets the index of the brush. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Gets or sets the index of the brush. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Initializes a new instance of the `WmfFillRegion` class.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Initializes a new instance of the `WmfFillRegion` class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | The region. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | The brush. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Gets or sets the index of the region.

Value: Index into the WMF Object Table to get the region to be filled.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Gets or sets the index of the region.

Value: Index into the WMF Object Table to get the region to be filled.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Gets or sets the index of the brush.

Value: Index into the WMF Object Table to get the brush to use for filling the region.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Gets or sets the index of the brush.

Value: Index into the WMF Object Table to get the brush to use for filling the region.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

