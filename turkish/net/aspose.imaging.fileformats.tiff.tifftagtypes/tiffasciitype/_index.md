---
title: TiffASCIIType
second_title: Aspose.Imaging for .NET API Referansı
description: Tiff ascii türü.
type: docs
weight: 7910
url: /tr/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/
---
## TiffASCIIType class

Tiff ascii türü.

```csharp
public sealed class TiffASCIIType : TiffDataType
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [TiffASCIIType](tiffasciitype#constructor)(TiffTags) | Yeni bir örneğini başlatır[`TiffASCIIType`](../tiffasciitype) sınıf. |
| [TiffASCIIType](tiffasciitype#constructor_1)(ushort) | Yeni bir örneğini başlatır[`TiffASCIIType`](../tiffasciitype) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Ek veri boyutunu bayt cinsinden alır (12 baytın etiket verilerine sığması için yeterli olmaması durumunda). |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/count) { get; } | Öğe sayısını alır. |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/datasize) { get; } | Ek veri boyutunu bayt cinsinden alır (12 baytın etiket verilerine sığması için yeterli olmaması durumunda). |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Etiket kimliği tamsayı gösterimini alır. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Etiket verilerinin geçerli olup olmadığını gösteren bir değer alır. Geçerli etiket, korunabilecek verileri içerir. Geçersiz etiket saklanamaz. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Etiket kimliğini alır. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/tagtype) { get; } | Etiket türünü alır. |
| [Text](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/text) { get; set; } | Metni alır veya ayarlar. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/value) { get; set; } | Bu veri türünün içerdiği değeri alır veya ayarlar. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Geçerli örneği aynı türdeki başka bir nesneyle karşılaştırır ve geçerli örneğin diğer nesneyle sıralama düzeninde aynı konumda olup olmadığını belirten bir tamsayı döndürür. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Bu örneğin derin bir klonunu gerçekleştirir. |
| override [ToString](../../aspose.imaging.fileformats.tiff/tiffdatatype/tostring)() | Bir döndürürString bu, bu örneği temsil eder. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffasciitype/writeadditionaldata)(TiffStreamWriter) | Ek etiket verilerini yazar. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Etiket verilerini yazar. |

### Ayrıca bakınız

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* ad alanı [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
