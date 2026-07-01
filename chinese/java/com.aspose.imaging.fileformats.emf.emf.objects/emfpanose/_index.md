---
title: "EmfPanose"
second_title: "Aspose.Imaging for Java API 参考"
description: "Panose 对象描述了 TrueType 字体的 PANOSE 字体分类值。"
type: docs
weight: 30
url: /zh/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

Panose 对象描述了 TrueType 字体的 PANOSE 字体分类值。这些特征用于将该字体与外观相似但名称不同的其他字体关联。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | 获取或设置一个 8 位无符号整数，指定族类型。 |
| [setFamilyType(byte value)](#setFamilyType-byte-) | 获取或设置一个 8 位无符号整数，指定族类型。 |
| [getSerifStyle()](#getSerifStyle--) | 获取或设置一个 8 位无符号整数，指定衬线样式。 |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | 获取或设置一个 8 位无符号整数，指定衬线样式。 |
| [getWeight()](#getWeight--) | 获取或设置一个 8 位无符号整数，指定字体的粗细。 |
| [setWeight(byte value)](#setWeight-byte-) | 获取或设置一个 8 位无符号整数，指定字体的粗细。 |
| [getProportion()](#getProportion--) | 获取或设置一个 8 位无符号整数，指定字体的比例。 |
| [setProportion(byte value)](#setProportion-byte-) | 获取或设置一个 8 位无符号整数，指定字体的比例。 |
| [getContrast()](#getContrast--) | 获取或设置一个 8 位无符号整数，指定字体的对比度。 |
| [setContrast(byte value)](#setContrast-byte-) | 获取或设置一个 8 位无符号整数，指定字体的对比度。 |
| [getStrokeVariation()](#getStrokeVariation--) | 获取或设置一个 8 位无符号整数，指定字体的笔画变化。 |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | 获取或设置一个 8 位无符号整数，指定字体的笔画变化。 |
| [getArmStyle()](#getArmStyle--) | 获取或设置一个 8 位无符号整数，指定字体的臂部样式。 |
| [setArmStyle(byte value)](#setArmStyle-byte-) | 获取或设置一个 8 位无符号整数，指定字体的臂部样式。 |
| [getLetterform()](#getLetterform--) | 获取或设置一个 8 位无符号整数，指定字体的字形。 |
| [setLetterform(byte value)](#setLetterform-byte-) | 获取或设置一个 8 位无符号整数，指定字体的字形。 |
| [getMidline()](#getMidline--) | 获取或设置一个 8 位无符号整数，指定字体的中线。 |
| [setMidline(byte value)](#setMidline-byte-) | 获取或设置一个 8 位无符号整数，指定字体的中线。 |
| [getXHeight()](#getXHeight--) | 获取或设置一个 8 位无符号整数，指定字体的 x 高度。 |
| [setXHeight(byte value)](#setXHeight-byte-) | 获取或设置一个 8 位无符号整数，指定字体的 x 高度。 |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


获取或设置一个 8 位无符号整数，指定族类型。该值必须位于 FamilyType（第 2.1.12 节）枚举表中。

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


获取或设置一个 8 位无符号整数，指定族类型。该值必须位于 FamilyType（第 2.1.12 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


获取或设置一个 8 位无符号整数，指定衬线样式。该值必须位于 SerifType（第 2.1.30 节）枚举表中。

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


获取或设置一个 8 位无符号整数，指定衬线样式。该值必须位于 SerifType（第 2.1.30 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


获取或设置一个 8 位无符号整数，指定字体的粗细。该值必须位于 Weight（第 2.1.34 节）枚举表中。

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的粗细。该值必须位于 Weight（第 2.1.34 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


获取或设置一个 8 位无符号整数，指定字体的比例。该值必须位于 Proportion（第 2.1.28 节）枚举表中。

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的比例。该值必须位于 Proportion（第 2.1.28 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


获取或设置一个 8 位无符号整数，指定字体的对比度。该值必须位于 Contrast（第 2.1.8 节）枚举表中。

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的对比度。该值必须位于 Contrast（第 2.1.8 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


获取或设置一个 8 位无符号整数，指定字体的笔画变化。该值必须位于 StrokeVariation（第 2.1.33 节）枚举表中。

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的笔画变化。该值必须位于 StrokeVariation（第 2.1.33 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


获取或设置一个 8 位无符号整数，指定字体的臂部样式。该值必须位于 ArmStyle（第 2.1.3 节）枚举表中。

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的臂部样式。该值必须位于 ArmStyle（第 2.1.3 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


获取或设置一个 8 位无符号整数，指定字体的字形。该值必须位于 Letterform（第 2.1.20 节）枚举表中。

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的字形。该值必须位于 Letterform（第 2.1.20 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


获取或设置一个 8 位无符号整数，指定字体的中线。该值必须位于 MidLine（第 2.1.23 节）枚举表中。

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的中线。该值必须位于 MidLine（第 2.1.23 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


获取或设置一个 8 位无符号整数，指定字体的 x 高度。该值必须位于 XHeight（第 2.1.35 节）枚举表中。

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


获取或设置一个 8 位无符号整数，指定字体的 x 高度。该值必须位于 XHeight（第 2.1.35 节）枚举表中。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 | byte |  |

