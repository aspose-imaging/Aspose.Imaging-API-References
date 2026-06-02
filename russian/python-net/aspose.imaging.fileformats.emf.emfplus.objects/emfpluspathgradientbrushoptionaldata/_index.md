---
title: "Класс EmfPlusPathGradientBrushOptionalData"
type: docs
weight: 510
url: /ru/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | Инициализирует новый экземпляр класса EmfPlusPathGradientBrushOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Получает или задает необязательный шаблон смешивания для кисти градиента по пути. Если это поле<br/>            присутствует, оно ДОЛЖНО содержать либо объект EmfPlusBlendColors (раздел 2.2.2.4), <br/>            либо объект EmfPlusBlendFactors (раздел 2.2.2.5), но НЕ ДОЛЖНО содержать оба. <br/>            Таблица ниже показывает допустимые комбинации флагов EmfPlusPathGradientBrushData<br/>            BrushData и соответствующих шаблонов смешивания: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Получает или задает необязательный объект EmfPlusFocusScaleData (раздел 2.2.2.18), который определяет <br/>            масштабы фокуса для кисти градиента по пути. Это поле ДОЛЖНО присутствовать, если<br/>            флаг BrushDataFocusScales установлен в поле BrushDataFlags объекта <br/>            EmfPlusPathGradientBrushData. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Получает или задает необязательный объект EmfPlusTransformMatrix (раздел 2.2.2.47), который определяет преобразование из мирового пространства в пространство устройства для кисти градиента по пути. <br/>            Это поле ДОЛЖНО присутствовать, если флаг BrushDataTransform установлен в поле BrushDataFlags объекта EmfPlusPathGradientBrushData. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

Инициализирует новый экземпляр класса EmfPlusPathGradientBrushOptionalData

