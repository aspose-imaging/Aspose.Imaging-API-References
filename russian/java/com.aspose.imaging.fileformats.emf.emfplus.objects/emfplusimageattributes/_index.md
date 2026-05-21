---
title: "EmfPlusImageAttributes"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Объект EmfPlusImageAttributes определяет, как цвета растрового изображения обрабатываются во время рендеринга."
type: docs
weight: 48
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImageAttributes extends EmfPlusGraphicsObjectType
```

Объект EmfPlusImageAttributes определяет, как цвета растрового изображения обрабатываются во время рендеринга.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes--) |  |
## Методы

| Метод | Описание |
| --- | --- |
| [getWrapMode()](#getWrapMode--) | Получает или задает 32-битное беззнаковое целое, которое определяет, как обрабатывать граничные условия с помощью значения из перечисления WrapMode (раздел 2.1.1.34). |
| [setWrapMode(int value)](#setWrapMode-int-) | Получает или задает 32-битное беззнаковое целое, которое определяет, как обрабатывать граничные условия с помощью значения из перечисления WrapMode (раздел 2.1.1.34). |
| [getClampArgb32Color()](#getClampArgb32Color--) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет края, используемый, когда значение WrapMode равно WrapModeClamp. |
| [setClampArgb32Color(int value)](#setClampArgb32Color-int-) | Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет края, используемый, когда значение WrapMode равно WrapModeClamp. |
| [getObjectClamp()](#getObjectClamp--) | Получает или задает 32-битное знаковое целое, которое определяет поведение зажима объекта. |
| [setObjectClamp(int value)](#setObjectClamp-int-) | Получает или задает 32-битное знаковое целое, которое определяет поведение зажима объекта. |
### EmfPlusImageAttributes() {#EmfPlusImageAttributes--}
```
public EmfPlusImageAttributes()
```


### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как обрабатывать граничные условия с помощью значения из перечисления WrapMode (раздел 2.1.1.34).

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Получает или задает 32-битное беззнаковое целое, которое определяет, как обрабатывать граничные условия с помощью значения из перечисления WrapMode (раздел 2.1.1.34).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getClampArgb32Color() {#getClampArgb32Color--}
```
public int getClampArgb32Color()
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет края, используемый, когда значение WrapMode равно WrapModeClamp. Этот цвет виден, когда исходный прямоугольник, обработанный записью EmfPlusDrawImage (раздел 2.3.4.8), больше самого изображения.

**Returns:**
int
### setClampArgb32Color(int value) {#setClampArgb32Color-int-}
```
public void setClampArgb32Color(int value)
```


Получает или задает объект EmfPlusARGB (раздел 2.2.2.1), который определяет цвет края, используемый, когда значение WrapMode равно WrapModeClamp. Этот цвет виден, когда исходный прямоугольник, обработанный записью EmfPlusDrawImage (раздел 2.3.4.8), больше самого изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

### getObjectClamp() {#getObjectClamp--}
```
public int getObjectClamp()
```


Получает или задает 32-битное знаковое целое, которое определяет поведение зажима объекта. Оно не используется, пока этот объект не будет применён к отрисовываемому изображению. Это значение ДОЛЖНО быть одним из значений, определённых в следующей таблице.

**Returns:**
int
### setObjectClamp(int value) {#setObjectClamp-int-}
```
public void setObjectClamp(int value)
```


Получает или задает 32-битное знаковое целое, которое определяет поведение зажима объекта. Оно не используется, пока этот объект не будет применён к отрисовываемому изображению. Это значение ДОЛЖНО быть одним из значений, определённых в следующей таблице.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int |  |

