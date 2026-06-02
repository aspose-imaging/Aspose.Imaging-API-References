---
title: "Classe DicomImage"
type: docs
weight: 20
url: /it/python-net/aspose.imaging.fileformats.dicom/dicomimage/
---

**Summary:** This Class implements Digital Imaging and Communications in Medicine<br/>            (DICOM) raster image format support and offers a comprehensive solution for<br/>            processing DICOM images with precision and flexibility. You can seamlessly<br/>            manipulate image pages, including operations to get, add, or remove pages, and<br/>            control the default and active pages. With capabilities to work with alpha channels,<br/>            embed XMP metadata, resize, rotate, crop, binarize, adjust, apply filters,<br/>            and convert to other raster formats. This API empowers developers to handle<br/>            DICOM images effectively while meeting diverse application requirements in<br/>            medical imaging contexts.

**Module:** [aspose.imaging.fileformats.dicom](/imaging/python-net/aspose.imaging.fileformats.dicom/)

**Full Name:** aspose.imaging.fileformats.dicom.DicomImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [DicomImage(dicom_options, width, height)](#DicomImage_dicom_options_width_height_1) | Inizializza una nuova istanza della classe DicomImage senza sforzo con questo<br/>            costruttore, utilizzando i parametri dicomOptions. Perfetto per gli sviluppatori che desiderano<br/>            immergersi rapidamente ed efficientemente negli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nei loro progetti. |
| [DicomImage(stream)](#DicomImage_stream_2) | Crea una nuova istanza della classe DicomImage utilizzando un parametro stream<br/>            in questo costruttore. Perfetto per gli sviluppatori che cercano un modo semplificato per inizializzare<br/>            gli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) da flussi di dati esistenti nei loro progetti. |
| [DicomImage(stream, load_options)](#DicomImage_stream_load_options_3) | Inizia una nuova istanza della classe DicomImage in modo fluido impiegando un parametro stream e<br/>            i parametri loadOptions in questo costruttore. Ideale per gli sviluppatori desiderosi di iniziare<br/>            a lavorare con gli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) rapidamente ed efficacemente nei loro progetti. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| active_page | [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r/w | Gestisci la pagina attiva dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori<br/>            che desiderano passare dinamicamente tra le pagine di immagini multi-pagina, garantendo una navigazione<br/>            e un'elaborazione efficienti. |
| active_page_index | int | r | Recupera l'indice della pagina attiva senza sforzo con questa proprietà intuitiva.<br/>            Ideale per gli sviluppatori che cercano un accesso rapido all'indice della pagina corrente in immagini multi-pagina,<br/>            garantendo una navigazione e un'elaborazione efficienti. |
| auto_adjust_palette | bool | r/w | Ottiene o imposta un valore che indica se la palette viene regolata automaticamente. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Ottiene o imposta un valore per il colore di sfondo. |
| bits_per_pixel | int | r | Ottiene il conteggio dei bit per pixel dell'immagine. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ottiene i limiti dell'oggetto. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene il contenitore [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Ottiene lo stream di dati dell'oggetto. |
| dicom_pages | [DicomPage[]](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | r | Accedi alle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori<br/>            che desiderano interagire con le singole pagine all'interno dell'immagine, garantendo una navigazione e una manipolazione fluide. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta l'istanza Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Recupera il valore del formato file senza sforzo con questa proprietà intuitiva. Ideale per gli sviluppatori<br/>            che cercano un accesso rapido al formato del file immagine, garantendo una gestione e un'elaborazione efficienti in base al tipo di file. |
| file_info | [DicomImageInfo](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimageinfo/) | r | Recupera facilmente informazioni preziose dall'intestazione del file DICOM con questa<br/>            proprietà intuitiva. Ideale per gli sviluppatori che cercano un accesso rapido ai dettagli essenziali<br/>            contenuti nel file DICOM, garantendo un'estrazione e un'analisi dei dati efficienti. |
| has_alpha | bool | r | Recupera se l'immagine ha un canale alfa senza sforzo con questa proprietà intuitiva.<br/>            Ideale per gli sviluppatori che desiderano determinare se l'immagine contiene informazioni sulla trasparenza,<br/>            garantendo una gestione precisa dei dati del canale alfa nelle attività di elaborazione delle immagini. |
| has_background_color | bool | r/w | Ottiene o imposta un valore che indica se l'immagine ha un colore di sfondo. |
| has_transparent_color | bool | r/w | Ottiene un valore che indica se l'immagine ha un colore trasparente. |
| height | int | r | Ottiene l'altezza dell'immagine. |
| horizontal_resolution | float | r/w | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Ottiene l'opacità di questa immagine. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Ottiene o imposta il monitor di interruzione. |
| is_cached | bool | r | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| is_raw_data_available | bool | r | Ottiene un valore che indica se il caricamento dei dati grezzi è supportato. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Ottiene o imposta i dati XMP dal fotogramma. |
| page_count | int | r | Recupera il conteggio totale delle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori<br/>            che cercano un accesso rapido al numero di pagine all'interno di un'immagine, garantendo<br/>            una navigazione e una gestione efficienti. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Accedi alle pagine dell'immagine con questa proprietà intuitiva. Ideale per gli sviluppatori<br/>            che desiderano interagire con le singole pagine all'interno dell'immagine, garantendo una navigazione fluida<br/>            e una manipolazione. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| premultiply_components | bool | r/w | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
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
| [add_page()](#add_page__1) | Aggiungi una nuova pagina alla fine dell'elenco di pagine dell'immagine con questo metodo semplice.<br/>            Ideale per gli sviluppatori che desiderano espandere dinamicamente le immagini multi-pagina, garantendo un'integrazione fluida<br/>            e l'organizzazione del contenuto dell'immagine. |
| [add_page(page)](#add_page_page_2) | Espandi la tua collezione di immagini aggiungendo una nuova pagina con questo metodo intuitivo.<br/>            Ideale per gli sviluppatori che desiderano aggiungere dinamicamente pagine a immagini multi-pagina,<br/>            garantendo un'espansione fluida e l'organizzazione del contenuto dell'immagine. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Migliora la luminanza dell'immagine regolando la _luminosità_, un<br/>            metodo parametrizzato che consente agli sviluppatori di regolare finemente la luminosità delle immagini.<br/>            Questa funzione intuitiva permette agli sviluppatori di manipolare senza sforzo la<br/>            luminosità dell'immagine, offrendo flessibilità e controllo sull'estetica visiva. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Migliora il contrasto di [Image](/imaging/python-net/aspose.imaging/image/) con questo metodo intuitivo,<br/> che regola la differenza tra le aree chiare e scure. Migliora la chiarezza visiva e<br/> la definizione senza sforzo, fornendo agli sviluppatori un controllo intuitivo su<br/> il contrasto dell'immagine per una resa ottimale. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Migliora la qualità dell'immagine e regola con la correzione gamma, una tecnica potente<br/> per affinare l'aspetto visivo. Ideale per gli sviluppatori che desiderano ottimizzare la presentazione dell'immagine,<br/> regolare il bilanciamento dei colori e garantire una resa coerente su diversi<br/> dispositivi e ambienti. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Ottieni regolazioni di colore precise applicando la correzione gamma in modo indipendente<br/> ai componenti rosso, verde e blu di un'immagine. Questo metodo garantisce un bilanciamento dei colori accurato<br/> e un output visivo ottimale, soddisfacendo gli sviluppatori che cercano un controllo granulare<br/> sulla resa dell'immagine e sulla precisione dei colori. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| auto_brightness_contrast() | Esegue la normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine. |
| auto_rotate() | Ruota automaticamente l'immagine in base ai dati di orientamento estratti dai metadati Exif <br/>            . Questo metodo garantisce che le immagini vengano visualizzate nella corretta orientazione, <br/>            migliorando l'esperienza dell'utente ed eliminando la necessità di regolazioni manuali. Analizzando le informazioni Exif, l'immagine viene ruotata di conseguenza, fornendo un'esperienza di visualizzazione fluida <br/>            su diverse piattaforme e dispositivi. Questo processo di rotazione automatizzata <br/>            semplifica la gestione delle immagini e migliora l'usabilità complessiva, soprattutto quando <br/>            si lavora con grandi lotti di immagini con orientamenti variabili. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Binarizza le immagini con l'algoritmo di sogliatura adattiva di Bradley, sfruttando la sogliatura dell'immagine integrale per prestazioni migliorate. Ideale per gli sviluppatori che desiderano<br/>            segmentare automaticamente le immagini in base alle variazioni locali di luminosità, garantendo<br/>            un rilevamento e un'estrazione accurati degli oggetti in condizioni di illuminazione variabili. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Converti facilmente l'immagine in un formato binario usando una soglia predefinita<br/>            con questo metodo semplice. Ideale per gli sviluppatori che desiderano semplificare le attività di elaborazione delle immagini segmentando l'immagine in componenti di primo piano e sfondo<br/>            in base ai livelli di intensità specificati. |
| binarize_otsu() | Applica la sogliatura Otsu per binarizzare l'immagine, determinando automaticamente il valore di soglia ottimale<br/>            basato sull'istogramma dell'immagine. Perfetto per gli sviluppatori che cercano<br/>            un metodo affidabile per segmentare le immagini in regioni di primo piano e sfondo con<br/>            un intervento manuale minimo. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| cache_data() | Questo metodo memorizza i dati in cache in modo efficiente, ottimizzando le prestazioni e garantendo un accesso rapido<br/>            quando necessario. Ideale per gli sviluppatori che desiderano migliorare la velocità e l'efficienza delle loro<br/>            applicazioni gestendo in modo intelligente le risorse dei dati. |
| [can_load(file_path)](#can_load_file_path_13) | Determina se l'immagine può essere caricata dal percorso file specificato. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate. |
| [can_load(stream)](#can_load_stream_15) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Determina se l'immagine può essere caricata dallo stream specificato. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Determina se l'immagine può essere caricata dallo stream specificato e, opzionalmente, utilizzando le _loadOptions_ specificate. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Determina se l'immagine può essere caricata dal percorso file specificato e, opzionalmente, utilizzando le opzioni di apertura specificate. |
| [can_save(options)](#can_save_options_20) | Determina se l'immagine può essere salvata nel formato file specificato rappresentato dalle opzioni di salvataggio fornite. |
| [create(files)](#create_files_21) | Crea l'immagine multipagina contenente i file specificati. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Crea l'immagine multipagina contenente i file specificati. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Crea una nuova immagine utilizzando le opzioni di creazione specificate. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Crea un'istanza di [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) dall'array di pixel fornito.<br/>            <br/>            Convalida che la larghezza e l'altezza specificate corrispondano alle dimensioni dei dati pixel.<br/>            Questo metodo può essere usato solo quando la libreria è in modalità Licensed. |
| [create(images)](#create_images_25) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Crea le opzioni di creazione multipagina specificate. |
| [create_from_files(files)](#create_from_files_files_28) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_images(images)](#create_from_images_images_30) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Regola l'area di ritaglio dell'immagine applicando spostamenti con questo metodo versatile.<br/>            Perfetto per gli sviluppatori che necessitano di un controllo preciso sul processo di ritaglio, garantendo<br/>            che i dettagli importanti vengano conservati eliminando gli elementi superflui. |
| [crop(rectangle)](#crop_rectangle_33) | Ritaglia l'immagine per rimuovere le aree indesiderate e concentrarti sul contenuto essenziale con questo<br/>            metodo semplice. Ideale per gli sviluppatori che desiderano personalizzare la composizione visiva delle<br/>            immagini, assicurando che trasmettano il messaggio desiderato in modo efficace. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Esegue il dithering sull'immagine corrente. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Migliora l'immagine corrente applicando effetti di dithering con questo metodo diretto<br/>            . Perfetto per gli sviluppatori che vogliono aggiungere texture e profondità alle immagini,<br/>            migliorandone la qualità visiva e l'appeal complessivo. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Migliora senza sforzo aree specifiche della tua immagine applicando filtri a rettangoli designati<br/>            . Questo metodo offre agli sviluppatori un controllo preciso sulla<br/>            manipolazione dell'immagine, consentendo regolazioni mirate per ottenere gli effetti<br/>            visivi desiderati con facilità. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Ottiene l'array predefinito di pixel ARGB a 32 bit. |
| [get_default_options(args)](#get_default_options_args_40) | Ottiene le opzioni predefinite. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Ottiene l'array predefinito di dati grezzi. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Ottiene il formato del file. |
| [get_file_format(stream)](#get_file_format_stream_45) | Ottiene il formato del file. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Ottiene il formato del file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Ottiene la data e l'ora dell'ultima modifica dell'immagine di risorsa. |
| [get_original_options()](#get_original_options__50) | Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Ottiene un pixel dell'immagine. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Ottiene un'altezza proporzionale. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Ottiene una larghezza proporzionale. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Converte in aps. |
| [get_skew_angle()](#get_skew_angle__55) | Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| grayscale() | Trasforma facilmente le immagini nella loro rappresentazione in scala di grigi, semplificando l'analisi visiva<br/>            e le attività di elaborazione. Perfetto per gli sviluppatori che desiderano migliorare la chiarezza delle immagini,<br/>            ridurre la complessità e facilitare algoritmi efficienti basati sulla scala di grigi<br/>            per diverse applicazioni. |
| [insert_page(page_index)](#insert_page_page_index_56) | Inserisci una nuova pagina nell'elenco delle pagine dell'immagine a un indice specificato con questo metodo intuitivo<br/>            . Ideale per gli sviluppatori che cercano un controllo preciso sulla disposizione delle pagine in<br/>            immagini multi-pagina, garantendo un'organizzazione fluida e la personalizzazione del contenuto dell'immagine. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Esegue un rapido controllo per determinare se l'immagine è firmata digitalmente, utilizzando la password e la soglia fornite. |
| [load(file_path)](#load_file_path_58) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(stream)](#load_stream_60) | Carica una nuova immagine dallo stream specificato. |
| [load(stream, load_options)](#load_stream_load_options_61) | Carica una nuova immagine dallo stream specificato. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | Carica pixel ARGB a 32 bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | Carica pixel ARGB a 64 bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | Carica pixel in formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | Carica pixel in formato CMYK.<br/>            Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | Carica parzialmente pixel ARGB a 32 bit (per blocchi). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | Carica parzialmente pixel ARGB a 64 bit per pacchetti. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Carica pixel parzialmente per pacchetti. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Carica pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Carica dati grezzi. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Carica dati grezzi. |
| [load_stream(stream)](#load_stream_stream_72) | Carica una nuova immagine dallo stream specificato. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Carica una nuova immagine dallo stream specificato. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| normalize_angle() | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normalizza l'istogramma dell'immagine — regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| remove_metadata() | Rimuove i metadati di questa istanza immagine impostando il valore di [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [remove_page(page_index)](#remove_page_page_index_78) | Elimina la pagina all'indice specificato dall'elenco delle pagine con questo metodo comodo.<br/>            Ideale per gli sviluppatori che cercano un controllo preciso sulla gestione delle immagini multi-pagina,<br/>            garantendo un'organizzazione fluida e la personalizzazione del contenuto dell'immagine. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Ridimensiona l'immagine mantenendo il suo rapporto d'aspetto con questo metodo comodo. Ideale<br/>            per gli sviluppatori che desiderano regolare le dimensioni dell'immagine proporzionalmente, garantendo<br/>            coerenza e preservando le proporzioni del contenuto originale.<br/>            Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto _newWidth_/width e _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Regola le dimensioni della tua immagine con questo semplice metodo di ridimensionamento. Che tu debba<br/>            ridurre o ingrandire la tua immagine, questa funzione garantisce che le tue esigenze di ridimensionamento siano soddisfatte<br/>            in modo efficiente e preciso, rendendola perfetta per gli sviluppatori che cercano regolazioni rapide e facili<br/>            delle dimensioni dell'immagine. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Ridimensiona l'immagine. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Ridimensiona l'immagine. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Regola l'altezza dell'immagine mantenendo il suo rapporto d'aspetto con questo<br/>            metodo intuitivo. Perfetto per gli sviluppatori che desiderano ridimensionare dinamicamente le immagini<br/>            preservandone le proporzioni, garantendo una visualizzazione ottimale e usabilità<br/>            nelle loro applicazioni. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Ridimensiona l'altezza proporzionalmente. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_93) | Ridimensiona l'immagine mantenendo il suo rapporto d'aspetto con questo metodo comodo. Ideale<br/>            per gli sviluppatori che desiderano regolare le dimensioni dell'immagine proporzionalmente, garantendo<br/>            coerenza e preservando le proporzioni del contenuto originale.<br/>            Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto _newWidth_/width e _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Regola la larghezza dell'immagine mantenendo il suo rapporto d'aspetto con questo pratico<br/>            metodo. Ideale per gli sviluppatori che desiderano ridimensionare le immagini proporzionalmente, garantendo<br/>            risultati coerenti e visivamente gradevoli su diversi ambienti di visualizzazione. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Ridimensiona la larghezza proporzionalmente. |
| [rotate(angle)](#rotate_angle_98) | Ruota l'immagine attorno al centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Ruota l'immagine attorno al suo centro con questo metodo pratico. Ideale per gli sviluppatori<br/>            che desiderano regolare l'orientamento dell'immagine dinamicamente, garantendo una presentazione ottimale e<br/>            allineamento all'interno delle loro applicazioni. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Manipola facilmente il fotogramma attivo ruotando, capovolgendo o eseguendo entrambe le azioni<br/>            simultaneamente con questo metodo semplice. Ideale per gli sviluppatori che devono<br/>            regolare dinamicamente l'orientamento di fotogrammi specifici all'interno delle loro sequenze di immagini,<br/>            garantendo una presentazione e un allineamento ottimali. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_101) | Ruota il flip completo. |
| save() | Salva i dati dell'immagine nello stream sottostante. |
| [save(file_path)](#save_file_path_102) | Salva l'immagine nella posizione file specificata. |
| [save(file_path, options)](#save_file_path_options_103) | Conserva i dati dell'oggetto salvandoli nel file designato (indice + nome file)<br/>            nella posizione indicata insieme al formato file e alle opzioni specificate. Ideale per gli sviluppatori che desiderano<br/>            archiviare in modo sicuro i dati in vari formati mantenendo flessibilità e controllo sui<br/>            parametri di salvataggio. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_104) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, over_write)](#save_file_path_over_write_105) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_106) | Salva i dati. |
| [save(stream, options_base)](#save_stream_options_base_107) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_108) | Salva facilmente i dati della tua immagine in uno stream specificato nel formato file desiderato<br/>            utilizzando questo metodo pratico. Che tu stia lavorando con JPEG, PNG o un altro formato,<br/>            questa funzione garantisce che i dati dell'immagine vengano salvati in modo efficiente e preciso,<br/>            rendendola ideale per gli sviluppatori che desiderano semplificare i loro processi di salvataggio dei file. |
| [save_all(file_path, options)](#save_all_file_path_options_109) | Conserva i dati dell'oggetto salvandoli nel file designato (indice + nome file)<br/>            nella posizione indicata insieme al formato file e alle opzioni specificate. Ideale per gli sviluppatori che desiderano<br/>            archiviare in modo sicuro i dati in vari formati mantenendo flessibilità e controllo sui<br/>            parametri di salvataggio. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Salva i pixel ARGB a 32 bit. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Salva i pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Salva i pixel (metodo specifico del formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Salva i dati grezzi. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Salva i dati dell'oggetto nello stream specificato. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Imposta un pixel immagine a 32 bit ARGB per la posizione specificata. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_121) | Imposta la tavolozza dell'immagine. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_122) | Imposta un pixel dell'immagine per la posizione specificata. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Regola la risoluzione di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) con precisione utilizzando questo<br/>            metodo semplice. Ideale per gli sviluppatori che desiderano personalizzare la risoluzione dell'immagine per<br/>            requisiti specifici, garantendo una qualità di visualizzazione ottimale e una gestione della dimensione del file. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |


### Constructor: DicomImage(dicom_options, width, height) {#DicomImage_dicom_options_width_height_1}


```
 DicomImage(dicom_options, width, height) 
```

Inizializza una nuova istanza della classe DicomImage senza sforzo con questo<br/>            costruttore, utilizzando i parametri dicomOptions. Perfetto per gli sviluppatori che desiderano<br/>            immergersi rapidamente ed efficientemente negli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) nei loro progetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dicom_options | [DicomOptions](/imaging/python-net/aspose.imaging.imageoptions/dicomoptions/) | Le opzioni DICOM. |
| width | int | La larghezza. |
| height | int | L'altezza. |

### Constructor: DicomImage(stream) {#DicomImage_stream_2}


```
 DicomImage(stream) 
```

Crea una nuova istanza della classe DicomImage utilizzando un parametro stream<br/>            in questo costruttore. Perfetto per gli sviluppatori che cercano un modo semplificato per inizializzare<br/>            gli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) da flussi di dati esistenti nei loro progetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |


**See also:**

**[Example # 1](#example_130)**: This example shows how to load a DICOM image from a file stream.


### Constructor: DicomImage(stream, load_options) {#DicomImage_stream_load_options_3}


```
 DicomImage(stream, load_options) 
```

Inizia una nuova istanza della classe DicomImage in modo fluido impiegando un parametro stream e<br/>            i parametri loadOptions in questo costruttore. Ideale per gli sviluppatori desiderosi di iniziare<br/>            a lavorare con gli oggetti [DicomImage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicomimage/) rapidamente ed efficacemente nei loro progetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Le opzioni di caricamento. |


**See also:**

**[Example # 1](#example_131)**: This example shows how to load a DICOM image from a file stream to stay withi...


### Method: add_page() {#add_page__1}


```
 add_page() 
```

Aggiungi una nuova pagina alla fine dell'elenco di pagine dell'immagine con questo metodo semplice.<br/>            Ideale per gli sviluppatori che desiderano espandere dinamicamente le immagini multi-pagina, garantendo un'integrazione fluida<br/>            e l'organizzazione del contenuto dell'immagine.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | La nuova [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) creata. |


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Espandi la tua collezione di immagini aggiungendo una nuova pagina con questo metodo intuitivo.<br/>            Ideale per gli sviluppatori che desiderano aggiungere dinamicamente pagine a immagini multi-pagina,<br/>            garantendo un'espansione fluida e l'organizzazione del contenuto dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La pagina da aggiungere. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Migliora la luminanza dell'immagine regolando la _luminosità_, un<br/>            metodo parametrizzato che consente agli sviluppatori di regolare finemente la luminosità delle immagini.<br/>            Questa funzione intuitiva permette agli sviluppatori di manipolare senza sforzo la<br/>            luminosità dell'immagine, offrendo flessibilità e controllo sull'estetica visiva.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| luminosità | int | Valore di luminosità. |


**See also:**

**[Example # 1](#example_143)**: The following example performs brightness correction of a DICOM image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Migliora il contrasto di [Image](/imaging/python-net/aspose.imaging/image/) con questo metodo intuitivo,<br/> che regola la differenza tra le aree chiare e scure. Migliora la chiarezza visiva e<br/> la definizione senza sforzo, fornendo agli sviluppatori un controllo intuitivo su<br/> il contrasto dell'immagine per una resa ottimale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| contrasto | float | Valore di contrasto (nell'intervallo [-100; 100]) |


**See also:**

**[Example # 1](#example_144)**: The following example performs contrast correction of a DICOM image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Migliora la qualità dell'immagine e regola con la correzione gamma, una tecnica potente<br/> per affinare l'aspetto visivo. Ideale per gli sviluppatori che desiderano ottimizzare la presentazione dell'immagine,<br/> regolare il bilanciamento dei colori e garantire una resa coerente su diversi<br/> dispositivi e ambienti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |


**See also:**

**[Example # 1](#example_141)**: The following example performs gamma-correction of a DICOM image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Ottieni regolazioni di colore precise applicando la correzione gamma in modo indipendente<br/> ai componenti rosso, verde e blu di un'immagine. Questo metodo garantisce un bilanciamento dei colori accurato<br/> e un output visivo ottimale, soddisfacendo gli sviluppatori che cercano un controllo granulare<br/> sulla resa dell'immagine e sulla precisione dei colori.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma_red | float | Coefficiente gamma per il canale rosso |
| gamma_green | float | Coefficiente gamma per il canale verde |
| gamma_blue | float | Gamma per il coefficiente del canale blu |


**See also:**

**[Example # 1](#example_142)**: The following example performs gamma-correction of a DICOM image applying dif...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra di pixel s x s<br/>                centrata attorno a questo pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarizza le immagini con l'algoritmo di sogliatura adattiva di Bradley, sfruttando la sogliatura dell'immagine integrale per prestazioni migliorate. Ideale per gli sviluppatori che desiderano<br/>            segmentare automaticamente le immagini in base alle variazioni locali di luminosità, garantendo<br/>            un rilevamento e un'estrazione accurati degli oggetti in condizioni di illuminazione variabili.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra di pixel s x s<br/>            centrata attorno a questo pixel. |
| window_size | int | La dimensione della finestra di pixel s x s centrata attorno a questo pixel |


**See also:**

**[Example # 1](#example_139)**: The following example binarizes a DICOM image with Bradley's adaptive thresho...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Converti facilmente l'immagine in un formato binario usando una soglia predefinita<br/>            con questo metodo semplice. Ideale per gli sviluppatori che desiderano semplificare le attività di elaborazione delle immagini segmentando l'immagine in componenti di primo piano e sfondo<br/>            in base ai livelli di intensità specificati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| soglia | System.Byte | Valore di soglia. Se il valore grigio corrispondente di un pixel è maggiore della soglia, verrà assegnato a esso un valore di<br/>            255, altrimenti 0. |


**See also:**

**[Example # 1](#example_137)**: The following example binarizes a DICOM image with the predefined threshold. ...


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Regola l'area di ritaglio dell'immagine applicando spostamenti con questo metodo versatile.<br/>            Perfetto per gli sviluppatori che necessitano di un controllo preciso sul processo di ritaglio, garantendo<br/>            che i dettagli importanti vengano conservati eliminando gli elementi superflui.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left_shift | int | Lo shift a sinistra. |
| right_shift | int | Lo shift a destra. |
| top_shift | int | Lo shift superiore. |
| bottom_shift | int | Lo shift inferiore. |


**See also:**

**[Example # 1](#example_136)**: The following example crops a DICOM image. The cropping area is specified via...


### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Ritaglia l'immagine per rimuovere le aree indesiderate e concentrarti sul contenuto essenziale con questo<br/>            metodo semplice. Ideale per gli sviluppatori che desiderano personalizzare la composizione visiva delle<br/>            immagini, assicurando che trasmettano il messaggio desiderato in modo efficace.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |


**See also:**

**[Example # 1](#example_135)**: The following example crops a DICOM image. The cropping area is be specified ...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Esegue il dithering sull'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Migliora l'immagine corrente applicando effetti di dithering con questo metodo diretto<br/>            . Perfetto per gli sviluppatori che vogliono aggiungere texture e profondità alle immagini,<br/>            migliorandone la qualità visiva e l'appeal complessivo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personalizzata per il dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Incorpora la firma digitale basata sulla password fornita in ogni pagina dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password usata per generare i dati della firma digitale. |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Migliora senza sforzo aree specifiche della tua immagine applicando filtri a rettangoli designati<br/>            . Questo metodo offre agli sviluppatori un controllo preciso sulla<br/>            manipolazione dell'immagine, consentendo regolazioni mirate per ottenere gli effetti<br/>            visivi desiderati con facilità.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Le opzioni. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni basate sulle impostazioni del file originale. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'angolo di inclinazione, in gradi. |


### Method: insert_page(page_index) {#insert_page_page_index_56}


```
 insert_page(page_index) 
```

Inserisci una nuova pagina nell'elenco delle pagine dell'immagine a un indice specificato con questo metodo intuitivo<br/>            . Ideale per gli sviluppatori che cercano un controllo preciso sulla disposizione delle pagine in<br/>            immagini multi-pagina, garantendo un'organizzazione fluida e la personalizzazione del contenuto dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_index | int | Indice della pagina. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) | La nuova [DicomPage](/imaging/python-net/aspose.imaging.fileformats.dicom/dicompage/) creata. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


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


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


```
 load(stream) 
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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


```
 load(stream, load_options) 
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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 32 bit (per blocchi).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 64 bit per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carica pixel parzialmente per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Il caricatore di pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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


### Method: remove_page(page_index) {#remove_page_page_index_78}


```
 remove_page(page_index) 
```

Elimina la pagina all'indice specificato dall'elenco delle pagine con questo metodo comodo.<br/>            Ideale per gli sviluppatori che cercano un controllo preciso sulla gestione delle immagini multi-pagina,<br/>            garantendo un'organizzazione fluida e la personalizzazione del contenuto dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| page_index | int | Indice della pagina. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>                Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_argb | int | Nuovo valore ARGB del colore per sostituire i colori non trasparenti. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

Ridimensiona l'immagine mantenendo il suo rapporto d'aspetto con questo metodo comodo. Ideale<br/>            per gli sviluppatori che desiderano regolare le dimensioni dell'immagine proporzionalmente, garantendo<br/>            coerenza e preservando le proporzioni del contenuto originale.<br/>            Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto _newWidth_/width e _newHeight_/height.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Il tipo di ridimensionamento. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Regola le dimensioni della tua immagine con questo semplice metodo di ridimensionamento. Che tu debba<br/>            ridurre o ingrandire la tua immagine, questa funzione garantisce che le tue esigenze di ridimensionamento siano soddisfatte<br/>            in modo efficiente e preciso, rendendola perfetta per gli sviluppatori che cercano regolazioni rapide e facili<br/>            delle dimensioni dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Regola l'altezza dell'immagine mantenendo il suo rapporto d'aspetto con questo<br/>            metodo intuitivo. Perfetto per gli sviluppatori che desiderano ridimensionare dinamicamente le immagini<br/>            preservandone le proporzioni, garantendo una visualizzazione ottimale e usabilità<br/>            nelle loro applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_93}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Ridimensiona l'immagine mantenendo il suo rapporto d'aspetto con questo metodo comodo. Ideale<br/>            per gli sviluppatori che desiderano regolare le dimensioni dell'immagine proporzionalmente, garantendo<br/>            coerenza e preservando le proporzioni del contenuto originale.<br/>            Il ridimensionamento proporzionale ridimensionerà ogni fotogramma secondo il rapporto _newWidth_/width e _newHeight_/height.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Il tipo di ridimensionamento. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Regola la larghezza dell'immagine mantenendo il suo rapporto d'aspetto con questo pratico<br/>            metodo. Ideale per gli sviluppatori che desiderano ridimensionare le immagini proporzionalmente, garantendo<br/>            risultati coerenti e visivamente gradevoli su diversi ambienti di visualizzazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Ruota l'immagine attorno al centro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

Ruota l'immagine attorno al suo centro con questo metodo pratico. Ideale per gli sviluppatori<br/>            che desiderano regolare l'orientamento dell'immagine dinamicamente, garantendo una presentazione ottimale e<br/>            allineamento all'interno delle loro applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata<br/>            in base alle proiezioni del rettangolo ruotato (punti d'angolo) in altri<br/>            casi, lasciando le dimensioni inalterate e solo<br/>            i contenuti dell'immagine __internal__ verranno ruotati. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Manipola facilmente il fotogramma attivo ruotando, capovolgendo o eseguendo entrambe le azioni<br/>            simultaneamente con questo metodo semplice. Ideale per gli sviluppatori che devono<br/>            regolare dinamicamente l'orientamento di fotogrammi specifici all'interno delle loro sequenze di immagini,<br/>            garantendo una presentazione e un allineamento ottimali.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Il tipo di rotazione e capovolgimento. |


**See also:**

**[Example # 1](#example_132)**: This example loads a DICOM image, rotates it by 90 degrees clockwise and opti...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_101}


```
 rotate_flip_all(rotate_flip) 
```

Ruota il flip completo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | La rotazione e capovolgimento. |

### Method: save(file_path) {#save_file_path_102}


```
 save(file_path) 
```

Salva l'immagine nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare l'immagine. |

### Method: save(file_path, options) {#save_file_path_options_103}


```
 save(file_path, options) 
```

Conserva i dati dell'oggetto salvandoli nel file designato (indice + nome file)<br/>            nella posizione indicata insieme al formato file e alle opzioni specificate. Ideale per gli sviluppatori che desiderano<br/>            archiviare in modo sicuro i dati in vari formati mantenendo flessibilità e controllo sui<br/>            parametri di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_104}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_105}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà effettuata un'aggiunta. |

### Method: save(stream) {#save_stream_106}


```
 save(stream) 
```

Salva i dati.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati. |

### Method: save(stream, options_base) {#save_stream_options_base_107}


```
 save(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_108}


```
 save(stream, options_base, bounds_rectangle) 
```

Salva facilmente i dati della tua immagine in uno stream specificato nel formato file desiderato<br/>            utilizzando questo metodo pratico. Che tu stia lavorando con JPEG, PNG o un altro formato,<br/>            questa funzione garantisce che i dati dell'immagine vengano salvati in modo efficiente e preciso,<br/>            rendendola ideale per gli sviluppatori che desiderano semplificare i loro processi di salvataggio dei file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo dei limiti dell'immagine di destinazione. Imposta il rettangolo vuoto per utilizzare i limiti della sorgente. |


**See also:**

**[Example # 1](#example_133)**: The following example loads a DICOM image from a file, then saves the image t...


### Method: save_all(file_path, options) {#save_all_file_path_options_109}


```
 save_all(file_path, options) 
```

Conserva i dati dell'oggetto salvandoli nel file designato (indice + nome file)<br/>            nella posizione indicata insieme al formato file e alle opzioni specificate. Ideale per gli sviluppatori che desiderano<br/>            archiviare in modo sicuro i dati in vari formati mantenendo flessibilità e controllo sui<br/>            parametri di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Salva i pixel ARGB a 32 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | L'array di pixel ARGB a 32 bit. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Salva i pixel.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | L'array di pixel CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Salva i pixel (metodo specifico del formato).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di pixel. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_121}


```
 set_palette(palette, update_colors) 
```

Imposta la tavolozza dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza da impostare. |
| update_colors | bool | se impostato su <c>true</c> i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine al caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_122}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_123}


```
 set_resolution(dpi_x, dpi_y) 
```

Regola la risoluzione di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) con precisione utilizzando questo<br/>            metodo semplice. Ideale per gli sviluppatori che desiderano personalizzare la risoluzione dell'immagine per<br/>            requisiti specifici, garantendo una qualità di visualizzazione ottimale e una gestione della dimensione del file.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dpi_x | float | La risoluzione orizzontale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La risoluzione verticale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_124}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Scrive l'intera riga di scansione all'indice di riga di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |
| argb_32_pixels | int[] | L'array di colori ARGB a 32 bit da scrivere. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_126}


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
### This example shows how to load a DICOM image from a file stream. {#example_130}
``` python
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Carica un'immagine DICOM da un flusso di file.
with open(join(dir_, "sample.dicom"), "rb") as stream:
	with DicomImage(stream) as dicom_image:
		# Salva ogni pagina come immagine PNG individuale.
		for dicom_page in dicom_image.dicom_pages:
			# Genera un nome file basato sull'indice della pagina.
			file_name = "sample.{0}.png".format(dicom_page.index)
			# Una pagina DICOM è un'immagine raster, quindi tutte le operazioni consentite su un'immagine raster sono applicabili a una pagina DICOM.
			dicom_page.save(join(dir_, file_name), PngOptions())


```

### This example shows how to load a DICOM image from a file stream to stay within the specified memory limit. {#example_131}
``` python
from aspose.imaging import LoadOptions, Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join as path_join


dir_: str = "c:\\temp"
# Carica un'immagine DICOM da un flusso di file.
with open(path_join(dir_, "multiframe.dicom"), "rb") as stream:
	# La dimensione massima consentita per tutti i buffer interni è 256KB.
	load_options = LoadOptions()
	load_options.buffer_size_hint = 256 * 1024
	with DicomImage(stream, load_options) as dicom_image:
		# Salva ogni pagina come immagine PNG individuale.
		for dicom_page in dicom_image.dicom_pages:
			# Genera un nome file basato sull'indice della pagina.
			file_name = "multiframe.{0}.png".format(dicom_page.index)
			# Una pagina DICOM è un'immagine raster, quindi tutte le operazioni consentite su un'immagine raster sono applicabili a una pagina DICOM.
			dicom_page.save(path_join(dir_, file_name), PngOptions())


```

### This example loads a DICOM image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_132}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Ruota, capovolgi e salva nel file di output.
	with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a DICOM image from a file, then saves the image to a PNG file stream. {#example_133}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions     

dir_: str = "c:\\temp"
with aspycore.as_of(Image.load(join(dir_, "sample.dicom")), DicomImage) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width // 2, image.height // 2)
	with open(join(dir_, "output.png"), "wb") as output_stream:
		# Salva il quarto in alto a sinistra dell'immagine in un flusso di file.
		image.save(output_stream, save_options, bounds)


```

### The following example crops a DICOM image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_135}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions    


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Ritaglia l'immagine. L'area di ritaglio è l'area rettangolare centrale dell'immagine.
	area = Rectangle(dicom_image.width // 4, dicom_image.height // 4, dicom_image.width // 2, dicom_image.height // 2)
	dicom_image.crop(area)
	# Salva l'immagine ritagliata in PNG
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a DICOM image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_136}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Ritaglia nuovamente. Imposta un margine del 10% della dimensione dell'immagine.
	horizontal_margin = dicom_image.width // 10
	vertical_margin = dicom_image.height // 10
	dicom_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Salva l'immagine ritagliata in PNG.
	dicom_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a DICOM image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_137}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.dicom import DicomImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Binarizza l'immagine con un valore di soglia di 127.
	# Se il valore di grigio corrispondente di un pixel è maggiore di 127, verrà assegnato il valore 255, altrimenti 0.
	dicom_image.binarize_fixed(127)
	dicom_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a DICOM image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_139}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Binarizza l'immagine con una differenza di luminosità di 5. La luminosità è una differenza tra un pixel e la media di una finestra di 10 x 10 pixel centrata su questo pixel.
	dicom_image.binarize_bradley(5, 10)
	dicom_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image. {#example_141}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join


dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Imposta il coefficiente gamma per i canali rosso, verde e blu.
	dicom_image.adjust_gamma(2.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a DICOM image applying different coefficients for color components. {#example_142}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Imposta i coefficienti gamma individuali per i canali rosso, verde e blu.
	dicom_image.adjust_gamma(1.5, 2.5, 3.5)
	dicom_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a DICOM image. {#example_143}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Imposta il valore di luminosità. I valori accettati di luminosità sono nell'intervallo [-255, 255].
	dicom_image.adjust_brightness(50)
	dicom_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a DICOM image. {#example_144}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import DicomImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.dicom")) as image:
	dicom_image = aspycore.as_of(image, DicomImage)
	# Imposta il valore di contrasto. I valori accettati di contrasto sono nell'intervallo [-100f, 100f].
	dicom_image.adjust_contrast(50.0)
	dicom_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Use JPEG compression in DICOM image. {#example_211}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions, DicomOptions
from aspose.imaging.fileformats.jpeg import JpegCompressionMode, SampleRoundingMode
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import Compression, ColorType, CompressionType

with Image.load("original.jpg") as input_image:
	obj_init = JpegOptions()
	obj_init.compression_type = JpegCompressionMode.BASELINE
	obj_init.sample_rounding_mode = SampleRoundingMode.TRUNCATE
	obj_init.quality = 50
	obj_init2 = Compression()
	obj_init2.type = CompressionType.JPEG
	obj_init2.jpeg = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG.dcm", options)


```

### Use JPEG 2000 compression in DICOM image. {#example_212}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.imageoptions import Jpeg2000Options, DicomOptions
from aspose.imaging.fileformats.jpeg2000 import Jpeg2000Codec, Compression, CompressionType, ColorType

with Image.load("original.jpg") as input_image:
	obj_init = Jpeg2000Options()
	obj_init.codec = Jpeg2000Codec.JP2
	obj_init.irreversible = False
	obj_init2 = Compression()
	obj_init2.type_ = CompressionType.JPEG2000
	obj_init2.jpeg2000 = obj_init
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = obj_init2
	input_image.save("original_JPEG2000.dcm", options)


```

### Use RLE compression in DICOM image. {#example_213}
``` python

from aspose.imaging import Image
from aspose.imaging.fileformats.dicom import Compression, CompressionType, ColorType
from aspose.imaging.imageoptions import DicomOptions

with Image.load("original.jpg") as input_image:
	compr = Compression()
	compr.type_ = CompressionType.RLE
	options = DicomOptions()
	options.color_type = ColorType.RGB_24_BIT
	options.compression = compr
	input_image.save("original_RLE.dcm", options)


```

### Change the color type in DICOM compression. {#example_214}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import DicomOptions
from aspose.imaging.fileformats.dicom import ColorType

with Image.load("original.jpg") as inputImage:
	options = DicomOptions()
	options.color_type = ColorType.GRAYSCALE_8_BIT
	inputImage.save("original_8Bit.dcm", options)


```

