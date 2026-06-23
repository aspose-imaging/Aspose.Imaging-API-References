---
title: "طريقة الضغط"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحدد طريقة الضغط المستخدمة لبيانات الصورة."
type: docs
weight: 11
url: /ar/java/com.aspose.imaging.fileformats.psd/compressionmethod/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class CompressionMethod extends System.Enum
```

يحدد طريقة الضغط المستخدمة لبيانات الصورة.
## الحقول

| حقل | الوصف |
| --- | --- |
| [Raw](#Raw) | بدون ضغط. |
| [RLE](#RLE) | يبدأ بيانات الصورة المضغوطة بتقنية RLE بعدد البايتات لكل خطوط المسح (الصفوف \* القنوات)، حيث يتم تخزين كل عدد كقيمة من بايتين. |
| [ZipWithoutPrediction](#ZipWithoutPrediction) | ZIP بدون توقع. |
| [ZipWithPrediction](#ZipWithPrediction) | ZIP مع توقع. |
### Raw {#Raw}
```
public static final short Raw
```


بدون ضغط. تُخزن بيانات الصورة كبايتات خام بترتيب RGBA مسطح. هذا يعني أنه يتم كتابة جميع بيانات R أولاً، ثم جميع بيانات G، ثم جميع بيانات B وأخيرًا جميع بيانات A.

### RLE {#RLE}
```
public static final short RLE
```


تبدأ بيانات الصورة المضغوطة بتقنية RLE بعدد البايتات لكل خطوط المسح (الصفوف \* القنوات)، حيث يتم تخزين كل عدد كقيمة من بايتين. يتبع ذلك البيانات المضغوطة بتقنية RLE، حيث يتم ضغط كل خط مسح بشكل منفصل. ضغط RLE هو نفس خوارزمية الضغط المستخدمة في روتين Macintosh ROM PackBits ومعيار TIFF.

### ZipWithoutPrediction {#ZipWithoutPrediction}
```
public static final short ZipWithoutPrediction
```


ZIP بدون توقع.

### ZipWithPrediction {#ZipWithPrediction}
```
public static final short ZipWithPrediction
```


ZIP مع توقع.

