---
title: "Класс MagicWandTool"
type: docs
weight: 100
url: /ru/python-net/aspose.imaging.magicwand/magicwandtool/
---

**Summary:** The class for magic wand algorithm main logic.

**Module:** [aspose.imaging.magicwand](/imaging/python-net/aspose.imaging.magicwand/)

**Full Name:** aspose.imaging.magicwand.MagicWandTool

**Inheritance:** IPartialArgb32PixelLoader

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [process(pixels_rectangle, pixels, start, end)](#process_pixels_rectangle_pixels_start_end_1) | Обрабатывает загруженные пиксели. |
| [select(source, settings)](#select_source_settings_2) | Создаёт новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) на основе [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) и исходного [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


### Method: process(pixels_rectangle, pixels, start, end) {#process_pixels_rectangle_pixels_start_end_1}


```
 process(pixels_rectangle, pixels, start, end) 
```

Обрабатывает загруженные пиксели.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| pixels_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Прямоугольник пикселей. |
| пиксели | int[] | 32‑битные ARGB пиксели. |
| start | [Point](/imaging/python-net/aspose.imaging/point/) | Точка начала пикселей. Если она не равна (left,top), это означает, что у нас не полный прямоугольник. |
| end | [Point](/imaging/python-net/aspose.imaging/point/) | Точка окончания пикселей. Если она не равна (right,bottom), это означает, что у нас не полный прямоугольник. |

### Method: select(source, settings)  [static] {#select_source_settings_2}


```
 select(source, settings) 
```

Создаёт новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) на основе [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) и исходного [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| source | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Растровое изображение, над которым работает алгоритм. |
| settings | [MagicWandSettings](/imaging/python-net/aspose.imaging.magicwand/magicwandsettings/) | Настройки алгоритма волшебной палочки, используемые при создании маски. |

**Returns**

| Тип | Описание |
| :- | :- |
| [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/) | Новый [ImageBitMask](/imaging/python-net/aspose.imaging.magicwand.imagemasks/imagebitmask/). |


