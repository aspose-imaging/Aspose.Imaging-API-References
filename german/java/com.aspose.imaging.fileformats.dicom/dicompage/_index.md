---
title: "DicomPage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Es ist eine Klasse zur Arbeit mit DICOM-Dateien des Typs Mehrfachbild."
type: docs
weight: 15
url: /de/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

Es ist eine Klasse zur Arbeit mit DICOM-Dateien des Typs Mehrfachbild.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Initialisiert eine neue Instanz der `DicomPage`-Klasse. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Initialisiert eine neue Instanz der `DicomPage`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getIndex()](#getIndex--) | Liefert den Index der aktuellen Seite. |
| [getWidth()](#getWidth--) | Ermittelt die Bildbreite. |
| [getHeight()](#getHeight--) | Ermittelt die Bildhöhe. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes. |
| [getFileFormat()](#getFileFormat--) | Ruft einen Wert des Dateiformats ab |

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
        // Zeichnen Sie etwas mit Vektorgrafiken.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Speichern Sie die Pixel des gezeichneten Bildes. Sie befinden sich nun auf der ersten Seite des Dicom‑Bildes.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Fügen Sie ein paar Seiten danach hinzu und machen Sie sie dunkler.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Fügen Sie ein paar Seiten vor der Hauptseite hinzu und machen Sie sie heller.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Speichern Sie das erstellte mehrseitige Bild in der Ausgabedatei.
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Initialisiert eine neue Instanz der `DicomPage`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Das Bild. |
| index | int | Der Index. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Initialisiert eine neue Instanz der `DicomPage`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | Das Bild. |
| index | int | Der Index. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Liefert den Index der aktuellen Seite.

Wert: Der Index.

**Returns:**
int - der Index der aktuellen Seite.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Ermittelt die Bildbreite.

Wert: Die Bildbreite.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermittelt die Bildhöhe.

Wert: Die Bildhöhe.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Ermittelt die Bit‑Pro‑Pixel‑Anzahl des Bildes.

Wert: Die Bit‑Pro‑Pixel‑Anzahl des Bildes.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ruft einen Wert des Dateiformats ab

**Returns:**
long
