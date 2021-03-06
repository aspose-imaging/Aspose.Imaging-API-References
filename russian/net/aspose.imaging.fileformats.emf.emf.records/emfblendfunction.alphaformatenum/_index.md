---
title: EmfBlendFunction.AlphaFormatEnum
second_title: Справочник по Aspose.Imaging for .NET API
description: Структура определяющая как исходный и конечный пиксели интерпретируются относительно альфа-прозрачности.
type: docs
weight: 3280
url: /ru/net/aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
## EmfBlendFunction.AlphaFormatEnum enumeration

Структура, определяющая, как исходный и конечный пиксели интерпретируются относительно альфа-прозрачности.

```csharp
public enum AlphaFormatEnum : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| NotTransparency | `0` | Пиксели в исходном растровом изображении не определяют альфа-прозрачность. В этом случае значение SrcConstantAlpha определяет сочетание растровых изображений источника и назначения. Обратите внимание, что в следующих уравнениях SrcConstantAlpha делится на 255, что дает значение в диапазоне от 0 до 1. |
| AC_SRC_ALPHA | `1` | Указывает, что исходное растровое изображение имеет разрядность 32 бита на пиксель, и задает значение прозрачности для каждого пикселя. |

### Смотрите также

* struct [EmfBlendFunction](../emfblendfunction)
* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
