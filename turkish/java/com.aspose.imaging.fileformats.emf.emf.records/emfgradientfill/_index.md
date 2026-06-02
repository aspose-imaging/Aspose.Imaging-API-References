---
title: "EmfGradientFill"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EMR_GRADIENTFILL kaydı, dikdörtgenleri veya üçgenleri renk geçişleriyle doldurmayı belirtir."
type: docs
weight: 65
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfgradientfill/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfGradientFill extends EmfDrawingRecordType
```

EMR\_GRADIENTFILL kaydı, dikdörtgenleri veya üçgenleri renk geçişleriyle doldurmayı belirtir.

Üç köşesi bir üçgen olan bir EMR_GRADIENTFILL kaydı, şeklinin renklerin yumuşak geçişleriyle doldurulması gerektiğini belirtir.[85] Bir dikdörtgenin sol üst ve sağ alt köşelerini belirten bir EMR_GRADIENTFILL kaydı, şeklinin renklerin yumuşak geçişleriyle doldurulması gerektiğini belirtir. Dikdörtgen çizerken kullanılabilecek GradientFill sayımında iki renk geçişi modu vardır. GRADIENT_FILL_RECT_H modunda, dikdörtgen soldan sağa doldurulur. GRADIENT_FILL_RECT_V modunda, dikdörtgen üstten alta doldurulur. Not: Bir EMR_GRADIENTFILL kaydı, TriVertex nesnelerindeki Alpha alanlarını göz ardı etmelidir. EMR_GRADIENTFILL kaydını hemen izleyen bir EMR_ALPHABLEND kaydı (bölüm 2.3.1.1), doldurulan alana alfa saydamlık geçişi uygulamak için kullanılabilir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfGradientFill(EmfRecord source)](#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | `EmfGradientFill` sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBounds()](#getBounds--) | Kapsayıcı bir dikdörtgeni, kapsayıcı‑kapsayıcı cihaz birimlerinde belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [setBounds(Rectangle value)](#setBounds-com.aspose.imaging.Rectangle-) | Kapsayıcı bir dikdörtgeni, kapsayıcı‑kapsayıcı cihaz birimlerinde belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19). |
| [getNVer()](#getNVer--) | Köşe sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setNVer(int value)](#setNVer-int-) | Köşe sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getNTri()](#getNTri--) | Doldurulacak dikdörtgen veya üçgen sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setNTri(int value)](#setNTri-int-) | Doldurulacak dikdörtgen veya üçgen sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getUlMode()](#getUlMode--) | Renk geçişi doldurma modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [setUlMode(int value)](#setUlMode-int-) | Renk geçişi doldurma modunu belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar. |
| [getVertexData()](#getVertexData--) | Dikdörtgenlerin veya üçgenlerin köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneleri alır veya ayarlar. |
| [setVertexData(EmfVertexData value)](#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-) | Dikdörtgenlerin veya üçgenlerin köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneleri alır veya ayarlar. |
### EmfGradientFill(EmfRecord source) {#EmfGradientFill-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfGradientFill(EmfRecord source)
```


`EmfGradientFill` sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | Kaynak. |

### getBounds() {#getBounds--}
```
public Rectangle getBounds()
```


Kapsayıcı bir dikdörtgeni, kapsayıcı‑kapsayıcı cihaz birimlerinde belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBounds(Rectangle value) {#setBounds-com.aspose.imaging.Rectangle-}
```
public void setBounds(Rectangle value)
```


Kapsayıcı bir dikdörtgeni, kapsayıcı‑kapsayıcı cihaz birimlerinde belirten bir WMF RectL nesnesini alır veya ayarlar ([MS-WMF] bölüm 2.2.2.19).

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getNVer() {#getNVer--}
```
public int getNVer()
```


Köşe sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setNVer(int value) {#setNVer-int-}
```
public void setNVer(int value)
```


Köşe sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getNTri() {#getNTri--}
```
public int getNTri()
```


Doldurulacak dikdörtgen veya üçgen sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Returns:**
int
### setNTri(int value) {#setNTri-int-}
```
public void setNTri(int value)
```


Doldurulacak dikdörtgen veya üçgen sayısını belirten 32 bit işaretsiz bir tamsayıyı alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getUlMode() {#getUlMode--}
```
public int getUlMode()
```


Değişim doldurma modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Değer GradientFill numaralandırmasında (bölüm 2.1.15) olmalıdır.

**Returns:**
int
### setUlMode(int value) {#setUlMode-int-}
```
public void setUlMode(int value)
```


Değişim doldurma modunu belirten 32 bit işaretsiz tam sayıyı alır veya ayarlar. Değer GradientFill numaralandırmasında (bölüm 2.1.15) olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getVertexData() {#getVertexData--}
```
public EmfVertexData getVertexData()
```


Dikdörtgenlerin veya üçgenlerin köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneleri alır veya ayarlar.

**Returns:**
[EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata)
### setVertexData(EmfVertexData value) {#setVertexData-com.aspose.imaging.fileformats.emf.emf.records.EmfVertexData-}
```
public void setVertexData(EmfVertexData value)
```


Dikdörtgenlerin veya üçgenlerin köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneleri alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfVertexData](../../com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata) |  |

