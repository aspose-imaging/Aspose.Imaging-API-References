---
title: "FileCreateSource"
second_title: "Aspose.Imaging för Java API-referens"
description: "Representerar en filkälla för skapande."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Representerar en filkälla för skapande.
## Konstruktörer

| Konstruktor | Beskrivning |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initierar en ny instans av klassen `FileCreateSource` . |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initierar en ny instans av klassen `FileCreateSource` . |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getFilePath()](#getFilePath--) | Hämtar filvägen för att skapa. |
| [isTemporal()](#isTemporal--) | Hämtar ett värde som indikerar om filen kommer att vara temporär. |
| [getStreamContainer()](#getStreamContainer--) | Hämtar strömbehållaren. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Detta exempel demonstrerar användningen av Font‑ och SolidBrush‑klassen för att rita strängar på en Image‑yta. Exemplet skapar en ny Image och ritar former med Figures och GraphicsPath.
``` java
//Skapar en instans av BmpOptions och sätter dess olika egenskaper.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Skapa en instans av FileCreateSource och tilldela den som Source för BmpOptions‑instansen.
//Den andra booleska parametern avgör om filen som ska skapas är temporär eller inte.
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Skapar en instans av Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Skapar och initierar en instans av Graphics‑klassen
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Rensar Graphics‑ytan
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Skapar en instans av Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Skapa en instans av SolidBrush med röd färg
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Rita en sträng
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // spara alla ändringar
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initierar en ny instans av klassen `FileCreateSource` .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen att skapa. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initierar en ny instans av klassen `FileCreateSource` .

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| filePath | java.lang.String | Filvägen att skapa. |
| isTemporal | boolean | Om den är satt till `true` kommer den skapade filen att vara temporär. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Hämtar filvägen för att skapa.

Värde: Filvägen att skapa.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Hämtar ett värde som indikerar om filen kommer att vara temporär.

Värde: `true` om filen kommer att vara temporär; annars `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Hämtar strömbehållaren.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Använd med försiktighet. Du måste avyttra strömbehållaren efter hämtning.
