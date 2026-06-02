---
title: "VectorRasterizationOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die Vektor-Rasterisierungsoptionen."
type: docs
weight: 52
url: /de/java/com.aspose.imaging.imageoptions/vectorrasterizationoptions/
---
**Inheritance:**
java.lang.Object
```
public class VectorRasterizationOptions
```

Die Vektor-Rasterisierungsoptionen. Bitte beachten Sie, dass [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) seit der Version Aspose.Imaging 24.12 nicht mehr von [ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) abgeleitet wird.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [VectorRasterizationOptions()](#VectorRasterizationOptions--) |  |
| [VectorRasterizationOptions(VectorRasterizationOptions imageOptions)](#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSmoothingMode()](#getSmoothingMode--) | Gibt den Glättungsmodus zurück. |
| [setSmoothingMode(int value)](#setSmoothingMode-int-) | Legt den Glättungsmodus fest. |
| [getBorderX()](#getBorderX--) | Gibt den Rand X zurück oder legt ihn fest. |
| [setBorderX(float value)](#setBorderX-float-) | Gibt den Rand X zurück oder legt ihn fest. |
| [getBorderY()](#getBorderY--) | Gibt den Rand Y zurück oder legt ihn fest. |
| [setBorderY(float value)](#setBorderY-float-) | Gibt den Rand Y zurück oder legt ihn fest. |
| [getCenterDrawing()](#getCenterDrawing--) | Gibt einen Wert zurück, der angibt, ob zentriertes Zeichnen aktiviert ist. |
| [setCenterDrawing(boolean value)](#setCenterDrawing-boolean-) | Setzt einen Wert, der angibt, ob zentriertes Zeichnen. |
| [getPageHeight()](#getPageHeight--) | Liest die Seitenhöhe. |
| [setPageHeight(float value)](#setPageHeight-float-) | Setzt die Seitenhöhe. |
| [getPageSize()](#getPageSize--) | Liest die Seitengröße. |
| [setPageSize(SizeF value)](#setPageSize-com.aspose.imaging.SizeF-) | Setzt die Seitengröße. |
| [getPageWidth()](#getPageWidth--) | Liest die Seitenbreite. |
| [setPageWidth(float value)](#setPageWidth-float-) | Setzt die Seitenbreite. |
| [getBackgroundColor()](#getBackgroundColor--) | Liest eine Hintergrundfarbe. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Setzt eine Hintergrundfarbe. |
| [getDrawColor()](#getDrawColor--) | Liest eine Vordergrundfarbe. |
| [setDrawColor(Color value)](#setDrawColor-com.aspose.imaging.Color-) | Setzt eine Vordergrundfarbe. |
| [getTextRenderingHint()](#getTextRenderingHint--) | Liest den Textdarstellungs-Hinweis. |
| [setTextRenderingHint(int value)](#setTextRenderingHint-int-) | Setzt den Textdarstellungs-Hinweis. |
| [getPositioning()](#getPositioning--) | Liest die Positionierung. |
| [setPositioning(int value)](#setPositioning-int-) | Setzt die Positionierung. |
| [getReplaceTextMapping()](#getReplaceTextMapping--) | Liest die Text-Ersetzungszuordnung. |
| [setReplaceTextMapping(HashMap<String,String> value)](#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--) | Setzt die Text-Ersetzungszuordnung. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopiert diese Instanz nach `vectorRasterizationOptions`. |
| [deepClone()](#deepClone--) | Erstellt einen flachen Klon des Objekts. |
### VectorRasterizationOptions() {#VectorRasterizationOptions--}
```
public VectorRasterizationOptions()
```


### VectorRasterizationOptions(VectorRasterizationOptions imageOptions) {#VectorRasterizationOptions-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public VectorRasterizationOptions(VectorRasterizationOptions imageOptions)
```


**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| imageOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) |  |

### getSmoothingMode() {#getSmoothingMode--}
```
public final int getSmoothingMode()
```


Gibt den Glättungsmodus zurück.

**Returns:**
int - der Glättungsmodus.
### setSmoothingMode(int value) {#setSmoothingMode-int-}
```
public final void setSmoothingMode(int value)
```


Legt den Glättungsmodus fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Glättungsmodus. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, ein Bild zu laden.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Um SVG zu rasterisieren, müssen wir Rasterisierungsoptionen angeben.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Legt die Standardfarbe des Hintergrunds für ein Bild fest. Der Standardwert ist weiß.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Legt die Seitengröße fest
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing wird auf Linien und Kurven sowie die Kanten gefüllter Flächen angewendet.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap ohne Hinting gezeichnet.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduziert die Bildgröße um das 10-fache, d.h. die Ausgabengröße beträgt 10% der Originalgröße.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // In einer PNG-Datei speichern
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getBorderX() {#getBorderX--}
```
public float getBorderX()
```


Gibt den Rand X zurück oder legt ihn fest.

**Returns:**
float - Der Rand X.
### setBorderX(float value) {#setBorderX-float-}
```
public void setBorderX(float value)
```


Gibt den Rand X zurück oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Rand X. |

### getBorderY() {#getBorderY--}
```
public float getBorderY()
```


Gibt den Rand Y zurück oder legt ihn fest.

**Returns:**
float - Der Rand Y.
### setBorderY(float value) {#setBorderY-float-}
```
public void setBorderY(float value)
```


Gibt den Rand Y zurück oder legt ihn fest.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Der Rand Y. |

### getCenterDrawing() {#getCenterDrawing--}
```
public boolean getCenterDrawing()
```


Gibt einen Wert zurück, der angibt, ob zentriertes Zeichnen aktiviert ist.

**Returns:**
boolean - ein Wert, der angibt, ob zentriertes Zeichnen erfolgt.
### setCenterDrawing(boolean value) {#setCenterDrawing-boolean-}
```
public void setCenterDrawing(boolean value)
```


Setzt einen Wert, der angibt, ob zentriertes Zeichnen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | boolean | ein Wert, der angibt, ob das Zeichnen zentriert ist. |

### getPageHeight() {#getPageHeight--}
```
public float getPageHeight()
```


Liest die Seitenhöhe.

**Returns:**
float - die Seitenhöhe.
### setPageHeight(float value) {#setPageHeight-float-}
```
public void setPageHeight(float value)
```


Setzt die Seitenhöhe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | die Seitenhöhe. |

### getPageSize() {#getPageSize--}
```
public SizeF getPageSize()
```


Liest die Seitengröße.

**Returns:**
[SizeF](../../com.aspose.imaging/sizef) - the page size.
### setPageSize(SizeF value) {#setPageSize-com.aspose.imaging.SizeF-}
```
public void setPageSize(SizeF value)
```


Setzt die Seitengröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [SizeF](../../com.aspose.imaging/sizef) | die Seitengröße. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

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


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

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

### getPageWidth() {#getPageWidth--}
```
public float getPageWidth()
```


Liest die Seitenbreite.

**Returns:**
float - die Seitenbreite.
### setPageWidth(float value) {#setPageWidth-float-}
```
public void setPageWidth(float value)
```


Setzt die Seitenbreite.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | die Seitenbreite. |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Liest eine Hintergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - a background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Setzt eine Hintergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | eine Hintergrundfarbe. |


**Example: This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions.**

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


**Example: This example shows how to load a EMF image from a file and convert it to SVG using EmfRasterizationOptions.**

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

### getDrawColor() {#getDrawColor--}
```
public Color getDrawColor()
```


Liest eine Vordergrundfarbe.

**Returns:**
[Color](../../com.aspose.imaging/color) - a foreground color.
### setDrawColor(Color value) {#setDrawColor-com.aspose.imaging.Color-}
```
public void setDrawColor(Color value)
```


Setzt eine Vordergrundfarbe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | eine Vordergrundfarbe. |

### getTextRenderingHint() {#getTextRenderingHint--}
```
public final int getTextRenderingHint()
```


Liest den Textdarstellungs-Hinweis.

Wert: Der Textdarstellungs‑Hinweis.

**Returns:**
int - der Textdarstellungshinweis.
### setTextRenderingHint(int value) {#setTextRenderingHint-int-}
```
public final void setTextRenderingHint(int value)
```


Setzt den Textdarstellungs-Hinweis.

Wert: Der Textdarstellungs‑Hinweis.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | der Textdarstellungshinweis. |


**Example: This example shows how to load an SVG image from a file and rasterize it to PNG using various options.**

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, ein Bild zu laden.
com.aspose.imaging.fileformats.svg.SvgImage svgImage = (com.aspose.imaging.fileformats.svg.SvgImage) com.aspose.imaging.Image.load(dir + "test.svg");
try {
    // Um SVG zu rasterisieren, müssen wir Rasterisierungsoptionen angeben.
    com.aspose.imaging.imageoptions.SvgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.SvgRasterizationOptions();

    // Legt die Standardfarbe des Hintergrunds für ein Bild fest. Der Standardwert ist weiß.
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getGray());

    // Legt die Seitengröße fest
    rasterizationOptions.setPageSize(new com.aspose.imaging.SizeF(svgImage.getWidth(), svgImage.getHeight()));

    // Antialiasing wird auf Linien und Kurven sowie die Kanten gefüllter Flächen angewendet.
    rasterizationOptions.setSmoothingMode(com.aspose.imaging.SmoothingMode.AntiAlias);

    // Jedes Zeichen wird mit seiner antialiasierten Glyphen‑Bitmap ohne Hinting gezeichnet.
    rasterizationOptions.setTextRenderingHint(com.aspose.imaging.TextRenderingHint.AntiAlias);

    // Reduziert die Bildgröße um das 10-fache, d.h. die Ausgabengröße beträgt 10% der Originalgröße.
    rasterizationOptions.setScaleX(0.1f);
    rasterizationOptions.setScaleY(0.1f);

    com.aspose.imaging.imageoptions.PngOptions saveOptions = new com.aspose.imaging.imageoptions.PngOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    // In einer PNG-Datei speichern
    svgImage.save(dir + "test.output.png", saveOptions);
} finally {
    svgImage.dispose();
}
```

### getPositioning() {#getPositioning--}
```
public final int getPositioning()
```


Liest die Positionierung.

Wert: Die Positionierung.

**Returns:**
int - die Positionierung.
### setPositioning(int value) {#setPositioning-int-}
```
public final void setPositioning(int value)
```


Setzt die Positionierung.

Wert: Die Positionierung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Positionierung. |

### getReplaceTextMapping() {#getReplaceTextMapping--}
```
public final HashMap<String,String> getReplaceTextMapping()
```


Liest die Text-Ersetzungszuordnung.

Wert: Die Text-Ersetzungszuordnung.

**Returns:**
java.util.HashMap<java.lang.String,java.lang.String> - die Text-Ersetzungszuordnung.
### setReplaceTextMapping(HashMap<String,String> value) {#setReplaceTextMapping-java.util.HashMap-java.lang.String-java.lang.String--}
```
public final void setReplaceTextMapping(HashMap<String,String> value)
```


Setzt die Text-Ersetzungszuordnung.

Wert: Die Text-Ersetzungszuordnung.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.HashMap<java.lang.String,java.lang.String> | die Text-Ersetzungszuordnung. |

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopiert diese Instanz nach `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Die Vektor-Rasterisierungsoptionen. |

### deepClone() {#deepClone--}
```
public VectorRasterizationOptions deepClone()
```


Erstellt einen flachen Klon des Objekts.

**Returns:**
[VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) - The shallow clone of object.
