---
title: "DicomImageInfo"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dicom dosya başlığından tüm meta-bilgileri içerir."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.fileformats.dicom/dicomimageinfo/
---
**Inheritance:**
java.lang.Object
```
public class DicomImageInfo
```

Dicom dosya başlığından tüm meta-bilgileri içerir.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getDicomHeaderInfoByBytes()](#getDicomHeaderInfoByBytes--) | Dicom başlık bilgilerini bayt olarak alır. |
| [getPlanarConfiguration()](#getPlanarConfiguration--) | Planar yapılandırmayı alır. |
| [getSignedImage()](#getSignedImage--) | \"signedImage\" olup olmadığını gösteren bir değeri alır. |
| [getDicomInfo()](#getDicomInfo--) | DICOM dosyasının başlık bilgilerini alır. |
| [getSamplesPerPixel()](#getSamplesPerPixel--) | \"samplesPerPixel\" değerini alır. |
| [getBitsAllocated()](#getBitsAllocated--) | \"bitsAllocated\" değerini alır. |
| [getBitsStored()](#getBitsStored--) | Depolanan bit sayısını alır. |
| [getPhotoInterpretation()](#getPhotoInterpretation--) | \"PhotoInterpretation\" değerini alır. |
| [getWidth()](#getWidth--) | Genişliği alır. |
| [getHeight()](#getHeight--) | Yüksekliği alır. |
| [getWindowCentre()](#getWindowCentre--) | Pencere merkezini alır. |
| [getWindowWidth()](#getWindowWidth--) | Pencerenin genişliğini alır. |
| [getPixelRepresentation()](#getPixelRepresentation--) | Piksel \"pixelRepresentation\" değerini alır. |
| [getRescaleIntercept()](#getRescaleIntercept--) | \"rescaleIntercept\" değerini alır. |
| [getRescaleSlope()](#getRescaleSlope--) | \"rescaleSlope\" değerini alır. |
| [getNumberOfFrames()](#getNumberOfFrames--) | Kare sayısını alır. |
| [isLittleEndian()](#isLittleEndian--) | Bu örneğin little endian olup olmadığını gösteren bir değeri alır. |
| [getReds()](#getReds--) | Kırmızı renk dizisini alır. |
| [getGreens()](#getGreens--) | Yeşil renk dizisini alır. |
| [getBlues()](#getBlues--) | Mavi renk dizisini alır. |
| [getOffset()](#getOffset--) | Ofseti alır. |
| [addTag(String tagDescription, Object value)](#addTag-java.lang.String-java.lang.Object-) | Yeni Dicom etiketi ekle. |
| [tryAddTag(String tagDescription, Object value)](#tryAddTag-java.lang.String-java.lang.Object-) | Yeni Dicom etiketi ekle. |
| [removeTagAt(int index)](#removeTagAt-int-) | Mevcut bir etiketi kaldır. |
| [tryRemoveTagAt(int index)](#tryRemoveTagAt-int-) | Mevcut bir etiketi kaldır. |
| [updateTagAt(int index, Object newValue)](#updateTagAt-int-java.lang.Object-) | Mevcut bir etiketi güncelle. |
| [tryUpdateTagAt(int index, Object newValue)](#tryUpdateTagAt-int-java.lang.Object-) | Mevcut bir etiketi güncelle. |
### getDicomHeaderInfoByBytes() {#getDicomHeaderInfoByBytes--}
```
public byte[] getDicomHeaderInfoByBytes()
```


Dicom başlık bilgilerini bayt olarak alır.

Değer: Dicom başlık bilgisi bayt olarak.

**Returns:**
byte[] - Dicom başlık bilgisi bayt olarak.
### getPlanarConfiguration() {#getPlanarConfiguration--}
```
public int getPlanarConfiguration()
```


Planar yapılandırmayı alır.

Değer: Düzlemsel yapılandırma.

**Returns:**
int - planar yapılandırma.
### getSignedImage() {#getSignedImage--}
```
public boolean getSignedImage()
```


\"signedImage\" olup olmadığını gösteren bir değeri alır.

**Returns:**
boolean - \"signedImage\" olup olmadığını gösteren bir değer.
### getDicomInfo() {#getDicomInfo--}
```
public List<String> getDicomInfo()
```


DICOM dosyasının başlık bilgilerini alır.

**Returns:**
java.util.List<java.lang.String> - DICOM dosyasının başlık bilgisi.

**Example: The following example shows how to read the header information of a DICOM image.**

``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1489\\";
com.aspose.imaging.fileformats.dicom.DicomImage image = (com.aspose.imaging.fileformats.dicom.DicomImage) com.aspose.imaging.Image.load(dir + "ttfm.dcm");
try {
    for (String s : image.getFileInfo().getDicomInfo()) {
        System.out.println(s);
    }
}
finally {
    image.close();
}

// STDOUT:
//Medya Depolama Sop Class Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Medya Depolama Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Transfer Söz Dizimi Uid: 1.2.840.10008.1.2.4.70
//Uygulama Sınıfı Uid: 1.2.840.114236
//Belirli Karakter Seti: ISO_IR 100
//Görüntü Türü: \SECONDARY\INTRAOPERATIVE
//Sop Class Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Çalışma Tarihi: 20110824
//Seri Tarihi: 20110824
//İçerik Tarihi: 20110824
//Çalışma Saati: 094836.214743984
//Seri Saati: 094836.214743984
//İçerik Saati: 100451.214743816
//Modalite: US
//Üretici: Medistim
//Kurum Adı: Hospital Name
//Kurum Adresi: Hospital Address or Department
//İstasyon Adı: VERIQ
//İşlem Yapan Hekimin Adı: CA Prof. Debus
//Üreticinin Model Adı: VeriQ C
//Önerilen Görüntü Çerçeve Hızı: 1
//Hasta Adı: Femoral trombenarterectomy^Case Report:
//Hasta Kimliği: Vaka Raporu 1
//Hasta Cinsiyeti: M
//Hasta Boyu: 0
//Hasta Ağırlığı: 0
//Hasta Yorumları: www.medistim.com adresindeki vaka raporuna bakın
//Cine Hızı: 1
//Etkin Süre: 1
//Cihaz Seri Numarası: 0
//Yazılım Sürümü(leri): 3.3.0 RC0 oluşturuldu 02 / 23 / 12  09:50:45
//Kare Zamanı: 1000
//Çalışma Örneği UID: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//Seri Örneği UID: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Seri Numarası: 1
//Örnek Numarası: 1
//Piksel Başına Örnek: 3
//Fotometrik Yorum: RGB
//Planar Yapılandırma: 0
//Kare Sayısı: 1
//Kare Artış İşaretçisi:
//Satırlar: 768
//Sütunlar: 1024
//Ayrılan Bit: 8
//Depolanan Bit: 8
//Yüksek Bit: 7
//Piksel Temsili: 0
//Kayıplı Görüntü Sıkıştırma: 00
//Piksel Verisi: 1492
```

### getSamplesPerPixel() {#getSamplesPerPixel--}
```
public int getSamplesPerPixel()
```


\"samplesPerPixel\" değerini alır.

Değer: "samplesPerPixel" öğesinin değeri.

**Returns:**
int - "samplesPerPixel" öğesinin bir değeri.
### getBitsAllocated() {#getBitsAllocated--}
```
public int getBitsAllocated()
```


\"bitsAllocated\" değerini alır.

Değer: "bitsAllocated" öğesinin değeri.

**Returns:**
int - "bitsAllocated" öğesinin bir değeri.
### getBitsStored() {#getBitsStored--}
```
public int getBitsStored()
```


Depolanan bit sayısını alır.

**Returns:**
int - depolanan bit sayısı.
### getPhotoInterpretation() {#getPhotoInterpretation--}
```
public String getPhotoInterpretation()
```


\"PhotoInterpretation\" değerini alır.

**Returns:**
java.lang.String - "PhotoInterpretation" öğesinin bir değeri.
### getWidth() {#getWidth--}
```
public int getWidth()
```


Genişliği alır.

Değer: genişliğin değeri.

**Returns:**
int - genişlik.
### getHeight() {#getHeight--}
```
public int getHeight()
```


Yüksekliği alır.

Değer: yüksekliğin değeri.

**Returns:**
int - yükseklik.
### getWindowCentre() {#getWindowCentre--}
```
public double getWindowCentre()
```


Pencere merkezini alır.

Değer: pencere merkezinin değeri.

**Returns:**
double - pencere merkezi.
### getWindowWidth() {#getWindowWidth--}
```
public double getWindowWidth()
```


Pencerenin genişliğini alır.

Değer: pencerenin genişliği.

**Returns:**
double - pencerenin genişliği.
### getPixelRepresentation() {#getPixelRepresentation--}
```
public int getPixelRepresentation()
```


Piksel \"pixelRepresentation\" değerini alır.

Değer: "pixelRepresentation" öğesinin değeri.

**Returns:**
int - pixel "pixelRepresentation" öğesinin bir değeri.
### getRescaleIntercept() {#getRescaleIntercept--}
```
public double getRescaleIntercept()
```


\"rescaleIntercept\" değerini alır.

Değer: "rescaleIntercept" öğesinin değeri.

**Returns:**
double - "rescaleIntercept" öğesinin bir değeri.
### getRescaleSlope() {#getRescaleSlope--}
```
public double getRescaleSlope()
```


\"rescaleSlope\" değerini alır.

Değer: "rescaleSlope" öğesinin değeri.

**Returns:**
double - "rescaleSlope" öğesinin bir değeri.
### getNumberOfFrames() {#getNumberOfFrames--}
```
public int getNumberOfFrames()
```


Kare sayısını alır.

Değer: çerçeve sayısı.

**Returns:**
int - çerçeve sayısı.
### isLittleEndian() {#isLittleEndian--}
```
public boolean isLittleEndian()
```


Bu örneğin little endian olup olmadığını gösteren bir değeri alır.

Değer: bu örnek küçük endian ise `true`; aksi takdirde `false`.

**Returns:**
boolean - bu örneğin küçük endian olup olmadığını gösteren bir değer.
### getReds() {#getReds--}
```
public byte[] getReds()
```


Kırmızı renk dizisini alır.

Değer: kırmızılar.

**Returns:**
byte[] - kırmızıya ait dizi renkleri
### getGreens() {#getGreens--}
```
public byte[] getGreens()
```


Yeşil renk dizisini alır.

Değer: Kırmızı rengi.

**Returns:**
byte[] - yeşile ait dizi renkleri
### getBlues() {#getBlues--}
```
public byte[] getBlues()
```


Mavi renk dizisini alır.

Değer: Mavi renkler.

**Returns:**
byte[] - maviye ait dizi renkleri
### getOffset() {#getOffset--}
```
public int getOffset()
```


Ofseti alır.

Değer: Ofsetin değeri.

**Returns:**
int - ofset.
### addTag(String tagDescription, Object value) {#addTag-java.lang.String-java.lang.Object-}
```
public void addTag(String tagDescription, Object value)
```


Yeni Dicom etiketi ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagDescription | java.lang.String | Etiket açıklaması. Boş veya yalnızca boşluk olamaz. |
| değer | java.lang.Object | Etiket değeri. Boş olamaz. |

### tryAddTag(String tagDescription, Object value) {#tryAddTag-java.lang.String-java.lang.Object-}
```
public boolean tryAddTag(String tagDescription, Object value)
```


Yeni Dicom etiketi ekle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| tagDescription | java.lang.String | Etiket açıklaması. Boş veya yalnızca boşluk olamaz. |
| değer | java.lang.Object | Etiket değeri. Boş olamaz. |

**Returns:**
boolean - İşlem sonucu.
### removeTagAt(int index) {#removeTagAt-int-}
```
public void removeTagAt(int index)
```


Mevcut bir etiketi kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Güncellenecek etiketin indeksi. |

### tryRemoveTagAt(int index) {#tryRemoveTagAt-int-}
```
public boolean tryRemoveTagAt(int index)
```


Mevcut bir etiketi kaldır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Güncellenecek etiketin indeksi. |

**Returns:**
boolean - İşlem sonucu.
### updateTagAt(int index, Object newValue) {#updateTagAt-int-java.lang.Object-}
```
public void updateTagAt(int index, Object newValue)
```


Mevcut bir etiketi güncelle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Güncellenecek etiketin indeksi. |
| newValue | java.lang.Object | Etiket değeri. Boş olamaz. |

### tryUpdateTagAt(int index, Object newValue) {#tryUpdateTagAt-int-java.lang.Object-}
```
public boolean tryUpdateTagAt(int index, Object newValue)
```


Mevcut bir etiketi güncelle.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | int | Güncellenecek etiketin indeksi. |
| newValue | java.lang.Object | Etiket değeri. Boş olamaz. |

**Returns:**
boolean - İşlem sonucu.
