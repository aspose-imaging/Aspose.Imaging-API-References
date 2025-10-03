---
title: ImageOptionsBase.ProgressEventHandler
second_title: Aspose.Imaging for .NET API Reference
description: ImageOptionsBase property. Gets or sets the progress event handler
type: docs
weight: 70
url: /net/aspose.imaging/imageoptionsbase/progresseventhandler/
---
## ImageOptionsBase.ProgressEventHandler property

Gets or sets the progress event handler.

```csharp
public ProgressEventHandler ProgressEventHandler { get; set; }
```

### Property Value

The progress event handler.

## Examples

The following example shows how to print information about progress events for load/export operations.

```csharp
[C#]

public void Test3460()
{
    string dir = "c:\\aspose.imaging\\net\\issues\\3460";
    string fileName = System.IO.Path.Combine(dir, "big.png");

    // Example of use of separate operation progress event handlers for load/export operations
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

// The STDOUT log may look like this:
//Initialization : 1/4
//PreProcessing : 2/4
//Processing : 3/4
//Finalization : 4/4
//Export event Initialization : 1/4
//Export event PreProcessing : 2/4
//Export event Processing : 3/4
//Export event RelativeProgress : 1/1
//RelativeProgress : 1/1
//Export event Finalization : 4/4
```

### See Also

* delegate [ProgressEventHandler](../../progresseventhandler/)
* class [ImageOptionsBase](../)
* namespace [Aspose.Imaging](../../imageoptionsbase/)
* assembly [Aspose.Imaging](../../../)


