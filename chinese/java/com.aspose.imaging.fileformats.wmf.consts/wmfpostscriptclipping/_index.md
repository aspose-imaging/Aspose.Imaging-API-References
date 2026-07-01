---
title: "WmfPostScriptClipping"
second_title: "Aspose.Imaging for Java API 参考"
description: "PostScriptClipping 枚举定义可应用于用于 PostScript 输出的剪裁路径的函数。"
type: docs
weight: 32
url: /zh/java/com.aspose.imaging.fileformats.wmf.consts/wmfpostscriptclipping/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class WmfPostScriptClipping extends System.Enum
```

PostScriptClipping 枚举定义可应用于用于 PostScript 输出的剪裁路径的函数。
## 字段

| 字段 | 描述 |
| --- | --- |
| [CLIP_SAVE](#CLIP-SAVE) | 保存当前的 PostScript 剪裁路径。 |
| [CLIP_RESTORE](#CLIP-RESTORE) | 将 PostScript 剪裁路径恢复到上一次由 CLIP\_SAVE 函数保存、并通过 CLIP\_TO\_PATH 记录（第 2.3.6.6 节）应用的剪裁路径。 |
| [CLIP_INCLUSIVE](#CLIP-INCLUSIVE) | 将当前的 PostScript 剪裁路径与当前剪裁路径相交，并将结果保存为新的 PostScript 剪裁路径。 |
### CLIP_SAVE {#CLIP-SAVE}
```
public static final int CLIP_SAVE
```


保存当前的 PostScript 剪裁路径。

### CLIP_RESTORE {#CLIP-RESTORE}
```
public static final int CLIP_RESTORE
```


将 PostScript 剪裁路径恢复到上一次由 CLIP\_SAVE 函数保存、并通过 CLIP\_TO\_PATH 记录（第 2.3.6.6 节）应用的剪裁路径。

### CLIP_INCLUSIVE {#CLIP-INCLUSIVE}
```
public static final int CLIP_INCLUSIVE
```


将当前的 PostScript 剪裁路径与当前剪裁路径相交，并将结果保存为新的 PostScript 剪裁路径。

