---
title: "EmfRegionMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تعداد RegionMode يحدد القيم المستخدمة مع EMR_SELECTCLIPPATH و EMR_EXTSELECTCLIPRGN لتحديد المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية."
type: docs
weight: 39
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

تحدد تعداد RegionMode القيم التي تُستخدم مع EMR\_SELECTCLIPPATH و EMR\_EXTSELECTCLIPRGN، محددةً المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [RGN_AND](#RGN-AND) | منطقة القص الجديدة تشمل التقاطع (المناطق المتداخلة) بين منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة). |
| [RGN_OR](#RGN-OR) | تشمل منطقة القص الجديدة الاتحاد (المناطق المدمجة) لمنطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة). |
| [RGN_XOR](#RGN-XOR) | تشمل منطقة القص الجديدة اتحاد منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة) ولكن بدون المناطق المتداخلة |
| [RGN_DIFF](#RGN-DIFF) | تشمل منطقة القص الجديدة مناطق منطقة القص الحالية مع استبعاد مناطق المسار الحالي (أو المنطقة الجديدة). |
| [RGN_COPY](#RGN-COPY) | منطقة القص الجديدة هي المسار الحالي (أو المنطقة الجديدة). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


منطقة القص الجديدة تشمل التقاطع (المناطق المتداخلة) بين منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


تشمل منطقة القص الجديدة الاتحاد (المناطق المدمجة) لمنطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


تشمل منطقة القص الجديدة اتحاد منطقة القص الحالية والمسار الحالي (أو المنطقة الجديدة) ولكن بدون المناطق المتداخلة

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


تشمل منطقة القص الجديدة مناطق منطقة القص الحالية مع استبعاد مناطق المسار الحالي (أو المنطقة الجديدة).

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


منطقة القص الجديدة هي المسار الحالي (أو المنطقة الجديدة).

