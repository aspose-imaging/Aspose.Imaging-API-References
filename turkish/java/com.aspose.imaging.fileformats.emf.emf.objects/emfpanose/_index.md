---
title: "EmfPanose"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Panose nesnesi, bir TrueType fontu için PANOSE font sınıflandırma değerlerini açıklar."
type: docs
weight: 30
url: /tr/java/com.aspose.imaging.fileformats.emf.emf.objects/emfpanose/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfPanose extends EmfObject
```

Panose nesnesi, bir TrueType yazı tipi için PANOSE yazı tipi sınıflandırma değerlerini tanımlar. Bu özellikler, yazı tipini benzer görünüme sahip ancak farklı isimli diğer yazı tipleriyle ilişkilendirmek için kullanılır.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPanose()](#EmfPanose--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getFamilyType()](#getFamilyType--) | Aile tipini belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setFamilyType(byte value)](#setFamilyType-byte-) | Aile tipini belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getSerifStyle()](#getSerifStyle--) | Serif stilini belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setSerifStyle(byte value)](#setSerifStyle-byte-) | Serif stilini belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getWeight()](#getWeight--) | Yazı tipinin ağırlığını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setWeight(byte value)](#setWeight-byte-) | Yazı tipinin ağırlığını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getProportion()](#getProportion--) | Yazı tipinin oranını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setProportion(byte value)](#setProportion-byte-) | Yazı tipinin oranını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getContrast()](#getContrast--) | Yazı tipinin kontrastını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [setContrast(byte value)](#setContrast-byte-) | Yazı tipinin kontrastını belirten 8 bit işaretsiz tam sayıyı alır veya ayarlar. |
| [getStrokeVariation()](#getStrokeVariation--) | Yazı tipinin darbeyi varyasyonunu belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setStrokeVariation(byte value)](#setStrokeVariation-byte-) | Yazı tipinin darbeyi varyasyonunu belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getArmStyle()](#getArmStyle--) | Yazı tipinin kol stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setArmStyle(byte value)](#setArmStyle-byte-) | Yazı tipinin kol stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getLetterform()](#getLetterform--) | Yazı tipinin harf biçimini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setLetterform(byte value)](#setLetterform-byte-) | Yazı tipinin harf biçimini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getMidline()](#getMidline--) | Yazı tipinin orta çizgisini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setMidline(byte value)](#setMidline-byte-) | Yazı tipinin orta çizgisini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getXHeight()](#getXHeight--) | Yazı tipinin x yüksekliğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setXHeight(byte value)](#setXHeight-byte-) | Yazı tipinin x yüksekliğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. |
### EmfPanose() {#EmfPanose--}
```
public EmfPanose()
```


### getFamilyType() {#getFamilyType--}
```
public byte getFamilyType()
```


Aile tipini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **FamilyType** (bölüm 2.1.12) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setFamilyType(byte value) {#setFamilyType-byte-}
```
public void setFamilyType(byte value)
```


Aile tipini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **FamilyType** (bölüm 2.1.12) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getSerifStyle() {#getSerifStyle--}
```
public byte getSerifStyle()
```


Serif stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **SerifType** (bölüm 2.1.30) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setSerifStyle(byte value) {#setSerifStyle-byte-}
```
public void setSerifStyle(byte value)
```


Serif stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **SerifType** (bölüm 2.1.30) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getWeight() {#getWeight--}
```
public byte getWeight()
```


Yazı tipinin ağırlığını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Weight** (bölüm 2.1.34) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setWeight(byte value) {#setWeight-byte-}
```
public void setWeight(byte value)
```


Yazı tipinin ağırlığını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Weight** (bölüm 2.1.34) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getProportion() {#getProportion--}
```
public byte getProportion()
```


Yazı tipinin oranını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Proportion** (bölüm 2.1.28) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setProportion(byte value) {#setProportion-byte-}
```
public void setProportion(byte value)
```


Yazı tipinin oranını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Proportion** (bölüm 2.1.28) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getContrast() {#getContrast--}
```
public byte getContrast()
```


Yazı tipinin kontrastını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Contrast** (bölüm 2.1.8) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setContrast(byte value) {#setContrast-byte-}
```
public void setContrast(byte value)
```


Yazı tipinin kontrastını belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Contrast** (bölüm 2.1.8) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getStrokeVariation() {#getStrokeVariation--}
```
public byte getStrokeVariation()
```


Yazı tipinin darbeyi varyasyonunu belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **StrokeVariation** (bölüm 2.1.33) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setStrokeVariation(byte value) {#setStrokeVariation-byte-}
```
public void setStrokeVariation(byte value)
```


Yazı tipinin darbeyi varyasyonunu belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **StrokeVariation** (bölüm 2.1.33) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getArmStyle() {#getArmStyle--}
```
public byte getArmStyle()
```


Yazı tipinin kol stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **ArmStyle** (bölüm 2.1.3) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setArmStyle(byte value) {#setArmStyle-byte-}
```
public void setArmStyle(byte value)
```


Yazı tipinin kol stilini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **ArmStyle** (bölüm 2.1.3) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getLetterform() {#getLetterform--}
```
public byte getLetterform()
```


Yazı tipinin harf biçimini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Letterform** (bölüm 2.1.20) enumerasyon tablosunda olmalıdır

**Returns:**
byte
### setLetterform(byte value) {#setLetterform-byte-}
```
public void setLetterform(byte value)
```


Yazı tipinin harf biçimini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **Letterform** (bölüm 2.1.20) enumerasyon tablosunda olmalıdır

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getMidline() {#getMidline--}
```
public byte getMidline()
```


Yazı tipinin orta çizgisini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **MidLine** (bölüm 2.1.23) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setMidline(byte value) {#setMidline-byte-}
```
public void setMidline(byte value)
```


Yazı tipinin orta çizgisini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **MidLine** (bölüm 2.1.23) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

### getXHeight() {#getXHeight--}
```
public byte getXHeight()
```


Yazı tipinin x yüksekliğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **XHeight** (bölüm 2.1.35) enumerasyon tablosunda olmalıdır.

**Returns:**
byte
### setXHeight(byte value) {#setXHeight-byte-}
```
public void setXHeight(byte value)
```


Yazı tipinin x yüksekliğini belirten 8 bit işaretsiz tamsayıyı alır veya ayarlar. Değer **XHeight** (bölüm 2.1.35) enumerasyon tablosunda olmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | byte |  |

