---
title: "EmfPlusImage"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusImage specifica un'immagine grafica sotto forma di bitmap o metafile."
type: docs
weight: 47
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusGraphicsObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsobjecttype)
```
public final class EmfPlusImage extends EmfPlusGraphicsObjectType
```

L'oggetto EmfPlusImage specifica un'immagine grafica sotto forma di bitmap o metafile.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusImage()](#EmfPlusImage--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getImageData()](#getImageData--) | Ottiene o imposta i dati immagine di lunghezza variabile che definiscono i dati immagine specificati nel campo Type. |
| [setImageData(EmfPlusBaseImageData value)](#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-) | Ottiene o imposta i dati immagine di lunghezza variabile che definiscono i dati immagine specificati nel campo Type. |
| [getType()](#getType--) | Ottiene o imposta il tipo di immagine, un intero senza segno a 32 bit che specifica il tipo di dati nel campo ImageData. |
| [setType(int value)](#setType-int-) | Ottiene o imposta il tipo di immagine, un intero senza segno a 32 bit che specifica il tipo di dati nel campo ImageData. |
### EmfPlusImage() {#EmfPlusImage--}
```
public EmfPlusImage()
```


### getImageData() {#getImageData--}
```
public EmfPlusBaseImageData getImageData()
```


Ottiene o imposta i dati immagine di lunghezza variabile che definiscono i dati immagine specificati nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di immagine.

**Returns:**
[EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
### setImageData(EmfPlusBaseImageData value) {#setImageData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData-}
```
public void setImageData(EmfPlusBaseImageData value)
```


Ottiene o imposta i dati immagine di lunghezza variabile che definiscono i dati immagine specificati nel campo Type. Il contenuto e il formato dei dati possono variare per ogni tipo di immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata) |  |

### getType() {#getType--}
```
public int getType()
```


Ottiene o imposta il tipo immagine, un intero senza segno a 32 bit che specifica il tipo di dati nel campo ImageData. Questo valore DEVE essere definito nell'enumerazione ImageDataType (sezione 2.1.1.15).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ottiene o imposta il tipo immagine, un intero senza segno a 32 bit che specifica il tipo di dati nel campo ImageData. Questo valore DEVE essere definito nell'enumerazione ImageDataType (sezione 2.1.1.15).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

