---
title: "VectorMultipageImage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "La imagen multipágina Vector"
type: docs
weight: 118
url: /es/java/com.aspose.imaging/vectormultipageimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImage](../../com.aspose.imaging/imultipageimage)
```
public abstract class VectorMultipageImage extends VectorImage implements IMultipageImage
```

La imagen multipágina Vector
## Constructores

| Constructor | Descripción |
| --- | --- |
| [VectorMultipageImage()](#VectorMultipageImage--) |  |
## Métodos

| Método | Descripción |
| --- | --- |
| [isCached()](#isCached--) | Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getDefaultPage()](#getDefaultPage--) | Obtiene la página predeterminada. |
| [getPageExportingAction()](#getPageExportingAction--) | Obtiene la acción de exportación de la página. |
| [setPageExportingAction(PageExportingAction value)](#setPageExportingAction-com.aspose.imaging.PageExportingAction-) | Establece la acción de exportación de la página. |
| [getMetadata()](#getMetadata--) | Obtiene los metadatos de la imagen. |
| [cacheData()](#cacheData--) | Almacena en caché los datos y asegura que no se realice una carga adicional de datos desde el `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Recorta el rectángulo especificado. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Redimensiona la imagen. |
| [rotate(float angle)](#rotate-float-) | Rota la imagen alrededor del centro. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Redimensiona la imagen. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Rota, voltea o rota y voltea la imagen. |
| [removeBackground(RemoveBackgroundSettings settings)](#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-) | Elimina el fondo. |
| [removeBackground()](#removeBackground--) | Elimina el fondo. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Establece la paleta de la imagen. |
| [getEmbeddedImages()](#getEmbeddedImages--) | Obtiene las imágenes incrustadas. |
### VectorMultipageImage() {#VectorMultipageImage--}
```
public VectorMultipageImage()
```


### isCached() {#isCached--}
```
public boolean isCached()
```


Obtiene un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.

Valor: `true` si los datos del objeto están en caché; de lo contrario, `false`.

**Returns:**
boolean - un valor que indica si los datos del objeto están almacenados en caché actualmente y no se requiere lectura de datos.
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int - el recuento de bits por píxel de la imagen.
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
### getDefaultPage() {#getDefaultPage--}
```
public abstract Image getDefaultPage()
```


Obtiene la página predeterminada.

Valor: La página predeterminada.

**Returns:**
[Image](../../com.aspose.imaging/image) - the default page.
### getPageExportingAction() {#getPageExportingAction--}
```
public PageExportingAction getPageExportingAction()
```


Obtiene la acción de exportación de la página. Tenga en cuenta que establecer este método liberará automáticamente los recursos de la página después de que se ejecute. Se ejecutará justo antes de que cada página se guarde.

Valor: La acción de exportación de la página.

**Returns:**
[PageExportingAction](../../com.aspose.imaging/pageexportingaction) - the page exporting action.
### setPageExportingAction(PageExportingAction value) {#setPageExportingAction-com.aspose.imaging.PageExportingAction-}
```
public void setPageExportingAction(PageExportingAction value)
```


Establece la acción de exportación de la página. Tenga en cuenta que establecer este método liberará automáticamente los recursos de la página después de que se ejecute. Se ejecutará justo antes de que cada página se guarde.

Valor: La acción de exportación de la página.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| value | [PageExportingAction](../../com.aspose.imaging/pageexportingaction) | la acción de exportación de la página. |

### getMetadata() {#getMetadata--}
```
public ImageMetadata getMetadata()
```


Obtiene los metadatos de la imagen.

**Returns:**
[ImageMetadata](../../com.aspose.imaging.metadata/imagemetadata) - the image metadata.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Almacena en caché los datos y asegura que no se realice una carga adicional de datos desde el `DataStreamSupporter.getDataStreamContainer()`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Recorta el rectángulo especificado.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | El rectángulo. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| resizeType | int | El tipo de redimensionado. |

### rotate(float angle) {#rotate-float-}
```
public void rotate(float angle)
```


Rota la imagen alrededor del centro.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| angle | float | El ángulo de rotación en grados. Los valores positivos girarán en sentido horario. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Redimensiona la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| newWidth | int | El nuevo ancho. |
| newHeight | int | El nuevo alto. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | La configuración de redimensionado. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Rota, voltea o rota y voltea la imagen.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| rotateFlipType | int | Tipo de rotación e inversión. |

### removeBackground(RemoveBackgroundSettings settings) {#removeBackground-com.aspose.imaging.RemoveBackgroundSettings-}
```
public void removeBackground(RemoveBackgroundSettings settings)
```


Elimina el fondo.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| settings | [RemoveBackgroundSettings](../../com.aspose.imaging/removebackgroundsettings) | Los ajustes. |

### removeBackground() {#removeBackground--}
```
public void removeBackground()
```


Elimina el fondo.

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

### getEmbeddedImages() {#getEmbeddedImages--}
```
public EmbeddedImage[] getEmbeddedImages()
```


Obtiene las imágenes incrustadas.

**Returns:**
com.aspose.imaging.EmbeddedImage[] - Matriz de imágenes
