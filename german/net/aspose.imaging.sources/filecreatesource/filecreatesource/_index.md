---
title: FileCreateSource
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonFileCreateSourceaspose.imaging.sources/filecreatesource Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.sources/filecreatesource/filecreatesource/
---
## FileCreateSource(string) {#constructor}

Initialisiert eine neue Instanz von[`FileCreateSource`](../../filecreatesource) Klasse.

```csharp
public FileCreateSource(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der zu erstellende Dateipfad. |

### Beispiele

Dieses Beispiel erstellt eine neue Image-Datei an einem Speicherort auf dem Datenträger, wie von der Source-Eigenschaft der BmpOptions-Instanz angegeben. Wenn der zweite Parameter nicht an den Konstruktor von FileCreateSource übergeben wird, hat die zu erstellende Datei standardmäßig die Eigenschaft IsTemporal auf True gesetzt. Wenn IsTemporal auf True gesetzt ist, wird am Ende der Ausführung keine Datei auf der Festplatte gespeichert.

```csharp
[C#]

//Erzeugt eine Instanz von BmpOptions und setzt ihre verschiedenen Eigenschaften
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Wenn der zweite Parameter nicht übergeben wird, ist IsTemporal für die Datei standardmäßig auf True gesetzt
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp");

//Erzeugt eine Instanz von Image 
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Bildverarbeitung durchführen
}
```

### Siehe auch

* class [FileCreateSource](../../filecreatesource)
* namensraum [Aspose.Imaging.Sources](../../filecreatesource)
* Montage [Aspose.Imaging](../../../)

---

## FileCreateSource(string, bool) {#constructor_1}

Initialisiert eine neue Instanz von[`FileCreateSource`](../../filecreatesource) Klasse.

```csharp
public FileCreateSource(string filePath, bool isTemporal)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der zu erstellende Dateipfad. |
| isTemporal | Boolean | Wenn eingestellt`Stimmt`Die erstellte Datei ist zeitlich. |

### Beispiele

Dieses Beispiel erstellt eine neue Image-Datei an einem Speicherort auf dem Datenträger, wie von der Source-Eigenschaft der BmpOptions-Instanz angegeben. Mehrere Eigenschaften für die BmpOptions-Instanz werden festgelegt, bevor das eigentliche Bild erstellt wird. Insbesondere die Source-Eigenschaft, die sich in diesem Fall auf den tatsächlichen Speicherort der Festplatte bezieht.

```csharp
[C#]

//Eine Instanz von BmpOptions erstellen und ihre verschiedenen Eigenschaften festlegen
Aspose.Imaging.ImageOptions.BmpOptions bmpOptions = new Aspose.Imaging.ImageOptions.BmpOptions();
bmpOptions.BitsPerPixel = 24;

//Eine Instanz von FileCreateSource erstellen und als Quelle für die Instanz von BmpOptions zuweisen
//Der zweite boolesche Parameter bestimmt, ob die zu erstellende Datei Temporär ist oder nicht
bmpOptions.Source = new Aspose.Imaging.Sources.FileCreateSource(@"C:\temp\output.bmp", false);

//Erstellen Sie eine Instanz von Image und initialisieren Sie sie mit einer Instanz von BmpOptions, indem Sie die Create-Methode aufrufen
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Create(bmpOptions, 500, 500))
{
    // Bildverarbeitung durchführen

    // Alle Änderungen speichern
    image.Save();
}
```

### Siehe auch

* class [FileCreateSource](../../filecreatesource)
* namensraum [Aspose.Imaging.Sources](../../filecreatesource)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
