---
title: "EmfRecordType Sınıflandırması"
type: docs
weight: 290
url: /tr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

RecordType sayımı, EMF kayıtlarını benzersiz şekilde tanımlayan değerleri tanımlar.<br/>            Bu değerler her kaydın Type alanında sağlanır.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| EMR_ABORTPATH | Bu kayıt bir yol parantezini iptal eder veya kapalı bir yol parantezinden yolu atar. |
| EMR_ALPHABLEND | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene piksel blok aktarımını belirtir,<br/>             alfa şeffaflık verilerini içerecek şekilde, belirli bir karıştırma işlemi göreviyle. |
| EMR_ANGLEARC | Bu kayıt, bir yayının çizgi segmentini tanımlar. Çizgi segmenti, <br/>            mevcut konumdan yayının başlangıcına çizilir. Yay, verilen yarıçap ve merkezle bir dairenin çevresi boyunca çizilir. Yayın uzunluğu, verilen başlangıç ve süpürme açılarıyla tanımlanır. |
| EMR_ARC | Bu kayıt, eliptik bir yay tanımlar. |
| EMR_ARCTO | Bu kayıt, eliptik bir yay tanımlar. Mevcut konumu, yayının <br/>            son noktasına sıfırlar. |
| EMR_BEGINPATH | Bu kayıt, oynatma aygıt bağlamında bir yol parantezi açar. |
| EMR_BITBLT | Bu kayıt, bir kaynak bitmap'ten bir hedef<br/>             dikdörtgene piksel blok aktarımını, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göreviyle belirtir. |
| EMR_CHORD | Bu kayıt, bir kord (elips ile bir çizgi segmentinin kesişimiyle sınırlanan bir bölge, sekant olarak adlandırılır) tanımlar. Kord, mevcut <br/>            kalem kullanılarak konturlanır ve mevcut fırça kullanılarak doldurulur. |
| EMR_CLOSEFIGURE | Bu kayıt, bir yoldaki açık bir şekli kapatır. |
| EMR_COLORCORRECTPALETTE | Bu kayıt, Windows <br/>            Color System (WCS) 1.0 değerlerini kullanarak mantıksal bir palet nesnesinin girişlerini nasıl düzelteceğini belirtir. |
| EMR_COLORMATCHTOTARGETW | Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir dosyada belirtilen renk profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirtir. |
| EMR_COMMENT | Bu kayıt, isteğe bağlı özel verileri belirtir. |
| EMR_CREATEBRUSHINDIRECT | Bu kayıt, grafik işlemlerinde şekil doldurmak için mantıksal bir fırça tanımlar. |
| EMR_CREATECOLORSPACE | Bu kayıt, ASCII karakterlerinden oluşan bir ada sahip bir renk profiliyle mantıksal bir renk alanı nesnesi oluşturur |
| EMR_CREATECOLORSPACEW | Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir renk profiliyle mantıksal bir renk alanı nesnesi oluşturur |
| EMR_CREATEDIBPATTERNBRUSHPT | Bu kayıt, DIB tarafından belirtilen desene sahip mantıksal bir fırça tanımlar. |
| EMR_CREATEMONOBRUSH | Bu kayıt, belirtilen bitmap deseniyle mantıksal bir fırça tanımlar. Bitmap, <br/>             cihazdan bağımsız bir bitmap (DIB) bölüm bitmapi olabileceği gibi cihazdan bağımlı bir bitmap de olabilir. |
| EMR_CREATEPALETTE | Bu kayıt, bir LogPalette nesnesi tanımlar. |
| EMR_CREATEPEN | Bu kayıt, belirtilen stil, genişlik ve renge sahip mantıksal bir kalem tanımlar. <br/>            Kalem daha sonra oynatma cihaz bağlamına seçilebilir ve çizgi ve eğrileri çizmek için kullanılabilir. |
| EMR_DELETECOLORSPACE | Bu kayıt, mantıksal bir renk alanı nesnesini siler. Not: Mantıksal bir renk alanı nesnesini silmek için EMR_DELETECOLORSPACE yerine bir EMR_DELETEOBJECT kaydı <br/>            kullanılmalıdır. |
| EMR_DELETEOBJECT | Bu kayıt, bir grafik nesnesini siler ve EMF Nesne Tablosundaki indeksini temizler. <br/>            Silinen nesne oynatma cihaz bağlamında seçili ise, o bağlam özelliği için varsayılan nesne <br/>            geri yüklenmelidir. |
| EMR_DRAWESCAPE | Bu kayıt, sürücüye isteğe bağlı bilgi gönderir. Amacı, bilginin <br/>            çizim yapılmasına yol açmasıdır. |
| EMR_ELLIPSE | Bu kayıt bir elips tanımlar. Elipsin merkezi, belirtilen sınırlayıcı dikdörtgenin merkezidir. Elips, mevcut kalemi kullanarak çizilir ve <br/>            mevcut fırça kullanılarak doldurulur. |
| EMR_ENDPATH | Bu kayıt bir yol parantezini kapatır ve parantez tarafından tanımlanan yolu <br/>            oynatma cihaz bağlamına seçer. |
| EMR_EOF | Bu kayıt metafaylın sonunu gösterir. |
| EMR_EXCLUDECLIPRECT | Bu kayıt, mevcut kırpma bölgesi <br/>            belirtilen dikdörtgenin çıkarılmasıyla oluşan yeni bir kırpma bölgesi tanımlar. |
| EMR_EXTCREATEFONTINDIRECTW | Bu kayıt, belirtilen özelliklere sahip mantıksal bir yazı tipini tanımlar. Yazı tipi <br/>            daha sonra oynatma cihaz bağlamı için geçerli yazı tipi olarak seçilebilir. |
| EMR_EXTCREATEPEN | Bu kayıt, belirtilen stil, <br/>            genişlik ve fırça özelliklerine sahip mantıksal bir kozmetik veya geometrik kalemi tanımlar. |
| EMR_EXTESCAPE | Bu kayıt, sürücüye keyfi bilgi gönderir. Amacı, bilginin <br/>            çizim yapılmasına neden olmamasıdır. |
| EMR_EXTFLOODFILL | Bu kayıt, görüntü yüzeyinin bir alanını mevcut fırça ile doldurur. |
| EMR_EXTSELECTCLIPRGN | Bu kayıt, belirtilen bölgeyi mevcut kırpma bölgesiyle <br/>            belirtilen modda birleştirir. |
| EMR_EXTTEXTOUTA | Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir ASCII metin dizesi çizer. Not <br/>            EMR_EXTTEXTOUTA, bir EMR_EXTTEXTOUTW kaydı (bölüm 2.3.5.8) ile taklit edilmelidir.  <br/>            Bu, EmrText nesnesindeki ASCII metin dizesinin Unicode UTF16-LE kodlamasına dönüştürülmesini gerektirir. |
| EMR_EXTTEXTOUTW | Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir Unicode metin dizesi çizer. |
| EMR_FILLPATH | Bu kayıt, mevcut yoldaki açık tüm şekilleri kapatır ve yolun iç kısmını <br/>            mevcut fırça ve çokgen doldurma modu kullanarak doldurur. |
| EMR_FILLRGN | Bu kayıt, belirtilen bölgeyi belirtilen fırça kullanarak doldurur. |
| EMR_FLATTENPATH | Bu kayıt, seçilen yoldaki herhangi bir eğriyi oynatma cihazı <br/>            bağlamına dönüştürür ve her eğriyi bir dizi çizgiye çevirir. |
| EMR_FORCEUFIMAPPING | Bu kayıt, yazı tipi eşleyicisinin yazı tiplerini UniversalFontId'lerine göre, <br/>            LogFont bilgilerine tercih vererek eşlemesini zorlar. |
| EMR_FRAMERGN | Bu kayıt, belirtilen bölgenin etrafına belirtilen fırça kullanılarak bir kenarlık çizer. |
| EMR_GLSBOUNDEDRECORD | Bu kayıt, çıktı için sınırlayıcı bir dikdörtgen içeren bir OpenGL işlevini belirtir. |
| EMR_GLSRECORD | Bu kayıt, bir OpenGL işlevini belirtir. |
| EMR_GRADIENTFILL | Bu kayıt, dikdörtgenleri veya üçgenleri renk geçişleriyle doldurulmasını belirtir. |
| EMR_HEADER | Bu kayıt, metafayın başlangıcını tanımlar ve özelliklerini belirtir; içeriği, <br/>            gömülü görüntünün boyutları dahil; metafaydaki kayıt sayısı; ve <br/>            gömülü görüntünün oluşturulduğu cihazın çözünürlüğü. Bu değerler, metafayın cihaz bağımsız olmasını sağlar. |
| EMR_INTERSECTCLIPRECT | Bu kayıt, mevcut kırpma <br/>            bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar. |
| EMR_INVERTRGN | Bu kayıt, belirtilen bölgedeki renkleri tersine çevirir. |
| EMR_LINETO | Bu kayıt, mevcut konumdan belirtilen noktaya kadar (nokta dahil olmadan) bir çizgi tanımlar,<br/>             belirtilen noktaya. Mevcut konumu belirtilen noktaya sıfırlar. |
| EMR_MASKBLT | Bu kayıt, bir kaynak bitmap'ten bir hedef<br/>             dikdörtgene piksel bloğu aktarımını, isteğe bağlı olarak bir fırça deseniyle ve bir <br/>            renk maskesi bitmap'inin uygulanmasıyla, belirtilen ön plan ve arka plan raster işlemlerine göre belirtir. |
| EMR_MODIFYWORLDTRANSFORM | Bu kayıt, belirtilen modu kullanarak oynatma cihazı bağlamı için dünya dönüşümünü yeniden tanımlar. |
| EMR_MOVETOEX | Bu kayıt, yeni geçerli konumun koordinatlarını mantıksal birimlerde tanımlar. |
| EMR_NAMEDESCAPE | Bu kayıt, verilen adlandırılmış sürücüye keyfi bilgileri iletir. |
| EMR_OFFSETCLIPRGN | Bu kayıt, belirtilen ofsetlerle oynatma aygıt bağlamının kırpma bölgesini yeniden tanımlar. |
| EMR_PAINTRGN | Bu kayıt, belirtilen bölgeyi şu anda <br/>            oynatma aygıt bağlamına seçili fırça kullanarak boyar. |
| EMR_PIE | Bu kayıt, bir elipsin kesişimi <br/>            ve iki radyal tarafından sınırlanan pasta şeklinde bir dilimi tanımlar. Pasta, mevcut kalem kullanılarak konturlanır ve <br/>            mevcut fırça kullanılarak doldurulur. |
| EMR_PIXELFORMAT | Bu kayıt, grafik işlemleri için kullanılacak piksel biçimini belirtir |
| EMR_PLGBLT | Bu kayıt, bir kaynak bitmap'ten hedef <br/>            paralelograma piksel blok aktarımını, bir renk maskesi bitmap'i uygulanarak belirtir. |
| EMR_POLYBEZIER | Bu kayıt bir veya daha fazla Bezier eğrisi tanımlar. Kübik Bezier eğrileri <br/>            belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır ve mevcut kalemle çizilir. |
| EMR_POLYBEZIER16 | Bu kayıt bir veya daha fazla Bezier eğrisi tanımlar. Eğriler mevcut kalem kullanılarak çizilir. |
| EMR_POLYBEZIERTO | Bu kayıt, mevcut konuma dayalı bir veya daha fazla Bezier eğrisi tanımlar. |
| EMR_POLYBEZIERTO16 | Bu kayıt, mevcut konuma dayalı bir veya daha fazla Bezier eğrisi tanımlar. |
| EMR_POLYDRAW | Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar. |
| EMR_POLYDRAW16 | Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar. |
| EMR_POLYGON | Bu kayıt, iki veya daha fazla köşeyi düz <br/>            çizgilerle bağlayan bir çokgen tanımlar. Çokgen, mevcut kalemi kullanarak ana hatları çizilir ve mevcut fırça <br/>            ve çokgen doldurma modu kullanılarak doldurulur. Çokgen, son köşeden ilk köşeye bir çizgi çizilerek otomatik olarak kapatılır. |
| EMR_POLYGON16 | Bu kayıt, iki veya daha fazla köşeyi düz çizgilerle bağlayan bir çokgen tanımlar. <br/>            Çokgen, mevcut kalemi kullanarak ana hatları çizilir ve mevcut fırça ve çokgen<br/>             doldurma modu kullanılarak doldurulur. Çokgen, son köşeden ilk köşeye bir çizgi çizilerek otomatik olarak kapatılır. |
| EMR_POLYLINE | Bu kayıt, belirtilen <br/>            dizi içindeki noktaları bağlayarak bir dizi çizgi segmenti tanımlar. |
| EMR_POLYLINE16 | Bu kayıt, belirtilen dizi içindeki noktaları bağlayarak bir dizi çizgi segmenti tanımlar. |
| EMR_POLYLINETO | Bu kayıt, mevcut konuma dayanarak bir veya daha fazla düz çizgi tanımlar. <br/>            Bir çizgi, mevcut konumdan noktalar alanı tarafından belirtilen ilk noktaya <br/>            mevcut kalem kullanılarak çizilir. Her ek çizgi için, çizim önceki çizginin bitiş <br/>            noktasından noktalar tarafından belirtilen bir sonraki noktaya yapılır. |
| EMR_POLYLINETO16 | Bu kayıt, mevcut konuma dayanarak bir veya daha fazla düz çizgi tanımlar.<br/>             Bir çizgi, mevcut konumdan Points alanı tarafından belirtilen ilk noktaya <br/>            mevcut kalem kullanılarak çizilir. Her ek çizgi için, çizim <br/>            önceki çizginin bitiş noktasından Points tarafından belirtilen bir sonraki noktaya yapılır. |
| EMR_POLYPOLYGON | Bu kayıt, bir dizi kapalı çokgen tanımlar. <br/>            Her çokgen, mevcut kalemi kullanarak ana hatları çizilir ve mevcut fırça ve çokgen doldurma modu kullanılarak doldurulur. <br/>            Bu kayıt tarafından tanımlanan çokgenler üst üste gelebilir. |
| EMR_POLYPOLYGON16 | Bu kayıt, bir dizi kapalı çokgen tanımlar. <br/>            Her çokgen, mevcut kalemi kullanarak ana hatları çizilir ve mevcut fırça ve çokgen doldurma modu kullanılarak doldurulur. <br/>            Bu kayıt tarafından belirtilen çokgenler üst üste gelebilir. |
| EMR_POLYPOLYLINE | Bu kayıt, birden çok bağlı çizgi segmenti serisi tanımlar. Çizgi segmentleri <br/>            mevcut kalem kullanılarak çizilir. Segmentler tarafından oluşturulan şekiller doldurulmaz. <br/>            Mevcut konum bu kayıt tarafından ne kullanılır ne de güncellenir. |
| EMR_POLYPOLYLINE16 | Bu kayıt, birden çok bağlı çizgi segmenti serisi tanımlar. |
| EMR_POLYTEXTOUTA | Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer.<br/>             Not: EMR_POLYTEXTOUTA, her dize için bir EMR_EXTTEXTOUTW kaydı serisiyle taklit edilmelidir. |
| EMR_POLYTEXTOUTW | Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer.<br/>            Not: EMR_POLYTEXTOUTW, her dize için bir EMR_EXTTEXTOUTW kaydı serisiyle taklit edilmelidir. |
| EMR_REALIZEPALETTE | Bu kayıt, mevcut mantıksal paletten girişleri sistem paletine eşler. |
| EMR_RECTANGLE | Bu kayıt bir dikdörtgen tanımlar. Dikdörtgen, mevcut <br/>            kalem kullanılarak kenarlığı çizilir ve mevcut fırça kullanılarak doldurulur. |
| EMR_RESIZEPALETTE | Bu kayıt, mantıksal bir paletin boyutunu artırır veya azaltır. |
| EMR_RESTOREDC | Bu kayıt, oynatma cihaz bağlamını belirtilen kaydedilmiş duruma geri yükler. <br/>            Oynatma cihaz bağlamı, daha önceki EMR_SAVEDC (bölüm 2.3.11) kayıtları tarafından oluşturulan kaydedilmiş cihaz bağlamları yığınından durum bilgisi çıkarılarak geri yüklenir. |
| EMR_ROUNDRECT | Bu kayıt, yuvarlatılmış köşelere sahip bir dikdörtgen tanımlar. Dikdörtgen, mevcut kalem kullanılarak kenarlığı çizilir <br/>            ve mevcut fırça kullanılarak doldurulur. |
| EMR_SAVEDDC | Bu kayıt, seçili nesneleri ve grafik modlarını tanımlayan verileri kopyalayarak oynatma cihaz bağlamının mevcut durumunu kaydeder <br/>            — bitmap, fırça, palet, <br/>            yazı tipi, kalem, bölge, çizim modu ve eşleme modu dahil— ve bunları kaydedilmiş cihaz bağlamları yığınına ekler. |
| EMR_SCALEVIEWPORTEXTEX | Bu kayıt, belirtilen çarpanlar ve bölücüler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için görüntü alanını yeniden tanımlar. |
| EMR_SCALEWINDOWEXTEX | Bu kayıt, belirtilen çarpanlar ve bölücüler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için pencereyi yeniden tanımlar. |
| EMR_SELECTCLIPPATH | Bu kayıt, mevcut yolu oynatma cihaz bağlamı için bir kırpma bölgesi olarak tanımlar <br/>            ve yeni bölgeyi belirtilen mod kullanarak mevcut herhangi bir kırpma bölgesiyle birleştirir. |
| EMR_SELECTOBJECT | Bu kayıt, bir nesneyi oynatma cihaz bağlamına ekler ve onu EMF Nesne Tablosundaki (bölüm 3.1.1.1) indeksine göre tanımlar. |
| EMR_SELECTPALETTE | Bu kayıt, bir LogPalette (bölüm 2.2.17) nesnesini oynatma cihaz bağlamına ekler ve onu EMF Nesne Tablosundaki indeksine göre tanımlar. |
| EMR_SETARCDIRECTION | Bu kayıt, yay ve dikdörtgen<br/>             işlemleri için kullanılacak çizim yönünü tanımlar. |
| EMR_SETBKCOLOR | Bu kayıt, arka plan rengini tanımlar. |
| EMR_SETBKMODE | Bu kayıt, oynatma aygıt bağlamının arka plan karıştırma modunu tanımlar. Arka plan karıştırma<br/>             modu, metin, taralı fırçalar ve katı çizgi olmayan kalem stilleriyle kullanılır. |
| EMR_SETBRUSHORGEX | Bu kayıt, geçerli fırçanın başlangıç noktasını tanımlar. |
| EMR_SETCOLORADJUSTMENT | Bu kayıt, belirtilen değerleri kullanarak oynatma aygıt bağlamı için renk ayarlama değerlerini tanımlar. |
| EMR_SETCOLORSPACE | Bu kayıt, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar. |
| EMR_SETDIBITSTODEVICE | Bu kayıt, bir kaynak<br/>             bitmap'in belirtilen tarama satırlarından bir hedef dikdörtgene piksel blok aktarımını belirtir. |
| EMR_SETICMMODE | Bu kayıt, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir. |
| EMR_SETICMPROFILEA | Bu kayıt, ASCII karakterlerinden oluşan bir ada sahip bir dosyada,<br/>             grafik çıktısı için bir renk profili belirtir. |
| EMR_SETICMPROFILEW | Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir dosyada,<br/>             grafik çıktısı için bir renk profili belirtir. |
| EMR_SETLAYOUT | Bu kayıt, metin ve grafiklerin çizildiği sıralamayı belirtir. |
| EMR_SETLINKEDUFIS | Bu kayıt, karakter araması sırasında kullanılacak bağlı yazı tiplerinin UniversalFontIds değerlerini ayarlar. |
| EMR_SETMAPMODE | Bu kayıt, oynatma aygıt bağlamının eşleme modunu tanımlar. Eşleme modu<br/>             sayfa alanı birimlerini aygıt alanı birimlerine dönüştürmek için kullanılan ölçü birimini tanımlar,<br/>             ayrıca aygıtın x ekseni ve y ekseninin yönünü de tanımlar. |
| EMR_SETMAPPERFLAGS | Bu kayıt, mantıksal yazı tiplerini fiziksel <br/>            yazı tipleriyle eşleştirme sürecinin parametrelerini, yazı tipi eşleyicisi tarafından gerçekleştirilen, belirtir. |
| EMR_SETMETARGN | Bu kayıt, oynatma aygıt bağlamı için geçerli kırpma bölgesini <br/>            mevcut meta bölgesiyle kesiştirir ve birleşik bölgeyi yeni meta bölge olarak kaydeder. Kırpma bölgesi sıfırlanarak boş bir bölgeye ayarlanır. |
| EMR_SETMITERLIMIT | Bu kayıt, oynatma <br/>            cihaz bağlamı için mitre birleşimlerinin uzunluk sınırını tanımlar. |
| EMR_SETPALETTEENTRIES | Bu kayıt, bir LogPalette nesnesinde <br/>            giriş aralığındaki RGB (kırmızı-yeşil-mavi) renk değerlerini tanımlar. |
| EMR_SETPIXELV | Bu kayıt, belirtilen mantıksal koordinatlarda pikselin rengini tanımlar. |
| EMR_SETPOLYFILLMODE | Bu kayıt, çokgen doldurma modunu tanımlar. |
| EMR_SETROP2 | Bu kayıt, ikili raster işlem modunu tanımlar. |
| EMR_SETSTRETCHBLTMODE | Bu kayıt, bitmap germe modunu tanımlar. |
| EMR_SETTEXTALIGN | Bu kayıt, metin hizalamasını tanımlar. |
| EMR_SETTEXTCOLOR | Bu kayıt, geçerli metin rengini tanımlar. |
| EMR_SETTEXTJUSTIFICATION | Bu kayıt, hizalama için<br/>             amaçlar için karakter aralarına eklenecek ekstra boşluk miktarını belirtir. |
| EMR_SETVIEWPORTEXTEX | Bu kayıt, görüntüleme alanı (viewport) kapsamını tanımlar. |
| EMR_SETVIEWPORTORGEX | Bu kayıt, görüntüleme alanı (viewport) başlangıç noktasını tanımlar. |
| EMR_SETWINDOWEXTEX | Bu kayıt, pencere kapsamını tanımlar. |
| EMR_SETWINDOWORGEX | Bu kayıt pencere kökenini tanımlar. |
| EMR_SETWORLDTRANSFORM | Bu kayıt, dünya uzayı ile <br/>            sayfa uzayı arasında iki boyutlu lineer bir dönüşümü tanımlar (daha fazla bilgi için, [MSDN-WRLDPGSPC]) oynatma cihaz bağlamı için. <br/>            Bu dönüşüm, grafik çıktısını ölçeklendirmek, döndürmek, kaydırmak veya çevirmek için kullanılabilir. |
| EMR_SMALLTEXTOUT | Bu kayıt bir dize üretir. |
| EMR_STRETCHBLT | Bu kayıt, bir kaynak bitmap'ten bir hedef<br/>             dikdörtgene piksel blok transferini, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen raster<br/>             işlemi doğrultusunda, gerekirse çıktıyı hedefin boyutlarına sığacak şekilde genişleterek veya sıkıştırarak belirtir. |
| EMR_STRETCHDIBITS | Bu kayıt, bir kaynak bitmap'ten bir hedef <br/>            dikdörtgene piksel blok transferini, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen raster işlemine göre, <br/>            gerekirse çıktıyı hedefin boyutlarına sığacak şekilde genişleterek veya sıkıştırarak belirtir. |
| EMR_STROKEANDFILLPATH | Bu kayıt, bir yoldaki açık tüm şekilleri kapatır, yolu mevcut kalemle <br/>            çizerek konturunu oluşturur ve içini mevcut fırça ile doldurur. |
| EMR_STROKEPATH | Bu kayıt, belirtilen yolu mevcut kalemi kullanarak çizer. |
| EMR_TRANSPARENTBLT | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene piksel blok transferini, <br/>             belirtilen rengi şeffaf olarak işleyerek, gerekirse çıktıyı hedefin boyutlarına sığacak şekilde genişleterek veya sıkıştırarak belirtir. |
| EMR_WIDENPATH | Bu kayıt, mevcut yolu, yol <br/>            oynatma cihaz bağlamına şu anda seçili kalemle çizilse boyanacak alan olarak yeniden tanımlar. |
