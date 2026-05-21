---
title: "EventType"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "Esta enumeración describe los posibles tipos de eventos de progreso que pueden ocurrir durante las operaciones de procesamiento de imágenes."
type: docs
weight: 11
url: /es/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Esta enumeración describe los posibles tipos de eventos de progreso que pueden ocurrir durante las operaciones de procesamiento de imágenes.
## Campos

| Campo | Descripción |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Progreso relativo de la etapa actual del procesamiento de la operación |
| [StageChange](#StageChange) | La siguiente etapa de la operación comenzó |
| [Initialization](#Initialization) | La inicialización de la operación |
| [PreProcessing](#PreProcessing) | El preprocesamiento |
| [Processing](#Processing) | El procesamiento |
| [Finalization](#Finalization) | La finalización de la operación |
## Métodos

| Método | Descripción |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Progreso relativo de la etapa actual del procesamiento de la operación

### StageChange {#StageChange}
```
public static final EventType StageChange
```


La siguiente etapa de la operación comenzó

### Initialization {#Initialization}
```
public static final EventType Initialization
```


La inicialización de la operación

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


El preprocesamiento

### Processing {#Processing}
```
public static final EventType Processing
```


El procesamiento

### Finalization {#Finalization}
```
public static final EventType Finalization
```


La finalización de la operación

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
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| nombre | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
