---
title: "WmfBinaryRasterOperation"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BinaryRasterOperation Sıralaması bölümü, ikili raster-işlem kodlarını listeler."
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfBinaryRasterOperation extends System.Enum
```

BinaryRasterOperation Sıralama bölümü, ikili raster‑operasyon kodlarını listeler. Raster operasyon kodları, metafile işleme sürecinin seçilen kalemin bitlerini hedef bitmapin bitleriyle nasıl birleştirdiğini tanımlar.

--------------------

Her raster‑operasyon kodu, seçilen kalemdeki ve hedef bitmapteki piksellerin değerlerinin birleştirildiği bir Boolean (mantıksal) işlemi temsil eder. Aşağıda bu işlemlerde kullanılan iki operant yer almaktadır. Operant Anlamı P Seçilen kalem D Hedef bitmap a Bitwise AND (bit düzeyinde VE) n Bitwise NOT (ters) o Bitwise OR (bit düzeyinde VEYA) x Bitwise exclusive OR (XOR) (özel VEYA)
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [Black](#Black) | 0, Piksel her zaman 0'dır. |
| [Notmergepen](#Notmergepen) | DPon, Piksel MERGEPEN renginin tersidir |
| [Masknotpen](#Masknotpen) | DPna, Piksel ekran rengi ile kalem renginin tersinin bir kombinasyonudur. |
| [Notcopypen](#Notcopypen) | Pn, Piksel kalem renginin tersidir. |
| [Maskpennot](#Maskpennot) | PDna, Piksel hem kalemin hem de ekranın tersinin ortak renklerinin bir kombinasyonudur. |
| [Not](#Not) | Dn, Piksel ekran renginin tersidir. |
| [Xorpen](#Xorpen) | DPx, Piksel kalemdeki veya ekrandaki renklerin bir kombinasyonudur, ancak ikisinde birden değildir. |
| [Notmaskpen](#Notmaskpen) | DPan, Piksel MASKPEN renginin tersidir. |
| [Maskpen](#Maskpen) | DPa, Piksel hem kalemin hem de ekranın ortak renklerinin bir kombinasyonudur. |
| [Notxorpen](#Notxorpen) | DPxn, Piksel XORPEN renginin tersidir. |
| [Nop](#Nop) | D, Piksel değişmeden kalır. |
| [Mergenotpen](#Mergenotpen) | DPno, Piksel hem ekranın hem de kalemin tersinin ortak renklerinin bir kombinasyonudur. |
| [Copypen](#Copypen) | P, Piksel kalem rengidir. |
| [Mergepennot](#Mergepennot) | PDno, Piksel kalem rengi ile ekran renginin tersinin bir kombinasyonudur. |
| [Mergepen](#Mergepen) | DPo, Piksel kalem rengi ile ekran renginin bir kombinasyonudur. |
| [White](#White) | 1, Piksel her zaman 1'dir |
### Black {#Black}
```
public static final int Black
```


0, Piksel her zaman 0'dır.

### Notmergepen {#Notmergepen}
```
public static final int Notmergepen
```


DPon, Piksel MERGEPEN renginin tersidir

### Masknotpen {#Masknotpen}
```
public static final int Masknotpen
```


DPna, Piksel ekran rengi ile kalem renginin tersinin bir kombinasyonudur.

### Notcopypen {#Notcopypen}
```
public static final int Notcopypen
```


Pn, Piksel kalem renginin tersidir.

### Maskpennot {#Maskpennot}
```
public static final int Maskpennot
```


PDna, Piksel hem kalemin hem de ekranın tersinin ortak renklerinin bir kombinasyonudur.

### Not {#Not}
```
public static final int Not
```


Dn, Piksel ekran renginin tersidir.

### Xorpen {#Xorpen}
```
public static final int Xorpen
```


DPx, Piksel kalemdeki veya ekrandaki renklerin bir kombinasyonudur, ancak ikisinde birden değildir.

### Notmaskpen {#Notmaskpen}
```
public static final int Notmaskpen
```


DPan, Piksel MASKPEN renginin tersidir.

### Maskpen {#Maskpen}
```
public static final int Maskpen
```


DPa, Piksel hem kalemin hem de ekranın ortak renklerinin bir kombinasyonudur.

### Notxorpen {#Notxorpen}
```
public static final int Notxorpen
```


DPxn, Piksel XORPEN renginin tersidir.

### Nop {#Nop}
```
public static final int Nop
```


D, Piksel değişmeden kalır.

### Mergenotpen {#Mergenotpen}
```
public static final int Mergenotpen
```


DPno, Piksel hem ekranın hem de kalemin tersinin ortak renklerinin bir kombinasyonudur.

### Copypen {#Copypen}
```
public static final int Copypen
```


P, Piksel kalem rengidir.

### Mergepennot {#Mergepennot}
```
public static final int Mergepennot
```


PDno, Piksel kalem rengi ile ekran renginin tersinin bir kombinasyonudur.

### Mergepen {#Mergepen}
```
public static final int Mergepen
```


DPo, Piksel kalem rengi ile ekran renginin bir kombinasyonudur.

### White {#White}
```
public static final int White
```


1, Piksel her zaman 1'dir

