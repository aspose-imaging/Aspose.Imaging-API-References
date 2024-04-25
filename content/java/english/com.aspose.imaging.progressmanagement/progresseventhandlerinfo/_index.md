---
title: ProgressEventHandlerInfo
second_title: Aspose.Imaging for Java API Reference
description: This class represents information about image load/save/export operations progress that can be used in external application to show conversion progress to end user
type: docs
weight: 10
url: /com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

This class represents information about image load/save/export operations progress, that can be used in external application to show conversion progress to end user
## Methods

| Method | Description |
| --- | --- |
| [getDescription()](#getDescription--) | Gets the description of the event |
| [getEventType()](#getEventType--) | Gets the type of the event. |
| [getMaxValue()](#getMaxValue--) | Gets the upper progress value limit. |
| [getValue()](#getValue--) | Gets current progress value. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Example of use of separate operation progress event handlers for load/export operations
final com.aspose.imaging.ProgressEventHandler loadHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Load event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

final com.aspose.imaging.ProgressEventHandler exportHandler = new com.aspose.imaging.ProgressEventHandler() {
    @Override
    public void invoke(com.aspose.imaging.progressmanagement.ProgressEventHandlerInfo info) {
        System.out.format("Export event %s : %d/%d\n", com.aspose.imaging.progressmanagement.EventType.toString(com.aspose.imaging.progressmanagement.EventType.class, info.getEventType()), info.getValue(), info.getMaxValue());
    }
};

com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName, new com.aspose.imaging.LoadOptions() {{ setProgressEventHandler(loadHandler); }} );
try {
    image.save(fileName + ".psd",
            new com.aspose.imaging.imageoptions.PsdOptions() {{ setProgressEventHandler( exportHandler); }});
}
finally {
    image.close();
}

// The STDOUT log may look like this:
//        Load event Initialization : 1/4
//        Load event PreProcessing : 2/4
//        Load event Processing : 3/4
//        Load event Finalization : 4/4
//        Export event Initialization : 1/4
//        Export event PreProcessing : 2/4
//        Export event Processing : 3/4
//        Export event RelativeProgress : 1/1
//        Load event RelativeProgress : 1/1
//        Export event Finalization : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Gets the description of the event

Value: The description.

**Returns:**
java.lang.String - the description of the event
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Gets the type of the event.

Value: The type of the event.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Gets the upper progress value limit.

Value: The upper progress value limit.

**Returns:**
int - the upper progress value limit.
### getValue() {#getValue--}
```
public final int getValue()
```


Gets current progress value.

Value: The progress value.

**Returns:**
int - current progress value.
