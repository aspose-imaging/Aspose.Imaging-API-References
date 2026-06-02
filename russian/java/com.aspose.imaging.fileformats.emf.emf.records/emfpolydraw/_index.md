---
title: "EmfPolyDraw"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYDRAW определяет набор отрезков линий и кривых Безье."
type: docs
weight: 89
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw extends EmfPolyShape
```

Запись EMR_POLYDRAW задаёт набор отрезков линий и кривых Безье.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyDraw(EmfRecord source)](#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyDraw`. |
| [EmfPolyDraw()](#EmfPolyDraw--) | Инициализирует новый экземпляр класса [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw). |
## Методы

| Метод | Описание |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Получает массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Задает массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints. |
### EmfPolyDraw(EmfRecord source) {#EmfPolyDraw-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolyDraw`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfPolyDraw() {#EmfPolyDraw--}
```
public EmfPolyDraw()
```


Инициализирует новый экземпляр класса [EmfPolyDraw](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw).

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Получает массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints. Это значение ДОЛЖНО принадлежать перечислению Point (section 2.1.26).

**Returns:**
byte[] — массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints.
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Задает массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints. Это значение ДОЛЖНО принадлежать перечислению Point (section 2.1.26).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] | массив длиной Count из байтов, который указывает, как используется каждая точка в массиве aPoints. |

