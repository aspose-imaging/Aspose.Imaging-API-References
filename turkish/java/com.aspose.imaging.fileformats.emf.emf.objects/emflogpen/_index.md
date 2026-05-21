---
title: "EmfLogPen"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogPen nesnesi, mantıksal bir kalemin stil genişliğini ve rengini tanımlar."
type: docs
weight: 27
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

LogPen nesnesi, mantıksal bir kalemin stilini, genişliğini ve rengini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | PenStyle'ı belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setPenStyle(int value)](#setPenStyle-int-) | PenStyle'ı belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getWidth()](#getWidth--) | X alanının değeriyle kalemin genişliğini belirten WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | X alanının değeriyle kalemin genişliğini belirten WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. |
| [getAffectWidth()](#getAffectWidth--) | Etkisinin genişliğini alır veya ayarlar. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Etkisinin genişliğini alır veya ayarlar. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Kalem renk değerini belirten WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Kalem renk değerini belirten WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


PenStyle'ı belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer, bölüm 2.1.25'te belirtilen PenStyle numaralandırma tablosundan tanımlanmalıdır.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


PenStyle'ı belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer, bölüm 2.1.25'te belirtilen PenStyle numaralandırma tablosundan tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


X alanının değeriyle kalemin genişliğini belirten WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. Y alanının değeri göz ardı edilmelidir.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


X alanının değeriyle kalemin genişliğini belirten WMF PointL nesnesini ([MS-WMF] bölüm 2.2.2.15) alır veya ayarlar. Y alanının değeri göz ardı edilmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Etkisinin genişliğini alır veya ayarlar.

Değer: Etkinin genişliği.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Etkisinin genişliğini alır veya ayarlar.

Değer: Etkinin genişliği.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Kalem renk değerini belirten WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

Değer: 32 bit ARGB renk

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Kalem renk değerini belirten WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar.

Değer: 32 bit ARGB renk

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

