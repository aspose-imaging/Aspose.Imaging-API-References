---
title: "EmfPlusTextureBrushData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusTextureBrushData specifica un'immagine di texture per un pennello grafico."
type: docs
weight: 77
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusTextureBrushData extends EmfPlusBaseBrushData
```

L'oggetto EmfPlusTextureBrushData specifica un'immagine di texture per un pennello grafico.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusTextureBrushData()](#EmfPlusTextureBrushData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBrushDataFlags()](#getBrushDataFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [setBrushDataFlags(int value)](#setBrushDataFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [getWrapMode()](#getWrapMode--) | Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica come ripetere l'immagine texture su una forma, quando l'immagine è più piccola dell'area da riempire. |
| [setWrapMode(int value)](#setWrapMode-int-) | Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica come ripetere l'immagine texture su una forma, quando l'immagine è più piccola dell'area da riempire. |
| [getOptionalData()](#getOptionalData--) | Ottiene o imposta un oggetto opzionale EmfPlusTextureBrushOptionalData (sezione 2.2.2.46) che specifica dati aggiuntivi per il pennello texture. |
| [setOptionalData(EmfPlusTextureBrushOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-) | Ottiene o imposta un oggetto opzionale EmfPlusTextureBrushOptionalData (sezione 2.2.2.46) che specifica dati aggiuntivi per il pennello texture. |
### EmfPlusTextureBrushData() {#EmfPlusTextureBrushData--}
```
public EmfPlusTextureBrushData()
```


### getBrushDataFlags() {#getBrushDataFlags--}
```
public int getBrushDataFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto dai flag BrushData (sezione 2.1.2.1). I seguenti flag sono rilevanti per un pennello texture: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Returns:**
int
### setBrushDataFlags(int value) {#setBrushDataFlags-int-}
```
public void setBrushDataFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto dai flag BrushData (sezione 2.1.2.1). I seguenti flag sono rilevanti per un pennello texture: BrushDataTransform BrushDataIsGammaCorrected BrushDataDoNotTransform

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWrapMode() {#getWrapMode--}
```
public int getWrapMode()
```


Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica come ripetere l'immagine texture su una forma, quando l'immagine è più piccola dell'area da riempire.

**Returns:**
int
### setWrapMode(int value) {#setWrapMode-int-}
```
public void setWrapMode(int value)
```


Ottiene o imposta un intero con segno a 32 bit dall'enumerazione WrapMode (sezione 2.1.1.34) che specifica come ripetere l'immagine texture su una forma, quando l'immagine è più piccola dell'area da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusTextureBrushOptionalData getOptionalData()
```


Ottiene o imposta un oggetto opzionale EmfPlusTextureBrushOptionalData (sezione 2.2.2.46) che specifica dati aggiuntivi per il pennello texture. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags

**Returns:**
[EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata)
### setOptionalData(EmfPlusTextureBrushOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusTextureBrushOptionalData-}
```
public void setOptionalData(EmfPlusTextureBrushOptionalData value)
```


Ottiene o imposta un oggetto opzionale EmfPlusTextureBrushOptionalData (sezione 2.2.2.46) che specifica dati aggiuntivi per il pennello texture. Il contenuto specifico di questo campo è determinato dal valore del campo BrushDataFlags

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusTextureBrushOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplustexturebrushoptionaldata) |  |

