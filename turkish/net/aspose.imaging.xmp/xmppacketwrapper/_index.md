---
title: XmpPacketWrapper
second_title: Aspose.Imaging for .NET API Referansı
description: Başlık ve fragman dahil olmak üzere serileştirilmiş xmp paketini içerir.
type: docs
weight: 11800
url: /tr/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

Başlık ve fragman dahil olmak üzere serileştirilmiş xmp paketini içerir.

```csharp
public class XmpPacketWrapper
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | Yeni bir örneğini başlatır[`XmpPacketWrapper`](../xmppacketwrapper) sınıf. |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | Yeni bir örneğini başlatır[`XmpPacketWrapper`](../xmppacketwrapper) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi) { get; } | Başlık işleme talimatını alır. |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta) { get; set; } | XMP metasını alır. İsteğe bağlı. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages) { get; } | Şu diziyi alır:[`XmpPackage`](../xmppackage) XMP. içinde |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount) { get; } | XMP yapısı içindeki paket miktarını alır. |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi) { get; } | Fragman işleme talimatını alır. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage)(XmpPackage) | Paketi ekler. |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages)() | Tümünü kaldırır[`XmpPackage`](../xmppackage) XMP. içinde |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage)(string) | Paketin xmp sarmalayıcısında olup olmadığını belirler. |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage)(string) | Paketi ad alanı URI'sine göre alır. |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage)(XmpPackage) | XMP paketini kaldırır. |

### Notlar

Bir çift XML işleme talimatından (PI'ler) oluşan bir sarmalayıcı rdf:RDF öğesinin etrafına yerleştirilebilir.

### Ayrıca bakınız

* ad alanı [Aspose.Imaging.Xmp](../../aspose.imaging.xmp)
* toplantı [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
