---
title: "EmfEof"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_EOF указывает конец метафайла и задаёт палитру."
type: docs
weight: 48
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfeof/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfControlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcontrolrecordtype)
```
public final class EmfEof extends EmfControlRecordType
```

Запись EMR\_EOF указывает конец метафайла и определяет палитру.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfEof(EmfRecord record)](#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfEof`. |
| [EmfEof()](#EmfEof--) | Инициализирует новый экземпляр класса `EmfEof`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPaletteArgb32Entries()](#getPaletteArgb32Entries--) | Получает необязательный буфер, содержащий данные палитры, который не обязан быть смежным с фиксированной частью записи EMR\_EOF. |
| [setPaletteArgb32Entries(int[] value)](#setPaletteArgb32Entries-int---) | Задаёт необязательный буфер, содержащий данные палитры, который не обязан быть смежным с фиксированной частью записи EMR\_EOF. |
| [getSizeLast()](#getSizeLast--) | Получает 32‑битное беззнаковое целое, которое ДОЛЖНО совпадать с Size и ДОЛЖНО быть последним полем записи, а следовательно, и метафайла. |
| [setSizeLast(int value)](#setSizeLast-int-) | Задаёт 32‑битное беззнаковое целое, которое ДОЛЖНО совпадать с Size и ДОЛЖНО быть последним полем записи, а следовательно, и метафайла. |
### EmfEof(EmfRecord record) {#EmfEof-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfEof(EmfRecord record)
```


Инициализирует новый экземпляр класса `EmfEof`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| record | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Запись. |

### EmfEof() {#EmfEof--}
```
public EmfEof()
```


Инициализирует новый экземпляр класса `EmfEof`.

### getPaletteArgb32Entries() {#getPaletteArgb32Entries--}
```
public int[] getPaletteArgb32Entries()
```


Получает необязательный буфер, содержащий данные палитры, который не обязан быть смежным с фиксированной частью записи EMR\_EOF. Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. Размер этого поля ДОЛЖЕН быть кратным 4 байтам.

**Returns:**
int[]
### setPaletteArgb32Entries(int[] value) {#setPaletteArgb32Entries-int---}
```
public void setPaletteArgb32Entries(int[] value)
```


Задаёт необязательный буфер, содержащий данные палитры, который не обязан быть смежным с фиксированной частью записи EMR\_EOF. Соответственно, поля в этом буфере, помеченные "UndefinedSpace", являются необязательными и ДОЛЖНЫ игнорироваться. Размер этого поля ДОЛЖЕН быть кратным 4 байтам.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int[] |  |

### getSizeLast() {#getSizeLast--}
```
public int getSizeLast()
```


Получает 32‑битное беззнаковое целое, которое ДОЛЖНО совпадать с Size и ДОЛЖНО быть последним полем записи, а следовательно, и метафайла. Объекты LogPaletteEntry, если они существуют, ДОЛЖНЫ предшествовать этому полю.

**Returns:**
int
### setSizeLast(int value) {#setSizeLast-int-}
```
public void setSizeLast(int value)
```


Задаёт 32‑битное беззнаковое целое, которое ДОЛЖНО совпадать с Size и ДОЛЖНО быть последним полем записи, а следовательно, и метафайла. Объекты LogPaletteEntry, если они существуют, ДОЛЖНЫ предшествовать этому полю.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

