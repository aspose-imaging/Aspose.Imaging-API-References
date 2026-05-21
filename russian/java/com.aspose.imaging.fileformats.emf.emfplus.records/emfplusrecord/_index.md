---
title: "EmfPlusRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Базовый тип записи Emf."
type: docs
weight: 46
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)

**All Implemented Interfaces:**
com.aspose.internal.fileformats.emf.IRecord
```
public class EmfPlusRecord extends MetaObject implements IRecord
```

Базовый тип записи Emf+.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusRecord()](#EmfPlusRecord--) | Инициализирует новый экземпляр класса `EmfPlusRecord`. |
| [EmfPlusRecord(EmfPlusRecord source)](#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusRecord`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getType()](#getType--) | Получает 16‑битное беззнаковое целое, идентифицирующее тип записи. |
| [getFlags()](#getFlags--) | Получает 16‑битное беззнаковое целое, содержащее информацию для некоторых записей о том, как должна выполняться операция и о структуре записи. |
| [setFlags(short value)](#setFlags-short-) | Задаёт 16‑битное беззнаковое целое, содержащее информацию для некоторых записей о том, как должна выполняться операция и о структуре записи. |
| [getSize()](#getSize--) | Получает 32‑битное беззнаковое целое, определяющее количество байтов, выровненных по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| [setSize(int value)](#setSize-int-) | Задаёт 32‑битное беззнаковое целое, определяющее количество байтов, выровненных по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи. |
| [getDataSize()](#getDataSize--) | Получает 32‑битное беззнаковое целое, которое ДОЛЖНО определять 32‑бит\\u2013aligned количество байтов данных в следующем поле RecordData. |
| [setDataSize(int value)](#setDataSize-int-) | Задаёт 32‑битное беззнаковое целое, которое ДОЛЖНО определять 32‑бит\\u2013aligned количество байтов данных в следующем поле RecordData. |
### EmfPlusRecord() {#EmfPlusRecord--}
```
public EmfPlusRecord()
```


Инициализирует новый экземпляр класса `EmfPlusRecord`.

### EmfPlusRecord(EmfPlusRecord source) {#EmfPlusRecord-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusRecord(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusRecord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getType() {#getType--}
```
public short getType()
```


Получает 16‑битное беззнаковое целое, идентифицирующее тип записи.

**Returns:**
short
### getFlags() {#getFlags--}
```
public short getFlags()
```


Получает 16‑битное беззнаковое целое, содержащее информацию для некоторых записей о том, как должна выполняться операция и о структуре записи.

**Returns:**
short - Флаги.
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Задаёт 16‑битное беззнаковое целое, содержащее информацию для некоторых записей о том, как должна выполняться операция и о структуре записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Флаги. |

### getSize() {#getSize--}
```
public int getSize()
```


Получает 32‑битное беззнаковое целое, определяющее количество байтов, выровненных по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи.

**Returns:**
int - Размер.
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Задаёт 32‑битное беззнаковое целое, определяющее количество байтов, выровненных по 32‑битам, во всей записи, включая 12‑байтовый заголовок записи и данные, специфичные для записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Размер. |

### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Получает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битное\u2013выравненное количество байт данных в поле RecordData, следующее за ним. Это число не включает 12-байтовый заголовок записи.

**Returns:**
int - Размер данных.
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Устанавливает 32-битное беззнаковое целое, которое ДОЛЖНО определять 32-битное\u2013выравненное количество байт данных в поле RecordData, следующее за ним. Это число не включает 12-байтовый заголовок записи.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Размер данных. |

