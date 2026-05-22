---
title: "JpegExifData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "jpeg dosyaları için EXIF veri kapsayıcısı."
type: docs
weight: 12
url: /tr/java/com.aspose.imaging.exif/jpegexifdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.exif.TiffDataTypeController](../../com.aspose.imaging.exif/tiffdatatypecontroller), [com.aspose.imaging.exif.ExifData](../../com.aspose.imaging.exif/exifdata)
```
public final class JpegExifData extends ExifData
```

jpeg dosyaları için EXIF veri kapsayıcısı.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [JpegExifData()](#JpegExifData--) | Yeni bir `JpegExifData` sınıfı örneği başlatır. |
| [JpegExifData(TiffDataType[] exifData)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---) | Diziden veri ile yeni bir `JpegExifData` sınıfı örneği başlatır. |
| [JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)](#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---) | Diziden veri ile yeni bir `JpegExifData` sınıfı örneği başlatır. |
| [JpegExifData(ExifData exifData)](#JpegExifData-com.aspose.imaging.exif.ExifData-) | Diziden veri ile yeni bir [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) sınıfı örneği başlatır. |
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [MAX_EXIF_SEGMENT_SIZE](#MAX-EXIF-SEGMENT-SIZE) | İzin verilen maksimum EXIF segment boyutu (bayt olarak). |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArtist()](#getArtist--) | Sanatçıyı alır veya ayarlar. |
| [setArtist(String value)](#setArtist-java.lang.String-) | Sanatçıyı alır veya ayarlar. |
| [getBitsPerSample()](#getBitsPerSample--) | Örnek başına bitleri alır veya ayarlar. |
| [setBitsPerSample(int[] value)](#setBitsPerSample-int---) | Örnek başına bitleri alır veya ayarlar. |
| [getCompression()](#getCompression--) | Sıkıştırmayı alır veya ayarlar. |
| [setCompression(int value)](#setCompression-int-) | Sıkıştırmayı alır veya ayarlar. |
| [getCopyright()](#getCopyright--) | Telif hakkını alır veya ayarlar. |
| [setCopyright(String value)](#setCopyright-java.lang.String-) | Telif hakkını alır veya ayarlar. |
| [getDateTime()](#getDateTime--) | Tarih ve zamanı alır veya ayarlar. |
| [setDateTime(String value)](#setDateTime-java.lang.String-) | Tarih ve zamanı alır veya ayarlar. |
| [getImageDescription()](#getImageDescription--) | Görüntü açıklamasını alır veya ayarlar. |
| [setImageDescription(String value)](#setImageDescription-java.lang.String-) | Görüntü açıklamasını alır veya ayarlar. |
| [getImageLength()](#getImageLength--) | Görüntü uzunluğunu alır veya ayarlar. |
| [setImageLength(long value)](#setImageLength-long-) | Görüntü uzunluğunu alır veya ayarlar. |
| [getImageWidth()](#getImageWidth--) | Görüntü genişliğini alır veya ayarlar. |
| [setImageWidth(long value)](#setImageWidth-long-) | Görüntü genişliğini alır veya ayarlar. |
| [getModel()](#getModel--) | Modeli alır veya ayarlar. |
| [setModel(String value)](#setModel-java.lang.String-) | Modeli alır veya ayarlar. |
| [getPhotometricInterpretation()](#getPhotometricInterpretation--) | Fotometrik yorumu alır veya ayarlar. |
| [setPhotometricInterpretation(int value)](#setPhotometricInterpretation-int-) | Fotometrik yorumu alır veya ayarlar. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Planar yapılandırmayı alır veya ayarlar. |
| [setPlanarConfiguration(int value)](#setPlanarConfiguration-int-) | Planar yapılandırmayı alır veya ayarlar. |
| [getPrimaryChromaticities()](#getPrimaryChromaticities--) | Görüntünün üç ana renginin kromatikliğini alır veya ayarlar. |
| [setPrimaryChromaticities(TiffRational[] value)](#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---) | Görüntünün üç ana renginin kromatikliğini alır veya ayarlar. |
| [getReferenceBlackWhite()](#getReferenceBlackWhite--) | Referans siyah beyazı alır veya ayarlar. |
| [setReferenceBlackWhite(TiffRational[] value)](#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---) | Referans siyah beyazı alır veya ayarlar. |
| [getResolutionUnit()](#getResolutionUnit--) | Çözünürlük birimini alır veya ayarlar. |
| [setResolutionUnit(int value)](#setResolutionUnit-int-) | Çözünürlük birimini alır veya ayarlar. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | Piksel başına örnekleri alır veya ayarlar. |
| [setSamplesPerPixel(int value)](#setSamplesPerPixel-int-) | Piksel başına örnekleri alır veya ayarlar. |
| [getSoftware()](#getSoftware--) | Yazılımı alır veya ayarlar. |
| [setSoftware(String value)](#setSoftware-java.lang.String-) | Yazılımı alır veya ayarlar. |
| [getTransferFunction()](#getTransferFunction--) | Transfer fonksiyonunu alır veya ayarlar. |
| [setTransferFunction(int[] value)](#setTransferFunction-int---) | Transfer fonksiyonunu alır veya ayarlar. |
| [getXResolution()](#getXResolution--) | X çözünürlüğünü alır veya ayarlar. |
| [setXResolution(TiffRational value)](#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | X çözünürlüğünü alır veya ayarlar. |
| [getYCbCrCoefficients()](#getYCbCrCoefficients--) | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar. |
| [setYCbCrCoefficients(TiffRational[] value)](#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---) | RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar. |
| [getYCbCrPositioning()](#getYCbCrPositioning--) | Luminans bileşenine göre krominans bileşenlerinin konumunu alır veya ayarlar. |
| [setYCbCrPositioning(int value)](#setYCbCrPositioning-int-) | Luminans bileşenine göre krominans bileşenlerinin konumunu alır veya ayarlar. |
| [getYCbCrSubSampling()](#getYCbCrSubSampling--) | Luminans bileşenine göre krominans bileşenlerinin örnekleme oranını alır veya ayarlar. |
| [setYCbCrSubSampling(int[] value)](#setYCbCrSubSampling-int---) | Luminans bileşenine göre krominans bileşenlerinin örnekleme oranını alır veya ayarlar. |
| [getYResolution()](#getYResolution--) | Y çözünürlüğünü alır veya ayarlar. |
| [setYResolution(TiffRational value)](#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-) | Y çözünürlüğünü alır veya ayarlar. |
| [serializeExifData()](#serializeExifData--) | EXIF verilerini serileştirir. |
### JpegExifData() {#JpegExifData--}
```
public JpegExifData()
```


Yeni bir `JpegExifData` sınıfı örneği başlatır.

### JpegExifData(TiffDataType[] exifData) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] exifData)
```


Diziden veri ile yeni bir `JpegExifData` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exifData | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags) {#JpegExifData-com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---com.aspose.imaging.fileformats.tiff.TiffDataType---}
```
public JpegExifData(TiffDataType[] commonTags, TiffDataType[] exifTags, TiffDataType[] gpsTags)
```


Diziden veri ile yeni bir `JpegExifData` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| commonTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | Ortak etiketler. |
| exifTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | EXIF etiketleri. |
| gpsTags | [TiffDataType\[\]](../../com.aspose.imaging.fileformats.tiff/tiffdatatype) | GPS etiketleri. |

### JpegExifData(ExifData exifData) {#JpegExifData-com.aspose.imaging.exif.ExifData-}
```
public JpegExifData(ExifData exifData)
```


Diziden veri ile yeni bir [JpegExifData](../../com.aspose.imaging.exif/jpegexifdata) sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| exifData | [ExifData](../../com.aspose.imaging.exif/exifdata) | Ortak ve GPS etiketleriyle birlikte EXIF etiketlerinin dizisi. |

### MAX_EXIF_SEGMENT_SIZE {#MAX-EXIF-SEGMENT-SIZE}
```
public static final int MAX_EXIF_SEGMENT_SIZE
```


İzin verilen maksimum EXIF segment boyutu (bayt olarak).

### getArtist() {#getArtist--}
```
public String getArtist()
```


Sanatçıyı alır veya ayarlar.

Değer: Sanatçı.

**Returns:**
java.lang.String
### setArtist(String value) {#setArtist-java.lang.String-}
```
public void setArtist(String value)
```


Sanatçıyı alır veya ayarlar.

Değer: Sanatçı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getBitsPerSample() {#getBitsPerSample--}
```
public int[] getBitsPerSample()
```


Örnek başına bitleri alır veya ayarlar.

Değer: Örnek başına bit.

**Returns:**
int[]
### setBitsPerSample(int[] value) {#setBitsPerSample-int---}
```
public void setBitsPerSample(int[] value)
```


Örnek başına bitleri alır veya ayarlar.

Değer: Örnek başına bit.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getCompression() {#getCompression--}
```
public int getCompression()
```


Sıkıştırmayı alır veya ayarlar.

Değer: Sıkıştırma.

**Returns:**
int
### setCompression(int value) {#setCompression-int-}
```
public void setCompression(int value)
```


Sıkıştırmayı alır veya ayarlar.

Değer: Sıkıştırma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCopyright() {#getCopyright--}
```
public String getCopyright()
```


Telif hakkını alır veya ayarlar.

Değer: Telif hakkı.

**Returns:**
java.lang.String
### setCopyright(String value) {#setCopyright-java.lang.String-}
```
public void setCopyright(String value)
```


Telif hakkını alır veya ayarlar.

Değer: Telif hakkı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getDateTime() {#getDateTime--}
```
public String getDateTime()
```


Tarih ve zamanı alır veya ayarlar.

Değer: Tarih ve zaman.

**Returns:**
java.lang.String
### setDateTime(String value) {#setDateTime-java.lang.String-}
```
public void setDateTime(String value)
```


Tarih ve zamanı alır veya ayarlar.

Değer: Tarih ve zaman.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getImageDescription() {#getImageDescription--}
```
public String getImageDescription()
```


Görüntü açıklamasını alır veya ayarlar.

Değer: Görüntü açıklaması.

**Returns:**
java.lang.String
### setImageDescription(String value) {#setImageDescription-java.lang.String-}
```
public void setImageDescription(String value)
```


Görüntü açıklamasını alır veya ayarlar.

Değer: Görüntü açıklaması.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getImageLength() {#getImageLength--}
```
public long getImageLength()
```


Görüntü uzunluğunu alır veya ayarlar.

Değer: Görüntünün uzunluğu.

**Returns:**
long
### setImageLength(long value) {#setImageLength-long-}
```
public void setImageLength(long value)
```


Görüntü uzunluğunu alır veya ayarlar.

Değer: Görüntünün uzunluğu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getImageWidth() {#getImageWidth--}
```
public long getImageWidth()
```


Görüntü genişliğini alır veya ayarlar.

Değer: Görüntünün genişliği.

**Returns:**
long
### setImageWidth(long value) {#setImageWidth-long-}
```
public void setImageWidth(long value)
```


Görüntü genişliğini alır veya ayarlar.

Değer: Görüntünün genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | long |  |

### getModel() {#getModel--}
```
public String getModel()
```


Modeli alır veya ayarlar.

Değer: Model.

**Returns:**
java.lang.String
### setModel(String value) {#setModel-java.lang.String-}
```
public void setModel(String value)
```


Modeli alır veya ayarlar.

Değer: Model.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getPhotometricInterpretation() {#getPhotometricInterpretation--}
```
public int getPhotometricInterpretation()
```


Fotometrik yorumu alır veya ayarlar.

Değer: Fotometrik yorum.

**Returns:**
int
### setPhotometricInterpretation(int value) {#setPhotometricInterpretation-int-}
```
public void setPhotometricInterpretation(int value)
```


Fotometrik yorumu alır veya ayarlar.

Değer: Fotometrik yorum.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Planar yapılandırmayı alır veya ayarlar.

Değer: Düzlemsel yapılandırma.

**Returns:**
int
### setPlanarConfiguration(int value) {#setPlanarConfiguration-int-}
```
public void setPlanarConfiguration(int value)
```


Planar yapılandırmayı alır veya ayarlar.

Değer: Düzlemsel yapılandırma.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPrimaryChromaticities() {#getPrimaryChromaticities--}
```
public TiffRational[] getPrimaryChromaticities()
```


Görüntünün üç ana renginin kromatikliğini alır veya ayarlar.

Değer: Görüntünün üç ana renginin kromatikliği.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setPrimaryChromaticities(TiffRational[] value) {#setPrimaryChromaticities-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setPrimaryChromaticities(TiffRational[] value)
```


Görüntünün üç ana renginin kromatikliğini alır veya ayarlar.

Değer: Görüntünün üç ana renginin kromatikliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getReferenceBlackWhite() {#getReferenceBlackWhite--}
```
public TiffRational[] getReferenceBlackWhite()
```


Referans siyah beyazı alır veya ayarlar.

Değer: Referans siyah beyaz.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setReferenceBlackWhite(TiffRational[] value) {#setReferenceBlackWhite-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setReferenceBlackWhite(TiffRational[] value)
```


Referans siyah beyazı alır veya ayarlar.

Değer: Referans siyah beyaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getResolutionUnit() {#getResolutionUnit--}
```
public int getResolutionUnit()
```


Çözünürlük birimini alır veya ayarlar.

Değer: Çözünürlük birimi.

**Returns:**
int
### setResolutionUnit(int value) {#setResolutionUnit-int-}
```
public void setResolutionUnit(int value)
```


Çözünürlük birimini alır veya ayarlar.

Değer: Çözünürlük birimi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


Piksel başına örnekleri alır veya ayarlar.

Değer: Piksel başına örnek sayısı.

**Returns:**
int
### setSamplesPerPixel(int value) {#setSamplesPerPixel-int-}
```
public void setSamplesPerPixel(int value)
```


Piksel başına örnekleri alır veya ayarlar.

Değer: Piksel başına örnek sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSoftware() {#getSoftware--}
```
public String getSoftware()
```


Yazılımı alır veya ayarlar.

Değer: Yazılım.

**Returns:**
java.lang.String
### setSoftware(String value) {#setSoftware-java.lang.String-}
```
public void setSoftware(String value)
```


Yazılımı alır veya ayarlar.

Değer: Yazılım.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getTransferFunction() {#getTransferFunction--}
```
public int[] getTransferFunction()
```


Transfer fonksiyonunu alır veya ayarlar.

Değer: Transfer fonksiyonu.

**Returns:**
int[]
### setTransferFunction(int[] value) {#setTransferFunction-int---}
```
public void setTransferFunction(int[] value)
```


Transfer fonksiyonunu alır veya ayarlar.

Değer: Transfer fonksiyonu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getXResolution() {#getXResolution--}
```
public TiffRational getXResolution()
```


X çözünürlüğünü alır veya ayarlar.

Değer: x çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setXResolution(TiffRational value) {#setXResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setXResolution(TiffRational value)
```


X çözünürlüğünü alır veya ayarlar.

Değer: x çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrCoefficients() {#getYCbCrCoefficients--}
```
public TiffRational[] getYCbCrCoefficients()
```


RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar.

Değer: RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları.

**Returns:**
com.aspose.imaging.fileformats.tiff.TiffRational[]
### setYCbCrCoefficients(TiffRational[] value) {#setYCbCrCoefficients-com.aspose.imaging.fileformats.tiff.TiffRational---}
```
public void setYCbCrCoefficients(TiffRational[] value)
```


RGB'den YCbCr görüntü verisine dönüşüm için matris katsayılarını alır veya ayarlar.

Değer: RGB'den YCbCr görüntü verisine dönüşüm için matris katsayıları.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational\[\]](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### getYCbCrPositioning() {#getYCbCrPositioning--}
```
public int getYCbCrPositioning()
```


Luminans bileşenine göre krominans bileşenlerinin konumunu alır veya ayarlar.

Değer: Luminans bileşenine göre krominans bileşenlerinin konumu.

**Returns:**
int
### setYCbCrPositioning(int value) {#setYCbCrPositioning-int-}
```
public void setYCbCrPositioning(int value)
```


Luminans bileşenine göre krominans bileşenlerinin konumunu alır veya ayarlar.

Değer: Luminans bileşenine göre krominans bileşenlerinin konumu.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYCbCrSubSampling() {#getYCbCrSubSampling--}
```
public int[] getYCbCrSubSampling()
```


Luminans bileşenine göre krominans bileşenlerinin örnekleme oranını alır veya ayarlar.

Değer: Luminans bileşenine göre krominans bileşenlerinin örnekleme oranı.

**Returns:**
int[]
### setYCbCrSubSampling(int[] value) {#setYCbCrSubSampling-int---}
```
public void setYCbCrSubSampling(int[] value)
```


Luminans bileşenine göre krominans bileşenlerinin örnekleme oranını alır veya ayarlar.

Değer: Luminans bileşenine göre krominans bileşenlerinin örnekleme oranı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int[] |  |

### getYResolution() {#getYResolution--}
```
public TiffRational getYResolution()
```


Y çözünürlüğünü alır veya ayarlar.

Değer: y çözünürlüğü.

**Returns:**
[TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational)
### setYResolution(TiffRational value) {#setYResolution-com.aspose.imaging.fileformats.tiff.TiffRational-}
```
public void setYResolution(TiffRational value)
```


Y çözünürlüğünü alır veya ayarlar.

Değer: y çözünürlüğü.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [TiffRational](../../com.aspose.imaging.fileformats.tiff/tiffrational) |  |

### serializeExifData() {#serializeExifData--}
```
public byte[] serializeExifData()
```


EXIF verilerini serileştirir. Etiket değerlerini ve içeriklerini yazar. En çok etki eden boyut etiketi Thumbnail etiket içeriğidir.

**Returns:**
byte[] - Serileştirilmiş EXIF verisi.

Doğru jpeg görüntüsü üretmek için toplam segment boyutu MaxExifSegmentSize baytına eşit veya daha küçük olmalıdır. İpucu: çok büyük bir EXIF bölüm boyutunuz varsa thumbnail boyutunu azaltmayı veya sıkıştırmasını değiştirmeyi deneyin.
