---
title: EmfPlusDrawImagePoints
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der EmfPlusDrawImagePoints-Datensatz spezifiziert das Zeichnen eines skalierten Bildes innerhalb eines Parallelogramms.
type: docs
weight: 5970
url: /de/aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/
---
## EmfPlusDrawImagePoints class

Der EmfPlusDrawImagePoints-Datensatz spezifiziert das Zeichnen eines skalierten Bildes innerhalb eines Parallelogramms.

```csharp
public sealed class EmfPlusDrawImagePoints : EmfPlusDrawingRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfPlusDrawImagePoints](emfplusdrawimagepoints)(EmfPlusRecord) | Initialisiert eine neue Instanz von[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [ApplyingAnEffect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/applyinganeffect) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob [ein Effekt angewendet wird]. Dieses Bit zeigt an, dass das Rendern des Bildes das Anwenden eines Effekts umfasst. Wenn gesetzt, MUSS ein Objekt der Effektklasse in einem früheren EmfPlusSerializableObject-Datensatz (Abschnitt 2.3.5.2). |
| [Compressed](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/compressed) { get; set; } | Erhält oder setzt einen Wert, der angibt, ob PointData komprimiert ist. Dieses Bit gibt an, ob das PointData-Feld komprimierte Daten angibt. Falls gesetzt, gibt PointData absolute Positionen im Koordinatenraum mit 16-Bit-Integer- -Koordinaten an. Wenn leer, gibt PointData absolute Positionen im Koordinatenraum mit 32-Bit-Gleitkommakoordinaten an. Hinweis Wenn das P-Flag (unten) gesetzt ist, ist dieses Flag undefiniert und MUSS ignoriert werden. |
| virtual [DataSize](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/datasize) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes von Daten im folgenden RecordData-Feld definieren MUSS. Diese Nummer enthält nicht den 12-Byte-Datensatzheader. |
| virtual [Flags](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/flags) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die für einige Datensätze Informationen darüber enthält, wie die Operation ausgeführt werden soll, und über die Struktur des Datensatzes. |
| [ImageAttributesId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/imageattributesid) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Index des optionalen EmfPlusImageAttributes-Objekts (Abschnitt 2.2.1.5) in der EMF+-Objekttabelle enthält. |
| [ObjectId](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/objectid) { get; set; } | Ruft den Objektbezeichner ab oder setzt ihn. Der Index eines EmfPlusImage-Objekts (Abschnitt 2.2.1.4) in der EMF+ -Objekttabelle, der das zu rendernde Bild angibt. Der Wert MUSS null bis einschließlich 63 sein. |
| [PointData](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/pointdata) { get; set; } | Ruft ein Array von Count-Punkten ab oder legt es fest, die drei Punkte eines Parallelogramms angeben. Die drei Punkte repräsentieren die obere linke, obere rechte und untere linke Ecke des -Parallelogramms. Der vierte Punkt des Parallelogramms wird aus den ersten drei extrapoliert. Auf den -Teil des Bildes, der durch das SrcRect-Feld angegeben wird, SOLLTEN Skalierungs- und Scherungs -Transformationen angewendet werden, falls erforderlich, um in das Parallelogramm zu passen. |
| [Relative](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/relative) { get; set; } | Ruft einen Wert ab oder legt einen Wert fest, der angibt, ob dies der Fall ist[`EmfPlusDrawImagePoints`](../emfplusdrawimagepoints)ist relativ. Dieses Bit gibt an, ob das PointData-Feld relative oder absolute Positionen angibt. Wenn gesetzt, gibt jedes Element in PointData eine Position im Koordinatenraum an, die relativ zu der durch das vorherige Element im Array angegebenen Position ist. Im Fall des ersten Elements in PointData wird eine frühere Position bei den Koordinaten (0,0) angenommen. Wenn leer, gibt PointData absolute Positionen gemäß dem C-Flag an. Hinweis Wenn dieses Flag gesetzt ist, ist das C-Flag (oben) undefiniert und MUSS ignoriert werden. |
| virtual [Size](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/size) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die 32-Bit-ausgerichtete Anzahl von Bytes im gesamten Datensatz angibt, einschließlich des 12-Byte-Datensatzheaders und datensatzspezifischer Daten. |
| [SrcRect](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcrect) { get; set; } | Ruft ein EmfPlusRectF-Objekt (Abschnitt 2.2.2.39) ab oder legt es fest, das einen Teil des zu rendernden Bilds definiert. |
| [SrcUnit](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusdrawimagepoints/srcunit) { get; set; } | Ruft eine 32-Bit-Ganzzahl mit Vorzeichen ab oder legt diese fest, die die Einheiten des SrcRect-Felds definiert. Es MUSS der UnitPixel-Wert der UnitType-Enumeration sein (Abschnitt 2.1.1.33). |
| [Type](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrecord/type) { get; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab, die den Datensatztyp identifiziert. |

### Bemerkungen

Ein EmfPlusImage kann entweder eine Bitmap oder eine Metadatei spezifizieren. Farben in einem Bild können während des Renderns manipuliert werden. Sie können korrigiert, abgedunkelt, aufgehellt und entfernt werden.

### Siehe auch

* class [EmfPlusDrawingRecordType](../emfplusdrawingrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Records](../../aspose.imaging.fileformats.emf.emfplus.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
