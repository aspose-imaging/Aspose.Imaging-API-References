---
title: "EmfPlusStringFormat Class"
type: docs
weight: 650
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformat/
---

**Summary:** The EmfPlusStringFormat object specifies text layout,<br/>            display manipulations, and language identification

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStringFormat

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [EmfPlusStringFormat()](#EmfPlusStringFormat__1) | EmfPlusStringFormat sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| digit_language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar ve bu nesne dizedeki sayısal rakamlar için kullanılacak dili belirler.<br/>            Örneğin, bu dize Arap rakamları içeriyorsa,<br/>            bu alan Arap dili belirten bir dil tanımlayıcısı içermelidir. |
| digit_substitution | [EmfPlusStringDigitSubstitution](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringdigitsubstitution/) | r/w | Yerel ayar veya dile göre dizedeki sayısal rakamların nasıl değiştirileceğini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar<br/>            . Bu değer StringDigitSubstitution sayımında (bölüm 2.1.1.30) tanımlanmalıdır. |
| first_tab_offset | float | r/w | 32 bit kayan noktalı bir değeri alır veya ayarlar; bu değer bir metin satırının başlangıcı ile<br/>            ilk sekme durağı arasındaki boşluk sayısını belirtir. |
| hotkey_prefix | [EmfPlusHotkeyPrefix](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplushotkeyprefix/) | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu değer bir dize üzerinde bir klavye<br/>            kısayol öneki (yani, bir ampersand) ile karşılaşıldığında gerçekleştirilen işlem türünü belirtir.<br/>            Temelde, bu alan metinle ilgili klavye kısayol öneklerinin gösterilip gösterilmeyeceğini belirtir.<br/>            Değer, HotkeyPrefix<br/>            enumerasyonu (bölüm 2.1.1.14) içinde tanımlanmalıdır. |
| language | [EmfPlusLanguageIdentifierType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslanguageidentifiertype/) | r/w | Bir EmfPlusLanguageIdentifier nesnesini alır veya ayarlar (bölüm 2.2.2.23)<br/>            bu nesne dize için kullanılacak dili belirtir. |
| leading_margin | float | r/w | 32 bit kayan noktalı bir değeri alır veya ayarlar; bu değer bir dize'nin başlangıç konumuna eklenecek boşluğun uzunluğunu belirtir.<br/>            Varsayılan değer 1/6 inçtir; tipografik yazı tipleri için<br/>            varsayılan değer 0'dır. |
| line_align | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | 32 bit işaretsiz bir tam sayıyı alır veya ayarlar; bu değer dizeyi düzenleme dikdörtgeninde dikey olarak nasıl hizalayacağını belirtir.<br/>            Bu değer, StringAlignment enumerasyonu içinde tanımlanmalıdır. |
| range_count | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu değer StringFormatData alanında tanımlı EmfPlusCharacterRange<br/>            nesnelerinin sayısını belirtir (bölüm 2.2.2.8). |
| string_alignment | [EmfPlusStringAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringalignment/) | r/w | 32 bit işaretsiz bir tam sayıyı alır veya ayarlar; bu değer dizeyi düzenleme dikdörtgeninde yatay olarak nasıl hizalayacağını belirtir.<br/>            Bu değer, StringAlignment<br/>            enumerasyonu (bölüm 2.1.1.29) içinde tanımlanmalıdır. |
| string_format_data | [EmfPlusStringFormatData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/) | r/w | Bir EmfPlusStringFormatData nesnesini alır veya ayarlar (bölüm 2.2.2.44)<br/>            bu nesne isteğe bağlı metin yerleşim verilerini belirtir. |
| string_format_flags | [EmfPlusStringFormatFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/) | r/w | 32 bit işaretsiz bir tam sayıyı alır veya ayarlar; bu değer biçimlendirme, kırpma ve yazı tipi işleme için metin yerleşim seçeneklerini belirtir.<br/>            Bu değer, StringFormat bayraklarından oluşmalıdır<br/>            (bölüm 2.1.2.8). |
| tabstop_count | int | r/w | 32 bit işaretli bir tam sayıyı alır veya ayarlar; bu değer StringFormatData alanında tanımlı sekme duraklarının sayısını belirtir.<br/> |
| compound_line_data | float | r/w | 32 bit kayan noktalı bir değeri alır veya ayarlar; bu değer belirtilen bir dizedeki her karaktere ayrılan yatay boşluğun, yazı tipi tarafından tanımlanan karakter genişliğine oranını belirtir.<br/>            Bu özelliğin büyük değerleri karakterler arasında geniş boşluk sağlar; 1'den küçük değerler karakter çakışmasına neden olabilir. Varsayılan değer 1.03'tür; tipografik yazı tipleri için varsayılan değer 1.00'dir. |
| trailing_margin | float | r/w | 32 bit kayan noktalı bir değeri alır veya ayarlar; bu değer bir dizeden sonra bırakılacak boşluğun uzunluğunu belirtir. Varsayılan<br/>            değer 1/6 inçtir; tipografik yazı tipleri için varsayılan değer 0'dır. |
| trimming | [EmfPlusStringTrimming](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringtrimming/) | r/w | Bir dizeyi, düzenleme dikdörtgenine sığamayacak kadar büyük olduğunda karakterleri nasıl kırpacağını alır veya ayarlar. Bu değer<br/>            StringTrimming enumerasyonu (bölüm 2.1.1.31) içinde tanımlanmalıdır. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Sürümü alır veya ayarlar. |


### Constructor: EmfPlusStringFormat() {#EmfPlusStringFormat__1}


```
 EmfPlusStringFormat() 
```

EmfPlusStringFormat sınıfının yeni bir örneğini başlatır

