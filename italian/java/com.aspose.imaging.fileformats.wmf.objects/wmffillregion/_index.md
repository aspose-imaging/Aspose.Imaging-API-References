---
title: "WmfFillRegion"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record META_FILLREGION riempie una regione usando un pennello specificato."
type: docs
weight: 37
url: /it/java/com.aspose.imaging.fileformats.wmf.objects/wmffillregion/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging/fileformats.emf/metaobject), [com.aspose.imaging.fileformats.wmf.objects.WmfObject](../../com.aspose.imaging/fileformats.wmf.objects/wmfobject)
```
public class WmfFillRegion extends WmfObject
```

Il record META\_FILLREGION riempie una regione usando un pennello specificato.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [WmfFillRegion()](#WmfFillRegion--) | Inizializza una nuova istanza della classe `WmfFillRegion`. |
| [WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)](#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-) | Inizializza una nuova istanza della classe `WmfFillRegion`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getRegionIndex()](#getRegionIndex--) | Ottiene o imposta l'indice della regione. |
| [setRegionIndex(int value)](#setRegionIndex-int-) | Ottiene o imposta l'indice della regione. |
| [getBrushIndex()](#getBrushIndex--) | Ottiene o imposta l'indice del pennello. |
| [setBrushIndex(int value)](#setBrushIndex-int-) | Ottiene o imposta l'indice del pennello. |
### WmfFillRegion() {#WmfFillRegion--}
```
public WmfFillRegion()
```


Inizializza una nuova istanza della classe `WmfFillRegion`.

### WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush) {#WmfFillRegion-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-com.aspose.imaging.fileformats.wmf.objects.WmfGraphicObject-}
```
public WmfFillRegion(WmfGraphicObject region, WmfGraphicObject brush)
```


Inizializza una nuova istanza della classe `WmfFillRegion`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| region | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | La regione. |
| brush | [WmfGraphicObject](../../com.aspose.imaging.fileformats.wmf.objects/wmfgraphicobject) | Il pennello. |

### getRegionIndex() {#getRegionIndex--}
```
public int getRegionIndex()
```


Ottiene o imposta l'indice della regione.

Valore: indice nella tabella degli oggetti WMF per ottenere la regione da riempire.

**Returns:**
int
### setRegionIndex(int value) {#setRegionIndex-int-}
```
public void setRegionIndex(int value)
```


Ottiene o imposta l'indice della regione.

Valore: indice nella tabella degli oggetti WMF per ottenere la regione da riempire.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getBrushIndex() {#getBrushIndex--}
```
public int getBrushIndex()
```


Ottiene o imposta l'indice del pennello.

Valore: indice nella tabella degli oggetti WMF per ottenere il pennello da utilizzare per riempire la regione.

**Returns:**
int
### setBrushIndex(int value) {#setBrushIndex-int-}
```
public void setBrushIndex(int value)
```


Ottiene o imposta l'indice del pennello.

Valore: indice nella tabella degli oggetti WMF per ottenere il pennello da utilizzare per riempire la regione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

