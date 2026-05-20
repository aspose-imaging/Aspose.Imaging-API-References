---
title: "SampleRoundingMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد طريقة تحويل قيمة n-بت إلى قيمة 8-بت."
type: docs
weight: 17
url: /ar/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

يحدد طريقة تحويل قيمة n-بت إلى قيمة 8-بت.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Extrapolate](#Extrapolate) | استخرج قيمة 8‑بت لتلائمها في n‑بت، حيث 1 < n < 8. |
| [Truncate](#Truncate) | قم بقطع قيمة 8‑بت لتلائمها في n‑بت، حيث 1 < n < 8. |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


استخرج قيمة 8‑بت لتلائمها في n‑بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ل‑8‑بت هو 1 << 8 = 256، من 0 إلى 255. عدد جميع القيم الممكنة ل‑n‑بت هو 1 << n، من 0 إلى (1 << n) - 1. أكثر قيمة n‑بت منطقية Vn المقابلة لقيمة 8‑بت V8 هي Vn = V8 >> (8 - n).

### Truncate {#Truncate}
```
public static final int Truncate
```


قم بقطع قيمة 8‑بت لتلائمها في n‑بت، حيث 1 < n < 8. عدد جميع القيم الممكنة ل‑n‑بت هو 1 << n، من 0 إلى (1 << n) - 1. أكثر قيمة n‑بت منطقية Vn المقابلة لقيمة 8‑بت V8 هي Vn = V8 & ((1 << n) - 1).

