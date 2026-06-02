---
title: "EmfPlusStringFormatFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "StringFormat bayrakları, yön, kırpma ve yazı tipi işleme dahil olmak üzere grafik metin yerleşimi için seçenekleri belirtir."
type: docs
weight: 50
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusStringFormatFlags extends System.Enum
```

StringFormat bayrakları, yön, kırpma ve yazı tipi işleme dahil olmak üzere grafik metin yerleşimi için seçenekleri belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [StringFormatDirectionRightToLeft](#StringFormatDirectionRightToLeft) | Ayarlanırsa, dizenin okuma sırası SAĞDAN SOLA olmalıdır. |
| [StringFormatDirectionVertical](#StringFormatDirectionVertical) | Ayarlanırsa, metnin bireysel satırları görüntü cihazında dikey olarak çizilmelidir. |
| [StringFormatNoFitBlackBox](#StringFormatNoFitBlackBox) | Ayarlanırsa, karakterlerin bölümlerinin metin yerleşim dikdörtgeninin dışına taşmasına İZİN verilmelidir. |
| [StringFormatDisplayFormatControl](#StringFormatDisplayFormatControl) | Ayarlanırsa, kontrol karakterleri çıktıda temsilci Unicode glifleri olarak görünmelidir. |
| [StringFormatNoFontFallback](#StringFormatNoFontFallback) | Ayarlanırsa, istenen yazı tipinde desteklenmeyen karakterler için alternatif bir yazı tipi KULLANILMALIDIR. |
| [StringFormatMeasureTrailingSpaces](#StringFormatMeasureTrailingSpaces) | Ayarlanırsa, her satırın sonundaki boşluk dize uzunluğu ölçümlerine DÂHİL edilmelidir. |
| [StringFormatNoWrap](#StringFormatNoWrap) | Ayarlanırsa, metin yerleşim dikdörtgeninin sonunu aşan bir dize bir sonraki satıra SARILMAMALIDIR. |
| [StringFormatLineLimit](#StringFormatLineLimit) | Ayarlanırsa, metnin bütün satırları çıktılanmalı ve dize yerleşim dikdörtgeni tarafından kırpılmamalıdır. |
| [StringFormatNoClip](#StringFormatNoClip) | Ayarlanırsa, dize yerleşim dikdörtgeninin dışına uzanan metnin gösterilmesine izin verilmelidir. |
| [StringFormatBypassGdi](#StringFormatBypassGdi) | Bu bayrak, metin işleme için uygulamaya özgü bir süreç belirtmek üzere KULLANILABİLİR. |
### StringFormatDirectionRightToLeft {#StringFormatDirectionRightToLeft}
```
public static final long StringFormatDirectionRightToLeft
```


Ayarlanırsa, dize okuma sırası SAĞDAN SOLA olmalıdır. Yatay metin için bu, karakterlerin sağdan sola okunduğu anlamına gelir. Dikey metin için bu, sütunların sağdan sola okunduğu anlamına gelir. Temizlenirse, yatay veya dikey metin SOLDAN SAĞA okunmalıdır.

--------------------

Grafik metin yerleşimi, [EmfPlusStringFormat](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat) nesneleri tarafından belirtilir

### StringFormatDirectionVertical {#StringFormatDirectionVertical}
```
public static final long StringFormatDirectionVertical
```


Ayarlanırsa, metnin bireysel satırları görüntü cihazında dikey olarak çizilmelidir. Temizlenirse, metnin bireysel satırları yatay olarak çizilmeli ve her yeni satır önceki satırın altında olmalıdır.

### StringFormatNoFitBlackBox {#StringFormatNoFitBlackBox}
```
public static final long StringFormatNoFitBlackBox
```


Ayarlanırsa, karakterlerin bölümlerinin metin yerleşim dikdörtgeninin dışına taşmasına İZİN verilmelidir. Temizlenirse, metin yerleşim dikdörtgeninin sınırlarını aşan karakterler taşmayı önlemek için yeniden konumlandırılmalıdır. İtalik bir "f", taşan bölümlere sahip olabilen bir karakter örneğidir.

### StringFormatDisplayFormatControl {#StringFormatDisplayFormatControl}
```
public static final long StringFormatDisplayFormatControl
```


Ayarlanırsa, kontrol karakterleri çıktıda temsilci Unicode glifleri olarak görünmelidir.

### StringFormatNoFontFallback {#StringFormatNoFontFallback}
```
public static final long StringFormatNoFontFallback
```


Ayarlanırsa, istenen yazı tipinde desteklenmeyen karakterler için alternatif bir yazı tipi KULLANILMALIDIR. Temizlenirse, istenen yazı tipinde eksik bir karakter "yazı tipi eksik" karakteri olarak görünmelidir; bu, açık bir kare olabilir.

### StringFormatMeasureTrailingSpaces {#StringFormatMeasureTrailingSpaces}
```
public static final long StringFormatMeasureTrailingSpaces
```


Ayarlanırsa, her satırın sonundaki boşluk dize uzunluğu ölçümlerine DÂHİL edilmelidir. Temizlenirse, her satırın sonundaki boşluk dize uzunluğu ölçümlerinden ÇIKARILMALIDIR.

### StringFormatNoWrap {#StringFormatNoWrap}
```
public static final long StringFormatNoWrap
```


Ayarlanırsa, metin yerleşim dikdörtgeninin sonunu aşan bir dize bir sonraki satıra SARILMAMALIDIR. Temizlenirse, metin yerleşim dikdörtgeninin sonunu aşan bir dize, sınırlayıcı dikdörtgen içindeki son kelime sınırında bölünmeli ve dizenin geri kalanı bir sonraki satıra SARILMALIDIR.

### StringFormatLineLimit {#StringFormatLineLimit}
```
public static final long StringFormatLineLimit
```


Ayarlanırsa, metnin bütün satırları çıktılanmalı ve dize yerleşim dikdörtgeni tarafından kırpılmamalıdır. Temizlenirse, metin yerleşimi tüm satırlar çıktılanana kadar veya ek satırlar kırpma nedeniyle görünmez olana kadar devam etmelidir. Bu bayrak, satır yüksekliğinin katı olmayan bir yerleşim dikdörtgeni tarafından metnin kısmen gizlenmesine izin vermek veya engellemek için kullanılabilir. Tüm metnin görünür olması için, yerleşim dikdörtgeni en az bir satır yüksekliğinde olmalıdır.

### StringFormatNoClip {#StringFormatNoClip}
```
public static final long StringFormatNoClip
```


Ayarlanırsa, dize yerleşim dikdörtgeninin dışına uzanan metnin gösterilmesine izin verilmelidir. Temizlenirse, yerleşim dikdörtgeninin dışına uzanan tüm metin KIRPILMALIDIR.

### StringFormatBypassGdi {#StringFormatBypassGdi}
```
public static final long StringFormatBypassGdi
```


Bu bayrak, metin işleme için uygulamaya özgü bir süreç belirtmek üzere KULLANILABİLİR.

