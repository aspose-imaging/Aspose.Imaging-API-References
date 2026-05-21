---
title: "EmfModifyWorldTransform"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_MODIFYWORLDTRANSFORM modifica la trasformazione dallo spazio mondo corrente allo spazio pagina nel contesto del dispositivo di riproduzione."
type: docs
weight: 73
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfmodifyworldtransform/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfTransformRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emftransformrecordtype)
```
public final class EmfModifyWorldTransform extends EmfTransformRecordType
```

Il record EMR\_MODIFYWORLDTRANSFORM modifica la trasformazione dallo spazio mondo corrente allo spazio pagina nel contesto del dispositivo di riproduzione.

Per ulteriori informazioni su trasformazioni e spazi di coordinate, vedere [MSDN-WRLDPGSPC]. Vedere la sezione 2.3.12 per la specifica degli altri tipi di record di trasformazione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfModifyWorldTransform(EmfRecord source)](#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfModifyWorldTransform`. |
| [EmfModifyWorldTransform()](#EmfModifyWorldTransform--) | Inizializza una nuova istanza della classe `EmfModifyWorldTransform`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getModifyWorldTransformMode()](#getModifyWorldTransformMode--) | Ottiene o imposta un intero senza segno a 32 bit che specifica come viene utilizzata la trasformazione specificata in Xform. |
| [setModifyWorldTransformMode(int value)](#setModifyWorldTransformMode-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica come viene utilizzata la trasformazione specificata in Xform. |
### EmfModifyWorldTransform(EmfRecord source) {#EmfModifyWorldTransform-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfModifyWorldTransform(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfModifyWorldTransform`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfModifyWorldTransform() {#EmfModifyWorldTransform--}
```
public EmfModifyWorldTransform()
```


Inizializza una nuova istanza della classe `EmfModifyWorldTransform`.

### getModifyWorldTransformMode() {#getModifyWorldTransformMode--}
```
public int getModifyWorldTransformMode()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come viene utilizzata la trasformazione specificata in Xform. Questo valore DEVE appartenere all'enumerazione ModifyWorldTransformMode (sezione 2.1.24).

**Returns:**
int
### setModifyWorldTransformMode(int value) {#setModifyWorldTransformMode-int-}
```
public void setModifyWorldTransformMode(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica come viene utilizzata la trasformazione specificata in Xform. Questo valore DEVE appartenere all'enumerazione ModifyWorldTransformMode (sezione 2.1.24).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

