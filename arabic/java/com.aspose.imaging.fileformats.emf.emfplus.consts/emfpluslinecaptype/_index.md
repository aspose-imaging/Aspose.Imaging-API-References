---
title: "EmfPlusLineCapType"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد LineCapType أنواع نهايات الخط لاستخدامها في نهايات الخطوط التي تُرسم بأقلام الرسومات."
type: docs
weight: 31
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusLineCapType extends System.Enum
```

تحدد تعداد LineCapType أنواع نهايات الخط لاستخدامها في نهايات الخطوط التي تُرسم بأقلام الرسومات.

--------------------

يتم تحديد نهايات خطوط الرسومات بواسطة كائنات [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) (القسم 2.2.1.7).
## الحقول

| حقل | الوصف |
| --- | --- |
| [LineCapTypeFlat](#LineCapTypeFlat) | يحدد قمة خط مربعة. |
| [LineCapTypeSquare](#LineCapTypeSquare) | يحدد قمة خط مربعة. |
| [LineCapTypeRound](#LineCapTypeRound) | يحدد قمة خط دائرية. |
| [LineCapTypeTriangle](#LineCapTypeTriangle) | يحدد قمة خط مثلثية. |
| [LineCapTypeNoAnchor](#LineCapTypeNoAnchor) | يحدد أن نهاية الخط غير مثبتة. |
| [LineCapTypeSquareAnchor](#LineCapTypeSquareAnchor) | يحدد أن نهاية الخط مثبتة بقمة خط مربعة. |
| [LineCapTypeRoundAnchor](#LineCapTypeRoundAnchor) | يحدد أن نهاية الخط مثبتة بقمة خط دائرية. |
| [LineCapTypeDiamondAnchor](#LineCapTypeDiamondAnchor) | يحدد أن نهاية الخط مثبتة بقمة خط على شكل ماسة، وهي مربع مائل بزاوية 45 درجة. |
| [LineCapTypeArrowAnchor](#LineCapTypeArrowAnchor) | يحدد أن نهاية الخط مثبتة بشكل رأس سهم. |
| [LineCapTypeAnchorMask](#LineCapTypeAnchorMask) | قناع يُستخدم للتحقق مما إذا كانت قمة الخط قمة تثبيت. |
| [LineCapTypeCustom](#LineCapTypeCustom) | يحدد غطاء خط مخصص. |
### LineCapTypeFlat {#LineCapTypeFlat}
```
public static final int LineCapTypeFlat
```


يحدد قمة خط مربعة. يجب أن تكون نهاية الخط هي النقطة الأخيرة في الخط.

### LineCapTypeSquare {#LineCapTypeSquare}
```
public static final int LineCapTypeSquare
```


يحدد قمة خط مربعة. يجب أن يكون مركز المربع موجودًا عند النقطة الأخيرة في الخط. عرض المربع هو عرض الخط.

### LineCapTypeRound {#LineCapTypeRound}
```
public static final int LineCapTypeRound
```


يحدد قمة خط دائرية. يجب أن يكون مركز الدائرة موجودًا عند النقطة الأخيرة في الخط. قطر الدائرة هو عرض الخط.

### LineCapTypeTriangle {#LineCapTypeTriangle}
```
public static final int LineCapTypeTriangle
```


يحدد قمة خط مثلثية. يجب أن يكون قاعدة المثلث موجودة عند النقطة الأخيرة في الخط. قاعدة المثلث هي عرض الخط.

### LineCapTypeNoAnchor {#LineCapTypeNoAnchor}
```
public static final int LineCapTypeNoAnchor
```


يحدد أن نهاية الخط غير مثبتة.

### LineCapTypeSquareAnchor {#LineCapTypeSquareAnchor}
```
public static final int LineCapTypeSquareAnchor
```


يحدد أن نهاية الخط مثبتة بقمة خط مربعة. يجب أن يكون مركز المربع موجودًا عند النقطة الأخيرة في الخط. ارتفاع وعرض المربع هو عرض الخط.

### LineCapTypeRoundAnchor {#LineCapTypeRoundAnchor}
```
public static final int LineCapTypeRoundAnchor
```


يحدد أن نهاية الخط مثبتة بقمة خط دائرية. يجب أن يكون مركز الدائرة موجودًا عند النقطة الأخيرة في الخط. يجب أن تكون الدائرة أوسع من الخط.

### LineCapTypeDiamondAnchor {#LineCapTypeDiamondAnchor}
```
public static final int LineCapTypeDiamondAnchor
```


يحدد أن نهاية الخط مثبتة بقمة خط على شكل ماسة، وهي مربع مائل بزاوية 45 درجة. يجب أن يكون مركز الماسة موجودًا عند النقطة الأخيرة في الخط. يجب أن تكون الماسة أوسع من الخط.

### LineCapTypeArrowAnchor {#LineCapTypeArrowAnchor}
```
public static final int LineCapTypeArrowAnchor
```


يحدد أن نهاية الخط مثبتة بشكل رأس سهم. يجب أن تكون نقطة رأس السهم موجودة عند النقطة الأخيرة في الخط. يجب أن يكون رأس السهم أوسع من الخط.

### LineCapTypeAnchorMask {#LineCapTypeAnchorMask}
```
public static final int LineCapTypeAnchorMask
```


قناع يُستخدم للتحقق مما إذا كانت قمة الخط قمة تثبيت.

### LineCapTypeCustom {#LineCapTypeCustom}
```
public static final int LineCapTypeCustom
```


يحدد غطاء خط مخصص.

