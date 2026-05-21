---
title: "DicomPage"
second_title: "Aspose.Imaging för Java API-referens"
description: "Det är en klass för att arbeta med DICOM-filer av typen multi frame"
type: docs
weight: 15
url: /sv/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

Det är en klass för att arbeta med DICOM-filer av typen multi frame
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Initierar en ny instans av klassen `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Initierar en ny instans av klassen `DicomPage`. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getIndex()](#getIndex--) | Hämtar indexet för den aktuella sidan. |
| [getWidth()](#getWidth--) | Hämtar bildens bredd. |
| [getHeight()](#getHeight--) | Hämtar bildens höjd. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Hämtar antalet bildbitar per pixel. |
| [getFileFormat()](#getFileFormat--) | Hämtar ett värde för filformat. |

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
        // Rita något med vektorgrafik.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Spara pixlarna i den ritade bilden. De finns nu på den första sidan av DICOM-bilden.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Lägg till några sidor efter, vilket gör dem mörkare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Lägg till några sidor framför huvudsidan, vilket gör dem ljusare.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Spara den skapade flersidiga bilden till utdatafilen.
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Initierar en ny instans av klassen `DicomPage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Bilden. |
| index | int | Indexet. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Initierar en ny instans av klassen `DicomPage`.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Bilden. |
| index | int | Indexet. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Laddningsalternativen. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Hämtar indexet för den aktuella sidan.

Värde: Indexet.

**Returns:**
int – indexet för den aktuella sidan.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Hämtar bildens bredd.

Värde: Bildens bredd.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Hämtar bildens höjd.

Värde: Bildens höjd.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Hämtar antalet bildbitar per pixel.

Värde: Bildens bitar per pixel-antal.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Hämtar ett värde för filformat.

**Returns:**
long
