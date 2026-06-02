---
title: "الفئة EmfUniversalFontId"
second_title: "Aspose.Imaging for .NET API Reference"
description: "الفئة Aspose.Imaging.FileFormats.Emf.Emf.Objects.EmfUniversalFontId. كائن UniversalFontId يحدد آلية لتحديد الخطوط في ملفات EMF."
type: docs
weight: 3270
url: /ar/net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
## EmfUniversalFontId class

كائن UniversalFontId يحدد آلية لتحديد الخطوط في ملفات EMF الميتا.

```csharp
public sealed class EmfUniversalFontId : EmfObject
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [EmfUniversalFontId](emfuniversalfontid/)() | المنشئ الافتراضي. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [Checksum](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/checksum/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يمثل المجموع الاختباري للخط. لقيمة المجموع الاختباري المعاني التالية. 0x00000000 الكائن هو خط جهاز. 0x00000001 الكائن هو خط Type 1 تم تثبيته على جهاز العميل وتم تعدادُه بواسطة برنامج تشغيل طابعة PostScript كخط جهاز. 0x00000002 الكائن ليس خطًا بل هو مُرصّص Type 1. 3 ≤ القيمة الكائن هو صورة نقطية أو متجهة أو خط TrueType، أو خط Type 1 مُرصّص تم إنشاؤه بواسطة مُرصّص Type 1. |
| [Index](../../aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/index/) { get; set; } | يحصل أو يعيّن عددًا صحيحًا غير موقع 32 بت يمثل فهرسًا مرتبطًا بكائن الخط. يتم تحديد معنى هذا الحقل بناءً على نوع الخط. |

### انظر أيضًا

* class [EmfObject](../emfobject/)
* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects/)
* assembly [Aspose.Imaging](../../)


