---
title: EmfPlusStringFormatData
second_title: Справочник по Aspose.Imaging for .NET API
description: Объект EmfPlusStringFormatData определяет позиции табуляции и позиции символов для графической строки.
type: docs
weight: 5790
url: /ru/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
## EmfPlusStringFormatData class

Объект EmfPlusStringFormatData определяет позиции табуляции и позиции символов для графической строки.

```csharp
public sealed class EmfPlusStringFormatData : EmfPlusStructureObjectType
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfPlusStringFormatData](emfplusstringformatdata)() | Конструктор по умолчанию. |

## Характеристики

| Имя | Описание |
| --- | --- |
| [CharRange](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/charrange) { get; set; } | Получает или задает необязательный массив объектов RangeCount EmfPlusCharacterRange , определяющих диапазон позиций символов в строке текст. Ограничивающая область определяется областью дисплея, которая занята группой символов, заданных диапазоном символов. Это поле ДОЛЖНО присутствовать, если значение поля RangeCount в объекте EmfPlusStringFormat больше 0. |
| [TabStops](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/tabstops) { get; set; } | Получает или задает необязательный массив значений с плавающей запятой, которые определяют необязательные положения табуляции для этого объекта. Каждое значение табуляции stop представляет количество пробелов между табуляциями или, для первой табуляции, количество пробелов между началом табуляции. строку текста и первую позицию табуляции. Это поле ДОЛЖНО присутствовать, если значение поля TabStopCount в объекте EmfPlusStringFormat больше 0. |

### Смотрите также

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* пространство имен [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->