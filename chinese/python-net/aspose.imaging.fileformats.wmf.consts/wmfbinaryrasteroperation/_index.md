---
title: "WmfBinaryRasterOperation 枚举"
type: docs
weight: 20
url: /zh/python-net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---

BinaryRasterOperation 枚举部分列出了二进制光栅操作码。光栅操作码<br/>                定义元文件处理如何将选定画笔的位与目标位图中的位合并。

**Module:** [aspose.imaging.fileformats.wmf.consts](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/)

**Full Name:** aspose.imaging.fileformats.wmf.consts.WmfBinaryRasterOperation

## **Members**
| **成员名称** | **描述** |
| :- | :- |
| BLACK | 0，像素始终为 0。 |
| COPYPEN | P，像素为画笔颜色。 |
| MASKNOTPEN | DPna，像素是屏幕颜色与画笔颜色的反相组合。 |
| MASKPEN | DPa, 像素是笔和屏幕共同的颜色的组合。 |
| MASKPENNOT | PDna, 像素是笔和<br/>                屏幕的反相共同的颜色的组合。 |
| MERGENOTPEN | DPno, 像素是屏幕和<br/>                笔的反相共同的颜色的组合。 |
| MERGEPEN | DPo, 像素是笔的颜色和屏幕的颜色的组合。 |
| MERGEPENNOT | PDno, 像素是笔的颜色和<br/>                屏幕颜色的反相的组合。 |
| NOP | D, 像素保持不变。 |
| NOT | Dn, 像素是屏幕颜色的反相。 |
| NOTCOPYPEN | Pn, 像素是笔颜色的反相。 |
| NOTMASKPEN | DPan, 像素是MASKPEN颜色的反相。 |
| NOTMERGEPEN | DPon, 像素是MERGEPEN颜色的反相 |
| NOTXORPEN | DPxn, 像素是XORPEN颜色的反相。 |
| WHITE | 1, 像素始终为1 |
| XORPEN | DPx，像素是笔或屏幕中的颜色组合，但不会同时在两者中。 |
