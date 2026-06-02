---
title: "EmfImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die API für die Unterstützung des Vektorbildformats Enhanced Metafile Format EMF ist ein umfassendes Werkzeug zur Verarbeitung grafischer Bilder geräteunabhängig, wobei die ursprünglichen Eigenschaften erhalten bleiben."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.emf/emfimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.fileformats.emf.MetaImage](../../com.aspose.imaging.fileformats.emf/metaimage)
```
public final class EmfImage extends MetaImage
```

Die API für die Unterstützung des Vektorbildformats Enhanced Metafile Format (EMF) ist ein umfassendes Werkzeug zur Verarbeitung grafischer Bilder geräteunabhängig, wobei die ursprünglichen Eigenschaften erhalten bleiben. Entwickelt, um Proportionen, Abmessungen, Farben und andere grafische Attribute beizubehalten, beinhaltet sie Unterstützung für das EMF Plus‑Format sowie Funktionen zum Beschneiden von Bereichen, Ändern der Leinwand- und Bildgröße, Drehen, Spiegeln, Festlegen von Bildpaletten, Exportieren und Importieren in den APS‑Gerätekontext, Komprimieren und Konvertieren von EMF in andere Formate, wodurch eine vielseitige Manipulation und nahtlose Integration von EMF‑Bildern in Anwendungen gewährleistet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfImage()](#EmfImage--) | Beginnen Sie mit EMF‑Bildern zu arbeiten, indem Sie eine neue Instanz der Klasse [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) initialisieren. |
| [EmfImage(int width, int height)](#EmfImage-int-int-) | Erstellen Sie eine neue Instanz der Klasse [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage), indem Sie die Parameter für Breite und Höhe angeben. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getHeader()](#getHeader--) | Rufen Sie den EMF‑Metadatei‑Header‑Datensatz mit dieser Eigenschaft ab. |
| [setHeader(EmfMetafileHeader value)](#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Ändern Sie den EMF‑Metadatei‑Header‑Datensatz mit dieser Eigenschaft. |
| [isCached()](#isCached--) | Greifen Sie auf einen Wert zu, der angibt, ob die Daten des Objekts derzeit im Cache sind, wodurch ein zusätzliches Einlesen von Daten entfällt. |
| [getRecords()](#getRecords--) | Rufen Sie die mit dem Objekt verknüpften Datensätze ab oder ändern Sie sie. |
| [setRecords(MetaObjectList value)](#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-) | Ändern Sie die mit dem Objekt verknüpften Datensätze. |
| [getFileFormat()](#getFileFormat--) | Greifen Sie auf den Dateiformatwert zu, der dem Objekt zugeordnet ist. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Rufen Sie die Bit‑pro‑Pixel‑Anzahl ab, die für Rasterbilder gilt, da dieser Parameter bei Vektorbildern nicht zutrifft. |
| [getWidthF()](#getWidthF--) | Zugriff auf die Breite des Bildes, der wesentliche Informationen für präzises Rendern und Verarbeiten liefert. |
| [getHeightF()](#getHeightF--) | Rufen Sie die Höhe des Bildes ab, um ein genaues Rendern und Layout‑Anpassungen zu ermöglichen. |
| [cacheData()](#cacheData--) | Daten effizient im Cache speichern und redundantes Laden aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) mit dieser Methode verhindern. |
| [getUsedFonts()](#getUsedFonts--) | Rufen Sie mit dieser Methode die Liste der im Metadatei verwendeten Schriftarten ab. |
| [resizeCanvas(Rectangle newRectangle)](#resizeCanvas-com.aspose.imaging.Rectangle-) | Ändern Sie die Größe der Leinwand mühelos mit dieser Funktion. |
| [getOriginalOptions()](#getOriginalOptions--) | Liefert die ursprünglichen Bildoptionen. |
| [setPalette(IColorPalette palette, boolean updateColors)](#setPalette-com.aspose.imaging.IColorPalette-boolean-) | Legt die Bildpalette fest. |

## Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen einschließlich EMF zu laden.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    com.aspose.imaging.imageoptions.SvgOptions saveOptions = new com.aspose.imaging.imageoptions.SvgOptions();

    // Text wird in Formen konvertiert.
    saveOptions.setTextAsShapes(true);

    com.aspose.imaging.imageoptions.EmfRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();

    // Die Hintergrundfarbe der Zeichenfläche.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhiteSmoke());

    // Die Seitengröße.
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(emfImage.getWidth(), emfImage.getHeight()));

    // Wenn ein eingebettetes EMF vorhanden ist, wird EMF gerendert; andernfalls wird WMF gerendert.
    rasterizationOptions.setRenderMode(com.aspose.imaging.fileformats.emf.EmfRenderMode.Auto);

    // Setzen Sie den horizontalen Rand
    rasterizationOptions.setBorderX(50);

    // Setzen Sie den vertikalen Rand
    rasterizationOptions.setBorderY(50);

    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    emfImage.save(dir + "test.output.svg", saveOptions);
} finally {
    emfImage.dispose();
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


## Example: The following example shows how to convert a emz images to emf format

``` java
String file = "example.emz";
String baseFolder = "D:\\Compressed\\";
String inputFile = (baseFolder + file);
String outFile = inputFile + ".emf";
try (final com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    final com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions()
    {{
        setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    }};
    image.save(outFile, new com.aspose.imaging.imageoptions.EmfOptions()
    {{
        setVectorRasterizationOptions(vectorRasterizationOptions);
    }});
}
```


## Example: The following example shows how to convert a emf images to emz format

``` java
String file = "input.emf";
String baseFolder = "D:\\Compressed\\";
String inputFile = baseFolder + file;
String outFile = inputFile + ".emz";
try (com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFile))
{
    com.aspose.imaging.imageoptions.VectorRasterizationOptions vectorRasterizationOptions = new com.aspose.imaging.imageoptions.EmfRasterizationOptions();
    vectorRasterizationOptions.setPageSize(com.aspose.imaging.Size.to_SizeF(image.getSize()));
    com.aspose.imaging.imageoptions.EmfOptions options = new com.aspose.imaging.imageoptions.EmfOptions();
    options.setVectorRasterizationOptions(vectorRasterizationOptions);
    options.setCompress(true);
    image.save(outFile, options);
}
```

### EmfImage() {#EmfImage--}
```
public EmfImage()
```


Beginnen Sie mit EMF‑Bildern zu arbeiten, indem Sie eine neue Instanz der Klasse [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage) initialisieren. Ideal, um EMF‑Bilder schnell und effizient in Ihre Projekte zu integrieren.

### EmfImage(int width, int height) {#EmfImage-int-int-}
```
public EmfImage(int width, int height)
```


Erstellen Sie eine neue Instanz der Klasse [EmfImage](../../com.aspose.imaging.fileformats.emf/emfimage), indem Sie die Parameter für Breite und Höhe angeben. Dieser Konstruktor vereinfacht den Vorgang, EMF‑Bilder mit spezifischen Abmessungen zu initialisieren, und steigert die Effizienz Ihres Entwicklungs‑Workflows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Breite | int | Die Breite. |
| Höhe | int | Die Höhe. |

### getHeader() {#getHeader--}
```
public EmfMetafileHeader getHeader()
```


Rufen Sie den EMF‑Metadatei‑Header‑Datensatz mit dieser Eigenschaft ab. Ideal, um Metadatei‑Daten in Ihrer Anwendung effizient zu verwalten. Verbessern Sie Ihren Workflow durch einen optimierten Zugriff auf Header‑Informationen der Metadatei.

**Returns:**
[EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader)
### setHeader(EmfMetafileHeader value) {#setHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public void setHeader(EmfMetafileHeader value)
```


Ändern Sie den EMF‑Metadatei‑Header‑Datensatz mit dieser Eigenschaft. Ideal, um Metadatei‑Daten in Ihrer Anwendung effizient zu verwalten. Verbessern Sie Ihren Workflow durch einen optimierten Zugriff auf Header‑Informationen der Metadatei.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) |  |

### isCached() {#isCached--}
```
public boolean isCached()
```


Greifen Sie auf einen Wert zu, der angibt, ob die Daten des Objekts derzeit im Cache sind, wodurch ein zusätzliches Einlesen von Daten entfällt. Steigern Sie die Effizienz, indem Sie schnell feststellen, ob zwischengespeicherte Daten sofort verfügbar sind. Optimieren Sie Ihren Workflow mit optimierten Datenabrufprozessen.

**Returns:**
boolean – `true`, wenn die Daten des Objekts im Cache sind; andernfalls `false`.
### getRecords() {#getRecords--}
```
public MetaObjectList getRecords()
```


Abrufen oder Ändern der mit dem Objekt verknüpften Datensätze. Effizient auf die Sammlung von Datensätzen zugreifen und sie verwalten für verbesserte Datenmanipulation und -verarbeitung. Optimieren Sie Ihren Arbeitsablauf, indem Sie nahtlos mit den Datensätzen des Objekts interagieren.

**Returns:**
[MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) - The records.
### setRecords(MetaObjectList value) {#setRecords-com.aspose.imaging.fileformats.emf.MetaObjectList-}
```
public void setRecords(MetaObjectList value)
```


Ändern Sie die mit dem Objekt verknüpften Datensätze. Effizient auf die Sammlung von Datensätzen zugreifen und sie verwalten für verbesserte Datenmanipulation und -verarbeitung. Optimieren Sie Ihren Arbeitsablauf, indem Sie nahtlos mit den Datensätzen des Objekts interagieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [MetaObjectList](../../com.aspose.imaging.fileformats.emf/metaobjectlist) | Die Datensätze. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Greifen Sie auf den Dateiformatwert zu, der dem Objekt zugeordnet ist. Bestimmen Sie einfach das Format der dem Objekt zugehörigen Datei für optimierte Verarbeitung und Kompatibilitätsprüfungen. Vereinfachen Sie Ihren Arbeitsablauf, indem Sie die Dateiformatinformationen mühelos abrufen.

**Returns:**
long
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie die Bit‑pro‑Pixel‑Anzahl für Rasterbilder ab, da dieser Parameter nicht für Vektorbilder gilt. Ermitteln Sie schnell die Pixeltiefe von Rasterbildern für präzise Analyse und Manipulation und gewährleisten Sie eine genaue Handhabung der Bilddaten.

**Returns:**
int – Die Bild-Bits‑pro‑Pixel‑Anzahl.
### getWidthF() {#getWidthF--}
```
public float getWidthF()
```


Zugriff auf die Breite des Bildes, um wesentliche Informationen für präzises Rendering und Verarbeitung bereitzustellen. Rufen Sie schnell die Bildbreite ab, um Kompatibilität und korrekte Anordnung in verschiedenen Anwendungen und Plattformen sicherzustellen.

**Returns:**
float - Die Bildbreite in Pixeln.
### getHeightF() {#getHeightF--}
```
public float getHeightF()
```


Rufen Sie die Höhe des Bildes ab, um genaues Rendering und Layout‑Anpassungen zu ermöglichen. Der Zugriff auf die Höheneigenschaft gewährleistet Kompatibilität und nahtlose Integration über verschiedene Plattformen und Anwendungen hinweg.

**Returns:**
float - Die Bildhöhe in Pixeln.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Daten effizient zwischenspeichern und redundantes Laden aus dem zugrunde liegenden `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer) mit dieser Methode verhindern. Verbessern Sie die Leistung und optimieren Sie den Datenzugriff in Ihrer Anwendung, um die Ressourcennutzung für eine höhere Reaktionsfähigkeit zu optimieren.


**Example: This example shows how to load a EMF image from a file and list all of its records.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, um alle Bildtypen, einschließlich WMF, zu laden.
com.aspose.imaging.fileformats.emf.EmfImage emfImage = (com.aspose.imaging.fileformats.emf.EmfImage) com.aspose.imaging.Image.load(dir + "test.emf");
try {
    // Daten im Cache speichern, um alle Datensätze zu laden.
    emfImage.cacheData();
    System.out.println("The total number of records: " + emfImage.getRecords().size());

    // Der Schlüssel ist ein Datensatztyp, der Wert ist die Anzahl der Datensätze dieses Typs im WMF‑Bild.
    java.util.HashMap<Class, Integer> types =
            new java.util.HashMap<>();

    // Statistiken sammeln
    for (Object obj : emfImage.getRecords()) {
        com.aspose.imaging.fileformats.emf.emf.records.EmfRecord record = (com.aspose.imaging.fileformats.emf.emf.records.EmfRecord) obj;

        Class objType = record.getClass();
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
    emfImage.dispose();
}

//Die Ausgabe könnte so aussehen:
//Die Gesamtzahl der Datensätze: 1188
//Datensatztyp                              Anzahl
//----------------------------------------------
//EmfMetafileHeader:                       1
//EmfSetBkMode:                            1
//EmfSetTextAlign:                         1
//EmfSetRop2:                              1
//EmfSetWorldTransform:                    1
//EmfExtSelectClipRgn:                     1
//EmfCreateBrushIndirect:                  113
//EmfSelectObject:                         240
//EmfCreatePen:                            116
//EmfSetPolyFillMode:                      1
//EmfBeginPath:                            120
//EmfMoveToEx:                             122
//EmfPolyBezierTo16:                       36
//EmfLineTo:                               172
//EmfCloseFigure:                          14
//EmfEndPath:                              120
//EmfStrokeAndFillPath:                    113
//EmfStrokePath:                           7
//EmfSetTextColor:                         2
//EmfExtCreateFontIndirectW:               2
//EmfExtTextOutW:                          2
//EmfStretchBlt:                           1
//EmfEof:                                  1
```

### getUsedFonts() {#getUsedFonts--}
```
public String[] getUsedFonts()
```


Rufen Sie die Liste der im Metafile verwendeten Schriftarten mit dieser Methode ab. Gewinnen Sie Einblicke in die Schriftartnutzung, um eine effiziente Verwaltung und Optimierung der Schriftressourcen für verbessertes Rendering und Anzeigetreue zu ermöglichen.

**Returns:**
java.lang.String[] - Die Schriftartenliste
### resizeCanvas(Rectangle newRectangle) {#resizeCanvas-com.aspose.imaging.Rectangle-}
```
public void resizeCanvas(Rectangle newRectangle)
```


Ändern Sie die Leinwandgröße mühelos mit dieser Funktion. Ideal, um die Gesamtabmessungen des Bildes anzupassen, ohne dessen Inhalt zu verändern. Verbessern Sie die Präsentation und bereiten Sie Bilder für verschiedene Anzeigegrößen mühelos vor.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newRectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das neue Rechteck. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Liefert die ursprünglichen Bildoptionen.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The original image options.
### setPalette(IColorPalette palette, boolean updateColors) {#setPalette-com.aspose.imaging.IColorPalette-boolean-}
```
public void setPalette(IColorPalette palette, boolean updateColors)
```


Legt die Bildpalette fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| palette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Die zu setzende Palette. |
| updateColors | boolean | Wenn auf `true` gesetzt, werden die Farben gemäß der neuen Palette aktualisiert; andernfalls bleiben die Farbindizes unverändert. Beachten Sie, dass unveränderte Indizes das Bild beim Laden zum Absturz bringen können, wenn einige Indizes keinen entsprechenden Paletteneintrag haben. |

