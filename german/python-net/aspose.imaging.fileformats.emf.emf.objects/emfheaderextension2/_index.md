---
title: "EmfHeaderExtension2 Klasse"
type: docs
weight: 100
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension2/
---

**Summary:** The HeaderExtension2 object defines the second extension to the EMF metafile header. It adds the<br/>            ability to measure device surfaces in micrometers, which enhances the resolution and scalability of EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension2

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfHeaderExtension2()](#EmfHeaderExtension2__1) | Initialisiert eine neue Instanz der EmfHeaderExtension2 Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF RectL Objekt ([MS-WMF] section 2.2.2.19), das die rechteckigen inklusiven‑inklusiven <br/>            Grenzen in Geräte‑Einheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann. |
| Bytes | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe des Metafiles in Bytes angibt. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt ein WMF SizeL Objekt ([MS-WMF] section 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt. |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF RectL Objekt, das die rechteckigen inklusiven‑inklusiven Abmessungen in .01‑Millimeter <br/>            Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt. |
| handles | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Grafikobjekte angibt, die während der Verarbeitung des Metafiles verwendet werden. |
| micrometers_x | int | r/w | Liest oder setzt die 32‑Bit‑horizontale Größe des Anzeigegeräts, für das das Metafile‑Bild erzeugt wurde, in Mikrometern. |
| micrometers_y | int | r/w | Liest oder setzt die 32‑Bit‑vertikale Größe des Anzeigegeräts, für das das Metafile‑Bild erzeugt wurde, in Mikrometern. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt ein WMF SizeL Objekt, das die Größe des Referenzgeräts in Millimetern angibt. |
| n_desription | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Zeichen im Array <br/>            angibt, das die Beschreibung des Inhalts des Metafiles enthält. Dies ist Null, wenn keine Beschreibungszeichenkette vorhanden ist. |
| n_pal_entries | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge in der Metafile‑<br/>            Palette angibt. Die Palette befindet sich im EMR_EOF‑Datensatz. |
| off_description | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Offset vom Beginn dieses <br/>            Datensatzes zum Array angibt, das die Beschreibung des Inhalts des Metafiles enthält. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Signatur des Datensatzes angibt. Dieser MUSS ENHMETA_SIGNATURE sein, <br/>            aus der Aufzählung FormatSignature (Abschnitt 2.1.14). |
| Datensätze | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Datensätze im Metafile angibt. |
| reserviert | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl ohne Vorzeichen, die 0x0000 sein MUSS und die ignoriert werden MUSS. |
| valid | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) gültig ist. |
| version | int | r/w | Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die EMF‑Metadatei‑Interoperabilität angibt. Dieser SOLLTE 0x00010000 sein. |


### Constructor: EmfHeaderExtension2() {#EmfHeaderExtension2__1}


```
 EmfHeaderExtension2() 
```

Initialisiert eine neue Instanz der EmfHeaderExtension2 Klasse

