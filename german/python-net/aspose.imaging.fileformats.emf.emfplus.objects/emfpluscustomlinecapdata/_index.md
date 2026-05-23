---
title: "EmfPlusCustomLineCapData Klasse"
type: docs
weight: 270
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapdata/
---

**Summary:** The EmfPlusCustomLineCapData object specifies default data for a custom line cap.

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusCustomLineCapData

**Inheritance:** EmfPlusCustomBaseLineCap

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusCustomLineCapData()](#EmfPlusCustomLineCapData__1) | Initialisiert eine neue Instanz der EmfPlusCustomLineCapData Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| base_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Liest oder setzt 32‑Bit‑vorzeichenlose Ganzzahl, die den Wert aus der LineCap‑Aufzählung (Abschnitt 2.1.1.18) <br/>            angibt, auf dem die benutzerdefinierte Linienkapitelung basiert. |
| base_inset | float | r/w | Liest oder setzt 32‑Bit‑Gleitkommawert, der den Abstand zwischen dem Anfang <br/>            der Linienkapitelung und dem Ende der Linie angibt. |
| custom_line_cap_data_flags | [EmfPlusCustomLineCapDataFlags](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluscustomlinecapdataflags/) | r/w | Liest oder setzt 32‑Bit‑vorzeichenlose Ganzzahl, die die Daten im OptionalData‑Feld angibt. |
| fill_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt ein EmfPlusPointF-Objekt, das derzeit nicht verwendet wird. Es MUSS auf {0.0, 0.0} gesetzt werden. |
| optional_data | [EmfPlusCustomLineCapOptionalData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomlinecapoptionaldata/) | r/w | Liest oder setzt optional ein EmfPlusCustomLineCapOptionalData-Objekt (Abschnitt 2.2.2.14)<br/>             das zusätzliche Daten für die benutzerdefinierte Grafiklinienkapitelung angibt. Der spezifische Inhalt dieses Feldes wird bestimmt <br/>            durch den Wert des CustomLineCapDataFlags‑Feldes. |
| stroke_end_cap | int | r/w | Liest oder setzt 32‑Bit‑vorzeichenlose Ganzzahl, die den Wert in der LineCap‑Aufzählung angibt, der bestimmt, welche <br/>            Linienkapitelung am Ende der zu zeichnenden Linie verwendet werden soll. |
| stroke_hot_spot | [PointF](/imaging/python-net/aspose.imaging/pointf/) | r/w | Liest oder setzt ein EmfPlusPointF-Objekt, das derzeit nicht verwendet wird. Es MUSS auf {0.0, 0.0} gesetzt werden. |
| stroke_join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Liest oder setzt 32‑Bit‑vorzeichenlose Ganzzahl, die den Wert in der LineJoin‑Aufzählung <br/>            (Abschnitt 2.1.1.19) angibt, welche festlegt, wie zwei Linien, die mit demselben Stift gezeichnet werden und deren Enden sich treffen, verbunden werden. An der Schnittstelle der beiden Linienenden <br/>            sorgt ein Linienübergang dafür, dass die Verbindung kontinuierlicher wirkt. |
| stroke_miter_limit | float | r/w | Liest oder setzt 32‑Bit‑Gleitkommawert, der die Begrenzung der Dicke<br/>             der Verbindung an einer Gehrungsecke enthält, indem das maximal zulässige Verhältnis<br/>             von Gehrungslänge zu Linienbreite festgelegt wird. |
| stroke_start_cap | int | r/w | Liest oder setzt 32‑Bit‑vorzeichenlose Ganzzahl, die den Wert in der LineCap‑Aufzählung angibt, der die <br/>            Linienkapitelung am Anfang der zu zeichnenden Linie bestimmt. |
| width_scale | float | r/w | Liest oder setzt 32‑Bit‑Gleitkommawert, der den Betrag angibt, um den die benutzerdefinierte Linienkapitelung in Bezug auf die Breite des EmfPlusPen-<br/>             Objekts (Abschnitt 2.2.1.7) skaliert wird, das zum Zeichnen der Linien verwendet wird. |


### Constructor: EmfPlusCustomLineCapData() {#EmfPlusCustomLineCapData__1}


```
 EmfPlusCustomLineCapData() 
```

Initialisiert eine neue Instanz der EmfPlusCustomLineCapData Klasse

