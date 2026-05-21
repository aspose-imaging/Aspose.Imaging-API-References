---
title: "EmfComment"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT содержит произвольные закрытые данные."
type: docs
weight: 25
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcomment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype)
```
public final class EmfComment extends EmfCommentRecordType
```

Запись EMR\_COMMENT содержит произвольные закрытые данные. Примечание: поля, не описанные в этом разделе, указаны в разделе 2.3.3.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfComment(EmfRecord source)](#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfComment`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getPrivateData()](#getPrivateData--) | Получает или задает необязательный массив байтов, определяющий закрытые данные. |
| [setPrivateData(byte[] value)](#setPrivateData-byte---) | Получает или задает необязательный массив байтов, определяющий закрытые данные. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает идентификатор комментария. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает идентификатор комментария. |
### EmfComment(EmfRecord source) {#EmfComment-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfComment(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfComment`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getPrivateData() {#getPrivateData--}
```
public byte[] getPrivateData()
```


Получает или задает необязательный массив байтов, определяющий закрытые данные. Первый DWORD этих данных НЕ ДОЛЖЕН быть одним из предопределенных значений идентификатора комментария, указанных в разделе 2.3.3. Закрытые данные неизвестны EMF; они имеют смысл только для приложений, которые знают формат данных и как их использовать. Записи закрытых данных EMR\_COMMENT МОГУТ игнорироваться.

**Returns:**
byte[]
### setPrivateData(byte[] value) {#setPrivateData-byte---}
```
public void setPrivateData(byte[] value)
```


Получает или задает необязательный массив байтов, определяющий закрытые данные. Первый DWORD этих данных НЕ ДОЛЖЕН быть одним из предопределенных значений идентификатора комментария, указанных в разделе 2.3.3. Закрытые данные неизвестны EMF; они имеют смысл только для приложений, которые знают формат данных и как их использовать. Записи закрытых данных EMR\_COMMENT МОГУТ игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte[] |  |

### getCommentIdentifier() {#getCommentIdentifier--}
```
public int getCommentIdentifier()
```


Получает или задает идентификатор комментария.

Значение: идентификатор комментария.

**Returns:**
int
### setCommentIdentifier(int value) {#setCommentIdentifier-int-}
```
public void setCommentIdentifier(int value)
```


Получает или задает идентификатор комментария.

Значение: идентификатор комментария.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

