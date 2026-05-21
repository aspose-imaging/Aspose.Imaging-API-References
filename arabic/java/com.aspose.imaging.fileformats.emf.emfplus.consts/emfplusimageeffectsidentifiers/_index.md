---
title: "EmfPlusImageEffectsIdentifiers"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد معرفات ImageEffects GUIDs القياسية لتحديد تأثيرات صورة الرسومات."
type: docs
weight: 28
url: /ar/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusimageeffectsidentifiers/
---
**Inheritance:**
java.lang.Object
```
public final class EmfPlusImageEffectsIdentifiers
```

معرّفات ImageEffects تُعرّف GUIDs القياسية لتحديد تأثيرات الصور الرسومية. تُستخدم هذه المعرّفات بواسطة برامج تشغيل الأجهزة لنشر مستويات الدعم لهذه التأثيرات. تُعرّف ثوابت المعرف باستخدام تمثيل سلسلة GUID بين أقواس معقوفة ([MS-DTYP] القسم 2.3.4.3).

--------------------

يتم تحديد معرّفات تأثيرات الصورة وكتل معلمات تأثيرات الصورة بواسطة سجلات [EmfPlusSerializableObject](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusserializableobject) لسجلات [EmfPlusDrawImagePoints](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints).
## الحقول

| حقل | الوصف |
| --- | --- |
| [BLUR_EFFECT_GUID](#BLUR-EFFECT-GUID) | يحدد تأثير الضبابية. |
| [BRIGHTNESS_CONTRAST_EFFECT_GUID](#BRIGHTNESS-CONTRAST-EFFECT-GUID) | يحدد تأثير سطوع وتباين. |
| [COLOR_BALANCE_EFFECT_GUID](#COLOR-BALANCE-EFFECT-GUID) | يحدد تأثير توازن الألوان. |
| [COLOR_CURVE_EFFECT_GUID](#COLOR-CURVE-EFFECT-GUID) | يحدد تأثير منحنى اللون. |
| [COLOR_LOOKUP_TABLE_EFFECT_GUID](#COLOR-LOOKUP-TABLE-EFFECT-GUID) | يحدد تأثير جدول البحث اللوني. |
| [COLOR_MATRIX_EFFECT_GUID](#COLOR-MATRIX-EFFECT-GUID) | يحدد تأثير مصفوفة اللون. |
| [HUE_SATURATION_LIGHTNESS_EFFECT_GUID](#HUE-SATURATION-LIGHTNESS-EFFECT-GUID) | يحدد تأثير درجة اللون والتشبع والإضاءة. |
| [LEVELS_EFFECT_GUID](#LEVELS-EFFECT-GUID) | يحدد تأثير المستويات. |
| [RED_EYE_CORRECTION_EFFECT_GUID](#RED-EYE-CORRECTION-EFFECT-GUID) | يحدد تأثير تصحيح العين الحمراء. |
| [SHARPEN_EFFECT_GUID](#SHARPEN-EFFECT-GUID) | يحدد تأثير الشحذ. |
| [TINT_EFFECT_GUID](#TINT-EFFECT-GUID) | يحدد تأثير الصبغة. |
## الطرق

| طريقة | الوصف |
| --- | --- |
| [contain(String objectGuid)](#contain-java.lang.String-) | يحتوي على المعرف الفريد للعنصر المحدد. |
### BLUR_EFFECT_GUID {#BLUR-EFFECT-GUID}
```
public static final String BLUR_EFFECT_GUID
```


يحدد تأثير الضبابية.

### BRIGHTNESS_CONTRAST_EFFECT_GUID {#BRIGHTNESS-CONTRAST-EFFECT-GUID}
```
public static final String BRIGHTNESS_CONTRAST_EFFECT_GUID
```


يحدد تأثير سطوع وتباين.

### COLOR_BALANCE_EFFECT_GUID {#COLOR-BALANCE-EFFECT-GUID}
```
public static final String COLOR_BALANCE_EFFECT_GUID
```


يحدد تأثير توازن الألوان.

### COLOR_CURVE_EFFECT_GUID {#COLOR-CURVE-EFFECT-GUID}
```
public static final String COLOR_CURVE_EFFECT_GUID
```


يحدد تأثير منحنى اللون.

### COLOR_LOOKUP_TABLE_EFFECT_GUID {#COLOR-LOOKUP-TABLE-EFFECT-GUID}
```
public static final String COLOR_LOOKUP_TABLE_EFFECT_GUID
```


يحدد تأثير جدول البحث اللوني.

### COLOR_MATRIX_EFFECT_GUID {#COLOR-MATRIX-EFFECT-GUID}
```
public static final String COLOR_MATRIX_EFFECT_GUID
```


يحدد تأثير مصفوفة اللون.

### HUE_SATURATION_LIGHTNESS_EFFECT_GUID {#HUE-SATURATION-LIGHTNESS-EFFECT-GUID}
```
public static final String HUE_SATURATION_LIGHTNESS_EFFECT_GUID
```


يحدد تأثير درجة اللون والتشبع والإضاءة.

### LEVELS_EFFECT_GUID {#LEVELS-EFFECT-GUID}
```
public static final String LEVELS_EFFECT_GUID
```


يحدد تأثير المستويات.

### RED_EYE_CORRECTION_EFFECT_GUID {#RED-EYE-CORRECTION-EFFECT-GUID}
```
public static final String RED_EYE_CORRECTION_EFFECT_GUID
```


يحدد تأثير تصحيح العين الحمراء.

### SHARPEN_EFFECT_GUID {#SHARPEN-EFFECT-GUID}
```
public static final String SHARPEN_EFFECT_GUID
```


يحدد تأثير الشحذ.

### TINT_EFFECT_GUID {#TINT-EFFECT-GUID}
```
public static final String TINT_EFFECT_GUID
```


يحدد تأثير الصبغة.

### contain(String objectGuid) {#contain-java.lang.String-}
```
public static boolean contain(String objectGuid)
```


يحتوي على المعرف الفريد للعنصر المحدد.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| objectGuid | java.lang.String | معرف العنصر الفريد. |

**Returns:**
منطقي - صحيح إذا كان يحتوي.
