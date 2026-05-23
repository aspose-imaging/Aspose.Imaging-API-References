---
title: "EmfPlusStringFormatFlags Sıralaması"
type: docs
weight: 410
url: /tr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusstringformatflags/
---

StringFormat bayrakları, yön, kırpma ve yazı tipi işleme dahil olmak üzere grafik metin yerleşimi için seçenekleri belirtir. Bu bayraklar birden fazla seçeneği belirtmek için birleştirilebilir.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusStringFormatFlags

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| STRING_FORMAT_BYPASS_GDI | Bu bayrak, metin renderleme için uygulamaya özgü bir süreci belirtmek üzere MAY kullanılabilir. |
| STRING_FORMAT_DIRECTION_RIGHT_TO_LEFT | Ayarlanmışsa, dizenin okuma yönü SHOULD sağdan sola olmalıdır. Yatay metin için bu, karakterlerin sağdan sola okunması anlamına gelir. Dikey metin için bu, sütunların sağdan sola okunması anlamına gelir.<br/>            Temizlenmişse, yatay veya dikey metin SHOULD soldan sağa okunmalıdır. |
| STRING_FORMAT_DIRECTION_VERTICAL | Ayarlanmışsa, bireysel metin satırları SHOULD dikey olarak çizilir.<br/>            Temizlenmişse, bireysel metin satırları SHOULD yatay olarak çizilir, her yeni satır bir öncekinin altında yer alır. |
| STRING_FORMAT_DISPLAY_FORMAT_CONTROL | Ayarlanmışsa, kontrol karakterleri çıktıda temsilci Unicode glifleri olarak SHOULD görünür. |
| STRING_FORMAT_LINE_LIMIT | Ayarlanmışsa, metnin bütün satırları SHOULD çıktıya alınır ve string'in yerleşim dikdörtgeni tarafından kesilmemelidir (SHOULD NOT).<br/>            Temizlenmişse, metin yerleşimi tüm satırlar çıktıya alınana kadar veya ek satırlar kırpma nedeniyle görünmez olana kadar SHOULD devam eder.<br/>            Bu bayrak, satır yüksekliğinin katı olmayan bir yerleşim dikdörtgeni tarafından bir metin satırının kısmen gizlenmesine izin vermek ya da engellemek için kullanılabilir. Tüm metnin görünür olması için, yerleşim dikdörtgeni en az bir satır yüksekliği kadar olmalıdır. |
| STRING_FORMAT_MEASURE_TRAILING_SPACES | Ayarlanırsa, her satırın sonundaki boşluk DİZİ uzunluğu ölçümlerine dahil edilmelidir.<br/>            Temizlenirse, her satırın sonundaki boşluk DİZİ uzunluğu ölçümlerinden hariç tutulmalıdır. |
| STRING_FORMAT_NO_CLIP | Ayarlanırsa, dize yerleşim dikdörtgeninin dışına uzanan metnin gösterilmesine izin verilmelidir.<br/>            Temizlenirse, yerleşim dikdörtgeninin dışına uzanan tüm metin kırpılmalıdır. |
| STRING_FORMAT_NO_FIT_BLACK_BOX | Ayarlanırsa, karakterlerin bölümlerinin metin yerleşim dikdörtgeninin dışına taşmasına izin verilmelidir.<br/>            Temizlenirse, metin yerleşim dikdörtgeninin sınırlarının dışına taşan karakterler taşmayı önlemek için yeniden konumlandırılmalıdır.<br/>            İtalik bir "f", dışa taşan bölümlere sahip olabilen bir karakter örneğidir. |
| STRING_FORMAT_NO_FONT_FALLBACK | Ayarlanırsa, istenen yazı tipinde desteklenmeyen karakterler için alternatif bir yazı tipi kullanılmalıdır.<br/>            Temizlenirse, istenen yazı tipinde bulunmayan bir karakter "yazı tipi eksik" karakteri olarak görünmelidir; bu bir açık kare olabilir. |
| STRING_FORMAT_NO_WRAP | Ayarlanırsa, metin yerleşim dikdörtgeninin sonunu aşan bir dize bir sonraki satıra kaydırılamaz.<br/>            Temizlenirse, metin yerleşim dikdörtgeninin sonunu aşan bir dize, sınırlayıcı dikdörtgen içindeki son kelime sınırında bölünmeli ve dizenin geri kalanı bir sonraki satıra kaydırılmalıdır. |
