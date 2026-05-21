---
title: "WmfCreatePalette"
second_title: "Aspose.Imaging for Java API Referansı"
description: "META_CREATEPALETTE kaydı, Bölüm 2.2.1.3'te bir Palet Nesnesi oluşturur."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

META\_CREATEPALETTE kaydı, bir Palette Nesnesi (bölüm 2.2.1.3) oluşturur.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs kaydı. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | Palet başlangıç etiketi |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | Log paleti alır. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Log paletini ayarlar. |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs kaydı.

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


Palet başlangıç etiketi

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Log paleti alır.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Log paletini ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | Mantıksal palet. |

