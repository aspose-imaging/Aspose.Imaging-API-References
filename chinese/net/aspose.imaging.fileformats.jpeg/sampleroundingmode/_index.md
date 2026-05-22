---
title: "枚举 SampleRoundingMode"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Aspose.Imaging.FileFormats.Jpeg.SampleRoundingMode 枚举。定义将 n 位值转换为 8 位值的方式"
type: docs
weight: 6910
url: /zh/net/aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
## SampleRoundingMode enumeration

定义将 n 位值转换为 8 位值的方法。

```csharp
public enum SampleRoundingMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| Extrapolate | `0` | 将 8 位值外推以适配 n 位，其中 1 < n < 8。所有可能的 8 位值数量为 1 << 8 = 256，范围 0 到 255。所有可能的 n 位值数量为 1 << n，范围 0 到 (1 << n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 >> (8 - n)。 |
| Truncate | `1` | 将 8 位值截断以适配 n 位，其中 1 < n < 8。所有可能的 n 位值数量为 1 << n，范围 0 到 (1 << n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 & ((1 << n) - 1)。 |

### 另请参见

* namespace [Aspose.Imaging.FileFormats.Jpeg](../../aspose.imaging.fileformats.jpeg/)
* assembly [Aspose.Imaging](../../)


