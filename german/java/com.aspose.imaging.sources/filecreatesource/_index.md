---
title: "FileCreateSource"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Stellt eine Dateiquelle für die Erstellung dar."
type: docs
weight: 10
url: /de/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Stellt eine Dateiquelle für die Erstellung dar.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Initialisiert eine neue Instanz der `FileCreateSource`-Klasse. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Initialisiert eine neue Instanz der `FileCreateSource`-Klasse. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFilePath()](#getFilePath--) | Ruft den Dateipfad zum Erstellen ab. |
| [isTemporal()](#isTemporal--) | Ruft einen Wert ab, der angibt, ob die Datei temporär ist. |
| [getStreamContainer()](#getStreamContainer--) | Ruft den Stream‑Container ab. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Dieses Beispiel demonstriert die Verwendung der Klassen Font und SolidBrush, um Zeichenketten auf einer Image-Oberfläche zu zeichnen. Das Beispiel erstellt ein neues Image und zeichnet Formen mit Figures und GraphicsPath
``` java
//Erstellt eine Instanz von BmpOptions und setzt deren verschiedene Eigenschaften
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Erstellen Sie eine Instanz von FileCreateSource und weisen Sie sie als Source für die Instanz von BmpOptions zu
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei IsTemporal ist oder nicht
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Erstellt eine Instanz von Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Erstellt und initialisiert eine Instanz der Klasse Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Löscht die Graphics-Oberfläche
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Erstellt eine Instanz von Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Erstellt eine Instanz von SolidBrush mit roter Farbe
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Zeichnet eine Zeichenkette
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // Alle Änderungen speichern
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Initialisiert eine neue Instanz der `FileCreateSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad zum Erstellen. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Initialisiert eine neue Instanz der `FileCreateSource`-Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | java.lang.String | Der Dateipfad zum Erstellen. |
| isTemporal | boolean | Wenn auf `true` gesetzt, wird die erstellte Datei temporär. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ruft den Dateipfad zum Erstellen ab.

Wert: Der Dateipfad zum Erstellen.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Ruft einen Wert ab, der angibt, ob die Datei temporär ist.

Wert: `true`, wenn die Datei temporär ist; andernfalls `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ruft den Stream‑Container ab.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Vorsichtig verwenden. Der Stream‑Container muss nach dem Abrufen freigegeben werden.
