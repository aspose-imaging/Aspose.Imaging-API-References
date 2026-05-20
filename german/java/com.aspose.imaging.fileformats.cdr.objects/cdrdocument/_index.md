---
title: "CdrDocument"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das cdr‑Root‑Objekt"
type: docs
weight: 17
url: /de/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

Das cdr‑Root‑Objekt
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getArrows()](#getArrows--) | Liefert die Pfeile. |
| [getFills()](#getFills--) | Liefert die Füllungen. |
| [getOutLines()](#getOutLines--) | Liefert die Konturlinien. |
| [getBmps()](#getBmps--) | Liefert die BMPs. |
| [getBmpMasks()](#getBmpMasks--) | Liefert die BMP-Masken. |
| [getFonts()](#getFonts--) | Liefert die Schriftarten. |
| [getStyles()](#getStyles--) | Liefert die Stile. |
| [getTexts()](#getTexts--) | Liefert die Texte. |
| [getPatterns()](#getPatterns--) | Liefert die Muster. |
| [getVectorPatterns()](#getVectorPatterns--) | Liefert die Vektormuster. |
| [getPowerClips()](#getPowerClips--) | Liefert die Power-Clips. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Die Power-Clips. |
| [getClipIds()](#getClipIds--) | Liefert die Clip-IDs. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Setzt die Clip-IDs. |
| [getLastTextIndex()](#getLastTextIndex--) | Liefert die Textindizes. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Die Textindizes. |
| [getVersion()](#getVersion--) | Liest die Version. |
| [setVersion(int value)](#setVersion-int-) | Setzt die Version. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Liefert die Pfeile.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - die Pfeile.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Liefert die Füllungen.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - die Pfeile.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Liefert die Konturlinien.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - die Konturlinien.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Liefert die BMPs.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - die BMPs.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Liefert die BMP-Masken.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - die BMP-Masken.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Liefert die Schriftarten.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - die Schriftarten.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Liefert die Stile.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - die Stile.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Liefert die Texte.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Liefert die Muster.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - die Muster.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Liefert die Vektormuster.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - die Vektormuster.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Liefert die Power-Clips.

Wert: Die Power-Clips.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - die Power-Clips.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Die Power-Clips.

Wert: Die Power-Clips.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | die Power-Clips. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Liefert die Clip-IDs.

Wert: Die Clip-IDs.

**Returns:**
java.util.List<java.lang.Short> - die Clip-IDs.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Setzt die Clip-IDs.

Wert: Die Clip-IDs.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | java.util.List<java.lang.Short> | die Clip-IDs. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Liefert die Textindizes.

Wert: Die Textindizes.

**Returns:**
int - die Textindizes.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Die Textindizes.

Wert: Die Textindizes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Textindizes. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Liest die Version.

**Returns:**
int - die Version.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Setzt die Version.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int | die Version. |

