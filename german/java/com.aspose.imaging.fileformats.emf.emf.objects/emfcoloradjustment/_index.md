---
title: "EmfColorAdjustment"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das ColorAdjustment-Objekt definiert Werte zum Anpassen der Farben in Quell‑Bitmaps bei Bit‑Block‑Transfers."
type: docs
weight: 12
url: /de/java/com.aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emf.objects.EmfObject](../../com.aspose.imaging.fileformats.emf.emf.objects/emfobject)
```
public final class EmfColorAdjustment extends EmfObject
```

Das ColorAdjustment-Objekt definiert Werte zum Anpassen der Farben in Quell‑Bitmaps bei Bit‑Block‑Transfers.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfColorAdjustment()](#EmfColorAdjustment--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getSize()](#getSize--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. |
| [setSize(short value)](#setSize-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. |
| [getValues()](#getValues--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie das Ausgabebild vorbereitet wird. |
| [setValues(int value)](#setValues-int-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die angibt, wie das Ausgabebild vorbereitet wird. |
| [getIlluminantIndex()](#getIlluminantIndex--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Standardlichtquelle angibt, unter der das Bild betrachtet wird, aus der Illuminant‑Aufzählung (Abschnitt 2.1.19). |
| [setIlluminantIndex(int value)](#setIlluminantIndex-int-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Standardlichtquelle angibt, unter der das Bild betrachtet wird, aus der Illuminant‑Aufzählung (Abschnitt 2.1.19). |
| [getRedGamma()](#getRedGamma--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die rote Primärfarbe der Quellfarben angibt. |
| [setRedGamma(short value)](#setRedGamma-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die rote Primärfarbe der Quellfarben angibt. |
| [getGreenGamma()](#getGreenGamma--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die grüne Primärfarbe der Quellfarben angibt. |
| [setGreenGamma(short value)](#setGreenGamma-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die grüne Primärfarbe der Quellfarben angibt. |
| [getBlueGamma()](#getBlueGamma--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die blaue Primärfarbe der Quellfarben angibt. |
| [setBlueGamma(short value)](#setBlueGamma-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die blaue Primärfarbe der Quellfarben angibt. |
| [getReferenceBlack()](#getReferenceBlack--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Schwarzreferenz für die Quellfarben angibt. |
| [setReferenceBlack(short value)](#setReferenceBlack-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Schwarzreferenz für die Quellfarben angibt. |
| [getReferenceWhite()](#getReferenceWhite--) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Weißreferenz für die Quellfarben angibt. |
| [setReferenceWhite(short value)](#setReferenceWhite-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die die Weißreferenz für die Quellfarben angibt. |
| [getContrast()](#getContrast--) | Liefert oder setzt eine 16‑Bit‑vorzeichenbehaftete Ganzzahl, die die Menge des Kontrasts angibt, die auf das Quellobjekt angewendet werden soll. |
| [setContrast(short value)](#setContrast-short-) | Liefert oder setzt eine 16‑Bit‑vorzeichenbehaftete Ganzzahl, die die Menge des Kontrasts angibt, die auf das Quellobjekt angewendet werden soll. |
| [getBrightness()](#getBrightness--) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Helligkeitsmenge angibt, die auf das Quellobjekt angewendet wird. |
| [setBrightness(short value)](#setBrightness-short-) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Helligkeitsmenge angibt, die auf das Quellobjekt angewendet wird. |
| [getColorfullness()](#getColorfullness--) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Farbintensität angibt, die auf das Quellobjekt angewendet wird. |
| [setColorfullness(short value)](#setColorfullness-short-) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Farbintensität angibt, die auf das Quellobjekt angewendet wird. |
| [getRedGreenTint()](#getRedGreenTint--) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Menge der Rot‑ oder Grün‑Tönungsanpassung angibt, die auf das Quellobjekt angewendet wird. |
| [setRedGreenTint(short value)](#setRedGreenTint-short-) | Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Menge der Rot‑ oder Grün‑Tönungsanpassung angibt, die auf das Quellobjekt angewendet wird. |
### EmfColorAdjustment() {#EmfColorAdjustment--}
```
public EmfColorAdjustment()
```


### getSize() {#getSize--}
```
public short getSize()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. Dieser Wert MUSS 0x0018 sein.

**Returns:**
short
### setSize(short value) {#setSize-short-}
```
public void setSize(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Größe dieses Objekts in Bytes angibt. Dieser Wert MUSS 0x0018 sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getValues() {#getValues--}
```
public int getValues()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die angibt, wie das Ausgabebild vorzubereiten ist. Dieses Feld kann auf NULL oder auf eine beliebige Kombination von Werten in der ColorAdjustment‑Aufzählung (Abschnitt 2.1.5) gesetzt werden.

**Returns:**
int
### setValues(int value) {#setValues-int-}
```
public void setValues(int value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die angibt, wie das Ausgabebild vorzubereiten ist. Dieses Feld kann auf NULL oder auf eine beliebige Kombination von Werten in der ColorAdjustment‑Aufzählung (Abschnitt 2.1.5) gesetzt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getIlluminantIndex() {#getIlluminantIndex--}
```
public int getIlluminantIndex()
```


Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Standardlichtquelle angibt, unter der das Bild betrachtet wird, aus der Illuminant‑Aufzählung (Abschnitt 2.1.19).

**Returns:**
int
### setIlluminantIndex(int value) {#setIlluminantIndex-int-}
```
public void setIlluminantIndex(int value)
```


Liefert oder setzt eine 16‑Bit‑vorzeichenlose Ganzzahl, die den Typ der Standardlichtquelle angibt, unter der das Bild betrachtet wird, aus der Illuminant‑Aufzählung (Abschnitt 2.1.19).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getRedGamma() {#getRedGamma--}
```
public short getRedGamma()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die rote Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Returns:**
short
### setRedGamma(short value) {#setRedGamma-short-}
```
public void setRedGamma(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die rote Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getGreenGamma() {#getGreenGamma--}
```
public short getGreenGamma()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die grüne Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Returns:**
short
### setGreenGamma(short value) {#setGreenGamma-short-}
```
public void setGreenGamma(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die grüne Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getBlueGamma() {#getBlueGamma--}
```
public short getBlueGamma()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die blaue Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Returns:**
short
### setBlueGamma(short value) {#setBlueGamma-short-}
```
public void setBlueGamma(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die den n‑ten Potenz‑Gamma‑Korrekturwert für die blaue Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getReferenceBlack() {#getReferenceBlack--}
```
public short getReferenceBlack()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Schwarz‑Referenz für die Quellfarben angibt. Alle Farben, die dunkler als dieser Wert sind, werden als Schwarz behandelt. Dieser Wert SOLLTE im Bereich von null bis 4.000 liegen.

**Returns:**
short
### setReferenceBlack(short value) {#setReferenceBlack-short-}
```
public void setReferenceBlack(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Schwarz‑Referenz für die Quellfarben angibt. Alle Farben, die dunkler als dieser Wert sind, werden als Schwarz behandelt. Dieser Wert SOLLTE im Bereich von null bis 4.000 liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getReferenceWhite() {#getReferenceWhite--}
```
public short getReferenceWhite()
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Weiß‑Referenz für die Quellfarben angibt. Alle Farben, die heller als dieser Wert sind, werden als Weiß behandelt. Dieser Wert SOLLTE im Bereich von 6.000 bis 10.000 liegen.

**Returns:**
short
### setReferenceWhite(short value) {#setReferenceWhite-short-}
```
public void setReferenceWhite(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenlose Ganzzahl, die die Weiß‑Referenz für die Quellfarben angibt. Alle Farben, die heller als dieser Wert sind, werden als Weiß behandelt. Dieser Wert SOLLTE im Bereich von 6.000 bis 10.000 liegen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getContrast() {#getContrast--}
```
public short getContrast()
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Kontrastmenge angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Kontrastanpassung MUSS NICHT durchgeführt werden.

**Returns:**
short
### setContrast(short value) {#setContrast-short-}
```
public void setContrast(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Kontrastmenge angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Kontrastanpassung MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getBrightness() {#getBrightness--}
```
public short getBrightness()
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Helligkeitsmenge angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Helligkeitsanpassung MUSS NICHT durchgeführt werden.

**Returns:**
short
### setBrightness(short value) {#setBrightness-short-}
```
public void setBrightness(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Helligkeitsmenge angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Helligkeitsanpassung MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getColorfullness() {#getColorfullness--}
```
public short getColorfullness()
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Farbintensität angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Farbintensitätsanpassung MUSS NICHT durchgeführt werden.

**Returns:**
short
### setColorfullness(short value) {#setColorfullness-short-}
```
public void setColorfullness(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Farbintensität angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Farbintensitätsanpassung MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

### getRedGreenTint() {#getRedGreenTint--}
```
public short getRedGreenTint()
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Menge der Rot‑ oder Grün‑Tönungsanpassung angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Positive Zahlen passen in Richtung Rot an und negative Zahlen passen in Richtung Grün an. Ein Wert von null bedeutet, dass die Tönungsanpassung MUSS NICHT durchgeführt werden.

**Returns:**
short
### setRedGreenTint(short value) {#setRedGreenTint-short-}
```
public void setRedGreenTint(short value)
```


Liest oder setzt eine 16‑Bit vorzeichenbehaftete Ganzzahl, die die Menge der Rot‑ oder Grün‑Tönungsanpassung angibt, die auf das Quellobjekt angewendet wird. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Positive Zahlen passen in Richtung Rot an und negative Zahlen passen in Richtung Grün an. Ein Wert von null bedeutet, dass die Tönungsanpassung MUSS NICHT durchgeführt werden.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | short |  |

