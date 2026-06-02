---
title: "EmfPlusHatchBrushData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusHatchBrushData nesnesi, bir grafik fırçası için çapalama desenini belirtir."
type: docs
weight: 45
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

EmfPlusHatchBrushData nesnesi, bir grafik fırçası için çapalama desenini belirtir.

`EmfPlusBrush` nesneleri (bölüm 2.2.1.1) ile grafik fırçaları tanımlanır. Bir hatch fırçası arka planı boyar ve bu arka plan üzerine çizgi, nokta, tire, kare ve çapraz çizgi desenleri çizer. Hatch fırçası iki renk tanımlar: biri arka plan için, diğeri arka plan üzerindeki desen için. Arka plan rengine arka plan rengi, desenin rengine ise ön plan rengi denir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Hatch deseninin arka planını boyamak için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Hatch deseninin arka planını boyamak için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Hatch deseninin çizgilerini çizmek için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Hatch deseninin çizgilerini çizmek için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar. |
| [getHatchStyle()](#getHatchStyle--) | Fırça hatch stilini belirten 32-bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Fırça hatch stilini belirten 32-bitlik işaretsiz bir tam sayıyı alır veya ayarlar. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Hatch deseninin arka planını boyamak için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Hatch deseninin arka planını boyamak için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Hatch deseninin çizgilerini çizmek için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Hatch deseninin çizgilerini çizmek için kullanılan rengi belirten 32-bitlik bir EmfPlusArgb nesnesini alır veya ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Fırça hatch stilini belirten 32-bitlik işaretsiz bir tam sayıyı alır veya ayarlar. Bu, `EmfPlusHatchStyle` sayımında MUST tanımlanmalıdır.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Fırça hatch stilini belirten 32-bitlik işaretsiz bir tam sayıyı alır veya ayarlar. Bu, `EmfPlusHatchStyle` sayımında MUST tanımlanmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int |  |

