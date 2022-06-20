---
title: WmfFontQuality
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление FontQuality указывает насколько близко атрибуты логического шрифта должны совпадать с атрибутами физического шрифта при отображении текста.
type: docs
weight: 8180
url: /ru/net/aspose.imaging.fileformats.wmf.consts/wmffontquality/
---
## WmfFontQuality enumeration

Перечисление FontQuality указывает, насколько близко атрибуты логического шрифта должны совпадать с атрибутами физического шрифта при отображении текста.

```csharp
public enum WmfFontQuality : byte
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| Default | `0` | Указывает, что качество символов шрифта не имеет значения, поэтому можно использовать DRAFT. |
| Draft | `1` | Указывает, что качество символов шрифта менее важно, чем соответствие логических атрибутов. Для растеризованных шрифтов СЛЕДУЕТ включить масштабирование, что означает, что доступно больше размеров шрифта. |
| Proof | `2` | Указывает, что качество символов шрифта более важно, чем соответствие логических атрибутов. Для растеризованных шрифтов СЛЕДУЕТ отключить масштабирование и СЛЕДУЕТ выбрать шрифт ближайший по размеру. |
| Nonantialiased | `3` | Указывает, что сглаживание НЕ ДОЛЖНО использоваться при рендеринге текста |
| Antialiased | `4` | Указывает, что сглаживание ДОЛЖНО использоваться при рендеринге текста, если шрифт его поддерживает. |
| Cleartype | `5` | Указывает, что сглаживание ClearType СЛЕДУЕТ использовать при рендеринге текста, если шрифт его поддерживает. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->