---
title: EmfStockObject
second_title: Aspose.Imaging لمرجع NET API
description: يحدد تعداد StockObject فهارس الكائنات الرسومية المنطقية المحددة مسبقًا التي يمكن استخدامها في عمليات الرسومات. الهياكل المحددة لكائنات المخزون تعتمد على التنفيذ  ومع ذلك  يجب أن تكون خصائص كائنات المخزون مكافئة لـ خصائص الكائنات التي تم إنشاؤها بشكل صريح من نفس النوع. يتم تحديد هذه الخصائص حيثما أمكن لعناصر المخزون المحددة في هذا التعداد.
type: docs
weight: 2860
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

يحدد تعداد StockObject فهارس الكائنات الرسومية المنطقية المحددة مسبقًا التي يمكن استخدامها في عمليات الرسومات. الهياكل المحددة لكائنات المخزون تعتمد على التنفيذ ؛ ومع ذلك ، يجب أن تكون خصائص كائنات المخزون مكافئة لـ خصائص الكائنات التي تم إنشاؤها بشكل صريح من نفس النوع. يتم تحديد هذه الخصائص حيثما أمكن لعناصر المخزون المحددة في هذا التعداد.

```csharp
public enum EmfStockObject
```

### قيم

| اسم | قيمة | وصف |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | فرشاة بيضاء صلبة اللون تعادل الفرشاة المنطقية (كائن LogBrushEx ، القسم 2.2.12) بالخصائص التالية: BrushStyle: BS_SOLID (WMF BrushStyle enumeration، [MS-WMF] القسم 2.1.1.4) اللون: 0x00FFFFFF (كائن WMF ColorRef ، القسم [MS-WMF] 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | فرشاة بلون رمادي فاتح مصمت تعادل الفرشاة المنطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | فرشاة رمادية صلبة اللون تعادل الفرشاة المنطقية بالخصائص التالية: BrushStyle: BS_SOLID اللون: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | فرشاة بلون رمادي غامق صلبة تعادل الفرشاة المنطقية بالخصائص التالية: BrushStyle: BS_SOLID اللون: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | فرشاة ذات لون أسود خالص تعادل الفرشاة المنطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00000000 |
| NULL_BRUSH | `-2147483643` | فرشاة فارغة تعادل الفرشاة المنطقية بالخصائص التالية: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | قلم أبيض بلون خالص مكافئ لقلم منطقي (كائن LogPen ، القسم 2.2.19) بالخصائص التالية: PenStyle: PS_COSMETIC + PS_SOLID (تعداد PenStyle ، القسم 2.1.25) ColorRef: 0x00FFFFFF ( كائن WMF ColorRef) . |
| BLACK_PEN | `-2147483641` | قلم أسود بلون خالص يعادل القلم المنطقي بالخصائص التالية: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | قلم فارغ يكافئ قلمًا منطقيًا بالخصائص التالية: نمط القلم: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | خط مجموعة أحرف OEM ذو عرض ثابت يكافئ الخط المنطقي (كائن LogFont ، القسم 2.2.13) بالخصائص التالية: Charset: OEM_CHARSET (WMF CharacterSet enumeration، [MS-WMF] القسم 2.1.1.5 ) PitchAndFamily: FF_DONTCARE (WMF FamilyFont enumeration، [MS-WMF] القسم 2.1.1.8) + FIXED_PITCH (WMF PitchFont enumeration، [MS-WMF] القسم 2.1.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | خط ذو عرض ثابت مكافئ لخط منطقي بالخصائص التالية: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | خط متغير العرض مكافئ لخط منطقي بالخصائص التالية: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | خط مضمون إتاحته في نظام التشغيل. الخط الفعلي الذي تم تحديده بواسطة هذه القيمة هو تنفيذ يعتمد على |
| DEVICE_DEFAULT_FONT | `-2147483634` | الخط الافتراضي الذي يتم توفيره بواسطة برنامج تشغيل جهاز الرسومات لجهاز الإخراج الحالي. الخط الفعلي الذي تم تحديده بواسطة هذه القيمة هو تنفيذ يعتمد على |
| DEFAULT_PALETTE | `-2147483633` | اللوحة الافتراضية التي تم تحديدها لجهاز الإخراج الحالي. لوحة الألوان الفعلية المحددة بواسطة هذه القيمة تعتمد على التنفيذ |
| SYSTEM_FIXED_FONT | `-2147483632` | خط ذو عرض ثابت مضمون إتاحته في نظام التشغيل. الخط الفعلي الذي تم تحديده بواسطة هذه القيمة هو تنفيذ يعتمد على |
| DEFAULT_GUI_FONT | `-2147483631` | خط ذو عرض ثابت مضمون إتاحته في نظام التشغيل. الخط الفعلي الذي تم تحديده بواسطة هذه القيمة هو تنفيذ يعتمد على |
| DC_BRUSH | `-2147483630` | فرشاة الألوان الصلبة المحددة حاليًا في سياق جهاز التشغيل |
| DC_PEN | `-2147483629` | القلم ذو اللون الصلب المحدد حاليًا في سياق جهاز التشغيل |

### أنظر أيضا

* مساحة الاسم [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* المجسم [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->