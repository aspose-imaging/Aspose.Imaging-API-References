---
title: "EmfPlusBrushDataFlags Enumeration"
type: docs
weight: 30
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/
---

Флаги BrushData указывают свойства графических кистей, включая наличие дополнительных полей данных. Эти флаги могут комбинироваться для указания нескольких вариантов.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusBrushDataFlags

## **Members**
| **Имя члена** | **Description** |
| :- | :- |
| BRUSH_DATA_BLEND_FACTORS_H | Этот флаг имеет значение в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData.<br/>
            Если установлен, объект [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) (раздел 2.2.2.5), определяющий шаблон смешивания вдоль горизонтального градиента, ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти. |
| BRUSH_DATA_BLEND_FACTORS_V | Этот флаг имеет значение в объектах EmfPlusLinearGradientBrushData.<br/>
            Если установлен, объект EmfPlusBlendFactors, определяющий шаблон смешивания вдоль вертикального градиента, ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти. |
| BRUSH_DATA_DO_NOT_TRANSFORM | Этот флаг имеет значение в объектах EmfPlusTextureBrushData.<br/>
            Если установлен, преобразование из мирового пространства в пространство устройства НЕ ДОЛЖНО применяться к текстурной кисти. |
| BRUSH_DATA_FOCUS_SCALES | Этот флаг имеет значение в объектах EmfPlusPathGradientBrushData.<br/>
            Если установлен, объект [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) (раздел 2.2.2.18) ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти. |
| BRUSH_DATA_IS_GAMMA_CORRECTED | Этот флаг имеет значение в объектах EmfPlusLinearGradientBrushData, EmfPlusPathGradientBrushData и EmfPlusTextureBrushData.<br/>
            Если установлен, кисть ДОЛЖНА быть уже гамма‑корректирована; то есть яркость и интенсивность вывода были скорректированы в соответствии с входным изображением. |
| BRUSH_DATA_PATH | Этот флаг имеет значение в объектах [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) (раздел 2.2.2.29).<br/>
            Если установлен, объект [EmfPlusBoundaryPathData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypathdata/) (раздел 2.2.2.6) ДОЛЖЕН быть указан в поле BoundaryData объекта данных кисти.<br/>
            Если сброшен, объект [EmfPlusBoundaryPointData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarypointdata/) (раздел 2.2.2.7) ДОЛЖЕН быть указан в поле BoundaryData объекта данных кисти. |
| BRUSH_DATA_PRESET_COLORS | Этот флаг имеет значение в объектах EmfPlusLinearGradientBrushData и EmfPlusPathGradientBrushData.<br/>
            Если установлен, объект [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) (раздел 2.2.2.4) ДОЛЖЕН быть указан в поле OptionalData объекта данных кисти. |
| BRUSH_DATA_TRANSFORM | Этот флаг имеет значение в объектах [EmfPlusLinearGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushdata/) (раздел 2.2.2.24), [EmfPlusPathGradientBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/) и [EmfPlusTextureBrushData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/) (раздел 2.2.2.45).<br/>
            Если установлен, матрица преобразования из мирового пространства в пространство устройства размером 2x3 ДОЛЖНА быть указана в поле OptionalData объекта данных кисти. |
