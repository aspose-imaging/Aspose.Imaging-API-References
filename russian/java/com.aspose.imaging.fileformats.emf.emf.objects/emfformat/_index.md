---
title: "EmfFormat"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmrFormat содержит информацию, которая идентифицирует формат данных изображения в записи EMR_COMMENT_MULTIFORMATS раздел 2.3.3.4.3."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfFormat extends EmfObject
```

Объект EmrFormat содержит информацию, определяющую формат данных изображения в записи EMR\_COMMENT\_MULTIFORMATS (раздел 2.3.3.4.3).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfFormat()](#EmfFormat--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getSignature()](#getSignature--) | Получает или задает 32-битное беззнаковое целое, которое указывает формат данных изображения. |
| [setSignature(int value)](#setSignature-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает формат данных изображения. |
| [getVersion()](#getVersion--) | Получает или задает 32-битное беззнаковое целое, которое указывает номер версии формата. |
| [setVersion(int value)](#setVersion-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает номер версии формата. |
| [getSizeData()](#getSizeData--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер данных в байтах. |
| [setSizeData(int value)](#setSizeData-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер данных в байтах. |
| [getOffData()](#getOffData--) | Получает или задает 32-битное беззнаковое целое, которое указывает смещение данных от начала поля идентификатора в записи EMR\_COMMENT\_PUBLIC (раздел 2.3.3.4). |
| [setOffData(int value)](#setOffData-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает смещение данных от начала поля идентификатора в записи EMR\_COMMENT\_PUBLIC (раздел 2.3.3.4). |
### EmfFormat() {#EmfFormat--}
```
public EmfFormat()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Получает или задает 32-битное беззнаковое целое, которое указывает формат данных изображения. Это значение ДОЛЖНО находиться в перечислении FormatSignature (раздел 2.1.14).

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает формат данных изображения. Это значение ДОЛЖНО находиться в перечислении FormatSignature (раздел 2.1.14).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Получает или задает 32-битное беззнаковое целое, которое указывает номер версии формата. Если поле Signature указывает encapsulated PostScript (EPS), это значение ДОЛЖНО быть 0x00000001; в противном случае это значение ДОЛЖНО игнорироваться.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает номер версии формата. Если поле Signature указывает encapsulated PostScript (EPS), это значение ДОЛЖНО быть 0x00000001; в противном случае это значение ДОЛЖНО игнорироваться.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getSizeData() {#getSizeData--}
```
public int getSizeData()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер данных в байтах.

**Returns:**
int
### setSizeData(int value) {#setSizeData-int-}
```
public void setSizeData(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер данных в байтах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOffData() {#getOffData--}
```
public int getOffData()
```


Получает или задает 32-битное беззнаковое целое, которое указывает смещение данных от начала поля идентификатора в записи EMR\_COMMENT\_PUBLIC (раздел 2.3.3.4). Смещение ДОЛЖНО быть выровнено по 32-битной границе.

**Returns:**
int
### setOffData(int value) {#setOffData-int-}
```
public void setOffData(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает смещение данных от начала поля идентификатора в записи EMR\_COMMENT\_PUBLIC (раздел 2.3.3.4). Смещение ДОЛЖНО быть выровнено по 32-битной границе.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

