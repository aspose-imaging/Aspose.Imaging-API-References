---
title: "WmfLogColorSpace Sınıfı"
type: docs
weight: 380
url: /tr/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/
---

**Summary:** The LogColorSpace object specifies a logical color space for the<br/>                playback device context, which can be the name of a color profile in<br/>                ASCII characters.

**Module:** [aspose.imaging.fileformats.wmf.objects](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/)

**Full Name:** aspose.imaging.fileformats.wmf.objects.WmfLogColorSpace

**Inheritance:** MetaObject

## **Constructors**
| **Name** | **Açıklama** |
| :- | :- |
| [WmfLogColorSpace()](#WmfLogColorSpace__1) | WmfLogColorSpace sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Açıklama** |
| :- | :- | :- | :- |
| color_space_type | [WmfLogicalColorSpaceEnum](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmflogicalcolorspaceenum/) | r/w | Renk uzayını belirten 32 bit işaretli bir tam sayı alır veya ayarlar<br/>                tür. Bu, LogicalColorSpace enumeration içinde tanımlanmalıdır<br/>                (section 2.1.1.14). Eğer bu değer LCS_sRGB veya<br/>                LCS_WINDOWS_COLOR_SPACE ise, sRGB renk uzayı MUST be used. |
| endpoints | [WmfCieXyzTriple](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfciexyztriple/) | r/w | CIEXYZTriple nesnesini (section 2.2.2.7) alır veya ayarlar<br/>                CIE kromatikliği x, y ve z koordinatlarını tanımlayan üç renk için<br/>                RGB [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) ile mantıksal<br/>                bitmap ile ilişkili renk uzayına karşılık gelir. Eğer<br/>                [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) alanı LCS_CALIBRATED_RGB olarak belirtilmezse, bu alan MUST be ignored. |
| filename | string | r/w | Opsiyonel, ASCII karakter dizesini alır veya ayarlar; bu dize, bir renk profili içeren dosyanın adını belirtir. Bir dosya adı belirtilmişse ve [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) alanı LCS_CALIBRATED_RGB olarak ayarlanmışsa, bu yapının diğer alanları SHOULD be ignored. |
| gamma_blue | int | r/w | Mavi için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar.<br/>                Eğer [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) alanı LCS_CALIBRATED_RGB olarak belirtilmemişse, bu alan MUST be ignored. |
| gamma_green | int | r/w | Yeşil için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar.<br/>                Eğer [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) alanı LCS_CALIBRATED_RGB olarak belirtilmemişse, bu alan MUST be ignored. |
| gamma_red | int | r/w | Kırmızı için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar.<br/>                Eğer [WmfLogColorSpace.color_space_type](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) alanı LCS_CALIBRATED_RGB olarak belirtilmemişse, bu alan MUST be ignored. |
| intent | [WmfGamutMappingIntent](/imaging/python-net/aspose.imaging.fileformats.wmf.consts/wmfgamutmappingintent/) | r/w | Gamut eşleme amacını tanımlayan 32 bit işaretli bir tam sayı alır veya ayarlar.<br/>                It MUST be defined in the GamutMappingIntent enumeration<br/>                (section 2.1.1.11). |
| signature | int | r/w | Renk uzayı nesnelerinin [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) belirten 32 bit işaretsiz tam sayı alır veya ayarlar; it MUST be set to<br/>                the value 0x50534F43, which is the ASCII encoding of the string<br/>                "PSOC". |
| size | int | r/w | Bu nesnenin [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) bayt cinsinden tanımlayan 32 bit işaretsiz tam sayı alır veya ayarlar. |
| version | int | r/w | Bir [None](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmflogcolorspace/) sayısını tanımlayan 32 bit işaretsiz tam sayı alır veya ayarlar; it MUST be0x00000400. |


### Constructor: WmfLogColorSpace() {#WmfLogColorSpace__1}


```
 WmfLogColorSpace() 
```

WmfLogColorSpace sınıfının yeni bir örneğini başlatır

