---
title: WmfBinaryRasterOperation
second_title: Aspose.Imaging for .NET API 参考
description: BinaryRasterOperation 枚举部分列出了二进制光栅操作代码光栅操作代码 定义图元文件处理如何将来自选定笔的位与目标位图中的 位结合起来
type: docs
weight: 8100
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfbinaryrasteroperation/
---
## WmfBinaryRasterOperation enumeration

BinaryRasterOperation 枚举部分列出了二进制光栅操作代码。光栅操作代码 定义图元文件处理如何将来自选定笔的位与目标位图中的 位结合起来。

```csharp
public enum WmfBinaryRasterOperation
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| Black | `1` | 0，像素始终为 0. |
| Notmergepen | `2` | DPon，像素是 MERGEPEN 颜色的倒数 |
| Masknotpen | `3` | DPna, Pixel 是屏幕颜色和笔颜色反相的组合。 |
| Notcopypen | `4` | Pn，像素是笔颜色的倒数。 |
| Maskpennot | `5` | PDna，像素是笔和屏幕的 反转的共同颜色的组合。 |
| Not | `6` | Dn，像素是屏幕颜色的倒数。 |
| Xorpen | `7` | DPx，像素是笔或屏幕中颜色的组合，但不是两者。 |
| Notmaskpen | `8` | Dpan，像素是 MASKPEN 颜色的倒数。 |
| Maskpen | `9` | DPa，像素是笔和屏幕共有的颜色的组合。 |
| Notxorpen | `10` | DPxn，像素是 XORPEN 颜色的倒数。 |
| Nop | `11` | D，像素保持不变。 |
| Mergenotpen | `12` | DPno，像素是屏幕共同的颜色和 笔的反色的组合。 |
| Copypen | `13` | P，像素是笔的颜色。 |
| Mergepennot | `14` | PDno，像素是笔颜色和 屏幕颜色的倒数的组合。 |
| Mergepen | `15` | DPo，Pixel是笔颜色和屏幕颜色的组合。 |
| White | `16` | 1，像素始终为 1 |

### 评论

每个光栅操作代码代表一个布尔运算，其中 所选笔和目标位图中的像素值组合在一起。以下是 这些操作中使用的两个操作数。 操作数含义 P选定的笔 D目标位图 a位与 n位非（逆） o位或 x位异或（异或）

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
