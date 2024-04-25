---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Aspose.Imaging for .NET API Referansı
description: Ad alanı MS-EMFPLUS türlerini içerir Gelişmiş Meta Dosyası Biçimi Artı Uzantıları 2.3 EMF Kayıtları
type: docs
weight: 390
url: /tr/aspose.imaging.fileformats.emf.emfplus.records/
---
Ad alanı, [MS-EMFPLUS] türlerini içerir: Gelişmiş Meta Dosyası Biçimi Artı Uzantıları 2.3 EMF+ Kayıtları

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | EmfPlusBeginContainer kaydı, yeni bir grafik durum kapsayıcısını açar ve bunun için bir dönüşüm belirtir. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | EmfPlusBeginContainerNoParams kaydı yeni bir grafik durumu kapsayıcısını açar. |
| [EmfPlusClear](./emfplusclear) | EmfPlusClear kaydı, çıktı koordinat alanını temizler ve onu bir arka plan rengi ve şeffaflıkla başlatır |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Kırpma kayıt türleri, kırpma bölgelerini ve işlemlerini belirtir. |
| [EmfPlusComment](./emfpluscomment) | EmfPlusComment kaydı, isteğe bağlı özel verileri belirtir. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Kontrol kaydı türleri, EMF+ meta dosyası işleme için genel parametreleri belirtir. |
| [EmfPlusDrawArc](./emfplusdrawarc) | EmfPlusDrawArc kaydı, bir elipsin yayının çizilmesini belirtir. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | EmfPlusDrawBeziers kaydı, bağlantılı Bezier eğrilerinin bir dizisini çizmeyi belirtir. Bezier veri noktalarının sırası başlangıç noktası, kontrol noktası 1, kontrol noktası 2 ve bitiş noktasıdır. Daha fazla bilgi için bkz. [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | EmfPlusDrawClosedCurve kaydı, kapalı bir ana eğri çizgi çizmeyi belirtir |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | EmfPlusDrawCurve kaydı bir ana spline çizimini belirtir NOT: ObjectID (1 bayt): EMF+ Nesne Tablosundaki bir EmfPlusPen nesnesinin (bölüm 2.2.1.7) eğrisini çizmek için. Değer, sıfır ile 63 arasında OLMALIDIR. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | EmfPlusDrawDriverString kaydı, karakter konumlarıyla metin çıktısını belirtir. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | EmfPlusDrawEllipse kaydı, bir elips çizmeyi belirtir. |
| [EmfPlusDrawImage](./emfplusdrawimage) | EmfPlusDrawImage kaydı, ölçeklenmiş bir görüntünün çizimini belirtir. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | EmfPlusDrawImagePoints kaydı, paralelkenar içinde ölçeklenmiş bir görüntü çizmeyi belirtir. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Çizim kayıt türleri, grafik çıktısını belirtir. |
| [EmfPlusDrawLines](./emfplusdrawlines) | EmfPlusDrawlLines kaydı, bir dizi bağlantılı çizgi çizmeyi belirtir |
| [EmfPlusDrawPath](./emfplusdrawpath) | EmfPlusDrawPath kaydı, bir grafik yolu çizmeyi belirtir. |
| [EmfPlusDrawPie](./emfplusdrawpie) | EmfPlusDrawPie kaydı, bir elipsin içinin bir bölümünün çizimini belirtir. |
| [EmfPlusDrawRects](./emfplusdrawrects) | EmfPlusDrawRects kaydı, bir dizi dikdörtgenin çizilmesini belirtir |
| [EmfPlusDrawString](./emfplusdrawstring) | EmfPlusDrawString kaydı, metin çıktısını dize biçimlendirme ile belirtir |
| [EmfPlusEndContainer](./emfplusendcontainer) | EmfPlusEndContainer kaydı, daha önce bir kapsayıcı başlatma işlemi tarafından açılmış bir grafik durumu kapsayıcısını kapatır. |
| [EmfPlusEndOfFile](./emfplusendoffile) | EmfPlusEndOfFile kaydı, meta dosyasındaki EMF+ verilerinin sonunu belirtir. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | EmfPlusFillClosedCurve kaydı, kapalı bir kardinal spline'ın içinin doldurulmasını belirtir |
| [EmfPlusFillEllipse](./emfplusfillellipse) | EmfPlusFillEllipse kaydı, bir elipsin içinin doldurulmasını belirtir |
| [EmfPlusFillPath](./emfplusfillpath) | Dolgu yolu record FLAGS: İşlemin nasıl gerçekleştirileceği, ve kaydın yapısı hakkında bilgi sağlayan 16 bitlik işaretsiz tamsayı. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 bit): Bu bit, BrushId alanındaki verinin türünü belirtir. Ayarlanırsa, BrushId, EmfPlusARGB nesnesi olarak bir renk belirtir (bölüm 2.2.2.1). Temizse, BrushId, EMF+ Nesne Tablosundaki bir EmfPlusBrush nesnesinin (bölüm 2.2.1.1) dizinini içerir. X (1 bit): Ayrılmıştır ve yoksayılmalıdır. ObjectId (1 bayt): EmfPlusPath nesnesinin dizini ( bölüm 2.2.1.6) EMF+ Nesne Tablosunu doldurmak için. Değer, sıfır ile 63 arasında OLMALIDIR. |
| [EmfPlusFillPie](./emfplusfillpie) | EmfPlusFillPie kaydı, bir elipsin içinin bir bölümünün doldurulmasını belirtir |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | EmfPlusFillPolygon kaydı, bir çokgenin içinin doldurulmasını belirtir. |
| [EmfPlusFillRects](./emfplusfillrects) | EmfPlusFillRects kaydı, bir dizi dikdörtgenin içinin doldurulmasını belirtir |
| [EmfPlusFillRegion](./emfplusfillregion) | EmfPlusFillRegion kaydı, bir grafik bölgesinin içinin doldurulmasını belirtir |
| [EmfPlusGetDc](./emfplusgetdc) | EmfPlusGetDC kaydı, meta dosyasında karşılaşılan sonraki EMF kayıtlarının işlenmesi GEREKTİĞİNİ belirtir. |
| [EmfPlusHeader](./emfplusheader) | EmfPlusHeader kaydı, meta dosyasındaki EMF+ verilerinin başlangıcını belirtir. EmfPlusHeader kaydı, meta dosyasındaki EMF başlığının hemen ardından gelen kayıt OLMALIDIR, bir EMF EMR_COMMENT_EMFPLUS kaydına yerleştirilmelidir ZORUNLU. EMR_COMMENT_EMFPLUS kaydı, [MS-EMF] bölüm 2.3.3.2. 'de belirtilmiştir. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | EmfPlusMultiplyWorldTransform kaydı, geçerli dünya uzay dönüşümünü a belirtilen dönüşüm matrisi ile çarpar. |
| [EmfPlusObject](./emfplusobject) | EmfPlusObject kaydı, grafik işlemlerinde kullanılacak bir nesneyi belirtir. Nesne tanımı , Bayraklar alanının değeriyle gösterilen birden çok kayda yayılabilir. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Nesne Kayıt Türleri, yeniden kullanılabilir grafik nesnelerini tanımlar. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | EmfPlusOffsetClip kaydı, dünya alanı için geçerli kırpma bölgesinde bir çeviri dönüşümü uygular. Yeni geçerli kırpma bölgesi, çeviri dönüşümünün sonucuna ayarlanır. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Özellik Kayıt Türleri, oynatma cihazı bağlamının özelliklerini belirtir. |
| [EmfPlusRecord](./emfplusrecord) | Emf+ temel kayıt türü. |
| [EmfPlusResetClip](./emfplusresetclip) | EmfPlusResetClip kaydı, dünya alanı için geçerli kırpma bölgesini sonsuza sıfırlar. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | EmfPlusResetWorldTransform kaydı, geçerli dünya uzay dönüşümünü tanımlama matrisine sıfırlar. |
| [EmfPlusRestore](./emfplusrestore) | EmfPlusRestore kaydı, belirtilen bir dizin tarafından tanımlanan grafik durumunu, kaydedilmiş grafik durumları yığınından geri yükler. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | EmfPlusRotateWorldTransform kaydı, geçerli dünya uzay dönüşümü üzerinde bir dönüş gerçekleştirir. |
| [EmfPlusSave](./emfplussave) | EmfPlusSave kaydı, belirtilen bir dizin tarafından tanımlanan grafik durumunu bir kaydedilmiş grafik durumu yığınına kaydeder. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | EmfPlusScaleWorldTransform kaydı, mevcut dünya uzay dönüşümü üzerinde bir ölçeklendirme gerçekleştirir. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | EmfPlusSerializableObject kaydı, bir veri arabelleğine serileştirilmiş bir görüntü efektleri parametre bloğu tanımlar. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | EmfPlusSetAntiAliasMode kaydı, metin çıktısı için kenar yumuşatma modunu belirtir. |
| [EmfPlusSetClipPath](./emfplussetclippath) | EmfPlusSetClipPath kaydı, geçerli kırpma bölgesini bir grafik yolu ile birleştirir. Yeni geçerli kırpma bölgesi, CombineMode işleminin sonucuna ayarlanır. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | EmfPlusSetClipRect kaydı, geçerli kırpma bölgesini bir dikdörtgenle birleştirir. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | EmfPlusSetClipRegion kaydı, geçerli kırpma bölgesini başka bir grafik bölgesiyle birleştirir. Yeni geçerli kırpma bölgesi, önceki geçerli kırpma bölgesi ve belirtilen EmfPlusRegion nesnesi üzerinde CombineMode işleminin gerçekleştirilmesinin sonucuna ayarlanır. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | EmfPlusSetCompositingMode kaydı, kaynak renklerin arka plan renkleriyle nasıl birleştirildiğini belirtir. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | EmfPlusSetCompositingQuality kaydı, birden çok nesneden bileşik görüntüler oluşturmak için istenen kalite düzeyini belirtir. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | EmfPlusSetInterpolationMode kaydı, germe ve küçültme dahil olmak üzere görüntü ölçeklemenin nasıl gerçekleştirildiğini belirtir. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | EmfPlusSetPageTransform kaydı, sayfa space koordinatlarını cihaz uzay koordinatlarına dönüştürmek için ölçekleme faktörlerini ve birimlerini belirtir. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | EmfPlusSetPixelOffsetMode kaydı, piksellerin çizim yüzeyinin koordinatlarına göre nasıl ortalanacağını belirtir. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | EmfPlusSetRenderingOrigin kaydı, grafik çıktısı için işleme kaynağını belirtir. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | EmfPlusSetTextContrast kaydı, gama düzeltme değerine göre metin kontrastını belirtir. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | EmfPlusSetTextRenderingHint kaydı, kenar yumuşatma türü de dahil olmak üzere metin oluşturma kalitesini belirtir. |
| [EmfPlusSetTsClip](./emfplussettsclip) | EmfPlusSetTSClip kaydı, bir terminal sunucusu için grafik aygıtı bağlamında kırpma alanlarını belirtir. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | EmfPlusSetTSGraphics kaydı, bir terminal sunucusu için grafik aygıtı bağlamının durumunu belirtir. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | EmfPlusSetWorldTransform kaydı, dünya dönüşümünü a belirtilen dönüşüm matrisindeki değerlere göre ayarlar. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | Durum Kayıt Türleri, oynatma cihazı bağlamının durumuyla ilgili işlemleri belirtir. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Terminal Sunucusu Kayıt Türleri, bir terminal sunucusunda grafik işlemeyi belirtir. Aşağıdaki , EMF+ terminal sunucusu kayıt türleridir. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Dönüştürme Kayıt Türleri, koordinat uzaylarında özellikleri ve dönüşümleri belirtir. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | EmfPlusTranslateWorldTransform kaydı, geçerli dünya uzay dönüşümü üzerinde bir çeviri gerçekleştirir. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
