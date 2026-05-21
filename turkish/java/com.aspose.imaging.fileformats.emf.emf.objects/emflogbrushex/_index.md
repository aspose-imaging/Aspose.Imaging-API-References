---
title: "EmfLogBrushEx"
second_title: "Aspose.Imaging for Java API Referansı"
description: "LogBrushEx nesnesi, cihazdan bağımsız bir fırçanın stil rengini ve desenini tanımlar."
type: docs
weight: 21
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogbrushex/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfLogBrushEx extends EmfObject
```

LogBrushEx nesnesi, aygıt bağımsız bir fırçanın stilini, rengini ve desenini tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfLogBrushEx()](#EmfLogBrushEx--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrushStyle()](#getBrushStyle--) | Fırça stilini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBrushStyle(int value)](#setBrushStyle-int-) | Fırça stilini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Renk belirten 32 bit WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Renk belirten 32 bit WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. |
| [getBrushHatch()](#getBrushHatch--) | Fırça tarama verilerini içeren 32 bit işaretsiz alanı alır veya ayarlar. |
| [setBrushHatch(int value)](#setBrushHatch-int-) | Fırça tarama verilerini içeren 32 bit işaretsiz alanı alır veya ayarlar. |
### EmfLogBrushEx() {#EmfLogBrushEx--}
```
public EmfLogBrushEx()
```


### getBrushStyle() {#getBrushStyle--}
```
public int getBrushStyle()
```


Fırça stilini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer, WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) bir enumerasyon olmalıdır. Bu yapıda desteklenen stil değerleri bu bölümde daha sonra listelenir. BS\_NULL stili, etkisi olmayan bir fırça belirtmek için KULLANILMALIDIR.

**Returns:**
int
### setBrushStyle(int value) {#setBrushStyle-int-}
```
public void setBrushStyle(int value)
```


Fırça stilini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer, WMF BrushStyle enumerasyonundan ([MS-WMF] bölüm 2.1.1.4) bir enumerasyon olmalıdır. Bu yapıda desteklenen stil değerleri bu bölümde daha sonra listelenir. BS\_NULL stili, etkisi olmayan bir fırça belirtmek için KULLANILMALIDIR.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Renk belirten 32 bit WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. Bu alanın yorumu, aşağıdaki tabloda açıklandığı gibi BrushStyle değerine bağlıdır.

Değer: 32 bit ARGB renk

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Renk belirten 32 bit WMF ColorRef nesnesini ([MS-WMF] bölüm 2.2.2.8) alır veya ayarlar. Bu alanın yorumu, aşağıdaki tabloda açıklandığı gibi BrushStyle değerine bağlıdır.

Değer: 32 bit ARGB renk

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBrushHatch() {#getBrushHatch--}
```
public int getBrushHatch()
```


Fırça tarama verilerini içeren 32 bit işaretsiz alanı alır veya ayarlar. Yorumu, BrushStyle değerine bağlıdır,

**Returns:**
int
### setBrushHatch(int value) {#setBrushHatch-int-}
```
public void setBrushHatch(int value)
```


Fırça tarama verilerini içeren 32 bit işaretsiz alanı alır veya ayarlar. Yorumu, BrushStyle değerine bağlıdır,

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

