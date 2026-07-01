---
title: "FontExtensions"
second_title: "مرجع API لـ Aspose.Imaging للـ Java"
description: "يحتوي على طرق توسيع لفئة Imaging.Font."
type: docs
weight: 16
url: /ar/java/com.aspose.imaging.extensions/fontextensions/
---
**Inheritance:**
java.lang.Object
```
public final class FontExtensions
```

يحتوي على طرق امتداد لفئة `Imaging.Font`.
## الطرق

| طريقة | الوصف |
| --- | --- |
| [toGdiFont(Font font)](#toGdiFont-com.aspose.imaging.Font-) | يقوم بتحويل `Imaging.Font` إلى `System.Drawing.Font`. |
| [toGdiFont(Font font, int fontUnit)](#toGdiFont-com.aspose.imaging.Font-int-) | يقوم بتحويل `Font` إلى `System.Drawing.Font`. |
### toGdiFont(Font font) {#toGdiFont-com.aspose.imaging.Font-}
```
public static Font toGdiFont(Font font)
```


يقوم بتحويل `Imaging.Font` إلى `System.Drawing.Font`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | `Imaging.Font` المراد تحويله. |

**Returns:**
[Font](../../java.awt/font) - The converted `System.Drawing.Font`.
### toGdiFont(Font font, int fontUnit) {#toGdiFont-com.aspose.imaging.Font-int-}
```
public static Font toGdiFont(Font font, int fontUnit)
```


يقوم بتحويل `Font` إلى `System.Drawing.Font`.

**Parameters:**
| معامل | نوع | الوصف |
| --- | --- | --- |
| font | [Font](../../com.aspose.imaging/font) | `Font` المراد تحويله. |
| fontUnit | int | وحدة رسومية جديدة |

**Returns:**
[Font](../../java.awt/font) - The converted `System.Drawing.Font`.
