---
title: "EmfScaleWindowExtex"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SCALEWINDOWEXTEX kaydı, belirtilen çarpanlar ve bölenler kullanılarak oluşturulan oranları kullanarak oynatma cihaz bağlamı için pencereyi yeniden tanımlar."
type: docs
weight: 114
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleWindowExtex extends EmfStateRecordType
```

EMR\_SCALEWINDOWEXTEX kaydı, belirtilen çarpanlar ve bölücülerle oluşan oranları kullanarak bir oynatma cihaz bağlamı için pencereyi yeniden tanımlar.

Cihaz bağlamı sabit ölçekli bir eşleme modu kullanıyorsa kapsam değiştirilemez. Yalnızca MM\_ISOTROPIC ve MM\_ANISOTROPIC sabit ölçekli değildir. Pencere kapsamları aşağıdaki gibi değiştirilir. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfScaleWindowExtex(EmfRecord source)](#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Yeni bir `EmfScaleWindowExtex` sınıfı örneği başlatır. |
| [EmfScaleWindowExtex()](#EmfScaleWindowExtex--) | Yeni bir [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) sınıfı örneği başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getXNum()](#getXNum--) | Yatay çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setXNum(int value)](#setXNum-int-) | Yatay çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [getXDenom()](#getXDenom--) | Yatay böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setXDenom(int value)](#setXDenom-int-) | Yatay böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [getYNum()](#getYNum--) | Dikey çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setYNum(int value)](#setYNum-int-) | Dikey çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [getYDenom()](#getYDenom--) | Dikey böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
| [setYDenom(int value)](#setYDenom-int-) | Dikey böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. |
### EmfScaleWindowExtex(EmfRecord source) {#EmfScaleWindowExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleWindowExtex(EmfRecord source)
```


Yeni bir `EmfScaleWindowExtex` sınıfı örneği başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfScaleWindowExtex() {#EmfScaleWindowExtex--}
```
public EmfScaleWindowExtex()
```


Yeni bir [EmfScaleWindowExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscalewindowextex) sınıfı örneği başlatır.

### getXNum() {#getXNum--}
```
public int getXNum()
```


Yatay çarpanı belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Yatay çarpanı belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Yatay böleni belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Yatay böleni belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Dikey çarpanı belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Dikey çarpanı belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Dikey böleni belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Dikey böleni belirten 32-bit işaretli tamsayıyı alır veya ayarlar. SIFIR OLMAMAZ.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

