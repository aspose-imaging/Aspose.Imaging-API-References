---
title: "EmfPlusLinearGradientBrushOptionalData Sınıfı"
type: docs
weight: 450
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---

**Summary:** The EmfPlusLinearGradientBrushOptionalData object specifies optional data for a linear gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLinearGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData__1) | EmfPlusLinearGradientBrushOptionalData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase[]](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Doğrusal gradyan fırçası için isteğe bağlı bir karışım deseni alır veya ayarlar. Bu alan mevcutsa, <br/>            bir EmfPlusBlendColors nesnesi (bölüm 2.2.4) veya bir veya iki EmfPlusBlendFactors nesnesi (bölüm 2.2.5) içermelidir, <br/>            ancak ikisini birden içeremez. Aşağıdaki tablo, <br/>            EmfPlusLinearGradientBrushData BrushData bayrakları ile ilgili geçerli kombinasyonları ve karşılık gelen karışım desenlerini gösterir:<br/>            EmfPlusBlendFactors |
| blend_pattern_as_blend_factors_h | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Karışım desenini h blend faktörleri olarak alır. |
| blend_pattern_as_blend_factors_v | [EmfPlusBlendFactors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors/) | r | Karışım desenini v blend faktörleri olarak alır. |
| blend_pattern_as_preset_colors | [EmfPlusBlendColors](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors/) | r | Karışım desenini önceden ayarlanmış renkler olarak alır. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | İsteğe bağlı bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar; bu nesne, lineer degrade fırçası için dünya uzayından cihaz uzayına dönüşümü belirtir. <br/>            Bu alan, EmfPlusLinearGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa VAR OLMAK ZORUNDADIR. |


### Constructor: EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData__1}


```
 EmfPlusLinearGradientBrushOptionalData() 
```

EmfPlusLinearGradientBrushOptionalData sınıfının yeni bir örneğini başlatır

