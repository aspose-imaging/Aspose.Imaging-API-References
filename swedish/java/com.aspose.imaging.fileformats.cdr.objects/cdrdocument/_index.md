---
title: "CdrDocument"
second_title: "Aspose.Imaging för Java API-referens"
description: "cdr‑rotobjektet"
type: docs
weight: 17
url: /sv/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

cdr‑rotobjektet
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [getArrows()](#getArrows--) | Hämtar pilarna. |
| [getFills()](#getFills--) | Hämtar fyllningarna. |
| [getOutLines()](#getOutLines--) | Hämtar konturerna. |
| [getBmps()](#getBmps--) | Hämtar BMP-filerna. |
| [getBmpMasks()](#getBmpMasks--) | Hämtar BMP-maskerna. |
| [getFonts()](#getFonts--) | Hämtar typsnitten. |
| [getStyles()](#getStyles--) | Hämtar stilarna. |
| [getTexts()](#getTexts--) | Hämtar texterna. |
| [getPatterns()](#getPatterns--) | Hämtar mönstren. |
| [getVectorPatterns()](#getVectorPatterns--) | Hämtar vektormönstren. |
| [getPowerClips()](#getPowerClips--) | Hämtar power-klippen. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Power-klippen. |
| [getClipIds()](#getClipIds--) | Hämtar klipp-ID:n. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Sätter klipp-ID:n. |
| [getLastTextIndex()](#getLastTextIndex--) | Hämtar textindexen. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Textindexen. |
| [getVersion()](#getVersion--) | Hämtar versionen. |
| [setVersion(int value)](#setVersion-int-) | Ställer in versionen. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Hämtar pilarna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - pilarna.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Hämtar fyllningarna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - pilarna.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Hämtar konturerna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - konturerna.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Hämtar BMP-filerna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP-filerna.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Hämtar BMP-maskerna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - BMP-maskerna.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Hämtar typsnitten.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - typsnitten.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Hämtar stilarna.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - stilarna.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Hämtar texterna.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Hämtar mönstren.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - mönstren.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Hämtar vektormönstren.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - vektormönstren.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Hämtar power-klippen.

Värde: Kraftklippen.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - kraftklippen.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Power-klippen.

Värde: Kraftklippen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | kraftklippen. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Hämtar klipp-ID:n.

Värde: Klipp-ID:n.

**Returns:**
java.util.List<java.lang.Short> - klipp-ID:n.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Sätter klipp-ID:n.

Värde: Klipp-ID:n.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | java.util.List<java.lang.Short> | klipp-ID:n. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Hämtar textindexen.

Värde: Textindexen.

**Returns:**
int - textindexen.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Textindexen.

Värde: Textindexen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | textindexen. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Hämtar versionen.

**Returns:**
int - versionen.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Ställer in versionen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde | int | versionen. |

