---
title: "EventType"
second_title: "Aspose.Imaging för Java API-referens"
description: "Denna enum beskriver möjliga typer av framstegshändelser som kan inträffa under bildbehandlingsoperationer."
type: docs
weight: 11
url: /sv/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Denna enum beskriver möjliga typer av framstegshändelser som kan inträffa under bildbehandlingsoperationer.
## Fält

| Fält | Beskrivning |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Relativt framsteg för nuvarande steg i operationens bearbetning |
| [StageChange](#StageChange) | Nästa steg i operationen har startat |
| [Initialization](#Initialization) | Initieringen av operationen |
| [PreProcessing](#PreProcessing) | Förbehandlingen |
| [Processing](#Processing) | Bearbetningen |
| [Finalization](#Finalization) | Slutförandet av operationen |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Relativt framsteg för nuvarande steg i operationens bearbetning

### StageChange {#StageChange}
```
public static final EventType StageChange
```


Nästa steg i operationen har startat

### Initialization {#Initialization}
```
public static final EventType Initialization
```


Initieringen av operationen

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Förbehandlingen

### Processing {#Processing}
```
public static final EventType Processing
```


Bearbetningen

### Finalization {#Finalization}
```
public static final EventType Finalization
```


Slutförandet av operationen

### values() {#values--}
```
public static EventType[] values()
```




**Returns:**
com.aspose.imaging.progressmanagement.EventType[]
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static EventType valueOf(String name)
```




**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| namn | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
