---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Kaynak ve hedef piksellerin alfa şeffaflığı açısından nasıl yorumlandığını belirten bir yapı."
type: docs
weight: 10
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

Kaynak ve hedef piksellerin alfa şeffaflığı açısından nasıl yorumlandığını belirten bir yapı.
## Alanlar

| Alan | Açıklama |
| --- | --- |
| [NotTransparency](#NotTransparency) | Kaynak bitmap'teki pikseller alfa şeffaflığını belirtmez. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | Kaynak bitmap'in piksel başına 32 bit olduğunu ve her piksel için bir alfa şeffaflık değeri belirttiğini gösterir. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


Kaynak bitmap'teki pikseller alfa şeffaflığını belirtmez. Bu durumda, SrcConstantAlpha değeri kaynak ve hedef bitmap'lerin karışımını belirler. Aşağıdaki denklemlerde SrcConstantAlpha'ın 255'e bölündüğüne dikkat edin; bu, 0 ile 1 arasında bir değer üretir.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


Kaynak bitmap'in piksel başına 32 bit olduğunu ve her piksel için bir alfa şeffaflık değeri belirttiğini gösterir.

