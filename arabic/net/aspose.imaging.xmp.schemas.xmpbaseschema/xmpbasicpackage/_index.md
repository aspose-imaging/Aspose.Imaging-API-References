---
title: "الفئة XmpBasicPackage"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.Xmp.Schemas.XmpBaseSchema.XmpBasicPackage. تمثل مساحة الاسم الأساسية لـ XMP"
type: docs
weight: 11980
url: /ar/net/aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/
---
## XmpBasicPackage class

يمثل مساحة الاسم الأساسية لـ XMP.

```csharp
public class XmpBasicPackage : XmpPackage
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [XmpBasicPackage](xmpbasicpackage/#constructor)() | يُنشئ مثلاً جديداً من الفئة `XmpBasicPackage`. |
| [XmpBasicPackage](xmpbasicpackage/#constructor_1)(string, string) | يُنشئ مثلاً جديداً من الفئة `XmpBasicPackage`. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Count](../../aspose.imaging.xmp/xmppackage/count/) { get; } | يحصل على عدد مفاتيح XMP. |
| virtual [Item](../../aspose.imaging.xmp/xmppackage/item/) { get; set; } | يحصل على أو يعيّن الكائن بالمفتاح المحدد. |
| virtual [Keys](../../aspose.imaging.xmp/xmppackage/keys/) { get; } | يحصل على المفاتيح في حزمة XMP. |
| [NamespaceUri](../../aspose.imaging.xmp/xmppackage/namespaceuri/) { get; } | يحصل على URI مساحة الاسم. |
| [Prefix](../../aspose.imaging.xmp/xmppackage/prefix/) { get; } | يحصل على البادئة. |
| [XmlNamespace](../../aspose.imaging.xmp/xmppackage/xmlnamespace/) { get; } | يحصل على مساحة الاسم XML. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| virtual [AddValue](../../aspose.imaging.xmp/xmppackage/addvalue/)(string, object) | يضيف القيمة إلى المفتاح المحدد. |
| override [AddValue](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/addvalue/#addvalue_1)(string, string) | يضيف خاصية string. |
| virtual [Clear](../../aspose.imaging.xmp/xmppackage/clear/)() | يمسح هذا الكائن. |
| virtual [ContainsKey](../../aspose.imaging.xmp/xmppackage/containskey/)(string) | يحدد ما إذا كانت هذه المجموعة المفتاح المحدد. |
| [GetEnumerator](../../aspose.imaging.xmp/xmppackage/getenumerator/)() | يرجع عدادًا يتنقل عبر المجموعة. |
| virtual [GetXmlValue](../../aspose.imaging.xmp/xmppackage/getxmlvalue/)() | يحول قيمة XMP إلى تمثيل XML. |
| virtual [Remove](../../aspose.imaging.xmp/xmppackage/remove/)(string) | أزل القيمة بالمفتاح المحدد. |
| [SetCreatedDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreateddate/#setcreateddate)(DateTime) | يضيف تاريخ إنشاء المورد. |
| [SetCreatedDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreateddate/#setcreateddate_1)(string) | يضيف تاريخ إنشاء المورد. |
| [SetCreatorTool](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setcreatortool/)(string) | يضبط أداة الإنشاء. |
| [SetIdentifier](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setidentifier/)(string[]) | يضبط المعرف. |
| [SetLabel](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setlabel/)(string) | يضبط التسمية. |
| [SetMetadataDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmetadatadate/#setmetadatadate)(DateTime) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [SetMetadataDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmetadatadate/#setmetadatadate_1)(string) | يضيف تاريخ آخر تعديل للبيانات الوصفية. |
| [SetModifyDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmodifydate/#setmodifydate)(DateTime) | يضيف تاريخ آخر تعديل للمورد. |
| [SetModifyDate](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setmodifydate/#setmodifydate_1)(string) | يضيف تاريخ آخر تعديل للمورد. |
| [SetRating](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/setrating/)(int) | يضبط التقييم. |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/)(string, IXmlValue) | يضبط القيمة. |
| virtual [SetValue](../../aspose.imaging.xmp/xmppackage/setvalue/)(string, IXmpType) | يضبط القيمة. |
| virtual [SetXmpTypeValue](../../aspose.imaging.xmp/xmppackage/setxmptypevalue/)(string, XmpTypeBase) | يضبط قيمة نوع XMP. |
| [TryGetValue](../../aspose.imaging.xmp/xmppackage/trygetvalue/)(string, out object) | يحصل على القيمة بواسطة *key*. |

## الحقول

| الاسم | الوصف |
| --- | --- |
| const [RatingMax](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingmax/) | القيمة القصوى للتقييم. |
| const [RatingMin](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingmin/) | القيمة الدنيا للتقييم. |
| const [RatingRejected](../../aspose.imaging.xmp.schemas.xmpbaseschema/xmpbasicpackage/ratingrejected/) | القيمة المرفوضة للتقييم. |

### انظر أيضًا

* class [XmpPackage](../../aspose.imaging.xmp/xmppackage/)
* namespace [Aspose.Imaging.Xmp.Schemas.XmpBaseSchema](../../aspose.imaging.xmp.schemas.xmpbaseschema/)
* assembly [Aspose.Imaging](../../)


