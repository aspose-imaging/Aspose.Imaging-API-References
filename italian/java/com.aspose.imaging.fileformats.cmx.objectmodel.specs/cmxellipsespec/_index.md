---
title: "CmxEllipseSpec"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Rappresenta le informazioni geometriche specificate per un'ellisse."
type: docs
weight: 11
url: /it/java/com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
[com.aspose.imaging.fileformats.cmx.objectmodel.specs.ICmxObjectSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/icmxobjectspec)
```
public class CmxEllipseSpec implements ICmxObjectSpec
```

Rappresenta le informazioni geometriche specificate per un'ellisse.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [CmxEllipseSpec()](#CmxEllipseSpec--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getAngle1()](#getAngle1--) | Ottiene il primo angolo usato per definire il settore a torta. |
| [setAngle1(float value)](#setAngle1-float-) | Imposta il primo angolo usato per definire il settore a torta. |
| [getAngle2()](#getAngle2--) | Ottiene il secondo angolo usato per definire il settore a torta. |
| [setAngle2(float value)](#setAngle2-float-) | Imposta il secondo angolo usato per definire il settore a torta. |
| [getRotation()](#getRotation--) | Ottiene l'angolo di rotazione dell'ellisse. |
| [setRotation(float value)](#setRotation-float-) | Imposta l'angolo di rotazione dell'ellisse. |
| [getPie()](#getPie--) | Ottiene un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta. |
| [setPie(boolean value)](#setPie-boolean-) | Imposta un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta. |
| [getCenterX()](#getCenterX--) | Ottiene la coordinata X del centro del rettangolo. |
| [setCenterX(float value)](#setCenterX-float-) | Imposta la coordinata X del centro del rettangolo. |
| [getCenterY()](#getCenterY--) | Ottiene la coordinata Y del centro del rettangolo. |
| [setCenterY(float value)](#setCenterY-float-) | Imposta la coordinata Y del centro del rettangolo. |
| [getDiameterX()](#getDiameterX--) | Ottiene il diametro per la dimensione X del rettangolo. |
| [setDiameterX(float value)](#setDiameterX-float-) | Imposta il diametro per la dimensione X del rettangolo. |
| [getDiameterY()](#getDiameterY--) | Ottiene il diametro per la dimensione Y del rettangolo. |
| [setDiameterY(float value)](#setDiameterY-float-) | Imposta il diametro per la dimensione Y del rettangolo. |
| [getBoundingBox()](#getBoundingBox--) | Ottiene il riquadro di delimitazione. |
| [setBoundingBox(RectangleF value)](#setBoundingBox-com.aspose.imaging.RectangleF-) | Imposta il riquadro di delimitazione. |
| [toString()](#toString--) | Restituisce una String che rappresenta questa istanza. |
| [equals(Object o)](#equals-java.lang.Object-) | Verifica se gli oggetti sono uguali. |
| [hashCode()](#hashCode--) | Ottieni il codice hash dell'oggetto corrente. |
### CmxEllipseSpec() {#CmxEllipseSpec--}
```
public CmxEllipseSpec()
```


### getAngle1() {#getAngle1--}
```
public final float getAngle1()
```


Ottiene il primo angolo usato per definire il settore a torta. Non influisce se `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) è `false`. Misura in radianti.

**Returns:**
float - il primo angolo usato per definire il settore a torta.
### setAngle1(float value) {#setAngle1-float-}
```
public final void setAngle1(float value)
```


Imposta il primo angolo usato per definire il settore a torta. Non influisce se `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) è `false`. Misura in radianti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | il primo angolo usato per definire il settore della torta. |

### getAngle2() {#getAngle2--}
```
public final float getAngle2()
```


Ottiene il secondo angolo usato per definire il settore della torta. Non influisce se `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) è `false`. Misura in radianti.

**Returns:**
float - il secondo angolo usato per definire il settore della torta.
### setAngle2(float value) {#setAngle2-float-}
```
public final void setAngle2(float value)
```


Imposta il secondo angolo usato per definire il settore della torta. Non influisce se `Pie`(\#getPie.getPie/\#setPie(boolean).setPie(boolean)) è `false`. Misura in radianti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | il secondo angolo usato per definire il settore della torta. |

### getRotation() {#getRotation--}
```
public final float getRotation()
```


Ottiene l'angolo di rotazione dell'ellisse. Misura in radianti.

**Returns:**
float - l'angolo di rotazione dell'ellisse.
### setRotation(float value) {#setRotation-float-}
```
public final void setRotation(float value)
```


Imposta l'angolo di rotazione dell'ellisse. Misura in radianti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | l'angolo di rotazione dell'ellisse. |

### getPie() {#getPie--}
```
public final boolean getPie()
```


Ottiene un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta.

**Returns:**
boolean - un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta.
### setPie(boolean value) {#setPie-boolean-}
```
public final void setPie(boolean value)
```


Imposta un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | boolean | un valore che indica se questo [CmxEllipseSpec](../../com.aspose.imaging.fileformats.cmx.objectmodel.specs/cmxellipsespec) è una torta. |

### getCenterX() {#getCenterX--}
```
public final float getCenterX()
```


Ottiene la coordinata X del centro del rettangolo. Misura in unità di distanza comuni del documento.

**Returns:**
float - la coordinata X del centro del rettangolo.
### setCenterX(float value) {#setCenterX-float-}
```
public final void setCenterX(float value)
```


Imposta la coordinata X del centro del rettangolo. Misura in unità di distanza comuni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | la coordinata X del centro del rettangolo. |

### getCenterY() {#getCenterY--}
```
public final float getCenterY()
```


Ottiene la coordinata Y per il centro del rettangolo. Misura in unità di distanza comuni del documento.

**Returns:**
float - la coordinata Y per il centro del rettangolo.
### setCenterY(float value) {#setCenterY-float-}
```
public final void setCenterY(float value)
```


Imposta la coordinata Y per il centro del rettangolo. Misura in unità di distanza comuni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | la coordinata Y per il centro del rettangolo. |

### getDiameterX() {#getDiameterX--}
```
public final float getDiameterX()
```


Ottiene il diametro per la dimensione X del rettangolo. Misura in unità di distanza comuni del documento.

**Returns:**
float - il diametro per la dimensione X del rettangolo.
### setDiameterX(float value) {#setDiameterX-float-}
```
public final void setDiameterX(float value)
```


Imposta il diametro per la dimensione X del rettangolo. Misura in unità di distanza comuni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | il diametro per la dimensione X del rettangolo. |

### getDiameterY() {#getDiameterY--}
```
public final float getDiameterY()
```


Ottiene il diametro per la dimensione Y del rettangolo. Misura in unità di distanza comuni del documento.

**Returns:**
float - il diametro per la dimensione Y del rettangolo.
### setDiameterY(float value) {#setDiameterY-float-}
```
public final void setDiameterY(float value)
```


Imposta il diametro per la dimensione Y del rettangolo. Misura in unità di distanza comuni del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float | il diametro per la dimensione Y del rettangolo. |

### getBoundingBox() {#getBoundingBox--}
```
public final RectangleF getBoundingBox()
```


Ottiene il riquadro di delimitazione.

Valore: il riquadro di delimitazione.

**Returns:**
[RectangleF](../../com.aspose.imaging/rectanglef) - the bounding box.
### setBoundingBox(RectangleF value) {#setBoundingBox-com.aspose.imaging.RectangleF-}
```
public final void setBoundingBox(RectangleF value)
```


Imposta il riquadro di delimitazione.

Valore: il riquadro di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [RectangleF](../../com.aspose.imaging/rectanglef) | il riquadro di delimitazione. |

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
