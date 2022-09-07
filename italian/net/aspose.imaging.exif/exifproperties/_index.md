---
title: ExifProperties
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Elenco tag Exif
type: docs
weight: 1080
url: /it/net/aspose.imaging.exif/exifproperties/
---
## ExifProperties enumeration

Elenco tag Exif

```csharp
public enum ExifProperties : ushort
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| ImageWidth | `256` | Il numero di colonne di dati immagine, uguale al numero di pixel per riga. |
| ImageLength | `257` | Il numero di righe di dati immagine. |
| BitsPerSample | `258` | Il numero di bit per componente dell'immagine. In questo standard ogni componente dell'immagine è 8 bit, quindi il valore per questo tag è 8. |
| Compression | `259` | Lo schema di compressione utilizzato per i dati dell'immagine. Quando un'immagine primaria è compressa JPEG, questa designazione non è necessaria e viene omessa. |
| PhotometricInterpretation | `262` | La composizione dei pixel. |
| ImageDescription | `270` | Una stringa di caratteri che fornisce il titolo dell'immagine. Potrebbe essere un commento come "Picnic aziendale del 1988" o simili. |
| Make | `271` | Il produttore dell'apparecchio di registrazione. Questo è il produttore del DSC, scanner, digitalizzatore video o altra apparecchiatura che ha generato l'immagine. Quando il campo viene lasciato vuoto, viene considerato sconosciuto. |
| Model | `272` | Il nome del modello o il numero del modello dell'apparecchiatura. Questo è il nome del modello o il numero del DSC, scanner, digitalizzatore video o altro apparecchio che ha generato l'immagine. Quando il campo viene lasciato vuoto, viene considerato sconosciuto. |
| Orientation | `274` | L'orientamento dell'immagine visualizzato in termini di righe e colonne. |
| SamplesPerPixel | `277` | Il numero di componenti per pixel. Poiché questo standard si applica alle immagini RGB e YCbCr, il valore impostato per questo tag è 3. |
| XResolution | `282` | Il numero di pixel per ResolutionUnit nella direzione ImageWidth. Quando la risoluzione dell'immagine è sconosciuta, viene designato 72 [dpi]. |
| YResolution | `283` | Il numero di pixel per ResolutionUnit nella direzione ImageLength. Viene designato lo stesso valore di XResolution. |
| PlanarConfiguration | `284` | Indica se i componenti dei pixel sono registrati in un formato grosso o planare. Se questo campo non esiste, viene presupposto il valore predefinito TIFF di 1 (grosso). |
| ResolutionUnit | `296` | L'unità per misurare XResolution e YResolution. La stessa unità viene utilizzata sia per XResolution che per YResolution. Se la risoluzione dell'immagine è sconosciuta, viene designato 2 (pollici). |
| TransferFunction | `301` | Una funzione di trasferimento per l'immagine, descritta in stile tabellare. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag ColorSpace delle informazioni sullo spazio colore. |
| Software | `305` | Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di input dell'immagine utilizzato per generare l'immagine. Il formato dettagliato non è specificato, ma si consiglia di seguire l'esempio mostrato di seguito. Quando il campo viene lasciato vuoto, viene considerato sconosciuto. |
| DateTime | `306` | La data e l'ora di creazione dell'immagine. Nello standard Exif, è la data e l'ora in cui il file è stato modificato. |
| Artist | `315` | Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. Il formato dettagliato non è specificato, ma si consiglia di scrivere le informazioni come nell'esempio seguente per facilitare l'interoperabilità. Quando il campo viene lasciato vuoto, viene considerato sconosciuto. Es.) "Proprietario della fotocamera, John Smith; Fotografo, Michael Brown; Creatore dell'immagine, Ken James" |
| WhitePoint | `318` | La cromaticità del punto bianco dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag ColorSpace delle informazioni sullo spazio colore. |
| PrimaryChromaticities | `319` | La cromaticità dei tre colori primari dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag ColorSpace delle informazioni sullo spazio colore. |
| YCbCrCoefficients | `529` | I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr. |
| YCbCrSubSampling | `530` | Il rapporto di campionamento delle componenti di crominanza in relazione alla componente di luminanza. |
| YCbCrPositioning | `531` | La posizione dei componenti di crominanza rispetto al componente di luminanza . Questo campo è designato solo per dati compressi JPEG o dati YCbCr non compressi. Il valore predefinito TIFF è 1 (centrato); ma quando Y:Cb:Cr = 4:2:2 è raccomandato in questo standard che 2 (co-situati) siano usati per registrare i dati, al fine di migliorare la qualità dell'immagine quando viene visualizzata su sistemi TV. Quando questo campo non esiste, il lettore deve assumere l'impostazione predefinita TIFF. Nel caso di Y:Cb:Cr = 4:2:0, si consiglia l'impostazione predefinita TIFF (centrata). Se il lettore non ha la capacità di supportare entrambi i tipi di YCbCrPositioning, seguirà il TIFF predefinito indipendentemente dal valore in questo campo. È preferibile che i lettori " siano in grado di supportare sia il posizionamento centrato che quello co-situato. |
| ReferenceBlackWhite | `532` | Il valore del punto nero di riferimento e il valore del punto bianco di riferimento . Non vengono fornite impostazioni predefinite in TIFF, ma i valori seguenti sono indicati come predefiniti qui. Lo spazio colore è dichiarato in un tag di informazioni sullo spazio colore, con il valore predefinito che è il valore che fornisce le caratteristiche ottimali dell'immagine Interoperabilità queste condizioni |
| Copyright | `33432` | Informazioni sul copyright. In questo standard il tag viene utilizzato per indicare i diritti d'autore sia del fotografo che dell'editore. È l'avviso di copyright della persona o organizzazione che rivendica i diritti sull'immagine. L'istruzione Interoperability copyright che include data e diritti dovrebbe essere scritta in questo campo ; ad esempio, "Copyright, John Smith, 19xx. Tutti i diritti riservati.". In questo standard il campo registra i diritti d'autore sia del fotografo che dell'editore, ciascuno registrato in una parte separata della dichiarazione. Quando c'è una chiara distinzione tra i diritti d'autore del fotografo e dell'editore, questi devono essere scritti nell'ordine del fotografo seguito dal copyright dell'editore, separati da NULL (in questo caso poiché la dichiarazione termina anche con un NULL, ci sono due codici NULL ). Quando viene fornito solo il copyright del fotografo , viene terminato da un codice NULL . Quando viene fornito solo il copyright dell'editor, la parte del copyright del fotografo è composta da uno spazio seguito da un codice NULL finale, quindi viene fornito il copyright dell'editor. Quando il campo viene lasciato vuoto, viene trattato come sconosciuto. |
| ExposureTime | `33434` | Tempo di esposizione, espresso in secondi. |
| FNumber | `33437` | Il numero F. |
| ExposureProgram | `34850` | La classe del programma utilizzato dalla fotocamera per impostare l'esposizione quando viene scattata la foto. |
| SpectralSensitivity | `34852` | Indica la sensibilità spettrale di ciascun canale della telecamera utilizzata. |
| PhotographicSensitivity | `34855` | Indica la velocità ISO e la latitudine ISO della fotocamera o del dispositivo di input come specificato in ISO 12232. |
| OECF | `34856` | Indica la funzione di conversione optoelettrica (OECF) specificata nella ISO 14524. |
| ExifVersion | `36864` | La versione exif. |
| DateTimeOriginal | `36867` | La data e l'ora in cui sono stati generati i dati dell'immagine originale. |
| DateTimeDigitized | `36868` | La data e l'ora digitalizzata. |
| ComponentsConfiguration | `37121` | La configurazione dei componenti. |
| CompressedBitsPerPixel | `37122` | Specifico per dati compressi; indica i bit compressi per pixel. |
| ShutterSpeedValue | `37377` | Il valore della velocità dell'otturatore. |
| ApertureValue | `37378` | Il valore di apertura dell'obiettivo. |
| BrightnessValue | `37379` | Il valore di luminosità. |
| ExposureBiasValue | `37380` | Il valore di distorsione dell'esposizione. |
| MaxApertureValue | `37381` | Il valore di apertura massimo. |
| SubjectDistance | `37382` | La distanza dal soggetto, espressa in metri. |
| MeteringMode | `37383` | La modalità di misurazione. |
| LightSource | `37384` | La gentile fonte di luce. |
| Flash | `37385` | Indica lo stato del flash quando è stata scattata l'immagine. |
| FocalLength | `37386` | La lunghezza focale effettiva dell'obiettivo, in mm. |
| SubjectArea | `37396` | Questo tag indica la posizione e l'area del soggetto principale nella scena generale. |
| MakerNote | `37500` | Un tag per i produttori di writer Exif per registrare tutte le informazioni desiderate. I contenuti sono a discrezione del produttore, ma questo tag non deve essere utilizzato per scopi diversi dallo scopo previsto. |
| UserComment | `37510` | Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli in ImageDescription e senza le limitazioni del codice carattere del tag ImageDescription. |
| SubsecTime | `37520` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTime. |
| SubsecTimeOriginal | `37521` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTimeOriginal. |
| SubsecTimeDigitized | `37522` | Un tag utilizzato per registrare frazioni di secondo per il tag DateTimeDigitized. |
| FlashpixVersion | `40960` | La versione del formato Flashpix supportata da un file FPXR. |
| ColorSpace | `40961` | Il tag delle informazioni sullo spazio colore (ColorSpace) viene sempre registrato come identificatore dello spazio colore. |
| RelatedSoundFile | `40964` | Il relativo file audio. |
| FlashEnergy | `41483` | Indica l'energia stroboscopica al momento dell'acquisizione dell'immagine, misurata in Beam Candle Power Seconds (BCPS). |
| SpatialFrequencyResponse | `41484` | Questo tag registra la tabella della frequenza spaziale della telecamera o del dispositivo di input e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione della diagonale, come specificato in ISO 12233. |
| FocalPlaneXResolution | `41486` | Indica il numero di pixel nella direzione della larghezza dell'immagine (X) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| FocalPlaneYResolution | `41487` | Indica il numero di pixel nella direzione dell'altezza dell'immagine (Y) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| FocalPlaneResolutionUnit | `41488` | Indica l'unità per misurare FocalPlaneXResolution e FocalPlaneYResolution. Questo valore è lo stesso di ResolutionUnit. |
| SubjectLocation | `41492` | Indica la posizione del soggetto principale nella scena. Il valore di questo tag rappresenta il pixel al centro del soggetto principale rispetto al bordo sinistro, prima dell'elaborazione della rotazione secondo il tag Rotation. |
| ExposureIndex | `41493` | Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento dell'acquisizione dell'immagine. |
| SensingMethod | `41495` | Indica il tipo di sensore di immagine sulla fotocamera o sul dispositivo di input. |
| FileSource | `41728` | L'origine del file. |
| SceneType | `41729` | Indica il tipo di scena. Se un DSC ha registrato l'immagine, questo valore del tag deve essere sempre impostato su 1, a indicare che l'immagine è stata fotografata direttamente. |
| CFAPattern | `41730` | Indica il motivo geometrico della matrice di filtri colore (CFA) del sensore di immagine quando viene utilizzato un sensore di area colore a un chip. Non si applica a tutti i metodi di rilevamento. |
| CustomRendered | `41985` | Questo tag indica l'uso di un'elaborazione speciale sui dati dell'immagine, come il rendering orientato all'output. Quando viene eseguita un'elaborazione speciale, il lettore deve disabilitare o ridurre al minimo qualsiasi ulteriore elaborazione. |
| ExposureMode | `41986` | Questo tag indica la modalità di esposizione impostata al momento dello scatto dell'immagine. Nella modalità di bracketing automatico, la fotocamera riprende una serie di fotogrammi della stessa scena con impostazioni di esposizione diverse. |
| WhiteBalance | `41987` | Questo tag indica la modalità di bilanciamento del bianco impostata al momento dello scatto dell'immagine. |
| DigitalZoomRatio | `41988` | Questo tag indica il rapporto di zoom digitale al momento dello scatto dell'immagine. Se il numeratore del valore registrato è 0, significa che non è stato utilizzato lo zoom digitale. |
| FocalLengthIn35MmFilm | `41989` | Questo tag indica la lunghezza focale equivalente assumendo una fotocamera con pellicola da 35 mm, in mm. Un valore di 0 significa che la lunghezza focale è sconosciuta. Nota che questo tag è diverso dal tag FocalLength. |
| SceneCaptureType | `41990` | Questo tag indica il tipo di scena che è stata girata. Può anche essere utilizzato per registrare la modalità in cui è stata scattata l'immagine. |
| GainControl | `41991` | Questo tag indica il grado di regolazione complessiva del guadagno dell'immagine. |
| Contrast | `41992` | Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera quando è stata scattata l'immagine. |
| Saturation | `41993` | Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera quando è stata scattata l'immagine. |
| Sharpness | `41994` | Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera quando è stata scattata l'immagine |
| DeviceSettingDescription | `41995` | Questo tag indica informazioni sulle condizioni di ripresa di un particolare modello di fotocamera. Il tag viene utilizzato solo per indicare le condizioni di ripresa delle immagini nel lettore. |
| SubjectDistanceRange | `41996` | Questo tag indica la distanza dal soggetto. |
| ImageUniqueID | `42016` | L'ID univoco dell'immagine. |
| GPSVersionID | `0` | Indica la versione di GPSInfoIFD. |
| GPSLatitudeRef | `1` | Indica se la latitudine è latitudine nord o sud. |
| GPSLatitude | `2` | Indica la latitudine. La latitudine è espressa come tre valori RAZIONALI che forniscono rispettivamente i gradi, i minuti e secondi. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe gg/1,mm/1,ss/1. Quando vengono utilizzati gradi e minuti e, ad esempio, vengono fornite frazioni di minuti fino a due cifre decimali, il formato sarebbe gg/1,mmmm/100,0/1. |
| GPSLongitudeRef | `3` | Indica se la longitudine è est o longitudine ovest. |
| GPSLongitude | `4` | Indica la longitudine. La longitudine è espressa come tre valori RAZIONALI che forniscono rispettivamente i gradi, i minuti e secondi. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe ddd/1,mm/1,ss/1. Quando vengono utilizzati gradi e minuti e, ad esempio, vengono fornite frazioni di minuti fino a due cifre decimali, il formato sarebbe gg/1,mmmm/100,0/1. |
| GPSAltitudeRef | `5` | Indica l'altitudine utilizzata come altitudine di riferimento. Se il riferimento è il livello del mare e l'altitudine è sopra il livello del mare, viene dato 0. Se l'altitudine è sotto il livello del mare, viene dato un valore di 1 e l'altitudine è indicata come valore assoluto in il tag GPSAltitude. |
| GPSAltitude | `6` | Indica l'altitudine in base al riferimento in GPSAltitudeRef. L'altitudine è espressa come un valore RAZIONALE. L'unità di riferimento è metri. |
| GPSTimestamp | `7` | Indica l'ora come UTC (Coordinated Universal Time). TimeStamp è espresso come tre valori RAZIONALI che forniscono l'ora, i minuti ei secondi. |
| GPSSatellites | `8` | Indica i satelliti GPS utilizzati per le misurazioni. Questo tag può essere utilizzato per descrivere il numero di satelliti, il loro numero ID, angolo di elevazione, azimut, SNR e altre informazioni in notazione ASCII. Il formato non è specificato. Se il ricevitore GPS non è in grado di effettuare misurazioni, il valore del tag deve essere impostato su NULL. |
| GPSStatus | `9` | Indica lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| GPSMeasureMode | `10` | Indica la modalità di misurazione GPS. - 2 o 3 dimensioni. |
| GPSDOP | `11` | Indica il DOP GPS (grado di precisione dei dati). Un valore HDOP viene scritto durante la misurazione bidimensionale, e PDOP durante la misurazione tridimensionale. |
| GPSSpeedRef | `12` | Indica l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. 'K' 'M' e 'N' rappresentano chilometri per ora, miglia orarie e nodi. |
| GPSSpeed | `13` | Indica la velocità di movimento del ricevitore GPS. |
| GPSTrackRef | `14` | Indica il riferimento per dare la direzione del movimento del ricevitore GPS. 'T' indica la vera direzione e 'M' è direzione magnetica. |
| GPSTrack | `15` | Indica la direzione del movimento del ricevitore GPS. L'intervallo di valori è compreso tra 0,00 e 359,99. |
| GPSImgDirectionRef | `16` | Indica il riferimento per dare la direzione dell'immagine quando viene catturata. 'T' indica la vera direzione e 'M' è direzione magnetica. |
| GPSImgDirection | `17` | Indica la direzione dell'immagine quando è stata catturata. L'intervallo di valori è compreso tra 0,00 e 359,99. |
| GPSMapDatum | `18` | Indica i dati del rilievo geodetico utilizzati dal ricevitore GPS. |
| GPSDestLatitudeRef | `19` | Indica se la latitudine del punto di destinazione è latitudine nord o sud. Il valore ASCII 'N' indica la latitudine nord e 'S' è la latitudine sud. |
| GPSDestLatitude | `20` | Indica la latitudine del punto di destinazione. La latitudine è espressa come tre valori RAZIONALI che forniscono rispettivamente i gradi, minuti e secondi. Se la latitudine è espressa in gradi, minuti e secondi, un tipico formato sarebbe dd/1,mm/1,ss/1. Quando vengono utilizzati gradi e minuti e, ad esempio, le frazioni di minuti sono con un massimo di due cifre decimali, il formato sarebbe gg/1,mmmm/100,0/1. |
| GPSDestLongitudeRef | `21` | Indica se la longitudine del punto di destinazione è la longitudine est o ovest. ASCII 'E' indica la longitudine est, e 'W' è la longitudine ovest. |
| GPSDestLongitude | `22` | Indica la longitudine del punto di destinazione. La longitudine è espressa come tre valori RAZIONALI che forniscono rispettivamente i gradi, minuti e secondi. Se la longitudine è espressa in gradi, minuti e secondi, un tipico formato sarebbe gg/1,mm/1,ss/1. Quando vengono utilizzati gradi e minuti e, ad esempio, le frazioni di minuti sono con un massimo di due cifre decimali, il formato sarebbe gg/1,mmmm/100,0/1. |
| GPSDestBearingRef | `23` | Indica il riferimento utilizzato per dare il rilevamento al punto di destinazione. 'T' indica la vera direzione e 'M' è direzione magnetica. |
| GPSDestBearing | `24` | Indica il rilevamento verso il punto di destinazione. L'intervallo di valori è compreso tra 0,00 e 359,99. |
| GPSDestDistanceRef | `25` | Indica l'unità utilizzata per esprimere la distanza dal punto di destinazione. 'K', 'M' e 'N' rappresentano chilometri, miglia e nodi. |
| GPSDestDistance | `26` | Indica la distanza dal punto di destinazione. |
| GPSProcessingMethod | `27` | Una stringa di caratteri che registra il nome del metodo utilizzato per la ricerca della posizione. Il primo byte indica il codice carattere utilizzato, seguito dal nome del metodo. |
| GPSAreaInformation | `28` | Una stringa di caratteri che registra il nome dell'area GPS. Il primo byte indica il codice carattere utilizzato, seguito dal nome dell'area GPS. |
| GPSDateStamp | `29` | Una stringa di caratteri che registra informazioni su data e ora relative a UTC (Coordinated Universal Time). Il formato è AAAA:MM:GG._x000g_ |
| GPSDifferential | `30` | Indica se la correzione differenziale è applicata al ricevitore GPS. |
| StripOffsets | `273` | Per ogni striscia, l'offset di byte di quella striscia. Si consiglia di selezionarlo in modo che il numero di strip byte non superi i 64 Kbyte. Tag Aux. |
| JPEGInterchangeFormat | `513` | L'offset rispetto al byte iniziale (SOI) dei dati di anteprima compressi JPEG. Non viene utilizzato per i dati JPEG dell'immagine primaria. |
| JPEGInterchangeFormatLength | `514` | Il numero di byte di dati di anteprima compressi JPEG. Non viene utilizzato per i dati JPEG dell'immagine primaria. Le miniature JPEG non vengono divise, ma vengono registrate come flusso di bit JPEG continuo da SOI a EOI. I marcatori Appn e COM non devono essere registrati. Le miniature compresse devono essere registrate in non più di 64 Kbyte, inclusi tutti gli altri dati da registrare in APP1. |
| ExifIfdPointer | `34665` | Un puntatore all'IFD Exif. Interoperabilità, Exif IFD ha la stessa struttura di quella dell'IFD specificato in TIFF. normalmente, tuttavia, non contiene dati di immagine come nel caso di TIFF. |
| GPSIfdPointer | `34853` | Il puntatore gps ifd. |
| RowsPerStrip | `278` | Il numero di righe per striscia. Questo è il numero di righe nell'immagine di una striscia quando un'immagine è divisa in strisce. |
| StripByteCounts | `279` | Il numero totale di byte in ciascuna striscia. |
| PixelXDimension | `40962` | Informazioni specifiche sui dati compressi. Quando viene registrato un file compresso, la larghezza valida dell'immagine significativa deve essere registrata in questo tag, indipendentemente dal fatto che siano presenti o meno dati di riempimento o un marker di riavvio. |
| PixelYDimension | `40963` | Informazioni specifiche sui dati compressi. Quando viene registrato un file compresso, l'altezza valida dell'immagine significativa deve essere registrata in questo tag |
| Gamma | `42240` | Valore gamma |
| SensitivityType | `34864` | Tipo di sensibilità fotografica |
| StandardOutputSensitivity | `34865` | Indica la sensibilità di uscita standard della telecamera |
| RecommendedExposureIndex | `34866` | Indica l'indice di esposizione consigliato |
| ISOSpeed | `34867` | Informazioni sul valore della velocità iso come definito in ISO 12232 |
| ISOSpeedLatitudeYYY | `34868` | Questo tag indica il valore yyy della latitudine della velocità ISO come definito in ISO 12232 |
| ISOSpeedLatitudeZZZ | `34869` | Questo tag indica il valore zzz della latitudine della velocità ISO come definito in ISO 12232 |
| CameraOwnerName | `42032` | Contiene il nome del proprietario della fotocamera |
| BodySerialNumber | `42033` | Contiene il numero di serie del corpo della fotocamera |
| LensMake | `42035` | Questo tag registra il produttore dell'obiettivo |
| LensModel | `42036` | Questo tag registra il nome del modello dell'obiettivo e il numero del modello |
| LensSerialNumber | `42037` | Questo tag registra il numero di serie dell'obiettivo intercambiabile |
| LensSpecification | `42034` | Questo tag rileva la lunghezza focale minima, la lunghezza focale massima, il numero F minimo nella lunghezza focale minima e il numero F minimo nella lunghezza focale massima |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.Exif](../../aspose.imaging.exif)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
