---
title: EmfPlusPenOptionalData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das EmfPlusPenOptionalData-Objekt gibt optionale Daten für einen Grafikstift an
type: docs
weight: 5680
url: /de/aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/
---
## EmfPlusPenOptionalData class

Das EmfPlusPenOptionalData-Objekt gibt optionale Daten für einen Grafikstift an

```csharp
public sealed class EmfPlusPenOptionalData : EmfPlusStructureObjectType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusPenOptionalData](emfpluspenoptionaldata)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [CompoundLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/compoundlinedata) { get; set; } | Erhält oder setzt das optionale EmfPlusCompoundLineData-Objekt (Abschnitt 2.2.2.9) , das ein Array von Fließkommawerten angibt, die die zusammengesetzte Linie eines Stifts definieren, die aus parallelen Linien und Leerzeichen besteht. Dieses Feld MUSS vorhanden sein, wenn das PenDataCompoundLine-Flag im PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist |
| [CustomEndCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customendcapdata) { get; set; } | Erhält oder setzt das optionale EmfPlusCustomEndCapData-Objekt (Abschnitt 2.2.2.11) , das die benutzerdefinierte Endkappenform definiert, die die Form ist, die am Ende einer mit diesem Stift gezeichneten Linie verwendet. Es kann eine von verschiedenen Formen haben, wie z. B. ein Quadrat, ein Kreis oder eine Raute. Dieses -Feld MUSS vorhanden sein, wenn das PenDataCustomEndCap-Flag im PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist |
| [CustomStartCapData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/customstartcapdata) { get; set; } | Ruft das optionale EmfPlusCustomStartCapData-Objekt (Abschnitt 2.2.2.15) ab oder legt es fest, das die benutzerdefinierte Anfangskappenform definiert, die die Form ist, die am Anfang einer mit diesem Stift gezeichneten Linie verwendet. Es kann ein beliebiges in verschiedenen Formen sein, z. B. ein Quadrat, ein Kreis oder eine Raute. Dieses Feld MUSS vorhanden sein, wenn das PenDataCustomStartCap-Flag im PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist |
| [DashedLineCapType](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinecaptype) { get; set; } | Ruft eine optionale 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Form für an beiden Enden jedes Bindestrichs in einer gestrichelten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineCap-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der DasshedLineCapType-Enumeration (Abschnitt 2.1.1.10) definiert sein. |
| [DashedLineData](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashedlinedata) { get; set; } | Ruft das optionale EmfPlusDasshedLineData-Objekt (Abschnitt 2.2.2.16) ab oder legt es fest, das die Längen von Bindestrichen und Leerzeichen in einer benutzerdefinierten -Strichlinie angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag PenDataDashedLine im Feld PenDataFlags des Objekts EmfPlusPenData gesetzt ist. |
| [DashOffset](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/dashoffset) { get; set; } | Ruft einen optionalen 32-Bit-Gleitkommawert ab oder legt diesen fest, der den -Abstand vom Anfang einer Zeile bis zum Anfang des ersten Leerzeichens in einem gestrichelten Linienmuster angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataDashedLineOffset-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist. |
| [EndCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/endcap) { get; set; } | Ruft eine optionale 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Form für das Ende einer Zeile im CustomEndCapData-Feld angibt. Dieses -Feld MUSS vorhanden sein, wenn das PenDataEndCap-Flag im -PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineCapType-Enumeration definiert sein. |
| [Join](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/join) { get; set; } | Ruft eine optionale vorzeichenbehaftete 32-Bit-Ganzzahl ab oder legt diese fest, die angibt, wie zwei Linien verbunden werden, die mit demselben Stift gezeichnet werden und deren Enden sich treffen. Dieses Feld MUSS vorhanden sein, wenn das PenDataJoin-Flag in dem PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist, und der -Wert MUSS in der LineJoinType-Enumeration (Abschnitt 2.1.1.19) definiert sein. |
| [LineStyle](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/linestyle) { get; set; } | Ruft eine optionale 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die den Stil angibt, der für mit diesem Stiftobjekt gezeichnete Linien verwendet wird. Dieses Feld MUSS vorhanden sein, wenn das PenDataLineStyle-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der LineStyle-Enumeration (Abschnitt 2.1.1.20) definiert sein. |
| [MiterLimit](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/miterlimit) { get; set; } | Ruft einen optionalen 32-Bit-Gleitkommawert ab oder legt diesen fest, der die -Gehrungsgrenze angibt, die das maximal zulässige Verhältnis der Gehrungslänge zur -Linienbreite darstellt. Die Gehrungslänge ist der Abstand vom Schnittpunkt der Linienwände auf der Innenseite der Verbindung bis zum Schnittpunkt der Linienwände außerhalb der Verbindung. Die Gehrungslänge kann groß sein, wenn der Winkel zwischen zwei Linien klein ist. Dieses Feld MUSS vorhanden sein, wenn das PenDataMiterLimit-Flag im PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist. |
| [PenAlignment](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/penalignment) { get; set; } | Ruft eine optionale 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die -Verteilung der Stiftbreite in Bezug auf die -Koordinaten der gezeichneten Linie angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataNonCenter-Flag im Feld PenDataFlags des EmfPlusPenData-Objekts gesetzt ist, und der Wert MUSS in der Aufzählung PenAlignment definiert sein (Abschnitt 2.1.1.24). |
| [StartCap](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/startcap) { get; set; } | Ruft eine optionale 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Form für den Beginn einer Zeile im Feld CustomStartCapData angibt. Dieses Feld MUSS vorhanden sein, wenn das PenDataStartCap-Flag im PenDataFlags-Feld des EmfPlusPenData-Objekts gesetzt ist, und der -Wert MUSS in der LineCapType-Enumeration (Abschnitt 2.1.1.18) definiert sein. |
| [TransformMatrix](../../aspose.imaging.fileformats.emf.emfplus.objects/emfpluspenoptionaldata/transformmatrix) { get; set; } | Ruft ein optionales EmfPlusTransformMatrix-Objekt (Abschnitt 2.2.2.47) ab oder legt es fest, das eine Weltraum-zu-Geräteraum-Transformation für den Stift angibt. Dieses Feld MUSS vorhanden sein, wenn das Flag PenDataTransform im Feld PenDataFlags des Objekts EmfPlusPenData gesetzt ist. |

### Siehe auch

* class [EmfPlusStructureObjectType](../emfplusstructureobjecttype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../aspose.imaging.fileformats.emf.emfplus.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
