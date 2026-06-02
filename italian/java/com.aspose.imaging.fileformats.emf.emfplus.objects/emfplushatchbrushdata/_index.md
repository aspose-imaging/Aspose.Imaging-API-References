---
title: "EmfPlusHatchBrushData"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto EmfPlusHatchBrushData specifica un motivo a tratteggio per un pennello grafico."
type: docs
weight: 45
url: /it/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplushatchbrushdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusBaseBrushData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusbasebrushdata)
```
public final class EmfPlusHatchBrushData extends EmfPlusBaseBrushData
```

L'oggetto EmfPlusHatchBrushData specifica un motivo a tratteggio per un pennello grafico.

I pennelli grafici sono specificati da oggetti `EmfPlusBrush` (sezione 2.2.1.1). Un pennello a trama dipinge uno sfondo e disegna un modello di linee, punti, trattini, quadrati e linee a trama incrociata sopra questo sfondo. Il pennello a trama definisce due colori: uno per lo sfondo e uno per il modello sopra lo sfondo. Il colore dello sfondo è chiamato colore di sfondo, e il colore del modello è chiamato colore di primo piano.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfPlusHatchBrushData()](#EmfPlusHatchBrushData--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBackArgb32Color()](#getBackArgb32Color--) | Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per dipingere lo sfondo del modello a trama. |
| [setBackArgb32Color(int value)](#setBackArgb32Color-int-) | Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per dipingere lo sfondo del modello a trama. |
| [getForeArgb32Color()](#getForeArgb32Color--) | Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per disegnare le linee del modello a trama. |
| [setForeArgb32Color(int value)](#setForeArgb32Color-int-) | Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per disegnare le linee del modello a trama. |
| [getHatchStyle()](#getHatchStyle--) | Ottiene o imposta un intero senza segno a 32 bit che specifica lo stile di trama del pennello. |
| [setHatchStyle(int value)](#setHatchStyle-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica lo stile di trama del pennello. |
### EmfPlusHatchBrushData() {#EmfPlusHatchBrushData--}
```
public EmfPlusHatchBrushData()
```


### getBackArgb32Color() {#getBackArgb32Color--}
```
public int getBackArgb32Color()
```


Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per dipingere lo sfondo del modello a trama.

**Returns:**
int
### setBackArgb32Color(int value) {#setBackArgb32Color-int-}
```
public void setBackArgb32Color(int value)
```


Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per dipingere lo sfondo del modello a trama.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getForeArgb32Color() {#getForeArgb32Color--}
```
public int getForeArgb32Color()
```


Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per disegnare le linee del modello a trama.

**Returns:**
int
### setForeArgb32Color(int value) {#setForeArgb32Color-int-}
```
public void setForeArgb32Color(int value)
```


Ottiene o imposta un oggetto EmfPlusArgb a 32 bit che specifica il colore usato per disegnare le linee del modello a trama.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getHatchStyle() {#getHatchStyle--}
```
public int getHatchStyle()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica lo stile di trama del pennello. Deve essere definito nell'enumerazione `EmfPlusHatchStyle`.

**Returns:**
int
### setHatchStyle(int value) {#setHatchStyle-int-}
```
public void setHatchStyle(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica lo stile di trama del pennello. Deve essere definito nell'enumerazione `EmfPlusHatchStyle`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

