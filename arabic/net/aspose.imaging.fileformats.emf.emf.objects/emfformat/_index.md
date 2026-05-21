---
title: "الفئة EmfFormat"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfFormat. كائن EmrFormat يحتوي على معلومات تحدد تنسيق بيانات الصورة في سجل EMR_COMMENT_MULTIFORMATS القسم 2.3.3.4.3"
type: docs
weight: 3050
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---
## EmfFormat class

كائن EmrFormat يحتوي على معلومات تحدد تنسيق بيانات الصورة في سجل EMR_COMMENT_MULTIFORMATS (القسم 2.3.3.4.3).

```csharp
public sealed class EmfFormat : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfFormat](emfformat/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [OffData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/offdata/) { get; set; } | الحصول أو الضبط عدد صحيح غير موقع 32‑بت يحدد الإزاحة إلى البيانات من بداية حقل المعرف في سجل EMR_COMMENT_PUBLIC (القسم 2.3.3.4). يجب أن تكون الإزاحة محاذاة 32‑بت. |
| [Signature](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/signature/) { get; set; } | الحصول أو الضبط عدد صحيح غير موقع 32‑بت يحدد تنسيق بيانات الصورة. يجب أن تكون هذه القيمة ضمن تعداد FormatSignature (القسم 2.1.14). |
| [SizeData](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/sizedata/) { get; set; } | الحصول أو الضبط عدد صحيح غير موقع 32‑بت يحدد حجم البيانات بالبايت |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfformat/version/) { get; set; } | الحصول أو الضبط عدد صحيح غير موقع 32‑بت يحدد رقم نسخة التنسيق. إذا كان حقل Signature يحدد PostScript المضمن (EPS)، يجب أن تكون هذه القيمة 0x00000001؛ وإلا يجب تجاهل هذه القيمة. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


