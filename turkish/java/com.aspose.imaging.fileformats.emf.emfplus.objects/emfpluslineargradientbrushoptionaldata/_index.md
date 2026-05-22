---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Aspose.Imaging for Java API Referansı"
description: "EmfPlusLinearGradientBrushOptionalData nesnesi, doğrusal degrade fırçası için isteğe bağlı verileri belirtir."
type: docs
weight: 54
url: /tr/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

EmfPlusLinearGradientBrushOptionalData nesnesi, doğrusal degrade fırçası için isteğe bağlı verileri belirtir.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Doğrusal degrade fırçası için dünya uzayından cihaz uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Doğrusal degrade fırçası için dünya uzayından cihaz uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). |
| [getBlendPattern()](#getBlendPattern--) | Doğrusal degrade fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Doğrusal degrade fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Karışım desenini önceden ayarlanmış renkler olarak alır. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Karışım desenini yatay karışım faktörleri olarak alır. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Karışım desenini dikey karışım faktörleri olarak alır. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Doğrusal degrade fırçası için dünya uzayından cihaz uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). Bu alan, EmfPlusLinearGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa bulunmalıdır.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Doğrusal degrade fırçası için dünya uzayından cihaz uzayına dönüşümü belirten isteğe bağlı bir EmfPlusTransformMatrix nesnesini alır veya ayarlar (bölüm 2.2.2.47). Bu alan, EmfPlusLinearGradientBrushData nesnesinin BrushDataFlags alanında BrushDataTransform bayrağı ayarlıysa bulunmalıdır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Doğrusal degrade fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. Bu alan mevcutsa, bir EmfPlusBlendColors nesnesi (bölüm 2.2.2.4) ya da bir veya iki EmfPlusBlendFactors nesnesi (bölüm 2.2.2.5) içermelidir; ancak ikisini birden içeremez. Aşağıdaki tablo, EmfPlusLinearGradientBrushData BrushData bayrakları ile ilgili karışım desenlerinin geçerli kombinasyonlarını gösterir: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Doğrusal degrade fırçası için isteğe bağlı bir karışım desenini alır veya ayarlar. Bu alan mevcutsa, bir EmfPlusBlendColors nesnesi (bölüm 2.2.2.4) ya da bir veya iki EmfPlusBlendFactors nesnesi (bölüm 2.2.2.5) içermelidir; ancak ikisini birden içeremez. Aşağıdaki tablo, EmfPlusLinearGradientBrushData BrushData bayrakları ile ilgili karışım desenlerinin geçerli kombinasyonlarını gösterir: EmfPlusBlendFactors

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Karışım desenini önceden ayarlanmış renkler olarak alır.

Değer: Karışım deseni önceden ayarlanmış renkler olarak.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Karışım desenini yatay karışım faktörleri olarak alır.

Değer: Karışım deseni yatay karışım faktörleri olarak.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Karışım desenini dikey karışım faktörleri olarak alır.

Değer: Karışım deseni dikey karışım faktörleri olarak.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
