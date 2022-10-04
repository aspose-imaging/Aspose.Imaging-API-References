---
title: XmpPacketWrapper
second_title: Aspose.Imaging لمرجع NET API
description: يحتوي على حزمة xmp متسلسلة بما في ذلك الرأس والمقطورة.
type: docs
weight: 11800
url: /ar/net/aspose.imaging.xmp/xmppacketwrapper/
---
## XmpPacketWrapper class

يحتوي على حزمة xmp متسلسلة بما في ذلك الرأس والمقطورة.

```csharp
public class XmpPacketWrapper
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [XmpPacketWrapper](xmppacketwrapper#constructor)() | يقوم بتهيئة مثيل جديد لملف[`XmpPacketWrapper`](../xmppacketwrapper) فئة . |
| [XmpPacketWrapper](xmppacketwrapper#constructor_1)(XmpHeaderPi, XmpTrailerPi, XmpMeta) | يقوم بتهيئة مثيل جديد لملف[`XmpPacketWrapper`](../xmppacketwrapper) فئة . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [HeaderPi](../../aspose.imaging.xmp/xmppacketwrapper/headerpi) { get; } | يحصل على تعليمات معالجة الرأس. |
| [Meta](../../aspose.imaging.xmp/xmppacketwrapper/meta) { get; set; } | يحصل على تعريف XMP. اختياري. |
| [Packages](../../aspose.imaging.xmp/xmppacketwrapper/packages) { get; } | يحصل على مجموعة من[`XmpPackage`](../xmppackage) داخل XMP. |
| [PackagesCount](../../aspose.imaging.xmp/xmppacketwrapper/packagescount) { get; } | الحصول على كمية الحزم داخل بنية XMP . |
| [TrailerPi](../../aspose.imaging.xmp/xmppacketwrapper/trailerpi) { get; } | يحصل على تعليمات معالجة المقطورة. |

## طُرق

| اسم | وصف |
| --- | --- |
| [AddPackage](../../aspose.imaging.xmp/xmppacketwrapper/addpackage)(XmpPackage) | يضيف الحزمة . |
| [ClearPackages](../../aspose.imaging.xmp/xmppacketwrapper/clearpackages)() | يزيل الكل[`XmpPackage`](../xmppackage) داخل XMP. |
| [ContainsPackage](../../aspose.imaging.xmp/xmppacketwrapper/containspackage)(string) | تحديد ما إذا كانت الحزمة موجودة في مجمّع xmp. |
| [GetPackage](../../aspose.imaging.xmp/xmppacketwrapper/getpackage)(string) | يحصل على الحزمة حسب مساحة الاسم URI. |
| [RemovePackage](../../aspose.imaging.xmp/xmppacketwrapper/removepackage)(XmpPackage) | يزيل حزمة XMP . |

### ملاحظات

يمكن وضع غلاف يتكون من زوج من تعليمات معالجة XML (PIs) حول rdf: عنصر RDF .

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.Xmp](../../aspose.imaging.xmp)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->