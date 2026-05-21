---
title: "CdrDocument"
second_title: "Referencia de la API de Aspose.Imaging para Java"
description: "El cdr root object"
type: docs
weight: 17
url: /es/java/com.aspose.imaging.fileformats.cdr.objects/cdrdocument/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.DisposableObject](../../com.aspose.imaging/disposableobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObject](../../com.aspose.imaging.fileformats.cdr.objects/cdrobject), [com.aspose.imaging.fileformats.cdr.objects.CdrObjectContainer](../../com.aspose.imaging.fileformats.cdr.objects/cdrobjectcontainer)
```
public class CdrDocument extends CdrObjectContainer
```

El cdr root object
## Métodos

| Método | Descripción |
| --- | --- |
| [getArrows()](#getArrows--) | Obtiene las flechas. |
| [getFills()](#getFills--) | Obtiene los rellenos. |
| [getOutLines()](#getOutLines--) | Obtiene los contornos. |
| [getBmps()](#getBmps--) | Obtiene los BMP. |
| [getBmpMasks()](#getBmpMasks--) | Obtiene las máscaras BMP. |
| [getFonts()](#getFonts--) | Obtiene las fuentes. |
| [getStyles()](#getStyles--) | Obtiene los estilos. |
| [getTexts()](#getTexts--) | Obtiene los textos. |
| [getPatterns()](#getPatterns--) | Obtiene los patrones. |
| [getVectorPatterns()](#getVectorPatterns--) | Obtiene los patrones vectoriales. |
| [getPowerClips()](#getPowerClips--) | Obtiene los clips de potencia. |
| [setPowerClips(SortedMap<Short,CdrListObjects> value)](#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--) | Los clips de potencia. |
| [getClipIds()](#getClipIds--) | Obtiene los IDs de recorte. |
| [setClipIds(List<Short> value)](#setClipIds-java.util.List-java.lang.Short--) | Establece los IDs de recorte. |
| [getLastTextIndex()](#getLastTextIndex--) | Obtiene los índices de texto. |
| [setLastTextIndex(int value)](#setLastTextIndex-int-) | Los índices de texto. |
| [getVersion()](#getVersion--) | Obtiene la versión. |
| [setVersion(int value)](#setVersion-int-) | Establece la versión. |
### getArrows() {#getArrows--}
```
public final IntObjDictionary<CdrArrow> getArrows()
```


Obtiene las flechas.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrArrow> - las flechas.
### getFills() {#getFills--}
```
public final IntObjDictionary<CdrFill> getFills()
```


Obtiene los rellenos.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFill> - las flechas.
### getOutLines() {#getOutLines--}
```
public final IntObjDictionary<CdrOutline> getOutLines()
```


Obtiene los contornos.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrOutline> - los contornos.
### getBmps() {#getBmps--}
```
public final IntObjDictionary<CdrBmp> getBmps()
```


Obtiene los BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - los BMP.
### getBmpMasks() {#getBmpMasks--}
```
public final IntObjDictionary<CdrBmp> getBmpMasks()
```


Obtiene las máscaras BMP.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrBmp> - las máscaras BMP.
### getFonts() {#getFonts--}
```
public final IntObjDictionary<CdrFont> getFonts()
```


Obtiene las fuentes.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrFont> - las fuentes.
### getStyles() {#getStyles--}
```
public final IntObjDictionary<CdrStyle> getStyles()
```


Obtiene los estilos.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrStyle> - los estilos.
### getTexts() {#getTexts--}
```
public final CdrTextCollection getTexts()
```


Obtiene los textos.

**Returns:**
[CdrTextCollection](../../com.aspose.imaging.fileformats.cdr.types/cdrtextcollection) - the texts.
### getPatterns() {#getPatterns--}
```
public final IntObjDictionary<CdrPattern> getPatterns()
```


Obtiene los patrones.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrPattern> - los patrones.
### getVectorPatterns() {#getVectorPatterns--}
```
public final IntObjDictionary<CdrVectorPattern> getVectorPatterns()
```


Obtiene los patrones vectoriales.

**Returns:**
com.aspose.java.optimization.maps.IntObjDictionary<com.aspose.imaging.fileformats.cdr.objects.CdrVectorPattern> - los patrones vectoriales.
### getPowerClips() {#getPowerClips--}
```
public final SortedMap<Short,CdrListObjects> getPowerClips()
```


Obtiene los clips de potencia.

Valor: los clips de energía.

**Returns:**
java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> - los clips de energía.
### setPowerClips(SortedMap<Short,CdrListObjects> value) {#setPowerClips-java.util.SortedMap-java.lang.Short-com.aspose.imaging.fileformats.cdr.objects.CdrListObjects--}
```
public final void setPowerClips(SortedMap<Short,CdrListObjects> value)
```


Los clips de potencia.

Valor: los clips de energía.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.SortedMap<java.lang.Short,com.aspose.imaging.fileformats.cdr.objects.CdrListObjects> | los clips de energía. |

### getClipIds() {#getClipIds--}
```
public final List<Short> getClipIds()
```


Obtiene los IDs de recorte.

Valor: los IDs de clip.

**Returns:**
java.util.List<java.lang.Short> - los IDs de clip.
### setClipIds(List<Short> value) {#setClipIds-java.util.List-java.lang.Short--}
```
public final void setClipIds(List<Short> value)
```


Establece los IDs de recorte.

Valor: los IDs de clip.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | java.util.List<java.lang.Short> | los IDs de clip. |

### getLastTextIndex() {#getLastTextIndex--}
```
public final int getLastTextIndex()
```


Obtiene los índices de texto.

Valor: los índices de texto.

**Returns:**
int - los índices de texto.
### setLastTextIndex(int value) {#setLastTextIndex-int-}
```
public final void setLastTextIndex(int value)
```


Los índices de texto.

Valor: los índices de texto.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | los índices de texto. |

### getVersion() {#getVersion--}
```
public final int getVersion()
```


Obtiene la versión.

**Returns:**
int - la versión.
### setVersion(int value) {#setVersion-int-}
```
public final void setVersion(int value)
```


Establece la versión.

**Parameters:**
| Parámetro | Tipo | Descripción |
| --- | --- | --- |
| valor | int | la versión. |

