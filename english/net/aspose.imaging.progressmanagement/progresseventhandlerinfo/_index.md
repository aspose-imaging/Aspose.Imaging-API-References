---
title: Class ProgressEventHandlerInfo
second_title: Aspose.Imaging for .NET API Reference
description: Aspose.Imaging.ProgressManagement.ProgressEventHandlerInfo class. This class represents information about image load/save/export operations progress that can be used in external application to show conversion progress to end user
type: docs
weight: 11350
url: /net/aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
## ProgressEventHandlerInfo class

This class represents information about image load/save/export operations progress, that can be used in external application to show conversion progress to end user

```csharp
public class ProgressEventHandlerInfo
```

## Properties

| Name | Description |
| --- | --- |
| [Description](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/description/) { get; } | Gets the description of the event |
| [EventType](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/eventtype/) { get; } | Gets the type of the event. |
| [MaxValue](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/maxvalue/) { get; } | Gets the upper progress value limit. |
| [Value](../../aspose.imaging.progressmanagement/progresseventhandlerinfo/value/) { get; } | Gets current progress value. |

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

* namespace [Aspose.Imaging.ProgressManagement](../../aspose.imaging.progressmanagement/)
* assembly [Aspose.Imaging](../../)


