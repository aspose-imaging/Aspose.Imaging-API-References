---
title: EmfPlusStringFormatFlags
second_title: Aspose.Imaging for .NET API Referansı
description: StringFormat bayrakları yön kırpma ve yazı tipi işleme dahil olmak üzere grafik metin düzeni seçeneklerini belirtir. Bu bayraklar birden çok seçeneği belirtmek için birleştirilebilir.
type: docs
weight: 5080
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---
## EmfPlusStringFormatFlags enumeration

StringFormat bayrakları, yön, kırpma ve yazı tipi işleme dahil olmak üzere grafik metin düzeni seçeneklerini belirtir. Bu bayraklar, birden çok seçeneği belirtmek için birleştirilebilir.

```csharp
[Flags]
public enum EmfPlusStringFormatFlags : uint
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| StringFormatDirectionRightToLeft | `1` | Ayarlanırsa, dizenin okuma sırası sağdan sola OLMALIDIR. Yatay metin için bu, karakterlerin sağdan sola okunduğu anlamına gelir. Dikey metin için bu, sütunların sağdan sola okunduğu anlamına gelir. Açıksa, yatay veya dikey metin soldan sağa doğru OKUNMALIDIR. |
| StringFormatDirectionVertical | `2` | Ayarlanırsa, tek tek metin satırları görüntüleme cihazında dikey olarak ÇİZİLMELİDİR. Açıksa, her yeni satır bir önceki satırın altında olacak şekilde tek tek metin satırları yatay olarak ÇİZİLMELİDİR. |
| StringFormatNoFitBlackBox | `4` | Ayarlanırsa, karakter bölümlerinin metin yerleşimi dikdörtgeninden taşmasına izin verilmelidir ZORUNLU. Açıksa, metin yerleşimi dikdörtgeninin sınırlarını aşan karakterler taşmayı önlemek için yeniden konumlandırılmalıdır ZORUNLU. İtalik, "f" bir örnektir. sarkan parçalara sahip olabilen karakter. |
| StringFormatDisplayFormatControl | `20` | Ayarlanırsa, kontrol karakterleri çıktıda temsili Unicode glifleri olarak GÖRÜNTÜLENMELİDİR. |
| StringFormatNoFontFallback | `400` | Ayarlanırsa, istenen yazı tipinde desteklenmeyen karakterler için alternatif bir yazı tipi KULLANILMALIDIR. Temizse, istenen yazı tipinde eksik olan bir karakter, açık bir kare OLABİLİR "yazı tipi eksik" karakter olarak GÖRÜNTÜLENMELİDİR. |
| StringFormatMeasureTrailingSpaces | `800` | Ayarlanırsa, her satırın sonundaki boşluk dize uzunluğu ölçümlerine DAHİL EDİLMELİDİR. Boşsa, her satırın sonundaki boşluk dize uzunluğu ölçümlerinden MUTLAKA ÇIKARILMALIDIR. |
| StringFormatNoWrap | `1000` | Ayarlanırsa, metin düzeni dikdörtgeninin sonunu aşan bir dize bir sonraki satıra SARILMAMALIDIR. Temizse, metin düzeni dikdörtgeninin sonunu geçen bir dize, içindeki son kelime sınırından KIRILMALIDIR sınırlayıcı dikdörtgen ve dizenin geri kalanı bir sonraki satıra SARILMALIDIR. |
| StringFormatLineLimit | `2000` | Ayarlanırsa, metnin tüm satırları çıktı olarak alınmalı ve dizenin yerleşim dikdörtgeni tarafından KIRPILMAMALIDIR. Temizse, metin düzeni tüm satırlar çıkana kadar veya kırpmanın bir sonucu olarak ek satırlar görünmeyinceye kadar devam etmelidir. Bu bayrak, bir metin satırının, satır yüksekliğinin katı olmayan bir yerleşim dikdörtgeni tarafından kısmen karartılmasına izin vermek veya reddetmek için kullanılabilir. Tüm metnin görünür olması için, en az bir satır yüksekliği kadar uzun bir yerleşim dikdörtgeni. |
| StringFormatNoClip | `4000` | Ayarlanırsa, dize düzeni dikdörtgeninin dışına uzanan metnin gösterilmesine izin verilmelidir. Açıksa, düzen dikdörtgeninin dışına uzanan tüm metinler kırpılmalıdır. |
| StringFormatBypassGdi | `80000000` | Bu işaret, metin oluşturmak için uygulamaya özel bir süreci belirtmek için KULLANILABİLİR. |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
