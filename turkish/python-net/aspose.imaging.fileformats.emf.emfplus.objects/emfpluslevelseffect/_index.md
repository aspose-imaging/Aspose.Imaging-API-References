---
title: "EmfPlusLevelsEffect Sınıf"
type: docs
weight: 420
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluslevelseffect/
---

**Summary:** The LevelsEffect object specifies adjustments to the highlights, midtones, and shadows of an image.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusLevelsEffect

**Inheritance:** EmfPlusImageEffectsObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusLevelsEffect()](#EmfPlusLevelsEffect__1) | EmfPlusLevelsEffect sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| vurgula | int | r/w | Alır veya ayarlar: Görüntünün vurgularını ne kadar aydınlatacağını belirtir. Renk<br/>            kanal değerleri, yoğunluk aralığının yüksek ucunda, orta veya düşük uçlara yakın değerlere göre daha fazla değiştirilir; bu, görüntünün daha karanlık bölümlerinin kontrastını kaybetmeden aydınlatılabileceği anlamına gelir.<br/>            0 ≤ değer &lt; Bu eşik değerinin üzerindeki yüzde yoğunlukta vurguların ARTIŞ göstermesi GEREKİR.<br/>            100 Vurguların DEĞİŞMEMESİ gerekir. |
| mid_tone | int | r/w | Alır veya ayarlar: Görüntünün orta tonlarını ne kadar aydınlatacağını veya karartacağını belirtir. Renk<br/>            kanal değerleri, yoğunluk aralığının ortasında, yüksek veya düşük uçlara yakın değerlere göre daha fazla değiştirilir; bu, görüntünün en karanlık ve en aydınlık bölümlerinin kontrastını kaybetmeden aydınlatılıp karartılabileceği anlamına gelir.<br/>            -100 ≤ değer &lt; 0 Orta tonların daha karanlık yapılacağını belirtir.<br/>            0 Orta tonların DEĞİŞMEMESİ gerekir.<br/>            0 &lt; değer ≤ 100 Orta tonların daha aydınlık yapılacağını belirtir. |
| shadow | int | r/w | Alır veya ayarlar: Görüntünün gölgelerini ne kadar karartacağını belirtir. Renk kanal değerleri, yoğunluk aralığının düşük ucunda, orta veya yüksek uçlara yakın değerlere göre daha fazla değiştirilir; bu, görüntünün daha açık bölümlerinin kontrastını kaybetmeden karartılabileceği anlamına gelir.<br/>            0 Gölgelerin DEĞİŞMEMESİ gerekir.<br/>            0 &lt; değer ≤ 100<br/>            Bu eşik değerinin altındaki yüzde yoğunlukta gölgelerin daha karanlık yapılacağını belirtir. |


### Constructor: EmfPlusLevelsEffect() {#EmfPlusLevelsEffect__1}


```
 EmfPlusLevelsEffect() 
```

EmfPlusLevelsEffect sınıfının yeni bir örneğini başlatır.

