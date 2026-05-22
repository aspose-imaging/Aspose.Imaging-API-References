---
title: "ExifProperties"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Exif etiketleri listesi"
type: docs
weight: 11
url: /tr/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Exif etiketleri listesi
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [ImageWidth](#ImageWidth) | Görüntü verisinin sütun sayısı, satır başına piksel sayısına eşittir. |
| [ImageLength](#ImageLength) | Görüntü verisinin satır sayısı. |
| [BitsPerSample](#BitsPerSample) | Görüntü bileşeni başına bit sayısı. |
| [Compression](#Compression) | Görüntü verisi için kullanılan sıkıştırma şeması. |
| [PhotometricInterpretation](#PhotometricInterpretation) | Piksel bileşimi. |
| [ImageDescription](#ImageDescription) | Görüntünün başlığını veren karakter dizgesi. |
| [Make](#Make) | Kayıt ekipmanının üreticisi. |
| [Model](#Model) | Ekipmanın model adı veya model numarası. |
| [Orientation](#Orientation) | Satır ve sütun açısından görüntü yönelimi. |
| [SamplesPerPixel](#SamplesPerPixel) | Piksel başına bileşen sayısı. |
| [XResolution](#XResolution) | ImageWidth yönünde ResolutionUnit başına piksel sayısı. |
| [YResolution](#YResolution) | ImageLength yönünde ResolutionUnit başına piksel sayısı. |
| [PlanarConfiguration](#PlanarConfiguration) | Piksel bileşenlerinin chunky ya da planar formatta kaydedilip kaydedilmediğini gösterir. |
| [ResolutionUnit](#ResolutionUnit) | XResolution ve YResolution ölçümü için birim. |
| [TransferFunction](#TransferFunction) | Tablo biçiminde tanımlanan görüntü için bir transfer fonksiyonu. |
| [Software](#Software) | Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılım veya firmware adını ve sürümünü kaydeder. |
| [DateTime](#DateTime) | Görüntünün oluşturulma tarihi ve saati. |
| [Artist](#Artist) | Bu etiket, kamera sahibi, fotoğrafçı veya görüntü oluşturucusunun adını kaydeder. |
| [WhitePoint](#WhitePoint) | Görüntünün beyaz noktasının kromatikliği. |
| [PrimaryChromaticities](#PrimaryChromaticities) | Görüntünün üç ana renginin kromatikliği. |
| [YCbCrCoefficients](#YCbCrCoefficients) | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranı. |
| [YCbCrPositioning](#YCbCrPositioning) | Krominans bileşenlerinin parlaklık bileşenine göre konumu. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Referans siyah nokta değeri ve referans beyaz nokta değeri. |
| [Copyright](#Copyright) | Telif hakkı bilgileri. |
| [ExposureTime](#ExposureTime) | Pozlama süresi, saniye cinsinden. |
| [FNumber](#FNumber) | F numarası. |
| [ExposureProgram](#ExposureProgram) | Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan program sınıfı. |
| [SpectralSensitivity](#SpectralSensitivity) | Kullanılan kameranın her kanalının spektral duyarlılığını gösterir. |
| [PhotographicSensitivity](#PhotographicSensitivity) | ISO 12232'de belirtildiği gibi kameranın veya giriş cihazının ISO Hızı ve ISO Enlemini gösterir. |
| [OECF](#OECF) | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) gösterir. |
| [ExifVersion](#ExifVersion) | Exif sürümü. |
| [DateTimeOriginal](#DateTimeOriginal) | Orijinal görüntü verisinin oluşturulduğu tarih ve saat. |
| [DateTimeDigitized](#DateTimeDigitized) | Dijitalleştirilen tarih ve saat. |
| [ComponentsConfiguration](#ComponentsConfiguration) | Bileşenlerin yapılandırması. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Sıkıştırılmış verilere özgüdür; piksel başına sıkıştırılmış bit sayısını belirtir. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Deklanşör hızı değeri. |
| [ApertureValue](#ApertureValue) | Lens diyafram değeri. |
| [BrightnessValue](#BrightnessValue) | Parlaklık değeri. |
| [ExposureBiasValue](#ExposureBiasValue) | Pozlama sapma değeri. |
| [MaxApertureValue](#MaxApertureValue) | Maksimum diyafram değeri. |
| [SubjectDistance](#SubjectDistance) | Özneye olan mesafe, metre cinsinden. |
| [MeteringMode](#MeteringMode) | Ölçüm modu. |
| [LightSource](#LightSource) | Işık kaynağı türü. |
| [Flash](#Flash) | Görüntünün çekildiği anda flaş durumunu gösterir. |
| [FocalLength](#FocalLength) | Lensin gerçek odak uzaklığı, mm cinsinden. |
| [SubjectArea](#SubjectArea) | Bu etiket, genel sahnedeki ana konunun konumunu ve alanını gösterir. |
| [MakerNote](#MakerNote) | Exif yazarları üretenler için istenen bilgileri kaydetmek amacıyla bir etiket. |
| [UserComment](#UserComment) | Exif kullanıcılarının ImageDescription etiketindeki anahtar kelimeler ve yorumların yanı sıra görüntüye ek anahtar kelime veya yorum yazabilmesi ve ImageDescription etiketinin karakter kodu sınırlamaları olmadan bir etiket. |
| [SubsecTime](#SubsecTime) | DateTime etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | DateTimeOriginal etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | DateTimeDigitized etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket. |
| [FlashpixVersion](#FlashpixVersion) | Bir FPXR dosyası tarafından desteklenen Flashpix format sürümü. |
| [ColorSpace](#ColorSpace) | Renk uzayı bilgi etiketi (ColorSpace) her zaman renk uzayı belirteci olarak kaydedilir. |
| [RelatedSoundFile](#RelatedSoundFile) | İlgili ses dosyası. |
| [FlashEnergy](#FlashEnergy) | Görüntünün yakalandığı anda ışık patlaması enerjisini, Beam Candle Power Seconds (BCPS) cinsinden gösterir. |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Bu etiket, ISO 12233'te belirtildiği gibi, kamera veya giriş cihazının uzaysal frekans tablosunu ve SFR değerlerini görüntü genişliği, görüntü yüksekliği ve diyagonal yönde kaydeder. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını gösterir. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | FocalPlaneXResolution ve FocalPlaneYResolution ölçümü için kullanılan birimi gösterir. |
| [SubjectLocation](#SubjectLocation) | Sahnede ana konunun konumunu gösterir. |
| [ExposureIndex](#ExposureIndex) | Görüntünün yakalandığı anda kamera veya giriş cihazında seçilen pozlama indeksini gösterir. |
| [SensingMethod](#SensingMethod) | Kamera veya giriş cihazındaki görüntü sensörü tipini gösterir. |
| [FileSource](#FileSource) | Dosya kaynağı. |
| [SceneType](#SceneType) | Sahne tipini gösterir. |
| [CFAPattern](#CFAPattern) | Tek çipli renk alan sensörü kullanıldığında görüntü sensörünün renk filtre dizisi (CFA) geometrik desenini gösterir. |
| [CustomRendered](#CustomRendered) | Bu etiket, çıktı yönünde işlenmeye yönelik özel işleme kullanımını gösterir. |
| [ExposureMode](#ExposureMode) | Bu etiket, görüntünün çekildiği anda ayarlanan pozlama modunu gösterir. |
| [WhiteBalance](#WhiteBalance) | Bu etiket, görüntünün çekildiği anda ayarlanan beyaz dengesi modunu gösterir. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Bu etiket, görüntünün çekildiği sırada dijital yakınlaştırma oranını gösterir. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Bu etiket, 35 mm film kamera varsayımıyla eşdeğer odak uzaklığını milimetre cinsinden gösterir. |
| [SceneCaptureType](#SceneCaptureType) | Bu etiket, çekilen sahnenin türünü gösterir. |
| [GainControl](#GainControl) | Bu etiket, genel görüntü kazanç ayarının derecesini gösterir. |
| [Contrast](#Contrast) | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan kontrast işleme yönünü gösterir. |
| [Saturation](#Saturation) | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan doygunluk işleme yönünü gösterir. |
| [Sharpness](#Sharpness) | Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan keskinlik işleme yönünü gösterir |
| [DeviceSettingDescription](#DeviceSettingDescription) | Bu etiket, belirli bir kamera modelinin fotoğraf çekim koşulları hakkında bilgi gösterir. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Bu etiket, nesneye olan mesafeyi gösterir. |
| [ImageUniqueID](#ImageUniqueID) | Görüntünün benzersiz kimliği. |
| [GPSVersionID](#GPSVersionID) | GPSInfoIFD sürümünü gösterir. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Enlemin kuzey mi yoksa güney mi olduğunu gösterir. |
| [GPSLatitude](#GPSLatitude) | Enlemi gösterir. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Boylamın doğu mu yoksa batı mı olduğunu gösterir. |
| [GPSLongitude](#GPSLongitude) | Boylamı gösterir. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Referans irtifa olarak kullanılan yüksekliği gösterir. |
| [GPSAltitude](#GPSAltitude) | GPSAltitudeRef referansına göre yüksekliği gösterir. |
| [GPSTimestamp](#GPSTimestamp) | Zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak gösterir. |
| [GPSSatellites](#GPSSatellites) | Ölçümler için kullanılan GPS uydularını gösterir. |
| [GPSStatus](#GPSStatus) | Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir. |
| [GPSMeasureMode](#GPSMeasureMode) | GPS ölçüm modunu gösterir. |
| [GPSDOP](#GPSDOP) | GPS DOP (veri kesinlik derecesi) değerini gösterir. |
| [GPSSpeedRef](#GPSSpeedRef) | GPS alıcısının hareket hızı ifadesinde kullanılan birimi gösterir. |
| [GPSSpeed](#GPSSpeed) | GPS alıcısının hareket hızını gösterir. |
| [GPSTrackRef](#GPSTrackRef) | GPS alıcısının hareket yönünü vermek için referansı gösterir. |
| [GPSTrack](#GPSTrack) | GPS alıcısının hareket yönünü gösterir. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Görüntünün çekildiği sırada yönünün verilmesi için referansı gösterir. |
| [GPSImgDirection](#GPSImgDirection) | Görüntünün çekildiği yönü gösterir. |
| [GPSMapDatum](#GPSMapDatum) | GPS alıcısı tarafından kullanılan jeodezik ölçüm verilerini gösterir. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösterir. |
| [GPSDestLatitude](#GPSDestLatitude) | Hedef noktanın enlemini gösterir. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösterir. |
| [GPSDestLongitude](#GPSDestLongitude) | Hedef noktanın boylamını gösterir. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Hedef noktaya yön vermek için kullanılan referansı gösterir. |
| [GPSDestBearing](#GPSDestBearing) | Hedef noktaya yönü gösterir. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Hedef noktaya olan mesafeyi ifade etmek için kullanılan birimi gösterir. |
| [GPSDestDistance](#GPSDestDistance) | Hedef noktaya olan mesafeyi gösterir. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizesi. |
| [GPSAreaInformation](#GPSAreaInformation) | GPS bölgesinin adını kaydeden bir karakter dizesi. |
| [GPSDateStamp](#GPSDateStamp) | UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden bir karakter dizesi. |
| [GPSDifferential](#GPSDifferential) | GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir. |
| [StripOffsets](#StripOffsets) | Her şerit için, o şeridin bayt ofsetini gösterir. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | JPEG sıkıştırmalı küçük resim verisinin başlangıç baytına (SOI) ofseti gösterir. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | JPEG sıkıştırmalı küçük resim verisinin bayt sayısını gösterir. |
| [ExifIfdPointer](#ExifIfdPointer) | Exif IFD'ye bir işaretçi. |
| [GPSIfdPointer](#GPSIfdPointer) | gps ifd işaretçisi. |
| [RowsPerStrip](#RowsPerStrip) | Şerit başına satır sayısını gösterir. |
| [StripByteCounts](#StripByteCounts) | Her şeritteki toplam bayt sayısını gösterir. |
| [PixelXDimension](#PixelXDimension) | Sıkıştırılmış veriye özgü bilgi. |
| [PixelYDimension](#PixelYDimension) | Sıkıştırılmış veriye özgü bilgi. |
| [Gamma](#Gamma) | Gamma değeri |
| [SensitivityType](#SensitivityType) | Fotografik duyarlılık türü |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Kameranın standart çıkış duyarlılığını gösterir |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Önerilen pozlama indeksini gösterir |
| [ISOSpeed](#ISOSpeed) | ISO 12232'de tanımlanan ISO hız değeri hakkında bilgi |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi yyy değerini gösterir |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi zzz değerini gösterir |
| [CameraOwnerName](#CameraOwnerName) | Kamera sahibinin adını içerir |
| [BodySerialNumber](#BodySerialNumber) | Kamera gövdesi seri numarasını içerir |
| [LensMake](#LensMake) | Bu etiket lens üreticisini kaydeder |
| [LensModel](#LensModel) | Bu etiket lens\`in model adını ve model numarasını kaydeder |
| [LensSerialNumber](#LensSerialNumber) | Bu etiket değiştirilebilir lensin seri numarasını kaydeder |
| [LensSpecification](#LensSpecification) | Bu etiket minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığındaki minimum F sayısını ve maksimum odak uzaklığındaki minimum F sayısını not eder |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Görüntü verisinin sütun sayısı, satır başına piksel sayısına eşittir.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Görüntü verisinin satır sayısı.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Görüntü bileşeni başına bit sayısı. Bu standartta görüntünün her bileşeni 8 bitten oluşur, bu yüzden bu etiketin değeri 8'dir.

### Compression {#Compression}
```
public static final int Compression
```


Görüntü verileri için kullanılan sıkıştırma şeması. Birincil görüntü JPEG sıkıştırmasıyla kaydedildiğinde, bu gösterim gerekli değildir ve atlanır.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


Piksel bileşimi.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Görüntünün başlığını veren bir karakter dizisi. "1988 şirket pikniği" gibi bir yorum olabilir.

### Make {#Make}
```
public static final int Make
```


Kayıt ekipmanının üreticisi. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın üreticisidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir.

### Model {#Model}
```
public static final int Model
```


Ekipmanın model adı veya model numarası. Bu, görüntüyü oluşturan DSC, tarayıcı, video dijitalleştirici veya diğer ekipmanın model adı veya numarasıdır. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir.

### Orientation {#Orientation}
```
public static final int Orientation
```


Satır ve sütun açısından görüntü yönelimi.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Piksel başına bileşen sayısı. Bu standart RGB ve YCbCr görüntülerine uygulandığından, bu etiket için ayarlanan değer 3'tür.

### XResolution {#XResolution}
```
public static final int XResolution
```


ImageWidth yönünde ResolutionUnit başına piksel sayısı. Görüntü çözünürlüğü bilinmiyorsa, 72 [dpi] atanır.

### YResolution {#YResolution}
```
public static final int YResolution
```


ImageLength yönünde ResolutionUnit başına piksel sayısı. XResolution ile aynı değer atanır.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Piksel bileşenlerinin chunky (parçalı) ya da planar (düzlemsel) formatta kaydedilip kaydedilmediğini gösterir. Bu alan yoksa, TIFF varsayılanı 1 (parçalı) kabul edilir.

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


XResolution ve YResolution ölçümü için birim. Hem XResolution hem de YResolution için aynı birim kullanılır. Görüntü çözünürlüğü bilinmiyorsa, 2 (inç) atanır.

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Görüntü için tablo biçiminde tanımlanan bir transfer fonksiyonu. Normalde bu etiket gerekli değildir, çünkü renk uzayı renk uzayı bilgisi ColorSpace etiketinde belirtilir.

### Software {#Software}
```
public static final int Software
```


Bu etiket, görüntüyü oluşturmak için kullanılan kamera veya görüntü giriş cihazının yazılım veya firmware'inin adını ve sürümünü kaydeder. Ayrıntılı format belirtilmemiştir, ancak aşağıdaki örnek takip edilmelidir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir.

### DateTime {#DateTime}
```
public static final int DateTime
```


Görüntünün oluşturulma tarihi ve saati. Exif standardında, dosyanın değiştirildiği tarih ve saat olarak kabul edilir.

### Artist {#Artist}
```
public static final int Artist
```


Bu etiket, kamera sahibi, fotoğrafçı veya görüntü oluşturucusunun adını kaydeder. Ayrıntılı format belirtilmemiştir, ancak birlikte çalışabilirliği kolaylaştırmak için aşağıdaki örnekteki gibi bilgi yazılması önerilir. Alan boş bırakıldığında, bilinmeyen olarak kabul edilir. (Ör. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


The chromaticity of the white point of the image. Normally this tag is not necessary, since color space is specified in the colorspace information ColorSpace tag.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


The chromaticity of the three primary colors of the image. Normally this tag is not necessary, since colorspace is specified in the colorspace information ColorSpace tag.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Krominans bileşenlerinin parlaklık bileşenine göre örnekleme oranı.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


The position of chrominance components in relation to the luminance component. This field is designated only for JPEG compressed data or uncompressed YCbCr data. The TIFF default is 1 (centered); but when Y:Cb:Cr = 4:2:2 it is recommended in this standard that 2 (co-sited) be used to record data, in order to improve the image quality when viewed on TV systems. When this field does not exist, the reader shall assume the TIFF default. In the case of Y:Cb:Cr = 4:2:0, the TIFF default (centered) is recommended. If the reader does not have the capability of supporting both kinds of YCbCrPositioning, it shall follow the TIFF default regardless of the value in this field. It is preferable that readers \" hem ortalanmış hem de yan yana konumlandırmayı destekleyebilmeli\".

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


The reference black point value and reference white point value. No defaults are given in TIFF, but the values below are given as defaults here. The color space is declared in a color space information tag, with the default being the value that gives the optimal image characteristics Interoperability these conditions

### Copyright {#Copyright}
```
public static final int Copyright
```


Copyright information. In this standard the tag is used to indicate both the photographer and editor copyrights. It is the copyright notice of the person or organization claiming rights to the image. The Interoperability copyright statement including date and rights should be written in this field; e.g., \"Copyright, John Smith, 19xx. All rights reserved.\" In this standard the field records both the photographer and editor copyrights, with each recorded in a separate part of the statement. When there is a clear distinction between the photographer and editor copyrights, these are to be written in the order of photographer followed by editor copyright, separated by NULL (in this case since the statement also ends with a NULL, there are two NULL codes). When only the photographer copyright is given, it is terminated by one NULL code . When only the editor copyright is given, the photographer copyright part consists of one space followed by a terminating NULL code, then the editor copyright is given. When the field is left blank, it is treated as unknown.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Pozlama süresi, saniye cinsinden.

### FNumber {#FNumber}
```
public static final int FNumber
```


F numarası.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


Fotoğraf çekildiğinde pozlamayı ayarlamak için kamera tarafından kullanılan program sınıfı.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Kullanılan kameranın her kanalının spektral duyarlılığını gösterir.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


ISO 12232'de belirtildiği gibi kameranın veya giriş cihazının ISO Hızı ve ISO Enlemini gösterir.

### OECF {#OECF}
```
public static final int OECF
```


ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) gösterir.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


Exif sürümü.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


Orijinal görüntü verisinin oluşturulduğu tarih ve saat.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


Dijitalleştirilen tarih ve saat.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


Bileşenlerin yapılandırması.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Sıkıştırılmış verilere özgüdür; piksel başına sıkıştırılmış bit sayısını belirtir.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Deklanşör hızı değeri.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Lens diyafram değeri.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Parlaklık değeri.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Pozlama sapma değeri.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Maksimum diyafram değeri.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


Özneye olan mesafe, metre cinsinden.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


Ölçüm modu.

### LightSource {#LightSource}
```
public static final int LightSource
```


Işık kaynağı türü.

### Flash {#Flash}
```
public static final int Flash
```


Görüntünün çekildiği anda flaş durumunu gösterir.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


Lensin gerçek odak uzaklığı, mm cinsinden.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Bu etiket, genel sahnedeki ana konunun konumunu ve alanını gösterir.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


A tag for manufacturers of Exif writers to record any desired information. The contents are up to the manufacturer, but this tag should not be used for any other than its intended purpose.

### UserComment {#UserComment}
```
public static final int UserComment
```


Exif kullanıcılarının ImageDescription etiketindeki anahtar kelimeler ve yorumların yanı sıra görüntüye ek anahtar kelime veya yorum yazabilmesi ve ImageDescription etiketinin karakter kodu sınırlamaları olmadan bir etiket.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


DateTime etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


DateTimeOriginal etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


DateTimeDigitized etiketi için saniyenin kesirlerini kaydetmek amacıyla kullanılan bir etiket.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


Bir FPXR dosyası tarafından desteklenen Flashpix format sürümü.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Renk uzayı bilgi etiketi (ColorSpace) her zaman renk uzayı belirteci olarak kaydedilir.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


İlgili ses dosyası.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Görüntünün yakalandığı anda ışık patlaması enerjisini, Beam Candle Power Seconds (BCPS) cinsinden gösterir.

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Bu etiket, ISO 12233'te belirtildiği gibi, kamera veya giriş cihazının uzaysal frekans tablosunu ve SFR değerlerini görüntü genişliği, görüntü yüksekliği ve diyagonal yönde kaydeder.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü genişliği (X) yönündeki piksel sayısını gösterir.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Kamera odak düzlemindeki FocalPlaneResolutionUnit başına görüntü yüksekliği (Y) yönündeki piksel sayısını gösterir.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indicates the unit for measuring FocalPlaneXResolution and FocalPlaneYResolution. This value is the same as the ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indicates the location of the main subject in the scene. The value of this tag represents the pixel at the center of the main subject relative to the left edge, prior to rotation processing as per the Rotation tag.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Görüntünün yakalandığı anda kamera veya giriş cihazında seçilen pozlama indeksini gösterir.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Kamera veya giriş cihazındaki görüntü sensörü tipini gösterir.

### FileSource {#FileSource}
```
public static final int FileSource
```


Dosya kaynağı.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indicates the type of scene. If a DSC recorded the image, this tag value shall always be set to 1, indicating that the image was directly photographed.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indicates the color filter array (CFA) geometric pattern of the image sensor when a one-chip color area sensor is used. It does not apply to all sensing methods.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


This tag indicates the use of special processing on image data, such as rendering geared to output. When special processing is performed, the reader is expected to disable or minimize any further processing.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


This tag indicates the exposure mode set when the image was shot. In auto-bracketing mode, the camera shoots a series of frames of the same scene at different exposure settings.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Bu etiket, görüntünün çekildiği anda ayarlanan beyaz dengesi modunu gösterir.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


This tag indicates the digital zoom ratio when the image was shot. If the numerator of the recorded value is 0, this indicates that digital zoom was not used.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


This tag indicates the equivalent focal length assuming a 35mm film camera, in mm. A value of 0 means the focal length is unknown. Note that this tag differs from the FocalLength tag.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


This tag indicates the type of scene that was shot. It can also be used to record the mode in which the image was shot.

### GainControl {#GainControl}
```
public static final int GainControl
```


Bu etiket, genel görüntü kazanç ayarının derecesini gösterir.

### Contrast {#Contrast}
```
public static final int Contrast
```


Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan kontrast işleme yönünü gösterir.

### Saturation {#Saturation}
```
public static final int Saturation
```


Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan doygunluk işleme yönünü gösterir.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Bu etiket, görüntünün çekildiği sırada kamera tarafından uygulanan keskinlik işleme yönünü gösterir

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


This tag indicates information on the picture-taking conditions of a particular camera model. The tag is used only to indicate the picture-taking conditions in the reader.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Bu etiket, nesneye olan mesafeyi gösterir.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


Görüntünün benzersiz kimliği.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


GPSInfoIFD sürümünü gösterir.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Enlemin kuzey mi yoksa güney mi olduğunu gösterir.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indicates the latitude. The latitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If latitude is expressed as degrees, minutes and seconds, a typical format would be dd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Boylamın doğu mu yoksa batı mı olduğunu gösterir.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indicates the longitude. The longitude is expressed as three RATIONAL values giving the degrees, minutes, and seconds, respectively. If longitude is expressed as degrees, minutes and seconds, a typical format would be ddd/1,mm/1,ss/1. When degrees and minutes are used and, for example, fractions of minutes are given up to two decimal places, the format would be ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indicates the altitude used as the reference altitude. If the reference is sea level and the altitude is above sea level, 0 is given. If the altitude is below sea level, a value of 1 is given and the altitude is indicated as an absolute value in the GPSAltitude tag.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indicates the altitude based on the reference in GPSAltitudeRef. Altitude is expressed as one RATIONAL value. The reference unit is meters.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indicates the time as UTC (Coordinated Universal Time). TimeStamp is expressed as three RATIONAL values giving the hour, minute, and second.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indicates the GPS satellites used for measurements. This tag can be used to describe the number of satellites, their ID number, angle of elevation, azimuth, SNR and other information in ASCII notation. The format is not specified. If the GPS receiver is incapable of taking measurements, value of the tag shall be set to NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Görüntü kaydedildiğinde GPS alıcısının durumunu gösterir.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indicates the GPS measurement mode. - 2- or 3-dimensional.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indicates the GPS DOP (data degree of precision). An HDOP value is written during two-dimensional measurement, and PDOP during three-dimensional measurement.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indicates the unit used to express the GPS receiver speed of movement. 'K' 'M' and 'N' represents kilometers per hour, miles per hour, and knots.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


GPS alıcısının hareket hızını gösterir.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


GPS alıcı hareket yönünü vermek için referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


GPS alıcı hareket yönünü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Fotoğraf çekildiğinde görüntünün yönünü vermek için referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Fotoğraf çekildiğinde görüntünün yönünü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


GPS alıcısı tarafından kullanılan jeodezik ölçüm verilerini gösterir.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösterir. ASCII değeri 'N' kuzey enlemini, 'S' ise güney enlemini gösterir.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Hedef noktanın enlemini gösterir. Enlem, derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir. Enlem derece, dakika ve saniye olarak ifade edilirse tipik format dd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde format dd/1,mmmm/100,0/1 olur.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösterir. ASCII 'E' doğu boylamını, 'W' ise batı boylamını gösterir.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Hedef noktanın boylamını gösterir. Boylam, derece, dakika ve saniyeyi veren üç RATIONAL değer olarak ifade edilir. Boylam derece, dakika ve saniye olarak ifade edilirse tipik format ddd/1,mm/1,ss/1 olur. Derece ve dakika kullanıldığında ve örneğin dakikanın kesirli kısmı iki ondalık basamağa kadar verildiğinde format ddd/1,mmmm/100,0/1 olur.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Hedef noktasına yön verme için kullanılan referansı gösterir. 'T' gerçek yönü, 'M' ise manyetik yönü gösterir.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Hedef noktasına yönü gösterir. Değer aralığı 0.00 ile 359.99 arasındadır.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Hedef noktasına olan mesafeyi ifade etmek için kullanılan birimi gösterir. 'K', 'M' ve 'N' sırasıyla kilometre, mil ve knot anlamına gelir.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Hedef noktaya olan mesafeyi gösterir.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Konum bulma için kullanılan yöntemin adını kaydeden bir karakter dizesi. İlk bayt kullanılan karakter kodunu gösterir ve ardından yöntemin adı gelir.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


GPS bölgesinin adını kaydeden bir karakter dizesi. İlk bayt kullanılan karakter kodunu gösterir ve ardından GPS bölgesinin adı gelir.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgisini kaydeden bir karakter dizesi. Format YYYY:MM:DD şeklindedir.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


GPS alıcısına diferansiyel düzeltmenin uygulanıp uygulanmadığını gösterir.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Her şerit için, o şeridin bayt ofseti. Şerit bayt sayısının 64 KByte'ı aşmaması için seçilmesi önerilir. Aux etiketi.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


JPEG sıkıştırmalı küçük resim verisinin başlangıç baytına (SOI) ofset. Bu, birincil görüntü JPEG verisi için kullanılmaz.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


JPEG sıkıştırmalı küçük resim verisinin bayt sayısı. Bu, birincil görüntü JPEG verisi için kullanılmaz. JPEG küçük resimler bölünmez, SOI'den EOI'ye kadar sürekli bir JPEG bit akışı olarak kaydedilir. Appn ve COM işaretçileri kaydedilmemelidir. Sıkıştırılmış küçük resimler, APP1'de kaydedilecek diğer tüm veriler dahil olmak üzere 64 KByte'ı geçmemelidir.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Exif IFD'ye bir işaretçi. Interoperability, Exif IFD, TIFF'te belirtilen IFD ile aynı yapıya sahiptir. Ancak genellikle TIFF'teki gibi görüntü verisi içermez.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


gps ifd işaretçisi.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Şerit başına satır sayısı. Görüntü şeritlere bölündüğünde bir şeritteki satır sayısını ifade eder.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Her şeritteki toplam bayt sayısını gösterir.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Sıkıştırılmış veriye özgü bilgi. Sıkıştırılmış bir dosya kaydedildiğinde, dolgu verisi veya yeniden başlatma işareti olsun, anlamlı görüntünün geçerli genişliği bu etikette kaydedilir.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Sıkıştırılmış veriye özgü bilgi. Sıkıştırılmış bir dosya kaydedildiğinde, anlamlı görüntünün geçerli yüksekliği bu etikette kaydedilir.

### Gamma {#Gamma}
```
public static final int Gamma
```


Gamma değeri

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Fotografik duyarlılık türü

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Kameranın standart çıkış duyarlılığını gösterir

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Önerilen pozlama indeksini gösterir

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


ISO 12232'de tanımlanan ISO hız değeri hakkında bilgi

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi yyy değerini gösterir

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Bu etiket, ISO 12232'de tanımlanan ISO hız enlemi zzz değerini gösterir

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Kamera sahibinin adını içerir

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Kamera gövdesi seri numarasını içerir

### LensMake {#LensMake}
```
public static final int LensMake
```


Bu etiket lens üreticisini kaydeder

### LensModel {#LensModel}
```
public static final int LensModel
```


Bu etiket lens\`in model adını ve model numarasını kaydeder

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Bu etiket değiştirilebilir lensin seri numarasını kaydeder

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Bu etiket minimum odak uzaklığını, maksimum odak uzaklığını, minimum odak uzaklığındaki minimum F sayısını ve maksimum odak uzaklığındaki minimum F sayısını not eder

