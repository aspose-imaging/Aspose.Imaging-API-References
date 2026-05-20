---
title: "Ereignistyp"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Diese Aufzählung beschreibt mögliche Fortschrittsereignistypen, die während Bildverarbeitungs‑Operationen auftreten können"
type: docs
weight: 11
url: /de/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Diese Aufzählung beschreibt mögliche Fortschrittsereignistypen, die während Bildverarbeitungs‑Operationen auftreten können
## Felder

| Feld | Beschreibung |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Relativer Fortschritt der aktuellen Phase der Vorgangsverarbeitung |
| [StageChange](#StageChange) | Die nächste Phase des Vorgangs hat begonnen |
| [Initialization](#Initialization) | Die Initialisierung des Vorgangs |
| [PreProcessing](#PreProcessing) | Die Vorverarbeitung |
| [Processing](#Processing) | Die Verarbeitung |
| [Finalization](#Finalization) | Die Finalisierung des Vorgangs |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Relativer Fortschritt der aktuellen Phase der Vorgangsverarbeitung

### StageChange {#StageChange}
```
public static final EventType StageChange
```


Die nächste Phase des Vorgangs hat begonnen

### Initialization {#Initialization}
```
public static final EventType Initialization
```


Die Initialisierung des Vorgangs

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Die Vorverarbeitung

### Processing {#Processing}
```
public static final EventType Processing
```


Die Verarbeitung

### Finalization {#Finalization}
```
public static final EventType Finalization
```


Die Finalisierung des Vorgangs

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
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Name | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
