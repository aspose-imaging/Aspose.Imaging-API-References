---
title: "EventType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu enum, görüntü işleme işlemleri sırasında meydana gelebilecek olası ilerleme olayı türlerini tanımlar."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Bu enum, görüntü işleme işlemleri sırasında meydana gelebilecek olası ilerleme olayı türlerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | İşlemin mevcut aşamasının göreceli ilerlemesi |
| [StageChange](#StageChange) | İşlemin bir sonraki aşaması başladı |
| [Initialization](#Initialization) | İşlemin başlatılması |
| [PreProcessing](#PreProcessing) | Ön işleme |
| [Processing](#Processing) | İşleme |
| [Finalization](#Finalization) | İşlemin sonlandırılması |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


İşlemin mevcut aşamasının göreceli ilerlemesi

### StageChange {#StageChange}
```
public static final EventType StageChange
```


İşlemin bir sonraki aşaması başladı

### Initialization {#Initialization}
```
public static final EventType Initialization
```


İşlemin başlatılması

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Ön işleme

### Processing {#Processing}
```
public static final EventType Processing
```


İşleme

### Finalization {#Finalization}
```
public static final EventType Finalization
```


İşlemin sonlandırılması

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
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ad | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
