---
title: "BmpImage-klass"
type: docs
weight: 50
url: /sv/python-net/aspose.imaging.fileformats.bmp/bmpimage/
---

**Summary:** You can effortlessly handle Bitmap (BMP) and Device Independent Bitmap<br/>            (DIB) files, facilitating efficient manipulation and processing of raster<br/>            images. Performing various operations on images, this API streamlines the<br/>            workflow, offering developers a reliable toolkit for working with BMP and<br/>            DIB formats in their software applications.

**Module:** [aspose.imaging.fileformats.bmp](/imaging/python-net/aspose.imaging.fileformats.bmp/)

**Full Name:** aspose.imaging.fileformats.bmp.BmpImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [BmpImage(path)](#BmpImage_path_1) | Börja använda BmpImage-klassen enkelt med den här konstruktorn som<br/>            initierar en ny instans. Perfekt för utvecklare som vill komma igång och<br/>            arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) objekt snabbt och effektivt. |
| [BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2) | Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen med den här konstruktorn,<br/>            genom att använda angivna parametrar som sökväg, bitsPerPixel och komprimering. Idealiskt för utvecklare<br/>            som vill initiera BmpImage-objekt snabbt och effektivt, med exakt kontroll<br/>            över bildens egenskaper. |
| [BmpImage(raster_image)](#BmpImage_raster_image_3) | Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen<br/>            genom att initiera den med ett RasterImage-objekt. Perfekt för utvecklare som vill<br/>            sömlöst konvertera befintliga rasterbilder till BmpImage-formatet, vilket säkerställer<br/>            kompatibilitet och enkel integration i deras projekt. |
| [BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4) | Börja arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att skapa en ny instans<br/>            med en rasterImage samt angivna parametrar som bitsPerPixel och komprimering.<br/>            Perfekt för utvecklare som söker ett enkelt sätt att hantera BmpImage-objekt,<br/>            vilket säkerställer flexibilitet och effektivitet i deras projekt. |
| [BmpImage(stream)](#BmpImage_stream_5) | Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen enkelt genom att initiera en ny instans<br/>            med den här konstruktorn, med en ström som indata. Perfekt för utvecklare som söker<br/>            ett bekvämt sätt att arbeta med BmpImage-objekt från olika datakällor,<br/>            vilket säkerställer flexibilitet och enkel integration. |
| [BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6) | Börja arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att skapa<br/>            en ny instans med en ström, samt angivna parametrar som bitsPerPixel<br/>            och komprimering. Perfekt för utvecklare som söker ett enkelt sätt att hantera<br/>            BmpImage-objekt, vilket säkerställer flexibilitet och effektivitet i deras projekt. |
| [BmpImage(width, height)](#BmpImage_width_height_7) | Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen enkelt genom att skapa en ny instans<br/>            med angivna bredd- och höjdparametrar. Idealiskt för utvecklare som söker<br/>            ett bekvämt sätt att generera BmpImage-objekt med anpassade dimensioner, vilket säkerställer<br/>            flexibilitet och enkel integration i deras projekt. |
| [BmpImage(width, height, bits_per_pixel, palette)](#BmpImage_width_height_bits_per_pixel_palette_8) | Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att initiera en ny instans<br/>            med parametrar som bredd, höjd, bitdjup och palett. Perfekt för<br/>            utvecklare som söker ett enkelt sätt att skapa BmpImage-objekt med<br/>            anpassade dimensioner och färgkonfigurationer, vilket säkerställer flexibilitet och effektivitet i deras projekt. |
| [BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution)](#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9) | Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen med den här konstruktorn,<br/>            genom att ange parametrar som bredd, höjd, bitsPerPixel och palett. Perfekt för utvecklare<br/>            som söker ett bekvämt sätt att generera BmpImage-objekt med anpassade dimensioner<br/>            och färgkonfigurationer, vilket säkerställer flexibilitet och enkel integration i deras projekt. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| [bitmap_info_header](#bitmap_info_header1) | [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | r | Få snabbt tillgång till viktiga detaljer om din bitmap-bild med denna enkla funktion.<br/>            Perfekt för utvecklare som behöver hämta headerinformation för sina bilder. |
| [bits_per_pixel](#bits_per_pixel2) | int | r | Få enkelt åtkomst till antalet bitar per pixel för bilden med denna egenskap.<br/>            Perfekt för utvecklare som söker snabb information om bildkvalitet och djup. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| [compression](#compression3) | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | r | Hämta kompressionstypen som används för bilden enkelt med den här egenskapen.<br/>            Perfekt för utvecklare som snabbt behöver åtkomst till information om bildkompression. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| [file_format](#file_format4) | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämta enkelt filformatvärdet med denna användarvänliga egenskap.<br/>            Idealiskt för utvecklare som söker snabb åtkomst till information om filformatet. |
| has_alpha | bool | r | Hämtar ett värde som indikerar om denna instans har alfa. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| has_transparent_color | bool | r/w | Hämtar eller anger ett värde som indikerar om denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans har en transparent färg. |
| [height](#height5) | int | r | Hämta bildens höjd enkelt med den här egenskapen. Idealiskt för utvecklare<br/>            som snabbt behöver åtkomst till information om bildens dimensioner. |
| [horizontal_resolution](#horizontal_resolution6) | float | r/w | Denna egenskap låter dig enkelt hämta eller ange den horisontella upplösningen,<br/>            mätt i pixlar per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑objektet. Idealiskt för<br/>            utvecklare som behöver exakt kontroll över bildens upplösning i sina applikationer. |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar bildens metadata. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste förmultipliceras. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Hämtar eller anger den anpassade färgkonvertern |
| [raw_data_format](#raw_data_format7) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämta enkelt formatet för dina rådata med denna användarvänliga funktion.<br/>            Perfekt för utvecklare som vill snabbt få åtkomst till viktig information om deras dataformat. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Hämtar de aktuella inställningarna för rådata. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Hämtar eller anger den indexerade färgkonvertern |
| [raw_line_size](#raw_line_size8) | int | r | Få snabbt åtkomst till storleken på varje rårad i byte med denna enkla egenskap.<br/>            Idealiskt för utvecklare som behöver effektivt hantera rå bilddata. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar bildens transparenta färg. |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| [vertical_resolution](#vertical_resolution9) | float | r/w | Hämta eller ange enkelt den vertikala upplösningen, mätt i pixlar per tum,<br/>            för detta [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑objekt med denna egenskap. Perfekt för utvecklare som kräver<br/>            exakt kontroll över bildens upplösning i sina applikationer. |
| [width](#width10) | int | r | Få enkelt åtkomst till bildens bredd med denna egenskap. Idealiskt för utvecklare<br/>            som söker snabb information om bildens dimensioner. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Justering av ljushet för bilden. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Bildkontrast |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Gammakorrigering av en bild. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Gammakorrigering av en bild. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Beräknar procentuell likhet mellan den extraherade datan och det ursprungliga lösenordet. |
| auto_brightness_contrast() | Utför automatisk adaptiv ljusstyrke‑ och kontrastnormalisering för hela bilden. |
| auto_rotate() | Rotera automatiskt bilden baserat på orienteringsdata som extraheras från Exif <br/>            metadata. Denna metod säkerställer att bilder visas i korrekt orientering, <br/>            förbättrar användarupplevelsen och eliminerar behovet av manuella justeringar. Genom <br/>            att analysera Exif‑information roteras bilden därefter, vilket ger en sömlös <br/>            visningsupplevelse på olika plattformar och enheter. Denna automatiserade rotationsprocess <br/>            förenklar bildhantering och förbättrar den övergripande användbarheten, särskilt när <br/>            man hanterar stora bildsatser med varierande orienteringar. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binärisering av en bild med fördefinierad tröskel |
| binarize_otsu() | Binärisering av en bild med Otsu-tröskelvärde |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Blandar denna bildinstans med _overlay_-bilden. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Blandar denna bildinstans med _overlay_-bilden. |
| cache_data() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_11) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_13) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_save(options)](#can_save_options_18) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(files)](#create_files_19) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_23) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26) | Börja enkelt använda BmpImage‑klassen med denna konstruktor, vilket förenklar<br/>            processen att initiera en ny instans. Idealiskt för utvecklare som söker<br/>            ett snabbt och effektivt sätt att integrera [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/)‑objekt i sina projekt. |
| [create_from_files(files)](#create_from_files_files_27) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_28) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_image(raster_image)](#create_from_image_raster_image_29) | Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30) | Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)](#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34) | Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_35) | Beskär bild med förskjutningar. |
| [crop(rectangle)](#crop_rectangle_36) | Beskär bilden. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_37) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_38) | Utför dithering på den aktuella bilden. |
| [embed_digital_signature(password)](#embed_digital_signature_password_39) | Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi. |
| [filter(rectangle, options)](#filter_rectangle_options_40) | Filtrerar den angivna rektangeln. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_41) | Hämtar en bildpixel i 32-bitars ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_42) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_43) | Hämta standardalternativen enkelt med denna enkla metod.<br/>            Idealiskt för utvecklare som söker snabb åtkomst till standardinställningar eller konfigurationer för bilder. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_44) | Hämtar standardpixelarrayen med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45) | Hämtar standardarrayen för rådata med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_46) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_47) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_48) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_49) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_50) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_51) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_52) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__53) | Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_54) | Hämtar en bildpixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_55) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_56) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_57) | Konverterar till aps. |
| [get_skew_angle()](#get_skew_angle__58) | Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| grayscale() | Transformation av en bild till dess gråskalerepresentation |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_59) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet. |
| [load(file_path)](#load_file_path_60) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_61) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_62) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_63) | Läser in en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_64) | Läser in 32-bitars ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_65) | Läser in 64-bitars ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_66) | Läser in pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_67) | Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68) | Läser in 32-bitars ARGB‑pixlar delvis (i block). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69) | Läser in 64-bitars ARGB‑pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_70) | Läser in pixlar delvis i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_71) | Läser in pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72) | Läser in rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73) | Läser in rådata. |
| [load_stream(stream)](#load_stream_stream_74) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_75) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_76) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| normalize_angle() | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_77) | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| normalize_histogram() | Normaliserar bildens histogram — justera pixelvärden för att använda hela tillgängliga intervallet. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_78) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_79) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| remove_metadata() | Tar bort metadata för denna bildinstans genom att sätta detta [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) värde till **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_80) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_81) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_82) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_83) | Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_84) | Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_85) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_86) | Ändrar storlek på bilden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_87) | Ändrar storlek på bilden. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_88) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_89) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_90) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_91) | Ändrar höjden proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_92) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_93) | Ändrar höjden proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_94) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_95) | Ändrar bredden proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_96) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_97) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_98) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_99) | Rotera bilden kring centrum. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_100) | Rotera, vänd eller rotera och vänd bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_101) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_102) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_103) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_104) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_105) | Sparar objektets data till den angivna strömmen. |
| [save(stream, options_base)](#save_stream_options_base_106) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_107) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_108) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_109) | Sparar pixlarna. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_110) | Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_111) | Sparar pixlar (formatspecifik metod). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_112) | Sparar rådata. |
| [save_to_stream(stream)](#save_to_stream_stream_113) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_114) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_116) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_117) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_118) | Ställer in en bildpixel i 32-bit ARGB för den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_119) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_120) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_121) | Justera upplösningen för din [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) enkelt med denna<br/>            användarvänliga metod. Perfekt för utvecklare som söker exakt kontroll över<br/>            bildens upplösning i sina applikationer. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_122) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_124) | Skriver hela skanningsraden till det angivna skanningsradindexet. |


### Constructor: BmpImage(path) {#BmpImage_path_1}


```
 BmpImage(path) 
```

Börja använda BmpImage-klassen enkelt med den här konstruktorn som<br/>            initierar en ny instans. Perfekt för utvecklare som vill komma igång och<br/>            arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) objekt snabbt och effektivt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in bilden från och initiera pixel‑ och palettdata med. |


**See also:**

**[Example # 1](#example_77)**: The example shows how to load a BmpImage from a file.


### Constructor: BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_2}


```
 BmpImage(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen med den här konstruktorn,<br/>            genom att använda angivna parametrar som sökväg, bitsPerPixel och komprimering. Idealiskt för utvecklare<br/>            som vill initiera BmpImage-objekt snabbt och effektivt, med exakt kontroll<br/>            över bildens egenskaper.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in bilden från och initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |


**See also:**

**[Example # 1](#example_78)**: The example shows how to load a BmpImage from a file with the specified bit d...


### Constructor: BmpImage(raster_image) {#BmpImage_raster_image_3}


```
 BmpImage(raster_image) 
```

Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen<br/>            genom att initiera den med ett RasterImage-objekt. Perfekt för utvecklare som vill<br/>            sömlöst konvertera befintliga rasterbilder till BmpImage-formatet, vilket säkerställer<br/>            kompatibilitet och enkel integration i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden för att initiera pixel‑ och palettdata med. |


**See also:**

**[Example # 1](#example_81)**: The example shows how to load a BmpImage from another instance of RasterImage.


### Constructor: BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_4}


```
 BmpImage(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Börja arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att skapa en ny instans<br/>            med en rasterImage samt angivna parametrar som bitsPerPixel och komprimering.<br/>            Perfekt för utvecklare som söker ett enkelt sätt att hantera BmpImage-objekt,<br/>            vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden för att initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |


**See also:**

**[Example # 1](#example_82)**: The example shows how to load a BmpImage from another instance of RasterImage...


### Constructor: BmpImage(stream) {#BmpImage_stream_5}


```
 BmpImage(stream) 
```

Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen enkelt genom att initiera en ny instans<br/>            med den här konstruktorn, med en ström som indata. Perfekt för utvecklare som söker<br/>            ett bekvämt sätt att arbeta med BmpImage-objekt från olika datakällor,<br/>            vilket säkerställer flexibilitet och enkel integration.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in bilden från och initiera pixel‑ och palettdata med. |


**See also:**

**[Example # 1](#example_79)**: The example shows how to load a BmpImage from a file stream.


### Constructor: BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) {#BmpImage_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_6}


```
 BmpImage(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Börja arbeta med [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att skapa<br/>            en ny instans med en ström, samt angivna parametrar som bitsPerPixel<br/>            och komprimering. Perfekt för utvecklare som söker ett enkelt sätt att hantera<br/>            BmpImage-objekt, vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in bilden från och initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |


**See also:**

**[Example # 1](#example_80)**: The example shows how to load a BmpImage from a file stream with the specifie...


### Constructor: BmpImage(width, height) {#BmpImage_width_height_7}


```
 BmpImage(width, height) 
```

Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen enkelt genom att skapa en ny instans<br/>            med angivna bredd- och höjdparametrar. Idealiskt för utvecklare som söker<br/>            ett bekvämt sätt att generera BmpImage-objekt med anpassade dimensioner, vilket säkerställer<br/>            flexibilitet och enkel integration i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd. |
| height | int | Bildens höjd. |


**See also:**

**[Example # 1](#example_20)**: The following example shows how to set a palette to a BMP image to reduce its...

**[Example # 2](#example_83)**: The example shows how to create a BmpImage of the specified size.


### Constructor: BmpImage(width, height, bits_per_pixel, palette) {#BmpImage_width_height_bits_per_pixel_palette_8}


```
 BmpImage(width, height, bits_per_pixel, palette) 
```

Börja använda [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen sömlöst genom att initiera en ny instans<br/>            med parametrar som bredd, höjd, bitdjup och palett. Perfekt för<br/>            utvecklare som söker ett enkelt sätt att skapa BmpImage-objekt med<br/>            anpassade dimensioner och färgkonfigurationer, vilket säkerställer flexibilitet och effektivitet i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd. |
| height | int | Bildens höjd. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten. |


**See also:**

**[Example # 1](#example_84)**: The example shows how to create a BmpImage of the specified size with the spe...


### Constructor: BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) {#BmpImage_width_height_bits_per_pixel_palette_compression_horizontal_resolution_vertical_resolution_9}


```
 BmpImage(width, height, bits_per_pixel, palette, compression, horizontal_resolution, vertical_resolution) 
```

Skapa enkelt en ny instans av [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) klassen med den här konstruktorn,<br/>            genom att ange parametrar som bredd, höjd, bitsPerPixel och palett. Perfekt för utvecklare<br/>            som söker ett bekvämt sätt att generera BmpImage-objekt med anpassade dimensioner<br/>            och färgkonfigurationer, vilket säkerställer flexibilitet och enkel integration i deras projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bildens bredd. |
| height | int | Bildens höjd. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Färgpaletten. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |


**See also:**

**[Example # 1](#example_85)**: The example shows how to create a BmpImage using various options.


### Property: bitmap_info_header {#bitmap_info_header1}

Få snabbt tillgång till viktiga detaljer om din bitmap-bild med denna enkla funktion.<br/>            Perfekt för utvecklare som behöver hämta headerinformation för sina bilder.

**See also:**

**[Example # 1](#example_89)**: The following example gets the information from the BMP header and prints it ...


### Property: bits_per_pixel {#bits_per_pixel2}

Få enkelt åtkomst till antalet bitar per pixel för bilden med denna egenskap.<br/>            Perfekt för utvecklare som söker snabb information om bildkvalitet och djup.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: compression {#compression3}

Hämta kompressionstypen som används för bilden enkelt med den här egenskapen.<br/>            Perfekt för utvecklare som snabbt behöver åtkomst till information om bildkompression.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: file_format {#file_format4}

Hämta enkelt filformatvärdet med denna användarvänliga egenskap.<br/>            Idealiskt för utvecklare som söker snabb åtkomst till information om filformatet.

**See also:**

**[Example # 1](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: height {#height5}

Hämta bildens höjd enkelt med den här egenskapen. Idealiskt för utvecklare<br/>            som snabbt behöver åtkomst till information om bildens dimensioner.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: horizontal_resolution {#horizontal_resolution6}

Denna egenskap låter dig enkelt hämta eller ange den horisontella upplösningen,<br/>            mätt i pixlar per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑objektet. Idealiskt för<br/>            utvecklare som behöver exakt kontroll över bildens upplösning i sina applikationer.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: raw_data_format {#raw_data_format7}

Hämta enkelt formatet för dina rådata med denna användarvänliga funktion.<br/>            Perfekt för utvecklare som vill snabbt få åtkomst till viktig information om deras dataformat.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: raw_line_size {#raw_line_size8}

Få snabbt åtkomst till storleken på varje rårad i byte med denna enkla egenskap.<br/>            Idealiskt för utvecklare som behöver effektivt hantera rå bilddata.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Property: vertical_resolution {#vertical_resolution9}

Hämta eller ange enkelt den vertikala upplösningen, mätt i pixlar per tum,<br/>            för detta [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑objekt med denna egenskap. Perfekt för utvecklare som kräver<br/>            exakt kontroll över bildens upplösning i sina applikationer.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Property: width {#width10}

Få enkelt åtkomst till bildens bredd med denna egenskap. Idealiskt för utvecklare<br/>            som söker snabb information om bildens dimensioner.

**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_87)**: The following example shows how the bitmap compression affects the output ima...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Justering av ljushet för bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ljusstyrka | int | Ljusstyrkevärde. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Bildkontrast

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| kontrast | float | Kontrastvärde (i intervallet [-100; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Gammakorrigering av en bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma | float | Gamma för röd, grön och blå kanalers koefficient |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Gammakorrigering av en bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| gamma_red | float | Gamma för röd kanal koefficient |
| gamma_green | float | Gamma för grön kanal koefficient |
| gamma_blue | float | Gamma för blå kanalkoefficient |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan en pixel och medelvärdet av ett s × s‑fönster av pixlar centrerade kring denna pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisering av en bild med Bradleys adaptiva tröskelalgoritm med hjälp av integral‑bildtröskling

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| brightness_difference | float | Ljusstyrkeskillnaden mellan en pixel och medelvärdet av ett s × s‑fönster av pixlar centrerade kring denna pixel. |
| window_size | int | Storleken på ett s x s fönster av pixlar centrerat kring denna pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binärisering av en bild med fördefinierad tröskel

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tröskelvärde | System.Byte | Tröskelvärde. Om motsvarande gråvärde för en pixel är större än tröskeln, tilldelas värdet 255, annars 0. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


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


### Method: can_load(stream)  [static] {#can_load_stream_13}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


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


### Method: can_save(options) {#can_save_options_18}


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


### Method: create(files)  [static] {#create_files_19}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


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


### Method: create(images)  [static] {#create_images_23}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


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


### Method: create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_file_with_params_path_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_26}


```
 create_from_file_with_params(path, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Börja enkelt använda BmpImage‑klassen med denna konstruktor, vilket förenklar<br/>            processen att initiera en ny instans. Idealiskt för utvecklare som söker<br/>            ett snabbt och effektivt sätt att integrera [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/)‑objekt i sina projekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in bilden från och initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_files(files)  [static] {#create_from_files_files_27}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_28}


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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_29}


```
 create_from_image(raster_image) 
```

Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden för att initiera pixel‑ och palettdata med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_image_with_params_raster_image_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_30}


```
 create_from_image_with_params(raster_image, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Bilden för att initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_images(images)  [static] {#create_from_images_images_31}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_32}


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


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_33}


```
 create_from_stream(stream) 
```

Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in bilden från och initiera pixel‑ och palettdata med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution)  [static] {#create_from_stream_with_params_stream_bits_per_pixel_compression_horizontal_resolution_vertical_resolution_34}


```
 create_from_stream_with_params(stream, bits_per_pixel, compression, horizontal_resolution, vertical_resolution) 
```

Initierar en ny instans av klassen [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in bilden från och initiera pixel‑ och palettdata med. |
| bits_per_pixel | int | Antalet bitar per pixel. |
| compression | [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Kompressionen att använda. |
| horizontal_resolution | float | Den horisontella upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |
| vertical_resolution | float | Den vertikala upplösningen. Observera att på grund av avrundning kan den resulterande upplösningen skilja sig något från den angivna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_35}


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

### Method: crop(rectangle) {#crop_rectangle_36}


```
 crop(rectangle) 
```

Beskär bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_37}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_38}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Den anpassade paletten för dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_39}


```
 embed_digital_signature(password) 
```

Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att generera digitala signaturdata. |

### Method: filter(rectangle, options) {#filter_rectangle_options_40}


```
 filter(rectangle, options) 
```

Filtrerar den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_41}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_42}


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


### Method: get_default_options(args) {#get_default_options_args_43}


```
 get_default_options(args) 
```

Hämta standardalternativen enkelt med denna enkla metod.<br/>            Idealiskt för utvecklare som söker snabb åtkomst till standardinställningar eller konfigurationer för bilder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | System.Object | Argumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Standardalternativ |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_44}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_45}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_46}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_47}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_48}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_49}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_50}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_51}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_52}


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


### Method: get_original_options() {#get_original_options__53}


```
 get_original_options() 
```

Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_54}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_55}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_56}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_57}


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


### Method: get_skew_angle() {#get_skew_angle__58}


```
 get_skew_angle() 
```

Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Snedvinkeln, i grader. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_59}


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


### Method: load(file_path)  [static] {#load_file_path_60}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_61}


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


### Method: load(stream)  [static] {#load_stream_62}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_63}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_64}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_65}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_66}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_67}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Läser in 32-bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_69}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Läser in 64-bitars ARGB‑pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Den 64-bit ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_70}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Läser in pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Pixelinläsaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_71}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_72}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_73}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_74}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_75}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_76}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_77}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metoder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_78}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_79}


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


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_80}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_81}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Gammal färg att ersätta. |
| old_color_diff | System.Byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Ny färg att ersätta den gamla färgen med. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_82}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_83}


```
 replace_non_transparent_colors(new_color) 
```

Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Ny färg att ersätta icke‑transparenta färger med. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_84}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color_argb | int | Nytt färg-ARGB-värde att ersätta icke-transparenta färger med. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_85}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_86}


```
 resize(new_width, new_height, resize_type) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Resize-typen. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_87}


```
 resize(new_width, new_height, settings) 
```

Ändrar storlek på bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_88}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_89}


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

Ändrar höjden proportionellt.

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

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_94}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_95}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_96}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_97}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_98}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_99}


```
 rotate(angle, resize_proportionally, background_color) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_100}


```
 rotate_flip(rotate_flip_type) 
```

Rotera, vänd eller rotera och vänd bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändningstypen. |

### Method: save(file_path) {#save_file_path_101}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_102}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_103}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_104}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_105}


```
 save(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save(stream, options_base) {#save_stream_options_base_106}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_107}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_108}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_109}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlar presenterade som 32-bitars heltalsvärden. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_110}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_111}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlar (formatspecifik metod).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 32-bitars ARGB-pixelarrayen. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_112}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_113}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_114}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_115}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_116}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_117}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_118}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_119}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_120}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_121}


```
 set_resolution(dpi_x, dpi_y) 
```

Justera upplösningen för din [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) enkelt med denna<br/>            användarvänliga metod. Perfekt för utvecklare som söker exakt kontroll över<br/>            bildens upplösning i sina applikationer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | float | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |


**See also:**

**[Example # 1](#example_19)**: The following example gets the general information about the image including ...

**[Example # 2](#example_88)**: The following example shows how to set horizontal/vertical resolution of a BM...


### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_122}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_123}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int[] | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_124}


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
### The following example shows how to create a BMP image of the specified size. {#example_18}
``` python
from aspose.imaging import Color
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join

directory = "c:\\temp\\"

# Skapa en BMP-bild 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Fyll bilden med ett enkelt linjärt röd-svart gradient.
	width = bmpImage.width
	height = bmpImage.height
	for y in range(height):
		for x in range(width):
			hue = (255 * x) // width
			bmpImage.set_pixel(x, y, Color.from_argb(255, hue, 0, 0))

	with open(path_join(directory, "output.bmp"), "w+b") as stream:
		bmpImage.save(stream)


```

### The following example gets the general information about the image including pixel format, image size, resolution, compression etc. {#example_19}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage
from os.path import join as path_join


with Image.load(r"c:\temp\sample.bmp") as image:
	bmpImage = as_of(image, BmpImage)    

	print("The pixel format:", bmpImage.raw_data_format)
	print("The raw line size in bytes:", bmpImage.raw_line_size)
	print("The bitmap compression:", bmpImage.compression)
	print("The bitmap width", bmpImage.width)
	print("The bitmap height", bmpImage.height)
	print("The number of bits per pixel", bmpImage.bits_per_pixel)

	hres = bmpImage.horizontal_resolution
	vres = bmpImage.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", hres)
	print("The vertical resolution, in pixels per inch:", vres)

	if hres != 96.0 or vres != 96.0:
		# Du kan överväga att använda SetResolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
		print("Set resolution values to 96 dpi")
		bmpImage.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch: {0}", bmpImage.horizontal_resolution);
		print("The vertical resolution, in pixels per inch: {0}", bmpImage.vertical_resolution);

	#Utdata kan se ut så här:
	#Pixelformatet: Rgb24Bpp, använda kanaler: 8,8,8
	#Råradens storlek i byte: 1500
	#Bitmap-kompressionen: Rgb
	#Bitmap-bredden: 500
	#Bitmap-höjden: 375
	#Antalet bitar per pixel: 24
	#Den horisontella upplösningen, i pixlar per tum: 0
	#Den vertikala upplösningen, i pixlar per tum: 0
	#Ställ in upplösningsvärden till 96 dpi
	#Den horisontella upplösningen, i pixlar per tum: 96.012
	#Den vertikala upplösningen, i pixlar per tum: 96.012


```

### The following example shows how to set a palette to a BMP image to reduce its output size. {#example_20}
``` python

from aspose.pycore import as_of
from aspose.imaging import Point, Color, Graphics, ColorPaletteHelper
from aspose.imaging.brushes import LinearGradientBrush
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import BmpOptions
from os.path import join as path_join

# Skapa en BMP-bild 100 x 100 px.
with BmpImage(100, 100) as bmpImage:
	# Den linjära gradienten från övre vänstra till nedre högra hörnet av bilden.
	brush = LinearGradientBrush(Point(0, 0), Point(bmpImage.width, bmpImage.height),
								Color.red,
								Color.green)
	# Fyll hela bilden med den linjära gradientpenseln.
	gr = Graphics(bmpImage)
	gr.fill_rectangle(brush, bmpImage.bounds)
	# Hämta den närmaste 8-bitars färgpaletten som täcker så många pixlar som möjligt, så att en palettiserad bild
	# är nästan visuellt omöjlig att skilja från en bmp utan palett
	palette = ColorPaletteHelper.get_close_image_palette(bmpImage, 256)
	# 8-bitars palett innehåller högst 256 färger.
	saveOptions = BmpOptions()
	saveOptions.palette = palette
	saveOptions.bits_per_pixel = 8
	
	with stream_ext.create_memory_stream() as stream:
		bmpImage.save(stream, saveOptions)
		print(f"The size of image with palette is {stream.tell()} bytes.")
		stream.seek(0)
		bmpImage.save(stream)
		print(f"The size of image without palette is {stream.tell()} bytes.")

# Utdata ser ut så här:
# Storleken på bilden med palett är 11078 byte.
# Storleken på bilden utan palett är 40054 byte.

```

### The example shows how to load a BmpImage from a file. {#example_77}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Läs in en BMP-bild från en fil.
# Källpixlarna kommer att konverteras till 32-bpp-format om det krävs.
with BmpImage(os.path.join(directory, "sample.bmp")) as bmp_image:
	# Utför någon bildbehandling.
	# Spara till en annan BMP-fil.
	bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file with the specified bit depth and resolution. {#example_78}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Läs in en BMP-bild från en fil.
# Källpixlarna kommer att konverteras till 24-bpp-format om det krävs.
# Upplösningen kommer att ställas in på 96 dpi.
with BmpImage(os.path.join(directory, "sample.bmp"), 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	# Utför någon bildbehandling.
	# Spara till en annan BMP-fil.
	bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))


```

### The example shows how to load a BmpImage from a file stream. {#example_79}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
import os

directory = r"c:\temp"

# Läs in en BMP-bild från en filström.
# Källpixlarna kommer att konverteras till 32-bpp-format om det krävs.
with open(os.path.join(directory, "sample.bmp"), "rb+") as stream:
	with BmpImage(stream) as bmp_image:
		# Utför någon bildbehandling.
		# Spara till en annan BMP-fil.
		bmp_image.save(os.path.join(directory, "sample.output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from a file stream with the specified bit depth and resolution. {#example_80}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
import os

directory = r"c:\temp"

# Läs in en BMP-bild från en filström.
# Källpixlarna kommer att konverteras till 24-bpp-format om det krävs.
# Upplösningen kommer att ställas in på 96 dpi.
with open(os.path.join(directory, "sample.bmp"), "rb") as stream:
	with BmpImage(stream, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
		# Utför någon bildbehandling.
		# Spara till en annan BMP-fil.
		bmp_image.save(os.path.join(directory, "sample.output.24bpp.96dpi.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage. {#example_81}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# Skapa en ny PNG-bild.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Fyll hela PNG-bilden med rött.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# Skapa en BMP-bild baserad på PNG-bilden.
		# Källpixlarna kommer att konverteras till 32-bpp-format om det krävs.
		with BmpImage(raster_image) as bmp_image:
			# Spara till en BMP-fil
			bmp_image.save(os.path.join(directory, "output.32bpp.bmp"))

```

### The example shows how to load a BmpImage from another instance of RasterImage with the specified bit depth and compression. {#example_82}
``` python

from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging import Image, RasterImage, Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os
import aspose.pycore as aspycore

directory = r"c:\temp"

# Skapa en ny PNG-bild.
with PngOptions() as create_options:
	create_options.source = StreamSource()
	with aspycore.as_of(Image.create(create_options, 100, 100), RasterImage) as raster_image:
		# Fyll hela PNG-bilden med rött.
		gr = Graphics(raster_image)
		brush = SolidBrush(Color.red)
		gr.fill_rectangle(brush, raster_image.bounds)

		# Skapa en BMP-bild baserad på PNG-bilden.
		# Källpixlarna kommer att konverteras till 24-bpp-format om det krävs.
		# Upplösningen kommer att ställas in på 96 dpi.
		with BmpImage(raster_image, 24, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
			# Spara till en BMP-fil
			bmp_image.save(os.path.join(directory, "output.24bpp.96dpi.bmp"))

```

### The example shows how to create a BmpImage of the specified size. {#example_83}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

# Skapa en 32-bpp BMP-bild på 100 x 100 px.
with BmpImage(100, 100) as bmp_image:
	# Fyll hela bilden med rött.
	Graphics gr = Graphics(bmp_image)
	brush = SolidBrush(Color.red)
	gr.fill_rectangle(brush, bmp_image.bounds)
	# Spara till en BMP-fil
	bmp_image.save(os.path.join(directory, "output.bmp"))


```

### The example shows how to create a BmpImage of the specified size with the specified palette. {#example_84}
``` python
from aspose.imaging.fileformats.bmp import BmpImage
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# Skapa en monokrom palett som endast innehåller röda och gröna färger.
palette = ColorPalette.create_with_colors(paletterColors)

# Skapa en monokrom 1-bpp BMP-bild på 100 x 100 px.
with BmpImage(100, 100, 1, palette) as bmp_image:
	gr = Graphics(bmp_image)

	# Fyll den övre halvan av bilden med rött.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Fyll den nedre halvan av bilden med grönt.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# Spara till BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.bmp"))


```

### The example shows how to create a BmpImage using various options. {#example_85}
``` python
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging import Graphics, Color, ColorPalette, Rectangle
from aspose.imaging.brushes import SolidBrush
import os

directory = r"c:\temp"

paletterColors = [Color.red, Color.green]

# Skapa en monokrom palett som endast innehåller röda och gröna färger.
palette = ColorPalette.create_with_colors(paletterColors)

# Skapa en monokrom 1-bpp BMP-bild på 100 x 100 px.
with BmpImage(100, 100, 1, palette, BitmapCompression.RGB, 96.0, 96.0) as bmp_image:
	gr = Graphics(bmp_image)

	# Fyll den övre halvan av bilden med rött.
	redBrush = SolidBrush(Color.red)
	gr.fill_rectangle(redBrush, Rectangle(0, 0, bmp_image.width, bmp_image.height // 2))

	# Fyll den nedre halvan av bilden med grönt.
	greenBrush = SolidBrush(Color.green)
	gr.fill_rectangle(greenBrush, Rectangle(0, bmp_image.height // 2, bmp_image.width, bmp_image.height // 2))

	# Spara till BMP
	bmp_image.save(os.path.join(directory, "output.monochrome.96dpi.bmp"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# Skapa en 32-bpp BMP-bild på 100 x 100 px.
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# Skapa en 24-bpp BMP-bild på 100 x 100 px.
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# Generellt stödjer inte BMP alfakanal, så resultatet kommer att se ut så här:
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, använda kanaler: 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, använda kanaler: 8,8,8, HasAlpha = False

```

### The following example shows how the bitmap compression affects the output image size. {#example_87}
``` python

from aspose.imaging import Color, ColorPalette, Graphics
from aspose.imaging.brushes import SolidBrush
from aspose.imaging.fileformats.bmp import BmpImage, BitmapCompression
from aspose.imaging.extensions import StreamExtensions as strm_ext

compressions = (BitmapCompression.RGB, BitmapCompression.RLE8)

paletterColors = (Color.red, Color.green)

# Skapa en monokrom palett som endast innehåller röda och gröna färger.
palette = ColorPalette.create_with_colors(paletterColors)

for compression in compressions:
	# Skapa en 8-bpp BMP-bild på 100 x 100 px.
	with BmpImage(100, 100, 8, palette, compression, 0.0, 0.0) as bmp_image:
		gr = Graphics(bmp_image)
		# Fyll hela bilden med rött.
		red_brush = SolidBrush(Color.red)
		gr.fill_rectangle(red_brush, bmp_image.bounds)
		# Spara bilden till en minnesström för att få utdatafilens storlek.
		with strm_ext.create_memory_stream() as stream:
			bmp_image.save(stream)
			print("---------------------------------------------")
			print("The compression =", bmp_image.compression.name)
			print("The number of bits per pixel =", bmp_image.bits_per_pixel)
			print(f"The image dimensions = {bmp_image.width} x {bmp_image.height}")
			print("The raw line size =", bmp_image.raw_line_size)
			print("The output size in bytes =", stream.tell())

# Utdata ser ut så här:
# ---------------------------------------------
# Komprimeringen = RGB
# Antalet bitar per pixel = 8
# Bildens dimensioner =100 x 100
# Den råa radstorleken = 100
# Utdata storlek i byte = 1178
# ---------------------------------------------
# Komprimeringen = RLE8
# Antalet bitar per pixel = 8
# Bildens dimensioner =100 x 100
# Den råa radstorleken = 100
# Utdata storlek i byte = 856

```

### The following example shows how to set horizontal/vertical resolution of a BMP image. {#example_88}
``` python

import os
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

directory = r"c:\temp"

with Image.load(os.path.join(directory, "sample.bmp")) as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	# Hämta horisontell och vertikal upplösning för BmpImage
	horizontal_resolution = bmp_image.horizontal_resolution
	vertical_resolution = bmp_image.vertical_resolution
	print("The horizontal resolution, in pixels per inch:", horizontal_resolution)
	print("The vertical resolution, in pixels per inch:", vertical_resolution)

	if (horizontal_resolution != 96.0 || vertical_resolution != 96.0)
	{
		# Använd set_resolution‑metoden för att uppdatera båda upplösningsvärdena i ett enda anrop.
		print("Set resolution values to 96 dpi")
		bmp_image.set_resolution(96.0, 96.0)
		print("The horizontal resolution, in pixels per inch:", bmp_image.horizontal_resolution);
		print("The vertical resolution, in pixels per inch:", bmp_image.vertical_resolution);
	}

	# Utdata kan se ut så här:
	# Den horisontella upplösningen, i pixlar per tum: 0
	# Den vertikala upplösningen, i pixlar per tum: 0
	# Ställ in upplösningsvärden till 96 dpi
	# Den horisontella upplösningen, i pixlar per tum: 96.0
	# Den vertikala upplösningen, i pixlar per tum: 96.0

```

### The following example gets the information from the BMP header and prints it to the console. {#example_89}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.bmp import BmpImage

with Image.load(r"c:\temp\sample.bmp") as image:
	bmp_image = aspycore.as_of(image, BmpImage)
	header = bmp_image.bitmap_info_header

	print("The number of palette colors that are required for displaying the bitmap:", header.bitmap_colors_important)
	print("The number of palette colors used in the bitmap:", header.bitmap_colors_used)
	print("The bitmap compression:", header.bitmap_compression)
	print("The bitmap height:", header.bitmap_height)
	print("The bitmap width:", header.bitmap_width)
	print("The bitmap raw data size in bytes:", header.bitmap_image_size)
	print("The number of planes:", header.bitmap_planes)
	print("The horizontal resolution of the bitmap, in pixels-per-meter:", header.bitmap_x_pels_per_meter)
	print("The vertical resolution of the bitmap, in pixels-per-meter:", header.bitmap_y_pels_per_meter)
	print("The number of bits per pixel:", header.bits_per_pixel)
	print("The extra bits masks:", header.extra_bit_masks)
	print("The header size in bytes:", header.header_size)

#Utdata kan se ut så här:
#Antalet palettfärger som krävs för att visa bitmapen: 0
#Antalet palettfärger som används i bitmapen: 0
#Bitmap-komprimeringen: 0
#Bitmap-höjden: 375
#Bitmap-bredden: 500
#Bitmapens rådatastorlek i byte: 562500
#Antalet plan: 1
#Den horisontella upplösningen för bitmapen, i pixlar per meter: 0
#Den vertikala upplösningen för bitmapen, i pixlar per meter: 0
#Antalet bitar per pixel: 24
#De extra bitmaskerna: 
#Headerstorleken i byte: 40

```

### Compress BMP image using DXT1 compression algorithm. {#example_207}
``` python
#cxFor:aspose.imaging.imageoptions.BmpOptions.compression

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.fileformats.bmp import BitmapCompression

with Image.load("Tiger.bmp") as image:
	bmp_options = BmpOptions()
	bmp_options.compression = BitmapCompression.DXT1
	image.save("CompressedTiger.bmp", bmp_options)

```

### Decompress BMP image which was previously compressed using DXT1 compression algorithm. {#example_208}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions

with Image.load("CompressedTiger.bmp") as image:
	image.save("DecompressedTiger.bmp", BmpOptions())


```

