---
title: "EmfAngleArc"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Il record EMR_ANGLEARC specifica un segmento di linea di un arco."
type: docs
weight: 12
url: /it/java/com.aspose.imaging.fileformats.emf.emf.records/emfanglearc/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.records.EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord), [com.aspose.imaging.fileformats.emf.emf.records.EmfDrawingRecordType](../../com.aspose.imaging.fileformats.emf.emf.records/emfdrawingrecordtype)
```
public final class EmfAngleArc extends EmfDrawingRecordType
```

Il record EMR\_ANGLEARC specifica un segmento di linea di un arco. Il segmento di linea è disegnato dalla posizione corrente all'inizio dell'arco. L'arco è tracciato lungo il perimetro di un cerchio con il raggio e il centro forniti. La lunghezza dell'arco è definita dagli angoli di avvio e di sweep forniti.
## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfAngleArc(EmfRecord source)](#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-) | Inizializza una nuova istanza della classe `EmfAngleArc`. |
| [EmfAngleArc()](#EmfAngleArc--) | Inizializza una nuova istanza della classe `EmfAngleArc`. |
## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCenter()](#getCenter--) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione 2.2.2.15 di [MS-WMF], che specifica le coordinate logiche del centro del cerchio. |
| [setCenter(Point value)](#setCenter-com.aspose.imaging.Point-) | Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione 2.2.2.15 di [MS-WMF], che specifica le coordinate logiche del centro del cerchio. |
| [getRadius()](#getRadius--) | Ottiene o imposta un intero senza segno a 32 bit che specifica il raggio del cerchio, in unità logiche. |
| [setRadius(int value)](#setRadius-int-) | Ottiene o imposta un intero senza segno a 32 bit che specifica il raggio del cerchio, in unità logiche. |
| [getStartAngle()](#getStartAngle--) | Ottiene o imposta un valore float a 32 bit che specifica l'angolo iniziale dell'arco, in gradi. |
| [setStartAngle(float value)](#setStartAngle-float-) | Ottiene o imposta un valore float a 32 bit che specifica l'angolo iniziale dell'arco, in gradi. |
| [getSweepAngle()](#getSweepAngle--) | Ottiene o imposta un valore float a 32 bit che specifica l'angolo di sweep dell'arco, in gradi. |
| [setSweepAngle(float value)](#setSweepAngle-float-) | Ottiene o imposta un valore float a 32 bit che specifica l'angolo di sweep dell'arco, in gradi. |
### EmfAngleArc(EmfRecord source) {#EmfAngleArc-com.aspose.imaging.fileformats.emf.emf.records.EmfRecord-}
```
public EmfAngleArc(EmfRecord source)
```


Inizializza una nuova istanza della classe `EmfAngleArc`.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| source | [EmfRecord](../../com.aspose.imaging.fileformats.emf.emf.records/emfrecord) | La sorgente. |

### EmfAngleArc() {#EmfAngleArc--}
```
public EmfAngleArc()
```


Inizializza una nuova istanza della classe `EmfAngleArc`.

### getCenter() {#getCenter--}
```
public Point getCenter()
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione 2.2.2.15 di [MS-WMF], che specifica le coordinate logiche del centro del cerchio.

**Returns:**
[Point](../../com.aspose.imaging/point)
### setCenter(Point value) {#setCenter-com.aspose.imaging.Point-}
```
public void setCenter(Point value)
```


Ottiene o imposta un oggetto WMF PointL a 64 bit, specificato nella sezione 2.2.2.15 di [MS-WMF], che specifica le coordinate logiche del centro del cerchio.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| value | [Point](../../com.aspose.imaging/point) |  |

### getRadius() {#getRadius--}
```
public int getRadius()
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il raggio del cerchio, in unità logiche.

**Returns:**
int
### setRadius(int value) {#setRadius-int-}
```
public void setRadius(int value)
```


Ottiene o imposta un intero senza segno a 32 bit che specifica il raggio del cerchio, in unità logiche.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | int |  |

### getStartAngle() {#getStartAngle--}
```
public float getStartAngle()
```


Ottiene o imposta un valore float a 32 bit che specifica l'angolo iniziale dell'arco, in gradi.

**Returns:**
float
### setStartAngle(float value) {#setStartAngle-float-}
```
public void setStartAngle(float value)
```


Ottiene o imposta un valore float a 32 bit che specifica l'angolo iniziale dell'arco, in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

### getSweepAngle() {#getSweepAngle--}
```
public float getSweepAngle()
```


Ottiene o imposta un valore float a 32 bit che specifica l'angolo di sweep dell'arco, in gradi.

**Returns:**
float
### setSweepAngle(float value) {#setSweepAngle-float-}
```
public void setSweepAngle(float value)
```


Ottiene o imposta un valore float a 32 bit che specifica l'angolo di sweep dell'arco, in gradi.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore | float |  |

