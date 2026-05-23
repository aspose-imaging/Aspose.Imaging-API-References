---
title: "Classe DjvuImage"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.djvu/djvuimage/
---

**Summary:** DjVu document class supports graphics file format and facilitates seamless<br/>            management of scanned documents and books, integrating text, drawings, images,<br/>            and photos into a single format. Supporting multi-page operations, you can<br/>            efficiently access unique document identifiers, count pages, set active pages,<br/>            and retrieve specific document pages. With features for resizing, rotating,<br/>            dithering, cropping, grayscale transformation, gamma corrections, adjustments,<br/>            and filters application, this class empowers precise manipulation and enhancement<br/>            of DjVu images to meet diverse application needs with ease and precision.

**Module:** [aspose.imaging.fileformats.djvu](/imaging/python-net/aspose.imaging.fileformats.djvu/)

**Full Name:** aspose.imaging.fileformats.djvu.DjvuImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DjvuImage(stream)](#DjvuImage_stream_1) | Inizia a lavorare con le immagini DjVu inizializzando una nuova istanza della<br/>            [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) classe usando un parametro Stream. Perfetto per<br/>            gli sviluppatori che desiderano un'integrazione senza soluzione di continuità dell'elaborazione delle immagini DjVu nei<br/>            loro progetti. |
| [DjvuImage(stream, load_options)](#DjvuImage_stream_load_options_2) | Inizia a lavorare con le immagini DjVu senza problemi con questo costruttore, che<br/>            inizializza una nuova istanza della classe [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) usando un parametro Stream e<br/>            parametri LoadOptions. Perfetto per gli sviluppatori che desiderano un controllo preciso sulle<br/>            opzioni di caricamento delle immagini DjVu mantenendo semplicità ed efficienza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| active_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r/w | Naviga nel tuo documento DjVu accedendo o impostando la pagina attualmente attiva<br/>            tramite questa proprietà. Passa senza soluzione di continuità tra le pagine per concentrarti su contenuti specifici<br/>            e migliorare l'esperienza di visualizzazione del documento. |
| auto_adjust_palette | bool | r/w | Ottiene o imposta un valore che indica se la palette viene regolata automaticamente. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un valore per il colore di sfondo. |
| bits_per_pixel | int | r | Ottiene il conteggio dei bit per pixel dell'immagine. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ottiene i limiti dell'oggetto. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene il contenitore [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Ottiene lo stream di dati dell'oggetto. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| djvu_pages | [DjvuPage[]](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r | Recupera rapidamente tutte le pagine contenute nel tuo documento DjVu usando questa<br/>            proprietà. Semplifica il flusso di lavoro di elaborazione dei documenti accedendo facilmente e<br/>            gestendo le singole pagine nei tuoi file DjVu. Migliora l'efficienza e<br/>            ottimizza le tue attività con un comodo recupero delle pagine. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta l'istanza Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ottieni le informazioni sul formato file associate al tuo file immagine DjVu. Determina rapidamente<br/>            il formato del tuo file per un'integrazione senza soluzione di continuità nel tuo flusso di lavoro. |
| first_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r | Accedi alla prima pagina del tuo documento DjVu con questa proprietà. Recupera rapidamente<br/>            la pagina iniziale per iniziare a visualizzare o elaborare il tuo documento in modo efficiente. |
| has_alpha | bool | r | Determina rapidamente se il tuo file immagine DjVu contiene un canale alfa.<br/>            Semplifica il tuo flusso di lavoro verificando la presenza di informazioni sulla trasparenza<br/>            nelle tue immagini. |
| has_background_color | bool | r/w | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| has_transparent_color | bool | r/w | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| height | int | r | Ottiene l'altezza dell'immagine. |
| horizontal_resolution | float | r/w | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| identificatore | int | r | Ottiene l'identificatore unico per il documento |
| image_opacity | float | r | Ottiene l'opacità di questa immagine. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Ottiene o imposta il monitor di interruzione. |
| is_cached | bool | r | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| is_raw_data_available | bool | r | Ottiene un valore che indica se il caricamento dei dati grezzi è supportato. |
| last_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r | Recupera l'ultima pagina del tuo documento DjVu usando questa proprietà. Accedi rapidamente<br/>            all'ultima pagina per scopi di visualizzazione o elaborazione con facilità. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Ottiene o imposta i dati XMP dal fotogramma. |
| next_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r | Naviga nel tuo documento DjVu accedendo alla pagina successiva con questa<br/>            pratica proprietà. Spostati rapidamente in avanti nella visualizzazione o<br/>            nelle attività di elaborazione del documento. |
| page_count | int | r | Recupera il numero totale di pagine nella tua collezione di immagini DjVu con questa proprietà.<br/>            Ideale per valutare rapidamente l'estensione del tuo documento o libro memorizzato in formato DjVu.<br/>            Migliora l'efficienza del tuo flusso di lavoro con informazioni precise sul conteggio delle pagine. |
| [pages](#pages1) | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Accedi alle singole pagine della tua collezione di immagini DjVu con questa proprietà.<br/>            Semplifica la navigazione e la manipolazione del tuo documento o libro memorizzato in formato DjVu<br/>            accedendo direttamente a ciascuna pagina. Migliora l'efficienza del tuo flusso di lavoro con un facile<br/>            recupero delle pagine. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| premultiply_components | bool | r/w | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| previous_page | [DjvuPage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvupage/) | r | Spostati rapidamente all'indietro nella visualizzazione o nelle attività di elaborazione del tuo documento DjVu<br/>            accedendo alla pagina precedente con questa pratica proprietà. Naviga in modo efficiente<br/>            attraverso il tuo documento con facilità. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Ottiene o imposta il convertitore di colore personalizzato |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Ottiene il formato dei dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Ottiene le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione. |
| raw_fallback_index | int | r/w | Ottiene o imposta l'indice di fallback da usare quando l'indice della tavolozza è fuori dai limiti |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Ottiene o imposta il convertitore di colore indicizzato |
| raw_line_size | int | r | Ottiene la dimensione della riga grezza in byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Ottiene la dimensione dell'oggetto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene il colore trasparente dell'immagine. |
| update_xmp_data | bool | r/w | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| use_palette | bool | r | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
| use_raw_data | bool | r/w | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile. |
| vertical_resolution | float | r/w | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Ottiene la larghezza dell'immagine. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta i dati Xmp. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Regola la _luminosità_ di un'immagine usando un parametro specificato, <br/>            fornendo controllo sui livelli di luminanza per una chiarezza visiva ottimale. Questo metodo aumenta <br/>            o diminuisce la luminosità complessiva dell'immagine, consentendo regolazioni precise per <br/>            ottenere gli effetti di illuminazione desiderati. Modulando la luminosità, gli utenti possono ottimizzare la visibilità dell'immagine <br/>            e migliorare la riproduzione dei dettagli per un'esperienza di visualizzazione migliorata. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Migliora il contrasto di [Image](/imaging/python-net/aspose.imaging/image/) per aumentare la chiarezza visiva e <br/>            evidenziare i dettagli con questo metodo, che regola la differenza di luminosità tra <br/>            le aree chiare e scure. Regolando finemente i livelli di contrasto, gli utenti possono ottenere immagini più vivide e <br/>            incisive, migliorando la qualità complessiva dell'immagine e massimizzando la visibilità dei dettagli. <br/>            Questa regolazione aiuta a far emergere le sottili sfumature di colore e texture, risultando in <br/>            immagini più dinamiche e visivamente attraenti. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | La correzione gamma, specificamente per i canali rosso, verde e blu, comporta la regolazione <br/>            della luminosità di ciascuna componente colore separatamente. Applicando diversi coefficienti gamma <br/>            ai canali RGB, è possibile perfezionare la luminosità e il contrasto complessivi <br/>            di un'immagine. Questa tecnica garantisce una rappresentazione accurata dei colori e migliora la <br/>            qualità visiva dell'immagine su diversi dispositivi di visualizzazione. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | La correzione gamma viene applicata a un'immagine con parametri personalizzabili per i canali rosso, verde <br/>            e blu, consentendo una regolazione precisa del bilanciamento del colore e della luminosità. Questo <br/>            metodo migliora la qualità dell'immagine perfezionando la rappresentazione dei colori, garantendo una resa ottimale <br/>            su diversi dispositivi di visualizzazione. Regolare i valori gamma per i singoli <br/>            canali migliora il bilanciamento del colore e l'appeal visivo. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| auto_brightness_contrast() | Esegue la normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine. |
| auto_rotate() | Ruota automaticamente l'immagine in base ai dati di orientamento estratti dai metadati Exif <br/>            . Questo metodo garantisce che le immagini vengano visualizzate nella corretta orientazione, <br/>            migliorando l'esperienza dell'utente ed eliminando la necessità di regolazioni manuali. Analizzando le informazioni Exif, l'immagine viene ruotata di conseguenza, fornendo un'esperienza di visualizzazione fluida <br/>            su diverse piattaforme e dispositivi. Questo processo di rotazione automatizzata <br/>            semplifica la gestione delle immagini e migliora l'usabilità complessiva, soprattutto quando <br/>            si lavora con grandi lotti di immagini con orientamenti variabili. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarizzazione usando l'algoritmo di sogliatura adattiva di Bradley con immagine integrale<br/> la sogliatura è un metodo che calcola una soglia locale per ogni pixel basandosi su una zona locale. Si adatta alle variazioni di illuminazione nell'immagine, rendendola adatta a immagini con condizioni di illuminazione non uniformi. Calcolando la soglia usando immagini integrali, gestisce efficientemente grandi zone, rendendola applicabile a applicazioni in tempo reale. Questa tecnica è comunemente usata nell'elaborazione di documenti, OCR (Riconoscimento Ottico dei Caratteri), e compiti di segmentazione delle immagini dove la binarizzazione accurata è essenziale per l'analisi successiva. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarizzazione con una soglia predefinita semplifica le immagini complesse in rappresentazioni binarie<br/> dove i pixel sono classificati come neri o bianchi in base alla loro intensità rispetto a un valore di soglia specificato. Questa tecnica è comunemente usata nell'elaborazione delle immagini per migliorare la chiarezza, semplificare l'analisi e preparare le immagini per ulteriori passaggi di elaborazione come il riconoscimento ottico dei caratteri (OCR). Applicando una soglia fissa, è possibile trasformare rapidamente le immagini in scala di grigi in forma binaria, rendendole più facili da interpretare ed estrarre informazioni significative. |
| binarize_otsu() | Binarizzazione usando la sogliatura di Otsu è una tecnica che calcola automaticamente una soglia ottimale basata sull'istogramma dell'immagine. Separa l'immagine in primo piano e sfondo minimizzando la varianza intra-classe. Il metodo di Otsu è ampiamente usato per segmentare le immagini in forma binaria, soprattutto quando la distribuzione delle intensità dei pixel è bimodale o multimodale. Questo approccio è utile per compiti come il rilevamento di oggetti, la segmentazione delle immagini e l'estrazione di caratteristiche, dove una delimitazione accurata tra primo piano e sfondo è cruciale. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| cache_data() | Memorizza i dati in modo privato per ottimizzare le prestazioni e ridurre la necessità di recuperare dati ripetutamente da fonti esterne. Questo approccio aiuta anche a conservare le risorse, soprattutto in scenari in cui l'accesso ai dati è frequente o le risorse sono limitate. |
| [can_load(file_path)](#can_load_file_path_11) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate. |
| [can_load(stream)](#can_load_stream_13) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate. |
| [can_save(options)](#can_save_options_18) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite. |
| [create(files)](#create_files_19) | Crea l'immagine multipagina contenente i file specificati. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Crea l'immagine multipagina contenente i file specificati. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Crea una nuova immagine utilizzando le opzioni di creazione specificate. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Crea un'istanza di [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) dall'array di pixel fornito.<br/>            <br/>            Convalida che la larghezza e l'altezza specificate corrispondano alle dimensioni dei dati pixel.<br/>            Questo metodo può essere usato solo quando la libreria è in modalità Licensed. |
| [create(images)](#create_images_23) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Crea le opzioni di creazione multipagina specificate. |
| [create_from_files(files)](#create_from_files_files_26) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_images(images)](#create_from_images_images_28) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | Il ritaglio con spostamenti consente di regolare con precisione la posizione e le dimensioni dell'area ritagliata all'interno di un'immagine. Questa funzione è preziosa per perfezionare le composizioni, allineare gli elementi e enfatizzare i punti focali nei tuoi contenuti visivi. Incorporando gli spostamenti nel processo di ritaglio, puoi ottenere una precisione pixel-perfetta e perfezionare l'inquadratura delle tue immagini con facilità. |
| [crop(rectangle)](#crop_rectangle_31) | "Crop" ritaglia la tua immagine per focalizzarsi su dettagli specifici o rimuovere elementi indesiderati,<br/> migliorandone la composizione e l'impatto visivo. Che tu stia regolando foto per i social media, creando banner per siti web o progettando materiale stampato, questo strumento ti aiuta a perfezionare le tue immagini con precisione e chiarezza. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | Esegue il dithering sull'immagine corrente. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | La funzione "Dither" applica un effetto di dithering alla tua immagine, migliorandone la qualità visiva riducendo le bande e migliorando le transizioni di colore. Che tu stia lavorando su arte digitale, fotografia o progetti di design grafico, questa funzione aggiunge un tocco professionale alle tue immagini, rendendole più fluide e raffinate. |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine. |
| [filter(rectangle, options)](#filter_rectangle_options_35) | Applica filtri a un'area rettangolare specificata all'interno dell'immagine per migliorare o modificare il suo aspetto. Mirando a regioni specifiche, questo metodo consente regolazioni precise, come sfocatura, nitidezza o l'applicazione di effetti artistici, per ottenere risultati visivi desiderati. La messa a punto dei filtri su aree selezionate permette agli utenti di personalizzare l'estetica dell'immagine, migliorare la chiarezza e creare effetti artistici su misura per le loro preferenze. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | Ottiene l'array predefinito di pixel ARGB a 32 bit. |
| [get_default_options(args)](#get_default_options_args_38) | Ottiene le opzioni predefinite. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | Ottiene l'array predefinito di dati grezzi. |
| [get_file_format(file_path)](#get_file_format_file_path_42) | Ottiene il formato del file. |
| [get_file_format(stream)](#get_file_format_stream_43) | Ottiene il formato del file. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | Ottiene il formato del file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | Ottiene la data e l'ora dell'ultima modifica dell'immagine di risorsa. |
| [get_original_options()](#get_original_options__48) | Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro. |
| [get_pixel(x, y)](#get_pixel_x_y_49) | Ottiene un pixel dell'immagine. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | Ottiene un'altezza proporzionale. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | Ottiene una larghezza proporzionale. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | Converte in aps. |
| [get_skew_angle()](#get_skew_angle__53) | Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| grayscale() | La trasformazione in scala di grigi converte un'immagine in una rappresentazione in bianco e nero, dove l'intensità di ogni pixel è rappresentata da un unico valore che varia dal nero al bianco. Questo processo rimuove le informazioni di colore, producendo un'immagine monocromatica. Le immagini in scala di grigi sono comunemente usate in applicazioni dove il colore non è necessario o dove si preferisce la semplicità, come la scansione di documenti, la stampa e alcuni tipi di analisi delle immagini. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | Esegue un rapido controllo per determinare se l'immagine è firmata digitalmente, utilizzando la password e la soglia fornite. |
| [load(file_path)](#load_file_path_55) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(stream)](#load_stream_57) | Carica il tuo documento DjVu con questo metodo. Semplifica il tuo processo accedendo rapidamente<br/> e importando i file DjVu nella tua applicazione. |
| [load(stream, load_options)](#load_stream_load_options_58) | Importa il tuo documento DjVu utilizzando questo metodo con i parametri stream e loadOptions.<br/> Semplifica il tuo processo accedendo rapidamente e importando i file DjVu nella tua applicazione, fornendo flessibilità e opzioni di personalizzazione per soddisfare le tue esigenze. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Carica pixel ARGB a 32 bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Carica pixel ARGB a 64 bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Carica pixel in formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Carica pixel in formato CMYK.<br/>            Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_document(stream)](#load_document_stream_63) | Carica il tuo documento DjVu con questo metodo. Semplifica il tuo processo accedendo rapidamente<br/> e importando i file DjVu nella tua applicazione. |
| [load_document(stream, load_options)](#load_document_stream_load_options_64) | Importa il tuo documento DjVu utilizzando questo metodo con i parametri stream e loadOptions.<br/> Semplifica il tuo processo accedendo rapidamente e importando i file DjVu nella tua applicazione, fornendo flessibilità e opzioni di personalizzazione per soddisfare le tue esigenze. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_65) | Carica parzialmente pixel ARGB a 32 bit (per blocchi). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_66) | Carica parzialmente pixel ARGB a 64 bit per pacchetti. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_67) | Carica pixel parzialmente per pacchetti. |
| [load_pixels(rectangle)](#load_pixels_rectangle_68) | Carica pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_69) | Carica dati grezzi. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_70) | Carica dati grezzi. |
| [load_stream(stream)](#load_stream_stream_71) | Carica una nuova immagine dallo stream specificato. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_72) | Carica una nuova immagine dallo stream specificato. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_73) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| normalize_angle() | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_74) | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normalizza l'istogramma dell'immagine — regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_75) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_76) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| remove_metadata() | Rimuove i metadati di questa istanza immagine impostando il valore di [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_77) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_78) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_79) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_80) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_81) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [resize(new_width, new_height)](#resize_new_width_new_height_82) | Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_83) | Ridimensiona l'immagine usando il metodo `Resize`, fornendo un modo semplice ed efficace<br/> per regolare le dimensioni delle tue immagini secondo le tue esigenze. Questa funzionalità versatile ti permette di scalare facilmente le immagini alla dimensione desiderata,<br/> migliorandone l'usabilità su varie piattaforme e applicazioni. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_84) | Ridimensiona l'immagine alla larghezza e altezza specificate applicando impostazioni aggiuntive<br/> secondo necessità. Questo metodo consente agli utenti di regolare le dimensioni dell'immagine mantenendo attributi desiderati come rapporto d'aspetto, qualità dell'immagine e impostazioni di compressione. Fornendo flessibilità nelle opzioni di ridimensionamento, gli utenti possono adattare l'immagine a requisiti specifici e ottimizzarne l'aspetto per varie applicazioni e piattaforme. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_85) | Ridimensiona l'immagine. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_86) | Ridimensiona l'immagine. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_87) | Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_88) | Il metodo `ResizeHeightProportionally` ti consente di regolare l'altezza della tua<br/> immagine mantenendo il suo rapporto d'aspetto. Questo garantisce che l'immagine mantenga le sue proporzioni, evitando distorsioni e preservando la sua integrità visiva.<br/> Che tu stia ottimizzando le immagini per pagine web, app mobili o stampa, questo metodo assicura che le tue immagini abbiano il miglior aspetto su diverse piattaforme e dispositivi. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_89) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_90) | Ridimensiona l'altezza proporzionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_91) | Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_92) | Il metodo `ResizeWidthProportionally` offre una soluzione comoda per regolare la<br/> larghezza della tua immagine mantenendo il suo rapporto d'aspetto. Ridimensionando proporzionalmente la larghezza, puoi garantire che le tue immagini rimangano visivamente attraenti e<br/> coerenti su diversi dispositivi e dimensioni dello schermo, migliorandone la versatilità e l'usabilità in vari contesti. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_93) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_94) | Ridimensiona la larghezza proporzionalmente. |
| [rotate(angle)](#rotate_angle_95) | Ruota l'immagine attorno al centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_96) | Ruota l'immagine attorno al suo centro con il metodo Rotate della classe<br/> RasterCachedMultipageImage. Questa funzione comoda ti permette di regolare facilmente l'orientamento delle immagini mantenendo la loro posizione centrale,<br/> migliorando le tue capacità di manipolazione delle immagini. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_97) | Il metodo `RotateFlip` offre opzioni di manipolazione versatili per la tua immagine, consentendo<br/> di ruotare, capovolgere o eseguire entrambe le operazioni sul fotogramma attivo in modo indipendente.<br/> Che tu stia modificando foto, creando grafiche o migliorando l'arte digitale, questo metodo fornisce un controllo preciso sull'orientamento e la composizione delle tue immagini,<br/> assicurando che soddisfino la tua visione creativa con facilità ed efficienza. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_98) | Ruota il flip completo. |
| save() | Salva i dati dell'immagine nello stream sottostante. |
| [save(file_path)](#save_file_path_99) | Salva l'immagine nella posizione file specificata. |
| [save(file_path, options)](#save_file_path_options_100) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_101) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, over_write)](#save_file_path_over_write_102) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_103) | Salva i dati. |
| [save(stream, options_base)](#save_stream_options_base_104) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_105) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_106) | Salva i pixel ARGB a 32 bit. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_107) | Salva i pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_108) | Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_109) | Salva i pixel (metodo specifico del formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_110) | Salva i dati grezzi. |
| [save_to_stream(stream)](#save_to_stream_stream_111) | Salva i dati dell'oggetto nello stream specificato. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_112) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_113) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_114) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_115) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_116) | Imposta un pixel immagine a 32 bit ARGB per la posizione specificata. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_117) | Imposta la tavolozza dell'immagine. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_118) | Imposta un pixel dell'immagine per la posizione specificata. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_119) | Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_120) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_121) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_122) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |


### Constructor: DjvuImage(stream) {#DjvuImage_stream_1}


```
 DjvuImage(stream) 
```

Inizia a lavorare con le immagini DjVu inizializzando una nuova istanza della<br/>            [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) classe usando un parametro Stream. Perfetto per<br/>            gli sviluppatori che desiderano un'integrazione senza soluzione di continuità dell'elaborazione delle immagini DjVu nei<br/>            loro progetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |


**See also:**

**[Example # 1](#example_145)**: This example shows how to load a DJVU image from a file stream.


### Constructor: DjvuImage(stream, load_options) {#DjvuImage_stream_load_options_2}


```
 DjvuImage(stream, load_options) 
```

Inizia a lavorare con le immagini DjVu senza problemi con questo costruttore, che<br/>            inizializza una nuova istanza della classe [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) usando un parametro Stream e<br/>            parametri LoadOptions. Perfetto per gli sviluppatori che desiderano un controllo preciso sulle<br/>            opzioni di caricamento delle immagini DjVu mantenendo semplicità ed efficienza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |


**See also:**

**[Example # 1](#example_146)**: This example shows how to load a DJVU image from a file stream to stay within...


### Property: pages {#pages1}

Accedi alle singole pagine della tua collezione di immagini DjVu con questa proprietà.<br/>            Semplifica la navigazione e la manipolazione del tuo documento o libro memorizzato in formato DjVu<br/>            accedendo direttamente a ciascuna pagina. Migliora l'efficienza del tuo flusso di lavoro con un facile<br/>            recupero delle pagine.

**See also:**

**[Example # 1](#example_145)**: This example shows how to load a DJVU image from a file stream.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Regola la _luminosità_ di un'immagine usando un parametro specificato, <br/>            fornendo controllo sui livelli di luminanza per una chiarezza visiva ottimale. Questo metodo aumenta <br/>            o diminuisce la luminosità complessiva dell'immagine, consentendo regolazioni precise per <br/>            ottenere gli effetti di illuminazione desiderati. Modulando la luminosità, gli utenti possono ottimizzare la visibilità dell'immagine <br/>            e migliorare la riproduzione dei dettagli per un'esperienza di visualizzazione migliorata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| luminosità | int | Valore di luminosità. |


**See also:**

**[Example # 1](#example_156)**: The following example performs brightness correction of a DJVU image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Migliora il contrasto di [Image](/imaging/python-net/aspose.imaging/image/) per aumentare la chiarezza visiva e <br/>            evidenziare i dettagli con questo metodo, che regola la differenza di luminosità tra <br/>            le aree chiare e scure. Regolando finemente i livelli di contrasto, gli utenti possono ottenere immagini più vivide e <br/>            incisive, migliorando la qualità complessiva dell'immagine e massimizzando la visibilità dei dettagli. <br/>            Questa regolazione aiuta a far emergere le sottili sfumature di colore e texture, risultando in <br/>            immagini più dinamiche e visivamente attraenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| contrasto | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**See also:**

**[Example # 1](#example_157)**: The following example performs contrast correction of a DJVU image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

La correzione gamma, specificamente per i canali rosso, verde e blu, comporta la regolazione <br/>            della luminosità di ciascuna componente colore separatamente. Applicando diversi coefficienti gamma <br/>            ai canali RGB, è possibile perfezionare la luminosità e il contrasto complessivi <br/>            di un'immagine. Questa tecnica garantisce una rappresentazione accurata dei colori e migliora la <br/>            qualità visiva dell'immagine su diversi dispositivi di visualizzazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**See also:**

**[Example # 1](#example_154)**: The following example performs gamma-correction of a DJVU image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

La correzione gamma viene applicata a un'immagine con parametri personalizzabili per i canali rosso, verde <br/>            e blu, consentendo una regolazione precisa del bilanciamento del colore e della luminosità. Questo <br/>            metodo migliora la qualità dell'immagine perfezionando la rappresentazione dei colori, garantendo una resa ottimale <br/>            su diversi dispositivi di visualizzazione. Regolare i valori gamma per i singoli <br/>            canali migliora il bilanciamento del colore e l'appeal visivo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma_red | float | Coefficiente gamma per il canale rosso |
| gamma_green | float | Coefficiente gamma per il canale verde |
| gamma_blue | float | Gamma per il coefficiente del canale blu |


**See also:**

**[Example # 1](#example_155)**: The following example performs gamma-correction of a DJVU image applying diff...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

Calcola la percentuale di somiglianza tra i dati estratti e la password originale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password utilizzata per estrarre i dati incorporati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore percentuale di similarità. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra di pixel s x s<br/>                centrata attorno a questo pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarizzazione usando l'algoritmo di sogliatura adattiva di Bradley con immagine integrale<br/> la sogliatura è un metodo che calcola una soglia locale per ogni pixel basandosi su una zona locale. Si adatta alle variazioni di illuminazione nell'immagine, rendendola adatta a immagini con condizioni di illuminazione non uniformi. Calcolando la soglia usando immagini integrali, gestisce efficientemente grandi zone, rendendola applicabile a applicazioni in tempo reale. Questa tecnica è comunemente usata nell'elaborazione di documenti, OCR (Riconoscimento Ottico dei Caratteri), e compiti di segmentazione delle immagini dove la binarizzazione accurata è essenziale per l'analisi successiva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra di pixel s x s<br/>            centrata attorno a questo pixel. |
| window_size | int | La dimensione della finestra di pixel s x s centrata attorno a questo pixel |


**See also:**

**[Example # 1](#example_152)**: The following example binarizes a DJVU image with Bradley's adaptive threshol...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarizzazione con una soglia predefinita semplifica le immagini complesse in rappresentazioni binarie<br/> dove i pixel sono classificati come neri o bianchi in base alla loro intensità rispetto a un valore di soglia specificato. Questa tecnica è comunemente usata nell'elaborazione delle immagini per migliorare la chiarezza, semplificare l'analisi e preparare le immagini per ulteriori passaggi di elaborazione come il riconoscimento ottico dei caratteri (OCR). Applicando una soglia fissa, è possibile trasformare rapidamente le immagini in scala di grigi in forma binaria, rendendole più facili da interpretare ed estrarre informazioni significative.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| soglia | System.Byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato a esso un valore di<br/>            255, altrimenti 0. |


**See also:**

**[Example # 1](#example_150)**: The following example binarizes a DJVU image with the predefined threshold. B...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

Unisce questa istanza di immagine con l'immagine _overlay_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine di sovrapposizione. |
| overlay_alpha | System.Byte | L'alpha della sovrapposizione. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Unisce questa istanza di immagine con l'immagine _overlay_.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'origine della fusione dell'immagine di sfondo. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine di sovrapposizione. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | L'area di sovrapposizione. |
| overlay_alpha | System.Byte | L'alpha della sovrapposizione. |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


```
 can_load(file_path) 
```

Determina se l'immagine può essere caricata dal percorso file specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal file specificato; altrimenti, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


```
 can_load(file_path, load_options) 
```

Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal file specificato; altrimenti, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_13}


```
 can_load(stream) 
```

Determina se l'immagine può essere caricata dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal flusso specificato; altrimenti, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


```
 can_load(stream, load_options) 
```

Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal flusso specificato; altrimenti, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


```
 can_load_stream(stream) 
```

Determina se l'immagine può essere caricata dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal flusso specificato; altrimenti, <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


```
 can_load_stream_with_options(stream, load_options) 
```

Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal flusso specificato; altrimenti, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


```
 can_load_with_options(file_path, load_options) 
```

Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere caricata dal file specificato; altrimenti, <c>false</c>. |


### Method: can_save(options) {#can_save_options_18}


```
 can_save(options) 
```

Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <c>true</c> se l'immagine può essere salvata nel formato di file specificato rappresentato dalle opzioni di salvataggio fornite; altrimenti, <c>false</c>. |


### Method: create(files)  [static] {#create_files_19}


```
 create(files) 
```

Crea l'immagine multipagina contenente i file specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | string[] | I file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine multipagina |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


```
 create(files, throw_exception_on_load_error) 
```

Crea l'immagine multipagina contenente i file specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | string[] | I file. |
| throw_exception_on_load_error | bool | se impostato su <c>true</c> [throw exception on load error]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine multipagina |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


```
 create(image_options, width, height) 
```

Crea una nuova immagine utilizzando le opzioni di creazione specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni dell'immagine. |
| width | int | La larghezza. |
| height | int | L'altezza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine appena creata. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


```
 create(image_options, width, height, pixels) 
```

Crea un'istanza di [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) dall'array di pixel fornito.<br/>            <br/>            Convalida che la larghezza e l'altezza specificate corrispondano alle dimensioni dei dati pixel.<br/>            Questo metodo può essere usato solo quando la libreria è in modalità Licensed.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni utilizzate per creare il [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | La larghezza del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | L'altezza del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| pixel | int[] | L'array di valori dei pixel usato per popolare l'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Una [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) popolata con i dati dei pixel forniti. |


### Method: create(images)  [static] {#create_images_23}


```
 create(images) 
```

Crea una nuova immagine utilizzando le immagini specificate come pagine

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Le immagini. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image come IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


```
 create(images, dispose_images) 
```

Crea una nuova immagine dalle immagini specificate come pagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Le immagini. |
| dispose_images | bool | se impostato su <c>true</c> [dispose images]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image come IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


```
 create(multipage_create_options) 
```

Crea le opzioni di creazione multipagina specificate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Le opzioni di creazione multipagina. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine multipagina |


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


```
 create_from_files(files) 
```

Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | string[] | I file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine multipagina |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file | string[] | I file. |
| throw_exception_on_load_error | bool | se impostato su <c>true</c> lancia un'eccezione in caso di errore di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine multipagina |


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


```
 create_from_images(images) 
```

Crea una nuova immagine utilizzando le immagini specificate come pagine

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Le immagini. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image come IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


```
 create_from_images(images, dispose_images) 
```

Crea una nuova immagine dalle immagini specificate come pagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Le immagini. |
| dispose_images | bool | se impostato su <c>true</c> [dispose images]. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image come IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Il ritaglio con spostamenti consente di regolare con precisione la posizione e le dimensioni dell'area ritagliata all'interno di un'immagine. Questa funzione è preziosa per perfezionare le composizioni, allineare gli elementi e enfatizzare i punti focali nei tuoi contenuti visivi. Incorporando gli spostamenti nel processo di ritaglio, puoi ottenere una precisione pixel-perfetta e perfezionare l'inquadratura delle tue immagini con facilità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left_shift | int | Lo shift a sinistra. |
| right_shift | int | Lo shift a destra. |
| top_shift | int | Lo shift superiore. |
| bottom_shift | int | Lo shift inferiore. |

### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

"Crop" ritaglia la tua immagine per focalizzarsi su dettagli specifici o rimuovere elementi indesiderati,<br/> migliorandone la composizione e l'impatto visivo. Che tu stia regolando foto per i social media, creando banner per siti web o progettando materiale stampato, questo strumento ti aiuta a perfezionare le tue immagini con precisione e chiarezza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |


**See also:**

**[Example # 1](#example_149)**: The following example crops a DJVU image. The cropping area is be specified v...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

Esegue il dithering sull'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


```
 dither(dithering_method, bits_count, custom_palette) 
```

La funzione "Dither" applica un effetto di dithering alla tua immagine, migliorandone la qualità visiva riducendo le bande e migliorando le transizioni di colore. Che tu stia lavorando su arte digitale, fotografia o progetti di design grafico, questa funzione aggiunge un tocco professionale alle tue immagini, rendendole più fluide e raffinate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personalizzata per il dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password usata per generare i dati della firma digitale. |

### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

Applica filtri a un'area rettangolare specificata all'interno dell'immagine per migliorare o modificare il suo aspetto. Mirando a regioni specifiche, questo metodo consente regolazioni precise, come sfocatura, nitidezza o l'applicazione di effetti artistici, per ottenere risultati visivi desiderati. La messa a punto dei filtri su aree selezionate permette agli utenti di personalizzare l'estetica dell'immagine, migliorare la chiarezza e creare effetti artistici su misura per le loro preferenze.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Le opzioni. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


```
 get_argb_32_pixel(x, y) 
```

Ottiene un pixel ARGB a 32 bit dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il pixel ARGB a 32 bit per la posizione specificata. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


```
 get_default_argb_32_pixels(rectangle) 
```

Ottiene l'array predefinito di pixel ARGB a 32 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array predefinito di pixel. |


### Method: get_default_options(args) {#get_default_options_args_38}


```
 get_default_options(args) 
```

Ottiene le opzioni predefinite.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| args | System.Object | Gli argomenti. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Opzioni predefinite |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Il caricatore parziale di dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Ottiene l'array predefinito di dati grezzi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Byte | L'array predefinito di dati grezzi. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


```
 get_file_format(file_path) 
```

Ottiene il formato del file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Il formato file determinato. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


```
 get_file_format(stream) 
```

Ottiene il formato del file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Il formato file determinato. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


```
 get_file_format_of_stream(stream) 
```

Ottiene il formato del file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Il formato file determinato. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Ottiene il rettangolo che si adatta all'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere il rettangolo di adattamento. |
| pixel | int[] | I pixel ARGB a 32 bit. |
| width | int | La larghezza dell'oggetto. |
| height | int | L'altezza dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di adattamento o un'eccezione se non è possibile trovare un rettangolo di adattamento. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Ottiene il rettangolo che si adatta all'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere il rettangolo di adattamento. |
| width | int | La larghezza dell'oggetto. |
| height | int | L'altezza dell'oggetto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di adattamento o un'eccezione se non è possibile trovare un rettangolo di adattamento. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


```
 get_modify_date(use_default) 
```

Ottiene la data e l'ora dell'ultima modifica dell'immagine di risorsa.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| use_default | bool | se impostato su <c>true</c> utilizza le informazioni da FileInfo come valore predefinito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.DateTime | La data e l'ora in cui l'immagine della risorsa è stata modificata l'ultima volta. |


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni basate sulle impostazioni del file originale. |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


```
 get_pixel(x, y) 
```

Ottiene un pixel dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del pixel per la posizione specificata. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


```
 get_proportional_height(width, height, new_width) 
```

Ottiene un'altezza proporzionale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| new_width | int | La nuova larghezza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | L'altezza proporzionale. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


```
 get_proportional_width(width, height, new_height) 
```

Ottiene una larghezza proporzionale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| new_height | int | La nuova altezza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | La larghezza proporzionale. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Converte in aps.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni dell'immagine. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo di ritaglio. |
| page_number | int[] | Il numero di pagina. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom | Il flusso serializzato |


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'angolo di inclinazione, in gradi. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


```
 is_digital_signed(password, percentage_threshold) 
```

Esegue un rapido controllo per determinare se l'immagine è firmata digitalmente, utilizzando la password e la soglia fornite.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password per verificare la firma. |
| percentage_threshold | int | La soglia (in percentuale)[0-100] che determina se l'immagine è considerata firmata.<br/>            Se non specificata, verrà applicata una soglia predefinita (<c>75</c>). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Vero se l'immagine è firmata, altrimenti falso. |


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file o l'URL da cui caricare l'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine caricata. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file o l'URL da cui caricare l'immagine. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine caricata. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Carica il tuo documento DjVu con questo metodo. Semplifica il tuo processo accedendo rapidamente<br/> e importando i file DjVu nella tua applicazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Documento djvu caricato |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Importa il tuo documento DjVu utilizzando questo metodo con i parametri stream e loadOptions.<br/> Semplifica il tuo processo accedendo rapidamente e importando i file DjVu nella tua applicazione, fornendo flessibilità e opzioni di personalizzazione per soddisfare le tue esigenze.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Documento djvu caricato |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

Carica pixel ARGB a 32 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di pixel ARGB a 32 bit caricato. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

Carica pixel ARGB a 64 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di pixel ARGB a 64 bit caricato. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

Carica pixel in formato CMYK.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array di pixel CMYK caricato presentato come valori interi a 32 bit. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

Carica pixel in formato CMYK.<br/>            Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | L'array di pixel CMYK caricato. |


### Method: load_document(stream)  [static] {#load_document_stream_63}


```
 load_document(stream) 
```

Carica il tuo documento DjVu con questo metodo. Semplifica il tuo processo accedendo rapidamente<br/> e importando i file DjVu nella tua applicazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) | Documento djvu caricato |


### Method: load_document(stream, load_options)  [static] {#load_document_stream_load_options_64}


```
 load_document(stream, load_options) 
```

Importa il tuo documento DjVu utilizzando questo metodo con i parametri stream e loadOptions.<br/> Semplifica il tuo processo accedendo rapidamente e importando i file DjVu nella tua applicazione, fornendo flessibilità e opzioni di personalizzazione per soddisfare le tue esigenze.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DjvuImage](/imaging/python-net/aspose.imaging.fileformats.djvu/djvuimage/) | Documento djvu caricato |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_65}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 32 bit (per blocchi).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 64 bit per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_67}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carica pixel parzialmente per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Il caricatore di pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_68}


```
 load_pixels(rectangle) 
```

Carica pixel.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di pixel caricato. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_69}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Carica dati grezzi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i dati grezzi. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | I limiti dell'immagine di destinazione. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota che se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Il caricatore di dati grezzi. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_70}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Carica dati grezzi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi da utilizzare per i dati caricati. Nota che se i dati non sono nel formato specificato, verrà eseguita la conversione dei dati. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Il caricatore di dati grezzi. |

### Method: load_stream(stream)  [static] {#load_stream_stream_71}


```
 load_stream(stream) 
```

Carica una nuova immagine dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare l'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine caricata. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_72}


```
 load_stream_with_options(stream, load_options) 
```

Carica una nuova immagine dallo stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso da cui caricare l'immagine. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine caricata. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_73}


```
 load_with_options(file_path, load_options) 
```

Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file o l'URL da cui caricare l'immagine. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'immagine caricata. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_74}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_75}


```
 read_argb_32_scan_line(scan_line_index) 
```

Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int[] | L'array dei valori di colore ARGB a 32 bit della riga di scansione. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_76}


```
 read_scan_line(scan_line_index) 
```

Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array dei valori di colore dei pixel della riga di scansione. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_77}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| old_color_argb | int | Valore ARGB del colore vecchio da sostituire. |
| old_color_diff | System.Byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| new_color_argb | int | Nuovo valore ARGB del colore per sostituire il colore vecchio. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_78}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_79}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| old_color_argb | int | Valore ARGB del colore vecchio da sostituire. |
| old_color_diff | System.Byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| new_color_argb | int | Nuovo valore ARGB del colore per sostituire il colore vecchio. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_80}


```
 replace_non_transparent_colors(new_color) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_81}


```
 replace_non_transparent_colors(new_color_argb) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_argb | int | Nuovo valore ARGB del colore per sostituire i colori non trasparenti. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_82}


```
 resize(new_width, new_height) 
```

Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_83}


```
 resize(new_width, new_height, resize_type) 
```

Ridimensiona l'immagine usando il metodo `Resize`, fornendo un modo semplice ed efficace<br/> per regolare le dimensioni delle tue immagini secondo le tue esigenze. Questa funzionalità versatile ti permette di scalare facilmente le immagini alla dimensione desiderata,<br/> migliorandone l'usabilità su varie piattaforme e applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Il tipo di ridimensionamento. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_84}


```
 resize(new_width, new_height, settings) 
```

Ridimensiona l'immagine alla larghezza e altezza specificate applicando impostazioni aggiuntive<br/> secondo necessità. Questo metodo consente agli utenti di regolare le dimensioni dell'immagine mantenendo attributi desiderati come rapporto d'aspetto, qualità dell'immagine e impostazioni di compressione. Fornendo flessibilità nelle opzioni di ridimensionamento, gli utenti possono adattare l'immagine a requisiti specifici e ottimizzarne l'aspetto per varie applicazioni e piattaforme.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_85}


```
 resize_by_settings(new_width, new_height, settings) 
```

Ridimensiona l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_86}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Ridimensiona l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Il tipo di ridimensionamento. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_87}


```
 resize_height_proportionally(new_height) 
```

Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_88}


```
 resize_height_proportionally(new_height, resize_type) 
```

Il metodo `ResizeHeightProportionally` ti consente di regolare l'altezza della tua<br/> immagine mantenendo il suo rapporto d'aspetto. Questo garantisce che l'immagine mantenga le sue proporzioni, evitando distorsioni e preservando la sua integrità visiva.<br/> Che tu stia ottimizzando le immagini per pagine web, app mobili o stampa, questo metodo assicura che le tue immagini abbiano il miglior aspetto su diverse piattaforme e dispositivi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_89}


```
 resize_height_proportionally(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_90}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_91}


```
 resize_width_proportionally(new_width) 
```

Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_92}


```
 resize_width_proportionally(new_width, resize_type) 
```

Il metodo `ResizeWidthProportionally` offre una soluzione comoda per regolare la<br/> larghezza della tua immagine mantenendo il suo rapporto d'aspetto. Ridimensionando proporzionalmente la larghezza, puoi garantire che le tue immagini rimangano visivamente attraenti e<br/> coerenti su diversi dispositivi e dimensioni dello schermo, migliorandone la versatilità e l'usabilità in vari contesti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_93}


```
 resize_width_proportionally(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_94}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: rotate(angle) {#rotate_angle_95}


```
 rotate(angle) 
```

Ruota l'immagine attorno al centro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_96}


```
 rotate(angle, resize_proportionally, background_color) 
```

Ruota l'immagine attorno al suo centro con il metodo Rotate della classe<br/> RasterCachedMultipageImage. Questa funzione comoda ti permette di regolare facilmente l'orientamento delle immagini mantenendo la loro posizione centrale,<br/> migliorando le tue capacità di manipolazione delle immagini.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata<br/>            in base alle proiezioni del rettangolo ruotato (punti d'angolo) in altri<br/>            casi, lasciando le dimensioni inalterate e solo<br/>            i contenuti dell'immagine __internal__ verranno ruotati. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_97}


```
 rotate_flip(rotate_flip_type) 
```

Il metodo `RotateFlip` offre opzioni di manipolazione versatili per la tua immagine, consentendo<br/> di ruotare, capovolgere o eseguire entrambe le operazioni sul fotogramma attivo in modo indipendente.<br/> Che tu stia modificando foto, creando grafiche o migliorando l'arte digitale, questo metodo fornisce un controllo preciso sull'orientamento e la composizione delle tue immagini,<br/> assicurando che soddisfino la tua visione creativa con facilità ed efficienza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Il tipo di rotazione e capovolgimento. |


**See also:**

**[Example # 1](#example_147)**: This example loads a DJVU image, rotates it by 90 degrees clockwise and optio...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_98}


```
 rotate_flip_all(rotate_flip) 
```

Ruota il flip completo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | La rotazione e capovolgimento. |

### Method: save(file_path) {#save_file_path_99}


```
 save(file_path) 
```

Salva l'immagine nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare l'immagine. |

### Method: save(file_path, options) {#save_file_path_options_100}


```
 save(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_101}


```
 save(file_path, options, bounds_rectangle) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti della sorgente. |

### Method: save(file_path, over_write) {#save_file_path_over_write_102}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà effettuata un'aggiunta. |

### Method: save(stream) {#save_stream_103}


```
 save(stream) 
```

Salva i dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

### Method: save(stream, options_base) {#save_stream_options_base_104}


```
 save(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_105}


```
 save(stream, options_base, bounds_rectangle) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti della sorgente. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_106}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Salva i pixel ARGB a 32 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | L'array di pixel ARGB a 32 bit. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_107}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Salva i pixel.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_108}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | L'array di pixel CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_109}


```
 save_pixels(rectangle, pixels) 
```

Salva i pixel (metodo specifico del formato).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di pixel ARGB a 32 bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_110}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Salva i dati grezzi.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dati | System.Byte | I dati grezzi. |
| data_offset | int | L'offset iniziale dei dati grezzi. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Le impostazioni dei dati grezzi in cui si trovano i dati. |

### Method: save_to_stream(stream) {#save_to_stream_stream_111}


```
 save_to_stream(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_112}


```
 save_to_stream_with_options(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_113}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti della sorgente. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_114}


```
 save_with_options(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_115}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti della sorgente. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_116}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Imposta un pixel immagine a 32 bit ARGB per la posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| argb_32_color | int | Il pixel ARGB a 32 bit per la posizione specificata. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_117}


```
 set_palette(palette, update_colors) 
```

Imposta la tavolozza dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza da impostare. |
| update_colors | bool | se impostato su <c>true</c> i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine al caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_118}


```
 set_pixel(x, y, color) 
```

Imposta un pixel dell'immagine per la posizione specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | int | La posizione x del pixel. |
| y | int | La posizione y del pixel. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Il colore del pixel per la posizione specificata. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_119}


```
 set_resolution(dpi_x, dpi_y) 
```

Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dpi_x | float | La risoluzione orizzontale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La risoluzione verticale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_120}


```
 try_set_metadata(metadata) 
```

Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | I metadati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | True se _metadata_ non è null e l'istanza di [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            supporta e/o implementa l'istanza di [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/); altrimenti, false. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_121}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Scrive l'intera riga di scansione all'indice di riga di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |
| argb_32_pixels | int[] | L'array di colori ARGB a 32 bit da scrivere. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_122}


```
 write_scan_line(scan_line_index, pixels) 
```

Scrive l'intera riga di scansione all'indice di riga di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di colori dei pixel da scrivere. |

## **Examples**
### This example shows how to load a DJVU image from a file stream. {#example_145}
``` python
from os.path import join
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions       

dir_: str = "c:\\temp"
# Carica un'immagine DJVU da un flusso di file.
with open(join(dir_, "sample.djvu"), "rb") as stream:
	with DjvuImage(stream) as djvu_image:
		# Salva ogni pagina come immagine PNG individuale.
		for djvu_page in djvu_image.pages:
			# Genera un nome file basato sul numero di pagina.
			file_name: str = "sample.{0}.png".format(djvu_page.page_number)
			djvu_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DJVU image from a file stream to stay within the specified memory limit. {#example_146}
``` python
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging import LoadOptions
from os.path import join

dir_: str = "c:\\temp"
# Carica un'immagine DJVU da un flusso di file.
with open(join(dir_, "sample.djvu"), "rb") as stream:
	# La dimensione massima consentita per tutti i buffer interni è 1 MB.
	load_options = LoadOptions()
	load_options.buffer_size_hint = 1 * 1024 * 1024
	with DjvuImage(stream, load_options) as djvu_image:
		# Salva ogni pagina come immagine PNG individuale.
		for djvu_page in djvu_image.pages:
			# Genera un nome file basato sul numero di pagina.
			file_name: str = "sample.{0}.png".format(djvu_page.page_number)
			djvu_page.save(join(dir_, file_name), PngOptions())


```

### This example loads a DJVU image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_147}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Ruota, capovolgi e salva nel file di output.
	with aspycore.as_of(Image.load(join(dir_, "sample.djvu")), DjvuImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example crops a DJVU image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_149}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

with Image.load("sample.djvu") as image:
	djvuImage = as_of(image, DjvuImage)
	# Ritaglia l'immagine. L'area di ritaglio è l'area rettangolare centrale dell'immagine.
	area = Rectangle(djvuImage.width // 4, djvuImage.height // 4, djvuImage.width // 2, djvuImage.height // 2)
	djvuImage.crop(area)
	# Salva l'immagine ritagliata in PNG
	djvuImage.save("sample.Crop.png", PngOptions())


```

### The following example binarizes a DJVU image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_150}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Binarizza l'immagine con un valore di soglia di 127.
	# Se il valore di grigio corrispondente di un pixel è maggiore di 127, verrà assegnato il valore 255, altrimenti 0.
	djvu_image.binarize_fixed(127)
	djvu_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DJVU image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_152}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è una differenza tra un pixel e la media di una finestra di 10 x 10 pixel centrata su questo pixel.
	djvu_image.binarize_bradley(5, 10)
	djvu_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DJVU image. {#example_154}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Imposta il coefficiente gamma per i canali rosso, verde e blu.
	djvu_image.adjust_gamma(2.5)
	djvu_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DJVU image applying different coefficients for color components. {#example_155}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
	djvu_image.adjust_gamma(1.5, 2.5, 3.5)
	djvu_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DJVU image. {#example_156}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Imposta il valore di luminosità. I valori accettati di luminosità sono nell'intervallo [-255, 255].
	djvu_image.adjust_brightness(50)
	djvu_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DJVU image. {#example_157}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.djvu import DjvuImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.djvu")) as image:
	djvu_image = aspycore.as_of(image, DjvuImage)
	# Imposta il valore di contrasto. I valori accettati di contrasto sono nell'intervallo [-100f, 100f].
	djvu_image.adjust_contrast(50.0)
	djvu_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

