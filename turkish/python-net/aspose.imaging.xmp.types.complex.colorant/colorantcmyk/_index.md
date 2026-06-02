---
title: "ColorantCmyk Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/
---

**Summary:** Represents CMYK Colorant.

**Module:** [aspose.imaging.xmp.types.complex.colorant](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/)

**Full Name:** aspose.imaging.xmp.types.complex.colorant.ColorantCmyk

**Inheritance:** IXmpType, ColorantBase

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [ColorantCmyk()](#ColorantCmyk__1) | Yeni bir [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) sınıfının örneğini başlatır. |
| [ColorantCmyk(black, cyan, magenta, yellow)](#ColorantCmyk_black_cyan_magenta_yellow_2) | Yeni bir [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) sınıfının örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| COLOR_VALUE_MAX [statik] | float | r | CMYK renk maddesindeki maksimum renk değeri. |
| COLOR_VALUE_MIN [statik] | float | r | CMYK renk maddesindeki minimum renk değeri. |
| black | float | r/w | Siyah bileşen değerini alır veya ayarlar. |
| color_type | [ColorType](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colortype/) | r/w | Renk tipini alır veya ayarlar. |
| cyan | float | r/w | Camgöbeği bileşen değerini alır veya ayarlar. |
| magenta | float | r/w | Macenta bileşen değerini alır veya ayarlar. |
| mode | [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/) | r | Alır [ColorMode](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colormode/). |
| namespace_uri | string | r | Varsayılan ad alanı URI'sını alır. |
| prefix | string | r | Öneki alır. |
| swatch_name | string | r/w | Renk örneğinin adını alır veya ayarlar. |
| yellow | float | r/w | Sarı bileşen değerini alır veya ayarlar. |
## **Methods**
| **Name** | **Açıklama** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |
| [get_xmp_representation()](#get_xmp_representation__2) | XMP formatında bulunan dize değerini alır. |


### Constructor: ColorantCmyk() {#ColorantCmyk__1}


```
 ColorantCmyk() 
```

Yeni bir [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) sınıfının örneğini başlatır.

### Constructor: ColorantCmyk(black, cyan, magenta, yellow) {#ColorantCmyk_black_cyan_magenta_yellow_2}


```
 ColorantCmyk(black, cyan, magenta, yellow) 
```

Yeni bir [ColorantCmyk](/imaging/python-net/aspose.imaging.xmp.types.complex.colorant/colorantcmyk/) sınıfının örneğini başlatır.

**Parameters:**

| Parameter | Tür | Açıklama |
| :- | :- | :- |
| black | float | Black bileşen değeri. |
| cyan | float | Camgöbeği renk bileşen değeri. |
| magenta | float | Magenta bileşen değeri. |
| yellow | float | Sarı bileşen değeri. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Object | Üye bazlı bir klon. |


### Method: get_xmp_representation() {#get_xmp_representation__2}


```
 get_xmp_representation() 
```

XMP formatında bulunan dize değerini alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | XMP formatında bulunan dize değerini döndürür. |


