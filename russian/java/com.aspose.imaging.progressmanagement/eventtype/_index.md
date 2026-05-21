---
title: "EventType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Это перечисление описывает возможные типы событий прогресса, которые могут возникать во время операций обработки изображений."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.progressmanagement/eventtype/
---
**Inheritance:**
java.lang.Object, java.lang.Enum
```
public enum EventType extends Enum<EventType>
```

Это перечисление описывает возможные типы событий прогресса, которые могут возникать во время операций обработки изображений.
## Поля

| Поле | Описание |
| --- | --- |
| [RelativeProgress](#RelativeProgress) | Относительный прогресс текущего этапа обработки операции |
| [StageChange](#StageChange) | Следующий этап операции начался |
| [Initialization](#Initialization) | Инициализация операции |
| [PreProcessing](#PreProcessing) | Предобработка |
| [Processing](#Processing) | Обработка |
| [Finalization](#Finalization) | Завершение операции |
## Методы

| Метод | Описание |
| --- | --- |
| [values()](#values--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
### RelativeProgress {#RelativeProgress}
```
public static final EventType RelativeProgress
```


Относительный прогресс текущего этапа обработки операции

### StageChange {#StageChange}
```
public static final EventType StageChange
```


Следующий этап операции начался

### Initialization {#Initialization}
```
public static final EventType Initialization
```


Инициализация операции

### PreProcessing {#PreProcessing}
```
public static final EventType PreProcessing
```


Предобработка

### Processing {#Processing}
```
public static final EventType Processing
```


Обработка

### Finalization {#Finalization}
```
public static final EventType Finalization
```


Завершение операции

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
| Параметр | Тип | Описание |
| --- | --- | --- |
| имя | java.lang.String |  |

**Returns:**
[EventType](../../com.aspose.imaging.progressmanagement/eventtype)
