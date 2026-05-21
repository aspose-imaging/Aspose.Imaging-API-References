---
title: "ApngFrame"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Создавайте кадры анимированного PNG (APNG) из одностраничных растровых изображений с помощью нашего API."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.apng/apngframe/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class ApngFrame extends RasterCachedImage implements IAnimationFrame
```

Создавайте кадры анимированного PNG (APNG) из одностраничных растровых изображений с помощью нашего API. Без труда задавайте анимацию и длительность кадров, указывайте количество кадров и регулируйте уровни гаммы и контраста, обеспечивая захватывающие и настраиваемые анимации, соответствующие вашему видению.
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getFrameTime()](#getFrameTime--) | Получает длительность кадра. |
| [setFrameTime(int value)](#setFrameTime-int-) | Устанавливает длительность кадра. |
| [getFrameTop()](#getFrameTop--) | Получает смещение верхней части кадра. |
| [getFrameLeft()](#getFrameLeft--) | Получает смещение левой части кадра. |
| [getDisposalMethod()](#getDisposalMethod--) | Получает метод освобождения. |
| [hasTransparentColor()](#hasTransparentColor--) | Возвращает значение, указывающее, имеет ли изображение прозрачный цвет. |
| [hasAlpha()](#hasAlpha--) | Возвращает значение, указывающее, имеет ли данный экземпляр альфа-канал. |
| [getTransparentColor()](#getTransparentColor--) | Возвращает прозрачный цвет. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Значение, указывающее, имеет ли изображение прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Прозрачный цвет. |
| [hasBackgroundColor()](#hasBackgroundColor--) | Возвращает значение, указывающее, имеет ли оно фоновый цвет. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает фоновый цвет. |
| [setBackgroundColor(boolean value)](#setBackgroundColor-boolean-) | Значение, указывающее, имеет ли оно фоновый цвет. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Фоновый цвет. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Получает значение, указывающее, [использовать альфа‑смешивание]. |
| [getFullFrame()](#getFullFrame--) | Получает полный кадр. |
| [cacheData()](#cacheData--) | Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)). |
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — количество бит на пиксель изображения.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

**Returns:**
int — ширина изображения.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

**Returns:**
int — высота изображения.
### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Получает длительность кадра.

**Returns:**
int - длительность кадра.
### setFrameTime(int value) {#setFrameTime-int-}
```
public final void setFrameTime(int value)
```


Устанавливает длительность кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | длительность кадра. |

### getFrameTop() {#getFrameTop--}
```
public final int getFrameTop()
```


Получает смещение верхней части кадра.

**Returns:**
int - смещение верхней части кадра.
### getFrameLeft() {#getFrameLeft--}
```
public final int getFrameLeft()
```


Получает смещение левой части кадра.

**Returns:**
int - смещение левой части кадра.
### getDisposalMethod() {#getDisposalMethod--}
```
public final int getDisposalMethod()
```


Получает метод освобождения.

**Returns:**
int - метод утилизации.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Возвращает значение, указывающее, имеет ли изображение прозрачный цвет.

**Returns:**
boolean - значение, указывающее, имеет ли изображение прозрачный цвет.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Возвращает значение, указывающее, имеет ли данный экземпляр альфа-канал.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Возвращает прозрачный цвет.

**Returns:**
[Color](../../com.aspose.imaging/color) - the transparent color.
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Значение, указывающее, имеет ли изображение прозрачный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли изображение прозрачный цвет. |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Прозрачный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | прозрачный цвет. |

### hasBackgroundColor() {#hasBackgroundColor--}
```
public boolean hasBackgroundColor()
```


Возвращает значение, указывающее, имеет ли оно фоновый цвет.

**Returns:**
boolean - значение, указывающее, имеет ли фон цвет.
### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает фоновый цвет.

**Returns:**
[Color](../../com.aspose.imaging/color) - the background color.
### setBackgroundColor(boolean value) {#setBackgroundColor-boolean-}
```
public void setBackgroundColor(boolean value)
```


Значение, указывающее, имеет ли оно фоновый цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, имеет ли фон цвет. |

### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Фоновый цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | цвет фона. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Получает значение, указывающее, [использовать альфа‑смешивание].

Значение: `true` если [use alpha blending]; иначе, `false`.

**Returns:**
boolean - значение, указывающее, используется ли [use alpha blending].
### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Получает полный кадр.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
### cacheData() {#cacheData--}
```
public void cacheData()
```


Кеширует данные и гарантирует, что дополнительная загрузка данных не будет выполнена из базового `DataStreamSupporter.DataStreamContainer`([DataStreamSupporter.getDataStreamContainer](../../com.aspose.imaging/datastreamsupporter\#getDataStreamContainer)).

