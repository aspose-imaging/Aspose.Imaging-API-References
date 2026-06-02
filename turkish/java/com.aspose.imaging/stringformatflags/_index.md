---
title: "StringFormatFlags"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Metin dizeleri için görüntüleme ve yerleşim bilgilerini belirtir."
type: docs
weight: 113
url: /tr/java/com.aspose.imaging/stringformatflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class StringFormatFlags extends System.Enum
```

Metin dizeleri için görüntüleme ve yerleşim bilgilerini belirtir.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [DirectionRightToLeft](#DirectionRightToLeft) | Metin sağdan sola görüntülenir. |
| [DirectionVertical](#DirectionVertical) | Metin dikey olarak hizalanır. |
| [FitBlackBox](#FitBlackBox) | Karakterlerin bazı bölümlerinin dize yerleşim dikdörtgeninin dışına taşmasına izin verilir. |
| [DisplayFormatControl](#DisplayFormatControl) | Sol‑sağ işareti gibi kontrol karakterleri, çıktıda temsilci bir glif ile gösterilir. |
| [NoFontFallback](#NoFontFallback) | İstenen yazı tipinde desteklenmeyen karakterler için alternatif yazı tiplerine geçiş devre dışı bırakılmıştır. |
| [MeasureTrailingSpaces](#MeasureTrailingSpaces) | Her satırın sonundaki boşluk dahil edilir. |
| [NoWrap](#NoWrap) | Metnin bir dikdörtgen içinde biçimlendirilirken satırlar arasındaki kaydırma devre dışı bırakılır. |
| [LineLimit](#LineLimit) | Biçimlendirme dikdörtgeninde yalnızca tam satırlar yerleştirilir. |
| [NoClip](#NoClip) | Gliflerin taşan bölümleri ve biçimlendirme dikdörtgeninin dışına çıkan kaydırılmamış metin gösterilmesine izin verilir. |
| [ExactAlignment](#ExactAlignment) | Tam hizalama, doğru doldurma GDI+ |
### DirectionRightToLeft {#DirectionRightToLeft}
```
public static final int DirectionRightToLeft
```


Metin sağdan sola görüntülenir.

### DirectionVertical {#DirectionVertical}
```
public static final int DirectionVertical
```


Metin dikey olarak hizalanır.

### FitBlackBox {#FitBlackBox}
```
public static final int FitBlackBox
```


Karakterlerin bazı bölümlerinin dize yerleşim dikdörtgeninin dışına taşmasına izin verilir. Varsayılan olarak, karakterler herhangi bir taşmayı önlemek için yeniden konumlandırılır.

### DisplayFormatControl {#DisplayFormatControl}
```
public static final int DisplayFormatControl
```


Sol‑sağ işareti gibi kontrol karakterleri, çıktıda temsilci bir glif ile gösterilir.

### NoFontFallback {#NoFontFallback}
```
public static final int NoFontFallback
```


İstenen yazı tipinde desteklenmeyen karakterler için alternatif yazı tiplerine geçiş devre dışı bırakılmıştır. Eksik karakterler, genellikle açık bir kare olan eksik glif ile gösterilir.

### MeasureTrailingSpaces {#MeasureTrailingSpaces}
```
public static final int MeasureTrailingSpaces
```


Her satırın sonundaki boşluk dahil edilir. Varsayılan olarak MeasureString yöntemi tarafından döndürülen sınır dikdörtgeni, her satırın sonundaki boşluğu dışarıda bırakır. Bu bayrağı ayarlayarak ölçümde bu boşluğu dahil edin.

### NoWrap {#NoWrap}
```
public static final int NoWrap
```


Metnin bir dikdörtgen içinde biçimlendirilirken satırlar arasındaki kaydırma devre dışı bırakılır. Bu bayrak, bir dikdörtgen yerine bir nokta geçirildiğinde veya belirtilen dikdörtgenin satır uzunluğu sıfır olduğunda otomatik olarak uygulanır.

### LineLimit {#LineLimit}
```
public static final int LineLimit
```


Biçimlendirme dikdörtgeninde yalnızca tam satırlar yerleştirilir. Varsayılan olarak, yerleşim metnin sonuna kadar veya kırpma sonucu daha fazla satır görünmez olana kadar devam eder, hangisi önce gelirse. Varsayılan ayarlar, satır yüksekliğinin tam katı olmayan bir biçimlendirme dikdörtgeni tarafından son satırın kısmen gizlenmesine izin verir. Yalnızca tam satırların görülmesini sağlamak için bu değeri belirtin ve bir satır yüksekliğine en az kadar yüksek bir biçimlendirme dikdörtgeni sağlamaya dikkat edin.

### NoClip {#NoClip}
```
public static final int NoClip
```


Gliflerin taşan bölümleri ve biçimlendirme dikdörtgeninin dışına çıkan kaydırılmamış metin gösterilmesine izin verilir. Varsayılan olarak, biçimlendirme dikdörtgeninin dışına çıkan tüm metin ve glif bölümleri kırpılır.

### ExactAlignment {#ExactAlignment}
```
public static final int ExactAlignment
```


Tam hizalama, doğru doldurma GDI+

