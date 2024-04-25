---
title: TiffTags
second_title: Aspose.Imaging für .NET-API-Referenz
description: Das TIFF-Tag enum.
type: docs
weight: 7740
url: /de/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

Das TIFF-Tag enum.

```csharp
public enum TiffTags
```

### Werte

| Name | Wert | Beschreibung |
| --- | --- | --- |
| SubFileType | `254` | Subfile-Datendeskriptor. |
| OsubfileType | `255` | [veraltet durch TIFF rev. 5.0] Art der Daten in Subfile. |
| ImageWidth | `256` | Bildbreite in Pixel. |
| ImageLength | `257` | Bildhöhe in Pixel. |
| BitsPerSample | `258` | Bits pro Kanal (Stichprobe). |
| Compression | `259` | Datenkomprimierungstechnik. |
| Photometric | `262` | Photometrische Auswertung. |
| Thresholding | `263` | [veraltet durch TIFF rev. 5.0] Schwellwerte für Daten verwendet. |
| CellWidth | `264` | [veraltet durch TIFF rev. 5.0] Breite der Dithering-Matrix. |
| CellLength | `265` | [veraltet durch TIFF rev. 5.0] Dithering-Matrixhöhe. |
| FillOrder | `266` | Datenreihenfolge innerhalb eines Bytes. |
| DocumentName | `269` | Name des Dokuments, das für Bild gilt. |
| ImageDescription | `270` | Informationen zum Bild. |
| Make | `271` | Name des Scannerherstellers. |
| Model | `272` | Name/Nummer des Scannermodells. |
| StripOffsets | `273` | Offsets zu Datenstreifen. |
| Orientation | `274` | [veraltet durch TIFF rev. 5.0] Bildausrichtung. |
| SamplesPerPixel | `277` | Samples pro Pixel. |
| RowsPerStrip | `278` | Zeilen pro Datenstreifen. |
| StripByteCounts | `279` | Bytes zählt für Strips. |
| MinSampleValue | `280` | [veraltet durch TIFF rev. 5.0] Minimaler Abtastwert. |
| MaxSampleValue | `281` | [veraltet durch TIFF rev. 5.0] Maximaler Abtastwert. |
| Xresolution | `282` | Pixel/Auflösung in x. |
| Yresolution | `283` | Pixel/Auflösung in y. |
| PlanarConfig | `284` | Speicherorganisation. |
| PageName | `285` | Bild des Seitennamens stammt von. |
| Xposition | `286` | X Seitenversatz des Bildes links. |
| Yposition | `287` | Y Seitenversatz des Bildes links. |
| FreeOffsets | `288` | [veraltet durch TIFF rev. 5.0] Byte-Offset zum freien Block. |
| FreeByteCounts | `289` | [veraltet durch TIFF rev. 5.0] Größen freier Blöcke. |
| GrayResponseUnit | `290` | [veraltet durch TIFF rev. 6.0] Genauigkeit der Graustufenkurve. |
| GrayResponseCurve | `291` | [veraltet durch TIFF rev. 6.0] Graustufen-Reaktionskurve. |
| T4Options | `292` | TIFF 6.0-Eigennamen-Alias für GROUP3OPTIONS. Optionen für CCITT-Gruppe 3-Faxcodierung. 32 Flag-Bits. |
| T6Options | `293` | Optionen für CCITT-Gruppe 4-Faxcodierung. 32 Flag-Bits. TIFF 6.0 Eigennamen-Alias für GROUP4OPTIONS. |
| ResolutionUnit | `296` | Auflösungseinheiten. |
| PageNumber | `297` | Seitenzahlen von mehreren Seiten. |
| ColorResponseUnit | `300` | [veraltet durch TIFF rev. 6.0] Genauigkeit der Farbkurve. |
| TransferFunction | `301` | Farbmetrikinfo. |
| Software | `305` | Name &amp; Release. |
| DateTime | `306` | Datum und Uhrzeit der Erstellung. |
| Artist | `315` | Ersteller des Bildes. |
| HostComputer | `316` | Maschine wo erstellt. |
| Predictor | `317` | Vorhersageschema mit LZW. |
| WhitePoint | `318` | Bildweißpunkt. |
| PrimaryChromaticities | `319` | Primäre Farbarten. |
| ColorMap | `320` | RGB-Karte für Palettenbild. |
| HalftoneHints | `321` | Highlight- und Schatteninfo. |
| TileWidth | `322` | Kachelbreite in Pixel. |
| TileLength | `323` | Kachelhöhe in Pixel. |
| TileOffsets | `324` | Offsets zu Datenkacheln. |
| TileByteCounts | `325` | Byte-Anzahl für Kacheln. |
| BadFaxLines | `326` | Zeilen mit falscher Pixelanzahl. |
| CleanFaxData | `327` | Neu generierte Zeileninfo. |
| ConsecutiveBadFaxLines | `328` | Max. aufeinanderfolgende fehlerhafte Zeilen. |
| SubIfd | `330` | Subimage-Deskriptoren. |
| InkSet | `332` | Tinten in getrenntem Bild. |
| InkNames | `333` | ASCII-Namen von Tinten. |
| NumberOfInks | `334` | Anzahl der Tinten. |
| DotRange | `336` | 0 % und 100 % Punktcodes. |
| TargetPrinter | `337` | Trennungsziel. |
| ExtraSamples | `338` | Informationen zu zusätzlichen Proben. |
| SampleFormat | `339` | Datenbeispielformat. |
| SminSampleValue | `340` | Variable MinSampleValue. |
| SmaxSampleValue | `341` | Variable MaxSampleValue. |
| TransferRange | `342` | Variable TransferRange |
| ClipPath | `343` | ClipPath. Eingeführt nach TIFF rev 6.0 von Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Eingeführt nach TIFF rev 6.0 von Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Eingeführt nach TIFF rev 6.0 von Adobe TIFF technote 2. |
| Indexed | `346` | Indexiert. Eingeführt nach TIFF rev 6.0 von Adobe TIFF Technote 3. |
| JpegTables | `347` | JPEG-Tabellenstream. Eingeführt nach TIFF rev 6.0. |
| OpiProxy | `351` | OPI-Proxy. Eingeführt nach TIFF rev 6.0 von Adobe TIFF technote. |
| JpegProc | `512` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] JPEG-Verarbeitungsalgorithmus. |
| JpegInerchangeFormat | `513` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Zeiger auf SOI-Marker. |
| JpegInterchangeFormatLength | `514` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] JFIF-Streamlänge |
| JpegRestartInterval | `515` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Länge des Neustartintervalls. |
| JpegLosslessPredictors | `517` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Prädiktor für verlustfreie Prozesse. |
| JpegPointTransform | `518` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Verlustfreie Punkttransformation. |
| JpegQTables | `519` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Q-Matrix-Offsets. |
| JpegDCtables | `520` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] Offsets der DCT-Tabelle. |
| JpegACtables | `521` | [veraltet durch Technical Note #2, der ein überarbeitetes JPEG-in-TIFF-Schema angibt] AC-Koeffizienten-Offsets. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr-Transformation. |
| YcbcrSubSampling | `530` | YCbCr-Subsampling-Faktoren. |
| YcbcrPositioning | `531` | Subsample-Positionierung. |
| ReferenceBlackWhite | `532` | Farbmetrikinfo. |
| XmlPacket | `700` | XML-Paket. Eingeführt nach TIFF Rev. 6.0 von Adobe XMP Specification, Januar 2004. |
| OpiImageid | `32781` | OPI-Bild-ID. Eingeführt nach TIFF rev 6.0 von Adobe TIFF technote. |
| Refpts | `32953` | Bildbezugspunkte. Privates Tag registriert bei Island Graphics. |
| Copyright | `33432` | Copyright-String. Dieses Tag ist in der TIFF-Version aufgelistet. 6.0 mit unbekanntem Eigentum. |
| PhotoshopResources | `34377` | Photoshop-Bildressourcen. |
| IccProfile | `34675` | Das eingebettete ICC-Geräteprofil |
| ExifIfdPointer | `34665` | Ein Zeiger auf das Exif IFD. |
| XPTitle | `40091` | Informationen über das Bild, verwendet von Windows Explorer. DieXPTitle wird vom Windows Explorer ignoriert, wenn dieImageDescription Tag existiert. |
| XPComment | `40092` | Kommentar zum Bild, verwendet von Windows Explorer. |
| XPAuthor | `40093` | Bildautor, verwendet von Windows Explorer. DieXPAuthor wird vom Windows Explorer ignoriert, wenn dieArtist Tag existiert. |
| XPKeywords | `40094` | Bildschlüsselwörter, verwendet von Windows Explorer. |
| XPSubject | `40095` | Subjektbild, verwendet von Windows Explorer. |

### Siehe auch

* namensraum [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* Montage [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
