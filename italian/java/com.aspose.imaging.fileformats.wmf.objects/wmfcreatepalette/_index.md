---
title: "WmfCreatePalette"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_CREATEPALETTE crea un oggetto Palette, sezione 2.2.1.3."
type: docs
weight: 22
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

Il record META\_CREATEPALETTE crea un oggetto Palette (sezione 2.2.1.3).
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs il record. |
## Campi

| Campo | Descrizione |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | Il tag di inizio della palette |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | Ottiene la palette log. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Imposta la palette log. |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs il record.

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


Il tag di inizio della palette

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Ottiene la palette log.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Imposta la palette log.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | La palette logica. |

