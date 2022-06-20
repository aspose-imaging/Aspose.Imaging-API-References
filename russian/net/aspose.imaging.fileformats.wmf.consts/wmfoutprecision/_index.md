---
title: WmfOutPrecision
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление OutPrecision определяет значения для точности вывода которая является требованием для преобразователя шрифтов для соответствия определенным параметрам шрифта включая высоту ширину ориентация символов спуск шаг и тип шрифта.
type: docs
weight: 8260
url: /ru/net/aspose.imaging.fileformats.wmf.consts/wmfoutprecision/
---
## WmfOutPrecision enumeration

Перечисление OutPrecision определяет значения для точности вывода, которая является требованием для преобразователя шрифтов для соответствия определенным параметрам шрифта, включая высоту, ширину, ориентация символов, спуск, шаг и тип шрифта.

```csharp
public enum WmfOutPrecision : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Default | `0` | Значение, определяющее поведение по умолчанию. |
| String | `1` | Значение, возвращаемое при перечислении растровых шрифтов. |
| Stroke | `3` | Значение, возвращаемое при перечислении TrueType и других контурных шрифтов, а также векторных шрифтов. |
| Tt | `4` | Значение, определяющее выбор шрифта TrueType, когда система содержит несколько шрифтов с одинаковыми именами. |
| Device | `5` | Значение, определяющее выбор шрифта устройства, когда система содержит несколько шрифтов с одинаковым именем. |
| Raster | `6` | Значение, определяющее выбор растрового шрифта, когда система содержит несколько шрифтов с одинаковыми именами. |
| TtOnly | `7` | Значение, указывающее требование только для шрифтов TrueType. Если в системе не установлены шрифты TrueType, задается поведение по умолчанию. |
| Outline | `8` | Значение, определяющее требование для TrueType и других контурных шрифтов. |
| ScreenOutline | `9` | Значение, указывающее предпочтение для TrueType и других контурных шрифтов. |
| PsOnly | `10` | Значение, указывающее требование только для шрифтов PostScript. Если в системе не установлены шрифты PostScript, указывается поведение по умолчанию. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->