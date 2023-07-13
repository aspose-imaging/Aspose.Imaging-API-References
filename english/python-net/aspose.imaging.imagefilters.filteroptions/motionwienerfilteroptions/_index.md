---
title: MotionWienerFilterOptions Class
type: docs
weight: 90
url: /python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/
---

Deconvolution filter options<br/>                deblur motion

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.MotionWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.Imaging Version:** 23.6

The MotionWienerFilterOptions type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
| [MotionWienerFilterOptions(length, smooth, angle)](#MotionWienerFilterOptions_length_smooth_angle_0) | Initializes a new instance of the [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) class. |
## **Properties**
|**Name**|**Type**|**Access**|**Description**|
| :- | :- | :- |
| snr | double | r/w | Gets or sets the SNR(signal-to-noise ratio)<br/>            recommended range 0.002 - 0.009, default value = 0.007 |
| brightness | double | r/w | Gets or sets the brightness.<br/>            recommended range 1 - 1.5<br/>            default value = 1.15 |
| grayscale | bool | r/w | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) is grayscale.<br/>            Return grayscale mode or RGB mode. |
| is_partial_loaded | bool | r | Gets a value indicating whether this instance is partial loaded. |
| length | int | r/w | Gets or sets the length. |
| smooth | double | r/w | Gets or sets the smooth. |
| angle | double | r/w | Gets or sets the angle in gradus. |

### MotionWienerFilterOptions(length, smooth, angle) {#MotionWienerFilterOptions_length_smooth_angle_0}


```
 MotionWienerFilterOptions(length, smooth, angle) 
```

Initializes a new instance of the [MotionWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/motionwienerfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| length | int | The length. |
| smooth | double | The smooth. |
| angle | double | The angle in gradus. |

