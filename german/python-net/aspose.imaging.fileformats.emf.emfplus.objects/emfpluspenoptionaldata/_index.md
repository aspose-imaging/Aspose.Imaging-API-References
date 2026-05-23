---
title: "Klasse EmfPlusPenOptionalData"
type: docs
weight: 560
url: /de/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---

**Summary:** The EmfPlusPenOptionalData object specifies optional data for a graphics pen

**Module:** [aspose.imaging.fileformats.emf.emfplus.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.objects.EmfPlusPenOptionalData

**Inheritance:** EmfPlusStructureObjectType

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfPlusPenOptionalData()](#EmfPlusPenOptionalData__1) | Initialisiert eine neue Instanz der Klasse EmfPlusPenOptionalData |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| compound_line_data | [EmfPlusCompoundLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscompoundlinedata/) | r/w | Ruft ab oder legt ein optionales EmfPlusCompoundLineData‑Objekt fest (Abschnitt 2.2.2.9) <br/>            das ein Array von Gleitkommawerten definiert, die<br/>            die zusammengesetzte Linie eines Stifts festlegen, die aus parallelen Linien<br/>            und Lücken besteht. Dieses Feld MUSS vorhanden sein, wenn das<br/>            PenDataCompoundLine‑Flag im Feld PenDataFlags <br/>            des EmfPlusPenData‑Objekts gesetzt ist. |
| custom_end_cap_data | [EmfPlusCustomEndCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomendcapdata/) | r/w | Ruft ab oder legt ein optionales EmfPlusCustomEndCapData‑Objekt fest (Abschnitt 2.2.2.11) <br/>            das die benutzerdefinierte Endkap-Form definiert, die am Ende einer mit diesem Stift gezeichneten Linie verwendet wird. Es kann jede beliebige<br/>            Form sein, z. B. ein Quadrat, ein Kreis oder ein Diamant. Dieses<br/>            Feld MUSS vorhanden sein, wenn das PenDataCustomEndCap‑Flag<br/>            im Feld PenDataFlags des EmfPlusPenData‑Objekts gesetzt ist. |
| custom_start_cap_data | [EmfPlusCustomStartCapData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfpluscustomstartcapdata/) | r/w | Ruft ab oder legt ein optionales EmfPlusCustomStartCapData‑Objekt fest (Abschnitt 2.2.2.15) <br/>            das die benutzerdefinierte Startkap-Form definiert, die am Anfang einer mit diesem Stift gezeichneten Linie verwendet wird. Es kann jede<br/>            beliebige Form sein, z. B. ein Quadrat, ein Kreis oder ein Diamant.<br/>            Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomStartCap‑Flag<br/>            im Feld PenDataFlags des EmfPlusPenData‑Objekts gesetzt ist. |
| dash_offset | float | r/w | Ruft ab oder legt einen optionalen 32‑Bit Gleitkommawert fest, der die<br/>            Entfernung vom Anfang einer Linie bis zum Beginn des<br/>            ersten Leerraums in einem gestrichelten Linienmuster angibt. Dieses Feld MUSS<br/>            vorhanden sein, wenn das PenDataDashedLineOffset‑Flag im<br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist. |
| dashed_line_cap_type | [EmfPlusDashedLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusdashedlinecaptype/) | r/w | Ruft ab oder legt eine optionale 32‑Bit vorzeichenbehaftete Ganzzahl fest, die die Form für<br/>            beide Enden jedes Strichs in einer gestrichelten Linie angibt. Dieses Feld MUSS<br/>            vorhanden sein, wenn das PenDataDashedLineCap‑Flag im<br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der<br/>            Wert MUSS in der Aufzählung DashedLineCapType definiert sein<br/>            (Abschnitt 2.1.1.10). |
| dashed_line_data | [EmfPlusDashedLineData](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusdashedlinedata/) | r/w | Ruft ab oder legt ein optionales EmfPlusDashedLineData‑Objekt fest (Abschnitt 2.2.2.16) <br/>            das die Längen von Strichen und Lücken in einer benutzerdefinierten<br/>            gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLine‑<br/>            Flag im PenDataFlags‑Feld des EmfPlusPenData<br/>            Objekts gesetzt ist. |
| end_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Ruft ab oder legt eine optionale 32‑Bit vorzeichenbehaftete Ganzzahl fest, die die Form<br/>             für das Ende einer Linie im Feld CustomEndCapData angibt. Dieses<br/>            Feld MUSS vorhanden sein, wenn das PenDataEndCap‑Flag im<br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der Wert<br/>            MUSS in der Aufzählung LineCapType definiert sein. |
| join | [EmfPlusLineJoinType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinejointype/) | r/w | Ruft ab oder legt eine optionale 32‑Bit vorzeichenbehaftete Ganzzahl fest, die angibt, wie<br/>             zwei Linien, die mit demselben Stift gezeichnet wurden und deren Enden zusammenstoßen, verbunden werden sollen.<br/>            Dieses Feld MUSS vorhanden sein, wenn das PenDataJoin‑Flag im<br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der<br/>            Wert MUSS in der Aufzählung LineJoinType definiert sein<br/>            (Abschnitt 2.1.1.19). |
| line_style | [EmfPlusLineStyle](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinestyle/) | r/w | Ruft ab oder legt eine optionale 32‑Bit vorzeichenbehaftete Ganzzahl fest, die den Stil<br/>            angibt, der für Linien verwendet wird, die mit diesem Stiftobjekt gezeichnet werden. Dieses Feld MUSS<br/>            vorhanden sein, wenn das PenDataLineStyle‑Flag im<br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und der<br/>            Wert MUSS in der Aufzählung LineStyle definiert sein<br/>            (Abschnitt 2.1.1.20). |
| miter_limit | float | r/w | Ruft den optionalen 32‑Bit‑Gleitkommawert ab oder legt ihn fest, der die Gehrung <br/>            Grenze angibt, die das maximal zulässige Verhältnis von Gehrungslänge zu<br/>            Linienbreite darstellt. Die Gehrungslänge ist der Abstand von der<br/>            Schnittstelle der Linienwände auf der Innenseite der Verbindung zur <br/>            Schnittstelle der Linienwände auf der Außenseite der Verbindung. <br/>            Die Gehrungslänge kann groß sein, wenn der Winkel zwischen zwei <br/>            Linien klein ist. Dieses Feld MUSS vorhanden sein, wenn das <br/>            PenDataMiterLimit‑Flag im PenDataFlags‑Feld <br/>            des EmfPlusPenData‑Objekts gesetzt ist. |
| pen_alignment | [EmfPlusPenAlignment](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluspenalignment/) | r/w | Ruft die optionale 32‑Bit‑Ganzzahl ab oder legt sie fest, die die <br/>            Verteilung der Stiftbreite in Bezug auf die <br/>            Koordinaten der zu zeichnenden Linie angibt. Dieses Feld MUSS <br/>            vorhanden sein, wenn das PenDataNonCenter‑Flag im <br/>            PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist, und <br/>            der Wert MUSS in der PenAlignment‑Aufzählung (Abschnitt 2.1.1.24) definiert sein. |
| start_cap | [EmfPlusLineCapType](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfpluslinecaptype/) | r/w | Ruft die optionale 32‑Bit‑Ganzzahl ab oder legt sie fest, die die Form für<br/>             den Anfang einer Linie im CustomStartCapData‑Feld angibt. <br/>            Dieses Feld MUSS vorhanden sein, wenn das PenDataStartCap‑Flag gesetzt ist <br/>            im PenDataFlags‑Feld des EmfPlusPenData‑Objekts, und der<br/>             Wert MUSS in der LineCapType‑Aufzählung <br/>            (Abschnitt 2.1.1.18) definiert sein. |
| transform_matrix | [Matrix](/imaging/python-net/aspose.imaging/matrix/) | r/w | Ruft das optionale EmfPlusTransformMatrix‑Objekt ab oder legt es fest (Abschnitt 2.2.2.47) <br/>            das eine Welt‑zu‑Geräte‑Raum‑Transformation für <br/>            den Stift angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataTransform‑<br/>            Flag im PenDataFlags‑Feld des EmfPlusPenData‑Objekts gesetzt ist. |


### Constructor: EmfPlusPenOptionalData() {#EmfPlusPenOptionalData__1}


```
 EmfPlusPenOptionalData() 
```

Initialisiert eine neue Instanz der Klasse EmfPlusPenOptionalData

