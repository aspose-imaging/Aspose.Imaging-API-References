---
title: "EmfExtEscape"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EXTESCAPE передаёт произвольную информацию драйверу принтера."
type: docs
weight: 53
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfextescape/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfEscapeRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfescaperecordtype)
```
public final class EmfExtEscape extends EmfEscapeRecordType
```

Запись EMR\_EXTESCAPE передаёт произвольную информацию драйверу принтера. Предполагается, что эта информация не приведёт к выполнению рисования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfExtEscape(EmfRecord source)](#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfExtEscape`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCjIn()](#getCjIn--) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера. |
| [setCjIn(int value)](#setCjIn-int-) | Получает или задаёт 32‑битное беззнаковое целое, указывающее количество байтов для передачи драйверу принтера. |
| [getData()](#getData--) | Получает или задаёт данные для передачи драйверу принтера. |
| [setData(byte[] value)](#setData-byte---) | Получает или задаёт данные для передачи драйверу принтера. |
### EmfExtEscape(EmfRecord source) {#EmfExtEscape-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfExtEscape(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfExtEscape`.

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

