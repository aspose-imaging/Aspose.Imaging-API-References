---
title: "EmfPlusFont"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusFont nesnesi, yazı tipinin boyutu ve stili dahil olmak üzere metnin görünümünü belirleyen özellikleri tanımlar."
type: docs
weight: 42
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfont/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusFont extends EmfPlusGraphicsObjectType
```

The EmfPlusFont nesnesi, yazı tipi, boyut ve stil dahil olmak üzere metnin görünümünü belirleyen özellikleri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusFont()](#EmfPlusFont--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyName()](#getFamilyName--) | Yazı tipi ailesinin adını içeren Length Unicode karakter uzunluğunda bir dizeyi alır veya ayarlar. |
| [setFamilyName(String value)](#setFamilyName-java.lang.String-) | Yazı tipi ailesinin adını içeren Length Unicode karakter uzunluğunda bir dizeyi alır veya ayarlar. |
| [getFontStyleFlags()](#getFontStyleFlags--) | Kalın ve italik gibi yazı tipinin görünümünü etkileyen karakter gliflerinin özelliklerini belirten 32-bit işaretli tam sayı değerini alır veya ayarlar. |
| [setFontStyleFlags(int value)](#setFontStyleFlags-int-) | Kalın ve italik gibi yazı tipinin görünümünü etkileyen karakter gliflerinin özelliklerini belirten 32-bit işaretli tam sayı değerini alır veya ayarlar. |
| [getSizeUnit()](#getSizeUnit--) | EmSize alanı için kullanılan birimleri belirten 32-bit işaretsiz tam sayı değerini alır veya ayarlar. |
| [setSizeUnit(int value)](#setSizeUnit-int-) | EmSize alanı için kullanılan birimleri belirten 32-bit işaretsiz tam sayı değerini alır veya ayarlar. |
| [getEmSize()](#getEmSize--) | SizeUnit alanı tarafından belirtilen birimlerde yazı tipinin em boyutunu belirten 32-bit kayan nokta değerini alır veya ayarlar. |
| [setEmSize(float value)](#setEmSize-float-) | SizeUnit alanı tarafından belirtilen birimlerde yazı tipinin em boyutunu belirten 32-bit kayan nokta değerini alır veya ayarlar. |
### EmfPlusFont() {#EmfPlusFont--}
```
public EmfPlusFont()
```


### getFamilyName() {#getFamilyName--}
```
public String getFamilyName()
```


Yazı tipi ailesinin adını içeren Length Unicode karakter uzunluğunda bir dizeyi alır veya ayarlar.

**Returns:**
java.lang.String
### setFamilyName(String value) {#setFamilyName-java.lang.String-}
```
public void setFamilyName(String value)
```


Yazı tipi ailesinin adını içeren Length Unicode karakter uzunluğunda bir dizeyi alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.lang.String |  |

### getFontStyleFlags() {#getFontStyleFlags--}
```
public int getFontStyleFlags()
```


Kalın ve italik gibi yazı tipinin görünümünü etkileyen karakter gliflerinin özelliklerini belirten 32-bit işaretli tam sayı değerini alır veya ayarlar. Bu değer FontStyle bayraklarından (bölüm 2.1.2.4) oluşmalıdır.

**Returns:**
int
### setFontStyleFlags(int value) {#setFontStyleFlags-int-}
```
public void setFontStyleFlags(int value)
```


Kalın ve italik gibi yazı tipinin görünümünü etkileyen karakter gliflerinin özelliklerini belirten 32-bit işaretli tam sayı değerini alır veya ayarlar. Bu değer FontStyle bayraklarından (bölüm 2.1.2.4) oluşmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getSizeUnit() {#getSizeUnit--}
```
public int getSizeUnit()
```


EmSize alanı için kullanılan birimleri belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bunlar genellikle yazı tipini tasarlarken kullanılan birimlerdir. Değer, UnitType numaralandırmasında (bölüm 2.1.1.33) olmalıdır.

**Returns:**
int
### setSizeUnit(int value) {#setSizeUnit-int-}
```
public void setSizeUnit(int value)
```


EmSize alanı için kullanılan birimleri belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bunlar genellikle yazı tipini tasarlarken kullanılan birimlerdir. Değer, UnitType numaralandırmasında (bölüm 2.1.1.33) olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getEmSize() {#getEmSize--}
```
public float getEmSize()
```


SizeUnit alanı tarafından belirtilen birimlerde yazı tipinin em boyutunu belirten 32-bit kayan nokta değerini alır veya ayarlar.

**Returns:**
float
### setEmSize(float value) {#setEmSize-float-}
```
public void setEmSize(float value)
```


SizeUnit alanı tarafından belirtilen birimlerde yazı tipinin em boyutunu belirten 32-bit kayan nokta değerini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

