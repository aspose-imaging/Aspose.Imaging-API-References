---
title: "TextRenderingHint"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد جودة عرض النص."
type: docs
weight: 115
url: /ar/java/com.aspose.imaging/textrenderinghint/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TextRenderingHint extends System.Enum
```

يحدد جودة عرض النص.
## الحقول

| حقل | الوصف |
| --- | --- |
| [SystemDefault](#SystemDefault) | يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز، مع تلميح العرض الافتراضي للنظام. |
| [SingleBitPerPixelGridFit](#SingleBitPerPixelGridFit) | يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز. |
| [SingleBitPerPixel](#SingleBitPerPixel) | يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز. |
| [AntiAliasGridFit](#AntiAliasGridFit) | يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز مع التلميح. |
| [AntiAlias](#AntiAlias) | يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح. |
| [ClearTypeGridFit](#ClearTypeGridFit) | يتم رسم كل حرف باستخدام خريطة البكسل ClearType للرمز مع التلميح. |
### SystemDefault {#SystemDefault}
```
public static final int SystemDefault
```


يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز، مع تلميح العرض الافتراضي للنظام. سيتم رسم النص باستخدام أي إعدادات تنعيم الخط التي اختارها المستخدم للنظام.

### SingleBitPerPixelGridFit {#SingleBitPerPixelGridFit}
```
public static final int SingleBitPerPixelGridFit
```


يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز. يُستخدم التلميح لتحسين مظهر الحرف على الجذوع والانحناءات.

### SingleBitPerPixel {#SingleBitPerPixel}
```
public static final int SingleBitPerPixel
```


يتم رسم كل حرف باستخدام خريطة البكسل الخاصة بالرمز. لا يُستخدم التلميح.

### AntiAliasGridFit {#AntiAliasGridFit}
```
public static final int AntiAliasGridFit
```


يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز مع التلميح. جودة أفضل بكثير بفضل مضاد التنعيم، لكن بتكلفة أداء أعلى.

### AntiAlias {#AntiAlias}
```
public static final int AntiAlias
```


يتم رسم كل حرف باستخدام خريطة البكسل المضادة للتنعيم للرمز بدون التلميح. جودة أفضل بفضل مضاد التنعيم. قد تكون اختلافات عرض الجذوع ملحوظة لأن التلميح مُعطل.

### ClearTypeGridFit {#ClearTypeGridFit}
```
public static final int ClearTypeGridFit
```


يتم رسم كل حرف باستخدام خريطة البكسل ClearType للرمز مع التلميح. أعلى إعداد جودة. يُستخدم للاستفادة من ميزات خط ClearType.

