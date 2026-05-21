---
title: "TgaImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Manipulieren Sie TGA-Rasterbilddateien mit unserer API, die für das TARGA Truevision Advanced Raster Adapter-Format optimiert ist und ein nahtloses Laden sowie Anpassen ermöglicht."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.fileformats.tga/tgaimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)
```
public class TgaImage extends RasterCachedImage
```

Manipulieren Sie TGA-Rasterbilddateien mit unserer API, die für das TARGA (Truevision Advanced Raster Adapter)-Format optimiert ist und ein nahtloses Laden sowie Anpassen ermöglicht. Aktualisieren Sie problemlos öffentliche Eigenschaften wie Autor, Zeitstempel, Bild-ID und Softwareversion, wobei Sie verschiedene Bits‑pro‑Pixel‑Einstellungen, Alpha‑Kanal und Farbdurchsichtigkeit verwenden können. Zusätzlich können Sie TGA‑Bilder in andere gängige Rasterformate exportieren, um die Kompatibilität für Ihre Projekte sicherzustellen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [TgaImage(String path)](#TgaImage-java.lang.String-) | Initialisiert ein neues [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) Objekt mit dem angegebenen Dateipfad zum Laden des Bildinhalts. |
| [TgaImage(RasterImage rasterImage)](#TgaImage-com.aspose.imaging.RasterImage-) | Erstellt eine neue Instanz der Klasse [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) durch Angabe eines Rasterbildobjekts. |
| [TgaImage(InputStream stream)](#TgaImage-java.io.InputStream-) | Initialisiert eine neue Instanz der Klasse [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) mithilfe eines Streams zum Laden des Bildes. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Ruft den Bits‑pro‑Pixel‑Wert ab und liefert wesentliche Informationen zur Farbtiefe des Bildes. |
| [getBytesPerPixel()](#getBytesPerPixel--) | Ermittelt den Bytes‑pro‑Pixel‑Wert, der die vom jeweiligen Pixel im Bild belegte Speichermenge angibt. |
| [hasAlpha()](#hasAlpha--) | Ruft einen booleschen Wert ab, der angibt, ob das [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) einen Alphakanal enthält, wodurch Transparenzeffekte ermöglicht werden. |
| [isGrayScale()](#isGrayScale--) | Ermittelt einen booleschen Wert, der angibt, ob das [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) ein Graustufenbild darstellt. |
| [getWidth()](#getWidth--) | Ruft die Breite des von dieser [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz dargestellten Bildes ab. |
| [getHeight()](#getHeight--) | Ermittelt die Höhe des von dieser [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz gekapselten Bildes. |
| [getFileFormat()](#getFileFormat--) | Liefert wichtige Informationen zum Dateiformat des von dieser Instanz von [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) dargestellten Bildes. |
| [hasColorMap()](#hasColorMap--) | Ermittelt, ob diese [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz eine Farbkarte enthält. |
| [getGammaValueNumerator()](#getGammaValueNumerator--) | Gibt den Zählerteil des Gamma‑Werts zurück, der für eine genaue Farbdarstellung in Bildern entscheidend ist. |
| [getGammaValueDenominator()](#getGammaValueDenominator--) | Ermittelt den Nennerteil des Gamma‑Werts, ein wesentlicher Faktor zur Bestimmung der Farbdarstellung in Bildern. |
| [getPixelAspectRatioNumerator()](#getPixelAspectRatioNumerator--) | Ermittelt die Zählerkomponente des Pixel‑Seitenverhältnisses, die das visuelle Erscheinungsbild der Pixel im Bild beeinflusst. |
| [getPixelAspectRatioDenominator()](#getPixelAspectRatioDenominator--) | Ermittelt den Nennerteil des Pixel‑Seitenverhältnisses, ein entscheidender Faktor für das visuelle Erscheinungsbild der Pixel im Bild. |
| [getXOrigin()](#getXOrigin--) | Gibt die absolute horizontale Koordinate der linken unteren Bildkante zurück, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie). |
| [setXOrigin(int value)](#setXOrigin-int-) | Setzt die absolute horizontale Koordinate der linken unteren Bildkante, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie). |
| [getYOrigin()](#getYOrigin--) | Gibt die absolute vertikale Koordinate der linken unteren Bildkante zurück, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie). |
| [setYOrigin(int value)](#setYOrigin-int-) | Setzt die absolute vertikale Koordinate der linken unteren Bildkante, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie). |
| [getImageId()](#getImageId--) | Gibt die eindeutige Kennung des Bildes zurück. |
| [setImageId(String value)](#setImageId-java.lang.String-) | Setzt die eindeutige Kennung des Bildes. |
| [getAuthorComments()](#getAuthorComments--) | Liest die vom Autor des Bildes bereitgestellten Kommentare aus oder legt sie fest. |
| [setAuthorComments(String value)](#setAuthorComments-java.lang.String-) | Liest die vom Autor des Bildes bereitgestellten Kommentare aus oder legt sie fest. |
| [getAuthorName()](#getAuthorName--) | Liest oder setzt den Namen des Autors, der dem Bild zugeordnet ist. |
| [setAuthorName(String value)](#setAuthorName-java.lang.String-) | Liest oder setzt den Namen des Autors, der dem Bild zugeordnet ist. |
| [getDateTimeStamp()](#getDateTimeStamp--) | Liest das Datum/Uhrzeit‑Stempel. |
| [setDateTimeStamp(Date value)](#setDateTimeStamp-java.util.Date-) | Setzt das Datum/Uhrzeit‑Stempel. |
| [getJobNameOrId()](#getJobNameOrId--) | Liest oder setzt den Jobnamen oder die ID, die dem Bild zugeordnet ist. |
| [setJobNameOrId(String value)](#setJobNameOrId-java.lang.String-) | Liest oder setzt den Jobnamen oder die ID, die dem Bild zugeordnet ist. |
| [getJobTime()](#getJobTime--) | Liest oder setzt den Zeitstempel, der die Jobzeit des Bildes angibt. |
| [setJobTime(Date value)](#setJobTime-java.util.Date-) | Liest oder setzt den Zeitstempel, der die Jobzeit des Bildes angibt. |
| [getTransparentColor()](#getTransparentColor--) | Liest oder setzt die Schlüssel­farbe, die dem Bild zugeordnet ist. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Liest oder setzt die Schlüssel­farbe, die dem Bild zugeordnet ist. |
| [hasTransparentColor()](#hasTransparentColor--) | Liest oder setzt einen booleschen Wert, der angibt, ob das Bild eine transparente Farbe enthält. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Liest oder setzt einen booleschen Wert, der angibt, ob das Bild eine transparente Farbe enthält. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest oder setzt die Hintergrundfarbe des Bildes. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Liest oder setzt die Hintergrundfarbe des Bildes. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe enthält. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Liest oder setzt einen Wert, der angibt, ob das Bild eine Hintergrundfarbe enthält. |
| [getSoftwareVersion()](#getSoftwareVersion--) | Liest oder setzt die Softwareversion, die dem Bild zugeordnet ist. |
| [setSoftwareVersion(String value)](#setSoftwareVersion-java.lang.String-) | Liest oder setzt die Softwareversion, die dem Bild zugeordnet ist. |
| [getSoftwareVersionLetter()](#getSoftwareVersionLetter--) | Liest oder setzt den Buchstaben‑Teil der Softwareversion, die dem Bild zugeordnet ist. |
| [setSoftwareVersionLetter(char value)](#setSoftwareVersionLetter-char-) | Liest oder setzt den Buchstaben‑Teil der Softwareversion, die dem Bild zugeordnet ist. |
| [getSoftwareVersionNumber()](#getSoftwareVersionNumber--) | Liest oder setzt den numerischen Teil der Softwareversion, die dem Bild zugeordnet ist. |
| [setSoftwareVersionNumber(int value)](#setSoftwareVersionNumber-int-) | Liest oder setzt den numerischen Teil der Softwareversion, die dem Bild zugeordnet ist. |
| [getSoftwareId()](#getSoftwareId--) | Verwaltet die Softwareidentifikation (ID), die dem Bild zugeordnet ist, und erlaubt bis zu 40 ASCII‑Zeichen. |
| [setSoftwareId(String value)](#setSoftwareId-java.lang.String-) | Verwaltet die Softwareidentifikation (ID), die dem Bild zugeordnet ist, und erlaubt bis zu 40 ASCII‑Zeichen. |
| [op_Equality(TgaImage first, TgaImage second)](#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Führt einen Gleichheitsvergleich zwischen zwei TGA‑Bildern durch und berücksichtigt dabei sowohl das erste als auch das zweite Bild im Vergleichsprozess. |
| [op_Inequality(TgaImage first, TgaImage second)](#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-) | Führt einen Ungleichheitsvergleich zwischen zwei TGA‑Bildern durch und bewertet dabei sowohl das erste als auch das zweite Bild. |
| [deepClone()](#deepClone--) | Erstellt ein Duplikat der aktuellen Instanz und erzeugt ein neues Objekt, das alle Attribute und Eigenschaften des Originals klont. |
| [deepClone(TgaImage tgaImage)](#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-) | Repliziert die Eigenschaften eines anderen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Objekts und erstellt eine neue Instanz mit identischen Attributen. |
| [equals(TgaImage other)](#equals-com.aspose.imaging.fileformats.tga.TgaImage-) | Bei einem Gleichheitsvergleich prüft die Methode, ob die aktuelle [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz gleich dem als Parameter übergebenen zweiten Bild ist. |
| [equals(Object other)](#equals-java.lang.Object-) | Die Methode führt einen Gleichheitsvergleich zwischen der aktuellen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz und einem als Parameter übergebenen anderen Objekt durch. |
| [rotateFlip(int rotateFlipType)](#rotateFlip-int-) | Die Methode "rotateFlip" ermöglicht Dreh‑ und Spiegelungsoperationen am Bild. |
| [hashCode()](#hashCode--) | Liest den Hash‑Code der aktuellen Instanz. |
| [crop(Rectangle rectangle)](#crop-com.aspose.imaging.Rectangle-) | Schneidet das Bild auf einen angegebenen Bereich zu. |
| [crop(int leftShift, int rightShift, int topShift, int bottomShift)](#crop-int-int-int-int-) | Schneidet das Bild zu, indem Verschiebungen für die linken, rechten, oberen und unteren Grenzen angegeben werden. |
| [resize(int newWidth, int newHeight, ImageResizeSettings settings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Skaliert das Bild, wobei spezifische Einstellungen angewendet werden, um die gewünschten Abmessungen und das Seitenverhältnis beizubehalten. |
| [resize(int newWidth, int newHeight, int resizeType)](#resize-int-int-int-) | Passt die Größe des Bildes mit einem angegebenen Skalierungstyp an, der bestimmt, wie der Skalierungsvorgang durchgeführt wird. |
| [rotate(float angle, boolean resizeProportionally, Color backgroundColor)](#rotate-float-boolean-com.aspose.imaging.Color-) | Dreht das Bild um sein Zentrum herum um einen angegebenen Winkel, wobei die Proportionalität der Größenänderung beibehalten und die Hintergrundfarbe erhalten bleibt. |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```


## Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```


## Example: Getting values of the public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    Date dateTimeStamp = image.getDateTimeStamp();
    String authorName = image.getAuthorName();
    String authorComments = image.getAuthorComments();
    String imageId = image.getImageId();
    String jobNameOrId = image.getJobNameOrId();
    Date jobTime = image.getJobTime();
    Color keyColor = image.getTransparentColor();
    String softwareId = image.getSoftwareId();
    String softwareVersion = image.getSoftwareVersion();
    char softwareVersionLetter = image.getSoftwareVersionLetter();
    int softwareVersionNumber = image.getSoftwareVersionNumber();
    int xOrigin = image.getXOrigin();
    int yOrigin = image.getYOrigin();
    int gammaValueDenominator = image.getGammaValueDenominator();
    int gammaValueNumerator = image.getGammaValueNumerator();
    boolean hasAlphaChannel = image.hasAlpha();
    boolean hasColorMap = image.hasColorMap();
    int height = image.getHeight();
    boolean isGrayScale = image.isGrayScale();
    int pixelAspectRatioDenominator = image.getPixelAspectRatioDenominator();
    int pixelAspectRatioNumerator = image.getPixelAspectRatioNumerator();
    Size size = image.getSize();
    int width = image.getWidth();
}
```


## Example: Updating public properties of the loaded TGA image.

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### TgaImage(String path) {#TgaImage-java.lang.String-}
```
public TgaImage(String path)
```


Initialisiert ein neues [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Objekt mithilfe des angegebenen Dateipfads zum Laden des Bildinhalts. Dieser Konstruktor initialisiert die Bildinstanz effizient, ermöglicht nahtlosen Zugriff auf TGA-Bilddateien und vereinfacht die Integration in Ihren Anwendungsablauf.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Pfad | java.lang.String | Der Pfad zum Laden eines Bildes. |

### TgaImage(RasterImage rasterImage) {#TgaImage-com.aspose.imaging.RasterImage-}
```
public TgaImage(RasterImage rasterImage)
```


Erstellen Sie eine neue Instanz der Klasse [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), indem Sie ein Rasterbild-Objekt bereitstellen. Dieser Konstruktor erleichtert die direkte Integration vorhandener Rasterbilder in das TGA-Bildformat und optimiert den Konvertierungsprozess für eine verbesserte Kompatibilität in Ihren Softwaresystemen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Das Rasterbild. |


**Example: Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image.**

``` java
try (RasterImage image = (RasterImage)Image.load("test.png"))
{
    try (TgaImage tgaImage = new TgaImage(image))
    {
        tgaImage.save("test.tga");
    }
}
```

### TgaImage(InputStream stream) {#TgaImage-java.io.InputStream-}
```
public TgaImage(InputStream stream)
```


Initialisieren Sie eine neue Instanz der Klasse [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) mithilfe eines Streams zum Laden des Bildes. Dieser Konstruktor ermöglicht die nahtlose Integration von Bilddaten aus Streams und erleichtert die effiziente Handhabung und Verarbeitung von TGA-Bildern in Ihren Softwareanwendungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Stream | java.io.InputStream | Der Stream zum Laden eines Bildes. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Rufen Sie den Bits‑pro‑Pixel‑Wert ab, der wesentliche Informationen über die Farbtiefe des Bildes liefert. Diese Eigenschaft dient als wichtiges Maß zur Verständnis des Detailgrades und der Farbreichtum des Bildes und unterstützt Entwickler dabei, Verarbeitungsalgorithmen und Ressourcenzuweisungen für eine effiziente Bildmanipulation und Rendering‑Aufgaben zu optimieren.

**Returns:**
int – Bits pro Pixel.
### getBytesPerPixel() {#getBytesPerPixel--}
```
public final int getBytesPerPixel()
```


Ermitteln Sie den Bytes‑pro‑Pixel‑Wert, der die vom einzelnen Pixel im Bild belegte Speichermenge angibt. Diese Eigenschaft dient als wichtiges Maß für Speicherverwaltung und Optimierung und unterstützt Entwickler dabei, Ressourcen effizient zuzuweisen und Bilddaten zu verarbeiten.

**Returns:**
int – Bytes pro Pixel.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Rufen Sie einen booleschen Wert ab, der angibt, ob das [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) einen Alphakanal enthält, um Transparenzeffekte zu ermöglichen. Diese Eigenschaft liefert wesentliche Informationen für die Handhabung von Bildkomposition und Rendering und unterstützt Entwickler bei der Implementierung verschiedener visueller Effekte und Kompositoperationen.

**Returns:**
boolean – ein Wert, der angibt, ob dieses [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) einen Alphakanal hat.
### isGrayScale() {#isGrayScale--}
```
public final boolean isGrayScale()
```


Erhalten Sie einen booleschen Wert, der angibt, ob das [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) ein Graustufenbild darstellt. Diese Eigenschaft ist entscheidend, um zwischen Farb- und Graustufenbildern zu unterscheiden, und unterstützt Entwickler bei der Anwendung geeigneter Verarbeitungs- und Rendering‑Techniken basierend auf den Farbattributen des Bildes.

**Returns:**
boolean – ein Wert, der angibt, ob dieses [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) ein Graustufenbild ist.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Rufen Sie die Breite des von dieser [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz dargestellten Bildes ab. Diese Eigenschaft liefert Entwicklern wesentliche Informationen über die Bildabmessungen und erleichtert verschiedene Bildmanipulations‑ und Verarbeitungsvorgänge in ihren Softwareanwendungen.

**Returns:**
int – diese Bildbreite in Pixeln.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Ermitteln Sie die Höhe des von dieser [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz gekapselten Bildes. Diese Eigenschaft liefert Entwicklern wichtige Details zu den vertikalen Abmessungen des Bildes und ermöglicht die nahtlose Integration und Manipulation von Bildern in ihren Softwarelösungen.

**Returns:**
int – diese Bildhöhe in Pixeln.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Erhalten Sie wichtige Informationen über das Dateiformat des Bildes, das durch diese Instanz von [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) dargestellt wird. Das Verständnis des Dateiformats ist entscheidend für Kompatibilitätsprüfungen und die Gewährleistung einer nahtlosen Integration in Softwaresysteme, wodurch eine effiziente Verarbeitung und Manipulation von Bildern ermöglicht wird.

**Returns:**
long – wichtige Informationen über das Dateiformat des Bildes, das durch diese Instanz von [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) dargestellt wird.
### hasColorMap() {#hasColorMap--}
```
public final boolean hasColorMap()
```


Ermitteln Sie, ob diese [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) Instanz eine Farbkarte enthält. Das Verständnis der Existenz einer Farbkarte ist entscheidend für die genaue Interpretation und Manipulation der Farbdaten des Bildes.

**Returns:**
boolean – ein Wert, der angibt, ob dieses Bild eine Farbkarte hat.
### getGammaValueNumerator() {#getGammaValueNumerator--}
```
public final int getGammaValueNumerator()
```


Ermittelt den Zählerteil des Gammawerts, der für eine genaue Farbdarstellung in Bildern entscheidend ist. Bei Bildern ohne Gamma-Korrektur sollte dieser Wert 1,0 betragen. Das Verständnis und die Nutzung dieses Wertes sind wichtig, um die Farbtreue zu erhalten und eine präzise Bilddarstellung sicherzustellen.

**Returns:**
int – der Zählerteil des Gammawerts, der für eine genaue Farbdarstellung in Bildern entscheidend ist.
### getGammaValueDenominator() {#getGammaValueDenominator--}
```
public final int getGammaValueDenominator()
```


Ermittelt den Nennerteil des Gammawerts, ein wesentlicher Faktor zur Bestimmung der Farbdarstellung in Bildern. Bei Bildern ohne Gamma-Korrektur sollte dieser Wert 1,0 betragen, um eine genaue Farbdarstellung zu gewährleisten. Das Verständnis und die Nutzung dieses Parameters sind grundlegend, um die Farbtreue zu wahren und eine präzise Bildvisualisierung zu erreichen.

**Returns:**
int
### getPixelAspectRatioNumerator() {#getPixelAspectRatioNumerator--}
```
public final int getPixelAspectRatioNumerator()
```


Ermittelt die Zählerkomponente des Pixel‑Seitenverhältnisses, die das visuelle Erscheinungsbild der Pixel im Bild beeinflusst. Das Verständnis und die Manipulation dieses Wertes sind entscheidend, um eine genaue Pixelrepräsentation und Seitenverhältnisse bei der Bilddarstellung und -verarbeitung zu erreichen.

**Returns:**
int
### getPixelAspectRatioDenominator() {#getPixelAspectRatioDenominator--}
```
public final int getPixelAspectRatioDenominator()
```


Ermittelt den Nennerteil des Pixel‑Seitenverhältnisses, ein entscheidender Faktor zur Bestimmung des visuellen Erscheinungsbildes der Pixel im Bild. Dieser Wert ist wichtig, um eine genaue Pixelrepräsentation und Seitenverhältnisse bei verschiedenen Bilddarstellungs- und Verarbeitungsoperationen zu erhalten und eine hochwertige visuelle Ausgabe sicherzustellen.

**Returns:**
int
### getXOrigin() {#getXOrigin--}
```
public final int getXOrigin()
```


Gibt die absolute horizontale Koordinate der linken unteren Bildkante zurück, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie).

**Returns:**
int – absolute horizontale Koordinate für die linke untere Ecke des Bildes, wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem Bildschirm liegt.
### setXOrigin(int value) {#setXOrigin-int-}
```
public final void setXOrigin(int value)
```


Setzt die absolute horizontale Koordinate der linken unteren Bildkante, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | absolute horizontale Koordinate für die linke untere Ecke des Bildes, wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem Bildschirm liegt. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getYOrigin() {#getYOrigin--}
```
public final int getYOrigin()
```


Gibt die absolute vertikale Koordinate der linken unteren Bildkante zurück, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie).

**Returns:**
int – absolute vertikale Koordinate für die linke untere Ecke des Bildes, wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem Bildschirm liegt.
### setYOrigin(int value) {#setYOrigin-int-}
```
public final void setYOrigin(int value)
```


Setzt die absolute vertikale Koordinate der linken unteren Bildkante, wie sie auf einem Anzeigegerät mit Ursprung in der linken unteren Bildschirmecke positioniert ist (z. B. die TARGA‑Serie).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | absolute vertikale Koordinate für die linke untere Ecke des Bildes, wie es auf einem Anzeigegerät positioniert ist, dessen Ursprung unten links auf dem Bildschirm liegt. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getImageId() {#getImageId--}
```
public final String getImageId()
```


Ermittelt die eindeutige Kennung, die dem Bild zugeordnet ist. Diese ID dient als Referenzpunkt, um das Bild innerhalb eines Systems oder einer Anwendung zu identifizieren und von anderen zu unterscheiden. Durch das Festlegen oder Abrufen der Image-ID können Sie Bilder effektiv verwalten und verfolgen, was organisierte Bildverwaltung und -abrufprozesse ermöglicht.

Dieses optionale Feld enthält Identifizierungsinformationen über das Bild. Die maximale Länge dieses Feldes beträgt 255 Bytes.

**Returns:**
java.lang.String – die eindeutige Kennung, die dem Bild zugeordnet ist.
### setImageId(String value) {#setImageId-java.lang.String-}
```
public final void setImageId(String value)
```


Legt die eindeutige Kennung fest, die dem Bild zugeordnet ist. Diese ID dient als Referenzpunkt, um das Bild innerhalb eines Systems oder einer Anwendung zu identifizieren und von anderen zu unterscheiden. Durch das Festlegen oder Abrufen der Image-ID können Sie Bilder effektiv verwalten und verfolgen, was organisierte Bildverwaltung und -abrufprozesse ermöglicht.

Dieses optionale Feld enthält Identifizierungsinformationen über das Bild. Die maximale Länge dieses Feldes beträgt 255 Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | die eindeutige Kennung, die dem Bild zugeordnet ist. |

### getAuthorComments() {#getAuthorComments--}
```
public final String getAuthorComments()
```


Ermittelt oder setzt die vom Autor des Bildes bereitgestellten Kommentare. Diese Kommentare enthalten oft wertvolle Informationen, wie Beschreibungen, Anmerkungen oder zusätzlichen Kontext zum Bild. Durch den Zugriff auf oder die Änderung der Eigenschaft Author Comments können Entwickler die Metadaten des Bildes erweitern und den Benutzern wertvolle Einblicke und Kontext zu Inhalt oder Entstehung bieten. Dies ist ein ASCII-Feld mit 324 Bytes, das in vier Zeilen zu je 80 Zeichen organisiert ist, jeweils gefolgt von einem Nullterminator.

**Returns:**
java.lang.String
### setAuthorComments(String value) {#setAuthorComments-java.lang.String-}
```
public final void setAuthorComments(String value)
```


Ermittelt oder setzt die vom Autor des Bildes bereitgestellten Kommentare. Diese Kommentare enthalten oft wertvolle Informationen, wie Beschreibungen, Anmerkungen oder zusätzlichen Kontext zum Bild. Durch den Zugriff auf oder die Änderung der Eigenschaft Author Comments können Entwickler die Metadaten des Bildes erweitern und den Benutzern wertvolle Einblicke und Kontext zu Inhalt oder Entstehung bieten. Dies ist ein ASCII-Feld mit 324 Bytes, das in vier Zeilen zu je 80 Zeichen organisiert ist, jeweils gefolgt von einem Nullterminator.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String |  |

### getAuthorName() {#getAuthorName--}
```
public final String getAuthorName()
```


Ermittelt oder setzt den Namen des Autors, der dem Bild zugeordnet ist. Diese Eigenschaft ermöglicht Entwicklern den Zugriff auf oder die Änderung des Metadatums des Autorennamens und liefert wertvolle Informationen über den Ersteller des Bildes. Durch die Nutzung der Eigenschaft Author Name können Benutzer leicht die Person identifizieren, die das Bild erstellt oder beigetragen hat, wodurch die Metadaten insgesamt verbessert und den Betrachtern wertvoller Kontext geboten wird. Dieses Feld umfasst insgesamt 40 ASCII-Zeichen für den Namen. Wird das Feld verwendet, sollte es den Namen der Person enthalten, die das Bild (Autor) erstellt hat.

**Returns:**
java.lang.String
### setAuthorName(String value) {#setAuthorName-java.lang.String-}
```
public final void setAuthorName(String value)
```


Ermittelt oder setzt den Namen des Autors, der dem Bild zugeordnet ist. Diese Eigenschaft ermöglicht Entwicklern den Zugriff auf oder die Änderung des Metadatums des Autorennamens und liefert wertvolle Informationen über den Ersteller des Bildes. Durch die Nutzung der Eigenschaft Author Name können Benutzer leicht die Person identifizieren, die das Bild erstellt oder beigetragen hat, wodurch die Metadaten insgesamt verbessert und den Betrachtern wertvoller Kontext geboten wird. Dieses Feld umfasst insgesamt 40 ASCII-Zeichen für den Namen. Wird das Feld verwendet, sollte es den Namen der Person enthalten, die das Bild (Autor) erstellt hat.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Autorname. |

### getDateTimeStamp() {#getDateTimeStamp--}
```
public final Date getDateTimeStamp()
```


Ermittelt das Datum/Zeit-Stempel. Dieses Feld definiert den Wert für Datum und Uhrzeit, zu der das Bild gespeichert wurde. Obwohl Betriebssysteme Dateien normalerweise mit Datum und Uhrzeit versehen, wird diese Funktion bereitgestellt, weil das Betriebssystem den Zeit- und Datumsstempel ändern kann, wenn die Datei kopiert wird. Durch die Nutzung dieses Bereichs erhalten Sie einen unveränderten Abschnitt für die Aufzeichnung von Datum und Uhrzeit.

**Returns:**
java.util.Date – Datum/Zeit-Stempel.
### setDateTimeStamp(Date value) {#setDateTimeStamp-java.util.Date-}
```
public final void setDateTimeStamp(Date value)
```


Setzt Datum/Uhrzeit-Stempel. Dieses Feld definiert den Wert für Datum und Uhrzeit, zu dem das Bild gespeichert wurde. Obwohl Betriebssysteme Dateien normalerweise mit Datum- und Zeitstempel versehen, wird diese Funktion bereitgestellt, weil das Betriebssystem den Datum- und Zeitstempel ändern kann, wenn die Datei kopiert wird. Durch die Verwendung dieses Bereichs erhalten Sie einen unveränderten Abschnitt für die Aufzeichnung von Datum und Uhrzeit.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date | Datum/Uhrzeit-Stempel. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getJobNameOrId() {#getJobNameOrId--}
```
public final String getJobNameOrId()
```


Ruft den Jobnamen oder die ID ab oder legt sie fest, die dem Bild zugeordnet sind. Diese Eigenschaft ermöglicht den Zugriff auf Metadaten oder deren Änderung, die mit dem jeweiligen Job oder Projekt des Bildes verbunden sind. Durch die Nutzung der Job Name/ID‑Eigenschaft können Benutzer das Projekt oder die Aufgabe, zu der das Bild gehört, leicht identifizieren, was die Organisation und Verwaltung von Bildressourcen in größeren Arbeitsabläufen oder Projekten erleichtert.

**Returns:**
java.lang.String - Job Name/ID.
### setJobNameOrId(String value) {#setJobNameOrId-java.lang.String-}
```
public final void setJobNameOrId(String value)
```


Ruft den Jobnamen oder die ID ab oder legt sie fest, die dem Bild zugeordnet sind. Diese Eigenschaft ermöglicht den Zugriff auf Metadaten oder deren Änderung, die mit dem jeweiligen Job oder Projekt des Bildes verbunden sind. Durch die Nutzung der Job Name/ID‑Eigenschaft können Benutzer das Projekt oder die Aufgabe, zu der das Bild gehört, leicht identifizieren, was die Organisation und Verwaltung von Bildressourcen in größeren Arbeitsabläufen oder Projekten erleichtert.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Job Name/ID. |

### getJobTime() {#getJobTime--}
```
public final Date getJobTime()
```


Ruft den Zeitstempel ab oder legt ihn fest, der die Jobzeit des Bildes angibt. Diese Eigenschaft ermöglicht Entwicklern den Zugriff auf Zeit-Metadaten oder deren Änderung, die mit dem jeweiligen Job oder Projekt des Bildes verbunden sind.

**Returns:**
java.util.Date - Job Time.
### setJobTime(Date value) {#setJobTime-java.util.Date-}
```
public final void setJobTime(Date value)
```


Ruft den Zeitstempel ab oder legt ihn fest, der die Jobzeit des Bildes angibt. Diese Eigenschaft ermöglicht Entwicklern den Zugriff auf Zeit-Metadaten oder deren Änderung, die mit dem jeweiligen Job oder Projekt des Bildes verbunden sind.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.Date | Job Time. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Ruft die Key Color ab oder legt sie fest. Diese Eigenschaft ermöglicht den Zugriff auf die als Key Color für bestimmte Bildverarbeitungsaufgaben oder Effekte festgelegte Farbe oder deren Änderung. Die Nutzung der Key Color‑Eigenschaft ermöglicht es Benutzern, farbbasierte Operationen wie Chroma‑Keying oder Farb­ersetzung anzuwenden, wodurch die Bildmanipulations‑Fähigkeiten und kreative Möglichkeiten erweitert werden.

Die Key Color kann als \\u2018background color\\u2019 oder \\u2018transparent color\\u2019 betrachtet werden. Dies ist die Farbe des \\u2018non image\\u2019‑Bereichs des Bildschirms und dieselbe Farbe, zu der der Bildschirm gelöscht würde, wenn er in der Anwendung gelöscht wird.

**Returns:**
[Color](../../com.aspose.imaging/color) - Key Color.
### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Ruft die Key Color ab oder legt sie fest. Diese Eigenschaft ermöglicht den Zugriff auf die als Key Color für bestimmte Bildverarbeitungsaufgaben oder Effekte festgelegte Farbe oder deren Änderung. Die Nutzung der Key Color‑Eigenschaft ermöglicht es Benutzern, farbbasierte Operationen wie Chroma‑Keying oder Farb­ersetzung anzuwenden, wodurch die Bildmanipulations‑Fähigkeiten und kreative Möglichkeiten erweitert werden.

Die Key Color kann als \\u2018background color\\u2019 oder \\u2018transparent color\\u2019 betrachtet werden. Dies ist die Farbe des \\u2018non image\\u2019‑Bereichs des Bildschirms und dieselbe Farbe, zu der der Bildschirm gelöscht würde, wenn er in der Anwendung gelöscht wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | Key Color. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Bild eine transparente Farbe enthält. Diese Eigenschaft ist entscheidend, um zu erkennen, ob das Bild Transparenz unterstützt, und hilft Ihnen, geeignete Handhabungen von transparenzbezogenen Vorgängen wie Blending, Compositing oder Maskierung zu implementieren.

**Returns:**
boolean – ein Wert, der angibt, ob das Bild eine transparente Farbe hat.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Ruft einen booleschen Wert ab oder legt ihn fest, der angibt, ob das Bild eine transparente Farbe enthält. Diese Eigenschaft ist entscheidend, um zu erkennen, ob das Bild Transparenz unterstützt, und hilft Ihnen, geeignete Handhabungen von transparenzbezogenen Vorgängen wie Blending, Compositing oder Maskierung zu implementieren.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Bild eine transparente Farbe hat. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Ruft die Hintergrundfarbe des Bildes ab oder legt sie fest. Diese Eigenschaft ermöglicht die Angabe der für den Bildhintergrund zu verwendenden Farbe, sorgt für Konsistenz und verbessert die visuelle Darstellung. Sie ist besonders nützlich für Szenarien, in denen das Bild vor einem Hintergrund mit anderer Farbe angezeigt wird oder wenn das Bild auf eine andere Leinwand gerendert wird.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Ruft die Hintergrundfarbe des Bildes ab oder legt sie fest. Diese Eigenschaft ermöglicht die Angabe der für den Bildhintergrund zu verwendenden Farbe, sorgt für Konsistenz und verbessert die visuelle Darstellung. Sie ist besonders nützlich für Szenarien, in denen das Bild vor einem Hintergrund mit anderer Farbe angezeigt wird oder wenn das Bild auf eine andere Leinwand gerendert wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | die Hintergrundfarbe. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Bild eine Hintergrundfarbe enthält. Diese Eigenschaft ist nützlich, um zu bestimmen, ob das Bild eine von dem Vordergrundinhalt getrennte Hintergrundfarbe aufweist. Sie ermöglicht es, die Bildverarbeitung oder das Rendering basierend auf dem Vorhandensein oder Fehlen einer Hintergrundfarbe anzupassen.

**Returns:**
boolean – ein Wert, der angibt, ob das Bild eine Hintergrundfarbe hat.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Ruft einen Wert ab oder legt ihn fest, der angibt, ob das Bild eine Hintergrundfarbe enthält. Diese Eigenschaft ist nützlich, um zu bestimmen, ob das Bild eine von dem Vordergrundinhalt getrennte Hintergrundfarbe aufweist. Sie ermöglicht es, die Bildverarbeitung oder das Rendering basierend auf dem Vorhandensein oder Fehlen einer Hintergrundfarbe anzupassen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Bild eine Hintergrundfarbe hat. |

### getSoftwareVersion() {#getSoftwareVersion--}
```
public final String getSoftwareVersion()
```


Ruft die Softwareversion des Bildes ab oder legt sie fest. Die zulässige Länge für den Versionsstring beträgt typischerweise 3 bis 4 Zeichen. Diese Eigenschaft ist nützlich, um die Software zu verfolgen, die zum Erstellen oder Bearbeiten des Bildes verwendet wurde, und kann wertvollen Kontext für Bildverarbeitung und Kompatibilitätsprüfungen liefern.

**Returns:**
java.lang.String - Software Version.
### setSoftwareVersion(String value) {#setSoftwareVersion-java.lang.String-}
```
public final void setSoftwareVersion(String value)
```


Ruft die Softwareversion des Bildes ab oder legt sie fest. Die zulässige Länge für den Versionsstring beträgt typischerweise 3 bis 4 Zeichen. Diese Eigenschaft ist nützlich, um die Software zu verfolgen, die zum Erstellen oder Bearbeiten des Bildes verwendet wurde, und kann wertvollen Kontext für Bildverarbeitung und Kompatibilitätsprüfungen liefern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Software Version. |

### getSoftwareVersionLetter() {#getSoftwareVersionLetter--}
```
public final char getSoftwareVersionLetter()
```


Ruft den Buchstabenanteil der Softwareversion des Bildes ab oder legt ihn fest. Diese Eigenschaft stellt ein zusätzliches Detail innerhalb des Versionsstrings dar und kann für eine feinere Versionsdifferenzierung nützlich sein.

**Returns:**
char - Buchstabenanteil der Software-Version.
### setSoftwareVersionLetter(char value) {#setSoftwareVersionLetter-char-}
```
public final void setSoftwareVersionLetter(char value)
```


Ruft den Buchstabenanteil der Softwareversion des Bildes ab oder legt ihn fest. Diese Eigenschaft stellt ein zusätzliches Detail innerhalb des Versionsstrings dar und kann für eine feinere Versionsdifferenzierung nützlich sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | char | Buchstabenanteil der Software-Version. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareVersionNumber() {#getSoftwareVersionNumber--}
```
public final int getSoftwareVersionNumber()
```


Ruft den numerischen Bestandteil der Software-Version ab oder setzt ihn. Diese Eigenschaft stellt den numerischen Teil der Software-Versionszeichenkette dar und liefert wichtige Informationen über die Version der Software, die zum Erstellen oder Ändern des Bildes verwendet wurde.

**Returns:**
int - Numerischer Teil der Software-Version.
### setSoftwareVersionNumber(int value) {#setSoftwareVersionNumber-int-}
```
public final void setSoftwareVersionNumber(int value)
```


Ruft den numerischen Bestandteil der Software-Version ab oder setzt ihn. Diese Eigenschaft stellt den numerischen Teil der Software-Versionszeichenkette dar und liefert wichtige Informationen über die Version der Software, die zum Erstellen oder Ändern des Bildes verwendet wurde.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | Numerischer Teil der Software-Version. |


**Example: Updating public properties of the loaded TGA image.**

``` java
try (TgaImage image = (TgaImage)Image.load("test.tga"))
{
    image.setDateTimeStamp(new Date());
    image.setAuthorName("John Smith");
    image.setAuthorComments("Comment");
    image.setImageId("ImageId");
    image.setJobNameOrId("Important Job");
    image.setJobTime(new Date(0,0, 10));
    image.setTransparentColor(Color.fromArgb(123));
    image.setSoftwareId("SoftwareId");
    image.setSoftwareVersion("abc1");
    image.setSoftwareVersionLetter('a');
    image.setSoftwareVersionNumber(2);
    image.setXOrigin(1000);
    image.setYOrigin(1000);

    image.save("test.tga");
}
```

### getSoftwareId() {#getSoftwareId--}
```
public final String getSoftwareId()
```


Verwaltet die Softwareidentifikation (ID), die dem Bild zugeordnet ist, und erlaubt bis zu 40 ASCII‑Zeichen. Diese Eigenschaft dient dazu, die verwendete Software eindeutig zu identifizieren, die beim Erstellen oder Verarbeiten des Bildes eingesetzt wurde, und liefert wertvolle Metadaten für organisatorische und informationsbezogene Zwecke.

**Returns:**
java.lang.String - Software‑ID.
### setSoftwareId(String value) {#setSoftwareId-java.lang.String-}
```
public final void setSoftwareId(String value)
```


Verwaltet die Softwareidentifikation (ID), die dem Bild zugeordnet ist, und erlaubt bis zu 40 ASCII‑Zeichen. Diese Eigenschaft dient dazu, die verwendete Software eindeutig zu identifizieren, die beim Erstellen oder Verarbeiten des Bildes eingesetzt wurde, und liefert wertvolle Metadaten für organisatorische und informationsbezogene Zwecke.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.lang.String | Software‑ID. |

### op_Equality(TgaImage first, TgaImage second) {#op-Equality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Equality(TgaImage first, TgaImage second)
```


Führt einen Gleichheitsvergleich zwischen zwei TGA‑Bildern durch und berücksichtigt dabei sowohl das erste als auch das zweite Bild, das am Vergleich beteiligt ist. Diese Methode erleichtert die unkomplizierte Bewertung der Bildgleichheit und sorgt für genaue Analysen und Entscheidungen innerhalb von Bildverarbeitungs‑Workflows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Erstes [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Zweites [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |

**Returns:**
boolean - Vergleichsergebnisse.
### op_Inequality(TgaImage first, TgaImage second) {#op-Inequality-com.aspose.imaging.fileformats.tga.TgaImage-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public static boolean op_Inequality(TgaImage first, TgaImage second)
```


Führt einen Ungleichheitsvergleich zwischen zwei TGA‑Bildern durch und bewertet dabei sowohl das erste als auch das zweite Bild, das am Vergleich beteiligt ist. Diese Methode hilft, Diskrepanzen oder Unterschiede zwischen Bildern zu identifizieren und ermöglicht eine präzise Analyse und Entscheidungsfindung bei Bildverarbeitungsaufgaben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| first | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Erstes [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |
| second | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Zweites [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |

**Returns:**
boolean - Vergleichsergebnisse.
### deepClone() {#deepClone--}
```
public final TgaImage deepClone()
```


Erstellt ein Duplikat der aktuellen Instanz, indem ein neues Objekt erzeugt wird, das alle Attribute und Eigenschaften des Originals klont. Diese Methode erleichtert die Erstellung identischer Kopien, gewährleistet Datenintegrität und bewahrt den Zustand der aktuellen Instanz, ohne das Originalobjekt zu beeinflussen.

**Returns:**
[TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) - Returns a new object that is a copy of the current instance.
### deepClone(TgaImage tgaImage) {#deepClone-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final void deepClone(TgaImage tgaImage)
```


Repliziert die Eigenschaften eines anderen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Objekts und erstellt eine neue Instanz mit identischen Attributen. Dieser Vorgang stellt die Wahrung der Datenintegrität sicher und erleichtert die Duplizierung von Bildeigenschaften, ohne das Quellobjekt zu verändern.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| tgaImage | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Anderes [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) |

### equals(TgaImage other) {#equals-com.aspose.imaging.fileformats.tga.TgaImage-}
```
public final boolean equals(TgaImage other)
```


Bei einem Gleichheitsvergleich prüft die Methode, ob die aktuelle [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz gleich dem als Parameter übergebenen zweiten Bild ist. Dieser Vorgang erleichtert die Bestimmung, ob zwei TGA‑Bilder identisch sind, und unterstützt Bildverarbeitungs‑ und Vergleichsaufgaben.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage) | Zweites [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |

**Returns:**
boolean - Vergleichsergebnisse.
### equals(Object other) {#equals-java.lang.Object-}
```
public boolean equals(Object other)
```


Die Methode führt einen Gleichheitsvergleich zwischen der aktuellen [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage)-Instanz und einem anderen als Parameter übergebenen Objekt durch. Insbesondere prüft sie, ob die Eigenschaften des aktuellen Bildes mit denen des zweiten Objekts übereinstimmen, und unterstützt die Bestimmung ihrer Gleichwertigkeit für Vergleichszwecke innerhalb von Bildverarbeitungs‑Workflows.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| other | java.lang.Object | Zweites [TgaImage](../../com.aspose.imaging.fileformats.tga/tgaimage), das am Vergleich teilnimmt. |

**Returns:**
boolean - Vergleichsergebnisse.
### rotateFlip(int rotateFlipType) {#rotateFlip-int-}
```
public void rotateFlip(int rotateFlipType)
```


Die Methode "rotateFlip" ermöglicht Dreh‑ und Spiegelvorgänge am Bild. Sie bietet vielseitige Funktionen zur Manipulation der Bildorientierung, sodass Benutzer Rotationen und Spiegelungen nach Bedarf durchführen können, was effiziente Bildverarbeitungsaufgaben in Softwareanwendungen unterstützt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rotateFlipType | int | Der Dreh‑/Spiegeltyp. |

### hashCode() {#hashCode--}
```
public int hashCode()
```


Ruft den Hashcode der aktuellen Instanz ab. Es ist jedoch zu beachten, dass dieser Hashcode möglicherweise nicht als Schlüssel geeignet ist, insbesondere weil Instanzen der Klasse TgaImage nicht unveränderlich sind.

**Returns:**
int - Hashcode dieser Instanz.
### crop(Rectangle rectangle) {#crop-com.aspose.imaging.Rectangle-}
```
public void crop(Rectangle rectangle)
```


Beschneidet das Bild auf einen angegebenen Bereich. Diese Methode ermöglicht es, einen rechteckigen Bereich im Bild zu definieren, der erhalten bleiben soll, während der Rest verworfen wird. Dieser Vorgang ist nützlich, um sich auf bestimmte Inhalte im Bild zu konzentrieren oder unerwünschte Teile zu entfernen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.imaging/rectangle) | Das Rechteck. |

### crop(int leftShift, int rightShift, int topShift, int bottomShift) {#crop-int-int-int-int-}
```
public void crop(int leftShift, int rightShift, int topShift, int bottomShift)
```


Beschneiden Sie das Bild, indem Sie Verschiebungen für die linken, rechten, oberen und unteren Begrenzungen angeben. Diese Methode ermöglicht es Ihnen, das Bild zu trimmen, indem Sie seine Begrenzungen unabhängig entlang der horizontalen und vertikalen Achsen verschieben. Durch Anpassen dieser Verschiebungen können Sie präzise steuern, welche Bildbereiche beibehalten werden sollen, und das Bild effektiv auf die gewünschten Abmessungen zuschneiden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| leftShift | int | Die linke Verschiebung. |
| rightShift | int | Die rechte Verschiebung. |
| topShift | int | Die obere Verschiebung. |
| bottomShift | int | Die untere Verschiebung. |

### resize(int newWidth, int newHeight, ImageResizeSettings settings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings settings)
```


Skalieren Sie das Bild, während Sie spezifische Einstellungen anwenden, um die gewünschten Abmessungen und das Seitenverhältnis beizubehalten. Durch Anpassen der Bildeinstellungen können Sie das Bild effektiv skalieren und dabei optimale visuelle Qualität sowie Kompatibilität mit verschiedenen Anzeigegeräten oder Anwendungen sicherstellen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| newWidth | int | Die neue Breite. |
| newHeight | int | Die neue Höhe. |
| settings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Die Skalierungseinstellungen. |

### resize(int newWidth, int newHeight, int resizeType) {#resize-int-int-int-}
```
public void resize(int newWidth, int newHeight, int resizeType)
```


Passt die Größe des Bildes mithilfe eines angegebenen Skalierungstyps an, der bestimmt, wie der Skalierungsvorgang durchgeführt wird. Diese Methode bietet Flexibilität beim Skalieren von Bildern nach verschiedenen Algorithmen oder Techniken. Durch die Auswahl des geeigneten Skalierungstyps können Sie das gewünschte Gleichgewicht zwischen Bildqualität und Rechenaufwand basierend auf spezifischen Anforderungen oder Vorlieben erreichen.

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


Dreht das Bild um sein Zentrum um einen angegebenen Winkel, wobei die Skalierungsproportionalität beibehalten und die Hintergrundfarbe erhalten bleibt. Diese Methode ermöglicht eine präzise Bildmanipulation und sorgt dafür, dass die Drehung das visuelle Gleichgewicht und die Konsistenz mit der angegebenen Hintergrundfarbe wahrt. Sie ist ideal für Aufgaben, bei denen eine genaue Drehung um das Zentrum erforderlich ist, wie z. B. die Korrektur der Ausrichtung oder künstlerische Anpassungen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| angle | float | Der Rotationswinkel in Grad. Positive Werte drehen im Uhrzeigersinn. |
| resizeProportionally | boolean | Wenn auf `true` gesetzt, wird die Bildgröße gemäß den Projektionen des gedrehten Rechtecks (Eckpunkte) geändert; andernfalls bleiben die Abmessungen unverändert und nur die `` Bildinhalte werden rotiert. |
| backgroundColor | [Color](../../com.aspose.imaging/color) | Farbe des Hintergrunds. |

