---
title: "EmfPlusPenData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPenData nesnesi, bir grafik kalemin özelliklerini belirtir."
type: docs
weight: 64
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

EmfPlusPenData nesnesi, bir grafik kalemin özelliklerini belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getPenUnit()](#getPenUnit--) | Kalem için ölçü birimlerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setPenUnit(int value)](#setPenUnit-int-) | Kalem için ölçü birimlerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getPenWidth()](#getPenWidth--) | PenUnit alanında belirtilen birimlerde kalem tarafından çizilen çizginin genişliğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [setPenWidth(float value)](#setPenWidth-float-) | PenUnit alanında belirtilen birimlerde kalem tarafından çizilen çizginin genişliğini belirten 32 bit kayan nokta değerini alır veya ayarlar. |
| [getOptionalData()](#getOptionalData--) | Kalem nesnesi için ek verileri belirten isteğe bağlı EmfPlusPenOptionalData nesnesini (bölüm 2.2.2.34) alır veya ayarlar. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Kalem nesnesi için ek verileri belirten isteğe bağlı EmfPlusPenOptionalData nesnesini (bölüm 2.2.2.34) alır veya ayarlar. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer MUTLAKA PenData bayraklarından (bölüm 2.1.2.7) oluşmalıdır.

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer MUTLAKA PenData bayraklarından (bölüm 2.1.2.7) oluşmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Kalem için ölçü birimlerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer MUTLAKA UnitType enumarasyonundan (bölüm 2.1.1.33) gelmelidir.

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Kalem için ölçü birimlerini belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Değer MUTLAKA UnitType enumarasyonundan (bölüm 2.1.1.33) gelmelidir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


PenUnit alanında belirtilen birimlerde kalem tarafından çizilen çizginin genişliğini belirten 32 bit kayan nokta değerini alır veya ayarlar. Sıfır genişlik belirtilirse, birimlere göre belirlenen minimum değer kullanılır.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


PenUnit alanında belirtilen birimlerde kalem tarafından çizilen çizginin genişliğini belirten 32 bit kayan nokta değerini alır veya ayarlar. Sıfır genişlik belirtilirse, birimlere göre belirlenen minimum değer kullanılır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Kalem nesnesi için ek verileri belirten isteğe bağlı EmfPlusPenOptionalData nesnesini (bölüm 2.2.2.34) alır veya ayarlar. Bu alanın belirli içeriği PenDataFlags alanının değerine göre belirlenir.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Kalem nesnesi için ek verileri belirten isteğe bağlı EmfPlusPenOptionalData nesnesini (bölüm 2.2.2.34) alır veya ayarlar. Bu alanın belirli içeriği PenDataFlags alanının değerine göre belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

