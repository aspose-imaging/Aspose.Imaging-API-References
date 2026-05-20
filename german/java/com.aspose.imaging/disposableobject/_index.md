---
title: "DisposableObject"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt ein verwertbares Objekt dar."
type: docs
weight: 40
url: /de/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Stellt ein verwertbares Objekt dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getDisposed()](#getDisposed--) | Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde. |
| [close()](#close--) | Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. |
| [dispose()](#dispose--) | Gibt die aktuelle Instanz frei. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Gibt einen Wert zurück, der angibt, ob diese Instanz freigegeben wurde.

**Returns:**
boolean – `true`, wenn freigegeben; andernfalls `false`.
### close() {#close--}
```
public void close()
```


Implementiert das Closable-Interface und kann seit JDK 1.7 in der try-with-resources-Anweisung verwendet werden. Diese Methode ruft einfach die Dispose-Methode auf.

### dispose() {#dispose--}
```
public void dispose()
```


Gibt die aktuelle Instanz frei.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Dies ist Font und Brush zum Zeichnen von Text auf einzelnen Frames.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Erstelle 5 Frames
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Erstelle ein PNG-Bild und zeichne die Seitenzahl darauf.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Erstelle einen Frame basierend auf dem PNG-Bild.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Füge den Frame zum TIFF-Bild hinzu.
        tiffImage.addFrame(frame);
    }

    // Das Bild wurde mit einem einzigen Standard-Frame erstellt. Entfernen wir ihn.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Vergiss nicht, den Frame freizugeben, wenn du ihn nicht zu einem anderen TiffImage hinzufügst.
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

