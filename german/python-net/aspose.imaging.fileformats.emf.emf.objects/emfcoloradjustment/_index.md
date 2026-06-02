---
title: "EmfColorAdjustment Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---

**Summary:** The ColorAdjustment object defines values for adjusting the colors in source bitmaps in bit-block transfers.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfColorAdjustment

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [EmfColorAdjustment()](#EmfColorAdjustment__1) | Initialisiert eine neue Instanz der EmfColorAdjustment Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| blue_gamma | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der den n‑ten Potenz‑Gamma‑Korrekturwert für den <br/>            blauen Primärfarbanteil der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. <br/>            Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur NICHT durchgeführt werden MUSS. |
| Helligkeit | int | r/w | Ruft einen 16‑Bit‑signed Integer ab oder legt ihn fest, der die Helligkeit angibt, die auf das Quellobjekt angewendet wird. <br/>            Dieser Wert SOLLTE im Bereich von –100 bis 100.<br/>            Ein Wert von null bedeutet, dass die Helligkeitsanpassung NICHT durchgeführt werden MUSS. |
| colorfullness | int | r/w | Ruft einen 16‑Bit‑signed Integer ab oder legt ihn fest, der die Farbsättigung angibt, die auf das Quellobjekt angewendet wird. <br/>            Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. <br/>            Ein Wert von null bedeutet, dass die Farbsättigungsanpassung NICHT durchgeführt werden MUSS |
| Kontrast | int | r/w | Ruft einen 16‑Bit‑signed Integer ab oder legt ihn fest, der den Kontrast angibt, der auf das Quellobjekt angewendet wird. <br/>            Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von null bedeutet, dass die Kontrastanpassung NICHT durchgeführt werden MUSS. |
| green_gamma | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der den n‑ten Potenz‑Gamma‑Korrekturwert für den grünen Primärfarbanteil der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. <br/>            Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur NICHT durchgeführt werden MUSS. |
| illuminant_index | [EmfIlluminant](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfilluminant/) | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der den Typ der Standardlichtquelle angibt, unter der das <br/>            Bild betrachtet wird, aus der Illuminant‑Aufzählung (Abschnitt 2.1.19). |
| red_gamma | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der den n‑ten Potenz‑Gamma‑Korrekturwert für den roten Primärfarbanteil der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen.<br/>            Ein Wert von 10.000 bedeutet, dass die Gamma‑Korrektur NICHT durchgeführt werden MUSS. |
| red_green_tint | int | r/w | Ruft einen 16‑Bit‑signed Integer ab oder legt ihn fest, der die Menge der Rot‑ oder Grün‑Tönungsanpassung angibt, die auf das Quellobjekt angewendet wird. <br/>            Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. <br/>            Positive Zahlen passen Richtung Rot an und negative Zahlen Richtung Grün. <br/>            Ein Wert von null bedeutet, dass die Tönungsanpassung NICHT durchgeführt werden MUSS |
| reference_black | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der die Schwarzreferenz für die Quellfarben angibt. <br/>            Alle Farben, die dunkler als dieser Wert sind, werden als Schwarz behandelt. <br/>            Dieser Wert SOLLTE im Bereich von null bis 4.000 liegen. |
| reference_white | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der die Weißreferenz für die Quellfarben angibt. <br/>            Alle Farben, die heller als dieser Wert sind, werden als Weiß behandelt. <br/>            Dieser Wert SOLLTE im Bereich von 6.000 bis 10.000 liegen. |
| size | int | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der die Größe dieses Objekts in Bytes angibt. Dieser Wert MUSS 0x0018 sein. |
| values | [EmfColorAdjustmentEnum](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/emfcoloradjustmentenum/) | r/w | Ruft einen 16‑Bit‑unsigned Integer ab oder legt ihn fest, der angibt, wie das Ausgabebild vorzubereiten ist. Dieses Feld kann <br/>            auf NULL gesetzt werden oder auf jede Kombination von Werten in der ColorAdjustment‑Aufzählung (Abschnitt 2.1.5). |


### Constructor: EmfColorAdjustment() {#EmfColorAdjustment__1}


```
 EmfColorAdjustment() 
```

Initialisiert eine neue Instanz der EmfColorAdjustment Klasse

