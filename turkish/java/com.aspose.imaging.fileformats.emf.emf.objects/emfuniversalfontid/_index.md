---
title: "EmfUniversalFontId"
second_title: "Aspose.Imaging for Java API Referansı"
description: "UniversalFontId nesnesi, EMF metafilelerinde yazı tiplerini tanımlamak için bir mekanizma tanımlar."
type: docs
weight: 37
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfUniversalFontId extends EmfObject
```

UniversalFontId nesnesi, EMF metafilelerinde yazı tiplerini tanımlamak için bir mekanizma tanımlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfUniversalFontId()](#EmfUniversalFontId--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getChecksum()](#getChecksum--) | Yazı tipinin sağlama toplamı olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setChecksum(int value)](#setChecksum-int-) | Yazı tipinin sağlama toplamı olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getIndex()](#getIndex--) | Yazı tipi nesnesiyle ilişkili bir dizin olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setIndex(int value)](#setIndex-int-) | Yazı tipi nesnesiyle ilişkili bir dizin olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. |
### EmfUniversalFontId() {#EmfUniversalFontId--}
```
public EmfUniversalFontId()
```


### getChecksum() {#getChecksum--}
```
public int getChecksum()
```


Yazı tipinin sağlama toplamı olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Sağlama toplamı değeri aşağıdaki anlamlara sahiptir. 0x00000000 Nesne bir cihaz yazı tipidir. 0x00000001 Nesne, istemci makinesine kurulmuş ve PostScript yazıcı sürücüsü tarafından cihaz yazı tipi olarak numaralandırılan Type 1 yazı tipidir. 0x00000002 Nesne bir yazı tipi değildir, ancak bir Type 1 rasterleştiricisidir. 3 \\u2264 değer Nesne bir bitmap, vektör veya TrueType yazı tipi ya da Type 1 rasterleştirilmiş bir yazı tipidir ve bir Type 1 rasterleştirici tarafından oluşturulmuştur.

**Returns:**
int
### setChecksum(int value) {#setChecksum-int-}
```
public void setChecksum(int value)
```


Yazı tipinin sağlama toplamı olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Sağlama toplamı değeri aşağıdaki anlamlara sahiptir. 0x00000000 Nesne bir cihaz yazı tipidir. 0x00000001 Nesne, istemci makinesine kurulmuş ve PostScript yazıcı sürücüsü tarafından cihaz yazı tipi olarak numaralandırılan Type 1 yazı tipidir. 0x00000002 Nesne bir yazı tipi değildir, ancak bir Type 1 rasterleştiricisidir. 3 \\u2264 değer Nesne bir bitmap, vektör veya TrueType yazı tipi ya da Type 1 rasterleştirilmiş bir yazı tipidir ve bir Type 1 rasterleştirici tarafından oluşturulmuştur.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getIndex() {#getIndex--}
```
public int getIndex()
```


Yazı tipi nesnesiyle ilişkili bir dizin olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu alanın anlamı yazı tipinin türüne göre belirlenir.

**Returns:**
int
### setIndex(int value) {#setIndex-int-}
```
public void setIndex(int value)
```


Yazı tipi nesnesiyle ilişkili bir dizin olan 32 bit işaretsiz tam sayıyı alır veya ayarlar. Bu alanın anlamı yazı tipinin türüne göre belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

