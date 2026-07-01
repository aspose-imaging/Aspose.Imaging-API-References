---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "Aspose.Imaging for Java API 参考"
description: "一个结构，指定如何根据 alpha 透明度解释源像素和目标像素。"
type: docs
weight: 10
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

一个结构，指定如何根据 alpha 透明度解释源像素和目标像素。
## 字段

| 字段 | 描述 |
| --- | --- |
| [NotTransparency](#NotTransparency) | 源位图中的像素未指定 alpha 透明度。 |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | 指示源位图为每像素 32 位，并为每个像素指定 alpha 透明度值。 |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


源位图中的像素未指定 alpha 透明度。在这种情况下，SrcConstantAlpha 值决定源位图和目标位图的混合。请注意，在下列公式中，SrcConstantAlpha 被除以 255，产生 0 到 1 范围的值。

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


指示源位图为每像素 32 位，并为每个像素指定 alpha 透明度值。

