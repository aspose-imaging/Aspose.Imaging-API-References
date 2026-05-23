---
title: "EmfPlusColorCurveEffect Class"
type: docs
weight: 180
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscolorcurveeffect/
---

**Summary:** The ColorCurveEffect object specifies one of eight adjustments to the color curve of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusColorCurveEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusColorCurveEffect()](#EmfPlusColorCurveEffect__1) | EmfPlusColorCurveEffect sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| adjustment_intensity | int | r/w | Alır veya ayarlar: CurveChannel tarafından belirtilen renk kanalına eğri ayarlamasının şiddetini belirten 32‑bit işaretli tamsayı. Bu alan için anlamlı değer aralıkları, CurveAdjustment değerine göre aşağıdaki gibi değişir:<br/>            Pozlama ayarlama aralığı:<br/>            -255 ≤ değer &lt; 0 Değer azaldıkça, görüntünün pozlaması AZALMALI.<br/>            0 Değer 0, pozlamanın DEĞİŞMEMESİ gerektiğini belirtir.<br/>            0 &lt; değer ≤ 255 Değer arttıkça, görüntünün pozlaması ARTMALI.<br/>            Yoğunluk ayarlama aralığı:<br/>            -255 ≤ değer &lt; 0 Değer azaldıkça, görüntünün yoğunluğu AZALMALI ve daha karanlık bir görüntü elde edilir.<br/>            0 Değer 0, yoğunluğun DEĞİŞMEMESİ gerektiğini belirtir.<br/>            0 &lt; değer ≤ 255 Değer arttıkça, görüntünün yoğunluğu ARTMALI.<br/>            Kontrast ayarlama aralığı:<br/>            -100 ≤ değer &lt; 0 Değer azaldıkça, görüntünün kontrastı AZALMALI.<br/>            0 Değer 0, kontrastın DEĞİŞMEMESİ gerektiğini belirtir.<br/>            0 &lt; değer ≤ 100 Değer arttıkça, görüntünün kontrastı ARTMALI.<br/>            Vurgulama ayarlama aralığı:<br/>            -100 ≤ değer &lt; 0 Değer azaldıkça, görüntünün aydınlık bölgeleri daha karanlık görünmelidir.<br/>            0 Değer 0, vurgunun DEĞİŞMEMESİ gerektiğini belirtir.<br/>            0 &lt; değer ≤ 100 Değer arttıkça, görüntünün aydınlık bölgeleri daha aydınlık görünmelidir.<br/>            Gölge ayarlama aralığı:<br/>            -100 ≤ değer &lt; 0 Değer azaldıkça, görüntünün karanlık bölgeleri daha karanlık görünmelidir.<br/>            0 Değer 0, gölgenin DEĞİŞMEMESİ gerektiğini belirtir.<br/>            0 &lt; değer ≤ 100 Değer arttıkça, görüntünün karanlık bölgeleri daha aydınlık görünmelidir.<br/>            Beyaz doygunluk ayarlama aralığı:<br/>            0 — 255 Değer arttıkça, renk kanal yoğunluk aralığının üst sınırı artar.<br/>            Siyah doygunluk ayarlama aralığı:<br/>            0 — 255 Değer arttıkça, renk kanal yoğunluk aralığının alt sınırı artar. |
| curve_adjustment | [EmfPlusCurveAdjustments](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurveadjustments/) | r/w | Alır veya ayarlar: Bit eşlemdeki renklere uygulanacak eğri ayarlamasını belirten 32‑bit işaretsiz tamsayı. Bu değer, CurveAdjustments<br/>            enumeration (section 2.1.1.7) içinde TANIMLANMALIDIR. |
| curve_channel | [EmfPlusCurveChannel](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscurvechannel/) | r/w | Alır veya ayarlar: Eğri ayarlamasının uygulanacağı renk kanalını belirten 32‑bit işaretsiz tamsayı. Bu değer, CurveChannel<br/>            enumeration (section 2.1.1.8) içinde TANIMLANMALIDIR. |


### Constructor: EmfPlusColorCurveEffect() {#EmfPlusColorCurveEffect__1}


```
 EmfPlusColorCurveEffect() 
```

EmfPlusColorCurveEffect sınıfının yeni bir örneğini başlatır

