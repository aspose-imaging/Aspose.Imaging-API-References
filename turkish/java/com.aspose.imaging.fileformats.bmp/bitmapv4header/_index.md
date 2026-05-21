---
title: "BitmapV4Header"
second_title: "Aspose.Imaging for Java API Referansı"
description: "BitmapV4Header yapısı bitmap bilgi başlık dosyasıdır."
type: docs
weight: 13
url: /tr/java/com.aspose.imaging.fileformats.bmp/bitmapv4header/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.bmp.BitmapCoreHeader](../../com.aspose.imaging.fileformats.bmp/bitmapcoreheader), [com.aspose.imaging.fileformats.bmp.BitmapInfoHeader](../../com.aspose.imaging.fileformats.bmp/bitmapinfoheader)
```
public class BitmapV4Header extends BitmapInfoHeader
```

BitmapV4Header yapısı bitmap bilgi başlık dosyasıdır. BITMAPINFOHEADER yapısının genişletilmiş bir sürümüdür.
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getRedMask()](#getRedMask--) | Her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [setRedMask(int value)](#setRedMask-int-) | Her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [getGreenMask()](#getGreenMask--) | Her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [setGreenMask(int value)](#setGreenMask-int-) | Her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [getBlueMask()](#getBlueMask--) | Her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [setBlueMask(int value)](#setBlueMask-int-) | Her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir. |
| [getAlphaMask()](#getAlphaMask--) | Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar. |
| [setAlphaMask(int value)](#setAlphaMask-int-) | Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar. |
| [getCSType()](#getCSType--) | DIB'in renk uzayını alır veya ayarlar. |
| [setCSType(int value)](#setCSType-int-) | DIB'in renk uzayını alır veya ayarlar. |
| [getEndpoints()](#getEndpoints--) | CoordinatesTriple sınıfını alır veya ayarlar. |
| [setEndpoints(CieCoordinatesTriple value)](#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-) | CoordinatesTriple sınıfını alır veya ayarlar. |
| [getGammaRed()](#getGammaRed--) | Kırmızı gama değerini alır veya ayarlar. |
| [setGammaRed(int value)](#setGammaRed-int-) | Kırmızı gama değerini alır veya ayarlar. |
| [getGammaGreen()](#getGammaGreen--) | Yeşil gama değerini alır veya ayarlar. |
| [setGammaGreen(int value)](#setGammaGreen-int-) | Yeşil gama değerini alır veya ayarlar. |
| [getGammaBlue()](#getGammaBlue--) | Mavi gama değerini alır veya ayarlar. |
| [setGammaBlue(int value)](#setGammaBlue-int-) | Mavi gama değerini alır veya ayarlar. |
### getRedMask() {#getRedMask--}
```
public int getRedMask()
```


Her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Returns:**
int
### setRedMask(int value) {#setRedMask-int-}
```
public void setRedMask(int value)
```


Her pikselin kırmızı bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getGreenMask() {#getGreenMask--}
```
public int getGreenMask()
```


Her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Returns:**
int
### setGreenMask(int value) {#setGreenMask-int-}
```
public void setGreenMask(int value)
```


Her pikselin yeşil bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBlueMask() {#getBlueMask--}
```
public int getBlueMask()
```


Her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Returns:**
int
### setBlueMask(int value) {#setBlueMask-int-}
```
public void setBlueMask(int value)
```


Her pikselin mavi bileşenini belirten renk maskesini alır veya ayarlar, yalnızca bV4Compression BI\_BITFIELDS olarak ayarlandığında geçerlidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getAlphaMask() {#getAlphaMask--}
```
public int getAlphaMask()
```


Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar.

**Returns:**
int
### setAlphaMask(int value) {#setAlphaMask-int-}
```
public void setAlphaMask(int value)
```


Her pikselin alfa bileşenini belirten renk maskesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getCSType() {#getCSType--}
```
public int getCSType()
```


DIB'in renk uzayını alır veya ayarlar.

**Returns:**
int
### setCSType(int value) {#setCSType-int-}
```
public void setCSType(int value)
```


DIB'in renk uzayını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEndpoints() {#getEndpoints--}
```
public CieCoordinatesTriple getEndpoints()
```


CoordinatesTriple sınıfını alır veya ayarlar.

**Returns:**
[CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) - The endpoints.
### setEndpoints(CieCoordinatesTriple value) {#setEndpoints-com.aspose.imaging.fileformats.bmp.structures.CieCoordinatesTriple-}
```
public void setEndpoints(CieCoordinatesTriple value)
```


CoordinatesTriple sınıfını alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [CieCoordinatesTriple](../../com.aspose.imaging.fileformats.bmp.structures/ciecoordinatestriple) | Uç noktalar. |

### getGammaRed() {#getGammaRed--}
```
public int getGammaRed()
```


Kırmızı gama değerini alır veya ayarlar.

**Returns:**
int - Kırmızı gama.
### setGammaRed(int value) {#setGammaRed-int-}
```
public void setGammaRed(int value)
```


Kırmızı gama değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Kırmızı gama. |

### getGammaGreen() {#getGammaGreen--}
```
public int getGammaGreen()
```


Yeşil gama değerini alır veya ayarlar.

**Returns:**
int - Yeşil gama.
### setGammaGreen(int value) {#setGammaGreen-int-}
```
public void setGammaGreen(int value)
```


Yeşil gama değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Yeşil gama. |

### getGammaBlue() {#getGammaBlue--}
```
public int getGammaBlue()
```


Mavi gama değerini alır veya ayarlar.

**Returns:**
int - Mavi gama.
### setGammaBlue(int value) {#setGammaBlue-int-}
```
public void setGammaBlue(int value)
```


Mavi gama değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | Gamma mavi. |

