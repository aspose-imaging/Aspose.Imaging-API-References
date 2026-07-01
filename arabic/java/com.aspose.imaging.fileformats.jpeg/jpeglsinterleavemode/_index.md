---
title: "JpegLsInterleaveMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد وضع التداخل لبيانات بكسل اللون متعددة المكونات."
type: docs
weight: 15
url: /ar/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

يحدد وضع التداخل لبيانات البكسل متعددة المكونات (اللون).
## الحقول

| حقل | الوصف |
| --- | --- |
| [None](#None) | يتم ترميز البيانات وتخزينها كمكوّن لكل مكوّن: RRRGGGBBB. |
| [Line](#Line) | وضع التداخل يكون حسب السطر. |
| [Sample](#Sample) | يتم ترميز البيانات وتخزينها بواسطة العينة. |
### None {#None}
```
public static final int None
```


يتم ترميز البيانات وتخزينها كمكوّن لكل مكوّن: RRRGGGBBB.

### Line {#Line}
```
public static final int Line
```


وضع التداخل هو حسب السطر. يتم ترميز سطر كامل من كل مكوّن قبل الانتقال إلى السطر التالي.

### Sample {#Sample}
```
public static final int Sample
```


يتم ترميز البيانات وتخزينها بواسطة العينة. بالنسبة للصور الملونة، هذا هو التنسيق مثل RGBRGBRGB.

