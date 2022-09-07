---
title: TiffTags
second_title: Aspose.Imaging för .NET API-referens
description: tiff-taggen enum.
type: docs
weight: 7740
url: /sv/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

tiff-taggen enum.

```csharp
public enum TiffTags
```

### Värderingar

| namn | Värde | Beskrivning |
| --- | --- | --- |
| SubFileType | `254` | Subfil data descriptor. |
| OsubfileType | `255` | [föråldrad av TIFF rev. 5.0] Typ av data i underfil. |
| ImageWidth | `256` | Bildbredd i pixlar. |
| ImageLength | `257` | Bildhöjd i pixlar. |
| BitsPerSample | `258` | Bitar per kanal (exempel). |
| Compression | `259` | Datakomprimeringsteknik. |
| Photometric | `262` | Fotometrisk tolkning. |
| Thresholding | `263` | [föråldrad av TIFF rev. 5.0] Tröskelvärde används på data. |
| CellWidth | `264` | [föråldrad av TIFF rev. 5.0] Dithering matris bredd. |
| CellLength | `265` | [föråldrad av TIFF rev. 5.0] Vibrerande matrishöjd. |
| FillOrder | `266` | Dataordning inom en byte. |
| DocumentName | `269` | Namn på dokument som gäller för bild. |
| ImageDescription | `270` | Information om bild. |
| Make | `271` | Skannerns tillverkares namn. |
| Model | `272` | Skannerns modellnamn/nummer. |
| StripOffsets | `273` | Offset till dataremsor. |
| Orientation | `274` | [föråldrad av TIFF rev. 5.0] Bildorientering. |
| SamplesPerPixel | `277` | Samples per pixel. |
| RowsPerStrip | `278` | Rader per dataremsa. |
| StripByteCounts | `279` | Antal byte för remsor. |
| MinSampleValue | `280` | [föråldrad av TIFF rev. 5.0] Minsta exempelvärde. |
| MaxSampleValue | `281` | [föråldrad av TIFF rev. 5.0] Maximalt provvärde. |
| Xresolution | `282` | Pixlar/upplösning i x. |
| Yresolution | `283` | Pixlar/upplösning i y. |
| PlanarConfig | `284` | Lagringsorganisation. |
| PageName | `285` | Sidnamnsbilden är från. |
| Xposition | `286` | X sidförskjutning av bilden lhs. |
| Yposition | `287` | Y-sida förskjutning av bilden lhs. |
| FreeOffsets | `288` | [föråldrad av TIFF rev. 5.0] Byte offset till ledigt block. |
| FreeByteCounts | `289` | [föråldrad av TIFF rev. 5.0] Storlekar på fria block. |
| GrayResponseUnit | `290` | [föråldrad av TIFF rev. 6.0] Gråskalekurvans noggrannhet. |
| GrayResponseCurve | `291` | [föråldrad av TIFF rev. 6.0] Svarskurva i gråskala. |
| T4Options | `292` | TIFF 6.0 egennamnsalias för GROUP3OPTIONS. Alternativ för CCITT Group 3-faxkodning. 32 flaggbitar. |
| T6Options | `293` | Alternativ för CCITT Group 4 faxkodning. 32 flaggbitar. TIFF 6.0 egennamnalias för GROUP4OPTIONS. |
| ResolutionUnit | `296` | Upplösningsenheter. |
| PageNumber | `297` | Sidnummer för flera sidor. |
| ColorResponseUnit | `300` | [föråldrad av TIFF rev. 6.0] Färgkurvans noggrannhet. |
| TransferFunction | `301` | Kolorimetri info. |
| Software | `305` | Namn och release. |
| DateTime | `306` | Skapandedatum och tid. |
| Artist | `315` | Skapare av bilden. |
| HostComputer | `316` | Maskin där den skapades. |
| Predictor | `317` | Förutsägelseschema med LZW. |
| WhitePoint | `318` | Bildens vitpunkt. |
| PrimaryChromaticities | `319` | Primära färger. |
| ColorMap | `320` | RGB-karta för palettbild. |
| HalftoneHints | `321` | Markera + skugginformation. |
| TileWidth | `322` | Kakelbredd i pixlar. |
| TileLength | `323` | Kakelhöjd i pixlar. |
| TileOffsets | `324` | Offset till databrickor. |
| TileByteCounts | `325` | Antal byte för brickor. |
| BadFaxLines | `326` | Rader med fel pixelantal. |
| CleanFaxData | `327` | Regenererad linjeinformation. |
| ConsecutiveBadFaxLines | `328` | Max antal felaktiga rader i följd. |
| SubIfd | `330` | Underbildsbeskrivningar. |
| InkSet | `332` | Bläck i separerad bild. |
| InkNames | `333` | ASCII-namn på bläck. |
| NumberOfInks | `334` | Antal bläck. |
| DotRange | `336` | 0 % och 100 % punktkoder. |
| TargetPrinter | `337` | Separationsmål. |
| ExtraSamples | `338` | Information om extra prover. |
| SampleFormat | `339` | Dataexempelformat. |
| SminSampleValue | `340` | Variabelt MinSampleValue. |
| SmaxSampleValue | `341` | Variabelt MaxSampleValue. |
| TransferRange | `342` | Variable TransferRange |
| ClipPath | `343` | ClipPath. Introducerad post TIFF rev 6.0 av Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Introducerad post TIFF rev 6.0 av Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Introducerad post TIFF rev 6.0 av Adobe TIFF technote 2. |
| Indexed | `346` | Indexerad. Introducerat efter TIFF rev 6.0 av Adobe TIFF Technote 3. |
| JpegTables | `347` | JPEG-tabellström. Introducerat inlägg TIFF rev 6.0. |
| OpiProxy | `351` | OPI-proxy. Introducerad post TIFF rev 6.0 av Adobe TIFF technote. |
| JpegProc | `512` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] JPEG-bearbetningsalgoritm. |
| JpegInerchangeFormat | `513` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Pekare till SOI-markör. |
| JpegInterchangeFormatLength | `514` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] JFIF-strömlängd |
| JpegRestartInterval | `515` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Omstartsintervalllängd. |
| JpegLosslessPredictors | `517` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Förlustfri proc-prediktor. |
| JpegPointTransform | `518` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Förlustfri punkttransform. |
| JpegQTables | `519` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] Q-matrisförskjutningar. |
| JpegDCtables | `520` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] DCT-tabelloffset. |
| JpegACtables | `521` | [föråldrad av teknisk anmärkning #2 som specificerar ett reviderat JPEG-i-TIFF-schema] AC-koefficientoffset. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr transform. |
| YcbcrSubSampling | `530` | YCbCr delsamplingsfaktorer. |
| YcbcrPositioning | `531` | Delprovspositionering. |
| ReferenceBlackWhite | `532` | Kolorimetri info. |
| XmlPacket | `700` | XML-paket. Introducerad post TIFF rev 6.0 av Adobe XMP Specification, januari 2004. |
| OpiImageid | `32781` | OPI ImageID. Introducerad post TIFF rev 6.0 av Adobe TIFF technote. |
| Refpts | `32953` | Bildreferenspunkter. Privat tagg registrerad på Island Graphics. |
| Copyright | `33432` | Upphovsrättssträng. Denna tagg är listad i TIFF rev. 6.0 med okänt ägande. |
| PhotoshopResources | `34377` | Photoshop bildresurser. |
| IccProfile | `34675` | Den inbäddade ICC-enhetsprofilen |
| ExifIfdPointer | `34665` | En pekare till Exif IFD. |
| XPTitle | `40091` | Information om bild, som används av Windows Explorer. TheXPTitle ignoreras av Windows Explorer omImageDescription taggen finns. |
| XPComment | `40092` | Kommentera bilden, som används av Windows Explorer. |
| XPAuthor | `40093` | Image Author, används av Windows Explorer. TheXPAuthor ignoreras av Windows Explorer omArtist taggen finns. |
| XPKeywords | `40094` | Bildnyckelord, som används av Windows Explorer. |
| XPSubject | `40095` | Ämnesbild, använd av Windows Explorer. |

### Se även

* namnutrymme [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* hopsättning [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
