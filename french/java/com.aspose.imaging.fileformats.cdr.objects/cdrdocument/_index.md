---
title: "CdrDocument"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'objet racine cdr"
type: docs
weight: 17
url: /fr/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

L'objet racine cdr
## Méthodes

| Méthode | Description |
| --- | --- |
| [getArrows()](#getArrows--) | Obtient les flèches. |
| [getFills()](#getFills--) | Obtient les remplissages. |
| [getOutLines()](#getOutLines--) | Obtient les contours. |
| [getBmps()](#getBmps--) | Obtient les BMP. |
| [getBmpMasks()](#getBmpMasks--) | Obtient les masques BMP. |
| [getFonts()](#getFonts--) | Obtient les polices. |
| [getStyles()](#getStyles--) | Obtient les styles. |
| [getTexts()](#getTexts--) | Obtient les textes. |
| [getPatterns()](#getPatterns--) | Obtient les motifs. |
| [getVectorPatterns()](#getVectorPatterns--) | Obtient les motifs vectoriels. |
| [getPowerClips()](#getPowerClips--) | Obtient les clips d'alimentation. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Les clips d'alimentation. |
| [getClipIds()](#getClipIds--) | Obtient les identifiants de clip. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Définit les identifiants de clip. |
| [getLastTextIndex()](#getLastTextIndex--) | Obtient les index de texte. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Les index de texte. |
| [getVersion()](#getVersion--) | Obtient la version. |
| [setVersion(int value)](#setVersion-int-) | Définit la version. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Obtient les flèches.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - les flèches.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Obtient les remplissages.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - les flèches.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Obtient les contours.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - les contours.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Obtient les BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - les BMP.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Obtient les masques BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - les masques BMP.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Obtient les polices.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - les polices.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Obtient les styles.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - les styles.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Obtient les textes.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Obtient les motifs.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - les motifs.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Obtient les motifs vectoriels.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - les motifs vectoriels.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Obtient les clips d'alimentation.

Valeur : les clips d'alimentation.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - les clips d'alimentation.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Les clips d'alimentation.

Valeur : les clips d'alimentation.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | les clips d'alimentation. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Obtient les identifiants de clip.

Valeur : les identifiants de clip.

**Returns:**
java.util.List<java.lang.Short> - les identifiants de clip.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Définit les identifiants de clip.

Valeur : les identifiants de clip.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | java.util.List<java.lang.Short> | les identifiants de clip. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Obtient les index de texte.

Valeur : les index de texte.

**Returns:**
int - les index de texte.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Les index de texte.

Valeur : les index de texte.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | les index de texte. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtient la version.

**Returns:**
int - la version.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Définit la version.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur | int | la version. |

