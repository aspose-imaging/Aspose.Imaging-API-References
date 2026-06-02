---
title: "EmfHeaderExtension1"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект HeaderExtension1 определяет первое расширение заголовка метафайла EMF."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfHeaderObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfheaderobject)
```
public final class EmfHeaderExtension1 extends EmfHeaderObject
```

Объект HeaderExtension1 определяет первое расширение заголовка метафайла EMF. Он добавляет поддержку объекта PixelFormatDescriptor (раздел 2.2.22) и записей OpenGL [OPENGL] (раздел 2.3.9).
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getCbPixelFormat()](#getCbPixelFormat--) | Получает или задает 32-битное беззнаковое целое, которое указывает размер объекта PixelFormatDescriptor. |
| [setCbPixelFormat(int value)](#setCbPixelFormat-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает размер объекта PixelFormatDescriptor. |
| [getOffPixelFormat()](#getOffPixelFormat--) | Получает или задает 32-битное беззнаковое целое, которое указывает смещение к объекту PixelFormatDescriptor. |
| [setOffPixelFormat(int value)](#setOffPixelFormat-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает смещение к объекту PixelFormatDescriptor. |
| [getBOpenGl()](#getBOpenGl--) | Получает или задает 32-битное беззнаковое целое, которое указывает, присутствуют ли команды OpenGL в метафайле. |
| [setBOpenGl(int value)](#setBOpenGl-int-) | Получает или задает 32-битное беззнаковое целое, которое указывает, присутствуют ли команды OpenGL в метафайле. |
### EmfHeaderExtension1() {#EmfHeaderExtension1--}
```
public EmfHeaderExtension1()
```


### getCbPixelFormat() {#getCbPixelFormat--}
```
public int getCbPixelFormat()
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер объекта PixelFormatDescriptor. Это ДОЛЖНО быть 0x00000000, если формат пикселей не установлен.

**Returns:**
int
### setCbPixelFormat(int value) {#setCbPixelFormat-int-}
```
public void setCbPixelFormat(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает размер объекта PixelFormatDescriptor. Это ДОЛЖНО быть 0x00000000, если формат пикселей не установлен.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getOffPixelFormat() {#getOffPixelFormat--}
```
public int getOffPixelFormat()
```


Получает или задает 32-битное беззнаковое целое, которое указывает смещение к объекту PixelFormatDescriptor. Это ДОЛЖНО быть 0x00000000, если формат пикселей не установлен.

**Returns:**
int
### setOffPixelFormat(int value) {#setOffPixelFormat-int-}
```
public void setOffPixelFormat(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает смещение к объекту PixelFormatDescriptor. Это ДОЛЖНО быть 0x00000000, если формат пикселей не установлен.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getBOpenGl() {#getBOpenGl--}
```
public int getBOpenGl()
```


Получает или задает 32-битное беззнаковое целое, которое указывает, присутствуют ли команды OpenGL в метафайле. 0x00000000 записи OpenGL отсутствуют в метафайле. 0x00000001 записи OpenGL присутствуют в метафайле.

**Returns:**
int
### setBOpenGl(int value) {#setBOpenGl-int-}
```
public void setBOpenGl(int value)
```


Получает или задает 32-битное беззнаковое целое, которое указывает, присутствуют ли команды OpenGL в метафайле. 0x00000000 записи OpenGL отсутствуют в метафайле. 0x00000001 записи OpenGL присутствуют в метафайле.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

