---
title: "DicomPage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "È una classe per lavorare con file DICOM di tipo multi frame."
type: docs
weight: 15
url: /it/java/com.aspose.imaging.fileformats.dicom/dicompage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class DicomPage extends RasterCachedImage
```

È una classe per lavorare con file DICOM di tipo multi frame.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [DicomPage(DicomImage image, int index)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-) | Inizializza una nuova istanza della classe `DicomPage`. |
| [DicomPage(DicomImage image, int index, LoadOptions loadOptions)](#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-) | Inizializza una nuova istanza della classe `DicomPage`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getIndex()](#getIndex--) | Restituisce l'indice della pagina corrente. |
| [getWidth()](#getWidth--) | Restituisce la larghezza dell'immagine. |
| [getHeight()](#getHeight--) | Restituisce l'altezza dell'immagine. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Restituisce il conteggio dei bit per pixel dell'immagine. |
| [getFileFormat()](#getFileFormat--) | Ottiene un valore del formato file |

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
        // Disegna qualcosa usando la grafica vettoriale.
        Graphics graphics = new Graphics(image);
        graphics.fillRectangle(new SolidBrush(Color.getBlueViolet()), image.getBounds());
        graphics.fillRectangle(new SolidBrush(Color.getAqua()), 10, 20, 50, 20);
        graphics.fillEllipse(new SolidBrush(Color.getOrange()), 30, 50, 70, 30);

        // Salva i pixel dell'immagine disegnata. Ora si trovano nella prima pagina dell'immagine Dicom.
        int[] pixels = image.loadArgb32Pixels(image.getBounds());

        // Aggiungi alcune pagine dopo, rendendole più scure.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.addPage();
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(i * 30);
        }

        // Aggiungi alcune pagine davanti alla pagina principale, rendendole più luminose.
        for (int i = 1; i < 5; i++)
        {
            DicomPage page = image.insertPage(0);
            page.saveArgb32Pixels(page.getBounds(), pixels);
            page.adjustBrightness(-i * 30);
        }

        // Salva l'immagine multipagina creata nel file di output.
        image.save("MultiPage.dcm");
    }
}
```

### DicomPage(DicomImage image, int index) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-}
```
public DicomPage(DicomImage image, int index)
```


Inizializza una nuova istanza della classe `DicomPage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | L'immagine. |
| index | int | L'indice. |

### DicomPage(DicomImage image, int index, LoadOptions loadOptions) {#DicomPage-com.aspose.imaging.fileformats.dicom.DicomImage-int-com.aspose.imaging.LoadOptions-}
```
public DicomPage(DicomImage image, int index, LoadOptions loadOptions)
```


Inizializza una nuova istanza della classe `DicomPage`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| image | [DicomImage](../../com.aspose.imaging.fileformats.dicom/dicomimage) | L'immagine. |
| index | int | L'indice. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Le opzioni di caricamento. |

### getIndex() {#getIndex--}
```
public final int getIndex()
```


Restituisce l'indice della pagina corrente.

Valore: L'indice.

**Returns:**
int - l'indice della pagina corrente.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Restituisce la larghezza dell'immagine.

Valore: la larghezza dell'immagine.

**Returns:**
int
### getHeight() {#getHeight--}
```
public int getHeight()
```


Restituisce l'altezza dell'immagine.

Valore: l'altezza dell'immagine.

**Returns:**
int
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Restituisce il conteggio dei bit per pixel dell'immagine.

Valore: il conteggio dei bit per pixel dell'immagine.

**Returns:**
int
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Ottiene un valore del formato file

**Returns:**
long
