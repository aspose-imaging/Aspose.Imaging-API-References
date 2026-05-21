---
title: "الفئة ColorPalette"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.ColorPalette. تُعرّف مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32 بت. غير قابلة للوراثة"
type: docs
weight: 380
url: /ar/net/aspose.imaging/colorpalette/
---
## ColorPalette class

يحدد مصفوفة من الألوان التي تشكل لوحة ألوان. الألوان هي ألوان ARGB 32‑بت. لا يمكن وراثتها.

```csharp
public sealed class ColorPalette : IColorPalette
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [ColorPalette](colorpalette/#constructor)(Color[]) | ينشئ مثيلًا جديدًا من الفئة `ColorPalette` وتكون IsCompactPalette غير صحيحة. |
| [ColorPalette](colorpalette/#constructor_2)(int[]) | ينشئ مثيلًا جديدًا من الفئة `ColorPalette` وتكون IsCompactPalette غير صحيحة. |
| [ColorPalette](colorpalette/#constructor_1)(Color[], bool) | ينشئ مثيلًا جديدًا من الفئة `ColorPalette`. |
| [ColorPalette](colorpalette/#constructor_3)(int[], bool) | ينشئ مثيلًا جديدًا من الفئة `ColorPalette`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Argb32Entries](../../aspose.imaging/colorpalette/argb32entries/) { get; } | يحصل على مصفوفة من هياكل ARGB 32-بت. |
| [Entries](../../aspose.imaging/colorpalette/entries/) { get; } | يحصل على مصفوفة من هياكل [`Color`](../color/). |
| [EntriesCount](../../aspose.imaging/colorpalette/entriescount/) { get; } | يحصل على عدد الإدخالات. |
| [IsCompactPalette](../../aspose.imaging/colorpalette/iscompactpalette/) { get; } | يحصل أو يعيّن قيمة تشير إلى ما إذا كانت لوحة الألوان المدمجة مستخدمة. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette/#copypalette)(IColorPalette) | ينسخ لوحة الألوان. |
| static [CopyPalette](../../aspose.imaging/colorpalette/copypalette/#copypalette_1)(IColorPalette, bool) | ينسخ لوحة الألوان. |
| [GetArgb32Color](../../aspose.imaging/colorpalette/getargb32color/)(int) | يحصل على لون لوحة ARGB 32-بت حسب الفهرس. |
| [GetColor](../../aspose.imaging/colorpalette/getcolor/)(int) | يحصل على لون اللوحة حسب الفهرس. |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex/#getnearestcolorindex)(Color) | يحصل على فهرس أقرب لون. |
| [GetNearestColorIndex](../../aspose.imaging/colorpalette/getnearestcolorindex/#getnearestcolorindex_1)(int) | يحصل على فهرس أقرب لون. |

### انظر أيضًا

* interface [IColorPalette](../icolorpalette/)
* namespace [Aspose.Imaging](../../aspose.imaging/)
* assembly [Aspose.Imaging](../../)


