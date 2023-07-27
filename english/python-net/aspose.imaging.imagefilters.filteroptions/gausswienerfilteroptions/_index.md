---
title: GaussWienerFilterOptions Class
type: docs
weight: 60
url: /python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/
---

**Summary:** Gauss Wiener Filter Options<br/>            Deblur gauss

**Module:** [aspose.imaging.imagefilters.filteroptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/)

**Full Name:** aspose.imaging.imagefilters.filteroptions.GaussWienerFilterOptions

**Inheritance:** DeconvolutionFilterOptions

**Aspose.Imaging Version:** 23.6

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GaussWienerFilterOptions()](#GaussWienerFilterOptions__1) | Initializes a new instance of the [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) class.<br/>            With default settings. |
| [GaussWienerFilterOptions(radius, smooth)](#GaussWienerFilterOptions_radius_smooth_2) | Initializes a new instance of the [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) class. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- |
| brightness | double | r/w | Gets or sets the brightness.<br/>            recommended range 1 - 1.5<br/>            default value = 1.15 |
| grayscale | bool | r/w | Gets or sets a value indicating whether this [DeconvolutionFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/deconvolutionfilteroptions/) is grayscale.<br/>            Return grayscale mode or RGB mode. |
| is_partial_loaded | bool | r | Gets a value indicating whether this instance is partial loaded. |
| radius | int | r/w | Gets or sets the radius. |
| smooth | double | r/w | Gets or sets the smooth. |
| snr | double | r/w | Gets or sets the SNR(signal-to-noise ratio)<br/>            recommended range 0.002 - 0.009, default value = 0.007 |


### Constructor: GaussWienerFilterOptions() {#GaussWienerFilterOptions__1}


```
 GaussWienerFilterOptions() 
```

Initializes a new instance of the [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) class.<br/>            With default settings.

### Constructor: GaussWienerFilterOptions(radius, smooth) {#GaussWienerFilterOptions_radius_smooth_2}


```
 GaussWienerFilterOptions(radius, smooth) 
```

Initializes a new instance of the [GaussWienerFilterOptions](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/gausswienerfilteroptions/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| radius | int | The radius. |
| smooth | double | The smooth. |

