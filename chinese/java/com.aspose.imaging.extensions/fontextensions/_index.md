---
title: "FontExtensions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "包含 Imaging.Font 类的扩展方法。"
type: docs
weight: 16
url: /zh/java/com.aspose.imaging.extensions/fontextensions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtensions
```

包含针对 `Imaging.Font` 类的扩展方法。
## 方法

| 方法 | 描述 |
| --- | --- |
| [toGdiFont(Font font)](#toGdiFont-com.aspose.imaging.Font-) | 将 `Imaging.Font` 转换为 `System.Drawing.Font`。 |
| [toGdiFont(Font font, int fontUnit)](#toGdiFont-com.aspose.imaging.Font-int-) | 将 `Font` 转换为 `System.Drawing.Font`。 |
### toGdiFont(Font font) {#toGdiFont-com.aspose.imaging.Font-}
```
public static Font toGdiFont(Font font)
```


将 `Imaging.Font` 转换为 `System.Drawing.Font`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | 要转换的 `Imaging.Font`。 |

**Returns:**
[Font](../../java.awt/font) - The converted `System.Drawing.Font`.
### toGdiFont(Font font, int fontUnit) {#toGdiFont-com.aspose.imaging.Font-int-}
```
public static Font toGdiFont(Font font, int fontUnit)
```


将 `Font` 转换为 `System.Drawing.Font`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | 要转换的 `Font`。 |
| fontUnit | int | 新的图形单位 |

**Returns:**
[Font](../../java.awt/font) - The converted `System.Drawing.Font`.
