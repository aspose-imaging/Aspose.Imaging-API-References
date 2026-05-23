---
title: "Класс EmfPlusLinearGradientBrushOptionalData"
type: docs
weight: 450
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | Инициализирует новый экземпляр класса EmfPlusLinearGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Получает или задает необязательный шаблон смешивания для кисти линейного градиента. Если это поле присутствует, <br/> оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), <br/> либо один или два объекта EmfPlusBlendFactors (раздел 2.2.2.5), <br/> но НЕ ДОЛЖНО содержать оба. Таблица ниже показывает допустимые комбинации <br/> флагов BrushData из EmfPlusLinearGradientBrushData и соответствующих шаблонов смешивания:<br/> EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Получает шаблон смешивания как коэффициенты смешивания h. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Получает шаблон смешивания как коэффициенты смешивания v. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Получает шаблон смешивания в виде предустановленных цветов. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет<br/>            преобразование из мирового пространства в пространство устройства для кисти линейного градиента. <br/>            Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле<br/>            BrushDataFlags объекта EmfPlusLinearGradientBrushData. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

Инициализирует новый экземпляр класса EmfPlusLinearGradientBrushOptionalData

