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

تعداد PenStyle يحدد سمات الأقلام التي يمكن استخدامها في عمليات الرسومات. نمط القلم هو مزيج من نوع القلم، نمط الخط، طرف الخط، وتوصيل الخط.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PS_COSMETIC](#PS-COSMETIC) | نوع قلم يحدد خطًا بعرض وحدة منطقية واحدة ونمطًا بلون صلب. |
| [PS_ENDCAP_ROUND](#PS-ENDCAP-ROUND) | طرف خط يحدد نهايات مستديرة. |
| [PS_JOIN_ROUND](#PS-JOIN-ROUND) | توصيل خط يحدد وصلات مستديرة. |
| [PS_SOLID](#PS-SOLID) | نمط خط بلون صلب. |
| [PS_DASH](#PS-DASH) | نمط خط متقطع. |
| [PS_DOT](#PS-DOT) | نمط خط منقط. |
| [PS_DASHDOT](#PS-DASHDOT) | نمط خط يتكون من شرطات ونقاط متناوبة |
| [PS_DASHDOTDOT](#PS-DASHDOTDOT) | نمط خط يتكون من شرطات ونقاط مزدوجة. |
| [PS_NULL](#PS-NULL) | نمط خط غير مرئي. |
| [PS_INSIDEFRAME](#PS-INSIDEFRAME) | نمط خط بلون صلب. |
| [PS_USERSTYLE](#PS-USERSTYLE) | نمط خط يتم تعريفه بواسطة مصفوفة تنسيق، تحدد أطوال الشرطات والفجوات في الخط |
| [PS_ALTERNATE](#PS-ALTERNATE) | نمط خط يتم فيه تعيين كل بكسل ثاني. |
| [PS_ENDCAP_SQUARE](#PS-ENDCAP-SQUARE) | غطاء خط يحدد نهايات مربعة. |
| [PS_ENDCAP_FLAT](#PS-ENDCAP-FLAT) | غطاء خط يحدد نهايات مسطحة. |
| [PS_JOIN_BEVEL](#PS-JOIN-BEVEL) | وصلة خط تحدد وصلات مشطوفة. |
| [PS_JOIN_MITER](#PS-JOIN-MITER) | وصلة خط تحدد وصلات ميتيرية عندما تكون أطوال الوصلات ضمن حد طول الميتر الحالي المحدد في سياق جهاز التشغيل. |
| [PS_GEOMETRIC](#PS-GEOMETRIC) | نوع قلم يحدد خطًا بعرض يُقاس بوحدات منطقية ونمط يمكن أن يحتوي على أي من خصائص الفرشاة. |
| [StyleMask](#StyleMask) | قناع النمط |
| [EndCapMask](#EndCapMask) | قناع غطاء النهاية |
| [JoinMask](#JoinMask) | قناع الوصلة |
| [TypeMask](#TypeMask) | قناع النوع |
### PS_COSMETIC {#PS-COSMETIC}
```
public static final int PS_COSMETIC
```


نوع قلم يحدد خطًا بعرض وحدة منطقية واحدة ونمطًا بلون صلب.

### PS_ENDCAP_ROUND {#PS-ENDCAP-ROUND}
```
public static final int PS_ENDCAP_ROUND
```


طرف خط يحدد نهايات مستديرة.

### PS_JOIN_ROUND {#PS-JOIN-ROUND}
```
public static final int PS_JOIN_ROUND
```


توصيل خط يحدد وصلات مستديرة.

### PS_SOLID {#PS-SOLID}
```
public static final int PS_SOLID
```


نمط خط بلون صلب.

### PS_DASH {#PS-DASH}
```
public static final int PS_DASH
```


نمط خط متقطع.

### PS_DOT {#PS-DOT}
```
public static final int PS_DOT
```


نمط خط منقط.

### PS_DASHDOT {#PS-DASHDOT}
```
public static final int PS_DASHDOT
```


نمط خط يتكون من شرطات ونقاط متناوبة

### PS_DASHDOTDOT {#PS-DASHDOTDOT}
```
public static final int PS_DASHDOTDOT
```


نمط خط يتكون من شرطات ونقاط مزدوجة.

### PS_NULL {#PS-NULL}
```
public static final int PS_NULL
```


نمط خط غير مرئي.

### PS_INSIDEFRAME {#PS-INSIDEFRAME}
```
public static final int PS_INSIDEFRAME
```


نمط خط بلون صلب. عندما يتم تحديد هذا النمط في سجل رسم يأخذ مستطيلًا محيطًا، يتم تقليص أبعاد الشكل بحيث يتناسب تمامًا داخل المستطيل المحيط، مع مراعاة عرض القلم.

### PS_USERSTYLE {#PS-USERSTYLE}
```
public static final int PS_USERSTYLE
```


نمط خط يتم تعريفه بواسطة مصفوفة تنسيق، تحدد أطوال الشرطات والفجوات في الخط

### PS_ALTERNATE {#PS-ALTERNATE}
```
public static final int PS_ALTERNATE
```


نمط خط يتم فيه تعيين كل بكسل ثاني. هذا النمط ينطبق فقط على نوع قلم PS\_COSMETIC

### PS_ENDCAP_SQUARE {#PS-ENDCAP-SQUARE}
```
public static final int PS_ENDCAP_SQUARE
```


غطاء خط يحدد نهايات مربعة.

### PS_ENDCAP_FLAT {#PS-ENDCAP-FLAT}
```
public static final int PS_ENDCAP_FLAT
```


غطاء خط يحدد نهايات مسطحة.

### PS_JOIN_BEVEL {#PS-JOIN-BEVEL}
```
public static final int PS_JOIN_BEVEL
```


وصلة خط تحدد وصلات مشطوفة.

### PS_JOIN_MITER {#PS-JOIN-MITER}
```
public static final int PS_JOIN_MITER
```


وصلة خط تحدد وصلات ميتيرية عندما تكون أطوال الوصلات ضمن حد طول الميتر الحالي المحدد في سياق جهاز التشغيل. إذا تجاوزت أطوال الوصلات حد الميتر، يتم تحديد وصلات مشطوفة.

### PS_GEOMETRIC {#PS-GEOMETRIC}
```
public static final int PS_GEOMETRIC
```


نوع قلم يحدد خطًا بعرض يُقاس بوحدات منطقية ونمط يمكن أن يحتوي على أي من خصائص الفرشاة.

### StyleMask {#StyleMask}
```
public static final int StyleMask
```


قناع النمط

### EndCapMask {#EndCapMask}
```
public static final int EndCapMask
```


قناع غطاء النهاية

### JoinMask {#JoinMask}
```
public static final int JoinMask
```


قناع الوصلة

### TypeMask {#TypeMask}
```
public static final int TypeMask
```


قناع النوع

