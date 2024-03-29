---
title: DicomImage
second_title: Aspose.Imaging für .NET-API-Referenz
description: Initialisiert eine neue Instanz vonDicomImageaspose.imaging.fileformats.dicom/dicomimage Klasse.
type: docs
weight: 10
url: /de/net/aspose.imaging.fileformats.dicom/dicomimage/dicomimage/
---
## DicomImage(DicomOptions, int, int) {#constructor}

Initialisiert eine neue Instanz von[`DicomImage`](../../dicomimage) Klasse.

```csharp
public DicomImage(DicomOptions dicomOptions, int width, int height)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| dicomOptions | DicomOptions | Die dicom-Optionen. |
| width | Int32 | Die Breite. |
| height | Int32 | Die Höhe. |

### Siehe auch

* class [DicomOptions](../../../aspose.imaging.imageoptions/dicomoptions)
* class [DicomImage](../../dicomimage)
* namensraum [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Montage [Aspose.Imaging](../../../)

---

## DicomImage(Stream, LoadOptions) {#constructor_2}

Initialisiert eine neue Instanz von[`DicomImage`](../../dicomimage) Klasse.

```csharp
public DicomImage(Stream stream, LoadOptions loadOptions)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |
| loadOptions | LoadOptions | Die Ladeoptionen. |

### Beispiele

Dieses Beispiel zeigt, wie ein DICOM-Bild aus einem Dateistream geladen wird, um innerhalb der angegebenen Speichergrenze zu bleiben.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein DICOM-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "multiframe.dicom"))
{
    // Die maximal zulässige Größe für alle internen Puffer beträgt 256 KB.
    Aspose.Imaging.LoadOptions loadOptions = new Aspose.Imaging.LoadOptions();
    loadOptions.BufferSizeHint = 256 * 1024;

    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream, loadOptions))
    {
        // Speichern Sie jede Seite als einzelnes PNG-Bild.
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Erzeuge einen Dateinamen basierend auf dem Seitenindex.
            string fileName = string.Format("multiframe.{0}.png", dicomPage.Index);

            // Eine DICOM-Seite ist ein Rasterbild, daher sind alle zulässigen Operationen mit einem Rasterbild auf eine DICOM-Seite anwendbar.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Siehe auch

* class [LoadOptions](../../../aspose.imaging/loadoptions)
* class [DicomImage](../../dicomimage)
* namensraum [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Montage [Aspose.Imaging](../../../)

---

## DicomImage(Stream) {#constructor_1}

Initialisiert eine neue Instanz von[`DicomImage`](../../dicomimage) Klasse.

```csharp
public DicomImage(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Strom. |

### Beispiele

Dieses Beispiel zeigt, wie ein DICOM-Bild aus einem Dateistream geladen wird.

```csharp
[C#]

string dir = "c:\\temp\\";

// Laden Sie ein DICOM-Bild aus einem Dateistream.
using (System.IO.Stream stream = System.IO.File.OpenRead(dir + "sample.dicom"))
{
    using (Aspose.Imaging.FileFormats.Dicom.DicomImage dicomImage = new Aspose.Imaging.FileFormats.Dicom.DicomImage(stream))
    {
        // Speichern Sie jede Seite als einzelnes PNG-Bild.                    
        foreach (Aspose.Imaging.FileFormats.Dicom.DicomPage dicomPage in dicomImage.DicomPages)
        {
            // Erzeuge einen Dateinamen basierend auf dem Seitenindex.
            string fileName = string.Format("sample.{0}.png", dicomPage.Index);

            // Eine DICOM-Seite ist ein Rasterbild, daher sind alle zulässigen Operationen mit einem Rasterbild auf eine DICOM-Seite anwendbar.
            dicomPage.Save(dir + fileName, new Aspose.Imaging.ImageOptions.PngOptions());
        }
    }
}
```

### Siehe auch

* class [DicomImage](../../dicomimage)
* namensraum [Aspose.Imaging.FileFormats.Dicom](../../dicomimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
