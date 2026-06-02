---
title: "Classe TgaImage"
type: docs
weight: 10
url: /it/python-net/aspose.imaging.fileformats.tga/tgaimage/
---

**Summary:** Manipulate TGA raster image files with our API, tailored for the TARGA<br/>            (Truevision Advanced Raster Adapter) format, enabling seamless loading and<br/>            customization. Easily update public properties such as author, timestamp,<br/>            image ID, and software version, while using various bits per pixel settings,<br/>            alpha channel and color transparency. Additionally, you can export TGA images<br/>            to other popular raster formats, ensuring compatibility for your projects.

**Module:** [aspose.imaging.fileformats.tga](/imaging/python-net/aspose.imaging.fileformats.tga/)

**Full Name:** aspose.imaging.fileformats.tga.TgaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [TgaImage(path)](#TgaImage_path_1) | Inizializza un nuovo oggetto [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) utilizzando il percorso file fornito per <br/>            caricare il contenuto dell'immagine. Questo costruttore inizializza in modo efficiente l'istanza dell'immagine <br/>            consentendo un accesso senza interruzioni ai file immagine TGA, semplificando l'integrazione <br/>            nel flusso di lavoro della tua applicazione. |
| [TgaImage(raster_image)](#TgaImage_raster_image_2) | Crea una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) fornendo un raster <br/>            oggetto immagine. Questo costruttore facilita l'integrazione diretta delle immagini raster esistenti <br/>            nel formato immagine TGA, ottimizzando il processo di conversione per <br/>            una compatibilità migliorata all'interno dei tuoi sistemi software. |
| [TgaImage(stream)](#TgaImage_stream_3) | Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) utilizzando uno stream per <br/>            caricare l'immagine. Questo costruttore consente un'integrazione senza interruzioni dei dati immagine <br/>            provenienti da stream, facilitando una gestione efficiente e l'elaborazione delle immagini TGA all'interno <br/>            delle tue applicazioni software. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| author_comments | string | r/w | Recupera o imposta i commenti forniti dall'autore dell'immagine. Questi commenti <br/>            contengono spesso informazioni preziose, come descrizioni, annotazioni o <br/>            contesto aggiuntivo sull'immagine. Accedendo o modificando la proprietà Author Comments <br/>            gli sviluppatori possono migliorare i metadati associati all'immagine, fornendo <br/>            agli utenti approfondimenti e contesto utili riguardo al suo contenuto o alla sua creazione.<br/>            Questo è un campo ASCII di 324 byte organizzato in quattro righe<br/>            di 80 caratteri, ciascuna seguita da un terminatore nullo. |
| author_name | string | r/w | Recupera o imposta il nome dell'autore associato all'immagine. Questa proprietà <br/>            consente agli sviluppatori di accedere o modificare i metadati del nome dell'autore, fornendo <br/>            informazioni preziose sul creatore dell'immagine. Utilizzando la proprietà Author Name <br/>            gli utenti possono identificare facilmente la persona responsabile della creazione o <br/>            del contributo all'immagine, migliorando i metadati complessivi e fornendo <br/>            contesto prezioso per gli spettatori.<br/>            Questo campo è composto da un totale di 40 caratteri ASCII per il nome. Se il campo è utilizzato,<br/>            deve contenere il nome della persona che ha creato l'immagine (autore). |
| auto_adjust_palette | bool | r/w | Ottiene o imposta un valore che indica se la palette viene regolata automaticamente. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Recupera o imposta il colore di sfondo dell'immagine. Questa proprietà consente <br/>            di specificare il colore da utilizzare per lo sfondo dell'immagine, garantendo coerenza e <br/>            migliorando la presentazione visiva. È particolarmente utile in scenari in cui <br/>            l'immagine viene visualizzata su uno sfondo di colore diverso o durante il rendering <br/>            dell'immagine su un'altra tela. |
| bits_per_pixel | int | r | Recupera il valore dei bit per pixel, fornendo informazioni essenziali sulla <br/>            profondità di colore dell'immagine. Questa proprietà funge da metrica cruciale per comprendere <br/>            il livello di dettaglio e la ricchezza di colore presenti nell'immagine, aiutando gli sviluppatori a <br/>            ottimizzare gli algoritmi di elaborazione e l'allocazione delle risorse per una manipolazione <br/>            e rendering efficienti dell'immagine. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Ottiene i limiti dell'oggetto. |
| buffer_size_hint | int | r/w | Ottiene o imposta il suggerimento della dimensione del buffer, che è definito come dimensione massima consentita per tutti i buffer interni. |
| bytes_per_pixel | int | r | Ottiene il valore dei byte per pixel, che indica la quantità di memoria occupata da <br/>            ogni pixel nell'immagine. Questa proprietà è una metrica cruciale per la gestione <br/>            e l'ottimizzazione della memoria, aiutando gli sviluppatori a allocare risorse <br/>            in modo efficiente e a elaborare i dati dell'immagine. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Ottiene il contenitore [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Ottiene lo stream di dati dell'oggetto. |
| date_time_stamp | System.Nullable`1[[System.DateTime]] | r/w | Recupera o imposta il timestamp data/ora.<br/>            Questo campo definisce il valore per la data e l'ora in cui l'immagine è stata salvata. <br/>            Anche se i sistemi operativi tipicamente aggiungono data e ora ai file, questa funzionalità è<br/>            fornita perché il sistema operativo può modificare il timestamp data e ora se il file è<br/>            copiato. Utilizzando quest'area, si garantisce una regione non modificata per la registrazione della data e dell'ora. |
| eliminato | bool | r | Ottiene un valore che indica se questa istanza è stata eliminata. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Ottiene o imposta l'istanza Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Ottieni informazioni cruciali sul formato file dell'immagine rappresentata da questa <br/>            istanza di [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). Comprendere il formato file è essenziale per <br/>            verifiche di compatibilità e per garantire un'integrazione senza interruzioni nei sistemi software, <br/>            consentendo una gestione efficiente e la manipolazione delle immagini. |
| gamma_value_denominator | int | r | Recupera la parte denominatore del valore gamma, un fattore fondamentale nella <br/>            determinazione della rappresentazione dei colori nelle immagini. Per le immagini prive di correzione gamma, questo valore dovrebbe essere 1.0, garantendo una resa accurata dei colori. <br/>            Apprezzare e sfruttare questo parametro è fondamentale per mantenere la fedeltà del colore e ottenere una visualizzazione precisa dell'immagine. |
| gamma_value_numerator | int | r | Recupera la parte numeratore del valore gamma, essenziale per una rappresentazione accurata dei colori nelle immagini. Nelle immagini senza correzione gamma, questo valore dovrebbe essere 1.0. Comprendere e utilizzare questo valore è cruciale per mantenere la fedeltà del colore e garantire un rendering accurato dell'immagine. |
| has_alpha | bool | r | Recupera un valore booleano che indica se il [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) include un <br/>            canale alfa, facilitando gli effetti di trasparenza. Questa proprietà fornisce informazioni essenziali <br/>            per la gestione della composizione e del rendering dell'immagine, assistendo gli sviluppatori nella <br/>            implementazione di diversi effetti visivi e operazioni di compositing. |
| has_background_color | bool | r/w | Recupera o imposta un valore che indica se l'immagine contiene un colore di sfondo. Questa proprietà è utile per determinare se l'immagine include un <br/>            colore di sfondo distinto dal contenuto in primo piano. Consente <br/>            di personalizzare l'elaborazione o il rendering dell'immagine in base alla presenza o assenza di <br/>            un colore di sfondo. |
| has_color_map | bool | r | Recupera se questa istanza di [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) contiene una mappa dei colori. <br/>            Comprendere la presenza di una mappa dei colori è cruciale per un'interpretazione accurata <br/>            e la manipolazione dei dati di colore dell'immagine. |
| has_transparent_color | bool | r/w | Recupera o imposta un valore booleano che indica se l'immagine contiene un <br/>            colore trasparente. Questa proprietà è essenziale per identificare se l'immagine <br/>            supporta la trasparenza, aiutandoti a implementare una gestione appropriata delle <br/>            operazioni legate alla trasparenza, come blending, compositing o masking. |
| height | int | r | Ottieni l'altezza dell'immagine incapsulata da questa [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            istanza. Questa proprietà fornisce agli sviluppatori dettagli critici riguardo le <br/>            dimensioni verticali dell'immagine, consentendo un'integrazione e manipolazione senza soluzione di continuità delle <br/>            immagini all'interno delle loro soluzioni software. |
| horizontal_resolution | float | r/w | Ottiene o imposta la risoluzione orizzontale, in pixel per pollice, di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_id | string | r/w | Ottiene o imposta l'identificatore univoco associato all'immagine. Questo ID funge da <br/>            punto di riferimento per identificare e distinguere l'immagine dalle altre all'interno di un <br/>            sistema o applicazione. Impostando o recuperando l'Image ID, è possibile gestire e <br/>            tracciare le immagini in modo efficace, facilitando processi di gestione e recupero delle immagini organizzate.<br/>            <br/>Questo campo opzionale contiene informazioni identificative sull'immagine. La lunghezza massima<br/>            per questo campo è di 255 byte.<br/> |
| image_opacity | float | r | Ottiene l'opacità di questa immagine. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Ottiene o imposta il monitor di interruzione. |
| is_cached | bool | r | Ottiene un valore che indica se i dati dell'immagine sono attualmente memorizzati nella cache. |
| is_gray_scale | bool | r | Ottieni un valore booleano che indica se il [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) rappresenta un'immagine in scala di grigi. Questa proprietà è cruciale per distinguere tra immagini a colori e <br/>            immagini in scala di grigi, aiutando gli sviluppatori ad applicare tecniche di elaborazione e <br/>            rendering appropriate basate sulle caratteristiche cromatiche dell'immagine. |
| is_raw_data_available | bool | r | Ottiene un valore che indica se il caricamento dei dati grezzi è supportato. |
| job_name_or_id | string | r/w | Recupera o imposta il nome o l'ID del lavoro associato all'immagine. Questa proprietà <br/>            consente di accedere o modificare i metadati relativi al lavoro o progetto specifico <br/>            associato all'immagine. Utilizzando la proprietà Job Name/ID, gli utenti possono facilmente <br/>            identificare il progetto o compito a cui l'immagine si riferisce, facilitando <br/>            l'organizzazione e la gestione delle risorse immagine all'interno di flussi di lavoro o progetti più ampi. |
| job_time | System.Nullable`1[[System.TimeSpan]] | r/w | Recupera o imposta il timestamp che indica il tempo del lavoro associato all'immagine. <br/>            Questa proprietà consente agli sviluppatori di accedere o modificare i metadati temporali relativi al <br/>            lavoro o progetto specifico associato all'immagine. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Ottiene i metadati dell'immagine. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Ottiene o imposta la tavolozza dei colori. La tavolozza dei colori non viene utilizzata quando i pixel sono rappresentati direttamente. |
| pixel_aspect_ratio_denominator | int | r | Recupera la parte denominatore del Pixel Aspect Ratio, un fattore cruciale nella <br/>            determinazione dell'aspetto visivo dei pixel all'interno dell'immagine. Questo valore è essenziale <br/>            per preservare una rappresentazione accurata dei pixel e i rapporti di aspetto in varie <br/>            operazioni di rendering e elaborazione delle immagini, garantendo un output visivo di alta qualità. |
| pixel_aspect_ratio_numerator | int | r | Recupera la componente numeratore del Pixel Aspect Ratio, che influenza l'aspetto visivo dei pixel all'interno dell'immagine. Comprendere e manipolare questo <br/>            valore è essenziale per ottenere una rappresentazione accurata dei pixel e i rapporti di aspetto <br/>            nel rendering e nell'elaborazione delle immagini. |
| premultiply_components | bool | r/w | Ottiene o imposta un valore che indica se i componenti dell'immagine devono essere premoltiplicati. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Ottiene o imposta il convertitore di colore personalizzato |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Ottiene il formato dei dati grezzi. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Ottiene le impostazioni attuali dei dati grezzi. Nota che quando si usano queste impostazioni i dati vengono caricati senza conversione. |
| raw_fallback_index | int | r/w | Ottiene o imposta l'indice di fallback da usare quando l'indice della tavolozza è fuori dai limiti |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Ottiene o imposta il convertitore di colore indicizzato |
| raw_line_size | int | r | Ottiene la dimensione della riga grezza in byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Ottiene la dimensione dell'oggetto. |
| software_id | string | r/w | Gestisce l'identificazione del software (ID) associata all'immagine, consentendo fino a 40 caratteri ASCII. Questa proprietà serve come mezzo per identificare in modo univoco il software utilizzato nella creazione o elaborazione dell'immagine, fornendo metadati preziosi per scopi organizzativi e informativi. |
| software_version | string | r/w | Recupera o imposta la versione del software associata all'immagine. La lunghezza accettata per la stringa di versione è tipicamente di 3-4 caratteri. Questa proprietà è <br/>            utile per tracciare il software utilizzato per creare o manipolare l'immagine e può <br/>            fornire un contesto prezioso per l'elaborazione delle immagini e i controlli di compatibilità. |
| software_version_letter | System.Char | r/w | Recupera o imposta la componente lettera della versione del software associata all'immagine. Questa proprietà rappresenta un dettaglio aggiuntivo nella stringa della versione del software <br/>            e può essere utile per una differenziazione più fine delle versioni. |
| software_version_number | int | r/w | Recupera o imposta la componente numerica della versione del software associata all'immagine. Questa proprietà rappresenta la parte numerica della stringa della versione del software <br/>            fornendo informazioni importanti sulla versione del software utilizzato per <br/>            creare o modificare l'immagine. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Recupera o imposta il colore chiave associato all'immagine. Questa proprietà consente <br/>            di accedere o modificare il colore designato come colore chiave per specifici compiti o effetti di elaborazione dell'immagine. Utilizzare la proprietà Key Color permette agli utenti di <br/>            applicare operazioni basate sul colore come chroma keying o sostituzione del colore, migliorando <br/>            le capacità di manipolazione dell'immagine e le possibilità creative.<br/>            <br/>Il Key Color può essere considerato come il ‘colore di sfondo’ o ‘colore trasparente’.<br/>            Questo è il colore dell’area ‘non immagine’ dello schermo, e lo stesso colore a cui lo<br/>            schermo verrebbe cancellato se cancellato nell’applicazione.<br/> |
| update_xmp_data | bool | r/w | Ottiene o imposta un valore che indica se aggiornare i metadati XMP. |
| use_palette | bool | r | Ottiene un valore che indica se la tavolozza dell'immagine è utilizzata. |
| use_raw_data | bool | r/w | Ottiene o imposta un valore che indica se utilizzare il caricamento dei dati grezzi quando è disponibile. |
| vertical_resolution | float | r/w | Ottiene o imposta la risoluzione verticale, in pixel per pollice, di questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Recupera la larghezza dell'immagine rappresentata da questa [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            istanza. Questa proprietà fornisce agli sviluppatori informazioni essenziali sulle <br/>            dimensioni dell'immagine, facilitando varie operazioni di manipolazione e elaborazione delle immagini <br/>            all'interno delle loro applicazioni software. |
| x_origin | int | r/w | Ottiene o imposta la coordinata orizzontale assoluta per l'angolo inferiore sinistro dell'immagine<br/>            così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello<br/>            schermo (ad es., la serie TARGA). |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Ottiene o imposta i dati Xmp. |
| y_origin | int | r/w | Ottiene o imposta la coordinata verticale assoluta per l'angolo inferiore sinistro dell'immagine<br/>            così come è posizionata su un dispositivo di visualizzazione con origine nell'angolo inferiore sinistro dello<br/>            schermo (ad es., la serie TARGA). |
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
| [clone()](#clone__19) | Produce un duplicato dell'istanza corrente, generando un nuovo oggetto che clona <br/>            tutti gli attributi e le proprietà dell'originale. Questo metodo facilita la <br/>            creazione di copie identiche, garantendo l'integrità dei dati e preservando lo stato dell' <br/>            istanza corrente senza influire sull'oggetto originale. |
| [clone(tga_image)](#clone_tga_image_20) | Replica le proprietà di un altro oggetto [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/), creando una <br/>            nuova istanza con attributi identici. Questa operazione garantisce la preservazione <br/>            dell'integrità dei dati e facilita la duplicazione delle proprietà dell'immagine senza <br/>            modificare l'oggetto di origine. |
| [create(files)](#create_files_21) | Crea l'immagine multipagina contenente i file specificati. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Crea l'immagine multipagina contenente i file specificati. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Crea una nuova immagine utilizzando le opzioni di creazione specificate. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Crea un'istanza di [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) dall'array di pixel fornito.<br/>            <br/>            Convalida che la larghezza e l'altezza specificate corrispondano alle dimensioni dei dati pixel.<br/>            Questo metodo può essere usato solo quando la libreria è in modalità Licensed. |
| [create(images)](#create_images_25) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Crea le opzioni di creazione multipagina specificate. |
| [create_from_files(files)](#create_from_files_files_28) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Crea l'immagine multipagina contenente i file specificati come pagine a caricamento differito. |
| [create_from_image(raster_image)](#create_from_image_raster_image_30) | Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Crea una nuova immagine utilizzando le immagini specificate come pagine |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Crea una nuova immagine dalle immagini specificate come pagine. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_34) | Ritaglia l'immagine specificando gli spostamenti per i bordi sinistro, destro, superiore e inferiore <br/>            . Questo metodo consente di tagliare l'immagine spostando i suoi bordi <br/>            indipendentemente lungo gli assi orizzontale e verticale. Regolando questi spostamenti, <br/>            è possibile controllare con precisione quali parti dell'immagine conservare, <br/>            ritagliandola efficacemente alle dimensioni desiderate. |
| [crop(rectangle)](#crop_rectangle_35) | Ritaglia l'immagine a una regione specificata. Questo metodo consente di definire un <br/>            area rettangolare all'interno dell'immagine da conservare, scartando il resto. Questa operazione <br/>            è utile per focalizzarsi su contenuti specifici dell'immagine o rimuovere parti indesiderate. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Esegue il dithering sull'immagine corrente. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Esegue il dithering sull'immagine corrente. |
| [embed_digital_signature(password)](#embed_digital_signature_password_38) | Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia. |
| [filter(rectangle, options)](#filter_rectangle_options_39) | Filtra il rettangolo specificato. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_40) | Ottiene un pixel ARGB a 32 bit dell'immagine. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_41) | Ottiene l'array predefinito di pixel ARGB a 32 bit. |
| [get_default_options(args)](#get_default_options_args_42) | Ottiene le opzioni predefinite. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_43) | Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44) | Ottiene l'array predefinito di dati grezzi usando il caricatore di pixel parziale. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_45) | Ottiene l'array predefinito di dati grezzi. |
| [get_file_format(file_path)](#get_file_format_file_path_46) | Ottiene il formato del file. |
| [get_file_format(stream)](#get_file_format_stream_47) | Ottiene il formato del file. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_48) | Ottiene il formato del file. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_49) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_50) | Ottiene il rettangolo che si adatta all'immagine corrente. |
| [get_modify_date(use_default)](#get_modify_date_use_default_51) | Ottiene la data e l'ora dell'ultima modifica dell'immagine di risorsa. |
| [get_original_options()](#get_original_options__52) | Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro. |
| [get_pixel(x, y)](#get_pixel_x_y_53) | Ottiene un pixel dell'immagine. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_54) | Ottiene un'altezza proporzionale. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_55) | Ottiene una larghezza proporzionale. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_56) | Converte in aps. |
| [get_skew_angle()](#get_skew_angle__57) | Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione. |
| grayscale() | Trasformazione di un'immagine nella sua rappresentazione in scala di grigi |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_58) | Esegue un rapido controllo per determinare se l'immagine è firmata digitalmente, utilizzando la password e la soglia fornite. |
| [load(file_path)](#load_file_path_59) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(file_path, load_options)](#load_file_path_load_options_60) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| [load(stream)](#load_stream_61) | Carica una nuova immagine dallo stream specificato. |
| [load(stream, load_options)](#load_stream_load_options_62) | Carica una nuova immagine dallo stream specificato. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_63) | Carica pixel ARGB a 32 bit. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_64) | Carica pixel ARGB a 64 bit. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_65) | Carica pixel in formato CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_66) | Carica pixel in formato CMYK.<br/>            Questo metodo è deprecato. Si prega di utilizzare il metodo più efficace [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67) | Carica parzialmente pixel ARGB a 32 bit (per blocchi). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68) | Carica parzialmente pixel ARGB a 64 bit per pacchetti. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_69) | Carica pixel parzialmente per pacchetti. |
| [load_pixels(rectangle)](#load_pixels_rectangle_70) | Carica pixel. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71) | Carica dati grezzi. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72) | Carica dati grezzi. |
| [load_stream(stream)](#load_stream_stream_73) | Carica una nuova immagine dallo stream specificato. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_74) | Carica una nuova immagine dallo stream specificato. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_75) | Carica una nuova immagine dal percorso file o URL specificato.<br/>            Se _filePath_ è un percorso file, il metodo apre semplicemente il file.<br/>            Se _filePath_ è un URL, il metodo scarica il file, lo memorizza temporaneamente e lo apre. |
| normalize_angle() | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_76) | Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normalizza l'istogramma dell'immagine — regola i valori dei pixel per utilizzare l'intera gamma disponibile. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_77) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_78) | Legge l'intera linea di scansione tramite l'indice di linea di scansione specificato. |
| remove_metadata() | Rimuove i metadati di questa istanza immagine impostando il valore di [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) a **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Sostituisce un colore con un altro con differenza consentita e preserva il valore alfa originale per mantenere bordi lisci. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Ridimensiona l'immagine. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Regola le dimensioni dell'immagine utilizzando un tipo di ridimensionamento specificato, che determina come <br/>            viene eseguita l'operazione di ridimensionamento. Questo metodo offre flessibilità nel ridimensionare <br/>            le immagini secondo diversi algoritmi o tecniche. Scegliendo il <br/>            tipo di ridimensionamento appropriato, è possibile ottenere il bilanciamento desiderato tra la qualità dell'immagine <br/>            e l'efficienza computazionale in base a requisiti o preferenze specifici. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Ridimensiona l'immagine applicando impostazioni specifiche per mantenere le dimensioni desiderate <br/>            e il rapporto d'aspetto. Personalizzando le impostazioni dell'immagine, è possibile ridimensionare efficacemente <br/>            l'immagine garantendo al contempo una qualità visiva ottimale e la compatibilità con <br/>            diversi dispositivi di visualizzazione o applicazioni. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Ridimensiona l'immagine. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Ridimensiona l'immagine. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Ridimensiona l'altezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Ridimensiona l'altezza proporzionalmente. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Ridimensiona l'altezza proporzionalmente. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_93) | Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/). |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_94) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_95) | Ridimensiona la larghezza proporzionalmente. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_96) | Ridimensiona la larghezza proporzionalmente. |
| [rotate(angle)](#rotate_angle_97) | Ruota l'immagine attorno al centro. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_98) | Ruota l'immagine attorno al suo centro di un angolo specificato mantenendo la proporzionalità del ridimensionamento <br/>            e preservando il colore di sfondo. Questo metodo consente una manipolazione precisa dell'immagine, assicurando che la rotazione mantenga l'equilibrio visivo <br/>            e la coerenza con il colore di sfondo specificato. È ideale per attività in cui <br/>            è necessaria una rotazione accurata attorno al centro, come la correzione dell'orientamento <br/>            o regolazioni artistiche. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_99) | Il metodo \"RotateFlip\" consente operazioni di rotazione e capovolgimento sull'immagine. Offre una funzionalità versatile per manipolare l'orientamento dell'immagine, permettendo agli utenti <br/>            di eseguire rotazioni e capovolgimenti secondo le loro esigenze, facilitando <br/>            attività di elaborazione delle immagini efficienti all'interno delle applicazioni software. |
| save() | Salva i dati dell'immagine nello stream sottostante. |
| [save(file_path)](#save_file_path_100) | Salva l'immagine nella posizione file specificata. |
| [save(file_path, options)](#save_file_path_options_101) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_102) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save(file_path, over_write)](#save_file_path_over_write_103) | Salva i dati dell'oggetto nella posizione file specificata. |
| [save(stream)](#save_stream_104) | I dati di salvataggio. |
| [save(stream, options_base)](#save_stream_options_base_105) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_106) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_107) | Salva i pixel ARGB a 32 bit. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_108) | Salva i pixel. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_109) | Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_110) | Salva i pixel (metodo specifico del formato). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_111) | Salva i dati grezzi. |
| [save_to_stream(stream)](#save_to_stream_stream_112) | Salva i dati dell'oggetto nello stream specificato. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_113) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114) | Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_115) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_116) | Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_117) | Imposta un pixel immagine a 32 bit ARGB per la posizione specificata. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | Imposta la tavolozza dell'immagine. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | Imposta un pixel dell'immagine per la posizione specificata. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_121) | Cerca di impostare un'istanza _metadata_, se questa istanza di [Image](/imaging/python-net/aspose.imaging/image/) supporta e implementa l'istanza [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_123) | Scrive l'intera riga di scansione all'indice di riga di scansione specificato. |


### Constructor: TgaImage(path) {#TgaImage_path_1}


```
 TgaImage(path) 
```

Inizializza un nuovo oggetto [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) utilizzando il percorso file fornito per <br/>            caricare il contenuto dell'immagine. Questo costruttore inizializza in modo efficiente l'istanza dell'immagine <br/>            consentendo un accesso senza interruzioni ai file immagine TGA, semplificando l'integrazione <br/>            nel flusso di lavoro della tua applicazione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| percorso | string | Il percorso per caricare un'immagine. |

### Constructor: TgaImage(raster_image) {#TgaImage_raster_image_2}


```
 TgaImage(raster_image) 
```

Crea una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) fornendo un raster <br/>            oggetto immagine. Questo costruttore facilita l'integrazione diretta delle immagini raster esistenti <br/>            nel formato immagine TGA, ottimizzando il processo di conversione per <br/>            una compatibilità migliorata all'interno dei tuoi sistemi software.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |


**See also:**

**[Example # 1](#example_216)**: Loading of the PNG image, conversion of it to the TgaImage and saving as a TG...


### Constructor: TgaImage(stream) {#TgaImage_stream_3}


```
 TgaImage(stream) 
```

Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) utilizzando uno stream per <br/>            caricare l'immagine. Questo costruttore consente un'integrazione senza interruzioni dei dati immagine <br/>            provenienti da stream, facilitando una gestione efficiente e l'elaborazione delle immagini TGA all'interno <br/>            delle tue applicazioni software.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso per caricare un'immagine. |

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


### Method: clone() {#clone__19}


```
 clone() 
```

Produce un duplicato dell'istanza corrente, generando un nuovo oggetto che clona <br/>            tutti gli attributi e le proprietà dell'originale. Questo metodo facilita la <br/>            creazione di copie identiche, garantendo l'integrità dei dati e preservando lo stato dell' <br/>            istanza corrente senza influire sull'oggetto originale.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | Restituisce un nuovo oggetto che è una copia dell'istanza corrente. |


### Method: clone(tga_image) {#clone_tga_image_20}


```
 clone(tga_image) 
```

Replica le proprietà di un altro oggetto [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/), creando una <br/>            nuova istanza con attributi identici. Questa operazione garantisce la preservazione <br/>            dell'integrità dei dati e facilita la duplicazione delle proprietà dell'immagine senza <br/>            modificare l'oggetto di origine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| tga_image | [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | Altri [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |

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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_30}


```
 create_from_image(raster_image) 
```

Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'immagine raster. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


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

Inizializza una nuova istanza della classe [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso per caricare un'immagine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_34}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Ritaglia l'immagine specificando gli spostamenti per i bordi sinistro, destro, superiore e inferiore <br/>            . Questo metodo consente di tagliare l'immagine spostando i suoi bordi <br/>            indipendentemente lungo gli assi orizzontale e verticale. Regolando questi spostamenti, <br/>            è possibile controllare con precisione quali parti dell'immagine conservare, <br/>            ritagliandola efficacemente alle dimensioni desiderate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| left_shift | int | Lo shift a sinistra. |
| right_shift | int | Lo shift a destra. |
| top_shift | int | Lo shift superiore. |
| bottom_shift | int | Lo shift inferiore. |

### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Ritaglia l'immagine a una regione specificata. Questo metodo consente di definire un <br/>            area rettangolare all'interno dell'immagine da conservare, scartando il resto. Questa operazione <br/>            è utile per focalizzarsi su contenuti specifici dell'immagine o rimuovere parti indesiderate.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Esegue il dithering sull'immagine corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Il metodo di dithering. |
| bits_count | int | Il conteggio finale dei bit per il dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_38}


```
 embed_digital_signature(password) 
```

Incorpora una firma digitale basata sulla password fornita nell'immagine usando la steganografia.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| password | string | La password usata per generare i dati della firma digitale. |

### Method: filter(rectangle, options) {#filter_rectangle_options_39}


```
 filter(rectangle, options) 
```

Filtra il rettangolo specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Le opzioni. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_40}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_41}


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


### Method: get_default_options(args) {#get_default_options_args_42}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_43}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Ottiene l'array predefinito di pixel usando il caricatore di pixel parziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo per cui ottenere i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_45}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_46}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_47}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_48}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_49}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_50}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_51}


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


### Method: get_original_options() {#get_original_options__52}


```
 get_original_options() 
```

Ottiene le opzioni basate sulle impostazioni originali del file.<br/>            Questo può essere utile per mantenere inalterata la profondità di bit e altri parametri dell'immagine originale.<br/>            Ad esempio, se carichiamo un'immagine PNG in bianco e nero a 1 bit per pixel e poi la salviamo usando il<br/>            metodo [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), verrà generata un'immagine PNG di output a 8 bit per pixel.<br/>            Per evitarlo e salvare l'immagine PNG a 1 bit per pixel, utilizza questo metodo per ottenere le opzioni di salvataggio corrispondenti e passale<br/>            al metodo [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) come secondo parametro.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni basate sulle impostazioni del file originale. |


### Method: get_pixel(x, y) {#get_pixel_x_y_53}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_54}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_55}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_56}


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


### Method: get_skew_angle() {#get_skew_angle__57}


```
 get_skew_angle() 
```

Ottiene l'angolo di inclinazione.<br/>            Questo metodo è applicabile ai documenti di testo scansionati, per determinare l'angolo di inclinazione durante la scansione.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | L'angolo di inclinazione, in gradi. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_58}


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


### Method: load(file_path)  [static] {#load_file_path_59}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_60}


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


### Method: load(stream)  [static] {#load_stream_61}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_62}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_63}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_64}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_65}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_66}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 32 bit (per blocchi).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo da cui caricare i pixel. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Il caricatore parziale di pixel. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Carica parzialmente pixel ARGB a 64 bit per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Il caricatore di pixel ARGB a 64 bit. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_69}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Carica pixel parzialmente per pacchetti.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo desiderato. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Il caricatore di pixel. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_70}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_73}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_74}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_75}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_76}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalizza l'angolo.<br/>            Questo metodo è applicabile ai documenti di testo scansionati per eliminare la scansione inclinata.<br/>            Questo metodo utilizza i metodi [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) e [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata in base alle proiezioni del rettangolo ruotato (punti d'angolo); altrimenti le dimensioni rimarranno inalterate e solo il contenuto interno dell'immagine verrà ruotato. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_77}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_78}


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
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore vecchio da sostituire. |
| old_color_diff | System.Byte | Differenza consentita nel colore vecchio per poter ampliare la tonalità del colore sostituito. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuovo colore con cui sostituire il colore vecchio. |

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

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nuovo colore con cui sostituire i colori non trasparenti. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Sostituisce tutti i colori non trasparenti con un nuovo colore e preserva il valore alfa originale per mantenere bordi lisci.<br/>            Nota: se lo utilizzi su immagini senza trasparenza, tutti i colori saranno sostituiti con un unico colore.

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

Regola le dimensioni dell'immagine utilizzando un tipo di ridimensionamento specificato, che determina come <br/>            viene eseguita l'operazione di ridimensionamento. Questo metodo offre flessibilità nel ridimensionare <br/>            le immagini secondo diversi algoritmi o tecniche. Scegliendo il <br/>            tipo di ridimensionamento appropriato, è possibile ottenere il bilanciamento desiderato tra la qualità dell'immagine <br/>            e l'efficienza computazionale in base a requisiti o preferenze specifici.

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

Ridimensiona l'immagine applicando impostazioni specifiche per mantenere le dimensioni desiderate <br/>            e il rapporto d'aspetto. Personalizzando le impostazioni dell'immagine, è possibile ridimensionare efficacemente <br/>            l'immagine garantendo al contempo una qualità visiva ottimale e la compatibilità con <br/>            diversi dispositivi di visualizzazione o applicazioni.

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

Ridimensiona l'altezza proporzionalmente.

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

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_93}


```
 resize_width_proportionally(new_width) 
```

Ridimensiona la larghezza proporzionalmente. Viene utilizzato il valore predefinito [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_94}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Tipo di ridimensionamento. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_95}


```
 resize_width_proportionally(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_96}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ridimensiona la larghezza proporzionalmente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_width | int | La nuova larghezza. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Le impostazioni di ridimensionamento dell'immagine. |

### Method: rotate(angle) {#rotate_angle_97}


```
 rotate(angle) 
```

Ruota l'immagine attorno al centro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_98}


```
 rotate(angle, resize_proportionally, background_color) 
```

Ruota l'immagine attorno al suo centro di un angolo specificato mantenendo la proporzionalità del ridimensionamento <br/>            e preservando il colore di sfondo. Questo metodo consente una manipolazione precisa dell'immagine, assicurando che la rotazione mantenga l'equilibrio visivo <br/>            e la coerenza con il colore di sfondo specificato. È ideale per attività in cui <br/>            è necessaria una rotazione accurata attorno al centro, come la correzione dell'orientamento <br/>            o regolazioni artistiche.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| angle | float | L'angolo di rotazione in gradi. I valori positivi ruoteranno in senso orario. |
| resize_proportionally | bool | se impostato su <c>true</c> la dimensione dell'immagine verrà modificata<br/>            in base alle proiezioni del rettangolo ruotato (punti d'angolo) in altri<br/>            casi, lasciando le dimensioni inalterate e solo<br/>            i contenuti dell'immagine __internal__ verranno ruotati. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Colore dello sfondo. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_99}


```
 rotate_flip(rotate_flip_type) 
```

Il metodo \"RotateFlip\" consente operazioni di rotazione e capovolgimento sull'immagine. Offre una funzionalità versatile per manipolare l'orientamento dell'immagine, permettendo agli utenti <br/>            di eseguire rotazioni e capovolgimenti secondo le loro esigenze, facilitando <br/>            attività di elaborazione delle immagini efficienti all'interno delle applicazioni software.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Il tipo di rotazione e capovolgimento. |

### Method: save(file_path) {#save_file_path_100}


```
 save(file_path) 
```

Salva l'immagine nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare l'immagine. |

### Method: save(file_path, options) {#save_file_path_options_101}


```
 save(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_102}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_103}


```
 save(file_path, over_write) 
```

Salva i dati dell'oggetto nella posizione file specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso file in cui salvare i dati dell'oggetto. |
| over_write | bool | se impostato su <c>true</c> sovrascrive il contenuto del file, altrimenti verrà effettuata un'aggiunta. |

### Method: save(stream) {#save_stream_104}


```
 save(stream) 
```

I dati di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Lo stream. |

### Method: save(stream, options_base) {#save_stream_options_base_105}


```
 save(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_106}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_107}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Salva i pixel ARGB a 32 bit.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | L'array di pixel ARGB a 32 bit. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_108}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Salva i pixel.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixel | int[] | I pixel CMYK presentati come valori interi a 32 bit. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_109}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Salva i pixel.<br/>            Questo metodo è deprecato. Si prega di utilizzare in modo più efficace il metodo [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | L'array di pixel CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_110}


```
 save_pixels(rectangle, pixels) 
```

Salva i pixel (metodo specifico del formato).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Il rettangolo in cui salvare i pixel. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | L'array di pixel ARGB a 32 bit. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_111}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_112}


```
 save_to_stream(stream) 
```

Salva i dati dell'oggetto nello stream specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'oggetto. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_113}


```
 save_to_stream_with_options(stream, options_base) 
```

Salva i dati dell'immagine nello stream specificato nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| stream | _io.BufferedRandom | Il flusso in cui salvare i dati dell'immagine. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni di salvataggio. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_115}


```
 save_with_options(file_path, options) 
```

Salva i dati dell'oggetto nella posizione file specificata nel formato file indicato secondo le opzioni di salvataggio.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| file_path | string | Il percorso del file. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Le opzioni. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_116}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_117}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_118}


```
 set_palette(palette, update_colors) 
```

Imposta la tavolozza dell'immagine.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La tavolozza da impostare. |
| update_colors | bool | se impostato su <c>true</c> i colori verranno aggiornati secondo la nuova tavolozza; altrimenti gli indici dei colori rimarranno invariati. Nota che gli indici invariati possono causare il crash dell'immagine al caricamento se alcuni indici non hanno voci corrispondenti nella tavolozza. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_119}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_120}


```
 set_resolution(dpi_x, dpi_y) 
```

Imposta la risoluzione per questo [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| dpi_x | float | La risoluzione orizzontale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La risoluzione verticale, in punti per pollice, del [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_121}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Scrive l'intera riga di scansione all'indice di riga di scansione specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| scan_line_index | int | Indice basato su zero della riga di scansione. |
| argb_32_pixels | int[] | L'array di colori ARGB a 32 bit da scrivere. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_123}


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
### Saving of the JPG image as a TGA image. {#example_215}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import TgaOptions

with Image.load("test.jpg") as image:
	image.save("test.tga"", TgaOptions())
	

```

### Loading of the PNG image, conversion of it to the TgaImage and saving as a TGA image. {#example_216}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.fileformats.tga import TgaImage

with as_of(Image.load("test.png"), RasterImage) as image:
	with TgaImage(image) as tgaImage:
		tgaImage.save("test.tga")


```

