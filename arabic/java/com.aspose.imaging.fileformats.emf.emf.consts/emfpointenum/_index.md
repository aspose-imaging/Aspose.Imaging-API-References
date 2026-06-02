---
title: "EmfPointEnum"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يُستخدم تعداد Point لتحديد كيفية استخدام نقطة في استدعاء الرسم."
type: docs
weight: 35
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfpointenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPointEnum extends System.Enum
```

يُستخدم تعداد Point لتحديد كيفية استخدام نقطة في استدعاء الرسم.
## الحقول

| حقل | الوصف |
| --- | --- |
| [PT_CLOSEFIGURE](#PT-CLOSEFIGURE) | يمكن دمج نوع PT\_LINETO أو PT\_BEZIERTO مع هذه القيمة باستخدام عامل OR البتّي للإشارة إلى أن النقطة المقابلة هي النقطة الأخيرة في الشكل وأن الشكل مغلق |
| [PT_LINETO](#PT-LINETO) | يحدد أنه يجب رسم خط من الموضع الحالي إلى هذه النقطة، والتي تصبح بعد ذلك الموضع الحالي الجديد |
| [PT_BEZIERTO](#PT-BEZIERTO) | يحدد أن هذه النقطة هي نقطة تحكم أو نقطة نهاية لمنحنى بيزير. |
| [PT_MOVETO](#PT-MOVETO) | يحدد أن هذه النقطة تبدأ شكلاً منفصلاً. |
### PT_CLOSEFIGURE {#PT-CLOSEFIGURE}
```
public static final byte PT_CLOSEFIGURE
```


يمكن دمج نوع PT\_LINETO أو PT\_BEZIERTO مع هذه القيمة باستخدام عامل OR البتّي للإشارة إلى أن النقطة المقابلة هي النقطة الأخيرة في الشكل وأن الشكل مغلق

### PT_LINETO {#PT-LINETO}
```
public static final byte PT_LINETO
```


يحدد أنه يجب رسم خط من الموضع الحالي إلى هذه النقطة، والتي تصبح بعد ذلك الموضع الحالي الجديد

### PT_BEZIERTO {#PT-BEZIERTO}
```
public static final byte PT_BEZIERTO
```


يحدد أن هذه النقطة هي نقطة تحكم أو نقطة نهاية لمنحنى بيزير.

### PT_MOVETO {#PT-MOVETO}
```
public static final byte PT_MOVETO
```


يحدد أن هذه النقطة تبدأ شكلاً منفصلاً. تصبح هذه النقطة الموضع الحالي الجديد.

