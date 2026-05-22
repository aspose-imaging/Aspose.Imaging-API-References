---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusPathGradientBrushOptionalData nesnesi, yol degrade fırçası için isteğe bağlı verileri belirtir."
type: docs
weight: 60
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusPathGradientBrushOptionalData nesnesi, yol degrade fırçası için isteğe bağlı verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Yol gradyan fırçası için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Yol gradyan fırçası için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesi (bölüm 2.2.2.47) alır veya ayarlar. |
| [getBlendPattern()](#getBlendPattern--) | Yol gradyan fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Yol gradyan fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. |
| [getFocusScaleData()](#getFocusScaleData--) | Yol gradyan fırçası için odak ölçeklerini belirten isteğe bağlı bir EmfPlusFocusScaleData nesnesini (bölüm 2.2.2.18) alır veya ayarlar. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Yol gradyan fırçası için odak ölçeklerini belirten isteğe bağlı bir EmfPlusFocusScaleData nesnesini (bölüm 2.2.2.18) alır veya ayarlar. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Yol gradyan fırçası için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. Bu alan, EmfPlusPathGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa MUST bulunmalıdır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Yol gradyan fırçası için dünya uzayından aygıt uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini (bölüm 2.2.2.47) alır veya ayarlar. Bu alan, EmfPlusPathGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa MUST bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Yol gradyan fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. Bu alan mevcutsa, MUST bir EmfPlusBlendColors nesnesi (bölüm 2.2.2.4) ya da bir EmfPlusBlendFactors nesnesi (bölüm 2.2.2.5) içermelidir, ancak MUST her ikisini de içermez. Aşağıdaki tablo, EmfPlusPathGradientBrushData BrushData bayraklarının geçerli kombinasyonlarını ve karşılık gelen karışım desenlerini gösterir:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Yol gradyan fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. Bu alan mevcutsa, MUST bir EmfPlusBlendColors nesnesi (bölüm 2.2.2.4) ya da bir EmfPlusBlendFactors nesnesi (bölüm 2.2.2.5) içermelidir, ancak MUST her ikisini de içermez. Aşağıdaki tablo, EmfPlusPathGradientBrushData BrushData bayraklarının geçerli kombinasyonlarını ve karşılık gelen karışım desenlerini gösterir:

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Yol gradyan fırçası için odak ölçeklerini belirten isteğe bağlı bir EmfPlusFocusScaleData nesnesini (bölüm 2.2.2.18) alır veya ayarlar. Bu alan, EmfPlusPathGradientBrushData nesnesinin BrushDataFlags alanında BrushDataFocusScales bayrağı ayarlıysa MUST bulunmalıdır.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Yol gradyan fırçası için odak ölçeklerini belirten isteğe bağlı bir EmfPlusFocusScaleData nesnesini (bölüm 2.2.2.18) alır veya ayarlar. Bu alan, EmfPlusPathGradientBrushData nesnesinin BrushDataFlags alanında BrushDataFocusScales bayrağı ayarlıysa MUST bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

