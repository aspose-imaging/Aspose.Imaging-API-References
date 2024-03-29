---
title: EmfMapMode
second_title: Справочник по Aspose.Imaging for .NET API
description: Перечисление MapMode используется для определения единицы измерения для преобразования единиц пространства страницы в единицы пространства устройства и для определения ориентации осей чертежа.
type: docs
weight: 2740
url: /ru/net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
## EmfMapMode enumeration

Перечисление MapMode используется для определения единицы измерения для преобразования единиц пространства страницы в единицы пространства устройства и для определения ориентации осей чертежа.

```csharp
public enum EmfMapMode
```

### Ценности

| Имя | Ценность | Описание |
| --- | --- | --- |
| MM_TEXT | `1` | Каждая логическая единица сопоставляется с одним пикселем устройства. Положительный x справа; положительный y не работает. |
| MM_LOMETRIC | `2` | Каждой логической единице соответствует 0,1 миллиметра. Положительный x справа; положительный y вверх. |
| MM_HIMETRIC | `3` | Каждой логической единице соответствует 0,01 миллиметра. Положительный x справа; положительный y вверх. |
| MM_LOENGLISH | `4` | Каждая логическая единица соответствует 0,01 дюйма. Положительный x справа; положительный y — это up |
| MM_HIENGLISH | `5` | Каждая логическая единица соответствует 0,001 дюйма. Положительный x справа; положительный y вверх. |
| MM_TWIPS | `6` | Каждая логическая единица сопоставляется с одной двадцатой точки принтера (1/1440 дюйма, также называемой «twip»). Положительный x справа; положительный y вверх. |
| MM_ISOTROPIC | `7` | Логические единицы сопоставляются с произвольными единицами с одинаково масштабированными осями; то есть одна единица по оси x равна одной единице по оси y. Записи EMR_SETWINDOWEXTEX и EMR_SETVIEWPORTEXTEX СЛЕДУЕТ использовать для указания единиц измерения и ориентации осей. ДОЛЖНЫ быть выполнены корректировки, необходимые для обеспечения того, чтобы единицы x и y оставались одного размера. Например, когда установлен размер окна, область просмотра ДОЛЖНА быть скорректирована так, чтобы единицы измерения оставались изотропными. |
| MM_ANISOTROPIC | `8` | Логические единицы сопоставляются с произвольными единицами с произвольным масштабом осей. Записи EMR_SETWINDOWEXTEX и EMR_SETVIEWPORTEXTEX СЛЕДУЕТ использовать для указания единиц измерения, ориентации и масштабирования. |

### Смотрите также

* пространство имен [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* сборка [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
