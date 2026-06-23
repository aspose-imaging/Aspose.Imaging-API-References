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
| [FilterTypeNone](#FilterTypeNone) | يحدد أنه لا يتم تنفيذ الترشيح. |
| [FilterTypePoint](#FilterTypePoint) | يحدد أنه يتم حساب كل بكسل وجهة عن طريق أخذ عينة من أقرب بكسل من صورة المصدر. |
| [FilterTypeLinear](#FilterTypeLinear) | يحدد أنه يتم إجراء الاستيفاء الخطي باستخدام المتوسط المرجح لمنطقة 2×2 بكسل تحيط بالبكسل المصدر. |
| [FilterTypeTriangle](#FilterTypeTriangle) | يحدد أن كل بكسل في صورة المصدر يساهم بالتساوي في صورة الوجهة. |
| [FilterTypeBox](#FilterTypeBox) | يحدد خوارزمية مرشح الصندوق، حيث يتم حساب كل بكسل وجهة عن طريق متوسط مستطيل من بكسلات المصدر. |
| [FilterTypePyramidalQuad](#FilterTypePyramidalQuad) | يحدد أنه يتم استخدام مرشح خيمة مكوّن من 4 عينات. |
| [FilterTypeGaussianQuad](#FilterTypeGaussianQuad) | يحدد أنه يتم استخدام مرشح غاوسي مكوّن من 4 عينات، مما يخلق تأثير تشويش على الصورة. |
### FilterTypeNone {#FilterTypeNone}
```
public static final byte FilterTypeNone
```


يحدد أنه لا يتم تنفيذ الترشيح.

### FilterTypePoint {#FilterTypePoint}
```
public static final byte FilterTypePoint
```


يحدد أنه يتم حساب كل بكسل وجهة عن طريق أخذ عينة من أقرب بكسل من صورة المصدر.

### FilterTypeLinear {#FilterTypeLinear}
```
public static final byte FilterTypeLinear
```


يحدد أنه يتم إجراء الاستيفاء الخطي باستخدام المتوسط المرجح لمنطقة 2×2 بكسل تحيط بالبكسل المصدر.

### FilterTypeTriangle {#FilterTypeTriangle}
```
public static final byte FilterTypeTriangle
```


يحدد أن كل بكسل في صورة المصدر يساهم بالتساوي في صورة الوجهة. هذا هو أبطأ خوارزميات الترشيح.

### FilterTypeBox {#FilterTypeBox}
```
public static final byte FilterTypeBox
```


يحدد خوارزمية مرشح الصندوق، حيث يتم حساب كل بكسل وجهة عن طريق متوسط مستطيل من بكسلات المصدر. هذه الخوارزمية مفيدة فقط عند تقليل حجم الصورة.

### FilterTypePyramidalQuad {#FilterTypePyramidalQuad}
```
public static final byte FilterTypePyramidalQuad
```


يحدد أنه يتم استخدام مرشح خيمة مكوّن من 4 عينات.

### FilterTypeGaussianQuad {#FilterTypeGaussianQuad}
```
public static final byte FilterTypeGaussianQuad
```


يحدد أنه يتم استخدام مرشح غاوسي مكوّن من 4 عينات، مما يخلق تأثير تشويش على الصورة.

