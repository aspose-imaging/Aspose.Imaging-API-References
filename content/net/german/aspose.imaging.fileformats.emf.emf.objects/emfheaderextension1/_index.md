---
title: EmfHeaderExtension1
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das HeaderExtension1-Objekt definiert die erste Erweiterung des EMF-Metadatei-Headers. Es fügt Unterstützung für ein PixelFormatDescriptor-Objekt Abschnitt 2.2.22 und OpenGL OPENGL-Datensätze Abschnitt 2.3.9 hinzu.
type: docs
weight: 2990
url: /de/aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/
---
## EmfHeaderExtension1 class

Das HeaderExtension1-Objekt definiert die erste Erweiterung des EMF-Metadatei-Headers. Es fügt Unterstützung für ein PixelFormatDescriptor-Objekt (Abschnitt 2.2.22) und OpenGL [OPENGL]-Datensätze (Abschnitt 2.3.9) hinzu.

```csharp
public sealed class EmfHeaderExtension1 : EmfHeaderObject
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [EmfHeaderExtension1](emfheaderextension1)() | Default_Constructor |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BOpenGl](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/bopengl) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die angibt, ob OpenGL-Befehle in der Metadatei vorhanden sind. 0x00000000 OpenGL-Einträge sind in der Metadatei nicht vorhanden. 0x00000001 OpenGL-Einträge sind in der Metadatei vorhanden. |
| [Bounds](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bounds) { get; set; } | Ruft ein WMF-RectL-Objekt ab oder legt es fest ([MS-WMF] Abschnitt 2.2.2.19), das die rechteckigen einschließenden -Grenzen in Geräteeinheiten des kleinsten Rechtecks angibt, das um das in der Metadatei gespeicherte Bild gezeichnet werden kann. |
| [Bytes](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/bytes) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Größe der Metadatei in Byte angibt. |
| [CbPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/cbpixelformat) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Größe des PixelFormatDescriptor-Objekts angibt. Dies MUSS 0x00000000 sein, wenn kein Pixelformat eingestellt ist |
| [Device](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/device) { get; set; } | Ruft ein WMF SizeL-Objekt ([MS-WMF] Abschnitt 2.2.2.22) ab oder legt es fest, das die Größe des Referenzgeräts in Pixeln angibt |
| [Frame](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/frame) { get; set; } | Ruft ein WMF RectL-Objekt ab oder legt es fest, das die rechteckigen inklusiven Abmessungen eines Rechtecks in Einheiten von 0,01 Millimetern angibt, das das in der Metadatei gespeicherte Bild umgibt. |
| [Handles](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/handles) { get; set; } | Ruft eine 16-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Anzahl der Grafikobjekte angibt, die während der Verarbeitung der Metadatei verwendet werden. |
| [Millimeters](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/millimeters) { get; set; } | Ruft ein WMF SizeL-Objekt ab oder legt es fest, das die Größe des Referenzgeräts in Millimetern angibt |
| [NDesription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/ndesription) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Anzahl der Zeichen im Array angibt, das die Beschreibung des Inhalts der Metadatei enthält. Dies ist null, wenn es keine Beschreibungszeichenfolge gibt. |
| [NPalEntries](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/npalentries) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Anzahl der Einträge in der Metadatei- -Palette angibt. Die Palette befindet sich im EMR_EOF record |
| [OffDescription](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/offdescription) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Offset vom Anfang dieses -Datensatzes zu dem Array angibt, das die Beschreibung des Inhalts der Metadatei enthält |
| [OffPixelFormat](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderextension1/offpixelformat) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die den Offset zum PixelFormatDescriptor-Objekt angibt. Dies MUSS 0x00000000 sein, wenn kein Pixelformat festgelegt ist. |
| [Records](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/records) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt sie fest, die die Anzahl der Datensätze in der Metadatei angibt |
| [RecordSignature](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/recordsignature) { get; set; } | Ruft eine 32-Bit-Ganzzahl ohne Vorzeichen ab oder legt diese fest, die die Datensatzsignatur angibt. Dies MUSS ENHMETA_SIGNATURE sein, aus der FormatSignature-Enumeration (Abschnitt 2.1.14). |
| [Reserved](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/reserved) { get; set; } | Erhält oder setzt eine 16-Bit-Ganzzahl ohne Vorzeichen, die 0x0000 sein MUSS und ignoriert werden MUSS |
| [Valid](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/valid) { get; } | Ruft einen Wert ab, der angibt, ob dies[`EmfHeaderObject`](../emfheaderobject)ist gültig. |
| [Version](../../aspose.imaging.fileformats.emf.emf.objects/emfheaderobject/version) { get; set; } | Ruft Version (4 Bytes) ab oder legt sie fest: Eine 32-Bit-Ganzzahl ohne Vorzeichen, die die EMF-Metadatei-Interoperabilität angibt. Dies SOLLTE 0x00010000 sein |

### Siehe auch

* class [EmfHeaderObject](../emfheaderobject)
* namensraum [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
