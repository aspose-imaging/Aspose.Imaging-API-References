---
title: "EmfLogPen"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "L'oggetto LogPen definisce lo stile, la larghezza e il colore di una penna logica."
type: docs
weight: 27
url: /it/java/com.aspose.imaging.fileformats.emf.emf.objects/emflogpen/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfBasePen](../../com.aspose.imaging.fileformats.emf.emf.objects/emfbasepen)
```
public final class EmfLogPen extends EmfBasePen
```

L'oggetto LogPen definisce lo stile, la larghezza e il colore di una penna logica.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfLogPen()](#EmfLogPen--) |  |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getPenStyle()](#getPenStyle--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il PenStyle. |
| [setPenStyle(int value)](#setPenStyle-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il PenStyle. |
| [getWidth()](#getWidth--) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica la larghezza della penna in base al valore del suo campo x. |
| [setWidth(Point value)](#setWidth-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica la larghezza della penna in base al valore del suo campo x. |
| [getAffectWidth()](#getAffectWidth--) | Ottiene o imposta la larghezza dell'effetto. |
| [setAffectWidth(int value)](#setAffectWidth-int-) | Ottiene o imposta la larghezza dell'effetto. |
| [getArgb32ColorRef()](#getArgb32ColorRef--) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il valore del colore della penna. |
| [setArgb32ColorRef(int value)](#setArgb32ColorRef-int-) | Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il valore del colore della penna. |
### EmfLogPen() {#EmfLogPen--}
```
public EmfLogPen()
```


### getPenStyle() {#getPenStyle--}
```
public int getPenStyle()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il PenStyle. Il valore DEVE essere definito nella tabella di enumerazione PenStyle, specificata nella sezione 2.1.25.

**Returns:**
int
### setPenStyle(int value) {#setPenStyle-int-}
```
public void setPenStyle(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il PenStyle. Il valore DEVE essere definito nella tabella di enumerazione PenStyle, specificata nella sezione 2.1.25.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getWidth() {#getWidth--}
```
public Point getWidth()
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica la larghezza della penna in base al valore del suo campo x. Il valore del suo campo y DEVE essere ignorato.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setWidth(Point value) {#setWidth-com.aspose.imaging.Point-}
```
public void setWidth(Point value)
```


Ottiene o imposta un oggetto WMF PointL ([MS-WMF] sezione 2.2.2.15) che specifica la larghezza della penna in base al valore del suo campo x. Il valore del suo campo y DEVE essere ignorato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getAffectWidth() {#getAffectWidth--}
```
public int getAffectWidth()
```


Ottiene o imposta la larghezza dell'effetto.

Valore: La larghezza dell'effetto.

**Returns:**
int
### setAffectWidth(int value) {#setAffectWidth-int-}
```
public void setAffectWidth(int value)
```


Ottiene o imposta la larghezza dell'effetto.

Valore: La larghezza dell'effetto.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getArgb32ColorRef() {#getArgb32ColorRef--}
```
public int getArgb32ColorRef()
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il valore del colore della penna.

Valore: Il colore ARGB a 32 bit

**Returns:**
int
### setArgb32ColorRef(int value) {#setArgb32ColorRef-int-}
```
public void setArgb32ColorRef(int value)
```


Ottiene o imposta un oggetto WMF ColorRef ([MS-WMF] sezione 2.2.2.8) che specifica il valore del colore della penna.

Valore: Il colore ARGB a 32 bit

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

