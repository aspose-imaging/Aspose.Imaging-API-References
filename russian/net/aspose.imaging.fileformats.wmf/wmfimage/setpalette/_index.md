---
title: SetPalette
second_title: Справочник по Aspose.Imaging for .NET API
description: Устанавливает палитру изображения.
type: docs
weight: 180
url: /ru/net/aspose.imaging.fileformats.wmf/wmfimage/setpalette/
---
## WmfImage.SetPalette method

Устанавливает палитру изображения.

```csharp
public override void SetPalette(IColorPalette palette, bool updateColors)
```

| Параметр | Тип | Описание |
| --- | --- | --- |
| palette | IColorPalette | Палитра для установки. |
| updateColors | Boolean | если установлено значение` true` цвета будут обновлены в соответствии на новую палитру; в противном случае индексы цвета остаются неизменными. Обратите внимание, что неизмененные индексы могут привести к сбою изображения при загрузке, если некоторые индексы не имеют соответствующих записей палитры. |

### Исключения

| исключение | условие |
| --- | --- |
| NotImplementedException |  |

### Смотрите также

* interface [IColorPalette](../../../aspose.imaging/icolorpalette)
* class [WmfImage](../../wmfimage)
* пространство имен [Aspose.Imaging.FileFormats.Wmf](../../wmfimage)
* сборка [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->