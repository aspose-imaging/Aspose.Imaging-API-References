---
title: "DjvuImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die DjVu-Dokumentklasse unterstützt das Grafikdateiformat und ermöglicht eine nahtlose Verwaltung von gescannten Dokumenten und Büchern, indem Text, Zeichnungen, Bilder und Fotos in ein einziges Format integriert werden."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.djvu/djvuimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)
```
public final class DjvuImage extends RasterCachedMultipageImage
```

Die DjVu-Dokumentklasse unterstützt das Grafikdateiformat und ermöglicht eine nahtlose Verwaltung von gescannten Dokumenten und Büchern, indem Text, Zeichnungen, Bilder und Fotos in ein einziges Format integriert werden. Sie unterstützt Mehrseiten‑Operationen, sodass Sie effizient auf eindeutige Dokument‑IDs zugreifen, Seiten zählen, aktive Seiten festlegen und bestimmte Dokumentseiten abrufen können. Mit Funktionen zum Skalieren, Drehen, Dithern, Zuschneiden, Graustufen‑Transformation, Gamma‑Korrekturen, Anpassungen und zur Anwendung von Filtern ermöglicht diese Klasse eine präzise Manipulation und Verbesserung von DjVu‑Bildern, um vielfältige Anwendungsanforderungen mühelos und exakt zu erfüllen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DjvuImage(InputStream stream)](#DjvuImage-java.io.InputStream-) | Beginnen Sie mit DjVu‑Bildern zu arbeiten, indem Sie eine neue Instanz der [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)-Klasse mit einem Stream‑Parameter initialisieren. |
| [DjvuImage(InputStream stream, LoadOptions loadOptions)](#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Beginnen Sie nahtlos mit DjVu‑Bildern zu arbeiten, indem Sie diesen Konstruktor verwenden, der eine neue [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)-Klasseninstanz mit einem Stream‑ und LoadOptions‑Parameter initialisiert. |
| [DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)](#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-) | Beginnen Sie nahtlos mit DjVu‑Bildern zu arbeiten, indem Sie diesen Konstruktor verwenden, der eine neue [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage)-Klasseninstanz mit einem Stream‑ und LoadOptions‑Parameter initialisiert. |
## Felder

| Feld | Beschreibung |
| --- | --- |
| [PropertyChanged](#PropertyChanged) | Tritt auf, wenn ein Eigenschaftswert geändert wird. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [loadDocument(InputStream stream)](#loadDocument-java.io.InputStream-) | Laden Sie Ihr DjVu‑Dokument mit dieser Methode. |
| [loadDocument(InputStream stream, LoadOptions loadOptions)](#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-) | Lädt das Dokument. |
| [getIdentifier()](#getIdentifier--) | Liefert die eindeutige Kennung für das Dokument |
| [getPageCount()](#getPageCount--) | Rufen Sie die Gesamtzahl der Seiten in Ihrer DjVu-Bildsammlung mit dieser Eigenschaft ab. |
| [getPages()](#getPages--) | Greifen Sie mit dieser Eigenschaft auf die einzelnen Seiten Ihrer DjVu-Bildsammlung zu. |
| [getDjvuPages()](#getDjvuPages--) | Rufen Sie schnell alle Seiten, die in Ihrem DjVu-Dokument enthalten sind, mit dieser Eigenschaft ab. |
| [getActivePage()](#getActivePage--) | Navigieren Sie durch Ihr DjVu-Dokument, indem Sie die aktuell aktive Seite mit dieser Eigenschaft abrufen oder festlegen. |
| [setActivePage(DjvuPage value)](#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-) | Navigieren Sie durch Ihr DjVu-Dokument, indem Sie die aktuell aktive Seite mit dieser Eigenschaft abrufen oder festlegen. |
| [getFirstPage()](#getFirstPage--) | Greifen Sie mit dieser Eigenschaft auf die erste Seite Ihres DjVu-Dokuments zu. |
| [getLastPage()](#getLastPage--) | Rufen Sie die letzte Seite Ihres DjVu-Dokuments mit dieser Eigenschaft ab. |
| [getNextPage()](#getNextPage--) | Navigieren Sie durch Ihr DjVu-Dokument, indem Sie mit dieser praktischen Eigenschaft die nächste Seite aufrufen. |
| [getPreviousPage()](#getPreviousPage--) | Bewegen Sie sich schnell rückwärts in Ihrem DjVu-Dokument beim Anzeigen oder Verarbeiten, indem Sie mit dieser praktischen Eigenschaft die vorherige Seite aufrufen. |
| [getFileFormat()](#getFileFormat--) | Erhalten Sie die Dateiformatinformationen, die mit Ihrer DjVu-Bilddatei verknüpft sind. |
| [hasAlpha()](#hasAlpha--) | Bestimmen Sie schnell, ob Ihre DjVu-Bilddatei einen Alphakanal enthält. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Drehen Sie das Bild um sein Zentrum mit der Rotate-Methode der Klasse RasterCachedMultipageImage. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändern Sie die Größe des Bildes mit der \`Resize\`-Methode, die eine einfache und effektive Möglichkeit bietet, die Abmessungen Ihrer Bilder nach Ihren Anforderungen anzupassen. |
| [resizeWidthProportionally(int newWidth, int resizeType)](#resizeWidthProportionally-int-int-) | Die \`ResizeWidthProportionally\`-Methode bietet eine praktische Lösung, um die Breite Ihres Bildes anzupassen und gleichzeitig das Seitenverhältnis beizubehalten. |
| [resizeHeightProportionally(int newHeight, int resizeType)](#resizeHeightProportionally-int-int-) | Die \`ResizeHeightProportionally\`-Methode ermöglicht es Ihnen, die Höhe Ihres Bildes anzupassen und dabei das Seitenverhältnis zu erhalten. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Die \`RotateFlip\`-Methode bietet vielseitige Manipulationsoptionen für Ihr Bild, sodass Sie das aktive Bildrahmen unabhängig drehen, spiegeln oder beide Vorgänge ausführen können. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Die \"Dither\"-Funktion wendet einen Dithering-Effekt auf Ihr Bild an und verbessert dessen visuelle Qualität, indem sie Banding reduziert und Farbübergänge verbessert. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | \"Crop\" schneidet Ihr Bild zu, um sich auf bestimmte Details zu konzentrieren oder unerwünschte Elemente zu entfernen, und verbessert dadurch die Komposition und visuelle Wirkung. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Crop with shifts ermöglicht es Ihnen, die Position und Abmessungen des beschnittenen Bereichs innerhalb eines Bildes präzise anzupassen. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Die Binärisierung mit einem vordefinierten Schwellenwert vereinfacht komplexe Bilder zu binären Darstellungen, wobei Pixel basierend auf ihrer Intensität im Vergleich zu einem angegebenen Schwellenwert entweder als Schwarz oder Weiß kategorisiert werden. |
| [binarizeOtsu()](#binarizeOtsu--) | Die Binärisierung mittels Otsu-Schwellenwertbestimmung ist eine Technik, die automatisch einen optimalen Schwellenwert basierend auf dem Histogramm des Bildes berechnet. |
| [binarizeBradley(double brightnessDifference, int windowSize)](#binarizeBradley-double-int-) | Die Binärisierung mit Bradleys adaptivem Schwellenwertalgorithmus und Integralbild-Schwellenwertbestimmung ist ein Verfahren, das für jedes Pixel einen lokalen Schwellenwert basierend auf einer lokalen Nachbarschaft berechnet. |
| [grayscale()](#grayscale--) | Die Graustufentransformation wandelt ein Bild in eine Schwarz-Weiß-Darstellung um, wobei die Intensität jedes Pixels durch einen einzelnen Wert von Schwarz bis Weiß repräsentiert wird. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Die Gamma-Korrektur, speziell für die Rot-, Grün- und Blaukanäle, beinhaltet die separate Anpassung der Helligkeit jeder Farbkomponente. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Gamma-Korrektur wird auf ein Bild mit anpassbaren Parametern für die Rot-, Grün- und Blaukanäle angewendet, wodurch eine präzise Einstellung von Farbbalance und Helligkeit ermöglicht wird. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Passen Sie die `brightness` eines Bildes mit einem angegebenen Parameter an und erhalten Sie Kontrolle über die Luminanzwerte für optimale visuelle Klarheit. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Verbessern Sie den Kontrast von [Image](../../com.aspose.imaging/image), um die visuelle Klarheit zu erhöhen und Details hervorzuheben, mit dieser Methode, die den Unterschied in der Helligkeit zwischen hellen und dunklen Bereichen anpasst. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Wenden Sie Filter auf einen angegebenen rechteckigen Bereich im Bild an, um dessen Aussehen zu verbessern oder zu verändern. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändern Sie die Größe des Bildes auf die angegebene Breite und Höhe, wobei bei Bedarf zusätzliche Einstellungen angewendet werden. |
| [cacheData()](#cacheData--) | Speichern Sie die Daten privat im Cache, um die Leistung zu optimieren und den Bedarf an wiederholten Datenabrufen aus externen Quellen zu reduzieren. |

## Example: This example shows how to load a DJVU image from a file stream.

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Speichern Sie jede Seite als einzelnes PNG-Bild.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generieren Sie einen Dateinamen basierend auf der Seitennummer.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### DjvuImage(InputStream stream) {#DjvuImage-java.io.InputStream-}
```
public DjvuImage(InputStream stream)
```


Beginnen Sie mit DjVu-Bildern zu arbeiten, indem Sie eine neue Instanz der Klasse [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) mit einem Stream-Parameter initialisieren. Perfekt für Entwickler, die eine nahtlose Integration der DjVu-Bildverarbeitung in ihre Projekte wünschen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |

### DjvuImage(InputStream stream, LoadOptions loadOptions) {#DjvuImage-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(InputStream stream, LoadOptions loadOptions)
```


Arbeiten Sie nahtlos mit DjVu-Bildern, indem Sie diesen Konstruktor verwenden, der eine neue Instanz der Klasse [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) mit einem Stream- und LoadOptions-Parameter initialisiert. Perfekt für Entwickler, die präzise Kontrolle über DjVu-Bildladeoptionen wünschen und dabei Einfachheit und Effizienz beibehalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream, aus dem geladen werden soll. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### DjvuImage(System.IO.Stream stream, LoadOptions loadOptions) {#DjvuImage-com.aspose.ms.System.IO.Stream-com.aspose.imaging.LoadOptions-}
```
public DjvuImage(System.IO.Stream stream, LoadOptions loadOptions)
```


Arbeiten Sie nahtlos mit DjVu-Bildern, indem Sie diesen Konstruktor verwenden, der eine neue Instanz der Klasse [DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) mit einem Stream- und LoadOptions-Parameter initialisiert. Perfekt für Entwickler, die präzise Kontrolle über DjVu-Bildladeoptionen wünschen und dabei Einfachheit und Effizienz beibehalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | com.aspose.ms.System.IO.Stream | Der Stream, aus dem geladen werden soll. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

### PropertyChanged {#PropertyChanged}
```
public final StdEvent<System.ComponentModel.PropertyChangedEventArgs> PropertyChanged
```


Tritt auf, wenn ein Eigenschaftswert geändert wird.

### loadDocument(InputStream stream) {#loadDocument-java.io.InputStream-}
```
public static DjvuImage loadDocument(InputStream stream)
```


Laden Sie Ihr DjVu-Dokument mit dieser Methode. Optimieren Sie Ihren Prozess, indem Sie Ihre DjVu-Dateien schnell zugreifen und in Ihre Anwendung importieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### loadDocument(InputStream stream, LoadOptions loadOptions) {#loadDocument-java.io.InputStream-com.aspose.imaging.LoadOptions-}
```
public static DjvuImage loadDocument(InputStream stream, LoadOptions loadOptions)
```


Lädt das Dokument.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream. |
| loadOptions | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen. |

**Returns:**
[DjvuImage](../../com.aspose.imaging.fileformats.djvu/djvuimage) - Loaded djvu document
### getIdentifier() {#getIdentifier--}
```
public int getIdentifier()
```


Liefert die eindeutige Kennung für das Dokument

**Returns:**
int - Der Bezeichner.
### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtzahl der Seiten in Ihrer DjVu-Bildsammlung mit dieser Eigenschaft ab. Ideal, um schnell das Ausmaß Ihres Dokuments oder Buches im DjVu-Format zu beurteilen. Verbessern Sie die Effizienz Ihres Workflows mit genauen Seitenzählinformationen.

**Returns:**
int - Die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Greifen Sie mit dieser Eigenschaft auf die einzelnen Seiten Ihrer DjVu-Bildsammlung zu. Vereinfachen Sie die Navigation und Manipulation Ihres Dokuments oder Buches im DjVu-Format, indem Sie jede Seite direkt aufrufen. Verbessern Sie die Effizienz Ihres Workflows durch einfache Seitenabfrage.

**Returns:**
com.aspose.imaging.Image[] - Die Seiten.

**Example: This example shows how to load a DJVU image from a file stream.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
java.io.InputStream stream = new java.io.FileInputStream(dir + "sample.djvu");
com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = new com.aspose.imaging.fileformats.djvu.DjvuImage(stream);
try {
    // Speichern Sie jede Seite als einzelnes PNG-Bild.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage djvuPage : djvuImage.getPages()) {
        // Generieren Sie einen Dateinamen basierend auf der Seitennummer.
        String fileName = String.format("sample.%s.png", djvuPage.getPageNumber());
        djvuPage.save(dir + fileName, new com.aspose.imaging.imageoptions.PngOptions());
    }
} finally {
    djvuImage.dispose();
    stream.close();
}
```

### getDjvuPages() {#getDjvuPages--}
```
public DjvuPage[] getDjvuPages()
```


Rufen Sie schnell alle Seiten, die in Ihrem DjVu-Dokument enthalten sind, über diese Eigenschaft ab. Vereinfachen Sie Ihren Dokumentverarbeitungs-Workflow, indem Sie einzelne Seiten Ihrer DjVu-Dateien leicht zugreifen und verwalten. Steigern Sie die Effizienz und optimieren Sie Ihre Aufgaben mit einer bequemen Seitenabfrage.

**Returns:**
com.aspose.imaging.fileformats.djvu.DjvuPage[] - Die Seiten.
### getActivePage() {#getActivePage--}
```
public DjvuPage getActivePage()
```


Navigieren Sie durch Ihr DjVu-Dokument, indem Sie über diese Eigenschaft die aktuell aktive Seite abrufen oder festlegen. Wechseln Sie nahtlos zwischen Seiten, um sich auf spezifische Inhalte zu konzentrieren und das Dokumentanzeigeerlebnis zu verbessern.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage)

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
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

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Seiten: 2
//Die aktive Seitennummer:    1
//Die erste Seitennummer:     1
//Die letzte Seitennummer:      2
//--------------------------------------------------
//Seitennummer:     1
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
//--------------------------------------------------
//Seitennummer:     2
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
```

### setActivePage(DjvuPage value) {#setActivePage-com.aspose.imaging.fileformats.djvu.DjvuPage-}
```
public void setActivePage(DjvuPage value)
```


Navigieren Sie durch Ihr DjVu-Dokument, indem Sie über diese Eigenschaft die aktuell aktive Seite abrufen oder festlegen. Wechseln Sie nahtlos zwischen Seiten, um sich auf spezifische Inhalte zu konzentrieren und das Dokumentanzeigeerlebnis zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) | Die aktive Seite. |

### getFirstPage() {#getFirstPage--}
```
public DjvuPage getFirstPage()
```


Greifen Sie mit dieser Eigenschaft auf die erste Seite Ihres DjVu-Dokuments zu. Rufen Sie schnell die Anfangsseite ab, um Ihr Dokument effizient zu betrachten oder zu verarbeiten.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The first page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
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

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Seiten: 2
//Die aktive Seitennummer:    1
//Die erste Seitennummer:     1
//Die letzte Seitennummer:      2
//--------------------------------------------------
//Seitennummer:     1
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
//--------------------------------------------------
//Seitennummer:     2
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
```

### getLastPage() {#getLastPage--}
```
public DjvuPage getLastPage()
```


Rufen Sie die letzte Seite Ihres DjVu-Dokuments über diese Eigenschaft ab. Greifen Sie schnell und einfach auf die Endseite zu, um sie zu betrachten oder zu verarbeiten.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The last page.

**Example: This example shows how to load a DJVU image from a file stream and print information about the pages.**

``` java
String dir = "c:\\temp\\";

// Lade ein DJVU‑Bild aus einem Dateistream.
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

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Seiten: 2
//Die aktive Seitennummer:    1
//Die erste Seitennummer:     1
//Die letzte Seitennummer:      2
//--------------------------------------------------
//Seitennummer:     1
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
//--------------------------------------------------
//Seitennummer:     2
//Seitengröße:       { Width = 2481, Height = 3508}
//Rohformat der Seite: RgbIndexed1Bpp, verwendete Kanäle: 1
```

### getNextPage() {#getNextPage--}
```
public DjvuPage getNextPage()
```


Navigieren Sie durch Ihr DjVu-Dokument, indem Sie mit dieser praktischen Eigenschaft die nächste Seite aufrufen. Bewegen Sie sich schnell vorwärts bei der Dokumentanzeige oder -verarbeitung.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The next page.
### getPreviousPage() {#getPreviousPage--}
```
public DjvuPage getPreviousPage()
```


Bewegen Sie sich schnell rückwärts in Ihren DjVu-Dokumentanzeige- oder -verarbeitungsaufgaben, indem Sie die vorherige Seite über diese praktische Eigenschaft aufrufen. Navigieren Sie effizient und mühelos durch Ihr Dokument.

**Returns:**
[DjvuPage](../../com.aspose.imaging.fileformats.djvu/djvupage) - The previous page.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Erhalten Sie die Dateiformatinformationen, die mit Ihrer DjVu-Bilddatei verknüpft sind. Bestimmen Sie schnell das Format Ihrer Datei für eine nahtlose Integration in Ihren Workflow.

**Returns:**
long
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Bestimmen Sie schnell, ob Ihre DjVu-Bilddatei einen Alpha-Kanal enthält. Vereinfachen Sie Ihren Workflow, indem Sie das Vorhandensein von Transparenzinformationen in Ihren Bildern prüfen.

**Returns:**
boolean - Der hat Alphakanal.
### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Drehen Sie das Bild um sein Zentrum mit der Rotate-Methode der Klasse RasterCachedMultipageImage. Diese praktische Funktion ermöglicht es Ihnen, die Ausrichtung von Bildern einfach anzupassen, während die zentrale Position beibehalten wird, und erweitert Ihre Bildbearbeitungsfähigkeiten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Vergrößern Sie das Bild mit der \`Resize\`‑Methode, die eine einfache und effektive Möglichkeit bietet, die Abmessungen Ihrer Bilder nach Ihren Anforderungen anzupassen. Diese vielseitige Funktion ermöglicht es Ihnen, Bilder problemlos auf die gewünschte Größe zu skalieren und verbessert ihre Verwendbarkeit auf verschiedenen Plattformen und in Anwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |


**Example: This example loads a DJVU image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeWidthProportionally(int newWidth, int resizeType) {#resizeWidthProportionally-int-int-}
```
public void resizeWidthProportionally(int newWidth, int resizeType)
```


Die \`ResizeWidthProportionally\`‑Methode bietet eine praktische Lösung, um die Breite Ihres Bildes anzupassen und dabei das Seitenverhältnis beizubehalten. Durch proportionale Anpassung der Breite stellen Sie sicher, dass Ihre Bilder visuell ansprechend und konsistent auf verschiedenen Geräten und Bildschirmgrößen bleiben, was ihre Vielseitigkeit und Verwendbarkeit in unterschiedlichen Kontexten erhöht.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein DJVU‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Breite angegeben, die Höhe wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeWidthProportionally(image.getWidth() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeHeightProportionally(int newHeight, int resizeType) {#resizeHeightProportionally-int-int-}
```
public void resizeHeightProportionally(int newHeight, int resizeType)
```


Die \`ResizeHeightProportionally\`‑Methode ermöglicht es Ihnen, die Höhe Ihres Bildes anzupassen und dabei das Seitenverhältnis beizubehalten. Dadurch bleibt das Bild proportional, Verzerrungen werden vermieden und die visuelle Integrität erhalten. Egal, ob Sie Bilder für Webseiten, mobile Apps oder Druckmedien optimieren, diese Methode sorgt dafür, dass Ihre Bilder auf verschiedenen Plattformen und Geräten optimal aussehen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Typ der Skalierung. |


**Example: This example loads a DJVU image and resizes it proportionally using various resizing methods.**
Dieses Beispiel lädt ein DJVU‑Bild und skaliert es proportional mit verschiedenen Skalierungsmethoden. Es wird nur die Höhe angegeben, die Breite wird automatisch berechnet.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.nearestneighbour.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "upsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resizeHeightProportionally(image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);

    // Als PNG mit den Standardoptionen speichern.
    image.save(dir + "downsample.bilinear.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Die \`RotateFlip\`‑Methode bietet vielseitige Manipulationsoptionen für Ihr Bild und ermöglicht das Drehen, Spiegeln oder beide Vorgänge unabhängig am aktiven Frame. Egal, ob Sie Fotos bearbeiten, Grafiken erstellen oder digitale Kunst verbessern, diese Methode liefert präzise Kontrolle über Ausrichtung und Zusammensetzung Ihrer Bilder, sodass sie Ihrer kreativen Vision mühelos und effizient entsprechen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Rotations‑Umkehrtyp. |


**Example: This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java
String dir = "c:\\temp\\";

int[] rotateFlipTypes = new int[]
        {
                com.aspose.imaging.RotateFlipType.Rotate90FlipNone,
                com.aspose.imaging.RotateFlipType.Rotate90FlipX,
                com.aspose.imaging.RotateFlipType.Rotate90FlipXY,
                com.aspose.imaging.RotateFlipType.Rotate90FlipY,
        };

for (int rotateFlipType : rotateFlipTypes) {
    // Drehen, spiegeln und in die Ausgabedatei speichern.
    com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + rotateFlipType + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Die „Dither“-Funktion wendet einen Dithering‑Effekt auf Ihr Bild an und verbessert die visuelle Qualität, indem Banding reduziert und Farbübergänge verbessert werden. Ob Sie an digitaler Kunst, Fotografie oder Grafikdesignprojekten arbeiten, diese Funktion verleiht Ihren Bildern einen professionellen Touch und lässt sie glatter und feiner erscheinen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |


**Example: The following example loads a DJVU image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Führen Sie Schwellenwert-Dithering mit einer 4‑Bit-Farbpalette durch, die 16 Farben enthält.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    dicomImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage dicomImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Führen Sie Floyd-Dithering mit einer 1‑Bit-Farbpalette durch, die nur 2 Farben enthält – Schwarz und Weiß.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    dicomImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    dicomImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


„Crop“ schneidet Ihr Bild zu, um sich auf bestimmte Details zu konzentrieren oder unerwünschte Elemente zu entfernen, und verbessert so die Komposition und visuelle Wirkung. Ob Sie Fotos für soziale Medien anpassen, Website‑Banner erstellen oder Druckmaterialien gestalten, dieses Werkzeug hilft Ihnen, Ihre Bilder präzise und klar zu verfeinern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |


**Example: The following example crops a DJVU image.**
Das folgende Beispiel schneidet ein DJVU‑Bild zu. Der Beschnittbereich wird über **Aspose.Imaging.Rectangle** angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Schneiden Sie das Bild zu. Der Zuschnittsbereich ist der rechteckige zentrale Bereich des Bildes.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            djvuImage.getWidth() / 4, djvuImage.getHeight() / 4, djvuImage.getWidth() / 2, djvuImage.getHeight() / 2);
    djvuImage.crop(area);

    // Speichern Sie das zugeschnittene Bild als PNG
    djvuImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


„Crop with shifts“ ermöglicht es Ihnen, Position und Abmessungen des beschnittenen Bereichs in einem Bild präzise anzupassen. Diese Funktion ist unverzichtbar, um Kompositionen zu verfeinern, Elemente auszurichten und Fokuspunkte in Ihren Visuals zu betonen. Durch die Integration von Verschiebungen in den Beschnittvorgang können Sie pixelgenaue Präzision erreichen und den Bildausschnitt mühelos feinjustieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Die Binärisierung mit einem vordefinierten Schwellenwert vereinfacht komplexe Bilder zu binären Darstellungen, bei denen Pixel je nach ihrer Intensität im Vergleich zu einem festgelegten Schwellenwert als Schwarz oder Weiß klassifiziert werden. Diese Technik wird häufig in der Bildverarbeitung eingesetzt, um die Klarheit zu erhöhen, Analysen zu vereinfachen und Bilder für weitere Verarbeitungsschritte wie die optische Zeichenerkennung (OCR) vorzubereiten. Durch Anwendung eines festen Schwellenwerts können Sie Graustufenbilder schnell in binäre Form umwandeln, was deren Interpretation und das Extrahieren bedeutungsvoller Informationen erleichtert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |


**Example: The following example binarizes a DJVU image with the predefined threshold.**
Das folgende Beispiel binarisiert ein DJVU‑Bild mit dem vordefinierten Schwellenwert. Binärisierte Bilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisieren Sie das Bild mit einem Schwellenwert von 127.
    // Wenn der entsprechende Grauwert eines Pixels größer als 127 ist, wird ihm der Wert 255 zugewiesen, sonst 0.
    djvuImage.binarizeFixed((byte) 127);
    djvuImage.save(dir + "sample.BinarizeFixed.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeOtsu() {#binarizeOtsu--}
```
public void binarizeOtsu()
```


Die Binärisierung mittels Otsu‑Schwellwertbestimmung ist eine Technik, die automatisch einen optimalen Schwellenwert basierend auf dem Histogramm des Bildes berechnet. Sie trennt das Bild in Vordergrund und Hintergrund, indem sie die Intra‑Klassen‑Varianz minimiert. Otsus Methode wird häufig zur Segmentierung von Bildern in binäre Form verwendet, insbesondere wenn die Verteilung der Pixelintensitäten bimodal oder multimodal ist. Dieser Ansatz ist vorteilhaft für Aufgaben wie Objekterkennung, Bildsegmentierung und Merkmalsextraktion, bei denen eine genaue Abgrenzung zwischen Vordergrund und Hintergrund entscheidend ist.


**Example: The following example binarizes a DJVU image with Otsu thresholding.**
Das folgende Beispiel binarisiert ein DJVU‑Bild mit Otsu‑Schwellwertbestimmung. Binärisierte Bilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisieren Sie das Bild mit Otsu‑Schwellenwertverfahren.
    djvuImage.binarizeOtsu();
    djvuImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference, int windowSize) {#binarizeBradley-double-int-}
```
public void binarizeBradley(double brightnessDifference, int windowSize)
```


Die Binärisierung mittels Bradleys adaptivem Schwellwert‑Algorithmus mit Integral‑Bild‑Schwellwertbestimmung ist ein Verfahren, das für jedes Pixel einen lokalen Schwellenwert basierend auf einer Nachbarschaft berechnet. Es passt sich an Beleuchtungsvariationen im Bild an und ist daher für Bilder mit ungleichmäßigen Lichtverhältnissen geeignet. Durch die Berechnung des Schwellenwerts mit Integral‑Bildern wird effizient mit großen Nachbarschaften umgegangen, was es für Echtzeitanwendungen nutzbar macht. Diese Technik wird häufig in der Dokumentenverarbeitung, OCR (Optische Zeichenerkennung) und Bildsegmentierungsaufgaben eingesetzt, bei denen eine genaue Binärisierung für die nachfolgende Analyse unerlässlich ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |
| windowSize | int | Die Größe des s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |


**Example: The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size.**
Das folgende Beispiel binarisiert ein DJVU‑Bild mit Bradleys adaptivem Schwellwert‑Algorithmus und der angegebenen Fenstergröße. Binärisierte Bilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Binarisieren Sie das Bild mit einem Helligkeitsunterschied von 5. Die Helligkeit ist die Differenz zwischen einem Pixel und dem Durchschnitt eines 10 × 10‑Pixel‑Fensters, das um diesen Pixel zentriert ist.
    djvuImage.binarizeBradley(5, 10);
    djvuImage.save(dir + "sample.BinarizeBradley5_10x10.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Die Graustufen‑Transformation wandelt ein Bild in eine Schwarz‑Weiß‑Darstellung um, bei der die Intensität jedes Pixels durch einen einzelnen Wert von Schwarz bis Weiß repräsentiert wird. Dieser Vorgang entfernt Farbinformationen und erzeugt ein monochromes Bild. Graustufenbilder werden häufig in Anwendungen verwendet, bei denen Farbe unnötig ist oder Einfachheit bevorzugt wird, wie z. B. beim Dokumentenscannen, Drucken und bestimmten Arten der Bildanalyse.


**Example: The following example transforms a colored DJVU image to its grayscale representation.**
Das folgende Beispiel wandelt ein farbiges DJVU‑Bild in seine Graustufen‑Darstellung um. Graustufenbilder bestehen ausschließlich aus Grautönen und enthalten nur Intensitätsinformationen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    djvuImage.grayscale();
    djvuImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Die Gammakorrektur, speziell für die Rot‑, Grün‑ und Blau‑Kanäle, beinhaltet die separate Anpassung der Helligkeit jeder Farbkomponente. Durch Anwendung unterschiedlicher Gamma‑Koeffizienten auf die RGB‑Kanäle können Sie die Gesamthelligkeit und den Kontrast eines Bildes feinjustieren. Diese Technik sorgt für eine genaue Farbdarstellung und verbessert die visuelle Qualität des Bildes auf verschiedenen Anzeigegeräten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |


**Example: The following example performs gamma-correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Setzen Sie den Gamma-Koeffizienten für Rot-, Grün- und Blaukanäle.
    djvuImage.adjustGamma(2.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Gammakorrektur wird auf ein Bild angewendet, wobei die Parameter für die Rot‑, Grün‑ und Blau‑Kanäle anpassbar sind, sodass eine präzise Einstellung von Farbton und Helligkeit möglich ist. Diese Methode verbessert die Bildqualität, indem sie die Farbdarstellung feinabstimmt und ein optimales Rendering auf verschiedenen Anzeigegeräten gewährleistet. Die Anpassung der Gamma‑Werte einzelner Kanäle verbessert das Farbgleichgewicht und die visuelle Attraktivität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |


**Example: The following example performs gamma-correction of a DJVU image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Setzen Sie individuelle Gamma-Koeffizienten für die Rot-, Grün- und Blaukanäle.
    djvuImage.adjustGamma(1.5f, 2.5f, 3.5f);
    djvuImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Passen Sie die `brightness` eines Bildes mit einem angegebenen Parameter an, um die Leuchtstärke für optimale visuelle Klarheit zu steuern. Diese Methode erhöht oder verringert die Gesamthelligkeit des Bildes und ermöglicht feine Anpassungen, um gewünschte Lichteffekte zu erzielen. Durch Modulation der Helligkeit können Benutzer die Sichtbarkeit des Bildes optimieren und die Detailwiedergabe für ein verbessertes Seherlebnis steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |


**Example: The following example performs brightness correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Legen Sie den Helligkeitswert fest. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
    djvuImage.adjustBrightness(50);
    djvuImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Verbessern Sie den Kontrast von [Image](../../com.aspose.imaging/image), um die visuelle Klarheit zu erhöhen und Details hervorzuheben, indem diese Methode den Helligkeitsunterschied zwischen hellen und dunklen Bereichen anpasst. Durch Feinabstimmung der Kontrastwerte können Benutzer lebendigere und eindrucksvollere Bilder erzielen, die Gesamtbildqualität verbessern und die Detailsichtbarkeit maximieren. Diese Anpassung bringt subtile Nuancen in Farbe und Textur zum Vorschein und führt zu dynamischeren und optisch ansprechenderen Bildern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |


**Example: The following example performs contrast correction of a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Legen Sie den Kontrastwert fest. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
    djvuImage.adjustContrast(50f);
    djvuImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Wenden Sie Filter auf einen angegebenen rechteckigen Bereich im Bild an, um dessen Aussehen zu verbessern oder zu verändern. Durch das Anvisieren bestimmter Regionen ermöglicht diese Methode präzise Anpassungen wie Unschärfe, Schärfung oder das Anwenden künstlerischer Effekte, um gewünschte visuelle Ergebnisse zu erzielen. Das Feinabstimmen von Filtern in ausgewählten Bereichen befähigt Benutzer, die Bildästhetik zu individualisieren, die Klarheit zu verbessern und künstlerische Effekte nach ihren Vorlieben zu erzeugen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |


**Example: The following example applies various types of filters to a DJVU image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    djvuImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    djvuImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    djvuImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    djvuImage.filter(djvuImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    djvuImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skalieren Sie das Bild auf die angegebene Breite und Höhe, wobei bei Bedarf zusätzliche Einstellungen angewendet werden. Diese Methode ermöglicht es Benutzern, die Abmessungen des Bildes anzupassen und dabei gewünschte Attribute wie Seitenverhältnis, Bildqualität und Komprimierungseinstellungen beizubehalten. Durch die Bereitstellung von Flexibilität bei den Skalierungsoptionen können Benutzer das Bild an spezifische Anforderungen anpassen und sein Erscheinungsbild für verschiedene Anwendungen und Plattformen optimieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |


**Example: This example loads a DJVU image and resizes it using various resizing settings.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.ImageResizeSettings resizeSettings = new com.aspose.imaging.ImageResizeSettings();

// Der adaptive Algorithmus basierend auf gewichteter und gemischter rationaler Funktion sowie Lanczos‑3‑Interpolation.
resizeSettings.setMode(com.aspose.imaging.ResizeType.AdaptiveResample);

// Der kleine rechteckige Filter
resizeSettings.setFilterType(com.aspose.imaging.ImageFilterType.SmallRectangular);

// Die Anzahl der Farben in der Palette.
resizeSettings.setEntriesCount(256);

// Die Farbquantisierung wird nicht verwendet
resizeSettings.setColorQuantizationMethod(com.aspose.imaging.ColorQuantizationMethod.None);

// Die euklidische Methode
resizeSettings.setColorCompareMethod(com.aspose.imaging.ColorCompareMethod.Euclidian);

com.aspose.imaging.Image image = (com.aspose.imaging.Image) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    com.aspose.imaging.fileformats.djvu.DjvuImage djvuImage = (com.aspose.imaging.fileformats.djvu.DjvuImage) image;

    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    djvuImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Als PNG speichern
    djvuImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### cacheData() {#cacheData--}
```
public void cacheData()
```


Cache die Daten privat, um die Leistung zu optimieren und den Bedarf an wiederholten Datenabrufen aus externen Quellen zu reduzieren. Dieser Ansatz hilft zudem, Ressourcen zu schonen, insbesondere in Szenarien, in denen der Datenzugriff häufig ist oder Ressourcen begrenzt sind.


**Example: The following example shows how to cache all pages of a DJVU image.**

``` java
String dir = "c:\\temp\\";

// Laden Sie ein Bild aus einer DJVU-Datei.
com.aspose.imaging.fileformats.djvu.DjvuImage image = (com.aspose.imaging.fileformats.djvu.DjvuImage) com.aspose.imaging.Image.load(dir + "sample.djvu");
try {
    // Dieser Aufruf zwischenspeichert alle Seiten, sodass kein zusätzliches Laden von Daten aus dem zugrunde liegenden Datenstrom durchgeführt wird.
    image.cacheData();

    // Oder Sie können die Seiten einzeln zwischenspeichern.
    for (com.aspose.imaging.fileformats.djvu.DjvuPage page : image.getPages()) {
        page.cacheData();
    }
} finally {
    image.dispose();
}
```

