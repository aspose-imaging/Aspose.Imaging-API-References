---
title: "EmfPlusFont"
second_title: "Aspose.Imaging for Java API 参考"
description: "EmfPlusFont 对象指定决定文本外观的属性，包括字体大小和样式。"
type: docs
weight: 42
url: /zh/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

EmfPlusFont 对象指定决定文本外观的属性，包括字体、大小和样式。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | 获取或设置一个长度为 Length 的 Unicode 字符串，其中包含字体系列的名称。 |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | 获取或设置一个长度为 Length 的 Unicode 字符串，其中包含字体系列的名称。 |
| [getFontStyleFlags()](#getFontStyleFlags--) | 获取或设置一个 32 位有符号整数，指定影响字体外观的字符字形属性，例如粗体和斜体。 |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | 获取或设置一个 32 位有符号整数，指定影响字体外观的字符字形属性，例如粗体和斜体。 |
| [getSizeUnit()](#getSizeUnit--) | 获取或设置一个 32 位无符号整数，指定用于 EmSize 字段的单位。 |
| [setSizeUnit(int value)](#setSizeUnit-int-) | 获取或设置一个 32 位无符号整数，指定用于 EmSize 字段的单位。 |
| [getEmSize()](#getEmSize--) | 获取或设置一个 32 位浮点值，指定字体的 em 大小，单位由 SizeUnit 字段指定。 |
| [setEmSize(float value)](#setEmSize-float-) | 获取或设置一个 32 位浮点值，指定字体的 em 大小，单位由 SizeUnit 字段指定。 |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


获取或设置一个长度为 Length 的 Unicode 字符串，其中包含字体系列的名称。

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


获取或设置一个长度为 Length 的 Unicode 字符串，其中包含字体系列的名称。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


获取或设置一个 32 位有符号整数，指定影响字体外观的字符字形属性，例如粗体和斜体。该值必须由 FontStyle 标志组成（第 2.1.2.4 节）。

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


获取或设置一个 32 位有符号整数，指定影响字体外观的字符字形属性，例如粗体和斜体。该值必须由 FontStyle 标志组成（第 2.1.2.4 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


获取或设置一个 32 位无符号整数，指定用于 EmSize 字段的单位。这些通常是设计字体时使用的单位。该值必须属于 UnitType 枚举（第 2.1.1.33 节）。

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


获取或设置一个 32 位无符号整数，指定用于 EmSize 字段的单位。这些通常是设计字体时使用的单位。该值必须属于 UnitType 枚举（第 2.1.1.33 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


获取或设置一个 32 位浮点值，指定字体的 em 大小，单位由 SizeUnit 字段指定。

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


获取或设置一个 32 位浮点值，指定字体的 em 大小，单位由 SizeUnit 字段指定。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | float |  |

