---
title: "WmfPostScriptCap"
second_title: "Aspose.Imaging for Java API 参考"
description: "PostScriptCap 枚举定义用于 PostScript 打印机驱动程序的线端类型。"
type: docs
weight: 31
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptcap/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptCap extends System.Enum
```

PostScriptCap 枚举定义用于 PostScript 打印机驱动程序的线端类型。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PostScriptNotSet](#PostScriptNotSet) | 指定线段结束样式尚未设置，且可能使用默认样式 [24]。 |
| [PostScriptFlatCap](#PostScriptFlatCap) | 指定线段在最后一点结束。 |
| [PostScriptRoundCap](#PostScriptRoundCap) | 指定圆形端帽。 |
| [PostScriptSquareCap](#PostScriptSquareCap) | 指定方形端帽。 |
### PostScriptNotSet {#PostScriptNotSet}
```
public static final int PostScriptNotSet
```


指定线段结束样式尚未设置，且可能使用默认样式 [24]。

### PostScriptFlatCap {#PostScriptFlatCap}
```
public static final int PostScriptFlatCap
```


指定线段在最后一点结束。端点被方形化。

### PostScriptRoundCap {#PostScriptRoundCap}
```
public static final int PostScriptRoundCap
```


指定圆形端帽。圆心位于线段的最后一点。圆的直径等于线宽，即线的厚度。

### PostScriptSquareCap {#PostScriptSquareCap}
```
public static final int PostScriptSquareCap
```


指定方形端帽。方形的中心位于线段的最后一点。方形的高和宽均等于线宽，即线的厚度。

