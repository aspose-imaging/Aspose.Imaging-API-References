---
title: Load
second_title: Aspose.Imaging für .NET-API-Referenz
description: Lädt ein neues Bild aus der angegebenen Datei.
type: docs
weight: 20
url: /de/net/aspose.imaging/image/load/
---
## Load(string, LoadOptions) {#load_3}

Lädt ein neues Bild aus der angegebenen Datei.

```csharp
public static Image Load(string filePath, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Bild geladen werden soll. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Das geladene Bild.

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Load(string) {#load_2}

Lädt ein neues Bild aus der angegebenen Datei.

```csharp
public static Image Load(string filePath)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| filePath | String | Der Dateipfad, aus dem das Bild geladen werden soll. |

### Rückgabewert

Das geladene Bild.

### Beispiele

Dieses Beispiel zeigt das Laden einer vorhandenen Bilddatei in eine Instanz von Aspose.Imaging.Image unter Verwendung des angegebenen Dateipfads

```csharp
[C#]

//Bildinstanz erstellen und mit einer vorhandenen Bilddatei vom Speicherort initialisieren
using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(@"C:\temp\sample.bmp"))
{
    // Bildverarbeitung durchführen
}
```

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Load(Stream, LoadOptions) {#load_1}

Lädt ein neues Bild aus dem angegebenen Stream.

```csharp
public static Image Load(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem das Bild geladen werden soll. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Rückgabewert

Das geladene Bild.

### Siehe auch

* class [LoadOptions](../../loadoptions)
* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

---

## Load(Stream) {#load}

Lädt ein neues Bild aus dem angegebenen Stream.

```csharp
public static Image Load(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem das Bild geladen werden soll. |

### Rückgabewert

Das geladene Bild.

### Beispiele

Dieses Beispiel demonstriert die Verwendung von System.IO.Stream-Objekten zum Laden einer vorhandenen Bilddatei

```csharp
[C#]

//Eine Instanz von FileStream erstellen
using (System.IO.FileStream stream = new System.IO.FileStream(@"C:\temp\sample.bmp", System.IO.FileMode.Open))
{
    //Eine Instanz der Image-Klasse erstellen und eine vorhandene Datei durch das FileStream-Objekt laden, indem die Load-Methode aufgerufen wird
    using (Aspose.Imaging.Image image = Aspose.Imaging.Image.Load(stream))
    {
        // Bildverarbeitung durchführen.
    }
}
```

### Siehe auch

* class [Image](../../image)
* namensraum [Aspose.Imaging](../../image)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->