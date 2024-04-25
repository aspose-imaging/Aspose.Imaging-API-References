---
title: EmfRecordType
second_title: Aspose.Imaging for .NET API Referansı
description: RecordType numaralandırması EMF kayıtlarını benzersiz şekilde tanımlayan değerleri tanımlar. Bu değerler her kaydın Tür alanında sağlanır.
type: docs
weight: 2820
url: /tr/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

RecordType numaralandırması, EMF kayıtlarını benzersiz şekilde tanımlayan değerleri tanımlar. Bu değerler, her kaydın Tür alanında sağlanır.

```csharp
public enum EmfRecordType
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| EMR_HEADER | `1` | Bu kayıt, meta dosyasının başlangıcını tanımlar ve özelliklerini belirtir; içeriği, gömülü görüntünün boyutları dahil ; meta dosyasındaki kayıt sayısı; ve gömülü görüntünün oluşturulduğu aygıtın çözünürlüğü. Bu değerler, meta dosyasının aygıttan bağımsız olmasını mümkün kılar. |
| EMR_POLYBEZIER | `2` | Bu kayıt, bir veya daha fazla Bezier eğrisini tanımlar. Kübik Bezier eğrileri, belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır ve geçerli kalemle işaretlenir. |
| EMR_POLYGON | `3` | Bu kayıt, düz çizgilerle bağlanan iki veya daha fazla köşeden oluşan bir çokgen tanımlar. Çokgen, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça ve çokgen doldurma modu kullanılarak doldurulur. Çokgen, son tepe noktasından ilk noktaya bir çizgi çizilerek otomatik olarak kapatılır. |
| EMR_POLYLINE | `4` | Bu kayıt, belirtilen dizisindeki noktaları bağlayarak bir dizi çizgi parçasını tanımlar. |
| EMR_POLYBEZIERTO | `5` | Bu kayıt, geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi tanımlar. |
| EMR_POLYLINETO | `6` | Bu kayıt, geçerli konuma dayalı olarak bir veya daha fazla düz çizgi tanımlar. Geçerli kalem kullanılarak, nokta alanı tarafından belirtilen ilk noktaya geçerli konumdan bir çizgi çizilir. Her ek satır için, bir önceki satırın bitiş noktasından noktalarla belirtilen sonraki noktaya kadar çizim yapılır. |
| EMR_POLYPOLYLINE | `7` | Bu kayıt, birden çok bağlantılı hat segmenti serisini tanımlar. Çizgi parçaları, geçerli kalem kullanılarak çizilir. Segmentlerin oluşturduğu rakamlar doldurulmamıştır. T mevcut konum bu kayıt tarafından kullanılmaz veya güncellenmez. |
| EMR_POLYPOLYGON | `8` | Bu kayıt, bir dizi kapalı çokgen tanımlar. Her çokgen, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça ve çokgen doldurma modu kullanılarak doldurulur. Bu kayıt tarafından tanımlanan çokgenler çakışabilir. |
| EMR_SETWINDOWEXTEX | `9` | Bu kayıt, pencere kapsamını tanımlar. |
| EMR_SETWINDOWORGEX | `10` | Bu kayıt, pencerenin kökenini tanımlar. |
| EMR_SETVIEWPORTEXTEX | `11` | Bu kayıt, görünüm alanı kapsamını tanımlar. |
| EMR_SETVIEWPORTORGEX | `12` | Bu kayıt, görünüm alanı kaynağını tanımlar. |
| EMR_SETBRUSHORGEX | `13` | Bu kayıt, geçerli fırçanın kaynağını tanımlar. |
| EMR_EOF | `14` | Bu kayıt, meta dosyasının sonunu gösterir. |
| EMR_SETPIXELV | `15` | Bu kayıt, belirtilen mantıksal koordinatlarda pikselin rengini tanımlar. |
| EMR_SETMAPPERFLAGS | `16` | Bu kayıt, mantıksal yazı tiplerini, yazı tipi eşleyicisi tarafından gerçekleştirilen fiziksel yazı tipleriyle eşleştirme sürecinin parametrelerini belirtir. |
| EMR_SETMAPMODE | `17` | Bu kayıt, oynatma cihazı bağlamının eşleme modunu tanımlar. Eşleme modu , sayfa alanı birimlerini aygıt alanı birimlerine dönüştürmek için kullanılan ölçü birimini, tanımlar ve ayrıca aygıtın x ekseni ve y ekseninin yönünü tanımlar. |
| EMR_SETBKMODE | `18` | Bu kayıt, oynatma cihazı bağlamının arka plan karıştırma modunu tanımlar. Arka plan mix modu, düz çizgiler olmayan metin, taralı fırçalar ve kalem stilleriyle kullanılır. |
| EMR_SETPOLYFILLMODE | `19` | Bu kayıt, çokgen doldurma modunu tanımlar. |
| EMR_SETROP2 | `20` | Bu kayıt, ikili tarama çalışma modunu tanımlar. |
| EMR_SETSTRETCHBLTMODE | `21` | Bu kayıt, bitmap uzatma modunu tanımlar. |
| EMR_SETTEXTALIGN | `22` | Bu kayıt, metin hizalamasını tanımlar. |
| EMR_SETCOLORADJUSTMENT | `23` | Bu kayıt, belirtilen değerleri kullanarak oynatma cihazı bağlamı için renk ayarlama değerlerini tanımlar. |
| EMR_SETTEXTCOLOR | `24` | Bu kayıt, geçerli metin rengini tanımlar. |
| EMR_SETBKCOLOR | `25` | Bu kayıt, arka plan rengini tanımlar. |
| EMR_OFFSETCLIPRGN | `26` | Bu kayıt, oynatma aygıtı bağlamının kırpma bölgesini belirtilen ofsetlerle yeniden tanımlar. |
| EMR_MOVETOEX | `27` | Bu kayıt, mantıksal birimlerde yeni geçerli konumun koordinatlarını tanımlar. |
| EMR_SETMETARGN | `28` | Bu kayıt, oynatma cihazı bağlamı için geçerli kırpma bölgesini geçerli meta bölgesiyle kesişir ve birleştirilmiş bölgeyi yeni meta bölge olarak kaydeder. Kırpma bölgesi boş bir bölgeye sıfırlanır. |
| EMR_EXCLUDECLIPRECT | `29` | Bu kayıt, mevcut kırpma bölgesi eksi belirtilen dikdörtgenden oluşan yeni bir kırpma bölgesini tanımlar. |
| EMR_INTERSECTCLIPRECT | `30` | Bu kayıt, geçerli kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranlarını kullanarak oynatma aygıtı bağlamı için görünüm penceresini yeniden tanımlar. |
| EMR_SCALEWINDOWEXTEX | `32` | Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranlarını kullanarak oynatma aygıtı bağlamı için pencereyi yeniden tanımlar. |
| EMR_SAVEDC | `33` | Bu kayıt, bitmap, fırça, palet, yazı tipi, kalem, bölge, çizim modu ve eşleme modu dahil olmak üzere seçili nesneleri ve grafik modlarını açıklayan verileri kayıtlı bir yığına kopyalayarak oynatma cihazı bağlamının mevcut durumunu kaydeder. cihaz bağlamları. |
| EMR_RESTOREDC | `34` | Bu kayıt, oynatma aygıtı bağlamını belirtilen kayıtlı duruma geri yükler. Kayıttan yürütme aygıtı bağlamı, önceki EMR_SAVEDC (bölüm 2.3.11) kayıtları tarafından oluşturulan bir kayıtlı aygıt bağlamı yığınından durum bilgisi çıkarılarak geri yüklenir. |
| EMR_SETWORLDTRANSFORM | `35` | Bu kayıt, kayıttan yürütme aygıtı bağlamı için dünya alanı ile sayfa alanı (daha fazla bilgi için, bkz. [MSDN-WRLDPGSPC]) arasında iki boyutlu bir doğrusal dönüşüm tanımlar. Bu dönüştürme, grafik çıktısını ölçeklemek, döndürmek, kırpmak veya çevirmek için kullanılabilir. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Bu kayıt, belirtilen modu kullanarak kayıttan yürütme aygıtı bağlamı için dünya dönüşümünü yeniden tanımlar. |
| EMR_SELECTOBJECT | `37` | Bu kayıt, oynatma cihazı bağlamına bir nesne ekler ve onu EMF Nesne Tablosunda (bölüm 3.1.1.1) dizini ile tanımlar. |
| EMR_CREATEPEN | `38` | Bu kayıt, belirtilen stile, genişliğe ve renge sahip bir mantıksal kalemi tanımlar. Kalem daha sonra oynatma cihazı bağlamında seçilebilir ve çizgiler ve eğriler çizmek için kullanılabilir. |
| EMR_CREATEBRUSHINDIRECT | `39` | Bu kayıt, grafik işlemlerinde şekil doldurma için mantıksal bir fırça tanımlar. |
| EMR_DELETEOBJECT | `40` | Bu kayıt, EMF Nesne Tablosundaki dizinini temizleyerek bir grafik nesnesini siler. Silinen nesne oynatma aygıtı bağlamında seçilirse, bu bağlam özelliği için varsayılan nesne GERİ YÜKLENMELİDİR. |
| EMR_ANGLEARC | `41` | Bu kayıt, bir yayın çizgi segmentini tanımlar. Çizgi parçası, geçerli konumundan yayın başlangıcına kadar çizilir. Yay, verilen yarıçap ve merkeze sahip bir dairenin çevresi boyunca çizilir. Yayın uzunluğu, verilen başlangıç ve süpürme açıları tarafından tanımlanır. |
| EMR_ELLIPSE | `42` | Bu kayıt bir elipsi tanımlar. Elipsin merkezi, belirtilen sınırlayıcı dikdörtgenin merkezidir. Elips, geçerli kalem kullanılarak ana hatları çizilir ve , geçerli fırça kullanılarak doldurulur. |
| EMR_RECTANGLE | `43` | Bu kayıt bir dikdörtgen tanımlar. Dikdörtgen, geçerli kalemi kullanılarak ana hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| EMR_ROUNDRECT | `44` | Bu kayıt, köşeleri yuvarlatılmış bir dikdörtgeni tanımlar. Dikdörtgen, geçerli kalem kullanılarak dış hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| EMR_ARC | `45` | Bu kayıt, eliptik bir yay tanımlar. |
| EMR_CHORD | `46` | Bu kayıt bir kirişi tanımlar (bir elips ve bir çizgi parçasının kesişimiyle sınırlanan bölge, sekant olarak adlandırılır). Akor, geçerli kalemi kullanılarak ana hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| EMR_PIE | `47` | Bu kayıt, bir elips ve iki yarıçapın kesişimiyle sınırlanan pasta şeklinde bir kama tanımlar. Pasta, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça kullanılarak doldurulur. |
| EMR_SELECTPALETTE | `48` | Bu kayıt, kayıttan yürütme aygıtı bağlamına bir LogPalette (bölüm 2.2.17) nesnesi ekler ve bunu EMF Nesne Tablosundaki dizini ile tanımlar. |
| EMR_CREATEPALETTE | `49` | Bu kayıt bir LogPalette nesnesini tanımlar. |
| EMR_SETPALETTEENTRIES | `50` | Bu kayıt, bir LogPalette nesnesindeki giriş aralığındaki RGB (kırmızı-yeşil-mavi) renk değerlerini tanımlar. |
| EMR_RESIZEPALETTE | `51` | Bu kayıt, mantıksal paletin boyutunu artırır veya azaltır. |
| EMR_REALIZEPALETTE | `52` | Bu kayıt, geçerli mantıksal paletteki girişleri sistem paletine eşler. |
| EMR_EXTFLOODFILL | `53` | Bu kayıt, geçerli fırça ile ekran yüzeyinin bir alanını doldurur. |
| EMR_LINETO | `54` | Bu kayıt, geçerli konumdan belirtilen noktaya kadar, ancak içermeyen bir çizgi tanımlar. Geçerli konumu belirtilen noktaya sıfırlar. |
| EMR_ARCTO | `55` | Bu kayıt bir eliptik yayı tanımlar. Geçerli konumu, yayın bitiş noktasına sıfırlar. |
| EMR_POLYDRAW | `56` | Bu kayıt, bir dizi çizgi parçası ve Bezier eğrisi tanımlar. |
| EMR_SETARCDIRECTION | `57` | Bu kayıt, yay ve dikdörtgen işlemleri için kullanılacak çizim yönünü tanımlar. |
| EMR_SETMITERLIMIT | `58` | Bu kayıt, oynatma cihaz bağlamı için gönye birleştirmelerinin uzunluk sınırını tanımlar. |
| EMR_BEGINPATH | `59` | Bu kayıt, oynatma cihazı bağlamında bir yol parantezini açar. |
| EMR_ENDPATH | `60` | Bu kayıt bir yol parantezini kapatır ve paranteziyle tanımlanan yolu oynatma cihazı bağlamına seçer. |
| EMR_CLOSEFIGURE | `61` | Bu kayıt, yoldaki açık bir şekli kapatır. |
| EMR_FILLPATH | `62` | Bu kayıt, geçerli yoldaki tüm açık şekilleri kapatır ve geçerli fırça ve çokgen doldurma modunu kullanarak yolun içini doldurur. |
| EMR_STROKEANDFILLPATH | `63` | Bu kayıt, bir yoldaki tüm açık şekilleri kapatır, geçerli kalemi kullanarak yolun ana hatlarını konturlar ve geçerli fırçayı kullanarak içini doldurur. |
| EMR_STROKEPATH | `64` | Bu kayıt, geçerli kalemi kullanarak belirtilen yolu işler. |
| EMR_FLATTENPATH | `65` | Bu kayıt, seçilen yoldaki herhangi bir eğriyi oynatma aygıtı bağlamına dönüştürerek her eğriyi bir satır dizisine dönüştürür. |
| EMR_WIDENPATH | `66` | Bu kayıt, geçerli yolu, oynatma aygıtı bağlamında seçili olan kalem kullanılarak yoluna kontur yapıldığında boyanacak alan olarak yeniden tanımlar. |
| EMR_SELECTCLIPPATH | `67` | Bu kayıt, yeni bölgeyi belirtilen modu kullanarak mevcut herhangi bir kırpma bölgesiyle birleştirerek, oynatma aygıtı bağlamı için bir kırpma bölgesi olarak geçerli yolu tanımlar. |
| EMR_ABORTPATH | `68` | Bu kayıt, bir yol parantezini iptal eder veya yolu kapalı bir yol parantezinden atar. |
| EMR_COMMENT | `70` | Bu kayıt, isteğe bağlı özel verileri belirtir. |
| EMR_FILLRGN | `71` | Bu kayıt, belirtilen fırçayı kullanarak belirtilen bölgeyi doldurur. |
| EMR_FRAMERGN | `72` | Bu kayıt, belirtilen fırçayı kullanarak belirtilen bölgenin çevresine bir sınır çizer. |
| EMR_INVERTRGN | `73` | Bu kayıt, belirtilen bölgedeki renkleri tersine çevirir. |
| EMR_PAINTRGN | `74` | Bu kayıt, oynatma aygıtı bağlamında içinde seçili olan fırçayı kullanarak belirtilen bölgeyi boyar. |
| EMR_EXTSELECTCLIPRGN | `75` | Bu kayıt, belirtilen bölgeyi belirtilen modu kullanarak geçerli klip bölgesiyle birleştirir. |
| EMR_BITBLT | `76` | Bu kayıt, belirli bir tarama işlemine göre, isteğe bağlı olarak bir fırça deseni ile birlikte bir kaynak bitmap'ten bir hedef dikdörtgenine piksellerin blok aktarımını belirtir. |
| EMR_STRETCHBLT | `77` | Bu kayıt, isteğe bağlı olarak, belirtilen bir raster işlemine göre bir fırça deseniyle birlikte, gerekirse hedefin boyutlarına uyacak şekilde çıktıyı gererek veya sıkıştırarak, bir kaynak bitmap'ten bir target dikdörtgenine piksellerin blok aktarımını belirtir. |
| EMR_MASKBLT | `78` | Bu kayıt, belirtilen ön plan ve arka plan raster işlemlerine göre, isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bit eşlemi uygulamasıyla birlikte bir kaynak bit eşleminden bir hedef dikdörtgenine piksellerin blok aktarımını belirtir. |
| EMR_PLGBLT | `79` | Bu kayıt, bir renk maskesi bitmap uygulamasıyla bir kaynak bitmap'ten bir hedef paralelkenarına piksellerin blok aktarımını belirtir. |
| EMR_SETDIBITSTODEVICE | `80` | Bu kayıt, source bitmap'in belirtilen tarama satırlarından bir hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| EMR_STRETCHDIBITS | `81` | Bu kayıt, piksellerin bir kaynak bitmap'ten bir hedef dikdörtgenine, isteğe bağlı olarak, belirtilen bir tarama işlemine göre bir fırça deseni ile birlikte, çıktıyı, gerekirse hedefin boyutlarına uyacak şekilde gererek veya sıkıştırarak blok aktarımını belirtir. . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Bu kayıt, belirtilen özelliklere sahip bir mantıksal yazı tipini tanımlar. yazı tipi daha sonra oynatma cihazı bağlamı için geçerli yazı tipi olarak seçilebilir. |
| EMR_EXTTEXTOUTA | `83` | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir ASCII metin dizesi çizer. Not EMR_EXTTEXTOUTA, bir EMR_EXTTEXTOUTW kaydıyla öykünülmelidir (bölüm 2.3.5.8). Bu, EmrText nesnesindeki ASCII metin dizesinin Unicode UTF16-LE kodlamasına dönüştürülmesini gerektirir. |
| EMR_EXTTEXTOUTW | `84` | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir Unicode metin dizesi çizer. |
| EMR_POLYBEZIER16 | `85` | Bu kayıt, bir veya daha fazla Bezier eğrisini tanımlar. Eğriler, geçerli kalem kullanılarak çizilir. |
| EMR_POLYGON16 | `86` | Bu kayıt, düz çizgilerle bağlanan iki veya daha fazla tepe noktasından oluşan bir çokgeni tanımlar. Çokgen, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça ve poligon doldurma modu kullanılarak doldurulur. Çokgen, son tepe noktasından ilk noktaya bir çizgi çizilerek otomatik olarak kapatılır. |
| EMR_POLYLINE16 | `87` | Bu kayıt, belirtilen dizideki noktaları birleştirerek bir dizi çizgi parçasını tanımlar. |
| EMR_POLYBEZIERTO16 | `88` | Bu kayıt, geçerli konuma dayalı olarak bir veya daha fazla Bezier eğrisi tanımlar. |
| EMR_POLYLINETO16 | `89` | Bu kayıt, geçerli konuma dayalı olarak bir veya daha fazla düz çizgi tanımlar. Geçerli kalem kullanılarak, Noktalar alanı tarafından belirtilen ilk noktaya geçerli konumdan bir çizgi çizilir. Her ek satır için, bir önceki satırın bitiş noktasından Points. ile belirtilen sonraki noktaya kadar çizim yapılır. |
| EMR_POLYPOLYLINE16 | `90` | Bu kayıt, birden çok bağlantılı hat segmenti serisini tanımlar. |
| EMR_POLYPOLYGON16 | `91` | Bu kayıt, bir dizi kapalı çokgen tanımlar. Her çokgen, geçerli kalem kullanılarak ana hatları çizilir ve geçerli fırça ve çokgen doldurma modu kullanılarak doldurulur. Bu kayıt tarafından belirtilen poligonlar çakışabilir. |
| EMR_POLYDRAW16 | `92` | Bu kayıt, bir dizi çizgi parçası ve Bezier eğrisi tanımlar. |
| EMR_CREATEMONOBRUSH | `93` | Bu kayıt, belirtilen bit eşlem desenine sahip bir mantıksal fırçayı tanımlar. Bitmap, cihazdan bağımsız bir bitmap (DIB) bölümü bitmap olabilir veya cihaza bağlı bir bitmap olabilir. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Bu kayıt, DIB tarafından belirtilen desene sahip bir mantıksal fırçayı tanımlar. |
| EMR_EXTCREATEPEN | `95` | Bu kayıt, belirtilen stile, genişliğe ve fırça özelliklerine sahip bir mantıksal kozmetik veya geometrik kalemi tanımlar. |
| EMR_POLYTEXTOUTA | `96` | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer. Not EMR_POLYTEXTOUTA, dize başına bir tane olmak üzere bir dizi EMR_EXTTEXTOUTW kaydıyla öykünülmelidir |
| EMR_POLYTEXTOUTW | `97` | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer. Not EMR_POLYTEXTOUTW, dize başına bir tane olmak üzere bir dizi EMR_EXTTEXTOUTW kaydıyla öykünülmelidir |
| EMR_SETICMMODE | `98` | Bu kayıt, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir. |
| EMR_CREATECOLORSPACE | `99` | Bu kayıt, ASCII karakterlerinden oluşan bir ada sahip bir renk profilinden mantıksal bir renk uzayı nesnesi oluşturur |
| EMR_SETCOLORSPACE | `100` | Bu kayıt, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar. |
| EMR_DELETECOLORSPACE | `101` | Bu kayıt, mantıksal bir renk uzayı nesnesini siler. Not Mantıksal bir renk uzayı nesnesini silmek için EMR_DELETECOLORSPACE yerine bir EMR_DELETEOBJECT kaydı KULLANILMALIDIR |
| EMR_GLSRECORD | `102` | Bu kayıt bir OpenGL işlevini belirtir. |
| EMR_GLSBOUNDEDRECORD | `103` | Bu kayıt, çıktı için sınırlayıcı bir dikdörtgen içeren bir OpenGL işlevini belirtir. |
| EMR_PIXELFORMAT | `104` | Bu kayıt, grafik işlemleri için kullanılacak piksel biçimini belirtir |
| EMR_DRAWESCAPE | `105` | Bu kayıt, sürücüye isteğe bağlı bilgileri iletir. Amaç, bilgisinin çizimin yapılmasıyla sonuçlanmasıdır. |
| EMR_EXTESCAPE | `106` | Bu kayıt, sürücüye isteğe bağlı bilgileri iletir. Amaç, bilgisinin çizimin yapılmasına neden olmamasıdır. |
| EMR_SMALLTEXTOUT | `108` | Bu kayıt bir dizge verir. |
| EMR_FORCEUFIMAPPING | `109` | Bu kayıt, yazı tipi eşleyicisini, tercihindeki UniversalFontId'lerine göre yazı tiplerini LogFont bilgileriyle eşleştirmeye zorlar. |
| EMR_NAMEDESCAPE | `110` | Bu kayıt, verilen adlandırılmış sürücüye rastgele bilgiler iletir. |
| EMR_COLORCORRECTPALETTE | `111` | Bu kayıt, Windows Renk Sistemi (WCS) 1.0 değerleri kullanılarak bir mantıksal palet nesnesinin girdilerinin nasıl düzeltileceğini belirtir |
| EMR_SETICMPROFILEA | `112` | Bu kayıt, grafik çıktısı için ASCII karakterlerinden oluşan bir ada sahip bir dosyada, bir renk profilini belirtir. |
| EMR_SETICMPROFILEW | `113` | Bu kayıt, grafik çıktısı için Unicode karakterlerden oluşan bir ada sahip bir dosyadaki renk profilini belirtir, |
| EMR_ALPHABLEND | `114` | Bu kayıt, belirli bir karıştırma işlemine göre, alfa saydamlık verileri dahil olmak üzere, bir kaynak bitmap'ten bir hedef dikdörtgene piksellerin blok aktarımını belirtir. |
| EMR_SETLAYOUT | `115` | Bu kayıt, metin ve grafiklerin çizilme sırasını belirtir |
| EMR_TRANSPARENTBLT | `116` | Bu kayıt, piksellerin bir kaynak bitmap'ten bir hedef dikdörtgene blok aktarımını, belirtilen bir rengi şeffaf olarak ele almayı, gerekirse çıktıyı hedefin boyutlarına uyacak şekilde germeyi veya sıkıştırmayı belirtir |
| EMR_GRADIENTFILL | `118` | Bu kayıt, dikdörtgenleri veya üçgenleri color gradyanlarıyla doldurmayı belirtir. |
| EMR_SETLINKEDUFIS | `119` | Bu kayıt, karakter araması sırasında kullanılacak bağlantılı yazı tiplerinin UniversalFontId'lerini ayarlar. |
| EMR_SETTEXTJUSTIFICATION | `120` | Bu kayıt, gerekçe amaçları için kesme karakterlerine eklenecek fazladan boşluk miktarını belirtir. |
| EMR_COLORMATCHTOTARGETW | `121` | Bu kayıt, adı Unicode karakterlerden oluşan bir dosyada belirtilen bir renk profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirtir. |
| EMR_CREATECOLORSPACEW | `122` | Bu kayıt, adı Unicode karakterlerden oluşan bir renk profilinden mantıksal bir renk uzayı nesnesi oluşturur |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
