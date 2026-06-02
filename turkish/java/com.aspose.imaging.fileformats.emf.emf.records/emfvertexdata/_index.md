---
title: "EmfVertexData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Dikdörtgenler veya üçgenler için köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneler."
type: docs
weight: 155
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.records/emfvertexdata/
---
**Inheritance:**
java.lang.Object
```
public final class EmfVertexData
```

Dikdörtgenler veya üçgenler için köşe noktalarını ve bunlara karşılık gelen renkleri belirten nesneler.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfVertexData()](#EmfVertexData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getVertexObjects()](#getVertexObjects--) | nVer TriVertex nesnelerinin bir dizisini alır veya ayarlar (bölüm 2.2.26). |
| [setVertexObjects(EmfTriVertex[] value)](#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---) | nVer TriVertex nesnelerinin bir dizisini alır veya ayarlar (bölüm 2.2.26). |
| [getVertexIndexes()](#getVertexIndexes--) | ulMode alanının değerine bağlı olarak nTri GradientRectangle nesnelerinin (bölüm 2.2.7) veya GradientTriangle nesnelerinin (bölüm 2.2.8) bir dizisini alır veya ayarlar. |
| [setVertexIndexes(EmfGradientRectangle[] value)](#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---) | ulMode alanının değerine bağlı olarak nTri GradientRectangle nesnelerinin (bölüm 2.2.7) veya GradientTriangle nesnelerinin (bölüm 2.2.8) bir dizisini alır veya ayarlar. |
| [getVertexPadding()](#getVertexPadding--) | ulMode alanının değeri GradientRectangle nesnelerini (bölüm 2.2.7) gösteriyorsa bulunması ZORUNLU olan, nTri çarpı dört bayttan oluşan isteğe bağlı değişken uzunlukta bir dizi alır veya ayarlar. |
| [setVertexPadding(byte[] value)](#setVertexPadding-byte---) | ulMode alanının değeri GradientRectangle nesnelerini (bölüm 2.2.7) gösteriyorsa bulunması ZORUNLU olan, nTri çarpı dört bayttan oluşan isteğe bağlı değişken uzunlukta bir dizi alır veya ayarlar. |
### EmfVertexData() {#EmfVertexData--}
```
public EmfVertexData()
```


### getVertexObjects() {#getVertexObjects--}
```
public EmfTriVertex[] getVertexObjects()
```


nVer TriVertex nesnelerinin (bölüm 2.2.26) bir dizisini alır veya ayarlar. Her nesne, ulMode alanının değerine bağlı olarak bir dikdörtgen ya da üçgenin köşe konumunu ve rengini belirtir.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex[]
### setVertexObjects(EmfTriVertex[] value) {#setVertexObjects-com.aspose.imaging.fileformats.emf.emf.objects.EmfTriVertex---}
```
public void setVertexObjects(EmfTriVertex[] value)
```


nVer TriVertex nesnelerinin (bölüm 2.2.26) bir dizisini alır veya ayarlar. Her nesne, ulMode alanının değerine bağlı olarak bir dikdörtgen ya da üçgenin köşe konumunu ve rengini belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfTriVertex\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emftrivertex) |  |

### getVertexIndexes() {#getVertexIndexes--}
```
public EmfGradientRectangle[] getVertexIndexes()
```


ulMode alanının değerine bağlı olarak nTri GradientRectangle nesnelerinin (bölüm 2.2.7) veya GradientTriangle nesnelerinin (bölüm 2.2.8) bir dizisini alır veya ayarlar. Her nesne, VertexObjects alanındaki TriVertex nesneleri dizisine indeksleri belirtir.

**Returns:**
com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle[]
### setVertexIndexes(EmfGradientRectangle[] value) {#setVertexIndexes-com.aspose.imaging.fileformats.emf.emf.objects.EmfGradientRectangle---}
```
public void setVertexIndexes(EmfGradientRectangle[] value)
```


ulMode alanının değerine bağlı olarak nTri GradientRectangle nesnelerinin (bölüm 2.2.7) veya GradientTriangle nesnelerinin (bölüm 2.2.8) bir dizisini alır veya ayarlar. Her nesne, VertexObjects alanındaki TriVertex nesneleri dizisine indeksleri belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfGradientRectangle\[\]](../../com.aspose.imaging.fileformats.emf.emf.objects/emfgradientrectangle) |  |

### getVertexPadding() {#getVertexPadding--}
```
public byte[] getVertexPadding()
```


ulMode alanının değeri GradientRectangle nesnelerini (bölüm 2.2.7) gösteriyorsa bulunması ZORUNLU olan, nTri çarpı dört bayttan oluşan isteğe bağlı değişken uzunlukta bir dizi alır veya ayarlar. ulMode alanının değeri GradientTriangle nesnelerini (bölüm 2.2.8) gösteriyorsa VertexPadding bulunmaz. Bu alan YOK SAYILMALI.

**Returns:**
byte[]
### setVertexPadding(byte[] value) {#setVertexPadding-byte---}
```
public void setVertexPadding(byte[] value)
```


ulMode alanının değeri GradientRectangle nesnelerini (bölüm 2.2.7) gösteriyorsa bulunması ZORUNLU olan, nTri çarpı dört bayttan oluşan isteğe bağlı değişken uzunlukta bir dizi alır veya ayarlar. ulMode alanının değeri GradientTriangle nesnelerini (bölüm 2.2.8) gösteriyorsa VertexPadding bulunmaz. Bu alan YOK SAYILMALI.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte[] |  |

