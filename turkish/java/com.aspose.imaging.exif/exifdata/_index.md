---
title: "ExifData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EXIF veri kapsayıcısı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.exif/exifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller)

**All Implemented Interfaces:**
[com.aspose.imaging.metadata.IImageMetadataFormat](../../com.aspose.imaging.metadata/iimagemetadataformat)
```
public class ExifData extends TiffDataTypeController implements IImageMetadataFormat
```

EXIF veri kapsayıcısı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ExifData()](#ExifData--) | Yeni bir `ExifData` sınıfı örneği başlatır. |
| [ExifData(TiffDataType[] exifdata)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Diziden gelen veriyle yeni bir `ExifData` sınıfı örneği başlatır. |
| [ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Diziden gelen veriyle yeni bir `ExifData` sınıfı örneği başlatır. |
| [ExifData(ExifData exifdata)](#ExifData-com.aspose.imaging.exif.ExifData-) | Diziden gelen veriyle yeni bir [ExifData](../../com.aspose.imaging.exif/exifdata) sınıfı örneği başlatır. |
| [ExifData(byte[] binaryData)](#ExifData-byte---) | Yeni bir [ExifData](../../com.aspose.imaging.exif/exifdata) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isBigEndian()](#isBigEndian--) | Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBigEndian(boolean value)](#setBigEndian-boolean-) | Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getMake()](#getMake--) | Kayıt ekipmanının üreticisini alır. |
| [setMake(String value)](#setMake-java.lang.String-) | Kayıt ekipmanının üreticisini ayarlar. |
| [getApertureValue()](#getApertureValue--) | Diyafram değerini alır veya ayarlar. |
| [setApertureValue(TiffRational value)](#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Diyafram değerini alır veya ayarlar. |
| [getBodySerialNumber()](#getBodySerialNumber--) | Kamera gövdesi seri numarasını alır veya ayarlar. |
| [setBodySerialNumber(String value)](#setBodySerialNumber-java.lang.String-) | Kamera gövdesi seri numarasını alır veya ayarlar. |
| [getBrightnessValue()](#getBrightnessValue--) | Parlaklık değerini alır veya ayarlar. |
| [setBrightnessValue(TiffSRational value)](#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Parlaklık değerini alır veya ayarlar. |
| [getCFAPattern()](#getCFAPattern--) | CFA desenini alır veya ayarlar. |
| [setCFAPattern(byte[] value)](#setCFAPattern-byte---) | CFA desenini alır veya ayarlar. |
| [getCameraOwnerName()](#getCameraOwnerName--) | Kamera sahibi adını alır veya ayarlar |
| [setCameraOwnerName(String value)](#setCameraOwnerName-java.lang.String-) | Kamera sahibi adını alır veya ayarlar |
| [getColorSpace()](#getColorSpace--) | Renk uzayını alır veya ayarlar. |
| [setColorSpace(int value)](#setColorSpace-int-) | Renk uzayını alır veya ayarlar. |
| [getComponentsConfiguration()](#getComponentsConfiguration--) | Bileşen yapılandırmasını alır veya ayarlar. |
| [setComponentsConfiguration(byte[] value)](#setComponentsConfiguration-byte---) | Bileşen yapılandırmasını alır veya ayarlar. |
| [getCompressedBitsPerPixel()](#getCompressedBitsPerPixel--) | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| [setCompressedBitsPerPixel(TiffRational value)](#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-) | Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar. |
| [getContrast()](#getContrast--) | Kontrastı alır veya ayarlar. |
| [setContrast(int value)](#setContrast-int-) | Kontrastı alır veya ayarlar. |
| [getCustomRendered()](#getCustomRendered--) | Özel işlenmişi alır veya ayarlar. |
| [setCustomRendered(int value)](#setCustomRendered-int-) | Özel işlenmişi alır veya ayarlar. |
| [getDateTimeDigitized()](#getDateTimeDigitized--) | Dijitalleştirilme tarih ve saatini alır veya ayarlar. |
| [setDateTimeDigitized(String value)](#setDateTimeDigitized-java.lang.String-) | Dijitalleştirilme tarih ve saatini alır veya ayarlar. |
| [getDateTimeOriginal()](#getDateTimeOriginal--) | Orijinal tarih ve saatini alır veya ayarlar. |
| [setDateTimeOriginal(String value)](#setDateTimeOriginal-java.lang.String-) | Orijinal tarih ve saatini alır veya ayarlar. |
| [getDeviceSettingDescription()](#getDeviceSettingDescription--) | Aygıt ayarları açıklamasını alır veya ayarlar. |
| [setDeviceSettingDescription(byte[] value)](#setDeviceSettingDescription-byte---) | Aygıt ayarları açıklamasını alır veya ayarlar. |
| [getDigitalZoomRatio()](#getDigitalZoomRatio--) | Dijital yakınlaştırma oranını alır veya ayarlar. |
| [setDigitalZoomRatio(TiffRational value)](#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-) | Dijital yakınlaştırma oranını alır veya ayarlar. |
| [getExifVersion()](#getExifVersion--) | EXIF sürümünü alır veya ayarlar. |
| [setExifVersion(byte[] value)](#setExifVersion-byte---) | EXIF sürümünü alır veya ayarlar. |
| [getExposureBiasValue()](#getExposureBiasValue--) | Pozlama sapma değerini alır veya ayarlar. |
| [setExposureBiasValue(TiffSRational value)](#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Pozlama sapma değerini alır veya ayarlar. |
| [getExposureIndex()](#getExposureIndex--) | Pozlama indeksini alır veya ayarlar. |
| [setExposureIndex(TiffRational value)](#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-) | Pozlama indeksini alır veya ayarlar. |
| [getExposureMode()](#getExposureMode--) | Pozlama modunu alır veya ayarlar. |
| [setExposureMode(int value)](#setExposureMode-int-) | Pozlama modunu alır veya ayarlar. |
| [getExposureProgram()](#getExposureProgram--) | Pozlama programını alır veya ayarlar. |
| [setExposureProgram(int value)](#setExposureProgram-int-) | Pozlama programını alır veya ayarlar. |
| [getExposureTime()](#getExposureTime--) | Pozlama süresini alır veya ayarlar. |
| [setExposureTime(TiffRational value)](#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-) | Pozlama süresini alır veya ayarlar. |
| [getFNumber()](#getFNumber--) | F-numarasını alır veya ayarlar. |
| [setFNumber(TiffRational value)](#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-) | F-numarasını alır veya ayarlar. |
| [getFileSource()](#getFileSource--) | Dosya kaynağı türünü alır veya ayarlar. |
| [setFileSource(byte value)](#setFileSource-byte-) | Dosya kaynağı türünü alır veya ayarlar. |
| [getFlash()](#getFlash--) | Flaş'ı alır veya ayarlar. |
| [setFlash(int value)](#setFlash-int-) | Flaş'ı alır veya ayarlar. |
| [getFlashEnergy()](#getFlashEnergy--) | Flaş enerjisini alır veya ayarlar. |
| [setFlashEnergy(TiffRational value)](#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-) | Flaş enerjisini alır veya ayarlar. |
| [getFlashpixVersion()](#getFlashpixVersion--) | Flaş piksel sürümünü alır veya ayarlar. |
| [setFlashpixVersion(byte[] value)](#setFlashpixVersion-byte---) | Flaş piksel sürümünü alır veya ayarlar. |
| [getFocalLength()](#getFocalLength--) | Odak uzaklığını alır veya ayarlar. |
| [setFocalLength(TiffRational value)](#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-) | Odak uzaklığını alır veya ayarlar. |
| [getFocalLengthIn35MmFilm()](#getFocalLengthIn35MmFilm--) | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| [setFocalLengthIn35MmFilm(int value)](#setFocalLengthIn35MmFilm-int-) | 35 mm filmde odak uzaklığını alır veya ayarlar. |
| [getFocalPlaneResolutionUnit()](#getFocalPlaneResolutionUnit--) | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| [setFocalPlaneResolutionUnit(int value)](#setFocalPlaneResolutionUnit-int-) | Odak düzlemi çözünürlük birimini alır veya ayarlar. |
| [getFocalPlaneXResolution()](#getFocalPlaneXResolution--) | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| [setFocalPlaneXResolution(TiffRational value)](#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Odak düzlemi x çözünürlüğünü alır veya ayarlar. |
| [getFocalPlaneYResolution()](#getFocalPlaneYResolution--) | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| [setFocalPlaneYResolution(TiffRational value)](#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Odak düzlemi y çözünürlüğünü alır veya ayarlar. |
| [getGPSAltitude()](#getGPSAltitude--) | GPS yüksekliğini alır veya ayarlar. |
| [setGPSAltitude(TiffRational value)](#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-) | GPS yüksekliğini alır veya ayarlar. |
| [getGPSAltitudeRef()](#getGPSAltitudeRef--) | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| [setGPSAltitudeRef(byte value)](#setGPSAltitudeRef-byte-) | Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar. |
| [getGPSAreaInformation()](#getGPSAreaInformation--) | GPS alan bilgilerini alır veya ayarlar. |
| [setGPSAreaInformation(byte[] value)](#setGPSAreaInformation-byte---) | GPS alan bilgilerini alır veya ayarlar. |
| [getGPSDOP()](#getGPSDOP--) | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| [setGPSDOP(TiffRational value)](#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-) | GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar. |
| [getGPSDestBearing()](#getGPSDestBearing--) | Hedef noktaya olan GPS yönünü alır veya ayarlar. |
| [setGPSDestBearing(TiffRational value)](#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hedef noktaya olan GPS yönünü alır veya ayarlar. |
| [getGPSDestBearingRef()](#getGPSDestBearingRef--) | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [setGPSDestBearingRef(String value)](#setGPSDestBearingRef-java.lang.String-) | Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [getGPSDestDistance()](#getGPSDestDistance--) | Hedef noktaya olan GPS mesafesini alır veya ayarlar. |
| [setGPSDestDistance(TiffRational value)](#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Hedef noktaya olan GPS mesafesini alır veya ayarlar. |
| [getGPSDestDistanceRef()](#getGPSDestDistanceRef--) | Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| [setGPSDestDistanceRef(String value)](#setGPSDestDistanceRef-java.lang.String-) | Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar. |
| [getGPSDestLatitude()](#getGPSDestLatitude--) | Hedef noktanın GPS enlem değerini alır veya ayarlar. |
| [setGPSDestLatitude(TiffRational[] value)](#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hedef noktanın GPS enlem değerini alır veya ayarlar. |
| [getGPSDestLatitudeRef()](#getGPSDestLatitudeRef--) | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| [setGPSDestLatitudeRef(String value)](#setGPSDestLatitudeRef-java.lang.String-) | Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar. |
| [getGPSDestLongitude()](#getGPSDestLongitude--) | Hedef noktanın GPS boylam değerini alır veya ayarlar. |
| [setGPSDestLongitude(TiffRational[] value)](#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | Hedef noktanın GPS boylam değerini alır veya ayarlar. |
| [getGPSDestLongitudeRef()](#getGPSDestLongitudeRef--) | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| [setGPSDestLongitudeRef(String value)](#setGPSDestLongitudeRef-java.lang.String-) | Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar. |
| [getGPSDifferential()](#getGPSDifferential--) | GPS alıcıya diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| [setGPSDifferential(int value)](#setGPSDifferential-int-) | GPS alıcıya diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar. |
| [getGPSImgDirection()](#getGPSImgDirection--) | Görüntünün çekildiği anda GPS yönünü alır veya ayarlar. |
| [setGPSImgDirection(TiffRational value)](#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-) | Görüntünün çekildiği anda GPS yönünü alır veya ayarlar. |
| [getGPSImgDirectionRef()](#getGPSImgDirectionRef--) | Görüntünün çekildiği anda yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [setGPSImgDirectionRef(String value)](#setGPSImgDirectionRef-java.lang.String-) | Görüntünün çekildiği anda yön vermek için kullanılan GPS referansını alır veya ayarlar. |
| [getGPSDateStamp()](#getGPSDateStamp--) | UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgilerini kaydeden GPS karakter dizesini alır veya ayarlar. |
| [setGPSDateStamp(String value)](#setGPSDateStamp-java.lang.String-) | UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgilerini kaydeden GPS karakter dizesini alır veya ayarlar. |
| [getGPSLatitude()](#getGPSLatitude--) | GPS enlemini alır veya ayarlar. |
| [setGPSLatitude(TiffRational[] value)](#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | GPS enlemini alır veya ayarlar. |
| [getGPSLatitudeRef()](#getGPSLatitudeRef--) | GPS enleminin kuzey mi güney mi olduğunu alır veya ayarlar. |
| [setGPSLatitudeRef(String value)](#setGPSLatitudeRef-java.lang.String-) | GPS enleminin kuzey mi güney mi olduğunu alır veya ayarlar. |
| [getGPSLongitude()](#getGPSLongitude--) | GPS boylamını alır veya ayarlar. |
| [setGPSLongitude(TiffRational[] value)](#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---) | GPS boylamını alır veya ayarlar. |
| [getGPSLongitudeRef()](#getGPSLongitudeRef--) | GPS boylamının doğu mu batı mı olduğunu alır veya ayarlar. |
| [setGPSLongitudeRef(String value)](#setGPSLongitudeRef-java.lang.String-) | GPS boylamının doğu mu batı mı olduğunu alır veya ayarlar. |
| [getGPSMapDatum()](#getGPSMapDatum--) | GPS alıcı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar. |
| [setGPSMapDatum(String value)](#setGPSMapDatum-java.lang.String-) | GPS alıcı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar. |
| [getGPSMeasureMode()](#getGPSMeasureMode--) | GPS ölçüm modunu alır veya ayarlar. |
| [setGPSMeasureMode(String value)](#setGPSMeasureMode-java.lang.String-) | GPS ölçüm modunu alır veya ayarlar. |
| [getGPSProcessingMethod()](#getGPSProcessingMethod--) | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar. |
| [setGPSProcessingMethod(byte[] value)](#setGPSProcessingMethod-byte---) | Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar. |
| [getGPSSatellites()](#getGPSSatellites--) | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| [setGPSSatellites(String value)](#setGPSSatellites-java.lang.String-) | Ölçümler için kullanılan GPS uydularını alır veya ayarlar. |
| [getGPSSpeed()](#getGPSSpeed--) | GPS alıcısının hareket hızını alır veya ayarlar. |
| [setGPSSpeed(TiffRational value)](#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-) | GPS alıcısının hareket hızını alır veya ayarlar. |
| [getGPSSpeedRef()](#getGPSSpeedRef--) | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| [setGPSSpeedRef(String value)](#setGPSSpeedRef-java.lang.String-) | GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar. |
| [getGPSStatus()](#getGPSStatus--) | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| [setGPSStatus(String value)](#setGPSStatus-java.lang.String-) | Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar. |
| [getGPSTimestamp()](#getGPSTimestamp--) | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| [setGPSTimestamp(TiffRational[] value)](#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---) | GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar. |
| [getGPSTrack()](#getGPSTrack--) | GPS alıcı hareketinin yönünü alır veya ayarlar. |
| [setGPSTrack(String value)](#setGPSTrack-java.lang.String-) | GPS alıcı hareketinin yönünü alır veya ayarlar. |
| [getGPSTrackRef()](#getGPSTrackRef--) | GPS alıcı hareketinin yönünü vermek için referansı alır veya ayarlar. |
| [setGPSTrackRef(String value)](#setGPSTrackRef-java.lang.String-) | GPS alıcı hareketinin yönünü vermek için referansı alır veya ayarlar. |
| [getGPSVersionID()](#getGPSVersionID--) | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| [setGPSVersionID(byte[] value)](#setGPSVersionID-byte---) | GPS sürüm tanımlayıcısını alır veya ayarlar. |
| [getGainControl()](#getGainControl--) | Genel görüntü kazancı ayarının derecesini alır veya ayarlar. |
| [setGainControl(int value)](#setGainControl-int-) | Genel görüntü kazancı ayarının derecesini alır veya ayarlar. |
| [getGamma()](#getGamma--) | Gammayı alır veya ayarlar. |
| [setGamma(TiffRational value)](#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-) | Gammayı alır veya ayarlar. |
| [getISOSpeed()](#getISOSpeed--) | ISO hızını alır veya ayarlar. |
| [setISOSpeed(long value)](#setISOSpeed-long-) | ISO hızını alır veya ayarlar. |
| [getISOSpeedValue()](#getISOSpeedValue--) | ISO hız değerini alır. |
| [setISOSpeedValue(long value)](#setISOSpeedValue-long-) | ISO hız değerini ayarlar. |
| [getISOSpeedLatitudeYYY()](#getISOSpeedLatitudeYYY--) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| [setISOSpeedLatitudeYYY(long value)](#setISOSpeedLatitudeYYY-long-) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar. |
| [getISOSpeedLatitudeZZZ()](#getISOSpeedLatitudeZZZ--) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| [setISOSpeedLatitudeZZZ(long value)](#setISOSpeedLatitudeZZZ-long-) | ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar. |
| [getPhotographicSensitivity()](#getPhotographicSensitivity--) | Fotoğraf duyarlılığını alır veya ayarlar. |
| [setPhotographicSensitivity(long value)](#setPhotographicSensitivity-long-) | Fotoğraf duyarlılığını alır veya ayarlar. |
| [getImageUniqueID()](#getImageUniqueID--) | Görüntünün benzersiz tanımlayıcısını alır veya ayarlar. |
| [setImageUniqueID(String value)](#setImageUniqueID-java.lang.String-) | Görüntünün benzersiz tanımlayıcısını alır veya ayarlar. |
| [getLensMake()](#getLensMake--) | Lens üreticisini alır veya ayarlar. |
| [setLensMake(String value)](#setLensMake-java.lang.String-) | Lens üreticisini alır veya ayarlar. |
| [getLensModel()](#getLensModel--) | Lens modelini alır veya ayarlar. |
| [setLensModel(String value)](#setLensModel-java.lang.String-) | Lens modelini alır veya ayarlar. |
| [getLensSerialNumber()](#getLensSerialNumber--) | Lens seri numarasını alır veya ayarlar. |
| [setLensSerialNumber(String value)](#setLensSerialNumber-java.lang.String-) | Lens seri numarasını alır veya ayarlar. |
| [getLensSpecification()](#getLensSpecification--) | Lens özelliklerini alır veya ayarlar |
| [setLensSpecification(TiffRational[] value)](#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---) | Lens özelliklerini alır veya ayarlar |
| [getLightSource()](#getLightSource--) | Işık kaynağını alır veya ayarlar. |
| [setLightSource(int value)](#setLightSource-int-) | Işık kaynağını alır veya ayarlar. |
| [getMakerNoteData()](#getMakerNoteData--) | Üretici not verisini alır. |
| [getMakerNoteRawData()](#getMakerNoteRawData--) | Üretici not ham verisini alır veya ayarlar. |
| [setMakerNoteRawData(byte[] value)](#setMakerNoteRawData-byte---) | Üretici not ham verisini alır veya ayarlar. |
| [getMakerNotes()](#getMakerNotes--) | Üretici notlarını alır. |
| [getMaxApertureValue()](#getMaxApertureValue--) | Maksimum diyafram değerini alır veya ayarlar. |
| [setMaxApertureValue(TiffRational value)](#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-) | Maksimum diyafram değerini alır veya ayarlar. |
| [getMeteringMode()](#getMeteringMode--) | Ölçüm modunu alır veya ayarlar. |
| [setMeteringMode(int value)](#setMeteringMode-int-) | Ölçüm modunu alır veya ayarlar. |
| [getOECF()](#getOECF--) | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| [setOECF(byte[] value)](#setOECF-byte---) | ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar. |
| [getOrientation()](#getOrientation--) | Yönü alır [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [setOrientation(int value)](#setOrientation-int-) | Yönü ayarlar [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation). |
| [getPixelXDimension()](#getPixelXDimension--) | Piksel x boyutunu alır veya ayarlar. |
| [setPixelXDimension(long value)](#setPixelXDimension-long-) | Piksel x boyutunu alır veya ayarlar. |
| [getPixelYDimension()](#getPixelYDimension--) | Piksel y boyutunu alır veya ayarlar. |
| [setPixelYDimension(long value)](#setPixelYDimension-long-) | Piksel y boyutunu alır veya ayarlar. |
| [getProperties()](#getProperties--) | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| [setProperties(TiffDataType[] value)](#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar. |
| [getRecommendedExposureIndex()](#getRecommendedExposureIndex--) | Önerilen pozlama indeksini alır veya ayarlar. |
| [setRecommendedExposureIndex(long value)](#setRecommendedExposureIndex-long-) | Önerilen pozlama indeksini alır veya ayarlar. |
| [getRelatedSoundFile()](#getRelatedSoundFile--) | İlgili ses dosyasını alır veya ayarlar. |
| [setRelatedSoundFile(String value)](#setRelatedSoundFile-java.lang.String-) | İlgili ses dosyasını alır veya ayarlar. |
| [getSaturation()](#getSaturation--) | Doygunluğu alır veya ayarlar. |
| [setSaturation(int value)](#setSaturation-int-) | Doygunluğu alır veya ayarlar. |
| [getSceneCaptureType()](#getSceneCaptureType--) | Sahne yakalama tipini alır veya ayarlar. |
| [setSceneCaptureType(int value)](#setSceneCaptureType-int-) | Sahne yakalama tipini alır veya ayarlar. |
| [getSceneType()](#getSceneType--) | Sahne tipini alır veya ayarlar. |
| [setSceneType(byte value)](#setSceneType-byte-) | Sahne tipini alır veya ayarlar. |
| [getSensingMethod()](#getSensingMethod--) | Algılama yöntemini alır veya ayarlar. |
| [setSensingMethod(int value)](#setSensingMethod-int-) | Algılama yöntemini alır veya ayarlar. |
| [getSensitivityType()](#getSensitivityType--) | Duyarlılık tipini alır veya ayarlar. |
| [setSensitivityType(int value)](#setSensitivityType-int-) | Duyarlılık tipini alır veya ayarlar. |
| [getSharpness()](#getSharpness--) | Keskinliği alır veya ayarlar. |
| [setSharpness(int value)](#setSharpness-int-) | Keskinliği alır veya ayarlar. |
| [getShutterSpeedValue()](#getShutterSpeedValue--) | Deklanşör hızı değerini alır veya ayarlar. |
| [setShutterSpeedValue(TiffSRational value)](#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-) | Deklanşör hızı değerini alır veya ayarlar. |
| [getSpatialFrequencyResponse()](#getSpatialFrequencyResponse--) | Uzamsal frekans yanıtını alır veya ayarlar. |
| [setSpatialFrequencyResponse(byte[] value)](#setSpatialFrequencyResponse-byte---) | Uzamsal frekans yanıtını alır veya ayarlar. |
| [getSpectralSensitivity()](#getSpectralSensitivity--) | Spektral duyarlılığı alır veya ayarlar. |
| [setSpectralSensitivity(String value)](#setSpectralSensitivity-java.lang.String-) | Spektral duyarlılığı alır veya ayarlar. |
| [getStandardOutputSensitivity()](#getStandardOutputSensitivity--) | Standart çıkış duyarlılığını alır |
| [setStandardOutputSensitivity(long value)](#setStandardOutputSensitivity-long-) | Standart çıkış duyarlılığını ayarlar |
| [getSubjectArea()](#getSubjectArea--) | Konu alanını alır veya ayarlar. |
| [setSubjectArea(int[] value)](#setSubjectArea-int---) | Konu alanını alır veya ayarlar. |
| [getSubjectDistance()](#getSubjectDistance--) | Konu mesafesini alır veya ayarlar. |
| [setSubjectDistance(TiffRational value)](#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-) | Konu mesafesini alır veya ayarlar. |
| [getSubjectDistanceRange()](#getSubjectDistanceRange--) | Konu mesafe aralığını alır veya ayarlar. |
| [setSubjectDistanceRange(int value)](#setSubjectDistanceRange-int-) | Konu mesafe aralığını alır veya ayarlar. |
| [getSubjectLocation()](#getSubjectLocation--) | Konu konumunu alır veya ayarlar. |
| [setSubjectLocation(int[] value)](#setSubjectLocation-int---) | Konu konumunu alır veya ayarlar. |
| [getSubsecTime()](#getSubsecTime--) | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setSubsecTime(String value)](#setSubsecTime-java.lang.String-) | DateTime etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getSubsecTimeDigitized()](#getSubsecTimeDigitized--) | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setSubsecTimeDigitized(String value)](#setSubsecTimeDigitized-java.lang.String-) | DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getSubsecTimeOriginal()](#getSubsecTimeOriginal--) | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [setSubsecTimeOriginal(String value)](#setSubsecTimeOriginal-java.lang.String-) | DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar. |
| [getUserComment()](#getUserComment--) | Kullanıcı yorumunu alır veya ayarlar. |
| [setUserComment(String value)](#setUserComment-java.lang.String-) | Kullanıcı yorumunu alır veya ayarlar. |
| [getWhiteBalance()](#getWhiteBalance--) | Beyaz dengesini alır veya ayarlar. |
| [setWhiteBalance(int value)](#setWhiteBalance-int-) | Beyaz dengesini alır veya ayarlar. |
| [getWhitePoint()](#getWhitePoint--) | Görüntünün beyaz noktasının kromatik değerini alır veya ayarlar. |
| [setWhitePoint(TiffRational[] value)](#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---) | Görüntünün beyaz noktasının kromatik değerini alır veya ayarlar. |
| [getCommonTags()](#getCommonTags--) | Ortak bölüme ait etiketleri alır veya ayarlar. |
| [setCommonTags(TiffDataType[] value)](#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Ortak bölüme ait etiketleri alır veya ayarlar. |
| [getExifTags()](#getExifTags--) | Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar. |
| [setExifTags(TiffDataType[] value)](#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar. |
| [getGPSTags()](#getGPSTags--) | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| [setGPSTags(TiffDataType[] value)](#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar. |
| [getThumbnail()](#getThumbnail--) | Küçük resmi alır. |
| [setThumbnail(RasterImage value)](#setThumbnail-com.aspose.imaging.RasterImage-) | Küçük resmi ayarlar. |
| [getXResolutionInt()](#getXResolutionInt--) | x çözünürlüğünü alır. |
| [setXResolution(int value)](#setXResolution-int-) | x çözünürlüğünü ayarlar. |
| [getYResolutionInt()](#getYResolutionInt--) | y çözünürlüğünü alır. |
| [setYResolution(int value)](#setYResolution-int-) | y çözünürlüğünü ayarlar. |
| [removeTag(int tagId)](#removeTag-int-) | Etiketi konteynerden kaldır |
| [getTagValue(int key)](#getTagValue-int-) | Etiket değerini alır. |

## Example: Access camera manufacturer maker notes in Jpeg image.

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### ExifData() {#ExifData--}
```
public ExifData()
```


Yeni bir `ExifData` sınıfı örneği başlatır.

### ExifData(TiffDataType[] exifdata) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] exifdata)
```


Diziden gelen veriyle yeni bir `ExifData` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exifdata | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#ExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public ExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Diziden gelen veriyle yeni bir `ExifData` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ortak etiketler. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF etiketleri. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS etiketleri. |

### ExifData(ExifData exifdata) {#ExifData-com.aspose.imaging.exif.ExifData-}
```
public ExifData(ExifData exifdata)
```


Diziden gelen veriyle yeni bir [ExifData](../../com.aspose.imaging.exif/exifdata) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exifdata | [ExifData](../../com.aspose.imaging.exif/exifdata) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### ExifData(byte[] binaryData) {#ExifData-byte---}
```
public ExifData(byte[] binaryData)
```


Yeni bir [ExifData](../../com.aspose.imaging.exif/exifdata) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| binaryData | byte[] | İkili veri. |

### isBigEndian() {#isBigEndian--}
```
public boolean isBigEndian()
```


Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Akışın oluşturulduğu EXIF verisi büyük endian ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setBigEndian(boolean value) {#setBigEndian-boolean-}
```
public void setBigEndian(boolean value)
```


Akıştan oluşturulan EXIF verisinin büyük endian olup olmadığını gösteren bir değeri alır veya ayarlar.

Değer: Akışın oluşturulduğu EXIF verisi büyük endian ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getMake() {#getMake--}
```
public final String getMake()
```


Kayıt ekipmanının üreticisini alır.

Değer: Kayıt ekipmanının üreticisi.

**Returns:**
java.lang.String - kayıt ekipmanının üreticisi.
### setMake(String value) {#setMake-java.lang.String-}
```
public final void setMake(String value)
```


Kayıt ekipmanının üreticisini ayarlar.

Değer: Kayıt ekipmanının üreticisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String | kayıt ekipmanının üreticisi. |

### getApertureValue() {#getApertureValue--}
```
public TiffRational getApertureValue()
```


Diyafram değerini alır veya ayarlar.

Değer: Diyafram değeri.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setApertureValue(TiffRational value) {#setApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setApertureValue(TiffRational value)
```


Diyafram değerini alır veya ayarlar.

Değer: Diyafram değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getBodySerialNumber() {#getBodySerialNumber--}
```
public String getBodySerialNumber()
```


Kamera gövdesi seri numarasını alır veya ayarlar.

Değer: Gövde seri numarası.

**Returns:**
java.lang.String
### setBodySerialNumber(String value) {#setBodySerialNumber-java.lang.String-}
```
public void setBodySerialNumber(String value)
```


Kamera gövdesi seri numarasını alır veya ayarlar.

Değer: Gövde seri numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBrightnessValue() {#getBrightnessValue--}
```
public TiffSRational getBrightnessValue()
```


Parlaklık değerini alır veya ayarlar.

Değer: Parlaklık değeri.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setBrightnessValue(TiffSRational value) {#setBrightnessValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setBrightnessValue(TiffSRational value)
```


Parlaklık değerini alır veya ayarlar.

Değer: Parlaklık değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getCFAPattern() {#getCFAPattern--}
```
public byte[] getCFAPattern()
```


CFA desenini alır veya ayarlar.

Değer: CFA deseni.

**Returns:**
byte[]
### setCFAPattern(byte[] value) {#setCFAPattern-byte---}
```
public void setCFAPattern(byte[] value)
```


CFA desenini alır veya ayarlar.

Değer: CFA deseni.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getCameraOwnerName() {#getCameraOwnerName--}
```
public String getCameraOwnerName()
```


Kamera sahibi adını alır veya ayarlar

Değer: kamera sahibinin adı.

**Returns:**
java.lang.String
### setCameraOwnerName(String value) {#setCameraOwnerName-java.lang.String-}
```
public void setCameraOwnerName(String value)
```


Kamera sahibi adını alır veya ayarlar

Değer: kamera sahibinin adı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getColorSpace() {#getColorSpace--}
```
public int getColorSpace()
```


Renk uzayını alır veya ayarlar.

Değer: renk uzayı.

**Returns:**
int
### setColorSpace(int value) {#setColorSpace-int-}
```
public void setColorSpace(int value)
```


Renk uzayını alır veya ayarlar.

Değer: renk uzayı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getComponentsConfiguration() {#getComponentsConfiguration--}
```
public byte[] getComponentsConfiguration()
```


Bileşen yapılandırmasını alır veya ayarlar.

Değer: bileşen yapılandırması.

**Returns:**
byte[]
### setComponentsConfiguration(byte[] value) {#setComponentsConfiguration-byte---}
```
public void setComponentsConfiguration(byte[] value)
```


Bileşen yapılandırmasını alır veya ayarlar.

Değer: bileşen yapılandırması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getCompressedBitsPerPixel() {#getCompressedBitsPerPixel--}
```
public TiffRational getCompressedBitsPerPixel()
```


Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar.

Değer: piksel başına sıkıştırılmış bit.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setCompressedBitsPerPixel(TiffRational value) {#setCompressedBitsPerPixel-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setCompressedBitsPerPixel(TiffRational value)
```


Piksel başına sıkıştırılmış bit sayısını alır veya ayarlar.

Değer: piksel başına sıkıştırılmış bit.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getContrast() {#getContrast--}
```
public int getContrast()
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Returns:**
int
### setContrast(int value) {#setContrast-int-}
```
public void setContrast(int value)
```


Kontrastı alır veya ayarlar.

Değer: kontrast.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCustomRendered() {#getCustomRendered--}
```
public int getCustomRendered()
```


Özel işlenmişi alır veya ayarlar.

Değer: özel işlenmiş.

**Returns:**
int
### setCustomRendered(int value) {#setCustomRendered-int-}
```
public void setCustomRendered(int value)
```


Özel işlenmişi alır veya ayarlar.

Değer: özel işlenmiş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getDateTimeDigitized() {#getDateTimeDigitized--}
```
public String getDateTimeDigitized()
```


Dijitalleştirilme tarih ve saatini alır veya ayarlar.

Değer: dijitalleştirilen tarih ve saat.

**Returns:**
java.lang.String
### setDateTimeDigitized(String value) {#setDateTimeDigitized-java.lang.String-}
```
public void setDateTimeDigitized(String value)
```


Dijitalleştirilme tarih ve saatini alır veya ayarlar.

Değer: dijitalleştirilen tarih ve saat.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDateTimeOriginal() {#getDateTimeOriginal--}
```
public String getDateTimeOriginal()
```


Orijinal tarih ve saatini alır veya ayarlar.

Değer: orijinal tarih ve saat.

**Returns:**
java.lang.String
### setDateTimeOriginal(String value) {#setDateTimeOriginal-java.lang.String-}
```
public void setDateTimeOriginal(String value)
```


Orijinal tarih ve saatini alır veya ayarlar.

Değer: orijinal tarih ve saat.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDeviceSettingDescription() {#getDeviceSettingDescription--}
```
public byte[] getDeviceSettingDescription()
```


Aygıt ayarları açıklamasını alır veya ayarlar.

Değer: cihaz ayarı açıklaması.

**Returns:**
byte[]
### setDeviceSettingDescription(byte[] value) {#setDeviceSettingDescription-byte---}
```
public void setDeviceSettingDescription(byte[] value)
```


Aygıt ayarları açıklamasını alır veya ayarlar.

Değer: cihaz ayarı açıklaması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getDigitalZoomRatio() {#getDigitalZoomRatio--}
```
public TiffRational getDigitalZoomRatio()
```


Dijital yakınlaştırma oranını alır veya ayarlar.

Değer: dijital zoom oranı.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setDigitalZoomRatio(TiffRational value) {#setDigitalZoomRatio-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setDigitalZoomRatio(TiffRational value)
```


Dijital yakınlaştırma oranını alır veya ayarlar.

Değer: dijital zoom oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExifVersion() {#getExifVersion--}
```
public byte[] getExifVersion()
```


EXIF sürümünü alır veya ayarlar.

Değer: EXIF sürümü.

**Returns:**
byte[]
### setExifVersion(byte[] value) {#setExifVersion-byte---}
```
public void setExifVersion(byte[] value)
```


EXIF sürümünü alır veya ayarlar.

Değer: EXIF sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getExposureBiasValue() {#getExposureBiasValue--}
```
public TiffSRational getExposureBiasValue()
```


Pozlama sapma değerini alır veya ayarlar.

Değer: pozlama sapma değeri.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setExposureBiasValue(TiffSRational value) {#setExposureBiasValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setExposureBiasValue(TiffSRational value)
```


Pozlama sapma değerini alır veya ayarlar.

Değer: pozlama sapma değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getExposureIndex() {#getExposureIndex--}
```
public TiffRational getExposureIndex()
```


Pozlama indeksini alır veya ayarlar.

Değer: pozlamanın indeksi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureIndex(TiffRational value) {#setExposureIndex-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureIndex(TiffRational value)
```


Pozlama indeksini alır veya ayarlar.

Değer: pozlamanın indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getExposureMode() {#getExposureMode--}
```
public int getExposureMode()
```


Pozlama modunu alır veya ayarlar.

Değer: pozlama modu.

**Returns:**
int
### setExposureMode(int value) {#setExposureMode-int-}
```
public void setExposureMode(int value)
```


Pozlama modunu alır veya ayarlar.

Değer: pozlama modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExposureProgram() {#getExposureProgram--}
```
public int getExposureProgram()
```


Pozlama programını alır veya ayarlar.

Değer: pozlama programı.

**Returns:**
int
### setExposureProgram(int value) {#setExposureProgram-int-}
```
public void setExposureProgram(int value)
```


Pozlama programını alır veya ayarlar.

Değer: pozlama programı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getExposureTime() {#getExposureTime--}
```
public TiffRational getExposureTime()
```


Pozlama süresini alır veya ayarlar.

Değer: pozlama süresi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setExposureTime(TiffRational value) {#setExposureTime-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setExposureTime(TiffRational value)
```


Pozlama süresini alır veya ayarlar.

Değer: pozlama süresi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFNumber() {#getFNumber--}
```
public TiffRational getFNumber()
```


F-numarasını alır veya ayarlar.

Değer: F-numarası.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFNumber(TiffRational value) {#setFNumber-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFNumber(TiffRational value)
```


F-numarasını alır veya ayarlar.

Değer: F-numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFileSource() {#getFileSource--}
```
public byte getFileSource()
```


Dosya kaynağı türünü alır veya ayarlar.

Değer: dosya kaynağı türü.

**Returns:**
byte
### setFileSource(byte value) {#setFileSource-byte-}
```
public void setFileSource(byte value)
```


Dosya kaynağı türünü alır veya ayarlar.

Değer: dosya kaynağı türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getFlash() {#getFlash--}
```
public int getFlash()
```


Flaş'ı alır veya ayarlar.

Değer: flaş.

**Returns:**
int
### setFlash(int value) {#setFlash-int-}
```
public void setFlash(int value)
```


Flaş'ı alır veya ayarlar.

Değer: flaş.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFlashEnergy() {#getFlashEnergy--}
```
public TiffRational getFlashEnergy()
```


Flaş enerjisini alır veya ayarlar.

Değer: flaş enerjisi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFlashEnergy(TiffRational value) {#setFlashEnergy-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFlashEnergy(TiffRational value)
```


Flaş enerjisini alır veya ayarlar.

Değer: flaş enerjisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFlashpixVersion() {#getFlashpixVersion--}
```
public byte[] getFlashpixVersion()
```


Flaş piksel sürümünü alır veya ayarlar.

Değer: flaş pix sürümü.

**Returns:**
byte[]
### setFlashpixVersion(byte[] value) {#setFlashpixVersion-byte---}
```
public void setFlashpixVersion(byte[] value)
```


Flaş piksel sürümünü alır veya ayarlar.

Değer: flaş pix sürümü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getFocalLength() {#getFocalLength--}
```
public TiffRational getFocalLength()
```


Odak uzaklığını alır veya ayarlar.

Değer: odak uzunluğu.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalLength(TiffRational value) {#setFocalLength-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalLength(TiffRational value)
```


Odak uzaklığını alır veya ayarlar.

Değer: odak uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalLengthIn35MmFilm() {#getFocalLengthIn35MmFilm--}
```
public int getFocalLengthIn35MmFilm()
```


35 mm filmde odak uzaklığını alır veya ayarlar.

Değer: 35 mm filmde odak uzunluğu.

**Returns:**
int
### setFocalLengthIn35MmFilm(int value) {#setFocalLengthIn35MmFilm-int-}
```
public void setFocalLengthIn35MmFilm(int value)
```


35 mm filmde odak uzaklığını alır veya ayarlar.

Değer: 35 mm filmde odak uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFocalPlaneResolutionUnit() {#getFocalPlaneResolutionUnit--}
```
public int getFocalPlaneResolutionUnit()
```


Odak düzlemi çözünürlük birimini alır veya ayarlar.

Değer: odak düzlemi çözünürlük birimi.

**Returns:**
int
### setFocalPlaneResolutionUnit(int value) {#setFocalPlaneResolutionUnit-int-}
```
public void setFocalPlaneResolutionUnit(int value)
```


Odak düzlemi çözünürlük birimini alır veya ayarlar.

Değer: odak düzlemi çözünürlük birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFocalPlaneXResolution() {#getFocalPlaneXResolution--}
```
public TiffRational getFocalPlaneXResolution()
```


Odak düzlemi x çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi x çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneXResolution(TiffRational value) {#setFocalPlaneXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneXResolution(TiffRational value)
```


Odak düzlemi x çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi x çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getFocalPlaneYResolution() {#getFocalPlaneYResolution--}
```
public TiffRational getFocalPlaneYResolution()
```


Odak düzlemi y çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi y çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setFocalPlaneYResolution(TiffRational value) {#setFocalPlaneYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setFocalPlaneYResolution(TiffRational value)
```


Odak düzlemi y çözünürlüğünü alır veya ayarlar.

Değer: Odak düzlemi y çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitude() {#getGPSAltitude--}
```
public TiffRational getGPSAltitude()
```


GPS yüksekliğini alır veya ayarlar.

Değer: GPS yüksekliği.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSAltitude(TiffRational value) {#setGPSAltitude-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSAltitude(TiffRational value)
```


GPS yüksekliğini alır veya ayarlar.

Değer: GPS yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSAltitudeRef() {#getGPSAltitudeRef--}
```
public byte getGPSAltitudeRef()
```


Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar.

Değer: Referans yüksekliği olarak kullanılan GPS yüksekliği.

**Returns:**
byte
### setGPSAltitudeRef(byte value) {#setGPSAltitudeRef-byte-}
```
public void setGPSAltitudeRef(byte value)
```


Referans yüksekliği olarak kullanılan GPS yüksekliğini alır veya ayarlar.

Değer: Referans yüksekliği olarak kullanılan GPS yüksekliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getGPSAreaInformation() {#getGPSAreaInformation--}
```
public byte[] getGPSAreaInformation()
```


GPS alan bilgilerini alır veya ayarlar.

Değer: GPS alan bilgisi.

**Returns:**
byte[]
### setGPSAreaInformation(byte[] value) {#setGPSAreaInformation-byte---}
```
public void setGPSAreaInformation(byte[] value)
```


GPS alan bilgilerini alır veya ayarlar.

Değer: GPS alan bilgisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getGPSDOP() {#getGPSDOP--}
```
public TiffRational getGPSDOP()
```


GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar.

Değer: GPS DOP (veri kesinlik derecesi).

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDOP(TiffRational value) {#setGPSDOP-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDOP(TiffRational value)
```


GPS DOP (veri kesinlik derecesi) değerini alır veya ayarlar.

Değer: GPS DOP (veri kesinlik derecesi).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearing() {#getGPSDestBearing--}
```
public TiffRational getGPSDestBearing()
```


Hedef noktaya olan GPS yönünü alır veya ayarlar.

Değer: Hedef noktaya olan GPS yönü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestBearing(TiffRational value) {#setGPSDestBearing-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestBearing(TiffRational value)
```


Hedef noktaya olan GPS yönünü alır veya ayarlar.

Değer: Hedef noktaya olan GPS yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestBearingRef() {#getGPSDestBearingRef--}
```
public String getGPSDestBearingRef()
```


Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Hedef noktaya yön vermek için kullanılan GPS referansı.

**Returns:**
java.lang.String
### setGPSDestBearingRef(String value) {#setGPSDestBearingRef-java.lang.String-}
```
public void setGPSDestBearingRef(String value)
```


Hedef noktaya yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Hedef noktaya yön vermek için kullanılan GPS referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSDestDistance() {#getGPSDestDistance--}
```
public TiffRational getGPSDestDistance()
```


Hedef noktaya olan GPS mesafesini alır veya ayarlar.

Değer: Hedef noktaya olan GPS mesafesi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSDestDistance(TiffRational value) {#setGPSDestDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSDestDistance(TiffRational value)
```


Hedef noktaya olan GPS mesafesini alır veya ayarlar.

Değer: Hedef noktaya olan GPS mesafesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestDistanceRef() {#getGPSDestDistanceRef--}
```
public String getGPSDestDistanceRef()
```


Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar.

Değer: Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimi.

**Returns:**
java.lang.String
### setGPSDestDistanceRef(String value) {#setGPSDestDistanceRef-java.lang.String-}
```
public void setGPSDestDistanceRef(String value)
```


Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimini alır veya ayarlar.

Değer: Hedef noktaya olan mesafeyi ifade etmek için kullanılan GPS birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSDestLatitude() {#getGPSDestLatitude--}
```
public TiffRational[] getGPSDestLatitude()
```


Hedef noktanın GPS enlem değerini alır veya ayarlar.

Değer: Hedef noktanın GPS enlemi.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLatitude(TiffRational[] value) {#setGPSDestLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLatitude(TiffRational[] value)
```


Hedef noktanın GPS enlem değerini alır veya ayarlar.

Değer: Hedef noktanın GPS enlemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLatitudeRef() {#getGPSDestLatitudeRef--}
```
public String getGPSDestLatitudeRef()
```


Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değeri.

**Returns:**
java.lang.String
### setGPSDestLatitudeRef(String value) {#setGPSDestLatitudeRef-java.lang.String-}
```
public void setGPSDestLatitudeRef(String value)
```


Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın enleminin kuzey mi yoksa güney mi olduğunu gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSDestLongitude() {#getGPSDestLongitude--}
```
public TiffRational[] getGPSDestLongitude()
```


Hedef noktanın GPS boylam değerini alır veya ayarlar.

Değer: Hedef noktanın GPS boylamı.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSDestLongitude(TiffRational[] value) {#setGPSDestLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSDestLongitude(TiffRational[] value)
```


Hedef noktanın GPS boylam değerini alır veya ayarlar.

Değer: Hedef noktanın GPS boylamı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSDestLongitudeRef() {#getGPSDestLongitudeRef--}
```
public String getGPSDestLongitudeRef()
```


Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değeri.

**Returns:**
java.lang.String
### setGPSDestLongitudeRef(String value) {#setGPSDestLongitudeRef-java.lang.String-}
```
public void setGPSDestLongitudeRef(String value)
```


Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değerini alır veya ayarlar.

Değer: Hedef noktanın boylamının doğu mu yoksa batı mı olduğunu gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSDifferential() {#getGPSDifferential--}
```
public int getGPSDifferential()
```


GPS alıcıya diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar.

Değer: Diferansiyel düzeltmenin GPS alıcısına uygulanıp uygulanmadığını gösteren GPS değeri.

**Returns:**
int
### setGPSDifferential(int value) {#setGPSDifferential-int-}
```
public void setGPSDifferential(int value)
```


GPS alıcıya diferansiyel düzeltmenin uygulanıp uygulanmadığını gösteren bir GPS değerini alır veya ayarlar.

Değer: Diferansiyel düzeltmenin GPS alıcısına uygulanıp uygulanmadığını gösteren GPS değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGPSImgDirection() {#getGPSImgDirection--}
```
public TiffRational getGPSImgDirection()
```


Görüntünün çekildiği anda GPS yönünü alır veya ayarlar.

Değer: Görüntünün çekildiği zaman GPS yönü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSImgDirection(TiffRational value) {#setGPSImgDirection-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSImgDirection(TiffRational value)
```


Görüntünün çekildiği anda GPS yönünü alır veya ayarlar.

Değer: Görüntünün çekildiği zaman GPS yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSImgDirectionRef() {#getGPSImgDirectionRef--}
```
public String getGPSImgDirectionRef()
```


Görüntünün çekildiği anda yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Görüntünün çekildiği zaman yönünü vermek için kullanılan GPS referansı.

**Returns:**
java.lang.String
### setGPSImgDirectionRef(String value) {#setGPSImgDirectionRef-java.lang.String-}
```
public void setGPSImgDirectionRef(String value)
```


Görüntünün çekildiği anda yön vermek için kullanılan GPS referansını alır veya ayarlar.

Değer: Görüntünün çekildiği zaman yönünü vermek için kullanılan GPS referansı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSDateStamp() {#getGPSDateStamp--}
```
public String getGPSDateStamp()
```


UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgilerini kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden GPS karakter dizesi.

**Returns:**
java.lang.String
### setGPSDateStamp(String value) {#setGPSDateStamp-java.lang.String-}
```
public void setGPSDateStamp(String value)
```


UTC (Eşgüdümlü Evrensel Zaman) ile ilgili tarih ve saat bilgilerini kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: UTC'ye (Eşgüdümlü Evrensel Zaman) göre tarih ve saat bilgilerini kaydeden GPS karakter dizesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSLatitude() {#getGPSLatitude--}
```
public TiffRational[] getGPSLatitude()
```


GPS enlemini alır veya ayarlar.

Değer: GPS enlemi.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLatitude(TiffRational[] value) {#setGPSLatitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLatitude(TiffRational[] value)
```


GPS enlemini alır veya ayarlar.

Değer: GPS enlemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLatitudeRef() {#getGPSLatitudeRef--}
```
public String getGPSLatitudeRef()
```


GPS enleminin kuzey mi güney mi olduğunu alır veya ayarlar.

Değer: GPS enlemi kuzey mi yoksa güney mi.

**Returns:**
java.lang.String
### setGPSLatitudeRef(String value) {#setGPSLatitudeRef-java.lang.String-}
```
public void setGPSLatitudeRef(String value)
```


GPS enleminin kuzey mi güney mi olduğunu alır veya ayarlar.

Değer: GPS enlemi kuzey mi yoksa güney mi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSLongitude() {#getGPSLongitude--}
```
public TiffRational[] getGPSLongitude()
```


GPS boylamını alır veya ayarlar.

Değer: GPS boylamı.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSLongitude(TiffRational[] value) {#setGPSLongitude-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSLongitude(TiffRational[] value)
```


GPS boylamını alır veya ayarlar.

Değer: GPS boylamı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSLongitudeRef() {#getGPSLongitudeRef--}
```
public String getGPSLongitudeRef()
```


GPS boylamının doğu mu batı mı olduğunu alır veya ayarlar.

Değer: GPS boylamı doğu mu yoksa batı mı.

**Returns:**
java.lang.String
### setGPSLongitudeRef(String value) {#setGPSLongitudeRef-java.lang.String-}
```
public void setGPSLongitudeRef(String value)
```


GPS boylamının doğu mu batı mı olduğunu alır veya ayarlar.

Değer: GPS boylamı doğu mu yoksa batı mı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSMapDatum() {#getGPSMapDatum--}
```
public String getGPSMapDatum()
```


GPS alıcı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar.

Değer: GPS alıcısı tarafından kullanılan GPS jeodezik ölçüm verileri.

**Returns:**
java.lang.String
### setGPSMapDatum(String value) {#setGPSMapDatum-java.lang.String-}
```
public void setGPSMapDatum(String value)
```


GPS alıcı tarafından kullanılan GPS jeodezik ölçüm verilerini alır veya ayarlar.

Değer: GPS alıcısı tarafından kullanılan GPS jeodezik ölçüm verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSMeasureMode() {#getGPSMeasureMode--}
```
public String getGPSMeasureMode()
```


GPS ölçüm modunu alır veya ayarlar.

Değer: GPS ölçüm modu.

**Returns:**
java.lang.String
### setGPSMeasureMode(String value) {#setGPSMeasureMode-java.lang.String-}
```
public void setGPSMeasureMode(String value)
```


GPS ölçüm modunu alır veya ayarlar.

Değer: GPS ölçüm modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSProcessingMethod() {#getGPSProcessingMethod--}
```
public byte[] getGPSProcessingMethod()
```


Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesi.

**Returns:**
byte[]
### setGPSProcessingMethod(byte[] value) {#setGPSProcessingMethod-byte---}
```
public void setGPSProcessingMethod(byte[] value)
```


Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesini alır veya ayarlar.

Değer: Konum bulma için kullanılan yöntemin adını kaydeden GPS karakter dizesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getGPSSatellites() {#getGPSSatellites--}
```
public String getGPSSatellites()
```


Ölçümler için kullanılan GPS uydularını alır veya ayarlar.

Değer: Ölçümler için kullanılan GPS uyduları.

**Returns:**
java.lang.String
### setGPSSatellites(String value) {#setGPSSatellites-java.lang.String-}
```
public void setGPSSatellites(String value)
```


Ölçümler için kullanılan GPS uydularını alır veya ayarlar.

Değer: Ölçümler için kullanılan GPS uyduları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSSpeed() {#getGPSSpeed--}
```
public TiffRational getGPSSpeed()
```


GPS alıcısının hareket hızını alır veya ayarlar.

Değer: GPS alıcısının hareket hızı.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGPSSpeed(TiffRational value) {#setGPSSpeed-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGPSSpeed(TiffRational value)
```


GPS alıcısının hareket hızını alır veya ayarlar.

Değer: GPS alıcısının hareket hızı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSSpeedRef() {#getGPSSpeedRef--}
```
public String getGPSSpeedRef()
```


GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar.

Değer: GPS alıcısının hareket hızını ifade etmek için kullanılan birim.

**Returns:**
java.lang.String
### setGPSSpeedRef(String value) {#setGPSSpeedRef-java.lang.String-}
```
public void setGPSSpeedRef(String value)
```


GPS alıcısının hareket hızını ifade etmek için kullanılan birimi alır veya ayarlar.

Değer: GPS alıcısının hareket hızını ifade etmek için kullanılan birim.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSStatus() {#getGPSStatus--}
```
public String getGPSStatus()
```


Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar.

Değer: Görüntü kaydedildiğinde GPS alıcısının durumu.

**Returns:**
java.lang.String
### setGPSStatus(String value) {#setGPSStatus-java.lang.String-}
```
public void setGPSStatus(String value)
```


Görüntü kaydedildiğinde GPS alıcısının durumunu alır veya ayarlar.

Değer: Görüntü kaydedildiğinde GPS alıcısının durumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSTimestamp() {#getGPSTimestamp--}
```
public TiffRational[] getGPSTimestamp()
```


GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar.

Değer: GPS zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setGPSTimestamp(TiffRational[] value) {#setGPSTimestamp-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setGPSTimestamp(TiffRational[] value)
```


GPS zamanını UTC (Eşgüdümlü Evrensel Zaman) olarak alır veya ayarlar.

Değer: GPS zamanı UTC (Eşgüdümlü Evrensel Zaman) olarak.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getGPSTrack() {#getGPSTrack--}
```
public String getGPSTrack()
```


GPS alıcı hareketinin yönünü alır veya ayarlar.

Değer: GPS alıcısının hareket yönü.

**Returns:**
java.lang.String
### setGPSTrack(String value) {#setGPSTrack-java.lang.String-}
```
public void setGPSTrack(String value)
```


GPS alıcı hareketinin yönünü alır veya ayarlar.

Değer: GPS alıcısının hareket yönü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSTrackRef() {#getGPSTrackRef--}
```
public String getGPSTrackRef()
```


GPS alıcı hareketinin yönünü vermek için referansı alır veya ayarlar.

Değer: GPS alıcısının hareket yönünü vermek için referans.

**Returns:**
java.lang.String
### setGPSTrackRef(String value) {#setGPSTrackRef-java.lang.String-}
```
public void setGPSTrackRef(String value)
```


GPS alıcı hareketinin yönünü vermek için referansı alır veya ayarlar.

Değer: GPS alıcısının hareket yönünü vermek için referans.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getGPSVersionID() {#getGPSVersionID--}
```
public byte[] getGPSVersionID()
```


GPS sürüm tanımlayıcısını alır veya ayarlar.

Değer: GPS sürüm tanımlayıcısı.

**Returns:**
byte[]
### setGPSVersionID(byte[] value) {#setGPSVersionID-byte---}
```
public void setGPSVersionID(byte[] value)
```


GPS sürüm tanımlayıcısını alır veya ayarlar.

Değer: GPS sürüm tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getGainControl() {#getGainControl--}
```
public int getGainControl()
```


Genel görüntü kazancı ayarının derecesini alır veya ayarlar.

Değer: Genel görüntü kazancının ayar derecesi.

**Returns:**
int
### setGainControl(int value) {#setGainControl-int-}
```
public void setGainControl(int value)
```


Genel görüntü kazancı ayarının derecesini alır veya ayarlar.

Değer: Genel görüntü kazancının ayar derecesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGamma() {#getGamma--}
```
public TiffRational getGamma()
```


Gammayı alır veya ayarlar.

Değer: Gamma değeri.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setGamma(TiffRational value) {#setGamma-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setGamma(TiffRational value)
```


Gammayı alır veya ayarlar.

Değer: Gamma değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getISOSpeed() {#getISOSpeed--}
```
public long getISOSpeed()
```


ISO hızını alır veya ayarlar.

Değer: ISO hızı.

**Returns:**
long
### setISOSpeed(long value) {#setISOSpeed-long-}
```
public void setISOSpeed(long value)
```


ISO hızını alır veya ayarlar.

Değer: ISO hızı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getISOSpeedValue() {#getISOSpeedValue--}
```
public final long getISOSpeedValue()
```


ISO hız değerini alır.

Değer: iso hız değeri.

**Returns:**
long - iso hız değeri.
### setISOSpeedValue(long value) {#setISOSpeedValue-long-}
```
public final void setISOSpeedValue(long value)
```


ISO hız değerini ayarlar.

Değer: iso hız değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long | iso hız değeri. |

### getISOSpeedLatitudeYYY() {#getISOSpeedLatitudeYYY--}
```
public long getISOSpeedLatitudeYYY()
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değeri.

Bu etiket ISOSpeed ve ISOSpeedLatitudeZZZ olmadan kaydedilmemelidir.

**Returns:**
long
### setISOSpeedLatitudeYYY(long value) {#setISOSpeedLatitudeYYY-long-}
```
public void setISOSpeedLatitudeYYY(long value)
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi yyy değeri.

Bu etiket ISOSpeed ve ISOSpeedLatitudeZZZ olmadan kaydedilmemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getISOSpeedLatitudeZZZ() {#getISOSpeedLatitudeZZZ--}
```
public long getISOSpeedLatitudeZZZ()
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değeri.

Bu etiket ISOSpeed ve ISOSpeedLatitudeYYY olmadan kaydedilmemelidir.

**Returns:**
long
### setISOSpeedLatitudeZZZ(long value) {#setISOSpeedLatitudeZZZ-long-}
```
public void setISOSpeedLatitudeZZZ(long value)
```


ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değerini alır veya ayarlar.

Değer: ISO 12232'de tanımlanan bir kamera veya giriş cihazının ISO hız enlemi zzz değeri.

Bu etiket ISOSpeed ve ISOSpeedLatitudeYYY olmadan kaydedilmemelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getPhotographicSensitivity() {#getPhotographicSensitivity--}
```
public long getPhotographicSensitivity()
```


Fotoğraf duyarlılığını alır veya ayarlar.

Değer: Fotoğraf duyarlılığı.

**Returns:**
long
### setPhotographicSensitivity(long value) {#setPhotographicSensitivity-long-}
```
public void setPhotographicSensitivity(long value)
```


Fotoğraf duyarlılığını alır veya ayarlar.

Değer: Fotoğraf duyarlılığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getImageUniqueID() {#getImageUniqueID--}
```
public String getImageUniqueID()
```


Görüntünün benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Görüntünün benzersiz tanımlayıcısı.

**Returns:**
java.lang.String
### setImageUniqueID(String value) {#setImageUniqueID-java.lang.String-}
```
public void setImageUniqueID(String value)
```


Görüntünün benzersiz tanımlayıcısını alır veya ayarlar.

Değer: Görüntünün benzersiz tanımlayıcısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLensMake() {#getLensMake--}
```
public String getLensMake()
```


Lens üreticisini alır veya ayarlar.

Değer: Lens üreticisi.

**Returns:**
java.lang.String
### setLensMake(String value) {#setLensMake-java.lang.String-}
```
public void setLensMake(String value)
```


Lens üreticisini alır veya ayarlar.

Değer: Lens üreticisi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLensModel() {#getLensModel--}
```
public String getLensModel()
```


Lens modelini alır veya ayarlar.

Değer: Lens modeli.

**Returns:**
java.lang.String
### setLensModel(String value) {#setLensModel-java.lang.String-}
```
public void setLensModel(String value)
```


Lens modelini alır veya ayarlar.

Değer: Lens modeli.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLensSerialNumber() {#getLensSerialNumber--}
```
public String getLensSerialNumber()
```


Lens seri numarasını alır veya ayarlar.

Değer: Lens seri numarası.

**Returns:**
java.lang.String
### setLensSerialNumber(String value) {#setLensSerialNumber-java.lang.String-}
```
public void setLensSerialNumber(String value)
```


Lens seri numarasını alır veya ayarlar.

Değer: Lens seri numarası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getLensSpecification() {#getLensSpecification--}
```
public TiffRational[] getLensSpecification()
```


Lens özelliklerini alır veya ayarlar

Değer: Lens özellikleri.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setLensSpecification(TiffRational[] value) {#setLensSpecification-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setLensSpecification(TiffRational[] value)
```


Lens özelliklerini alır veya ayarlar

Değer: Lens özellikleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getLightSource() {#getLightSource--}
```
public int getLightSource()
```


Işık kaynağını alır veya ayarlar.

Değer: Işık kaynağı.

**Returns:**
int
### setLightSource(int value) {#setLightSource-int-}
```
public void setLightSource(int value)
```


Işık kaynağını alır veya ayarlar.

Değer: Işık kaynağı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getMakerNoteData() {#getMakerNoteData--}
```
public TiffDataType[] getMakerNoteData()
```


Üretici not verisini alır.

Değer: Üretici notu verileri.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### getMakerNoteRawData() {#getMakerNoteRawData--}
```
public byte[] getMakerNoteRawData()
```


Üretici not ham verisini alır veya ayarlar.

Değer: Üretici notu ham verileri.

**Returns:**
byte[]
### setMakerNoteRawData(byte[] value) {#setMakerNoteRawData-byte---}
```
public void setMakerNoteRawData(byte[] value)
```


Üretici not ham verisini alır veya ayarlar.

Değer: Üretici notu ham verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getMakerNotes() {#getMakerNotes--}
```
public final MakerNote[] getMakerNotes()
```


Üretici notlarını alır.

Değer: Üretici notları.

**Returns:**
com.aspose.imaging.exif.MakerNote[] - üretici notları.

**Example: Access camera manufacturer maker notes in Jpeg image.**

``` java
try (JpegImage image = (JpegImage)Image.load("Sample.jpg"))
{
    for (MakerNote makerNote : image.getExifData().getMakerNotes())
    {
        System.out.format("Name = %s, Value = %s", makerNote.getName(), makerNote.getValue());
    }
}
```

### getMaxApertureValue() {#getMaxApertureValue--}
```
public TiffRational getMaxApertureValue()
```


Maksimum diyafram değerini alır veya ayarlar.

Değer: Maksimum diyafram değeri.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setMaxApertureValue(TiffRational value) {#setMaxApertureValue-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setMaxApertureValue(TiffRational value)
```


Maksimum diyafram değerini alır veya ayarlar.

Değer: Maksimum diyafram değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getMeteringMode() {#getMeteringMode--}
```
public int getMeteringMode()
```


Ölçüm modunu alır veya ayarlar.

Değer: Ölçüm modu.

**Returns:**
int
### setMeteringMode(int value) {#setMeteringMode-int-}
```
public void setMeteringMode(int value)
```


Ölçüm modunu alır veya ayarlar.

Değer: Ölçüm modu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOECF() {#getOECF--}
```
public byte[] getOECF()
```


ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar.

Değer: ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonu (OECF).

**Returns:**
byte[]
### setOECF(byte[] value) {#setOECF-byte---}
```
public void setOECF(byte[] value)
```


ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonunu (OECF) alır veya ayarlar.

Değer: ISO 14524'te belirtilen Opto-Elektrik Dönüşüm Fonksiyonu (OECF).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


Yönü alır [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Değer: Yön.

**Returns:**
int - yön.
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


Yönü ayarlar [ExifOrientation](../../com.aspose.imaging.exif.enums/exiforientation).

Değer: Yön.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | yön. |

### getPixelXDimension() {#getPixelXDimension--}
```
public long getPixelXDimension()
```


Piksel x boyutunu alır veya ayarlar.

Değer: Piksel x boyutu.

**Returns:**
long
### setPixelXDimension(long value) {#setPixelXDimension-long-}
```
public void setPixelXDimension(long value)
```


Piksel x boyutunu alır veya ayarlar.

Değer: Piksel x boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getPixelYDimension() {#getPixelYDimension--}
```
public long getPixelYDimension()
```


Piksel y boyutunu alır veya ayarlar.

Değer: Piksel y boyutu.

**Returns:**
long
### setPixelYDimension(long value) {#setPixelYDimension-long-}
```
public void setPixelYDimension(long value)
```


Piksel y boyutunu alır veya ayarlar.

Değer: Piksel y boyutu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getProperties() {#getProperties--}
```
public TiffDataType[] getProperties()
```


Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar.

Değer: EXIF etiketleri (ortak ve GPS etiketleri dahil).

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setProperties(TiffDataType[] value) {#setProperties-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setProperties(TiffDataType[] value)
```


Tüm EXIF etiketlerini (ortak ve GPS etiketleri dahil) alır veya ayarlar.

Değer: EXIF etiketleri (ortak ve GPS etiketleri dahil).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getRecommendedExposureIndex() {#getRecommendedExposureIndex--}
```
public long getRecommendedExposureIndex()
```


Önerilen pozlama indeksini alır veya ayarlar.

Değer: Önerilen pozlama indeksi.

**Returns:**
long
### setRecommendedExposureIndex(long value) {#setRecommendedExposureIndex-long-}
```
public void setRecommendedExposureIndex(long value)
```


Önerilen pozlama indeksini alır veya ayarlar.

Değer: Önerilen pozlama indeksi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getRelatedSoundFile() {#getRelatedSoundFile--}
```
public String getRelatedSoundFile()
```


İlgili ses dosyasını alır veya ayarlar.

Değer: İlgili ses dosyası.

**Returns:**
java.lang.String
### setRelatedSoundFile(String value) {#setRelatedSoundFile-java.lang.String-}
```
public void setRelatedSoundFile(String value)
```


İlgili ses dosyasını alır veya ayarlar.

Değer: İlgili ses dosyası.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSaturation() {#getSaturation--}
```
public int getSaturation()
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Returns:**
int
### setSaturation(int value) {#setSaturation-int-}
```
public void setSaturation(int value)
```


Doygunluğu alır veya ayarlar.

Değer: Doygunluk.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSceneCaptureType() {#getSceneCaptureType--}
```
public int getSceneCaptureType()
```


Sahne yakalama tipini alır veya ayarlar.

Değer: Sahne yakalama türü.

**Returns:**
int
### setSceneCaptureType(int value) {#setSceneCaptureType-int-}
```
public void setSceneCaptureType(int value)
```


Sahne yakalama tipini alır veya ayarlar.

Değer: Sahne yakalama türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSceneType() {#getSceneType--}
```
public byte getSceneType()
```


Sahne tipini alır veya ayarlar.

Değer: Sahne türü.

**Returns:**
byte
### setSceneType(byte value) {#setSceneType-byte-}
```
public void setSceneType(byte value)
```


Sahne tipini alır veya ayarlar.

Değer: Sahne türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getSensingMethod() {#getSensingMethod--}
```
public int getSensingMethod()
```


Algılama yöntemini alır veya ayarlar.

Değer: Algılama yöntemi.

**Returns:**
int
### setSensingMethod(int value) {#setSensingMethod-int-}
```
public void setSensingMethod(int value)
```


Algılama yöntemini alır veya ayarlar.

Değer: Algılama yöntemi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSensitivityType() {#getSensitivityType--}
```
public int getSensitivityType()
```


Duyarlılık tipini alır veya ayarlar.

Değer: Hassasiyet türü.

**Returns:**
int
### setSensitivityType(int value) {#setSensitivityType-int-}
```
public void setSensitivityType(int value)
```


Duyarlılık tipini alır veya ayarlar.

Değer: Hassasiyet türü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSharpness() {#getSharpness--}
```
public int getSharpness()
```


Keskinliği alır veya ayarlar.

Değer: Keskinlik.

**Returns:**
int
### setSharpness(int value) {#setSharpness-int-}
```
public void setSharpness(int value)
```


Keskinliği alır veya ayarlar.

Değer: Keskinlik.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getShutterSpeedValue() {#getShutterSpeedValue--}
```
public TiffSRational getShutterSpeedValue()
```


Deklanşör hızı değerini alır veya ayarlar.

Değer: Enstantane hızı değeri.

**Returns:**
[TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational)
### setShutterSpeedValue(TiffSRational value) {#setShutterSpeedValue-com.aspose.imaging.fileformats.tiff.TiffSRational-}
```
public void setShutterSpeedValue(TiffSRational value)
```


Deklanşör hızı değerini alır veya ayarlar.

Değer: Enstantane hızı değeri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffSRational](../../com.aspose.imaging.fileformats.tiff/tiffsrational) |  |

### getSpatialFrequencyResponse() {#getSpatialFrequencyResponse--}
```
public byte[] getSpatialFrequencyResponse()
```


Uzamsal frekans yanıtını alır veya ayarlar.

Değer: Uzamsal frekans yanıtı.

**Returns:**
byte[]
### setSpatialFrequencyResponse(byte[] value) {#setSpatialFrequencyResponse-byte---}
```
public void setSpatialFrequencyResponse(byte[] value)
```


Uzamsal frekans yanıtını alır veya ayarlar.

Değer: Uzamsal frekans yanıtı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

### getSpectralSensitivity() {#getSpectralSensitivity--}
```
public String getSpectralSensitivity()
```


Spektral duyarlılığı alır veya ayarlar.

Değer: Spektral hassasiyet.

**Returns:**
java.lang.String
### setSpectralSensitivity(String value) {#setSpectralSensitivity-java.lang.String-}
```
public void setSpectralSensitivity(String value)
```


Spektral duyarlılığı alır veya ayarlar.

Değer: Spektral hassasiyet.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getStandardOutputSensitivity() {#getStandardOutputSensitivity--}
```
public long getStandardOutputSensitivity()
```


Standart çıkış duyarlılığını alır

Değer: Standart çıkış duyarlılığı.

**Returns:**
long
### setStandardOutputSensitivity(long value) {#setStandardOutputSensitivity-long-}
```
public void setStandardOutputSensitivity(long value)
```


Standart çıkış duyarlılığını ayarlar

Değer: Standart çıkış duyarlılığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getSubjectArea() {#getSubjectArea--}
```
public int[] getSubjectArea()
```


Konu alanını alır veya ayarlar.

Değer: Konu alanı.

**Returns:**
int[]
### setSubjectArea(int[] value) {#setSubjectArea-int---}
```
public void setSubjectArea(int[] value)
```


Konu alanını alır veya ayarlar.

Değer: Konu alanı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getSubjectDistance() {#getSubjectDistance--}
```
public TiffRational getSubjectDistance()
```


Konu mesafesini alır veya ayarlar.

Değer: Konu mesafesi.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setSubjectDistance(TiffRational value) {#setSubjectDistance-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setSubjectDistance(TiffRational value)
```


Konu mesafesini alır veya ayarlar.

Değer: Konu mesafesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getSubjectDistanceRange() {#getSubjectDistanceRange--}
```
public int getSubjectDistanceRange()
```


Konu mesafe aralığını alır veya ayarlar.

Değer: Konu mesafe aralığı.

**Returns:**
int
### setSubjectDistanceRange(int value) {#setSubjectDistanceRange-int-}
```
public void setSubjectDistanceRange(int value)
```


Konu mesafe aralığını alır veya ayarlar.

Değer: Konu mesafe aralığı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSubjectLocation() {#getSubjectLocation--}
```
public int[] getSubjectLocation()
```


Konu konumunu alır veya ayarlar.

Değer: Konu konumu.

**Returns:**
int[]
### setSubjectLocation(int[] value) {#setSubjectLocation-int---}
```
public void setSubjectLocation(int[] value)
```


Konu konumunu alır veya ayarlar.

Değer: Konu konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getSubsecTime() {#getSubsecTime--}
```
public String getSubsecTime()
```


DateTime etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTime etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### setSubsecTime(String value) {#setSubsecTime-java.lang.String-}
```
public void setSubsecTime(String value)
```


DateTime etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTime etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubsecTimeDigitized() {#getSubsecTimeDigitized--}
```
public String getSubsecTimeDigitized()
```


DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeDigitized etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### setSubsecTimeDigitized(String value) {#setSubsecTimeDigitized-java.lang.String-}
```
public void setSubsecTimeDigitized(String value)
```


DateTimeDigitized etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeDigitized etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getSubsecTimeOriginal() {#getSubsecTimeOriginal--}
```
public String getSubsecTimeOriginal()
```


DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeOriginal etiketi için saniyenin kesirleri.

**Returns:**
java.lang.String
### setSubsecTimeOriginal(String value) {#setSubsecTimeOriginal-java.lang.String-}
```
public void setSubsecTimeOriginal(String value)
```


DateTimeOriginal etiketi için saniyenin kesirlerini alır veya ayarlar.

Değer: DateTimeOriginal etiketi için saniyenin kesirleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getUserComment() {#getUserComment--}
```
public String getUserComment()
```


Kullanıcı yorumunu alır veya ayarlar.

Değer: Kullanıcı yorumu.

**Returns:**
java.lang.String
### setUserComment(String value) {#setUserComment-java.lang.String-}
```
public void setUserComment(String value)
```


Kullanıcı yorumunu alır veya ayarlar.

Değer: Kullanıcı yorumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getWhiteBalance() {#getWhiteBalance--}
```
public int getWhiteBalance()
```


Beyaz dengesini alır veya ayarlar.

Değer: Beyaz dengesi.

**Returns:**
int
### setWhiteBalance(int value) {#setWhiteBalance-int-}
```
public void setWhiteBalance(int value)
```


Beyaz dengesini alır veya ayarlar.

Değer: Beyaz dengesi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWhitePoint() {#getWhitePoint--}
```
public TiffRational[] getWhitePoint()
```


Görüntünün beyaz noktasının kromatik değerini alır veya ayarlar.

Değer: Görüntünün beyaz noktasının kromatikliği.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setWhitePoint(TiffRational[] value) {#setWhitePoint-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setWhitePoint(TiffRational[] value)
```


Görüntünün beyaz noktasının kromatik değerini alır veya ayarlar.

Değer: Görüntünün beyaz noktasının kromatikliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getCommonTags() {#getCommonTags--}
```
public TiffDataType[] getCommonTags()
```


Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılır.

Değer: Ortak bölüm etiketleri.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setCommonTags(TiffDataType[] value) {#setCommonTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setCommonTags(TiffDataType[] value)
```


Ortak bölüme ait etiketleri alır veya ayarlar. Bu yalnızca jpeg görüntüler için geçerlidir, tiff formatında ise tiffOptions kullanılır.

Değer: Ortak bölüm etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getExifTags() {#getExifTags--}
```
public TiffDataType[] getExifTags()
```


Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar.

Değer: EXIF bölüm etiketleri.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setExifTags(TiffDataType[] value) {#setExifTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setExifTags(TiffDataType[] value)
```


Yalnızca EXIF bölümüne ait etiketleri alır veya ayarlar.

Değer: EXIF bölüm etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getGPSTags() {#getGPSTags--}
```
public TiffDataType[] getGPSTags()
```


Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar.

Değer: GPS etiketleri.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffDataType[]
### setGPSTags(TiffDataType[] value) {#setGPSTags-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public void setGPSTags(TiffDataType[] value)
```


Yalnızca GPS bölümüne ait etiketleri alır veya ayarlar.

Değer: GPS etiketleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) |  |

### getThumbnail() {#getThumbnail--}
```
public final RasterImage getThumbnail()
```


Küçük resmi alır.

**Returns:**
[RasterImage](../../com.aspose.imaging/rasterimage) - the thumbnail image.
### setThumbnail(RasterImage value) {#setThumbnail-com.aspose.imaging.RasterImage-}
```
public final void setThumbnail(RasterImage value)
```


Küçük resmi ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [RasterImage](../../com.aspose.imaging/rasterimage) | küçük resim. |

### getXResolutionInt() {#getXResolutionInt--}
```
public final int getXResolutionInt()
```


x çözünürlüğünü alır.

Değer: x çözünürlüğü.

**Returns:**
int - x çözünürlüğü.
### setXResolution(int value) {#setXResolution-int-}
```
public final void setXResolution(int value)
```


x çözünürlüğünü ayarlar.

Değer: x çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | x çözünürlüğü. |

### getYResolutionInt() {#getYResolutionInt--}
```
public final int getYResolutionInt()
```


y çözünürlüğünü alır.

Değer: y çözünürlüğü.

**Returns:**
int - y çözünürlüğü.
### setYResolution(int value) {#setYResolution-int-}
```
public final void setYResolution(int value)
```


y çözünürlüğünü ayarlar.

Değer: y çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | y çözünürlüğü. |

### removeTag(int tagId) {#removeTag-int-}
```
public void removeTag(int tagId)
```


Etiketi konteynerden kaldır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagId | int | Kaldırılacak etiket tanımlayıcısı. |

### getTagValue(int key) {#getTagValue-int-}
```
public final TiffDataType getTagValue(int key)
```


Etiket değerini alır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| key | int | Etiket anahtarı [ExifProperties](../../com.aspose.imaging.exif/exifproperties). |

**Returns:**
[TiffDataType](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) - The TiffDataType
