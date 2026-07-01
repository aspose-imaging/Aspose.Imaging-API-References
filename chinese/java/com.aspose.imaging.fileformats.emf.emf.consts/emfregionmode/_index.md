---
title: "EmfRegionMode"
second_title: "Aspose.Imaging for Java API 参考"
description: "RegionMode 枚举定义了与 EMR_SELECTCLIPPATH 和 EMR_EXTSELECTCLIPRGN 一起使用的值，用于指定当前路径或正在与当前剪裁区域合并的新区域。"
type: docs
weight: 39
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.consts/emfregionmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRegionMode extends System.Enum
```

RegionMode 枚举定义了与 EMR\_SELECTCLIPPATH 和 EMR\_EXTSELECTCLIPRGN 一起使用的取值，用于指定当前路径或正在与当前剪裁区域合并的新区域。
## 字段

| 字段 | 描述 |
| --- | --- |
| [RGN_AND](#RGN-AND) | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的交集（重叠区域）。 |
| [RGN_OR](#RGN-OR) | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集（组合区域）。 |
| [RGN_XOR](#RGN-XOR) | 新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集，但不包括重叠区域。 |
| [RGN_DIFF](#RGN-DIFF) | 新的剪裁区域包括当前剪裁区域的区域，排除当前路径（或新区域）的部分。 |
| [RGN_COPY](#RGN-COPY) | 新的剪裁区域是当前路径（或新区域）。 |
### RGN_AND {#RGN-AND}
```
public static final int RGN_AND
```


新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的交集（重叠区域）。

### RGN_OR {#RGN-OR}
```
public static final int RGN_OR
```


新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集（组合区域）。

### RGN_XOR {#RGN-XOR}
```
public static final int RGN_XOR
```


新的剪裁区域包括当前剪裁区域与当前路径（或新区域）的并集，但不包括重叠区域。

### RGN_DIFF {#RGN-DIFF}
```
public static final int RGN_DIFF
```


新的剪裁区域包括当前剪裁区域的区域，排除当前路径（或新区域）的部分。

### RGN_COPY {#RGN-COPY}
```
public static final int RGN_COPY
```


新的剪裁区域是当前路径（或新区域）。

