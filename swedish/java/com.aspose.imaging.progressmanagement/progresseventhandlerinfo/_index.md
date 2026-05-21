---
title: "ProgressEventHandlerInfo"
second_title: "Aspose.Imaging för Java API-referens"
description: "Denna klass representerar information om framsteg för bildladdning-/sparande-/exportoperationer som kan användas i ett externt program för att visa konverteringsframsteg för slutanvändaren."
type: docs
weight: 10
url: /sv/java/com.aspose.imaging.progressmanagement/progresseventhandlerinfo/
---
**Inheritance:**
java.lang.Object
```
public class ProgressEventHandlerInfo
```

Denna klass representerar information om framsteg för bildladdnings-/sparnings-/exportoperationer, som kan användas i ett externt program för att visa konverteringsframsteg för slutanvändaren.
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getDescription()](#getDescription--) | Hämtar beskrivningen av händelsen |
| [getEventType()](#getEventType--) | Hämtar typen av händelsen. |
| [getMaxValue()](#getMaxValue--) | Hämtar det övre gränsvärdet för framstegsvärdet. |
| [getValue()](#getValue--) | Hämtar aktuellt framstegsvärde. |

## Example: The following example shows how to print information about progress events for load/export operations.

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1440\\";
String fileName = dir + "big.png";

// Exempel på användning av separata händelsehanterare för operationens framsteg för inläsnings-/exportoperationer.
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

// STDOUT‑loggen kan se ut så här:
//        Laddningshändelse Initiering : 1/4
//        Laddningshändelse Förbehandling : 2/4
//        Laddningshändelse Bearbetning : 3/4
//        Laddningshändelse Slutförande : 4/4
//        Exporthändelse Initiering : 1/4
//        Exporthändelse Förbehandling : 2/4
//        Exporthändelse Bearbetning : 3/4
//        Exporthändelse Relativt framsteg : 1/1
//        Laddningshändelse Relativt framsteg : 1/1
//        Exporthändelse Slutförande : 4/4
```

### getDescription() {#getDescription--}
```
public final String getDescription()
```


Hämtar beskrivningen av händelsen

Värde: Beskrivningen.

**Returns:**
java.lang.String - händelsens beskrivning
### getEventType() {#getEventType--}
```
public final EventType getEventType()
```


Hämtar typen av händelsen.

Värde: Händelsens typ.

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype) - the type of the event.
### getMaxValue() {#getMaxValue--}
```
public final int getMaxValue()
```


Hämtar det övre gränsvärdet för framstegsvärdet.

Värde: Det övre gränsvärdet för framstegsvärdet.

**Returns:**
int - det övre gränsvärdet för framstegsvärdet.
### getValue() {#getValue--}
```
public final int getValue()
```


Hämtar aktuellt framstegsvärde.

Värde: Framstegsvärdet.

**Returns:**
int - aktuellt framstegsvärde.
