---
title: "EmfPlusCompositingQuality"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد CompositingQuality يحدد مستويات الجودة لإنشاء صور مركبة"
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluscompositingquality/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusCompositingQuality extends System.Enum
```

تعداد CompositingQuality يحدد مستويات الجودة لإنشاء صور مركبة
## الحقول

| حقل | الوصف |
| --- | --- |
| [CompositingQualityDefault](#CompositingQualityDefault) | لم يتم إجراء تصحيح غاما. |
| [CompositingQualityHighSpeed](#CompositingQualityHighSpeed) | لم يتم إجراء تصحيح غاما. |
| [CompositingQualityHighQuality](#CompositingQualityHighQuality) | تم إجراء تصحيح غاما. |
| [CompositingQualityGammaCorrected](#CompositingQualityGammaCorrected) | تمكين تصحيح غاما للحصول على تجميع عالي الجودة مع سرعة أقل. |
| [CompositingQualityAssumeLinear](#CompositingQualityAssumeLinear) | لم يتم إجراء تصحيح غاما؛ ومع ذلك، يؤدي استخدام القيم الخطية إلى جودة أفضل من الإعداد الافتراضي بسرعة أقل قليلاً. |
### CompositingQualityDefault {#CompositingQualityDefault}
```
public static final byte CompositingQualityDefault
```


لم يتم إجراء تصحيح غاما. يتحكم تصحيح غاما في السطوع والتباين العامين للصورة. بدون تصحيح غاما، قد تظهر الصور المركبة فاتحة جدًا أو داكنة جدًا.

### CompositingQualityHighSpeed {#CompositingQualityHighSpeed}
```
public static final byte CompositingQualityHighSpeed
```


لم يتم إجراء تصحيح غاما. يتم تفضيل سرعة التجميع على حساب الجودة. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityDefault.

### CompositingQualityHighQuality {#CompositingQualityHighQuality}
```
public static final byte CompositingQualityHighQuality
```


تم إجراء تصحيح غاما. يتم تفضيل جودة التجميع على حساب السرعة.

### CompositingQualityGammaCorrected {#CompositingQualityGammaCorrected}
```
public static final byte CompositingQualityGammaCorrected
```


تمكين تصحيح غاما للحصول على تجميع عالي الجودة مع سرعة أقل. من حيث النتيجة، لا يوجد فرق بين هذه القيمة وCompositingQualityHighQuality.

### CompositingQualityAssumeLinear {#CompositingQualityAssumeLinear}
```
public static final byte CompositingQualityAssumeLinear
```


لم يتم إجراء تصحيح غاما؛ ومع ذلك، يؤدي استخدام القيم الخطية إلى جودة أفضل من الإعداد الافتراضي بسرعة أقل قليلاً.

