---
title: "EmfNamedEscape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись MR_NAMEDESCAPE передаёт произвольную информацию указанному драйверу принтера."
type: docs
weight: 75
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfnamedescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfNamedEscape extends EmfEscapeRecordType
```

Запись MR\_NAMEDESCAPE передаёт произвольную информацию указанному драйверу принтера.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfNamedEscape(EmfRecord source)](#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfNamedEscape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCjDriver()](#getCjDriver--) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт в поле DriverName. |
| [setCjDriver(int value)](#setCjDriver-int-) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт в поле DriverName. |
| [getCjIn()](#getCjIn--) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт для передачи драйверу принтера. |
| [setCjIn(int value)](#setCjIn-int-) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт для передачи драйверу принтера. |
| [getDriverName()](#getDriverName--) | Получает или задаёт строку из 16‑битных символов Unicode, указывающую имя драйвера принтера, который получит данные. |
| [setDriverName(String value)](#setDriverName-java.lang.String-) | Получает или задаёт строку из 16‑битных символов Unicode, указывающую имя драйвера принтера, который получит данные. |
| [getData()](#getData--) | Получает или задаёт данные для передачи драйверу принтера. |
| [setData(byte[] value)](#setData-byte---) | Получает или задаёт данные для передачи драйверу принтера. |
### EmfNamedEscape(EmfRecord source) {#EmfNamedEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfNamedEscape(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfNamedEscape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getCjDriver() {#getCjDriver--}
```
public int getCjDriver()
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт в поле DriverName. Это значение ДОЛЖНО быть чётным.

**Returns:**
int
### setCjDriver(int value) {#setCjDriver-int-}
```
public void setCjDriver(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт в поле DriverName. Это значение ДОЛЖНО быть чётным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт для передачи драйверу принтера.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байт для передачи драйверу принтера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDriverName() {#getDriverName--}
```
public String getDriverName()
```


Получает или задаёт строку из 16‑битных символов Unicode, указывающую имя драйвера принтера, который получит данные. Эта строка ДОЛЖНА иметь длину cjDriver байт и ДОЛЖНА завершаться нулевым символом.

**Returns:**
java.lang.String
### setDriverName(String value) {#setDriverName-java.lang.String-}
```
public void setDriverName(String value)
```


Получает или задаёт строку из 16‑битных символов Unicode, указывающую имя драйвера принтера, который получит данные. Эта строка ДОЛЖНА иметь длину cjDriver байт и ДОЛЖНА завершаться нулевым символом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задаёт данные для передачи драйверу принтера. ДОЛЖНО быть доступно cjIn байт.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задаёт данные для передачи драйверу принтера. ДОЛЖНО быть доступно cjIn байт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

