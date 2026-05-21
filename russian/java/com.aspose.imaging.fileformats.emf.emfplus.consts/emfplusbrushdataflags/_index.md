---
title: "EmfPlusBrushDataFlags"
second_title: "Справочник API Aspose.Imaging для Java"
description: "Флаги BrushData определяют свойства графических кистей, включая наличие дополнительных полей данных."
type: docs
weight: 11
url: /ru/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusBrushDataFlags extends System.Enum
```

Флаги BrushData определяют свойства графических кистей, включая наличие дополнительных полей данных. Эти флаги можно комбинировать для указания нескольких параметров.
## Поля

| Поле | Описание |
| --- | --- |
| [BrushDataPath](#BrushDataPath) | Этот флаг имеет смысл в объектах [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (раздел 2.2.2.29). |
| [BrushDataTransform](#BrushDataTransform) | Этот флаг имеет смысл в объектах [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (раздел 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) и объектах `EmfPlusTextureBrushData` (раздел 2.2.2.45). |
| [BrushDataPresetColors](#BrushDataPresetColors) | Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsH](#BrushDataBlendFactorsH) | Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData. |
| [BrushDataBlendFactorsV](#BrushDataBlendFactorsV) | Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData. |
| [BrushDataFocusScales](#BrushDataFocusScales) | Этот флаг имеет смысл в объектах EmfPlusPathGradientBrushData. |
| [BrushDataIsGammaCorrected](#BrushDataIsGammaCorrected) | Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData и EmfPlusTextureBrushData. |
| [BrushDataDoNotTransform](#BrushDataDoNotTransform) | Этот флаг имеет смысл в объектах EmfPlusTextureBrushData. |
### BrushDataPath {#BrushDataPath}
```
public static final int BrushDataPath
```


Этот флаг имеет смысл в объектах [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) (раздел 2.2.2.29). Если установлен, объект [EmfPlusBoundaryPathData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata) (раздел 2.2.2.6) ДОЛЖЕН быть указан в поле BoundaryData объекта данных кисти. Если сброшен, объект [EmfPlusBoundaryPointData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata) (раздел 2.2.2.7) ДОЛЖЕН быть указан в поле BoundaryData объекта данных кисти.

--------------------

Графические кисти задаются объектами [EmfPlusBrush](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush) objects

### BrushDataTransform {#BrushDataTransform}
```
public static final int BrushDataTransform
```


Этот флаг имеет смысл в объектах [EmfPlusLinearGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata) (раздел 2.2.2.24), [EmfPlusPathGradientBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata) и объектах `EmfPlusTextureBrushData` (раздел 2.2.2.45). Если установлен, 2x3 матрица преобразования из мирового пространства в пространство устройства ДОЛЖНА быть указана в поле OptionalData объекта данных кисти.

### BrushDataPresetColors {#BrushDataPresetColors}
```
public static final int BrushDataPresetColors
```


Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData. Если установлен, объект [EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors) (раздел 2.2.2.4) ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти.

### BrushDataBlendFactorsH {#BrushDataBlendFactorsH}
```
public static final int BrushDataBlendFactorsH
```


Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData. Если установлен, объект [EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors) (раздел 2.2.2.5), который задает шаблон смешивания вдоль горизонтального градиента, ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти.

### BrushDataBlendFactorsV {#BrushDataBlendFactorsV}
```
public static final int BrushDataBlendFactorsV
```


Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData. Если установлен, объект EmfPlusBlendFactors, который задает шаблон смешивания вдоль вертикального градиента, ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти.

### BrushDataFocusScales {#BrushDataFocusScales}
```
public static final int BrushDataFocusScales
```


Этот флаг имеет смысл в объектах EmfPlusPathGradientBrushData. Если установлен, объект [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) (раздел 2.2.2.18) ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти.

### BrushDataIsGammaCorrected {#BrushDataIsGammaCorrected}
```
public static final int BrushDataIsGammaCorrected
```


Этот флаг имеет смысл в объектах EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData и EmfPlusTextureBrushData. Если установлен, кисть ДОЛЖНА быть уже гамма‑корректирована; то есть яркость и интенсивность выхода скорректированы в соответствии с входным изображением.

### BrushDataDoNotTransform {#BrushDataDoNotTransform}
```
public static final int BrushDataDoNotTransform
```


Этот флаг имеет смысл в объектах EmfPlusTextureBrushData. Если установлен, преобразование из мирового пространства в пространство устройства НЕ ДОЛЖНО применяться к текстурной кисти.

