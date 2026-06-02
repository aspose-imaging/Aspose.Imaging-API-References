---
title: "EmfPlusLineCapType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LineCapType sayımı, grafik kalemlerle çizilen çizgilerin uçlarında kullanılacak çizgi ucu türlerini tanımlar."
type: docs
weight: 31
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

LineCapType sayımı, grafik kalemlerle çizilen çizgilerin uçlarında kullanılacak çizgi ucu türlerini tanımlar.

--------------------

Grafik çizgi uçları, [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) nesneleri (bölüm 2.2.1.7) tarafından belirtilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | Kare kesimli bir çizgi ucu belirtir. |
| [LineCapTypeSquare](#LineCapTypeSquare) | Kare bir çizgi kapağı belirtir. |
| [LineCapTypeRound](#LineCapTypeRound) | Dairesel bir çizgi ucu belirtir. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | Üçgen bir çizgi kapağı belirtir. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | Çizgi ucunun sabitlenmediğini belirtir. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | Çizgi ucunun kare bir çizgi ucu ile sabitlendiğini belirtir. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | Çizgi ucunun dairesel bir çizgi ucu ile sabitlendiğini belirtir. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | Çizgi ucunun 45 derece döndürülmüş bir kare olan elmas şekilli bir çizgi ucu ile sabitlendiğini belirtir. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | Çizgi ucunun ok başı şekliyle sabitlendiğini belirtir. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | Bir çizgi ucunun sabitleme ucu olup olmadığını kontrol etmek için kullanılan maske. |
| [LineCapTypeCustom](#LineCapTypeCustom) | Özel bir çizgi kapağını belirtir. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


Kare kesimli bir çizgi ucu belirtir. Çizginin ucu, çizgideki son nokta OLMALIDIR.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


Kare bir çizgi ucu belirtir. Karenin merkezi, çizgideki son noktada BULUNMALIDIR. Karenin genişliği, çizgi genişliğidir.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


Dairesel bir çizgi ucu belirtir. Dairenin merkezi, çizgideki son noktada BULUNMALIDIR. Dairenin çapı, çizgi genişliğidir.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


Üçgen bir çizgi ucu belirtir. Üçgenin tabanı, çizgideki son noktada BULUNMALIDIR. Üçgenin tabanı, çizgi genişliğidir.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


Çizgi ucunun sabitlenmediğini belirtir.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


Çizgi ucunun kare bir çizgi ucu ile sabitlendiğini belirtir. Karenin merkezi, çizgideki son noktada BULUNMALIDIR. Karenin yüksekliği ve genişliği, çizgi genişliğidir.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


Çizgi ucunun dairesel bir çizgi ucu ile sabitlendiğini belirtir. Dairenin merkezi, çizgideki son noktada BULUNMALIDIR. Dairenin çizgiden daha geniş OLMASI GEREKİR.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


Çizgi ucunun 45 derece döndürülmüş bir kare olan elmas şekilli bir çizgi ucu ile sabitlendiğini belirtir. Elmasın merkezi, çizgideki son noktada BULUNMALIDIR. Elmasın çizgiden daha geniş OLMASI GEREKİR.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


Çizgi ucunun ok başı şekliyle sabitlendiğini belirtir. Ok başının ucu, çizgideki son noktada BULUNMALIDIR. Ok başının çizgiden daha geniş OLMASI GEREKİR.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


Bir çizgi ucunun sabitleme ucu olup olmadığını kontrol etmek için kullanılan maske.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


Özel bir çizgi kapağını belirtir.

