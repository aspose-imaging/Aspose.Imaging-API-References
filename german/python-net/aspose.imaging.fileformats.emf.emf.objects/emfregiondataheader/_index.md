---
title: "EmfRegionDataHeader Klasse"
type: docs
weight: 250
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfregiondataheader/
---

**Summary:** The RegionDataHeader object describes the properties of a RegionData object.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfRegionDataHeader

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfRegionDataHeader()](#EmfRegionDataHeader__1) | Initialisiert eine neue Instanz der EmfRegionDataHeader-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Ruft ab oder legt ein 128‑Bit WMF RectL‑Objekt ([MS-WMF] Abschnitt 2.2.2.19) fest, das <br/>            die Grenzen der Region definiert. |
| count_rects | int | r/w | Ruft ab oder legt eine 32‑Bit vorzeichenlose Ganzzahl fest, die die Anzahl der Rechtecke in dieser Region angibt. |
| rgn_size | int | r/w | Ruft ab oder legt eine 32‑Bit vorzeichenlose Ganzzahl fest, die die Größe des Rechteckpuffers in Bytes angibt. |
| size | int | r/w | Ruft ab oder legt eine 32‑Bit vorzeichenlose Ganzzahl fest, die die Größe dieses Objekts in Bytes angibt. Dieser Wert MUSS 0x00000020 sein. |
| Typ | int | r/w | Ruft ab oder legt eine 32‑Bit vorzeichenlose Ganzzahl fest, die den Regionstyp angibt. Dieser SOLLTE <br/>            RDH_RECTANGLES (0x00000001) sein. |


### Constructor: EmfRegionDataHeader() {#EmfRegionDataHeader__1}


```
 EmfRegionDataHeader() 
```

Initialisiert eine neue Instanz der EmfRegionDataHeader-Klasse

