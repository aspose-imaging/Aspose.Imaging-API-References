---
title: "SampleRoundingMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد طريقة يتم فيها تحويل قيمة n-بت إلى قيمة 8-بت."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

يحدد طريقة يتم فيها تحويل قيمة n-بت إلى قيمة 8-بت.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Extrapolate](#Extrapolate) | استخرج قيمة 8-بت لتناسبها في n بت، حيث 1 < n < 8. |
| [Truncate](#Truncate) | اقص قيمة 8-بت لتناسبها في n بت، حيث 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


استخرج قيمة 8-بت لتناسبها في n بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ذات 8-بت هو 1 << 8 = 256، من 0 إلى 255. عدد جميع القيم الممكنة ذات n-بت هو 1 << n، من 0 إلى (1 << n) - 1. القيمة الأكثر منطقية ذات n-بت Vn المقابلة لبعض قيمة 8-بت V8 تساوي Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


اقص قيمة 8-بت لتناسبها في n بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ذات n-بت هو 1 << n، من 0 إلى (1 << n) - 1. القيمة الأكثر منطقية ذات n-بت Vn المقابلة لبعض قيمة 8-بت V8 تساوي Vn = V8 & ((1 << n) - 1).

