---
title: JpegLsPresetCodingParameters Class
type: docs
weight: 30
url: /python-net/aspose.imaging.fileformats.jpeg/jpeglspresetcodingparameters/
---

**Summary:** Defines the JPEG-LS preset coding parameters as defined in ISO/IEC 14495-1, C.2.4.1.1.<br/>            JPEG-LS defines a default set of parameters, but custom parameters can be used.<br/>            When used these parameters are written into the encoded bit stream as they are needed for the decoding process.

**Module:** [aspose.imaging.fileformats.jpeg](/imaging/python-net/aspose.imaging.fileformats.jpeg/)

**Full Name:** aspose.imaging.fileformats.jpeg.JpegLsPresetCodingParameters

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [JpegLsPresetCodingParameters()](#JpegLsPresetCodingParameters__1) | Initializes a new instance of the JpegLsPresetCodingParameters class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| maximum_sample_value | int | r/w | Gets or sets the maximum possible value for any image sample in a scan.<br/>            This must be greater than or equal to the actual maximum value for the components in a scan. |
| reset_value | int | r/w | Gets or sets the value at which the counters A, B, and N are halved. |
| threshold1 | int | r/w | Gets or sets the first quantization threshold value for the local gradients. |
| threshold2 | int | r/w | Gets or sets the second quantization threshold value for the local gradients. |
| threshold3 | int | r/w | Gets or sets the third quantization threshold value for the local gradients. |


### Constructor: JpegLsPresetCodingParameters() {#JpegLsPresetCodingParameters__1}


```
 JpegLsPresetCodingParameters() 
```

Initializes a new instance of the JpegLsPresetCodingParameters class

