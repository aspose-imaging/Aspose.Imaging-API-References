---
title: "EmfPlusBlurEffect Sınıfı"
type: docs
weight: 100
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusblureffect/
---

**Summary:** The BlurEffect object specifies a decrease in the difference in intensity between pixels in an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlurEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusBlurEffect()](#EmfPlusBlurEffect__1) | EmfPlusBlurEffect sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| blur_radius | float | r/w | Alır veya ayarlar bulanıklaştırma yarıçapını piksel cinsinden belirten 32-bit kayan nokta sayısı,<br/>bu, verilen bir pikselin yeni değerinin hesaplanmasında kullanılan piksel sayısını belirler.<br/>Bu değer 0.0 ile 255.0 arasında olmalıdır. |
| expand_edge | bool | r/w | Alır veya ayarlar 32-bit Boolean değer, bitmap'in yumuşak kenarlar üretmek için BlurRadius değerine eşit bir miktarda genişleyip genişlemeyeceğini belirtir. Bu değer AŞAĞIDAKİLERDEN BİRİ OLMALIDIR:<br/>FALSE<br/>0x00000000<br/>Bitmap'in boyutu DEĞİŞMEMELİ ve yumuşak kenarları BlurRadius'un boyutuna kırpılmalıdır.<br/>TRUE<br/>0x00000001<br/>Bitmap'in boyutu BlurRadius'a eşit bir miktarda genişlemeli ve yumuşak kenarlar üretmelidir. |


### Constructor: EmfPlusBlurEffect() {#EmfPlusBlurEffect__1}


```
 EmfPlusBlurEffect() 
```

EmfPlusBlurEffect sınıfının yeni bir örneğini başlatır.

