---
title: ImageAttributes
second_title: Справочник по Aspose.Imaging for .NET API
description: АнImageAttributes./imageattributes Объект содержит информацию о том как цвета растрового изображения и метафайла манипулируются во время рендеринга. АнImageAttributes./imageattributesОбъект поддерживает несколько настроек настройки цвета включая матрицы настройки цвета матрицы настройки оттенков серого значения гамма-коррекции таблицы карты цветов и пороговые значения цвета. Во время рендеринга цвета можно корректировать затемнять осветлять и удалять. Чтобы применить такие манипуляции инициализируйтеImageAttributes./imageattributes объект и пройти путь этогоImageAttributes./imageattributes объекта вместе с путемImage./image  в метод DrawImage.
type: docs
weight: 9680
url: /ru/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

Ан[`ImageAttributes`](../imageattributes) Объект содержит информацию о том, как цвета растрового изображения и метафайла манипулируются во время рендеринга. Ан[`ImageAttributes`](../imageattributes)Объект поддерживает несколько настроек настройки цвета, включая матрицы настройки цвета, матрицы настройки оттенков серого, значения гамма-коррекции, таблицы карты цветов и пороговые значения цвета. Во время рендеринга цвета можно корректировать, затемнять, осветлять и удалять. Чтобы применить такие манипуляции, инициализируйте[`ImageAttributes`](../imageattributes) объект и пройти путь этого[`ImageAttributes`](../imageattributes) объекта (вместе с путем[`Image`](../image) ) в метод DrawImage.

```csharp
public sealed class ImageAttributes
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [ImageAttributes](imageattributes)() | Конструктор по умолчанию. |

## Методы

| Имя | Описание |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Очищает таблицу переназначения цветов кисти от этого[`ImageAttributes`](../imageattributes) объект. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Очищает ключ цвета (диапазон прозрачности) для категории по умолчанию. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Очищает ключ цвета (диапазон прозрачности) для указанной категории. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Очищает матрицу настройки цвета для категории по умолчанию. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Очищает матрицу настройки цвета для указанной категории. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Отключает гамма-коррекцию для категории по умолчанию. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Отключает гамма-коррекцию для указанной категории. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Очищает настройку NoOp для категории по умолчанию. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Очищает настройку NoOp для указанной категории. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Очищает настройку выходного канала CMYK (голубой-пурпурный-желтый-черный) для категории по умолчанию. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Очищает настройку выходного канала (голубой-пурпурный-желтый-черный) для указанной категории. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Очищает настройку цветового профиля выходного канала для категории по умолчанию. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Очищает настройку цветового профиля выходного канала для указанной категории. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Очищает таблицу переназначения цветов для категории по умолчанию. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Очищает таблицу переназначения цветов для указанной категории. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Очищает пороговое значение для категории по умолчанию. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Очищает пороговое значение для указанной категории. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Устанавливает таблицу переназначения цветов для категории кистей. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Устанавливает ключ цвета для категории по умолчанию. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Устанавливает цветовой ключ (диапазон прозрачности) для указанной категории. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для категории по умолчанию. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Задает матрицу настройки цвета и матрицу настройки оттенков серого для указанной категории. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Задает матрицу настройки цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Задает матрицу настройки цвета для категории по умолчанию. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Задает матрицу настройки цвета для указанной категории. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Устанавливает значение гаммы для категории по умолчанию. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Устанавливает значение гаммы для указанной категории. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Отключает настройку цвета для категории по умолчанию. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Отключает настройку цвета для указанной категории. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Устанавливает выходной канал CMYK (голубой-пурпурный-желтый-черный) для категории по умолчанию. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Устанавливает выходной канал CMYK (голубой-пурпурный-желтый-черный) для указанной категории. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Устанавливает файл цветового профиля выходного канала для категории по умолчанию. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Устанавливает файл цветового профиля выходного канала для указанной категории. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Задает таблицу переназначения цветов для категории по умолчанию. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Задает таблицу переназначения цветов для указанной категории. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Устанавливает порог (диапазон прозрачности) для категории по умолчанию. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Устанавливает порог (диапазон прозрачности) для указанной категории. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Устанавливает режим переноса, который используется для решения о том, как размещать текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Устанавливает режим обтекания и цвет, используемые для решения, как разместить текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Устанавливает режим обтекания и цвет, используемые для решения, как разместить текстуру поперек формы или на границах формы. Текстура накладывается на фигуру, чтобы заполнить ее, когда текстура меньше, чем фигура, которую она заполняет. |

### Смотрите также

* пространство имен [Aspose.Imaging](../../aspose.imaging)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
