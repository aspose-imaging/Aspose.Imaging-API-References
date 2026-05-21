---
title: "EmfCreateBrushIndirect"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_CREATEBRUSHINDIRECT определяет логическую кисть для графических операций."
type: docs
weight: 35
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcreatebrushindirect/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfObjectCreationRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfobjectcreationrecordtype)
```
public final class EmfCreateBrushIndirect extends EmfObjectCreationRecordType
```

Запись EMR\_CREATEBRUSHINDIRECT определяет логическую кисть для графических операций.

Объект логической кисти, определенный этой записью, может быть выбран в контекст устройства воспроизведения с помощью записи EMR\_SELECTOBJECT (раздел 2.3.8.5), которая указывает логическую кисть для последующих графических операций.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCreateBrushIndirect(EmfRecord source)](#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCreateBrushIndirect`. |
| [EmfCreateBrushIndirect()](#EmfCreateBrushIndirect--) | Инициализирует новый экземпляр класса `EmfCreateBrushIndirect`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getIhBrush()](#getIhBrush--) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс объекта логической кисти в таблице объектов EMF (раздел 3.1.1.1). |
| [setIhBrush(int value)](#setIhBrush-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает индекс объекта логической кисти в таблице объектов EMF (раздел 3.1.1.1). |
| [getLogBrush()](#getLogBrush--) | Получает или задает объект LogBrushEx (раздел 2.2.12), который определяет стиль, цвет и узор логической кисти. |
| [setLogBrush(EmfLogBrushEx value)](#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-) | Получает или задает объект LogBrushEx (раздел 2.2.12), который определяет стиль, цвет и узор логической кисти. |
### EmfCreateBrushIndirect(EmfRecord source) {#EmfCreateBrushIndirect-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCreateBrushIndirect(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCreateBrushIndirect`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfCreateBrushIndirect() {#EmfCreateBrushIndirect--}
```
public EmfCreateBrushIndirect()
```


Инициализирует новый экземпляр класса `EmfCreateBrushIndirect`.

### getIhBrush() {#getIhBrush--}
```
public int getIhBrush()
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс объекта логической кисти в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранен, чтобы объект можно было повторно использовать или изменить.

**Returns:**
int
### setIhBrush(int value) {#setIhBrush-int-}
```
public void setIhBrush(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает индекс объекта логической кисти в таблице объектов EMF (раздел 3.1.1.1). Этот индекс ДОЛЖЕН быть сохранен, чтобы объект можно было повторно использовать или изменить.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getLogBrush() {#getLogBrush--}
```
public EmfLogBrushEx getLogBrush()
```


Получает или задает объект LogBrushEx (раздел 2.2.12), который определяет стиль, цвет и узор логической кисти. Поле BrushStyle в этом объекте ДОЛЖНО быть BS\_SOLID, BS\_HATCHED или BS\_NULL.

**Returns:**
[EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex)
### setLogBrush(EmfLogBrushEx value) {#setLogBrush-com.aspose.imaging.fileformats.emf.emf.objects.EmfLogBrushEx-}
```
public void setLogBrush(EmfLogBrushEx value)
```


Получает или задает объект LogBrushEx (раздел 2.2.12), который определяет стиль, цвет и узор логической кисти. Поле BrushStyle в этом объекте ДОЛЖНО быть BS\_SOLID, BS\_HATCHED или BS\_NULL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfLogBrushEx](../../com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex) |  |

