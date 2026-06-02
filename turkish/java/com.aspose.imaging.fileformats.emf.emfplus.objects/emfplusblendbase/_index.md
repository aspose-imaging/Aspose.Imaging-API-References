---
title: "EmfPlusBlendBase"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Base object for blend objects"
type: docs
weight: 16
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public abstract class EmfPlusBlendBase extends EmfPlusStructureObjectType
```

Base object for blend objects
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusBlendBase()](#EmfPlusBlendBase--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getBlendPositions()](#getBlendPositions--) | Alır veya ayarlar karışım konumlarını, gradient çizgisi boyunca mesafenin oranlarını belirten PositionCount 32-bit kayan nokta değerlerinden oluşan bir dizi. |
| [setBlendPositions(float[] value)](#setBlendPositions-float---) | Alır veya ayarlar karışım konumlarını, gradient çizgisi boyunca mesafenin oranlarını belirten PositionCount 32-bit kayan nokta değerlerinden oluşan bir dizi. |
### EmfPlusBlendBase() {#EmfPlusBlendBase--}
```
public EmfPlusBlendBase()
```


### getBlendPositions() {#getBlendPositions--}
```
public float[] getBlendPositions()
```


Alır veya ayarlar karışım konumlarını, gradient çizgisi boyunca mesafenin oranlarını belirten PositionCount 32-bit kayan nokta değerlerinden oluşan bir dizi. Her öğe 0.0 ile 1.0 arasında (dahil) bir sayı OLMALIDIR. Doğrusal bir gradient fırçası için 0.0 başlangıç noktasını, 1.0 ise bitiş noktasını temsil eder. Yol gradient fırçası için 0.0 orta noktayı, 1.0 ise bir uç noktayı temsil eder.

**Returns:**
float[]
### setBlendPositions(float[] value) {#setBlendPositions-float---}
```
public void setBlendPositions(float[] value)
```


Alır veya ayarlar karışım konumlarını, gradient çizgisi boyunca mesafenin oranlarını belirten PositionCount 32-bit kayan nokta değerlerinden oluşan bir dizi. Her öğe 0.0 ile 1.0 arasında (dahil) bir sayı OLMALIDIR. Doğrusal bir gradient fırçası için 0.0 başlangıç noktasını, 1.0 ise bitiş noktasını temsil eder. Yol gradient fırçası için 0.0 orta noktayı, 1.0 ise bir uç noktayı temsil eder.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | float[] |  |

