---
title: "DisposableObject"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar ett engångsobjekt."
type: docs
weight: 40
url: /sv/java/com.aspose.imaging/disposableobject/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, java.io.Closeable
```
public class DisposableObject implements System.IDisposable, Closeable
```

Representerar ett engångsobjekt.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [DisposableObject()](#DisposableObject--) |  |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDisposed()](#getDisposed--) | Hämtar ett värde som indikerar om den här instansen har frigjorts. |
| [close()](#close--) | Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. |
| [dispose()](#dispose--) | Frigör den aktuella instansen. |
### DisposableObject() {#DisposableObject--}
```
public DisposableObject()
```


### getDisposed() {#getDisposed--}
```
public final boolean getDisposed()
```


Hämtar ett värde som indikerar om den här instansen har frigjorts.

**Returns:**
boolean - `true` om frigjord; annars `false`.
### close() {#close--}
```
public void close()
```


Implementerar Closable‑gränssnittet och kan användas i try‑with‑resources‑satsen sedan JDK 1.7. Denna metod anropar helt enkelt dispose‑metoden.

### dispose() {#dispose--}
```
public void dispose()
```


Frigör den aktuella instansen.


**Example: The following example shows how to compose a mutlipage TIFF from individual raster images.**

``` java

com.aspose.imaging.imageoptions.TiffOptions createTiffOptions
        = new com.aspose.imaging.imageoptions.TiffOptions(com.aspose.imaging.fileformats.tiff.enums.TiffExpectedFormat.Default);
createTiffOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("c:\\temp\\multipage.tif", false));
createTiffOptions.setPhotometric(com.aspose.imaging.fileformats.tiff.enums.TiffPhotometrics.Rgb);
createTiffOptions.setBitsPerSample(new int[]{8, 8, 8});

com.aspose.imaging.fileformats.tiff.TiffImage tiffImage = (com.aspose.imaging.fileformats.tiff.TiffImage) com.aspose.imaging.Image.create(createTiffOptions, 100, 100);
try {
    // Detta är Font och Brush för att rita text på enskilda ramar.
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Arial", 64);
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getWhite());

    // Skapa 5 ramar
    for (int i = 1; i <= 5; i++) {
        com.aspose.imaging.imageoptions.PngOptions createPngOptions = new com.aspose.imaging.imageoptions.PngOptions();
        createPngOptions.setSource(new com.aspose.imaging.sources.StreamSource(new java.io.ByteArrayInputStream(new byte[0])));

        // Skapa en PNG‑bild och rita sidnumret på den.
        com.aspose.imaging.fileformats.png.PngImage pngImage = (com.aspose.imaging.fileformats.png.PngImage) com.aspose.imaging.Image.create(createPngOptions, 100, 100);
        com.aspose.imaging.Graphics gr = new com.aspose.imaging.Graphics(pngImage);
        gr.drawString(Integer.toString(i), font, brush, 10, 10);

        // Skapa en ram baserad på PNG‑bilden.
        com.aspose.imaging.fileformats.tiff.TiffFrame frame = new com.aspose.imaging.fileformats.tiff.TiffFrame(pngImage);

        // Lägg till ramen i TIFF‑bilden.
        tiffImage.addFrame(frame);
    }

    // Bilden skapades med en enda standardram. Låt oss ta bort den.
    com.aspose.imaging.fileformats.tiff.TiffFrame activeFrame = tiffImage.getActiveFrame();
    tiffImage.setActiveFrame(tiffImage.getFrames()[1]);
    tiffImage.removeFrame(0);

    // Glöm inte att frigöra ramen om du inte kommer att lägga till den i någon annan TiffImage
    activeFrame.dispose();

    tiffImage.save();
} finally {
    tiffImage.dispose();
}
```

