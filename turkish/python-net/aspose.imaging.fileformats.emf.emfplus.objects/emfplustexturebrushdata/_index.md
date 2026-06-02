---
title: "EmfPlusTextureBrushData Sınıfı"
type: docs
weight: 680
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---

**Summary:** The EmfPlusTextureBrushData object specifies a texture image for a graphics brush.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushData

**Inheritance:** EmfPlusBaseBrushData

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData__1) | EmfPlusTextureBrushData sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| brush_data_flags | [EmfPlusBrushDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusbrushdataflags/) | r/w | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tam sayı alır veya ayarlar. <br/>            Bu değer BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. <br/>            Aşağıdaki bayraklar bir doku fırçası için ilgilidir<br/>            BrushDataTransform<br/>            BrushDataIsGammaCorrected<br/>            BrushDataDoNotTransform |
| optional_data | [EmfPlusTextureBrushOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/) | r/w | Doku fırçası için ek veri belirten isteğe bağlı bir EmfPlusTextureBrushOptionalData nesnesi (bölüm 2.2.2.46) alır veya ayarlar. <br/>            Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | WrapMode sayımından (bölüm 2.1.1.34) 32 bit işaretli tam sayı alır veya ayarlar <br/>            bu, görüntü doldurulan alandan daha küçük olduğunda doku görüntüsünün bir şekil üzerinde nasıl tekrarlanacağını belirler. |


### Constructor: EmfPlusTextureBrushData() {#EmfPlusTextureBrushData__1}


```
 EmfPlusTextureBrushData() 
```

EmfPlusTextureBrushData sınıfının yeni bir örneğini başlatır

