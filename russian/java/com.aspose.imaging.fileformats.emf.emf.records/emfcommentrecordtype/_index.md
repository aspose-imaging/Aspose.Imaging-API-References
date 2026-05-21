---
title: "EmfCommentRecordType"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Типы записей комментариев определяют форматы для указания произвольных записей внедрения частных данных в другие форматы метафайлов и добавления новых или специализированных команд."
type: docs
weight: 32
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.records/emfcommentrecordtype/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord)
```
public abstract class EmfCommentRecordType extends EmfRecord
```

Типы записей комментариев определяют форматы для указания произвольных приватных данных, встраивания записей в другие форматы метафайлов и добавления новых или специальных команд.
## Методы

| Метод | Описание |
| --- | --- |
| [getDataSize()](#getDataSize--) | Получает или задает 32-битное беззнаковое целое число, которое определяет размер, в байтах, полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое следует далее. |
| [setDataSize(int value)](#setDataSize-int-) | Получает или задает 32-битное беззнаковое целое число, которое определяет размер, в байтах, полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое следует далее. |
| [getCommentIdentifier()](#getCommentIdentifier--) | Получает или задает идентификатор комментария. |
| [setCommentIdentifier(int value)](#setCommentIdentifier-int-) | Получает или задает идентификатор комментария. |
### getDataSize() {#getDataSize--}
```
public int getDataSize()
```


Получает или задает 32-битное беззнаковое целое число, которое определяет размер, в байтах, полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое следует далее. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если оно присутствует.

**Returns:**
int
### setDataSize(int value) {#setDataSize-int-}
```
public void setDataSize(int value)
```


Получает или задает 32-битное беззнаковое целое число, которое определяет размер, в байтах, полей CommentIdentifier и CommentRecordParm в поле RecordBuffer, которое следует далее. Оно НЕ ДОЛЖНО включать размер самого себя или размер поля AlignmentPadding, если оно присутствует.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

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

