---
title: "EmfExtTextOutOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "ExtTextOutOptions sayımı, EMR_SMALLTEXTOUTsection 2.3.5.37 kayıtları ve EmrText nesnelerinde metin çıktısının çeşitli yönlerini kontrol eden parametreleri belirtir."
type: docs
weight: 19
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfExtTextOutOptions extends System.Enum
```

ExtTextOutOptions sayımı, EMR\_SMALLTEXTOUT (bölüm 2.3.5.37) kayıtları ve EmrText nesneleri tarafından metin çıktısının çeşitli yönlerini kontrol eden parametreleri belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ETO_OPAQUE](#ETO-OPAQUE) | Bu bit, mevcut arka plan renginin dikdörtgeni doldurmak için SHOULD kullanılacağını gösterir. |
| [ETO_CLIPPED](#ETO-CLIPPED) | Bu bit, metnin dikdörtgene kırpılması gerektiğini (SHOULD) gösterir. |
| [ETO_GLYPH_INDEX](#ETO-GLYPH-INDEX) | Bu bit, çıktı metin dizesindeki karakter kodlarının aslında TrueType yazı tipindeki karakter gliflerinin indeksleri olduğunu gösterir. |
| [ETO_RTLREADING](#ETO-RTLREADING) | Bu bit, metnin varsayılan soldan sağa sıralama yerine sağdan sola okuma düzeninde (MUST) yerleştirilmesi gerektiğini gösterir. |
| [ETO_NO_RECT](#ETO-NO-RECT) | Bu bit, kaydın metin çıktısı için bir sınırlayıcı dikdörtgen belirtmediğini gösterir. |
| [ETO_SMALL_CHARS](#ETO-SMALL-CHARS) | Bu bit, çıktı metin dizesindeki karakter kodlarının 8 bit olduğunu, 16 bitlik Unicode UTF16-LE karakter kodlarının düşük baytlarından türetildiğini ve yüksek baytın 0 varsayıldığını gösterir. |
| [ETO_NUMERICSLOCAL](#ETO-NUMERICSLOCAL) | Bu bit, sayıları görüntülerken yerel ayara uygun rakamların (SHOULD) kullanılmasını gösterir. |
| [ETO_NUMERICSLATIN](#ETO-NUMERICSLATIN) | Bu bit, sayıları görüntülerken Avrupa rakamlarının (SHOULD) kullanılmasını gösterir. |
| [ETO_IGNORELANGUAGE](#ETO-IGNORELANGUAGE) | Bu bit, sağdan sola dizeler için glif yerleştirme konusunda özel bir işletim sistemi işleme yapılmaması gerektiğini; yani tüm glif konumlandırmasının metafildeki çizim ve durum kayıtları tarafından (SHOULD) halledilmesi gerektiğini gösterir. |
| [ETO_PDY](#ETO-PDY) | Bu bit, hem yatay hem de dikey karakter yer değiştirme değerlerinin (SHOULD) sağlanması gerektiğini gösterir. |
| [ETO_REVERSE_INDEX_MAP](#ETO-REVERSE-INDEX-MAP) | Bu bit ayrılmıştır ve (SHOULD NOT) kullanılmamalıdır. |
### ETO_OPAQUE {#ETO-OPAQUE}
```
public static final int ETO_OPAQUE
```


Bu bit, mevcut arka plan renginin dikdörtgeni doldurmak için SHOULD kullanılacağını gösterir.

### ETO_CLIPPED {#ETO-CLIPPED}
```
public static final int ETO_CLIPPED
```


Bu bit, metnin dikdörtgene kırpılması gerektiğini (SHOULD) gösterir.

### ETO_GLYPH_INDEX {#ETO-GLYPH-INDEX}
```
public static final int ETO_GLYPH_INDEX
```


Bu bit, çıktı metin dizesindeki karakter kodlarının aslında TrueType yazı tipindeki karakter gliflerinin indeksleri olduğunu gösterir. Glif indeksleri yazı tipine özgüdür, bu nedenle oynatma sırasında doğru karakterlerin görüntülenebilmesi için kullanılan yazı tipinin (MUST) indeksleri oluşturan yazı tipiyle aynı olması gerekir.

### ETO_RTLREADING {#ETO-RTLREADING}
```
public static final int ETO_RTLREADING
```


Bu bit, metnin varsayılan soldan sağa sıralama yerine sağdan sola okuma düzeninde (MUST) yerleştirilmesi gerektiğini gösterir. Bu (SHOULD) yalnızca oynatma aygıt bağlamına seçilen yazı tipi İbranice veya Arapça olduğunda uygulanmalıdır.

### ETO_NO_RECT {#ETO-NO-RECT}
```
public static final int ETO_NO_RECT
```


Bu bit, kaydın metin çıktısı için bir sınırlayıcı dikdörtgen belirtmediğini gösterir.

### ETO_SMALL_CHARS {#ETO-SMALL-CHARS}
```
public static final int ETO_SMALL_CHARS
```


Bu bit, çıktı metin dizesindeki karakter kodlarının 8 bit olduğunu, 16 bitlik Unicode UTF16-LE karakter kodlarının düşük baytlarından türetildiğini ve yüksek baytın 0 varsayıldığını gösterir.

### ETO_NUMERICSLOCAL {#ETO-NUMERICSLOCAL}
```
public static final int ETO_NUMERICSLOCAL
```


Bu bit, sayıları görüntülerken yerel ayara uygun rakamların (SHOULD) kullanılmasını gösterir.

### ETO_NUMERICSLATIN {#ETO-NUMERICSLATIN}
```
public static final int ETO_NUMERICSLATIN
```


Bu bit, sayıları görüntülerken Avrupa rakamlarının (SHOULD) kullanılmasını gösterir.

### ETO_IGNORELANGUAGE {#ETO-IGNORELANGUAGE}
```
public static final int ETO_IGNORELANGUAGE
```


Bu bit, sağdan sola dizeler için glif yerleştirme konusunda özel bir işletim sistemi işleme yapılmaması gerektiğini; yani tüm glif konumlandırmasının metafildeki çizim ve durum kayıtları tarafından (SHOULD) halledilmesi gerektiğini gösterir.

### ETO_PDY {#ETO-PDY}
```
public static final int ETO_PDY
```


Bu bit, hem yatay hem de dikey karakter yer değiştirme değerlerinin (SHOULD) sağlanması gerektiğini gösterir.

### ETO_REVERSE_INDEX_MAP {#ETO-REVERSE-INDEX-MAP}
```
public static final int ETO_REVERSE_INDEX_MAP
```


Bu bit ayrılmıştır ve (SHOULD NOT) kullanılmamalıdır.

