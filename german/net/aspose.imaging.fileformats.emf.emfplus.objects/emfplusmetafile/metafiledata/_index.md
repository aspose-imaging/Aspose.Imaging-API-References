---
title: MetafileData
second_title: Aspose.Imaging für .NET-API-Referenz
description: Ruft Daten variabler Länge ab oder legt diese fest die die eingebettete Metadatei angeben. Der Inhalt und das Format der Daten können für jeden Metadateityp unterschiedlich sein.
type: docs
weight: 20
url: /de/net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusmetafile/metafiledata/
---
## EmfPlusMetafile.MetafileData property

Ruft Daten variabler Länge ab oder legt diese fest, die die eingebettete Metadatei angeben. Der Inhalt und das Format der Daten können für jeden Metadateityp unterschiedlich sein.

```csharp
public byte[] MetafileData { get; set; }
```

### Bemerkungen

Grafikbilder werden durch EmfPlusImage-Objekte (Abschnitt 2.2.1.4) spezifiziert. Ein EmfPlusMetafile-Objekt MUSS im ImageData-Feld eines EmfPlusImage-Objekts vorhanden sein, wenn ImageTypeMetafile in seinem Type-Feld angegeben ist. Dieses Objekt ist generisch und wird für verschiedene Datentypen verwendet, darunter: Eine WMF-Metadatei [MS-WMF]; WMF-Metadatei, die platziert werden kann; Eine EMF-Metadatei [MS-EMF]; Eine EMF+-Metadatei, die Grafikoperationen nur mit EMF+-Datensätzen spezifiziert; and Eine EMF+-Metadatei, die Grafikoperationen sowohl mit EMF+- als auch mit EMF-Datensätzen spezifiziert. Siehe Abschnitt 2.2.2 für die Spezifikation zusätzlicher Strukturobjekte.

### Siehe auch

* class [EmfPlusMetafile](../../emfplusmetafile)
* namensraum [Aspose.Imaging.FileFormats.Emf.EmfPlus.Objects](../../emfplusmetafile)
* Montage [Aspose.Imaging](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->