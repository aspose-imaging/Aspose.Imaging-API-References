---
title: EmfPlusStringFormat
second_title: Aspose.Imaging for .NET API Referansı
description: EmfPlusStringFormat nesnesi metin düzenini ekran manipülasyonlarını ve dil tanımlamasını belirtir
type: docs
weight: 5780
url: /tr/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---
## EmfPlusStringFormat class

EmfPlusStringFormat nesnesi metin düzenini, ekran manipülasyonlarını ve dil tanımlamasını belirtir

```csharp
public sealed class EmfPlusStringFormat : EmfPlusGraphicsObjectType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfPlusStringFormat](emfplusstringformat)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [DigitLanguage](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitlanguage) { get; set; } | Dizedeki sayısal basamaklar için kullanılacak dilini belirten bir EmfPlusLanguageIdentifier nesnesi alır veya ayarlar. Örneğin, bu dize Arapça rakamlar içeriyorsa, bu alan bir Arapça dili belirten bir dil tanımlayıcısı OLMALIDIR |
| [DigitSubstitution](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/digitsubstitution) { get; set; } | Dizedeki sayısal basamakların bir yerel ayara veya dile göre nasıl değiştirileceğini belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer StringDigitSubstitution numaralandırmasında (bölüm 2.1.1.30) tanımlanmalıdır. |
| [FirstTabOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/firsttaboffset) { get; set; } | Bir metin satırının başlangıcı ile ilk sekme arasındaki boşluk sayısını belirten 32 bit kayan nokta değerini alır veya ayarlar stop |
| [HotkeyPrefix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/hotkeyprefix) { get; set; } | Bir klavye kısayol önekiyle (yani bir ve işareti) karşılaşıldığında bir dize üzerinde gerçekleştirilen işlemenin türünü belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. Temel olarak, bu alan klavye kısayolu öneklerinin görüntülenip görüntülenmeyeceğini belirtir. text ile ilişkilendir. Değer HotkeyPrefix numaralandırmasında tanımlanmalıdır (bölüm 2.1.1.14). |
| [Language](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/language) { get; set; } | string için kullanılacak dili belirten bir EmfPlusLanguageIdentifier nesnesi (bölüm 2.2.2.23) alır veya ayarlar |
| [LeadingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/leadingmargin) { get; set; } | Bir dizenin başlangıç konumuna eklenecek alanın uzunluk değerini belirten bir 32 bit kayan nokta değeri alır veya ayarlar. Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için, the varsayılan değeri 0. 'dir |
| [LineAlign](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/linealign) { get; set; } | Düzen dikdörtgeninde dizenin dikey olarak nasıl hizalanacağını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer StringAlignment numaralandırmasında tanımlanmalıdır. |
| [RangeCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/rangecount) { get; set; } | StringFormatData alanında tanımlanan EmfPlusCharacterRange nesnelerinin (bölüm 2.2.2.8) sayısını belirten 32 bitlik işaretli bir tamsayı alır veya ayarlar. |
| [StringAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringalignment) { get; set; } | Düzen dikdörtgeninde dizenin yatay olarak nasıl hizalanacağını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu değer StringAlignment numaralandırmasında (bölüm 2.1.1.29) TANIMLANMALIDIR. |
| [StringFormatData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatdata) { get; set; } | İsteğe bağlı metin düzeni verilerini belirten bir EmfPlusStringFormatData nesnesi (bölüm 2.2.2.44) alır veya ayarlar. |
| [StringFormatFlags](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/stringformatflags) { get; set; } | Biçimlendirme, kırpma ve yazı tipi işleme için metin layout seçeneklerini belirten 32 bit işaretsiz bir tamsayı alır veya ayarlar. Bu değer StringFormat flags 'den oluşmalıdır (bölüm 2.1.2.8). |
| [TabstopCount](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tabstopcount) { get; set; } | StringFormatData alanında tanımlanan sekme durakları sayısını belirten 32 bit işaretli bir tamsayı alır veya ayarlar. |
| [Tracking](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/tracking) { get; set; } | Belirtilen bir dizede, karakterinin yazı tipi tanımlı genişliğine ayrılan yatay boşluğun oran değerini belirten 32 bit kayan nokta değerini alır veya ayarlar. Bu özellik için büyük değerler, karakterler arasında ample boşluk belirtir; 1'den küçük değerler, karakter çakışmasına neden olabilir. Varsayılan 1.03'tür; typeographic yazı tipleri için varsayılan değer 1.00. 'dir |
| [TrailingMargin](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trailingmargin) { get; set; } | Bir dizeden sonra bırakılacak alanın uzunluk değerini belirten 32 bitlik bir kayan nokta değeri alır veya ayarlar. default 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0. 'dir |
| [Trimming](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/trimming) { get; set; } | Alır veya ayarlar, bir düzen dikdörtgenine sığmayacak kadar büyük olan bir dizeden karakterlerin nasıl kırpılacağını belirtir. Bu değer , StringTrimming numaralandırmasında tanımlanmalıdır (bölüm 2.1.1.31). |
| [Version](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype/version) { get; set; } | Sürümü alır veya ayarlar. |

### Ayrıca bakınız

* class [EmfPlusGraphicsObjectType](../emfplusgraphicsobjecttype)
* ad alanı [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
