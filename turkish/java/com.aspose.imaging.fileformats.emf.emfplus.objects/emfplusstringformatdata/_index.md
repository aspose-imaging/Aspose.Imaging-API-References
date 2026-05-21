---
title: "EmfPlusStringFormatData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusStringFormatData nesnesi, bir grafik dizesi için sekme duraklarını ve karakter konumlarını belirtir."
type: docs
weight: 75
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

EmfPlusStringFormatData nesnesi, bir grafik dizesi için sekme duraklarını ve karakter konumlarını belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTabStops()](#getTabStops--) | Alır veya ayarlar, bu nesne için isteğe bağlı sekme durak konumlarını belirten isteğe bağlı kayan nokta değerleri dizisini. |
| [setTabStops(float[] value)](#setTabStops-float---) | Alır veya ayarlar, bu nesne için isteğe bağlı sekme durak konumlarını belirten isteğe bağlı kayan nokta değerleri dizisini. |
| [getCharRange()](#getCharRange--) | Alır veya ayarlar, bir metin dizesi içindeki karakter konumlarının aralığını belirten isteğe bağlı RangeCount EmfPlusCharacterRange nesneleri dizisini. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Alır veya ayarlar, bir metin dizesi içindeki karakter konumlarının aralığını belirten isteğe bağlı RangeCount EmfPlusCharacterRange nesneleri dizisini. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Alır veya ayarlar, bu nesne için isteğe bağlı sekme durak konumlarını belirten isteğe bağlı kayan nokta değerleri dizisini. Her sekme durak değeri, sekme durakları arasındaki boşluk sayısını ya da ilk sekme durak için bir metin satırının başlangıcı ile ilk sekme durak arasındaki boşluk sayısını temsil eder. EmfPlusStringFormat nesnesindeki TabStopCount alanının değeri 0'dan büyükse bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Alır veya ayarlar, bu nesne için isteğe bağlı sekme durak konumlarını belirten isteğe bağlı kayan nokta değerleri dizisini. Her sekme durak değeri, sekme durakları arasındaki boşluk sayısını ya da ilk sekme durak için bir metin satırının başlangıcı ile ilk sekme durak arasındaki boşluk sayısını temsil eder. EmfPlusStringFormat nesnesindeki TabStopCount alanının değeri 0'dan büyükse bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Alır veya ayarlar, bir metin dizesi içindeki karakter konumlarının aralığını belirten isteğe bağlı RangeCount EmfPlusCharacterRange nesneleri dizisini. Sınırlayıcı bölge, karakter aralığıyla belirtilen karakter grubunun kapladığı ekran alanı ile tanımlanır. EmfPlusStringFormat nesnesindeki RangeCount alanının değeri 0'dan büyükse bu alan ZORUNLU olarak bulunmalıdır.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Alır veya ayarlar, bir metin dizesi içindeki karakter konumlarının aralığını belirten isteğe bağlı RangeCount EmfPlusCharacterRange nesneleri dizisini. Sınırlayıcı bölge, karakter aralığıyla belirtilen karakter grubunun kapladığı ekran alanı ile tanımlanır. EmfPlusStringFormat nesnesindeki RangeCount alanının değeri 0'dan büyükse bu alan ZORUNLU olarak bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

