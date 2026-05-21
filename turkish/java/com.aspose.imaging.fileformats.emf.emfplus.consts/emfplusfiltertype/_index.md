---
title: "EmfPlusFilterType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "FilterType sayımı, metin ve grafik kalitesini artırmak ve görüntü oluşturmak için kullanılabilecek filtreleme algoritması türlerini tanımlar."
type: docs
weight: 22
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

FilterType sayımı, metin ve grafik kalitesini artırmak ve görüntü oluşturmak için kullanılabilecek filtreleme algoritması türlerini tanımlar.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | Filtrelemenin yapılmadığını belirtir. |
| [FilterTypePoint](#FilterTypePoint) | Her hedef pikselin, kaynak görüntüden en yakın piksel örneklenerek hesaplandığını belirtir. |
| [FilterTypeLinear](#FilterTypeLinear) | Doğrusal enterpolasyonun, kaynak pikseli çevreleyen 2x2 piksel alanının ağırlıklı ortalaması kullanılarak yapıldığını belirtir. |
| [FilterTypeTriangle](#FilterTypeTriangle) | Kaynak görüntüdeki her pikselin hedef görüntüye eşit katkıda bulunduğunu belirtir. |
| [FilterTypeBox](#FilterTypeBox) | Her hedef pikselin, bir kaynak piksel dikdörtgeninin ortalaması alınarak hesaplandığı bir kutu filtre algoritmasını belirtir. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | 4 örnekli çadır filtresinin kullanıldığını belirtir. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | 4 örnekli Gaussian filtresinin kullanıldığını, bunun da bir görüntüde bulanıklaştırma etkisi yarattığını belirtir. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


Filtrelemenin yapılmadığını belirtir.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


Her hedef pikselin, kaynak görüntüden en yakın piksel örneklenerek hesaplandığını belirtir.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


Doğrusal enterpolasyonun, kaynak pikseli çevreleyen 2x2 piksel alanının ağırlıklı ortalaması kullanılarak yapıldığını belirtir.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


Kaynak görüntüdeki her pikselin hedef görüntüye eşit katkıda bulunduğunu belirtir. Bu, filtreleme algoritmalarının en yavaş olanıdır.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


Bir kutu filtresi algoritmasını belirtir; bu algoritmada her hedef piksel, kaynak piksellerin bir dikdörtgeninin ortalamasını alarak hesaplanır. Bu algoritma yalnızca bir görüntünün boyutunu küçültürken yararlıdır.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


4 örnekli çadır filtresinin kullanıldığını belirtir.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


4 örnekli Gaussian filtresinin kullanıldığını, bunun da bir görüntüde bulanıklaştırma etkisi yarattığını belirtir.

