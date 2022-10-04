---
title: EmfCreateMonoBrush
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der Datensatz EMR_CREATEMONOBRUSH definiert einen monochromen Musterpinsel für Grafikoperationen. Das Muster wird durch eine monochrome DIB angegeben.
type: docs
weight: 3500
url: /de/net/aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/
---
## EmfCreateMonoBrush class

Der Datensatz EMR_CREATEMONOBRUSH definiert einen monochromen Musterpinsel für Grafikoperationen. Das Muster wird durch eine monochrome DIB angegeben.

```csharp
public sealed class EmfCreateMonoBrush : EmfObjectCreationRecordType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfCreateMonoBrush](emfcreatemonobrush)(EmfRecord) | Initialisiert eine neue Instanz von[`EmfCreateMonoBrush`](../emfcreatemonobrush) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BitmapBuffer](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/bitmapbuffer) { get; set; } | Ruft ab oder legt einen Puffer fest, der eine gepackte DIB in Form eines WMF DeviceIndependentBitmap-Objekts enthält ([MS-WMF] Abschnitt 2.2.2.9). Es muss nicht mit dem festen Teil des EMR_CREATEDIBPATTERNBRUSHPT-Datensatzes zusammenhängen. |
| [IhBrush](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/ihbrush) { get; set; } | Ruft eine vorzeichenlose 32-Bit-Ganzzahl ab oder legt sie fest, die den Index des Musterpinselobjekts monochrome in der EMF-Objekttabelle (Abschnitt 3.1.1.1) angibt. Dieser Index MUSS gespeichert werden, damit dieses Objekt wiederverwendet oder geändert werden kann. |
| [Size](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/size) { get; set; } | Ruft die Größe des Datensatzes ab oder legt sie fest |
| [Type](../../aspose.imaging.fileformats.emf.emf.records/emfrecord/type) { get; set; } | Ruft den Typ ab oder legt ihn fest. |
| [Usage](../../aspose.imaging.fileformats.emf.emf.records/emfcreatemonobrush/usage) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die angibt, wie Werte in der Tabelle color im DIB-Header zu interpretieren sind. Dieser Wert MUSS in der DIBColors-Enumeration (Abschnitt 2.1.9) enthalten sein. |

### Siehe auch

* class [EmfObjectCreationRecordType](../emfobjectcreationrecordtype)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Records](../../aspose.imaging.fileformats.emf.emf.records)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->