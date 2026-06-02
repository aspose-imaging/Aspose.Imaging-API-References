---
title: "EmfPlusPathPointFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini nasıl yorumlayacağını belirten 32-bit işaretsiz tam sayı."
type: docs
weight: 38
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspathpointflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPathPointFlags extends System.Enum
```

Bu nesne tarafından tanımlanan noktaları ve ilişkili nokta türlerini yorumlamayı belirten 32 bit işaretsiz tamsayı. C (1 bit): Ayarlanmışsa, PathPoints dizisi 16 bit tamsayı koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Temizlenmişse, PathPoints dizisi 32 bit kayan nokta koordinatlarıyla koordinat uzayında mutlak konumları belirtir. Not: Aşağıdaki P bayrağı ayarlanmışsa, bu bayrak KAPALI olabilir ve GÖZARDEN DİŞARIDA bırakılmalıdır. R (1 bit): Ayarlanmışsa, PathPointTypes dizisindeki nokta türleri EmfPlusPathPointTypeRle nesneleri (bölüm 2.2.2.32) tarafından, run‑length encoding (RLE) sıkıştırması kullanılarak ve/veya EmfPlusPathPointType nesneleri (bölüm 2.2.2.31) tarafından belirtilir. RLE sıkıştırması hakkında daha fazla bilgi için [MS-WMF] bölüm 3.1.6'ya bakınız. Temizlenmişse, PathPointTypes dizisindeki nokta türleri EmfPlusPathPointType nesneleri tarafından belirtilir. P (1 bit): Ayarlanmışsa, PathPoints dizisindeki her öğe, dizideki önceki öğe tarafından belirtilen konuma göre koordinat uzayında bir konum belirtir. PathPoints içindeki ilk öğe için, (0,0) koordinatlarında bir önceki konum varsayılır. Temizlenmişse, PathPoints dizisindeki her öğe mutlak bir konum belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [C](#C) | c bayrağı |
| [R](#R) | r bayrağı |
| [P](#P) | p bayrağı |
### C {#C}
```
public static final short C
```


c bayrağı

### R {#R}
```
public static final short R
```


r bayrağı

### P {#P}
```
public static final short P
```


p bayrağı

