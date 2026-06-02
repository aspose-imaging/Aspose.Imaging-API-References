---
title: "DicomPage"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Es una clase para trabajar con archivos DICOM del tipo multicuadro."
type: docs
weight: 15
url: /es/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

Es una clase para trabajar con archivos DICOM del tipo multicuadro.
## Constructores

| Constructor | Descripción |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Inicializa una nueva instancia de la clase `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Inicializa una nueva instancia de la clase `DicomPage`. |
## Métodos

| Método | Descripción |
| --- | --- |
| [getIndex()](#getIndex--) | Obtiene el índice de la página actual. |
| [getWidth()](#getWidth--) | Obtiene el ancho de la imagen. |
| [getHeight()](#getHeight--) | Obtiene la altura de la imagen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtiene la cantidad de bits por píxel de la imagen. |
| [getFileFormat()](#getFileFormat--) | Obtiene un valor del formato de archivo |

## Example: Create a multi-page Dicom image.

``` java
        
try (DicomOptions dicomOptions = new DicomOptions())
{
    dicomOptions.setSource(new StreamSource());
    try (DicomImage image = (DicomImage) Image.create(
            dicomOptions,
            100,
            100))
    {
        // Dibuja algo usando gráficos vectoriales
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Guarda los píxeles de la imagen dibujada. Ahora están en la primera página de la imagen Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Añade algunas páginas después, oscureciéndolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Añade algunas páginas antes de la página principal, iluminándolas
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Guarda la imagen multipágina creada en el archivo de salida
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Inicializa una nueva instancia de la clase `DicomPage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | La imagen. |
| index | int | El índice. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Inicializa una nueva instancia de la clase `DicomPage`.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | La imagen. |
| index | int | El índice. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Las opciones de carga. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Obtiene el índice de la página actual.

Valor: El índice.

**Returns:**
int - el índice de la página actual.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtiene el ancho de la imagen.

Valor: El ancho de la imagen.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtiene la altura de la imagen.

Valor: La altura de la imagen.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtiene la cantidad de bits por píxel de la imagen.

Valor: El recuento de bits por píxel de la imagen.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtiene un valor del formato de archivo

**Returns:**
long
