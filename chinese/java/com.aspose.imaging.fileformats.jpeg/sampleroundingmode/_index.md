---
title: "SampleRoundingMode"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义将 n 位值转换为 8 位值的方法。"
type: docs
weight: 17
url: /zh/java/com.aspose.imaging.fileformats.jpeg/sampleroundingmode/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class SampleRoundingMode extends System.Enum
```

定义将 n 位值转换为 8 位值的方法。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Extrapolate](#Extrapolate) | 将 8 位值外推以适配 n 位，其中 1 < n < 8。 |
| [Truncate](#Truncate) | 将 8 位值截断以适配 n 位，其中 1 < n < 8。 |
### Extrapolate {#Extrapolate}
```
public static final int Extrapolate
```


将 8 位值外推以适配 n 位，其中 1 < n < 8。所有可能的 8 位值数量为 1 << 8 = 256，范围从 0 到 255。所有可能的 n 位值数量为 1 << n，范围从 0 到 (1 << n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 >> (8 - n)。

### Truncate {#Truncate}
```
public static final int Truncate
```


将 8 位值截断以适配 n 位，其中 1 < n < 8。所有可能的 n 位值数量为 1 << n，范围从 0 到 (1 << n) - 1。对应某个 8 位值 V8 的最合理的 n 位值 Vn 等于 Vn = V8 & ((1 << n) - 1)。

