---
title: "CmxImageFill"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Informazioni sul riempimento dell'immagine"
type: docs
weight: 13
url: /it/java/com.aspose.imaging.fileformats.cmx.objectmodel.styles/cmximagefill/
---
**Inheritance:**
java.lang.Object
```
public class CmxImageFill
```

Informazioni sul riempimento dell'immagine
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmxImageFill()](#CmxImageFill--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImages()](#getImages--) | Ottiene le immagini. |
| [setImages(CmxRasterImage[] value)](#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---) | Imposta le immagini. |
| [getProcedure()](#getProcedure--) | Ottiene la procedura. |
| [setProcedure(CmxProcedure value)](#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-) | Imposta la procedura. |
| [getTileOffsetX()](#getTileOffsetX--) | Ottiene l'offset della tessera X. |
| [setTileOffsetX(float value)](#setTileOffsetX-float-) | Imposta l'offset della tessera X. |
| [getTileOffsetY()](#getTileOffsetY--) | Ottiene l'offset della tessera Y. |
| [setTileOffsetY(float value)](#setTileOffsetY-float-) | Imposta l'offset della tessera Y. |
| [getRcpOffset()](#getRcpOffset--) | Ottiene l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [setRcpOffset(float value)](#setRcpOffset-float-) | Imposta l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |
| [getOffsetType()](#getOffsetType--) | Ottiene il tipo di offset tra le tessere adiacenti. |
| [setOffsetType(int value)](#setOffsetType-int-) | Imposta il tipo di offset tra le tessere adiacenti. |
| [getPatternWidth()](#getPatternWidth--) | Ottiene la larghezza del modello. |
| [setPatternWidth(float value)](#setPatternWidth-float-) | Imposta la larghezza del modello. |
| [getPatternHeight()](#getPatternHeight--) | Ottiene l'altezza del modello. |
| [setPatternHeight(float value)](#setPatternHeight-float-) | Imposta l'altezza del modello. |
| [isRelative()](#isRelative--) | Ottiene un valore che indica se i valori di dimensione dei pattern sono relativi. |
| [setRelative(boolean value)](#setRelative-boolean-) | Imposta un valore che indica se i valori di dimensione dei pattern sono relativi. |
| [getRotate180()](#getRotate180--) | Ottiene un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto. |
| [setRotate180(boolean value)](#setRotate180-boolean-) | Imposta un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### CmxImageFill() {#CmxImageFill--}
```
public CmxImageFill()
```


### getImages() {#getImages--}
```
public final CmxRasterImage[] getImages()
```


Ottiene le immagini.

**Returns:**
com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage[] - le immagini.
### setImages(CmxRasterImage[] value) {#setImages-com.aspose.imaging.fileformats.cmx.objectmodel.specs.CmxRasterImage---}
```
public final void setImages(CmxRasterImage[] value)
```


Imposta le immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CmxRasterImage\[\]](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxrasterimage) | le immagini. |

### getProcedure() {#getProcedure--}
```
public final CmxProcedure getProcedure()
```


Ottiene la procedura.

**Returns:**
[CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) - the procedure.
### setProcedure(CmxProcedure value) {#setProcedure-com.aspose.imaging.fileformats.cmx.objectmodel.CmxProcedure-}
```
public final void setProcedure(CmxProcedure value)
```


Imposta la procedura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [CmxProcedure](../../com.aspose.imaging.fileformats.cmx.objectmodel/cmxprocedure) | la procedura. |

### getTileOffsetX() {#getTileOffsetX--}
```
public final float getTileOffsetX()
```


Ottiene l'offset della tessera X.

**Returns:**
float - l'offset della tessera X.
### setTileOffsetX(float value) {#setTileOffsetX-float-}
```
public final void setTileOffsetX(float value)
```


Imposta l'offset della tessera X.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'offset della tessera X. |

### getTileOffsetY() {#getTileOffsetY--}
```
public final float getTileOffsetY()
```


Ottiene l'offset della tessera Y.

**Returns:**
float - l'offset della tessera Y.
### setTileOffsetY(float value) {#setTileOffsetY-float-}
```
public final void setTileOffsetY(float value)
```


Imposta l'offset della tessera Y.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'offset della tessera Y. |

### getRcpOffset() {#getRcpOffset--}
```
public final float getRcpOffset()
```


Ottiene l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). La dimensione è una frazione dell'altezza o della larghezza.

**Returns:**
float - l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))).
### setRcpOffset(float value) {#setRcpOffset-float-}
```
public final void setRcpOffset(float value)
```


Imposta l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). La dimensione è una frazione dell'altezza o della larghezza.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'offset relativo tra le righe o le colonne delle tessere (dipende da `OffsetType`(\#getOffsetType.getOffsetType/\#setOffsetType(int).setOffsetType(int))). |

### getOffsetType() {#getOffsetType--}
```
public final int getOffsetType()
```


Ottiene il tipo di offset tra le tessere adiacenti.

**Returns:**
int - il tipo di offset tra tessere adiacenti.
### setOffsetType(int value) {#setOffsetType-int-}
```
public final void setOffsetType(int value)
```


Imposta il tipo di offset tra le tessere adiacenti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int | il tipo di offset tra tessere adiacenti. |

### getPatternWidth() {#getPatternWidth--}
```
public final float getPatternWidth()
```


Ottiene la larghezza del pattern. Utilizza l'unità di misura di distanza comune del documento nel caso in cui `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sia `false`, altrimenti ha la dimensione della frazione della larghezza in pixel dell'immagine.

**Returns:**
float - la larghezza del pattern.
### setPatternWidth(float value) {#setPatternWidth-float-}
```
public final void setPatternWidth(float value)
```


Imposta la larghezza del pattern. Utilizza l'unità di misura di distanza comune del documento nel caso in cui `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sia `false`, altrimenti ha la dimensione della frazione della larghezza in pixel dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | la larghezza del pattern. |

### getPatternHeight() {#getPatternHeight--}
```
public final float getPatternHeight()
```


Ottiene l'altezza del pattern. Utilizza l'unità di misura di distanza comune del documento nel caso in cui `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sia `false`, altrimenti ha la dimensione della frazione dell'altezza in pixel dell'immagine.

**Returns:**
float - l'altezza del pattern.
### setPatternHeight(float value) {#setPatternHeight-float-}
```
public final void setPatternHeight(float value)
```


Imposta l'altezza del pattern. Utilizza l'unità di misura di distanza comune del documento nel caso in cui `IsRelative`(\#isRelative.isRelative/\#setRelative(boolean).setRelative(boolean)) sia `false`, altrimenti ha la dimensione della frazione dell'altezza in pixel dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'altezza del pattern. |

### isRelative() {#isRelative--}
```
public final boolean isRelative()
```


Ottiene un valore che indica se i valori di dimensione dei pattern sono relativi.

**Returns:**
boolean
### setRelative(boolean value) {#setRelative-boolean-}
```
public final void setRelative(boolean value)
```


Imposta un valore che indica se i valori di dimensione dei pattern sono relativi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | boolean |  |

### getRotate180() {#getRotate180--}
```
public final boolean getRotate180()
```


Ottiene un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto.

Valore: `true` se l'immagine è capovolta; altrimenti, `false`.

**Returns:**
boolean - un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto.
### setRotate180(boolean value) {#setRotate180-boolean-}
```
public final void setRotate180(boolean value)
```


Imposta un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto.

Valore: `true` se l'immagine è capovolta; altrimenti, `false`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se questo [CmxImageSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmximagespec) è capovolto. |

### toString() {#toString--}
```
public String toString()
```


Restituisce una String che rappresenta questa istanza.

**Returns:**
java.lang.String - Una stringa che rappresenta questa istanza.
### equals(Object o) {#equals-java.lang.Object-}
```
public boolean equals(Object o)
```


Verifica se gli oggetti sono uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| o | java.lang.Object | L'altro oggetto. |

**Returns:**
boolean - Il risultato del confronto di uguaglianza.
### hashCode() {#hashCode--}
```
public int hashCode()
```


Ottieni il codice hash dell'oggetto corrente.

**Returns:**
int - Il codice hash.
