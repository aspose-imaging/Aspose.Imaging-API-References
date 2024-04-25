---
title: EventType
second_title: Aspose.Imaging for Java API Reference
description: This enum describes possible progress event types that can occurred during image processing operations
type: docs
weight: 11
url: /com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

This enum describes possible progress event types that can occurred during image processing operations
## Fields

| Field | Description |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Relative progress of current stage of the operation processing |
| [StageChange](#StageChange) | The next stage of the operation started |
| [Initialization](#Initialization) | The initialization of the operation |
| [PreProcessing](#PreProcessing) | The pre processing |
| [Processing](#Processing) | The processing |
| [Finalization](#Finalization) | The finalization of the operation |
## Methods

| Method | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Relative progress of current stage of the operation processing

### StageChange {#StageChange}
```
public static final EventType StageChange
```


The next stage of the operation started

### Initialization {#Initialization}
```
public static final EventType Initialization
```


The initialization of the operation

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


The pre processing

### Processing {#Processing}
```
public static final EventType Processing
```


The processing

### Finalization {#Finalization}
```
public static final EventType Finalization
```


The finalization of the operation

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
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
