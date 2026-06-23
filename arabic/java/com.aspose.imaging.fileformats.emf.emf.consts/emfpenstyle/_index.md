---
title: "EmfPenStyle"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد PenStyle سمات الأقلام التي يمكن استخدامها في عمليات الرسومات."
type: docs
weight: 34
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpenstyle/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPenStyle extends System.Enum
```

تحدد تعداد PenStyle خصائص الأقلام التي يمكن استخدامها في عمليات الرسومات. نمط القلم هو مزيج من نوع القلم، نمط الخط، شكل الطرف، وشكل الانضمام.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | نوع القلم الذي يحدد خطًا بعرض وحدة منطقية واحدة ونمطًا بلون صلب |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | شكل الطرف الذي يحدد نهايات مستديرة. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | شكل الانضمام الذي يحدد وصلات مستديرة |
| [PS_SOLID](#PS-SOLID) | نمط الخط الذي هو لون صلب |
| [PS_DASH](#PS-DASH) | نمط الخط الذي هو متقطع |
| [PS_DOT](#PS-DOT) | نمط الخط الذي هو منقط. |
| [PS_DASHDOT](#PS-DASHDOT) | نمط الخط الذي يتكون من شرطات ونقاط متناوبة |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | نمط الخط الذي يتكون من شرطات ونقط مزدوجة. |
| [PS_NULL](#PS-NULL) | نمط الخط الذي هو غير مرئي. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | نمط الخط الذي هو لون صلب. |
| [PS_USERSTYLE](#PS-USERSTYLE) | نمط الخط الذي يُعرّف بواسطة مصفوفة تنسيق، تحدد أطوال الشرطات والفجوات في الخط |
| [PS_ALTERNATE](#PS-ALTERNATE) | نمط الخط الذي يتم فيه تعيين كل بكسل بديل. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | شكل الطرف الذي يحدد نهايات مربعة. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | شكل الطرف الذي يحدد نهايات مسطحة. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | شكل الانضمام الذي يحدد وصلات مشطوفة. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | شكل الانضمام الذي يحدد وصلات مائلة عندما تكون أطوال الوصلات ضمن حد طول المائل الحالي المحدد في سياق جهاز التشغيل. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | نوع القلم الذي يحدد خطًا بعرض يُقاس بوحدات منطقية ونمطًا يمكن أن يحتوي على أي من خصائص الفرشاة. |
| [StyleMask](#StyleMask) | قناع النمط |
| [EndCapMask](#EndCapMask) | قناع الطرف النهائي |
| [JoinMask](#JoinMask) | قناع الانضمام |
| [TypeMask](#TypeMask) | قناع النوع |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


نوع القلم الذي يحدد خطًا بعرض وحدة منطقية واحدة ونمطًا بلون صلب

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


شكل الطرف الذي يحدد نهايات مستديرة.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


شكل الانضمام الذي يحدد وصلات مستديرة

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


نمط الخط الذي هو لون صلب

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


نمط الخط الذي هو متقطع

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


نمط الخط الذي هو منقط.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


نمط الخط الذي يتكون من شرطات ونقاط متناوبة

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


نمط الخط الذي يتكون من شرطات ونقط مزدوجة.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


نمط الخط الذي هو غير مرئي.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


نمط الخط الذي هو لون صلب. عندما يتم تحديد هذا النمط في سجل رسم يتضمن مستطيلًا محيطًا، يتم تقليص أبعاد الشكل بحيث يتناسب تمامًا داخل المستطيل المحيط، مع مراعاة عرض القلم.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


نمط الخط الذي يُعرّف بواسطة مصفوفة تنسيق، تحدد أطوال الشرطات والفجوات في الخط

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


نمط الخط الذي يتم فيه تعيين كل بكسل بديل. هذا النمط ينطبق فقط على نوع القلم PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


شكل الطرف الذي يحدد نهايات مربعة.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


شكل الطرف الذي يحدد نهايات مسطحة.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


شكل الانضمام الذي يحدد وصلات مشطوفة.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


شكل الانضمام الذي يحدد وصلات مائلة عندما تكون أطوال الوصلات ضمن حد طول المائل الحالي المحدد في سياق جهاز التشغيل. إذا تجاوزت أطوال الوصلات حد المائل، يتم تحديد وصلات مشطوفة.

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


نوع القلم الذي يحدد خطًا بعرض يُقاس بوحدات منطقية ونمطًا يمكن أن يحتوي على أي من خصائص الفرشاة.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


قناع النمط

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


قناع الطرف النهائي

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


قناع الانضمام

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


قناع النوع

