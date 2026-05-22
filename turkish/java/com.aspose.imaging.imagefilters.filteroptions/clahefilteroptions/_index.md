---
title: "ClaheFilterOptions"
second_title: "Aspose.Imaging for Java API Referansı"
description: "Contrast-Limited Adaptive Histogram Equalization CLAHE filtresini yapılandırmak için seçenekler sağlar."
type: docs
weight: 14
url: /tr/java/com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.imagefilters.filteroptions.FilterOptionsBase](../../com.aspose.imaging.imagefilters.filteroptions/filteroptionsbase)
```
public class ClaheFilterOptions extends FilterOptionsBase
```

Kontrast Sınırlı Uyarlamalı Histogram Eşitleme (CLAHE) filtresini yapılandırmak için seçenekler sağlar.
## Yapıcılar

| Yapıcı | Açıklama |
| --- | --- |
| [ClaheFilterOptions()](#ClaheFilterOptions--) |  |
| [ClaheFilterOptions(boolean isGrayscale)](#ClaheFilterOptions-boolean-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)](#ClaheFilterOptions-boolean-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)](#ClaheFilterOptions-boolean-int-int-) |  |
| [ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)](#ClaheFilterOptions-boolean-int-int-double-) | Belirtilen parametrelerle [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) sınıfının yeni bir örneğini başlatır. |
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [isGrayscale()](#isGrayscale--) | Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değeri alır. |
| [getTilesNumberHorizontal()](#getTilesNumberHorizontal--) | Yatay yönde döşemelerin sayısını alır. |
| [getTilesNumberVertical()](#getTilesNumberVertical--) | Dikey yönde döşemelerin sayısını alır. |
| [getClipLimit()](#getClipLimit--) | Kontrast sınırlama eşiğini alır. |
### ClaheFilterOptions() {#ClaheFilterOptions--}
```
public ClaheFilterOptions()
```


### ClaheFilterOptions(boolean isGrayscale) {#ClaheFilterOptions-boolean-}
```
public ClaheFilterOptions(boolean isGrayscale)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isGrayscale | boolean |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal) {#ClaheFilterOptions-boolean-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical) {#ClaheFilterOptions-boolean-int-int-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical)
```


**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isGrayscale | boolean |  |
| tilesNumberHorizontal | int |  |
| tilesNumberVertical | int |  |

### ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit) {#ClaheFilterOptions-boolean-int-int-double-}
```
public ClaheFilterOptions(boolean isGrayscale, int tilesNumberHorizontal, int tilesNumberVertical, double clipLimit)
```


Belirtilen parametrelerle [ClaheFilterOptions](../../com.aspose.imaging.imagefilters.filteroptions/clahefilteroptions) sınıfının yeni bir örneğini başlatır.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| isGrayscale | boolean | Filtrenin gri tonlamalı modda çalışıp çalışmaması gerektiğini gösterir. |
| tilesNumberHorizontal | int | Yatayda döşeme sayısı. Varsayılan değer 8. |
| tilesNumberVertical | int | Dikeyde döşeme sayısı. Varsayılan değer 8. |
| clipLimit | double | Kontrast sınırlama eşiği. Varsayılan değer 4.0. |

### isGrayscale() {#isGrayscale--}
```
public final boolean isGrayscale()
```


Filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değeri alır.

**Returns:**
boolean - filtrenin gri tonlamalı modda çalışıp çalışmadığını gösteren bir değer.
### getTilesNumberHorizontal() {#getTilesNumberHorizontal--}
```
public final int getTilesNumberHorizontal()
```


Yatay yönde döşemelerin sayısını alır. Görüntünün yerel kontrast eşitlemesi için yatay olarak kaç bölgeye ayrıldığını belirler.

**Returns:**
int - yatay yönde döşemelerin sayısı.
### getTilesNumberVertical() {#getTilesNumberVertical--}
```
public final int getTilesNumberVertical()
```


Dikey yönde döşemelerin sayısını alır. Görüntünün yerel kontrast eşitlemesi için dikey olarak kaç bölgeye ayrıldığını belirler.

**Returns:**
int - dikey yönde döşemelerin sayısı.
### getClipLimit() {#getClipLimit--}
```
public final double getClipLimit()
```


Kontrast sınırlama eşiğini alır. Daha yüksek değerler daha fazla kontrast sağlar; daha düşük değerler gürültü yükselmesini önlemek için iyileştirmeyi sınırlar.

**Returns:**
double - kontrast sınırlama eşiği.
