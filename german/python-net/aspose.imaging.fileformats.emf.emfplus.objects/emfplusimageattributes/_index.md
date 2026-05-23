---
title: "EmfPlusImageAttributes Klasse"
type: docs
weight: 390
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimageattributes/
---

**Summary:** The EmfPlusImageAttributes object specifies how bitmap image<br/>            colors are manipulated during rendering.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusImageAttributes

**Inheritance:** EmfPlusGraphicsObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusImageAttributes()](#EmfPlusImageAttributes__1) | Initialisiert eine neue Instanz der EmfPlusImageAttributes Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| clamp_argb_32_color | int | r/w | Liest oder schreibt ein EmfPlusARGB‑Objekt (Abschnitt 2.2.2.1), das die zu verwendende Randfarbe angibt <br/>            wenn der WrapMode‑Wert WrapModeClamp ist. Diese Farbe ist sichtbar, wenn das <br/>            Quellrechteck, das von einem EmfPlusDrawImage‑Datensatz (Abschnitt 2.3.4.8) verarbeitet wird,<br/>            größer ist als das Bild selbst. |
| object_clamp | [EmfPlusObjectClamp](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusobjectclamp/) | r/w | Liest oder schreibt eine 32‑Bit vorzeichenbehaftete Ganzzahl, die das Clamping‑Verhalten des Objekts festlegt.<br/>            Sie wird erst verwendet, wenn dieses Objekt auf ein zu zeichnendes Bild angewendet wird. Dieser Wert MUSS einer der in der <br/>            folgenden Tabelle definierten Werte sein. |
| version | [EmfPlusGraphicsVersion](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusgraphicsversion/) | r/w | Liest oder setzt die Version. |
| wrap_mode | [EmfPlusWrapMode](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluswrapmode/) | r/w | Liest oder schreibt eine 32‑Bit vorzeichenlose Ganzzahl, die festlegt, wie Randbedingungen mit einem Wert aus der WrapMode‑Aufzählung (Abschnitt 2.1.1.34) behandelt werden. |


### Constructor: EmfPlusImageAttributes() {#EmfPlusImageAttributes__1}


```
 EmfPlusImageAttributes() 
```

Initialisiert eine neue Instanz der EmfPlusImageAttributes Klasse

