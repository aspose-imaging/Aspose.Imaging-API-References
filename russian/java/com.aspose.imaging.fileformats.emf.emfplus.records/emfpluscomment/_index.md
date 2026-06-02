---
title: "EmfPlusComment"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EmfPlusComment задает произвольные закрытые данные."
type: docs
weight: 14
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.records/emfpluscomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord)
```
public final class EmfPlusComment extends EmfPlusRecord
```

Запись EmfPlusComment задает произвольные закрытые данные.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusComment(EmfPlusRecord source)](#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-) | Инициализирует новый экземпляр класса `EmfPlusComment`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Получает или задает байтовый массив длиной DataSize, содержащий приватные данные. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Получает или задает байтовый массив длиной DataSize, содержащий приватные данные. |
| [getFlags()](#getFlags--) | Получает или задает 16-битное беззнаковое целое, которое не используется. |
| [setFlags(short value)](#setFlags-short-) | Получает или задает 16-битное беззнаковое целое, которое не используется. |
### EmfPlusComment(EmfPlusRecord source) {#EmfPlusComment-com.aspose.imaging.fileformats.emf.emfplus.records.EmfPlusRecord-}
```
public EmfPlusComment(EmfPlusRecord source)
```


Инициализирует новый экземпляр класса `EmfPlusComment`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfPlusRecord](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord) | Источник. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Получает или задает байтовый массив длиной DataSize, содержащий приватные данные. Байты данных, специфичных для записи, которые следуют.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Получает или задает байтовый массив длиной DataSize, содержащий приватные данные. Байты данных, специфичных для записи, которые следуют.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getFlags() {#getFlags--}
```
public short getFlags()
```


Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться при получении.

**Returns:**
short
### setFlags(short value) {#setFlags-short-}
```
public void setFlags(short value)
```


Получает или задает 16-битное беззнаковое целое, которое не используется. Это поле ДОЛЖНО быть установлено в ноль и ДОЛЖНО игнорироваться при получении.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short |  |

