---
title: "GifFrameBlock"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Блок кадра Gif."
type: docs
weight: 12
url: /ru/java/com.aspose.imaging.fileformats.gif.blocks/gifframeblock/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.DataStreamSupporter](../../com.aspose.imaging/datastreamsupporter), [com.aspose.imaging.Image](../../com.aspose.imaging/image), [com.aspose.imaging.RasterImage](../../com.aspose.imaging/rasterimage), [com.aspose.imaging.RasterCachedImage](../../com.aspose.imaging/rastercachedimage)

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.gif.IGifBlock](../../com.aspose.imaging.fileformats.gif/igifblock), [com.aspose.imaging.IAnimationFrame](../../com.aspose.imaging/ianimationframe), com.aspose.fileformats.core.interfaces.IInterlaced
```
public final class GifFrameBlock extends RasterCachedImage implements IGifBlock, IAnimationFrame, IInterlaced
```

Блок кадра Gif.
## Конструкторы

| Конструктор | Описание |
| --- | --- |
| [GifFrameBlock(int width, int height)](#GifFrameBlock-int-int-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height)](#GifFrameBlock-int-int-int-int-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)](#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image)](#GifFrameBlock-com.aspose.imaging.RasterImage-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream)](#GifFrameBlock-java.io.InputStream-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(System.IO.Stream stream)](#GifFrameBlock-com.aspose.ms.System.IO.Stream-) |  |
| [GifFrameBlock(InputStream stream, int left, int top)](#GifFrameBlock-java.io.InputStream-int-int-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(String path)](#GifFrameBlock-java.lang.String-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top)](#GifFrameBlock-java.lang.String-int-int-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
| [GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)](#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-) | Создаёт новый экземпляр класса `GifFrameBlock`. |
## Поля

| Поле | Описание |
| --- | --- |
| [EXTENSION_LABEL](#EXTENSION-LABEL) | Метка расширения блока. |
| [IMAGE_DESCRIPTOR_SIZE](#IMAGE-DESCRIPTOR-SIZE) | Размер дескриптора изображения. |
## Методы

| Метод | Описание |
| --- | --- |
| [getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)](#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-) | Получает связанную цветовую палитру. |
| [createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)](#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-) | Создаёт флаги. |
| [getFileFormat()](#getFileFormat--) | Получает значение формата файла |
| [getWidth()](#getWidth--) | Получает ширину изображения. |
| [getHeight()](#getHeight--) | Получает высоту изображения. |
| [getBitsPerPixel()](#getBitsPerPixel--) | Получает количество бит на пиксель изображения. |
| [getFrameTime()](#getFrameTime--) | Получает длительность. |
| [setFrameTime(int value)](#setFrameTime-int-) | Устанавливает длительность. |
| [getInterlaced()](#getInterlaced--) | Получает или задаёт значение, указывающее, является ли этот `GifFrameBlock` чересстрочным. |
| [isInterlaced()](#isInterlaced--) | Получает значение, указывающее, является ли данный экземпляр изображения чересстрочным. |
| [setInterlaced(boolean value)](#setInterlaced-boolean-) | Получает или задаёт значение, указывающее, является ли этот `GifFrameBlock` чересстрочным. |
| [isPaletteSorted()](#isPaletteSorted--) | Получает или задаёт значение, указывающее, отсортирована ли цветовая палитра. |
| [setPaletteSorted(boolean value)](#setPaletteSorted-boolean-) | Получает или задаёт значение, указывающее, отсортирована ли цветовая палитра. |
| [getGifFrameBitsPerPixel()](#getGifFrameBitsPerPixel--) | Получает или задаёт количество бит на пиксель в кадре GIF. |
| [setGifFrameBitsPerPixel(byte value)](#setGifFrameBitsPerPixel-byte-) | Получает или задаёт количество бит на пиксель в кадре GIF. |
| [getLeft()](#getLeft--) | Получает или задаёт позицию изображения слева. |
| [setLeft(int value)](#setLeft-int-) | Получает или задаёт позицию изображения слева. |
| [getTop()](#getTop--) | Получает или задаёт позицию изображения сверху. |
| [setTop(int value)](#setTop-int-) | Получает или задаёт позицию изображения сверху. |
| [getFrameTop()](#getFrameTop--) | Преобразует в p. |
| [getFrameLeft()](#getFrameLeft--) | Получает значение слева. |
| [getDisposalMethod()](#getDisposalMethod--) | Получает метод освобождения. |
| [getFlags()](#getFlags--) | Получает или задаёт флаги. |
| [setFlags(byte value)](#setFlags-byte-) | Получает или задаёт флаги. |
| [isUseAlphaBlending()](#isUseAlphaBlending--) | Получает значение, указывающее, [использовать альфа‑смешивание]. |
| [getControlBlock()](#getControlBlock--) | Получает блок управления графикой, связанный с этим блоком. |
| [hasTransparentColor()](#hasTransparentColor--) | Получает значение, указывающее, имеет ли блок кадра прозрачный цвет. |
| [getTransparentColor()](#getTransparentColor--) | Получает прозрачный цвет блока кадра. |
| [setTransparentColor(boolean value)](#setTransparentColor-boolean-) | Получает значение, указывающее, имеет ли блок кадра прозрачный цвет. |
| [setTransparentColor(Color value)](#setTransparentColor-com.aspose.imaging.Color-) | Получает прозрачный цвет блока кадра. |
| [getBackgroundColor()](#getBackgroundColor--) | Получает значение фонового цвета. |
| [setBackgroundColor(Color value)](#setBackgroundColor-com.aspose.imaging.Color-) | Устанавливает значение фонового цвета. |
| [getOriginalOptions()](#getOriginalOptions--) | Получает параметры, основанные на настройках оригинального файла. |
| [adjustBrightness(int brightness)](#adjustBrightness-int-) | Регулировка яркости изображения. |
| [replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)](#replaceColor-int-byte-int-) | Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [replaceNonTransparentColors(int newColorArgb)](#replaceNonTransparentColors-int-) | Заменяет все непрозрачные цвета новым цветом и сохраняет исходное альфа-значение, чтобы сохранить плавные края. |
| [getFullFrame()](#getFullFrame--) | Получает полный кадр. |
| [resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)](#resize-int-int-com.aspose.imaging.ImageResizeSettings-) | Изменяет размер этого экземпляра [RasterCachedImage](../../com.aspose.imaging/rastercachedimage). |
### GifFrameBlock(int width, int height) {#GifFrameBlock-int-int-}
```
public GifFrameBlock(int width, int height)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### GifFrameBlock(int left, int top, int width, int height) {#GifFrameBlock-int-int-int-int-}
```
public GifFrameBlock(int left, int top, int width, int height)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |

### GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel) {#GifFrameBlock-int-int-int-int-com.aspose.imaging.IColorPalette-boolean-boolean-byte-}
```
public GifFrameBlock(int left, int top, int width, int height, IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte bitsPerPixel)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |
| width | int | Ширина изображения. |
| height | int | Высота изображения. |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |
| isPaletteSorted | boolean | если установлено `true`, цветовая палитра сортируется. |
| isGifFrameInterlaced | boolean | если установлено `true`, кадр GIF является чересстрочным. |
| bitsPerPixel | byte | Биты на пиксель. |

### GifFrameBlock(RasterImage image) {#GifFrameBlock-com.aspose.imaging.RasterImage-}
```
public GifFrameBlock(RasterImage image)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с помощью которого инициализируются данные пикселей и палитры кадра. |

### GifFrameBlock(RasterImage image, int left, int top) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-}
```
public GifFrameBlock(RasterImage image, int left, int top)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |

### GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-com.aspose.imaging.RasterImage-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(RasterImage image, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |
| isPaletteSorted | boolean | если установлено `true`, цветовая палитра сортируется. |
| isGifFrameInterlaced | boolean | если установлено `true`, кадр GIF является чересстрочным. |
| lzwCodeSize | byte | Биты на пиксель. |

### GifFrameBlock(InputStream stream) {#GifFrameBlock-java.io.InputStream-}
```
public GifFrameBlock(InputStream stream)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |

### GifFrameBlock(System.IO.Stream stream) {#GifFrameBlock-com.aspose.ms.System.IO.Stream-}
```
public GifFrameBlock(System.IO.Stream stream)
```


**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | com.aspose.ms.System.IO.Stream |  |

### GifFrameBlock(InputStream stream, int left, int top) {#GifFrameBlock-java.io.InputStream-int-int-}
```
public GifFrameBlock(InputStream stream, int left, int top)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |

### GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.io.InputStream-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(InputStream stream, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| stream | java.io.InputStream | Поток, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |
| isPaletteSorted | boolean | если установлено `true`, цветовая палитра сортируется. |
| isGifFrameInterlaced | boolean | если установлено `true`, кадр GIF является чересстрочным. |
| lzwCodeSize | byte | Биты на пиксель. |

### GifFrameBlock(String path) {#GifFrameBlock-java.lang.String-}
```
public GifFrameBlock(String path)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |

### GifFrameBlock(String path, int left, int top) {#GifFrameBlock-java.lang.String-int-int-}
```
public GifFrameBlock(String path, int left, int top)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |

### GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize) {#GifFrameBlock-java.lang.String-int-int-boolean-boolean-byte-}
```
public GifFrameBlock(String path, int left, int top, boolean isPaletteSorted, boolean isGifFrameInterlaced, byte lzwCodeSize)
```


Создаёт новый экземпляр класса `GifFrameBlock`.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| path | java.lang.String | Путь, из которого загружается изображение и с помощью которого инициализируются данные пикселей и палитры кадра. |
| слева | int | Позиция изображения слева. |
| сверху | int | Позиция изображения сверху. |
| isPaletteSorted | boolean | если установлено `true`, цветовая палитра сортируется. |
| isGifFrameInterlaced | boolean | если установлено `true`, кадр GIF является чересстрочным. |
| lzwCodeSize | byte | Биты на пиксель. |

### EXTENSION_LABEL {#EXTENSION-LABEL}
```
public static final int EXTENSION_LABEL
```


Метка расширения блока.

### IMAGE_DESCRIPTOR_SIZE {#IMAGE-DESCRIPTOR-SIZE}
```
public static final int IMAGE_DESCRIPTOR_SIZE
```


Размер дескриптора изображения.

### getColorPalette(IColorPalette framePalette, IColorPalette containerPalette) {#getColorPalette-com.aspose.imaging.IColorPalette-com.aspose.imaging.IColorPalette-}
```
public static IColorPalette getColorPalette(IColorPalette framePalette, IColorPalette containerPalette)
```


Получает связанную цветовую палитру.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| framePalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра кадра. |
| containerPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Палитра контейнера. |

**Returns:**
[IColorPalette](../../com.aspose.imaging/icolorpalette) - The color palette.
### createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced) {#createFlags-com.aspose.imaging.IColorPalette-boolean-boolean-}
```
public static byte createFlags(IColorPalette colorPalette, boolean isPaletteSorted, boolean isGifFrameInterlaced)
```


Создаёт флаги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| colorPalette | [IColorPalette](../../com.aspose.imaging/icolorpalette) | Цветовая палитра. |
| isPaletteSorted | boolean | если установлено `true`, цвета в цветовой палитре сортируются. |
| isGifFrameInterlaced | boolean | если установлено `true`, изображение кадра GIF является чересстрочным. |

**Returns:**
byte — созданные флаги.
### getFileFormat() {#getFileFormat--}
```
public long getFileFormat()
```


Получает значение формата файла

**Returns:**
long
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
### getBitsPerPixel() {#getBitsPerPixel--}
```
public int getBitsPerPixel()
```


Получает количество бит на пиксель изображения.

**Returns:**
int — Количество бит на пиксель изображения.
### getFrameTime() {#getFrameTime--}
```
public int getFrameTime()
```


Получает длительность.

Значение: продолжительность в миллисекундах.

**Returns:**
int — продолжительность.
### setFrameTime(int value) {#setFrameTime-int-}
```
public void setFrameTime(int value)
```


Устанавливает длительность.

Значение: продолжительность в миллисекундах.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | продолжительность. |

### getInterlaced() {#getInterlaced--}
```
public boolean getInterlaced()
```


Получает или задаёт значение, указывающее, является ли этот `GifFrameBlock` чересстрочным.

**Returns:**
boolean — `true`, если чересстрочно; иначе `false`.
### isInterlaced() {#isInterlaced--}
```
public boolean isInterlaced()
```


Получает значение, указывающее, является ли данный экземпляр изображения чересстрочным.

Значение: `true`, если данный экземпляр изображения чересстрочный; иначе `false`.

**Returns:**
boolean — значение, указывающее, является ли данный экземпляр изображения чересстрочным.
### setInterlaced(boolean value) {#setInterlaced-boolean-}
```
public void setInterlaced(boolean value)
```


Получает или задаёт значение, указывающее, является ли этот `GifFrameBlock` чересстрочным.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если чересстрочно; иначе `false`. |

### isPaletteSorted() {#isPaletteSorted--}
```
public boolean isPaletteSorted()
```


Получает или задаёт значение, указывающее, отсортирована ли цветовая палитра.

**Returns:**
boolean — `true`, если цветовая палитра сортирована; иначе `false`.
### setPaletteSorted(boolean value) {#setPaletteSorted-boolean-}
```
public void setPaletteSorted(boolean value)
```


Получает или задаёт значение, указывающее, отсортирована ли цветовая палитра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean | `true`, если цветовая палитра сортирована; иначе `false`. |

### getGifFrameBitsPerPixel() {#getGifFrameBitsPerPixel--}
```
public byte getGifFrameBitsPerPixel()
```


Получает или задаёт количество бит на пиксель в кадре GIF.

**Returns:**
byte — количество бит на пиксель в кадре GIF.
### setGifFrameBitsPerPixel(byte value) {#setGifFrameBitsPerPixel-byte-}
```
public void setGifFrameBitsPerPixel(byte value)
```


Получает или задаёт количество бит на пиксель в кадре GIF.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Количество бит на пиксель в кадре GIF. |

### getLeft() {#getLeft--}
```
public int getLeft()
```


Получает или задаёт позицию изображения слева.

**Returns:**
int — положение изображения слева.
### setLeft(int value) {#setLeft-int-}
```
public void setLeft(int value)
```


Получает или задаёт позицию изображения слева.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Положение изображения слева. |

### getTop() {#getTop--}
```
public int getTop()
```


Получает или задаёт позицию изображения сверху.

**Returns:**
int - расположение верхнего изображения.
### setTop(int value) {#setTop-int-}
```
public void setTop(int value)
```


Получает или задаёт позицию изображения сверху.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | int | Расположение верхнего изображения. |

### getFrameTop() {#getFrameTop--}
```
public int getFrameTop()
```


Преобразует в p.

Значение: верх.

**Returns:**
int
### getFrameLeft() {#getFrameLeft--}
```
public int getFrameLeft()
```


Получает значение слева.

Значение: левый.

**Returns:**
int - левый.
### getDisposalMethod() {#getDisposalMethod--}
```
public int getDisposalMethod()
```


Получает метод освобождения.

**Returns:**
int - метод утилизации.
### getFlags() {#getFlags--}
```
public byte getFlags()
```


Получает или задаёт флаги.

**Returns:**
byte - флаги.
### setFlags(byte value) {#setFlags-byte-}
```
public void setFlags(byte value)
```


Получает или задаёт флаги.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | byte | Флаги. |

### isUseAlphaBlending() {#isUseAlphaBlending--}
```
public boolean isUseAlphaBlending()
```


Получает значение, указывающее, [использовать альфа‑смешивание].

Значение: `true` если [use alpha blending]; иначе, `false`.

**Returns:**
boolean - значение, указывающее, используется ли [use alpha blending].
### getControlBlock() {#getControlBlock--}
```
public GifGraphicsControlBlock getControlBlock()
```


Получает блок управления графикой, связанный с этим блоком.

**Returns:**
[GifGraphicsControlBlock](../../com.aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock) - The control block.
### hasTransparentColor() {#hasTransparentColor--}
```
public boolean hasTransparentColor()
```


Получает значение, указывающее, имеет ли блок кадра прозрачный цвет.

**Returns:**
boolean
### getTransparentColor() {#getTransparentColor--}
```
public Color getTransparentColor()
```


Получает прозрачный цвет блока кадра.

**Returns:**
[Color](../../com.aspose.imaging/color)
### setTransparentColor(boolean value) {#setTransparentColor-boolean-}
```
public void setTransparentColor(boolean value)
```


Получает значение, указывающее, имеет ли блок кадра прозрачный цвет.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | boolean |  |

### setTransparentColor(Color value) {#setTransparentColor-com.aspose.imaging.Color-}
```
public void setTransparentColor(Color value)
```


Получает прозрачный цвет блока кадра.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) |  |

### getBackgroundColor() {#getBackgroundColor--}
```
public Color getBackgroundColor()
```


Получает значение фонового цвета.

**Returns:**
[Color](../../com.aspose.imaging/color) - a value for the background color.
### setBackgroundColor(Color value) {#setBackgroundColor-com.aspose.imaging.Color-}
```
public void setBackgroundColor(Color value)
```


Устанавливает значение фонового цвета.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| value | [Color](../../com.aspose.imaging/color) | значение для цвета фона. |

### getOriginalOptions() {#getOriginalOptions--}
```
public ImageOptionsBase getOriginalOptions()
```


Получает параметры на основе настроек оригинального файла. Это может быть полезно для сохранения глубины цвета и других параметров оригинального изображения без изменений. Например, если мы загружаем чёрно‑белое PNG‑изображение с 1 битом на пиксель и затем сохраняем его с помощью метода [DataStreamSupporter.save(String)](../../com.aspose.imaging/datastreamsupporter\\#save-String-), будет получено PNG‑изображение с 8‑битами на пиксель. Чтобы избежать этого и сохранить PNG‑изображение с 1‑битом на пиксель, используйте этот метод для получения соответствующих параметров сохранения и передайте их методу [Image.save(String, ImageOptionsBase)](../../com.aspose.imaging/image\\#save-String--ImageOptionsBase-) в качестве второго параметра.

**Returns:**
[ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase) - The options based on the original file settings.
### adjustBrightness(int brightness) {#adjustBrightness-int-}
```
public void adjustBrightness(int brightness)
```


Регулировка яркости изображения.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| brightness | int | Значение яркости. |

### replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb) {#replaceColor-int-byte-int-}
```
public void replaceColor(int oldColorArgb, byte oldColorDiff, int newColorArgb)
```


Заменяет один цвет другим с допустимой разницей и сохраняет исходное альфа-значение, чтобы сохранить плавные края.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| oldColorArgb | int | Старое значение ARGB цвета, которое будет заменено. |
| oldColorDiff | byte | Допустимая разница в старом цвете, позволяющая расширить заменённый тон цвета. |
| newColorArgb | int | Новое значение ARGB цвета, которым заменяется старый цвет. |

### replaceNonTransparentColors(int newColorArgb) {#replaceNonTransparentColors-int-}
```
public void replaceNonTransparentColors(int newColorArgb)
```


Заменяет все непрозрачные цвета новым цветом и сохраняет исходное значение альфа, чтобы сохранить плавные края. Примечание: если использовать её на изображениях без прозрачности, все цвета будут заменены одним цветом.

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newColorArgb | int | Новое значение ARGB цвета, которым заменяются непрозрачные цвета. |

### getFullFrame() {#getFullFrame--}
```
public RasterImage getFullFrame()
```


Получает полный кадр.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - he RasterImage with full frame
### resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings) {#resize-int-int-com.aspose.imaging.ImageResizeSettings-}
```
public void resize(int newWidth, int newHeight, ImageResizeSettings imageResizeSettings)
```


Изменяет размер этого экземпляра [RasterCachedImage](../../com.aspose.imaging/rastercachedimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| newWidth | int | Новая ширина. |
| newHeight | int | Новая высота. |
| imageResizeSettings | [ImageResizeSettings](../../com.aspose.imaging/imageresizesettings) | Настройки изменения размера. |

