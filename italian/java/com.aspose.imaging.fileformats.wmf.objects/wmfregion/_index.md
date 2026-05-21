---
title: "WmfRegion"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto Region definisce una forma potenzialmente non rettilinea definita da un array di linee di scansione."
type: docs
weight: 62
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject)
```
public class WmfRegion extends MetaObject
```

L'oggetto Region definisce una forma potenzialmente non rettilinea definita da un array di linee di scansione.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfRegion()](#WmfRegion--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getNextInChain()](#getNextInChain--) | Ottiene o imposta il successivo nella catena. |
| [setNextInChain(short value)](#setNextInChain-short-) | Ottiene o imposta il successivo nella catena. |
| [getObjectType()](#getObjectType--) | Ottiene o imposta il tipo dell'oggetto. |
| [setObjectType(short value)](#setObjectType-short-) | Ottiene o imposta il tipo dell'oggetto. |
| [getObjectCount()](#getObjectCount--) | Ottiene o imposta il conteggio degli oggetti. |
| [setObjectCount(int value)](#setObjectCount-int-) | Ottiene o imposta il conteggio degli oggetti. |
| [getRegionSize()](#getRegionSize--) | Ottiene o imposta la dimensione della regione. |
| [setRegionSize(short value)](#setRegionSize-short-) | Ottiene o imposta la dimensione della regione. |
| [getScanCount()](#getScanCount--) | Ottiene o imposta il conteggio delle scansioni. |
| [setScanCount(short value)](#setScanCount-short-) | Ottiene o imposta il conteggio delle scansioni. |
| [getMaxScan()](#getMaxScan--) | Ottiene o imposta la scansione massima. |
| [setMaxScan(short value)](#setMaxScan-short-) | Ottiene o imposta la scansione massima. |
| [getBoundingRectangle()](#getBoundingRectangle--) | Ottiene o imposta il rettangolo di delimitazione. |
| [setBoundingRectangle(Rectangle value)](#setBoundingRectangle-com.aspose.imaging.Rectangle-) | Ottiene o imposta il rettangolo di delimitazione. |
| [getAScans()](#getAScans--) | Ottiene o imposta una scansione. |
| [setAScans(WmfScanObject[] value)](#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---) | Ottiene o imposta una scansione. |
### WmfRegion() {#WmfRegion--}
```
public WmfRegion()
```


### getNextInChain() {#getNextInChain--}
```
public short getNextInChain()
```


Ottiene o imposta il successivo nella catena.

Valore: Un valore che DEVE essere ignorato.

**Returns:**
short
### setNextInChain(short value) {#setNextInChain-short-}
```
public void setNextInChain(short value)
```


Ottiene o imposta il successivo nella catena.

Valore: Un valore che DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getObjectType() {#getObjectType--}
```
public short getObjectType()
```


Ottiene o imposta il tipo dell'oggetto.

Valore: L'identificatore della regione. Deve essere 0x0006.

**Returns:**
short
### setObjectType(short value) {#setObjectType-short-}
```
public void setObjectType(short value)
```


Ottiene o imposta il tipo dell'oggetto.

Valore: L'identificatore della regione. Deve essere 0x0006.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getObjectCount() {#getObjectCount--}
```
public int getObjectCount()
```


Ottiene o imposta il conteggio degli oggetti.

Valore: Un valore che DEVE essere ignorato.

**Returns:**
int
### setObjectCount(int value) {#setObjectCount-int-}
```
public void setObjectCount(int value)
```


Ottiene o imposta il conteggio degli oggetti.

Valore: Un valore che DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getRegionSize() {#getRegionSize--}
```
public short getRegionSize()
```


Ottiene o imposta la dimensione della regione.

Valore: La dimensione della regione in byte più la dimensione di aScans in byte.

**Returns:**
short
### setRegionSize(short value) {#setRegionSize-short-}
```
public void setRegionSize(short value)
```


Ottiene o imposta la dimensione della regione.

Valore: La dimensione della regione in byte più la dimensione di aScans in byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getScanCount() {#getScanCount--}
```
public short getScanCount()
```


Ottiene o imposta il conteggio delle scansioni.

Valore: Il numero di linee di scansione che compongono la regione.

**Returns:**
short
### setScanCount(short value) {#setScanCount-short-}
```
public void setScanCount(short value)
```


Ottiene o imposta il conteggio delle scansioni.

Valore: Il numero di linee di scansione che compongono la regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getMaxScan() {#getMaxScan--}
```
public short getMaxScan()
```


Ottiene o imposta la scansione massima.

Valore: Il numero massimo di punti in una singola scansione in questa regione.

**Returns:**
short
### setMaxScan(short value) {#setMaxScan-short-}
```
public void setMaxScan(short value)
```


Ottiene o imposta la scansione massima.

Valore: Il numero massimo di punti in una singola scansione in questa regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getBoundingRectangle() {#getBoundingRectangle--}
```
public Rectangle getBoundingRectangle()
```


Ottiene o imposta il rettangolo di delimitazione.

Valore: Un oggetto Rect (sezione 2.2.2.18) che definisce il rettangolo di delimitazione.

**Returns:**
[Rectangle](../../com.aspose.imaging/rectangle)
### setBoundingRectangle(Rectangle value) {#setBoundingRectangle-com.aspose.imaging.Rectangle-}
```
public void setBoundingRectangle(Rectangle value)
```


Ottiene o imposta il rettangolo di delimitazione.

Valore: Un oggetto Rect (sezione 2.2.2.18) che definisce il rettangolo di delimitazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.imaging/rectangle) |  |

### getAScans() {#getAScans--}
```
public WmfScanObject[] getAScans()
```


Ottiene o imposta una scansione.

Valore: Un array di oggetti Scan (sezione 2.2.2.21) che definiscono le linee di scansione nella regione.

**Returns:**
com.aspose.imaging.fileformats.wmf.objects.WmfScanObject[]
### setAScans(WmfScanObject[] value) {#setAScans-com.aspose.imaging.fileformats.wmf.objects.WmfScanObject---}
```
public void setAScans(WmfScanObject[] value)
```


Ottiene o imposta una scansione.

Valore: Un array di oggetti Scan (sezione 2.2.2.21) che definiscono le linee di scansione nella regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [WmfScanObject\[\]](../../com.aspose.imaging.fileformats.wmf.objects/wmfscanobject) |  |

