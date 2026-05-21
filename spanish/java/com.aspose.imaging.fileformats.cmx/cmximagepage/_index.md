---
title: "CmxImagePage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La imagen de la página CMX"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.cmx/cmximagepage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.ICmxImage](../../com.aspose.imaging.fileformats.cmx/icmximage)
```
public class CmxImagePage extends VectorImage implements ICmxImage
```

La imagen de la página CMX
## Constructores

| Constructor | Descripción |
| --- | --- |
| [CmxImagePage(CmxPage cmxPage, Image container)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-) | Inicializa una nueva instancia de la clase [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
| [CmxImagePage(CmxPage cmxPage)](#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-) | Inicializa una nueva instancia de la clase [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage). |
## Métodos

| Método | Descripción |
| --- | --- |
| [getCmxPage()](#getCmxPage--) | Obtiene la página CMX. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [getWidthF()](#getWidthF--) | Obtiene el ancho del objeto, en pulgadas. |
| [getHeightF()](#getHeightF--) | Obtiene la altura del objeto, en pulgadas. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getDefaultOptions(Object[] args)](#getDefaultOptions-java.lang.Object---) | Obtiene las opciones predeterminadas. |
| [cacheData()](#cacheData--) | No se puede usar la caché. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Establece la paleta de la imagen. |
### CmxImagePage(CmxPage cmxPage, Image container) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-com.aspose.imaging.Image-}
```
public CmxImagePage(CmxPage cmxPage, Image container)
```


Inicializa una nueva instancia de la clase [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La página CMX. |
| container | [Image](../../com.aspose.imaging/image) | El contenedor. |

### CmxImagePage(CmxPage cmxPage) {#CmxImagePage-com.aspose.imaging.fileformats.cmx.objectmodel.CmxPage-}
```
public CmxImagePage(CmxPage cmxPage)
```


Inicializa una nueva instancia de la clase [CmxImagePage](../../com.aspose.imaging.fileformats.cmx/cmximagepage).

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| cmxPage | [CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) | La página CMX. |

### getCmxPage() {#getCmxPage--}
```
public final CmxPage getCmxPage()
```


Obtiene la página CMX.

**Returns:**
[CmxPage](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxpage) - the CMX page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene un valor del formato de archivo

**Returns:**
long - un valor del formato de archivo
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

**Returns:**
int - el recuento de bits por píxel de la imagen.
### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.

Valor: `true` si los datos del objeto están en caché; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Obtiene el ancho del objeto, en pulgadas.

**Returns:**
float - el ancho del objeto, en pulgadas.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Obtiene la altura del objeto, en pulgadas.

**Returns:**
float - la altura del objeto, en pulgadas.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
int - el ancho de la imagen.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

Valor: La altura de la imagen.

**Returns:**
int - la altura de la imagen.
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
public void cacheData()
```


No se puede usar la caché.


**Example: The following example shows how to cache all pages of a CMX image.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen desde un archivo CMX.
com.aspose.imaging.fileformats.cmx.CmxImage image = (com.aspose.imaging.fileformats.cmx.CmxImage) com.aspose.imaging.Image.load(dir + "sample.cmx");
try {
    // Esta llamada almacena en caché solo la página predeterminada.
    image.cacheData();

    // Almacena en caché todas las páginas para que no se realice una carga de datos adicional desde el flujo de datos subyacente.
    for (com.aspose.imaging.fileformats.cmx.CmxImagePage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

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

