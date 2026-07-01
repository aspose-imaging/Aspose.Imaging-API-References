---
title: "EmfRegionMode"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "تحدد تعداد RegionMode القيم التي تُستخدم مع EMR_SELECTCLIPPATH و EMR_EXTSELECTCLIPRGN لتحديد المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية."
type: docs
weight: 39
url: /ar/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

تحدد تعداد RegionMode القيم التي تُستخدم مع EMR\_SELECTCLIPPATH و EMR\_EXTSELECTCLIPRGN، لتحديد المسار الحالي أو منطقة جديدة يتم دمجها مع منطقة القص الحالية.
## الحقول

| حقل | الوصف |
| --- | --- |
| [RGN_AND](#RGN-AND) | تشمل المنطقة المقصّة الجديدة تقاطع (المناطق المتداخلة) المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة). |
| [RGN_OR](#RGN-OR) | تشمل المنطقة المقصّة الجديدة اتحاد (المناطق المدمجة) المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة). |
| [RGN_XOR](#RGN-XOR) | تشمل المنطقة المقصّة الجديدة اتحاد المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة) ولكن دون المناطق المتداخلة |
| [RGN_DIFF](#RGN-DIFF) | تشمل المنطقة المقصّة الجديدة مناطق المنطقة المقصّة الحالية مع استبعاد تلك الخاصة بالمسار الحالي (أو المنطقة الجديدة). |
| [RGN_COPY](#RGN-COPY) | المنطقة المقصّة الجديدة هي المسار الحالي (أو المنطقة الجديدة). |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


تشمل المنطقة المقصّة الجديدة تقاطع (المناطق المتداخلة) المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة).

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


تشمل المنطقة المقصّة الجديدة اتحاد (المناطق المدمجة) المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة).

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


تشمل المنطقة المقصّة الجديدة اتحاد المنطقة المقصّة الحالية والمسار الحالي (أو المنطقة الجديدة) ولكن دون المناطق المتداخلة

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


تشمل المنطقة المقصّة الجديدة مناطق المنطقة المقصّة الحالية مع استبعاد تلك الخاصة بالمسار الحالي (أو المنطقة الجديدة).

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


المنطقة المقصّة الجديدة هي المسار الحالي (أو المنطقة الجديدة).

