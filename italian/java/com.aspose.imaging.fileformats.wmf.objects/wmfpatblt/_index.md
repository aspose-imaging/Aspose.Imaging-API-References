---
title: "WmfPatBlt"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_PATBLT dipinge un rettangolo specificato usando il pennello che è definito nel contesto del dispositivo di riproduzione."
type: docs
weight: 52
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmfpatblt/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfobject), [com.aspose.imaging.fileformats.wmf.objects.WmfPointObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfpointobject)
```
public class WmfPatBlt extends WmfPointObject
```

Il record META\_PATBLT dipinge un rettangolo specificato usando il pennello che è definito nel contesto del dispositivo di riproduzione. Il colore del pennello e il colore o i colori della superficie sono combinati usando l'operazione raster specificata.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfPatBlt()](#WmfPatBlt--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRasterOperation()](#getRasterOperation--) | Ottiene o imposta l'operazione raster. |
| [setRasterOperation(int value)](#setRasterOperation-int-) | Ottiene o imposta l'operazione raster. |
| [getHeight()](#getHeight--) | Ottiene o imposta l'altezza. |
| [setHeight(short value)](#setHeight-short-) | Ottiene o imposta l'altezza. |
| [getWidth()](#getWidth--) | Ottiene o imposta la larghezza. |
| [setWidth(short value)](#setWidth-short-) | Ottiene o imposta la larghezza. |
### WmfPatBlt() {#WmfPatBlt--}
```
public WmfPatBlt()
```


### getRasterOperation() {#getRasterOperation--}
```
public int getRasterOperation()
```


Ottiene o imposta l'operazione raster.

Valore: il codice dell'operazione raster. Questo codice DEVE essere uno dei valori nella tabella di enumerazione Ternary Raster Operation.

**Returns:**
int
### setRasterOperation(int value) {#setRasterOperation-int-}
```
public void setRasterOperation(int value)
```


Ottiene o imposta l'operazione raster.

Valore: il codice dell'operazione raster. Questo codice DEVE essere uno dei valori nella tabella di enumerazione Ternary Raster Operation.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHeight() {#getHeight--}
```
public short getHeight()
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, del rettangolo.

**Returns:**
short
### setHeight(short value) {#setHeight-short-}
```
public void setHeight(short value)
```


Ottiene o imposta l'altezza.

Valore: l'altezza, in unità logiche, del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

### getWidth() {#getWidth--}
```
public short getWidth()
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, del rettangolo.

**Returns:**
short
### setWidth(short value) {#setWidth-short-}
```
public void setWidth(short value)
```


Ottiene o imposta la larghezza.

Valore: la larghezza, in unità logiche, del rettangolo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | short |  |

