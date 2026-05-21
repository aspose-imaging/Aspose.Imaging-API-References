---
title: "EmfCommentBeginGroup"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Запись EMR_COMMENT_BEGINGROUP указывает начало группы записей рисования."
type: docs
weight: 26
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentbegingroup/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype), [com.aspose.imaging.fileformats.emf.emf.records.EmfCommentPublicRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfcommentpublicrecordtype)
```
public final class EmfCommentBeginGroup extends EmfCommentPublicRecordType
```

Запись EMR\_COMMENT\_BEGINGROUP определяет начало группы записей рисования.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfCommentBeginGroup(EmfRecord source)](#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Инициализирует новый экземпляр класса `EmfCommentBeginGroup`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getRectangle()](#getRectangle--) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который указывает выходной прямоугольник в логических координатах. |
| [setRectangle(Rectangle value)](#setRectangle-com.aspose.imaging.Rectangle-) | Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который указывает выходной прямоугольник в логических координатах. |
| [getNDescription()](#getNDescription--) | Получает или задает количество символов Unicode в последующей необязательной строке описания. |
| [setNDescription(int value)](#setNDescription-int-) | Получает или задает количество символов Unicode в последующей необязательной строке описания. |
| [getDescription()](#getDescription--) | Получает или задает необязательную нуль-терминированную строку Unicode, описывающую эту группу записей. |
| [setDescription(String value)](#setDescription-java.lang.String-) | Получает или задает необязательную нуль-терминированную строку Unicode, описывающую эту группу записей. |
### EmfCommentBeginGroup(EmfRecord source) {#EmfCommentBeginGroup-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfCommentBeginGroup(EmfRecord source)
```


Инициализирует новый экземпляр класса `EmfCommentBeginGroup`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Источник. |

### getRectangle() {#getRectangle--}
```
public Rectangle getRectangle()
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который указывает выходной прямоугольник в логических координатах.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setRectangle(Rectangle value) {#setRectangle-com.aspose.imaging.Rectangle-}
```
public void setRectangle(Rectangle value)
```


Получает или задает объект WMF RectL ([MS-WMF] раздел 2.2.2.19), который указывает выходной прямоугольник в логических координатах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNDescription() {#getNDescription--}
```
public int getNDescription()
```


Получает или задает количество символов Unicode в последующей необязательной строке описания.

**Returns:**
int
### setNDescription(int value) {#setNDescription-int-}
```
public void setNDescription(int value)
```


Получает или задает количество символов Unicode в последующей необязательной строке описания.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getDescription() {#getDescription--}
```
public String getDescription()
```


Получает или задает необязательную нуль-терминированную строку Unicode, описывающую эту группу записей.

**Returns:**
java.lang.String
### setDescription(String value) {#setDescription-java.lang.String-}
```
public void setDescription(String value)
```


Получает или задает необязательную нуль-терминированную строку Unicode, описывающую эту группу записей.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | java.lang.String |  |

