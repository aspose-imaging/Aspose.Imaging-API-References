---
title: "TgaImage-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.imaging.fileformats.tga/tgaimage/
---

**Summary:** Manipulate TGA raster image files with our API, tailored for the TARGA<br/>            (Truevision Advanced Raster Adapter) format, enabling seamless loading and<br/>            customization. Easily update public properties such as author, timestamp,<br/>            image ID, and software version, while using various bits per pixel settings,<br/>            alpha channel and color transparency. Additionally, you can export TGA images<br/>            to other popular raster formats, ensuring compatibility for your projects.

**Module:** [aspose.imaging.fileformats.tga](/imaging/python-net/aspose.imaging.fileformats.tga/)

**Full Name:** aspose.imaging.fileformats.tga.TgaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, RasterCachedImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TgaImage(path)](#TgaImage_path_1) | Initierar ett nytt [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) objekt med den angivna filsökvägen för <br/> inläsning av bildinnehållet. Denna konstruktor initierar bildinstansen effektivt, vilket möjliggör sömlös åtkomst till TGA-bildfiler och förenklar integrationen <br/> i ditt applikationsflöde. |
| [TgaImage(raster_image)](#TgaImage_raster_image_2) | Skapa en ny instans av [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) klassen genom att tillhandahålla ett raster <br/> bildobjekt. Denna konstruktor underlättar direktintegration av befintliga <br/> rasterbilder i TGA-bildformatet, vilket strömlinjeformar konverteringsprocessen för <br/> förbättrad kompatibilitet i dina mjukvarusystem. |
| [TgaImage(stream)](#TgaImage_stream_3) | Initiera en ny instans av [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) klassen med en ström för <br/> att läsa in bilden. Denna konstruktor möjliggör sömlös integration av bilddata <br/> från strömmar, vilket underlättar effektiv hantering och bearbetning av TGA-bilder inom <br/> dina mjukvaruapplikationer. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| author_comments | string | r/w | Hämtar eller anger kommentarer som tillhandahållits av bildens författare. Dessa kommentarer <br/> innehåller ofta värdefull information, såsom beskrivningar, annotationer eller <br/> ytterligare sammanhang kring bilden. Genom att komma åt eller ändra egenskapen Author Comments <br/> kan utvecklare förbättra metadata som är kopplade till bilden, vilket ger <br/> användare värdefulla insikter och sammanhang om dess innehåll eller skapelse.<br/> Detta är ett ASCII-fält på 324 byte som är organiserat som fyra rader<br/> med 80 tecken vardera, var och en följd av en null-terminator. |
| author_name | string | r/w | Hämtar eller anger namnet på författaren som är kopplad till bilden. Denna egenskap <br/> gör det möjligt för utvecklare att komma åt eller ändra författarens namnmetadata, vilket ger <br/> värdefull information om bildens skapare. Genom att använda egenskapen Author Name <br/> kan användare enkelt identifiera den person som ansvarar för att ha skapat eller <br/> bidragit till bilden, vilket förbättrar dess övergripande metadata och ger värdefullt <br/> sammanhang för betraktare.<br/> Detta fält består av totalt 40 ASCII-tecken för namnet. Om fältet används,<br/> bör det innehålla namnet på personen som skapade bilden (författare). |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger bakgrundsfärgen för bilden. Denna egenskap låter <br/> dig specificera färgen som används för bildens bakgrund, vilket säkerställer konsistens och <br/> förbättrar den visuella presentationen. Den är särskilt användbar i scenarier där <br/> bilden visas på en bakgrund med en annan färg eller vid rendering av <br/> bilden på en annan canvas. |
| bits_per_pixel | int | r | Hämta värdet för bitar per pixel, vilket ger viktig information om bildens <br/> färgdjup. Denna egenskap fungerar som ett avgörande mått för att förstå <br/> detaljnivån och färgrikedomen i bilden, vilket hjälper utvecklare att <br/> optimera bearbetningsalgoritmer och resursallokering för effektiv bild-<br/> manipulation och renderingsuppgifter. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| bytes_per_pixel | int | r | Hämta värdet för byte per pixel, vilket anger hur mycket minne varje pixel i bilden upptar. Denna egenskap fungerar som ett viktigt mått för minneshantering och optimering, vilket hjälper utvecklare att effektivt allokera resurser <br/> och bearbeta bilddata. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| date_time_stamp | System.Nullable`1[[System.DateTime]] | r/w | Hämtar eller anger datum/tidsstämpel.<br/> Detta fält definierar värdet för datum och tid då bilden sparades. <br/> Även om operativsystem vanligtvis tids- och datumstämplar filer, tillhandahålls denna funktion<br/> eftersom operativsystemet kan ändra tids- och datumstämpeln om filen <br/> kopieras. Genom att använda detta område garanteras ett oförändrat område för datum- och tidsregistrering. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämta viktig information om bildens filformat som representeras av denna <br/> instans av [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/)... Att förstå filformatet är avgörande för <br/> kompatibilitetskontroller och för att säkerställa sömlös integration i mjukvarusystem, <br/> vilket möjliggör effektiv bearbetning och manipulation av bilder. |
| gamma_value_denominator | int | r | Hämtar nämnardelen av gamma-värdet, en viktig faktor för <br/> att bestämma färgrepresentation i bilder. För bilder utan gamma-<br/> korrigering bör detta värde vara 1,0, vilket säkerställer korrekt färgrendering. <br/> Att förstå och utnyttja denna parameter är grundläggande för att upprätthålla färg<br/> trohet och uppnå exakt bildvisualisering. |
| gamma_value_numerator | int | r | Hämtar täljardelen av gamma-värdet, vilket är avgörande för korrekt färg<br/> representation i bilder. I bilder utan gamma-korrigering bör detta värde vara <br/> 1,0. Att förstå och använda detta värde är viktigt för att bevara färg<br/> trohet och säkerställa korrekt bildrendering. |
| has_alpha | bool | r | Hämta ett booleskt värde som indikerar om [TgaImage] innehåller en <br/> alfakanal, vilket möjliggör transparenseffekter. Denna egenskap ger viktig <br/> information för hantering av bildkomposition och rendering, och hjälper utvecklare att <br/> implementera olika visuella effekter och sammansättningsoperationer. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som visar om bilden innehåller en bakgrunds<br/> färg. Denna egenskap är användbar för att avgöra om bilden har en <br/> tydlig bakgrundsfärg som skiljer sig från förgrundsinnehållet. Den gör det möjligt att anpassa bildbehandling eller rendering baserat på om en bakgrundsfärg <br/> finns eller saknas. |
| has_color_map | bool | r | Hämta om denna [TgaImage]-instans innehåller en färgkarta. <br/> Att förstå närvaron av en färgkarta är avgörande för korrekt tolkning <br/> och manipulation av bildens färgdata. |
| has_transparent_color | bool | r/w | Hämtar eller anger ett booleskt värde som visar om bilden innehåller en <br/> transparent färg. Denna egenskap är viktig för att identifiera om bilden <br/> stödjer transparens, vilket hjälper dig att implementera lämplig hantering av <br/> transparensrelaterade operationer såsom blandning, sammansättning eller maskning. |
| height | int | r | Hämta bildens höjd som kapslas in av detta [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            instans. Denna egenskap ger utvecklare kritisk information om bildens vertikala dimensioner, vilket möjliggör sömlös integration och manipulation av bilder i deras programvarulösningar. |
| horizontal_resolution | float | r/w | Hämtar eller anger den horisontella upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_id | string | r/w | Hämtar eller anger den unika identifieraren som är associerad med bilden. Detta ID fungerar som en <br/>            referenspunkt för att identifiera och särskilja bilden från andra inom ett <br/>            system eller en applikation. Genom att ange eller läsa av Bild‑ID:t kan du hantera och <br/>            spåra bilder effektivt, vilket underlättar organiserad bildhantering och återhämtnings‑<br/>            processer.<br/>            <br/>Detta valfria fält innehåller identifierande information om bilden. Den maximala längden<br/>            för detta fält är 255 byte.<br/> |
| image_opacity | float | r | Hämtar opaciteten för denna bild. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om bilddata för närvarande är cachad. |
| is_gray_scale | bool | r | Hämta ett booleskt värde som indikerar om [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            representerar en gråskalebild. Denna egenskap är avgörande för att särskilja färg‑ och <br/>            gråskalebilder, vilket hjälper utvecklare att tillämpa lämpliga bearbetnings‑ och <br/>            renderingsmetoder baserat på bildens färgkaraktäristik. |
| is_raw_data_available | bool | r | Hämtar ett värde som indikerar om inläsning av rådata stöds. |
| job_name_or_id | string | r/w | Hämtar eller anger jobbnamnet eller ID:t som är kopplat till bilden. Denna egenskap <br/>            gör det möjligt att komma åt eller ändra metadata relaterade till det specifika jobbet eller projektet <br/>            som är associerat med bilden. Genom att använda egenskapen Jobbnamn/ID kan användare enkelt <br/>            identifiera det projekt eller den uppgift som bilden tillhör, vilket underlättar <br/>            organisering och hantering av bildresurser inom större arbetsflöden eller projekt. |
| job_time | System.Nullable`1[[System.TimeSpan]] | r/w | Hämtar eller anger tidsstämpeln som indikerar jobbtiden som är kopplad till bilden. <br/>            Denna egenskap låter utvecklare komma åt eller ändra tidsmetadata relaterad till <br/>            det specifika jobbet eller projektet som är associerat med bilden. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar bildens metadata. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| pixel_aspect_ratio_denominator | int | r | Hämtar nämnardelen av Pixel Aspect Ratio, en avgörande faktor för <br/>            att bestämma den visuella aspekten av pixlar i bilden. Detta värde är nödvändigt <br/>            för att bevara korrekt pixelrepresentation och bildförhållanden genom olika <br/>            bildrenderings‑ och bearbetningsoperationer, vilket säkerställer högkvalitativ visuell output. |
| pixel_aspect_ratio_numerator | int | r | Hämtar täljarens komponent av Pixel Aspect Ratio, som påverkar den <br/>            visuella aspekten av pixlar i bilden. Att förstå och manipulera detta <br/>            värde är nödvändigt för att uppnå korrekt pixelrepresentation och bildförhållanden <br/>            vid bildrendering och bearbetning. |
| premultiply_components | bool | r/w | Hämtar eller anger ett värde som indikerar om bildkomponenterna måste förmultipliceras. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Hämtar eller anger den anpassade färgkonvertern |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Hämtar det råa dataformatet. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Hämtar de aktuella inställningarna för rådata. Observera att när dessa inställningar används laddas data utan konvertering. |
| raw_fallback_index | int | r/w | Hämtar eller anger reservindexet som ska användas när palettindexet är utanför gränserna |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Hämtar eller anger den indexerade färgkonvertern |
| raw_line_size | int | r | Hämtar den råa radstorleken i byte. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| software_id | string | r/w | Hantera mjukvaruidentifieringen (ID) som är kopplad till bilden, med stöd för <br/>            upp till 40 ASCII‑tecken. Denna egenskap fungerar som ett sätt att unikt identifiera <br/>            den mjukvara som används för att skapa eller bearbeta bilden, vilket ger värdefull <br/>            metadata för organisatoriska och informativa ändamål. |
| software_version | string | r/w | Hämtar eller anger mjukvaruversionen som är kopplad till bilden. Den accepterade <br/>            längden för versionssträngen är vanligtvis 3 till 4 tecken. Denna egenskap är <br/>            användbar för att spåra den mjukvara som använts för att skapa eller manipulera bilden och kan <br/>            ge värdefull kontext för bildbearbetning och kompatibilitetskontroller. |
| software_version_letter | System.Char | r/w | Hämtar eller anger bokstavskomponenten i mjukvaruversionen som är kopplad till <br/>            bilden. Denna egenskap representerar en extra detalj i mjukvaruversionens <br/>            sträng och kan vara användbar för finare versionsdifferentiering. |
| software_version_number | int | r/w | Hämtar eller anger den numeriska komponenten i mjukvaruversionen som är kopplad till <br/>            bilden. Denna egenskap representerar den numeriska delen av mjukvaruversionens <br/>            sträng och ger viktig information om versionen av den mjukvara som använts för att <br/>            skapa eller modifiera bilden. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger nyckelfärgen som är kopplad till bilden. Denna egenskap låter <br/>            dig komma åt eller ändra färgen som är utsedd som nyckelfärg för specifika bild‑<br/>            bearbetningsuppgifter eller effekter. Genom att använda egenskapen Nyckelfärg kan användare <br/>            tillämpa färgbaserade operationer såsom chroma‑keying eller färgbyte, vilket förbättrar <br/>            bildmanipuleringsmöjligheter och kreativa möjligheter.<br/>            <br/>Nyckelfärgen kan betraktas som ‘bakgrundsfärgen’ eller ‘transparent färg’.<br/>            Detta är färgen på det ‘icke‑bild’ området på skärmen, och samma färg som skärmen <br/>            skulle rensas till om den raderas i applikationen.<br/> |
| update_xmp_data | bool | r/w | Hämtar eller anger ett värde som indikerar om XMP-metadata ska uppdateras. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| use_raw_data | bool | r/w | Hämtar eller anger ett värde som indikerar om rådatainläsning ska användas när rådatainläsning är tillgänglig. |
| vertical_resolution | float | r/w | Hämtar eller anger den vertikala upplösningen, i pixlar per tum, för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Hämta bredden på bilden som representeras av detta [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) <br/>            instans. Denna egenskap ger utvecklare viktig information om bildens <br/>            dimensioner, vilket underlättar olika bildmanipulerings‑ och bearbetningsuppgifter <br/>            i deras programvaruapplikationer. |
| x_origin | int | r/w | Hämtar eller anger absolut horisontell koordinat för bildens nedre vänstra hörn<br/>            när den placeras på en displayenhet med ursprung i bildens nedre vänstra hörn av<br/>            skärmen (t.ex. TARGA-serien). |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
| y_origin | int | r/w | Hämtar eller anger absolut vertikal koordinat för bildens nedre vänstra hörn<br/>            när den placeras på en displayenhet med ursprung i bildens nedre vänstra hörn av<br/>            skärmen (t.ex. TARGA-serien). |
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
| [clone()](#clone__19) | Skapar en duplikat av den aktuella instansen och genererar ett nytt objekt som klonar <br/>            alla attribut och egenskaper hos originalet. Denna metod underlättar <br/>            skapandet av identiska kopior, säkerställer dataintegritet och bevarar tillståndet för <br/>            den aktuella instansen utan att påverka originalobjektet. |
| [clone(tga_image)](#clone_tga_image_20) | Replikera egenskaperna hos ett annat [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/)‑objekt, och skapa en <br/>            ny instans med identiska attribut. Denna operation säkerställer bevarandet <br/>            av dataintegritet och underlättar duplicering av bildegenskaper utan <br/>            att förändra källobjektet. |
| [create(files)](#create_files_21) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_22) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_23) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_24) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_25) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_26) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_27) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_files(files)](#create_from_files_files_28) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_29) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_image(raster_image)](#create_from_image_raster_image_30) | Initierar en ny instans av klassen [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [create_from_images(images)](#create_from_images_images_31) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_32) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create_from_stream(stream)](#create_from_stream_stream_33) | Initierar en ny instans av klassen [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_34) | Beskär bilden genom att ange förskjutningar för vänster, höger, topp och botten <br/>            av gränserna. Denna metod låter dig trimma bilden genom att flytta dess gränser <br/>            oberoende längs de horisontella och vertikala axlarna. Genom att justera dessa förskjutningar <br/>            kan du exakt kontrollera vilka delar av bilden som ska behållas, och effektivt <br/>            beskära den till önskade dimensioner. |
| [crop(rectangle)](#crop_rectangle_35) | Beskär bilden till ett specificerat område. Denna metod låter dig definiera ett <br/>            rektangulärt område inom bilden som ska behållas, och kasta resten. Denna operation <br/>            är användbar för att fokusera på specifikt innehåll i bilden eller ta bort oönskade <br/>            delar. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Utför dithering på den aktuella bilden. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Utför dithering på den aktuella bilden. |
| [embed_digital_signature(password)](#embed_digital_signature_password_38) | Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi. |
| [filter(rectangle, options)](#filter_rectangle_options_39) | Filtrerar den angivna rektangeln. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_40) | Hämtar en bildpixel i 32-bitars ARGB. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_41) | Hämtar standardarrayen för 32-bitars ARGB-pixlar. |
| [get_default_options(args)](#get_default_options_args_42) | Hämtar standardalternativen. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_43) | Hämtar standardpixelarrayen med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44) | Hämtar standardarrayen för rådata med partiell pixel‑laddare. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_45) | Hämtar standardarrayen för rådata. |
| [get_file_format(file_path)](#get_file_format_file_path_46) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_47) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_48) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_49) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_50) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_modify_date(use_default)](#get_modify_date_use_default_51) | Hämtar datum och tid då resursbilden senast ändrades. |
| [get_original_options()](#get_original_options__52) | Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern. |
| [get_pixel(x, y)](#get_pixel_x_y_53) | Hämtar en bildpixel. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_54) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_55) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_56) | Konverterar till aps. |
| [get_skew_angle()](#get_skew_angle__57) | Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning. |
| grayscale() | Transformation av en bild till dess gråskalerepresentation |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_58) | Utför en snabb kontroll för att avgöra om bilden är digitalt signerad, med det angivna lösenordet och tröskelvärdet. |
| [load(file_path)](#load_file_path_59) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_60) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_61) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_62) | Läser in en ny bild från den angivna strömmen. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_63) | Läser in 32-bitars ARGB‑pixlar. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_64) | Läser in 64-bitars ARGB‑pixlar. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_65) | Läser in pixlar i CMYK‑format. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_66) | Läser in pixlar i CMYK‑format.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67) | Läser in 32-bitars ARGB‑pixlar delvis (i block). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68) | Läser in 64-bitars ARGB‑pixlar delvis i paket. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_69) | Läser in pixlar delvis i paket. |
| [load_pixels(rectangle)](#load_pixels_rectangle_70) | Läser in pixlar. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71) | Läser in rådata. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72) | Läser in rådata. |
| [load_stream(stream)](#load_stream_stream_73) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_74) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_75) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| normalize_angle() | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_76) | Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metoder. |
| normalize_histogram() | Normaliserar bildens histogram — justera pixelvärden för att använda hela tillgängliga intervallet. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_77) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_78) | Läser hela skanningsraden enligt det angivna skanningsradindexet. |
| remove_metadata() | Tar bort metadata för denna bildinstans genom att sätta detta [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) värde till **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_79) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_80) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_81) | Ersätter en färg med en annan med tillåten skillnad och bevarar det ursprungliga alfa‑värdet för att spara mjuka kanter. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_82) | Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_83) | Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda. |
| [resize(new_width, new_height)](#resize_new_width_new_height_84) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_85) | Justera bildens storlek med en angiven omformningstyp, som bestämmer hur <br/>            omformningsoperationen utförs. Denna metod ger flexibilitet vid omformning <br/>            av bilder enligt olika algoritmer eller tekniker. Genom att välja rätt <br/>            omformningstyp kan du uppnå önskad balans mellan bildkvalitet och beräknings‑effektivitet baserat på specifika krav eller preferenser. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_86) | Ändra bildens storlek samtidigt som du tillämpar specifika inställningar för att behålla önskade <br/>            dimensioner och bildförhållande. Genom att anpassa bildinställningarna kan du effektivt <br/>            ändra bildens storlek samtidigt som du säkerställer optimal visuell kvalitet och kompatibilitet med <br/>            olika displayenheter eller applikationer. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_87) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_88) | Ändrar storlek på bilden. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_89) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_90) | Ändrar höjden proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_91) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_92) | Ändrar höjden proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_93) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_94) | Ändrar bredden proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_95) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_96) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_97) | Rotera bilden kring centrum. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_98) | Roterar bilden kring dess centrum med en angiven vinkel samtidigt som omformnings‑ <br/>            proportioner bibehålls och bakgrundsfärgen bevaras. Denna metod möjliggör <br/>            exakt bildmanipulation och säkerställer att rotationen behåller visuell balans <br/>            och konsistens med den angivna bakgrundsfärgen. Den är idealisk för uppgifter där <br/>            exakt rotation kring centrum är nödvändig, såsom orienteringskorrigering <br/>            eller konstnärliga justeringar. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_99) | Metoden "RotateFlip" möjliggör roterings‑ och vändningsoperationer på bilden. Den <br/>            erbjuder mångsidig funktionalitet för att manipulera bildens orientering, så att användare <br/>            kan utföra rotationer och vändningar enligt sina krav, vilket underlättar <br/>            effektiva bildbehandlingsuppgifter i mjukvaruapplikationer. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_100) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_101) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_102) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_103) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_104) | Sparade data. |
| [save(stream, options_base)](#save_stream_options_base_105) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_106) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_107) | Sparar de 32‑bitars ARGB‑pixlarna. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_108) | Sparar pixlarna. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_109) | Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden. |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_110) | Sparar pixlar (formatspecifik metod). |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_111) | Sparar rådata. |
| [save_to_stream(stream)](#save_to_stream_stream_112) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_113) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_115) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_116) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_117) | Ställer in en bildpixel i 32-bit ARGB för den angivna positionen. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_118) | Ställer in bildpaletten. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_119) | Ställer in en bildpixel för den angivna positionen. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_120) | Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_121) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122) | Skriver hela skanningsraden till det angivna skanningsradindexet. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_123) | Skriver hela skanningsraden till det angivna skanningsradindexet. |


### Constructor: TgaImage(path) {#TgaImage_path_1}


```
 TgaImage(path) 
```

Initierar ett nytt [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) objekt med den angivna filsökvägen för <br/> inläsning av bildinnehållet. Denna konstruktor initierar bildinstansen effektivt, vilket möjliggör sömlös åtkomst till TGA-bildfiler och förenklar integrationen <br/> i ditt applikationsflöde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sökväg | string | Sökvägen för att läsa in en bild. |

### Constructor: TgaImage(raster_image) {#TgaImage_raster_image_2}


```
 TgaImage(raster_image) 
```

Skapa en ny instans av [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) klassen genom att tillhandahålla ett raster <br/> bildobjekt. Denna konstruktor underlättar direktintegration av befintliga <br/> rasterbilder i TGA-bildformatet, vilket strömlinjeformar konverteringsprocessen för <br/> förbättrad kompatibilitet i dina mjukvarusystem.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |


**See also:**

**[Example # 1](#example_216)**: Loading of the PNG image, conversion of it to the TgaImage and saving as a TG...


### Constructor: TgaImage(stream) {#TgaImage_stream_3}


```
 TgaImage(stream) 
```

Initiera en ny instans av [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) klassen med en ström för <br/> att läsa in bilden. Denna konstruktor möjliggör sömlös integration av bilddata <br/> från strömmar, vilket underlättar effektiv hantering och bearbetning av TGA-bilder inom <br/> dina mjukvaruapplikationer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in en bild. |

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


### Method: clone() {#clone__19}


```
 clone() 
```

Skapar en duplikat av den aktuella instansen och genererar ett nytt objekt som klonar <br/>            alla attribut och egenskaper hos originalet. Denna metod underlättar <br/>            skapandet av identiska kopior, säkerställer dataintegritet och bevarar tillståndet för <br/>            den aktuella instansen utan att påverka originalobjektet.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | Returnerar ett nytt objekt som är en kopia av den aktuella instansen. |


### Method: clone(tga_image) {#clone_tga_image_20}


```
 clone(tga_image) 
```

Replikera egenskaperna hos ett annat [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/)‑objekt, och skapa en <br/>            ny instans med identiska attribut. Denna operation säkerställer bevarandet <br/>            av dataintegritet och underlättar duplicering av bildegenskaper utan <br/>            att förändra källobjektet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| tga_image | [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) | Annan [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |

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


### Method: create_from_image(raster_image)  [static] {#create_from_image_raster_image_30}


```
 create_from_image(raster_image) 
```

Initierar en ny instans av klassen [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| raster_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Rasterbilden. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


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

Initierar en ny instans av klassen [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen för att läsa in en bild. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [TgaImage](/imaging/python-net/aspose.imaging.fileformats.tga/tgaimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_34}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Beskär bilden genom att ange förskjutningar för vänster, höger, topp och botten <br/>            av gränserna. Denna metod låter dig trimma bilden genom att flytta dess gränser <br/>            oberoende längs de horisontella och vertikala axlarna. Genom att justera dessa förskjutningar <br/>            kan du exakt kontrollera vilka delar av bilden som ska behållas, och effektivt <br/>            beskära den till önskade dimensioner.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| left_shift | int | Vänsterskiftet. |
| right_shift | int | Högerskiftet. |
| top_shift | int | Översta skiftet. |
| bottom_shift | int | Nedersta skiftet. |

### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Beskär bilden till ett specificerat område. Denna metod låter dig definiera ett <br/>            rektangulärt område inom bilden som ska behållas, och kasta resten. Denna operation <br/>            är användbar för att fokusera på specifikt innehåll i bilden eller ta bort oönskade <br/>            delar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Utför dithering på den aktuella bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Dithermetoden. |
| bits_count | int | Det slutgiltiga bitantalet för dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


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

### Method: embed_digital_signature(password) {#embed_digital_signature_password_38}


```
 embed_digital_signature(password) 
```

Bädda in digital signatur baserad på angivet lösenord i bilden med hjälp av steganografi.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| password | string | Lösenordet som används för att generera digitala signaturdata. |

### Method: filter(rectangle, options) {#filter_rectangle_options_39}


```
 filter(rectangle, options) 
```

Filtrerar den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Alternativen. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_40}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_41}


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


### Method: get_default_options(args) {#get_default_options_args_42}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_43}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Hämtar standardpixelarrayen med partiell pixel‑laddare.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln för att hämta pixlar. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_45}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_46}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_47}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_48}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_49}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_50}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_51}


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


### Method: get_original_options() {#get_original_options__52}


```
 get_original_options() 
```

Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_pixel(x, y) {#get_pixel_x_y_53}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_54}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_55}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_56}


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


### Method: get_skew_angle() {#get_skew_angle__57}


```
 get_skew_angle() 
```

Hämtar snedvinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bestämma snedvinkeln vid skanning.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| float | Snedvinkeln, i grader. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_58}


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


### Method: load(file_path)  [static] {#load_file_path_59}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_60}


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


### Method: load(stream)  [static] {#load_stream_61}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_62}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_63}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_64}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_65}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_66}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_67}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Läser in 32-bitars ARGB‑pixlar delvis (i block).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att ladda pixlar från. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Den partiella pixel‑laddaren. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_68}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Läser in 64-bitars ARGB‑pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Den 64-bit ARGB-pixelinläsaren. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_69}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Läser in pixlar delvis i paket.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den önskade rektangeln. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Pixelinläsaren. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_70}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_71}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_72}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_73}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_74}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_75}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_76}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normaliserar vinkeln.<br/>            Denna metod är tillämplig på skannade textdokument för att bli av med snedvriden skanning.<br/>            Metoden använder [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) och [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/) metoder.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| resize_proportionally | bool | Om den är inställd på <c>true</c> kommer bildens storlek att ändras enligt den roterade rektangelns (hörnpunkternas) projektioner, annars lämnas dimensionerna oförändrade och endast bildens innehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_77}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_78}


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
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Gammal färg att ersätta. |
| old_color_diff | System.Byte | Tillåten skillnad i gammal färg för att kunna bredda den ersatta färgtonen. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Ny färg att ersätta den gamla färgen med. |

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

Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Ny färg att ersätta icke‑transparenta färger med. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_83}


```
 replace_non_transparent_colors(new_color_argb) 
```

Ersätter alla icke-transparenta färger med en ny färg och bevarar original‑alfavärdet för att spara mjuka kanter.<br/>            Obs: om du använder den på bilder utan transparens, kommer alla färger att ersättas med en enda.

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

Justera bildens storlek med en angiven omformningstyp, som bestämmer hur <br/>            omformningsoperationen utförs. Denna metod ger flexibilitet vid omformning <br/>            av bilder enligt olika algoritmer eller tekniker. Genom att välja rätt <br/>            omformningstyp kan du uppnå önskad balans mellan bildkvalitet och beräknings‑effektivitet baserat på specifika krav eller preferenser.

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

Ändra bildens storlek samtidigt som du tillämpar specifika inställningar för att behålla önskade <br/>            dimensioner och bildförhållande. Genom att anpassa bildinställningarna kan du effektivt <br/>            ändra bildens storlek samtidigt som du säkerställer optimal visuell kvalitet och kompatibilitet med <br/>            olika displayenheter eller applikationer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_89}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_90}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_91}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_92}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_93}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_94}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_95}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_96}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_97}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_98}


```
 rotate(angle, resize_proportionally, background_color) 
```

Roterar bilden kring dess centrum med en angiven vinkel samtidigt som omformnings‑ <br/>            proportioner bibehålls och bakgrundsfärgen bevaras. Denna metod möjliggör <br/>            exakt bildmanipulation och säkerställer att rotationen behåller visuell balans <br/>            och konsistens med den angivna bakgrundsfärgen. Den är idealisk för uppgifter där <br/>            exakt rotation kring centrum är nödvändig, såsom orienteringskorrigering <br/>            eller konstnärliga justeringar.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |
| resize_proportionally | bool | om den är satt till <c>true</c> kommer bildens storlek att ändras<br/>
            enligt den roterade rektangelns (hörnpunkternas) projektioner i annat<br/>
            fall lämnas dimensionerna orörda och endast<br/>
            __internal__ bildinnehåll roteras. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Bakgrundens färg. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_99}


```
 rotate_flip(rotate_flip_type) 
```

Metoden "RotateFlip" möjliggör roterings‑ och vändningsoperationer på bilden. Den <br/>            erbjuder mångsidig funktionalitet för att manipulera bildens orientering, så att användare <br/>            kan utföra rotationer och vändningar enligt sina krav, vilket underlättar <br/>            effektiva bildbehandlingsuppgifter i mjukvaruapplikationer.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Rotationsvändningstypen. |

### Method: save(file_path) {#save_file_path_100}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_101}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_102}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_103}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_104}


```
 save(stream) 
```

Sparade data.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

### Method: save(stream, options_base) {#save_stream_options_base_105}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_106}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_107}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Sparar de 32‑bitars ARGB‑pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | 32-bitars ARGB-pixelarrayen. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_108}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Sparar pixlarna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixlar | int[] | CMYK-pixlar presenterade som 32-bitars heltalsvärden. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_109}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Sparar pixlarna.<br/>            Denna metod är föråldrad. Använd den mer effektiva [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/) metoden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | CMYK-pixelarrayen. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_110}


```
 save_pixels(rectangle, pixels) 
```

Sparar pixlar (formatspecifik metod).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln att spara pixlar till. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | 32-bitars ARGB-pixelarrayen. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_111}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_112}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_113}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_114}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_115}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_116}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_117}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_118}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_119}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_120}


```
 set_resolution(dpi_x, dpi_y) 
```

Ställer in upplösningen för denna [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| dpi_x | float | Den horisontella upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | Den vertikala upplösningen, i punkter per tum, för [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_121}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_122}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Skriver hela skanningsraden till det angivna skanningsradindexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| scan_line_index | int | Nollbaserat index för skanningslinjen. |
| argb_32_pixels | int[] | Den 32-bitars ARGB-färgarrayen att skriva. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_123}


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

