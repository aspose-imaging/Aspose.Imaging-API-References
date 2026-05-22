---
title: "EmfStretchMode 枚举"
type: docs
weight: 340
url: /zh/python-net/aspose.imaging.fileformats.emf.emf.consts/emfstretchmode/
---

StretchMode 枚举用于指定在拉伸或压缩位图时，如何添加或移除颜色数据。

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfStretchMode

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| STRETCH_ANDSCANS | 对已消除和现有像素的颜色值执行布尔 AND 操作。<br/>            如果位图是单色位图，此模式会以牺牲白色像素为代价保留黑色像素 |
| STRETCH_DELETESCANS | 删除像素。此模式删除所有已消除的像素行，而不尝试保留其信息。 |
| STRETCH_HALFTONE | 将像素从源矩形映射到目标矩形中的像素块。 <br/>            目标像素块的平均颜色近似于源像素的颜色。 |
| STRETCH_ORSCANS | 对已消除和现有像素的颜色值执行布尔 OR 操作。 <br/>            如果位图是单色位图，此模式会以牺牲黑色像素为代价保留白色像素。 |
