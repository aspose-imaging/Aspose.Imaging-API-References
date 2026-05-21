---
title: "CdrImagePage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La página de imagen Cdr"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.cdr/cdrimagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cdr.ICdrImage](../../com.aspose.imaging.fileformats.cdr/icdrimage)
```
public class CdrImagePage extends VectorImage implements ICdrImage
```

La página de imagen Cdr
## Métodos

| Método | Descripción |
| --- | --- |
| [getParentImage()](#getParentImage--) | Obtiene la imagen padre. |
| [getPageNumber()](#getPageNumber--) | Obtiene el número de página. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getCdrDocument()](#getCdrDocument--) | Obtiene el documento CDR. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [cacheData()](#cacheData--) | Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` subyacente. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Establece la paleta de la imagen. |
### getParentImage() {#getParentImage--}
```
public final CdrImage getParentImage()
```


Obtiene la imagen padre.

Valor: La imagen padre.

**Returns:**
[CdrImage](../../com.aspose.imaging.fileformats.cdr/cdrimage) - the parent image.
### getPageNumber() {#getPageNumber--}
```
public final int getPageNumber()
```


Obtiene el número de página.

Valor: El número de página.

**Returns:**
int - el número de página.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - el recuento de bits por píxel de la imagen.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene un valor del formato de archivo

**Returns:**
long - un valor del formato de archivo
### getCdrDocument() {#getCdrDocument--}
```
public final CdrDocument getCdrDocument()
```


Obtiene el documento CDR.

Valor: El documento CDR.

**Returns:**
[CdrDocument](../../com.aspose.imaging.fileformats.cdr.objects/cdrdocument) - the CDR document.
### getDefaultOptions(Object[] args) {#getDefaultOptions-java.lang.Object---}
```
public ImageOptionsBase getDefaultOptions(Object[] args)
```


Obtiene las opciones predeterminadas.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| args | java.lang.Object[] | Los argumentos. |

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - Default options
### cacheData() {#cacheData--}
```
public synchronized void cacheData()
```


Almacena en caché los datos y asegura que no se realizará carga adicional de datos desde el `P:com.aspose.imaging.dataStreamSupporter.dataStreamContainer` subyacente.

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Establece la paleta de la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | La paleta a establecer. |
| updateColors | boolean | si se establece en `true` los colores se actualizarán según la nueva paleta; de lo contrario, los índices de color permanecerán sin cambios. Tenga en cuenta que los índices sin cambios pueden provocar un error al cargar la imagen si algunos índices no tienen entradas correspondientes en la paleta. |

