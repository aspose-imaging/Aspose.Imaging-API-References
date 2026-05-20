---
title: "FileCreateSource"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta una sorgente file per la creazione."
type: docs
weight: 10
url: /it/java/com.aspose.imaging.sources/filecreatesource/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.Source](../../com.aspose.imaging/source), [com.aspose.imaging.sources.FileSource](../../com.aspose.imaging.sources/filesource)
```
public final class FileCreateSource extends FileSource
```

Rappresenta una sorgente file per la creazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [FileCreateSource(String filePath)](#FileCreateSource-java.lang.String-) | Inizializza una nuova istanza della classe `FileCreateSource`. |
| [FileCreateSource(String filePath, boolean isTemporal)](#FileCreateSource-java.lang.String-boolean-) | Inizializza una nuova istanza della classe `FileCreateSource`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getFilePath()](#getFilePath--) | Ottiene il percorso del file da creare. |
| [isTemporal()](#isTemporal--) | Ottiene un valore che indica se il file sarà temporaneo. |
| [getStreamContainer()](#getStreamContainer--) | Ottiene il contenitore di flusso. |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
Questo esempio dimostra l'uso delle classi Font e SolidBrush per disegnare stringhe sulla superficie dell'Image. L'esempio crea una nuova Image e disegna forme usando Figures e GraphicsPath.
``` java
//Crea un'istanza di BmpOptions e imposta le sue varie proprietà.
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//Crea un'istanza di FileCreateSource e assegnala come Source per l'istanza di BmpOptions
//Il secondo parametro Boolean determina se il file da creare è IsTemporal o meno
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//Crea un'istanza di Image
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //Crea e inizializza un'istanza della classe Graphics
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //Cancella la superficie di Graphics
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //Crea un'istanza di Font
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //Crea un'istanza di SolidBrush con colore rosso
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //Disegna una stringa
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // salva tutte le modifiche
    image.save();
} finally {
    image.dispose();
}
```

### FileCreateSource(String filePath) {#FileCreateSource-java.lang.String-}
```
public FileCreateSource(String filePath)
```


Inizializza una nuova istanza della classe `FileCreateSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da creare. |

### FileCreateSource(String filePath, boolean isTemporal) {#FileCreateSource-java.lang.String-boolean-}
```
public FileCreateSource(String filePath, boolean isTemporal)
```


Inizializza una nuova istanza della classe `FileCreateSource`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| filePath | java.lang.String | Il percorso del file da creare. |
| isTemporal | boolean | Se impostato su `true`, il file creato sarà temporaneo. |

### getFilePath() {#getFilePath--}
```
public String getFilePath()
```


Ottiene il percorso del file da creare.

Valore: Il percorso del file da creare.

**Returns:**
java.lang.String
### isTemporal() {#isTemporal--}
```
public boolean isTemporal()
```


Ottiene un valore che indica se il file sarà temporaneo.

Valore: `true` se il file sarà temporaneo; altrimenti, `false`.

**Returns:**
boolean
### getStreamContainer() {#getStreamContainer--}
```
public StreamContainer getStreamContainer()
```


Ottiene il contenitore di flusso.

**Returns:**
[StreamContainer](../../com.aspose.imaging/streamcontainer) - the stream container.

Usare con cautela. Sarà necessario eliminare il contenitore di flusso dopo il recupero.
