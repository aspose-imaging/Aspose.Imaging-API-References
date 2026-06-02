---
title: "EmfLogFont"
second_title: "Aspose.Imaging for Java API 参考文档"
description: "LogFont 对象指定了逻辑字体的基本属性。"
type: docs
weight: 22
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public class EmfLogFont extends EmfObject
```

LogFont 对象指定了逻辑字体的基本属性。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfLogFont()](#EmfLogFont--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getHeight()](#getHeight--) | 获取或设置一个 32 位有符号整数，指定字体字符单元或字符的高度（以逻辑单位为单位）。 |
| [setHeight(int value)](#setHeight-int-) | 获取或设置一个 32 位有符号整数，指定字体字符单元或字符的高度（以逻辑单位为单位）。 |
| [getWidth()](#getWidth--) | 获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（以逻辑单位为单位）。 |
| [setWidth(int value)](#setWidth-int-) | 获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（以逻辑单位为单位）。 |
| [getEscapement()](#getEscapement--) | 获取或设置一个 32 位有符号整数，指定转向向量与设备 x 轴之间的角度（以十分之一度为单位）。 |
| [setEscapement(int value)](#setEscapement-int-) | 获取或设置一个 32 位有符号整数，指定转向向量与设备 x 轴之间的角度（以十分之一度为单位）。 |
| [getOrientation()](#getOrientation--) | 获取或设置一个 32 位有符号整数，指定每个字符基线与设备 x 轴之间的角度（以十分之一度为单位）。 |
| [setOrientation(int value)](#setOrientation-int-) | 获取或设置一个 32 位有符号整数，指定每个字符基线与设备 x 轴之间的角度（以十分之一度为单位）。 |
| [getWeight()](#getWeight--) | 获取或设置一个 32 位有符号整数，指定字体的粗细，范围为 0 到 1000。 |
| [setWeight(int value)](#setWeight-int-) | 获取或设置一个 32 位有符号整数，指定字体的粗细，范围为 0 到 1000。 |
| [getItalic()](#getItalic--) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示斜体字体；否则必须设置为 0x00。 |
| [setItalic(byte value)](#setItalic-byte-) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示斜体字体；否则必须设置为 0x00。 |
| [getUnderline()](#getUnderline--) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示下划线字体；否则必须设置为 0x00。 |
| [setUnderline(byte value)](#setUnderline-byte-) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示下划线字体；否则必须设置为 0x00。 |
| [getStrikeout()](#getStrikeout--) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示删除线字体；否则必须设置为 0x00。 |
| [setStrikeout(byte value)](#setStrikeout-byte-) | 获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示删除线字体；否则必须设置为 0x00。 |
| [getCharSet()](#getCharSet--) | 获取或设置一个 8 位无符号整数，指定字符字形集合。 |
| [setCharSet(byte value)](#setCharSet-byte-) | 获取或设置一个 8 位无符号整数，指定字符字形集合。 |
| [getOutPrecision()](#getOutPrecision--) | 获取或设置一个 8 位无符号整数，指定输出精度。 |
| [setOutPrecision(byte value)](#setOutPrecision-byte-) | 获取或设置一个 8 位无符号整数，指定输出精度。 |
| [getClipPrecision()](#getClipPrecision--) | 获取或设置一个 8 位无符号整数，指定裁剪精度。 |
| [setClipPrecision(byte value)](#setClipPrecision-byte-) | 获取或设置一个 8 位无符号整数，指定裁剪精度。 |
| [getQuality()](#getQuality--) | 获取或设置一个 8 位无符号整数，指定输出质量。 |
| [setQuality(byte value)](#setQuality-byte-) | 获取或设置一个 8 位无符号整数，指定输出质量。 |
| [getPitchAndFamily()](#getPitchAndFamily--) | 获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），指定字体的间距和族。 |
| [setPitchAndFamily(WmfPitchAndFamily value)](#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-) | 获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），指定字体的间距和族。 |
| [getFacename()](#getFacename--) | 获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，指定字体的字形名称。 |
| [setFacename(String value)](#setFacename-java.lang.String-) | 获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，指定字体的字形名称。 |
### EmfLogFont() {#EmfLogFont--}
```
public EmfLogFont()
```


### getHeight() {#getHeight--}
```
public int getHeight()
```


获取或设置一个 32 位有符号整数，指定字体字符单元或字符的高度（以逻辑单位为单位）。字符高度值，也称为 em 大小，是字符单元高度值减去内部前导值。字体映射器应按以下方式解释 Height 字段中指定的值。

**Returns:**
int
### setHeight(int value) {#setHeight-int-}
```
public void setHeight(int value)
```


获取或设置一个 32 位有符号整数，指定字体字符单元或字符的高度（以逻辑单位为单位）。字符高度值，也称为 em 大小，是字符单元高度值减去内部前导值。字体映射器应按以下方式解释 Height 字段中指定的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWidth() {#getWidth--}
```
public int getWidth()
```


获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（以逻辑单位为单位）。如果 Width 字段值为零，则应根据其他 LogFont 值计算出适当的值，以找到具有排版师预期宽高比的字体。

**Returns:**
int
### setWidth(int value) {#setWidth-int-}
```
public void setWidth(int value)
```


获取或设置一个 32 位有符号整数，指定字体中字符的平均宽度（以逻辑单位为单位）。如果 Width 字段值为零，则应根据其他 LogFont 值计算出适当的值，以找到具有排版师预期宽高比的字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getEscapement() {#getEscapement--}
```
public int getEscapement()
```


获取或设置一个 32 位有符号整数，指定设备上倾斜向量与 x 轴之间的角度（以十分之一度为单位）。倾斜向量与一行文本的基线平行。

**Returns:**
int
### setEscapement(int value) {#setEscapement-int-}
```
public void setEscapement(int value)
```


获取或设置一个 32 位有符号整数，指定设备上倾斜向量与 x 轴之间的角度（以十分之一度为单位）。倾斜向量与一行文本的基线平行。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getOrientation() {#getOrientation--}
```
public int getOrientation()
```


获取或设置一个 32 位有符号整数，指定每个字符基线与设备 x 轴之间的角度（以十分之一度为单位）。

**Returns:**
int
### setOrientation(int value) {#setOrientation-int-}
```
public void setOrientation(int value)
```


获取或设置一个 32 位有符号整数，指定每个字符基线与设备 x 轴之间的角度（以十分之一度为单位）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getWeight() {#getWeight--}
```
public int getWeight()
```


获取或设置一个 32 位有符号整数，指定字体的粗细，范围为 0 到 1000。例如，400 为常规，700 为粗体。如果该值为 0，则可以使用默认粗细。

**Returns:**
int
### setWeight(int value) {#setWeight-int-}
```
public void setWeight(int value)
```


获取或设置一个 32 位有符号整数，指定字体的粗细，范围为 0 到 1000。例如，400 为常规，700 为粗体。如果该值为 0，则可以使用默认粗细。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | int |  |

### getItalic() {#getItalic--}
```
public byte getItalic()
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示斜体字体；否则必须设置为 0x00。

**Returns:**
byte
### setItalic(byte value) {#setItalic-byte-}
```
public void setItalic(byte value)
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示斜体字体；否则必须设置为 0x00。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getUnderline() {#getUnderline--}
```
public byte getUnderline()
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示下划线字体；否则必须设置为 0x00。

**Returns:**
byte
### setUnderline(byte value) {#setUnderline-byte-}
```
public void setUnderline(byte value)
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示下划线字体；否则必须设置为 0x00。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getStrikeout() {#getStrikeout--}
```
public byte getStrikeout()
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示删除线字体；否则必须设置为 0x00。

**Returns:**
byte
### setStrikeout(byte value) {#setStrikeout-byte-}
```
public void setStrikeout(byte value)
```


获取或设置一个 8 位无符号整数，如果设置为 0x01 则表示删除线字体；否则必须设置为 0x00。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getCharSet() {#getCharSet--}
```
public byte getCharSet()
```


获取或设置一个 8 位无符号整数，指定字符字形集合。它必须是 WMF CharacterSet 枚举中的值（[MS-WMF] 第 2.1.1.5 节）。如果字符集未知，元文件处理不应尝试翻译或解释使用该字体渲染的字符串。

**Returns:**
byte
### setCharSet(byte value) {#setCharSet-byte-}
```
public void setCharSet(byte value)
```


获取或设置一个 8 位无符号整数，指定字符字形集合。它必须是 WMF CharacterSet 枚举中的值（[MS-WMF] 第 2.1.1.5 节）。如果字符集未知，元文件处理不应尝试翻译或解释使用该字体渲染的字符串。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getOutPrecision() {#getOutPrecision--}
```
public byte getOutPrecision()
```


获取或设置一个 8 位无符号整数，指定输出精度。输出精度定义字体必须多接近地匹配请求的高度、宽度、字符方向、倾斜、间距和字体类型。它必须是 WMF OutPrecision 枚举中的值。

**Returns:**
byte
### setOutPrecision(byte value) {#setOutPrecision-byte-}
```
public void setOutPrecision(byte value)
```


获取或设置一个 8 位无符号整数，指定输出精度。输出精度定义字体必须多接近地匹配请求的高度、宽度、字符方向、倾斜、间距和字体类型。它必须是 WMF OutPrecision 枚举中的值。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getClipPrecision() {#getClipPrecision--}
```
public byte getClipPrecision()
```


获取或设置一个 8 位无符号整数，指定裁剪精度。裁剪精度定义如何裁剪部分超出裁剪区域的字符。它可以是 WMF ClipPrecision 标志的一个或多个。

**Returns:**
byte
### setClipPrecision(byte value) {#setClipPrecision-byte-}
```
public void setClipPrecision(byte value)
```


获取或设置一个 8 位无符号整数，指定裁剪精度。裁剪精度定义如何裁剪部分超出裁剪区域的字符。它可以是 WMF ClipPrecision 标志的一个或多个。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getQuality() {#getQuality--}
```
public byte getQuality()
```


获取或设置一个 8 位无符号整数，指定输出质量。输出质量定义尝试将逻辑字体属性与实际物理字体的匹配程度。它必须是 WMF FontQuality 枚举中的一个值（[MS-WMF] 第 2.1.1.10 节）。

**Returns:**
byte
### setQuality(byte value) {#setQuality-byte-}
```
public void setQuality(byte value)
```


获取或设置一个 8 位无符号整数，指定输出质量。输出质量定义尝试将逻辑字体属性与实际物理字体的匹配程度。它必须是 WMF FontQuality 枚举中的一个值（[MS-WMF] 第 2.1.1.10 节）。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | byte |  |

### getPitchAndFamily() {#getPitchAndFamily--}
```
public WmfPitchAndFamily getPitchAndFamily()
```


获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），指定字体的间距和族。字体族以一般方式描述字体的外观。它们用于在指定的字形不可用时指定字体。

**Returns:**
[WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily)
### setPitchAndFamily(WmfPitchAndFamily value) {#setPitchAndFamily-com.aspose.imaging.fileformats.wmf.objects.WmfPitchAndFamily-}
```
public void setPitchAndFamily(WmfPitchAndFamily value)
```


获取或设置一个 WMF PitchAndFamily 对象（[MS-WMF] 第 2.2.2.14 节），指定字体的间距和族。字体族以一般方式描述字体的外观。它们用于在指定的字形不可用时指定字体。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | [WmfPitchAndFamily](../../com.aspose.imaging.fileformats.wmf.objects/wmfpitchandfamily) |  |

### getFacename() {#getFacename--}
```
public String getFacename()
```


获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，指定字体的字形名称。如果此字符串的长度少于 32 个字符，则必须包含一个终止的 NULL，之后该字段的其余部分必须被忽略。

**Returns:**
java.lang.String
### setFacename(String value) {#setFacename-java.lang.String-}
```
public void setFacename(String value)
```


获取或设置一个 Facename（64 字节）：一个不超过 32 个 Unicode 字符的字符串，指定字体的字形名称。如果此字符串的长度少于 32 个字符，则必须包含一个终止的 NULL，之后该字段的其余部分必须被忽略。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String |  |

