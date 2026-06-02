---
title: "EmfDesignVector"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das DesignVector‑Abschnitt‑2.2.3‑Objekt definiert den Designvektor, der Werte für die Schriftachsen einer Multiple‑Master‑Schrift festlegt."
type: docs
weight: 13
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfdesignvector/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfDesignVector extends EmfObject
```

Das DesignVector‑Objekt (Abschnitt 2.2.3) definiert den Designvektor, der Werte für die Schriftachsen einer Multiple‑Master‑Schrift festlegt.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfDesignVector()](#EmfDesignVector--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSignature()](#getSignature--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF DEN Wert 0x08007664 gesetzt werden MUSS. |
| [setSignature(int value)](#setSignature-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF DEN Wert 0x08007664 gesetzt werden MUSS. |
| [getNumAxes()](#getNumAxes--) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Elemente im Values‑Array angibt. |
| [setNumAxes(int value)](#setNumAxes-int-) | Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Elemente im Values‑Array angibt. |
| [getValues()](#getValues--) | Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenbehafteten Ganzzahlen, das die Werte der Schriftachsen einer Multiple‑Master‑OpenType‑Schrift angibt. |
| [setValues(int[] value)](#setValues-int---) | Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenbehafteten Ganzzahlen, das die Werte der Schriftachsen einer Multiple‑Master‑OpenType‑Schrift angibt. |
### EmfDesignVector() {#EmfDesignVector--}
```
public EmfDesignVector()
```


### getSignature() {#getSignature--}
```
public int getSignature()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF DEN Wert 0x08007664 gesetzt werden MUSS.

**Returns:**
int
### setSignature(int value) {#setSignature-int-}
```
public void setSignature(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die AUF DEN Wert 0x08007664 gesetzt werden MUSS.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getNumAxes() {#getNumAxes--}
```
public int getNumAxes()
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Elemente im Values‑Array angibt. Sie MUSS im Bereich von 0 bis 16 liegen, einschließlich.

**Returns:**
int
### setNumAxes(int value) {#setNumAxes-int-}
```
public void setNumAxes(int value)
```


Liest oder setzt eine 32‑Bit‑vorzeichenlose Ganzzahl, die die Anzahl der Elemente im Values‑Array angibt. Sie MUSS im Bereich von 0 bis 16 liegen, einschließlich.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getValues() {#getValues--}
```
public int[] getValues()
```


Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenbehafteten Ganzzahlen, das die Werte der Schriftachsen einer Multiple‑Master‑OpenType‑Schrift angibt. Die maximale Anzahl von Werten im Array beträgt 16.

**Returns:**
int[]
### setValues(int[] value) {#setValues-int---}
```
public void setValues(int[] value)
```


Liest oder setzt ein optionales Array von 32‑Bit‑vorzeichenbehafteten Ganzzahlen, das die Werte der Schriftachsen einer Multiple‑Master‑OpenType‑Schrift angibt. Die maximale Anzahl von Werten im Array beträgt 16.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int[] |  |

