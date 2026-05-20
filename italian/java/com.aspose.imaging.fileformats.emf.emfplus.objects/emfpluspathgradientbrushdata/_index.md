---
title: "EmfPlusPathGradientBrushData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPathGradientBrushData specifica un gradiente di percorso per un pennello grafico."
type: docs
weight: 59
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusPathGradientBrushData extends EmfPlusBaseBrushData
```

L'oggetto EmfPlusPathGradientBrushData specifica un gradiente di percorso per un pennello grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPathGradientBrushData()](#EmfPlusPathGradientBrushData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta un intero con segno a 32 bit dell'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del confine del pennello. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta un intero con segno a 32 bit dell'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del confine del pennello. |
| [getCenterArgb32Color()](#getCenterArgb32Color--) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. |
| [setCenterArgb32Color(int value)](#setCenterArgb32Color-int-) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. |
| [getCenterPointF()](#getCenterPointF--) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. |
| [setCenterPointF(PointF value)](#setCenterPointF-com.aspose.imaging.PointF-) | Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. |
| [getSurroundingArgb32Colors()](#getSurroundingArgb32Colors--) | Ottiene o imposta un array di oggetti SurroundingColorCount EmfPlusARGB che specificano i colori per i punti discreti sul bordo del pennello. |
| [setSurroundingArgb32Colors(int[] value)](#setSurroundingArgb32Colors-int---) | Ottiene o imposta un array di oggetti SurroundingColorCount EmfPlusARGB che specificano i colori per i punti discreti sul bordo del pennello. |
| [getBoundaryData()](#getBoundaryData--) | Ottiene o imposta il contorno del pennello gradiente di percorso, che è specificato da un percorso o da una spline cardinale chiusa. |
| [setBoundaryData(EmfPlusBoundaryBase value)](#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-) | Ottiene o imposta il contorno del pennello gradiente di percorso, che è specificato da un percorso o da una spline cardinale chiusa. |
| [getOptionalData()](#getOptionalData--) | Ottiene o imposta un oggetto opzionale EmfPlusPathGradientBrushOptionalData (sezione 2.2.2.30) che specifica dati aggiuntivi per il pennello gradiente di percorso. |
| [setOptionalData(EmfPlusPathGradientBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-) | Ottiene o imposta un oggetto opzionale EmfPlusPathGradientBrushOptionalData (sezione 2.2.2.30) che specifica dati aggiuntivi per il pennello gradiente di percorso. |
### EmfPlusPathGradientBrushData() {#EmfPlusPathGradientBrushData--}
```
public EmfPlusPathGradientBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto da flag BrushData (sezione 2.1.2.1). I seguenti flag sono rilevanti per un pennello gradiente di percorso:

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto da flag BrushData (sezione 2.1.2.1). I seguenti flag sono rilevanti per un pennello gradiente di percorso:

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del contorno del pennello. Quando si dipinge al di fuori del contorno, la modalità di avvolgimento specifica come il gradiente di colore viene ripetuto

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica se dipingere l'area al di fuori del contorno del pennello. Quando si dipinge al di fuori del contorno, la modalità di avvolgimento specifica come il gradiente di colore viene ripetuto

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCenterArgb32Color() {#getCenterArgb32Color--}
```
public int getCenterArgb32Color()
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. Il colore del pennello cambia gradualmente dal colore del contorno al colore centrale man mano che si sposta dal contorno al punto centrale.

**Returns:**
int
### setCenterArgb32Color(int value) {#setCenterArgb32Color-int-}
```
public void setCenterArgb32Color(int value)
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. Il colore del pennello cambia gradualmente dal colore del contorno al colore centrale man mano che si sposta dal contorno al punto centrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getCenterPointF() {#getCenterPointF--}
```
public PointF getCenterPointF()
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. Il colore del pennello cambia gradualmente dal colore del contorno al colore centrale man mano che si sposta dal contorno al punto centrale.

**Returns:**
[PointF](../../com.aspose.imaging/pointf)
### setCenterPointF(PointF value) {#setCenterPointF-com.aspose.imaging.PointF-}
```
public void setCenterPointF(PointF value)
```


Ottiene o imposta l'oggetto EmfPlusARGB (sezione 2.2.2.1) che specifica il colore centrale del pennello gradiente di percorso, che è il colore che appare nel punto centrale del pennello. Il colore del pennello cambia gradualmente dal colore del contorno al colore centrale man mano che si sposta dal contorno al punto centrale.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [PointF](../../com.aspose.imaging/pointf) |  |

### getSurroundingArgb32Colors() {#getSurroundingArgb32Colors--}
```
public int[] getSurroundingArgb32Colors()
```


Ottiene o imposta un array di oggetti SurroundingColorCount EmfPlusARGB che specificano i colori per i punti discreti sul bordo del pennello.

**Returns:**
int[]
### setSurroundingArgb32Colors(int[] value) {#setSurroundingArgb32Colors-int---}
```
public void setSurroundingArgb32Colors(int[] value)
```


Ottiene o imposta un array di oggetti SurroundingColorCount EmfPlusARGB che specificano i colori per i punti discreti sul bordo del pennello.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int[] |  |

### getBoundaryData() {#getBoundaryData--}
```
public EmfPlusBoundaryBase getBoundaryData()
```


Ottiene o imposta il contorno del pennello gradiente di percorso, che è specificato da un percorso o da una spline cardinale chiusa. Se il flag BrushDataPath è impostato nel campo BrushDataFlags, questo campo DEVE contenere un oggetto EmfPlusBoundaryPathData (sezione 2.2.2.6); altrimenti, questo campo DEVE contenere un oggetto EmfPlusBoundaryPointData (sezione 2.2.2.7).

**Returns:**
[EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase)
### setBoundaryData(EmfPlusBoundaryBase value) {#setBoundaryData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBoundaryBase-}
```
public void setBoundaryData(EmfPlusBoundaryBase value)
```


Ottiene o imposta il contorno del pennello gradiente di percorso, che è specificato da un percorso o da una spline cardinale chiusa. Se il flag BrushDataPath è impostato nel campo BrushDataFlags, questo campo DEVE contenere un oggetto EmfPlusBoundaryPathData (sezione 2.2.2.6); altrimenti, questo campo DEVE contenere un oggetto EmfPlusBoundaryPointData (sezione 2.2.2.7).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBoundaryBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusboundarybase) |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData getOptionalData()
```


Ottiene o imposta un oggetto opzionale EmfPlusPathGradientBrushOptionalData (sezione 2.2.2.30) che specifica dati aggiuntivi per il pennello gradiente di percorso. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags.

**Returns:**
[EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata)
### setOptionalData(EmfPlusPathGradientBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPathGradientBrushOptionalData-}
```
public void setOptionalData(EmfPlusPathGradientBrushOptionalData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusPathGradientBrushOptionalData (sezione 2.2.2.30) che specifica dati aggiuntivi per il pennello gradiente di percorso. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusPathGradientBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata) |  |

