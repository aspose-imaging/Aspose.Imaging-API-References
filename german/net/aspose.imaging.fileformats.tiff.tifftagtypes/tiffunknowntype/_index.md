---
title: TiffUnknownType
second_title: Aspose.Imaging für .NET-API-Referenz
description: Der unbekannte TIFF-Typ. Falls das tiff-Tag nicht erkannt werden kann wird dieser Typ instanziiert.
type: docs
weight: 8050
url: /de/net/aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/
---
## TiffUnknownType class

Der unbekannte TIFF-Typ. Falls das tiff-Tag nicht erkannt werden kann, wird dieser Typ instanziiert.

```csharp
public sealed class TiffUnknownType : TiffDataType
```

## Konstrukteure

| Name | Beschreibung |
| --- | --- |
| [TiffUnknownType](tiffunknowntype)(TiffStreamReader, ushort, ushort, uint, uint) | Initialisiert eine neue Instanz von[`TiffUnknownType`](../tiffunknowntype) Klasse. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [AlignedDataSize](../../aspose.imaging.fileformats.tiff/tiffdatatype/aligneddatasize) { get; } | Ruft die zusätzliche Datengröße in Bytes ab (falls die 12 Bytes nicht ausreichen, um die Tag-Daten aufzunehmen). |
| override [Count](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/count) { get; } | Ruft die Anzahl der Elemente ab. |
| override [DataSize](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/datasize) { get; } | Ruft die zusätzliche Datengröße in Bytes ab (falls die 12 Bytes nicht ausreichen, um die Tag-Daten aufzunehmen). |
| [Id](../../aspose.imaging.fileformats.tiff/tiffdatatype/id) { get; } | Ruft die ganzzahlige Darstellung der Tag-ID ab. |
| [IsValid](../../aspose.imaging.fileformats.tiff/tiffdatatype/isvalid) { get; } | Ruft einen Wert ab, der angibt, ob Tag-Daten gültig sind. Das gültige Tag enthält Daten, die bewahrt werden können. Das ungültige Tag kann nicht gespeichert werden. |
| [OffsetOrValue](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/offsetorvalue) { get; } | Ruft den Offset-Wert für zusätzliche Daten oder den Wert selbst ab, falls die Anzahl 1 ist. |
| [Stream](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/stream) { get; } | Ruft den Stream ab, aus dem zusätzliche Daten gelesen werden. |
| [TagId](../../aspose.imaging.fileformats.tiff/tiffdatatype/tagid) { get; } | Ruft die Tag-ID ab. |
| override [TagType](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tagtype) { get; } | Ruft den Tag-Typ ab. |
| override [Value](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/value) { get; set; } | Liest oder setzt den Wert, den dieser Datentyp enthält. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| [CompareTo](../../aspose.imaging.fileformats.tiff/tiffdatatype/compareto)(object) | Vergleicht die aktuelle Instanz mit einem anderen Objekt des gleichen Typs und gibt eine ganze Zahl zurück, die angibt, ob die aktuelle Instanz in der Sortierreihenfolge an der gleichen Position wie das andere Objekt vorangeht, folgt oder an derselben Position vorkommt. |
| virtual [DeepClone](../../aspose.imaging.fileformats.tiff/tiffdatatype/deepclone)() | Führt einen tiefen Klon dieser Instanz durch. |
| override [ToString](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/tostring)() | Gibt a zurückString die diese Instanz darstellt. |
| override [WriteAdditionalData](../../aspose.imaging.fileformats.tiff.tifftagtypes/tiffunknowntype/writeadditionaldata)(TiffStreamWriter) | Schreibt die zusätzlichen Tag-Daten. |
| [WriteTag](../../aspose.imaging.fileformats.tiff/tiffdatatype/writetag)(TiffStreamWriter, long) | Schreibt die Tag-Daten. |

### Bemerkungen

Beachten Sie das[`TiffUnknownType`](../tiffunknowntype) wird nicht zurück zum Stream serialisiert.

### Siehe auch

* class [TiffDataType](../../aspose.imaging.fileformats.tiff/tiffdatatype)
* namensraum [Aspose.Imaging.FileFormats.Tiff.TiffTagTypes](../../aspose.imaging.fileformats.tiff.tifftagtypes)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->