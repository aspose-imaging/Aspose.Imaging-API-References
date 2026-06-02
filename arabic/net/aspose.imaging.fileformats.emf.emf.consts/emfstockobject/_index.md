---
title: "Enum EmfStockObject"
second_title: "Aspose.Imaging for .NET API Reference"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfStockObject enum. تحدد تعداد StockObject فهارس الكائنات الرسومية المنطقية المعرفة مسبقًا التي يمكن استخدامها في عمليات الرسومات. البنى المحددة لكائنات المخزون تعتمد على التنفيذ، ومع ذلك يجب أن تكون خصائص كائنات المخزون مكافئة لخصائص الكائنات التي تم إنشاؤها صراحةً من نفس النوع. يتم تحديد هذه الخصائص حيثما أمكن لكائنات المخزون المعرفة في هذا التعداد."
type: docs
weight: 2950
url: /ar/net/aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
## EmfStockObject enumeration

تحدد تعداد StockObject الفهارس للكائنات الرسومية المنطقية المعرفة مسبقًا والتي يمكن استخدامها في عمليات الرسومات. هياكل كائنات المخزون محددة حسب التنفيذ؛ ومع ذلك، يجب أن تكون خصائص كائنات المخزون مكافئة لخصائص الكائنات التي تم إنشاؤها صراحةً من نفس النوع. يتم تحديد هذه الخصائص حيثما أمكن لكائنات المخزون المعرفة في هذا التعداد.

```csharp
public enum EmfStockObject
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| WHITE_BRUSH | `-2147483648` | فرشاة بيضاء صلبة اللون تعادل فرشاة منطقية (كائن LogBrushEx، القسم 2.2.12) بالخصائص التالية: BrushStyle: BS_SOLID (تعداد BrushStyle في WMF، [MS-WMF] القسم 2.1.1.4) Color: 0x00FFFFFF (كائن ColorRef في WMF، [MS-WMF] القسم 2.2.2.8) |
| LTGRAY_BRUSH | `-2147483647` | فرشاة رمادية فاتحة صلبة اللون تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00C0C0C0 |
| GRAY_BRUSH | `-2147483646` | فرشاة رمادية صلبة اللون تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00808080 |
| DKGRAY_BRUSH | `-2147483645` | فرشاة رمادية داكنة صلبة اللون تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00404040 |
| BLACK_BRUSH | `-2147483644` | فرشاة سوداء صلبة اللون تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS_SOLID Color: 0x00000000 |
| NULL_BRUSH | `-2147483643` | فرشاة فارغة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS_NULL |
| WHITE_PEN | `-2147483642` | قلم أبيض صلب اللون يعادل قلمًا منطقيًا (كائن LogPen، القسم 2.2.19) بالخصائص التالية: PenStyle: PS_COSMETIC + PS_SOLID (تعداد PenStyle، القسم 2.1.25) ColorRef: 0x00FFFFFF (كائن ColorRef في WMF). |
| BLACK_PEN | `-2147483641` | قلم أسود صلب اللون يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS_COSMETIC + PS_SOLID ColorRef: 0x00000000 |
| NULL_PEN | `-2147483640` | قلم فارغ يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS_NULL |
| OEM_FIXED_FONT | `-2147483638` | خط ثابت العرض، مجموعة أحرف OEM يعادل خطًا منطقيًا (كائن LogFont، القسم 2.2.13) بالخصائص التالية: Charset: OEM_CHARSET (تعداد CharacterSet في WMF، [MS-WMF] القسم 2.1.1.5) PitchAndFamily: FF_DONTCARE (تعداد FamilyFont في WMF، [MS-WMF] القسم 2.1.1.8) + FIXED_PITCH (تعداد PitchFont في WMF، [MS-WMF] القسم 2.1.24) |
| ANSI_FIXED_FONT | `-2147483637` | خط ثابت العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + FIXED_PITCH |
| ANSI_VAR_FONT | `-2147483636` | خط متغير العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI_CHARSET PitchAndFamily: FF_DONTCARE + VARIABLE_PITCH |
| SYSTEM_FONT | `-2147483635` | خط مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ |
| DEVICE_DEFAULT_FONT | `-2147483634` | خط الافتراضي الذي يقدمه برنامج تشغيل جهاز الرسومات للجهاز الخارجي الحالي. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ |
| DEFAULT_PALETTE | `-2147483633` | لوحة الألوان الافتراضية المعرفة للجهاز الخارجي الحالي. لوحة الألوان الفعلية المحددة بهذه القيمة تعتمد على التنفيذ |
| SYSTEM_FIXED_FONT | `-2147483632` | خط ثابت العرض مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ |
| DEFAULT_GUI_FONT | `-2147483631` | خط ثابت العرض مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ |
| DC_BRUSH | `-2147483630` | فرشاة اللون الصلب المحددة حاليًا في سياق جهاز التشغيل |
| DC_PEN | `-2147483629` | قلم اللون الصلب المحدد حاليًا في سياق جهاز التشغيل |

### انظر أيضًا

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


