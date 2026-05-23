---
title: "Enumerazione ExifProperties"
type: docs
weight: 190
url: /it/python-net/aspose.imaging.exif/exifproperties/
---

Elenco dei tag Exif

**Module:** [aspose.imaging.exif](/imaging/python-net/aspose.imaging.exif/)

**Full Name:** aspose.imaging.exif.ExifProperties

## **Members**
| **Member name** | **Descrizione** |
| :- | :- |
| APERTURE_VALUE | Il valore dell'apertura dell'obiettivo. |
| ARTIST | Questo tag registra il nome del proprietario della fotocamera, del fotografo o del creatore dell'immagine. Il formato dettagliato non è specificato, ma si consiglia di scrivere le informazioni come nell'esempio seguente per facilitare l'interoperabilità. Quando il campo è lasciato vuoto, viene trattato come sconosciuto. Ex.) "Camera owner, John Smith; Photographer, Michael Brown; Image creator, Ken James" |
| BITS_PER_SAMPLE | Il numero di bit per componente dell'immagine. In questo standard ogni componente dell'immagine è di 8 bit, quindi il valore per questo tag è 8. |
| BODY_SERIAL_NUMBER | Contiene il numero di serie del corpo della fotocamera |
| BRIGHTNESS_VALUE | Il valore di luminosità. |
| CAMERA_OWNER_NAME | Contiene il nome del proprietario della fotocamera |
| CFA_PATTERN | Indica il modello geometrico della matrice di filtro colore (CFA) del sensore d'immagine quando viene utilizzato un sensore a zona colore a chip unico. Non si applica a tutti i metodi di rilevamento. |
| COLOR_SPACE | Il tag di informazione dello spazio colore (ColorSpace) è sempre registrato come specificatore dello spazio colore. |
| COMPONENTS_CONFIGURATION | La configurazione dei componenti. |
| COMPRESSED_BITS_PER_PIXEL | Specifico per dati compressi; indica i bit compressi per pixel. |
| COMPRESSIONE | Lo schema di compressione utilizzato per i dati dell'immagine. Quando un'immagine primaria è compressa in JPEG, questa designazione non è necessaria e viene omessa. |
| CONTRASTO | Questo tag indica la direzione dell'elaborazione del contrasto applicata dalla fotocamera al momento dello scatto. |
| DIRITTO D'AUTORE | Informazioni sul diritto d'autore. In questo standard il tag è usato per<br/>                indicare sia i diritti d'autore del fotografo che dell'editor. È<br/>                l'avviso di diritto d'autore della persona o dell'organizzazione che rivendica<br/>                i diritti sull'immagine. La dichiarazione di diritto d'autore di interoperabilità<br/>                che include data e diritti dovrebbe essere scritta in questo<br/>                campo; ad esempio, "Copyright, John Smith, 19xx. Tutti i diritti<br/>                riservati.". In questo standard il campo registra sia i diritti d'autore del<br/>                fotografo che dell'editor, con ciascuno registrato in una<br/>                parte separata della dichiarazione. Quando c'è una chiara distinzione<br/>                tra i diritti d'autore del fotografo e dell'editor, questi devono essere<br/>                scritti nell'ordine fotografo seguito dal diritto d'autore dell'editor,<br/>                separati da NULL (in questo caso, poiché la dichiarazione termina anche con<br/>                un NULL, ci sono due codici NULL). Quando è fornito solo il diritto d'autore del fotografo,<br/>                viene terminato da un codice NULL. Quando è fornito solo il diritto d'autore dell'editor, la parte del diritto d'autore del fotografo<br/>                consiste in uno spazio seguito da un codice NULL terminante, poi<br/>                viene fornito il diritto d'autore dell'editor. Quando il campo è lasciato vuoto, viene<br/>                considerato sconosciuto. |
| RENDERIZZATO_PERSONALIZZATO | Questo tag indica l'uso di elaborazioni speciali sui dati dell'immagine, come il rendering orientato all'output. Quando viene eseguita un'elaborazione speciale, ci si aspetta che il lettore disabiliti o minimizzi ulteriori elaborazioni. |
| DATA_ORA | La data e l'ora di creazione dell'immagine. Nello standard Exif, è la data e l'ora in cui il file è stato modificato. |
| DATA_ORA_DIGITATA | La data e l'ora della digitalizzazione. |
| DATA_ORA_ORIGINALE | La data e l'ora in cui sono stati generati i dati originali dell'immagine. |
| DESCRIZIONE_IMPOSTAZIONI_DISPOSITIVO | Questo tag indica informazioni sulle condizioni di scatto di un modello di fotocamera specifico. Il tag è usato solo per indicare le condizioni di scatto nel lettore. |
| RAPPORTO_ZOOM_DIGITALE | Questo tag indica il rapporto di zoom digitale al momento dello scatto. Se il numeratore del valore registrato è 0, ciò indica che lo zoom digitale non è stato utilizzato. |
| PUNTATORE_EXIF_IFD | Un puntatore all'Exif IFD. L'interoperabilità, l'Exif IFD ha la stessa struttura dell'IFD specificato in TIFF. Tuttavia, normalmente non contiene dati immagine come nel caso di TIFF. |
| VERSIONE_EXIF | La versione Exif. |
| VALORE_BIAS_ESPOSIZIONE | Il valore del bias di esposizione. |
| INDICE_ESPOSIZIONE | Indica l'indice di esposizione selezionato sulla fotocamera o sul dispositivo di input al momento della cattura dell'immagine. |
| EXPOSURE_MODE | Questo tag indica la modalità di esposizione impostata quando l'immagine è stata scattata. In modalità auto-bracketing, la fotocamera scatta una serie di fotogrammi della stessa scena con impostazioni di esposizione diverse. |
| EXPOSURE_PROGRAM | La classe del programma utilizzato dalla fotocamera per impostare l'esposizione al momento dello scatto. |
| EXPOSURE_TIME | Tempo di esposizione, espresso in secondi. |
| FILE_SOURCE | La sorgente del file. |
| FLASH | Indica lo stato del flash quando l'immagine è stata scattata. |
| FLASHPIX_VERSION | La versione del formato Flashpix supportata da un file FPXR. |
| FLASH_ENERGY | Indica l'energia dello strobo al momento della cattura dell'immagine, misurata in Beam Candle Power Seconds (BCPS). |
| FOCAL_LENGTH | La lunghezza focale reale dell'obiettivo, in mm. |
| FOCAL_LENGTH_IN_35_MM_FILM | Questo tag indica la lunghezza focale equivalente assumendo una fotocamera a pellicola da 35 mm, in mm. Un valore di 0 indica che la lunghezza focale è sconosciuta. Nota che questo tag differisce dal tag FocalLength. |
| FOCAL_PLANE_RESOLUTION_UNIT | Indica l'unità di misura per FocalPlaneXResolution e FocalPlaneYResolution. Questo valore è lo stesso di ResolutionUnit. |
| FOCAL_PLANE_X_RESOLUTION | Indica il numero di pixel nella direzione della larghezza dell'immagine (X) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| FOCAL_PLANE_Y_RESOLUTION | Indica il numero di pixel nella direzione dell'altezza dell'immagine (Y) per FocalPlaneResolutionUnit sul piano focale della fotocamera. |
| F_NUMBER | Il F number. |
| GAIN_CONTROL | Questo tag indica il grado di regolazione complessiva del guadagno dell'immagine. |
| GAMMA | Valore Gamma |
| GPSDOP | Indica il GPS DOP (grado di precisione dei dati). Un valore HDOP viene scritto durante la misurazione bidimensionale,<br/>                e PDOP durante la misurazione tridimensionale. |
| GPS_ALTITUDE | Indica l'altitudine basata sul riferimento in GPSAltitudeRef. L'altitudine è espressa come un valore RATIONAL.<br/>                L'unità di riferimento è metri. |
| GPS_ALTITUDE_REF | Indica l'altitudine usata come altitudine di riferimento. Se il riferimento è il livello del mare e l'altitudine è sopra il livello del mare,<br/>                viene fornito 0. Se l'altitudine è sotto il livello del mare, viene fornito un valore di 1 e l'altitudine è indicata come valore assoluto nel<br/>                tag GPSAltitude. |
| GPS_AREA_INFORMATION | Una stringa di caratteri che registra il nome dell'area GPS. Il primo byte indica<br/>                il codice dei caratteri usato, e segue il nome dell'area GPS. |
| GPS_DATE_STAMP | Una stringa di caratteri che registra le informazioni di data e ora relative a UTC<br/>                (Tempo Universale Coordinato). Il formato è YYYY:MM:DD. |
| GPS_DEST_BEARING | Indica la direzione verso il punto di destinazione. L'intervallo di valori è da 0.00 a 359.99. |
| GPS_DEST_BEARING_REF | Indica il riferimento usato per fornire la direzione verso il punto di destinazione. 'T' indica la direzione vera e 'M' è<br/>                la direzione magnetica. |
| GPS_DEST_DISTANCE | Indica la distanza dal punto di destinazione. |
| GPS_DEST_DISTANCE_REF | Indica l'unità usata per esprimere la distanza dal punto di destinazione. 'K', 'M' e 'N' rappresentano chilometri, miglia<br/>                e nodi. |
| GPS_DEST_LATITUDE | Indica la latitudine del punto di destinazione. La latitudine è espressa come tre valori RATIONAL che forniscono i<br/>                gradi, i minuti e i secondi, rispettivamente. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico<br/>                sarebbe dd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono<br/>                fornite fino a due cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1. |
| GPS_DEST_LATITUDE_REF | Indica se la latitudine del punto di destinazione è latitudine nord o sud. Il valore ASCII 'N' indica la latitudine nord<br/>                e 'S' indica la latitudine sud. |
| GPS_DEST_LONGITUDE | Indica la longitudine del punto di destinazione. La longitudine è espressa come tre valori RATIONAL che forniscono i<br/>                gradi, i minuti e i secondi, rispettivamente. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico<br/>                sarebbe ddd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono<br/>                fornite fino a due cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1. |
| GPS_DEST_LONGITUDE_REF | Indica se la longitudine del punto di destinazione è longitudine est o ovest. ASCII 'E' indica la longitudine est,<br/>                e 'W' indica la longitudine ovest. |
| GPS_DIFFERENTIAL | Indica se è applicata una correzione differenziale al ricevitore GPS. |
| GPS_IFD_POINTER | Il puntatore gps ifd. |
| GPS_IMG_DIRECTION | Indica la direzione dell'immagine al momento della cattura. L'intervallo di valori è da 0,00 a 359,99. |
| GPS_IMG_DIRECTION_REF | Indica il riferimento per fornire la direzione dell'immagine al momento della cattura. 'T' indica la direzione vera e 'M' è<br/>                la direzione magnetica. |
| GPS_LATITUDE | Indica la latitudine. La latitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e<br/>                i secondi, rispettivamente. Se la latitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe<br/>                dd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due<br/>                cifre decimali, il formato sarebbe dd/1,mmmm/100,0/1. |
| GPS_LATITUDE_REF | Indica se la latitudine è nord o sud. |
| GPS_LONGITUDE | Indica la longitudine. La longitudine è espressa come tre valori RATIONAL che forniscono i gradi, i minuti e<br/>                i secondi, rispettivamente. Se la longitudine è espressa in gradi, minuti e secondi, un formato tipico sarebbe<br/>                ddd/1,mm/1,ss/1. Quando si usano gradi e minuti e, ad esempio, le frazioni di minuti sono fornite fino a due<br/>                cifre decimali, il formato sarebbe ddd/1,mmmm/100,0/1. |
| GPS_LONGITUDE_REF | Indica se la longitudine è est o ovest. |
| GPS_MAP_DATUM | Indica i dati di rilevamento geodetico utilizzati dal ricevitore GPS. |
| GPS_MEASURE_MODE | Indica la modalità di misurazione GPS. - 2- o 3- dimensionale. |
| GPS_PROCESSING_METHOD | Una stringa di caratteri che registra il nome del metodo utilizzato per la ricerca della posizione.<br/>                Il primo byte indica il codice dei caratteri utilizzato, e segue il nome<br/>                del metodo. |
| GPS_SATELLITES | Indica i satelliti GPS utilizzati per le misurazioni. Questo tag può essere usato per descrivere il numero di satelliti,<br/>                il loro numero ID, l'angolo di elevazione, l'azimut, il SNR e altre informazioni in notazione ASCII. Il formato non è<br/>                specificato. Se il ricevitore GPS non è in grado di effettuare misurazioni, il valore del tag deve essere impostato a NULL. |
| GPS_SPEED | Indica la velocità del movimento del ricevitore GPS. |
| GPS_SPEED_REF | Indica l'unità utilizzata per esprimere la velocità di movimento del ricevitore GPS. 'K', 'M' e 'N' rappresentano chilometri per<br/>                ora, miglia per ora e nodi. |
| GPS_STATUS | Indica lo stato del ricevitore GPS al momento della registrazione dell'immagine. |
| GPS_TIMESTAMP | Indica il tempo in UTC (Coordinated Universal Time). Il timestamp è espresso come tre valori RATIONAL<br/>                che indicano l'ora, il minuto e il secondo. |
| GPS_TRACK | Indica la direzione del movimento del ricevitore GPS. L'intervallo di valori è da 0,00 a 359,99. |
| GPS_TRACK_REF | Indica il riferimento per fornire la direzione del movimento del ricevitore GPS. 'T' indica la direzione vera e 'M' è<br/>                la direzione magnetica. |
| GPS_VERSION_ID | Indica la versione di GPSInfoIFD. |
| IMAGE_DESCRIPTION | Una stringa di caratteri che fornisce il titolo dell'immagine. Può essere un commento come "picnic aziendale 1988" o simili. |
| IMAGE_LENGTH | Il numero di righe dei dati dell'immagine. |
| IMAGE_UNIQUE_ID | L'ID univoco dell'immagine. |
| IMAGE_WIDTH | Il numero di colonne dei dati dell'immagine, pari al numero di pixel per riga. |
| ISO_SPEED | Informazioni sul valore della velocità ISO come definito nella ISO 12232. |
| ISO_SPEED_LATITUDE_YYY | Questo tag indica il valore della latitudine della velocità ISO yyy come definito nella ISO 12232. |
| ISO_SPEED_LATITUDE_ZZZ | Questo tag indica il valore della latitudine della velocità ISO zzz come definito nella ISO 12232. |
| JPEG_INTERCHANGE_FORMAT | L'offset al byte iniziale (SOI) dei dati della miniatura JPEG compressa. Non è utilizzato per i dati JPEG dell'immagine principale. |
| JPEG_INTERCHANGE_FORMAT_LENGTH | Il numero di byte dei dati della miniatura JPEG compressa. Non è utilizzato per i dati JPEG dell'immagine principale. Le miniature JPEG non sono suddivise ma sono registrate come un flusso continuo di JPEG dal SOI all'EOI. I marcatori Appn e COM non devono essere registrati. Le miniature compresse devono essere registrate in non più di 64 Kbyte, includendo tutti gli altri dati da registrare in APP1. |
| LENS_MAKE | Questo tag registra il produttore dell'obiettivo. |
| LENS_MODEL | Questo tag registra il nome modello e il numero modello dell'obiettivo. |
| LENS_SERIAL_NUMBER | Questo tag registra il numero di serie dell'obiettivo intercambiabile. |
| LENS_SPECIFICATION | Questo tag indica la lunghezza focale minima, la lunghezza focale massima, il numero F minimo alla lunghezza focale minima e il numero F minimo alla lunghezza focale massima. |
| LIGHT_SOURCE | Il tipo di sorgente luminosa. |
| MAKE | Il produttore dell'apparecchiatura di registrazione. È il produttore del DSC, scanner, digitalizzatore video o altro apparecchio che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto. |
| MAKER_NOTE | Un tag per i produttori di scrittori Exif per registrare qualsiasi informazione desiderata. Il contenuto è a discrezione del produttore, ma questo tag non dovrebbe essere usato per altro rispetto al suo scopo previsto. |
| MAX_APERTURE_VALUE | Il valore dell'apertura massima. |
| METERING_MODE | La modalità di misurazione. |
| MODEL | Il nome modello o il numero modello dell'apparecchiatura. Questo è il nome modello o il numero del DSC, scanner, digitalizzatore video o altra apparecchiatura che ha generato l'immagine. Quando il campo è lasciato vuoto, viene considerato sconosciuto. |
| OECF | Indica la Funzione di Conversione Opto-Elettrica (OECF) specificata nella ISO 14524. |
| ORIENTATION | L'orientamento dell'immagine visualizzato in termini di righe e colonne. |
| PHOTOGRAPHIC_SENSITIVITY | Indica la Velocità ISO e la Latitudine ISO della fotocamera o del dispositivo di ingresso come specificato nella ISO 12232. |
| PHOTOMETRIC_INTERPRETATION | La composizione dei pixel. |
| PIXEL_X_DIMENSION | Informazioni specifiche per i dati compressi. Quando viene registrato un file compresso, la larghezza valida dell'immagine significativa deve essere registrata in questo tag, sia che vi siano dati di riempimento o un marcatore di riavvio. |
| PIXEL_Y_DIMENSION | Informazioni specifiche per i dati compressi. Quando viene registrato un file compresso, l'altezza valida dell'immagine significativa deve essere registrata in questo tag. |
| PLANAR_CONFIGURATION | Indica se i componenti dei pixel sono registrati in formato chunk (a blocchi) o planar (planare). Se questo campo non esiste, si assume il valore predefinito TIFF di 1 (chunky). |
| PRIMARY_CHROMATICITIES | La cromaticità dei tre colori primari dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag di informazione sullo spazio colore ColorSpace. |
| RECOMMENDED_EXPOSURE_INDEX | Indica l'indice di esposizione consigliato |
| REFERENCE_BLACK_WHITE | Il valore del punto nero di riferimento e del punto bianco di riferimento<br/>                valore. Nessun valore predefinito è fornito in TIFF, ma i valori seguenti sono forniti come predefiniti qui.<br/>                Lo spazio colore è dichiarato<br/>                in un tag di informazioni sullo spazio colore, con il valore predefinito<br/>                che fornisce le caratteristiche ottimali dell'immagine<br/>                Interoperabilità di queste condizioni |
| RELATED_SOUND_FILE | Il file audio correlato. |
| RESOLUTION_UNIT | L'unità per misurare XResolution e YResolution. La stessa unità è usata per entrambi XResolution e YResolution. Se la risoluzione dell'immagine è sconosciuta, viene designata 2 (pollici). |
| ROWS_PER_STRIP | Il numero di righe per striscia. Questo è il numero di righe nell'immagine di una striscia quando un'immagine è divisa in strisce. |
| SAMPLES_PER_PIXEL | Il numero di componenti per pixel. Poiché questo standard si applica alle immagini RGB e YCbCr, il valore impostato per questo tag è 3. |
| SATURATION | Questo tag indica la direzione dell'elaborazione della saturazione applicata dalla fotocamera quando l'immagine è stata scattata. |
| SCENE_CAPTURE_TYPE | Questo tag indica il tipo di scena che è stata fotografata. Può anche essere usato per registrare la modalità in cui l'immagine è stata scattata. |
| SCENE_TYPE | Indica il tipo di scena. Se un DSC ha registrato l'immagine, il valore di questo tag deve sempre essere impostato a 1, indicando che l'immagine è stata fotografata direttamente. |
| SENSING_METHOD | Indica il tipo di sensore d'immagine sulla fotocamera o sul dispositivo di input. |
| SENSITIVITY_TYPE | Tipo di sensibilità fotografica |
| SHARPNESS | Questo tag indica la direzione dell'elaborazione della nitidezza applicata dalla fotocamera quando l'immagine è stata scattata |
| SHUTTER_SPEED_VALUE | Il valore della velocità dell'otturatore. |
| SOFTWARE | Questo tag registra il nome e la versione del software o del firmware della fotocamera o del dispositivo di acquisizione immagini utilizzato per generare l'immagine. Il formato dettagliato non è specificato, ma si consiglia di seguire l'esempio mostrato di seguito. Quando il campo è lasciato vuoto, viene considerato sconosciuto. |
| SPATIAL_FREQUENCY_RESPONSE | Questo tag registra la tabella di frequenza spaziale della fotocamera o del dispositivo di acquisizione e i valori SFR nella direzione della larghezza dell'immagine, dell'altezza dell'immagine e della direzione diagonale, come specificato nella ISO 12233. |
| SPECTRAL_SENSITIVITY | Indica la sensibilità spettrale di ciascun canale della fotocamera utilizzata. |
| STANDARD_OUTPUT_SENSITIVITY | Indica la sensibilità di uscita standard della fotocamera |
| STRIP_BYTE_COUNTS | Il numero totale di byte in ciascuna striscia. |
| STRIP_OFFSETS | Per ogni striscia, l'offset in byte di quella striscia. Si consiglia di selezionare questo in modo che il numero di byte per striscia non superi i 64 Kbyte.<br/>                Tag ausiliario. |
| SUBJECT_AREA | Questo tag indica la posizione e l'area del soggetto principale nella scena complessiva. |
| SUBJECT_DISTANCE | La distanza dal soggetto, espressa in metri. |
| SUBJECT_DISTANCE_RANGE | Questo tag indica la distanza dal soggetto. |
| SUBJECT_LOCATION | Indica la posizione del soggetto principale nella scena. Il valore di questo tag rappresenta il pixel al centro del soggetto principale rispetto al bordo sinistro, prima dell'elaborazione di rotazione secondo il tag Rotation. |
| SUBSEC_TIME | Un tag usato per registrare le frazioni di secondo per il tag DateTime. |
| SUBSEC_TIME_DIGITIZED | Un tag usato per registrare le frazioni di secondo per il tag DateTimeDigitized. |
| SUBSEC_TIME_ORIGINAL | Un tag usato per registrare frazioni di secondo per il tag DateTimeOriginal. |
| TRANSFER_FUNCTION | Una funzione di trasferimento per l'immagine, descritta in stile tabellare. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag ColorSpace delle informazioni sullo spazio colore. |
| USER_COMMENT | Un tag per gli utenti Exif per scrivere parole chiave o commenti sull'immagine oltre a quelli presenti in ImageDescription, e senza le limitazioni di codifica dei caratteri del tag ImageDescription. |
| WHITE_BALANCE | Questo tag indica la modalità di bilanciamento del bianco impostata al momento dello scatto dell'immagine. |
| WHITE_POINT | La cromaticità del punto bianco dell'immagine. Normalmente questo tag non è necessario, poiché lo spazio colore è specificato nel tag ColorSpace delle informazioni sullo spazio colore. |
| X_RESOLUTION | Il numero di pixel per ResolutionUnit nella direzione ImageWidth. Quando la risoluzione dell'immagine è sconosciuta, viene designato 72 [dpi]. |
| Y_CB_CR_COEFFICIENTS | I coefficienti della matrice per la trasformazione da dati immagine RGB a YCbCr. |
| Y_CB_CR_POSITIONING | La posizione dei componenti di crominanza in relazione al<br/>                componente di luminanza. Questo campo è designato solo per<br/>                dati compressi JPEG o dati YCbCr non compressi. Il valore predefinito TIFF<br/>                è 1 (centrato); ma quando Y:Cb:Cr = 4:2:2 è<br/>                consigliato in questo standard che 2 (co-sited) sia usato per<br/>                registrare i dati, al fine di migliorare la qualità dell'immagine quando visualizzata<br/>                su sistemi TV. Quando questo campo non esiste, il lettore dovrà<br/>                assumere il valore predefinito TIFF. Nel caso di Y:Cb:Cr = 4:2:0, il<br/>                valore predefinito TIFF (centrato) è consigliato. Se il lettore<br/>                non ha la capacità di supportare entrambi i tipi di<br/>                YCbCrPositioning, dovrà seguire il valore predefinito TIFF indipendentemente<br/>                dal valore in questo campo. È preferibile che i lettori "<br/>                siano in grado di supportare sia il posizionamento centrato che quello co-sited. |
| Y_CB_CR_SUB_SAMPLING | Il rapporto di campionamento dei componenti di crominanza in relazione al componente di luminanza. |
| Y_RESOLUTION | Il numero di pixel per ResolutionUnit nella direzione ImageLength. Viene designato lo stesso valore di XResolution. |
