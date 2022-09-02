---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Aspose.Imaging for .NET API Referansı
description: Ad alanı MS-EMF türlerini içerir Gelişmiş Meta Dosyası Formatı. 2.3 EMF Kayıtları
type: docs
weight: 360
url: /tr/net/aspose.imaging.fileformats.emf.emf.records/
---
Ad alanı, [MS-EMF] türlerini içerir: Gelişmiş Meta Dosyası Formatı. 2.3 EMF Kayıtları

## sınıflar

| Sınıf | Tanım |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Bu kayıt, bir yol parantezini iptal eder veya yolu kapalı bir yol parantezinden atar. |
| [EmfAlphaBlend](./emfalphablend) | EMR_ALPHABLEND kaydı, belirli bir karıştırma işlemine göre alfa saydamlık verileri dahil olmak üzere bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| [EmfAngleArc](./emfanglearc) | EMR_ANGLEARC kaydı, bir yayın çizgi kesimini belirtir. Çizgi parçası, geçerli konumundan yayın başlangıcına kadar çizilir. Yay, yarıçapı ve merkezi olan bir dairenin çevresi boyunca çizilir. Yayın uzunluğu, verilen başlangıç ve süpürme açıları ile tanımlanır |
| [EmfArc](./emfarc) | EMR_ARC kaydı, eliptik bir yay belirtir. |
| [EmfArcTo](./emfarcto) | EMR_ARCTO kaydı, eliptik bir yayı belirtir. Geçerli konumu yayın bitiş noktasına sıfırlar. |
| [EmfBeginPath](./emfbeginpath) | Bu kayıt, geçerli oynatma cihazı bağlamında bir yol parantezini açar. Bir yol parantezi açıldıktan sonra, bir uygulama, yoldaki noktaları tanımlamak için kayıtları işlemeye başlayabilir.Bir uygulama, EMR_ENDPATH'i işleyerek bir açık yol parantezini KAPATMALIDIR. record. Bir uygulama EMR_BEGINPATH kaydını işlediğinde, önceki tüm yollar oynatma cihazı bağlamından ATILMALIDIR. |
| [EmfBitBlt](./emfbitblt) | EMR_BITBLT kaydı, belirli bir tarama işlemine göre, isteğe bağlı olarak bir fırça deseni ile birlikte, bir kaynak bitmap'ten hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | Bitmap kayıt türleri, bitmap görüntülerinin blok aktarımlarını gerçekleştirir. |
| [EmfChord](./emfchord) | EMR_CHORD kaydı, bir elips ile kesen adı verilen bir çizgi parçasının kesişimiyle sınırlanan bir bölge olan bir akoru belirtir. Akor, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| [EmfClippingRecordType](./emfclippingrecordtype) | Kırpma kaydı türleri, kırpma bölgelerini belirtir ve yönetir. Not EMR_SETMETARGN kaydı parametreleri belirtmiyor. |
| [EmfCloseFigure](./emfclosefigure) | Bu kayıt bir yoldaki açık bir şekli kapatır. EMR_CLOSEFIGURE kaydının işlenmesi şeklin mevcut konumundan şeklin ilk noktasına bir line çizerek şekli kapatması ZORUNLUDUR ve ardından çizgi birleştirme stilini kullanarak çizgileri bağlaması ZORUNLUDUR. Bir şekil, EMR_CLOSEFIGURE kaydı yerine EMR_LINETO kaydı işlenerek kapatılırsa, birleştirme yerine köşeyi oluşturmak için bitiş kapakları kullanılır.EMR_LINETO, bölüm 2.3.5.13. bölümünde belirtilir. oynatma aygıtı bağlamında path parantezini aç. Yoldaki bir şekil, bu kayıt işlenerek açıkça kapatılmadığı sürece açıktır. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | EMR_COLORCORRECTPALETTE kaydı, WCS 1.0 değerleri kullanılarak mantıksal bir palet nesnesinin girişlerinin nasıl düzeltileceğini belirtir. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | EMR_COLORMATCHTOTargetW kaydı, adı Unicode karakterlerden oluşan bir dosyada belirtilen color profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirtir. |
| [EmfComment](./emfcomment) | EMR_COMMENT kaydı isteğe bağlı özel veriler içeriyor. Not Bu bölümde açıklanmayan alanlar 2.3.3. bölümünde belirtilmiştir. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | EMR_COMMENT_BEGINGROUP kaydı, bir grup çizim kaydının başlangıcını belirtir. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | EMR_COMMENT_EMFPLUS kaydı, gömülü EMF+ kayıtları içerir. Not Bu bölümde açıklanmayan alanlar 2.3.3. bölümünde belirtilmiştir. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | EMR_COMMENT_EMFSPOOL kaydı, gömülü EMFSPOOL kayıtları içerir. Not Bu bölümde açıklanmayan alanlar 2.3.3. bölümünde belirtilmiştir. |
| [EmfCommentEndGroup](./emfcommentendgroup) | EMR_COMMENT_ENDGROUP kaydı, bir grup çizim kaydının sonunu belirtir. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | EMR_COMMENT_MULTIFORMATS kaydı, bir görüntüyü birden çok grafik biçiminde belirtir. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | EMR_COMMENT_PUBLIC kayıt türleri, EMF işleme uzantılarını belirtir. |
| [EmfCommentRecordType](./emfcommentrecordtype) | Yorum kaydı türleri, isteğe bağlı özel verileri belirtmek, kayıtlarını diğer meta dosyası biçimlerine yerleştirmek ve yeni veya özel amaçlı komutlar eklemek için biçimleri tanımlar. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | EMR_COMMENT_WINDOWS_METAFILE kaydı, gömülü bir WMF meta dosyasındaki bir görüntüyü belirtir. |
| [EmfControlRecordType](./emfcontrolrecordtype) | Kontrol kaydı türleri, bir EMF meta dosyasının başlangıcını ve sonunu ve meta dosyasının özelliklerini tanımlar. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | EMR_CREATEBRUSHINDIRECT kaydı, grafik işlemleri için mantıksal bir fırça tanımlar. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | EMR_CREATECOLORSPACE kaydı, ASCII karakterlerinden oluşan bir adına sahip bir renk profilinden mantıksal bir renk uzayı nesnesi oluşturur. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | EMR_CREATECOLORSPACEW kaydı, bir renk profilinden, Unicode karakterlerden oluşan bir adla mantıksal bir renk uzayı nesnesi oluşturur. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | EMR_CREATEDIBPATTERNBRUSHPT kaydı, grafik işlemleri için bir desen fırçası tanımlar. modeli bir DIB tarafından belirtilir. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | EMR_CREATEMONOBRUSH kaydı, grafik işlemleri için bir monokrom desen fırçasını tanımlar. Desen, monokrom bir DIB tarafından belirtilir. |
| [EmfCreatePalette](./emfcreatepalette) | EMR_CREATEPALETTE kaydı, grafik işlemleri için mantıksal bir palet tanımlar. |
| [EmfCreatePen](./emfcreatepen) | EMR_CREATEPEN kaydı, grafik işlemleri için mantıksal bir kalem tanımlar. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | EMR_DELETECOLORSPACE kaydı, mantıksal bir renk uzayı nesnesini siler. |
| [EmfDeleteObject](./emfdeleteobject) | EMR_DELETEOBJECT kaydı, EMF Nesne Tablosunda (bölüm 3.1.1.1) dizini tarafından belirtilen bir grafik nesnesini siler. |
| [EmfDrawEscape](./emfdrawescape) | EMR_DRAWESCAPE kaydı, isteğe bağlı bilgileri bir yazıcı sürücüsüne iletir. Amaç, bilgisinin çizimin yapılmasıyla sonuçlanmasıdır. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | Çizim kayıt türleri, grafik çizimi gerçekleştirir. |
| [EmfEllipse](./emfellipse) | EMR_ELLIPSE kaydı bir elipsi belirtir. Elipsin merkezi, belirtilen sınırlayıcı dikdörtgenin merkezidir. Elips, geçerli kalem kullanılarak ana hatları çizilir ve mevcut fırça kullanılarak doldurulur. |
| [EmfEndPath](./emfendpath) | Bu kayıt bir yol parantezini kapatır ve parantez tarafından tanımlanan yolu oynatma aygıtı bağlamına seçer. |
| [EmfEof](./emfeof) | EMR_EOF kaydı, meta dosyasının sonunu belirtir ve bir palet belirtir. |
| [EmfEscapeRecordType](./emfescaperecordtype) | Kaçış kaydı türleri, yazıcı sürücüsü işlevlerini yürütür. |
| [EmfExcludeClipRect](./emfexcludecliprect) | EMR_EXCLUDECLIPRECT kaydı, mevcut kırpma bölgesinden belirtilen dikdörtgenin çıkarılmasıyla oluşan yeni bir kırpma bölgesini belirtir. Not Bu bölümde açıklanmayan alanlar 2.3.2. bölümünde belirtilmiştir. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | EMR_EXTCREATEFONTINDIRECTW kaydı, grafik işlemleri için mantıksal bir yazı tipi tanımlar. |
| [EmfExtCreatePen](./emfextcreatepen) | EMR_EXTCREATEPEN kaydı, grafik işlemleri için genişletilmiş bir mantıksal kalem tanımlar. An isteğe bağlı DIB, çizgi stili olarak kullanılmak üzere belirtilebilir. |
| [EmfExtEscape](./emfextescape) | EMR_EXTESCAPE kaydı, isteğe bağlı bilgileri bir yazıcı sürücüsüne iletir. Amaç, bilgisinin çizimin yapılmasıyla sonuçlanmamasıdır. |
| [EmfExtFloodFill](./emfextfloodfill) | EMR_EXTFLOODFILL kaydı, ekran yüzeyinin bir alanını geçerli fırça ile doldurur |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | EMR_EXTSELECTCLIPRGN kaydı, belirtilen modu kullanarak belirtilen bölgeyi geçerli klip bölgesi ile birleştirir. Not Bu bölümde açıklanmayan alanlar 2.3.2. bölümünde belirtilmiştir. |
| [EmfExtTextOutA](./emfexttextouta) | EMR_EXTTEXTOUTA kaydı, geçerli yazı tipini ve metin renklerini kullanarak bir ASCII metin dizesi çizer. |
| [EmfExtTextOutW](./emfexttextoutw) | EMR_EXTTEXTOUTW kaydı, geçerli yazı tipini ve metin renklerini kullanarak bir ASCII metin dizesi çizer. |
| [EmfFillPath](./emffillpath) | EMR_FILLPATH kaydı, geçerli yoldaki tüm açık şekilleri kapatır ve geçerli fırça ve çokgen doldurma modunu kullanarak yolun içini doldurur. |
| [EmfFillRgn](./emffillrgn) | EMR_FILLRGN kaydı, belirtilen fırçayı kullanarak belirtilen bölgeyi doldurur. |
| [EmfFlatternPath](./emfflatternpath) | Bu kayıt, seçilen yoldaki tüm eğrileri oynatma aygıtı bağlamına dönüştürür; her eğri bir satır dizisine DÖNÜŞTÜRÜLMELİDİR. |
| [EmfForceUfiMapping](./emfforceufimapping) | EMR_FORCEUFIMAPPING kaydı, yazı tipi eşleyicisini, LogFont (bölüm 2.2.13) bilgilerine göre, onların UniversalFontId'lerine göre yazı tiplerini eşleştirmeye zorlar. |
| [EmfFrameRgn](./emfframergn) | EMR_FRAMERGN kaydı, belirtilen fırçayı kullanarak belirtilen bölgenin çevresine bir sınır çizer. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | EMR_GLSBOUNDEDRECORD kaydı, çıktı için sınırlayıcı bir dikdörtgene sahip bir OpenGL işlevini belirtir. |
| [EmfGlsRecord](./emfglsrecord) | EMR_GLSRECORD kaydı bir OpenGL işlevini belirtir. |
| [EmfGradientFill](./emfgradientfill) | EMR_GRADIENTFILL kaydı, dikdörtgenleri veya üçgenleri renk gradyanlarıyla doldurmayı belirtir. |
| [EmfIntersectClipRect](./emfintersectcliprect) | EMR_INTERSECTCLIPRECT kaydı, geçerli kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi belirtir. Not Bu bölümde açıklanmayan alanlar 2.3.2. bölümünde belirtilmiştir. |
| [EmfInvertRgn](./emfinvertrgn) | EMR_INVERTRGN kaydı, belirtilen bölgedeki renkleri tersine çevirir. |
| [EmfLineTo](./emflineto) | EMR_LINETO kaydı, geçerli konumdan belirtilen noktasına kadar olan ancak bu noktayı içermeyen bir çizgi belirtir. Geçerli konumu belirtilen noktaya sıfırlar. |
| [EmfMaskBlt](./emfmaskblt) | EMR_MASKBLT kaydı, belirtilen ön plan ve arka plan tarama işlemlerine göre, isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bitmap uygulamasıyla birlikte, bir kaynak bitmap'ten hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| [EmfMetafileHeader](./emfmetafileheader) | EMR_HEADER kayıt türleri, EMF metafiles başlangıç noktalarını tanımlar ve metafile içindeki görüntünün oluşturulduğu aygıtın özelliklerini belirtir. Başlık kaydındaki bilgiler, EMF meta dosyalarının herhangi bir belirli çıktı aygıtından bağımsız olmasını mümkün kılar. Boyut alanının değeri, bu bölümde daha önce listelenen farklı EMR_HEADER kayıt türlerini ayırt etmek için kullanılabilir. Üç olası durum vardır. headers: EmfMetafileHeader kaydı olan temel başlık. Bu başlığın sabit boyutlu kısmı 88 bayttır ve bir Header nesnesi içerir. EmfMetafileHeaderExtension1 kaydı olan ilk uzantı başlığı. Sabit boyutlu bu başlığın bir kısmı 100 bayttır ve bir Header object ve bir HeaderExtension1 nesnesi içerir (bölüm 2.2.10). EmfMetafileHeaderExtension2 kaydı olan ikinci uzantı başlığı. Bu başlığın sabit boyutlu kısmı 108 bayttır, ve bir Header nesnesi, bir HeaderExtension1 nesnesi ve bir HeaderExtension2 nesnesi içerir (bölüm 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | EmfMetafileHeaderExtension1 kaydı, EMF meta dosyalarının ilk uzantısında kullanılan başlık kaydıdır. EmfHeaderExtension1 alanının ardından kalan alanlar isteğe bağlıdır ve herhangi bir sırada bulunabilir. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | EmfMetafileHeaderExtension2 kaydı, EMF meta dosyalarının ikinci uzantısında kullanılan başlık kaydıdır. EmfHeaderExtension2 alanının ardından kalan alanlar isteğe bağlıdır ve herhangi bir sırada mevcut olabilir. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | EMR_MODIFYWORLDTRANSFORM kaydı, oynatma aygıtı bağlamında geçerli dünya-alanı page-space dönüşümüne değiştirir. |
| [EmfMoveToEx](./emfmovetoex) | EMR_MOVETOEX kaydı, yeni geçerli konumun koordinatlarını mantıksal birimlerde belirtir. |
| [EmfNamedEscape](./emfnamedescape) | MR_NAMEDESCAPE kaydı, rastgele bilgileri belirtilen bir yazıcı sürücüsüne iletir. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | Nesne oluşturma kayıt türleri, grafik nesneleri oluşturur. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | Nesne işleme kayıt türleri, grafik nesnelerini yönetir ve değiştirir. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | EMR_OFFSETCLIPRGN kaydı, oynatma aygıtı bağlamındaki geçerli kırpma bölgesini belirtilen ofsetlerle hareket ettirir. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | OpenGL kayıt türleri, OpenGL işlevlerini belirtir. |
| [EmfPaintRgn](./emfpaintrgn) | EMR_PAINTRGN kaydı, oynatma aygıtı bağlamında seçili olan fırçayı kullanarak belirtilen bölgeyi boyar. |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | Yol parantez kayıt türleri, yol parantezlerindeki yolları belirtir ve işler. Not: Yol parantez kayıtlarının hiçbiri parametreleri belirtmez. |
| [EmfPie](./emfpie) | EMR_PIE kaydı, bir elips ve iki radyalinin kesişimiyle sınırlanan pasta şeklindeki bir kamayı belirtir. Pasta, mevcut kalem kullanılarak ana hatları çizilir ve mevcut fırça kullanılarak doldurulur. |
| [EmfPixelFormat](./emfpixelformat) | EMR_PIXELFORMAT kaydı, grafik işlemleri için kullanılacak piksel biçimini belirtir. |
| [EmfPlgBlt](./emfplgblt) | EMR_PLGBLT kaydı, bir renk maskesi bitmap uygulamasıyla bir kaynak bitmap'ten bir hedef paralelkenarına piksellerin blok aktarımını belirtir. |
| [EmfPolyBezier](./emfpolybezier) | EMR_POLYBEZIER kaydı, bir veya daha fazla Bezier eğrisini belirtir. |
| [EmfPolyBezier16](./emfpolybezier16) | EMR_POLYBEZIER16 kaydı, bir veya daha fazla Bezier eğrisini belirtir. Eğriler, mevcut kalemle kullanılarak çizilir. |
| [EmfPolyBezierTo](./emfpolybezierto) | EMR_POLYBEZIERTO kaydı, geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi belirtir. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | EMR_POLYBEZIERTO16 kaydı, geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi belirtir. |
| [EmfPolyDraw](./emfpolydraw) | EMR_POLYDRAW kaydı, bir dizi çizgi parçası ve Bezier eğrisi belirtir. |
| [EmfPolyDraw16](./emfpolydraw16) | EMR_POLYDRAW16 kaydı, bir dizi çizgi parçası ve Bezier eğrisi belirtir. |
| [EmfPolygon](./emfpolygon) | EMR_POLYGON kaydı, düz çizgilerle bağlanan iki veya daha fazla tepe noktasından oluşan bir çokgen belirtir. |
| [EmfPolygon16](./emfpolygon16) | EMR_POLYGON16 kaydı, düz çizgilerle bağlanan iki veya daha fazla tepe noktasından oluşan bir çokgen belirtir. Çokgen, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça ve çokgen doldurma modu kullanılarak doldurulur. Çokgen, son tepe noktasından ilk noktaya bir çizgi çizilerek otomatik olarak kapatılır. |
| [EmfPolyline](./emfpolyline) | EMR_POLYLINE kaydı, belirtilen dizideki noktaları bağlayarak bir dizi çizgi parçası belirtir. |
| [EmfPolyline16](./emfpolyline16) | EMR_POLYLINE16 kaydı, belirtilen dizisindeki noktaları bağlayarak bir dizi çizgi parçasını belirtir. |
| [EmfPolylineTo](./emfpolylineto) | EMR_POLYLINETO kaydı, geçerli konuma dayalı olarak bir veya daha fazla düz çizgi belirtir. |
| [EmfPolylineTo16](./emfpolylineto16) | EMR_POLYLINETO16 kaydı, geçerli konuma dayalı olarak bir veya daha fazla düz çizgi belirtir. geçerli kalem kullanılarak, aPoints alanında belirtilen ilk noktaya geçerli konumdan bir çizgi çizilir. Her ek çizgi için, önceki çizgisinin bitiş noktasından aPoints tarafından belirtilen bir sonraki noktaya çizim yapılır. |
| [EmfPolyPolygon](./emfpolypolygon) | EMR_POLYPOLYGON kaydı, bir dizi kapalı çokgen belirtir. |
| [EmfPolyPolygon16](./emfpolypolygon16) | EMR_POLYPOLYGON16 kaydı, bir dizi kapalı çokgen belirtir. Her çokgen, geçerli kalem kullanılarak ana hatlarıyla çizilir ve geçerli fırça ve çokgen doldurma modu kullanılarak doldurulur. Bu kayıt tarafından çizilen çokgenler çakışabilir. |
| [EmfPolyPolyline](./emfpolypolyline) | EMR_POLYPOLYLINE kaydı, birden çok bağlantılı hat segmenti serisini belirtir. |
| [EmfPolyPolyline16](./emfpolypolyline16) | EMR_POLYPOLYLINE16 kaydı, birden çok bağlantılı hat segmenti serisini belirtir. |
| [EmfPolyTextOutA](./emfpolytextouta) | EMR_POLYTEXTOUTA kaydı, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer. |
| [EmfPolyTextOutW](./emfpolytextoutw) | EMR_POLYTEXTOUTW kaydı, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer. |
| [EmfRealizePalette](./emfrealizepalette) | Bu kayıt, current LogPalette nesnesinden (bölüm 2.2.17) gelen palet girişlerini system_palette. ile eşler. Bu EMF kaydı hiçbir parametre belirtmiyor. |
| [EmfRecord](./emfrecord) | EMF kayıtları için temel sınıf Tüm EMF kayıtları, 4 baytın katı bir uzunluğa sahip OLMALIDIR. Bu, önceki EMF kayıt türlerinin genel yapılarında, uygun olduğunda bu yapıların uçlarına AlignmentPadding field dahil edilerek gösterilmektedir. AlignmentPadding field içeriği her zaman yok sayılmalıdır. Kısaca, bu alanlar her bir EMF kayıt tanımında gösterilmez. |
| [EmfRectangle](./emfrectangle) | EMR_RECTANGLE kaydı bir dikdörtgen çizer. Dikdörtgen, geçerli pen kullanılarak ana hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| [EmfResizePalette](./emfresizepalette) | EMR_RESIZEPALETTE kaydı, mevcut bir LogPalette nesnesinin boyutunu artırır veya azaltır (bölüm 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | EMR_RESTOREDC kaydı, oynatma aygıtı bağlamını belirtilen duruma geri yükler. oynatma aygıtı bağlamı, önceki EMR_SAVEDC kayıtları (bölüm 2.3.11) tarafından tarafından oluşturulan bir yığından durum bilgisi çıkarılarak geri yüklenir. |
| [EmfRop4](./emfrop4) | Bir bitmap'in ön plan ve arka plan renkleri olan için üçlü tarama işlemlerini belirten bir dörtlü tarama işlemi. Bu değerler, kaynak dikdörtgenin renk verilerinin hedef dikdörtgenin renk verileriyle nasıl birleştirileceğini tanımlar. |
| [EmfRoundRect](./emfroundrect) | EMR_ROUNDRECT kaydı, köşeleri yuvarlatılmış bir dikdörtgeni belirtir. Dikdörtgen, geçerli kalem kullanılarak dış hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| [EmfSaveDc](./emfsavedc) | Kayıttan yürütme aygıtı bağlamının mevcut durumunu, varsa, önceki EMR_SAVEDC kayıtları tarafından kaydedilen a durum yığınına kaydeder. Durum, şu anda seçili bitmap, fırça, palet, yazı tipi, kalem ve bölge dahil olmak üzere grafik özellikleri ve nesnelerden oluşur. Durumu geri yüklemek için bir EMR_RESTOREDC kaydı kullanılır. Bu EMF kaydı hiçbir parametre belirtmiyor. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | EMR_SCALEVIEWPORTEXTEX kaydı, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranlarını kullanarak bir cihaz bağlamı için görünüm penceresini yeniden belirtir. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | EMR_SCALEWINDOWEXTEX kaydı, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranları kullanarak bir oynatma cihazı bağlamı için pencereyi by yeniden belirtir. |
| [EmfSelectClipPath](./emfselectclippath) | EMR_SELECTCLIPPATH kaydı, yeni bölgeyi belirtilen modu kullanarak mevcut herhangi bir kırpma bölgesiyle birleştirerek, oynatma cihaz bağlamı için bir kırpma bölgesi olarak geçerli yolu belirtir. |
| [EmfSelectObject](./emfselectobject) | EMR_SELECTOBJECT kaydı, geçerli meta dosyası oynatma aygıtı bağlamına bir grafik nesnesi ekler. Nesne, ya EMF Nesne Tablosundaki (bölüm 3.1.1.1) dizini ile ya da StockObject numaralandırmasındaki (bölüm 2.1.31) its değeri ile belirtilir. |
| [EmfSelectPalette](./emfselectpalette) | EMR_SELECTPALETTE kaydı, oynatma aygıtı bağlamı için mantıksal bir palet belirtir. |
| [EmfSetArcDirection](./emfsetarcdirection) | EMR_SETARCDIRECTION kaydı, yay ve dikdörtgen çıktısı için kullanılacak çizim yönünü belirtir. |
| [EmfSetBkColor](./emfsetbkcolor) | EMR_SETBKCOLOR kaydı, arka plan rengini belirtir. |
| [EmfSetBkMode](./emfsetbkmode) | EMR_SETBKMODE kaydı, oynatma aygıtı bağlamının arka plan karıştırma modunu belirtir. Arka plan karıştırma modu, düz çizgiler olmayan metin, taramalı fırçalar ve kalem stilleriyle kullanılır. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | EMR_SETBRUSHORGEX kaydı, geçerli fırçanın kaynağını belirtir. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | EMR_SETCOLORADJUSTMENT kaydı, oynatma cihaz bağlamında renk ayarlama özelliklerini belirtir. |
| [EmfSetColorSpace](./emfsetcolorspace) | EMR_SETCOLORSPACE kaydı, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | EMR_SETDIBITSTODEVICE kaydı, bir kaynak bit eşleminin belirtilen tarama satırlarından bir hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| [EmfSetIcmMode](./emfseticmmode) | EMR_SETICMMODE kaydı, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | EMR_SETICMPROFILEA kaydı, grafik çıktısı için ASCII karakterlerinden oluşan bir ada sahip bir dosyadaki bir renk profilini belirtir. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | EMR_SETICMPROFILEW kaydı, grafik çıktısı için Unicode karakterlerden oluşan bir dosyadaki bir renk profilini belirtir. |
| [EmfSetLayout](./emfsetlayout) | EMR_SETLAYOUT kaydı, metin ve grafiklerin çizilme sırasını belirtir. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | EMR_SETLINKEDUFIS kaydı, bağlantılı yazı tiplerinin UniversalFontId'lerini (bölüm 2.2.27) karakter araması sırasında kullanılacak olarak ayarlar. |
| [EmfSetMapMode](./emfsetmapmode) | EMR_SETMAPMODE kaydı, oynatma aygıtı bağlamının eşleme modunu belirtir. Eşleme modu, sayfa alanı birimlerini aygıt alanı birimlerine dönüştürmek için kullanılan ölçü birimini belirtir ve ayrıca aygıtın x ekseni ve y ekseninin yönünü belirtir. |
| [EmfSetMapperFlags](./emfsetmapperflags) | EMR_SETMAPPERFLAGS kaydı, mantıksal yazı tiplerini, yazı tipi eşleyicisi tarafından gerçekleştirilen, fiziksel yazı tipleriyle eşleştirme sürecinin parametrelerini belirtir. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter, oynatma aygıtı bağlamı için yeni bir meta bölge oluşturmak üzere geçerli meta bölgesini geçerli kırpma bölgesi ile ayarlar. Geçerli kırpma bölgesi null değerine sıfırlanmalıdır. Bu EMF kaydı hiçbir parametre belirtmiyor. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | EMR_SETMITERLIMIT kaydı, oynatma aygıtı bağlamı için gönye birleştirmelerinin uzunluğu sınırını belirtir. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | EMR_SETPALETTEENTRIES kaydı, mevcut bir LogPalette (bölüm 2.2.17) nesnesi için bir dizi girişte RGB renk değerlerini tanımlar. |
| [EmfSetPixelV](./emfsetpixelv) | EMR_SETPIXELV kaydı, belirtilen mantıksal koordinatlarda pikselin rengini tanımlar. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | EMR_SETPOLYFILLMODE kaydı çokgen doldurma modunu tanımlar. |
| [EmfSetRop2](./emfsetrop2) | EMR_SETROP2 kaydı, ikili tarama çalışma modunu tanımlar. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | EMR_SETSTRETCHBLTMODE kaydı, bitmap uzatma modunu belirtir. |
| [EmfSetTextAlign](./emfsettextalign) | EMR_SETTEXTALIGN kaydı, metin hizalamasını belirtir. |
| [EmfSetTextColor](./emfsettextcolor) | EMR_SETTEXTCOLOR kaydı, geçerli metin rengini tanımlar. |
| [EmfSetTextJustification](./emfsettextjustification) | EMR_SETTEXTJUSTIFICATION kaydı, metin yaslama için break karakterlerine eklenecek fazladan boşluk miktarını belirtir. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | EMR_SETVIEWPORTEXTEX kaydı, görünüm alanının kapsamını tanımlar. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | EMR_SETVIEWPORTORGEX kaydı, görünüm alanı kaynağını tanımlar. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | EMR_SETWINDOWEXTEX kaydı, pencere kapsamını tanımlar. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | EMR_SETWINDOWORGEX kaydı, pencere kökenini tanımlar. |
| [EmfSetWorldTransform](./emfsetworldtransform) | EMR_SETWORLDTRANSFORM kaydı, oynatma aygıtı bağlamında geçerli dünya-uzaydan sayfa alanına dönüşüm için bir dönüşüm belirtir. |
| [EmfSmallTextOut](./emfsmalltextout) | EMR_SMALLTEXTOUT kaydı bir dize çıkarır. |
| [EmfStateRecordType](./emfstaterecordtype) | Durum kaydı türleri, oynatma aygıtı bağlamının durumunu tanımlayan grafik özelliklerini belirtir ve yönetir. |
| [EmfStretchBlt](./emfstretchblt) | EMR_STRETCHBLT kaydı, isteğe bağlı olarak, belirtilen bir raster işlemine göre bir fırça deseniyle birlikte, gerekirse hedefin boyutlarına uyacak şekilde çıktıyı gererek veya sıkıştırarak, bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir. . |
| [EmfStretchDiBits](./emfstretchdibits) | EMR_STRETCHDIBITS kaydı, isteğe bağlı olarak, belirtilen bir tarama işlemine göre bir fırça deseniyle birlikte, bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir; gerekli. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | EMR_STROKEANDFILLPATH kaydı bir yoldaki tüm açık şekilleri kapatır, geçerli kalemi kullanarak yolunun ana hatlarını çizer ve geçerli fırçayı kullanarak içini doldurur. |
| [EmfStrokePath](./emfstrokepath) | EMR_STROKEPATH sınıfı |
| [EmfTransformRecordType](./emftransformrecordtype) | Dönüştürme kayıt türleri, dünya-alanını sayfa-alanına dönüşümlerini belirtir ve değiştirir. |
| [EmfTransparentBlt](./emftransparentblt) | EMR_TRANSPARENTBLT kaydı, bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir, belirtilen bir rengi şeffaf olarak ele alır, gerekirse çıktıyı hedefin boyutlarına uyacak şekilde genişletir veya sıkıştırır |
| [EmfVertexData](./emfvertexdata) | Dikdörtgenlerin veya üçgenlerin tepe noktalarını ve bunlara karşılık gelen renkleri belirten nesneler. |
| [EmfWidenPath](./emfwidenpath) | Bu kayıt, mevcut yolu, path oynatma aygıtı bağlamında seçili olan kalem kullanılarak çizilirse boyanacak alan olarak yeniden tanımlar. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
