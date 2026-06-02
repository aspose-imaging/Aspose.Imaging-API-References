---
title: "DicomPage"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "C'est une classe pour travailler avec les fichiers DICOM de type multi‑frame."
type: docs
weight: 15
url: /fr/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

C'est une classe pour travailler avec les fichiers DICOM de type multi‑frame.
## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Initialise une nouvelle instance de la classe `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Initialise une nouvelle instance de la classe `DicomPage`. |
## Méthodes

| Méthode | Description |
| --- | --- |
| [getIndex()](#getIndex--) | Obtient l'index de la page actuelle. |
| [getWidth()](#getWidth--) | Obtient la largeur de l'image. |
| [getHeight()](#getHeight--) | Obtient la hauteur de l'image. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Obtient le nombre de bits par pixel de l'image. |
| [getFileFormat()](#getFileFormat--) | Obtient une valeur du format de fichier |

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
        // Dessinez quelque chose en utilisant des graphiques vectoriels.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Enregistrez les pixels de l'image dessinée. Ils se trouvent maintenant sur la première page de l'image Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Ajoutez quelques pages après, les rendant plus sombres.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Ajoutez quelques pages avant la page principale, les rendant plus claires.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Enregistrez l'image multipage créée dans le fichier de sortie.
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Initialise une nouvelle instance de la classe `DicomPage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | L'image. |
| index | int | L'index. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Initialise une nouvelle instance de la classe `DicomPage`.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | L'image. |
| index | int | L'index. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Les options de chargement. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Obtient l'index de la page actuelle.

Valeur: l'index.

**Returns:**
int - l'index de la page actuelle.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Obtient la largeur de l'image.

Valeur : la largeur de l'image.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Obtient la hauteur de l'image.

Valeur : la hauteur de l'image.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Obtient le nombre de bits par pixel de l'image.

Valeur : le nombre de bits par pixel de l'image.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Obtient une valeur du format de fichier

**Returns:**
long
