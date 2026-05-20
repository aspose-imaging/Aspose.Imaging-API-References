---
title: "TgaOptions"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "TGA 文件格式创建选项。"
type: docs
weight: 47
url: /zh/java/com.aspose.imaging.imageoptions/tgaoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.ImageOptionsBase](../../com.aspose.imaging/imageoptionsbase)
```
public class TgaOptions extends ImageOptionsBase
```

TGA 文件格式创建选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [TgaOptions()](#TgaOptions--) | 初始化一个新的 [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) 类的实例。 |
| [TgaOptions(TgaOptions tgaOptions)](#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-) | 初始化一个新的 [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) 类的实例。 |

## Example: Saving of the JPG image as a TGA image.

``` java
try (Image image = Image.load("test.jpg"))
{
    image.save("test.tga", new TgaOptions());
}
```

### TgaOptions() {#TgaOptions--}
```
public TgaOptions()
```


初始化一个新的 [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) 类的实例。

### TgaOptions(TgaOptions tgaOptions) {#TgaOptions-com.aspose.imaging.imageoptions.TgaOptions-}
```
public TgaOptions(TgaOptions tgaOptions)
```


初始化一个新的 [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) 类的实例。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tgaOptions | [TgaOptions](../../com.aspose.imaging.imageoptions/tgaoptions) | TGA 选项。 |

