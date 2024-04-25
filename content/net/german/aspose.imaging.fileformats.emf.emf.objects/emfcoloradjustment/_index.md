---
title: EmfColorAdjustment
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das ColorAdjustment-Objekt definiert Werte zum Anpassen der Farben in Quellbitmaps bei Bitblockübertragungen.
type: docs
weight: 2930
url: /de/aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/
---
## EmfColorAdjustment class

Das ColorAdjustment-Objekt definiert Werte zum Anpassen der Farben in Quellbitmaps bei Bitblockübertragungen.

```csharp
public sealed class EmfColorAdjustment : EmfObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfColorAdjustment](emfcoloradjustment)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BlueGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/bluegamma) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Gammakorrekturwert der n-ten Potenz für die blaue Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass keine Gammakorrektur durchgeführt werden darf. |
| [Brightness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/brightness) { get; set; } | Ruft eine 16-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die auf das Quellobjekt anzuwendende Helligkeitsmenge angibt. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von Null bedeutet, dass keine Helligkeitsanpassung durchgeführt werden darf. |
| [Colorfullness](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/colorfullness) { get; set; } | Ruft eine vorzeichenbehaftete 16-Bit-Ganzzahl ab oder legt diese fest, die die auf das Quellobjekt anzuwendende Farbigkeit angibt. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von Null bedeutet, dass eine Farbanpassung NICHT durchgeführt werden darf |
| [Contrast](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/contrast) { get; set; } | Ruft eine vorzeichenbehaftete 16-Bit-Ganzzahl ab oder legt diese fest, die die auf das Quellobjekt anzuwendende Kontraststärke angibt. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Ein Wert von Null bedeutet, dass keine Kontrastanpassung durchgeführt werden darf. |
| [GreenGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/greengamma) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Gammakorrekturwert der n-ten Potenz für die grüne -Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass keine Gammakorrektur durchgeführt werden darf. |
| [IlluminantIndex](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/illuminantindex) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Typ der Standardlichtquelle angibt, unter der das -Bild betrachtet wird, aus der Illuminant-Enumeration (Abschnitt 2.1.19). |
| [RedGamma](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgamma) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die den Gammakorrekturwert der n-ten Potenz für die rote -Primärfarbe der Quellfarben angibt. Dieser Wert SOLLTE im Bereich von 2.500 bis 65.000 liegen. Ein Wert von 10.000 bedeutet, dass keine Gammakorrektur durchgeführt werden darf. |
| [RedGreenTint](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/redgreentint) { get; set; } | Ruft eine vorzeichenbehaftete 16-Bit-Ganzzahl ab oder legt sie fest, die den Betrag der Rot- oder Grüntonanpassung angibt, die auf das Quellobjekt angewendet werden soll. Dieser Wert SOLLTE im Bereich von –100 bis 100 liegen. Positive Zahlen werden in Richtung Rot und negative Zahlen in Richtung Grün angepasst. Ein Wert von Null bedeutet, dass die Farbtoneinstellung NICHT durchgeführt werden darf |
| [ReferenceBlack](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referenceblack) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Schwarzreferenz für die Quellfarben angibt. Alle dunkleren Farben werden als Schwarz behandelt. Dieser Wert SOLLTE im Bereich von null bis 4.000 liegen |
| [ReferenceWhite](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/referencewhite) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Weißreferenz für die Quellfarben angibt. Alle helleren Farben werden als Weiß behandelt. Dieser Wert SOLLTE im Bereich von 6.000 bis 10.000 liegen. |
| [Size](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/size) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Größe dieses Objekts in Byte angibt. Dies MUSS 0x0018. sein |
| [Values](../../aspose.imaging.fileformats.emf.emf.objects/emfcoloradjustment/values) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie das Ausgabebild vorbereitet wird. Dieses Feld kann auf NULL oder auf eine beliebige Kombination von Werten in der ColorAdjustment-Enumeration (Abschnitt 2.1.5) gesetzt werden. |

### Siehe auch

* class [EmfObject](../emfobject)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
