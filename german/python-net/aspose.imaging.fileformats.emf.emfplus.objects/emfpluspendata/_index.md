---
title: "EmfPlusPenData Klasse"
type: docs
weight: 550
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspendata/
---

**Summary:** The EmfPlusPenData object specifies properties of a graphics pen.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPenData()](#EmfPlusPenData__1) | Initialisiert eine neue Instanz der Klasse EmfPlusPenData |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| optional_data | [EmfPlusPenOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/) | r/w | Liest oder setzt ein optionales EmfPlusPenOptionalData-Objekt (Abschnitt 2.2.2.34) <br/>            das zusätzliche Daten für das Stiftobjekt angibt. Der spezifische <br/>            Inhalt dieses Feldes wird durch den Wert des <br/>            PenDataFlags-Feldes bestimmt. |
| pen_data_flags | [EmfPlusPenDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspendataflags/) | r/w | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Daten im <br/>            OptionalData-Feld angibt. Dieser Wert MUSS aus PenData-<br/>            Flags (Abschnitt 2.1.2.7) bestehen. |
| pen_unit | [EmfPlusUnitType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusunittype/) | r/w | Liest oder setzt einen 32‑Bit vorzeichenlosen Integer, der die Messeinheiten <br/>            für den Stift angibt. Der Wert MUSS aus der UnitType‑Aufzählung <br/>            (Abschnitt 2.1.1.33) stammen. |
| pen_width | float | r/w | Liest oder setzt einen 32‑Bit Gleitkommawert, der die Breite der <br/>            vom Stift gezeichneten Linie in den durch das PenUnit-<br/>            Feld angegebenen Einheiten bestimmt. Wenn eine Breite von Null angegeben wird, wird ein Minimalwert verwendet, <br/>            der durch die Einheiten bestimmt wird. |


### Constructor: EmfPlusPenData() {#EmfPlusPenData__1}


```
 EmfPlusPenData() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusPenData

