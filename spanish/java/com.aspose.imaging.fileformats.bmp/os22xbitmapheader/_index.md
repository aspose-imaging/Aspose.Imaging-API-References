---
title: "Os22XBitmapHeader"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Un OS/2 2.x OS22XBITMAPHEADER también conocido como BITMAPCOREHEADER2."
type: docs
weight: 16
url: /es/java/com.aspose.imaging.fileformats.bmp/os22xbitmapheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class Os22XBitmapHeader extends BitmapInfoHeader
```

Un OS/2 2.x OS22XBITMAPHEADER también conocido como BITMAPCOREHEADER2.
## Métodos

| Método | Descripción |
| --- | --- |
| [getUnits()](#getUnits--) | Obtiene las unidades. |
| [getReserved()](#getReserved--) | Obtiene el reservado. |
| [getRecording()](#getRecording--) | Obtiene la grabación. |
| [getRendering()](#getRendering--) | Obtiene el renderizado. |
| [getSize1()](#getSize1--) | Obtiene el tamaño1. |
| [getSize2()](#getSize2--) | Obtiene el tamaño2. |
| [getColorEncoding()](#getColorEncoding--) | Obtiene la codificación de color. |
| [getIdentifier()](#getIdentifier--) | Obtiene el identificador. |
### getUnits() {#getUnits--}
```
public int getUnits()
```


Obtiene las unidades.

**Returns:**
int - Tipo de unidades usadas para medir la resolución
### getReserved() {#getReserved--}
```
public int getReserved()
```


Obtiene el reservado.

**Returns:**
int - Rellenar la estructura al límite de 4 bytes
### getRecording() {#getRecording--}
```
public int getRecording()
```


Obtiene la grabación.

**Returns:**
int - Algoritmo de grabación
### getRendering() {#getRendering--}
```
public int getRendering()
```


Obtiene el renderizado.

**Returns:**
int - Algoritmo de tramado usado
### getSize1() {#getSize1--}
```
public int getSize1()
```


Obtiene el tamaño1.

**Returns:**
int - Reservado para uso del algoritmo de tramado
### getSize2() {#getSize2--}
```
public int getSize2()
```


Obtiene el tamaño2.

**Returns:**
int - Reservado para uso del algoritmo de tramado
### getColorEncoding() {#getColorEncoding--}
```
public int getColorEncoding()
```


Obtiene la codificación de color.

**Returns:**
int - Modelo de color usado en el bitmap
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Obtiene el identificador.

**Returns:**
int - Reservado para uso de la aplicación
