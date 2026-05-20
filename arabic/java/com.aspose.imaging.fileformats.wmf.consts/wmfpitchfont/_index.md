---
title: "WmfPitchFont"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد تعداد PitchFont القيم المستخدمة لتحديد خصائص الخط."
type: docs
weight: 29
url: /ar/java/com.aspose.imaging.fileformats.wmf.consts/wmfpitchfont/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPitchFont extends System.Enum
```

تحدد تعداد PitchFont القيم المستخدمة لتحديد خصائص الخط. تُستخدم القيم للإشارة إلى ما إذا كانت الأحرف في الخط ذات عرض ثابت أو متغير، أو ذات خطوة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [DEFAULT_PITCH](#DEFAULT-PITCH) | العرض الافتراضي، والذي يعتمد على التنفيذ. |
| [FIXED_PITCH](#FIXED-PITCH) | خطوة ثابتة، مما يعني أن جميع الأحرف في الخط تشغل نفس العرض عند إخراجها في سلسلة. |
| [VARIABLE_PITCH](#VARIABLE-PITCH) | خطوة متغيرة، مما يعني أن الأحرف في الخط تشغل عرضًا يتناسب مع العرض الفعلي للرموز عند إخراجها في سلسلة. |
### DEFAULT_PITCH {#DEFAULT-PITCH}
```
public static final byte DEFAULT_PITCH
```


العرض الافتراضي، والذي يعتمد على التنفيذ.

### FIXED_PITCH {#FIXED-PITCH}
```
public static final byte FIXED_PITCH
```


خطوة ثابتة، مما يعني أن جميع الأحرف في الخط تشغل نفس العرض عند إخراجها في سلسلة.

### VARIABLE_PITCH {#VARIABLE-PITCH}
```
public static final byte VARIABLE_PITCH
```


خطوة متغيرة، مما يعني أن الأحرف في الخط تشغل عرضًا يتناسب مع العرض الفعلي للرموز عند إخراجها في سلسلة. على سبيل المثال، عادةً ما تكون أحرف "i" والمسافة أصغر بكثير من حرف "W" أو "O".

