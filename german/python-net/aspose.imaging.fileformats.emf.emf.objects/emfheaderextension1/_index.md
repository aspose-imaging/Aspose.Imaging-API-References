---
title: "EmfHeaderExtension1 Klasse"
type: docs
weight: 90
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---

**Summary:** The HeaderExtension1 object defines the first extension to the EMF metafile header. <br/>            It adds support for a PixelFormatDescriptor object (section 2.2.22) and OpenGL <br/>            [OPENGL] records (section 2.3.9).

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfHeaderExtension1

**Inheritance:** EmfHeaderObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfHeaderExtension1()](#EmfHeaderExtension1__1) | Initialisiert eine neue Instanz der EmfHeaderExtension1‑Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| b_open_gl | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die angibt, ob OpenGL‑Befehle in der Metadatei vorhanden sind.<br/>            0x00000000 OpenGL‑Einträge sind nicht in der Metadatei vorhanden.<br/>            0x00000001 OpenGL‑Einträge sind in der Metadatei vorhanden. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF RectL Objekt ([MS-WMF] section 2.2.2.19), das die rechteckigen inklusiven‑inklusiven <br/>            Grenzen in Geräte‑Einheiten des kleinsten Rechtecks angibt, das um das im Metafile gespeicherte Bild gezeichnet werden kann. |
| Bytes | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe des Metafiles in Bytes angibt. |
| cb_pixel_format | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Größe des PixelFormatDescriptor‑Objekts angibt. <br/>            Dies MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist. |
| device | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt ein WMF SizeL Objekt ([MS-WMF] section 2.2.2.22), das die Größe des Referenzgeräts in Pixeln angibt. |
| frame | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt ein WMF RectL Objekt, das die rechteckigen inklusiven‑inklusiven Abmessungen in .01‑Millimeter <br/>            Einheiten eines Rechtecks angibt, das das im Metafile gespeicherte Bild umschließt. |
| handles | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Grafikobjekte angibt, die während der Verarbeitung des Metafiles verwendet werden. |
| millimeters | [Size](/imaging/python-net/aspose.imaging/size/) | r/w | Liest oder setzt ein WMF SizeL Objekt, das die Größe des Referenzgeräts in Millimetern angibt. |
| n_desription | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Zeichen im Array <br/>            angibt, das die Beschreibung des Inhalts des Metafiles enthält. Dies ist Null, wenn keine Beschreibungszeichenkette vorhanden ist. |
| n_pal_entries | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Einträge in der Metafile‑<br/>            Palette angibt. Die Palette befindet sich im EMR_EOF‑Datensatz. |
| off_description | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Offset vom Beginn dieses <br/>            Datensatzes zum Array angibt, das die Beschreibung des Inhalts des Metafiles enthält. |
| off_pixel_format | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die den Offset zum PixelFormatDescriptor‑Objekt angibt.<br/>            Dies MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist. |
| record_signature | [EmfFormatSignature](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfformatsignature/) | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Signatur des Datensatzes angibt. Dieser MUSS ENHMETA_SIGNATURE sein, <br/>            aus der Aufzählung FormatSignature (Abschnitt 2.1.14). |
| Datensätze | int | r/w | Liest oder setzt eine 32‑Bit‑Ganzzahl ohne Vorzeichen, die die Anzahl der Datensätze im Metafile angibt. |
| reserviert | int | r/w | Liest oder setzt eine 16‑Bit‑Ganzzahl ohne Vorzeichen, die 0x0000 sein MUSS und die ignoriert werden MUSS. |
| valid | bool | r | Gibt einen Wert zurück, der angibt, ob dieses [EmfHeaderObject](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/) gültig ist. |
| version | int | r/w | Liest oder setzt Version (4 Bytes): Ein 32‑Bit‑vorzeichenloser Integer, der die EMF‑Metadatei‑Interoperabilität angibt. Dieser SOLLTE 0x00010000 sein. |


### Constructor: EmfHeaderExtension1() {#EmfHeaderExtension1__1}


```
 EmfHeaderExtension1() 
```

Initialisiert eine neue Instanz der EmfHeaderExtension1‑Klasse

