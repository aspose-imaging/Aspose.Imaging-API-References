---
title: "AutoMaskingArgs Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.imaging.masking.options/automaskingargs/
---

**Summary:** Represents the arguments that are specified for automated masking methods

**Module:** [aspose.imaging.masking.options](/imaging/python-net/aspose.imaging.masking.options/)

**Full Name:** aspose.imaging.masking.options.AutoMaskingArgs

**Inheritance:** IMaskingArgs

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [AutoMaskingArgs()](#AutoMaskingArgs__1) | Initialisiert eine neue Instanz der AutoMaskingArgs Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| max_iteration_number | int | r/w | Liest oder setzt die maximale Anzahl von Iterationen. |
| number_of_objects | int | r/w | Liest oder setzt die Anzahl der Objekte<br/>            um das Ausgangsbild zu trennen (optional), Standardwert ist 2 (Objekt und Hintergrund). |
| objects_points | [Point[][]](/imaging/python-net/aspose.imaging/point[]/) | r/w | Liest oder setzt die Punkte, die zu getrennten Objekten gehören (optional)<br/>            NumberOfObjects-Koordinaten, die zu NumberOfObjects Objekten des Ausgangsbildes gehören.<br/>            Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen. |
| objects_rectangles | [Rectangle[]](/imaging/python-net/aspose.imaging/rectangle/) | r/w | Liest oder setzt die Rechtecke der Objekte, die zu getrennten Objekten gehören (optional).<br/>            Dieser Parameter wird verwendet, um die Präzision der Segmentierungsmethode zu erhöhen. |
| orphaned_points | [Point[]](/imaging/python-net/aspose.imaging/point/) | r/w | Liest oder setzt die Punkte, die keinem Objekt mehr zugeordnet sind (optional).<br/>            Dieser Parameter wird nur im Fall einer erneuten Segmentierung verwendet. |
| precision | float | r/w | Liest oder setzt die Präzision der Segmentierungsmethode (optional). |


### Constructor: AutoMaskingArgs() {#AutoMaskingArgs__1}


```
 AutoMaskingArgs() 
```

Initialisiert eine neue Instanz der AutoMaskingArgs Klasse

