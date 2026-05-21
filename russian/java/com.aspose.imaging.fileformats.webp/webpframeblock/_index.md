---
title: "WebPFrameBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Представляет реестр открывающих блоков webp."
type: docs
weight: 10
url: /ru/java/com.aspose.imaging.fileformats.webp/webpframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.webp.IFrame](../../com.aspose.imaging.fileformats.webp/iframe), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe)
```
public class WebPFrameBlock extends RasterCachedImage implements IFrame, IAnimationFrame
```

Представляет реестр открывающих блоков webp.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [WebPFrameBlock(RasterImage rasterImage)](#WebPFrameBlock-com.aspose.imaging.RasterImage-) | Инициализирует новый экземпляр класса `WebPFrameBlock`. |
| [WebPFrameBlock(int width, int height)](#WebPFrameBlock-int-int-) | Инициализирует новый экземпляр класса `WebPFrameBlock`. |
## Методы

| Метод | Описание |
| --- | --- |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [hasAlpha()](#hasAlpha--) | Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал. |
| [getDuration()](#getDuration--) | Получает или задает длительность кадра. |
| [setDuration(short value)](#setDuration-short-) | Получает или задает длительность кадра. |
| [getLeft()](#getLeft--) | Получает или задает левое положение кадра. |
| [setLeft(short value)](#setLeft-short-) | Получает или задает левое положение кадра. |
| [getTop()](#getTop--) | Получает или задает верхнее положение кадра. |
| [setTop(short value)](#setTop-short-) | Получает или задает верхнее положение кадра. |
| [getFrameTime()](#getFrameTime--) | Получает длительность кадра. |
| [getFrameTop()](#getFrameTop--) | Получает смещение верхней части кадра. |
| [getFrameLeft()](#getFrameLeft--) | Получает смещение левой части кадра. |
| [getDisposalMethod()](#getDisposalMethod--) | Получает метод освобождения. |
| [setDisposalMethod(int value)](#setDisposalMethod-int-) | Задает метод утилизации. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Получает значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра. |
| [setUseAlphaBlending(boolean value)](#setUseAlphaBlending-boolean-) | Задает значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра. |
| [getFullFrame()](#getFullFrame--) | Получает полный кадр. |
### WebPFrameBlock(RasterImage rasterImage) {#WebPFrameBlock-com.aspose.imaging.RasterImage-}
```
public WebPFrameBlock(RasterImage rasterImage)
```


Инициализирует новый экземпляр класса `WebPFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| rasterImage | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение. |

### WebPFrameBlock(int width, int height) {#WebPFrameBlock-int-int-}
```
public WebPFrameBlock(int width, int height)
```


Инициализирует новый экземпляр класса `WebPFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина. |
| height | int | Высота. |

### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Получает высоту изображения.

**Returns:**
int — высота изображения.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Получает ширину изображения.

**Returns:**
int — ширина изображения.
### hasAlpha() {#hasAlpha--}
```
public boolean hasAlpha()
```


Получает значение, указывающее, имеет ли этот экземпляр альфа‑канал.

**Returns:**
boolean - `true`, если у этого экземпляра есть альфа; в противном случае `false`.

**Example: The following example loads a WEBP image and prints information about raw data format and alpha channel.**

``` java
String dir = "c:\\temp\\";
String fileName = dir + "sample.webp";
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(fileName);
try {
    com.aspose.imaging.fileformats.webp.WebPImage webpImage = (com.aspose.imaging.fileformats.webp.WebPImage) image;

    // Если активный кадр TIFF содержит альфа-канал, то всё изображение TIFF считается имеющим альфа-канал.
    System.out.printf("ImageFile=%s, FileFormat=%s, HasAlpha=%s\r\n", fileName, webpImage.getRawDataFormat(), webpImage.hasAlpha());

    int i = 0;
    for (com.aspose.imaging.fileformats.webp.IFrame frame : webpImage.getBlocks()) {
        if (frame instanceof com.aspose.imaging.fileformats.webp.WebPFrameBlock) {
            com.aspose.imaging.fileformats.webp.WebPFrameBlock frameBlock = (com.aspose.imaging.fileformats.webp.WebPFrameBlock) frame;
            System.out.printf("Frame=%s, FileFormat=%s, HasAlpha=%s\r\n", i++, frameBlock.getRawDataFormat(), frameBlock.hasAlpha());
        }
    }
} finally {
    image.dispose();
}

// Вывод может выглядеть так:
// ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, использованные каналы: 1, HasAlpha=False
// Frame=0, FileFormat=RgbIndexed1Bpp, использованные каналы: 1, HasAlpha=False
```

### getDuration() {#getDuration--}
```
public short getDuration()
```


Получает или задает длительность кадра.

**Returns:**
short - Длительность.
### setDuration(short value) {#setDuration-short-}
```
public void setDuration(short value)
```


Получает или задает длительность кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Длительность. |

### getLeft() {#getLeft--}
```
public short getLeft()
```


Получает или задает левое положение кадра.

**Returns:**
short - Левый.
### setLeft(short value) {#setLeft-short-}
```
public void setLeft(short value)
```


Получает или задает левое положение кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Левый. |

### getTop() {#getTop--}
```
public short getTop()
```


Получает или задает верхнее положение кадра.

**Returns:**
short - Верхний.
### setTop(short value) {#setTop-short-}
```
public void setTop(short value)
```


Получает или задает верхнее положение кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | short | Верхний. |

### getFrameTime() {#getFrameTime--}
```
public final int getFrameTime()
```


Получает длительность кадра.

**Returns:**
int - длительность кадра.
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
### setDisposalMethod(int value) {#setDisposalMethod-int-}
```
public final void setDisposalMethod(int value)
```


Задает метод утилизации.

Значение: Метод утилизации.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | метод утилизации. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public final boolean isUseAlphaBlending()
```


Получает значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра.

Значение: `` если этот кадр использует альфа-смешивание; иначе, ``.

**Returns:**
boolean - значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра.
### setUseAlphaBlending(boolean value) {#setUseAlphaBlending-boolean-}
```
public final void setUseAlphaBlending(boolean value)
```


Задает значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра.

Значение: `` если этот кадр использует альфа-смешивание; иначе, ``.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | значение, указывающее, объединяется ли текущий кадр с альфа-значениями предыдущего кадра. |

### getFullFrame() {#getFullFrame--}
```
public final RasterImage getFullFrame()
```


Получает полный кадр.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - The full frame image.
