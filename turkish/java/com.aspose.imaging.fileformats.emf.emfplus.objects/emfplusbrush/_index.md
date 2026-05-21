---
title: "EmfPlusBrush"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusBrush nesnesi, bölgeleri doldurmak için bir grafik fırçasını belirtir."
type: docs
weight: 24
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbrush/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusBrush extends EmfPlusGraphicsObjectType
```

EmfPlusBrush nesnesi, bölgeleri doldurmak için bir grafik fırçasını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBrush()](#EmfPlusBrush--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBrushData()](#getBrushData--) | Fırça verilerini alır veya ayarlar. Tip alanında belirtilen fırça nesnesini tanımlayan değişken uzunlukta veri. |
| [setBrushData(EmfPlusBaseBrushData value)](#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-) | Fırça verilerini alır veya ayarlar. Tip alanında belirtilen fırça nesnesini tanımlayan değişken uzunlukta veri. |
| [getType()](#getType--) | Türü alır veya ayarlar. |
| [setType(int value)](#setType-int-) | Türü alır veya ayarlar. |
### EmfPlusBrush() {#EmfPlusBrush--}
```
public EmfPlusBrush()
```


### getBrushData() {#getBrushData--}
```
public EmfPlusBaseBrushData getBrushData()
```


Fırça verilerini alır veya ayarlar. Tip alanında belirtilen fırça nesnesini tanımlayan değişken uzunlukta veri. Verinin içeriği ve biçimi her fırça türü için farklı olabilir. EmfPlusHatchBrushData (bölüm 2.2.2.20) (tamam) EmfPlusLinearGradientBrushData nesnesi (bölüm 2.2.2.24) (tamam) EmfPlusPathGradientBrushData nesnesi (bölüm 2.2.2.29) (tamam) EmfPlusSolidBrushData nesnesi (bölüm 2.2.2.43) (tamam) EmfPlusTextureBrushData nesnesi (bölüm 2.2.2.45) (tamam)

Değer: Fırça verileri.

**Returns:**
[EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
### setBrushData(EmfPlusBaseBrushData value) {#setBrushData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData-}
```
public void setBrushData(EmfPlusBaseBrushData value)
```


Fırça verilerini alır veya ayarlar. Tip alanında belirtilen fırça nesnesini tanımlayan değişken uzunlukta veri. Verinin içeriği ve biçimi her fırça türü için farklı olabilir. EmfPlusHatchBrushData (bölüm 2.2.2.20) (tamam) EmfPlusLinearGradientBrushData nesnesi (bölüm 2.2.2.24) (tamam) EmfPlusPathGradientBrushData nesnesi (bölüm 2.2.2.29) (tamam) EmfPlusSolidBrushData nesnesi (bölüm 2.2.2.43) (tamam) EmfPlusTextureBrushData nesnesi (bölüm 2.2.2.45) (tamam)

Değer: Fırça verileri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata) |  |

### getType() {#getType--}
```
public int getType()
```


Türü alır veya ayarlar.

Değer: Fırça tipini belirten, BrushData alanının içeriğini belirleyen 32 bit işaretsiz tam sayı. Bu değer `EmfPlusBrushType` sayımında tanımlanmalıdır.

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Türü alır veya ayarlar.

Değer: Fırça tipini belirten, BrushData alanının içeriğini belirleyen 32 bit işaretsiz tam sayı. Bu değer `EmfPlusBrushType` sayımında tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

