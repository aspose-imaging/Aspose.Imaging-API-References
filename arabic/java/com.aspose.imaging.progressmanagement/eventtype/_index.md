---
title: "EventType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هذا التعداد يصف أنواع أحداث التقدم الممكنة التي يمكن أن تحدث أثناء عمليات معالجة الصورة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

هذا التعداد يصف أنواع أحداث التقدم الممكنة التي يمكن أن تحدث أثناء عمليات معالجة الصورة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | التقدم النسبي للمرحلة الحالية من معالجة العملية |
| [StageChange](#StageChange) | بدأت المرحلة التالية من العملية |
| [Initialization](#Initialization) | تهيئة العملية |
| [PreProcessing](#PreProcessing) | المعالجة المسبقة |
| [Processing](#Processing) | المعالجة |
| [Finalization](#Finalization) | إنهاء العملية |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


التقدم النسبي للمرحلة الحالية من معالجة العملية

### StageChange {#StageChange}
```
public static final EventType StageChange
```


بدأت المرحلة التالية من العملية

### Initialization {#Initialization}
```
public static final EventType Initialization
```


تهيئة العملية

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


المعالجة المسبقة

### Processing {#Processing}
```
public static final EventType Processing
```


المعالجة

### Finalization {#Finalization}
```
public static final EventType Finalization
```


إنهاء العملية

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
| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
