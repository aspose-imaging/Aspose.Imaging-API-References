---
title: TiffTags
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Il tag tiff enum.
type: docs
weight: 7740
url: /it/net/aspose.imaging.fileformats.tiff.enums/tifftags/
---
## TiffTags enumeration

Il tag tiff enum.

```csharp
public enum TiffTags
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| SubFileType | `254` | Descrittore dati sottofile. |
| OsubfileType | `255` | [obsoleto dal TIFF rev. 5.0] Tipo di dati nel sottofile. |
| ImageWidth | `256` | Larghezza immagine in pixel. |
| ImageLength | `257` | Altezza dell'immagine in pixel. |
| BitsPerSample | `258` | Bit per canale (campione). |
| Compression | `259` | Tecnica di compressione dati. |
| Photometric | `262` | Interpretazione fotometrica. |
| Thresholding | `263` | [obsoleto dal TIFF rev. 5.0] Soglia utilizzata sui dati. |
| CellWidth | `264` | [obsoleto dal TIFF rev. 5.0] Larghezza matrice dithering. |
| CellLength | `265` | [obsoleto dal TIFF rev. 5.0] Altezza matrice dithering. |
| FillOrder | `266` | Ordine dati all'interno di un byte. |
| DocumentName | `269` | Nome del documento valido per l'immagine. |
| ImageDescription | `270` | Informazioni sull'immagine. |
| Make | `271` | Nome produttore scanner. |
| Model | `272` | Nome/numero modello scanner. |
| StripOffsets | `273` | Offset alle strisce di dati. |
| Orientation | `274` | [obsoleto dal TIFF rev. 5.0] Orientamento dell'immagine. |
| SamplesPerPixel | `277` | Campioni per pixel. |
| RowsPerStrip | `278` | Righe per striscia di dati. |
| StripByteCounts | `279` | Conteggio byte per strip. |
| MinSampleValue | `280` | [obsoleto dal TIFF rev. 5.0] Valore campione minimo. |
| MaxSampleValue | `281` | [obsoleto dal TIFF rev. 5.0] Valore campione massimo. |
| Xresolution | `282` | Pixel/risoluzione in x. |
| Yresolution | `283` | Pixel/risoluzione in y. |
| PlanarConfig | `284` | Organizzazione di archiviazione. |
| PageName | `285` | L'immagine del nome della pagina proviene da. |
| Xposition | `286` | Offset pagina X dell'immagine a sinistra. |
| Yposition | `287` | Offset pagina Y dell'immagine a sinistra. |
| FreeOffsets | `288` | [obsoleto dal TIFF rev. 5.0] Offset byte al blocco libero. |
| FreeByteCounts | `289` | [obsoleto dal TIFF rev. 5.0] Dimensioni dei blocchi liberi. |
| GrayResponseUnit | `290` | [obsoleto dal TIFF rev. 6.0] Precisione della curva della scala dei grigi. |
| GrayResponseCurve | `291` | [obsoleto dal TIFF rev. 6.0] Curva di risposta in scala di grigi. |
| T4Options | `292` | Alias nome proprio TIFF 6.0 per GROUP3OPTIONS. Opzioni per la codifica fax CCITT Gruppo 3. 32 bit di flag. |
| T6Options | `293` | Opzioni per la codifica fax CCITT Gruppo 4. 32 bit di flag. TIFF 6.0 alias del nome proprio per GROUP4OPTIONS. |
| ResolutionUnit | `296` | Unità di risoluzione. |
| PageNumber | `297` | Numeri di pagina di più pagine. |
| ColorResponseUnit | `300` | [obsoleto dal TIFF rev. 6.0] Precisione della curva colore. |
| TransferFunction | `301` | Info colorimetria. |
| Software | `305` | Nome e rilascio. |
| DateTime | `306` | Data e ora di creazione. |
| Artist | `315` | Creatore dell'immagine. |
| HostComputer | `316` | Macchina dove è stata creata. |
| Predictor | `317` | Schema di previsione con LZW. |
| WhitePoint | `318` | Punto bianco immagine. |
| PrimaryChromaticities | `319` | Cromaticità primarie. |
| ColorMap | `320` | Mappa RGB per immagine pallette. |
| HalftoneHints | `321` | Informazioni su luci + ombre. |
| TileWidth | `322` | Larghezza piastrella in pixel. |
| TileLength | `323` | Altezza piastrella in pixel. |
| TileOffsets | `324` | Offset ai riquadri dati. |
| TileByteCounts | `325` | Conteggio byte per tile. |
| BadFaxLines | `326` | Righe con conteggio pixel errato. |
| CleanFaxData | `327` | Info linea rigenerate. |
| ConsecutiveBadFaxLines | `328` | Numero massimo di linee danneggiate consecutive. |
| SubIfd | `330` | Descrittori di immagini secondarie. |
| InkSet | `332` | Inchiostri in un'immagine separata. |
| InkNames | `333` | Nomi ASCII degli inchiostri. |
| NumberOfInks | `334` | Numero di inchiostri. |
| DotRange | `336` | Codici punto 0% e 100%. |
| TargetPrinter | `337` | Obiettivo di separazione. |
| ExtraSamples | `338` | Informazioni su campioni extra. |
| SampleFormat | `339` | Formato campione dati. |
| SminSampleValue | `340` | Variabile MinSampleValue. |
| SmaxSampleValue | `341` | Variabile MaxSampleValue. |
| TransferRange | `342` | Intervallo di trasferimento variabile |
| ClipPath | `343` | Percorso clip . Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Xclippathunits | `344` | XClipPathUnits. Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Yclippathunits | `345` | YClipPathUnits. Introdotto post TIFF rev 6.0 da Adobe TIFF technote 2. |
| Indexed | `346` | Indicizzato. Introdotto post TIFF rev 6.0 da Adobe TIFF Technote 3. |
| JpegTables | `347` | Flusso tabella JPEG. Introdotto il post TIFF rev 6.0. |
| OpiProxy | `351` | Proxy OPI. Introdotto post TIFF rev 6.0 da Adobe TIFF technote. |
| JpegProc | `512` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Algoritmo di elaborazione JPEG. |
| JpegInerchangeFormat | `513` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Puntatore al marker SOI. |
| JpegInterchangeFormatLength | `514` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] lunghezza flusso JFIF |
| JpegRestartInterval | `515` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Lunghezza intervallo di riavvio. |
| JpegLosslessPredictors | `517` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Predittore proc senza perdita. |
| JpegPointTransform | `518` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Trasformazione punto senza perdita. |
| JpegQTables | `519` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Offset matrice Q. |
| JpegDCtables | `520` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Offset tabella DCT. |
| JpegACtables | `521` | [obsoleto dalla nota tecnica n. 2 che specifica uno schema JPEG-in-TIFF rivisto] Scostamento coefficiente AC. |
| YcbcrCoefficients | `529` | RGB -&gt; YCbCr trasforma. |
| YcbcrSubSampling | `530` | Fattori di sottocampionamento YCbCr. |
| YcbcrPositioning | `531` | Posizionamento sottocampione. |
| ReferenceBlackWhite | `532` | Info colorimetria. |
| XmlPacket | `700` | Pacchetto XML. Introdotto post TIFF rev 6.0 da Adobe XMP Specification, gennaio 2004. |
| OpiImageid | `32781` | ID immagine OPI. Introdotto post TIFF rev 6.0 da Adobe TIFF technote. |
| Refpts | `32953` | Punti di riferimento dell'immagine. Tag privato registrato su Island Graphics. |
| Copyright | `33432` | Stringa di copyright. Questo tag è elencato nel TIFF rev. 6.0 con proprietà sconosciuta. |
| PhotoshopResources | `34377` | Risorse di immagini di Photoshop. |
| IccProfile | `34675` | Il profilo del dispositivo ICC incorporato |
| ExifIfdPointer | `34665` | Un puntatore all'IFD Exif. |
| XPTitle | `40091` | Informazioni sull'immagine, utilizzate da Esplora risorse. IlXPTitle viene ignorato da Esplora risorse se ilImageDescription il tag esiste. |
| XPComment | `40092` | Commento sull'immagine, utilizzato da Esplora risorse. |
| XPAuthor | `40093` | Autore immagine, utilizzato da Esplora risorse. IlXPAuthor viene ignorato da Esplora risorse se ilArtist il tag esiste. |
| XPKeywords | `40094` | Parole chiave immagine, utilizzate da Esplora risorse. |
| XPSubject | `40095` | Immagine soggetto, utilizzata da Esplora risorse. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Tiff.Enums](../../aspose.imaging.fileformats.tiff.enums)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
