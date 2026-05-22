---
title: "枚举 EmfMapMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Emf.Emf.Consts.EmfMapMode 枚举。MapMode 枚举用于定义将页面空间单位转换为设备空间单位的计量单位，并用于定义绘图轴的方向。"
type: docs
weight: 2830
url: /zh/net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---
## EmfMapMode enumeration

该 MapMode 枚举用于定义将页面空间单位转换为设备空间单位的度量单位，并定义绘图轴的方向。

```csharp
public enum EmfMapMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| MM_TEXT | `1` | 每个逻辑单位映射到一个设备像素。正 x 向右；正 y 向下。 |
| MM_LOMETRIC | `2` | 每个逻辑单位映射到 0.1 毫米。正 x 向右；正 y 向上。 |
| MM_HIMETRIC | `3` | 每个逻辑单位映射到 0.01 毫米。正 x 向右；正 y 向上。 |
| MM_LOENGLISH | `4` | 每个逻辑单位映射到 0.01 英寸。正 x 向右；正 y 向上 |
| MM_HIENGLISH | `5` | 每个逻辑单位映射到 0.001 英寸。正 x 向右；正 y 向上。 |
| MM_TWIPS | `6` | 每个逻辑单位映射到打印机点的二十分之一（1/1440 英寸，也称为 "twip"）。正 x 向右；正 y 向上。 |
| MM_ISOTROPIC | `7` | 逻辑单位映射到任意单位，且坐标轴等比例缩放；即 x 轴上的一个单位等于 y 轴上的一个单位。EMR_SETWINDOWEXTEX 和 EMR_SETVIEWPORTEXTEX 记录 SHOULD 被用于指定单位和坐标轴的方向。Adjustments MUST 在必要时进行，以确保 x 和 y 单位保持相同大小。例如，当设置窗口范围时，viewport MUST 被调整以保持单位各向同性。 |
| MM_ANISOTROPIC | `8` | 逻辑单位映射到任意单位，且坐标轴任意缩放。EMR_SETWINDOWEXTEX 和 EMR_SETVIEWPORTEXTEX 记录 SHOULD 被用于指定单位、方向和缩放。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts/)
* assembly [Aspose.Imaging](../../)


