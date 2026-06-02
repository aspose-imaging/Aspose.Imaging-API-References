---
title: "Enum OdTextAlignModeFlags"
second_title: "Aspose.Imaging for .NET API Reference"
description: "enum Aspose.Imaging.FileFormats.OpenDocument.Enums.OdTextAlignModeFlags. علامات وضع محاذاة النص في المستند المفتوح"
type: docs
weight: 6990
url: /ar/net/aspose.imaging.fileformats.opendocument.enums/odtextalignmodeflags/
---
## OdTextAlignModeFlags enumeration

علامات وضع محاذاة نص المستند المفتوح

```csharp
[Flags]
public enum OdTextAlignModeFlags
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Noupdatecp | `0` | يجب عدم تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. يجب تمرير نقطة المرجع إلى دالة إخراج النص. |
| Left | `0` | يجب أن تكون النقطة المرجعية على الحافة اليسرى للمستطيل المحيط. |
| Top | `0` | يجب أن تكون النقطة المرجعية على الحافة العليا للمستطيل المحيط. |
| Updatecp | `0` | يجب تحديث موضع الرسم في سياق جهاز التشغيل بعد كل استدعاء لإخراج النص. يجب استخدامه كنقطة مرجع. |
| Right | `1` | يجب أن تكون النقطة المرجعية على الحافة اليمنى للمستطيل المحيط. |
| Center | `2` | يجب محاذاة نقطة المرجع أفقياً مع مركز المستطيل الحد. |
| Justify | `4` | يجب محاذاة النص بحيث يكون لكل سطر نص في الفقرة نفس الطول. |
| Bottom | `8` | يجب أن تكون النقطة المرجعية على الحافة السفلية للمستطيل المحيط. |
| Baseline | `10` | يجب أن تكون النقطة المرجعية على خط أساس النص. |
| Rtlreading | `100` | يجب ترتيب النص بقراءة من اليمين إلى اليسار، بدلاً من الترتيب الافتراضي من اليسار إلى اليمين. يجب تطبيق ذلك فقط عندما يكون الخط المحدد في سياق جهاز التشغيل إما عبريًا أو عربيًا. |
| Horizontal | `3` | يمثل مجموعات محاذاة النص الأفقي (يسار &#x7C; يمين &#x7C; وسط) |
| Vertical | `18` | يمثل مجموعات محاذاة النص العمودي (أعلى &#x7C; أسفل &#x7C; خط الأساس) |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.OpenDocument.Enums](../../aspose.imaging.fileformats.opendocument.enums/)
* assembly [Aspose.Imaging](../../)


