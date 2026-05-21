---
title: "字体"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "定义文本的特定格式，包括字体、大小和样式属性。"
type: docs
weight: 48
url: /zh/java/com.aspose.imaging/font/
---
**Inheritance:**
java.lang.Object
```
public final class Font
```

定义文本的特定格式，包括字体、大小和样式属性。此类不可被继承。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [Font(Font prototype, int newStyle)](#Font-com.aspose.imaging.Font-int-) | 初始化一个新的 `com.aspose.imaging.Font`，该对象使用指定的现有 `com.aspose.imaging.Font` 和 `com.aspose.imaging.FontStyle` 枚举。 |
| [Font(String fontName, float emSize)](#Font-java.lang.String-float-) | 使用指定的大小初始化一个新的 `com.aspose.imaging.Font`。 |
| [Font(String fontName, float emSize, int style)](#Font-java.lang.String-float-int-) | 使用指定的大小和样式初始化一个新的 `com.aspose.imaging.Font`。 |
| [Font(String fontName, float emSize, int style, int unit, int characterSet)](#Font-java.lang.String-float-int-int-int-) | 使用指定的大小、样式、单位和字符集初始化一个新的 `com.aspose.imaging.Font`。 |
| [Font(String fontName, float emSize, int style, int unit)](#Font-java.lang.String-float-int-int-) | 使用指定的大小、样式和单位初始化一个新的 `com.aspose.imaging.Font`。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [makeFontWithGraphUnit(String fontName, float emSize, int unit)](#makeFontWithGraphUnit-java.lang.String-float-int-) | 使用指定的大小和单位初始化一个新的 `com.aspose.imaging.Font`。 |
| [getBold()](#getBold--) | 获取一个值，指示此 `Font` 是否为粗体。 |
| [getCharacterSet()](#getCharacterSet--) | 获取一个字节值，指定此 `Font` 使用的字符集。 |
| [getItalic()](#getItalic--) | 获取一个值，指示此 `Font` 是否为斜体。 |
| [getName()](#getName--) | 获取此 `Font` 的字体名称。 |
| [getStrikeout()](#getStrikeout--) | 获取一个值，指示此 `Font` 是否在字体上指定水平划线。 |
| [getUnderline()](#getUnderline--) | 获取一个值，指示此 `Font` 是否带下划线。 |
| [getStyle()](#getStyle--) | 获取此 `Font` 的样式信息。 |
| [getSize()](#getSize--) | 获取此 `Font` 的 em 大小，单位由 `P:Aspose.Imaging.Font.Unit` 属性指定。 |
| [getUnit()](#getUnit--) | 获取此 `Font` 的度量单位。 |
| [deepClone()](#deepClone--) | 创建此 `Font` 的精确深拷贝。 |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示指定的对象是否为 `com.aspose.imaging.Font`，且其属性值与此 `com.aspose.imaging.Font` 相同。 |
| [hashCode()](#hashCode--) | 获取此 `com.aspose.imaging.Font` 的哈希码。 |
| [toString()](#toString--) | 返回此 `com.aspose.imaging.Font` 的可读字符串表示。 |

## Example: This example demonstrates the use of Font and SolidBrush class to draw strings on Image surface.
此示例演示了使用 Font 和 SolidBrush 类在 Image 表面绘制字符串。示例创建了一个新 Image 并使用 Figures 和 GraphicsPath 绘制形状。
``` java
//创建一个 BmpOptions 实例并设置其各种属性。
com.aspose.imaging.imageoptions.BmpOptions bmpOptions = new com.aspose.imaging.imageoptions.BmpOptions();
bmpOptions.setBitsPerPixel(24);

//创建 FileCreateSource 的实例并将其指定为 BmpOptions 实例的 Source。
//第二个布尔参数决定要创建的文件是否为 IsTemporal。
bmpOptions.setSource(new com.aspose.imaging.sources.FileCreateSource("C:\\temp\\sample.bmp", false));

//创建 Image 的实例
com.aspose.imaging.Image image = com.aspose.imaging.Image.create(bmpOptions, 500, 500);
try {
    //创建并初始化 Graphics 类的实例
    com.aspose.imaging.Graphics graphics = new com.aspose.imaging.Graphics(image);

    //清除 Graphics 表面
    graphics.clear(com.aspose.imaging.Color.getWheat());

    //创建 Font 的实例
    com.aspose.imaging.Font font = new com.aspose.imaging.Font("Times New Roman", 16);

    //创建具有红色的 SolidBrush 实例
    com.aspose.imaging.brushes.SolidBrush brush = new com.aspose.imaging.brushes.SolidBrush(com.aspose.imaging.Color.getRed());

    //绘制字符串
    graphics.drawString("Created by Aspose.Imaging for Java", font, brush, new com.aspose.imaging.PointF(100, 100));

    // 保存所有更改
    image.save();
} finally {
    image.dispose();
}
```

### Font(Font prototype, int newStyle) {#Font-com.aspose.imaging.Font-int-}
```
public Font(Font prototype, int newStyle)
```


初始化一个新的 `com.aspose.imaging.Font`，该对象使用指定的现有 `com.aspose.imaging.Font` 和 `com.aspose.imaging.FontStyle` 枚举。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prototype | [Font](../../com.aspose.imaging/font) | 用于创建新 `com.aspose.imaging.Font` 的现有 `com.aspose.imaging.Font`。 |
| newStyle | int | 要应用于新 `com.aspose.imaging.Font` 的 `com.aspose.imaging.FontStyle`。`com.aspose.imaging.FontStyle` 枚举的多个值可以使用 OR 运算符组合。 |

### Font(String fontName, float emSize) {#Font-java.lang.String-float-}
```
public Font(String fontName, float emSize)
```


使用指定的大小初始化新的 `com.aspose.imaging.Font`。字符集设置为 `F:Aspose.Imaging.CharacterSet.Default`，图形单位设置为 `F:Aspose.Imaging.GraphicsUnit.Point`，字体样式设置为 `F:Aspose.Imaging.FontStyle.Regular`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小（以点为单位）。 |

### Font(String fontName, float emSize, int style) {#Font-java.lang.String-float-int-}
```
public Font(String fontName, float emSize, int style)
```


使用指定的大小和样式初始化新的 `com.aspose.imaging.Font`。字符集设置为 `F:Aspose.Imaging.CharacterSet.Default`，图形单位设置为 `F:Aspose.Imaging.GraphicsUnit.Point`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小（以点为单位）。 |
| style | int | 新字体的 `com.aspose.imaging.FontStyle`。 |

### Font(String fontName, float emSize, int style, int unit, int characterSet) {#Font-java.lang.String-float-int-int-int-}
```
public Font(String fontName, float emSize, int style, int unit, int characterSet)
```


使用指定的大小、样式、单位和字符集初始化一个新的 `com.aspose.imaging.Font`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 `com.aspose.imaging.FontStyle`。 |
| unit | int | 新字体的 `com.aspose.imaging.GraphicsUnit`。 |
| characterSet | int | 用于此字体的字符集。 |

### Font(String fontName, float emSize, int style, int unit) {#Font-java.lang.String-float-int-int-}
```
public Font(String fontName, float emSize, int style, int unit)
```


使用指定的大小、样式和单位初始化一个新的 `com.aspose.imaging.Font`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| style | int | 新字体的 `com.aspose.imaging.FontStyle`。 |
| unit | int | 新字体的 `com.aspose.imaging.GraphicsUnit`。 |

### makeFontWithGraphUnit(String fontName, float emSize, int unit) {#makeFontWithGraphUnit-java.lang.String-float-int-}
```
public static Font makeFontWithGraphUnit(String fontName, float emSize, int unit)
```


使用指定的大小和单位初始化一个新的 `com.aspose.imaging.Font`。字符集被设置为 `F:Aspose.Imaging.CharacterSet.Default`，样式被设置为 `F:Aspose.Imaging.FontStyle.Regular`。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | java.lang.String | `com.aspose.imaging.Font` 名称的字符串表示。 |
| emSize | float | 新字体的 em 大小，单位由 `unit` 参数指定。 |
| unit | int | 新字体的 `com.aspose.imaging.GraphicsUnit`。 |

**Returns:**
[Font](../../com.aspose.imaging/font)
### getBold() {#getBold--}
```
public boolean getBold()
```


获取一个值，指示此 `Font` 是否为粗体。

**Returns:**
boolean - 如果此 `Font` 为粗体则为 True；否则为 false。
### getCharacterSet() {#getCharacterSet--}
```
public int getCharacterSet()
```


获取一个字节值，指定此 `Font` 使用的字符集。

**Returns:**
int - 此 `Font` 使用的字符集。
### getItalic() {#getItalic--}
```
public boolean getItalic()
```


获取一个值，指示此 `Font` 是否为斜体。

**Returns:**
boolean - 如果此 `Font` 为斜体则为 True；否则为 false。
### getName() {#getName--}
```
public String getName()
```


获取此 `Font` 的字体名称。

**Returns:**
java.lang.String - 此 `Font` 的字体名称的字符串表示。
### getStrikeout() {#getStrikeout--}
```
public boolean getStrikeout()
```


获取一个值，指示此 `Font` 是否在字体上指定水平划线。

**Returns:**
boolean - 如果此 `Font` 有水平划线则为 True；否则为 false。
### getUnderline() {#getUnderline--}
```
public boolean getUnderline()
```


获取一个值，指示此 `Font` 是否带下划线。

**Returns:**
boolean - 如果此 `Font` 为下划线则为 True；否则为 false。
### getStyle() {#getStyle--}
```
public int getStyle()
```


获取此 `Font` 的样式信息。

**Returns:**
int - 包含此 `Font` 样式信息的 `FontStyle` 枚举。
### getSize() {#getSize--}
```
public float getSize()
```


获取此 `Font` 的 em 大小，单位由 `P:Aspose.Imaging.Font.Unit` 属性指定。

**Returns:**
float - 此 `Font` 的 em 大小。
### getUnit() {#getUnit--}
```
public int getUnit()
```


获取此 `Font` 的度量单位。

**Returns:**
int - 表示此 `Font` 测量单位的 `GraphicsUnit`。
### deepClone() {#deepClone--}
```
public Font deepClone()
```


创建此 `Font` 的精确深拷贝。

**Returns:**
[Font](../../com.aspose.imaging/font) - The `Font` this method creates.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示指定的对象是否为 `com.aspose.imaging.Font`，且其属性值与此 `com.aspose.imaging.Font` 相同。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要测试的对象。 |

**Returns:**
boolean - 如果 `obj` 参数是 `com.aspose.imaging.Font` 且其属性值与此 `com.aspose.imaging.Font` 相同则为 True；否则为 false。
### hashCode() {#hashCode--}
```
public int hashCode()
```


获取此 `com.aspose.imaging.Font` 的哈希码。

**Returns:**
int - 此 `com.aspose.imaging.Font` 的哈希码。
### toString() {#toString--}
```
public String toString()
```


返回此 `com.aspose.imaging.Font` 的可读字符串表示。

**Returns:**
java.lang.String - 表示此 `com.aspose.imaging.Font` 的字符串。
