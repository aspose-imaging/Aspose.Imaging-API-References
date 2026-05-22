---
title: "EmfMapMode 枚举"
type: docs
weight: 210
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfmapmode/
---

MapMode 枚举用于定义将页面 <br/>            空间单位转换为设备空间单位的计量单位，以及定义绘图坐标轴的方向。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfMapMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| MM_ANISOTROPIC | 逻辑单位映射到任意单位，轴的比例任意缩放。 <br/>            应使用 EMR_SETWINDOWEXTEX 和 EMR_SETVIEWPORTEXTEX 记录来指定单位、<br/>            方向和缩放。 |
| MM_HIENGLISH | 每个逻辑单位映射为 0.001 英寸。正向 x 向右；正向 y 向上。 |
| MM_HIMETRIC | 每个逻辑单位映射为 0.01 毫米。正向 x 向右；正向 y 向上。 |
| MM_ISOTROPIC | 逻辑单位映射到任意单位，且轴等比例缩放；即，x 轴上的一个单位 <br/>            等于 y 轴上的一个单位。应使用 EMR_SETWINDOWEXTEX 和 <br/>            EMR_SETVIEWPORTEXTEX 记录来指定单位和轴的方向 <br/>            。<br/>            必须根据需要进行调整，以确保 x 和 y 单位保持相同大小。 <br/>            例如，当设置窗口范围时，必须调整视口以保持单位各向同性。 |
| MM_LOENGLISH | 每个逻辑单位映射为 0.01 英寸。正向 x 向右；正向 y 向上 |
| MM_LOMETRIC | 每个逻辑单位映射为 0.1 毫米。正向 x 向右；正向 y 向上。 |
| MM_TEXT | 每个逻辑单位映射为一个设备像素。正向 x 向右；正向 y 向下。 |
| MM_TWIPS | 每个逻辑单位映射为打印机点的二十分之一 <br/>            (1/1440 英寸，也称为 "twip"). 正向 x 向右；正向 y 向上。 |
