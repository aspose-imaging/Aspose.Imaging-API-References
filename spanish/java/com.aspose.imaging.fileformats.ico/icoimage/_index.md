---
title: "IcoImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Manipule sin esfuerzo archivos de imagen ICO con nuestra API que admite varios formatos de archivo y tipos de fotogramas, incluidos PNG y BMP."
type: docs
weight: 10
url: /es/java/com.aspose.imaging.fileformats.ico/icoimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext)
```
public class IcoImage extends RasterCachedMultipageImage implements IMultipageImageExt
```

Manipule sin esfuerzo archivos de imagen ICO con nuestra API, que admite varios formatos de archivo y tipos de fotogramas, incluidos PNG y BMP. Personalice la configuración de bits por píxel y actualice las dimensiones de la imagen sin problemas, garantizando una representación óptima y compatibilidad para sus íconos en diferentes plataformas.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [IcoImage(int width, int height, IcoOptions options)](#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-) | Inicie la creación de imágenes ICO sin esfuerzo utilizando la clase [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). |
| [IcoImage(Image image, IcoOptions icoOptions)](#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diseñada para la simplicidad y eficiencia, la clase [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) le permite crear imágenes ICO con facilidad. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Recupere el formato de archivo sin esfuerzo con esta propiedad, lo que permite una integración fluida en su flujo de trabajo. |
| [getPageCount()](#getPageCount--) | Obtenga una visión inmediata de la estructura del documento con esta propiedad sencilla. |
| [getPages()](#getPages--) | Recupere información completa sobre las páginas del documento sin esfuerzo mediante esta propiedad. |
| [hasAlpha()](#hasAlpha--) | Determine si el canal alfa está presente en esta instancia con esta propiedad. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Amplíe su imagen ICO añadiendo una entrada de página de imagen, aprovechando el [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page)](#addPage-com.aspose.imaging.Image-) | Enriquezca su imagen ICO sin esfuerzo insertando una entrada de página de imagen usando la configuración predeterminada de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). |
| [addPage(Image page, IcoOptions icoOptions)](#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-) | Diversifique su imagen ICO sin esfuerzo integrando una entrada de imagen adaptada a sus necesidades con el [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) especificado. |
| [removePage(int index)](#removePage-int-) | Ajuste finamente su imagen ICO eliminando una entrada de imagen específica ubicada en el `` designado dentro del archivo. |
### IcoImage(int width, int height, IcoOptions options) {#IcoImage-int-int-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(int width, int height, IcoOptions options)
```


Inicie la creación de imágenes ICO sin esfuerzo utilizando la clase [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage). Este constructor le permite inicializar nuevas instancias de imágenes ICO especificando los parámetros de ancho, alto y opciones de creación. Con este constructor sencillo, puede adaptar las imágenes ICO a sus especificaciones exactas, garantizando una compatibilidad perfecta y una apariencia visual atractiva en diferentes plataformas y dispositivos.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| width | int | El ancho. |
| height | int | La altura. |
| options | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Las opciones de creación de ICO. |

### IcoImage(Image image, IcoOptions icoOptions) {#IcoImage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public IcoImage(Image image, IcoOptions icoOptions)
```


Diseñada para la simplicidad y la eficiencia, la clase [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) le permite crear imágenes ICO con facilidad. Este constructor inicializa una nueva instancia de la clase, proporcionando una base sólida para sus necesidades de manipulación de imágenes. Ya sea que esté desarrollando aplicaciones o mejorando interfaces de usuario, la clase [IcoImage](../../com.aspose.imaging.fileformats.ico/icoimage) simplifica la gestión de imágenes ICO, permitiéndole centrarse en ofrecer experiencias excepcionales.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [Image](../../com.aspose.imaging/image) | La imagen. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Las opciones de ICO. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Recupere el formato de archivo sin esfuerzo con esta propiedad, lo que permite una integración fluida en su flujo de trabajo. Al usar esta propiedad, obtiene acceso a información crítica sobre el formato de su archivo, garantizando compatibilidad y procesamiento eficiente.

**Returns:**
long
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Obtenga una visión inmediata de la estructura del documento con esta propiedad sencilla. Al invocar esta propiedad, recupera sin esfuerzo el número total de páginas contenidas en el archivo.

**Returns:**
int - el recuento de páginas.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Recupere información completa sobre las páginas del documento sin esfuerzo mediante esta propiedad. Al acceder a esta propiedad, obtiene una colección o matriz que contiene todas las páginas presentes en el documento.

**Returns:**
com.aspose.imaging.Image[] - las páginas.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Determine si el canal alfa está presente en esta instancia con esta propiedad. Ofrece una forma rápida de comprobar si la imagen o el documento contiene un canal alfa, lo cual es crucial para diversas tareas de procesamiento y renderizado de imágenes. Ideal para garantizar la compatibilidad y manejar efectos de transparencia en imágenes o documentos.

**Returns:**
boolean - un valor que indica si esta instancia tiene alfa.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public final void addPage(RasterImage page)
```


Amplíe su imagen ICO añadiendo una entrada de página de imagen, aprovechando el [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Este método incorpora sin problemas imágenes raster en su archivo ICO, convirtiéndolas a un formato PNG de 32 bits de alta calidad. Perfecto para mejorar sus archivos ICO con imágenes raster mientras garantiza una compatibilidad óptima y una calidad de renderizado superior.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | La imagen. |

### addPage(Image page) {#addPage-com.aspose.imaging.Image-}
```
public final void addPage(Image page)
```


Enriquezca su imagen ICO sin esfuerzo insertando una entrada de página de imagen usando la configuración predeterminada de [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions). Este método convierte convenientemente la imagen insertada a un formato PNG de 32 bits, garantizando compatibilidad y renderizado de alta calidad dentro de la imagen ICO. Perfecto para integrar sin problemas imágenes PNG en sus archivos ICO con facilidad y eficiencia.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | La imagen. |

### addPage(Image page, IcoOptions icoOptions) {#addPage-com.aspose.imaging.Image-com.aspose.imaging.imageoptions.IcoOptions-}
```
public final void addPage(Image page, IcoOptions icoOptions)
```


Diversifique su imagen ICO sin esfuerzo integrando una entrada de imagen adaptada a sus necesidades con el [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) especificado. Este método incorpora sin problemas la imagen según sus opciones personalizadas, garantizando flexibilidad y precisión en su archivo ICO.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| page | [Image](../../com.aspose.imaging/image) | La imagen. |
| icoOptions | [IcoOptions](../../com.aspose.imaging.imageoptions/icooptions) | Las opciones de ICO. |

### removePage(int index) {#removePage-int-}
```
public final void removePage(int index)
```


Ajuste finamente su imagen ICO eliminando una entrada de imagen específica ubicada en el `` designado dentro del archivo. Este método brinda un control preciso sobre la composición de su imagen, permitiéndole refinar su archivo ICO con facilidad.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| index | int | El índice. |

