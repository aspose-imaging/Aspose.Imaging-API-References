---
title: "EmfPlusTextureBrushOptionalData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusTextureBrushOptionalData specifica dati opzionali per un pennello di texture."
type: docs
weight: 78
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusTextureBrushOptionalData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusTextureBrushOptionalData specifica dati opzionali per un pennello di texture.

Nota: ogni campo di questo oggetto è opzionale e potrebbe non essere presente nel campo OptionalData di un oggetto EmfPlusTextureBrushData (sezione 2.2.2.45), a seconda delle bandiere BrushData (sezione 2.1.2.1) impostate nel suo campo BrushDataFlags. Sebbene non sia pratico rappresentare ogni possibile combinazione di campi presenti o assenti, questa sezione specifica il loro ordine relativo nell'oggetto. L'implementatore è responsabile di determinare quali campi sono effettivamente presenti in un dato record metafile e di deserializzare i dati per i singoli campi separatamente e in modo appropriato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusTextureBrushOptionalData()](#EmfPlusTextureBrushOptionalData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getTransformMatrix()](#getTransformMatrix--) | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello texture. |
| [setTransformMatrix(Matrix value)](#setTransformMatrix-com.aspose.imaging.Matrix-) | Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello texture. |
| [getImageObject()](#getImageObject--) | Ottiene o imposta un oggetto EmfPlusImage opzionale (sezione 2.2.1.4) che specifica la texture del pennello. |
| [setImageObject(EmfPlusImage value)](#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-) | Ottiene o imposta un oggetto EmfPlusImage opzionale (sezione 2.2.1.4) che specifica la texture del pennello. |
### EmfPlusTextureBrushOptionalData() {#EmfPlusTextureBrushOptionalData--}
```
public EmfPlusTextureBrushOptionalData()
```


### getTransformMatrix() {#getTransformMatrix--}
```
public Matrix getTransformMatrix()
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello texture. Questo campo MUST essere presente se la bandiera BrushDataTransform è impostata nel campo BrushDataFlags dell'oggetto EmfPlusTextureBrushData.

**Returns:**
[Matrix](../../com.aspose.imaging/matrix)
### setTransformMatrix(Matrix value) {#setTransformMatrix-com.aspose.imaging.Matrix-}
```
public void setTransformMatrix(Matrix value)
```


Ottiene o imposta un oggetto EmfPlusTransformMatrix opzionale (sezione 2.2.2.47) che specifica una trasformazione dallo spazio mondo allo spazio dispositivo per il pennello texture. Questo campo MUST essere presente se la bandiera BrushDataTransform è impostata nel campo BrushDataFlags dell'oggetto EmfPlusTextureBrushData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Matrix](../../com.aspose.imaging/matrix) |  |

### getImageObject() {#getImageObject--}
```
public EmfPlusImage getImageObject()
```


Ottiene o imposta un oggetto EmfPlusImage opzionale (sezione 2.2.1.4) che specifica la texture del pennello. Questo campo MUST essere presente se la dimensione del record EmfPlusObject (sezione 2.3.5.1) che definisce questo pennello texture è sufficientemente grande da contenere un oggetto EmfPlusImage oltre ai campi obbligatori dell'oggetto EmfPlusTextureBrushData e, facoltativamente, un oggetto EmfPlusTransformMatrix.

**Returns:**
[EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)
### setImageObject(EmfPlusImage value) {#setImageObject-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImage-}
```
public void setImageObject(EmfPlusImage value)
```


Ottiene o imposta un oggetto EmfPlusImage opzionale (sezione 2.2.1.4) che specifica la texture del pennello. Questo campo MUST essere presente se la dimensione del record EmfPlusObject (sezione 2.3.5.1) che definisce questo pennello texture è sufficientemente grande da contenere un oggetto EmfPlusImage oltre ai campi obbligatori dell'oggetto EmfPlusTextureBrushData e, facoltativamente, un oggetto EmfPlusTransformMatrix.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) |  |

