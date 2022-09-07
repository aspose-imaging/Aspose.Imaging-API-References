---
title: ExifProperties
second_title: Aspose.Imaging for .NET API Referansı
description: Exif etiketleri listesi
type: docs
weight: 1080
url: /tr/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Exif etiketleri listesi

```csharp
public enum ExifProperties : ushort
```

### değerler

| İsim | Değer | Tanım |
| --- | --- | --- |
| ImageWidth | `256` | Satır başına piksel sayısına eşit, görüntü verisi sütunlarının sayısı. |
| ImageLength | `257` | Görüntü verilerinin satır sayısı. |
| BitsPerSample | `258` | Görüntü bileşeni başına bit sayısı. Bu standartta görüntünün her bir bileşeni 8 bittir, dolayısıyla bu etiketin değeri 8. 'dir. |
| Compression | `259` | Görüntü verileri için kullanılan sıkıştırma şeması. Birincil görüntü JPEG sıkıştırıldığında, bu atama gerekli değildir ve atlanır. |
| PhotometricInterpretation | `262` | Piksel bileşimi. |
| ImageDescription | `270` | Resmin başlığını veren bir karakter dizisi. "1988 şirket pikniği" veya benzeri bir yorum olabilir. |
| Make | `271` | Kayıt ekipmanının üreticisi. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında bilinmeyen olarak kabul edilir. |
| Model | `272` | Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video sayısallaştırıcı veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında bilinmeyen olarak kabul edilir. |
| Orientation | `274` | Satır ve sütun olarak görüntülenen görüntü yönü. |
| SamplesPerPixel | `277` | Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntüleri için geçerli olduğundan, bu etiket için ayarlanan değer 3. |
| XResolution | `282` | ImageWidth yönünde Çözünürlük Birimi başına piksel sayısı. Görüntü çözünürlüğü bilinmediğinde, 72 [dpi] belirlenir. |
| YResolution | `283` | ImageLength yönünde Çözünürlük Birimi başına piksel sayısı. XResolution ile aynı değer belirlenir. |
| PlanarConfiguration | `284` | Piksel bileşenlerinin kalın mı yoksa düzlemsel biçimde mi kaydedildiğini gösterir. Bu alan yoksa, TIFF varsayılanının 1 (tıknaz) olduğu varsayılır. |
| ResolutionUnit | `296` | XResolution ve YResolution ölçümü için birim. Aynı birim hem XResolution hem de YResolution için kullanılır. Görüntü çözünürlüğü bilinmiyorsa 2 (inç) belirlenir. |
| TransferFunction | `301` | Tablo stilinde açıklanan resim için bir aktarım işlevi. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk alanı bilgisinde ColorSpace etiketinde belirtilir. |
| Software | `305` | Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılım veya donanım yazılımının adını ve sürümünü kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıda gösterilen örneğe uyulması önerilir. Alan boş bırakıldığında bilinmeyen olarak kabul edilir. |
| DateTime | `306` | Görüntü oluşturma tarihi ve saati. Exif standardında dosyanın değiştirildiği tarih ve saattir. |
| Artist | `315` | Bu etiket, kamera sahibinin, fotoğrafçının veya görüntü oluşturucunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak Birlikte Çalışabilirlik kolaylığı için bilgilerin aşağıdaki örnekteki gibi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. Ör.) "Kamera sahibi, John Smith; Fotoğrafçı, Michael Brown; Görüntü yaratıcısı, Ken James" |
| WhitePoint | `318` | Görüntünün beyaz noktasının renkliliği. Normalde bu etiket gerekli değildir, çünkü renk alanı renk alanı bilgisinde ColorSpace etiketinde belirtilir. |
| PrimaryChromaticities | `319` | Görüntünün üç ana renginin renkliliği. Normalde bu etiket gerekli değildir, çünkü renk alanı renk alanı bilgisinde ColorSpace etiketinde belirtilir. |
| YCbCrCoefficients | `529` | RGB'den YCbCr görüntü verilerine dönüşüm için matris katsayıları. |
| YCbCrSubSampling | `530` | Parlaklık bileşenine göre krominans bileşenlerinin örnekleme oranı. |
| YCbCrPositioning | `531` | Renklilik bileşenlerinin, parlaklık bileşenine göre konumu. Bu alan yalnızca JPEG sıkıştırılmış verileri veya sıkıştırılmamış YCbCr verileri için belirlenmiştir. TIFF varsayılanı 1'dir (ortalanmış); ancak Y:Cb:Cr = 4:2:2 olduğunda, TV sistemlerinde görüntülendiğinde görüntü kalitesini iyileştirmek için bu standartta 2'nin (birlikte konumlu) veri kaydetmek için kullanılması önerilir. Bu alan mevcut olmadığında, okuyucu TIFF varsayılanını olarak kabul edecektir. Y:Cb:Cr = 4:2:0 olması durumunda, TIFF varsayılanı (ortalanmış) önerilir. Reader , her iki YCbCrPositioning türünü destekleme yeteneğine sahip değilse, bu alandaki değerden bağımsız olarak TIFF varsayılanını izleyecektir. " okuyucularının hem ortalanmış hem de ortak konumlu konumlandırmayı destekleyebilmesi tercih edilir. |
| ReferenceBlackWhite | `532` | Referans siyah nokta değeri ve referans beyaz nokta değeri. TIFF'de varsayılanlar verilmez, ancak aşağıdaki değerler burada varsayılanlar olarak verilir. Renk alanı, bir renk alanı bilgi etiketinde bildirilir; default , optimum görüntü özelliklerini veren değerdir Birlikte çalışabilirlik bu koşullar |
| Copyright | `33432` | Telif hakkı bilgisi. Bu standartta etiketi, hem fotoğrafçı hem de editör telif haklarını belirtmek için olarak kullanılır. Görüntü üzerinde hak iddiasında bulunan kişi veya kuruluşun telif hakkı bildirimidir. Bu alanına tarih ve haklar dahil birlikte çalışabilirlik telif hakkı beyanı yazılmalıdır; örneğin, "Telif hakkı, John Smith, 19xx. Tüm hakları saklıdır.". Bu standartta alan, hem fotoğrafçı hem de editör telif haklarını kaydeder ve her biri bildirimin ayrı bir bölümünde a olarak kaydedilir. Fotoğrafçı ve editör telif hakları arasında net bir ayrım olduğunda, bunlar fotoğrafçının ardından editör telif hakkı ile yazılmalı, NULL ile ayrılmalıdır (bu durumda ifade ayrıca a NULL ile bittiği için, iki NULL kodu vardır. ). Yalnızca fotografçı telif hakkı verildiğinde, bir NULL kodla sonlandırılır. Yalnızca editör telif hakkı verildiğinde, fotoğrafçı telif hakkı part bir boşluk ve ardından bir sonlandırılan NULL kodundan oluşur, ardından editör telif hakkı verilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. |
| ExposureTime | `33434` | Pozlama süresi, saniye cinsinden verilir. |
| FNumber | `33437` | F numarası. |
| ExposureProgram | `34850` | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan programın sınıfı. |
| SpectralSensitivity | `34852` | Kullanılan kameranın her kanalının spektral hassasiyetini gösterir. |
| PhotographicSensitivity | `34855` | Kameranın veya giriş cihazının ISO Hızını ve ISO Enlemini, ISO 12232'de belirtildiği gibi gösterir. |
| OECF | `34856` | ISO 14524'te belirtilen Opto-Elektrik Dönüştürme İşlevini (OECF) belirtir. |
| ExifVersion | `36864` | Exif sürümü. |
| DateTimeOriginal | `36867` | Orijinal görüntü verilerinin oluşturulduğu tarih ve saat. |
| DateTimeDigitized | `36868` | Sayısallaştırılan tarih saat. |
| ComponentsConfiguration | `37121` | Bileşen yapılandırması. |
| CompressedBitsPerPixel | `37122` | Sıkıştırılmış verilere özel; piksel başına sıkıştırılmış bitleri belirtir. |
| ShutterSpeedValue | `37377` | Deklanşör hızı değeri. |
| ApertureValue | `37378` | Objektif diyafram değeri. |
| BrightnessValue | `37379` | Parlaklık değeri. |
| ExposureBiasValue | `37380` | Maruz kalma yanlılığı değeri. |
| MaxApertureValue | `37381` | Maksimum diyafram değeri. |
| SubjectDistance | `37382` | Metre cinsinden verilen özneye olan mesafe. |
| MeteringMode | `37383` | Ölçüm modu. |
| LightSource | `37384` | Nazik ışık kaynağı. |
| Flash | `37385` | Görüntü çekildiğinde flaşın durumunu gösterir. |
| FocalLength | `37386` | Merceğin mm cinsinden gerçek odak uzaklığı. |
| SubjectArea | `37396` | Bu etiket, genel sahnedeki ana konunun yerini ve alanını gösterir. |
| MakerNote | `37500` | Exif yazarlarının üreticileri için istenen herhangi bir bilgiyi kaydetmeleri için bir etiket. İçerik üreticiye bağlıdır, ancak bu etiket kullanım amacı dışında kullanılmamalıdır. |
| UserComment | `37510` | Exif kullanıcılarının, ImageDescription'dakilerin yanı sıra ve ImageDescription etiketinin karakter kodu sınırlamaları olmaksızın, görüntüye anahtar sözcükler veya yorumlar yazabileceği bir etiket. |
| SubsecTime | `37520` | DateTime etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeOriginal | `37521` | DateTimeOriginal etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| SubsecTimeDigitized | `37522` | DateTimeDigitized etiketi için saniyelerin kesirlerini kaydetmek için kullanılan bir etiket. |
| FlashpixVersion | `40960` | Bir FPXR dosyası tarafından desteklenen Flashpix biçimi sürümü. |
| ColorSpace | `40961` | Renk alanı bilgi etiketi (ColorSpace) her zaman renk alanı belirteci olarak kaydedilir. |
| RelatedSoundFile | `40964` | İlgili ses dosyası. |
| FlashEnergy | `41483` | Işın Mum Gücü Saniyesinde (BCPS) ölçüldüğü gibi, görüntünün çekildiği andaki flaş enerjisini gösterir. |
| SpatialFrequencyResponse | `41484` | Bu etiket, ISO 12233'te belirtildiği gibi, kamera veya giriş cihazı uzamsal frekans tablosunu ve SFR değerlerini görüntü genişliği, görüntü yüksekliği ve çapraz yön yönünde kaydeder. |
| FocalPlaneXResolution | `41486` | Kamera odak düzleminde FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını belirtir. |
| FocalPlaneYResolution | `41487` | Kamera odak düzleminde FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını belirtir. |
| FocalPlaneResolutionUnit | `41488` | FocalPlaneXResolution ve FocalPlaneYResolution ölçüm birimini gösterir. Bu değer, ResolutionUnit. ile aynıdır. |
| SubjectLocation | `41492` | Sahnedeki ana konunun konumunu belirtir. Bu etiketin değeri, Döndürme etiketine göre döndürme işleminden önce, sol kenara göre ana konunun merkezindeki pikseli temsil eder. |
| ExposureIndex | `41493` | Görüntünün çekildiği anda kamerada veya giriş cihazında seçilen pozlama indeksini gösterir. |
| SensingMethod | `41495` | Kamera veya giriş aygıtındaki görüntü sensörü türünü belirtir. |
| FileSource | `41728` | Dosya kaynağı. |
| SceneType | `41729` | Sahnenin türünü belirtir. Bir DSC görüntüyü kaydettiyse, bu etiket değeri, görüntünün doğrudan fotoğraflandığını belirten her zaman 1'e ayarlanmalıdır. |
| CFAPattern | `41730` | Tek çipli bir renk alanı sensörü kullanıldığında, görüntü sensörünün renk filtresi dizisi (CFA) geometrik modelini gösterir. Tüm algılama yöntemleri için geçerli değildir. |
| CustomRendered | `41985` | Bu etiket, çıktıya yönelik işleme gibi görüntü verileri üzerinde özel işlemenin kullanıldığını gösterir. Özel işleme gerçekleştirildiğinde, okuyucunun daha fazla işlemi devre dışı bırakması veya en aza indirmesi beklenir. |
| ExposureMode | `41986` | Bu etiket, görüntü çekildiğinde ayarlanan poz modunu gösterir. Otomatik basamaklama modunda, fotoğraf makinesi aynı sahnenin bir dizi karesini farklı pozlama ayarlarında çeker. |
| WhiteBalance | `41987` | Bu etiket, görüntü çekildiğinde ayarlanan beyaz dengesi modunu gösterir. |
| DigitalZoomRatio | `41988` | Bu etiket, görüntü çekildiğinde dijital yakınlaştırma oranını gösterir. Kaydedilen değerin payı 0 ise bu, dijital yakınlaştırmanın kullanılmadığını gösterir. |
| FocalLengthIn35MmFilm | `41989` | Bu etiket, mm cinsinden 35 mm filmli bir kamera varsayıldığında eşdeğer odak uzaklığını gösterir. 0 değeri, odak uzaklığının bilinmediği anlamına gelir. Bu etiketin FocalLength etiketinden farklı olduğunu unutmayın. |
| SceneCaptureType | `41990` | Bu etiket, çekilen sahnenin türünü belirtir. Ayrıca görüntünün çekildiği modu kaydetmek için de kullanılabilir. |
| GainControl | `41991` | Bu etiket, genel görüntü kazancı ayarının derecesini gösterir. |
| Contrast | `41992` | Bu etiket, görüntü çekilirken kamera tarafından uygulanan kontrast işlemenin yönünü gösterir. |
| Saturation | `41993` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan doygunluk işleminin yönünü gösterir. |
| Sharpness | `41994` | Bu etiket, görüntü çekildiğinde kamera tarafından uygulanan netlik işleme yönünü gösterir |
| DeviceSettingDescription | `41995` | Bu etiket, belirli bir kamera modelinin fotoğraf çekme koşullarına ilişkin bilgileri gösterir. Etiket yalnızca okuyucudaki resim çekme koşullarını belirtmek için kullanılır. |
| SubjectDistanceRange | `41996` | Bu etiket özneye olan uzaklığı gösterir. |
| ImageUniqueID | `42016` | Resmin benzersiz kimliği. |
| GPSVersionID | `0` | GPSInfoIFD sürümünü gösterir. |
| GPSLatitudeRef | `1` | Enlemin kuzey mi yoksa güney enlemi mi olduğunu gösterir. |
| GPSLatitude | `2` | Enlemi gösterir. Enlem sırasıyla derece, dakika ve saniye veren üç RATIONAL değeri olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir biçim dd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, iki ondalık basamağa kadar dakika kesirleri verildiğinde, biçim dd/1,mmmm/100,0/1. olur. |
| GPSLongitudeRef | `3` | Boylamın doğu veya batı boylamı olduğunu gösterir. |
| GPSLongitude | `4` | Boylamı gösterir. Boylam sırasıyla derece, dakika ve saniye veren üç RATIONAL değeri olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir biçim ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin, iki ondalık basamağa kadar dakika kesirleri verildiğinde, biçim ddd/1,mmmm/100,0/1. olur. |
| GPSAltitudeRef | `5` | Referans irtifa olarak kullanılan rakımı gösterir. Referans deniz seviyesi ise ve rakım deniz seviyesinden yüksekse 0 verilir. Rakım deniz seviyesinin altındaysa 1 değeri verilir ve rakım GPSAltitude etiketinde mutlak değer olarak belirtilir. |
| GPSAltitude | `6` | GPSAltitudeRef'teki referansa dayalı olarak rakımı gösterir. Rakım bir RATIONAL değeri olarak ifade edilir. Referans birimi metredir. |
| GPSTimestamp | `7` | Saati UTC (Koordineli Evrensel Saat) olarak gösterir. Zaman Damgası, saat, dakika ve saniyeyi veren üç RATIONAL değeri olarak ifade edilir. |
| GPSSatellites | `8` | Ölçümler için kullanılan GPS uydularını gösterir. Bu etiket, uyduların sayısını, kimlik numaralarını, yükseklik açısını, azimutu, SNR'yi ve ASCII notasyonundaki diğer bilgileri tanımlamak için kullanılabilir. Biçim belirtilmemiş . GPS alıcısı ölçüm yapamıyorsa, etiketin değeri NULL olarak ayarlanmalıdır. |
| GPSStatus | `9` | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| GPSMeasureMode | `10` | GPS ölçüm modunu gösterir. - 2 veya 3 boyutlu. |
| GPSDOP | `11` | GPS DOP'yi gösterir (veri kesinlik derecesi). İki boyutlu ölçüm sırasında bir HDOP değeri, ve üç boyutlu ölçüm sırasında PDOP değeri yazılır. |
| GPSSpeedRef | `12` | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi gösterir. 'K' 'M' ve 'N', saatte kilometre, saatte mil ve deniz milini temsil eder. |
| GPSSpeed | `13` | GPS alıcısı hareketinin hızını gösterir. |
| GPSTrackRef | `14` | GPS alıcısı hareketinin yönünü vermek için referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir. |
| GPSTrack | `15` | GPS alıcısı hareketinin yönünü gösterir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPSImgDirectionRef | `16` | Yakalandığında görüntünün yönünü vermek için referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir. |
| GPSImgDirection | `17` | Görüntünün çekildiği andaki yönünü belirtir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPSMapDatum | `18` | GPS alıcısı tarafından kullanılan jeodezik araştırma verilerini gösterir. |
| GPSDestLatitudeRef | `19` | Varış noktasının enleminin kuzey mi yoksa güney enlemi mi olduğunu gösterir. ASCII değeri 'N' kuzey enlemini, 'S' ise güney enlemini gösterir. |
| GPSDestLatitude | `20` | Varış noktasının enlemini gösterir. Enlem, sırasıyla derece, dakika ve saniye veren üç RATIONAL değeri olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse, tipik bir biçimi gg/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakika kesirleri iki ondalık basamağa kadar verildiğinde olduğunda, biçim dd/1,mmmm/100,0/1. olur. |
| GPSDestLongitudeRef | `21` | Varış noktasının boylamının doğu veya batı boylamı olduğunu gösterir. ASCII 'E' doğu boylamını, ve 'W' batı boylamını gösterir. |
| GPSDestLongitude | `22` | Varış noktasının boylamını gösterir. Boylam, sırasıyla derece, dakika ve saniye veren üç RATIONAL değeri olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse, tipik bir biçimi ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakika kesirleri iki ondalık basamağa kadar verildiğinde olduğunda, biçim ddd/1,mmmm/100,0/1. olur. |
| GPSDestBearingRef | `23` | Yönü varış noktasına vermek için kullanılan referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir. |
| GPSDestBearing | `24` | Varış noktasına olan kerterizi gösterir. Değer aralığı 0,00 ile 359,99 arasındadır. |
| GPSDestDistanceRef | `25` | Varış noktasına olan mesafeyi ifade etmek için kullanılan birimi belirtir. 'K', 'M' ve 'N' kilometreleri, mil ve düğümleri temsil eder. |
| GPSDestDistance | `26` | Hedef noktaya olan mesafeyi gösterir. |
| GPSProcessingMethod | `27` | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizisi. İlk bayt, kullanılan karakter kodunu belirtir ve bunu yöntemin name 'si izler. |
| GPSAreaInformation | `28` | GPS alanının adını kaydeden bir karakter dizisi. İlk bayt, kullanılan karakter kodunu gösterir ve bunu GPS alanının adı izler. |
| GPSDateStamp | `29` | UTC (Koordineli Evrensel Saat) ile ilgili tarih ve saat bilgilerini kaydeden bir karakter dizisi. Biçim YYYY:MM:DD. şeklindedir. |
| GPSDifferential | `30` | GPS alıcısına diferansiyel düzeltme uygulanıp uygulanmadığını gösterir. |
| StripOffsets | `273` | Her şerit için, o şeridin bayt ofseti. Bunun, şerit bayt sayısının 64 Kbaytı geçmeyecek şekilde seçilmesi önerilir. Aux etiketi. |
| JPEGInterchangeFormat | `513` | JPEG sıkıştırılmış küçük resim verilerinin başlangıç baytına (SOI) göre kayma. Bu, birincil resim JPEG verileri için kullanılmaz. |
| JPEGInterchangeFormatLength | `514` | JPEG sıkıştırılmış küçük resim verilerinin bayt sayısı. Bu, birincil görüntü JPEG verileri için kullanılmaz. JPEG küçük resimleri bölünmez, ancak SOI'den EOI'ye sürekli bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretleri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1. 'ye kaydedilecek tüm diğer veriler dahil olmak üzere en fazla 64 Kbayt'ta kaydedilmelidir. |
| ExifIfdPointer | `34665` | Exif IFD'si için bir işaretçi. Birlikte çalışabilirlik, Exif IFD, TIFF'de belirtilen IFD ile aynı yapıya sahiptir. ancak normalde, TIFF. durumunda olduğu gibi görüntü verisi içermez. |
| GPSIfdPointer | `34853` | gps ifd işaretçisi. |
| RowsPerStrip | `278` | Şerit başına satır sayısı. Bu, bir görüntü şeritlere bölündüğünde bir şeridin görüntüsündeki satır sayısıdır. |
| StripByteCounts | `279` | Her şeritteki toplam bayt sayısı. |
| PixelXDimension | `40962` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, dolgu verisi veya yeniden başlatma işareti olsun veya olmasın anlamlı görüntünün geçerli genişliği bu etikete kaydedilmelidir. |
| PixelYDimension | `40963` | Sıkıştırılmış verilere özel bilgiler. Sıkıştırılmış bir dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikete kaydedilmelidir |
| Gamma | `42240` | Gama değeri |
| SensitivityType | `34864` | Fotoğraf hassasiyeti türü |
| StandardOutputSensitivity | `34865` | camera standart çıkış hassasiyetini gösterir |
| RecommendedExposureIndex | `34866` | Önerilen maruz kalma indeksini gösterir |
| ISOSpeed | `34867` | ISO 12232 'de tanımlandığı şekliyle iso hız değeri hakkında bilgi |
| ISOSpeedLatitudeYYY | `34868` | Bu etiket, ISO 12232 'de tanımlandığı gibi ISO hız enlem yyy değerini gösterir. |
| ISOSpeedLatitudeZZZ | `34869` | Bu etiket, ISO 12232 'de tanımlandığı gibi ISO hız enlemi zzz değerini gösterir. |
| CameraOwnerName | `42032` | Kamera sahibinin adını içerir |
| BodySerialNumber | `42033` | Kamera gövdesi seri numarasını içerir |
| LensMake | `42035` | Bu etiket, lens üreticisini kaydeder |
| LensModel | `42036` | Bu etiket, lensin model adını ve model numarasını kaydeder |
| LensSerialNumber | `42037` | Bu etiket, değiştirilebilir lensin seri numarasını kaydeder |
| LensSpecification | `42034` | Bu etiket, minimum odak uzaklığını, maksimum odak uzunluğunu, minimum odak uzunluğunda minimum F sayısını ve maksimum odak uzunluğunda minimum F sayısını belirtir |

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
