---
title: "TiffAlphaStorage"
second_title: "Aspose.Imaging for Java API 参考"
description: "指定 tiff 文档的 alpha 存储。"
type: docs
weight: 11
url: /zh/java/com.aspose.imaging.fileformats.tiff.enums/tiffalphastorage/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class TiffAlphaStorage extends System.Enum
```

指定 tiff 文档的 alpha 存储。
## 字段

| 字段 | 描述 |
| --- | --- |
| [Unspecified](#Unspecified) | 未指定 alpha，且已存储在 tiff 文件中。 |
| [Associated](#Associated) | alpha 值以预乘形式存储。 |
| [Unassociated](#Unassociated) | alpha 值以非关联形式存储。 |
### Unspecified {#Unspecified}
```
public static final int Unspecified
```


未指定 alpha，且已存储在 tiff 文件中。

### Associated {#Associated}
```
public static final int Associated
```


alpha 值以预乘形式存储。恢复 alpha 时可能出现一些四舍五入效应，恢复后的值可能与原始值不同。

### Unassociated {#Unassociated}
```
public static final int Unassociated
```


alpha 值以非关联形式存储。这意味着恢复的 alpha 与存储到 tiff 中的完全相同。

