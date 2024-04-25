---
title: WmfCreatePalette
second_title: Aspose.Imaging for Java API Reference
description: The META_CREATEPALETTE record creates a Palette Object section 2.2.1.3.
type: docs
weight: 22
url: /com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

The META\_CREATEPALETTE record creates a Palette Object (section 2.2.1.3).
## Constructors

| Constructor | Description |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs the record. |
## Fields

| Field | Description |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | The palette start tag |
## Methods

| Method | Description |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | Gets the log palette. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Sets the log palette. |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs the record.

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


The palette start tag

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Gets the log palette.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Sets the log palette.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | The logical palette. |

