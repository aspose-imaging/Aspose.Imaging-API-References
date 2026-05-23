---
title: "EmfPlusPathGradientBrushOptionalData Class"
type: docs
weight: 510
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---

**Summary:** The EmfPlusPathGradientBrushOptionalData object specifies optional data for a path gradient brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData__1) | EmfPlusPathGradientBrushOptionalData sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| blend_pattern | [EmfPlusBlendBase](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/) | r/w | Yol gradient fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. Bu alan mevcutsa,<br/>            bir EmfPlusBlendColors nesnesi (bölüm 2.2.2.4) veya bir EmfPlusBlendFactors nesnesi (bölüm 2.2.2.5) içermelidir, ancak ikisini birden içermemelidir. <br/>            Aşağıdaki tablo, EmfPlusPathGradientBrushData<br/>            BrushData bayrakları ve ilgili karışım desenlerinin geçerli kombinasyonlarını gösterir: |
| focus_scale_data | [EmfPlusFocusScaleData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata/) | r/w | Yol gradient fırçası için odak ölçeklerini belirten isteğe bağlı bir EmfPlusFocusScaleData nesnesi (bölüm 2.2.2.18) alır veya ayarlar. Bu alan, <br/>            BrushDataFocusScales bayrağı BrushDataFlags alanında ayarlıysa EmfPlusPathGradientBrushData nesnesinde bulunmak ZORUNDADIR. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Yol gradient fırçası için dünya uzayından cihaz uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar. <br/>            Bu alan, EmfPlusPathGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa bulunmak ZORUNDADIR. |


### Constructor: EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData__1}


```
 EmfPlusPathGradientBrushOptionalData() 
```

EmfPlusPathGradientBrushOptionalData sınıfının yeni bir örneğini başlatır.

