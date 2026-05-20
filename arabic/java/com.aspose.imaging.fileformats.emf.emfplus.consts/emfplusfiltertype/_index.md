---
title: "EmfPlusFilterType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد FilterType أنواع خوارزميات الترشيح التي يمكن استخدامها لتحسين جودة النص والرسومات وعرض الصور."
type: docs
weight: 22
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusfiltertype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusFilterType extends System.Enum
```

تحدد تعداد FilterType أنواع خوارزميات الترشيح التي يمكن استخدامها لتحسين جودة النص والرسومات وعرض الصور.
## الحقول

| حقل | الوصف |
| --- | --- |
| [FilterTypeNone](#FilterTypeNone) | يحدد أنه لا يتم إجراء الترشيح. |
| [FilterTypePoint](#FilterTypePoint) | يحدد أن كل بكسل هدف يُحسب عن طريق أخذ عينة من أقرب بكسل من الصورة المصدر. |
| [FilterTypeLinear](#FilterTypeLinear) | يحدد أن الاستيفاء الخطي يُجرى باستخدام المتوسط المرجح لمنطقة 2×2 بكسل حول بكسل المصدر. |
| [FilterTypeTriangle](#FilterTypeTriangle) | يحدد أن كل بكسل في الصورة المصدر يساهم بالتساوي في الصورة الهدف. |
| [FilterTypeBox](#FilterTypeBox) | يحدد خوارزمية مرشح الصندوق، حيث يُحسب كل بكسل هدف بمتوسط مستطيل من بكسلات المصدر. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | يحدد أنه يتم استخدام مرشح خيمة بـ 4 عينات. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | يحدد أنه يتم استخدام مرشح Gaussian بـ 4 عينات، مما يخلق تأثير ضبابية على الصورة. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


يحدد أنه لا يتم إجراء الترشيح.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


يحدد أن كل بكسل هدف يُحسب عن طريق أخذ عينة من أقرب بكسل من الصورة المصدر.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


يحدد أن الاستيفاء الخطي يُجرى باستخدام المتوسط المرجح لمنطقة 2×2 بكسل حول بكسل المصدر.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


يحدد أن كل بكسل في الصورة المصدر يساهم بالتساوي في الصورة الهدف. هذا هو أبطأ خوارزميات الترشيح.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


يحدد خوارزمية مرشح الصندوق، حيث يتم حساب كل بكسل هدف عن طريق متوسط مستطيل من بكسلات المصدر. هذه الخوارزمية مفيدة فقط عند تقليل حجم الصورة.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


يحدد أنه يتم استخدام مرشح خيمة بـ 4 عينات.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


يحدد أنه يتم استخدام مرشح Gaussian بـ 4 عينات، مما يخلق تأثير ضبابية على الصورة.

