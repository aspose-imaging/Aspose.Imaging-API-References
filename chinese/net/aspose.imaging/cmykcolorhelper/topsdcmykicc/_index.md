---
title: "CmykColorHelper.ToPsdCmykIcc"
second_title: "Aspose.Imaging for .NET API 参考"
description: "CmykColorHelper 方法。使用自定义配置文件通过 ICC 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反"
type: docs
weight: 150
url: /zh/net/aspose.imaging/cmykcolorhelper/topsdcmykicc/
---
## ToPsdCmykIcc(int[], Stream, Stream) {#topsdcmykicc_3}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。

```csharp
public static int[] ToPsdCmykIcc(int[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值取反。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int[]) {#topsdcmykicc_2}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。

```csharp
public static int[] ToPsdCmykIcc(int[] pixels)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32[] | ARGB 颜色。 |

### 返回值

CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值取反。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int) {#topsdcmykicc}

使用默认配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。使用 PSD CMYK 格式 KCMY 字节顺序，通道值取反。

```csharp
public static int ToPsdCmykIcc(int argb)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| argb | Int32 | ARGB 颜色。 |

### 返回值

CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值取反。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int, Stream, Stream) {#topsdcmykicc_1}

使用自定义配置文件的 Icc 转换将 ARGB 颜色转换为 CMYK 颜色。

```csharp
public static int ToPsdCmykIcc(int pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 像素 | Int32 | ARGB 颜色。 |
| rgbIccStream | Stream | 包含 RGB Icc 配置文件的流。 |
| cmykIccStream | Stream | 包含 CMYK Icc 配置文件的流。 |

### 返回值

CMYK 颜色以 KCMY 字节顺序的 32 位整数值呈现，通道值取反。

### 另请参见

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


