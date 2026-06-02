---
title: "BigTiffImage-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/
---

**Summary:** With the [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) class you can effortlessly manipulate<br/>            BigTiff image format files. Our API offering seamless handling and customization<br/>            options, ensuring optimal processing of large-scale image data with versatile features<br/>            tailored to your specific requirements.

**Module:** [aspose.imaging.fileformats.bigtiff](/imaging/python-net/aspose.imaging.fileformats.bigtiff/)

**Full Name:** aspose.imaging.fileformats.bigtiff.BigTiffImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, TiffImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BigTiffImage(frame)](#BigTiffImage_frame_1) | Skapa en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) genom att initiera<br/>            den med en TiffFrame-parameter. Ideal för utvecklare som söker ett bekvämt<br/>            sätt att arbeta med BigTiffImage-objekt, vilket säkerställer flexibilitet och enkel integration<br/>            i deras projekt. |
| [BigTiffImage(frames)](#BigTiffImage_frames_2) | Börja använda klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) sömlöst genom att<br/>            initiera en ny instans med en lista av TiffFrames-parameter.<br/>            Perfekt för utvecklare som söker en enkel metod för att arbeta med<br/>            BigTiffImage-objekt som innehåller flera ramar, vilket säkerställer effektivitet i deras projekt. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | Hantera den aktiva ramen sömlöst, vilket underlättar dynamisk navigering och <br/>            manipulation inom den angivna kontexten. Ge din applikation möjlighet att interagera <br/>            effektivt med multimediainnehåll, vilket förbättrar användarengagemang och produktivitet. |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämtar bildens bitar per pixel. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Växla byteordningen för TIFF-filer sömlöst, vilket säkerställer exakt kontroll över <br/>            datainterpretation. Ge dina applikationer flexibiliteten att anpassa sig till <br/>            olika filspecificeringar, vilket förbättrar kompatibilitet och effektivitet i databehandling. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämtar filformatet för denna [Image](/imaging/python-net/aspose.imaging/image/) instans. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | Hämta en array av [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) instanser, vilket möjliggör omfattande <br/>            åtkomst och manipulation av enskilda ramar i TIFF-bilden. Utnyttja <br/>            kraften i denna array för att effektivisera bildbehandlingsarbetsflöden, vilket säkerställer exakt <br/>            kontroll och optimering av visuellt innehåll. |
| has_alpha | bool | r | Bestäm om bilden har en alfakanal, vilket ger viktig information <br/>            för renderings- och sammansättningsoperationer. Integrera denna funktion för att optimera <br/>            visuella bearbetningsarbetsflöden, vilket säkerställer korrekt representation och manipulation av <br/>            transparenta element. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| has_transparent_color | bool | r/w | Hämtar ett värde som indikerar om bilden har en transparent färg. |
| height | int | r | Hämtar objektets höjd. |
| horizontal_resolution | float | r/w | Hämta den horisontella upplösningen för den angivna [Image](/imaging/python-net/aspose.imaging/image/) i pixlar <br/>            per tum, vilket underlättar exakt justering och renderingsmöjligheter. Få <br/>            enkel åtkomst till viktig bildmetadata, vilket möjliggör strömlinjeformade bildbehandlingsarbetsflöden för förbättrade användarupplevelser. |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar eller anger XMP-data från ramen. |
| page_count | int | r | Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar <br/> effektiv navigering och hantering av flersidigt innehåll. Integrera denna <br/> funktion för att förbättra användarupplevelsen, vilket möjliggör sömlös åtkomst till <br/> omfattande dokumentstrukturer. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Få åtkomst till dokumentets sidor sömlöst, vilket möjliggör dynamisk navigering och <br/>            manipulation inom innehållsstrukturen. Ge din applikation effektiv <br/>            åtkomst till enskilda sidor, vilket underlättar strömlinjeformad dokumentbehandling och <br/>            förbättrad användarinteraktion. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Indikera om komponenter kräver premultiplikation, vilket säkerställer effektiv hantering <br/>            av visuella element. Förbättra renderingsprocesser genom att växla denna egenskap, <br/>            vilket strömlinjeformar grafiska arbetsflöden för optimerad prestanda. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Hämtar eller anger den anpassade färgkonvertern |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Hämtar de aktuella inställningarna för rådata. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Hämtar eller anger den indexerade färgkonvertern |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar bildens transparenta färg. |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| vertical_resolution | float | r/w | Få åtkomst till den vertikala upplösningen för den angivna [Image](/imaging/python-net/aspose.imaging/image/) i pixlar per <br/>            tum, vilket möjliggör exakt justering och renderingsoptimeringar. Använd viktig <br/>            bilddata enkelt för att effektivisera bildbehandlingsarbetsflöden, vilket säkerställer <br/>            överlägsen kvalitet och prestanda i dina applikationer. |
| width | int | r | Hämtar objektets bredd. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(image)](#add_image_1) | Lägg till ramarna från den angivna bilden sömlöst i den aktuella ramen, <br/>            konsolidera deras innehåll och förbättra kompositionsflexibiliteten. Integrera <br/>            denna metod för att effektivisera ramhantering och manipulation i din <br/>            applikation, vilket underlättar effektiv hantering av fler-ramsbilder. |
| [add_frame(frame)](#add_frame_frame_2) | Inkludera den angivna ramen sömlöst i bilden, vilket utökar dess innehåll <br/>            och mångsidighet. Använd denna metod för att förbättra bildkomposition och hantering, <br/>            vilket möjliggör effektiv hantering av fler-ramsbilder i din applikation. |
| [add_frames(frames)](#add_frames_frames_3) | Integrera arrayen av ramar sömlöst i bilden, vilket berikar dess innehåll och <br/>            mångsidighet. Använd denna metod för att förbättra bildkomposition och hantering, <br/>            vilket möjliggör effektiv hantering av fler-ramsbilder i din applikation. |
| [add_page(page)](#add_page_page_4) | Utöka enkelt din BigTiff-bild genom att lägga till en ny sida med denna intuitiva metod.<br/>            Perfekt för utvecklare som vill dynamiskt förbättra innehållet i sina fler-sidiga bilder. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Implementera _brightness_-justering för bilden, vilket möjliggör <br/>            modifiering av den övergripande luminansnivån. Incorporera denna metod i ditt bild-<br/>            bearbetningsarbetsflöde för att förbättra synligheten och höja den visuella kvaliteten på <br/>            bilder i din applikation. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | Förbättra kontrasten för [Image](/imaging/python-net/aspose.imaging/image/) instansen, <br/>            förstärka skillnaderna mellan dess ljusa och mörka områden. Integrera denna <br/>            funktion för att förbättra den visuella klarheten och den övergripande kvaliteten på bilden <br/>            i din applikation. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Applicera gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå \n            önskad färgbalans. Inkludera denna metod i ditt bildbehandlings-\n            arbetsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i efterföljande \n            analys- eller visningsuppgifter inom din applikation. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Utför gamma‑korrektion på bilden med individuella koefficienter för röda, \n            gröna och blå kanaler, vilket möjliggör finjusterade justeringar av färgbalans \n            och kontrast. Integrera denna metod i din bildbehandlingspipeline för att \n            uppnå exakt kontroll över färgåtergivning och förbättra den visuella äktheten inom \n            din applikation. |
| align_resolutions() | Implementera hjälpmethoden AlignResolutions för att synkronisera horisontella och \n            vertikala upplösningar, vilket säkerställer enhetlighet i bilddimensioner. Denna funktionalitet \n            underlättar strömlinjeformade bildbehandlingsarbetsflöden genom att harmonisera upplösnings-\n            parametrar, optimera visuell kvalitet och konsistens över olika plattformar och \n            enheter. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| auto_brightness_contrast() | Utför automatisk adaptiv ljusstyrke‑ och kontrastnormalisering för hela bilden. |
| auto_rotate() | Rotera automatiskt bilden baserat på orienteringsdata som extraheras från Exif <br/>            metadata. Denna metod säkerställer att bilder visas i korrekt orientering, <br/>            förbättrar användarupplevelsen och eliminerar behovet av manuella justeringar. Genom <br/>            att analysera Exif‑information roteras bilden därefter, vilket ger en sömlös <br/>            visningsupplevelse på olika plattformar och enheter. Denna automatiserade rotationsprocess <br/>            förenklar bildhantering och förbättrar den övergripande användbarheten, särskilt när <br/>            man hanterar stora bildsatser med varierande orienteringar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Implementera binarisering på bilden med Bradleys adaptiva tröskelalgoritm \n            med integrerad bildtröskling. Detta tillvägagångssätt beräknar dynamiskt \n            lokala tröskelvärden baserat på bildens omgivning, vilket förbättrar anpassningsförmågan till \n            varierande ljusförhållanden och säkerställer robust segmentering för efterföljande \n            bearbetningsuppgifter inom din applikation. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Applicera binarisering på bilden med ett fördefinierat tröskelvärde, vilket konverterar den till \n            en binär bild med tydliga förgrunds- och bakgrundsområden. Inkludera denna \n            metod i ditt bildbehandlingsarbetsflöde för att underlätta segmentering och funktionsextraktion, \n            vilket förbättrar noggrannheten och effektiviteten i bildanalys inom \n            din applikation. |
| binarize_otsu() | Använd Otsu‑tröskling för att utföra binarisering på bilden, automatiskt \n            bestämma det optimala tröskelvärdet baserat på bildens histogram. Integrera \n            denna metod i ditt bildbehandlingsarbetsflöde för att uppnå effektiv segmentering \n            och funktionsextraktion, vilket förbättrar noggrannheten och pålitligheten i bildanalys-\n            uppgifter inom din applikation. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | Blandar denna bildinstans med _overlay_-bilden. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | Blandar denna bildinstans med _overlay_-bilden. |
| cache_data() | Cachar data privat. |
| [can_load(file_path)](#can_load_file_path_15) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_17) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_save(options)](#can_save_options_22) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(files)](#create_files_23) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_26) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_27) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_28) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_29) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_files(files)](#create_from_files_files_30) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_31) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_images(images)](#create_from_images_images_32) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_33) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create_with_frame(frame)](#create_with_frame_frame_34) | Initierar en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/). |
| [create_with_frames(frames)](#create_with_frames_frames_35) | Initierar en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | Utför beskärning av bilden genom att ange förskjutningar åt vänster, höger, upp och \n            ner. Denna metod möjliggör exakt urval av önskad del av bilden, underlättar effektiv borttagning av oönskade områden och fokuserar på \n            väsentligt innehåll. Integrera denna funktionalitet i din bildbehandlings-\n            pipeline för att förbättra klarhet och komposition efter behov inom din applikation. |
| [crop(rectangle)](#crop_rectangle_37) | Beskär bilden med ett angivet rektangulärt område, vilket möjliggör exakt urval av \n            önskat innehåll. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att \n            effektivt ta bort oönskade områden och fokusera på väsentliga detaljer, vilket förbättrar den \n            övergripande klarheten och kompositionen av bilden. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | Utför dithering på den aktuella bilden för att förbättra dess visuella kvalitet och minska \n            färgbandningsartefakter. Integrera denna metod i ditt bildbehandlingsarbetsflöde \n            för att säkerställa mjukare övergångar mellan färger, vilket resulterar i förbättrat övergripande bild-\n            utseende och klarhet. |
| [embed_digital_signature(password)](#embed_digital_signature_password_40) | Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden. |
| [filter(rectangle, options)](#filter_rectangle_options_41) | Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bild<br/>            behandlingsfilter för att förbättra eller ändra det valda området. Integrera denna metod <br/>            i ditt bildmanipuleringsflöde för att uppnå riktade förbättringar eller <br/>            transformationer i din applikation. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_42) | Hämtar en bildpixel i 32-bitars ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_43) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_44) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_45) | Hämtar standardpixelarrayen med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46) | Hämtar standardarrayen för rådata med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_47) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_48) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_49) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_50) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_51) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_52) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_53) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__54) | Hämta alternativ som härrör från de ursprungliga filinställningarna, vilket underlättar sömlös \n            bevarande av nyckelparametrar såsom bitdjup och andra väsentliga attribut för \n            den ursprungliga bilden. Använd denna metod för att upprätthålla trohet och konsistens i \n            bildbehandlingsuppgifter, vilket säkerställer optimala resultat utan onödiga förändringar.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med <br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem <br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_55) | Hämtar en bildpixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_56) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_57) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_58) | Konverterar till aps. |
| [get_skew_angle()](#get_skew_angle__59) | Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| grayscale() | Konvertera bilden till dess gråskalerepresentation, vilket omvandlar den till en \n            enkankalig bild där varje pixel representerar intensitet. Integrera denna metod \n            i din bildbehandlingspipeline för att förenkla analys och förbättra \n            kompatibiliteten med gråskale‑baserade algoritmer, vilket underlättar olika dator‑\n            visions‑ och bildanalysuppgifter inom din applikation. |
| [insert_frame(index, frame)](#insert_frame_index_frame_60) | Infoga den nya ramen på det angivna indexet i ramsekvensen, vilket säkerställer \n            exakt kontroll över ramordningen. Använd denna metod för att hantera ramsekvenser \n            effektivt, vilket underlättar dynamisk manipulation och organisering av bild‑\n            innehåll inom din applikation. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet. |
| [load(file_path)](#load_file_path_62) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_64) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_65) | Läser in en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | Läser in 32-bitars ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | Läser in 64-bitars ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | Läser in pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | Läser in 32-bitars ARGB‑pixlar delvis (i block). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | Läser in 64-bitars ARGB‑pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Läser in pixlar delvis i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Läser in pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Läser in rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Läser in rådata. |
| [load_stream(stream)](#load_stream_stream_76) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| normalize_angle() | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Använd metoden NormalizeAngle som är speciellt utformad för skannade textdokument \n            för att korrigera snedvridna skanningar, vilket säkerställer exakt justering. Integrera sömlöst \n            denna funktionalitet i dina textbehandlingsarbetsflöden för att förbättra \n            dokumentets läsbarhet och kvalitet, vilket ökar den övergripande effektiviteten i textigenkänning \n            och analysuppgifter.<br/>            Denna metod använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)‑metoder. |
| normalize_histogram() | Normaliserar bildens histogram — justera pixelvärden för att använda hela tillgängliga intervallet. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [remove_frame(frame)](#remove_frame_frame_82) | Ta effektivt bort den angivna ramen från bildsekvensen, vilket underlättar \n            strömlinjeformad ramhantering inom din applikation. Integrera denna funktionalitet \n            för att förbättra precision och flexibilitet i rammanipulation, vilket säkerställer sömlös \n            organisering och presentation av bildinnehåll. |
| [remove_frame(index)](#remove_frame_index_83) | Tar bort ramen enligt dess index. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_84) | Tar bort ramen enligt dess index. |
| remove_metadata() | Tar bort metadata för denna bildinstans genom att sätta värdena för [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) och [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) till **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_85) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_86) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_87) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_frame(index, new_frame)](#replace_frame_index_new_frame_88) | Ersätt ramen på den angivna positionen med en annan ram sömlöst, \n            vilket underlättar dynamisk ramhantering inom bildsekvensen. Integrera denna \n            metod för att förbättra flexibilitet och precision i rammanipulation, vilket säkerställer \n            optimal organisering och presentation av bildinnehåll inom din applikation. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_89) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_90) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_91) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_92) | Utför en proportionell storleksändring av bilden, bevara dess bildförhållande \n            samtidigt som dess dimensioner justeras. Använd denna metod för att dynamiskt skala bilder \n            inom din applikation, vilket säkerställer en konsekvent visuell återgivning av innehållets \n            integritet.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_93) | Justera bildens storlek baserat på angivna inställningar, vilket möjliggör exakt \n            kontroll över dimensioner, bildförhållande och skalningsbeteende. Integrera denna \n            metod i ditt bildbehandlingsarbetsflöde för att uppnå anpassade storleksändringar \n            som är skräddarsydda för din applikations specifika krav. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_94) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_95) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_96) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_97) | Utför en proportionell justering av bildens höjd, bevara dess bildförhållande \n            för konsekvent visuell integritet. Använd denna metod för att dynamiskt ändra storlek på \n            bilder inom din applikation, vilket säkerställer optimal visning över olika plattformar \n            och enheter utan att kompromissa med innehållets kvalitet. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_98) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_99) | Ändrar höjden proportionellt. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_100) | Utför en proportionell storleksändring av bilden, bevara dess bildförhållande \n            samtidigt som dess dimensioner justeras. Använd denna metod för att dynamiskt skala bilder \n            inom din applikation, vilket säkerställer en konsekvent visuell återgivning av innehållets \n            integritet.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_101) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_102) | Justera bildens bredd samtidigt som dess bildförhållande behålls, vilket säkerställer \n            proportionell storleksändring för optimal visuell presentation. Använd denna metod för \n            att dynamiskt skala bilder inom din applikation, vilket underlättar enhetlig och \n            estetiskt tilltalande återgivning över olika visningssammanhang. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_103) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_104) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_105) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_106) | Rotera bilden kring dess mittpunkt med en angiven vinkel, vilket möjliggör exakt \n            orienteringsjustering. Inkludera denna funktionalitet i din bildbehandlings-\n            pipeline för att underlätta korrekta transformationer, vilket säkerställer optimal justering och \n            presentation av visuellt innehåll inom din applikation. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_107) | Utför rotation, spegling eller en kombination av båda operationerna uteslutande på den \n            aktiva ramen. Denna metod möjliggör exakt manipulation av enskilda ramar inom \n            bildsekvensen, vilket ökar flexibiliteten i bildredigering och komposition inom \n            din applikation. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_108) | Roterar alla flip. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_109) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_110) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_111) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_112) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_113) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_114) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_115) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_116) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_117) | Sparar pixlarna. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_118) | Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_119) | Sparar pixlarna internt. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_120) | Sparar rådata. |
| [save_to_stream(stream)](#save_to_stream_stream_121) | Sparar bilden till en ström |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_122) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_124) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_125) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_126) | Ställer in en bildpixel i 32-bit ARGB för den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_127) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_128) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_129) | Ställer in upplösningen för den angivna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), vilket möjliggör <br/>            exakt kontroll över bildrendering och displayegenskaper. Integrera denna <br/>            funktion för att optimera visuell output och säkerställa kompatibilitet med olika <br/>            utdataenheter och plattformar, vilket förbättrar den övergripande användarupplevelsen. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_130) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_132) | Skriver hela skanningsraden till det angivna skanningsradindexet. |


### Constructor: BigTiffImage(frame) {#BigTiffImage_frame_1}


```
 BigTiffImage(frame) 
```

Skapa en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) genom att initiera<br/>            den med en TiffFrame-parameter. Ideal för utvecklare som söker ett bekvämt<br/>            sätt att arbeta med BigTiffImage-objekt, vilket säkerställer flexibilitet och enkel integration<br/>            i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Tiff-ramen att initiera bilden med. |

### Constructor: BigTiffImage(frames) {#BigTiffImage_frames_2}


```
 BigTiffImage(frames) 
```

Börja använda klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) sömlöst genom att<br/>            initiera en ny instans med en lista av TiffFrames-parameter.<br/>            Perfekt för utvecklare som söker en enkel metod för att arbeta med<br/>            BigTiffImage-objekt som innehåller flera ramar, vilket säkerställer effektivitet i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramarna. |

### Method: add(image) {#add_image_1}


```
 add(image) 
```

Lägg till ramarna från den angivna bilden sömlöst i den aktuella ramen, <br/>            konsolidera deras innehåll och förbättra kompositionsflexibiliteten. Integrera <br/>            denna metod för att effektivisera ramhantering och manipulation i din <br/>            applikation, vilket underlättar effektiv hantering av fler-ramsbilder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | Källbilden. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

Inkludera den angivna ramen sömlöst i bilden, vilket utökar dess innehåll <br/>            och mångsidighet. Använd denna metod för att förbättra bildkomposition och hantering, <br/>            vilket möjliggör effektiv hantering av fler-ramsbilder i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramen att lägga till. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

Integrera arrayen av ramar sömlöst i bilden, vilket berikar dess innehåll och <br/>            mångsidighet. Använd denna metod för att förbättra bildkomposition och hantering, <br/>            vilket möjliggör effektiv hantering av fler-ramsbilder i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramar-arrayen att lägga till. |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Utöka enkelt din BigTiff-bild genom att lägga till en ny sida med denna intuitiva metod.<br/>            Perfekt för utvecklare som vill dynamiskt förbättra innehållet i sina fler-sidiga bilder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sidan att lägga till. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Implementera _brightness_-justering för bilden, vilket möjliggör <br/>            modifiering av den övergripande luminansnivån. Incorporera denna metod i ditt bild-<br/>            bearbetningsarbetsflöde för att förbättra synligheten och höja den visuella kvaliteten på <br/>            bilder i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

Förbättra kontrasten för [Image](/imaging/python-net/aspose.imaging/image/) instansen, <br/>            förstärka skillnaderna mellan dess ljusa och mörka områden. Integrera denna <br/>            funktion för att förbättra den visuella klarheten och den övergripande kvaliteten på bilden <br/>            i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Applicera gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå \n            önskad färgbalans. Inkludera denna metod i ditt bildbehandlings-\n            arbetsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i efterföljande \n            analys- eller visningsuppgifter inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Utför gamma‑korrektion på bilden med individuella koefficienter för röda, \n            gröna och blå kanaler, vilket möjliggör finjusterade justeringar av färgbalans \n            och kontrast. Integrera denna metod i din bildbehandlingspipeline för att \n            uppnå exakt kontroll över färgåtergivning och förbättra den visuella äktheten inom \n            din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma_red | float | Gamma för röd kanal koefficient |
| gamma_green | float | Gamma för grön kanal koefficient |
| gamma_blue | float | Gamma för blå kanalkoefficient |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


```
 analyze_percentage_digital_signature(password) 
```

Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att extrahera den inbäddade datan. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Procentuell likhetsvärde. |


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s fönster av pixlar<br/>                centrerat kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

Implementera binarisering på bilden med Bradleys adaptiva tröskelalgoritm \n            med integrerad bildtröskling. Detta tillvägagångssätt beräknar dynamiskt \n            lokala tröskelvärden baserat på bildens omgivning, vilket förbättrar anpassningsförmågan till \n            varierande ljusförhållanden och säkerställer robust segmentering för efterföljande \n            bearbetningsuppgifter inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s fönster av pixlar<br/>            centrerat kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Applicera binarisering på bilden med ett fördefinierat tröskelvärde, vilket konverterar den till \n            en binär bild med tydliga förgrunds- och bakgrundsområden. Inkludera denna \n            metod i ditt bildbehandlingsarbetsflöde för att underlätta segmentering och funktionsextraktion, \n            vilket förbättrar noggrannheten och effektiviteten i bildanalys inom \n            din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | System.Byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas ett värde av<br/>            255 till den, annars 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


```
 blend(origin, overlay, overlay_alpha) 
```

Blandar denna bildinstans med _overlay_-bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Överlagringsbilden. |
| overlay_alpha | System.Byte | Alfa för överlagring. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Blandar denna bildinstans med _overlay_-bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | Bakgrundsbildens blandningsursprung. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Överlagringsbilden. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Överlagringsområdet. |
| overlay_alpha | System.Byte | Alfa för överlagring. |

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


```
 can_load(file_path) 
```

Bestämmer om bilden kan läsas in från den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna filen; annars <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


```
 can_load(file_path, load_options) 
```

Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna filen; annars <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_17}


```
 can_load(stream) 
```

Bestämmer om bilden kan läsas in från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna strömmen; annars <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


```
 can_load(stream, load_options) 
```

Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att läsa från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna strömmen; annars <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


```
 can_load_stream(stream) 
```

Bestämmer om bilden kan läsas in från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att läsa från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna strömmen; annars <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


```
 can_load_stream_with_options(stream, load_options) 
```

Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att läsa från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna strömmen; annars <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


```
 can_load_with_options(file_path, load_options) 
```

Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan laddas från den angivna filen; annars <c>false</c>. |


### Method: can_save(options) {#can_save_options_22}


```
 can_save(options) 
```

Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparaalternativen att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | <c>true</c> om bilden kan sparas till det angivna filformatet som representeras av de överförda sparaalternativen; annars <c>false</c>. |


### Method: create(files)  [static] {#create_files_23}


```
 create(files) 
```

Skapar flersidig bild som innehåller de angivna filerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| files | string[] | Filerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den flersidiga bilden |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


```
 create(files, throw_exception_on_load_error) 
```

Skapar flersidig bild som innehåller de angivna filerna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| files | string[] | Filerna. |
| throw_exception_on_load_error | bool | om den är inställd på <c>true</c> [throw exception on load error]. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den flersidiga bilden |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


```
 create(image_options, width, height) 
```

Skapar en ny bild med de angivna skapandealternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bildalternativen. |
| width | int | Bredden. |
| height | int | Höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den nyss skapade bilden. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_26}


```
 create(image_options, width, height, pixels) 
```

Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen som används för att skapa [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | Bredden på [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | Höjden på [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| pixlar | int[] | Arrayen med pixelvärden som används för att fylla bilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | En [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) som är fylld med den angivna pixeldata. |


### Method: create(images)  [static] {#create_images_27}


```
 create(images) 
```

Skapar en ny bild med de angivna bilderna som sidor

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Bilderna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_28}


```
 create(images, dispose_images) 
```

Skapar en ny bild från de angivna bilderna som sidor.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Bilderna. |
| dispose_images | bool | om den är inställd på <c>true</c> [dispose images]. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_29}


```
 create(multipage_create_options) 
```

Skapar de angivna flersidiga skapalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Alternativen för att skapa flersidiga bilder. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den flersidiga bilden |


### Method: create_from_files(files)  [static] {#create_from_files_files_30}


```
 create_from_files(files) 
```

Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| files | string[] | Filerna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den flersidiga bilden |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_31}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| files | string[] | Filerna. |
| throw_exception_on_load_error | bool | om den är inställd på <c>true</c> kasta undantag vid inläsningsfel. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den flersidiga bilden |


### Method: create_from_images(images)  [static] {#create_from_images_images_32}


```
 create_from_images(images) 
```

Skapar en ny bild med de angivna bilderna som sidor

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Bilderna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_33}


```
 create_from_images(images, dispose_images) 
```

Skapar en ny bild från de angivna bilderna som sidor.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Bilderna. |
| dispose_images | bool | om den är inställd på <c>true</c> [dispose images]. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Bilden som IMultipageImage |


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_34}


```
 create_with_frame(frame) 
```

Initierar en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Tiff-ramen att initiera bilden med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) | En ny BigTiffImage-bild som inkluderar ramen. |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_35}


```
 create_with_frames(frames) 
```

Initierar en ny instans av klassen [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramarna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BigTiffImage](/imaging/python-net/aspose.imaging.fileformats.bigtiff/bigtiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Utför beskärning av bilden genom att ange förskjutningar åt vänster, höger, upp och \n            ner. Denna metod möjliggör exakt urval av önskad del av bilden, underlättar effektiv borttagning av oönskade områden och fokuserar på \n            väsentligt innehåll. Integrera denna funktionalitet i din bildbehandlings-\n            pipeline för att förbättra klarhet och komposition efter behov inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left_shift | int | Vänsterskiftet. |
| right_shift | int | Högerskiftet. |
| top_shift | int | Översta skiftet. |
| bottom_shift | int | Nedersta skiftet. |

### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

Beskär bilden med ett angivet rektangulärt område, vilket möjliggör exakt urval av \n            önskat innehåll. Integrera denna metod i ditt bildbehandlingsarbetsflöde för att \n            effektivt ta bort oönskade områden och fokusera på väsentliga detaljer, vilket förbättrar den \n            övergripande klarheten och kompositionen av bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Utför dithering på den aktuella bilden för att förbättra dess visuella kvalitet och minska \n            färgbandningsartefakter. Integrera denna metod i ditt bildbehandlingsarbetsflöde \n            för att säkerställa mjukare övergångar mellan färger, vilket resulterar i förbättrat övergripande bild-\n            utseende och klarhet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den anpassade paletten för dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_40}


```
 embed_digital_signature(password) 
```

Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att generera digitala signaturdata. |

### Method: filter(rectangle, options) {#filter_rectangle_options_41}


```
 filter(rectangle, options) 
```

Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bild<br/>            behandlingsfilter för att förbättra eller ändra det valda området. Integrera denna metod <br/>            i ditt bildmanipuleringsflöde för att uppnå riktade förbättringar eller <br/>            transformationer i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_42}


```
 get_argb_32_pixel(x, y) 
```

Hämtar en bildpixel i 32-bitars ARGB.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den 32‑bitars ARGB-pixeln för den angivna platsen. |


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_43}


```
 get_default_argb_32_pixels(rectangle) 
```

Hämtar standardarrayen för 32-bitars ARGB-pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Standardpixelarrayen. |


### Method: get_default_options(args) {#get_default_options_args_44}


```
 get_default_options(args) 
```

Hämtar standardalternativen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | System.Object | Argumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Standardalternativ |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_45}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Hämtar standardarrayen för rådata med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Den partiella rådata‑laddaren. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_47}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Hämtar standardarrayen för rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta rådata. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Byte | Standardrådataarrayen. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_48}


```
 get_file_format(file_path) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Det bestämda filformatet. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_49}


```
 get_file_format(stream) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Det bestämda filformatet. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_50}


```
 get_file_format_of_stream(stream) 
```

Hämtar filformatet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Det bestämda filformatet. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_51}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta en passande rektangel. |
| pixlar | int[] | De 32-bitars ARGB-pixlarna. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_52}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Hämtar rektangeln som passar den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta en passande rektangel. |
| width | int | Objektets bredd. |
| height | int | Objektets höjd. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den passande rektangeln eller ett undantag om ingen passande rektangel kan hittas. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_53}


```
 get_modify_date(use_default) 
```

Hämtar datum och tid då resursbilden senast ändrades.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| use_default | bool | Om den är satt till <c>true</c> används informationen från FileInfo som standardvärde. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.DateTime | Datumet och tiden då resursbilden senast ändrades. |


### Method: get_original_options() {#get_original_options__54}


```
 get_original_options() 
```

Hämta alternativ som härrör från de ursprungliga filinställningarna, vilket underlättar sömlös \n            bevarande av nyckelparametrar såsom bitdjup och andra väsentliga attribut för \n            den ursprungliga bilden. Använd denna metod för att upprätthålla trohet och konsistens i \n            bildbehandlingsuppgifter, vilket säkerställer optimala resultat utan onödiga förändringar.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med <br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/)‑metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem <br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/)‑metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_55}


```
 get_pixel(x, y) 
```

Hämtar en bildpixel.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | Pixelns färg för den angivna platsen. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_56}


```
 get_proportional_height(width, height, new_width) 
```

Hämtar en proportionell höjd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_width | int | Den nya bredden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella höjden. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_57}


```
 get_proportional_width(width, height, new_height) 
```

Hämtar en proportionell bredd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |
| new_height | int | Den nya höjden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Den proportionella bredden. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_58}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Konverterar till aps.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Bildalternativen. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Klippningsrektangeln. |
| page_number | int[] | Sidnumret. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom | Den serialiserade strömmen |


### Method: get_skew_angle() {#get_skew_angle__59}


```
 get_skew_angle() 
```

Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Snedvinkeln, i grader. |


### Method: insert_frame(index, frame) {#insert_frame_index_frame_60}


```
 insert_frame(index, frame) 
```

Infoga den nya ramen på det angivna indexet i ramsekvensen, vilket säkerställer \n            exakt kontroll över ramordningen. Använd denna metod för att hantera ramsekvenser \n            effektivt, vilket underlättar dynamisk manipulation och organisering av bild‑\n            innehåll inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för _frame_. |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramen för infogning. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


```
 is_digital_signed(password, percentage_threshold) 
```

Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet för att kontrollera signeringen. |
| percentage_threshold | int | Tröskelvärdet (i procent)[0-100] som avgör om bilden anses vara signerad.<br/>            Om det inte anges, kommer ett standardtröskelvärde (<c>75</c>) att tillämpas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om bilden är signerad, annars falskt. |


### Method: load(file_path)  [static] {#load_file_path_62}


```
 load(file_path) 
```

Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen eller URL:en att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


```
 load(file_path, load_options) 
```

Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen eller URL:en att ladda bilden från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load(stream)  [static] {#load_stream_64}


```
 load(stream) 
```

Läser in en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


```
 load(stream, load_options) 
```

Läser in en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att ladda bilden från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


```
 load_argb_32_pixels(rectangle) 
```

Läser in 32-bitars ARGB‑pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Den inlästa 32-bitars ARGB-pixelarrayen. |


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


```
 load_argb_64_pixels(rectangle) 
```

Läser in 64-bitars ARGB‑pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Den laddade 64-bit ARGB-pixelarrayen. |


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


```
 load_cmyk_32_pixels(rectangle) 
```

Läser in pixlar i CMYK‑format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Den laddade CMYK-pixlarna presenteras som 32-bitars heltalsvärden. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


```
 load_cmyk_pixels(rectangle) 
```

Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Den laddade CMYK-pixelarrayen. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Läser in 32-bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Läser in 64-bitars ARGB‑pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Den 64-bit ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Läser in pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Pixelinläsaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


```
 load_pixels(rectangle) 
```

Läser in pixlar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Den laddade pixelarrayen. |


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Läser in rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda rådata från. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Målbildens gränser. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Rådatainläsaren. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Läser in rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda rådata från. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Inställningarna för rådata att använda för laddade data. Observera att om data inte är i det angivna formatet kommer datakonvertering att utföras. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Rådatainläsaren. |

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


```
 load_stream(stream) 
```

Läser in en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att ladda bilden från. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


```
 load_stream_with_options(stream, load_options) 
```

Läser in en ny bild från den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att ladda bilden från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


```
 load_with_options(file_path, load_options) 
```

Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen eller URL:en att ladda bilden från. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Den inlästa bilden. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Använd metoden NormalizeAngle som är speciellt utformad för skannade textdokument \n            för att korrigera snedvridna skanningar, vilket säkerställer exakt justering. Integrera sömlöst \n            denna funktionalitet i dina textbehandlingsarbetsflöden för att förbättra \n            dokumentets läsbarhet och kvalitet, vilket ökar den övergripande effektiviteten i textigenkänning \n            och analysuppgifter.<br/>            Denna metod använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/)‑metoder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


```
 read_argb_32_scan_line(scan_line_index) 
```

Läser hela skanningsraden enligt det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int[] | Skanningslinjens 32-bit ARGB-färgvärdearray. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


```
 read_scan_line(scan_line_index) 
```

Läser hela skanningsraden enligt det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Skanningslinjens pixel-färgvärdearray. |


### Method: remove_frame(frame) {#remove_frame_frame_82}


```
 remove_frame(frame) 
```

Ta effektivt bort den angivna ramen från bildsekvensen, vilket underlättar \n            strömlinjeformad ramhantering inom din applikation. Integrera denna funktionalitet \n            för att förbättra precision och flexibilitet i rammanipulation, vilket säkerställer sömlös \n            organisering och presentation av bildinnehåll.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramen att ta bort. |

### Method: remove_frame(index) {#remove_frame_index_83}


```
 remove_frame(index) 
```

Tar bort ramen enligt dess index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för ramen som ska tas bort. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Den borttagna ramen. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_84}


```
 remove_frame_by_index(index) 
```

Tar bort ramen enligt dess index.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Index för ramen som ska tas bort. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Den borttagna ramen. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_85}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color_argb | int | Gammalt färg-ARGB-värde att ersätta. |
| old_color_diff | System.Byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta gammal färg med. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_86}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_87}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color_argb | int | Gammalt färg-ARGB-värde att ersätta. |
| old_color_diff | System.Byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta gammal färg med. |

### Method: replace_frame(index, new_frame) {#replace_frame_index_new_frame_88}


```
 replace_frame(index, new_frame) 
```

Ersätt ramen på den angivna positionen med en annan ram sömlöst, \n            vilket underlättar dynamisk ramhantering inom bildsekvensen. Integrera denna \n            metod för att förbättra flexibilitet och precision i rammanipulation, vilket säkerställer \n            optimal organisering och presentation av bildinnehåll inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Den nollbaserade rampositionen. |
| new_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Ramen för att ersätta den vid angivet _index_. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Den borttagna ramen. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_89}


```
 replace_non_transparent_colors(new_color) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_90}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta icke-transparenta färger med. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_91}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_92}


```
 resize(new_width, new_height, resize_type) 
```

Utför en proportionell storleksändring av bilden, bevara dess bildförhållande \n            samtidigt som dess dimensioner justeras. Använd denna metod för att dynamiskt skala bilder \n            inom din applikation, vilket säkerställer en konsekvent visuell återgivning av innehållets \n            integritet.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_93}


```
 resize(new_width, new_height, settings) 
```

Justera bildens storlek baserat på angivna inställningar, vilket möjliggör exakt \n            kontroll över dimensioner, bildförhållande och skalningsbeteende. Integrera denna \n            metod i ditt bildbehandlingsarbetsflöde för att uppnå anpassade storleksändringar \n            som är skräddarsydda för din applikations specifika krav.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_94}


```
 resize_by_settings(new_width, new_height, settings) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_95}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_96}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_97}


```
 resize_height_proportionally(new_height, resize_type) 
```

Utför en proportionell justering av bildens höjd, bevara dess bildförhållande \n            för konsekvent visuell integritet. Använd denna metod för att dynamiskt ändra storlek på \n            bilder inom din applikation, vilket säkerställer optimal visning över olika plattformar \n            och enheter utan att kompromissa med innehållets kvalitet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_98}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_99}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_100}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Utför en proportionell storleksändring av bilden, bevara dess bildförhållande \n            samtidigt som dess dimensioner justeras. Använd denna metod för att dynamiskt skala bilder \n            inom din applikation, vilket säkerställer en konsekvent visuell återgivning av innehållets \n            integritet.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_101}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_102}


```
 resize_width_proportionally(new_width, resize_type) 
```

Justera bildens bredd samtidigt som dess bildförhållande behålls, vilket säkerställer \n            proportionell storleksändring för optimal visuell presentation. Använd denna metod för \n            att dynamiskt skala bilder inom din applikation, vilket underlättar enhetlig och \n            estetiskt tilltalande återgivning över olika visningssammanhang.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_103}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_104}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_105}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_106}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotera bilden kring dess mittpunkt med en angiven vinkel, vilket möjliggör exakt \n            orienteringsjustering. Inkludera denna funktionalitet i din bildbehandlings-\n            pipeline för att underlätta korrekta transformationer, vilket säkerställer optimal justering och \n            presentation av visuellt innehåll inom din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_107}


```
 rotate_flip(rotate_flip_type) 
```

Utför rotation, spegling eller en kombination av båda operationerna uteslutande på den \n            aktiva ramen. Denna metod möjliggör exakt manipulation av enskilda ramar inom \n            bildsekvensen, vilket ökar flexibiliteten i bildredigering och komposition inom \n            din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändningstypen. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_108}


```
 rotate_flip_all(rotate_flip) 
```

Roterar alla flip.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändning. |

### Method: save(file_path) {#save_file_path_109}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_110}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_111}


```
 save(file_path, options, bounds_rectangle) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsning. |

### Method: save(file_path, over_write) {#save_file_path_over_write_112}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_113}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_114}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_115}


```
 save(stream, options_base, bounds_rectangle) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Målbildens avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_116}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_117}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlar presenterade som 32-bitars heltalsvärden. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_118}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_119}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlarna internt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pixlarna. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_120}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Sparar rådata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| data | System.Byte | Rådata. |
| data_offset | int | Startoffset för rådata. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rådatarektangeln. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Rådatainställningarna som datan är i. |

### Method: save_to_stream(stream) {#save_to_stream_stream_121}


```
 save_to_stream(stream) 
```

Sparar bilden till en ström

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_122}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Målbildens avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsningar. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_124}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_125}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Målbildernas avgränsningsrektangel. Ställ in den tomma rektangeln för att använda källans avgränsning. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_126}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Ställer in en bildpixel i 32-bit ARGB för den angivna positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| argb_32_color | int | Den 32-bitars ARGB-pixeln för den angivna positionen. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_127}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_128}


```
 set_pixel(x, y, color) 
```

Ställer in en bildpixel för den angivna positionen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | int | Pixelns x‑position. |
| y | int | Pixelns y‑position. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Pixelns färg för den angivna positionen. |

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_129}


```
 set_resolution(dpi_x, dpi_y) 
```

Ställer in upplösningen för den angivna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), vilket möjliggör <br/>            exakt kontroll över bildrendering och displayegenskaper. Integrera denna <br/>            funktion för att optimera visuell output och säkerställa kompatibilitet med olika <br/>            utdataenheter och plattformar, vilket förbättrar den övergripande användarupplevelsen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | float | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_130}


```
 try_set_metadata(metadata) 
```

Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Metadata. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Sant om _metadata_ inte är null och [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/)‑instansen <br/>            stöder och/eller implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)‑instansen; annars falskt. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int[] | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_132}


```
 write_scan_line(scan_line_index, pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pixel‑färgarrayen att skriva. |

