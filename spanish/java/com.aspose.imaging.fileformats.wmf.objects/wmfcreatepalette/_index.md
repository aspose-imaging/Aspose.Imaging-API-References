---
title: "WmfCreatePalette"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El registro META_CREATEPALETTE crea un objeto de paleta sección 2.2.1.3."
type: docs
weight: 22
url: /es/java/com.aspose.imaging.fileformats.wmf.objects/wmfcreatepalette/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject)
```
public class WmfCreatePalette extends WmfGraphicObject
```

El registro META\_CREATEPALETTE crea un objeto Palette (sección 2.2.1.3).
## Constructores

| Constructor | Descripción |
| --- | --- |
| [WmfCreatePalette()](#WmfCreatePalette--) | WMFs el registro. |
## Campos

| Campo | Descripción |
| --- | --- |
| [PALETTE_START](#PALETTE-START) | La etiqueta de inicio de la paleta |
## Métodos

| Método | Descripción |
| --- | --- |
| [getLogPalette()](#getLogPalette--) | Obtiene la paleta lógica. |
| [setLogPalette(EmfLogPalette value)](#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-) | Establece la paleta lógica. |
### WmfCreatePalette() {#WmfCreatePalette--}
```
public WmfCreatePalette()
```


WMFs el registro.

### PALETTE_START {#PALETTE-START}
```
public static final int PALETTE_START
```


La etiqueta de inicio de la paleta

### getLogPalette() {#getLogPalette--}
```
public EmfLogPalette getLogPalette()
```


Obtiene la paleta lógica.

**Returns:**
[EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) - The logical palette.
### setLogPalette(EmfLogPalette value) {#setLogPalette-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogPalette-}
```
public void setLogPalette(EmfLogPalette value)
```


Establece la paleta lógica.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [EmfLogPalette](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogpalette) | La paleta lógica. |

