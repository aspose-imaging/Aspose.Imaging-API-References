---
title: "ExifProperties"
second_title: "Riferimento API Aspose.Imaging per Java"
description: "Elenco dei tag Exif"
type: docs
weight: 11
url: /it/java/com.aspose.imaging.exif/exifproperties/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class ExifProperties extends System.Enum
```

Elenco dei tag Exif
## Campi

| Campo | Descrizione |
| --- | --- |
| [ImageWidth](#ImageWidth) | Il numero di colonne dei dati dell'immagine, pari al numero di pixel per riga. |
| [ImageLength](#ImageLength) | Il numero di righe dei dati dell'immagine. |
| [BitsPerSample](#BitsPerSample) | Il numero di bit per componente dell'immagine. |
| [Compression](#Compression) | Lo schema di compressione utilizzato per i dati dell'immagine. |
| [PhotometricInterpretation](#PhotometricInterpretation) | La composizione dei pixel. |
| [ImageDescription](#ImageDescription) | Una stringa di caratteri che fornisce il titolo dell'immagine. |
| [Make](#Make) | Il produttore dell'attrezzatura di registrazione. |
| [Model](#Model) | Il nome modello o il numero modello dell'attrezzatura. |
| [Orientation](#Orientation) | L'orientamento dell'immagine visualizzato in termini di righe e colonne. |
| [SamplesPerPixel](#SamplesPerPixel) | Il numero di componenti per pixel. |
| [XResolution](#XResolution) | Il numero di pixel per ResolutionUnit nella direzione ImageWidth. |
| [YResolution](#YResolution) | Il numero di pixel per ResolutionUnit nella direzione ImageLength. |
| [PlanarConfiguration](#PlanarConfiguration) | Indica se i componenti dei pixel sono registrati in formato chunky o planar. |
| [ResolutionUnit](#ResolutionUnit) | L'unità di misura per XResolution e YResolution. |
| [TransferFunction](#TransferFunction) | Una funzione di trasferimento per l'immagine, descritta in stile tabellare. |
| [Software](#Software) | Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di acquisizione immagini utilizzato per generare l'immagine. |
| [DateTime](#DateTime) | La data e l'ora di creazione dell'immagine. |
| [Artist](#Artist) | Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. |
| [WhitePoint](#WhitePoint) | La cromaticità del punto bianco dell'immagine. |
| [PrimaryChromaticities](#PrimaryChromaticities) | La cromaticità dei tre colori primari dell'immagine. |
| [YCbCrCoefficients](#YCbCrCoefficients) | I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr. |
| [YCbCrSubSampling](#YCbCrSubSampling) | Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza. |
| [YCbCrPositioning](#YCbCrPositioning) | La posizione dei componenti di crominanza rispetto al componente di luminanza. |
| [ReferenceBlackWhite](#ReferenceBlackWhite) | Il valore del punto nero di riferimento e il valore del punto bianco di riferimento. |
| [Copyright](#Copyright) | Informazioni sul copyright. |
| [ExposureTime](#ExposureTime) | Tempo di esposizione, espresso in secondi. |
| [FNumber](#FNumber) | Il numero F. |
| [ExposureProgram](#ExposureProgram) | La classe del programma usato dalla fotocamera per impostare l'esposizione al momento dello scatto. |
| [SpectralSensitivity](#SpectralSensitivity) | Indica la sensibilità spettrale di ciascun canale della fotocamera utilizzata. |
| [PhotographicSensitivity](#PhotographicSensitivity) | Indica la velocità ISO e la latitudine ISO della fotocamera o del dispositivo di input come specificato nella ISO 12232. |
| [OECF](#OECF) | Indica la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| [ExifVersion](#ExifVersion) | La versione Exif. |
| [DateTimeOriginal](#DateTimeOriginal) | La data e l'ora in cui sono stati generati i dati immagine originali. |
| [DateTimeDigitized](#DateTimeDigitized) | La data e l'ora di digitalizzazione. |
| [ComponentsConfiguration](#ComponentsConfiguration) | La configurazione dei componenti. |
| [CompressedBitsPerPixel](#CompressedBitsPerPixel) | Specifico per dati compressi; indica i bit compressi per pixel. |
| [ShutterSpeedValue](#ShutterSpeedValue) | Il valore della velocità dell'otturatore. |
| [ApertureValue](#ApertureValue) | Il valore dell'apertura dell'obiettivo. |
| [BrightnessValue](#BrightnessValue) | Il valore della luminosità. |
| [ExposureBiasValue](#ExposureBiasValue) | Il valore del compenso di esposizione. |
| [MaxApertureValue](#MaxApertureValue) | Il valore dell'apertura massima. |
| [SubjectDistance](#SubjectDistance) | La distanza dal soggetto, espressa in metri. |
| [MeteringMode](#MeteringMode) | La modalità di misurazione. |
| [LightSource](#LightSource) | Il tipo di sorgente luminosa. |
| [Flash](#Flash) | Indica lo stato del flash al momento dello scatto dell'immagine. |
| [FocalLength](#FocalLength) | La lunghezza focale reale dell'obiettivo, in mm. |
| [SubjectArea](#SubjectArea) | Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva. |
| [MakerNote](#MakerNote) | Un tag per i produttori di scrittori Exif per registrare qualsiasi informazione desiderata. |
| [UserComment](#UserComment) | Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli in ImageDescription, e senza le limitazioni di codifica dei caratteri del tag ImageDescription. |
| [SubsecTime](#SubsecTime) | Un tag usato per registrare frazioni di secondo per il tag DateTime. |
| [SubsecTimeOriginal](#SubsecTimeOriginal) | Un tag usato per registrare frazioni di secondo per il tag DateTimeOriginal. |
| [SubsecTimeDigitized](#SubsecTimeDigitized) | Un tag usato per registrare frazioni di secondo per il tag DateTimeDigitized. |
| [FlashpixVersion](#FlashpixVersion) | La versione del formato Flashpix supportata da un file FPXR. |
| [ColorSpace](#ColorSpace) | Il tag di informazione dello spazio colore (ColorSpace) è sempre registrato come specificatore dello spazio colore. |
| [RelatedSoundFile](#RelatedSoundFile) | Il file audio correlato. |
| [FlashEnergy](#FlashEnergy) | Indica l'energia dello strobo al momento della cattura dell'immagine, misurata in Beam Candle Power Seconds (BCPS). |
| [SpatialFrequencyResponse](#SpatialFrequencyResponse) | Questo tag registra la tabella di frequenza spaziale della fotocamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato nella ISO 12233. |
| [FocalPlaneXResolution](#FocalPlaneXResolution) | Indica il numero di pixel nella direzione della larghezza dell'immagine (X) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| [FocalPlaneYResolution](#FocalPlaneYResolution) | Indica il numero di pixel nella direzione dell'altezza dell'immagine (Y) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| [FocalPlaneResolutionUnit](#FocalPlaneResolutionUnit) | Indica l'unità di misura per FocalPlaneXResolution e FocalPlaneYResolution. |
| [SubjectLocation](#SubjectLocation) | Indica la posizione del soggetto principale nella scena. |
| [ExposureIndex](#ExposureIndex) | Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento della cattura dell'immagine. |
| [SensingMethod](#SensingMethod) | Indica il tipo di sensore d'immagine sulla fotocamera o sul dispositivo di input. |
| [FileSource](#FileSource) | La sorgente del file. |
| [SceneType](#SceneType) | Indica il tipo di scena. |
| [CFAPattern](#CFAPattern) | Indica il modello geometrico della matrice di filtri colore (CFA) del sensore d'immagine quando viene utilizzato un sensore a zona colore a chip singolo. |
| [CustomRendered](#CustomRendered) | Questo tag indica l'uso di elaborazioni speciali sui dati dell'immagine, come il rendering orientato all'output. |
| [ExposureMode](#ExposureMode) | Questo tag indica la modalità di esposizione impostata al momento dello scatto dell'immagine. |
| [WhiteBalance](#WhiteBalance) | Questo tag indica la modalità di bilanciamento del bianco impostata al momento dello scatto dell'immagine. |
| [DigitalZoomRatio](#DigitalZoomRatio) | Questo tag indica il rapporto di zoom digitale al momento dello scatto dell'immagine. |
| [FocalLengthIn35MmFilm](#FocalLengthIn35MmFilm) | Questo tag indica la lunghezza focale equivalente assumendo una fotocamera a pellicola da 35 mm, in mm. |
| [SceneCaptureType](#SceneCaptureType) | Questo tag indica il tipo di scena che è stata fotografata. |
| [GainControl](#GainControl) | Questo tag indica il grado di regolazione complessiva del guadagno dell'immagine. |
| [Contrast](#Contrast) | Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera al momento dello scatto. |
| [Saturation](#Saturation) | Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera al momento dello scatto. |
| [Sharpness](#Sharpness) | Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera al momento dello scatto |
| [DeviceSettingDescription](#DeviceSettingDescription) | Questo tag indica informazioni sulle condizioni di scatto di un modello di fotocamera specifico. |
| [SubjectDistanceRange](#SubjectDistanceRange) | Questo tag indica la distanza dal soggetto. |
| [ImageUniqueID](#ImageUniqueID) | L'ID unico dell'immagine. |
| [GPSVersionID](#GPSVersionID) | Indica la versione di GPSInfoIFD. |
| [GPSLatitudeRef](#GPSLatitudeRef) | Indica se la latitudine è nord o sud. |
| [GPSLatitude](#GPSLatitude) | Indica la latitudine. |
| [GPSLongitudeRef](#GPSLongitudeRef) | Indica se la longitudine è est o ovest. |
| [GPSLongitude](#GPSLongitude) | Indica la longitudine. |
| [GPSAltitudeRef](#GPSAltitudeRef) | Indica l'altitudine usata come altitudine di riferimento. |
| [GPSAltitude](#GPSAltitude) | Indica l'altitudine basata sul riferimento in GPSAltitudeRef. |
| [GPSTimestamp](#GPSTimestamp) | Indica l'ora in UTC (Tempo Coordinato Universale). |
| [GPSSatellites](#GPSSatellites) | Indica i satelliti GPS usati per le misurazioni. |
| [GPSStatus](#GPSStatus) | Indica lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| [GPSMeasureMode](#GPSMeasureMode) | Indica la modalità di misurazione GPS. |
| [GPSDOP](#GPSDOP) | Indica il GPS DOP (grado di precisione dei dati). |
| [GPSSpeedRef](#GPSSpeedRef) | Indica l'unità usata per esprimere la velocità di movimento del ricevitore GPS. |
| [GPSSpeed](#GPSSpeed) | Indica la velocità di movimento del ricevitore GPS. |
| [GPSTrackRef](#GPSTrackRef) | Indica il riferimento per indicare la direzione del movimento del ricevitore GPS. |
| [GPSTrack](#GPSTrack) | Indica la direzione del movimento del ricevitore GPS. |
| [GPSImgDirectionRef](#GPSImgDirectionRef) | Indica il riferimento per fornire la direzione dell'immagine al momento della cattura. |
| [GPSImgDirection](#GPSImgDirection) | Indica la direzione dell'immagine al momento della cattura. |
| [GPSMapDatum](#GPSMapDatum) | Indica i dati di rilievo geodetico utilizzati dal ricevitore GPS. |
| [GPSDestLatitudeRef](#GPSDestLatitudeRef) | Indica se la latitudine del punto di destinazione è nord o sud. |
| [GPSDestLatitude](#GPSDestLatitude) | Indica la latitudine del punto di destinazione. |
| [GPSDestLongitudeRef](#GPSDestLongitudeRef) | Indica se la longitudine del punto di destinazione è est o ovest. |
| [GPSDestLongitude](#GPSDestLongitude) | Indica la longitudine del punto di destinazione. |
| [GPSDestBearingRef](#GPSDestBearingRef) | Indica il riferimento utilizzato per fornire la rotta al punto di destinazione. |
| [GPSDestBearing](#GPSDestBearing) | Indica la rotta al punto di destinazione. |
| [GPSDestDistanceRef](#GPSDestDistanceRef) | Indica l'unità utilizzata per esprimere la distanza al punto di destinazione. |
| [GPSDestDistance](#GPSDestDistance) | Indica la distanza al punto di destinazione. |
| [GPSProcessingMethod](#GPSProcessingMethod) | Una stringa di caratteri che registra il nome del metodo utilizzato per la localizzazione. |
| [GPSAreaInformation](#GPSAreaInformation) | Una stringa di caratteri che registra il nome dell'area GPS. |
| [GPSDateStamp](#GPSDateStamp) | Una stringa di caratteri che registra le informazioni di data e ora relative a UTC (Tempo Coordinato Universale). |
| [GPSDifferential](#GPSDifferential) | Indica se la correzione differenziale è applicata al ricevitore GPS. |
| [StripOffsets](#StripOffsets) | Per ogni striscia, l'offset in byte di quella striscia. |
| [JPEGInterchangeFormat](#JPEGInterchangeFormat) | L'offset al byte iniziale (SOI) dei dati della miniatura compressa JPEG. |
| [JPEGInterchangeFormatLength](#JPEGInterchangeFormatLength) | Il numero di byte dei dati della miniatura compressa JPEG. |
| [ExifIfdPointer](#ExifIfdPointer) | Un puntatore all'Exif IFD. |
| [GPSIfdPointer](#GPSIfdPointer) | Il puntatore gps ifd. |
| [RowsPerStrip](#RowsPerStrip) | Il numero di righe per striscia. |
| [StripByteCounts](#StripByteCounts) | Il numero totale di byte in ogni striscia. |
| [PixelXDimension](#PixelXDimension) | Informazioni specifiche ai dati compressi. |
| [PixelYDimension](#PixelYDimension) | Informazioni specifiche ai dati compressi. |
| [Gamma](#Gamma) | Valore gamma |
| [SensitivityType](#SensitivityType) | Tipo di sensibilità fotografica |
| [StandardOutputSensitivity](#StandardOutputSensitivity) | Indica la sensibilità di uscita standard della fotocamera |
| [RecommendedExposureIndex](#RecommendedExposureIndex) | Indica l'indice di esposizione consigliato |
| [ISOSpeed](#ISOSpeed) | Informazioni sul valore di velocità ISO come definito nella ISO 12232 |
| [ISOSpeedLatitudeYYY](#ISOSpeedLatitudeYYY) | Questo tag indica il valore di latitudine della velocità ISO yyy come definito nella ISO 12232 |
| [ISOSpeedLatitudeZZZ](#ISOSpeedLatitudeZZZ) | Questo tag indica il valore di latitudine della velocità ISO zzz come definito nella ISO 12232 |
| [CameraOwnerName](#CameraOwnerName) | Contiene il nome del proprietario della fotocamera |
| [BodySerialNumber](#BodySerialNumber) | Contiene il numero di serie del corpo della fotocamera |
| [LensMake](#LensMake) | Questo tag registra il produttore dell'obiettivo |
| [LensModel](#LensModel) | Questo tag registra il nome modello e il numero modello del lens\`s |
| [LensSerialNumber](#LensSerialNumber) | Questo tag registra il numero di serie dell'obiettivo intercambiabile |
| [LensSpecification](#LensSpecification) | Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo alla lunghezza focale minima e il numero F minimo alla lunghezza focale massima |
### ImageWidth {#ImageWidth}
```
public static final int ImageWidth
```


Il numero di colonne dei dati dell'immagine, pari al numero di pixel per riga.

### ImageLength {#ImageLength}
```
public static final int ImageLength
```


Il numero di righe dei dati dell'immagine.

### BitsPerSample {#BitsPerSample}
```
public static final int BitsPerSample
```


Il numero di bit per componente dell'immagine. In questo standard ogni componente dell'immagine è di 8 bit, quindi il valore per questo tag è 8.

### Compression {#Compression}
```
public static final int Compression
```


Lo schema di compressione utilizzato per i dati dell'immagine. Quando un'immagine primaria è compressa in JPEG, questa designazione non è necessaria e viene omessa.

### PhotometricInterpretation {#PhotometricInterpretation}
```
public static final int PhotometricInterpretation
```


La composizione dei pixel.

### ImageDescription {#ImageDescription}
```
public static final int ImageDescription
```


Una stringa di caratteri che fornisce il titolo dell'immagine. Può essere un commento come "1988 company picnic" o simili.

### Make {#Make}
```
public static final int Make
```


Il produttore dell'attrezzatura di registrazione. Questo è il produttore del DSC, scanner, digitalizzatore video o altra attrezzatura che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### Model {#Model}
```
public static final int Model
```


Il nome modello o il numero modello dell'attrezzatura. Questo è il nome modello o il numero del DSC, scanner, digitalizzatore video o altra attrezzatura che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### Orientation {#Orientation}
```
public static final int Orientation
```


L'orientamento dell'immagine visualizzato in termini di righe e colonne.

### SamplesPerPixel {#SamplesPerPixel}
```
public static final int SamplesPerPixel
```


Il numero di componenti per pixel. Poiché questo standard si applica alle immagini RGB e YCbCr, il valore impostato per questo tag è 3.

### XResolution {#XResolution}
```
public static final int XResolution
```


Il numero di pixel per ResolutionUnit nella direzione ImageWidth. Quando la risoluzione dell'immagine è sconosciuta, viene designato 72 [dpi].

### YResolution {#YResolution}
```
public static final int YResolution
```


Il numero di pixel per ResolutionUnit nella direzione ImageLength. Viene designato lo stesso valore di XResolution.

### PlanarConfiguration {#PlanarConfiguration}
```
public static final int PlanarConfiguration
```


Indica se i componenti dei pixel sono registrati in formato chunky o planar. Se questo campo non esiste, si assume il valore predefinito TIFF di 1 (chunky).

### ResolutionUnit {#ResolutionUnit}
```
public static final int ResolutionUnit
```


L'unità di misura per XResolution e YResolution. La stessa unità è usata sia per XResolution che per YResolution. Se la risoluzione dell'immagine è sconosciuta, viene designato 2 (pollici).

### TransferFunction {#TransferFunction}
```
public static final int TransferFunction
```


Una funzione di trasferimento per l'immagine, descritta in stile tabellare. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace.

### Software {#Software}
```
public static final int Software
```


Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di acquisizione immagine utilizzato per generare l'immagine. Il formato dettagliato non è specificato, ma si consiglia di seguire l'esempio mostrato di seguito. Quando il campo è lasciato vuoto, viene considerato sconosciuto.

### DateTime {#DateTime}
```
public static final int DateTime
```


La data e l'ora di creazione dell'immagine. Nello standard Exif, è la data e l'ora in cui il file è stato modificato.

### Artist {#Artist}
```
public static final int Artist
```


Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. Il formato dettagliato non è specificato, ma si consiglia di scrivere le informazioni come nell'esempio seguente per facilitare l'interoperabilità. Quando il campo è lasciato vuoto, viene considerato sconosciuto. (Es. "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James")

### WhitePoint {#WhitePoint}
```
public static final int WhitePoint
```


La cromaticità del punto bianco dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace.

### PrimaryChromaticities {#PrimaryChromaticities}
```
public static final int PrimaryChromaticities
```


La cromaticità dei tre colori primari dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace.

### YCbCrCoefficients {#YCbCrCoefficients}
```
public static final int YCbCrCoefficients
```


I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr.

### YCbCrSubSampling {#YCbCrSubSampling}
```
public static final int YCbCrSubSampling
```


Il rapporto di campionamento dei componenti di crominanza rispetto al componente di luminanza.

### YCbCrPositioning {#YCbCrPositioning}
```
public static final int YCbCrPositioning
```


La posizione dei componenti di crominanza rispetto al componente di luminanza. Questo campo è destinato solo a dati JPEG compressi o dati YCbCr non compressi. Il valore predefinito TIFF è 1 (centrato); ma quando Y:Cb:Cr = 4:2:2 è consigliato in questo standard utilizzare 2 (co-situato) per registrare i dati, al fine di migliorare la qualità dell'immagine visualizzata su sistemi TV. Quando questo campo non esiste, il lettore deve assumere il valore predefinito TIFF. Nel caso di Y:Cb:Cr = 4:2:0, è consigliato il valore predefinito TIFF (centrato). Se il lettore non ha la capacità di supportare entrambi i tipi di YCbCrPositioning, deve seguire il valore predefinito TIFF indipendentemente dal valore in questo campo. È preferibile che i lettori siano in grado di supportare sia il posizionamento centrato sia quello co-situato.

### ReferenceBlackWhite {#ReferenceBlackWhite}
```
public static final int ReferenceBlackWhite
```


Il valore del punto nero di riferimento e il valore del punto bianco di riferimento. Non sono forniti valori predefiniti in TIFF, ma i valori seguenti sono indicati qui come predefiniti. Lo spazio colore è dichiarato in un tag di informazione sullo spazio colore, con il valore predefinito che fornisce le caratteristiche ottimali dell'immagine Interoperability in queste condizioni.

### Copyright {#Copyright}
```
public static final int Copyright
```


Informazioni sul copyright. In questo standard il tag è usato per indicare sia i diritti d'autore del fotografo che dell'editor. È la nota di copyright della persona o organizzazione che rivendica i diritti sull'immagine. La dichiarazione di copyright Interoperability includendo data e diritti dovrebbe essere scritta in questo campo; ad esempio, "Copyright, John Smith, 19xx. All rights reserved." In questo standard il campo registra sia i diritti d'autore del fotografo sia quelli dell'editor, ciascuno registrato in una parte separata della dichiarazione. Quando c'è una chiara distinzione tra i diritti d'autore del fotografo e dell'editor, questi devono essere scritti nell'ordine fotografo seguito da editor, separati da NULL (in questo caso, poiché la dichiarazione termina anche con un NULL, ci sono due codici NULL). Quando è fornito solo il copyright del fotografo, è terminato da un codice NULL. Quando è fornito solo il copyright dell'editor, la parte del copyright del fotografo consiste in uno spazio seguito da un codice NULL terminatore, poi viene fornito il copyright dell'editor. Quando il campo è lasciato vuoto, è trattato come sconosciuto.

### ExposureTime {#ExposureTime}
```
public static final int ExposureTime
```


Tempo di esposizione, espresso in secondi.

### FNumber {#FNumber}
```
public static final int FNumber
```


Il numero F.

### ExposureProgram {#ExposureProgram}
```
public static final int ExposureProgram
```


La classe del programma usato dalla fotocamera per impostare l'esposizione al momento dello scatto.

### SpectralSensitivity {#SpectralSensitivity}
```
public static final int SpectralSensitivity
```


Indica la sensibilità spettrale di ciascun canale della fotocamera utilizzata.

### PhotographicSensitivity {#PhotographicSensitivity}
```
public static final int PhotographicSensitivity
```


Indica la velocità ISO e la latitudine ISO della fotocamera o del dispositivo di input come specificato nella ISO 12232.

### OECF {#OECF}
```
public static final int OECF
```


Indica la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524.

### ExifVersion {#ExifVersion}
```
public static final int ExifVersion
```


La versione Exif.

### DateTimeOriginal {#DateTimeOriginal}
```
public static final int DateTimeOriginal
```


La data e l'ora in cui sono stati generati i dati immagine originali.

### DateTimeDigitized {#DateTimeDigitized}
```
public static final int DateTimeDigitized
```


La data e l'ora di digitalizzazione.

### ComponentsConfiguration {#ComponentsConfiguration}
```
public static final int ComponentsConfiguration
```


La configurazione dei componenti.

### CompressedBitsPerPixel {#CompressedBitsPerPixel}
```
public static final int CompressedBitsPerPixel
```


Specifico per dati compressi; indica i bit compressi per pixel.

### ShutterSpeedValue {#ShutterSpeedValue}
```
public static final int ShutterSpeedValue
```


Il valore della velocità dell'otturatore.

### ApertureValue {#ApertureValue}
```
public static final int ApertureValue
```


Il valore dell'apertura dell'obiettivo.

### BrightnessValue {#BrightnessValue}
```
public static final int BrightnessValue
```


Il valore della luminosità.

### ExposureBiasValue {#ExposureBiasValue}
```
public static final int ExposureBiasValue
```


Il valore del compenso di esposizione.

### MaxApertureValue {#MaxApertureValue}
```
public static final int MaxApertureValue
```


Il valore dell'apertura massima.

### SubjectDistance {#SubjectDistance}
```
public static final int SubjectDistance
```


La distanza dal soggetto, espressa in metri.

### MeteringMode {#MeteringMode}
```
public static final int MeteringMode
```


La modalità di misurazione.

### LightSource {#LightSource}
```
public static final int LightSource
```


Il tipo di sorgente luminosa.

### Flash {#Flash}
```
public static final int Flash
```


Indica lo stato del flash al momento dello scatto dell'immagine.

### FocalLength {#FocalLength}
```
public static final int FocalLength
```


La lunghezza focale reale dell'obiettivo, in mm.

### SubjectArea {#SubjectArea}
```
public static final int SubjectArea
```


Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva.

### MakerNote {#MakerNote}
```
public static final int MakerNote
```


Un tag per i produttori di scrittori Exif per registrare qualsiasi informazione desiderata. Il contenuto è a discrezione del produttore, ma questo tag non dovrebbe essere usato per altro scopo diverso da quello previsto.

### UserComment {#UserComment}
```
public static final int UserComment
```


Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli in ImageDescription, e senza le limitazioni di codifica dei caratteri del tag ImageDescription.

### SubsecTime {#SubsecTime}
```
public static final int SubsecTime
```


Un tag usato per registrare frazioni di secondo per il tag DateTime.

### SubsecTimeOriginal {#SubsecTimeOriginal}
```
public static final int SubsecTimeOriginal
```


Un tag usato per registrare frazioni di secondo per il tag DateTimeOriginal.

### SubsecTimeDigitized {#SubsecTimeDigitized}
```
public static final int SubsecTimeDigitized
```


Un tag usato per registrare frazioni di secondo per il tag DateTimeDigitized.

### FlashpixVersion {#FlashpixVersion}
```
public static final int FlashpixVersion
```


La versione del formato Flashpix supportata da un file FPXR.

### ColorSpace {#ColorSpace}
```
public static final int ColorSpace
```


Il tag di informazione dello spazio colore (ColorSpace) è sempre registrato come specificatore dello spazio colore.

### RelatedSoundFile {#RelatedSoundFile}
```
public static final int RelatedSoundFile
```


Il file audio correlato.

### FlashEnergy {#FlashEnergy}
```
public static final int FlashEnergy
```


Indica l'energia dello strobo al momento della cattura dell'immagine, misurata in Beam Candle Power Seconds (BCPS).

### SpatialFrequencyResponse {#SpatialFrequencyResponse}
```
public static final int SpatialFrequencyResponse
```


Questo tag registra la tabella di frequenza spaziale della fotocamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato nella ISO 12233.

### FocalPlaneXResolution {#FocalPlaneXResolution}
```
public static final int FocalPlaneXResolution
```


Indica il numero di pixel nella direzione della larghezza dell'immagine (X) per FocalPlaneResolutionUnit sul piano focale della fotocamera.

### FocalPlaneYResolution {#FocalPlaneYResolution}
```
public static final int FocalPlaneYResolution
```


Indica il numero di pixel nella direzione dell'altezza dell'immagine (Y) per FocalPlaneResolutionUnit sul piano focale della fotocamera.

### FocalPlaneResolutionUnit {#FocalPlaneResolutionUnit}
```
public static final int FocalPlaneResolutionUnit
```


Indica l'unità di misura per FocalPlaneXResolution e FocalPlaneYResolution. Questo valore è lo stesso di ResolutionUnit.

### SubjectLocation {#SubjectLocation}
```
public static final int SubjectLocation
```


Indica la posizione del soggetto principale nella scena. Il valore di questo tag rappresenta il pixel al centro del soggetto principale rispetto al bordo sinistro, prima dell'elaborazione di rotazione secondo il tag Rotation.

### ExposureIndex {#ExposureIndex}
```
public static final int ExposureIndex
```


Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento della cattura dell'immagine.

### SensingMethod {#SensingMethod}
```
public static final int SensingMethod
```


Indica il tipo di sensore d'immagine sulla fotocamera o sul dispositivo di input.

### FileSource {#FileSource}
```
public static final int FileSource
```


La sorgente del file.

### SceneType {#SceneType}
```
public static final int SceneType
```


Indica il tipo di scena. Se una DSC ha registrato l'immagine, il valore di questo tag deve sempre essere impostato a 1, indicando che l'immagine è stata fotografata direttamente.

### CFAPattern {#CFAPattern}
```
public static final int CFAPattern
```


Indica il modello geometrico della matrice di filtri colore (CFA) del sensore d'immagine quando viene utilizzato un sensore a zona colore a chip unico. Non si applica a tutti i metodi di rilevamento.

### CustomRendered {#CustomRendered}
```
public static final int CustomRendered
```


Questo tag indica l'uso di elaborazioni speciali sui dati dell'immagine, come il rendering orientato all'output. Quando viene eseguita un'elaborazione speciale, ci si aspetta che il lettore disabiliti o riduca al minimo ulteriori elaborazioni.

### ExposureMode {#ExposureMode}
```
public static final int ExposureMode
```


Questo tag indica la modalità di esposizione impostata al momento dello scatto dell'immagine. In modalità auto-bracketing, la fotocamera scatta una serie di fotogrammi della stessa scena con impostazioni di esposizione diverse.

### WhiteBalance {#WhiteBalance}
```
public static final int WhiteBalance
```


Questo tag indica la modalità di bilanciamento del bianco impostata al momento dello scatto dell'immagine.

### DigitalZoomRatio {#DigitalZoomRatio}
```
public static final int DigitalZoomRatio
```


Questo tag indica il rapporto di zoom digitale al momento dello scatto dell'immagine. Se il numeratore del valore registrato è 0, ciò indica che non è stato utilizzato lo zoom digitale.

### FocalLengthIn35MmFilm {#FocalLengthIn35MmFilm}
```
public static final int FocalLengthIn35MmFilm
```


Questo tag indica la lunghezza focale equivalente assumendo una fotocamera a pellicola da 35 mm, in mm. Un valore di 0 indica che la lunghezza focale è sconosciuta. Si noti che questo tag differisce dal tag FocalLength.

### SceneCaptureType {#SceneCaptureType}
```
public static final int SceneCaptureType
```


Questo tag indica il tipo di scena che è stata fotografata. Può anche essere usato per registrare la modalità in cui è stata scattata l'immagine.

### GainControl {#GainControl}
```
public static final int GainControl
```


Questo tag indica il grado di regolazione complessiva del guadagno dell'immagine.

### Contrast {#Contrast}
```
public static final int Contrast
```


Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera al momento dello scatto.

### Saturation {#Saturation}
```
public static final int Saturation
```


Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera al momento dello scatto.

### Sharpness {#Sharpness}
```
public static final int Sharpness
```


Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera al momento dello scatto

### DeviceSettingDescription {#DeviceSettingDescription}
```
public static final int DeviceSettingDescription
```


Questo tag indica informazioni sulle condizioni di scatto di un modello di fotocamera specifico. Il tag è usato solo per indicare le condizioni di scatto nel lettore.

### SubjectDistanceRange {#SubjectDistanceRange}
```
public static final int SubjectDistanceRange
```


Questo tag indica la distanza dal soggetto.

### ImageUniqueID {#ImageUniqueID}
```
public static final int ImageUniqueID
```


L'ID unico dell'immagine.

### GPSVersionID {#GPSVersionID}
```
public static final int GPSVersionID
```


Indica la versione di GPSInfoIFD.

### GPSLatitudeRef {#GPSLatitudeRef}
```
public static final int GPSLatitudeRef
```


Indica se la latitudine è nord o sud.

### GPSLatitude {#GPSLatitude}
```
public static final int GPSLatitude
```


Indica la latitudine. La latitudine è espressa come tre valori RATIONAL che forniscono rispettivamente i gradi, i minuti e i secondi. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe dd/1,mm/1,ss/1. Quando vengono usati gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1.

### GPSLongitudeRef {#GPSLongitudeRef}
```
public static final int GPSLongitudeRef
```


Indica se la longitudine è est o ovest.

### GPSLongitude {#GPSLongitude}
```
public static final int GPSLongitude
```


Indica la longitudine. La longitudine è espressa come tre valori RATIONAL che forniscono rispettivamente i gradi, i minuti e i secondi. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe ddd/1,mm/1,ss/1. Quando vengono usati gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1.

### GPSAltitudeRef {#GPSAltitudeRef}
```
public static final int GPSAltitudeRef
```


Indica l'altitudine usata come altitudine di riferimento. Se il riferimento è il livello del mare e l'altitudine è sopra il livello del mare, viene fornito 0. Se l'altitudine è sotto il livello del mare, viene fornito 1 e l'altitudine è indicata come valore assoluto nel tag GPSAltitude.

### GPSAltitude {#GPSAltitude}
```
public static final int GPSAltitude
```


Indica l'altitudine basata sul riferimento in GPSAltitudeRef. L'altitudine è espressa come un valore RATIONAL. L'unità di riferimento è il metro.

### GPSTimestamp {#GPSTimestamp}
```
public static final int GPSTimestamp
```


Indica l'ora in UTC (Coordinated Universal Time). TimeStamp è espresso come tre valori RATIONAL che forniscono l'ora, il minuto e il secondo.

### GPSSatellites {#GPSSatellites}
```
public static final int GPSSatellites
```


Indica i satelliti GPS usati per le misurazioni. Questo tag può essere usato per descrivere il numero di satelliti, il loro numero ID, l'angolo di elevazione, l'azimut, SNR e altre informazioni in notazione ASCII. Il formato non è specificato. Se il ricevitore GPS è incapace di effettuare misurazioni, il valore del tag deve essere impostato a NULL.

### GPSStatus {#GPSStatus}
```
public static final int GPSStatus
```


Indica lo stato del ricevitore GPS al momento della registrazione dell'immagine.

### GPSMeasureMode {#GPSMeasureMode}
```
public static final int GPSMeasureMode
```


Indica la modalità di misurazione GPS. - 2- o 3-dimensionale.

### GPSDOP {#GPSDOP}
```
public static final int GPSDOP
```


Indica il GPS DOP (degree of precision dei dati). Un valore HDOP è registrato durante la misurazione bidimensionale, e PDOP durante la misurazione tridimensionale.

### GPSSpeedRef {#GPSSpeedRef}
```
public static final int GPSSpeedRef
```


Indica l'unità usata per esprimere la velocità di movimento del ricevitore GPS. 'K', 'M' e 'N' rappresentano chilometri all'ora, miglia all'ora e nodi.

### GPSSpeed {#GPSSpeed}
```
public static final int GPSSpeed
```


Indica la velocità di movimento del ricevitore GPS.

### GPSTrackRef {#GPSTrackRef}
```
public static final int GPSTrackRef
```


Indica il riferimento per fornire la direzione del movimento del ricevitore GPS. 'T' indica la direzione vera e 'M' quella magnetica.

### GPSTrack {#GPSTrack}
```
public static final int GPSTrack
```


Indica la direzione del movimento del ricevitore GPS. L'intervallo di valori è da 0.00 a 359.99.

### GPSImgDirectionRef {#GPSImgDirectionRef}
```
public static final int GPSImgDirectionRef
```


Indica il riferimento per fornire la direzione dell'immagine al momento della cattura. 'T' indica la direzione vera e 'M' quella magnetica.

### GPSImgDirection {#GPSImgDirection}
```
public static final int GPSImgDirection
```


Indica la direzione dell'immagine al momento della cattura. L'intervallo di valori è da 0.00 a 359.99.

### GPSMapDatum {#GPSMapDatum}
```
public static final int GPSMapDatum
```


Indica i dati di rilievo geodetico utilizzati dal ricevitore GPS.

### GPSDestLatitudeRef {#GPSDestLatitudeRef}
```
public static final int GPSDestLatitudeRef
```


Indica se la latitudine del punto di destinazione è nord o sud. Il valore ASCII 'N' indica la latitudine nord, e 'S' quella sud.

### GPSDestLatitude {#GPSDestLatitude}
```
public static final int GPSDestLatitude
```


Indica la latitudine del punto di destinazione. La latitudine è espressa come tre valori RATIONAL che forniscono rispettivamente gradi, minuti e secondi. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe dd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1.

### GPSDestLongitudeRef {#GPSDestLongitudeRef}
```
public static final int GPSDestLongitudeRef
```


Indica se la longitudine del punto di destinazione è est o ovest. L'ASCII 'E' indica la longitudine est, e 'W' quella ovest.

### GPSDestLongitude {#GPSDestLongitude}
```
public static final int GPSDestLongitude
```


Indica la longitudine del punto di destinazione. La longitudine è espressa come tre valori RATIONAL che forniscono rispettivamente gradi, minuti e secondi. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe ddd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1.

### GPSDestBearingRef {#GPSDestBearingRef}
```
public static final int GPSDestBearingRef
```


Indica il riferimento usato per fornire la rotta verso il punto di destinazione. 'T' indica la direzione vera e 'M' quella magnetica.

### GPSDestBearing {#GPSDestBearing}
```
public static final int GPSDestBearing
```


Indica la rotta verso il punto di destinazione. L'intervallo di valori è da 0.00 a 359.99.

### GPSDestDistanceRef {#GPSDestDistanceRef}
```
public static final int GPSDestDistanceRef
```


Indica l'unità usata per esprimere la distanza al punto di destinazione. 'K', 'M' e 'N' rappresentano chilometri, miglia e nodi.

### GPSDestDistance {#GPSDestDistance}
```
public static final int GPSDestDistance
```


Indica la distanza al punto di destinazione.

### GPSProcessingMethod {#GPSProcessingMethod}
```
public static final int GPSProcessingMethod
```


Una stringa di caratteri che registra il nome del metodo utilizzato per la localizzazione. Il primo byte indica il codice carattere usato, seguito dal nome del metodo.

### GPSAreaInformation {#GPSAreaInformation}
```
public static final int GPSAreaInformation
```


Una stringa di caratteri che registra il nome dell'area GPS. Il primo byte indica il codice carattere usato, seguito dal nome dell'area GPS.

### GPSDateStamp {#GPSDateStamp}
```
public static final int GPSDateStamp
```


Una stringa di caratteri che registra le informazioni di data e ora relative a UTC (Tempo Universale Coordinato). Il formato è YYYY:MM:DD.

### GPSDifferential {#GPSDifferential}
```
public static final int GPSDifferential
```


Indica se la correzione differenziale è applicata al ricevitore GPS.

### StripOffsets {#StripOffsets}
```
public static final int StripOffsets
```


Per ogni strip, l'offset in byte di quello strip. Si raccomanda di selezionarlo in modo che il numero di byte dello strip non superi 64 KByte. Tag Aux.

### JPEGInterchangeFormat {#JPEGInterchangeFormat}
```
public static final int JPEGInterchangeFormat
```


L'offset al byte iniziale (SOI) dei dati della miniatura JPEG compressa. Non è usato per i dati JPEG dell'immagine primaria.

### JPEGInterchangeFormatLength {#JPEGInterchangeFormatLength}
```
public static final int JPEGInterchangeFormatLength
```


Il numero di byte dei dati della miniatura JPEG compressa. Non è usato per i dati JPEG dell'immagine primaria. Le miniature JPEG non sono suddivise ma sono registrate come un flusso continuo di JPEG dal SOI all'EOI. I marcatori Appn e COM non devono essere registrati. Le miniature compresse devono essere registrate in non più di 64 KByte, includendo tutti gli altri dati da registrare in APP1.

### ExifIfdPointer {#ExifIfdPointer}
```
public static final int ExifIfdPointer
```


Un puntatore all'Exif IFD. L'interoperabilità, l'Exif IFD ha la stessa struttura dell'IFD specificato in TIFF. Tuttavia, normalmente non contiene dati immagine come nel caso di TIFF.

### GPSIfdPointer {#GPSIfdPointer}
```
public static final int GPSIfdPointer
```


Il puntatore gps ifd.

### RowsPerStrip {#RowsPerStrip}
```
public static final int RowsPerStrip
```


Il numero di righe per strip. Questo è il numero di righe nell'immagine di uno strip quando un'immagine è divisa in strip.

### StripByteCounts {#StripByteCounts}
```
public static final int StripByteCounts
```


Il numero totale di byte in ogni striscia.

### PixelXDimension {#PixelXDimension}
```
public static final int PixelXDimension
```


Informazioni specifiche per i dati compressi. Quando un file compresso è registrato, la larghezza valida dell'immagine significativa deve essere registrata in questo tag, indipendentemente dalla presenza di dati di riempimento o di un marcatore di riavvio.

### PixelYDimension {#PixelYDimension}
```
public static final int PixelYDimension
```


Informazioni specifiche per i dati compressi. Quando un file compresso è registrato, l'altezza valida dell'immagine significativa deve essere registrata in questo tag.

### Gamma {#Gamma}
```
public static final int Gamma
```


Valore gamma

### SensitivityType {#SensitivityType}
```
public static final int SensitivityType
```


Tipo di sensibilità fotografica

### StandardOutputSensitivity {#StandardOutputSensitivity}
```
public static final int StandardOutputSensitivity
```


Indica la sensibilità di uscita standard della fotocamera

### RecommendedExposureIndex {#RecommendedExposureIndex}
```
public static final int RecommendedExposureIndex
```


Indica l'indice di esposizione consigliato

### ISOSpeed {#ISOSpeed}
```
public static final int ISOSpeed
```


Informazioni sul valore di velocità ISO come definito nella ISO 12232

### ISOSpeedLatitudeYYY {#ISOSpeedLatitudeYYY}
```
public static final int ISOSpeedLatitudeYYY
```


Questo tag indica il valore di latitudine della velocità ISO yyy come definito nella ISO 12232

### ISOSpeedLatitudeZZZ {#ISOSpeedLatitudeZZZ}
```
public static final int ISOSpeedLatitudeZZZ
```


Questo tag indica il valore di latitudine della velocità ISO zzz come definito nella ISO 12232

### CameraOwnerName {#CameraOwnerName}
```
public static final int CameraOwnerName
```


Contiene il nome del proprietario della fotocamera

### BodySerialNumber {#BodySerialNumber}
```
public static final int BodySerialNumber
```


Contiene il numero di serie del corpo della fotocamera

### LensMake {#LensMake}
```
public static final int LensMake
```


Questo tag registra il produttore dell'obiettivo

### LensModel {#LensModel}
```
public static final int LensModel
```


Questo tag registra il nome modello e il numero modello del lens\`s

### LensSerialNumber {#LensSerialNumber}
```
public static final int LensSerialNumber
```


Questo tag registra il numero di serie dell'obiettivo intercambiabile

### LensSpecification {#LensSpecification}
```
public static final int LensSpecification
```


Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo alla lunghezza focale minima e il numero F minimo alla lunghezza focale massima

