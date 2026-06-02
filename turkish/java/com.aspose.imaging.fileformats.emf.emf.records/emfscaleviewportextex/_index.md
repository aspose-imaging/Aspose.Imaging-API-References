---
title: "EmfScaleViewportExtex"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_SCALEVIEWPORTEXTEX kaydı, belirtilen çarpanlar ve bölücüler tarafından oluşturulan oranları kullanarak bir aygıt bağlamı için görünüm alanını yeniden tanımlar."
type: docs
weight: 113
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfStateRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfstaterecordtype)
```
public final class EmfScaleViewportExtex extends EmfStateRecordType
```

EMR\_SCALEVIEWPORTEXTEX kaydı, belirtilen çarpanlar ve bölücülerle oluşan oranları kullanarak bir cihaz bağlamı için görünüm alanını yeniden tanımlar.

Aygıt bağlamı sabit ölçek eşleme modunu kullanıyorsa kapsam değiştirilemez. Yalnızca MM\_ISOTROPIC ve MM\_ANISOTROPIC sabit ölçek değildir. Görünüm alanı kapsamları aşağıdaki gibi değiştirilir. xNewWE = (xOldWE \* xNum) / xDenom yNewWE = (yOldWE \* yNum) / yDenom
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfScaleViewportExtex(EmfRecord source)](#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfScaleViewportExtex` sınıfının yeni bir örneğini başlatır. |
| [EmfScaleViewportExtex()](#EmfScaleViewportExtex--) | Yeni bir [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex) sınıfı örneği başlatır. |
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
### EmfScaleViewportExtex(EmfRecord source) {#EmfScaleViewportExtex-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfScaleViewportExtex(EmfRecord source)
```


`EmfScaleViewportExtex` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### EmfScaleViewportExtex() {#EmfScaleViewportExtex--}
```
public EmfScaleViewportExtex()
```


Yeni bir [EmfScaleViewportExtex](../../com.aspose.imaging.fileformats.emf.emf.records/emfscaleviewportextex) sınıfı örneği başlatır.

### getXNum() {#getXNum--}
```
public int getXNum()
```


Yatay çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Returns:**
int
### setXNum(int value) {#setXNum-int-}
```
public void setXNum(int value)
```


Yatay çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getXDenom() {#getXDenom--}
```
public int getXDenom()
```


Yatay böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Returns:**
int
### setXDenom(int value) {#setXDenom-int-}
```
public void setXDenom(int value)
```


Yatay böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYNum() {#getYNum--}
```
public int getYNum()
```


Dikey çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Returns:**
int
### setYNum(int value) {#setYNum-int-}
```
public void setYNum(int value)
```


Dikey çarpanı belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getYDenom() {#getYDenom--}
```
public int getYDenom()
```


Dikey böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Returns:**
int
### setYDenom(int value) {#setYDenom-int-}
```
public void setYDenom(int value)
```


Dikey böleni belirten 32 bit işaretli bir tam sayıyı alır veya ayarlar. Sıfır olamaz.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

