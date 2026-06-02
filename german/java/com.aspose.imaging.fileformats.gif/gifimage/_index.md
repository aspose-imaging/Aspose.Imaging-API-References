---
title: "GifImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für Graphical Interchange Format GIF image file bietet Entwicklern vielseitige Werkzeuge zur Verarbeitung komprimierter Rasterbilder und animierter GIFs."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.gif/gifimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage), [com.aspose.imaging.RasterCachedMultipageImage](../../com.aspose.imaging/rastercachedmultipageimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IMultipageImageExt](../../com.aspose.imaging/imultipageimageext), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifImage extends RasterCachedMultipageImage implements IMultipageImageExt, IInterlaced
```

Die API für Graphical Interchange Format (GIF) image file bietet Entwicklern vielseitige Werkzeuge zur Verarbeitung komprimierter Rasterbilder und animierter GIFs. Sie bietet Funktionen wie XMP-Metadatenverarbeitung, Einstellung der Farbpalette, Steuerung von Hintergrund- und Transparenzfarbe, Opazitätseinstellungen, Größenänderung, Zuschneiden, Filteranwendung, Gammakorrekturen, Kontrastanpassung, Graustufentransformation und Konvertierung in andere Formate. Diese API ermöglicht eine nahtlose Manipulation und Verbesserung von GIF-Bildern für ein breites Anwendungsspektrum.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-) | Initialisieren Sie ein neues [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Objekt mit angegebenen Parametern für das erste Bild und die globale Palette. |
| [GifImage(GifFrameBlock firstFrame)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Das Erstellen von GIF-Bildern wird mühelos mit dem [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Konstruktor. |
| [GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)](#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-) | Starten Sie mühelos mit dem [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Konstruktor. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie das Dateiformat mühelos über diese Eigenschaft ab. |
| [hasTrailer()](#hasTrailer--) | Verwalten Sie das Vorhandensein eines Trailers in Ihren GIF-Dateien mit dieser Eigenschaft. |
| [setTrailer(boolean value)](#setTrailer-boolean-) | Verwalten Sie das Vorhandensein eines Trailers in Ihren GIF-Dateien mit dieser Eigenschaft. |
| [isPaletteSorted()](#isPaletteSorted--) | Steuern Sie die Sortierung der Palette in Ihren GIF-Bildern mit dieser Eigenschaft. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Steuern Sie die Sortierung der Palette in Ihren GIF-Bildern mit dieser Eigenschaft. |
| [getLoopsCount()](#getLoopsCount--) | Rufen Sie die Schleifenanzahl mühelos mit dieser Eigenschaft ab. |
| [setLoopsCount(int value)](#setLoopsCount-int-) | Rufen Sie die Schleifenanzahl mühelos mit dieser Eigenschaft ab. |
| [getPaletteColorResolutionBits()](#getPaletteColorResolutionBits--) | Verwalten Sie die Farbauflösung der Palette Ihrer GIF-Bilder mit dieser Eigenschaft. |
| [setPaletteColorResolutionBits(byte value)](#setPaletteColorResolutionBits-byte-) | Verwalten Sie die Farbauflösung der Palette Ihrer GIF-Bilder mit dieser Eigenschaft. |
| [getPageCount()](#getPageCount--) | Ermitteln Sie die Gesamtzahl der im Bild enthaltenen Seiten mit dieser unkomplizierten Eigenschaft. |
| [getPages()](#getPages--) | Erhalten Sie über diese praktische Eigenschaft Zugriff auf die Seiten im Bild, wodurch eine nahtlose Navigation und Manipulation einzelner Seiten nach Bedarf ermöglicht wird. |
| [getBlocks()](#getBlocks--) | Erhalten Sie über diese Eigenschaft nahtlosen Zugriff auf die GIF-Blöcke, was eine einfache Abfrage und Manipulation der zugrunde liegenden Datenstrukturen des Bildes ermöglicht. |
| [isInterlaced()](#isInterlaced--) | Bestimmt, ob das Bild zeilenweise (interlaced) ist, was die Anzeige beim Laden beeinflusst. |
| [getOriginalOptions()](#getOriginalOptions--) | Rufen Sie die auf den ursprünglichen Dateieinstellungen basierenden Optionen ab, die für die Wahrung von Treue und Konsistenz bei der Bildverarbeitung und -manipulation entscheidend sind. |
| [addPage(RasterImage page)](#addPage-com.aspose.imaging.RasterImage-) | Fügen Sie nahtlos eine neue Seite in das bestehende Bild ein, wodurch dessen Inhalt verbessert und der Umfang erweitert wird. |
| [getActiveFrame()](#getActiveFrame--) | Verwalten und manipulieren Sie Frames mit dieser Eigenschaft, wodurch eine reibungslose Navigation und Änderung des aktiven Frames im GIF-Bild ermöglicht wird. |
| [setActiveFrame(GifFrameBlock value)](#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-) | Verwalten und manipulieren Sie Frames mit dieser Eigenschaft, wodurch eine reibungslose Navigation und Änderung des aktiven Frames im GIF-Bild ermöglicht wird. |
| [getBackgroundColor()](#getBackgroundColor--) | Verwalten Sie die Hintergrundfarbe des GIF-Bildes mit dieser Eigenschaft. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Verwalten Sie die Hintergrundfarbe des GIF-Bildes mit dieser Eigenschaft. |
| [getBackgroundColorIndex()](#getBackgroundColorIndex--) | Steuern Sie den Hintergrundfarbindizes des GIF-Bildes mit dieser Eigenschaft. |
| [setBackgroundColorIndex(byte value)](#setBackgroundColorIndex-byte-) | Steuern Sie den Hintergrundfarbindizes des GIF-Bildes mit dieser Eigenschaft. |
| [getPixelAspectRatio()](#getPixelAspectRatio--) | Verwalten Sie das Pixel‑Seitenverhältnis des GIF-Bildes mit dieser Eigenschaft. |
| [setPixelAspectRatio(byte value)](#setPixelAspectRatio-byte-) | Verwalten Sie das Pixel‑Seitenverhältnis des GIF-Bildes mit dieser Eigenschaft. |
| [hasTransparentColor()](#hasTransparentColor--) | Bestimmen Sie, ob der aktive Frame des GIF-Bildes eine transparente Farbe enthält. |
| [getTransparentColor()](#getTransparentColor--) | Rufen Sie die transparente Farbe des aktiven Frames im GIF-Bild ab. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Bestimmen Sie, ob der aktive Frame des GIF-Bildes eine transparente Farbe enthält. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Diese Eigenschaft bestimmt, ob das GIF-Bild eine Hintergrundfarbe enthält. |
| [getImageOpacity()](#getImageOpacity--) | Rufen Sie die Opazität des aktiven Frames im Bild ab, um Aufschluss über dessen Transparenzgrad zu erhalten. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Ändert die Größe dieser [Image](../../com.aspose.imaging/image)-Instanz. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Ändert die Größe dieser [Image](../../com.aspose.imaging/image)-Instanz. |
| [resizeFullFrame(int newWidth, int newHeight, int resizeType)](#resizeFullFrame-int-int-int-) | Größenänderung des Bildes unter Berücksichtigung aller Frames für jede Seite in einem GIF, wodurch potenzielle Artefakte vermieden werden. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Führen Sie ausschließlich Drehungen, Spiegelungen oder beides am aktiven Frame durch. |
| [dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)](#dither-int-int-com.aspose.imaging.IColorPalette-) | Wenden Sie Dithering auf das aktuelle Bild an. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Beschneiden Sie das Bild mithilfe eines angegebenen Rechteckbereichs. |
| [adjustGamma(float gamma)](#adjustGamma-float-) | Verbessern Sie die Bildqualität durch Anwendung einer Gammakorrektur. |
| [filter(Rectangle rectangle, FilterOptionsBase options)](#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-) | Wenden Sie einen spezifischen Filter auf den festgelegten Bereich des Bildes an, um dessen visuelle Qualität zu verbessern oder das Aussehen nach Wunsch zu verändern. |
| [setFrameTime(int time)](#setFrameTime-int-) | Passt die Dauer jedes Frames in Millisekunden an und sorgt für konsistentes Timing über die gesamte Bildsequenz hinweg. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Passt die Helligkeit des Bildes gemäß dem angegebenen `brightness`‑Parameter an. |
| [adjustContrast(float contrast)](#adjustContrast-float-) | Passt den Kontrast des Bildes an und verstärkt bzw. reduziert den Helligkeitsunterschied zwischen den Pixeln. |
| [adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)](#adjustGamma-float-float-float-) | Die Gammakorrektur eines Bildes wendet eine nichtlineare Anpassung der Pixelwerte an und erhöht bzw. verringert die Helligkeit basierend auf den angegebenen Koeffizienten für die roten, grünen und blauen Kanäle. |
| [grayscale()](#grayscale--) | Die Umwandlung eines Bildes in seine Graustufen‑Darstellung konvertiert das Farbbild in eine Graustufen‑Version, indem Farbinformationen entfernt und die Luminanz erhalten bleibt. |
| [binarizeFixed(byte threshold)](#binarizeFixed-byte-) | Die Binarisierung eines Bildes mit einem vordefinierten Schwellenwert konvertiert ein Graustufen‑ oder Farbbild in ein Binärbild, wobei jeder Pixel als schwarz oder weiß klassifiziert wird, abhängig davon, ob sein Intensitätswert einen angegebenen Schwellenwert überschreitet. |
| [binarizeOtsu()](#binarizeOtsu--) | Die Binarisierung eines Bildes mit Otsu‑Schwellenwertbestimmung ist ein Verfahren, das verwendet wird, um automatisch den optimalen Schwellenwert für die Umwandlung eines Graustufenbildes in ein Binärbild zu bestimmen. |
| [binarizeBradley(double brightnessDifference)](#binarizeBradley-double-) | Die Binarisierung eines Bildes mittels Bradleys adaptivem Schwellenwert‑Algorithmus mit Integral‑Bild‑Schwellenwert ist ein Verfahren zur Umwandlung eines Graustufenbildes in ein Binärbild. |
| [orderBlocks()](#orderBlocks--) | Das Anordnen der GIF‑Blöcke gemäß der GIF‑Spezifikation gewährleistet ein korrektes GIF‑Layout und die Einhaltung des Standards. |
| [clearBlocks()](#clearBlocks--) | Das Löschen aller GIF‑Blöcke entfernt alle im Bild gespeicherten Daten. |
| [insertBlock(int index, IGifBlock block)](#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-) | Das Einfügen eines neuen GIF‑Blocks ermöglicht das Hinzufügen benutzerdefinierter Daten an einer bestimmten Position im Bild. |
| [addBlock(IGifBlock block)](#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Das Hinzufügen eines neuen GIF‑Blocks erlaubt das Einbinden zusätzlicher Daten im Bild. |
| [removeBlock(IGifBlock block)](#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-) | Das Entfernen eines GIF‑Blocks löscht bestimmte Daten aus dem Bild und bietet die Möglichkeit, die Bildstruktur zu bereinigen oder zu ändern. |
| [resizeProportional(int newWidth, int newHeight, int resizeType)](#resizeProportional-int-int-int-) | Proportionales Skalieren erhält das Seitenverhältnis des Bildes bei Größenanpassung und stellt sicher, dass das Bild nicht gestreckt oder verzerrt wirkt. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Diese Methode dreht das Bild um seinen Mittelpunkt. |

## Example: This example shows how to create a GIF image and save it to a file.

``` java
String dir = "c:\\temp\\";

// Erstelle einen GIF‑Frame‑Block von 100x100 px.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
try {
    // Fülle den gesamten Block mit Rot.
    com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(firstBlock);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());
    gr.fillRectangle(brush, firstBlock.getBounds());

    com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
    try {
        gifImage.save(dir + "output.gif");
    } finally {
        gifImage.dispose();
    }
} finally {
    firstBlock.dispose();
}
```


## Example: Create multipage GIF image using single page raster images.

``` java
static void main(String[] args)
{
    // Frames laden
    RasterImage[] frames = loadFrames("Animation frames");

    // GIF‑Bild mit dem ersten Frame erstellen
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Frames zum GIF‑Bild mit der Methode AddPage hinzufügen
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // GIF‑Bild speichern
        image.save("Multipage.gif");
    }

    // Ressourcen freigeben
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```


## Example: Export of part of animation from GIF image based on time interval.

``` java
try (Image image = Image.load("Animation.gif"))
{
    GifOptions options = new GifOptions();
    options.setFullFrame(true);
    final MultiPageOptions multiPageOptions = new MultiPageOptions();
    multiPageOptions.setMode(MultiPageMode.TimeInterval);
    multiPageOptions.setTimeInterval(new TimeInterval(0, 400));
    options.setMultiPageOptions(multiPageOptions);

    image.save("PartOfAnimation.gif", options);
}
```

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette)
```


Initialisiere ein neues [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Objekt mit den angegebenen Parametern für den ersten Frame und die globale Palette. Beginne, GIF‑Bilder zügig zu verwalten, und stelle eine genaue Darstellung mit anpassbaren Einstellungen für optimale Ergebnisse sicher.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Der erste Frame, mit dem das GIF‑Bild initialisiert wird. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu verwendende globale Palette. Hinweis: Wenn sowohl `firstFrame` als auch `globalPalette` null sind, wird die Standard‑globale Palette verwendet. |

### GifImage(GifFrameBlock firstFrame) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public GifImage(GifFrameBlock firstFrame)
```


Das Erstellen von GIF‑Bildern wird mühelos mit dem [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Konstruktor. Mit nur dem Parameter firstFrame betritt man eine Welt dynamischer visueller Kommunikation.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Der erste Frame, mit dem das GIF‑Bild initialisiert wird. |

### GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer) {#GifImage-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-com.aspose.imaging.IColorPalette-boolean-byte-byte-byte-boolean-}
```
public GifImage(GifFrameBlock firstFrame, IColorPalette globalPalette, boolean isPaletteSorted, byte paletteColorResolution, byte paletteBackgroundColorIndex, byte aspectRatio, boolean hasTrailer)
```


Starten Sie mühelos mit dem [GifImage](../../com.aspose.imaging.fileformats.gif/gifimage)-Konstruktor. Mit dieser einfachen Methode können Sie problemlos animierte GIFs erstellen. Geben Sie einfach die Parameter firstFrame, globalPalette, paletteColorResolution, aspectRatio und weitere an, und Sie sind bereit, Ihre visuellen Inhalte zum Leben zu erwecken.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| firstFrame | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | Der erste Frame, mit dem das GIF‑Bild initialisiert wird. |
| globalPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu verwendende globale Palette. Hinweis: Wenn sowohl `firstFrame` als auch `globalPalette` null sind, wird die Standard‑globale Palette verwendet. |
| isPaletteSorted | boolean | Wenn auf `true` gesetzt, wird die Palette sortiert. Hinweis: Der Parameter wird verwendet, wenn `globalPalette` nicht null ist. |
| paletteColorResolution | byte | Die Farbauflösung der Palette. Hinweis: Der Parameter wird verwendet, wenn `globalPalette` nicht null ist. |
| paletteBackgroundColorIndex | byte | Der Index der Hintergrundfarbe der Palette. |
| aspectRatio | byte | Das Seitenverhältnis. |
| hasTrailer | boolean | Wenn auf `true` gesetzt, enthält das GIF‑Bild einen Trailer, andernfalls wird am Ende des Streams kein Trailer geschrieben. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie das Dateiformat mühelos über diese Eigenschaft ab. Sie ist Ihre zentrale Quelle zur Identifizierung des Formats Ihrer Dateien. Nahtlos in Ihren Arbeitsablauf integriert, liefert sie wichtige Informationen ohne Aufwand.

**Returns:**
long
### hasTrailer() {#hasTrailer--}
```
public boolean hasTrailer()
```


Verwalten Sie das Vorhandensein eines Trailers in Ihren GIF‑Dateien mit dieser Eigenschaft. Egal, ob Sie prüfen müssen, ob ein Trailer existiert, oder dessen Vorhandensein festlegen wollen, diese Eigenschaft vereinfacht den Vorgang. Halten Sie Ihre GIF‑Dateien strukturiert und konform mit dieser intuitiven Funktion.

**Returns:**
boolean - `true` wenn das GIF einen Trailer hat; andernfalls `false`.
### setTrailer(boolean value) {#setTrailer-boolean-}
```
public void setTrailer(boolean value)
```


Verwalten Sie das Vorhandensein eines Trailers in Ihren GIF‑Dateien mit dieser Eigenschaft. Egal, ob Sie prüfen müssen, ob ein Trailer existiert, oder dessen Vorhandensein festlegen wollen, diese Eigenschaft vereinfacht den Vorgang. Halten Sie Ihre GIF‑Dateien strukturiert und konform mit dieser intuitiven Funktion.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true` wenn das GIF einen Trailer hat; andernfalls `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Steuern Sie die Sortierung der Palette in Ihren GIF‑Bildern mit dieser Eigenschaft. Egal, ob Sie prüfen möchten, ob die Palette sortiert ist, oder das Sortierverhalten festlegen, diese Eigenschaft bietet eine einfache Möglichkeit, die Palette in Ihren GIF‑Dateien zu verwalten.

**Returns:**
boolean - `true`, wenn die Palette sortiert ist; andernfalls `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Steuern Sie die Sortierung der Palette in Ihren GIF‑Bildern mit dieser Eigenschaft. Egal, ob Sie prüfen möchten, ob die Palette sortiert ist, oder das Sortierverhalten festlegen, diese Eigenschaft bietet eine einfache Möglichkeit, die Palette in Ihren GIF‑Dateien zu verwalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | `true`, wenn die Palette sortiert ist; andernfalls `false`. |

### getLoopsCount() {#getLoopsCount--}
```
public int getLoopsCount()
```


Rufen Sie die Schleifenanzahl mühelos über diese Eigenschaft ab. Wenn Ihr GIF‑Bild Schleifeninformationen enthält, bietet diese Eigenschaft schnellen Zugriff auf die Schleifenanzahl, sodass Sie das Schleifenverhalten Ihrer GIF‑Dateien nahtlos verwalten können.

**Returns:**
int - Die Schleifenanzahl oder 1 (Standardwert)
### setLoopsCount(int value) {#setLoopsCount-int-}
```
public void setLoopsCount(int value)
```


Rufen Sie die Schleifenanzahl mühelos über diese Eigenschaft ab. Wenn Ihr GIF‑Bild Schleifeninformationen enthält, bietet diese Eigenschaft schnellen Zugriff auf die Schleifenanzahl, sodass Sie das Schleifenverhalten Ihrer GIF‑Dateien nahtlos verwalten können.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Die Schleifenanzahl oder 1 (Standardwert) |

### getPaletteColorResolutionBits() {#getPaletteColorResolutionBits--}
```
public byte getPaletteColorResolutionBits()
```


Verwalten Sie die Farbauflösung der Palette Ihrer GIF‑Bilder mit dieser Eigenschaft. Passen Sie die Anzahl der Bits an, die zur Darstellung der Farben in der Palette verwendet werden, und erhalten Sie feine Kontrolle über Farbtiefe und Bildqualität.

**Returns:**
byte - Die Bits der Palettenfarbauflösung.
### setPaletteColorResolutionBits(byte value) {#setPaletteColorResolutionBits-byte-}
```
public void setPaletteColorResolutionBits(byte value)
```


Verwalten Sie die Farbauflösung der Palette Ihrer GIF‑Bilder mit dieser Eigenschaft. Passen Sie die Anzahl der Bits an, die zur Darstellung der Farben in der Palette verwendet werden, und erhalten Sie feine Kontrolle über Farbtiefe und Bildqualität.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | Die Bits der Palettenfarbauflösung. |

### getPageCount() {#getPageCount--}
```
public int getPageCount()
```


Rufen Sie die Gesamtzahl der im Bild enthaltenen Seiten mit dieser einfachen Eigenschaft ab. Ideal, um schnell das Ausmaß des Bildinhalts zu beurteilen.

**Returns:**
int – die Seitenanzahl.
### getPages() {#getPages--}
```
public Image[] getPages()
```


Erhalten Sie über diese praktische Eigenschaft Zugriff auf die Seiten im Bild, wodurch eine nahtlose Navigation und Manipulation einzelner Seiten nach Bedarf ermöglicht wird.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
### getBlocks() {#getBlocks--}
```
public IGifBlock[] getBlocks()
```


Erhalten Sie über diese Eigenschaft nahtlosen Zugriff auf die GIF-Blöcke, was eine einfache Abfrage und Manipulation der zugrunde liegenden Datenstrukturen des Bildes ermöglicht.

**Returns:**
com.aspose.imaging.fileformats.gif.IGifBlock[] - die GIF‑Blöcke.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Bestimmt, ob das Bild interlaced ist, was die Anzeige beim Laden beeinflusst. Diese Eigenschaft liefert Einblicke in das Renderverhalten des Bildes, was für die Optimierung von Ladestrategien und die Verbesserung des Gesamterlebnisses entscheidend ist.

**Returns:**
boolean - `true`, wenn diese Bildinstanz interlaced ist; andernfalls `false`.
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Rufen Sie die originalen, dateibasierten Optionen ab, die entscheidend für die Aufrechterhaltung von Treue und Konsistenz bei der Bildverarbeitung und -manipulation sind. Diese Methode ermöglicht die nahtlose Integration dateispezifischer Parameter in nachfolgende Vorgänge und sorgt für eine genaue Wiedergabe sowie die Einhaltung der inhärenten Eigenschaften des Bildes. Dies kann hilfreich sein, um Bit‑Tiefe und andere Parameter des Originalbildes unverändert zu lassen. Zum Beispiel, wenn wir ein schwarz‑weißes PNG‑Bild mit 1 Bit pro Pixel laden und es dann mit der [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\#save-String-) Methode speichern, wird ein PNG‑Bild mit 8 Bit pro Pixel erzeugt. Um dies zu vermeiden und ein PNG‑Bild mit 1 Bit pro Pixel zu speichern, verwenden Sie diese Methode, um die entsprechenden Speicheroptionen zu erhalten und sie als zweiten Parameter an die [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\#save-String--ImageOptionsBase-) Methode zu übergeben.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### addPage(RasterImage page) {#addPage-com.aspose.imaging.RasterImage-}
```
public void addPage(RasterImage page)
```


Fügen Sie nahtlos eine neue Seite in das bestehende Bild ein, verbessern Sie dessen Inhalt und erweitern Sie dessen Umfang. Diese Methode erweitert Bildsammlungen um zusätzlichen Inhalt und fördert Kreativität sowie Flexibilität bei der Bildverwaltung und -komposition.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| page | [RasterImage](../../com.aspose.imaging/rasterimage) | Die hinzuzufügende Seite. |


**Example: Create multipage GIF image using single page raster images.**

``` java
static void main(String[] args)
{
    // Frames laden
    RasterImage[] frames = loadFrames("Animation frames");

    // GIF‑Bild mit dem ersten Frame erstellen
    try (GifImage image = new GifImage(new GifFrameBlock(frames[0])))
    {
        // Frames zum GIF‑Bild mit der Methode AddPage hinzufügen
        for (int index = 1; index < frames.length; index++)
        {
            image.addPage(frames[index]);
        }

        // GIF‑Bild speichern
        image.save("Multipage.gif");
    }

    // Ressourcen freigeben
    for (RasterImage frame : frames)
    {
        frame.close();
    }
}

private static RasterImage[] loadFrames(String directory)
{
    LinkedList<RasterImage> list = new LinkedList<RasterImage>();
    String[] fileList = new File(directory).list();
    if (fileList != null)
    {
        for (String filePath : fileList)
        {
            list.add((RasterImage) Image.load(filePath));
        }
    }
                
    return list.toArray(new RasterImage[0]);
}
```

### getActiveFrame() {#getActiveFrame--}
```
public GifFrameBlock getActiveFrame()
```


Verwalten und manipulieren Sie Frames mit dieser Eigenschaft, wodurch eine reibungslose Navigation und Änderung des aktiven Frames im GIF-Bild ermöglicht wird.

**Returns:**
[GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) - the active frame.

**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Die Ausgabe sieht folgendermaßen aus:
// Aktive Frame-Größe: { Width = 100, Height = 100}
// Alle Blöcke löschen
// Aktiver Frame ist nicht gesetzt
```

### setActiveFrame(GifFrameBlock value) {#setActiveFrame-com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock-}
```
public void setActiveFrame(GifFrameBlock value)
```


Verwalten und manipulieren Sie Frames mit dieser Eigenschaft, wodurch eine reibungslose Navigation und Änderung des aktiven Frames im GIF-Bild ermöglicht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [GifFrameBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifframeblock) | der aktive Frame. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Verwalten Sie die Hintergrundfarbe des GIF‑Bildes mit dieser Eigenschaft. Sie können die Hintergrundfarbe setzen oder abrufen, um Konsistenz zu gewährleisten und die visuelle Attraktivität zu steigern.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Verwalten Sie die Hintergrundfarbe des GIF‑Bildes mit dieser Eigenschaft. Sie können die Hintergrundfarbe setzen oder abrufen, um Konsistenz zu gewährleisten und die visuelle Attraktivität zu steigern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | die Hintergrundfarbe. |

### getBackgroundColorIndex() {#getBackgroundColorIndex--}
```
public byte getBackgroundColorIndex()
```


Steuern Sie den Hintergrundfarbindex des GIF‑Bildes mit dieser Eigenschaft. Setzen oder rufen Sie den Index ab, um Konsistenz zu wahren oder gewünschte visuelle Effekte zu erzielen.

**Returns:**
byte - der Hintergrundfarbindex.
### setBackgroundColorIndex(byte value) {#setBackgroundColorIndex-byte-}
```
public void setBackgroundColorIndex(byte value)
```


Steuern Sie den Hintergrundfarbindex des GIF‑Bildes mit dieser Eigenschaft. Setzen oder rufen Sie den Index ab, um Konsistenz zu wahren oder gewünschte visuelle Effekte zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | der Hintergrundfarbindex. |

### getPixelAspectRatio() {#getPixelAspectRatio--}
```
public byte getPixelAspectRatio()
```


Verwalten Sie das Pixel‑Seitenverhältnis des GIF‑Bildes mit dieser Eigenschaft. Setzen oder rufen Sie das Seitenverhältnis ab, um eine genaue Darstellung sicherzustellen und die visuelle Treue zu erhalten.

**Returns:**
byte - das Pixel‑Seitenverhältnis.
### setPixelAspectRatio(byte value) {#setPixelAspectRatio-byte-}
```
public void setPixelAspectRatio(byte value)
```


Verwalten Sie das Pixel‑Seitenverhältnis des GIF‑Bildes mit dieser Eigenschaft. Setzen oder rufen Sie das Seitenverhältnis ab, um eine genaue Darstellung sicherzustellen und die visuelle Treue zu erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | byte | das Pixel‑Seitenverhältnis. |

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Bestimmen Sie, ob der aktive Frame des GIF‑Bildes eine transparente Farbe enthält. Diese Eigenschaft bietet eine bequeme Möglichkeit, die Transparenz im Bild zu prüfen.

**Returns:**
boolean - ein Wert, der angibt, ob der aktive Frame eine transparente Farbe hat.
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Rufen Sie die transparente Farbe des aktiven Frames im GIF‑Bild ab. Diese Eigenschaft ermöglicht den Zugriff auf die spezifische Farbe, die im aktuell aktiven Frame als transparent festgelegt wurde.

**Returns:**
[Color](../../com.aspose.imaging/color) - active frame transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Bestimmen Sie, ob der aktive Frame des GIF‑Bildes eine transparente Farbe enthält. Diese Eigenschaft bietet eine bequeme Möglichkeit, die Transparenz im Bild zu prüfen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob der aktive Frame eine transparente Farbe hat. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Diese Eigenschaft bestimmt, ob das GIF‑Bild eine Hintergrundfarbe enthält. Wenn true, bedeutet dies, dass das Bild eine Hintergrundfarbe hat.

**Returns:**
boolean - ein Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.
### getImageOpacity() {#getImageOpacity--}
```
public float getImageOpacity()
```


Rufen Sie die Opazität des aktiven Frames im Bild ab, um Einblick in dessen Transparenzgrad zu erhalten. Diese Eigenschaft ist besonders nützlich, um den Grad der Transparenz oder Undurchsichtigkeit des aktiven Frames im Bild zu verstehen.

Der Opazitätswert zwischen 0,0 (vollständig transparent) und 1,0 (vollständig undurchsichtig).

**Returns:**
float - Opazität dieses Bildes (aktiver Frame).
### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Ändert die Größe dieser [Image](../../com.aspose.imaging/image)-Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |


**Example: This example loads a GIF image and resizes it using various resizing methods.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "upsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit Nearest‑Neighbour‑Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.NearestNeighbourResample);
    image.save(dir + "downsample.nearestneighbour.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Vergrößern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() * 2, image.getHeight() * 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "upsample.bilinear.gif");
} finally {
    image.dispose();
}

image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    // Verkleinern um das 2‑fache mit bilinearer Resampling.
    image.resize(image.getWidth() / 2, image.getHeight() / 2, com.aspose.imaging.ResizeType.BilinearResample);
    image.save(dir + "downsample.bilinear.gif");
} finally {
    image.dispose();
}
```

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Ändert die Größe dieser [Image](../../com.aspose.imaging/image)-Instanz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Einstellungen. |


**Example: This example loads a GIF image and resizes it using various resizing settings.**

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

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Verkleinern Sie um das 2‑fache mittels adaptiver Resampling.
    gifImage.resize(image.getWidth() / 2, image.getHeight() / 2, resizeSettings);

    // Als PNG speichern
    gifImage.save(dir + "downsample.adaptive.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### resizeFullFrame(int newWidth, int newHeight, int resizeType) {#resizeFullFrame-int-int-int-}
```
public void resizeFullFrame(int newWidth, int newHeight, int resizeType)
```


Skalierung des Bildes unter Berücksichtigung aller Frames für jede Seite in einem GIF, wodurch potenzielle Artefakte vermieden werden. Diese Methode ist entscheidend, um die Integrität und Qualität des Bildes zu erhalten, insbesondere beim Umgang mit animierten GIFs oder Frame‑Sequenzen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Führen Sie eine Rotation, ein Spiegeln oder beides ausschließlich am aktiven Frame durch. Dieser Vorgang wendet Transformationen ausschließlich auf den derzeit aktiven Frame des Bildes an und bewahrt die Integrität der anderen Frames in der Sequenz.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Dreh‑/Spiegeltyp. |


**Example: This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically.**

``` java

// Die Hilfsklasse, die im nachfolgenden Hauptbeispiel verwendet wird.
class Utils {
    // Die Hilfsmethode, um eine Zeichenkettenrepräsentation des Dateiformats zu erhalten.
    public String getRotateFlipTypeString(int rotateFlipType) {
        if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipNone) {
            return "RotateNoneFlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipNone) {
            return "Rotate90FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipNone) {
            return "Rotate180FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipNone) {
            return "Rotate270FlipNone";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipX) {
            return "RotateNoneFlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipX) {
            return "Rotate90FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipX) {
            return "Rotate180FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipX) {
            return "Rotate270FlipX";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipY) {
            return "RotateNoneFlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipY) {
            return "Rotate90FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipY) {
            return "Rotate180FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipY) {
            return "Rotate270FlipY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.RotateNoneFlipXY) {
            return "RotateNoneFlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate90FlipXY) {
            return "Rotate90FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate180FlipXY) {
            return "Rotate180FlipXY";
        } else if (rotateFlipType == com.aspose.imaging.RotateFlipType.Rotate270FlipXY) {
            return "Rotate270FlipXY";
        } else {
            return "UNDEFINED";
        }
    }
}

// Hier ist das Hauptbeispiel.
Utils utils = new Utils();

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
    com.aspose.imaging.fileformats.gif.GifImage image = (com.aspose.imaging.fileformats.gif.GifImage) com.aspose.imaging.Image.load(dir + "sample.gif");
    try {
        image.rotateFlip(rotateFlipType);
        image.save(dir + "sample." + utils.getRotateFlipTypeString(rotateFlipType) + ".png", new com.aspose.imaging.imageoptions.PngOptions());
    } finally {
        image.dispose();
    }
}
```

### dither(int ditheringMethod, int bitsCount, IColorPalette customPalette) {#dither-int-int-com.aspose.imaging.IColorPalette-}
```
public void dither(int ditheringMethod, int bitsCount, IColorPalette customPalette)
```


Wenden Sie Dithering auf das aktuelle Bild an. Dieser Prozess verbessert die Bildqualität, indem er Farbbänderungen reduziert und Farbübergänge verbessert, was zu einem glatteren Erscheinungsbild führt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ditheringMethod | int | Die Dithering-Methode. |
| bitsCount | int | Die endgültige Bitanzahl für Dithering. |
| customPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die benutzerdefinierte Palette für Dithering. |


**Example: The following example loads a GIF image and performs threshold and floyd dithering using different palette depth.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Führen Sie Schwellenwert-Dithering mit einer 4‑Bit-Farbpalette durch, die 16 Farben enthält.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    gifImage.dither(com.aspose.imaging.DitheringMethod.ThresholdDithering, 4, null);

    gifImage.save(dir + "sample.ThresholdDithering4.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Führen Sie Floyd-Dithering mit einer 1‑Bit-Farbpalette durch, die nur 2 Farben enthält – Schwarz und Weiß.
    // Je mehr Bits angegeben werden, desto höher die Qualität und desto größer die Größe des Ausgabebildes.
    // Beachten Sie, dass derzeit nur 1‑Bit-, 4‑Bit- und 8‑Bit-Paletten unterstützt werden.
    gifImage.dither(com.aspose.imaging.DitheringMethod.FloydSteinbergDithering, 1, null);

    gifImage.save(dir + "sample.FloydSteinbergDithering1.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beschneiden Sie das Bild mithilfe eines angegebenen Rechteckbereichs. Dieser Vorgang entfernt den äußeren Teil des Bildes und lässt nur den durch das Rechteck definierten ausgewählten Bereich übrig.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |


**Example: The following example crops a GIF image.**
Das folgende Beispiel schneidet ein GIF‑Bild zu. Der Beschnittbereich wird über Aspose.Imaging.Rectangle angegeben.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Schneiden Sie das Bild zu. Der Zuschnittsbereich ist der rechteckige zentrale Bereich des Bildes.
    com.aspose.imaging.Rectangle area = new com.aspose.imaging.Rectangle(
            gifImage.getWidth() / 4,
            gifImage.getHeight() / 4,
            gifImage.getWidth() / 2,
            gifImage.getHeight() / 2);
    gifImage.crop(area);

    // Speichern Sie das zugeschnittene Bild als PNG
    gifImage.save(dir + "sample.Crop.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gamma) {#adjustGamma-float-}
```
public void adjustGamma(float gamma)
```


Verbessern Sie die Bildqualität durch Anwendung einer Gammakorrektur. Diese Methode passt das Farb‑Gamma des Bildes an, um optimale visuelle Klarheit zu erreichen. Sie verändert den Gamma‑Wert jedes Pixels, was zu einer verbesserten Farbwiedergabe und einem insgesamt besseren Bildaussehen führt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Gamma | float | Gamma für Rot-, Grün- und Blaukanäle-Koeffizient |


**Example: The following example performs gamma-correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Setzen Sie den Gamma-Koeffizienten für Rot-, Grün- und Blaukanäle.
    gifImage.adjustGamma(2.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### filter(Rectangle rectangle, FilterOptionsBase options) {#filter-com.aspose.imaging.Rectangle-com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase-}
```
public void filter(Rectangle rectangle, FilterOptionsBase options)
```


Wenden Sie einen bestimmten Filter auf den vorgesehenen Bereich des Bildes an, um dessen visuelle Qualität zu verbessern oder das Aussehen nach Wunsch zu verändern. Diese Methode verarbeitet gezielt die Pixel innerhalb des definierten Rechtecks, ermöglicht gezielte Anpassungen und bewahrt gleichzeitig die Integrität der umgebenden Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |
| options | [FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase) | Die Optionen. |


**Example: The following example applies various types of filters to a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen Medianfilter mit einer Rechteckgröße von 5 auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MedianFilterOptions(5));
    gifImage.save(dir + "sample.MedianFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen bilateralen Glättungsfilter mit einer Kernelgröße von 5 auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.BilateralSmoothingFilterOptions(5));
    gifImage.save(dir + "sample.BilateralSmoothingFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen Gaußschen Weichzeichner mit einem Radius von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussianBlurFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussianBlurFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen Gauss-Wiener-Filter mit einem Radius von 5 und einem Glättungswert von 4,0 auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.GaussWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen Bewegungs-Wiener-Filter mit einer Länge von 5, einem Glättungswert von 4,0 und einem Winkel von 90,0 Grad auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions(10, 1.0, 90.0));
    gifImage.save(dir + "sample.MotionWienerFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}

image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Wenden Sie einen Schärfungsfilter mit einer Kernelgröße von 5 und einem Sigma-Wert von 4,0 auf das gesamte Bild an.
    gifImage.filter(gifImage.getBounds(), new com.aspose.imaging.imagefilters.filteroptions.SharpenFilterOptions(5, 4.0));
    gifImage.save(dir + "sample.SharpenFilter.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### setFrameTime(int time) {#setFrameTime-int-}
```
public void setFrameTime(int time)
```


Passt die Dauer jedes Frames in Millisekunden an und sorgt für ein konsistentes Timing in der gesamten Bildsequenz. Diese Methode legt die Anzeigedauer jedes Frames einheitlich fest, wodurch eine präzise Steuerung der Animationsgeschwindigkeit möglich ist. Das Ändern dieses Werts setzt die Verzögerung für alle Frames zurück.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Zeit | int | Die Zeitdauer des Frames in Millisekunden. |

### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Passt die Helligkeit des Bildes gemäß dem angegebenen `brightness`‑Parameter an. Diese Methode verändert die Helligkeit des gesamten Bildes einheitlich und erhöht oder verringert die Gesamthelligkeit, um den gewünschten Effekt zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightness | int | Helligkeitswert. |


**Example: The following example performs brightness correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Legen Sie den Helligkeitswert fest. Die zulässigen Helligkeitswerte liegen im Bereich [-255, 255].
    gifImage.adjustBrightness(50);
    gifImage.save(dir + "sample.AdjustBrightness.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustContrast(float contrast) {#adjustContrast-float-}
```
public void adjustContrast(float contrast)
```


Passt den Kontrast des Bildes an, indem es den Unterschied in der Helligkeit zwischen den Pixeln verstärkt oder reduziert. Diese Methode verändert den gesamten Tonwertumfang des Bildes, sodass dunklere Bereiche dunkler und hellere Bereiche heller werden, um die visuelle Klarheit und Detailgenauigkeit zu verbessern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| contrast | float | Kontrastwert (im Bereich [-100; 100]) |


**Example: The following example performs contrast correction of a GIF image.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Legen Sie den Kontrastwert fest. Die zulässigen Kontrastwerte liegen im Bereich [-100f, 100f].
    gifImage.adjustContrast(50f);
    gifImage.save(dir + "sample.AdjustContrast.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### adjustGamma(float gammaRed, float gammaGreen, float gammaBlue) {#adjustGamma-float-float-float-}
```
public void adjustGamma(float gammaRed, float gammaGreen, float gammaBlue)
```


Die Gammakorrektur eines Bildes wendet eine nichtlineare Anpassung der Pixelwerte an und erhöht oder reduziert die Helligkeit basierend auf den angegebenen Koeffizienten für die Rot‑, Grün‑ und Blaukanäle. Diese Methode hilft, die Farbbalance und die Luminanz des Bildes fein abzustimmen, wodurch das Gesamtbild und die visuelle Qualität verbessert werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| gammaRed | float | Gamma‑Koeffizient für den Rotkanal |
| gammaGreen | float | Gamma‑Koeffizient für den Grünkanal |
| gammaBlue | float | Gamma für den Blaukanal-Koeffizienten |


**Example: The following example performs gamma-correction of a GIF image applying different coefficients for color components.**

``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Setzen Sie individuelle Gamma-Koeffizienten für die Rot-, Grün- und Blaukanäle.
    gifImage.adjustGamma(1.5f, 2.5f, 3.5f);
    gifImage.save(dir + "sample.AdjustGamma.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### grayscale() {#grayscale--}
```
public void grayscale()
```


Die Umwandlung eines Bildes in seine Graustufen‑Darstellung konvertiert das Farbbild in eine Graustufen‑Version, indem Farbinformationen entfernt werden, während die Luminanz erhalten bleibt. Dieser Vorgang vereinfacht das Bild zu Grautönen und macht es für verschiedene Anwendungen wie Druck, Dokumentenverarbeitung und Graustufen‑Analyse geeignet.


**Example: The following example transforms a colored GIF image to its grayscale representation.**
Das folgende Beispiel wandelt ein farbiges GIF‑Bild in seine Graustufen‑Darstellung um. Graustufen‑Bilder bestehen ausschließlich aus Grautönen und enthalten nur Intensitätsinformationen.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    gifImage.grayscale();
    gifImage.save(dir + "sample.Grayscale.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeFixed(byte threshold) {#binarizeFixed-byte-}
```
public void binarizeFixed(byte threshold)
```


Die Binarisierung eines Bildes mit einem vordefinierten Schwellenwert konvertiert ein Graustufen‑ oder Farbbild in ein Binärbild, wobei jeder Pixel als schwarz oder weiß klassifiziert wird, abhängig davon, ob sein Intensitätswert einen angegebenen Schwellenwert überschreitet.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| threshold | byte | Schwellenwert. Wenn der entsprechende Grauwert eines Pixels größer als der Schwellenwert ist, wird ihm der Wert 255 zugewiesen, andernfalls 0. |


**Example: The following example binarizes a GIF image with the predefined threshold.**
Das folgende Beispiel binarisiert ein GIF‑Bild mit dem vordefinierten Schwellenwert. Binarisierte Bilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage djvuImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

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


Binarisierung eines Bildes mit Otsu‑Schwellwertbestimmung ist ein Verfahren, das verwendet wird, um automatisch den optimalen Schwellenwert für die Umwandlung eines Graustufen‑Bildes in ein Binärbild zu bestimmen. Der Otsu‑Algorithmus berechnet den Schwellenwert, der die Intra‑Klassen‑Varianz der Pixelintensitäten in den beiden resultierenden Klassen (Vordergrund und Hintergrund) minimiert. Diese Technik ist besonders nützlich, wenn der optimale Schwellenwert unbekannt ist und adaptiv basierend auf dem Histogramm des Bildes ermittelt werden muss.


**Example: The following example binarizes a GIF image with Otsu thresholding.**
Das folgende Beispiel binarisiert ein GIF‑Bild mit Otsu‑Schwellwertbestimmung. Binarisierte Bilder enthalten nur 2 Farben – Schwarz und Weiß.
``` java
String dir = "c:\\temp\\";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(dir + "sample.gif");
try {
    com.aspose.imaging.fileformats.gif.GifImage gifImage = (com.aspose.imaging.fileformats.gif.GifImage) image;

    // Binarisieren Sie das Bild mit Otsu‑Schwellenwertverfahren.
    gifImage.binarizeOtsu();
    gifImage.save(dir + "sample.BinarizeOtsu.png", new com.aspose.imaging.imageoptions.PngOptions());
} finally {
    image.dispose();
}
```

### binarizeBradley(double brightnessDifference) {#binarizeBradley-double-}
```
public void binarizeBradley(double brightnessDifference)
```


Binarisierung eines Bildes mittels Bradleys adaptivem Schwellwert‑Algorithmus mit Integral‑Bild‑Schwellwertbestimmung ist ein Verfahren zur Umwandlung eines Graustufen‑Bildes in ein Binärbild. Dieser Algorithmus berechnet für jedes Pixel einen lokalen Schwellenwert basierend auf dem durchschnittlichen Intensitätswert der umliegenden Pixel innerhalb eines festgelegten Fensters. Durch die adaptive Anpassung des Schwellenwerts an die lokalen Pixelintensitäten ist Bradleys Methode effektiv beim Umgang mit Beleuchtungs‑ und Kontrastschwankungen im Bild.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| brightnessDifference | double | Der Helligkeitsunterschied zwischen dem Pixel und dem Durchschnitt eines s × s‑Fensters von Pixeln, das um dieses Pixel zentriert ist. |

### orderBlocks() {#orderBlocks--}
```
public void orderBlocks()
```


Das Anordnen der GIF‑Blöcke gemäß der GIF‑Spezifikation gewährleistet ein korrektes GIF‑Layout und die Einhaltung des Standards. Dieser Vorgang beinhaltet das Anordnen der Blöcke in der richtigen Reihenfolge, wie in der Spezifikation definiert. Zusätzlich kann es das Entfernen bestimmter [GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock)-Instanzen umfassen, die für das endgültige Layout nicht erforderlich sind. Durch die Einhaltung der GIF‑Spezifikation wird das resultierende Bild korrekt strukturiert und ist mit GIF‑Betrachtungsanwendungen kompatibel.

### clearBlocks() {#clearBlocks--}
```
public void clearBlocks()
```


Das Löschen aller GIF‑Blöcke entfernt alle im Bild gespeicherten Daten. Dieser Vorgang setzt das Bild effektiv in einen leeren Zustand zurück und entfernt alle zuvor hinzugefügten Blöcke. Verwenden Sie diese Methode, wenn Sie mit einer sauberen Basis für das Erstellen oder Ändern eines GIF‑Bildes beginnen möchten.


**Example: The following example shows how to remove all blocks from a GIF image.**

``` java
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }

    System.out.println("Clear all the blocks");
    gifImage.clearBlocks();

    if (gifImage.getActiveFrame() != null) {
        System.out.println("Active frame size: " + gifImage.getActiveFrame().getSize());
    } else {
        System.out.println("Active frame is not set");
    }
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}

// Die Ausgabe sieht folgendermaßen aus:
// Aktive Frame-Größe: { Width = 100, Height = 100}
// Alle Blöcke löschen
// Aktiver Frame ist nicht gesetzt
```

### insertBlock(int index, IGifBlock block) {#insertBlock-int-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void insertBlock(int index, IGifBlock block)
```


Das Einfügen eines neuen GIF‑Blocks ermöglicht es, benutzerdefinierte Daten an einer bestimmten Position im Bild hinzuzufügen. Diese Methode erlaubt das Platzieren von benutzerdefinierten Blöcken an einer gewünschten Stelle im GIF‑Bild und bietet Flexibilität bei der Organisation und Strukturierung der Bilddaten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | int | Das nullbasierte Element, an dem der Block eingefügt wird. |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Der hinzuzufügende GIF‑Block. |

### addBlock(IGifBlock block) {#addBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void addBlock(IGifBlock block)
```


Das Hinzufügen eines neuen GIF‑Blocks ermöglicht es, zusätzliche Daten im Bild zu integrieren. Diese Methode erlaubt das Anhängen benutzerdefinierter Blöcke an das GIF‑Bild, die verschiedene Arten von Informationen enthalten können.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Der hinzuzufügende GIF‑Block. |


**Example: The following example shows how to compose an animated GIF image from individual GIF blocks.**

``` java
String dir = "c:\\temp\\";

// Erstellen Sie ein GIF‑Bild mit 100 × 100 px.
// Der erste Block ist standardmäßig vollständig schwarz.
com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock firstBlock = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);
com.aspose.imaging.fileformats.gif.GifImage gifImage = new com.aspose.imaging.fileformats.gif.GifImage(firstBlock);
try {
    // Der erste Kreis ist rot
    com.aspose.imaging.brushes.SolidBrush brush1 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    // Der zweite Kreis ist schwarz
    com.aspose.imaging.brushes.SolidBrush brush2 = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getBlack());

    // Erhöhen Sie schrittweise den Winkel der roten Bogenform.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush1, block.getBounds(), 0, angle);

        gifImage.addBlock(block);
    }

    // Erhöhen Sie schrittweise den Winkel des schwarzen Bogens und entfernen Sie den roten Bogen.
    for (int angle = 10; angle <= 360; angle += 10) {
        com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock block = new com.aspose.imaging.fileformats.gif.blocks.GifFrameBlock(100, 100);

        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(block);
        gr.fillPie(brush2, block.getBounds(), 0, angle);
        gr.fillPie(brush1, block.getBounds(), angle, 360 - angle);

        gifImage.addBlock(block);
    }

    gifImage.save(dir + "animated_radar.gif");
} finally {
    firstBlock.dispose();
    gifImage.dispose();
}
```

### removeBlock(IGifBlock block) {#removeBlock-com.aspose.imaging.fileformats.gif.IGifBlock-}
```
public void removeBlock(IGifBlock block)
```


Das Entfernen eines GIF-Blocks entfernt spezifische Daten aus dem Bild und bietet die Möglichkeit, die Bildstruktur zu bereinigen oder zu ändern. Diese Methode ermöglicht es Ihnen, unerwünschte oder unnötige Blöcke zu entfernen und das GIF-Bild für eine effiziente Speicherung zu optimieren. Verwenden Sie diese Funktion, um veraltete Informationen aus dem Bild zu eliminieren, während Sie dessen Integrität und Qualität erhalten.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
|  | block | [IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock) | Der zu entfernende Block. |

--------------------

Hinweis: Vergessen Sie nicht, den Block zu entsorgen, wenn Sie ihn nicht zu einem anderen GifImage hinzufügen. |

### resizeProportional(int newWidth, int newHeight, int resizeType) {#resizeProportional-int-int-int-}
```
public void resizeProportional(int newWidth, int newHeight, int resizeType)
```


Die proportionale Größenänderung bewahrt das Seitenverhältnis des Bildes, während seine Größe angepasst wird, und stellt sicher, dass das Bild nicht gestreckt oder verzerrt erscheint. Diese Methode ändert die Größe des Bildes proportional, indem sowohl Breite als auch Höhe um denselben Faktor skaliert werden. Die proportionale Größenänderung passt jedes Bildframe gemäß dem Verhältnis von `newWidth`/width und `newHeight`/height an.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| resizeType | int | Der Skalierungstyp. |

### rotate(float angle, boolean resizeProportionally, Color backgroundColor) {#rotate-float-boolean-com.aspose.imaging.Color-}
```
public void rotate(float angle, boolean resizeProportionally, Color backgroundColor)
```


Diese Methode dreht das Bild um seinen Mittelpunkt. Durch Angabe des Rotationswinkels können Sie das Bild im Uhrzeigersinn oder gegen den Uhrzeigersinn drehen, um die gewünschte Ausrichtung zu erreichen. Diese Drehung hilft, die Darstellung oder Ausrichtung des Bildes anzupassen, ohne dessen Inhalt zu verzerren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

