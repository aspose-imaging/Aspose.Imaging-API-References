---
title: "GifImage-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.imaging.fileformats.gif/gifimage/
---

**Summary:** The API for Graphical Interchange Format (GIF) image file provides<br/>            developers with versatile tools for processing compressed raster images and<br/>            animated GIFs. Offering features like XMP metadata handling, color palette<br/>            settings, background and transparent color control, opacity settings, resize,<br/>            crop, filter application, gamma corrections, contrast adjustment, grayscale<br/>            transformation, and conversion to other formats. This API empowers seamless<br/>            manipulation and enhancement of GIF images for a wide range of applications.

**Module:** [aspose.imaging.fileformats.gif](/imaging/python-net/aspose.imaging.fileformats.gif/)

**Full Name:** aspose.imaging.fileformats.gif.GifImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GifImage(first_frame)](#GifImage_first_frame_1) | Att skapa GIF‑bilder blir enkelt med [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            konstruktor. Med bara firstFrame‑parametern går du in i en värld av dynamisk <br/>            visuell kommunikation. |
| [GifImage(first_frame, global_palette)](#GifImage_first_frame_global_palette_2) | Initiera ett nytt [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) objekt med angivna parametrar för <br/>            första ramen och global palett. Börja hantera GIF‑bilder snabbt, och säkerställ <br/>            korrekt återgivning med anpassningsbara inställningar för optimala resultat. |
| [GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer)](#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3) | Kom igång enkelt med [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/)‑konstruktorn. Med denna <br/>            enkla metoden kan du dyka in i att skapa animerade GIF‑filer med lätthet. Ange bara <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio och andra <br/>            parametrar, så är du redo att ge liv åt dina visuella element. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| [active_frame](#active_frame1) | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | r/w | Hantera och manipulera ramar med denna egenskap, vilket möjliggör smidig navigering och <br/>            modifiering av den aktiva ramen i GIF‑bilden. |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hantera bakgrundsfärgen i GIF‑bilden med denna egenskap. Du kan sätta eller <br/>            hämta bakgrundsfärgen för att säkerställa konsistens och förbättra den visuella attraktionskraften. |
| background_color_index | System.Byte | r/w | Styr bakgrundsfärgindexet för GIF‑bilden med denna egenskap. Sätt eller <br/>            hämta indexet för att upprätthålla konsistens eller uppnå önskade visuella effekter. |
| bits_per_pixel | int | r | Hämtar bildens bitar per pixel. |
| blocks | [IGifBlock[]](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | r | Få sömlös åtkomst till GIF‑blocken med denna egenskap, vilket underlättar enkel <br/>            hämtning och manipulering av bildens underliggande datastrukturer. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämta filformatet enkelt med denna egenskap. Det är din primära källa <br/>            för att identifiera formatet på dina filer. Sömlöst integrerad i ditt arbetsflöde, <br/>            ger den viktig information utan krångel. |
| has_alpha | bool | r | Hämtar ett värde som indikerar om denna instans har alfa. |
| has_background_color | bool | r/w | Denna egenskap avgör om GIF‑bilden innehåller en bakgrundsfärg. Om <br/>            true indikerar det att bilden har en bakgrundsfärg. |
| has_trailer | bool | r/w | Hantera förekomsten av en trailer i dina GIF‑filer med denna egenskap. Oavsett om du <br/>            behöver kontrollera om en trailer finns eller ange dess närvaro, förenklar denna egenskap <br/>            processen. Håll dina GIF‑filer strukturerade och i enlighet med denna intuitiva funktion. |
| has_transparent_color | bool | r/w | Bestäm om den aktiva ramen i GIF‑bilden innehåller en transparent färg. <br/>            Denna egenskap ger ett bekvämt sätt att kontrollera transparens i bilden. |
| height | int | r | Hämtar bildens höjd. |
| horizontal_resolution | float | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Hämta opaciteten för den aktiva ramen i bilden, vilket ger insikt i <br/>            dess transparensnivå. Denna egenskap är särskilt användbar för att förstå <br/>            graden av transparens eller ogenomskinlighet i den aktiva ramen i bilden. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| is_interlaced | bool | r | Bestämmer om bilden är interlaced, vilket påverkar dess visning under inläsning. Denna <br/> egenskap ger insikt i bildens renderingsbeteende, vilket är avgörande för <br/> optimering av inläsningsstrategier och förbättring av den övergripande visningsupplevelsen. |
| is_palette_sorted | bool | r/w | Styr sorteringen av paletten i dina GIF-bilder med hjälp av denna egenskap. Oavsett <br/> om du behöver kontrollera om paletten är sorterad eller ange sorteringsbeteendet, så ger denna <br/> egenskap ett enkelt sätt att hantera palettens organisation i dina <br/> GIF-filer. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| loops_count | int | r/w | Hämta loopantalet enkelt med denna egenskap. Om din GIF-bild innehåller <br/> loopinformation ger denna egenskap dig snabb åtkomst till loopantalet, vilket gör det möjligt att sömlöst hantera loopbeteendet i dina GIF-filer. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar eller anger XMP-data från ramen. |
| page_count | int | r | Hämta det totala antalet sidor som finns i bilden med denna <br/> enkla egenskap. Idealisk för att snabbt bedöma omfattningen av bildens innehåll. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Få åtkomst till sidorna i bilden via denna praktiska egenskap, <br/> vilket möjliggör sömlös navigering och manipulation av enskilda sidor vid behov. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| palette_color_resolution_bits | System.Byte | r/w | Hantera palettens färgupplösning i dina GIF-bilder med denna egenskap. Justera <br/> antalet bitar som används för att representera färger i paletten, vilket ger fin kontroll <br/> över färgdjup och bildkvalitet. |
| pixel_aspect_ratio | System.Byte | r/w | Hantera pixelns bildförhållande i GIF-bilden med denna egenskap. Ställ in eller hämta <br/> bildförhållandet för att säkerställa korrekt rendering och bevara visuell trohet. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste förmultipliceras. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Hämtar eller anger den anpassade färgkonvertern |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Hämtar de aktuella inställningarna för rådata. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Hämtar eller anger den indexerade färgkonvertern |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämta den transparenta färgen för den aktiva ramen i GIF-bilden. Denna egenskap <br/> låter dig komma åt den specifika färg som har markerats som transparent <br/> i den för närvarande aktiva ramen. |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| vertical_resolution | float | r/w | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Hämtar bildens bredd. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(block)](#add_block_block_1) | Att lägga till ett nytt GIF-block gör att du kan inkludera ytterligare data i bilden. <br/> Denna metod låter dig lägga till anpassade block i GIF-bilden, som kan <br/> innehålla olika typer av information. |
| [add_page(page)](#add_page_page_2) | Inkludera en ny sida sömlöst i den befintliga bilden, vilket förbättrar dess innehåll <br/> och utökar dess omfattning. Denna metod utökar bildsamlingar med ytterligare <br/> innehåll, vilket främjar kreativitet och flexibilitet i bildhantering och sammansättning. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_3) | Justerar bildens ljusstyrka enligt den angivna<br/> _brightness_-parametern. Denna metod modifierar hela bildens ljusstyrka enhetligt, vilket ökar eller minskar den totala luminansen för att uppnå <br/> önskad effekt. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_4) | Justerar bildens kontrast, vilket ökar eller minskar skillnaden i <br/> ljusstyrka mellan pixlar. Denna metod ändrar bildens övergripande tonomfång, <br/> så att mörkare områden blir mörkare och ljusare områden blir ljusare för att förbättra visuell klarhet <br/> och detaljrikedom. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_5) | Förbättra bildkvaliteten genom att tillämpa gammakorrigering. Denna metod justerar bildens färg<br/> gamma för att uppnå optimal visuell klarhet. Den ändrar gamma‑värdet <br/> för varje pixel, vilket resulterar i förbättrad färgåtergivning och övergripande bildutseende. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_6) | Gammakorrigering av en bild applicerar en icke‑linjär justering av pixelvärdena, <br/> vilket ökar eller minskar ljusstyrkan baserat på de angivna koefficienterna för de röda, <br/> gröna och blå kanalerna. Denna metod hjälper till att finjustera färgbalansen och <br/> luminansen i bilden, vilket förbättrar dess övergripande utseende och visuella kvalitet. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_7) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| auto_brightness_contrast() | Utför automatisk adaptiv ljusstyrke‑ och kontrastnormalisering för hela bilden. |
| auto_rotate() | Rotera automatiskt bilden baserat på orienteringsdata som extraheras från Exif <br/>            metadata. Denna metod säkerställer att bilder visas i korrekt orientering, <br/>            förbättrar användarupplevelsen och eliminerar behovet av manuella justeringar. Genom <br/>            att analysera Exif‑information roteras bilden därefter, vilket ger en sömlös <br/>            visningsupplevelse på olika plattformar och enheter. Denna automatiserade rotationsprocess <br/>            förenklar bildhantering och förbättrar den övergripande användbarheten, särskilt när <br/>            man hanterar stora bildsatser med varierande orienteringar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_8) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med <br/> integral bildtröskling är en metod för att konvertera en gråskalebild till en <br/> binär bild. Denna algoritm beräknar en lokal tröskel för varje pixel baserat på <br/> den genomsnittliga intensiteten hos omgivande pixlar inom ett angivet fönster. Genom <br/> att adaptivt justera tröskeln baserat på lokala pixelintensiteter är Bradleys <br/> metod effektiv för att hantera variationer i belysning och kontrast över bilden. |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_9) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_10) | Binarisering av en bild med ett fördefinierat tröskelvärde konverterar en gråskala- eller färgbild <br/> till en binär bild, där varje pixel klassificeras som antingen svart eller vit <br/> baserat på om dess intensitetsvärde överstiger ett angivet tröskelvärde. |
| binarize_otsu() | Binarisering av en bild med Otsu-tröskling är en metod som används för att automatiskt <br/> bestämma det optimala tröskelvärdet för att konvertera en gråskalebild till en <br/> binär bild. Otsu‑trösklingsalgoritmen beräknar den tröskel som <br/> minimerar intraklassvariansen för pixelintensiteterna i de två resulterande <br/> klasserna (förgrund och bakgrund). Denna teknik är särskilt användbar när <br/> det optimala tröskelvärdet är okänt och måste bestämmas adaptivt baserat <br/> på bildens histogram. |
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
| clear_blocks() | Att rensa alla GIF‑block tar bort all befintlig data som lagrats i bilden. <br/> Denna operation återställer bilden effektivt till ett tomt tillstånd, vilket tar bort alla <br/> tidigare tillagda block. Använd denna metod när du behöver börja om från början med en ren <br/> start för att skapa eller modifiera en GIF‑bild. |
| [create(files)](#create_files_21) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_25) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_files(files)](#create_from_files_files_28) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_images(images)](#create_from_images_images_30) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_31) | Skapar en ny bild från de angivna bilderna som sidor. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_32) | Beskär bild med förskjutningar. |
| [crop(rectangle)](#crop_rectangle_33) | Beskär bilden med ett angivet rektangelområde. Denna operation tar bort den yttre <br/> delen av bilden och lämnar endast det valda området som definieras av rektangeln. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_34) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_35) | Applicera dithering på den aktuella bilden. Denna process förbättrar bildkvaliteten genom att <br/>            minska färgbandning och förbättra färgövergångar, vilket resulterar i ett mjukare <br/>            utseende. |
| [embed_digital_signature(password)](#embed_digital_signature_password_36) | Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden. |
| [filter(rectangle, options)](#filter_rectangle_options_37) | Applicera ett specifikt filter på det angivna området i bilden, förbättra dess visuella <br/>            kvalitet eller ändra dess utseende enligt önskemål. Denna metod bearbetar selektivt <br/>            pixlar inom den definierade rektangeln, vilket möjliggör riktade justeringar samtidigt <br/>            som integriteten hos den omgivande bilddata bevaras. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_38) | Hämtar en bildpixel i 32-bitars ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_39) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_40) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_41) | Hämtar standardpixelarrayen med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42) | Hämtar standardarrayen för rådata med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_43) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_44) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_45) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_46) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_47) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_48) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_49) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__50) | Hämta de ursprungliga filinställningsbaserade alternativen, avgörande för att upprätthålla trohet <br/>            och konsistens i bildbehandling och manipulation. Denna metod möjliggör sömlös <br/>            integration av filspecifika parametrar i efterföljande operationer, vilket säkerställer <br/>            exakt återgivning och efterlevnad av bildens inneboende egenskaper.<br/>            Detta kan vara hjälpsamt för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer den resulterande PNG-bilden med 8-bit per pixel att produceras.<br/>            För att undvika detta och spara PNG-bilden med 1-bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_51) | Hämtar en bildpixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_52) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_53) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_54) | Konverterar till aps. |
| [get_skew_angle()](#get_skew_angle__55) | Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| grayscale() | Omvandlingen av en bild till dess gråskalerepresentation konverterar färgbilden till en gråskala version genom att ta bort färginformation medan luminansen bevaras.<br/>            Denna process förenklar bilden till gråtoner, vilket gör den lämplig för olika tillämpningar såsom utskrift, dokumentbehandling och gråskalanalys. |
| [insert_block(index, block)](#insert_block_index_block_56) | Att infoga ett nytt GIF-block gör att du kan lägga till anpassad data på en specifik position <br/>            inom bilden. Denna metod möjliggör att placera anpassade block på en önskad <br/>            plats i GIF-bilden, vilket ger flexibilitet i organisering och strukturering av <br/>            bilddata. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_57) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet. |
| [load(file_path)](#load_file_path_58) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_59) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_60) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_61) | Läser in en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_62) | Läser in 32-bitars ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_63) | Läser in 64-bitars ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_64) | Läser in pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_65) | Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66) | Läser in 32-bitars ARGB‑pixlar delvis (i block). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67) | Läser in 64-bitars ARGB‑pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_68) | Läser in pixlar delvis i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_69) | Läser in pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70) | Läser in rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71) | Läser in rådata. |
| [load_stream(stream)](#load_stream_stream_72) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_73) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_74) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| normalize_angle() | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_75) | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metoder. |
| normalize_histogram() | Normaliserar bildens histogram — justera pixelvärden för att använda hela tillgängliga intervallet. |
| order_blocks() | Att ordna GIF-blocken enligt GIF-specifikationen säkerställer korrekt GIF <br/>            layout och efterlevnad av standarden. Denna process innebär att arrangera <br/>            blocken i rätt sekvens enligt specifikationen. Dessutom kan det <br/>            innebära att ta bort vissa [GifGraphicsControlBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifgraphicscontrolblock/) instanser som <br/>            inte är nödvändiga för den slutliga layouten. Genom att följa GIF-specifikationen kommer den <br/>            resulterande bilden att vara korrekt strukturerad och kompatibel med GIF‑visnings <br/>            applikationer. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_76) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_77) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [remove_block(block)](#remove_block_block_78) | Att ta bort ett GIF-block tar bort specifik data från bilden, vilket ger möjlighet att <br/>            rensa upp eller ändra bildstrukturen. Denna metod gör det möjligt att ta bort oönskade <br/>            eller onödiga block, vilket optimerar GIF-bilden för effektiv lagring. Använd denna <br/>            funktion för att eliminera föråldrad information från bilden samtidigt som dess <br/>            integritet och kvalitet bevaras. |
| remove_metadata() | Tar bort metadata för denna bildinstans genom att sätta detta [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) värde till **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Ändrar storlek på detta [Image](/imaging/python-net/aspose.imaging/image/)‑instans. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Ändrar storlek på detta [Image](/imaging/python-net/aspose.imaging/image/)‑instans. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Ändrar storlek på bilden. |
| [resize_full_frame(new_width, new_height, resize_type)](#resize_full_frame_new_width_new_height_resize_type_89) | Ändring av bildens storlek samtidigt som fulla ramar för varje sida i en <br/>            GIF tas i beaktande, vilket förhindrar potentiella artefakter från att uppstå. Denna metod är avgörande <br/>            för att upprätthålla bildens integritet och kvalitet, särskilt när man arbetar med <br/>            animerade GIF‑bilder eller bildsekvenser. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Ändrar bredden proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Ändrar höjden proportionellt. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_94) | Proportionell storleksändring bevarar bildens bildförhållande samtidigt som dess <br/>            storlek justeras, vilket säkerställer att bilden inte blir utdragen eller förvrängd. Denna metod <br/>            ändrar bildens storlek proportionellt, skalar både bredd och höjd med samma faktor.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_95) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_96) | Ändrar bredden proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_97) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_98) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_99) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_100) | Denna metod roterar bilden kring dess mittpunkt. Genom att ange rotations <br/>            vinkeln kan du rotera bilden medurs eller moturs för att uppnå önskad <br/>            orientering. Denna rotation hjälper till att justera bildens presentation eller <br/>            inriktning utan att förvränga dess innehåll. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_101) | Utför rotation, spegling eller båda på den aktiva ramen exklusivt. Denna operation <br/>            tillämpar transformationer enbart på den för närvarande aktiva ramen i bilden, <br/>            samtidigt som integriteten hos övriga ramar i sekvensen bevaras. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_102) | Roterar alla flip. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_103) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_104) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_105) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_106) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_107) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_108) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_109) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_110) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_111) | Sparar pixlarna. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_112) | Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_113) | Sparar pixlarna internt. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_114) | Sparar rådata. |
| [save_to_stream(stream)](#save_to_stream_stream_115) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_116) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_118) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_119) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_120) | Ställer in en bildpixel i 32-bit ARGB för den angivna positionen. |
| [set_frame_time(time)](#set_frame_time_time_121) | Justera varaktigheten för varje ram i millisekunder, vilket säkerställer konsekvent timing <br/>            genom hela bildsekvensen. Denna metod sätter enhetligt visningstiden för <br/>            varje ram, vilket möjliggör exakt kontroll över animationshastigheten.<br/>            Att ändra detta värde återställer fördröjningen för alla ramar. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_122) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_123) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_124) | Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_125) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_127) | Skriver hela skanningsraden till det angivna skanningsradindexet. |


### Constructor: GifImage(first_frame) {#GifImage_first_frame_1}


```
 GifImage(first_frame) 
```

Att skapa GIF‑bilder blir enkelt med [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) <br/>            konstruktor. Med bara firstFrame‑parametern går du in i en värld av dynamisk <br/>            visuell kommunikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Den första ramen för att initiera gif-bilden med. |


**See also:**

**[Example # 1](#example_93)**: This example shows how to create a GIF image and save it to a file.

**[Example # 2](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Constructor: GifImage(first_frame, global_palette) {#GifImage_first_frame_global_palette_2}


```
 GifImage(first_frame, global_palette) 
```

Initiera ett nytt [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/) objekt med angivna parametrar för <br/>            första ramen och global palett. Börja hantera GIF‑bilder snabbt, och säkerställ <br/>            korrekt återgivning med anpassningsbara inställningar för optimala resultat.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Den första ramen för att initiera gif-bilden med. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den globala paletten att använda. Observera att om både _firstFrame_ och _globalPalette_ är null så används standard‑globalpalett. |


**See also:**

**[Example # 1](#example_94)**: This example shows how to create a GIF image with a custom palette and save i...


### Constructor: GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) {#GifImage_first_frame_global_palette_is_palette_sorted_palette_color_resolution_palette_background_color_index_aspect_ratio_has_trailer_3}


```
 GifImage(first_frame, global_palette, is_palette_sorted, palette_color_resolution, palette_background_color_index, aspect_ratio, has_trailer) 
```

Kom igång enkelt med [GifImage](/imaging/python-net/aspose.imaging.fileformats.gif/gifimage/)‑konstruktorn. Med denna <br/>            enkla metoden kan du dyka in i att skapa animerade GIF‑filer med lätthet. Ange bara <br/>            firstFrame, globalPalette, paletteColorResolution, aspectRatio och andra <br/>            parametrar, så är du redo att ge liv åt dina visuella element.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| first_frame | [GifFrameBlock](/imaging/python-net/aspose.imaging.fileformats.gif.blocks/gifframeblock/) | Den första ramen för att initiera gif-bilden med. |
| global_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den globala paletten att använda. Observera att om både _firstFrame_ och _globalPalette_ är null så används standard‑globalpalett. |
| is_palette_sorted | bool | om den är satt till <c>true</c> sorteras paletten. Observera att parametern används när _globalPalette_ inte är null. |
| palette_color_resolution | System.Byte | Palettens färglösning. Observera att parametern används när _globalPalette_ inte är null. |
| palette_background_color_index | System.Byte | Palettens bakgrundsfärgsindex. |
| aspect_ratio | System.Byte | Bildförhållandet. |
| has_trailer | bool | om den är satt till <c>true</c> har gif-bilden en trailer, annars skrivs ingen trailer i slutet av strömmen. |

### Property: active_frame {#active_frame1}

Hantera och manipulera ramar med denna egenskap, vilket möjliggör smidig navigering och <br/>            modifiering av den aktiva ramen i GIF‑bilden.

**See also:**

**[Example # 1](#example_96)**: The following example shows how to remove all blocks from a GIF image.


### Method: add_block(block) {#add_block_block_1}


```
 add_block(block) 
```

Att lägga till ett nytt GIF-block gör att du kan inkludera ytterligare data i bilden. <br/> Denna metod låter dig lägga till anpassade block i GIF-bilden, som kan <br/> innehålla olika typer av information.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | GIF‑blocket att lägga till. |


**See also:**

**[Example # 1](#example_95)**: The following example shows how to compose an animated GIF image from individ...


### Method: add_page(page) {#add_page_page_2}


```
 add_page(page) 
```

Inkludera en ny sida sömlöst i den befintliga bilden, vilket förbättrar dess innehåll <br/> och utökar dess omfattning. Denna metod utökar bildsamlingar med ytterligare <br/> innehåll, vilket främjar kreativitet och flexibilitet i bildhantering och sammansättning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Sidan att lägga till. |


**See also:**

**[Example # 1](#example_217)**: Create multipage GIF image using single page raster images.


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_3}


```
 adjust_brightness(brightness) 
```

Justerar bildens ljusstyrka enligt den angivna<br/> _brightness_-parametern. Denna metod modifierar hela bildens ljusstyrka enhetligt, vilket ökar eller minskar den totala luminansen för att uppnå <br/> önskad effekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |


**See also:**

**[Example # 1](#example_104)**: The following example performs brightness correction of a GIF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_4}


```
 adjust_contrast(contrast) 
```

Justerar bildens kontrast, vilket ökar eller minskar skillnaden i <br/> ljusstyrka mellan pixlar. Denna metod ändrar bildens övergripande tonomfång, <br/> så att mörkare områden blir mörkare och ljusare områden blir ljusare för att förbättra visuell klarhet <br/> och detaljrikedom.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |


**See also:**

**[Example # 1](#example_105)**: The following example performs contrast correction of a GIF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_5}


```
 adjust_gamma(gamma) 
```

Förbättra bildkvaliteten genom att tillämpa gammakorrigering. Denna metod justerar bildens färg<br/> gamma för att uppnå optimal visuell klarhet. Den ändrar gamma‑värdet <br/> för varje pixel, vilket resulterar i förbättrad färgåtergivning och övergripande bildutseende.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |


**See also:**

**[Example # 1](#example_102)**: The following example performs gamma-correction of a GIF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_6}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gammakorrigering av en bild applicerar en icke‑linjär justering av pixelvärdena, <br/> vilket ökar eller minskar ljusstyrkan baserat på de angivna koefficienterna för de röda, <br/> gröna och blå kanalerna. Denna metod hjälper till att finjustera färgbalansen och <br/> luminansen i bilden, vilket förbättrar dess övergripande utseende och visuella kvalitet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma_red | float | Gamma för röd kanal koefficient |
| gamma_green | float | Gamma för grön kanal koefficient |
| gamma_blue | float | Gamma för blå kanalkoefficient |


**See also:**

**[Example # 1](#example_103)**: The following example performs gamma-correction of a GIF image applying diffe...


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

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med <br/> integral bildtröskling är en metod för att konvertera en gråskalebild till en <br/> binär bild. Denna algoritm beräknar en lokal tröskel för varje pixel baserat på <br/> den genomsnittliga intensiteten hos omgivande pixlar inom ett angivet fönster. Genom <br/> att adaptivt justera tröskeln baserat på lokala pixelintensiteter är Bradleys <br/> metod effektiv för att hantera variationer i belysning och kontrast över bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan en pixel och medelvärdet av ett s × s‑fönster av pixlar centrerade kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_9}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan pixeln och medelvärdet av ett s x s fönster av pixlar<br/>                centrerat kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_10}


```
 binarize_fixed(threshold) 
```

Binarisering av en bild med ett fördefinierat tröskelvärde konverterar en gråskala- eller färgbild <br/> till en binär bild, där varje pixel klassificeras som antingen svart eller vit <br/> baserat på om dess intensitetsvärde överstiger ett angivet tröskelvärde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | System.Byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas värdet 255, annars 0. |


**See also:**

**[Example # 1](#example_99)**: The following example binarizes a GIF image with the predefined threshold. Bi...


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


### Method: create_from_files(files)  [static] {#create_from_files_files_28}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_29}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_30}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_31}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_32}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Beskär bild med förskjutningar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left_shift | int | Vänsterskiftet. |
| right_shift | int | Högerskiftet. |
| top_shift | int | Översta skiftet. |
| bottom_shift | int | Nedersta skiftet. |

### Method: crop(rectangle) {#crop_rectangle_33}


```
 crop(rectangle) 
```

Beskär bilden med ett angivet rektangelområde. Denna operation tar bort den yttre <br/> delen av bilden och lämnar endast det valda området som definieras av rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |


**See also:**

**[Example # 1](#example_98)**: The following example crops a GIF image. The cropping area is be specified vi...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_34}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_35}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Applicera dithering på den aktuella bilden. Denna process förbättrar bildkvaliteten genom att <br/>            minska färgbandning och förbättra färgövergångar, vilket resulterar i ett mjukare <br/>            utseende.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den anpassade paletten för dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_36}


```
 embed_digital_signature(password) 
```

Bädda in digital signatur baserad på angivet lösenord i varje sida av bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att generera digitala signaturdata. |

### Method: filter(rectangle, options) {#filter_rectangle_options_37}


```
 filter(rectangle, options) 
```

Applicera ett specifikt filter på det angivna området i bilden, förbättra dess visuella <br/>            kvalitet eller ändra dess utseende enligt önskemål. Denna metod bearbetar selektivt <br/>            pixlar inom den definierade rektangeln, vilket möjliggör riktade justeringar samtidigt <br/>            som integriteten hos den omgivande bilddata bevaras.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_38}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_39}


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


### Method: get_default_options(args) {#get_default_options_args_40}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_41}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_42}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_43}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_44}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_45}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_46}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_47}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_48}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_49}


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


### Method: get_original_options() {#get_original_options__50}


```
 get_original_options() 
```

Hämta de ursprungliga filinställningsbaserade alternativen, avgörande för att upprätthålla trohet <br/>            och konsistens i bildbehandling och manipulation. Denna metod möjliggör sömlös <br/>            integration av filspecifika parametrar i efterföljande operationer, vilket säkerställer <br/>            exakt återgivning och efterlevnad av bildens inneboende egenskaper.<br/>            Detta kan vara hjälpsamt för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svartvit PNG-bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer den resulterande PNG-bilden med 8-bit per pixel att produceras.<br/>            För att undvika detta och spara PNG-bilden med 1-bit per pixel, använd denna metod för att få motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_51}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_52}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_53}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_54}


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


### Method: get_skew_angle() {#get_skew_angle__55}


```
 get_skew_angle() 
```

Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Snedvinkeln, i grader. |


### Method: insert_block(index, block) {#insert_block_index_block_56}


```
 insert_block(index, block) 
```

Att infoga ett nytt GIF-block gör att du kan lägga till anpassad data på en specifik position <br/>            inom bilden. Denna metod möjliggör att placera anpassade block på en önskad <br/>            plats i GIF-bilden, vilket ger flexibilitet i organisering och strukturering av <br/>            bilddata.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Det nollbaserade elementet där blocket kommer att infogas. |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | GIF‑blocket att lägga till. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_57}


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


### Method: load(file_path)  [static] {#load_file_path_58}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_59}


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


### Method: load(stream)  [static] {#load_stream_60}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_61}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_62}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_63}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_64}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_65}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_66}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Läser in 32-bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Läser in 64-bitars ARGB‑pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Den 64-bit ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_68}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Läser in pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Pixelinläsaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_69}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_70}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_71}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_72}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_73}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_74}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_75}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) metoder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_76}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_77}


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


### Method: remove_block(block) {#remove_block_block_78}


```
 remove_block(block) 
```

Att ta bort ett GIF-block tar bort specifik data från bilden, vilket ger möjlighet att <br/>            rensa upp eller ändra bildstrukturen. Denna metod gör det möjligt att ta bort oönskade <br/>            eller onödiga block, vilket optimerar GIF-bilden för effektiv lagring. Använd denna <br/>            funktion för att eliminera föråldrad information från bilden samtidigt som dess <br/>            integritet och kvalitet bevaras.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| block | [IGifBlock](/imaging/python-net/aspose.imaging.fileformats.gif/igifblock/) | Blocket att ta bort. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_79}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_80}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_81}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_82}


```
 replace_non_transparent_colors(new_color) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke‑transparenta färger med en ny färg och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.<br/>                Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta icke-transparenta färger med. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_84}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_85}


```
 resize(new_width, new_height, resize_type) 
```

Ändrar storlek på detta [Image](/imaging/python-net/aspose.imaging/image/)‑instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_86}


```
 resize(new_width, new_height, settings) 
```

Ändrar storlek på detta [Image](/imaging/python-net/aspose.imaging/image/)‑instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_87}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_88}


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

### Method: resize_full_frame(new_width, new_height, resize_type) {#resize_full_frame_new_width_new_height_resize_type_89}


```
 resize_full_frame(new_width, new_height, resize_type) 
```

Ändring av bildens storlek samtidigt som fulla ramar för varje sida i en <br/>            GIF tas i beaktande, vilket förhindrar potentiella artefakter från att uppstå. Denna metod är avgörande <br/>            för att upprätthålla bildens integritet och kvalitet, särskilt när man arbetar med <br/>            animerade GIF‑bilder eller bildsekvenser.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_90}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_91}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_92}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_93}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_94}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Proportionell storleksändring bevarar bildens bildförhållande samtidigt som dess <br/>            storlek justeras, vilket säkerställer att bilden inte blir utdragen eller förvrängd. Denna metod <br/>            ändrar bildens storlek proportionellt, skalar både bredd och höjd med samma faktor.<br/>            Den proportionella storleksändringen kommer att ändra varje ram enligt förhållandet _newWidth_/width och _newHeight_/height.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_95}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_96}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_97}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_98}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_99}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_100}


```
 rotate(angle, resize_proportionally, background_color) 
```

Denna metod roterar bilden kring dess mittpunkt. Genom att ange rotations <br/>            vinkeln kan du rotera bilden medurs eller moturs för att uppnå önskad <br/>            orientering. Denna rotation hjälper till att justera bildens presentation eller <br/>            inriktning utan att förvränga dess innehåll.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | om den är satt till <c>true</c> kommer bildens storlek att ändras<br/>
            enligt den roterade rektangelns (hörnpunkternas) projektioner i annat<br/>
            fall lämnas dimensionerna orörda och endast<br/>
            __internal__ bildinnehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_101}


```
 rotate_flip(rotate_flip_type) 
```

Utför rotation, spegling eller båda på den aktiva ramen exklusivt. Denna operation <br/>            tillämpar transformationer enbart på den för närvarande aktiva ramen i bilden, <br/>            samtidigt som integriteten hos övriga ramar i sekvensen bevaras.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändningstypen. |


**See also:**

**[Example # 1](#example_97)**: This example loads a GIF image, rotates it by 90 degrees clockwise and option...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_102}


```
 rotate_flip_all(rotate_flip) 
```

Roterar alla flip.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändning. |

### Method: save(file_path) {#save_file_path_103}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_104}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_105}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_106}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_107}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_108}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_109}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_110}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_111}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlar presenterade som 32-bitars heltalsvärden. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_112}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_113}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlarna internt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Pixlarna. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_114}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_115}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_116}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_117}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_118}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_119}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_120}


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

### Method: set_frame_time(time) {#set_frame_time_time_121}


```
 set_frame_time(time) 
```

Justera varaktigheten för varje ram i millisekunder, vilket säkerställer konsekvent timing <br/>            genom hela bildsekvensen. Denna metod sätter enhetligt visningstiden för <br/>            varje ram, vilket möjliggör exakt kontroll över animationshastigheten.<br/>            Att ändra detta värde återställer fördröjningen för alla ramar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tid | int | Tiden för bildrutes varaktighet i millisekunder. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_122}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_123}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_124}


```
 set_resolution(dpi_x, dpi_y) 
```

Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | float | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_125}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_126}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int[] | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_127}


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
### This example shows how to create a GIF image and save it to a file. {#example_93}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color


# Skapa ett GIF-ramblock på 100x100 px.
with GifFrameBlock(100, 100) as firstBlock:
	# Fyll hela blocket med rött.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	with GifImage(firstBlock) as gifImage:
		gifImage.save("output.gif")


```

### This example shows how to create a GIF image with a custom palette and save it to a file. {#example_94}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color, ColorPaletteHelper


# Skapa ett GIF-ramblock på 100x100 px.
with GifFrameBlock(100, 100) as firstBlock:
	# Fyll hela blocket med rött.
	gr = Graphics(firstBlock)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, firstBlock.bounds)

	# Använd en 4-bitars palett för att minska bildstorleken. Kvaliteten kan bli sämre.
	palette = ColorPaletteHelper.create_4_bit()

	with GifImage(firstBlock, palette) as gifImage:
		gifImage.save("output.gif")


```

### The following example shows how to compose an animated GIF image from individual GIF blocks. {#example_95}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 
from aspose.imaging.brushes import SolidBrush
from aspose.imaging import Graphics, Color

# Skapa en GIF-bild 100 x 100 px.
# Det första blocket är helt svart som standard.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		# Den första cirkeln är röd
		brush1 = SolidBrush(Color.red)

		# Den andra cirkeln är svart
		brush2 = SolidBrush(Color.black)

		# Öka gradvis vinkeln på den röda bågformen.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush1, block.bounds, 0, angle)
			gifImage.add_block(block)
		
		# Öka gradvis vinkeln på den svarta bågen och radera den röda bågen.
		for angle in range(10, 361, 10):
			block = GifFrameBlock(100, 100)
			gr = Graphics(block)
			gr.fill_pie(brush2, block.bounds, 0, angle)
			gr.fill_pie(brush1, block.bounds, angle, 360 - angle)
			gifImage.add_block(block)

		gifImage.save("animated_radar.gif")


```

### The following example shows how to remove all blocks from a GIF image. {#example_96}
``` python
from aspose.imaging.fileformats.gif.blocks import GifFrameBlock
from aspose.imaging.fileformats.gif import GifImage 

# Skapa en GIF-bild 100 x 100 px.
# Det första blocket är helt svart som standard.
with GifFrameBlock(100, 100) as firstBlock:
	with GifImage(firstBlock) as gifImage:
		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

		print("Clear all the blocks")
		gifImage.clear_blocks()

		if gifImage.active_frame is not None:
			print(f"Active frame size: {gifImage.active_frame.size}")
		else:
			print("Active frame is not set")

# Utdata ser ut så här:
# Aktiv ramstorlek: { Width = 100, Height = 100}
# Rensa alla block
# Aktiv ram är inte inställd

```

### This example loads a GIF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_97}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Rotera, vänd och spara till utdatafilen.
	with aspycore.as_of(Image.load(join(dir_, "sample.gif")), GifImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example crops a GIF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_98}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.gif import GifImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Beskär bilden. Beskärningsområdet är bildens rektangulära centrala område.
	area = Rectangle(gif_image.width // 4, gif_image.height // 4, gif_image.width // 2,
					 gif_image.height // 2)
	gif_image.crop(area)
	# Spara den beskurna bilden som PNG
	gif_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a GIF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_99}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	djvu_image = aspycore.as_of(image, GifImage)
	# Binärisera bilden med ett tröskelvärde på 127.
	# Om ett motsvarande gråvärde för en pixel är större än 127, tilldelas värdet 255, annars 0.
	djvu_image.binarize_fixed(127)
	djvu_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image. {#example_102}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp\\"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Ställ in gamma‑koefficient för röd, grön och blå kanal.
	gif_image.adjust_gamma(2.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a GIF image applying different coefficients for color components. {#example_103}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Ställ in individuella gamma‑koefficienter för röd, grön och blå kanal.
	gif_image.adjust_gamma(1.5, 2.5, 3.5)
	gif_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a GIF image. {#example_104}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.gif import GifImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.gif")) as image:
	gif_image = aspycore.as_of(image, GifImage)
	# Ställ in ljushetsvärdet. Godkända värden för ljushet ligger i intervallet [-255, 255].
	gif_image.adjust_brightness(50)
	gif_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a GIF image. {#example_105}
``` python


import aspose.pycore as aspycore

from aspose.imaging import Image

from aspose.imaging.fileformats.gif import GifImage

from aspose.imaging.imageoptions import PngOptions

from os.path import join



dir_ = "c:\\temp"

with Image.load(join(dir_, "sample.gif")) as image:

	gif_image = aspycore.as_of(image, GifImage)

	# Ställ in kontrastvärdet. Godkända värden för kontrast ligger i intervallet [-100f, 100f].

	gif_image.adjust_contrast(50.0)

	gif_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())



# ExEnd

```

### Create multipage GIF image using single page raster images. {#example_217}
``` python
from aspose.imaging import Image, RasterImage
from aspose.pycore import as_of
from os import listdir
from os.path import isfile, join

def load_frames(directory):
	for f in listdir(directory):
		full_path = join(directory, f)
		if isfile(full_path):
			yield as_of(Image.load(file_path), RasterImage)


# Läs in ramar
frames = list(load_frames("Animation frames"))
# Skapa GIF-bild med den första ramen
with GifImage(GifFrameBlock(frames[0])) as image:
	# Lägg till ramar i GIF-bilden med metoden AddPage
	for index in range(1, len(frames)):
		image.add_page(frames[index])

	# Spara GIF-bild
	image.save("Multipage.gif")
	
for it in frames:
	with it as _:
		# Frigör bilderna
		pass


```

### Export of part of animation from GIF image based on time interval. {#example_223}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import GifOptions, MultiPageOptions, MultiPageMode, TimeInterval

with Image.load("Animation.gif") as image:
	obj_init = MultiPageOptions()
	obj_init.mode = MultiPageMode.TIME_INTERVAL
	obj_init.time_interval = TimeInterval(0, 400)
	options = GifOptions()
	options.full_frame = True
	options.multi_page_options = obj_init
	image.save("PartOfAnimation.gif", options)


```

