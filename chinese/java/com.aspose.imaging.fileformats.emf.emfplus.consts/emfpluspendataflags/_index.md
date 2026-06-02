---
title: "EmfPlusPenDataFlags"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "PenData 标志指定图形笔的属性，包括可选数据字段的存在。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusPenDataFlags extends System.Enum
```

PenData 标志指定图形笔的属性，包括可选数据字段的存在。这些标志可以组合以指定多个选项。

--------------------

图形笔由 [EmfPlusPen](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspen) 对象指定。
## 字段

| 字段 | 描述 |
| --- | --- |
| [PenDataTransform](#PenDataTransform) | 如果设置，则必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 2x3 变换矩阵。 |
| [PenDataStartCap](#PenDataStartCap) | 如果设置，则必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定起始线帽的样式。 |
| [PenDataEndCap](#PenDataEndCap) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定结束线帽的样式。 |
| [PenDataJoin](#PenDataJoin) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定线段连接类型。 |
| [PenDataMiterLimit](#PenDataMiterLimit) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定斜接限制。 |
| [PenDataLineStyle](#PenDataLineStyle) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定线条样式。 |
| [PenDataDashedLineCap](#PenDataDashedLineCap) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定虚线线帽。 |
| [PenDataDashedLineOffset](#PenDataDashedLineOffset) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定虚线偏移。 |
| [PenDataDashedLine](#PenDataDashedLine) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) 对象。 |
| [PenDataNonCenter](#PenDataNonCenter) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定笔的对齐方式。 |
| [PenDataCompoundLine](#PenDataCompoundLine) | 指示在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中是否存在 [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) 对象的长度和内容。 |
| [PenDataCustomStartCap](#PenDataCustomStartCap) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) 对象。 |
| [PenDataCustomEndCap](#PenDataCustomEndCap) | 指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) 对象。 |
### PenDataTransform {#PenDataTransform}
```
public static final int PenDataTransform
```


如果设置，则必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 2x3 变换矩阵。

### PenDataStartCap {#PenDataStartCap}
```
public static final int PenDataStartCap
```


如果设置，则必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定起始线帽的样式。

### PenDataEndCap {#PenDataEndCap}
```
public static final int PenDataEndCap
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定结束线帽的样式。

### PenDataJoin {#PenDataJoin}
```
public static final int PenDataJoin
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定线段连接类型。

### PenDataMiterLimit {#PenDataMiterLimit}
```
public static final int PenDataMiterLimit
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定斜接限制。

### PenDataLineStyle {#PenDataLineStyle}
```
public static final int PenDataLineStyle
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定线条样式。

### PenDataDashedLineCap {#PenDataDashedLineCap}
```
public static final int PenDataDashedLineCap
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定虚线线帽。

### PenDataDashedLineOffset {#PenDataDashedLineOffset}
```
public static final int PenDataDashedLineOffset
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定虚线偏移。

### PenDataDashedLine {#PenDataDashedLine}
```
public static final int PenDataDashedLine
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusDashedLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata) 对象。

### PenDataNonCenter {#PenDataNonCenter}
```
public static final int PenDataNonCenter
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定笔的对齐方式。

### PenDataCompoundLine {#PenDataCompoundLine}
```
public static final int PenDataCompoundLine
```


指示在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中是否存在 [EmfPlusCompoundLineData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata) 对象的长度和内容。

### PenDataCustomStartCap {#PenDataCustomStartCap}
```
public static final int PenDataCustomStartCap
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusCustomStartCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata) 对象。

### PenDataCustomEndCap {#PenDataCustomEndCap}
```
public static final int PenDataCustomEndCap
```


指示是否必须在 [EmfPlusPenData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata) 对象的 OptionalData 字段中指定一个 [EmfPlusCustomEndCapData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata) 对象。

