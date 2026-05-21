---
title: "EmfPlusMetafile"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusMetafileData specifica un metafile che contiene un'immagine grafica"
type: docs
weight: 55
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseImageData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbaseimagedata)
```
public final class EmfPlusMetafile extends EmfPlusBaseImageData
```

L'oggetto EmfPlusMetafileData specifica un metafile che contiene un'immagine grafica
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusMetafile()](#EmfPlusMetafile--) | Inizializza una nuova istanza della classe `EmfPlusMetafile`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getType()](#getType--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di metafile incorporato nel campo MetafileData. |
| [setType(int value)](#setType-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di metafile incorporato nel campo MetafileData. |
| [getMetafileDataSize()](#getMetafileDataSize--) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte dei dati del metafile nel campo MetafileData. |
| [setMetafileDataSize(int value)](#setMetafileDataSize-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte dei dati del metafile nel campo MetafileData. |
| [getMetafileData()](#getMetafileData--) | Ottiene o imposta dati di lunghezza variabile che specificano il metafile incorporato. |
| [setMetafileData(byte[] value)](#setMetafileData-byte---) | Ottiene o imposta dati di lunghezza variabile che specificano il metafile incorporato. |
### EmfPlusMetafile() {#EmfPlusMetafile--}
```
public EmfPlusMetafile()
```


Inizializza una nuova istanza della classe `EmfPlusMetafile`.

### getType() {#getType--}
```
public int getType()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di metafile incorporato nel campo MetafileData. Questo valore MUST be defined in the MetafileDataType enumeration (sezione 2.1.1.21).

**Returns:**
int
### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il tipo di metafile incorporato nel campo MetafileData. Questo valore MUST be defined in the MetafileDataType enumeration (sezione 2.1.1.21).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMetafileDataSize() {#getMetafileDataSize--}
```
public int getMetafileDataSize()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte dei dati del metafile nel campo MetafileData.

**Returns:**
int
### setMetafileDataSize(int value) {#setMetafileDataSize-int-}
```
public void setMetafileDataSize(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica la dimensione in byte dei dati del metafile nel campo MetafileData.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getMetafileData() {#getMetafileData--}
```
public byte[] getMetafileData()
```


Ottiene o imposta dati di lunghezza variabile che specificano il metafile incorporato. Il contenuto e il formato dei dati possono variare per ciascun tipo di metafile.

Le immagini grafiche sono specificate da oggetti EmfPlusImage (sezione 2.2.1.4). Un oggetto EmfPlusMetafile DEVE essere presente nel campo ImageData di un oggetto EmfPlusImage se ImageTypeMetafile è specificato nel suo campo Type. Questo oggetto è generico e viene utilizzato per diversi tipi di dati, inclusi: un metafile WMF [MS-WMF]; metafile WMF che può essere posizionato; un metafile EMF [MS-EMF]; un metafile EMF+ che specifica operazioni grafiche solo con record EMF+; e un metafile EMF+ che specifica operazioni grafiche con sia record EMF+ sia record EMF. Vedere la sezione 2.2.2 per la specifica di ulteriori oggetti strutturali.

**Returns:**
byte[]
### setMetafileData(byte[] value) {#setMetafileData-byte---}
```
public void setMetafileData(byte[] value)
```


Ottiene o imposta dati di lunghezza variabile che specificano il metafile incorporato. Il contenuto e il formato dei dati possono variare per ciascun tipo di metafile.

Le immagini grafiche sono specificate da oggetti EmfPlusImage (sezione 2.2.1.4). Un oggetto EmfPlusMetafile DEVE essere presente nel campo ImageData di un oggetto EmfPlusImage se ImageTypeMetafile è specificato nel suo campo Type. Questo oggetto è generico e viene utilizzato per diversi tipi di dati, inclusi: un metafile WMF [MS-WMF]; metafile WMF che può essere posizionato; un metafile EMF [MS-EMF]; un metafile EMF+ che specifica operazioni grafiche solo con record EMF+; e un metafile EMF+ che specifica operazioni grafiche con sia record EMF+ sia record EMF. Vedere la sezione 2.2.2 per la specifica di ulteriori oggetti strutturali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | byte[] |  |

