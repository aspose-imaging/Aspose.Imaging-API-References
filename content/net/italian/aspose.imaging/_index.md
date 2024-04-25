---
title: Aspose.Imaging
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lo spazio dei nomi è il nucleo per gli spazi dei nomi nidificati e gli oggetti di base utilizzati per lelaborazione di Aspose.Imaging.
type: docs
weight: 10
url: /it/aspose.imaging/
---
Lo spazio dei nomi è il nucleo per gli spazi dei nomi nidificati e gli oggetti di base utilizzati per l'elaborazione di Aspose.Imaging.

## Classi

| Classe | Descrizione |
| --- | --- |
| [AggregateException](./aggregateexception) | Aggrega più eccezioni. |
| [Blend](./blend) | Definisce un modello di fusione. Questa classe non può essere ereditata. |
| [Brush](./brush) | La classe base del pennello. |
| [BuildVersionInfo](./buildversioninfo) | Contiene le informazioni sulla versione build corrente. |
| [Cache](./cache) | Contiene le impostazioni della cache. |
| [CmykColorHelper](./cmykcolorhelper) | Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno. Fornisce l'API simile a quella[`CmykColor`](../aspose.imaging/cmykcolor) struct. È più leggero perché il colore CMYK è presentato proprio come Int32 anziché come struttura con campi interni. Preferisci utilizzare i metodi statici di questa classe quando possibile invece del deprecato [`CmykColor`](../aspose.imaging/cmykcolor) struttura |
| [ColorBlend](./colorblend) | Definisce le matrici di colori e le posizioni utilizzate per interpolare la fusione dei colori in una sfumatura multicolore. Questa classe non può essere ereditata. |
| [ColorMap](./colormap) | Definisce una mappa per la conversione dei colori. Diversi metodi di[`ImageAttributes`](../aspose.imaging/imageattributes) la classe regola i colori dell'immagine usando una tabella di rimappatura dei colori, che è una matrice di[`ColorMap`](../aspose.imaging/colormap) strutture. Non ereditabile. |
| [ColorMatrix](./colormatrix) | Definisce una matrice 5 x 5 che contiene le coordinate per lo spazio RGBA. Diversi metodi di[`ImageAttributes`](../aspose.imaging/imageattributes) la classe regola i colori dell'immagine utilizzando una matrice di colori. Questa classe non può essere ereditata. |
| [ColorPalette](./colorpalette) | Definisce una matrice di colori che compongono una tavolozza di colori. I colori sono colori ARGB a 32 bit. Non ereditabile. |
| [ColorPaletteHelper](./colorpalettehelper) | Classe di supporto per la manipolazione delle tavolozze dei colori. |
| [ColorTranslator](./colortranslator) | Converte i colori da e verso le strutture GDI+ Color. Questa classe non può essere ereditata. |
| [CompositeException](./compositeexception) | L'eccezione composita |
| [CustomFontSource](./customfontsource) | Funzione del provider di origine del carattere personalizzato |
| [CustomLineCap](./customlinecap) | Incapsula un limite di riga personalizzato definito dall'utente. |
| [DataStreamSupporter](./datastreamsupporter) | Il contenitore del flusso di dati. |
| [DisposableObject](./disposableobject) | Rappresenta l'oggetto usa e getta. |
| [EmbeddedImage](./embeddedimage) | La classe dell'immagine incorporata |
| [Figure](./figure) | La figura. Un contenitore per le forme. |
| [FileStreamContainer](./filestreamcontainer) | Helper per l'elaborazione del flusso di file. |
| [Font](./font) | Definisce un formato particolare per il testo, inclusi il carattere, le dimensioni e gli attributi di stile. Questa classe non può essere ereditata. |
| [FontSettings](./fontsettings) | Impostazioni generali dei caratteri del renderer dei formati vettoriali di imaging. |
| [Graphics](./graphics) | Rappresenta la grafica in base al motore grafico utilizzato nell'assieme corrente. |
| [GraphicsPath](./graphicspath) | Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata. |
| [Image](./image) | L'immagine è la classe base per tutti i tipi di immagini. |
| [ImageAttributes](./imageattributes) | An[`ImageAttributes`](../aspose.imaging/imageattributes) oggetto contiene informazioni su come vengono manipolati i colori bitmap e metafile durante il rendering. Un[`ImageAttributes`](../aspose.imaging/imageattributes)oggetto mantiene diverse impostazioni di regolazione del colore, incluse matrici di regolazione del colore, matrici di regolazione della scala di grigi, valori di correzione gamma, tabelle della mappa dei colori e valori di soglia dei colori. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializzare an[`ImageAttributes`](../aspose.imaging/imageattributes) oggetto e passare il percorso di quello[`ImageAttributes`](../aspose.imaging/imageattributes) oggetto (insieme al percorso di an[`Image`](../aspose.imaging/image) ) al metodo DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry) | Rappresenta il registro dei creatori di immagini. |
| [ImageExportersRegistry](./imageexportersregistry) | Rappresenta il registro degli esportatori di immagini. |
| [ImageLoadersRegistry](./imageloadersregistry) | Rappresenta il registro dei caricatori di immagini. |
| [ImageOptionsBase](./imageoptionsbase) | Le opzioni di base dell'immagine. |
| [ImageResizeSettings](./imageresizesettings) | Impostazioni di ridimensionamento dell'immagine class |
| [IntRange](./intrange) | Classe per rappresentare la sequenza di elementi |
| [License](./license) | Fornisce i metodi per concedere in licenza il componente. |
| [LoadOptions](./loadoptions) | Rappresenta le opzioni di caricamento. |
| [Matrix](./matrix) | Sostituisce la matrice GDI+. |
| [Metered](./metered) | Fornisce i metodi per impostare la chiave misurata. |
| [NonGenericDictionary](./nongenericdictionary) | Rappresenta un dizionario non generico. |
| [NonGenericList](./nongenericlist) | Elenco non generico di oggetti |
| [ObjectWithBounds](./objectwithbounds) | L'oggetto con limiti. |
| [OpenTypeFontsCache](./opentypefontscache) | Cache per i font OpenType installati nel sistema. |
| [PageExportingAction](./pageexportingaction) | Delegato per l'attivazione prima dell'esportazione della pagina |
| [Pen](./pen) | Definisce un oggetto utilizzato per disegnare linee, curve e figure. |
| [PixelDataFormat](./pixeldataformat) | Il formato dei dati dei pixel. Questo è un oggetto immutabile. |
| [ProgressEventHandler](./progresseventhandler) | Riferimento alla funzione del gestore eventi di avanzamento |
| [RasterCachedImage](./rastercachedimage) | Rappresenta un'immagine raster che supporta operazioni grafiche raster. Questa immagine memorizza nella cache i dati dei pixel quando richiesto. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage) | L'immagine multipagina raster |
| [RasterImage](./rasterimage) | Rappresenta un'immagine raster che supporta operazioni di grafica raster. |
| [RawDataSettings](./rawdatasettings) | Le impostazioni dei dati grezzi |
| [Region](./region) | Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata. |
| [ResolutionSetting](./resolutionsetting) | L'impostazione della risoluzione per le opzioni di salvataggio dell'immagine. |
| [Shape](./shape) | La forma. Un insieme continuo di punti collegati utilizzando una regola specifica. |
| [ShapeSegment](./shapesegment) | Rappresenta un segmento di forma. Un segmento è una linea o una curva che collega due punti. |
| [Source](./source) | L'origine viene utilizzata per contenere tutte le informazioni rilevanti per un oggetto pipe. |
| [SplitStreamContainer](./splitstreamcontainer) | Rappresenta il contenitore del flusso diviso che contiene il flusso e fornisce le routine di elaborazione del flusso. |
| [StreamContainer](./streamcontainer) | Rappresenta il contenitore del flusso che contiene il flusso e fornisce le routine di elaborazione del flusso. |
| [StringFormat](./stringformat) | Incapsula le informazioni sul layout del testo (come allineamento, orientamento e tabulazioni), le manipolazioni di visualizzazione (come l'inserimento di puntini di sospensione e la sostituzione di cifre nazionali) e le funzioni OpenType. Questa classe non può essere ereditata. |
| [TransparencySupporter](./transparencysupporter) | L'oggetto che supporta la trasparenza. |
| [VectorImage](./vectorimage) | L'immagine vettoriale è la classe base per tutti i tipi di immagini vettoriali. |
| [VectorMultipageImage](./vectormultipageimage) | L'immagine multipagina Vector |
## Interfacce

| Interfaccia | Descrizione |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | Il processore buffer avanzato. |
| [IAnimationFrame](./ianimationframe) | Il riquadro dell'animazione |
| [IBufferProcessor](./ibufferprocessor) | Il processore buffer. |
| [IColorConverter](./icolorconverter) | Il convertitore di colori. |
| [IColorPalette](./icolorpalette) | L'interfaccia della tavolozza dei colori. |
| [IImageCreator](./iimagecreator) | Il creatore di immagini. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor) | Il descrittore del creatore dell'immagine che specifica le proprietà del creatore. Il descrittore del creatore viene utilizzato per superare la necessità di contenere ogni istanza del creatore di immagini in memoria e problemi di multithreading. |
| [IImageDescriptor](./iimagedescriptor) | Il descrittore dell'immagine. Contiene proprietà e metodi di base per tutti gli altri tipi di descrittori di immagini. |
| [IImageExporter](./iimageexporter) | L'esportatore di immagini. Può esportare dati dal formato Aspose.Imaging interno in un formato dati specificato. |
| [IImageExporterDescriptor](./iimageexporterdescriptor) | Rappresenta il descrittore di esportazione dell'immagine. Il descrittore di esportazione viene utilizzato per superare la necessità di contenere ogni istanza di esportazione in memoria e problemi di multithreading. |
| [IImageLoader](./iimageloader) | Il caricatore di immagini. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor) | Il descrittore del caricatore di immagini che specifica le proprietà del caricatore. Il descrittore del caricatore viene utilizzato per superare la necessità di contenere ogni istanza del caricatore di immagini in memoria e problemi di multithreading. |
| [IIndexedColorConverter](./iindexedcolorconverter) | Il convertitore di colori per i formati immagine indicizzati. |
| [IKeyedObject](./ikeyedobject) | Rappresenta l'interfaccia per oggetti con chiavi. |
| [IMultipageImage](./imultipageimage) | L'interfaccia immagine multipagina |
| [IMultipageImageExt](./imultipageimageext) | L'interfaccia immagine multipagina estesa |
| [IObjectWithBounds](./iobjectwithbounds) | Rappresenta un oggetto con limiti. |
| [IOrderedShape](./iorderedshape) | Rappresenta una forma ordinata. Una forma ordinata è un insieme continuo di punti avente un punto iniziale e un punto finale. L'insieme continuo di punti collegati mediante una regola specifica. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Conforme ai pixel ARGB a 32 bit caricati parzialmente. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | Il caricatore di pixel ARGB a 64 bit. |
| [IPartialPixelLoader](./ipartialpixelloader) | Conforme ai pixel caricati parzialmente. |
| [IPartialRawDataLoader](./ipartialrawdataloader) | Il caricatore di dati parziale. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | Il caricatore di pixel ARGB a 32 bit dell'immagine raster. |
| [IRasterImagePixelLoader](./irasterimagepixelloader) | Il caricatore di pixel dell'immagine raster. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader) | Il caricatore di dati grezzi dell'immagine raster. |
## Enumerazione

| Enumerazione | Descrizione |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods) | Indica il modo in cui deve essere trattato il grafico dopo essere stato visualizzato. |
| [CacheType](./cachetype) | Specifica il tipo di cache da utilizzare. |
| [CharacterSet](./characterset) | Rappresenta il set di caratteri utilizzato. |
| [ColorAdjustType](./coloradjusttype) | Specifica quali oggetti utilizzano le informazioni sulla regolazione del colore. |
| [ColorChannelFlag](./colorchannelflag) | Specifica i singoli canali nello spazio colore CMYK (ciano, magenta, giallo, nero). Questa enumerazione viene utilizzata dai metodi SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod) | Metodo di confronto dei colori per adattarsi al vicino più vicino |
| [ColorMatrixFlag](./colormatrixflag) | Specifica i tipi di immagini e colori che saranno interessati dalle impostazioni di regolazione del colore e della scala di grigi di un[`ImageAttributes`](../aspose.imaging/imageattributes) . |
| [ColorQuantizationMethod](./colorquantizationmethod) | Metodi di quantizzazione dei colori |
| [CompositingQuality](./compositingquality) | Specifica il livello di qualità da utilizzare durante la composizione. |
| [DashCap](./dashcap) | Specifica il tipo di forma grafica da utilizzare su entrambe le estremità di ciascun trattino in una linea tratteggiata. |
| [DashStyle](./dashstyle) | Specifica lo stile delle linee tratteggiate disegnate con a[`Pen`](../aspose.imaging/pen) oggetto. |
| [DataRecoveryMode](./datarecoverymode) | La modalità di recupero dati. |
| [DitheringMethod](./ditheringmethod) | Metodo di dithering. |
| [DitheringMethods](./ditheringmethods) | I metodi di dithering utilizzati per controllare la conversione del colore. |
| [FileFormat](./fileformat) | Uno dei formati di file di imaging supportati. |
| [FillMode](./fillmode) | Specifica come viene riempito l'interno di un percorso chiuso. |
| [FontStyle](./fontstyle) | Specifica le informazioni sullo stile applicate al testo. |
| [GraphicsUnit](./graphicsunit) | Specifica l'unità di misura per i dati forniti. |
| [HatchStyle](./hatchstyle) | Specifica i diversi modelli disponibili per[`HatchBrush`](../aspose.imaging.brushes/hatchbrush) oggetti. |
| [HotkeyPrefix](./hotkeyprefix) | Specifica il tipo di visualizzazione per i prefissi dei tasti di scelta rapida relativi al testo. |
| [ImageFilterType](./imagefiltertype) | Filtri immagine da utilizzare |
| [InterpolationMode](./interpolationmode) | Il[`InterpolationMode`](../aspose.imaging/interpolationmode) enumeration specifica l'algoritmo utilizzato quando le immagini vengono ridimensionate o ruotate. |
| [KnownColor](./knowncolor) | Specifica i colori di sistema noti. |
| [LineCap](./linecap) | Specifica gli stili di cappuccio disponibili con cui a[`Pen`](../aspose.imaging/pen) l'oggetto può terminare una riga. |
| [LineJoin](./linejoin) | Specifica come unire segmenti di linea o curva consecutivi in una figura (sottotraccia) contenuta in un[`GraphicsPath`](../aspose.imaging/graphicspath) oggetto. |
| [MatrixOrder](./matrixorder) | Specifica l'ordine per le operazioni di trasformazione della matrice. |
| [PaletteMiningMethod](./paletteminingmethod) | Il metodo di mining della tavolozza delle immagini |
| [PdfComplianceVersion](./pdfcomplianceversion) | Specifica il livello di conformità PDF al file di output. |
| [PenAlignment](./penalignment) | Specifica l'allineamento di a[`Pen`](../aspose.imaging/pen)oggetto rispetto alla linea teorica a larghezza zero. |
| [PenType](./pentype) | Specifica il tipo di riempimento a[`Pen`](../aspose.imaging/pen) l'oggetto usa per riempire le linee. |
| [PixelFormat](./pixelformat) | Il significato effettivo del formato dati pixel. |
| [ResizeType](./resizetype) | Specifica il tipo di ridimensionamento. |
| [ResolutionUnit](./resolutionunit) | Unità di risoluzione enum. |
| [RotateFlipType](./rotatefliptype) | Specifica di quanto viene ruotata un'immagine e l'asse utilizzato per capovolgere l'immagine. |
| [SeekOrigin](./seekorigin) | Fornisce i campi che rappresentano i punti di riferimento in[`StreamContainer`](../aspose.imaging/streamcontainer) per la ricerca. |
| [SmoothingMode](./smoothingmode) | Specifica se l'arrotondamento (antialias) viene applicato a linee e curve e ai bordi delle aree riempite. |
| [StringAlignment](./stringalignment) | Specifica l'allineamento di una stringa di testo rispetto al relativo rettangolo di layout. |
| [StringDigitSubstitute](./stringdigitsubstitute) | L'enumerazione specifica come sostituire le cifre in una stringa in base alla locale o alla lingua dell'utente. |
| [StringFormatFlags](./stringformatflags) | Specifica le informazioni di visualizzazione e layout per le stringhe di testo. |
| [StringTrimming](./stringtrimming) | Specifica come tagliare i caratteri da una stringa che non rientra completamente in una forma di layout. |
| [TextRenderingHint](./textrenderinghint) | Specifica la qualità del rendering del testo. |
| [WarpMode](./warpmode) | Specifica il tipo di trasformazione warp applicata. |
| [WrapMode](./wrapmode) | Specifica come una trama o una sfumatura viene affiancata quando è più piccola dell'area da riempire. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
