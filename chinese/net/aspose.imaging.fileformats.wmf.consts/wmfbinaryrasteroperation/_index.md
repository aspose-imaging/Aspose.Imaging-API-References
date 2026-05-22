---
title: "枚举 WmfBinaryRasterOperation"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Wmf.Consts.WmfBinaryRasterOperation 枚举。BinaryRasterOperation 枚举部分列出了二进制光栅操作码。光栅操作码定义了元文件处理如何将选定笔的位与目标位图中的位组合。"
type: docs
weight: 8280
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
## WmfBinaryRasterOperation enumeration

此 BinaryRasterOperation 枚举部分列出了二进制光栅操作代码。光栅操作代码定义元文件处理如何将选定笔的位与目标位图中的位合并。

```csharp
public enum WmfBinaryRasterOperation
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Black | `1` | 0，像素始终为 0。 |
| Notmergepen | `2` | DPon，像素是 MERGEPEN 颜色的反相。 |
| Masknotpen | `3` | DPna，像素是屏幕颜色与笔颜色的反相的组合。 |
| Notcopypen | `4` | Pn，像素是笔颜色的反相。 |
| Maskpennot | `5` | PDna，像素是笔颜色与屏幕反相的共同颜色的组合。 |
| Not | `6` | Dn，像素是屏幕颜色的反相。 |
| Xorpen | `7` | DPx，像素是笔或屏幕中的颜色的组合，但不包括两者都有的颜色。 |
| Notmaskpen | `8` | DPan，像素是 MASKPEN 颜色的反相。 |
| Maskpen | `9` | DPa，像素是笔和屏幕共同的颜色的组合。 |
| Notxorpen | `10` | DPxn，像素是 XORPEN 颜色的反相。 |
| Nop | `11` | D，像素保持不变。 |
| Mergenotpen | `12` | DPno，像素是屏幕颜色与笔颜色的反相共同的颜色的组合。 |
| Copypen | `13` | P，像素是笔的颜色。 |
| Mergepennot | `14` | PDno，像素是笔颜色与屏幕颜色的反相的组合。 |
| Mergepen | `15` | DPo，像素是笔颜色与屏幕颜色的组合。 |
| White | `16` | 1，像素始终为 1。 |

## 备注

每个光栅操作码表示一种布尔运算，其中选定笔的像素值与目标位图的像素值被组合。以下是这些运算中使用的两个操作数。 操作数 含义 P 选定的笔 D 目标位图 a 位与 (AND) n 位非（取反） o 位或 (OR) x 位异或 (XOR)

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts/)
* assembly [Aspose.Imaging](../../)


