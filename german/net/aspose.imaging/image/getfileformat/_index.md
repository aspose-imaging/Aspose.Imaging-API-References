---
title: GetFileFormat
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft das Dateiformat ab.
type: docs
weight: 270
url: /de/net/aspose.imaging/image/getfileformat/
---
## GetFileFormat(string) {#getfileformat_1}

Ruft das Dateiformat ab.

```csharp
public static FileFormat GetFileFormat(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad. |

### Rückgabewert

Das ermittelte Dateiformat.

### Bemerkungen

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden darf. Verwenden Sie eine der CanLoad-Methodenüberladungen, um zu bestimmen, ob die Datei geladen werden kann.

### Beispiele

Dieses Beispiel zeigt, wie Sie das Bildformat ermitteln, ohne das gesamte Bild aus einer Datei zu laden.

```csharp
[C#]

string dir = "c:\\temp\\";

// Verwenden Sie einen absoluten Pfad zur Datei
Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(dir + "sample.gif");
System.Console.WriteLine("The file format is {0}", format);
```

### Siehe auch

* enum [FileFormat](../../fileformat)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## GetFileFormat(Stream) {#getfileformat}

Ruft das Dateiformat ab.

```csharp
public static FileFormat GetFileFormat(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |

### Rückgabewert

Das ermittelte Dateiformat.

### Bemerkungen

Das ermittelte Dateiformat bedeutet nicht, dass das angegebene Bild geladen werden darf. Verwenden Sie eine der CanLoad-Methodenüberladungen, um zu bestimmen, ob der Stream geladen werden kann.

### Beispiele

Dieses Beispiel zeigt, wie Sie das Bildformat ermitteln, ohne das gesamte Bild aus einem Dateistream zu laden.

```csharp
[C#]

string dir = "c:\\temp\\";

// Verwenden Sie einen Dateistream
using (System.IO.FileStream stream = System.IO.File.OpenRead(dir + "sample.bmp"))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}

// Die folgenden Daten sind kein gültiger Bildstream, daher gibt GetFileFormat FileFormat.Undefined zurück.
byte[] imageData = new byte[] { 0, 0, 0, 0, 0, 0, 0, 0 };
using (System.IO.MemoryStream stream = new System.IO.MemoryStream(imageData))
{
    Aspose.Imaging.FileFormat format = Aspose.Imaging.Image.GetFileFormat(stream);
    System.Console.WriteLine("The file format is {0}", format);
}
```

### Siehe auch

* enum [FileFormat](../../fileformat)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
