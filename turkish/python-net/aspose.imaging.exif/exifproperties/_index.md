---
title: "ExifProperties Enumerasyonu"
type: docs
weight: 190
url: /tr/python-net/aspose.imaging.exif/exifproperties/
---

Exif etiketleri listesi

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Üye adı** | **Açıklama** |
| :- | :- |
| APERTURE_VALUE | Lens diyafram değeri. |
| ARTIST | Bu etiket, kamera sahibi, fotoğrafçı veya görüntü oluşturucusunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak birlikte çalışabilirliği kolaylaştırmak için bilginin aşağıdaki örnekteki gibi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. Ör.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Görüntü bileşeni başına bit sayısı. Bu standartta görüntünün her bileşeni 8 bit olduğundan, bu etiketin değeri 8'dir. |
| BODY_SERIAL_NUMBER | Kamera gövdesi seri numarasını içerir |
| BRIGHTNESS_VALUE | Parlaklık değeri. |
| CAMERA_OWNER_NAME | Kamera sahibi adını içerir |
| CFA_PATTERN | Tek çipli renk alan sensörü kullanıldığında görüntü sensörünün renk filtresi dizisi (CFA) geometrik desenini gösterir. Tüm algılama yöntemlerine uygulanmaz. |
| COLOR_SPACE | Renk uzayı bilgi etiketi (ColorSpace) her zaman renk uzayı belirteci olarak kaydedilir. |
| COMPONENTS_CONFIGURATION | Bileşenlerin yapılandırması. |
| COMPRESSED_BITS_PER_PIXEL | Sıkıştırılmış veriye özgüdür; piksel başına sıkıştırılmış bit sayısını belirtir. |
| COMPRESSION | Görüntü verileri için kullanılan sıkıştırma şeması. Bir birincil görüntü JPEG ile sıkıştırıldığında, bu gösterim gerekli değildir ve atlanır. |
| CONTRAST | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| COPYRIGHT | Telif hakkı bilgisi. Bu standartta etiket, fotoğrafçı ve editör telif haklarını<br/>                göstermek için kullanılır. Bu, görüntünün haklarını talep eden kişi ya da kuruluşun<br/>                telif hakkı bildirimidir. Interoperability telif hakkı<br/>                beyanı, tarih ve hakları içerecek şekilde bu alana yazılmalıdır; örn., "Copyright, John Smith, 19xx. All rights<br/>                reserved.". Bu standartta alan, fotoğrafçı ve editör telif haklarını, beyanın ayrı bir<br/>                kısmında kaydeder. Fotoğrafçı ve editör telif hakları arasında net bir ayrım olduğunda, bunlar<br/>                fotoğrafçı takiben editör telif hakkı sırasıyla, NULL ile ayrılarak yazılır (bu durumda beyan aynı zamanda<br/>                bir NULL ile bittiği için iki NULL kodu bulunur). Sadece fotoğrafçı<br/>                telif hakkı verildiğinde, bir NULL kodu ile sonlandırılır. Sadece<br/>                editör telif hakkı verildiğinde, fotoğrafçı telif hakkı bölümü bir boşluk ve sonlandırıcı NULL kodundan oluşur, ardından<br/>                editör telif hakkı verilir. Alan boş bırakıldığında, bilinmiyormuş gibi değerlendirilir. |
| CUSTOM_RENDERED | Bu etiket, görüntü verileri üzerinde çıktıya yönelik render gibi özel işleme kullanımını gösterir. Özel işleme gerçekleştirildiğinde, okuyucunun daha fazla işleme devre dışı bırakması veya en aza indirmesi beklenir. |
| DATE_TIME | Görüntünün oluşturulma tarihi ve saati. Exif standardında, dosyanın değiştirildiği tarih ve saat olarak tanımlanır. |
| DATE_TIME_DIGITIZED | Sayısallaştırma tarih ve saati. |
| DATE_TIME_ORIGINAL | Orijinal görüntü verisinin oluşturulduğu tarih ve saat. |
| DEVICE_SETTING_DESCRIPTION | Bu etiket, belirli bir kamera modelinin fotoğraf çekim koşulları hakkında bilgi verir. Etiket yalnızca okuyucuda fotoğraf çekim koşullarını göstermek için kullanılır. |
| DIGITAL_ZOOM_RATIO | Bu etiket, görüntünün çekildiği sıradaki dijital zoom oranını gösterir. Kaydedilen değerin payı 0 ise, dijital zoomun kullanılmadığını gösterir. |
| EXIF_IFD_POINTER | Exif IFD'ye bir işaretçi. Interoperability, Exif IFD, TIFF'te belirtilen IFD ile aynı yapıya sahiptir. Ancak genellikle, TIFF durumunda olduğu gibi görüntü verisi içermez. |
| EXIF_VERSION | Exif sürümü. |
| EXPOSURE_BIAS_VALUE | Pozlama sapma değeri. |
| EXPOSURE_INDEX | Görüntü yakalandığında kamera veya giriş cihazı üzerinde seçilen pozlama indeksini gösterir. |
| EXPOSURE_MODE | Bu etiket, görüntü çekildiğinde ayarlanan pozlama modunu gösterir. Otomatik braketleme modunda, kamera aynı sahnenin farklı pozlama ayarlarıyla bir dizi kare çeker. |
| EXPOSURE_PROGRAM | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan program sınıfı. |
| EXPOSURE_TIME | Pozlama süresi, saniye cinsinden verilir. |
| FILE_SOURCE | Dosya kaynağı. |
| FLASH | Görüntü çekildiğinde flaşın durumunu gösterir. |
| FLASHPIX_VERSION | Bir FPXR dosyası tarafından desteklenen Flashpix format sürümü. |
| FLASH_ENERGY | Görüntü yakalandığında ölçülen, ışın mum gücü saniyesi (BCPS) cinsinden strob enerji seviyesini gösterir. |
| FOCAL_LENGTH | Lensin gerçek odak uzaklığı, milimetre cinsinden. |
| FOCAL_LENGTH_IN_35_MM_FILM | Bu etiket, 35mm filmli bir kamera varsayılarak eşdeğer odak uzaklığını milimetre cinsinden gösterir. 0 değeri odak uzaklığının bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| FOCAL_PLANE_RESOLUTION_UNIT | FocalPlaneXResolution ve FocalPlaneYResolution ölçümü için birimi gösterir. Bu değer ResolutionUnit ile aynıdır. |
| FOCAL_PLANE_X_RESOLUTION | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını gösterir. |
| FOCAL_PLANE_Y_RESOLUTION | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir. |
| F_NUMBER | F sayısı. |
| GAIN_CONTROL | Bu etiket, genel görüntü kazanç ayarının derecesini gösterir. |
| GAMMA | Gamma değeri |
| GPSDOP | GPS DOP (veri kesinliği derecesi) gösterir. İki boyutlu ölçüm sırasında bir HDOP değeri, üç boyutlu ölçüm sırasında ise bir PDOP değeri yazılır.<br/>                 |
| GPS_ALTITUDE | GPSAltitudeRef referansına göre yüksekliği gösterir. Yükseklik bir RATIONAL değer olarak ifade edilir.<br/>                Referans birimi metredir. |
| GPS_ALTITUDE_REF | Referans yüksekliği olarak kullanılan yüksekliği gösterir. Referans deniz seviyesi ise ve yükseklik deniz seviyesinin üzerindeyse,<br/>                0 verilir. Yükseklik deniz seviyesinin altındaysa, 1 değeri verilir ve yükseklik GPSAltitude etiketinde mutlak bir değer olarak gösterilir.<br/>                 |
| GPS_AREA_INFORMATION | GPS bölgesinin adını kaydeden bir karakter dizisi. İlk bayt kullanılan karakter kodunu gösterir,<br/>                ardından GPS bölgesinin adı gelir. |
| GPS_DATE_STAMP | UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden bir karakter dizisi.<br/>                Biçim YYYY:MM:DD'dir. |
| GPS_DEST_BEARING | Hedef noktaya doğru yönü gösterir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPS_DEST_BEARING_REF | Hedef noktaya yön vermek için kullanılan referansı gösterir. 'T' gerçek yönü, 'M' ise<br/>                manyetik yönü gösterir. |
| GPS_DEST_DISTANCE | Hedef noktaya olan mesafeyi gösterir. |
| GPS_DEST_DISTANCE_REF | Hedef noktaya olan mesafeyi ifade etmek için kullanılan birimi gösterir. 'K', 'M' ve 'N' sırasıyla kilometre, mil<br/>                ve knot anlamına gelir. |
| GPS_DEST_LATITUDE | Hedef noktanın enlemini gösterir. Enlem, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir.<br/>                derece, dakika ve saniyeler. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir format dd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikaların kesirleri iki ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 olur. |
| GPS_DEST_LATITUDE_REF | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösterir. ASCII değeri 'N' kuzey<br/>                enlemini, 'S' ise güney enlemini gösterir. |
| GPS_DEST_LONGITUDE | Hedef noktanın boylamını gösterir. Boylam, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir.<br/>                derece, dakika ve saniyeler. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir format ddd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikaların kesirleri iki ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 olur. |
| GPS_DEST_LONGITUDE_REF | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösterir. ASCII 'E' doğu boylamını,<br/>                'W' ise batı boylamını gösterir. |
| GPS_DIFFERENTIAL | GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösterir. |
| GPS_IFD_POINTER | gps ifd işaretçisi. |
| GPS_IMG_DIRECTION | Görüntünün çekildiği yönü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPS_IMG_DIRECTION_REF | Görüntünün çekildiği yönün verilmesi için referansı gösterir. 'T' gerçek yönü, 'M' ise<br/>                manyetik yönü gösterir. |
| GPS_LATITUDE | Enlemi gösterir. Enlem, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir.<br/>                derece, dakika ve saniyeler. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir format dd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikaların kesirleri iki ondalık basamağa kadar verildiğinde, format dd/1,mmmm/100,0/1 olur. |
| GPS_LATITUDE_REF | Enlemin kuzey mi yoksa güney mi olduğunu gösterir. |
| GPS_LONGITUDE | Boylamı gösterir. Boylam, derece, dakika ve saniyeyi sırasıyla veren üç RATIONAL değer olarak ifade edilir.<br/>                derece, dakika ve saniyeler. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir format ddd/1,mm/1,ss/1 olur. Derece ve dakikalar kullanıldığında ve örneğin, dakikaların kesirleri iki ondalık basamağa kadar verildiğinde, format ddd/1,mmmm/100,0/1 olur. |
| GPS_LONGITUDE_REF | Boylamın doğu mu yoksa batı mı olduğunu gösterir. |
| GPS_MAP_DATUM | GPS alıcısı tarafından kullanılan jeodezik ölçüm verilerini gösterir. |
| GPS_MEASURE_MODE | GPS ölçüm modunu gösterir. - 2- veya 3- boyutlu. |
| GPS_PROCESSING_METHOD | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi.<br/>                İlk bayt kullanılan karakter kodunu gösterir ve ardından yöntemin adı<br/>                gelir. |
| GPS_SATELLITES | Ölçümler için kullanılan GPS uydularını gösterir. Bu etiket, uydu sayısını,<br/>                kimlik numarasını, yükselti açısını, azimutu, SNR ve diğer bilgileri ASCII notasyonunda tanımlamak için kullanılabilir. Biçim belirtilmemiştir.<br/>                GPS alıcısı ölçüm yapamıyorsa, etiketin değeri NULL olarak ayarlanmalıdır. |
| GPS_SPEED | GPS alıcısının hareket hızını gösterir. |
| GPS_SPEED_REF | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi gösterir. 'K' 'M' ve 'N' sırasıyla kilometre/saat,<br/>                mil/saat ve knot anlamına gelir. |
| GPS_STATUS | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| GPS_TIMESTAMP | Zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak gösterir. TimeStamp üç RATIONAL değerle ifade edilir<br/>                saat, dakika ve saniyeyi vererek. |
| GPS_TRACK | GPS alıcısının hareket yönünü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır. |
| GPS_TRACK_REF | GPS alıcısının hareket yönünü vermek için referansı gösterir. 'T' gerçek yönü, 'M' ise<br/>                manyetik yönü belirtir. |
| GPS_VERSION_ID | GPSInfoIFD sürümünü gösterir. |
| IMAGE_DESCRIPTION | Görüntünün başlığını veren bir karakter dizisi. "1988 şirket pikniği" gibi bir yorum olabilir. |
| IMAGE_LENGTH | Görüntü verisinin satır sayısı. |
| IMAGE_UNIQUE_ID | Görselin benzersiz kimliği. |
| IMAGE_WIDTH | Görsel verisinin sütun sayısı, satır başına piksel sayısına eşittir. |
| ISO_SPEED | ISO 12232'de tanımlanan ISO hız değeri hakkında bilgi |
| ISO_SPEED_LATITUDE_YYY | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi yyy değerini gösterir |
| ISO_SPEED_LATITUDE_ZZZ | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi zzz değerini gösterir |
| JPEG_INTERCHANGE_FORMAT | JPEG sıkıştırılmış küçük resim verisinin başlangıç baytına (SOI) olan offset. Bu, birincil görsel JPEG verisi için kullanılmaz. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | JPEG sıkıştırılmış küçük resim verisinin bayt sayısı. Bu, birincil görsel JPEG verisi için kullanılmaz. JPEG küçük resimler bölünmez, SOI'den EOI'ye kadar kesintisiz bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretçileri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1'de kaydedilecek diğer tüm veriler dahil olmak üzere, 64 Kbaytı geçmemelidir. |
| LENS_MAKE | Bu etiket, lens üreticisini kaydeder |
| LENS_MODEL | Bu etiket, lensin model adını ve model numarasını kaydeder |
| LENS_SERIAL_NUMBER | Bu etiket, değiştirilebilir lensin seri numarasını kaydeder |
| LENS_SPECIFICATION | Bu etiket, minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığındaki minimum F numarasını ve maksimum odak uzaklığındaki minimum F numarasını belirtir |
| LIGHT_SOURCE | Işık kaynağının türü. |
| MAKE | Kayıt ekipmanının üreticisi. Bu, görseli oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| MAKER_NOTE | Exif yazarlarının üreticileri için istenen herhangi bir bilgiyi kaydetmek amacıyla bir etikettir. İçerik üreticiye bağlıdır, ancak bu etiket yalnızca amaçlandığı amaç için kullanılmalıdır. |
| MAX_APERTURE_VALUE | Maksimum diyafram değeri. |
| METERING_MODE | Ölçüm modu. |
| MODEL | Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| OECF | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) gösterir. |
| ORIENTATION | Görüntünün satır ve sütun açısından bakıldığında yönü. |
| PHOTOGRAPHIC_SENSITIVITY | ISO 12232'de belirtildiği gibi kameranın veya giriş cihazının ISO Hızını ve ISO Enlemini gösterir. |
| PHOTOMETRIC_INTERPRETATION | Piksel bileşimi. |
| PIXEL_X_DIMENSION | Sıkıştırılmış veriye özgü bilgi. Bir sıkıştırılmış dosya kaydedildiğinde, dolgu verisi veya yeniden başlatma işareti olsun, anlamlı görüntünün geçerli genişliği bu etikete kaydedilir. |
| PIXEL_Y_DIMENSION | Sıkıştırılmış veriye özgü bilgi. Bir sıkıştırılmış dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikete kaydedilir. |
| PLANAR_CONFIGURATION | Piksel bileşenlerinin chunky (parçalı) ya da planar (düzlemsel) formatta kaydedilip kaydedilmediğini gösterir. Bu alan yoksa, TIFF varsayılanı 1 (parçalı) kabul edilir. |
| PRIMARY_CHROMATICITIES | Görüntünün üç birincil renginin kromatikliği. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| RECOMMENDED_EXPOSURE_INDEX | Önerilen pozlama indeksini gösterir |
| REFERENCE_BLACK_WHITE | Referans siyah nokta değeri ve referans beyaz nokta<br/>                değeri. TIFF'te varsayılanlar verilmez, ancak aşağıdaki değerler burada varsayılan olarak verilmiştir.<br/>                Renk uzayı bir renk uzayı bilgi etiketi içinde bildirilir<br/>                varsayılan<br/>                optimal görüntü özelliklerini sağlayan değer olur<br/>                Bu koşullarda birlikte çalışabilirlik |
| RELATED_SOUND_FILE | İlgili ses dosyası. |
| RESOLUTION_UNIT | XResolution ve YResolution ölçümü için birim. Aynı birim hem XResolution hem de YResolution için kullanılır. Görüntü çözünürlüğü bilinmiyorsa, 2 (inç) atanır. |
| ROWS_PER_STRIP | Şerit başına satır sayısı. Bir görüntü şeritlere bölündüğünde bir şeritteki satır sayısıdır. |
| SAMPLES_PER_PIXEL | Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntülerine uygulandığından, bu etiket için ayarlanan değer 3'tür. |
| SATURATION | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| SCENE_CAPTURE_TYPE | Bu etiket, çekilen sahnenin türünü gösterir. Ayrıca görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| SCENE_TYPE | Sahne türünü gösterir. Eğer bir DSC görüntüyü kaydettiyse, bu etiket değeri her zaman 1 olarak ayarlanmalı ve görüntünün doğrudan fotoğraf çekildiğini gösterir. |
| SENSING_METHOD | Kamera veya giriş cihazındaki görüntü sensörünün türünü gösterir. |
| SENSITIVITY_TYPE | Fotografik duyarlılık türü |
| SHARPNESS | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan keskinlik işleme yönünü gösterir |
| SHUTTER_SPEED_VALUE | Enstantane hızı değeri. |
| YAZILIM | Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılımı ya da donanımının adını ve sürümünü kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıda gösterilen örnek takip edilmesi önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| SPATIAL_FREQUENCY_RESPONSE | Bu etiket, ISO 12233'te belirtildiği gibi, kamera veya giriş cihazının uzamsal frekans tablosunu ve görüntü genişliği, görüntü yüksekliği ve diyagonal yönündeki SFR değerlerini kaydeder. |
| SPECTRAL_SENSITIVITY | Kullanılan kameranın her kanalının spektral duyarlılığını gösterir. |
| STANDARD_OUTPUT_SENSITIVITY | Kameranın standart çıkış duyarlılığını gösterir. |
| STRIP_BYTE_COUNTS | Her şeritteki toplam bayt sayısı. |
| STRIP_OFFSETS | Her şerit için, o şeridin bayt ofseti. Şerit bayt sayısının 64 Kbaytı geçmemesi için bunun seçilmesi önerilir.<br/>                Aux etiket. |
| SUBJECT_AREA | Bu etiket, genel sahnedeki ana konunun konumunu ve alanını gösterir. |
| SUBJECT_DISTANCE | Metre cinsinden verilen konuya olan mesafe. |
| SUBJECT_DISTANCE_RANGE | Bu etiket, konuya olan mesafeyi gösterir. |
| SUBJECT_LOCATION | Sahnedeki ana konunun konumunu gösterir. Bu etiketin değeri, Rotasyon etiketiyle belirtilen döndürme işleminden önce, sol kenara göre ana konunun merkezindeki pikseli temsil eder. |
| SUBSEC_TIME | DateTime etiketi için saniyenin kesirlerini kaydetmekte kullanılan bir etiket. |
| SUBSEC_TIME_DIGITIZED | DateTimeDigitized etiketi için saniyenin kesirlerini kaydetmekte kullanılan bir etiket. |
| SUBSEC_TIME_ORIGINAL | DateTimeOriginal etiketi için saniyenin kesirlerini kaydetmekte kullanılan bir etiket. |
| TRANSFER_FUNCTION | Görüntü için tablo biçiminde tanımlanan bir transfer fonksiyonu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| USER_COMMENT | Exif kullanıcılarının ImageDescription'daki anahtar kelimeler ve yorumların yanı sıra görüntüye anahtar kelime veya yorum yazabilmesi için bir etiket ve ImageDescription etiketinin karakter kodu sınırlamaları olmaksızın. |
| WHITE_BALANCE | Bu etiket, görüntünün çekildiği sırada ayarlanan beyaz dengesi modunu gösterir. |
| WHITE_POINT | Görüntünün beyaz noktasının renk doygunluğu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir. |
| X_RESOLUTION | ImageWidth yönünde ResolutionUnit başına piksel sayısı. Görüntü çözünürlüğü bilinmediğinde 72 [dpi] atanır. |
| Y_CB_CR_COEFFICIENTS | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları. |
| Y_CB_CR_POSITIONING | Krominans bileşenlerinin parlaklık bileşenine göre konumu.<br/>                Bu alan yalnızca JPEG sıkıştırmalı veri veya sıkıştırılmamış YCbCr veri için belirlenir.<br/>                TIFF varsayılanı 1 (ortalanmış) dir; ancak Y:Cb:Cr = 4:2:2 olduğunda, bu standartta verileri kaydetmek için 2 (yan yana) kullanılmasının önerildiği, TV sistemlerinde görüntü kalitesini artırmak için.<br/>                Bu alan mevcut olmadığında, okuyucu TIFF varsayılanını varsaymalıdır.<br/>                Y:Cb:Cr = 4:2:0 durumunda, TIFF varsayılanı (ortalanmış) önerilir.<br/>                Okuyucu her iki YCbCrPositioning türünü de destekleme yeteneğine sahip değilse, bu alandaki değerden bağımsız olarak TIFF varsayılanını izlemelidir.<br/>                Okuyucuların hem ortalanmış hem de yan yana konumlandırmayı destekleyebilmeleri tercih edilir. |
| Y_CB_CR_SUB_SAMPLING | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| Y_RESOLUTION | ImageLength yönünde ResolutionUnit başına piksel sayısı. XResolution ile aynı değer atanır. |
