---
title: "EmfPlusTextureBrushData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusTextureBrushData nesnesi, bir grafik fırçası için doku görüntüsü belirtir."
type: docs
weight: 77
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

EmfPlusTextureBrushData nesnesi, bir grafik fırçası için doku görüntüsü belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. |
| [getWrapMode()](#getWrapMode--) | WrapMode sayımından (bölüm 2.1.1.34) 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer, görüntü doldurulan alanın boyutundan küçük olduğunda doku görüntüsünün bir şekil boyunca nasıl tekrarlanacağını belirtir. |
| [setWrapMode(int value)](#setWrapMode-int-) | WrapMode sayımından (bölüm 2.1.1.34) 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer, görüntü doldurulan alanın boyutundan küçük olduğunda doku görüntüsünün bir şekil boyunca nasıl tekrarlanacağını belirtir. |
| [getOptionalData()](#getOptionalData--) | Doku fırçası için ek veri belirten isteğe bağlı bir EmfPlusTextureBrushOptionalData nesnesini (bölüm 2.2.2.46) alır veya ayarlar. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Doku fırçası için ek veri belirten isteğe bağlı bir EmfPlusTextureBrushOptionalData nesnesini (bölüm 2.2.2.46) alır veya ayarlar. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. Aşağıdaki bayraklar bir doku fırçası için ilgilidir: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform.

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


OptionalData alanındaki veriyi belirten 32 bit işaretsiz tamsayıyı alır veya ayarlar. Bu değer BrushData bayraklarından (bölüm 2.1.2.1) oluşmalıdır. Aşağıdaki bayraklar bir doku fırçası için ilgilidir: BrushDataTransform, BrushDataIsGammaCorrected, BrushDataDoNotTransform.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


WrapMode sayımından (bölüm 2.1.1.34) 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer, görüntü doldurulan alanın boyutundan küçük olduğunda doku görüntüsünün bir şekil boyunca nasıl tekrarlanacağını belirtir.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


WrapMode sayımından (bölüm 2.1.1.34) 32 bit işaretli tamsayıyı alır veya ayarlar; bu değer, görüntü doldurulan alanın boyutundan küçük olduğunda doku görüntüsünün bir şekil boyunca nasıl tekrarlanacağını belirtir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Doku fırçası için ek veri belirten isteğe bağlı bir EmfPlusTextureBrushOptionalData nesnesini (bölüm 2.2.2.46) alır veya ayarlar. Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Doku fırçası için ek veri belirten isteğe bağlı bir EmfPlusTextureBrushOptionalData nesnesini (bölüm 2.2.2.46) alır veya ayarlar. Bu alanın belirli içeriği BrushDataFlags alanının değerine göre belirlenir.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

