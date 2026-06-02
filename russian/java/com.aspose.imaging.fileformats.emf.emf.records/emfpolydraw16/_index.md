---
title: "EmfPolyDraw16"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_POLYDRAW16 определяет набор отрезков линий и кривых Безье."
type: docs
weight: 90
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfpolydraw16/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfBoundedRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfboundedrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfPolyShape](../../com.aspose.imaging.fileformats.emf.emf.records/emfpolyshape)
```
public final class EmfPolyDraw16 extends EmfPolyShape
```

Запись EMR_POLYDRAW16 задаёт набор отрезков линий и кривых Безье.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPolyDraw16(EmfRecord source)](#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfPolyDraw16`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getAbTypes()](#getAbTypes--) | Получает или задает массив длиной Count из байтов, который определяет типы точек. |
| [setAbTypes(byte[] value)](#setAbTypes-byte---) | Устанавливает массив байтов длиной Count, который определяет типы точек. |
### EmfPolyDraw16(EmfRecord source) {#EmfPolyDraw16-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfPolyDraw16(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfPolyDraw16`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getAbTypes() {#getAbTypes--}
```
public byte[] getAbTypes()
```


Получает или задает массив байтов длиной Count, который определяет типы точек. Это значение MUST быть в перечислении Point (section 2.1.26).

**Returns:**
byte[]
### setAbTypes(byte[] value) {#setAbTypes-byte---}
```
public void setAbTypes(byte[] value)
```


Устанавливает массив байтов длиной Count, который определяет типы точек. Это значение MUST быть в перечислении Point (section 2.1.26).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] | массив байтов длиной Count, который определяет типы точек. |

