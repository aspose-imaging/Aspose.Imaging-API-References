---
title: "EventType"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Questo enum descrive i possibili tipi di eventi di progresso che possono verificarsi durante le operazioni di elaborazione delle immagini."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Questo enum descrive i possibili tipi di eventi di progresso che possono verificarsi durante le operazioni di elaborazione delle immagini.
## Campi

| Campo | Descrizione |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Progresso relativo della fase corrente dell'elaborazione dell'operazione |
| [StageChange](#StageChange) | La fase successiva dell'operazione è iniziata |
| [Initialization](#Initialization) | L'inizializzazione dell'operazione |
| [PreProcessing](#PreProcessing) | La pre-elaborazione |
| [Processing](#Processing) | L'elaborazione |
| [Finalization](#Finalization) | La finalizzazione dell'operazione |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Progresso relativo della fase corrente dell'elaborazione dell'operazione

### StageChange {#StageChange}
```
public static final EventType StageChange
```


La fase successiva dell'operazione è iniziata

### Initialization {#Initialization}
```
public static final EventType Initialization
```


L'inizializzazione dell'operazione

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


La pre-elaborazione

### Processing {#Processing}
```
public static final EventType Processing
```


L'elaborazione

### Finalization {#Finalization}
```
public static final EventType Finalization
```


La finalizzazione dell'operazione

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
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| nome | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
