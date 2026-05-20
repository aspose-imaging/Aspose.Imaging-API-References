---
title: "EmfPlusPathGradientBrushOptionalData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPathGradientBrushOptionalData specifica dati opzionali per un pennello a gradiente di percorso."
type: docs
weight: 60
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspathgradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPathGradientBrushOptionalData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusPathGradientBrushOptionalData specifica dati opzionali per un pennello a gradiente di percorso.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPathGradientBrushOptionalData()](#EmfPlusPathGradientBrushOptionalData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente di percorso. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente di percorso. |
| [getBlendPattern()](#getBlendPattern--) | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente di percorso. |
| [setBlendPattern(EmfPlusBlendBase value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-) | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente di percorso. |
| [getFocusScaleData()](#getFocusScaleData--) | Ottiene o imposta un oggetto EmfPlusFocusScaleData opzionale (sezione 2.2.2.18) che specifica le scale di messa a fuoco per il pennello a gradiente di percorso. |
| [setFocusScaleData(EmfPlusFocusScaleData value)](#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-) | Ottiene o imposta un oggetto EmfPlusFocusScaleData opzionale (sezione 2.2.2.18) che specifica le scale di messa a fuoco per il pennello a gradiente di percorso. |
### EmfPlusPathGradientBrushOptionalData() {#EmfPlusPathGradientBrushOptionalData--}
```
public EmfPlusPathGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente di percorso. Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel campo BrushDataFlags dell'oggetto EmfPlusPathGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente di percorso. Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel campo BrushDataFlags dell'oggetto EmfPlusPathGradientBrushData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase getBlendPattern()
```


Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente di percorso. Se questo campo è presente, DEVE contenere o un oggetto EmfPlusBlendColors (sezione 2.2.2.4) o un oggetto EmfPlusBlendFactors (sezione 2.2.2.5), ma NON DEVE contenere entrambi. La tabella seguente mostra le combinazioni valide dei flag BrushData di EmfPlusPathGradientBrushData e i relativi modelli di fusione:

**Returns:**
[EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase)
### setBlendPattern(EmfPlusBlendBase value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase-}
```
public void setBlendPattern(EmfPlusBlendBase value)
```


Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente di percorso. Se questo campo è presente, DEVE contenere o un oggetto EmfPlusBlendColors (sezione 2.2.2.4) o un oggetto EmfPlusBlendFactors (sezione 2.2.2.5), ma NON DEVE contenere entrambi. La tabella seguente mostra le combinazioni valide dei flag BrushData di EmfPlusPathGradientBrushData e i relativi modelli di fusione:

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBlendBase](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getFocusScaleData() {#getFocusScaleData--}
```
public EmfPlusFocusScaleData getFocusScaleData()
```


Ottiene o imposta un oggetto EmfPlusFocusScaleData opzionale (sezione 2.2.2.18) che specifica le scale di messa a fuoco per il pennello a gradiente di percorso. Questo campo DEVE essere presente se il flag BrushDataFocusScales è impostato nel campo BrushDataFlags dell'oggetto EmfPlusPathGradientBrushData.

**Returns:**
[EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata)
### setFocusScaleData(EmfPlusFocusScaleData value) {#setFocusScaleData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusFocusScaleData-}
```
public void setFocusScaleData(EmfPlusFocusScaleData value)
```


Ottiene o imposta un oggetto EmfPlusFocusScaleData opzionale (sezione 2.2.2.18) che specifica le scale di messa a fuoco per il pennello a gradiente di percorso. Questo campo DEVE essere presente se il flag BrushDataFocusScales è impostato nel campo BrushDataFlags dell'oggetto EmfPlusPathGradientBrushData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusFocusScaleData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusfocusscaledata) |  |

