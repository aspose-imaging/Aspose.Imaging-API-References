---
title: "PngLoadOptions"
second_title: "Aspose.Imaging for Java API 参考"
description: "png 加载选项。"
type: docs
weight: 18
url: /zh/java/com.aspose.imaging.imageloadoptions/pngloadoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.LoadOptions](../../com.aspose.imaging/loadoptions)
```
public class PngLoadOptions extends LoadOptions
```

png 加载选项。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [PngLoadOptions()](#PngLoadOptions--) | 初始化 `PngLoadOptions` 类的新实例。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getStrictMode()](#getStrictMode--) | 获取或设置指示是否[strict mode]的值。 |
| [setStrictMode(boolean value)](#setStrictMode-boolean-) | 获取或设置指示是否[strict mode]的值。 |
### PngLoadOptions() {#PngLoadOptions--}
```
public PngLoadOptions()
```


初始化 `PngLoadOptions` 类的新实例。

### getStrictMode() {#getStrictMode--}
```
public boolean getStrictMode()
```


获取或设置指示是否[strict mode]的值。

**Returns:**
布尔 - 指示是否[strict mode]的值。
### setStrictMode(boolean value) {#setStrictMode-boolean-}
```
public void setStrictMode(boolean value)
```


获取或设置指示是否[strict mode]的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | boolean | 指示是否[strict mode]的值。 |


**Example: The following example shows how to read PNG file : a strict mode.**
以下示例展示了如何读取 PNG 文件：严格模式。严格模式允许发现潜在问题：PNG 图像，例如未识别的数据块、意外的文件结束。这类文件仍然可以通过 Aspose.Imaging 以及常见查看器以默认（非严格）模式打开。然而，任何尝试以严格模式打开它们的操作都会导致相应的异常。
``` java
String dir = "c:\\aspose.imaging\\java\\issues\\1442\\";
String inputImage = dir + "FC5F1998104EB92469CB14070628073616BB28F9.png";
String outputImage = inputImage + ".png";

// 默认模式（非严格） - 读取成功。
com.aspose.imaging.Image image = com.aspose.imaging.Image.load(inputImage);
try {
    image.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image.close();
}

// 严格模式 - ImageLoadException : 文件意外结束。
com.aspose.imaging.Image image2 = com.aspose.imaging.Image.load(inputImage, new com.aspose.imaging.imageloadoptions.PngLoadOptions() {{
    setStrictMode(true);
    }});
                
try {
    image2.save(outputImage, new com.aspose.imaging.imageoptions.PngOptions());
}
finally {
    image2.close();
}
```

