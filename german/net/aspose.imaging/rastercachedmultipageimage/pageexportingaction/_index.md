---
title: PageExportingAction
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.
type: docs
weight: 90
url: /de/net/aspose.imaging/rastercachedmultipageimage/pageexportingaction/
---
## RasterCachedMultipageImage.PageExportingAction property

Ruft die Aktion zum Exportieren der Seite ab oder legt sie fest. Bitte beachten Sie, dass das Festlegen dieser Methode automatisch Seitenressourcen freigibt, nachdem sie ausgeführt wurde. Sie wird unmittelbar vor dem Speichern jeder Seite ausgeführt.

```csharp
public virtual PageExportingAction PageExportingAction { get; set; }
```

### Eigentumswert

Die Seitenexportaktion.

### Beispiele

Das folgende Beispiel zeigt die Stapelkonvertierung vor dem Speichern (Exportieren) von TIFF-Bildern.

```csharp
[C#]

string fileName = "10MB_Tif.tif";
    string inputFileName = fileName;

    string outputFileNameTif = "output.tif";
    
    //Die Möglichkeit der Stapelkonvertierung vor dem Speichern (Exportieren) von Tiff-Bildern ist implementiert.

    using (Aspose.Imaging.FileFormats.Tiff.TiffImage tiffImage = (Aspose.Imaging.FileFormats.Tiff.TiffImage)Aspose.Imaging.Image.Load(inputFileName))
    {
        // Batch-Operation für Seiten festlegen
        tiffImage.PageExportingAction = delegate(int index, Image page)
        {
            // Löst Garbage Collection aus, um unnötige Garbage-Speicherung von vorherigen Seiten zu vermeiden
            GC.Collect();

            ((Aspose.Imaging.RasterImage)page).Rotate(90);
        };

        tiffImage.Save(outputFileNameTif);

        /* Attention! In batch mode all pages will be released in this line!
         If you want to further perform operations on the original image, you should reload it from the source to another instance. */
    }
```

### Siehe auch

* delegate [PageExportingAction](../../pageexportingaction)
* class [RasterCachedMultipageImage](../../rastercachedmultipageimage)
* namensraum [Aspose.Imaging](../../rastercachedmultipageimage)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->