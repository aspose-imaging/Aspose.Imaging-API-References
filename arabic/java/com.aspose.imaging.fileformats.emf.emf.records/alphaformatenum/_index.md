---
title: "EmfBlendFunction.AlphaFormatEnum"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "هيكل يحدد كيفية تفسير بكسلات المصدر والهدف بالنسبة للشفافية ألفا."
type: docs
weight: 10
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.records/emfblendfunction.alphaformatenum/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public static final class EmfBlendFunction.AlphaFormatEnum extends System.Enum
```

هيكل يحدد كيفية تفسير بكسلات المصدر والهدف بالنسبة للشفافية ألفا.
## الحقول

| حقل | الوصف |
| --- | --- |
| [NotTransparency](#NotTransparency) | البكسلات في صورة المصدر لا تحدد شفافية ألفا. |
| [AC_SRC_ALPHA](#AC-SRC-ALPHA) | يشير إلى أن صورة المصدر هي 32 بت لكل بكسل وتحدد قيمة شفافية ألفا لكل بكسل. |
### NotTransparency {#NotTransparency}
```
public static final byte NotTransparency
```


البكسلات في صورة المصدر لا تحدد شفافية ألفا. في هذه الحالة، تحدد قيمة SrcConstantAlpha مزيج صورة المصدر والصورة الوجهة. لاحظ أنه في المعادلات التالية يتم قسمة SrcConstantAlpha على 255، مما ينتج قيمة في النطاق من 0 إلى 1.

### AC_SRC_ALPHA {#AC-SRC-ALPHA}
```
public static final byte AC_SRC_ALPHA
```


يشير إلى أن صورة المصدر هي 32 بت لكل بكسل وتحدد قيمة شفافية ألفا لكل بكسل.

