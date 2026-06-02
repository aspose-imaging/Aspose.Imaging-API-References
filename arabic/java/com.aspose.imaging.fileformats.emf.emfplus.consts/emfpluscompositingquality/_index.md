---
title: "EmfPlusCompositingQuality"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد CompositingQuality يحدد مستويات الجودة لإنشاء صور مركبة."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

تعداد CompositingQuality يحدد مستويات الجودة لإنشاء صور مركبة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | لا يتم إجراء تصحيح جاما. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | لا يتم إجراء تصحيح جاما. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | يتم إجراء تصحيح جاما. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | تمكين تصحيح الجاما للحصول على تجميع بجودة أعلى مع سرعة أقل. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | لا يتم إجراء تصحيح جاما؛ ومع ذلك، يؤدي استخدام القيم الخطية إلى جودة أفضل من الإعداد الافتراضي بسرعة أقل قليلاً. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


لا يتم إجراء تصحيح جاما. يتحكم تصحيح الجاما في السطوع والتباين العامين للصورة. بدون تصحيح جاما، قد تظهر الصور المركبة فاتحة جدًا أو داكنة جدًا.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


لا يتم إجراء تصحيح جاما. يتم تفضيل سرعة التجميع على حساب الجودة. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


يتم إجراء تصحيح جاما. يتم تفضيل جودة التجميع على حساب السرعة.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


تمكين تصحيح الجاما للحصول على تجميع بجودة أعلى مع سرعة أقل. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


لا يتم إجراء تصحيح جاما؛ ومع ذلك، يؤدي استخدام القيم الخطية إلى جودة أفضل من الإعداد الافتراضي بسرعة أقل قليلاً.

