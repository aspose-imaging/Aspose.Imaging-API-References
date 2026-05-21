---
title: "DjvuPage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Clase de página Djvu"
type: docs
weight: 11
url: /es/java/com.aspose.imaging.fileformats.djvu/djvupage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DjvuPage extends RasterCachedImage
```

Clase de página Djvu
## Campos

| Campo | Descripción |
| --- | --- |
| [PageExportedAction](#PageExportedAction) | Ocurre cuando [page exported action]. |
| [PropertyChanged](#PropertyChanged) | Ocurre cuando cambia el valor de una propiedad. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getParentImage()](#getParentImage--) | Obtiene la imagen principal a la que pertenece la página |
| [getWidth()](#getWidth--) | Obtiene el ancho de la página |
| [getHeight()](#getHeight--) | Obtiene la altura de la página |
| [getImage()](#getImage--) | Obtiene la imagen. |
| [getThumbnailImage()](#getThumbnailImage--) | Obtiene o establece la imagen en miniatura para la página |
| [setThumbnailImage(DjvuRaster value)](#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-) | Obtiene o establece la imagen en miniatura para la página |
| [getPageNumber()](#getPageNumber--) | Obtiene el número de página. |
| [isColor()](#isColor--) | Obtiene un valor que indica si esta instancia es a color. |
| [getTextForLocation(Rectangle rect)](#getTextForLocation-com.aspose.imaging.Rectangle-) | Obtiene el texto para la ubicación del rectángulo |
| [getForegroundImage()](#getForegroundImage--) | Obtiene la imagen de primer plano para la página |
| [getForegroundImage(int subsample)](#getForegroundImage-int-) | Obtiene la imagen de primer plano para la página |
| [getTextImage()](#getTextImage--) | Obtiene la imagen de texto. |
| [getTextImage(int subsample)](#getTextImage-int-) | Obtiene la imagen de texto. |
| [getBackgroundImage()](#getBackgroundImage--) | Obtiene la imagen de fondo. |
| [extractThumbnailImage()](#extractThumbnailImage--) | Extrae la imagen en miniatura de la página Djvu. |
### PageExportedAction {#PageExportedAction}
```
public static final DefEvent<OnPageExportedAction> PageExportedAction
```


Ocurre cuando [page exported action].

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Ocurre cuando cambia el valor de una propiedad.

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int
### getParentImage() {#getParentImage--}
```
public DjvuImage getParentImage()
```


Obtiene la imagen principal a la que pertenece la página

Valor: El documento.

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la página

Valor: El ancho.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la página

Valor: La altura.

**Returns:**
int
### getImage() {#getImage--}
```
public DjvuRaster getImage()
```


Obtiene la imagen.

Valor: La imagen.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### getThumbnailImage() {#getThumbnailImage--}
```
public DjvuRaster getThumbnailImage()
```


Obtiene o establece la imagen en miniatura para la página

Valor: La imagen en miniatura.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster)
### setThumbnailImage(DjvuRaster value) {#setThumbnailImage-com.aspose.imaging.fileformats.djvu.DjvuRaster-}
```
public void setThumbnailImage(DjvuRaster value)
```


Obtiene o establece la imagen en miniatura para la página

Valor: La imagen en miniatura.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) |  |

### getPageNumber() {#getPageNumber--}
```
public int getPageNumber()
```


Obtiene el número de página.

Valor: El número de página.

**Returns:**
int

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Cargar una imagen DJVU desde un flujo de archivo.
java.io.FileInputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
    try {
        System.out.println("The total number of pages: " + djvuImage.getPages().length);
        System.out.println("The active page number:    " + djvuImage.getActivePage().getPageNumber());
        System.out.println("The first page number:     " + djvuImage.getFirstPage().getPageNumber());
        System.out.println("The last page number:      " + djvuImage.getLastPage().getPageNumber());

        for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
            System.out.println("--------------------------------------------------");
            System.out.println("Page number:     " + djvuPage.getPageNumber());
            System.out.println("Page size:       " + djvuPage.getSize());
            System.out.println("Page raw format: " + djvuPage.getRawDataFormat());
        }
    } finally {
        djvuImage.dispose();
    }
} finally {
    stream.close();
}

//La salida puede verse así:
//El número total de páginas: 2
//El número de página activo:    1
//El número de la primera página:     1
//El número de la última página:      2
//--------------------------------------------------
//Número de página:     1
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
//--------------------------------------------------
//Número de página:     2
//Tamaño de página:       { Width = 2481, Height = 3508}
//Formato bruto de página: RgbIndexed1Bpp, canales usados: 1
```

### isColor() {#isColor--}
```
public boolean isColor()
```


Obtiene un valor que indica si esta instancia es a color.

Valor: `true` si esta instancia es de color; de lo contrario, `false`.

**Returns:**
boolean
### getTextForLocation(Rectangle rect) {#getTextForLocation-com.aspose.imaging.Rectangle-}
```
public String getTextForLocation(Rectangle rect)
```


Obtiene el texto para la ubicación del rectángulo

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo de ubicación. |

**Returns:**
java.lang.String - Texto encontrado en la ubicación
### getForegroundImage() {#getForegroundImage--}
```
public DjvuRaster getForegroundImage()
```


Obtiene la imagen de primer plano para la página

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getForegroundImage(int subsample) {#getForegroundImage-int-}
```
public DjvuRaster getForegroundImage(int subsample)
```


Obtiene la imagen de primer plano para la página

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| submuestreo | int | El submuestreo. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - Bitmap image
### getTextImage() {#getTextImage--}
```
public DjvuRaster getTextImage()
```


Obtiene la imagen de texto.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getTextImage(int subsample) {#getTextImage-int-}
```
public DjvuRaster getTextImage(int subsample)
```


Obtiene la imagen de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| submuestreo | int | El submuestreo. |

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### getBackgroundImage() {#getBackgroundImage--}
```
public DjvuRaster getBackgroundImage()
```


Obtiene la imagen de fondo.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The bitmap
### extractThumbnailImage() {#extractThumbnailImage--}
```
public DjvuRaster extractThumbnailImage()
```


Extrae la imagen en miniatura de la página Djvu.

**Returns:**
[DjvuRaster](../../com.aspose.imaging.fileformats.djvu/djvuraster) - The DjVu raster image.
