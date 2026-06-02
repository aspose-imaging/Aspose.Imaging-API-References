---
title: "EmfPlusClear"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusClear очищает выходное координатное пространство и инициализирует его фоновым цветом и прозрачностью."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusclear/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawingrecordtype)
```
public final class EmfPlusClear extends EmfPlusDrawingRecordType
```

Запись EmfPlusClear очищает выходное координатное пространство и инициализирует его фоновым цветом и прозрачностью.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusClear(EmfPlusRecord source)](#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusClear`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getArgb32Color()](#getArgb32Color--) | Получает или задает цвет. |
| [setArgb32Color(int value)](#setArgb32Color-int-) | Получает или задает цвет. |
### EmfPlusClear(EmfPlusRecord source) {#EmfPlusClear-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusClear(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusClear`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getArgb32Color() {#getArgb32Color--}
```
public int getArgb32Color()
```


Получает или задает цвет. Объект EmfPlusARGB (раздел 2.2.2.1), определяющий цвет для закраски экрана. Все цвета указаны в [IEC-RGB], если не указано иное.

Значение: Цвет.

**Returns:**
int
### setArgb32Color(int value) {#setArgb32Color-int-}
```
public void setArgb32Color(int value)
```


Получает или задает цвет. Объект EmfPlusARGB (раздел 2.2.2.1), определяющий цвет для закраски экрана. Все цвета указаны в [IEC-RGB], если не указано иное.

Значение: Цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

