---
title: "EmfGlsRecord"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_GLSRECORD определяет функцию OpenGL."
type: docs
weight: 64
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfglsrecord/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfOpenGlRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfopenglrecordtype)
```
public final class EmfGlsRecord extends EmfOpenGlRecordType
```

Запись EMR\_GLSRECORD определяет функцию OpenGL.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfGlsRecord(EmfRecord source)](#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfGlsRecord`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getCbData()](#getCbData--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [setCbData(int value)](#setCbData-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. |
| [getData()](#getData--) | Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL. |
| [setData(byte[] value)](#setData-byte---) | Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL. |
### EmfGlsRecord(EmfRecord source) {#EmfGlsRecord-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGlsRecord(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfGlsRecord`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getCbData() {#getCbData--}
```
public int getCbData()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. Если это значение равно нулю, к этой записи не прикрепляются данные.

**Returns:**
int
### setCbData(int value) {#setCbData-int-}
```
public void setCbData(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер, в байтах, поля Data. Если это значение равно нулю, к этой записи не прикрепляются данные.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getData() {#getData--}
```
public byte[] getData()
```


Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL.

**Returns:**
byte[]
### setData(byte[] value) {#setData-byte---}
```
public void setData(byte[] value)
```


Получает или задает необязательный массив байтов длиной cbData, который указывает данные для функции OpenGL.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

