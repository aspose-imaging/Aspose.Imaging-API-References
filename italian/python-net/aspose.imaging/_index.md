---
title: "aspose.imaging"
type: docs
weight: 10
url: /it/python-net/aspose.imaging/
---


Il modulo è il nucleo per i moduli nidificati e gli oggetti più basilari utilizzati per l'elaborazione di Aspose.Imaging.

## **Classes**
| **Class** | **Descrizione** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Definisce un modello di fusione. Questa classe non può essere ereditata. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | La classe base del pennello. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Contiene le informazioni sulla versione corrente della build. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Contiene le impostazioni della cache. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | Il colore CMYK del pixel. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Metodi di supporto per lavorare con il colore CMYK presentato come valore intero a 32 bit con segno.<br/>            Fornisce un'API simile a quella della struttura [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/).<br/>            È più leggera perché il colore CMYK è presentato semplicemente come Int32 anziché come struttura con campi interni.<br/>            Si prega di preferire l'uso dei metodi statici di questa classe quando possibile invece della struttura deprecata<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del pixel. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Definisce array di colori e posizioni utilizzati per l'interpolazione della fusione dei colori in un gradiente multicolore. Questa classe non può essere ereditata. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Definisce una mappa per la conversione dei colori. Diversi metodi della classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) regolano i colori dell'immagine utilizzando una tabella di rimappatura dei colori, che è un array di strutture [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Non ereditabile. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Definisce una matrice 5 x 5 che contiene le coordinate per lo spazio RGBA. Diversi metodi della classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) regolano i colori dell'immagine utilizzando una matrice dei colori. Questa classe non può essere ereditata. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Definisce un array di colori che costituiscono una tavolozza di colori. I colori sono ARGB a 32 bit. Non ereditabile. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Classe di supporto per la manipolazione delle tavolozze di colori. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Traduce i colori da e verso le strutture GDI+ Color. Questa classe non può essere ereditata. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Incapsula un'estremità di linea personalizzata definita dall'utente. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | Il contenitore del flusso di dati. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Rappresenta un oggetto eliminabile. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | La classe immagine incorporata |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | La figura. Un contenitore per forme. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Supporto per l'elaborazione dei flussi di file. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Definisce un formato particolare per il testo, includendo il tipo di carattere, la dimensione e gli attributi di stile. Questa classe non può essere ereditata. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Impostazioni dei caratteri del renderer per formati vettoriali di imaging generali. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Rappresenta la grafica secondo il motore grafico utilizzato nell'assembly corrente. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Rappresenta una serie di linee e curve collegate. Questa classe non può essere ereditata. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | Il processore di buffer avanzato. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | Il fotogramma di animazione |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | Il processore di buffer. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | Il convertitore di colore. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | L'interfaccia della tavolozza di colori. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Interfaccia dei metadati dell'immagine. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Il creatore di immagini. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Il descrittore del creatore di immagini che specifica le proprietà del creatore. Il descrittore del creatore è usato per superare<br/>            la necessità di contenere ogni istanza del creatore di immagini in memoria e i problemi di multithreading. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | Il descrittore dell'immagine. Contiene le proprietà e i metodi di base per tutti gli altri tipi di descrittori di immagine. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | L'esportatore di immagini. Può esportare dati dal formato interno `aspose.imaging` a un formato di dati specificato. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Rappresenta il descrittore dell'esportatore di immagini. Il descrittore dell'esportatore è usato per superare la necessità di contenere ogni istanza dell'esportatore<br/>            in memoria e i problemi di multithreading. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Il caricatore di immagini. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Il descrittore del caricatore di immagini che specifica le proprietà del caricatore. Il descrittore del caricatore è usato per superare<br/>            la necessità di contenere ogni istanza del caricatore di immagini in memoria e i problemi di multithreading. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | Il convertitore di colore per formati di immagine indicizzati. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Interfaccia del contenitore dei metadati dell'immagine. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | L'interfaccia dell'immagine multipagina |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | L'interfaccia estesa dell'immagine multipagina |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Rappresenta un oggetto con limiti. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Rappresenta una forma ordinata. Una forma ordinata è un insieme continuo di punti con un punto di partenza e un punto finale.<br/>            L'insieme continuo di punti è collegato mediante una regola specifica. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Conforma ai pixel ARGB a 32 bit caricati parzialmente. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Conforma ai pixel caricati parzialmente. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Il caricatore di dati parziali. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | Il caricatore di pixel ARGB a 32 bit per immagini raster. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit per immagini raster. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | Il caricatore di pixel per immagini raster. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | Il caricatore di dati grezzi per immagini raster. |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine è la classe base per tutti i tipi di immagini. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) contiene informazioni su come i colori bitmap e metafile vengono manipolati durante il rendering. Un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) mantiene diverse impostazioni di regolazione del colore, incluse matrici di regolazione del colore, matrici di regolazione in scala di grigi, valori di correzione gamma, tabelle di mappatura dei colori e valori di soglia del colore. Durante il rendering, i colori possono essere corretti, scuriti, schiariti e rimossi. Per applicare tali manipolazioni, inizializza un oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) e passa il percorso di quell'oggetto [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) (insieme al percorso di un [Image](/imaging/python-net/aspose.imaging/image/)) al metodo DrawImage. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Rappresenta il registro dei creatori di immagini. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Rappresenta il registro degli esportatori di immagini. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Rappresenta il registro dei caricatori di immagini. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni base dell'immagine. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Classe delle impostazioni di ridimensionamento dell'immagine |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Classe per rappresentare una sequenza di elementi |
| [License](/imaging/python-net/aspose.imaging/license/) | Fornisce metodi per licenziare il componente. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Rappresenta le opzioni di caricamento. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Sostituisce la matrice GDI+. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Fornisce metodi a consumo per l'integrazione |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Rappresenta un dizionario non generico. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Elenco non generico di oggetti |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | L'oggetto con i limiti. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Cache per i font OpenType installati nel sistema. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Definisce un oggetto usato per disegnare linee, curve e figure. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Il formato dei dati pixel. Questo è un oggetto immutabile. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Rappresenta una coppia ordinata di coordinate intere x e y che definisce un punto in un piano bidimensionale. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Rappresenta una coppia ordinata di coordinate in virgola mobile x e y che definisce un punto in un piano bidimensionale. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Rappresenta un'immagine raster che supporta operazioni grafiche raster. Questa immagine memorizza nella cache i dati pixel quando necessario. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | L'immagine raster multipagina |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rappresenta un'immagine raster che supporta operazioni grafiche raster. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi. |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Memorizza un insieme di quattro interi che rappresentano la posizione e le dimensioni di un rettangolo. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Memorizza un insieme di quattro numeri in virgola mobile che rappresentano la posizione e le dimensioni di un rettangolo. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Descrive l'interno di una forma grafica composta da rettangoli e percorsi. Questa classe non può essere ereditata. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Le impostazioni di rimozione dello sfondo |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | L'impostazione di risoluzione per le opzioni di salvataggio dell'immagine. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | La forma. Un insieme continuo di punti collegati mediante una regola specifica. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Rappresenta un segmento di forma. Un segmento è una linea o curva che collega due punti. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Rappresenta la dimensione. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Memorizza una coppia ordinata di numeri a virgola mobile, tipicamente la larghezza e l'altezza di un rettangolo. |
| [Source](/imaging/python-net/aspose.imaging/source/) | La sorgente è usata per contenere tutte le informazioni rilevanti per una pipe di oggetti. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Rappresenta un contenitore di flusso diviso che contiene il flusso e fornisce routine di elaborazione del flusso. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Rappresenta un contenitore di flusso che contiene il flusso e fornisce routine di elaborazione del flusso. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Incapsula le informazioni di layout del testo (come allineamento, orientamento e tabulazioni), le manipolazioni di visualizzazione (come l'inserimento di ellissi e la sostituzione di cifre nazionali) e le funzionalità OpenType. Questa classe non può essere ereditata. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | L'oggetto che supporta la trasparenza. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | L'immagine vettoriale è la classe base per tutti i tipi di immagini vettoriali. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | L'immagine multipagina Vector |
## **Enumerations**
| **Enumeration** | **Descrizione** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Indica il modo in cui la grafica deve essere trattata dopo essere stata visualizzata. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Specifica il tipo di cache da utilizzare. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Rappresenta il set di caratteri utilizzato. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Specifica quali oggetti utilizzano le informazioni di regolazione del colore. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Specifica i canali individuali nello spazio colore CMYK (ciano, magenta, giallo, nero). Questa enumerazione è usata dai metodi SetOutputChannel. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Metodo di confronto del colore per regolare al vicino più prossimo |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Specifica i tipi di immagini e colori che saranno influenzati dalle impostazioni di regolazione del colore e della scala di grigi di un [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Metodi di quantizzazione dei colori |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Specifica il livello di qualità da utilizzare durante il compositing. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Specifica il tipo di forma grafica da utilizzare su entrambe le estremità di ogni trattino in una linea tratteggiata. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Specifica lo stile delle linee tratteggiate disegnate con un oggetto [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | La modalità di recupero dati. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Metodo di dithering. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | I metodi di dithering usati per controllare la conversione del colore. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Uno dei formati di file di imaging supportati. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Specifica come viene riempito l'interno di un percorso chiuso. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Specifica le informazioni di stile applicate al testo. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Specifica l'unità di misura per i dati forniti. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Specifica i diversi motivi disponibili per gli oggetti [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/). |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Specifica il tipo di visualizzazione per i prefissi dei tasti di scelta rapida relativi al testo. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Filtri immagine da utilizzare |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | L'enumerazione [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) specifica l'algoritmo utilizzato quando le immagini vengono scalate o ruotate. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Specifica i colori di sistema noti. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Specifica gli stili di estremità disponibili con cui un oggetto [Pen](/imaging/python-net/aspose.imaging/pen/) può terminare una linea. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Specifica come unire segmenti consecutivi di linee o curve in una figura (sottotraccia) contenuta in un oggetto [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Specifica l'ordine per le operazioni di trasformazione della matrice. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | Il metodo di estrazione della palette dell'immagine |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Specifica il livello di conformità PDF per il file di output. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Specifica l'allineamento di un oggetto [Pen](/imaging/python-net/aspose.imaging/pen/) rispetto alla linea teorica a larghezza zero. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Specifica il tipo di riempimento che un oggetto [Pen](/imaging/python-net/aspose.imaging/pen/) utilizza per riempire le linee. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | Il significato reale del formato dei dati pixel. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | Il tipo di elaborazione. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Specifica il tipo di ridimensionamento. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Enumerazione dell'unità di risoluzione. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Specifica di quanto un'immagine è ruotata e l'asse utilizzato per capovolgere l'immagine. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Fornisce i campi che rappresentano i punti di riferimento in [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) per la ricerca. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Specifica se l'anti-aliasing (smussatura) è applicato a linee e curve e ai bordi delle aree riempite. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Specifica l'allineamento di una stringa di testo rispetto al suo rettangolo di layout. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | L'enumerazione specifica come sostituire le cifre in una stringa in base alla locale o alla lingua dell'utente. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Specifica le informazioni di visualizzazione e layout per le stringhe di testo. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Specifica come tagliare i caratteri da una stringa che non si adatta completamente a una forma di layout. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Specifica la qualità del rendering del testo. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Specifica il tipo di trasformazione di deformazione applicata. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Specifica come una texture o una sfumatura viene ripetuta quando è più piccola dell'area da riempire. |
