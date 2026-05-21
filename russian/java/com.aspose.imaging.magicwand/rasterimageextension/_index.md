---
title: "RasterImageExtension"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Класс с методами расширения масок для ."
type: docs
weight: 15
url: /ru/java/com.aspose.imaging.magicwand/rasterimageextension/
---
**Inheritance:**
java.lang.Object
```
public final class RasterImageExtension
```

Класс с методами расширения масок для [RasterImage](../../com.aspose.imaging/rasterimage).
## Методы

| Метод | Описание |
| --- | --- |
| [selectMask(RasterImage source)](#selectMask-com.aspose.imaging.RasterImage-) |  |
| [selectMask(RasterImage source, MagicWandSettings settings)](#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-) | Создаёт [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с выбором пикселей, цвета которых похожи на цвет опорной точки, на основе [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings). |
| [applyMask(RasterImage image, IImageMask mask)](#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-) | Применяет [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) к [RasterImage](../../com.aspose.imaging/rasterimage). |
### selectMask(RasterImage source) {#selectMask-com.aspose.imaging.RasterImage-}
```
public static ImageBitMask selectMask(RasterImage source)
```




**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) |  |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask)
### selectMask(RasterImage source, MagicWandSettings settings) {#selectMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.MagicWandSettings-}
```
public static ImageBitMask selectMask(RasterImage source, MagicWandSettings settings)
```


Создаёт [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) с выбором пикселей, цвета которых похожи на цвет опорной точки, на основе [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| source | [RasterImage](../../com.aspose.imaging/rasterimage) | Растровое изображение, над которым работает алгоритм. |
| settings | [MagicWandSettings](../../com.aspose.imaging.magicwand/magicwandsettings) | Настройки, используемые для обработки выделения, включают опорную точку. |

**Returns:**
[ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask) - New [ImageBitMask](../../com.aspose.imaging.magicwand.imagemasks/imagebitmask).
### applyMask(RasterImage image, IImageMask mask) {#applyMask-com.aspose.imaging.RasterImage-com.aspose.imaging.magicwand.imagemasks.IImageMask-}
```
public static void applyMask(RasterImage image, IImageMask mask)
```


Применяет [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) к [RasterImage](../../com.aspose.imaging/rasterimage).

**Parameters:**
| Параметр | Тип | Описание |
| --- | --- | --- |
| image | [RasterImage](../../com.aspose.imaging/rasterimage) | Изображение, к которому применяется маска. |
| mask | [IImageMask](../../com.aspose.imaging.magicwand.imagemasks/iimagemask) | Маска, которая будет применена. |

