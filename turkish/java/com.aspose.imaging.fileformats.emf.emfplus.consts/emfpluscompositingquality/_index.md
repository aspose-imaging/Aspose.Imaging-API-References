---
title: "EmfPlusCompositingQuality"
second_title: "Aspose.Imaging for Java API Referansı"
description: "CompositingQuality enumarasyonu, birleşik görüntüler oluşturma kalitesi seviyelerini tanımlar."
type: docs
weight: 15
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

CompositingQuality enumarasyonu, birleşik görüntüler oluşturma kalitesi seviyelerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | Gamma düzeltmesi uygulanmaz. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | Gamma düzeltmesi uygulanmaz. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | Gamma düzeltmesi uygulanır. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | Daha yüksek kalite kompozisyon için daha düşük hızda gamma düzeltmesini etkinleştir. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | Gamma düzeltmesi uygulanmaz; ancak, lineer değerlerin kullanılması varsayılandan biraz daha düşük hızda daha iyi kalite sağlar. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


Gamma düzeltmesi uygulanmaz. Gamma düzeltmesi bir görüntünün genel parlaklık ve kontrastını kontrol eder. Gamma düzeltmesi olmadan, birleştirilmiş görüntüler çok aydınlık veya çok karanlık görünebilir.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


Gamma düzeltmesi uygulanmaz. Kompozisyon hızı kalite pahasına tercih edilir. Sonuç açısından, bu değer ile CompositingQualityDefault arasında bir fark yoktur.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


Gamma düzeltmesi uygulanır. Kompozisyon kalitesi hız pahasına tercih edilir.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


Daha yüksek kalite kompozisyon için daha düşük hızda gamma düzeltmesini etkinleştir. Sonuç açısından, bu değer ile CompositingQualityHighQuality arasında bir fark yoktur.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


Gamma düzeltmesi uygulanmaz; ancak, lineer değerlerin kullanılması varsayılandan biraz daha düşük hızda daha iyi kalite sağlar.

