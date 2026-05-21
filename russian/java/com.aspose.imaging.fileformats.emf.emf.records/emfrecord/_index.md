---
title: "EmfRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый класс для записей EMF. Все записи EMF ДОЛЖНЫ иметь длину, кратную 4 байтам."
type: docs
weight: 106
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfRecord extends MetaObject implements IRecord
```

Базовый класс для записей EMF. Все записи EMF ДОЛЖНЫ иметь длину, кратную 4 байтам. Это отображено в общих структурах предыдущих типов записей EMF путем включения полей AlignmentPadding там, где это уместно, в конце этих структур. Содержимое полей AlignmentPadding ДОЛЖНО всегда игнорироваться. Для краткости эти поля не показаны в определении каждой отдельной записи EMF.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfRecord()](#EmfRecord--) | Инициализирует новый экземпляр класса `EmfRecord`. |
| [EmfRecord(EmfRecord source)](#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfRecord`. |
| [EmfRecord(int type)](#EmfRecord-int-) | Инициализирует новый экземпляр класса `EmfRecord`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Получает тип. |
| [setType(int value)](#setType-int-) | Устанавливает тип. |
| [getSize()](#getSize--) | Получает размер записи |
| [setSize(int value)](#setSize-int-) | Задает размер записи |
### EmfRecord() {#EmfRecord--}
```
public EmfRecord()
```


Инициализирует новый экземпляр класса `EmfRecord`.

### EmfRecord(EmfRecord source) {#EmfRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfRecord(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfRecord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### EmfRecord(int type) {#EmfRecord-int-}
```
public EmfRecord(int type)
```


Инициализирует новый экземпляр класса `EmfRecord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| тип | int | Тип записи. |

### getType() {#getType--}
```
public int getType()
```


Получает тип.

**Returns:**
int — тип.
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Устанавливает тип.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Тип. |

### getSize() {#getSize--}
```
public int getSize()
```


Получает размер записи

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Задает размер записи

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

