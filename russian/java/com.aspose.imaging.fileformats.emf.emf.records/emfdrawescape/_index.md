---
title: "EmfDrawEscape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_DRAWESCAPE передает произвольную информацию драйверу принтера."
type: docs
weight: 44
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfdrawescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfDrawEscape extends EmfEscapeRecordType
```

Запись EMR\_DRAWESCAPE передаёт произвольную информацию драйверу принтера. Предполагается, что эта информация приведёт к выполнению рисования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfDrawEscape(EmfRecord source)](#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfDrawEscape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCjIn()](#getCjIn--) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера. |
| [setCjIn(int value)](#setCjIn-int-) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера. |
| [getData()](#getData--) | Получает или задаёт данные для передачи драйверу принтера. |
| [setData(byte[] value)](#setData-byte---) | Получает или задаёт данные для передачи драйверу принтера. |
### EmfDrawEscape(EmfRecord source) {#EmfDrawEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfDrawEscape(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfDrawEscape`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getCjIn() {#getCjIn--}
```
public int getCjIn()
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера.

**Returns:**
int
### setCjIn(int value) {#setCjIn-int-}
```
public void setCjIn(int value)
```


Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задаёт данные для передачи драйверу принтера. Должно быть доступно cjIn байт.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задаёт данные для передачи драйверу принтера. Должно быть доступно cjIn байт.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

