---
title: ProgressEventHandler
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft den Fortschrittsereignishandler ab oder legt ihn fest.
type: docs
weight: 50
url: /de/net/aspose.imaging/loadoptions/progresseventhandler/
---
## LoadOptions.ProgressEventHandler property

Ruft den Fortschrittsereignishandler ab oder legt ihn fest.

```csharp
public ProgressEventHandler ProgressEventHandler { get; set; }
```

### Eigentumswert

Der Fortschrittsereignishandler.

### Beispiele

Das folgende Beispiel zeigt, wie Informationen zu Fortschrittsereignissen für Lade-/Exportvorgänge gedruckt werden.

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // Beispiel für die Verwendung separater Ereignishandler für den Vorgangsfortschritt für Lade-/Exportvorgänge
    using (var image = Aspose.Imaging.Image.Load(fileName, new Aspose.Imaging.LoadOptions { ProgressEventHandler = ProgressCallback }))
    {
        image.Save(fileName + ".psd",
                   new Aspose.Imaging.ImageOptions.PsdOptions() { ProgressEventHandler = ExportProgressCallback });
    }
}

private void ProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("{0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

private void ExportProgressCallback(Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo info)
{
    System.Console.WriteLine("Export event {0} : {1}/{2}", info.EventType, info.Value, info.MaxValue);
}

// Das STDOUT-Log könnte so aussehen:
//Initialisierung: 1/4
//Vorverarbeitung: 2/4
//Verarbeitung: 3/4
//Abschluss : 4/4
//Event-Initialisierung exportieren: 1/4
//Event PreProcessing exportieren: 2/4
//Event-Verarbeitung exportieren: 3/4
//Event RelativeProgress exportieren: 1/1
//Relativer Fortschritt : 1/1
//Ereignis exportieren Finalisierung : 4/4
```

### Siehe auch

* delegate [ProgressEventHandler](../../progresseventhandler)
* class [LoadOptions](../../loadoptions)
* namensraum [Aspose.Imaging](../../loadoptions)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->