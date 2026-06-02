---
title: "الفئة XmpPacketWrapper"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Xmp.XmpPacketWrapper. تحتوي على حزمة xmp متسلسلة تشمل الرأس والذيل."
type: docs
weight: 12450
url: /ar/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

يحتوي على حزمة xmp المتسلسلة بما في ذلك الرأس والذيل.

```csharp
public class XmpPacketWrapper : IImageMetadataFormat, IXmlValue
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper/#constructor)() | تهيئ كائنًا جديدًا من الفئة `XmpPacketWrapper`. |
| [XmpPacketWrapper](xmppacketwrapper/#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | تهيئ كائنًا جديدًا من الفئة `XmpPacketWrapper`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi/) { get; } | تحصل على تعليمات معالجة الرأس. |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta/) { get; set; } | تحصل على بيانات XMP الوصفية. اختياري. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages/) { get; } | تحصل على مصفوفة من [`XmpPackage`](../xmppackage/) داخل XMP. |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount/) { get; } | تحصل على عدد الحزم داخل بنية XMP. |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi/) { get; } | تحصل على تعليمات معالجة الذيل. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage/)(XmpPackage) | يضيف الحزمة. |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages/)() | يزيل جميع [`XmpPackage`](../xmppackage/) داخل XMP. |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage/)(string) | يحدد ما إذا كانت الحزمة موجودة في xmp wrapper. |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage/)(string) | تحصل على الحزمة حسب مساحة الاسم URI. |
| [GetXmlValue](../../aspose.imaging.xmp/xmppacketwrapper/getxmlvalue/)() | يحول قيمة XMP إلى تمثيل XML. |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage/)(XmpPackage) | يزيل حزمة XMP. |
| override [ToString](../../aspose.imaging.xmp/xmppacketwrapper/tostring/)() | يرجع سلسلة XML تمثل الكائن الحالي. |

## ملاحظات

يمكن وضع غلاف يتكون من زوج من تعليمات معالجة XML (PIs) حول عنصر rdf:RDF.

### انظر أيضًا

* interface [IImageMetadataFormat](../../aspose.imaging.metadata/iimagemetadataformat/)
* interface [IXmlValue](../ixmlvalue/)
* namespace [Aspose.Imaging.Xmp](../../aspose.imaging.xmp/)
* assembly [Aspose.Imaging](../../)


