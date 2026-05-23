---
title: "WebPImage klass"
type: docs
weight: 30
url: /sv/python-net/aspose.imaging.fileformats.webp/webpimage/
---

**Summary:** Manipulate WebP raster images with our API, using its modern features for both<br/>            lossless and lossy compression, ensuring optimal image quality with reduced file sizes.<br/>            Seamlessly handle extended file formats, animations, and alpha channels, while easily<br/>            updating dimensions, resizing proportionally, cropping, rotating, applying filters,<br/>            adjusting image parameters, and converting to other image formats for versatile<br/>            web image optimization.

**Module:** [aspose.imaging.fileformats.webp](/imaging/python-net/aspose.imaging.fileformats.webp/)

**Full Name:** aspose.imaging.fileformats.webp.WebPImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WebPImage(path)](#WebPImage_path_1) | Instansiera en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass, initierad <br/>            från en angiven filkälla. Använd denna konstruktor för att sömlöst skapa WebP <br/>            bildobjekt direkt från filer, vilket förenklar processen för inläsning och <br/>            manipulering av WebP-bilddata i din applikation. |
| [WebPImage(path, load_options)](#WebPImage_path_load_options_2) | Skapa en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass med en fil och <br/>            specificerade inläsningsalternativ, vilket möjliggör flexibel hantering av WebP-bilddata. Använd <br/>            denna konstruktor för att sömlöst initiera WebP-bildobjekt från filer samtidigt som <br/>            du anpassar inläsningsparametrar enligt din applikations krav. |
| [WebPImage(raster_image)](#WebPImage_raster_image_3) | Instansiera en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass, initierad <br/>            från ett tillhandahållet rasterImage-objekt. Denna konstruktor möjliggör sömlös <br/>            konvertering av rasterbilder till WebP-format, vilket möjliggör effektiv hantering och <br/>            manipulering av bilddata i din applikation. |
| [WebPImage(raster_image, load_options)](#WebPImage_raster_image_load_options_4) | Skapa en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass med ett rasterImage-objekt och <br/>            specificerade inläsningsalternativ, vilket möjliggör flexibel hantering av bilddata. Använd <br/>            denna konstruktor för att sömlöst initiera WebP-bildobjekt från rasterbilder samtidigt som <br/>            du anpassar inläsningsparametrar enligt din applikations krav. |
| [WebPImage(stream)](#WebPImage_stream_5) | Instansiera ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) , initierad <br/> från en angiven strömkälla. Använd denna konstruktor för att sömlöst skapa WebP <br/> bildobjekt direkt från strömmar, vilket möjliggör effektiv hantering och manipulation <br/> av WebP-bilddata i din applikation. |
| [WebPImage(stream, load_options)](#WebPImage_stream_load_options_6) | Skapa ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från en ström,  <br/> med angivna inläsningsalternativ och minneshanteringsinställningar. Denna <br/> konstruktor erbjuder flexibilitet vid inläsning av WebP-bilder från strömmar samtidigt som <br/> minnesresurser hanteras effektivt, vilket säkerställer optimal prestanda och resurs <br/> utnyttjande i din applikation. |
| [WebPImage(width, height, options)](#WebPImage_width_height_options_7) | Instansiera ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) med en tom <br/> bild med angivna bredd- och höjdmått. Denna konstruktor möjliggör <br/> skapandet av tomma WebP-bilder, vilket ger en grund för efterföljande bild-<br/> manipulation och innehållsgenerering i din applikation. |
| [WebPImage(width, height, options, load_options)](#WebPImage_width_height_options_load_options_8) | Skapa ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) med en tom bild och angivna <br/> inläsningsalternativ. Denna konstruktor möjliggör initiering av WebP-bilder med <br/> anpassningsbara inläsningsparametrar, vilket ger flexibilitet vid bildskapande och <br/> manipulation i din applikation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämtar bildens bitar per pixel. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information <br/> om det format i vilket bilden lagras. Använd denna egenskap för att bestämma <br/> bildens filformat, vilket underlättar kompatibilitetskontroller och <br/> format‑specifik bearbetning i din applikation. |
| [has_alpha](#has_alpha1) | bool | r | Hämta om bilden innehåller en alfakanal, vilket indikerar förekomst av <br/> transparensinformation. Använd denna egenskap för att avgöra om bilden <br/> innehåller transparens, vilket möjliggör korrekt hantering och bearbetning av <br/> alfarelaterade operationer i din applikation. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| has_transparent_color | bool | r/w | Hämtar ett värde som indikerar om bilden har en transparent färg. |
| height | int | r | Hämtar bildens höjd. |
| horizontal_resolution | float | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar eller anger XMP-data från ramen. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | r | Hämta eller ändra alternativen som är kopplade till den angivna egenskapen, vilket möjliggör <br/> finjusterad anpassning av beteende och inställningar. Använd denna egenskap för att <br/> sömlöst komma åt och manipulera konfigurerbara parametrar, vilket underlättar mångsidig <br/> kontroll och optimering av din applikations funktionalitet. |
| page_count | int | r | Hämta det totala antalet sidor i det angivna dokumentet, vilket underlättar <br/> effektiv navigering och hantering av flersidigt innehåll. Integrera denna <br/> funktion för att förbättra användarupplevelsen, vilket möjliggör sömlös åtkomst till <br/> omfattande dokumentstrukturer. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Åtkomst till WebP‑blocken i bilden, vilket möjliggör detaljerad granskning eller <br/> manipulation av den underliggande blockstrukturen. Använd denna egenskap för att analysera <br/> eller ändra enskilda block i WebP‑bilddata, vilket underlättar avancerade <br/> bildbehandlingstekniker i din applikation. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste förmultipliceras. |
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
| vertical_resolution | float | r/w | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Hämtar bildens bredd. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Inkludera ett nytt WebP‑block i bilden, vilket berikar dess innehåll och <br/> underlättar avancerad bildmanipulation. Integrera denna metod för att dynamiskt <br/> förbättra strukturen och komplexiteten i WebP‑bilddata i din <br/> applikation, vilket möjliggör exakt kontroll och optimering av bildrendering. |
| [add_page(page)](#add_page_page_2) | Lägg till en ny sida i bilden, vilket utökar dess innehåll och rymmer ytterligare <br/> visuella element. Integrera denna metod för att underlätta dynamisk sidhantering <br/> i din applikation, vilket möjliggör sömlös skapande och utökning av flersidiga <br/> dokument eller bilder. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Implementera _brightness_-justering för bilden, vilket möjliggör <br/> modifiering av den övergripande luminansnivån. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra synligheten och öka den visuella kvaliteten på bilder <br/> i din applikation. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Förbättra kontrasten på [Image](/imaging/python-net/aspose.imaging/image/), vilket förstärker <br/> skillnaderna mellan ljusa och mörka områden. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra den visuella klarheten och den övergripande bildkvaliteten i <br/> din applikation. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Applicera gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå <br/> önskad ljusstyrka och färgbalans. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i <br/> efterföljande analys‑ eller visningsuppgifter i din applikation. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Utför gamma‑korrektion på bilden med individuella koefficienter för de röda, <br/> gröna och blå kanalerna, vilket möjliggör finjusterade justeringar av färgbalans och <br/> kontrast. Integrera denna metod i din bildbehandlingspipeline för att uppnå <br/> exakt kontroll över färgåtergivning och förbättra den visuella trovärdigheten i din <br/> applikation. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| auto_brightness_contrast() | Utför automatisk adaptiv ljusstyrke‑ och kontrastnormalisering för hela bilden. |
| auto_rotate() | Rotera automatiskt bilden baserat på orienteringsdata som extraheras från Exif <br/>            metadata. Denna metod säkerställer att bilder visas i korrekt orientering, <br/>            förbättrar användarupplevelsen och eliminerar behovet av manuella justeringar. Genom <br/>            att analysera Exif‑information roteras bilden därefter, vilket ger en sömlös <br/>            visningsupplevelse på olika plattformar och enheter. Denna automatiserade rotationsprocess <br/>            förenklar bildhantering och förbättrar den övergripande användbarheten, särskilt när <br/>            man hanterar stora bildsatser med varierande orienteringar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Applicera binarisering på bilden med Bradleys adaptiva tröskelalgoritm <br/> med integralbildströskling. Denna metod beräknar dynamiskt lokala <br/> tröskelvärden baserat på bildens omgivning, vilket ökar anpassningsförmågan till varierande <br/> ljusförhållanden och säkerställer robust segmentering för efterföljande bearbetnings‑<br/> uppgifter i din applikation. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Utför binarisering på bilden med ett fördefinierat tröskelvärde, omvandla <br/> den till en binär bild där pixlar klassificeras som förgrund eller bakgrund <br/> baserat på deras intensitet i förhållande till tröskeln. Integrera denna metod i <br/> ditt bildbehandlingsflöde för att underlätta segmentering och funktionsextraktion <br/> uppgifter, vilket förbättrar noggrannheten och effektiviteten i efterföljande analys i din <br/> applikation. |
| binarize_otsu() | Utför binarisering på bilden med Otsus tröskelmetod, som automatiskt <br/> bestämmer det optimala tröskelvärdet baserat på bildens histogram. Integrera <br/> denna metod i ditt bildbehandlingsflöde för att uppnå effektiv segmentering <br/> och funktionsextraktion, vilket förbättrar noggrannheten och tillförlitligheten i bildanalys‑<br/> uppgifter i din applikation. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_11) | Blandar denna bildinstans med _overlay_-bilden. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_12) | Blandar denna bildinstans med _overlay_-bilden. |
| cache_data() | Cachar data privat. |
| [can_load(file_path)](#can_load_file_path_13) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_14) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_15) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_16) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_17) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_18) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_19) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_save(options)](#can_save_options_20) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| clear_blocks() | Rensa alla befintliga WebP‑block från bilden, vilket ger en ren start för <br/> efterföljande ändringar eller tillägg. Använd denna metod för att effektivt återställa <br/> blockstrukturen i WebP‑bilddata, vilket säkerställer optimal hantering och <br/> organisering av bildinnehållet i din applikation. |
| [create(files)](#create_files_21) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_25) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_file_with_options(path, load_options)](#create_from_file_with_options_path_load_options_28) | Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från fil. |
| [create_from_files(files)](#create_from_files_files_29) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_30) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_image(raster_image)](#create_from_image_raster_image_31) | Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från rasterImage. |
| [create_from_image_with_options(raster_image, load_options)](#create_from_image_with_options_raster_image_load_options_32) | Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från rasterImage. |
| [create_from_images(images)](#create_from_images_images_33) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_34) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create_from_stream(stream)](#create_from_stream_stream_35) | Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) <br/>                från ström. |
| [create_from_stream_with_options(stream, load_options)](#create_from_stream_with_options_stream_load_options_36) | Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från ström. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_37) | Beskär bilden genom att tillämpa vänster-, höger-, topp- och bottenförskjutningar, vilket effektivt <br/>            väljer ett intresseområde i bilden. Använd denna metod för att <br/>            dynamiskt extrahera önskade delar av bilden samtidigt som du justerar dess sammansättning <br/>            och fokus enligt din applikations krav. |
| [crop(rectangle)](#crop_rectangle_38) | Beskär bilden med ett angivet rektangelområde, ta bort oönskade delar <br/>            samtidigt som du behåller önskat innehåll. Integrera denna metod i ditt bild‑<br/>            bearbetningsflöde för att exakt extrahera och fokusera på specifika intresseområden <br/>            i bilden, vilket förbättrar klarhet och komposition för olika tillämpningar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_39) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_40) | Utför dithering på den aktuella bilden för att minska färgbandning och förbättra den visuella <br/>            kvaliteten. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå <br/>            mjukare övergångar mellan färger och förbättra bildens övergripande utseende i din applikation. |
| [embed_digital_signature(password)](#embed_digital_signature_password_41) | Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden. |
| [filter(rectangle, options)](#filter_rectangle_options_42) | Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bild<br/>            behandlingsfilter för att förbättra eller ändra det valda området. Integrera denna metod <br/>            i ditt bildmanipuleringsflöde för att uppnå riktade förbättringar eller <br/>            transformationer i din applikation. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_43) | Hämtar en bildpixel i 32-bitars ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_44) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_45) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_46) | Hämtar standardpixelarrayen med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47) | Hämtar standardarrayen för rådata med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_48) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_49) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_50) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_51) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_52) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_53) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_54) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__55) | Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_56) | Hämtar en bildpixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_57) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_58) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_59) | Konverterar till aps. |
| [get_skew_angle()](#get_skew_angle__60) | Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| grayscale() | Konvertera bilden till dess gråskalerepresentation, vilket omvandlar den till en <br/>            enkankalig bild där varje pixel representerar intensitet eller luminans. Integrera <br/>            denna metod i din bildbehandlingspipeline för att förenkla analys och förbättra <br/>            kompatibiliteten med gråskalebaserade algoritmer, vilket underlättar olika dator<br/>            vision- och bildanalysuppgifter i din applikation. |
| [insert_block(index, block)](#insert_block_index_block_61) | Infoga ett nytt WebP‑block på det angivna indexet i bilden, vilket möjliggör exakt <br/>            kontroll över blocksekvensen. Integrera denna metod för att sömlöst införliva <br/>            ytterligare WebP‑block i bildens datastruktur, vilket underlättar avancerad bild<br/>            behandling och optimering i din applikation. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_62) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet. |
| [load(file_path)](#load_file_path_63) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_64) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_65) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_66) | Läser in data från strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_67) | Läser in 32-bitars ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_68) | Läser in 64-bitars ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_69) | Läser in pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_70) | Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71) | Läser in 32-bitars ARGB‑pixlar delvis (i block). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72) | Läser in 64-bitars ARGB‑pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_73) | Läser in pixlar delvis i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_74) | Läser in pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75) | Läser in rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76) | Läser in rådata. |
| [load_stream(stream)](#load_stream_stream_77) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_78) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_79) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| normalize_angle() | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_80) | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metoder. |
| normalize_histogram() | Normaliserar bildens histogram — justera pixelvärden för att använda hela tillgängliga intervallet. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [remove_block(block)](#remove_block_block_83) | Ta bort det angivna WebP‑blocket från bilden, vilket underlättar effektiv hantering <br/>            av bildens datastruktur. Använd denna metod för att förenkla bildbehandlings<br/>            arbetsflöden genom att eliminera onödiga block eller komponenter i din applikation. |
| remove_metadata() | Tar bort metadata för denna bildinstans genom att sätta detta [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) värde till **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | Ändra bildens storlek och justera dess dimensioner samtidigt som bildförhållandet bevaras. <br/>            Integrera denna metod i ditt bildbehandlingsflöde för att dynamiskt skala <br/>            bilder så att de passar olika visnings- eller lagringskrav i din applikation. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | Ändra bildens storlek enligt angivna inställningar, vilket möjliggör exakt kontroll över <br/>            dimensioner, bildförhållande och skalningsbeteende. Integrera denna metod i ditt <br/>            bildbehandlingsflöde för att uppnå anpassade storleksändringsoperationer skräddarsydda för <br/>            de specifika kraven i din applikation. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | Justera bildens höjd proportionellt, samtidigt som bildförhållandet bevaras <br/>            för enhetlig storleksändring. Integrera denna metod i ditt bildbehandlingsflöde <br/>            för att dynamiskt ändra bildstorlek med jämna proportioner, vilket säkerställer optimal visning eller <br/>            lagring i din applikation. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | Ändrar höjden proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | Justera bildens bredd proportionellt samtidigt som bildförhållandet bibehålls. <br/>            Integrera denna metod i ditt bildbehandlingsflöde för att dynamiskt ändra <br/>            bildstorlek med konsekventa proportioner, vilket säkerställer optimal visning eller lagring i <br/>            din applikation. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_102) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | Rotera bilden kring dess centrum med en angiven vinkel, samtidigt som den proportionellt <br/>            skalas om och angivna bakgrundsfärgsparametrar tillämpas. Inkorpora denna <br/>            metod i ditt bildbehandlingsflöde för att uppnå precisa transformationer med <br/>            anpassningsbara bakgrundsfärger, vilket säkerställer optimal visuell presentation i din <br/>            applikation. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | Applicera rotation, spegling eller båda operationerna uteslutande på den aktiva ramen <br/>            i bilden. Integrera denna metod i ditt bildbehandlingsflöde för att <br/>            uppnå exakt manipulation av enskilda ramar, vilket ökar flexibiliteten och <br/>            kontrollen över ramtransformationer i din applikation. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | Roterar alla flip. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_106) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_107) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_109) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_110) | Sparar data. |
| [save(stream, options_base)](#save_stream_options_base_111) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | Sparar pixlarna. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | Sparar pixlarna internt. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | Sparar rådata. |
| [save_to_stream(stream)](#save_to_stream_stream_118) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | Ställer in en bildpixel i 32-bit ARGB för den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_124) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_125) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_126) | Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_127) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_129) | Skriver hela skanningsraden till det angivna skanningsradindexet. |


### Constructor: WebPImage(path) {#WebPImage_path_1}


```
 WebPImage(path) 
```

Instansiera en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass, initierad <br/>            från en angiven filkälla. Använd denna konstruktor för att sömlöst skapa WebP <br/>            bildobjekt direkt från filer, vilket förenklar processen för inläsning och <br/>            manipulering av WebP-bilddata i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen till filen WebP‑bild |


**See also:**

**[Example # 1](#example_164)**: This example shows how to load a WebP image from a file and save it to PNG.


### Constructor: WebPImage(path, load_options) {#WebPImage_path_load_options_2}


```
 WebPImage(path, load_options) 
```

Skapa en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass med en fil och <br/>            specificerade inläsningsalternativ, vilket möjliggör flexibel hantering av WebP-bilddata. Använd <br/>            denna konstruktor för att sömlöst initiera WebP-bildobjekt från filer samtidigt som <br/>            du anpassar inläsningsparametrar enligt din applikations krav.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen till filen WebP‑bild |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

### Constructor: WebPImage(raster_image) {#WebPImage_raster_image_3}


```
 WebPImage(raster_image) 
```

Instansiera en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass, initierad <br/>            från ett tillhandahållet rasterImage-objekt. Denna konstruktor möjliggör sömlös <br/>            konvertering av rasterbilder till WebP-format, vilket möjliggör effektiv hantering och <br/>            manipulering av bilddata i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |


**See also:**

**[Example # 1](#example_166)**: This example shows how to create a WebP image from another raster image.


### Constructor: WebPImage(raster_image, load_options) {#WebPImage_raster_image_load_options_4}


```
 WebPImage(raster_image, load_options) 
```

Skapa en ny instans av [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) klass med ett rasterImage-objekt och <br/>            specificerade inläsningsalternativ, vilket möjliggör flexibel hantering av bilddata. Använd <br/>            denna konstruktor för att sömlöst initiera WebP-bildobjekt från rasterbilder samtidigt som <br/>            du anpassar inläsningsparametrar enligt din applikations krav.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

### Constructor: WebPImage(stream) {#WebPImage_stream_5}


```
 WebPImage(stream) 
```

Instansiera ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) , initierad <br/> från en angiven strömkälla. Använd denna konstruktor för att sömlöst skapa WebP <br/> bildobjekt direkt från strömmar, vilket möjliggör effektiv hantering och manipulation <br/> av WebP-bilddata i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen WebP‑bild. |


**See also:**

**[Example # 1](#example_165)**: This example shows how to load a WebP image from a file stream and save it to...


### Constructor: WebPImage(stream, load_options) {#WebPImage_stream_load_options_6}


```
 WebPImage(stream, load_options) 
```

Skapa ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från en ström,  <br/> med angivna inläsningsalternativ och minneshanteringsinställningar. Denna <br/> konstruktor erbjuder flexibilitet vid inläsning av WebP-bilder från strömmar samtidigt som <br/> minnesresurser hanteras effektivt, vilket säkerställer optimal prestanda och resurs <br/> utnyttjande i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen WebP‑bild. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

### Constructor: WebPImage(width, height, options) {#WebPImage_width_height_options_7}


```
 WebPImage(width, height, options) 
```

Instansiera ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) med en tom <br/> bild med angivna bredd- och höjdmått. Denna konstruktor möjliggör <br/> skapandet av tomma WebP-bilder, vilket ger en grund för efterföljande bild-<br/> manipulation och innehållsgenerering i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd |
| height | int | Bildens höjd. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Alternativen. |


**See also:**

**[Example # 1](#example_167)**: This example shows how to create a WebP image with the specified options from...


### Constructor: WebPImage(width, height, options, load_options) {#WebPImage_width_height_options_load_options_8}


```
 WebPImage(width, height, options, load_options) 
```

Skapa ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) med en tom bild och angivna <br/> inläsningsalternativ. Denna konstruktor möjliggör initiering av WebP-bilder med <br/> anpassningsbara inläsningsparametrar, vilket ger flexibilitet vid bildskapande och <br/> manipulation i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd |
| height | int | Bildens höjd. |
| options | [WebPOptions](/imaging/python-net/aspose.imaging.imageoptions/webpoptions/) | Alternativen. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

### Property: has_alpha {#has_alpha1}

Hämta om bilden innehåller en alfakanal, vilket indikerar förekomst av <br/> transparensinformation. Använd denna egenskap för att avgöra om bilden <br/> innehåller transparens, vilket möjliggör korrekt hantering och bearbetning av <br/> alfarelaterade operationer i din applikation.

**See also:**

**[Example # 1](#example_168)**: The following example loads a WEBP image and prints information about raw dat...


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Inkludera ett nytt WebP‑block i bilden, vilket berikar dess innehåll och <br/> underlättar avancerad bildmanipulation. Integrera denna metod för att dynamiskt <br/> förbättra strukturen och komplexiteten i WebP‑bilddata i din <br/> applikation, vilket möjliggör exakt kontroll och optimering av bildrendering.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Webp‑blocket att lägga till. |

### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Lägg till en ny sida i bilden, vilket utökar dess innehåll och rymmer ytterligare <br/> visuella element. Integrera denna metod för att underlätta dynamisk sidhantering <br/> i din applikation, vilket möjliggör sömlös skapande och utökning av flersidiga <br/> dokument eller bilder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sidan att lägga till. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Implementera _brightness_-justering för bilden, vilket möjliggör <br/> modifiering av den övergripande luminansnivån. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra synligheten och öka den visuella kvaliteten på bilder <br/> i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Förbättra kontrasten på [Image](/imaging/python-net/aspose.imaging/image/), vilket förstärker <br/> skillnaderna mellan ljusa och mörka områden. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra den visuella klarheten och den övergripande bildkvaliteten i <br/> din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Applicera gamma‑korrektion på bilden, justera pixelintensiteter för att uppnå <br/> önskad ljusstyrka och färgbalans. Integrera denna metod i ditt bild‑<br/> bearbetningsflöde för att förbättra den visuella kvaliteten och öka noggrannheten i <br/> efterföljande analys‑ eller visningsuppgifter i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Utför gamma‑korrektion på bilden med individuella koefficienter för de röda, <br/> gröna och blå kanalerna, vilket möjliggör finjusterade justeringar av färgbalans och <br/> kontrast. Integrera denna metod i din bildbehandlingspipeline för att uppnå <br/> exakt kontroll över färgåtergivning och förbättra den visuella trovärdigheten i din <br/> applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma_red | float | Gamma för röd kanal koefficient |
| gamma_green | float | Gamma för grön kanal koefficient |
| gamma_blue | float | Gamma för blå kanalkoefficient |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_7}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_8}


```
 binarize_bradley(brightness_difference) 
```

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s fönster av pixlar<br/>                centrerat kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Applicera binarisering på bilden med Bradleys adaptiva tröskelalgoritm <br/> med integralbildströskling. Denna metod beräknar dynamiskt lokala <br/> tröskelvärden baserat på bildens omgivning, vilket ökar anpassningsförmågan till varierande <br/> ljusförhållanden och säkerställer robust segmentering för efterföljande bearbetnings‑<br/> uppgifter i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s fönster av pixlar<br/>            centrerat kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Utför binarisering på bilden med ett fördefinierat tröskelvärde, omvandla <br/> den till en binär bild där pixlar klassificeras som förgrund eller bakgrund <br/> baserat på deras intensitet i förhållande till tröskeln. Integrera denna metod i <br/> ditt bildbehandlingsflöde för att underlätta segmentering och funktionsextraktion <br/> uppgifter, vilket förbättrar noggrannheten och effektiviteten i efterföljande analys i din <br/> applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | System.Byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas ett värde av<br/>            255 till den, annars 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_11}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_12}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_13}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_14}


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


### Method: can_load(stream)  [static] {#can_load_stream_15}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_16}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_17}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_18}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_19}


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


### Method: can_save(options) {#can_save_options_20}


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


### Method: create(files)  [static] {#create_files_21}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_22}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_23}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_24}


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


### Method: create(images)  [static] {#create_images_25}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_26}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_27}


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


### Method: create_from_file_with_options(path, load_options)  [static] {#create_from_file_with_options_path_load_options_28}


```
 create_from_file_with_options(path, load_options) 
```

Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från fil.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen till filen WebP‑bild |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_29}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_30}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_31}


```
 create_from_image(raster_image) 
```

Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från rasterImage.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_image_with_options(raster_image, load_options)  [static] {#create_from_image_with_options_raster_image_load_options_32}


```
 create_from_image_with_options(raster_image, load_options) 
```

Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från rasterImage.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_33}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_34}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_35}


```
 create_from_stream(stream) 
```

Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) <br/>                från ström.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen WebP‑bild. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: create_from_stream_with_options(stream, load_options)  [static] {#create_from_stream_with_options_stream_load_options_36}


```
 create_from_stream_with_options(stream, load_options) 
```

Initierar ett nytt objekt av klassen [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) från ström.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen WebP‑bild. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebPImage](/imaging/python-net/aspose.imaging.fileformats.webp/webpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_37}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Beskär bilden genom att tillämpa vänster-, höger-, topp- och bottenförskjutningar, vilket effektivt <br/>            väljer ett intresseområde i bilden. Använd denna metod för att <br/>            dynamiskt extrahera önskade delar av bilden samtidigt som du justerar dess sammansättning <br/>            och fokus enligt din applikations krav.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left_shift | int | Vänsterskiftet. |
| right_shift | int | Högerskiftet. |
| top_shift | int | Översta skiftet. |
| bottom_shift | int | Nedersta skiftet. |

### Method: crop(rectangle) {#crop_rectangle_38}


```
 crop(rectangle) 
```

Beskär bilden med ett angivet rektangelområde, ta bort oönskade delar <br/>            samtidigt som du behåller önskat innehåll. Integrera denna metod i ditt bild‑<br/>            bearbetningsflöde för att exakt extrahera och fokusera på specifika intresseområden <br/>            i bilden, vilket förbättrar klarhet och komposition för olika tillämpningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_39}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_40}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Utför dithering på den aktuella bilden för att minska färgbandning och förbättra den visuella <br/>            kvaliteten. Integrera denna metod i ditt bildbehandlingsflöde för att uppnå <br/>            mjukare övergångar mellan färger och förbättra bildens övergripande utseende i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den anpassade paletten för dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_41}


```
 embed_digital_signature(password) 
```

Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att generera digitala signaturdata. |

### Method: filter(rectangle, options) {#filter_rectangle_options_42}


```
 filter(rectangle, options) 
```

Filtrera innehållet inom den angivna rektangeln genom att applicera ett bestämt bild<br/>            behandlingsfilter för att förbättra eller ändra det valda området. Integrera denna metod <br/>            i ditt bildmanipuleringsflöde för att uppnå riktade förbättringar eller <br/>            transformationer i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_43}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_44}


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


### Method: get_default_options(args) {#get_default_options_args_45}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_46}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_47}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_48}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_49}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_50}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_51}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_52}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_53}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_54}


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


### Method: get_original_options() {#get_original_options__55}


```
 get_original_options() 
```

Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_56}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_57}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_58}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_59}


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


### Method: get_skew_angle() {#get_skew_angle__60}


```
 get_skew_angle() 
```

Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Snedvinkeln, i grader. |


### Method: insert_block(index, block) {#insert_block_index_block_61}


```
 insert_block(index, block) 
```

Infoga ett nytt WebP‑block på det angivna indexet i bilden, vilket möjliggör exakt <br/>            kontroll över blocksekvensen. Integrera denna metod för att sömlöst införliva <br/>            ytterligare WebP‑block i bildens datastruktur, vilket underlättar avancerad bild<br/>            behandling och optimering i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Det nollbaserade elementet där _block_ kommer att<br/>                infogas. |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Webp‑blocket att lägga till. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_62}


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


### Method: load(file_path)  [static] {#load_file_path_63}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_64}


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


### Method: load(stream)  [static] {#load_stream_65}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_66}


```
 load(stream, load_options) 
```

Läser in data från strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen WebP‑bild. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Laddningsalternativen |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) |  |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_67}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_68}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_69}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_70}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Läser in 32-bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_72}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Läser in 64-bitars ARGB‑pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Den 64-bit ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_73}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Läser in pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Pixelinläsaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_74}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_75}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_76}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_77}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_78}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_79}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_80}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metoder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


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


### Method: remove_block(block) {#remove_block_block_83}


```
 remove_block(block) 
```

Ta bort det angivna WebP‑blocket från bilden, vilket underlättar effektiv hantering <br/>            av bildens datastruktur. Använd denna metod för att förenkla bildbehandlings<br/>            arbetsflöden genom att eliminera onödiga block eller komponenter i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| block | [IFrame](/imaging/python-net/aspose.imaging.fileformats.webp/iframe/) | Blocket att ta bort. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta icke-transparenta färger med. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

Ändra bildens storlek och justera dess dimensioner samtidigt som bildförhållandet bevaras. <br/>            Integrera denna metod i ditt bildbehandlingsflöde för att dynamiskt skala <br/>            bilder så att de passar olika visnings- eller lagringskrav i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

Ändra bildens storlek enligt angivna inställningar, vilket möjliggör exakt kontroll över <br/>            dimensioner, bildförhållande och skalningsbeteende. Integrera denna metod i ditt <br/>            bildbehandlingsflöde för att uppnå anpassade storleksändringsoperationer skräddarsydda för <br/>            de specifika kraven i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

Justera bildens höjd proportionellt, samtidigt som bildförhållandet bevaras <br/>            för enhetlig storleksändring. Integrera denna metod i ditt bildbehandlingsflöde <br/>            för att dynamiskt ändra bildstorlek med jämna proportioner, vilket säkerställer optimal visning eller <br/>            lagring i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

Justera bildens bredd proportionellt samtidigt som bildförhållandet bibehålls. <br/>            Integrera denna metod i ditt bildbehandlingsflöde för att dynamiskt ändra <br/>            bildstorlek med konsekventa proportioner, vilket säkerställer optimal visning eller lagring i <br/>            din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotera bilden kring dess centrum med en angiven vinkel, samtidigt som den proportionellt <br/>            skalas om och angivna bakgrundsfärgsparametrar tillämpas. Inkorpora denna <br/>            metod i ditt bildbehandlingsflöde för att uppnå precisa transformationer med <br/>            anpassningsbara bakgrundsfärger, vilket säkerställer optimal visuell presentation i din <br/>            applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | om den är satt till <c>true</c> kommer bildens storlek att ändras<br/>
            enligt den roterade rektangelns (hörnpunkternas) projektioner i annat<br/>
            fall lämnas dimensionerna orörda och endast<br/>
            __internal__ bildinnehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

Applicera rotation, spegling eller båda operationerna uteslutande på den aktiva ramen <br/>            i bilden. Integrera denna metod i ditt bildbehandlingsflöde för att <br/>            uppnå exakt manipulation av enskilda ramar, vilket ökar flexibiliteten och <br/>            kontrollen över ramtransformationer i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändningstypen. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

Roterar alla flip.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändning. |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

Sparar data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bilddata till. |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlar presenterade som 32-bitars heltalsvärden. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlarna internt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pixlarna. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_124}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_125}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_126}


```
 set_resolution(dpi_x, dpi_y) 
```

Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | float | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_127}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_128}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int[] | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_129}


```
 write_scan_line(scan_line_index, pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pixel‑färgarrayen att skriva. |

## **Examples**
### This example shows how to load a WebP image from a file and save it to PNG. {#example_164}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
# Läs in en WebP‑bild från en fil.
with WebPImage(join(dir_, "test.webp")) as web_pimage:
	# Spara som PNG
	# Observera att endast den aktiva ramen kommer att sparas som PNG, eftersom PNG inte är ett flersidigt format.
	web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to load a WebP image from a file stream and save it to PNG. {#example_165}
``` python

import aspose.pycore as aspycore
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
# Läs in en WebP‑bild från en filström.
with open(join(dir_, "test.webp"), "w+b") as stream:
	with WebPImage(stream) as web_pimage:
		# Spara som PNG
		# Observera att endast den aktiva ramen kommer att sparas som PNG, eftersom PNG inte är ett flersidigt format.
		web_pimage.save(join(dir_, "test.output.png"), PngOptions())


```

### This example shows how to create a WebP image from another raster image. {#example_166}
``` python
from os.path import join
from aspose.imaging import Graphics, Color
from aspose.imaging.fileformats.png import PngImage
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions      

dir_: str = "c:\\temp"
# Läs in en PNG‑bild på 100 × 100 px.
with PngImage(100, 100) as png_image:
	graphics = Graphics(png_image)
	# Fyll hela bilden med rött.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, png_image.bounds)
	# Skapa en WebP‑bild baserad på PNG‑bilden.
	with WebPImage(png_image) as web_pimage:
		# Spara till en WebP-fil med standardalternativ
		web_pimage.save(join(dir_, "output.webp"), WebPOptions())


```

### This example shows how to create a WebP image with the specified options from scratch. {#example_167}
``` python
from aspose.imaging.fileformats.webp import WebPImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.imageoptions import WebPOptions
from os.path import join


dir_: str = "c:\\temp"
create_options = WebPOptions()
create_options.lossless = True
create_options.quality = 100.0

# Skapa en WebP-bild på 100x100 px.
with WebPImage(100, 100, create_options) as web_pimage:
	graphics = Graphics(web_pimage)
	# Fyll hela bilden med rött.
	brush = SolidBrush(Color.red)
	graphics.fill_rectangle(brush, web_pimage.bounds)
	# Spara till en WebP-fil
	web_pimage.save(join(dir_, "output.webp"))


```

### The following example loads a WEBP image and prints information about raw data format and alpha channel. {#example_168}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.webp import WebPImage, WebPFrameBlock

dir_ = "c:\\temp"
file_name = dir_ + "sample.webp"
with Image.load(file_name) as image:
	webp_image = aspycore.as_of(image, WebPImage)
	# Om den aktiva TIFF-ramen har alfakanal, betraktas hela TIFF-bilden som att den har alfakanal.
	print(f"ImageFile={file_name}, FileFormat={webp_image.raw_data_format}, HasAlpha={webp_image.has_alpha}")
	i: int = 0
	for frame in webp_image.blocks:
		if aspycore.is_assignable(frame, WebPFrameBlock):
			frame_block = aspycore.as_of(frame, WebPFrameBlock)
			print(f"Frame={i}, FileFormat={frame_block.raw_data_format}, HasAlpha={frame_block.has_alpha}")
			i += 1

# Utdata kan se ut så här:
# ImageFile=c:\temp\sample.webp, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False
# Frame=0, FileFormat=RgbIndexed1Bpp, använda kanaler: 1, HasAlpha=False


```

