---
title: "JpegLsPresetCodingParameters 类"
type: docs
weight: 30
url: /zh/python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/
---

**Summary:** Defines the JPEG-LS preset coding parameters as defined in ISO/IEC 14495-1, C.2.4.1.1.<br/>            JPEG-LS defines a default set of parameters, but custom parameters can be used.<br/>            When used these parameters are written into the encoded bit stream as they are needed for the decoding process.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [JpegLsPresetCodingParameters()](#JpegLsPresetCodingParameters__1) | 初始化 JpegLsPresetCodingParameters 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| maximum_sample_value | int | r/w | 获取或设置扫描中任何图像样本的最大可能值。<br/>            该值必须大于或等于扫描中各组件的实际最大值。 |
| reset_value | int | r/w | 获取或设置计数器 A、B 和 N 被减半的值。 |
| threshold1 | int | r/w | 获取或设置局部梯度的第一个量化阈值。 |
| threshold2 | int | r/w | 获取或设置局部梯度的第二量化阈值。 |
| threshold3 | int | r/w | 获取或设置局部梯度的第三量化阈值。 |


### Constructor: JpegLsPresetCodingParameters() {#JpegLsPresetCodingParameters__1}


```
 JpegLsPresetCodingParameters() 
```

初始化 JpegLsPresetCodingParameters 类的新实例

