---
title: "EmfPlusLinearGradientBrushOptionalData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusLinearGradientBrushOptionalData specifica dati opzionali per un pennello a gradiente lineare."
type: docs
weight: 54
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluslineargradientbrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusLinearGradientBrushOptionalData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusLinearGradientBrushOptionalData specifica dati opzionali per un pennello a gradiente lineare.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusLinearGradientBrushOptionalData()](#EmfPlusLinearGradientBrushOptionalData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente lineare. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente lineare. |
| [getBlendPattern()](#getBlendPattern--) | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente lineare. |
| [setBlendPattern(EmfPlusBlendBase[] value)](#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---) | Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente lineare. |
| [getBlendPatternAsPresetColors()](#getBlendPatternAsPresetColors--) | Ottiene il modello di fusione come colori predefiniti. |
| [getBlendPatternAsBlendFactorsH()](#getBlendPatternAsBlendFactorsH--) | Ottiene il modello di fusione come fattori di fusione h. |
| [getBlendPatternAsBlendFactorsV()](#getBlendPatternAsBlendFactorsV--) | Ottiene il modello di fusione come fattori di fusione v. |
### EmfPlusLinearGradientBrushOptionalData() {#EmfPlusLinearGradientBrushOptionalData--}
```
public EmfPlusLinearGradientBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente lineare. Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel campo BrushDataFlags dell'oggetto EmfPlusLinearGradientBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Ottiene o imposta un oggetto opzionale EmfPlusTransformMatrix (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello a gradiente lineare. Questo campo DEVE essere presente se il flag BrushDataTransform è impostato nel campo BrushDataFlags dell'oggetto EmfPlusLinearGradientBrushData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getBlendPattern() {#getBlendPattern--}
```
public EmfPlusBlendBase[] getBlendPattern()
```


Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente lineare. Se questo campo è presente, DEVE contenere oppure un oggetto EmfPlusBlendColors (sezione 2.2.2.4), oppure uno o due oggetti EmfPlusBlendFactors (sezione 2.2.2.5), ma NON DEVE contenere entrambi. La tabella seguente mostra le combinazioni valide dei flag BrushData di EmfPlusLinearGradientBrushData e i corrispondenti modelli di fusione: EmfPlusBlendFactors

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase[]
### setBlendPattern(EmfPlusBlendBase[] value) {#setBlendPattern-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBlendBase---}
```
public void setBlendPattern(EmfPlusBlendBase[] value)
```


Ottiene o imposta un modello di fusione opzionale per il pennello a gradiente lineare. Se questo campo è presente, DEVE contenere oppure un oggetto EmfPlusBlendColors (sezione 2.2.2.4), oppure uno o due oggetti EmfPlusBlendFactors (sezione 2.2.2.5), ma NON DEVE contenere entrambi. La tabella seguente mostra le combinazioni valide dei flag BrushData di EmfPlusLinearGradientBrushData e i corrispondenti modelli di fusione: EmfPlusBlendFactors

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBlendBase\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendbase) |  |

### getBlendPatternAsPresetColors() {#getBlendPatternAsPresetColors--}
```
public EmfPlusBlendColors getBlendPatternAsPresetColors()
```


Ottiene il modello di fusione come colori predefiniti.

Valore: Il modello di fusione come colori predefiniti.

**Returns:**
[EmfPlusBlendColors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendcolors)
### getBlendPatternAsBlendFactorsH() {#getBlendPatternAsBlendFactorsH--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsH()
```


Ottiene il modello di fusione come fattori di fusione h.

Valore: Il modello di fusione come fattori di fusione h.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
### getBlendPatternAsBlendFactorsV() {#getBlendPatternAsBlendFactorsV--}
```
public EmfPlusBlendFactors getBlendPatternAsBlendFactorsV()
```


Ottiene il modello di fusione come fattori di fusione v.

Valore: Il modello di fusione come fattori di fusione v.

**Returns:**
[EmfPlusBlendFactors](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusblendfactors)
