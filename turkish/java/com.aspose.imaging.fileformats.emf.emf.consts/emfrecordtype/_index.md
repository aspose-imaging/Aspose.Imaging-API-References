---
title: "EmfRecordType"
second_title: "Aspose.Imaging for Java API Referansı"
description: "RecordType sayımı, EMF kayıtlarını benzersiz şekilde tanımlayan değerleri tanımlar."
type: docs
weight: 38
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

RecordType numaralandırması, EMF kayıtlarını benzersiz şekilde tanımlayan değerleri tanımlar. Bu değerler her kaydın Type alanında sağlanır.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Bu kayıt, metafilenin başlangıcını tanımlar ve özelliklerini belirtir; içeriği, gömülü görüntünün boyutları dahil; metafiledeki kayıt sayısı; ve gömülü görüntünün oluşturulduğu cihazın çözünürlüğü. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Bu kayıt bir veya daha fazla Bezier eğrisini tanımlar. |
| [EMR_POLYGON](#EMR-POLYGON) | Bu kayıt, düz çizgilerle bağlanan iki veya daha fazla köşeden oluşan bir çokgeni tanımlar. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Bu kayıt, belirtilen dizideki noktaları bağlayarak bir dizi çizgi segmenti tanımlar. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Bu kayıt, geçerli konuma dayalı bir veya daha fazla Bezier eğrisini tanımlar. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Bu kayıt, geçerli konuma dayalı bir veya daha fazla düz çizgiyi tanımlar. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Bu kayıt, birden çok bağlanmış çizgi segmenti serisini tanımlar. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Bu kayıt, kapalı çokgenlerden oluşan bir seriyi tanımlar. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Bu kayıt, pencere kapsamını tanımlar. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Bu kayıt, pencere kökenini tanımlar. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Bu kayıt, görüntüleme alanı kapsamını tanımlar. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Bu kayıt, görüntüleme alanı kökenini tanımlar. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Bu kayıt, geçerli fırçanın kökenini tanımlar. |
| [EMR_EOF](#EMR-EOF) | Bu kayıt, metafilenin sonunu gösterir. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Bu kayıt, belirtilen mantıksal koordinatlardaki pikselin rengini tanımlar. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Bu kayıt, font eşleyicisi tarafından gerçekleştirilen mantıksal fontların fiziksel fontlarla eşleştirilmesi sürecinin parametrelerini belirtir. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Bu kayıt, oynatma aygıt bağlamının eşleme modunu tanımlar. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Bu kayıt, oynatma aygıt bağlamının arka plan karışım modunu tanımlar. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Bu kayıt, çokgen doldurma modunu tanımlar. |
| [EMR_SETROP2](#EMR-SETROP2) | Bu kayıt, ikili raster işlem modunu tanımlar. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Bu kayıt bitmap germe modunu tanımlar. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Bu kayıt metin hizalamasını tanımlar. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Bu kayıt, belirtilen değerleri kullanarak oynatma cihaz bağlamı için renk ayarlama değerlerini tanımlar. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Bu kayıt geçerli metin rengini tanımlar. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Bu kayıt arka plan rengini tanımlar. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Bu kayıt, belirtilen kaydırmalarla oynatma cihaz bağlamının kırpma bölgesini yeniden tanımlar. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Bu kayıt, yeni geçerli konumun koordinatlarını mantıksal birimlerde tanımlar. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Bu kayıt, oynatma cihaz bağlamının geçerli kırpma bölgesi ile geçerli meta bölgeyi kesiştirir ve birleşik bölgeyi yeni meta bölge olarak kaydeder. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Bu kayıt, mevcut kırpma bölgesinden belirtilen dikdörtgen çıkarılarak oluşan yeni bir kırpma bölgesi tanımlar. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Bu kayıt, geçerli kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için görüntü alanını yeniden tanımlar. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için pencereyi yeniden tanımlar. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Bu kayıt, seçilen nesneleri ve grafik modlarını tanımlayan verileri\\u2014bitmap, fırça, palet, yazı tipi, kalem, bölge, çizim modu ve eşleme modu dahil\\u2014kopyalayarak oynatma cihaz bağlamının geçerli durumunu kaydedilmiş cihaz bağlamları yığınına kaydeder. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Bu kayıt, oynatma cihaz bağlamını belirtilen kaydedilmiş duruma geri yükler. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Bu kayıt, oynatma cihaz bağlamı için dünya uzayı ile sayfa uzayı arasında iki boyutlu lineer dönüşümü tanımlar (daha fazla bilgi için, [MSDN-WRLDPGSPC] adresine bakın). |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Bu kayıt, belirtilen modu kullanarak oynatma cihaz bağlamı için dünya dönüşümünü yeniden tanımlar. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Bu kayıt, EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki indeksiyle tanımlayarak bir nesneyi oynatma cihaz bağlamına ekler. |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Bu kayıt, belirtilen stil, genişlik ve renge sahip mantıksal bir kalemi tanımlar. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Bu kayıt, grafik işlemlerinde şekil doldurmak için mantıksal bir fırça tanımlar. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Bu kayıt, bir grafik nesnesini siler ve EMF Nesne Tablosundaki indeksini temizler. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Bu kayıt, bir yayının çizgi segmentini tanımlar. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Bu kayıt bir elips tanımlar. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Bu kayıt bir dikdörtgen tanımlar. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Bu kayıt yuvarlatılmış köşelere sahip bir dikdörtgen tanımlar. |
| [EMR_ARC](#EMR-ARC) | Bu kayıt eliptik bir yay tanımlar. |
| [EMR_CHORD](#EMR-CHORD) | Bu kayıt, bir kord (elips ile bir doğru parçasının kesişimiyle sınırlanan, sekant olarak adlandırılan bir bölge) tanımlar. |
| [EMR_PIE](#EMR-PIE) | Bu kayıt, elips ile iki radyalin kesişimiyle sınırlanan bir pasta şekilli dilimi tanımlar. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Bu kayıt, bir LogPalette (bölüm 2.2.17) nesnesini oynatma cihaz bağlamına ekler ve onu EMF Nesne Tablosundaki indeksiyle tanımlar. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Bu kayıt, bir LogPalette nesnesini tanımlar. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Bu kayıt, bir LogPalette nesnesindeki giriş aralığında RGB (kırmızı-yeşil-mavi) renk değerlerini tanımlar. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Bu kayıt, mantıksal bir paletin boyutunu artırır veya azaltır. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Bu kayıt, geçerli mantıksal paletten sistem paletine girişleri eşler. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Bu kayıt, görüntü yüzeyinin bir alanını geçerli fırça ile doldurur. |
| [EMR_LINETO](#EMR-LINETO) | Bu kayıt, geçerli konumdan belirtilen noktaya kadar (nokta dahil olmadan) bir çizgi tanımlar. |
| [EMR_ARCTO](#EMR-ARCTO) | Bu kayıt eliptik bir yay tanımlar. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Bu kayıt, yay ve dikdörtgen işlemleri için kullanılacak çizim yönünü tanımlar. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Bu kayıt, oynatma cihaz bağlamı için mitre birleşimlerinin uzunluk sınırını tanımlar. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Bu kayıt, oynatma cihaz bağlamında bir yol parantezi açar. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Bu kayıt bir yol parantezini kapatır ve parantezle tanımlanan yolu oynatma cihaz bağlamına seçer. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Bu kayıt, bir yoldaki açık şekli kapatır. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Bu kayıt, geçerli yoldaki açık tüm şekilleri kapatır ve yolun içini geçerli fırça ve çokgen doldurma modu kullanarak doldurur. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Bu kayıt, bir yoldaki açık tüm şekilleri kapatır, yolun dış hattını geçerli kalemle çizer ve içini geçerli fırça ile doldurur. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Bu kayıt, belirtilen yolu geçerli kalemle işler. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Bu kayıt, yol içinde seçili olan herhangi bir eğriyi oynatma cihaz bağlamına dönüştürür ve her eğriyi bir dizi çizgiye çevirir. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Bu kayıt, geçerli yolu, oynatma cihaz bağlamına şu anda seçili kalemle çizildiğinde boyanacak alan olarak yeniden tanımlar. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Bu kayıt, geçerli yolu oynatma cihaz bağlamı için bir kırpma bölgesi olarak tanımlar ve yeni bölgeyi belirtilen modla mevcut kırpma bölgesiyle birleştirir. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Bu kayıt, bir yol parantezini iptal eder veya kapalı bir yol parantezinden yolu atar. |
| [EMR_COMMENT](#EMR-COMMENT) | Bu kayıt, keyfi özel verileri belirtir. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Bu kayıt, belirtilen bölgeyi belirtilen fırça ile doldurur. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Bu kayıt, belirtilen bölgenin etrafına belirtilen fırça ile bir kenarlık çizer. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Bu kayıt, belirtilen bölgedeki renkleri tersine çevirir. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Bu kayıt, oynatma cihaz bağlamına şu anda seçili fırça ile belirtilen bölgeyi boyar. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Bu kayıt, belirtilen bölgeyi geçerli kırpma bölgesiyle belirtilen mod kullanarak birleştirir. |
| [EMR_BITBLT](#EMR-BITBLT) | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını belirtir. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını, gerekirse çıktıyı hedefin boyutlarına sığdırmak için genişleterek veya sıkıştırarak belirtir. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bitmap'i uygulamasıyla birlikte, belirtilen ön plan ve arka plan raster işlemlerine göre piksel blok aktarımını belirtir. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Bu kayıt, bir kaynak bitmap'ten bir hedef paralelograma, bir renk maskesi bitmap'i uygulamasıyla birlikte piksel blok aktarımını belirtir. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Bu kayıt, bir kaynak bitmap'in belirtilen tarama satırlarından bir hedef dikdörtgene piksel blok aktarımını belirtir. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını, gerekirse çıktıyı hedefin boyutlarına sığdırmak için genişleterek veya sıkıştırarak belirtir. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Bu kayıt, belirtilen özelliklere sahip mantıksal bir yazı tipini tanımlar. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir ASCII metin dizesi çizer. Not EMR\\_EXTTEXTOUTA, bir EMR\\_EXTTEXTOUTW kaydıyla (bölüm 2.3.5.8) taklit edilmelidir. |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir Unicode metin dizesi çizer. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Bu kayıt bir veya daha fazla Bezier eğrisini tanımlar. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Bu kayıt, düz çizgilerle bağlanan iki veya daha fazla köşeden oluşan bir çokgeni tanımlar. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Bu kayıt, belirtilen dizideki noktaları bağlayarak bir dizi çizgi segmenti tanımlar. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Bu kayıt, geçerli konuma dayalı bir veya daha fazla Bezier eğrisi tanımlar. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Bu kayıt, geçerli konuma dayalı bir veya daha fazla düz çizgiyi tanımlar. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Bu kayıt, birden çok bağlanmış çizgi segmenti serisini tanımlar. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Bu kayıt, kapalı çokgenlerden oluşan bir seriyi tanımlar. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Bu kayıt, belirtilen bitmap desenine sahip mantıksal bir fırça tanımlar. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Bu kayıt, DIB tarafından belirtilen desene sahip mantıksal bir fırça tanımlar. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Bu kayıt, belirtilen stil, genişlik ve fırça özelliklerine sahip mantıksal bir kozmetik veya geometrik kalemi tanımlar. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Bu kayıt, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Bu kayıt, ASCII karakterlerden oluşan bir ad taşıyan bir renk profili üzerinden mantıksal bir renk uzayı nesnesi oluşturur. |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Bu kayıt, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Bu kayıt, mantıksal bir renk uzayı nesnesini siler. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Bu kayıt, bir OpenGL işlevini belirtir. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Bu kayıt, çıktı için sınırlayıcı bir dikdörtgen içeren bir OpenGL işlevini belirtir. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Bu kayıt, grafik işlemleri için kullanılacak piksel biçimini belirtir. |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Bu kayıt, sürücüye keyfi bilgi gönderir. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Bu kayıt, sürücüye keyfi bilgi gönderir. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Bu kayıt bir dize çıktılar. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Bu kayıt, yazı tipi eşleyicisinin, LogFont bilgilerine tercih olarak UniversalFontId'lerine göre yazı tiplerini eşlemesini zorlar. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Bu kayıt, verilen adlandırılmış sürücüye keyfi bilgi gönderir. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Bu kayıt, Windows Color System (WCS) 1.0 değerlerini kullanarak mantıksal palet nesnesinin girişlerini nasıl düzelteceğini belirtir. |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Bu kayıt, grafik çıktısı için ASCII karakterlerinden oluşan bir ada sahip bir dosyada renk profilini belirtir. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Bu kayıt, grafik çıktısı için Unicode karakterlerinden oluşan bir ada sahip bir dosyada renk profilini belirtir. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Bu kayıt, belirtilen bir karıştırma işlemi doğrultusunda, alfa şeffaflık verilerini içerecek şekilde, kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını belirtir. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Bu kayıt, metin ve grafiklerin çizildiği sıralamayı belirtir. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Bu kayıt, belirtilen bir rengi şeffaf olarak kabul ederek, gerekirse çıktıyı hedefin boyutlarına sığdırmak için gererek veya sıkıştırarak, kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını belirtir. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Bu kayıt, dikdörtgenleri veya üçgenleri renk geçişleriyle doldurulmasını belirtir. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Bu kayıt, karakter araması sırasında kullanılacak bağlı yazı tiplerinin UniversalFontIds değerlerini ayarlar. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Bu kayıt, hizalama amacıyla bölme karakterlerine eklenecek ekstra boşluk miktarını belirtir. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir dosyada belirtilen renk profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirtir. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir renk profilinden mantıksal bir renk uzayı nesnesi oluşturur. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Bu kayıt, metafilenin başlangıcını tanımlar ve özelliklerini belirtir; içeriği, gömülü görüntünün boyutları dahil; metafildeki kayıt sayısı; ve gömülü görüntünün oluşturulduğu cihazın çözünürlüğü. Bu değerler, metafilenin cihazdan bağımsız olmasını sağlar.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Bu kayıt bir veya daha fazla Bezier eğrisini tanımlar. Kübik Bezier eğrileri, belirtilen uç noktalar ve kontrol noktaları kullanılarak tanımlanır ve mevcut kalemle çizilir.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Bu kayıt, iki veya daha fazla köşeyi düz çizgilerle bağlayan bir çokgeni tanımlar. Çokgen, mevcut kalemle kontur çizilerek ve mevcut fırça ile çokgen doldurma modu kullanılarak doldurulur. Çokgen, son köşeden ilk köşeye bir çizgi çizilerek otomatik olarak kapatılır.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Bu kayıt, belirtilen dizideki noktaları bağlayarak bir dizi çizgi segmenti tanımlar.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Bu kayıt, geçerli konuma dayalı bir veya daha fazla Bezier eğrisini tanımlar.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Bu kayıt, mevcut konuma dayanarak bir veya daha fazla düz çizgi tanımlar. Bir çizgi, mevcut kalem kullanılarak mevcut konumdan points alanı tarafından belirtilen ilk noktaya çizilir. Her ek çizgi için, önceki çizginin bitiş noktasından points tarafından belirtilen bir sonraki noktaya çizim yapılır.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Bu kayıt, birden fazla bağlantılı çizgi segmenti serisini tanımlar. Çizgi segmentleri mevcut kalemle çizilir. Segmentlerle oluşan şekiller doldurulmaz. Mevcut konum bu kayıt tarafından ne kullanılır ne de güncellenir.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Bu kayıt, kapalı çokgenlerden oluşan bir seri tanımlar. Her çokgen, mevcut kalemle kontur çizilerek ve mevcut fırça ile çokgen doldurma modu kullanılarak doldurulur. Bu kayıt tarafından tanımlanan çokgenler üst üste gelebilir.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Bu kayıt, pencere kapsamını tanımlar.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Bu kayıt, pencere kökenini tanımlar.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Bu kayıt, görüntüleme alanı kapsamını tanımlar.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Bu kayıt, görüntüleme alanı kökenini tanımlar.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Bu kayıt, geçerli fırçanın kökenini tanımlar.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Bu kayıt, metafilenin sonunu gösterir.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Bu kayıt, belirtilen mantıksal koordinatlardaki pikselin rengini tanımlar.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Bu kayıt, font eşleyicisi tarafından gerçekleştirilen mantıksal fontların fiziksel fontlarla eşleştirilmesi sürecinin parametrelerini belirtir.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Bu kayıt, oynatma cihaz bağlamının eşleme modunu tanımlar. Eşleme modu, sayfa alanı birimlerini cihaz alanı birimlerine dönüştürmek için kullanılan ölçü birimini ve ayrıca cihazın x ekseni ve y ekseninin yönünü tanımlar.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Bu kayıt, oynatma cihaz bağlamının arka plan karıştırma modunu tanımlar. Arka plan karıştırma modu, metin, taralı fırçalar ve katı olmayan kalem stilleriyle kullanılır.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Bu kayıt, çokgen doldurma modunu tanımlar.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Bu kayıt, ikili raster işlem modunu tanımlar.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Bu kayıt bitmap germe modunu tanımlar.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Bu kayıt metin hizalamasını tanımlar.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Bu kayıt, belirtilen değerleri kullanarak oynatma cihaz bağlamı için renk ayarlama değerlerini tanımlar.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Bu kayıt geçerli metin rengini tanımlar.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Bu kayıt arka plan rengini tanımlar.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Bu kayıt, belirtilen kaydırmalarla oynatma cihaz bağlamının kırpma bölgesini yeniden tanımlar.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Bu kayıt, yeni geçerli konumun koordinatlarını mantıksal birimlerde tanımlar.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Bu kayıt, oynatma cihaz bağlamının mevcut kırpma bölgesiyle mevcut meta bölgeyi kesiştirir ve birleşik bölgeyi yeni meta bölge olarak kaydeder. Kırpma bölgesi null bir bölgeye sıfırlanır.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Bu kayıt, mevcut kırpma bölgesinden belirtilen dikdörtgen çıkarılarak oluşan yeni bir kırpma bölgesi tanımlar.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Bu kayıt, geçerli kırpma bölgesi ile belirtilen dikdörtgenin kesişiminden yeni bir kırpma bölgesi tanımlar.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için görüntü alanını yeniden tanımlar.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Bu kayıt, belirtilen çarpanlar ve bölenler tarafından oluşturulan oranları kullanarak oynatma cihaz bağlamı için pencereyi yeniden tanımlar.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Bu kayıt, seçilen nesneleri ve grafik modlarını tanımlayan verileri\\u2014bitmap, fırça, palet, yazı tipi, kalem, bölge, çizim modu ve eşleme modu dahil\\u2014kopyalayarak oynatma cihaz bağlamının geçerli durumunu kaydedilmiş cihaz bağlamları yığınına kaydeder.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Bu kayıt, oynatma cihaz bağlamını belirtilen kaydedilmiş duruma geri yükler. Oynatma cihaz bağlamı, önceki EMR\\_SAVEDC (bölüm 2.3.11) kayıtları tarafından oluşturulan kaydedilmiş cihaz bağlamları yığınından durum bilgisi çıkarılarak geri yüklenir.

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Bu kayıt, oynatma cihaz bağlamı için dünya alanı ile sayfa alanı arasında iki boyutlu lineer bir dönüşümü tanımlar (daha fazla bilgi için [MSDN-WRLDPGSPC] adresine bakın). Bu dönüşüm, grafik çıktısını ölçeklendirmek, döndürmek, kaydırmak veya çevirmek için kullanılabilir.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Bu kayıt, belirtilen modu kullanarak oynatma cihaz bağlamı için dünya dönüşümünü yeniden tanımlar.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Bu kayıt, EMF Nesne Tablosu (bölüm 3.1.1.1) içindeki indeksiyle tanımlayarak bir nesneyi oynatma cihaz bağlamına ekler.

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Bu kayıt, belirtilen stil, genişlik ve renge sahip mantıksal bir kalemi tanımlar. Kalem daha sonra oynatma cihaz bağlamına seçilebilir ve çizgi ve eğri çizmek için kullanılabilir.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Bu kayıt, grafik işlemlerinde şekil doldurmak için mantıksal bir fırça tanımlar.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Bu kayıt, bir grafik nesnesini siler ve EMF Nesne Tablosundaki indeksini temizler. Silinen nesne oynatma cihaz bağlamında seçiliyse, o bağlam özelliği için varsayılan nesne GERI YÜKLENMELİDİR.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Bu kayıt, bir yay için bir çizgi segmenti tanımlar. Çizgi segmenti, mevcut konumdan yay başlangıcına çizilir. Yay, verilen yarıçap ve merkezle bir dairenin çevresi boyunca çizilir. Yayın uzunluğu, verilen başlangıç ve süpürme açılarıyla tanımlanır.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Bu kayıt bir elips tanımlar. Elipsin merkezi, belirtilen sınırlayıcı dikdörtgenin merkezidir. Elips, mevcut kalemi kullanarak konturlanır ve mevcut fırça kullanılarak doldurulur.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Bu kayıt bir dikdörtgen tanımlar. Dikdörtgen, mevcut kalemi kullanarak konturlanır ve mevcut fırça kullanılarak doldurulur.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Bu kayıt yuvarlatılmış köşelere sahip bir dikdörtgen tanımlar. Dikdörtgen, mevcut kalemi kullanarak konturlanır ve mevcut fırça kullanılarak doldurulur.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Bu kayıt eliptik bir yay tanımlar.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Bu kayıt bir kord (elips ile bir doğru parçasının kesişimiyle sınırlanan, sekant olarak adlandırılan bir bölge) tanımlar. Kord, mevcut kalemi kullanarak konturlanır ve mevcut fırça kullanılarak doldurulur.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Bu kayıt, bir elips ile iki radyalin kesişimiyle sınırlanan dilim şeklinde bir dilim tanımlar. Dilim, mevcut kalemi kullanarak konturlanır ve mevcut fırça kullanılarak doldurulur.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Bu kayıt, bir LogPalette (bölüm 2.2.17) nesnesini oynatma cihaz bağlamına ekler ve onu EMF Nesne Tablosundaki indeksiyle tanımlar.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Bu kayıt, bir LogPalette nesnesini tanımlar.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Bu kayıt, bir LogPalette nesnesindeki giriş aralığında RGB (kırmızı-yeşil-mavi) renk değerlerini tanımlar.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Bu kayıt, mantıksal bir paletin boyutunu artırır veya azaltır.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Bu kayıt, geçerli mantıksal paletten sistem paletine girişleri eşler.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Bu kayıt, görüntü yüzeyinin bir alanını geçerli fırça ile doldurur.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Bu kayıt, mevcut konumdan belirtilen noktaya kadar (nokta dahil olmadan) bir çizgi tanımlar. Mevcut konumu belirtilen noktaya sıfırlar.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Bu kayıt bir eliptik yay tanımlar. Yayın son noktasına mevcut konumu sıfırlar.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Bu kayıt, yay ve dikdörtgen işlemleri için kullanılacak çizim yönünü tanımlar.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Bu kayıt, oynatma cihaz bağlamı için mitre birleşimlerinin uzunluk sınırını tanımlar.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Bu kayıt, oynatma cihaz bağlamında bir yol parantezi açar.

--------------------

Bir yol parantezi açıldıktan sonra, bir uygulama yoldaki noktaları tanımlamak için kayıtları işlemeye başlayabilir. Bir uygulama, EMR\_ENDPATH kaydını işleyerek açık bir yol parantezini KAPATMAK zorundadır. Bir uygulama EMR\_BEGINPATH kaydını işlediğinde, önceki tüm yollar oynatma cihaz bağlamından ATILMALIDIR.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Bu kayıt bir yol parantezini kapatır ve parantezle tanımlanan yolu oynatma cihaz bağlamına seçer.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Bu kayıt, bir yoldaki açık şekli kapatır.

--------------------

EMR\_CLOSEFIGURE kaydının işlenmesi, mevcut konumdan şeklin ilk noktasına bir çizgi çizerek şekli KAPATMALI ve ardından çizgi birleştirme stilini kullanarak çizgileri bağlamalıdır. Bir şekil, EMR\_CLOSEFIGURE kaydı yerine EMR\_LINETO kaydı işlenerek kapatılırsa, köşe oluşturmak için birleştirme yerine uç kapakları kullanılır. EMR\_LINETO, bölüm 2.3.5.13'te belirtilmiştir. EMR\_CLOSEFIGURE kaydı, yalnızca oynatma cihaz bağlamında açık bir yol parantezi olduğunda KULLANILMALIDIR. Bir yoldaki şekil, bu kayıt işlenerek açıkça kapatılmadıkça açıktır. Not: Şekil, mevcut nokta ve şeklin başlangıç noktası aynı olsa bile açık olabilir. EMR\_CLOSEFIGURE kaydı işlendiğinden sonra, yola bir çizgi veya eğri eklemek YENİ bir şekil başlatmalıdır.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Bu kayıt, geçerli yoldaki açık tüm şekilleri kapatır ve yolun içini geçerli fırça ve çokgen doldurma modu kullanarak doldurur.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Bu kayıt, bir yoldaki açık tüm şekilleri kapatır, yolun dış hattını geçerli kalemle çizer ve içini geçerli fırça ile doldurur.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Bu kayıt, belirtilen yolu geçerli kalemle işler.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Bu kayıt, yol içinde seçili olan herhangi bir eğriyi oynatma cihaz bağlamına dönüştürür ve her eğriyi bir dizi çizgiye çevirir.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Bu kayıt, geçerli yolu, oynatma cihaz bağlamına şu anda seçili kalemle çizildiğinde boyanacak alan olarak yeniden tanımlar.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Bu kayıt, geçerli yolu oynatma cihaz bağlamı için bir kırpma bölgesi olarak tanımlar ve yeni bölgeyi belirtilen modla mevcut kırpma bölgesiyle birleştirir.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Bu kayıt, bir yol parantezini iptal eder veya kapalı bir yol parantezinden yolu atar.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Bu kayıt, keyfi özel verileri belirtir.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Bu kayıt, belirtilen bölgeyi belirtilen fırça ile doldurur.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Bu kayıt, belirtilen bölgenin etrafına belirtilen fırça ile bir kenarlık çizer.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Bu kayıt, belirtilen bölgedeki renkleri tersine çevirir.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Bu kayıt, oynatma cihaz bağlamına şu anda seçili fırça ile belirtilen bölgeyi boyar.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Bu kayıt, belirtilen bölgeyi geçerli kırpma bölgesiyle belirtilen mod kullanarak birleştirir.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını belirtir.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını, gerekirse çıktıyı hedefin boyutlarına sığdırmak için genişleterek veya sıkıştırarak belirtir.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseni ve bir renk maskesi bitmap'i uygulamasıyla birlikte, belirtilen ön plan ve arka plan raster işlemlerine göre piksel blok aktarımını belirtir.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Bu kayıt, bir kaynak bitmap'ten bir hedef paralelograma, bir renk maskesi bitmap'i uygulamasıyla birlikte piksel blok aktarımını belirtir.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Bu kayıt, bir kaynak bitmap'in belirtilen tarama satırlarından bir hedef dikdörtgene piksel blok aktarımını belirtir.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Bu kayıt, bir kaynak bitmap'ten bir hedef dikdörtgene, isteğe bağlı olarak bir fırça deseniyle birlikte, belirtilen bir raster işlemi göre piksel blok aktarımını, gerekirse çıktıyı hedefin boyutlarına sığdırmak için genişleterek veya sıkıştırarak belirtir.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Bu kayıt, belirtilen özelliklere sahip mantıksal bir yazı tipi tanımlar. Yazı tipi, daha sonra oynatma cihaz bağlamı için mevcut yazı tipi olarak seçilebilir.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir ASCII metin dizesi çizer. Not: EMR\_EXTTEXTOUTA, bir EMR\_EXTTEXTOUTW kaydıyla (bölüm 2.3.5.8) taklit edilmelidir. Bu, EmrText nesnesindeki ASCII metin dizesinin Unicode UTF16-LE kodlamasına dönüştürülmesini gerektirir.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Bu kayıt, geçerli yazı tipini ve metin renklerini kullanarak bir Unicode metin dizesi çizer.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Bu kayıt bir veya daha fazla Bezier eğrisi tanımlar. Eğriler, mevcut kalemi kullanarak çizilir.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Bu kayıt, iki veya daha fazla köşeyi düz çizgilerle bağlayan bir çokgeni tanımlar. Çokgen, mevcut kalemle kontur çizilerek ve mevcut fırça ile çokgen doldurma modu kullanılarak doldurulur. Çokgen, son köşeden ilk köşeye bir çizgi çizilerek otomatik olarak kapatılır.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Bu kayıt, belirtilen dizideki noktaları bağlayarak bir dizi çizgi segmenti tanımlar.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Bu kayıt, geçerli konuma dayalı bir veya daha fazla Bezier eğrisi tanımlar.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Bu kayıt, mevcut konuma dayalı bir veya daha fazla düz çizgi tanımlar. Bir çizgi, mevcut konumdan Points alanı tarafından belirtilen ilk noktaya mevcut kalemi kullanarak çizilir. Her ek çizgi için, çizim önceki çizginin bitiş noktasından Points tarafından belirtilen bir sonraki noktaya yapılır.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Bu kayıt, birden çok bağlanmış çizgi segmenti serisini tanımlar.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Bu kayıt bir dizi kapalı çokgen tanımlar. Her çokgen, mevcut kalemi kullanarak konturlanır ve mevcut fırça ve çokgen doldurma modu kullanılarak doldurulur. Bu kayıt tarafından belirtilen çokgenler üst üste binebilir.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Bu kayıt, bir dizi çizgi segmenti ve Bezier eğrisi tanımlar.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Bu kayıt, belirtilen bitmap desenine sahip mantıksal bir fırça tanımlar. Bitmap, cihaz bağımsız bir bitmap (DIB) bölüm bitmapi veya cihaz bağımlı bir bitmap olabilir.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Bu kayıt, DIB tarafından belirtilen desene sahip mantıksal bir fırça tanımlar.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Bu kayıt, belirtilen stil, genişlik ve fırça özelliklerine sahip mantıksal bir kozmetik veya geometrik kalemi tanımlar.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla ASCII metin dizesi çizer. Not: EMR\_POLYTEXTOUTA, her dize için bir EMR\_EXTTEXTOUTW kaydı serisiyle taklit edilmelidir.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Bu kayıt, mevcut yazı tipi ve metin renklerini kullanarak bir veya daha fazla Unicode metin dizesi çizer. Not: EMR\_POLYTEXTOUTW, her dize için bir EMR\_EXTTEXTOUTW kaydı serisiyle taklit edilmelidir.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Bu kayıt, grafik işlemleri için Görüntü Renk Yönetimi (ICM) modunu belirtir.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Bu kayıt, ASCII karakterlerden oluşan bir ad taşıyan bir renk profili üzerinden mantıksal bir renk uzayı nesnesi oluşturur.

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Bu kayıt, grafik işlemleri için geçerli mantıksal renk uzayı nesnesini tanımlar.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Bu kayıt, mantıksal bir renk alanı nesnesini siler. Not: Mantıksal bir renk alanı nesnesini silmek için EMR\_DELETECOLORSPACE yerine bir EMR\_DELETEOBJECT kaydı KULLANILMALIDIR.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Bu kayıt, bir OpenGL işlevini belirtir.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Bu kayıt, çıktı için sınırlayıcı bir dikdörtgen içeren bir OpenGL işlevini belirtir.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Bu kayıt, grafik işlemleri için kullanılacak piksel biçimini belirtir.

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Bu kayıt, sürücüye keyfi bilgi iletir. Amacı, bilginin çizim yapılmasına yol açmasıdır.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Bu kayıt, sürücüye keyfi bilgi iletir. Amacı, bilginin çizim yapılmasına neden olmamasıdır.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Bu kayıt bir dize çıktılar.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Bu kayıt, yazı tipi eşleyicisinin, LogFont bilgilerine tercih olarak UniversalFontId'lerine göre yazı tiplerini eşlemesini zorlar.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Bu kayıt, verilen adlandırılmış sürücüye keyfi bilgi gönderir.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Bu kayıt, Windows Color System (WCS) 1.0 değerlerini kullanarak mantıksal palet nesnesinin girişlerini nasıl düzelteceğini belirtir.

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Bu kayıt, grafik çıktısı için ASCII karakterlerinden oluşan bir ada sahip bir dosyada renk profilini belirtir.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Bu kayıt, grafik çıktısı için Unicode karakterlerinden oluşan bir ada sahip bir dosyada renk profilini belirtir.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Bu kayıt, belirtilen bir karıştırma işlemi doğrultusunda, alfa şeffaflık verilerini içerecek şekilde, kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını belirtir.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Bu kayıt, metin ve grafiklerin çizildiği sıralamayı belirtir.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Bu kayıt, belirtilen bir rengi şeffaf olarak kabul ederek, gerekirse çıktıyı hedefin boyutlarına sığdırmak için gererek veya sıkıştırarak, kaynak bitmap'ten hedef dikdörtgene piksel blok aktarımını belirtir.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Bu kayıt, dikdörtgenleri veya üçgenleri renk geçişleriyle doldurulmasını belirtir.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Bu kayıt, karakter araması sırasında kullanılacak bağlı yazı tiplerinin UniversalFontIds değerlerini ayarlar.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Bu kayıt, hizalama amacıyla bölme karakterlerine eklenecek ekstra boşluk miktarını belirtir.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir dosyada belirtilen renk profiliyle renk eşleştirmesi yapılıp yapılmayacağını belirtir.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Bu kayıt, Unicode karakterlerinden oluşan bir ada sahip bir renk profilinden mantıksal bir renk uzayı nesnesi oluşturur.

