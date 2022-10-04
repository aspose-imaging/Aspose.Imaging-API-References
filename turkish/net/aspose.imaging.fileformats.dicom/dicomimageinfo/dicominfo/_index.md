---
title: DicomInfo
second_title: Aspose.Imaging for .NET API Referansı
description: DICOM dosyasının başlık bilgilerini alır.
type: docs
weight: 40
url: /tr/net/aspose.imaging.fileformats.dicom/dicomimageinfo/dicominfo/
---
## DicomImageInfo.DicomInfo property

DICOM dosyasının başlık bilgilerini alır.

```csharp
public List<string> DicomInfo { get; }
```

### Örnekler

Aşağıdaki örnek, bir DICOM görüntüsünün başlık bilgilerinin nasıl okunacağını gösterir.

```csharp
[C#]

string dir = "c:\\aspose.imaging\\issues\\net\\3635\\testdata\\3628";
using (Aspose.Imaging.FileFormats.Dicom.DicomImage image = (Aspose.Imaging.FileFormats.Dicom.DicomImage)Aspose.Imaging.Image.Load(System.IO.Path.Combine(dir, "ttfm.dcm")))
{
    foreach (string s in image.FileInfo.DicomInfo)
    {
        System.Console.WriteLine(s);
    }
}

// STDOUT:
//Media Storage Sop Sınıf Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Media Storage Sop Instance Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Transfer Sözdizimi Uid: 1.2.840.10008.1.2.4.70
//Uygulama Sınıfı Uid: 1.2.840.114236
//Belirli Karakter Kümesi: ISO_IR 100
//Görüntü Türü: \İKİNCİ\İNTRAOPERATİF
//Sop Sınıf Uid: 1.2.840.10008.5.1.4.1.1.3.1
//Sop Örnek Kullanıcı Kimliği: 2.16.840.1.114488.0.4.123489834087.1330071425.2
//Çalışma Tarihi: 20110824
//Seri Tarihi: 20110824
//İçerik Tarihi: 20110824
//Çalışma Süresi: 094836.214743984
//Seri Süresi: 094836.214743984
//İçerik Süresi: 100451.214743816
//Modalite: ABD
//Üretici: Medistim
//Kurum Adı: Hastane Adı
//Kurum Adresi: Hastane Adresi veya Bölüm
//İstasyon Adı: VERIQ
//İcracı Doktorun Adı: CA Prof. Debus
//Üreticinin Model Adı: VeriQ C
//Önerilen Görüntü Kare Hızı: 1
//Hasta Adı: Femoral trombenarterektomi^Olgu Raporu:
//Hasta Kimliği: Vaka Raporu 1
//Hastanın Cinsiyeti: M
//Hastanın Boyutu: 0
//Hasta Ağırlığı: 0
//Hasta Yorumları: www.medistim.com adresindeki vaka raporuna bakın
//Sinema Oranı: 1
//Geçerlilik Süresi: 1
//Cihaz Seri Numarası: 0
//Yazılım Versiyonları: 3.3.0 RC0 inşa 02 / 23 / 12 09:50:45
//Kare Süresi: 1000
//Çalışma Örneği Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.0
//Seri Örnek Uid: 2.16.840.1.114488.0.4.123489834087.1330071425.1
//Seri Numarası: 1
//Örnek Numarası: 1
//Piksel Başına Örnek Sayısı: 3
//Fotometrik Yorum: RGB
//Düzlemsel Yapılandırma: 0
//Çerçeve Sayısı: 1
//Çerçeve Artış İşaretçisi:
//Satırlar: 768
//Sütunlar: 1024
// Ayrılan Bitler: 8
// Depolanan Bitler: 8
//yüksek Bit: 7
//Piksel Temsili: 0
//Kayıplı Görüntü Sıkıştırma: 00
//Piksel Verisi: 1492
```

### Ayrıca bakınız

* class [DicomImageInfo](../../dicomimageinfo)
* ad alanı [Aspose.Imaging.FileFormats.Dicom](../../dicomimageinfo)
* toplantı [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->