---
title: "IImageMask"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Описывает маску."
type: docs
weight: 18
url: /ru/java/com.aspose.imaging.magicwand.imagemasks/iimagemask/
---
**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable
```
public interface IImageMask extends System.ICloneable
```

Описывает маску.
## Методы

| Метод | Описание |
| --- | --- |
| [getSource()](#getSource--) | Возвращает исходное изображение, использованное для создания этой маски, если оно существует. |
| [getWidth()](#getWidth--) | Возвращает ширину этой маски в пикселях. |
| [getHeight()](#getHeight--) | Возвращает высоту этой маски в пикселях. |
| [getBounds()](#getBounds--) | Возвращает границы этой маски в пикселях. |
| [getSelectionBounds()](#getSelectionBounds--) | Возвращает границы выбранной части маски в пикселях. |
| [isOpaque(int x, int y)](#isOpaque-int-int-) | Проверяет, является ли указанный пиксель непрозрачным. |
| [isTransparent(int x, int y)](#isTransparent-int-int-) | Проверяет, является ли указанный пиксель прозрачным. |
| [getByteOpacity(int x, int y)](#getByteOpacity-int-int-) | Получает непрозрачность указанного пикселя с точностью до байта. |
### getSource() {#getSource--}
```
public abstract RasterImage getSource()
```


Возвращает исходное изображение, использованное для создания этой маски, если оно существует.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the source image used to create this mask, if exists.
### getWidth() {#getWidth--}
```
public abstract int getWidth()
```


Возвращает ширину этой маски в пикселях.

**Returns:**
int — ширина этой маски в пикселях.
### getHeight() {#getHeight--}
```
public abstract int getHeight()
```


Возвращает высоту этой маски в пикселях.

**Returns:**
int — высота этой маски в пикселях.
### getBounds() {#getBounds--}
```
public abstract Rectangle getBounds()
```


Возвращает границы этой маски в пикселях.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds, in pixels, of this mask.
### getSelectionBounds() {#getSelectionBounds--}
```
public abstract Rectangle getSelectionBounds()
```


Возвращает границы выбранной части маски в пикселях.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle) - the bounds of the selected part of the mask, in pixels.
### isOpaque(int x, int y) {#isOpaque-int-int-}
```
public abstract boolean isOpaque(int x, int y)
```


Проверяет, является ли указанный пиксель непрозрачным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
boolean — true, если указанный пиксель непрозрачный; иначе false.
### isTransparent(int x, int y) {#isTransparent-int-int-}
```
public abstract boolean isTransparent(int x, int y)
```


Проверяет, является ли указанный пиксель прозрачным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
boolean — true, если указанный пиксель прозрачный; иначе false.
### getByteOpacity(int x, int y) {#getByteOpacity-int-int-}
```
public abstract byte getByteOpacity(int x, int y)
```


Получает непрозрачность указанного пикселя с точностью до байта.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| x | int | Координата x пикселя. |
| y | int | Координата y пикселя. |

**Returns:**
byte — значение байта, представляющее непрозрачность указанного пикселя.
