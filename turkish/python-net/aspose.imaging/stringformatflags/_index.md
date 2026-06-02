---
title: "StringFormatFlags Sınıflaması"
type: docs
weight: 11220
url: /tr/python-net/aspose.imaging/stringformatflags/
---

Metin dizgileri için görüntüleme ve yerleşim bilgilerini belirtir.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.StringFormatFlags

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| DIRECTION_RIGHT_TO_LEFT | Metin sağdan sola doğru görüntülenir. |
| DIRECTION_VERTICAL | Metin dikey olarak hizalanır. |
| DISPLAY_FORMAT_CONTROL | Sol‑sağ işareti gibi kontrol karakterleri, çıktıda temsilci bir glif ile gösterilir. |
| EXACT_ALIGNMENT | Tam hizalama, doğru dolgu GDI+ |
| FIT_BLACK_BOX | Karakterlerin bölümlerinin dize düzenleme dikdörtgeninin dışına taşmasına izin verilir. Varsayılan olarak, karakterler taşmayı önlemek için yeniden konumlandırılır. |
| LINE_LIMIT | Yalnızca tam satırlar biçimlendirme dikdörtgeninde yerleştirilir. Varsayılan olarak yerleşim, metnin sonuna kadar ya da kırpma sonucu daha fazla satır görünür olmayana kadar, hangisi önce gelirse o kadar devam eder.<br/>            Varsayılan ayarların, satır yüksekliğinin tam katı olmayan bir biçimlendirme dikdörtgeni tarafından son satırın kısmen gizlenmesine izin verdiğini unutmayın. Yalnızca tam satırların görülmesini sağlamak için,<br/>            bu değeri belirtin ve bir satır yüksekliğine en az eşit bir biçimlendirme dikdörtgeni sağlamaya dikkat edin. |
| MEASURE_TRAILING_SPACES | Her satırın sonundaki sondaki boşluğu içerir. Varsayılan olarak MeasureString yöntemi tarafından döndürülen sınır dikdörtgeni, her satırın sonundaki boşluğu dışlar. Bu bayrağı, ölçümde o boşluğu dahil etmek için ayarlayın. |
| NO_CLIP | Gliflerin taşan bölümleri ve biçimlendirme dikdörtgeninin dışına ulaşan sarılmamış metin gösterilmesine izin verilir. Varsayılan olarak biçimlendirme dikdörtgeninin dışına çıkan tüm metin ve glif bölümleri kırpılır. |
| NO_FONT_FALLBACK | İstenen yazı tipinde desteklenmeyen karakterler için alternatif yazı tiplerine geri dönüş devre dışı bırakılmıştır. Eksik karakterler, genellikle açık bir kare olan eksik glif ile gösterilir. |
| NO_WRAP | Bir dikdörtgen içinde biçimlendirme yapılırken satırlar arasındaki metin kaydırma devre dışı bırakılır. Bu bayrak, bir nokta bir dikdörtgen yerine geçirildiğinde veya belirtilen dikdörtgenin satır uzunluğu sıfır olduğunda otomatik olarak uygulanır. |
