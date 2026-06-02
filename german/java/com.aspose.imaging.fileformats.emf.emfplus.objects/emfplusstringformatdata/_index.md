---
title: "EmfPlusStringFormatData"
second_title: "Aspose.Imaging für Java API-Referenz"
description: "Das EmfPlusStringFormatData-Objekt gibt Tabulatoren und Zeichenpositionen für eine Grafikzeichenkette an."
type: docs
weight: 75
url: /de/java/com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstringformatdata/
---
**Inheritance:**
java.lang.Object, [com.aspose.imaging.fileformats.emf.MetaObject](../../com.aspose.imaging.fileformats.emf/metaobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusObject](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusobject), [com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusStructureObjectType](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusstructureobjecttype)
```
public final class EmfPlusStringFormatData extends EmfPlusStructureObjectType
```

Das EmfPlusStringFormatData-Objekt gibt Tabulatoren und Zeichenpositionen für eine Grafikzeichenkette an.
## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [EmfPlusStringFormatData()](#EmfPlusStringFormatData--) |  |
## Methoden

| Methode | Beschreibung |
| --- | --- |
| [getTabStops()](#getTabStops--) | Liest oder setzt ein optionales Array von Fließkommawerten, das die optionalen Tabulatorpositionen für dieses Objekt angibt. |
| [setTabStops(float[] value)](#setTabStops-float---) | Liest oder setzt ein optionales Array von Fließkommawerten, das die optionalen Tabulatorpositionen für dieses Objekt angibt. |
| [getCharRange()](#getCharRange--) | Liest oder setzt ein optionales Array von RangeCount EmfPlusCharacterRange‑Objekten, das den Bereich der Zeichenpositionen innerhalb einer Textzeichenkette angibt. |
| [setCharRange(EmfPlusCharacterRange[] value)](#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---) | Liest oder setzt ein optionales Array von RangeCount EmfPlusCharacterRange‑Objekten, das den Bereich der Zeichenpositionen innerhalb einer Textzeichenkette angibt. |
### EmfPlusStringFormatData() {#EmfPlusStringFormatData--}
```
public EmfPlusStringFormatData()
```


### getTabStops() {#getTabStops--}
```
public float[] getTabStops()
```


Liest oder setzt ein optionales Array von Fließkommawerten, das die optionalen Tabulatorpositionen für dieses Objekt angibt. Jeder Tabulatorwert stellt die Anzahl der Leerzeichen zwischen Tabulatoren dar oder, beim ersten Tabulator, die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulator. Dieses Feld MUSS vorhanden sein, wenn der Wert des Feldes TabStopCount im EmfPlusStringFormat‑Objekt größer als 0 ist.

**Returns:**
float[]
### setTabStops(float[] value) {#setTabStops-float---}
```
public void setTabStops(float[] value)
```


Liest oder setzt ein optionales Array von Fließkommawerten, das die optionalen Tabulatorpositionen für dieses Objekt angibt. Jeder Tabulatorwert stellt die Anzahl der Leerzeichen zwischen Tabulatoren dar oder, beim ersten Tabulator, die Anzahl der Leerzeichen zwischen dem Beginn einer Textzeile und dem ersten Tabulator. Dieses Feld MUSS vorhanden sein, wenn der Wert des Feldes TabStopCount im EmfPlusStringFormat‑Objekt größer als 0 ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert | float[] |  |

### getCharRange() {#getCharRange--}
```
public EmfPlusCharacterRange[] getCharRange()
```


Liest oder setzt ein optionales Array von RangeCount EmfPlusCharacterRange‑Objekten, das den Bereich der Zeichenpositionen innerhalb einer Textzeichenkette angibt. Der Begrenzungsbereich wird durch den Anzeigebereich definiert, der von einer Gruppe von Zeichen, die durch den Zeichenbereich spezifiziert werden, belegt wird. Dieses Feld MUSS vorhanden sein, wenn der Wert des Feldes RangeCount im EmfPlusStringFormat‑Objekt größer als 0 ist.

**Returns:**
com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange[]
### setCharRange(EmfPlusCharacterRange[] value) {#setCharRange-com.aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCharacterRange---}
```
public void setCharRange(EmfPlusCharacterRange[] value)
```


Liest oder setzt ein optionales Array von RangeCount EmfPlusCharacterRange‑Objekten, das den Bereich der Zeichenpositionen innerhalb einer Textzeichenkette angibt. Der Begrenzungsbereich wird durch den Anzeigebereich definiert, der von einer Gruppe von Zeichen, die durch den Zeichenbereich spezifiziert werden, belegt wird. Dieses Feld MUSS vorhanden sein, wenn der Wert des Feldes RangeCount im EmfPlusStringFormat‑Objekt größer als 0 ist.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| value | [EmfPlusCharacterRange\[\]](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfpluscharacterrange) |  |

