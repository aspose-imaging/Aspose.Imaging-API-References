---
title: "Font.Font"
second_title: "Aspose.Imaging for .NET API 参考"
description: "Font 构造函数。初始化一个使用指定现有 Font 和 FontStyle 枚举的新 Font。"
type: docs
weight: 10
url: /zh/net/aspose.imaging/font/font/
---
## Font(Font, FontStyle) {#constructor}

初始化一个使用指定现有 [`Font`](../) 和 [`FontStyle`](../../fontstyle/) 枚举的新 [`Font`](../)。

```csharp
public Font(Font prototype, FontStyle newStyle)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| prototype | Font | 用于创建新 [`Font`](../) 的现有 [`Font`](../)。 |
| newStyle | FontStyle | 要应用于新 [`Font`](../) 的 [`FontStyle`](../../fontstyle/)。[`FontStyle`](../../fontstyle/) 枚举的多个值可以使用 OR 运算符进行组合。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | *prototype* 为 null。 |

### 另请参见

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float) {#constructor_1}

使用指定大小初始化一个新 [`Font`](../)。字符集设置为 Default，图形单位设置为 Point，字体样式设置为 Regular。

```csharp
public Font(string fontName, float emSize)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名称的字符串表示形式。 |
| emSize | 单精度 | 新字体的 em 大小（以点为单位）。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 小于或等于 0、结果为无穷大或不是有效数字。 |
| ArgumentNullException | *fontName* 为 null。 |

### 另请参见

* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle) {#constructor_2}

使用指定的大小和样式初始化一个新 [`Font`](../)。字符集设置为 Default，图形单位设置为 Point。

```csharp
public Font(string fontName, float emSize, FontStyle style)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名称的字符串表示形式。 |
| emSize | 单精度 | 新字体的 em 大小（以点为单位）。 |
| style | FontStyle | 新字体的 [`FontStyle`](../../fontstyle/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 小于或等于 0、结果为无穷大或不是有效数字。 |
| ArgumentNullException | *fontName* 为 null。 |

### 另请参见

* enum [FontStyle](../../fontstyle/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, GraphicsUnit) {#constructor_5}

使用指定的大小和单位初始化一个新 [`Font`](../)。字符集设置为 Default，样式设置为 Regular。

```csharp
public Font(string fontName, float emSize, GraphicsUnit unit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名称的字符串表示形式。 |
| emSize | 单精度 | 新字体的 em 大小，单位由 *unit* 参数指定。 |
| unit | GraphicsUnit | 新字体的 [`GraphicsUnit`](../../graphicsunit/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 小于或等于 0、结果为无穷大或不是有效数字。 |
| ArgumentNullException | *fontName* 为 null。 |

### 另请参见

* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit, CharacterSet) {#constructor_4}

使用指定的大小、样式、单位和字符集初始化一个新 [`Font`](../)。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit, 
    CharacterSet characterSet)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名称的字符串表示形式。 |
| emSize | 单精度 | 新字体的 em 大小，单位由 *unit* 参数指定。 |
| style | FontStyle | 新字体的 [`FontStyle`](../../fontstyle/)。 |
| unit | GraphicsUnit | 新字体的 [`GraphicsUnit`](../../graphicsunit/)。 |
| characterSet | CharacterSet | 用于此字体的字符集。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 小于或等于 0、结果为无穷大或不是有效数字。 |
| ArgumentNullException | *fontName* 为 null。 |

### 另请参见

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* enum [CharacterSet](../../characterset/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)

---

## Font(string, float, FontStyle, GraphicsUnit) {#constructor_3}

使用指定的大小、样式和单位初始化一个新 [`Font`](../)。

```csharp
public Font(string fontName, float emSize, FontStyle style, GraphicsUnit unit)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fontName | String | [`Font`](../) 名称的字符串表示形式。 |
| emSize | 单精度 | 新字体的 em 大小，单位由 *unit* 参数指定。 |
| style | FontStyle | 新字体的 [`FontStyle`](../../fontstyle/)。 |
| unit | GraphicsUnit | 新字体的 [`GraphicsUnit`](../../graphicsunit/)。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | *emSize* 小于或等于 0、结果为无穷大或不是有效数字。 |
| ArgumentNullException | *fontName* 为 null。 |

### 另请参见

* enum [FontStyle](../../fontstyle/)
* enum [GraphicsUnit](../../graphicsunit/)
* class [Font](../)
* namespace [Aspose.Imaging](../../font/)
* assembly [Aspose.Imaging](../../../)


