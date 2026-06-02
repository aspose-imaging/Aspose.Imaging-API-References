---
title: "EmfUniversalFontId Klasse"
type: docs
weight: 280
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfuniversalfontid/
---

**Summary:** The UniversalFontId object defines a mechanism for identifying fonts in EMF metafiles.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfUniversalFontId

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfUniversalFontId()](#EmfUniversalFontId__1) | Initialisiert eine neue Instanz der EmfUniversalFontId Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Prüfsumme | int | r/w | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der die Prüfsumme der Schriftart ist.<br/>
            Der Prüfsummenwert hat die folgenden Bedeutungen.<br/>
            0x00000000  Das Objekt ist eine Geräteschriftart. <br/>
            0x00000001  Das Objekt ist eine Type‑1‑Schriftart, die auf dem Client‑Computer installiert wurde und von <br/>
            dem PostScript‑Druckertreiber als Geräteschriftart aufgelistet wird. <br/>
            0x00000002  Das Objekt ist keine Schriftart, sondern ein Type‑1‑Rasterisierer. <br/>
            3 ≤ Wert   Das Objekt ist eine Bitmap-, Vektor- oder TrueType‑Schriftart bzw. eine von einem Type‑1‑Rasterisierer erstellte rasterisierte Schriftart. |
| index | int | r/w | Liest oder setzt einen 32‑Bit‑vorzeichenlosen Integer, der ein Index ist, der dem Schriftart‑Objekt zugeordnet ist. Der <br/>
            Bedeutungsinhalt dieses Feldes wird durch den Schrifttyp bestimmt. |


### Constructor: EmfUniversalFontId() {#EmfUniversalFontId__1}


```
 EmfUniversalFontId() 
```

Initialisiert eine neue Instanz der EmfUniversalFontId Klasse

