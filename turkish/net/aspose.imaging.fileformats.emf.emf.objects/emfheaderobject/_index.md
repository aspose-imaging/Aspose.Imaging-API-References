---
title: EmfHeaderObject
second_title: Aspose.Imaging for .NET API Referansı
description: Başlık nesnesi EMF meta dosyası başlığını tanımlar. Meta dosyasındaki görüntünün oluşturulduğu aygıtın özelliklerini belirtir.
type: docs
weight: 3010
url: /tr/net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/
---
## EmfHeaderObject class

Başlık nesnesi, EMF meta dosyası başlığını tanımlar. Meta dosyasındaki görüntünün oluşturulduğu aygıtın özelliklerini belirtir.

```csharp
public class EmfHeaderObject : EmfObject
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [EmfHeaderObject](emfheaderobject)() | Default_Constructor |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Metafile içinde depolanan görüntünün etrafına çizilebilecek en küçük dikdörtgenin cihaz birimlerinde dikdörtgen kapsayıcı-kapsayıcı sınırlarını belirten bir WMF RectL nesnesi ([MS-WMF] bölüm 2.2.2.19) alır veya ayarlar. |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Meta dosyasının boyutunu bayt cinsinden belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Referans aygıtın boyutunu piksel cinsinden belirten bir WMF SizeL nesnesi ([MS-WMF] bölüm 2.2.2.22) alır veya ayarlar |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Metafile içinde depolanan görüntüyü çevreleyen bir dikdörtgenin dikdörtgen kapsayıcı-kapsayıcı boyutlarını 0,01 milimetre biriminde belirten bir WMF RectL nesnesi alır veya ayarlar |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Metafile 'nin işlenmesi sırasında kullanılacak grafik nesnelerinin sayısını belirten 16 bitlik işaretsiz bir tamsayı alır veya ayarlar. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Referans aygıtın boyutunu milimetre cinsinden belirten bir WMF SizeL nesnesi alır veya ayarlar |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Meta dosyasının içeriğinin açıklamasını içeren dizisindeki karakter sayısını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Açıklama dizesi yoksa bu sıfırdır. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Meta dosyası paletindeki girişlerin sayısını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Palet, EMR_EOF record içinde bulunur |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Bu kaydının başlangıcından meta dosyasının content açıklamasını içeren diziye olan uzaklığını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Metafile içindeki kayıt sayısını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Kayıt imzasını belirten 32 bitlik işaretsiz bir tamsayı alır veya ayarlar. Bu, FormatSignature numaralandırmasından (bölüm 2.1.14) ENHMETA_SIGNATURE, OLMALIDIR. |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | 0x0000 olması ve yoksayılması ZORUNLU olan 16 bitlik işaretsiz bir tamsayı alır veya ayarlar |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Bunun olup olmadığını gösteren bir değer alır.[`EmfHeaderObject`](../emfheaderobject)geçerlidir. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Sürüm (4 bayt) alır veya ayarlar: EMF meta dosyası birlikte çalışabilirliğini belirten 32 bit işaretsiz bir tam sayı. Bu 0x00010000 OLMALIDIR |

### Ayrıca bakınız

* class [EmfObject](../emfobject)
* ad alanı [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
