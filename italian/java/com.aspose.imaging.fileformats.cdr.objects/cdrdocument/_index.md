---
title: "CdrDocument"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto radice cdr"
type: docs
weight: 17
url: /it/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

L'oggetto radice cdr
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getArrows()](#getArrows--) | Ottiene le frecce. |
| [getFills()](#getFills--) | Ottiene i riempimenti. |
| [getOutLines()](#getOutLines--) | Ottiene le linee esterne. |
| [getBmps()](#getBmps--) | Ottiene i BMP. |
| [getBmpMasks()](#getBmpMasks--) | Ottiene le maschere BMP. |
| [getFonts()](#getFonts--) | Ottiene i font. |
| [getStyles()](#getStyles--) | Ottiene gli stili. |
| [getTexts()](#getTexts--) | Ottiene i testi. |
| [getPatterns()](#getPatterns--) | Ottiene i motivi. |
| [getVectorPatterns()](#getVectorPatterns--) | Ottiene i motivi vettoriali. |
| [getPowerClips()](#getPowerClips--) | Ottiene i clip di potenza. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | I clip di potenza. |
| [getClipIds()](#getClipIds--) | Ottiene gli ID clip. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Imposta gli ID clip. |
| [getLastTextIndex()](#getLastTextIndex--) | Ottiene gli indici di testo. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Gli indici di testo. |
| [getVersion()](#getVersion--) | Ottiene la versione. |
| [setVersion(int value)](#setVersion-int-) | Imposta la versione. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Ottiene le frecce.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - le frecce.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Ottiene i riempimenti.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - le frecce.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Ottiene le linee esterne.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - le linee esterne.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Ottiene i BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - i BMP.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Ottiene le maschere BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - le maschere BMP.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Ottiene i font.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - i font.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Ottiene gli stili.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - gli stili.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Ottiene i testi.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Ottiene i motivi.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - i pattern.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Ottiene i motivi vettoriali.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - i pattern vettoriali.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Ottiene i clip di potenza.

Valore: I clip di potenza.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - i clip di potenza.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


I clip di potenza.

Valore: I clip di potenza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | i clip di potenza. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Ottiene gli ID clip.

Valore: Gli ID dei clip.

**Returns:**
java.util.List<java.lang.Short> - gli ID dei clip.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Imposta gli ID clip.

Valore: Gli ID dei clip.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | java.util.List<java.lang.Short> | gli ID dei clip. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Ottiene gli indici di testo.

Valore: Gli indici di testo.

**Returns:**
int - gli indici di testo.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Gli indici di testo.

Valore: Gli indici di testo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | gli indici di testo. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Ottiene la versione.

**Returns:**
int - la versione.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Imposta la versione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | la versione. |

