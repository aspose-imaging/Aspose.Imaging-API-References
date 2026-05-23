---
title: "EmfFormat Klasse"
type: docs
weight: 60
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfformat/
---

**Summary:** The EmrFormat object contains information that identifies the format of image data in an<br/>            EMR_COMMENT_MULTIFORMATS record(section 2.3.3.4.3).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfFormat

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfFormat()](#EmfFormat__1) | Initialisiert eine neue Instanz der EmfFormat Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| off_data | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die den Offset zu den Daten vom <br/>            Beginn des Identifikatorfeldes in einem EMR_COMMENT_PUBLIC‑Datensatz (Abschnitt 2.3.3.4) angibt. <br/>            Der Offset MUSS 32‑Bit ausgerichtet sein. |
| signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die das Format der Bilddaten angibt. <br/>            Dieser Wert MUSS in der FormatSignature‑Aufzählung (Abschnitt 2.1.14) enthalten sein. |
| size_data | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Größe der Daten in Bytes angibt |
| version | int | r/w | Liest oder setzt eine 32‑Bit vorzeichenlose Ganzzahl, die die Versionsnummer des Formats angibt. <br/>            Wenn das Signaturfeld ein encapsulated PostScript (EPS) angibt, <br/>            muss dieser Wert 0x00000001 sein; andernfalls MUSS dieser Wert ignoriert werden. |


### Constructor: EmfFormat() {#EmfFormat__1}


```
 EmfFormat() 
```

Initialisiert eine neue Instanz der EmfFormat Klasse

