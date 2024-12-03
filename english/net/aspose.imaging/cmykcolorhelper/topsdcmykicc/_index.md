---
title: CmykColorHelper.ToPsdCmykIcc
second_title: Aspose.Imaging for .NET API Reference
description: CmykColorHelper method. The conversion from ARGB color to CMYK color using Icc conversion with custom profiles
type: docs
weight: 150
url: /net/aspose.imaging/cmykcolorhelper/topsdcmykicc/
---
## ToPsdCmykIcc(int, Stream, Stream) {#topsdcmykicc_1}

The conversion from ARGB color to CMYK color using Icc conversion with custom profiles.

```csharp
public static int ToPsdCmykIcc(int pixel, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixel | Int32 | The ARGB color. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values..

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int[], Stream, Stream) {#topsdcmykicc_3}

The conversion from ARGB colors to CMYK colors using Icc conversion with custom profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

```csharp
public static int[] ToPsdCmykIcc(int[] pixels, Stream rgbIccStream, Stream cmykIccStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The ARGB colors. |
| rgbIccStream | Stream | The stream containing RGB Icc profile. |
| cmykIccStream | Stream | The stream containing CMYK Icc profile. |

### Return Value

The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values..

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int[]) {#topsdcmykicc_2}

The conversion from ARGB colors to CMYK colors using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

```csharp
public static int[] ToPsdCmykIcc(int[] pixels)
```

| Parameter | Type | Description |
| --- | --- | --- |
| pixels | Int32[] | The ARGB colors. |

### Return Value

The CMYK colors presented as 32-bit integer values in KCMY byte order with inverted channel values..

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)

---

## ToPsdCmykIcc(int) {#topsdcmykicc}

The conversion from ARGB color to CMYK color using Icc conversion with default profiles. Uses PSD CMYK format KCMY byte order with inverted channel values.

```csharp
public static int ToPsdCmykIcc(int argb)
```

| Parameter | Type | Description |
| --- | --- | --- |
| argb | Int32 | The ARGB color. |

### Return Value

The CMYK color presented as a 32-bit integer value in KCMY byte order with inverted channel values.

### See Also

* class [CmykColorHelper](../)
* namespace [Aspose.Imaging](../../cmykcolorhelper/)
* assembly [Aspose.Imaging](../../../)


