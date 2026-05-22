---
title: "EmfPlusPathPointTypeRle"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPathPointTypeRle nesnesi, RLE sıkıştırması kullanarak bir grafik yolundaki noktalara ilişkin tip değerlerini belirtir."
type: docs
weight: 62
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtyperle/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBasePointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasepointtype)
```
public final class EmfPlusPathPointTypeRle extends EmfPlusBasePointType
```

EmfPlusPathPointTypeRle nesnesi, RLE sıkıştırması kullanarak bir grafik yolundaki noktalara ilişkilendirilen tip değerlerini belirtir. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 B|1|RunCount | PointType | B (1 bit): Ayarlıysa, yol noktaları bir Bezier eğrisi üzerindedir. Temizlenmişse, yol noktaları bir grafik çizgisi üzerindedir. RunCount (6 bit): Tip alanındaki PointType ile ilişkilendirilecek yol noktalarının sayısı olan çalıştırma sayısı. PointType (1 byte): Yol noktalarıyla ilişkilendirilecek tipi belirten bir EmfPlusPathPointType nesnesi (bölüm 2.2.2.31).
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPathPointTypeRle()](#EmfPlusPathPointTypeRle--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getData()](#getData--) | Veriyi alır veya ayarlar. |
| [setData(int value)](#setData-int-) | Veriyi alır veya ayarlar. |
| [getBezier()](#getBezier--) | `EmfPlusPathPointTypeRle` nesnesinin bezier olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [setBezier(boolean value)](#setBezier-boolean-) | `EmfPlusPathPointTypeRle` nesnesinin bezier olup olmadığını gösteren bir değeri alır veya ayarlar. |
| [getRunCount()](#getRunCount--) | Çalıştırma sayısını alır veya ayarlar. |
| [setRunCount(byte value)](#setRunCount-byte-) | Çalıştırma sayısını alır veya ayarlar. |
| [getPointType()](#getPointType--) | Noktanın tipini alır veya ayarlar. |
| [setPointType(EmfPlusPathPointType value)](#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-) | Noktanın tipini alır veya ayarlar. |
### EmfPlusPathPointTypeRle() {#EmfPlusPathPointTypeRle--}
```
public EmfPlusPathPointTypeRle()
```


### getData() {#getData--}
```
public int getData()
```


Veriyi alır veya ayarlar.

Value: Veri.

**Returns:**
int
### setData(int value) {#setData-int-}
```
public void setData(int value)
```


Veriyi alır veya ayarlar.

Value: Veri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getBezier() {#getBezier--}
```
public boolean getBezier()
```


`EmfPlusPathPointTypeRle` nesnesinin bezier olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, yol noktaları bir Bezier eğrisi üzerindedir. Temizlenmişse, yol noktaları bir grafik çizgisi üzerindedir.

Değer: bezier ise `true`; aksi takdirde `false`.

**Returns:**
boolean
### setBezier(boolean value) {#setBezier-boolean-}
```
public void setBezier(boolean value)
```


`EmfPlusPathPointTypeRle` nesnesinin bezier olup olmadığını gösteren bir değeri alır veya ayarlar. Ayarlıysa, yol noktaları bir Bezier eğrisi üzerindedir. Temizlenmişse, yol noktaları bir grafik çizgisi üzerindedir.

Değer: bezier ise `true`; aksi takdirde `false`.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | boolean |  |

### getRunCount() {#getRunCount--}
```
public byte getRunCount()
```


Çalıştırma sayısını alır veya ayarlar. RunCount (6 bit): PointType alanındaki tip ile ilişkilendirilecek yol noktalarının sayısı olan çalıştırma sayısı.

Değer: Çalıştırma sayısı.

**Returns:**
byte
### setRunCount(byte value) {#setRunCount-byte-}
```
public void setRunCount(byte value)
```


Çalıştırma sayısını alır veya ayarlar. RunCount (6 bit): PointType alanındaki tip ile ilişkilendirilecek yol noktalarının sayısı olan çalıştırma sayısı.

Değer: Çalıştırma sayısı.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getPointType() {#getPointType--}
```
public EmfPlusPathPointType getPointType()
```


Noktanın tipini alır veya ayarlar. PointType (1 byte): Yol noktalarıyla ilişkilendirilecek tipi belirten bir EmfPlusPathPointType nesnesi (bölüm 2.2.2.31).

Değer: Noktanın tipi.

**Returns:**
[EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype)
### setPointType(EmfPlusPathPointType value) {#setPointType-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathPointType-}
```
public void setPointType(EmfPlusPathPointType value)
```


Noktanın tipini alır veya ayarlar. PointType (1 byte): Yol noktalarıyla ilişkilendirilecek tipi belirten bir EmfPlusPathPointType nesnesi (bölüm 2.2.2.31).

Değer: Noktanın tipi.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusPathPointType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathpointtype) |  |

