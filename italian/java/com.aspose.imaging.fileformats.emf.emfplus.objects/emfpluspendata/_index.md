---
title: "EmfPlusPenData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusPenData specifica le proprietà di una penna grafica."
type: docs
weight: 64
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

L'oggetto EmfPlusPenData specifica le proprietà di una penna grafica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. |
| [getPenUnit()](#getPenUnit--) | Ottiene o imposta un intero senza segno a 32 bit che specifica le unità di misura per la penna. |
| [setPenUnit(int value)](#setPenUnit-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica le unità di misura per la penna. |
| [getPenWidth()](#getPenWidth--) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la larghezza della linea disegnata dalla penna nelle unità specificate dal campo PenUnit. |
| [setPenWidth(float value)](#setPenWidth-float-) | Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la larghezza della linea disegnata dalla penna nelle unità specificate dal campo PenUnit. |
| [getOptionalData()](#getOptionalData--) | Ottiene o imposta l'oggetto opzionale EmfPlusPenOptionalData (sezione 2.2.2.34) che specifica dati aggiuntivi per l'oggetto penna. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Ottiene o imposta l'oggetto opzionale EmfPlusPenOptionalData (sezione 2.2.2.34) che specifica dati aggiuntivi per l'oggetto penna. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto dai flag PenData (sezione 2.1.2.7).

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica i dati nel campo OptionalData. Questo valore DEVE essere composto dai flag PenData (sezione 2.1.2.7).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le unità di misura per la penna. Il valore DEVE appartenere all'enumerazione UnitType (sezione 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica le unità di misura per la penna. Il valore DEVE appartenere all'enumerazione UnitType (sezione 2.1.1.33).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la larghezza della linea disegnata dalla penna nelle unità specificate dal campo PenUnit. Se viene specificata una larghezza zero, viene utilizzato un valore minimo, determinato dalle unità.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Ottiene o imposta un valore a virgola mobile a 32 bit che specifica la larghezza della linea disegnata dalla penna nelle unità specificate dal campo PenUnit. Se viene specificata una larghezza zero, viene utilizzato un valore minimo, determinato dalle unità.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Ottiene o imposta l'oggetto opzionale EmfPlusPenOptionalData (sezione 2.2.2.34) che specifica dati aggiuntivi per l'oggetto penna. Il contenuto specifico di questo campo è determinato dal valore del campo PenDataFlags.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Ottiene o imposta l'oggetto opzionale EmfPlusPenOptionalData (sezione 2.2.2.34) che specifica dati aggiuntivi per l'oggetto penna. Il contenuto specifico di questo campo è determinato dal valore del campo PenDataFlags.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

