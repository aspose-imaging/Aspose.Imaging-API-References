---
title: "WmfLogColorSpaceW"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogColorSpaceW nesnesi, Unicode 16 bit karakterlerden oluşan bir ad taşıyan bir renk profili dosyasıyla tanımlanabilen mantıksal bir renk uzayı belirtir."
type: docs
weight: 45
url: /tr/java/com.aspose.imaging.fileformats.wmf.objects/wmflogcolorspacew/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfLogColorSpaceW extends MetaObject
```

LogColorSpaceW nesnesi, Unicode 16-bit karakterlerden oluşan bir adla bir renk profili dosyası tarafından tanımlanabilen bir mantıksal renk uzayı belirtir.

Bu nesnenin alan değerlerinin yorumlanmasıyla ilgili ek ayrıntılar için `WmfLogColorSpace` nesnesine (bölüm 2.2.2.11) bakın.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [WmfLogColorSpaceW()](#WmfLogColorSpaceW--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getSignature()](#getSignature--) | Renk alanı nesnelerinin `signature` değerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x50534F43 olmalıdır, bu da "PSOC" dizesinin ASCII kodlamasıdır. |
| [setSignature(int value)](#setSignature-int-) | Renk alanı nesnelerinin `signature` değerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x50534F43 olmalıdır, bu da "PSOC" dizesinin ASCII kodlamasıdır. |
| [getVersion()](#getVersion--) | Bir `version` numarasını tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x00000400 olmalıdır. |
| [setVersion(int value)](#setVersion-int-) | Bir `version` numarasını tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x00000400 olmalıdır. |
| [getSize()](#getSize--) | Bu nesnenin `size` değerini bayt cinsinden tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setSize(int value)](#setSize-int-) | Bu nesnenin `size` değerini bayt cinsinden tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getColorSpaceType()](#getColorSpaceType--) | Renk alanı tipini belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setColorSpaceType(int value)](#setColorSpaceType-int-) | Renk alanı tipini belirten 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getIntent()](#getIntent--) | Gamut eşleme amacını tanımlayan 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [setIntent(int value)](#setIntent-int-) | Gamut eşleme amacını tanımlayan 32 bit işaretli tam sayıyı alır veya ayarlar. |
| [getEndpoints()](#getEndpoints--) | Bitmap ile ilişkili mantıksal renk alanı için RGB `endpoints` değerlerine karşılık gelen üç rengin CIE renk doygunluğu x, y ve z koordinatlarını tanımlayan bir CIEXYZTriple nesnesini (bölüm 2.2.2.7) alır veya ayarlar. |
| [setEndpoints(WmfCieXyzTriple value)](#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-) | Bitmap ile ilişkili mantıksal renk alanı için RGB `endpoints` değerlerine karşılık gelen üç rengin CIE renk doygunluğu x, y ve z koordinatlarını tanımlayan bir CIEXYZTriple nesnesini (bölüm 2.2.2.7) alır veya ayarlar. |
| [getGammaRed()](#getGammaRed--) | Kırmızı için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [setGammaRed(int value)](#setGammaRed-int-) | Kırmızı için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [getGammaGreen()](#getGammaGreen--) | Yeşil için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Yeşil için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [getGammaBlue()](#getGammaBlue--) | Mavi için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Mavi için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. |
| [getFilename()](#getFilename--) | Renk profili içeren bir dosyanın adını belirten isteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE karakter dizesini alır veya ayarlar. |
| [setFilename(String value)](#setFilename-java.lang.String-) | Renk profili içeren bir dosyanın adını belirten isteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE karakter dizesini alır veya ayarlar. |
### WmfLogColorSpaceW() {#WmfLogColorSpaceW--}
```
public WmfLogColorSpaceW()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Renk alanı nesnelerinin `signature` değerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x50534F43 olmalıdır, bu da "PSOC" dizesinin ASCII kodlamasıdır.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Renk alanı nesnelerinin `signature` değerini belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x50534F43 olmalıdır, bu da "PSOC" dizesinin ASCII kodlamasıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVersion() {#getVersion--}
```
public int getVersion()
```


Bir `version` numarasını tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x00000400 olmalıdır.

**Returns:**
int
### setVersion(int value) {#setVersion-int-}
```
public void setVersion(int value)
```


Bir `version` numarasını tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar; bu değer 0x00000400 olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSize() {#getSize--}
```
public int getSize()
```


Bu nesnenin `size` değerini bayt cinsinden tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Returns:**
int
### setSize(int value) {#setSize-int-}
```
public void setSize(int value)
```


Bu nesnenin `size` değerini bayt cinsinden tanımlayan 32 bit işaretsiz tam sayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getColorSpaceType() {#getColorSpaceType--}
```
public int getColorSpaceType()
```


Renk alanı tipini belirten 32 bit işaretli tam sayıyı alır veya ayarlar. Bu değer LogicalColorSpace enumarasyonunda (bölüm 2.1.1.14) tanımlanmalıdır. Eğer bu değer LCS\_sRGB veya LCS\_WINDOWS\_COLOR\_SPACE ise, sRGB renk alanı kullanılmalıdır.

**Returns:**
int
### setColorSpaceType(int value) {#setColorSpaceType-int-}
```
public void setColorSpaceType(int value)
```


Renk alanı tipini belirten 32 bit işaretli tam sayıyı alır veya ayarlar. Bu değer LogicalColorSpace enumarasyonunda (bölüm 2.1.1.14) tanımlanmalıdır. Eğer bu değer LCS\_sRGB veya LCS\_WINDOWS\_COLOR\_SPACE ise, sRGB renk alanı kullanılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIntent() {#getIntent--}
```
public int getIntent()
```


Gamut eşleme amacını tanımlayan 32 bit işaretli tam sayıyı alır veya ayarlar. Bu değer GamutMappingIntent enumarasyonunda (bölüm 2.1.1.11) tanımlanmalıdır.

**Returns:**
int
### setIntent(int value) {#setIntent-int-}
```
public void setIntent(int value)
```


Gamut eşleme amacını tanımlayan 32 bit işaretli tam sayıyı alır veya ayarlar. Bu değer GamutMappingIntent enumarasyonunda (bölüm 2.1.1.11) tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEndpoints() {#getEndpoints--}
```
public WmfCieXyzTriple getEndpoints()
```


Bitmap ile ilişkili mantıksal renk alanı için RGB `endpoints` değerlerine karşılık gelen üç rengin CIE renk doygunluğu x, y ve z koordinatlarını tanımlayan bir CIEXYZTriple nesnesini (bölüm 2.2.2.7) alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Returns:**
[WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple)
### setEndpoints(WmfCieXyzTriple value) {#setEndpoints-com.aspose.imaging.fileformats.wmf.objects.WmfCieXyzTriple-}
```
public void setEndpoints(WmfCieXyzTriple value)
```


Bitmap ile ilişkili mantıksal renk alanı için RGB `endpoints` değerlerine karşılık gelen üç rengin CIE renk doygunluğu x, y ve z koordinatlarını tanımlayan bir CIEXYZTriple nesnesini (bölüm 2.2.2.7) alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [WmfCieXyzTriple](../../com.aspose.imaging.fileformats.wmf.objects/wmfciexyztriple) |  |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Kırmızı için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Returns:**
int
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Kırmızı için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Yeşil için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Returns:**
int
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Yeşil için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Mavi için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Returns:**
int
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Mavi için tonlu yanıt eğrisini tanımlayan 32 bit sabit nokta değerini alır veya ayarlar. `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak belirtilmemişse, bu alan yoksayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getFilename() {#getFilename--}
```
public String getFilename()
```


Renk profili içeren bir dosyanın adını belirten isteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE karakter dizesini alır veya ayarlar. Bir dosya adı belirtilmişse ve `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak ayarlanmışsa, bu yapının diğer alanları yoksayılmalıdır.

**Returns:**
java.lang.String
### setFilename(String value) {#setFilename-java.lang.String-}
```
public void setFilename(String value)
```


Renk profili içeren bir dosyanın adını belirten isteğe bağlı, null ile sonlandırılmış Unicode UTF16-LE karakter dizesini alır veya ayarlar. Bir dosya adı belirtilmişse ve `ColorSpaceType` alanı LCS\_CALIBRATED\_RGB olarak ayarlanmışsa, bu yapının diğer alanları yoksayılmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

