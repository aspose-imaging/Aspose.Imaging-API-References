---
title: "OdgImage"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Verarbeiten Sie das OpenDocument Graphic ODG-Vektorbildformat mit unserer API, das von OpenOffice und LibreOffice Draw zum Speichern von Zeichnungselementen im Vektorformat verwendet wird."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.opendocument/odgimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.VectorImage](../../com.aspose.imaging/vectorimage), [com.aspose.imaging.VectorMultipageImage](../../com.aspose.imaging/vectormultipageimage), [com.aspose.imaging.fileformats.opendocument.OdImage](../../com.aspose.imaging.fileformats.opendocument/odimage)
```
public class OdgImage extends OdImage
```

Verarbeiten Sie das OpenDocument Graphic (ODG)-Vektorbildformat mit unserer API, das von OpenOffice und LibreOffice Draw zum Speichern von Zeichnungselementen im Vektorformat verwendet wird. Parsen Sie Dokumente nahtlos, greifen Sie auf Seiten zu, skalieren und drehen Sie Bilder, um eine effiziente Verarbeitung und Anpassung von ODG-Dateien an Ihre spezifischen Anforderungen zu gewährleisten.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OdgImage(StreamContainer streamContainer, LoadOptions options)](#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-) | Starten Sie die Erstellung eines neuen Objekts der Klasse [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage), indem Sie eine frische Instanz initiieren. |
| [OdgImage(StreamContainer streamContainer)](#OdgImage-com.aspose.imaging.StreamContainer-) | Entwickelt für nahtlose Integration in Softwarelösungen, initialisiert der Konstruktor von [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage), indem er einen Stream-Container nutzt, eine neue Instanz. |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getFileFormat()](#getFileFormat--) | Rufen Sie den Dateiformatwert einfach mit dieser benutzerfreundlichen Eigenschaft ab. |
| [getPages()](#getPages--) | Durch das Abrufen der Seitensammlung ermöglicht diese Eigenschaft den Zugriff auf alle mit einem Bild verknüpften Seiten. |

## Example: This example loads a multi-page ODG image.

``` java
String dir = "c:\\temp\\";

// Die Verwendung von Aspose.Imaging.Image.Load ist ein einheitlicher Weg, ein Bild zu laden.
com.aspose.imaging.fileformats.opendocument.MultiPageImage image = (com.aspose.imaging.fileformats.opendocument.MultiPageImage) com.aspose.imaging.Image.load(dir + "sample.odg");
try {
    // In OdgImage umwandeln
    com.aspose.imaging.fileformats.opendocument.OdgImage odgImage = (com.aspose.imaging.fileformats.opendocument.OdgImage) image;

    // Alle Seiten abrufen
    com.aspose.imaging.Image[] pages = odgImage.getPages();

    // Führen Sie einige Bildverarbeitungen durch
} finally {
    image.dispose();
}
```


## Example: The following example shows how to export a FODG (Flat XML ODF Template) image to PDF format.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1509\\";

String inputFileName = dir + "VariousObjectsMultiPage.fodg";
String outputFileName = inputFileName + ".pdf";

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputFileName);
try {
    com.aspose.imaging.imageoptions.OdgRasterizationOptions rasterizationOptions = new com.aspose.imaging.imageoptions.OdgRasterizationOptions();
    rasterizationOptions.setBackgroundColor(com.aspose.imaging.Color.getWhite());
    rasterizationOptions.setPageSize(Size.to_SizeF(image.getSize()));

    com.aspose.imaging.imageoptions.PdfOptions saveOptions = new com.aspose.imaging.imageoptions.PdfOptions();
    saveOptions.setVectorRasterizationOptions(rasterizationOptions);

    image.save(outputFileName, saveOptions);
}
finally {
    image.close();
}
```

### OdgImage(StreamContainer streamContainer, LoadOptions options) {#OdgImage-com.aspose.imaging.StreamContainer-com.aspose.imaging.LoadOptions-}
```
public OdgImage(StreamContainer streamContainer, LoadOptions options)
```


Starten Sie die Erstellung eines neuen Objekts der Klasse [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage), indem Sie eine frische Instanz initiieren. Nutzen Sie das Potenzial eines Stream-Containers in Kombination mit Ladeoptionen, um einen vielseitigen Konstruktor zu erhalten, der Bilder nahtlos lädt. Dieser Konstruktor ermöglicht eine effiziente Bildverarbeitung und bietet anpassbare Ladekonfigurationen für verbesserte Anpassungsfähigkeit und Leistung in verschiedenen Szenarien.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream. |
| options | [LoadOptions](../../com.aspose.imaging/loadoptions) | Die Ladeoptionen |

### OdgImage(StreamContainer streamContainer) {#OdgImage-com.aspose.imaging.StreamContainer-}
```
public OdgImage(StreamContainer streamContainer)
```


Entwickelt für nahtlose Integration in Softwarelösungen, initialisiert der Konstruktor von [OdgImage](../../com.aspose.imaging.fileformats.opendocument/odgimage), indem er einen Stream-Container nutzt, eine neue Instanz. Diese Methode gewährleistet eine effiziente Handhabung von ODG-Bilddaten in Softwareumgebungen, optimiert die Ressourcennutzung und erleichtert optimierte Bildverarbeitungsabläufe.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| streamContainer | [StreamContainer](../../com.aspose.imaging/streamcontainer) | Der Stream‑Container. |

### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Rufen Sie den Dateiformatwert einfach über diese benutzerfreundliche Eigenschaft ab. Ideal für Entwickler, die schnellen Zugriff auf Informationen zum Dateiformat benötigen.

**Returns:**
long – ein Wert des Dateiformats
### getPages() {#getPages--}
```
public Image[] getPages()
```


Durch das Abrufen der Seitensammlung ermöglicht diese Eigenschaft den Zugriff auf alle mit einem Bild verknüpften Seiten. Durch den Zugriff auf diese Eigenschaft können Entwickler einzelne Seiten durchlaufen, bestimmte Seiten anhand ihres Index abrufen oder Batch-Operationen für die gesamte Sammlung durchführen.

**Returns:**
com.aspose.imaging.Image[] – die Seiten.
