---
title: "SvgRasterizationOptions"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Die SVG-Rasterisierungsoptionen."
type: docs
weight: 46
url: /de/java/com.aspose.imaging.imageoptions/svgrasterizationoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imageoptions.VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions)
```
public class SvgRasterizationOptions extends VectorRasterizationOptions
```

Die SVG-Rasterisierungsoptionen.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [SvgRasterizationOptions()](#SvgRasterizationOptions--) | Initialisiert eine neue Instanz der `SvgRasterizationOptions` Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getScaleX()](#getScaleX--) | Liest oder setzt die Skalierung x. |
| [setScaleX(float value)](#setScaleX-float-) | Liest oder setzt die Skalierung x. |
| [getScaleY()](#getScaleY--) | Liest oder setzt die Skalierung y. |
| [setScaleY(float value)](#setScaleY-float-) | Liest oder setzt die Skalierung y. |
| [copyTo(VectorRasterizationOptions vectorRasterizationOptions)](#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-) | Kopiert diese Instanz nach `vectorRasterizationOptions`. |
### SvgRasterizationOptions() {#SvgRasterizationOptions--}
```
public SvgRasterizationOptions()
```


Initialisiert eine neue Instanz der `SvgRasterizationOptions` Klasse.

### getScaleX() {#getScaleX--}
```
public float getScaleX()
```


Liest oder setzt die Skalierung x.

**Returns:**
float - Die Skalierung x.
### setScaleX(float value) {#setScaleX-float-}
```
public void setScaleX(float value)
```


Liest oder setzt die Skalierung x.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Skalierung x. |


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

### getScaleY() {#getScaleY--}
```
public float getScaleY()
```


Liest oder setzt die Skalierung y.

**Returns:**
float - Die Skalierung y.
### setScaleY(float value) {#setScaleY-float-}
```
public void setScaleY(float value)
```


Liest oder setzt die Skalierung y.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float | Die Skalierung y. |


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

### copyTo(VectorRasterizationOptions vectorRasterizationOptions) {#copyTo-com.aspose.imaging.imageoptions.VectorRasterizationOptions-}
```
public void copyTo(VectorRasterizationOptions vectorRasterizationOptions)
```


Kopiert diese Instanz nach `vectorRasterizationOptions`.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| vectorRasterizationOptions | [VectorRasterizationOptions](../../com.aspose.imaging.imageoptions/vectorrasterizationoptions) | Die Vektor-Rasterisierungsoptionen. |

