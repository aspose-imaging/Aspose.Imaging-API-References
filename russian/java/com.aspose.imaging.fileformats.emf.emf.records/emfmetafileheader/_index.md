---
title: "EmfMetafileHeader"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Типы записей EMR_HEADER определяют начальные точки EMF‑метафайлов и задают свойства устройства, на котором было создано изображение в метафайле."
type: docs
weight: 70
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public class EmfMetafileHeader extends EmfRecord
```

Записи EMR\_HEADER определяют начальные точки EMF‑метафайлов и задают свойства устройства, на котором было создано изображение в метафайле. Информация в заголовочной записи делает возможным независимость EMF‑метафайлов от конкретного выходного устройства. Значение поля Size может использоваться для различения разных типов записей EMR\_HEADER, перечисленных ранее в этом разделе. Существует три возможных заголовка: базовый заголовок, который представляет собой запись EmfMetafileHeader. Фиксированная часть этого заголовка составляет 88 байт и содержит объект Header. Первый расширенный заголовок, который представляет собой запись EmfMetafileHeaderExtension1. Фиксированная часть этого заголовка составляет 100 байт и содержит объект Header и объект HeaderExtension1 (раздел 2.2.10). Второй расширенный заголовок, который представляет собой запись EmfMetafileHeaderExtension2. Фиксированная часть этого заголовка составляет 108 байт и содержит объект Header, объект HeaderExtension1 и объект HeaderExtension2 (раздел 2.2.11).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfMetafileHeader(EmfRecord record)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfMetafileHeader`. |
| [EmfMetafileHeader()](#EmfMetafileHeader--) | Инициализирует новый экземпляр класса `EmfMetafileHeader`. |
| [EmfMetafileHeader(EmfMetafileHeader header)](#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-) | Инициализирует новый экземпляр класса `EmfMetafileHeader`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getEmfHeader()](#getEmfHeader--) | Получает объект Header (раздел 2.2.9), который содержит информацию о содержимом и структуре метафайла |
| [setEmfHeader(EmfHeaderObject value)](#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-) | Устанавливает объект Header (раздел 2.2.9), который содержит информацию о содержимом и структуре метафайла |
| [getEmfHeaderRecordBuffer()](#getEmfHeaderRecordBuffer--) | Получает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. |
| [setEmfHeaderRecordBuffer(byte[] value)](#setEmfHeaderRecordBuffer-byte---) | Устанавливает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. |
| [getEmfDescriptionBuffer()](#getEmfDescriptionBuffer--) | Получает буфер описания EMF. Необязательный массив байтов, содержащий строку описания EMF, которая не обязана быть смежной с фиксированной частью записи EmfMetafileHeader. |
| [setEmfDescriptionBuffer(byte[] value)](#setEmfDescriptionBuffer-byte---) | Устанавливает буфер описания EMF. Необязательный массив байтов, содержащий строку описания EMF, которая не обязана быть смежной с фиксированной частью записи EmfMetafileHeader. |
| [getEmfDescription()](#getEmfDescription--) | Получает описание EMF. Необязательная нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. |
| [setEmfDescription(String value)](#setEmfDescription-java.lang.String-) | Устанавливает описание EMF. Необязательная нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. |
### EmfMetafileHeader(EmfRecord record) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfMetafileHeader(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfMetafileHeader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfMetafileHeader() {#EmfMetafileHeader--}
```
public EmfMetafileHeader()
```


Инициализирует новый экземпляр класса `EmfMetafileHeader`.

### EmfMetafileHeader(EmfMetafileHeader header) {#EmfMetafileHeader-com.aspose.imaging.fileformats.emf.emf.records.EmfMetafileHeader-}
```
public EmfMetafileHeader(EmfMetafileHeader header)
```


Инициализирует новый экземпляр класса `EmfMetafileHeader`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| header | [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) | Заголовок. |

### getEmfHeader() {#getEmfHeader--}
```
public EmfHeaderObject getEmfHeader()
```


Получает объект Header (раздел 2.2.9), который содержит информацию о содержимом и структуре метафайла

**Returns:**
[EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
### setEmfHeader(EmfHeaderObject value) {#setEmfHeader-com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject-}
```
public void setEmfHeader(EmfHeaderObject value)
```


Устанавливает объект Header (раздел 2.2.9), который содержит информацию о содержимом и структуре метафайла

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject) |  |

### getEmfHeaderRecordBuffer() {#getEmfHeaderRecordBuffer--}
```
public byte[] getEmfHeaderRecordBuffer()
```


Получает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. Размер этого поля ДОЛЖЕН быть кратным 4 байтам.

**Returns:**
byte[]
### setEmfHeaderRecordBuffer(byte[] value) {#setEmfHeaderRecordBuffer-byte---}
```
public void setEmfHeaderRecordBuffer(byte[] value)
```


Устанавливает необязательный массив байтов, содержащий оставшуюся часть записи заголовка EMF. Размер этого поля ДОЛЖЕН быть кратным 4 байтам.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescriptionBuffer() {#getEmfDescriptionBuffer--}
```
public byte[] getEmfDescriptionBuffer()
```


Получает буфер описания EMF. Необязательный массив байтов, содержащий строку описания EMF, которая не обязана быть смежной с фиксированной частью записи EmfMetafileHeader. Соответственно, поле в этом буфере с меткой "UndefinedSpace" является необязательным и ДОЛЖНО игнорироваться.

**Returns:**
byte[]
### setEmfDescriptionBuffer(byte[] value) {#setEmfDescriptionBuffer-byte---}
```
public void setEmfDescriptionBuffer(byte[] value)
```


Устанавливает буфер описания EMF. Необязательный массив байтов, содержащий строку описания EMF, которая не обязана быть смежной с фиксированной частью записи EmfMetafileHeader. Соответственно, поле в этом буфере с меткой "UndefinedSpace" является необязательным и ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getEmfDescription() {#getEmfDescription--}
```
public String getEmfDescription()
```


Получает описание EMF. Необязательная нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. Ее расположение в записи и количество символов задаются полями offDescription и nDescription соответственно в EmfHeader. Если значение любого из этих полей равно нулю, строка описания отсутствует.

**Returns:**
java.lang.String
### setEmfDescription(String value) {#setEmfDescription-java.lang.String-}
```
public void setEmfDescription(String value)
```


Устанавливает описание EMF. Необязательная нуль-терминированная строка Unicode UTF16-LE произвольной длины и содержания. Ее расположение в записи и количество символов задаются полями offDescription и nDescription соответственно в EmfHeader. Если значение любого из этих полей равно нулю, строка описания отсутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

