---
title: "EmfPlusTextRenderingHint"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعرّف تعداد TextRenderingHint أنواع تلميح النص والتنعيم المضاد التي تؤثر على جودة عرض النص."
type: docs
weight: 52
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplustextrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusTextRenderingHint extends System.Enum
```

تحدد تعداد TextRenderingHint أنواع تلميحات النص وإزالة التعرجات، مما يؤثر على جودة عرض النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [TextRenderingHintSystemDefault](#TextRenderingHintSystemDefault) | يحدد أنه يجب رسم كل حرف نصي SHOULD باستخدام أي إعدادات تنعيم الخط التي تم تكوينها في نظام التشغيل. |
| [TextRenderingHintSingleBitPerPixelGridFit](#TextRenderingHintSingleBitPerPixelGridFit) | يحدد أنه يجب رسم كل حرف نصي SHOULD باستخدام مخطط البكسل الخاص بالرمز. |
| [TextRenderingHintSingleBitPerPixel](#TextRenderingHintSingleBitPerPixel) | يحدد أنه يجب رسم كل حرف نصي SHOULD باستخدام مخطط البكسل الخاص بالرمز. |
| [TextRenderingHintAntialiasGridFit](#TextRenderingHintAntialiasGridFit) | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز المضاد للتنعيم مع التنعيم. |
| [TextRenderingHintAntialias](#TextRenderingHintAntialias) | يحدد أن كل حرف نصي يتم رسمه باستخدام صورة البت للرمز المضاد للتنعيم بدون توجيه. |
| [TextRenderingHintClearTypeGridFit](#TextRenderingHintClearTypeGridFit) | يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز ClearType مع التنعيم. |
### TextRenderingHintSystemDefault {#TextRenderingHintSystemDefault}
```
public static final byte TextRenderingHintSystemDefault
```


يحدد أنه يجب رسم كل حرف نصي SHOULD باستخدام أي إعدادات تنعيم الخط التي تم تكوينها في نظام التشغيل.

### TextRenderingHintSingleBitPerPixelGridFit {#TextRenderingHintSingleBitPerPixelGridFit}
```
public static final byte TextRenderingHintSingleBitPerPixelGridFit
```


يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز. قد يُستخدم التنعيم لتحسين مظهر جذوع الرموز المنحنية وانحناءها.

### TextRenderingHintSingleBitPerPixel {#TextRenderingHintSingleBitPerPixel}
```
public static final byte TextRenderingHintSingleBitPerPixel
```


يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز. لا يُستخدم التنعيم.

### TextRenderingHintAntialiasGridFit {#TextRenderingHintAntialiasGridFit}
```
public static final byte TextRenderingHintAntialiasGridFit
```


يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز المضاد للتنعيم مع التنعيم. العرض عالي الجودة بسبب مضاد التنعيم، لكن بتكلفة أداء أعلى.

### TextRenderingHintAntialias {#TextRenderingHintAntialias}
```
public static final byte TextRenderingHintAntialias
```


يحدد أن كل حرف نصي يتم رسمه باستخدام صورة البت للرمز المضاد للتنعيم بدون توجيه. جودة أفضل تنتج عن مضاد التنعيم، لكن قد تكون اختلافات عرض الجذع ملحوظة لأن التوجيه مُعطل.

### TextRenderingHintClearTypeGridFit {#TextRenderingHintClearTypeGridFit}
```
public static final byte TextRenderingHintClearTypeGridFit
```


يحدد أنه يجب رسم كل حرف نصي باستخدام صورة البت للرمز ClearType مع التنعيم. هذا هو أعلى إعداد لتوجيه النص جودةً، ويُستخدم للاستفادة من ميزات خط ClearType.

