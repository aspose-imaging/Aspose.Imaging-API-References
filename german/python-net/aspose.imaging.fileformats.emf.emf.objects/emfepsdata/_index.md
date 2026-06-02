---
title: "EmfEpsData Klasse"
type: docs
weight: 50
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfepsdata/
---

**Summary:** The EpsData object is a container for EPS data

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfEpsData

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfEpsData()](#EmfEpsData__1) | Initialisiert eine neue Instanz der EmfEpsData Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| points | [EmfPoint28To4[]](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpoint28to4/) | r/w | Liest oder setzt ein Array von drei Point28_4‑Objekten (Abschnitt 2.2.23), das die <br/>            Koordinaten des Ausgabep parallelogramms mittels 28,4‑Bit‑FIX‑Notation definiert. |
| post_script_data | System.Byte | r/w | Liest oder setzt ein Byte-Array mit PostScript-Daten. Die Länge dieses Arrays kann <br/>            aus dem Feld SizeData berechnet werden. Diese Daten DÜRFEN verwendet werden, um ein Bild zu rendern. |
| size_data | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Gesamtgröße dieses Objekts in Bytes angibt. |
| version | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die das PostScript‑Sprachniveau angibt. Dieser <br/>            Wert MUSS 0x00000001 sein. |


### Constructor: EmfEpsData() {#EmfEpsData__1}


```
 EmfEpsData() 
```

Initialisiert eine neue Instanz der EmfEpsData Klasse

