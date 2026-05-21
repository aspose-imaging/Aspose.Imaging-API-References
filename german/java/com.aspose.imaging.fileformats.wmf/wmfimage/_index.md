---
title: "WmfImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie Microsoft Windows Metafile WMF-Bilder mit unserer API und verarbeiten dabei nahtlos sowohl Vektor- als auch Bitmap-Daten, die in variablen Längendatensätzen gespeichert sind."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.wmf/wmfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public class WmfImage extends MetaImage
```

Manipulieren Sie Microsoft Windows Metafile (WMF)-Bilder mit unserer API und verarbeiten dabei nahtlos sowohl Vektor- als auch Bitmap-Daten, die in variablen Längendatensätzen gespeichert sind. Skalieren, drehen und spiegeln Sie Bilder mühelos, während Sie benutzerdefinierte Bildpaletten festlegen. Konvertieren Sie WMF-Dateien in komprimierte WMZ-Formate oder speichern Sie sie in Rasterbildformaten für vielseitige Verwendung auf verschiedenen Plattformen und in Anwendungen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [WmfImage()](#WmfImage--) | Erstellen Sie eine neue Instanz der Klasse [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) und initialisieren Sie sie für die weitere Manipulation und Verarbeitung von Windows Metafile (WMF)-Bilddaten. |
| [WmfImage(int width, int height)](#WmfImage-int-int-) | Instanziieren Sie eine neue Instanz der Klasse [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage) mit anpassbaren Breiten- und Höhenparametern, um leere WMF-Bilder zu erstellen, die auf bestimmte Abmessungen zugeschnitten sind. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [isCached()](#isCached--) | Rufen Sie einen booleschen Wert ab, der angibt, ob die Daten des Objekts derzeit im Cache gespeichert sind, wodurch zusätzliche Lesevorgänge entfallen. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie die Anzahl der Bits pro Pixel des Bildes ab, was die Farbtiefe bzw. Granularität angibt. |
| [getWidthF()](#getWidthF--) | Greifen Sie auf die Breite des Bildes zu, die die Anzahl der Pixel entlang der horizontalen Achse angibt. |
| [getHeightF()](#getHeightF--) | Greifen Sie auf die Höhe des Bildes zu, die die Anzahl der Pixel entlang der vertikalen Achse darstellt. |
| [getInch()](#getInch--) | Greifen Sie auf die Eigenschaft inch zu oder ändern Sie sie, die eine üblicherweise zur Angabe physischer Abmessungen im Druck- oder Anzeige‑Kontext verwendete Maßeinheit darstellt. |
| [setInch(int value)](#setInch-int-) | Greifen Sie auf die Eigenschaft inch zu oder ändern Sie sie, die eine üblicherweise zur Angabe physischer Abmessungen im Druck- oder Anzeige‑Kontext verwendete Maßeinheit darstellt. |
| [getFileFormat()](#getFileFormat--) | Greifen Sie auf den Dateiformatwert zu, der dem Bild zugeordnet ist, und erhalten Sie Informationen über das Format, in dem das Bild gespeichert ist. |
| [getFrameBounds()](#getFrameBounds--) | Greifen Sie auf die Begrenzungen des Frames zu, die dessen Position und Abmessungen im Bild angeben. |
| [cacheData()](#cacheData--) | Cache die Daten effizient, um das zusätzliche Laden aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) zu vermeiden. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Wenden Sie eine angegebene Palette auf das Bild an, um die Farbdarstellung anzupassen. |
| [getUsedFonts()](#getUsedFonts--) | Rufen Sie die Liste der im Metafile verwendeten Schriftarten ab, um Einblick in die im Bild genutzten Schriftressourcen zu erhalten. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändern Sie die Größe der Leinwand des Bildes und passen Sie dessen Abmessungen an, während der Bildinhalt erhalten bleibt. |
| [addRecord(WmfObject record)](#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-) | Integrieren Sie das angegebene Record‑Objekt in das Bild, um dessen Inhalt mit zusätzlichen Daten oder Metadaten zu erweitern. |
| [getPostScript()](#getPostScript--) | Greifen Sie auf die mit dem Bild verknüpften PostScript-Daten zu, die detaillierte Informationen über dessen Struktur oder Inhalt liefern. |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die ursprünglichen Bildoptionen. |

## Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
try (com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage)com.aspose.imaging.Image.load(dir + "test.wmf"))
{
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();
                    
    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.WmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(Size.to_SizeF(wmfImage.getSize()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.wmf.WmfRenderMode.Auto);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    wmfImage.save(dir + "test.output.svg", saveOptions);
}
```


## Example: The following example shows how to convert a compressed images (*.
Das folgende Beispiel zeigt, wie komprimierte Bilder (*.emz, *.wmz, *.svgz) in ein Rasterformat konvertiert werden.
``` java
String[] files = new String[]{ "example.emz", "example.wmz", "example.svgz" };
String baseFolder = "D:\\Compressed\\";
for(String file : files)
{
    String inputFile = (baseFolder + file);
    String outFile = inputFile + ".png";
    try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
    {
        final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = 
                (com.aspose.imaging.imageoptions.VectorRasterizationOptions) image.getDefaultOptions(new Object[]{Color.getWhite(), image.getWidth(), image.getHeight()});
        image.save(outFile, new com.aspose.imaging.imageoptions.PngOptions()
        {{
            setVectorRasterizationOptions(vectorRasterizationOptions);
        }});
    }
}
```


## Example: The following example shows how to convert a wmz images to wmf format

``` java
String file = "example.wmz";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
                
    image.save(outFile, new com.aspose.imaging.imageoptions.WmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a wmf images to wmz format

``` java
String file = "castle.wmf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".wmz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.WmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.WmfOptions options = new com.aspose.imaging.imageoptions.WmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### WmfImage() {#WmfImage--}
```
public WmfImage()
```


Erstellen Sie eine neue Instanz der [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage)-Klasse und initialisieren Sie sie für die weitere Manipulation und Verarbeitung von Windows Metafile (WMF)-Bilddaten. Dieser Konstruktor stellt ein grundlegendes Objekt für die Arbeit mit WMF-Bildern bereit und ermöglicht die nahtlose Integration von WMF-Bildverarbeitungsfunktionen in die Funktionalität Ihrer Anwendung.

### WmfImage(int width, int height) {#WmfImage-int-int-}
```
public WmfImage(int width, int height)
```


Instanziieren Sie eine neue Instanz der [WmfImage](../../com.aspose.imaging.fileformats.wmf/wmfimage)-Klasse mit anpassbaren Breiten- und Höhenparametern, um leere WMF-Bilder zu erstellen, die auf bestimmte Abmessungen zugeschnitten sind. Verwenden Sie diesen Konstruktor, um WMF-Bilder mit genauen Abmessungen dynamisch zu erzeugen und flexible Bildgenerierung sowie -manipulation in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### isCached() {#isCached--}
```
public boolean isCached()
```


Rufen Sie einen booleschen Wert ab, der angibt, ob die Daten des Objekts derzeit im Cache gespeichert sind, wodurch zusätzliche Lesevorgänge entfallen. Nutzen Sie diese Eigenschaft, um die Leistung zu optimieren, indem Sie feststellen, ob die Daten des Objekts sofort verfügbar sind, ohne kostspielige Datenabrufprozesse in Ihrer Anwendung.

**Returns:**
boolean
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie die Anzahl der Bits pro Pixel des Bildes ab, was die Farbtiefe oder Granularität angibt. Nutzen Sie diese Eigenschaft, um die Farbdarstellung und Präzision des Bildes zu bestimmen, was Kompatibilitätsprüfungen und farbbezogene Verarbeitung in Ihrer Anwendung erleichtert.

**Returns:**
int
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Greifen Sie auf die Breite des Bildes zu, die die Anzahl der Pixel entlang der horizontalen Achse angibt. Nutzen Sie diese Eigenschaft, um die räumlichen Abmessungen und das Seitenverhältnis des Bildes zu bestimmen, wodurch präzise Layout- und Rendering-Anpassungen in Ihrer Anwendung ermöglicht werden.

**Returns:**
float - Die Bildbreite in Pixeln.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Greifen Sie auf die Höhe des Bildes zu, die die Anzahl der Pixel entlang der vertikalen Achse darstellt. Nutzen Sie diese Eigenschaft, um die räumlichen Abmessungen und das Seitenverhältnis des Bildes zu ermitteln, wodurch genaue Layout- und Rendering-Anpassungen in Ihrer Anwendung ermöglicht werden.

**Returns:**
float - Die Bildhöhe in Pixeln.
### getInch() {#getInch--}
```
public int getInch()
```


Greifen Sie auf die Inch-Eigenschaft zu oder ändern Sie sie, die eine typischerweise zur Angabe physischer Abmessungen im Druck- oder Anzeige‑Kontext verwendete Maßeinheit darstellt. Nutzen Sie diese Eigenschaft, um Inch‑Werte, die dem Bild zugeordnet sind, festzulegen oder abzurufen, wodurch eine genaue Darstellung physischer Abmessungen in Ihrer Anwendung ermöglicht wird.

**Returns:**
int
### setInch(int value) {#setInch-int-}
```
public void setInch(int value)
```


Greifen Sie auf die Inch-Eigenschaft zu oder ändern Sie sie, die eine typischerweise zur Angabe physischer Abmessungen im Druck- oder Anzeige‑Kontext verwendete Maßeinheit darstellt. Nutzen Sie diese Eigenschaft, um Inch‑Werte, die dem Bild zugeordnet sind, festzulegen oder abzurufen, wodurch eine genaue Darstellung physischer Abmessungen in Ihrer Anwendung ermöglicht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Greifen Sie auf den Dateiformatwert zu, der mit dem Bild verknüpft ist, und erhalten Sie Informationen über das Format, in dem das Bild gespeichert ist. Nutzen Sie diese Eigenschaft, um das Dateiformat des Bildes zu bestimmen, was Kompatibilitätsprüfungen und formatbezogene Verarbeitung in Ihrer Anwendung erleichtert.

**Returns:**
long
### getFrameBounds() {#getFrameBounds--}
```
public final Rectangle getFrameBounds()
```


Greifen Sie auf die Grenzen des Frames zu, die dessen Position und Abmessungen im Bild angeben. Nutzen Sie diese Eigenschaft, um detaillierte Informationen über die räumliche Lage des Frames abzurufen, wodurch präzise Manipulation und Rendering in Ihrer Anwendung ermöglicht werden.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the frame bounds.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Daten effizient im Cache speichern und damit das zusätzliche Laden aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)) vermeiden. Nutzen Sie diese Methode, um die Leistung zu optimieren und den Ressourcenverbrauch in Ihrer Anwendung zu minimieren, indem Sie lokale Daten im Cache speichern und darauf zugreifen.


**Example: This example shows how to load a WMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
com.aspose.imaging.fileformats.wmf.WmfImage wmfImage = (com.aspose.imaging.fileformats.wmf.WmfImage) com.aspose.imaging.Image.load(dir + "test.wmf");
try {
    // Daten im Cache speichern, um alle Datensätze zu laden.
    wmfImage.cacheData();
    System.out.println("The total number of records: " + wmfImage.getRecords().size());

    // Der Schlüssel ist ein Datensatztyp, der Wert ist die Anzahl der Datensätze dieses Typs im WMF‑Bild.
    java.util.HashMap<Class, Integer> types = new java.util.HashMap<>();

    // Statistiken sammeln
    for (Object obj : wmfImage.getRecords()) {
        com.aspose.imaging.fileformats.wmf.objects.WmfObject wmfObj = (com.aspose.imaging.fileformats.wmf.objects.WmfObject) obj;

        Class objType = wmfObj.getClass();
        if (!types.containsKey(objType)) {
            types.put(objType, 1);
        } else {
            int n = types.get(objType);
            types.put(objType, n + 1);
        }
    }

    // Statistiken ausgeben
    System.out.println("Record Type                              Count");
    System.out.println("----------------------------------------------");
    for (java.util.Map.Entry<Class, Integer> entry : types.entrySet()) {
        String objectType = entry.getKey().getSimpleName();
        int numberOfEntrances = entry.getValue();

        // Ausgabe mit Leerzeichen ausrichten
        int alignmentPos = 40;
        char[] chars = new char[alignmentPos - objectType.length()];
        java.util.Arrays.fill(chars, ' ');
        String gap = new String(chars);

        System.out.println(objectType + ":" + gap + numberOfEntrances);
    }
} finally {
    wmfImage.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Datensätze: 613
//Datensatztyp                              Anzahl
//----------------------------------------------
//WmfSetBkMode:                            1
//WmfSetTextAlign:                         1
//WmfSetRop2:                              1
//WmfSetWindowOrg:                         1
//WmfSetWindowExt:                         1
//WmfCreateBrushInDirect:                  119
//WmfSelectObject:                         240
//WmfCreatePenInDirect:                    119
//WmfSetPolyFillMode:                      1
//WmfPolyPolygon:                          114
//WmfPolyLine:                             7
//WmfSetTextColor:                         2
//WmfCreateFontInDirect:                   2
//WmfExtTextOut:                           2
//WmfDibStrechBlt:                         1
//WmfEof:                                  1
```

### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Wenden Sie eine angegebene Palette auf das Bild an, um die Farbdarstellung anzupassen. Verwenden Sie diese Methode, um die visuelle Darstellung zu verbessern und spezifische Farbeffekte in Ihrer Anwendung zu erzielen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Rufen Sie die Liste der im Metafile verwendeten Schriftarten ab, um Einblick in die im Bild genutzten Schriftressourcen zu erhalten. Verwenden Sie diese Methode, um die Schriftartnutzung zu analysieren und die Verfügbarkeit von Schriftarten für die Darstellung oder weitere Verarbeitung in Ihrer Anwendung sicherzustellen.

**Returns:**
java.lang.String[] - Die Schriftartenliste
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ändern Sie die Größe der Leinwand des Bildes und passen Sie seine Abmessungen an, während der Bildinhalt erhalten bleibt. Verwenden Sie diese Methode, um die Größe der Leinwand zu ändern, ohne den Inhalt zu verändern, und erleichtern Sie Layout-Anpassungen sowie Kompositionsänderungen in Ihrer Anwendung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das neue Rechteck. |

### addRecord(WmfObject record) {#addRecord-com.aspose.imaging.fileformats.wmf.objects.WmfObject-}
```
public int addRecord(WmfObject record)
```


Integrieren Sie das angegebene Datensatzobjekt in das Bild und erweitern Sie dessen Inhalt um zusätzliche Daten oder Metadaten. Verwenden Sie diese Methode, um Datensatzobjekte nahtlos in das Bild einzufügen und eine umfassende Datenspeicherung sowie -organisation in Ihrer Anwendung zu ermöglichen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| record | [WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject) | Der Datensatz. |

**Returns:**
int - Anzahl der Datensätze.
### getPostScript() {#getPostScript--}
```
public final String getPostScript()
```


Greifen Sie auf die mit dem Bild verknüpften PostScript-Daten zu, um detaillierte Informationen über deren Struktur oder Inhalt zu erhalten. Verwenden Sie diese Methode, um PostScript-Daten für weitere Analysen oder Verarbeitungen in Ihrer Anwendung abzurufen und erweiterte Funktionen im Zusammenhang mit der PostScript-Darstellung oder -Manipulation zu ermöglichen.

**Returns:**
java.lang.String - Das PostScript
### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Liefert die ursprünglichen Bildoptionen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
