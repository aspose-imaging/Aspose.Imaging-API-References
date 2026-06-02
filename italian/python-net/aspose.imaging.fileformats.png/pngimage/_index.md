---
title: "Classe PngImage"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.png/pngimage/
---

**Summary:** Manipulate Portable Network Graphics (PNG) raster images with our versatile API,<br/>            featuring support for compression levels and various color depths including<br/>            Grayscale, Indexed Color, TrueColor, and alpha channels. Seamlessly process XMP metadata,<br/>            enabling comprehensive image metadata management, while easily loading PNG images,<br/>            performing diverse manipulations, applying filters, and converting images to other file<br/>            formats for optimal versatility and customization.

**Module:** [aspose.imaging.fileformats.png](/imaging/python-net/aspose.imaging.fileformats.png/)

**Full Name:** aspose.imaging.fileformats.png.PngImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [PngImage(path)](#PngImage_path_1) | Costruisce una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) utilizzando il parametro path <br/>            per specificare la posizione del file immagine da caricare. Questo costruttore <br/>            consente agli sviluppatori di creare comodamente immagini PNG caricandole da un file, <br/>            semplificando il processo di utilizzo delle immagini PNG nelle loro applicazioni. |
| [PngImage(path, color_type)](#PngImage_path_color_type_2) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) specificando il <br/>            percorso del file immagine e il tipo di colore. Questo costruttore consente una creazione comoda <br/>            di immagini PNG da file con diversi tipi di colore, offrendo <br/>            flessibilità nella gestione di vari formati di immagine. |
| [PngImage(png_options, width, height)](#PngImage_png_options_width_height_3) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/), incorporando <br/>            opzioni PNG insieme ai parametri di larghezza e altezza. Questo costruttore consente <br/>            agli sviluppatori di creare immagini PNG con impostazioni e dimensioni personalizzabili, <br/>            offrendo flessibilità nella generazione di immagini per diversi casi d'uso. |
| [PngImage(raster_image)](#PngImage_raster_image_4) | Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fornendo un'immagine raster <br/>            come parametro. Questo costruttore consente agli sviluppatori di inizializzare direttamente un <br/>            oggetto immagine PNG utilizzando un'immagine raster esistente, semplificando il processo di <br/>            utilizzo delle immagini PNG nelle loro applicazioni. |
| [PngImage(raster_image, color_type)](#PngImage_raster_image_color_type_5) | Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) specificando un <br/>            immagine raster e un tipo di colore. Questo costruttore permette agli sviluppatori di convertire direttamente <br/>            le immagini raster in formato PNG specificando il tipo di colore desiderato, <br/>            offrendo flessibilità nella rappresentazione dei colori. |
| [PngImage(stream)](#PngImage_stream_6) | Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) inizializzandola <br/>            con uno stream. Questo costruttore consente agli sviluppatori di caricare immagini PNG direttamente <br/>            da uno stream, fornendo flessibilità nel recupero delle immagini da diverse fonti. |
| [PngImage(width, height)](#PngImage_width_height_7) | Inizializza un nuovo oggetto della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fornendo i parametri di <br/>            larghezza e altezza. Questo costruttore semplifica la creazione di immagini PNG <br/>            consentendo agli sviluppatori di specificare direttamente le dimensioni, facilitando <br/>            una gestione efficiente dei dati delle immagini PNG nelle loro applicazioni. |
| [PngImage(width, height, color_type)](#PngImage_width_height_color_type_8) | Istanzia una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/), specificando <br/>            i parametri di larghezza, altezza e tipo di colore desiderati. Questo costruttore consente <br/>            una rapida creazione di immagini PNG con dimensioni e configurazioni di colore su misura, <br/>            facilitando una generazione di immagini ottimizzata per varie applicazioni e flussi di lavoro. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Ottiene o imposta un valore che indica se la palette viene regolata automaticamente. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Recupera il colore di sfondo dell'immagine, se specificato. Questa proprietà <br/>            è utile per le applicazioni che devono identificare e potenzialmente manipolare <br/>            il colore di sfondo di un'immagine. |
| bits_per_pixel | int | r | Recupera il valore dei bit per pixel dell'immagine. Questa proprietà fornisce informazioni cruciali <br/>            sulla profondità di colore dell'immagine, consentendo agli sviluppatori di <br/>            comprendere il livello di dettaglio e la precisione del colore presenti nei dati dell'immagine. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ottiene i limiti dell'oggetto. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene il contenitore [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Ottiene lo stream di dati dell'oggetto. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta l'istanza Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Recupera il formato del file associato all'istanza dell'immagine. Questa <br/>            proprietà fornisce informazioni essenziali sul tipo di file, consentendo <br/>            una gestione e un'elaborazione efficienti in base ai requisiti specifici del formato. |
| [has_alpha](#has_alpha1) | bool | r | Restituisce un valore booleano che indica se l'immagine ha un canale alfa, <br/>            che ne determina la trasparenza. Questa proprietà è utile per le applicazioni <br/>            che devono gestire la trasparenza, consentendo agli sviluppatori di determinare se <br/>            è necessario un ulteriore processamento per gestire le aree trasparenti dell'immagine. |
| has_background_color | bool | r/w | Recupera un valore booleano che indica se l'immagine ha un colore di sfondo. <br/>            Questa proprietà è utile per le applicazioni che devono determinare se un'immagine <br/>            include un colore di sfondo, il che può essere importante per vari compiti di elaborazione <br/>            come compositing, rendering o esportazione. |
| has_transparent_color | bool | r/w | Fornisce un valore booleano che indica se l'immagine contiene un colore trasparente <br/>            . Questa proprietà è fondamentale per le applicazioni che devono gestire <br/>            la trasparenza, consentendo agli sviluppatori di determinare se è necessario un ulteriore <br/>            processamento per gestire le regioni trasparenti dell'immagine. |
| height | int | r | Ottieni l'altezza dell'immagine. Questa proprietà restituisce la dimensione verticale <br/>            dell'immagine, consentendo agli sviluppatori di determinarne la dimensione in pixel lungo l'asse <br/>            verticale. |
| horizontal_resolution | float | r/w | Recupera o modifica la risoluzione orizzontale dell'immagine. Questa proprietà <br/>            rappresenta il numero di pixel per pollice lungo l'asse orizzontale dell'<br/>            immagine. Modificare questa risoluzione può influire sulla dimensione fisica dell'immagine quando <br/>            stampata o visualizzata. |
| image_opacity | float | r | Ottiene l'opacità di questa immagine. |
| interlaced | bool | r | Recupera un valore booleano che indica se il [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) è <br/>            interlacciato, il che determina se i dati dell'immagine sono memorizzati in modo progressivo <br/>            per un caricamento o una trasmissione più rapida. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Ottiene o imposta il monitor di interruzione. |
| is_cached | bool | r | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| is_interlaced | bool | r | Restituisce un valore booleano che indica se l'istanza dell'immagine è interlacciata. Questa <br/>            proprietà è fondamentale per ottimizzare le strategie di caricamento e garantire prestazioni efficienti durante le operazioni di elaborazione o visualizzazione delle immagini. |
| is_raw_data_available | bool | r | Ottiene un valore che indica se il caricamento dei dati grezzi è supportato. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Ottiene i metadati dell'immagine. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| premultiply_components | bool | r/w | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Ottiene o imposta il convertitore di colore personalizzato |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Accede al formato dei dati grezzi dell'immagine. Questa proprietà fornisce informazioni su <br/>            come i dati dell'immagine sono strutturati internamente, il che può essere utile per operazioni avanzate di elaborazione delle immagini o conversione di formato. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Ottiene le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione. |
| raw_fallback_index | int | r/w | Ottiene o imposta l'indice di fallback da usare quando l'indice della tavolozza è fuori dai limiti |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Ottiene o imposta il convertitore di colore indicizzato |
| raw_line_size | int | r | Ottiene la dimensione della riga grezza in byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Ottiene la dimensione dell'oggetto. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Recupera il colore trasparente dell'immagine, se presente. Questa proprietà è <br/>            preziosa per le applicazioni che richiedono una gestione precisa delle aree trasparenti <br/>            all'interno delle immagini, consentendo agli sviluppatori di accedere e manipolare il colore trasparente specifico utilizzato. |
| update_xmp_data | bool | r/w | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| use_palette | bool | r | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
| use_raw_data | bool | r/w | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile. |
| vertical_resolution | float | r/w | Fornisce l'accesso alla risoluzione verticale dell'immagine. Gli sviluppatori possono utilizzare <br/>            questa proprietà per recuperare o modificare l'impostazione della risoluzione, che indica il numero di pixel per pollice (PPI) lungo l'asse verticale dell'immagine. |
| width | int | r | Consente di recuperare la larghezza dell'immagine, fornendo informazioni essenziali <br/>            sulle sue dimensioni. Questa proprietà è frequentemente utilizzata dagli sviluppatori per <br/>            determinare la larghezza dell'immagine, consentendo loro di eseguire varie operazioni basate <br/>            sulla sua dimensione |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta i dati Xmp. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Regola la luminosità dell'immagine. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Contrasto dell'immagine |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Correzione gamma di un'immagine. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Correzione gamma di un'immagine. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Calcola la percentuale di somiglianza tra i dati estratti e la password originale. |
| auto_brightness_contrast() | Esegue la normalizzazione automatica adattiva di luminosità e contrasto per l'intera immagine. |
| auto_rotate() | Ruota automaticamente l'immagine in base ai dati di orientamento estratti dai metadati Exif <br/>            . Questo metodo garantisce che le immagini vengano visualizzate nella corretta orientazione, <br/>            migliorando l'esperienza dell'utente ed eliminando la necessità di regolazioni manuali. Analizzando le informazioni Exif, l'immagine viene ruotata di conseguenza, fornendo un'esperienza di visualizzazione fluida <br/>            su diverse piattaforme e dispositivi. Questo processo di rotazione automatizzata <br/>            semplifica la gestione delle immagini e migliora l'usabilità complessiva, soprattutto quando <br/>            si lavora con grandi lotti di immagini con orientamenti variabili. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarizzazione di un'immagine con soglia predefinita |
| binarize_otsu() | Binarizzazione di un'immagine con soglia Otsu |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Unisce questa istanza di immagine con l'immagine _overlay_. |
| cache_data() | Memorizza nella cache i dati e garantisce che non vengano caricati ulteriori dati dal [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) sottostante. |
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
| [create_from_file_with_color_type(path, color_type)](#create_from_file_with_color_type_path_color_type_26) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_files(files)](#create_from_files_files_27) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_image_with_color_type(raster_image, color_type)](#create_from_image_with_color_type_raster_image_color_type_30) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height(width, height)](#create_with_width_height_width_height_34) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height_color_type(width, height, color_type)](#create_with_width_height_color_type_width_height_color_type_35) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [create_with_width_height_options(png_options, width, height)](#create_with_width_height_options_png_options_width_height_36) | Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | Ritaglia l'immagine con spostamenti. |
| [crop(rectangle)](#crop_rectangle_38) | Ritaglio dell'immagine. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | Esegue il dithering sull'immagine corrente. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | Esegue il dithering sull'immagine corrente. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | Filtra il rettangolo specificato. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | Ottiene l'array predefinito di pixel ARGB a 32 bit. |
| [get_default_options(args)](#get_default_options_args_45) | Ottiene le opzioni predefinite. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | Ottiene l'array predefinito di dati grezzi. |
| [get_file_format(file_path)](#get_file_format_file_path_49) | Ottiene il formato del file. |
| [get_file_format(stream)](#get_file_format_stream_50) | Ottiene il formato del file. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | Ottiene il formato del file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | Recupera il timestamp che indica l'ultima modifica della risorsa <br/>            immagine. Questo metodo fornisce l'accesso a metadati vitali, consentendo alle applicazioni di <br/>            determinare quando l'immagine è stata modificata l'ultima volta, facilitando il tracciamento delle versioni e <br/>            la gestione dei contenuti. |
| [get_original_options()](#get_original_options__55) | Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | Ottiene un pixel dell'immagine. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | Ottiene un'altezza proporzionale. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | Ottiene una larghezza proporzionale. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | Converte in aps. |
| [get_skew_angle()](#get_skew_angle__60) | Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| grayscale() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Esegue un rapido controllo per determinare se l'immagine è firmata digitalmente, utilizzando la password e la soglia fornite. |
| [load(file_path)](#load_file_path_62) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(stream)](#load_stream_64) | Carica una nuova immagine dallo stream specificato. |
| [load(stream, load_options)](#load_stream_load_options_65) | Carica una nuova immagine dallo stream specificato. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | Carica pixel ARGB a 32 bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | Carica pixel ARGB a 64 bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | Carica pixel in formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | Carica pixel in formato CMYK.<br/>            Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | Carica parzialmente pixel ARGB a 32 bit (per blocchi). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | Carica parzialmente pixel ARGB a 64 bit per pacchetti. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Carica pixel parzialmente per pacchetti. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Carica pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Carica dati grezzi. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Carica dati grezzi. |
| [load_stream(stream)](#load_stream_stream_76) | Carica una nuova immagine dallo stream specificato. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Carica una nuova immagine dallo stream specificato. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| normalize_angle() | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normalizza l'istogramma dell'immagine — regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| remove_metadata() | Rimuove i metadati di questa istanza immagine impostando il valore di [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_82) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_83) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_84) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_85) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_86) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [resize(new_width, new_height)](#resize_new_width_new_height_87) | Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_88) | Ridimensiona l'immagine. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_89) | Ridimensiona l'immagine. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_90) | Ridimensiona l'immagine. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_91) | Ridimensiona l'immagine. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_92) | Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_93) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_94) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_95) | Ridimensiona l'altezza proporzionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_96) | Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_97) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_98) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_99) | Ridimensiona la larghezza proporzionalmente. |
| [rotate(angle)](#rotate_angle_100) | Ruota l'immagine attorno al centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_101) | Ruota l'immagine attorno al centro. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_102) | Ruota, capovolge o ruota e capovolge l'immagine. |
| save() | Salva i dati dell'immagine nello stream sottostante. |
| [save(file_path)](#save_file_path_103) | Salva l'immagine nella posizione file specificata. |
| [save(file_path, options)](#save_file_path_options_104) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_105) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, over_write)](#save_file_path_over_write_106) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_107) | I dati di salvataggio. |
| [save(stream, options_base)](#save_stream_options_base_108) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_109) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
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
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_123) | Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_124) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_125) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_126) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |


### Constructor: PngImage(path) {#PngImage_path_1}


```
 PngImage(path) 
```

Costruisce una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) utilizzando il parametro path <br/>            per specificare la posizione del file immagine da caricare. Questo costruttore <br/>            consente agli sviluppatori di creare comodamente immagini PNG caricandole da un file, <br/>            semplificando il processo di utilizzo delle immagini PNG nelle loro applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| percorso | string | Il percorso per caricare un'immagine. |


**See also:**

**[Example # 1](#example_109)**: This example shows how to load a PNG image from a file.


### Constructor: PngImage(path, color_type) {#PngImage_path_color_type_2}


```
 PngImage(path, color_type) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) specificando il <br/>            percorso del file immagine e il tipo di colore. Questo costruttore consente una creazione comoda <br/>            di immagini PNG da file con diversi tipi di colore, offrendo <br/>            flessibilità nella gestione di vari formati di immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| percorso | string | Il percorso per caricare un'immagine. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |


**See also:**

**[Example # 1](#example_110)**: This example shows how to load a PNG image from a file with the specified col...


### Constructor: PngImage(png_options, width, height) {#PngImage_png_options_width_height_3}


```
 PngImage(png_options, width, height) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/), incorporando <br/>            opzioni PNG insieme ai parametri di larghezza e altezza. Questo costruttore consente <br/>            agli sviluppatori di creare immagini PNG con impostazioni e dimensioni personalizzabili, <br/>            offrendo flessibilità nella generazione di immagini per diversi casi d'uso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Le opzioni PNG. |
| width | int | La larghezza. |
| height | int | L'altezza. |

### Constructor: PngImage(raster_image) {#PngImage_raster_image_4}


```
 PngImage(raster_image) 
```

Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fornendo un'immagine raster <br/>            come parametro. Questo costruttore consente agli sviluppatori di inizializzare direttamente un <br/>            oggetto immagine PNG utilizzando un'immagine raster esistente, semplificando il processo di <br/>            utilizzo delle immagini PNG nelle loro applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |


**See also:**

**[Example # 1](#example_112)**: This example shows how to load PNG image from a BMP image.


### Constructor: PngImage(raster_image, color_type) {#PngImage_raster_image_color_type_5}


```
 PngImage(raster_image, color_type) 
```

Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) specificando un <br/>            immagine raster e un tipo di colore. Questo costruttore permette agli sviluppatori di convertire direttamente <br/>            le immagini raster in formato PNG specificando il tipo di colore desiderato, <br/>            offrendo flessibilità nella rappresentazione dei colori.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |


**See also:**

**[Example # 1](#example_113)**: This example shows how to load PNG image from a BMP image with the specified ...


### Constructor: PngImage(stream) {#PngImage_stream_6}


```
 PngImage(stream) 
```

Crea una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) inizializzandola <br/>            con uno stream. Questo costruttore consente agli sviluppatori di caricare immagini PNG direttamente <br/>            da uno stream, fornendo flessibilità nel recupero delle immagini da diverse fonti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso per caricare un'immagine. |


**See also:**

**[Example # 1](#example_111)**: This example shows how to load a PNG image from a file or a file stream.


### Constructor: PngImage(width, height) {#PngImage_width_height_7}


```
 PngImage(width, height) 
```

Inizializza un nuovo oggetto della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) fornendo i parametri di <br/>            larghezza e altezza. Questo costruttore semplifica la creazione di immagini PNG <br/>            consentendo agli sviluppatori di specificare direttamente le dimensioni, facilitando <br/>            una gestione efficiente dei dati delle immagini PNG nelle loro applicazioni.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |


**See also:**

**[Example # 1](#example_114)**: This example shows how to create a PNG image of the specified size, fill it w...


### Constructor: PngImage(width, height, color_type) {#PngImage_width_height_color_type_8}


```
 PngImage(width, height, color_type) 
```

Istanzia una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/), specificando <br/>            i parametri di larghezza, altezza e tipo di colore desiderati. Questo costruttore consente <br/>            una rapida creazione di immagini PNG con dimensioni e configurazioni di colore su misura, <br/>            facilitando una generazione di immagini ottimizzata per varie applicazioni e flussi di lavoro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |


**See also:**

**[Example # 1](#example_115)**: This example shows how to create a PNG image of the specified size with the s...


### Property: has_alpha {#has_alpha1}

Restituisce un valore booleano che indica se l'immagine ha un canale alfa, <br/>            che ne determina la trasparenza. Questa proprietà è utile per le applicazioni <br/>            che devono gestire la trasparenza, consentendo agli sviluppatori di determinare se <br/>            è necessario un ulteriore processamento per gestire le aree trasparenti dell'immagine.

**See also:**

**[Example # 1](#example_116)**: The following example shows how to check if a PNG image supports alpha-channel.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Regola la luminosità dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| luminosità | int | Valore di luminosità. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Contrasto dell'immagine

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| contrasto | float | Valore di contrasto (nell'intervallo [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Correzione gamma di un'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma | float | Coefficiente gamma per i canali rosso, verde e blu |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Correzione gamma di un'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| gamma_red | float | Coefficiente gamma per il canale rosso |
| gamma_green | float | Coefficiente gamma per il canale verde |
| gamma_blue | float | Gamma per il coefficiente del canale blu |

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
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarizzazione di un'immagine usando l'algoritmo di sogliatura adattiva di Bradley con la sogliatura dell'immagine integrale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| brightness_difference | float | La differenza di luminosità tra il pixel e la media di una finestra s x s di pixel centrata su questo pixel. |
| window_size | int | La dimensione della finestra di pixel s x s centrata attorno a questo pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarizzazione di un'immagine con soglia predefinita

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| soglia | System.Byte | Valore di soglia. Se il valore di grigio corrispondente di un pixel è maggiore della soglia, gli verrà assegnato il valore 255, altrimenti 0. |

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


### Method: create_from_file_with_color_type(path, color_type)  [static] {#create_from_file_with_color_type_path_color_type_26}


```
 create_from_file_with_color_type(path, color_type) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| percorso | string | Il percorso per caricare un'immagine. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_29}


```
 create_from_image(raster_image) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_image_with_color_type(raster_image, color_type)  [static] {#create_from_image_with_color_type_raster_image_color_type_30}


```
 create_from_image_with_color_type(raster_image, color_type) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso per caricare un'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height(width, height)  [static] {#create_with_width_height_width_height_34}


```
 create_with_width_height(width, height) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height_color_type(width, height, color_type)  [static] {#create_with_width_height_color_type_width_height_color_type_35}


```
 create_with_width_height_color_type(width, height, color_type) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| width | int | La larghezza. |
| height | int | L'altezza. |
| color_type | [PngColorType](/imaging/python-net/aspose.imaging.fileformats.png/pngcolortype/) | Il tipo di colore. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: create_with_width_height_options(png_options, width, height)  [static] {#create_with_width_height_options_png_options_width_height_36}


```
 create_with_width_height_options(png_options, width, height) 
```

Inizializza una nuova istanza della classe [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| png_options | [PngOptions](/imaging/python-net/aspose.imaging.imageoptions/pngoptions/) | Le opzioni PNG. |
| width | int | La larghezza. |
| height | int | L'altezza. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Ritaglia l'immagine con spostamenti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left_shift | int | Lo shift a sinistra. |
| right_shift | int | Lo shift a destra. |
| top_shift | int | Lo shift superiore. |
| bottom_shift | int | Lo shift inferiore. |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

Ritaglio dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

Esegue il dithering sull'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Esegue il dithering sull'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personalizzata per il dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password usata per generare i dati della firma digitale. |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

Filtra il rettangolo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Le opzioni. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


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


### Method: get_default_options(args) {#get_default_options_args_45}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


```
 get_modify_date(use_default) 
```

Recupera il timestamp che indica l'ultima modifica della risorsa <br/>            immagine. Questo metodo fornisce l'accesso a metadati vitali, consentendo alle applicazioni di <br/>            determinare quando l'immagine è stata modificata l'ultima volta, facilitando il tracciamento delle versioni e <br/>            la gestione dei contenuti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| use_default | bool | se impostato su <c>true</c> utilizza le informazioni da FileInfo come valore predefinito. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.DateTime | La data e l'ora in cui l'immagine della risorsa è stata modificata l'ultima volta. |


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni basate sulle impostazioni del file originale. |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


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


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'angolo di inclinazione, in gradi. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 32 bit (per blocchi).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 64 bit per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carica pixel parzialmente per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Il caricatore di pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_82}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_83}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore vecchio da sostituire. |
| old_color_diff | System.Byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuovo colore con cui sostituire il colore vecchio. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_85}


```
 replace_non_transparent_colors(new_color) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuovo colore con cui sostituire i colori non trasparenti. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_86}


```
 replace_non_transparent_colors(new_color_argb) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color_argb | int | Nuovo valore ARGB del colore per sostituire i colori non trasparenti. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_87}


```
 resize(new_width, new_height) 
```

Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_88}


```
 resize(new_width, new_height, resize_type) 
```

Ridimensiona l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Il tipo di ridimensionamento. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_89}


```
 resize(new_width, new_height, settings) 
```

Ridimensiona l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_90}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_91}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_92}


```
 resize_height_proportionally(new_height) 
```

Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_93}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_94}


```
 resize_height_proportionally(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_95}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ridimensiona l'altezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_height | int | La nuova altezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_96}


```
 resize_width_proportionally(new_width) 
```

Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_97}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_98}


```
 resize_width_proportionally(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_99}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: rotate(angle) {#rotate_angle_100}


```
 rotate(angle) 
```

Ruota l'immagine attorno al centro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_101}


```
 rotate(angle, resize_proportionally, background_color) 
```

Ruota l'immagine attorno al centro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_102}


```
 rotate_flip(rotate_flip_type) 
```

Ruota, capovolge o ruota e capovolge l'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Il tipo di rotazione e capovolgimento. |

### Method: save(file_path) {#save_file_path_103}


```
 save(file_path) 
```

Salva l'immagine nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare l'immagine. |

### Method: save(file_path, options) {#save_file_path_options_104}


```
 save(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_105}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_106}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà effettuata un'aggiunta. |

### Method: save(stream) {#save_stream_107}


```
 save(stream) 
```

I dati di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

### Method: save(stream, options_base) {#save_stream_options_base_108}


```
 save(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_109}


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
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di pixel ARGB a 32 bit. |

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

Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

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
### This example shows how to load a PNG image from a file. {#example_109}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.png import PngImage

# Carica un'immagine PNG da un file.
with as_of(Image.load("sample.png"), PngImage) as pngImage:
	# Trasforma l'immagine in una rappresentazione in scala di grigi
	pngImage.grayscale()
	# Salva in un file.
	pngImage.save("sample.grayscale.png")


```

### This example shows how to load a PNG image from a file with the specified color type. {#example_110}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.png import PngImage, PngColorType
from os.path import join

dir_ = "c:\\temp"
# Carica un'immagine PNG da un file.
# Nota che l'immagine a colori verrà convertita automaticamente in scala di grigi.
with PngImage(join(dir_, "sample.png"), PngColorType.GRAYSCALE) as png_image:
	# Salva in un file.
	png_image.save(join(dir_, "sample.grayscale.png"))


```

### This example shows how to load a PNG image from a file or a file stream. {#example_111}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.png import PngImage
from os.path import join


dir_: str = "c:\\temp"
# Carica un'immagine PNG da un flusso di file.
with open(join(dir_, "sample.png"), "rb") as stream:
	with PngImage(stream) as png_image:
		# Trasforma l'immagine in una rappresentazione in scala di grigi
		png_image.grayscale()
		# Salva in un file.
		png_image.save(join(dir_, "sample.grayscale.png"))


```

### This example shows how to load PNG image from a BMP image. {#example_112}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
# Carica un'immagine PNG TrueColor da un'immagine BMP.
# Prima, crea un'immagine BMP temporanea che servirà da base per la creazione di un'immagine PNG.
# Puoi anche caricare un'immagine BMP da un file o utilizzare un'immagine di qualsiasi altro formato raster.
with BmpImage(100, 100) as bmp_image:
	# Riempi l'intera immagine BMP di rosso.
	gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	with PngImage(bmp_image) as png_image:
		png_image.save(join(dir_, "output.png"))


```

### This example shows how to load PNG image from a BMP image with the specified color type. {#example_113}
``` python

from aspose.imaging import LoadOptions, Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.fileformats.png import PngImage, PngColorType
from os.path import join as path_join


dir_ = "c:\\temp"
# Carica un'immagine PNG in scala di grigi da un'immagine BMP a colori.
# Prima, crea un'immagine BMP temporanea che servirà da base per la creazione di un'immagine PNG.
# Puoi anche caricare un'immagine BMP da un file o utilizzare un'immagine di qualsiasi altro formato raster.
with BmpImage(100, 100) as bmp_image:
	# Riempi l'intera immagine BMP di rosso.
	gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# I colori dei pixel dell'immagine saranno convertiti nelle loro controparti in scala di grigi.
	with PngImage(bmp_image, PngColorType.GRAYSCALE) as png_image:
		png_image.save(path_join(dir_, "output.grayscale.png"))


```

### This example shows how to create a PNG image of the specified size, fill it with a solid color and save it to a file. {#example_114}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.png import PngImage
from os.path import join


dir_ = "c:\\temp"
# Crea un'immagine PNG di 100x100 px.
with PngImage(100, 100) as png_image:
	# Esegui qualche elaborazione dell'immagine, ad es. riempi l'intera immagine di rosso.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Salva in un file.
	png_image.save(join(dir_, "output.png"))


```

### This example shows how to create a PNG image of the specified size with the specified color type, fill it with a solid color and save it to a file. {#example_115}
``` python
from aspose.imaging.fileformats.png import PngImage, PngColorType
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from os.path import join

dir_: str = "c:\\temp"
# Crea un'immagine PNG in scala di grigi di 100x100 px.
# Tutti i colori saranno convertiti automaticamente nel formato in scala di grigi.
with PngImage(100, 100, PngColorType.GRAYSCALE) as png_image:
	# Esegui qualche elaborazione dell'immagine, ad es. riempi l'intera immagine di rosso.
	graphics = Graphics(png_image)
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Salva in un file.
	png_image.save(join(dir_, "output.grayscale.png"))


```

### The following example shows how to check if a PNG image supports alpha-channel. {#example_116}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.png import PngColorType, PngImage


# Ottieni tutti i tipi di colore PNG supportati.
color_types = [it for it in PngColorType]
for color_type in color_types:
	create_options = PngOptions()
	create_options.color_type = color_type
	with Image.create(create_options, 100, 100) as image:
		png_image = aspycore.as_of(image, PngImage)
		if png_image.has_alpha:
			print("A {0} PNG image supports alpha channel".format(create_options.color_type))
		else:
			print("A {0} PNG image doesn't support alpha channel".format(create_options.color_type))

# L'output appare così:
# Un'immagine PNG in scala di grigi non supporta il canale alfa
# Un'immagine PNG Truecolor non supporta il canale alfa
# Un'immagine PNG IndexedColor non supporta il canale alfa
# Un'immagine PNG GrayscaleWithAlpha supporta il canale alfa
# Un'immagine PNG TruecolorWithAlpha supporta il canale alfa


```

### The example shows how to remove any object from the image using Graphics Path with Content Aware fill algorithm. {#example_227}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import ContentAwareFillWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure)

	options = ContentAwareFillWatermarkOptions(mask)
	options.max_painting_attempts = 4
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

### The example shows how to remove any object from the image using Graphics Path with Telea algorithm. {#example_228}
``` python
from aspose.imaging import Image, Figure, GraphicsPath, RectangleF
from aspose.imaging.shapes import EllipseShape
from aspose.imaging.watermark import WatermarkRemover
from aspose.imaging.watermark.options import TeleaWatermarkOptions
from aspose.imaging.fileformats.png import PngImage
import aspose.pycore import as_of

image_file_path = "ball.png"; 
with Image.load(image_file_path) as image:
	pngImage = as_of(image, PngImage)
	mask = GraphicsPath()
	firstFigure = Figure()
	firstFigure.add_shape(EllipseShape(RectangleF(350, 170, 570 - 350, 400 - 170)))
	mask.add_figure(firstFigure);
	options = TeleaWatermarkOptions(mask)
	with WatermarkRemover.paint_over(pngImage, options) as result:
		result.save(outputPath)


```

