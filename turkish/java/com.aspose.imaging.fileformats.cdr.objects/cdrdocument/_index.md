---
title: "CdrDocument"
second_title: "Aspose.Imaging for Java API Referansı"
description: "cdr kök nesnesi"
type: docs
weight: 17
url: /tr/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

cdr kök nesnesi
## Yöntemler

| Yöntem | Açıklama |
| --- | --- |
| [getArrows()](#getArrows--) | Okları alır. |
| [getFills()](#getFills--) | Dolgu öğelerini alır. |
| [getOutLines()](#getOutLines--) | Dış hatları alır. |
| [getBmps()](#getBmps--) | BMP'leri alır. |
| [getBmpMasks()](#getBmpMasks--) | BMP maskelerini alır. |
| [getFonts()](#getFonts--) | Yazı tiplerini alır. |
| [getStyles()](#getStyles--) | Stilleri alır. |
| [getTexts()](#getTexts--) | Metinleri alır. |
| [getPatterns()](#getPatterns--) | Desenleri alır. |
| [getVectorPatterns()](#getVectorPatterns--) | Vektör desenlerini alır. |
| [getPowerClips()](#getPowerClips--) | Güç kliplerini alır. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Güç klipleri. |
| [getClipIds()](#getClipIds--) | Klip kimliklerini alır. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Klip kimliklerini ayarlar. |
| [getLastTextIndex()](#getLastTextIndex--) | Metin indekslerini alır. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Metin indeksleri. |
| [getVersion()](#getVersion--) | Sürümü alır. |
| [setVersion(int value)](#setVersion-int-) | Sürümü ayarlar. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Okları alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - okları.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Dolgu öğelerini alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - okları.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Dış hatları alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - dış hatları.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


BMP'leri alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP'leri.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


BMP maskelerini alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP maskelerini.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Yazı tiplerini alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - yazı tiplerini.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Stilleri alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - stiller.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Metinleri alır.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Desenleri alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - desenler.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Vektör desenlerini alır.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - vektör desenleri.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Güç kliplerini alır.

Değer: Güç klipleri.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - güç klipleri.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Güç klipleri.

Değer: Güç klipleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | güç klipleri. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Klip kimliklerini alır.

Değer: Klip kimlikleri.

**Returns:**
java.util.List<java.lang.Short> - klip kimlikleri.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Klip kimliklerini ayarlar.

Değer: Klip kimlikleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | java.util.List<java.lang.Short> | klip kimlikleri. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Metin indekslerini alır.

Değer: Metin indeksleri.

**Returns:**
int - metin indeksleri.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Metin indeksleri.

Değer: Metin indeksleri.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | metin indeksleri. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Sürümü alır.

**Returns:**
int - sürüm.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Sürümü ayarlar.

**Parameters:**
| Parametre | Tür | Açıklama |
| --- | --- | --- |
| değer | int | sürüm. |

