---
title: "JpegLsInterleaveMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义多分量颜色像素数据的交错模式。"
type: docs
weight: 15
url: /zh/java/com.aspose.imaging.fileformats.jpeg/jpeglsinterleavemode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class JpegLsInterleaveMode extends System.Enum
```

定义多组件（颜色）像素数据的交错模式。
## 字段

| 字段 | 描述 |
| --- | --- |
| [None](#None) | 数据以分量为单位进行编码和存储：RRRGGGBBB。 |
| [Line](#Line) | 交错模式为按行。 |
| [Sample](#Sample) | 数据以样本方式进行编码和存储。 |
### None {#None}
```
public static final int None
```


数据以分量为单位进行编码和存储：RRRGGGBBB。

### Line {#Line}
```
public static final int Line
```


交错模式为按行。每个分量的一整行在移动到下一行之前被编码。

### Sample {#Sample}
```
public static final int Sample
```


数据以样本方式进行编码和存储。对于彩色图像，这种格式类似于 RGBRGBRGB。

