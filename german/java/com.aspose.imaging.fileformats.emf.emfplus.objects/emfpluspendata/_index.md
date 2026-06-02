---
title: "EmfPlusPenData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusPenData-Objekt gibt Eigenschaften eines Grafikstifts an."
type: docs
weight: 64
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusPenData extends EmfPlusStructureObjectType
```

Das EmfPlusPenData-Objekt gibt Eigenschaften eines Grafikstifts an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusPenData()](#EmfPlusPenData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getPenDataFlags()](#getPenDataFlags--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [setPenDataFlags(int value)](#setPenDataFlags-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. |
| [getPenUnit()](#getPenUnit--) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Maßeinheiten für den Stift angibt. |
| [setPenUnit(int value)](#setPenUnit-int-) | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Maßeinheiten für den Stift angibt. |
| [getPenWidth()](#getPenWidth--) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der vom Stift gezeichneten Linie in den durch das Feld PenUnit angegebenen Einheiten festlegt. |
| [setPenWidth(float value)](#setPenWidth-float-) | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der vom Stift gezeichneten Linie in den durch das Feld PenUnit angegebenen Einheiten festlegt. |
| [getOptionalData()](#getOptionalData--) | Liest oder setzt ein optionales EmfPlusPenOptionalData‑Objekt (Abschnitt 2.2.2.34), das zusätzliche Daten für das Stift‑Objekt angibt. |
| [setOptionalData(EmfPlusPenOptionalData value)](#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-) | Liest oder setzt ein optionales EmfPlusPenOptionalData‑Objekt (Abschnitt 2.2.2.34), das zusätzliche Daten für das Stift‑Objekt angibt. |
### EmfPlusPenData() {#EmfPlusPenData--}
```
public EmfPlusPenData()
```


### getPenDataFlags() {#getPenDataFlags--}
```
public int getPenDataFlags()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus PenData‑Flags (Abschnitt 2.1.2.7) zusammengesetzt sein.

**Returns:**
int
### setPenDataFlags(int value) {#setPenDataFlags-int-}
```
public void setPenDataFlags(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im Feld OptionalData angibt. Dieser Wert MUSS aus PenData‑Flags (Abschnitt 2.1.2.7) zusammengesetzt sein.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPenUnit() {#getPenUnit--}
```
public int getPenUnit()
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Maßeinheiten für den Stift angibt. Der Wert MUSS aus der Aufzählung UnitType stammen (Abschnitt 2.1.1.33).

**Returns:**
int
### setPenUnit(int value) {#setPenUnit-int-}
```
public void setPenUnit(int value)
```


Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Maßeinheiten für den Stift angibt. Der Wert MUSS aus der Aufzählung UnitType stammen (Abschnitt 2.1.1.33).

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | int |  |

### getPenWidth() {#getPenWidth--}
```
public float getPenWidth()
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der vom Stift gezeichneten Linie in den durch das Feld PenUnit angegebenen Einheiten festlegt. Wird eine Breite von Null angegeben, wird ein Minimalwert verwendet, der durch die Einheiten bestimmt wird.

**Returns:**
float
### setPenWidth(float value) {#setPenWidth-float-}
```
public void setPenWidth(float value)
```


Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der vom Stift gezeichneten Linie in den durch das Feld PenUnit angegebenen Einheiten festlegt. Wird eine Breite von Null angegeben, wird ein Minimalwert verwendet, der durch die Einheiten bestimmt wird.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float |  |

### getOptionalData() {#getOptionalData--}
```
public EmfPlusPenOptionalData getOptionalData()
```


Liest oder setzt ein optionales EmfPlusPenOptionalData‑Objekt (Abschnitt 2.2.2.34), das zusätzliche Daten für das Stift‑Objekt angibt. Der konkrete Inhalt dieses Feldes wird durch den Wert des Feldes PenDataFlags bestimmt.

**Returns:**
[EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata)
### setOptionalData(EmfPlusPenOptionalData value) {#setOptionalData-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData-}
```
public void setOptionalData(EmfPlusPenOptionalData value)
```


Liest oder setzt ein optionales EmfPlusPenOptionalData‑Objekt (Abschnitt 2.2.2.34), das zusätzliche Daten für das Stift‑Objekt angibt. Der konkrete Inhalt dieses Feldes wird durch den Wert des Feldes PenDataFlags bestimmt.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusPenOptionalData](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata) |  |

