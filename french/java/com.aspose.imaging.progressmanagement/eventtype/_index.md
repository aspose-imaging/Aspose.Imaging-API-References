---
title: "EventType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "Cette énumération décrit les types d'événements de progression possibles qui peuvent survenir pendant les opérations de traitement d'images."
type: docs
weight: 11
url: /fr/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Cette énumération décrit les types d'événements de progression possibles qui peuvent survenir pendant les opérations de traitement d'images.
## Champs

| Champ | Description |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Progression relative de l'étape actuelle du traitement de l'opération |
| [StageChange](#StageChange) | L'étape suivante de l'opération a commencé |
| [Initialization](#Initialization) | L'initialisation de l'opération |
| [PreProcessing](#PreProcessing) | Le prétraitement |
| [Processing](#Processing) | Le traitement |
| [Finalization](#Finalization) | La finalisation de l'opération |
## Méthodes

| Méthode | Description |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Progression relative de l'étape actuelle du traitement de l'opération

### StageChange {#StageChange}
```
public static final EventType StageChange
```


L'étape suivante de l'opération a commencé

### Initialization {#Initialization}
```
public static final EventType Initialization
```


L'initialisation de l'opération

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Le prétraitement

### Processing {#Processing}
```
public static final EventType Processing
```


Le traitement

### Finalization {#Finalization}
```
public static final EventType Finalization
```


La finalisation de l'opération

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
| Paramètre | Type | Description |
| --- | --- | --- |
| nom | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
