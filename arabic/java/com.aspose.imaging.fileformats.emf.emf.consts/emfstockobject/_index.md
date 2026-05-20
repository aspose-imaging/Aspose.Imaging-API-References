---
title: "EmfStockObject"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد StockObject فهارس الكائنات الرسومية المنطقية المعرفة مسبقًا التي يمكن استخدامها في عمليات الرسم. هياكل الكائنات المخزنة تعتمد على التنفيذ، ومع ذلك يجب أن تكون خصائص الكائنات المخزنة مكافئة لخصائص الكائنات التي تم إنشاؤها صراحةً من نفس النوع."
type: docs
weight: 42
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfstockobject/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfStockObject extends System.Enum
```

تحدد تعداد StockObject فهارس الكائنات الرسومية المنطقية المعرفة مسبقًا التي يمكن استخدامها في عمليات الرسم. هياكل الكائنات المخزنة تعتمد على التنفيذ؛ ومع ذلك يجب أن تكون خصائص الكائنات المخزنة مكافئة لخصائص الكائنات التي تم إنشاؤها صراحةً من نفس النوع. تم تحديد هذه الخصائص حيثما أمكن للكائنات المخزنة المعرفة في هذا التعداد.
## الحقول

| حقل | الوصف |
| --- | --- |
| [WHITE_BRUSH](#WHITE-BRUSH) | فرشاة بيضاء ذات لون صلب تعادل فرشاة منطقية (كائن LogBrushEx، القسم 2.2.12) بالخصائص التالية: BrushStyle: BS\_SOLID (تعداد BrushStyle في WMF، [MS-WMF] القسم 2.1.1.4) Color: 0x00FFFFFF (كائن ColorRef في WMF، [MS-WMF] القسم 2.2.2.8) |
| [LTGRAY_BRUSH](#LTGRAY-BRUSH) | فرشاة صلبة اللون رمادية فاتحة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00C0C0C0 |
| [GRAY_BRUSH](#GRAY-BRUSH) | فرشاة صلبة اللون رمادية تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00808080 |
| [DKGRAY_BRUSH](#DKGRAY-BRUSH) | فرشاة صلبة اللون رمادية داكنة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00404040 |
| [BLACK_BRUSH](#BLACK-BRUSH) | فرشاة صلبة اللون سوداء تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00000000 |
| [NULL_BRUSH](#NULL-BRUSH) | فرشاة فارغة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_NULL |
| [WHITE_PEN](#WHITE-PEN) | قلم صلب اللون أبيض يعادل قلمًا منطقيًا (كائن LogPen، القسم 2.2.19) بالخصائص التالية: PenStyle: PS\_COSMETIC + PS\_SOLID (تعداد PenStyle، القسم 2.1.25) ColorRef: 0x00FFFFFF (كائن WMF ColorRef). |
| [BLACK_PEN](#BLACK-PEN) | قلم صلب اللون أسود يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000 |
| [NULL_PEN](#NULL-PEN) | قلم فارغ يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS\_NULL |
| [OEM_FIXED_FONT](#OEM-FIXED-FONT) | خط ثابت العرض، مجموعة أحرف OEM، يعادل خطًا منطقيًا (كائن LogFont، القسم 2.2.13) بالخصائص التالية: Charset: OEM\_CHARSET (تعداد WMF CharacterSet، [MS-WMF] القسم 2.1.1.5) PitchAndFamily: FF\_DONTCARE (تعداد WMF FamilyFont، [MS-WMF] القسم 2.1.1.8) + FIXED\_PITCH (تعداد WMF PitchFont، [MS-WMF] القسم 2.1.1.24) |
| [ANSI_FIXED_FONT](#ANSI-FIXED-FONT) | خط ثابت العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH |
| [ANSI_VAR_FONT](#ANSI-VAR-FONT) | خط متغير العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH |
| [SYSTEM_FONT](#SYSTEM-FONT) | خط مضمون التوفر في نظام التشغيل. |
| [DEVICE_DEFAULT_FONT](#DEVICE-DEFAULT-FONT) | الخط الافتراضي الذي يقدمه برنامج تشغيل جهاز الرسوميات للجهاز الخارجي الحالي. |
| [DEFAULT_PALETTE](#DEFAULT-PALETTE) | لوحة الألوان الافتراضية المعرفة للجهاز الخارجي الحالي. |
| [SYSTEM_FIXED_FONT](#SYSTEM-FIXED-FONT) | خط ثابت العرض مضمون التوفر في نظام التشغيل. |
| [DEFAULT_GUI_FONT](#DEFAULT-GUI-FONT) | خط ثابت العرض مضمون التوفر في نظام التشغيل. |
| [DC_BRUSH](#DC-BRUSH) | فرشاة صلبة اللون المحددة حاليًا في سياق جهاز التشغيل. |
| [DC_PEN](#DC-PEN) | قلم صلب اللون المحدد حاليًا في سياق جهاز التشغيل. |
### WHITE_BRUSH {#WHITE-BRUSH}
```
public static final int WHITE_BRUSH
```


فرشاة بيضاء ذات لون صلب تعادل فرشاة منطقية (كائن LogBrushEx، القسم 2.2.12) بالخصائص التالية: BrushStyle: BS\_SOLID (تعداد BrushStyle في WMF، [MS-WMF] القسم 2.1.1.4) Color: 0x00FFFFFF (كائن ColorRef في WMF، [MS-WMF] القسم 2.2.2.8)

### LTGRAY_BRUSH {#LTGRAY-BRUSH}
```
public static final int LTGRAY_BRUSH
```


فرشاة صلبة اللون رمادية فاتحة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00C0C0C0

### GRAY_BRUSH {#GRAY-BRUSH}
```
public static final int GRAY_BRUSH
```


فرشاة صلبة اللون رمادية تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00808080

### DKGRAY_BRUSH {#DKGRAY-BRUSH}
```
public static final int DKGRAY_BRUSH
```


فرشاة صلبة اللون رمادية داكنة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00404040

### BLACK_BRUSH {#BLACK-BRUSH}
```
public static final int BLACK_BRUSH
```


فرشاة صلبة اللون سوداء تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_SOLID Color: 0x00000000

### NULL_BRUSH {#NULL-BRUSH}
```
public static final int NULL_BRUSH
```


فرشاة فارغة تعادل فرشاة منطقية بالخصائص التالية: BrushStyle: BS\_NULL

### WHITE_PEN {#WHITE-PEN}
```
public static final int WHITE_PEN
```


قلم صلب اللون أبيض يعادل قلمًا منطقيًا (كائن LogPen، القسم 2.2.19) بالخصائص التالية: PenStyle: PS\_COSMETIC + PS\_SOLID (تعداد PenStyle، القسم 2.1.25) ColorRef: 0x00FFFFFF (كائن WMF ColorRef).

### BLACK_PEN {#BLACK-PEN}
```
public static final int BLACK_PEN
```


قلم صلب اللون أسود يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS\_COSMETIC + PS\_SOLID ColorRef: 0x00000000

### NULL_PEN {#NULL-PEN}
```
public static final int NULL_PEN
```


قلم فارغ يعادل قلمًا منطقيًا بالخصائص التالية: PenStyle: PS\_NULL

### OEM_FIXED_FONT {#OEM-FIXED-FONT}
```
public static final int OEM_FIXED_FONT
```


خط ثابت العرض، مجموعة أحرف OEM، يعادل خطًا منطقيًا (كائن LogFont، القسم 2.2.13) بالخصائص التالية: Charset: OEM\_CHARSET (تعداد WMF CharacterSet، [MS-WMF] القسم 2.1.1.5) PitchAndFamily: FF\_DONTCARE (تعداد WMF FamilyFont، [MS-WMF] القسم 2.1.1.8) + FIXED\_PITCH (تعداد WMF PitchFont، [MS-WMF] القسم 2.1.1.24)

### ANSI_FIXED_FONT {#ANSI-FIXED-FONT}
```
public static final int ANSI_FIXED_FONT
```


خط ثابت العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + FIXED\_PITCH

### ANSI_VAR_FONT {#ANSI-VAR-FONT}
```
public static final int ANSI_VAR_FONT
```


خط متغير العرض يعادل خطًا منطقيًا بالخصائص التالية: Charset: ANSI\_CHARSET PitchAndFamily: FF\_DONTCARE + VARIABLE\_PITCH

### SYSTEM_FONT {#SYSTEM-FONT}
```
public static final int SYSTEM_FONT
```


خط مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ.

### DEVICE_DEFAULT_FONT {#DEVICE-DEFAULT-FONT}
```
public static final int DEVICE_DEFAULT_FONT
```


الخط الافتراضي الذي يقدمه برنامج تشغيل جهاز الرسوميات للجهاز الخارجي الحالي. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ.

### DEFAULT_PALETTE {#DEFAULT-PALETTE}
```
public static final int DEFAULT_PALETTE
```


لوحة الألوان الافتراضية المعرفة للجهاز الخارجي الحالي. لوحة الألوان الفعلية المحددة بهذه القيمة تعتمد على التنفيذ.

### SYSTEM_FIXED_FONT {#SYSTEM-FIXED-FONT}
```
public static final int SYSTEM_FIXED_FONT
```


خط ثابت العرض مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ.

### DEFAULT_GUI_FONT {#DEFAULT-GUI-FONT}
```
public static final int DEFAULT_GUI_FONT
```


خط ثابت العرض مضمون التوفر في نظام التشغيل. الخط الفعلي المحدد بهذه القيمة يعتمد على التنفيذ.

### DC_BRUSH {#DC-BRUSH}
```
public static final int DC_BRUSH
```


فرشاة صلبة اللون المحددة حاليًا في سياق جهاز التشغيل.

### DC_PEN {#DC-PEN}
```
public static final int DC_PEN
```


قلم صلب اللون المحدد حاليًا في سياق جهاز التشغيل.

