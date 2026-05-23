---
title: "WmfImage‑klass"
type: docs
weight: 350
url: /sv/python-net/aspose.imaging.fileformats.wmf/wmfimage/
---

**Summary:** Manipulate Microsoft Windows Metafile (WMF) images with our API, seamlessly<br/>            handling both vector and bitmap data stored within variable-length records.<br/>            Resize, rotate, and flip images with ease while setting custom image palettes.<br/>            Convert WMF files to compressed WMZ formats or save them in raster image formats<br/>            for versatile usage across platforms and applications.

**Module:** [aspose.imaging.fileformats.wmf](/imaging/python-net/aspose.imaging.fileformats.wmf/)

**Full Name:** aspose.imaging.fileformats.wmf.WmfImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, MetaImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WmfImage()](#WmfImage__1) | Skapa en ny instans av klassen [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/), initierad för <br/>            vidare manipulation och bearbetning av Windows Metafile (WMF)-bilddata. Denna <br/>            konstruktor tillhandahåller ett grundläggande objekt för att arbeta med WMF‑bilder, vilket möjliggör <br/>            sömlös integration av WMF‑bildhanteringsfunktioner i din applikations <br/>            funktionalitet. |
| [WmfImage(width, height)](#WmfImage_width_height_2) | Instansiera en ny instans av klassen [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) med anpassningsbara <br/>            bredd- och höjdpunkter, vilket underlättar skapandet av tomma WMF‑bilder <br/>            anpassade till specifika dimensioner. Använd denna konstruktor för att dynamiskt generera <br/>            WMF‑bilder med exakta dimensioner, vilket möjliggör flexibel bildskapande och <br/>            manipulation i din applikation. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Hämtar eller anger ett värde som indikerar om automatisk justering av palett. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Hämtar eller anger ett värde för bakgrundsfärgen. |
| bits_per_pixel | int | r | Hämta antalet bitar per pixel för bilden, vilket indikerar färgdjupets nivå <br/>            eller granularitet. Använd denna egenskap för att bestämma bildens färg <br/>            representation och precision, vilket underlättar kompatibilitetskontroller och färgrelaterad <br/>            bearbetning i din applikation. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Hämtar objektets gränser. |
| buffer_size_hint | int | r/w | Hämtar eller anger en ledtråd för buffertstorlek som definierar maximal tillåten storlek för alla interna buffertar. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Hämtar [Image](/imaging/python-net/aspose.imaging/image/) behållaren. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Hämtar objektets datastream. |
| disposed | bool | r | Hämtar ett värde som indikerar om den här instansen är frigjord. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Hämtar eller anger Exif-instans. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Åtkomst till filformatvärdet som är associerat med bilden, vilket ger information <br/> om det format i vilket bilden lagras. Använd denna egenskap för att bestämma <br/> bildens filformat, vilket underlättar kompatibilitetskontroller och <br/> format‑specifik bearbetning i din applikation. |
| frame_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Åtkomst till ramens gränser, vilket indikerar dess position och dimensioner inom <br/>            bilden. Använd denna egenskap för att hämta detaljerad information om ramens <br/>            rumsliga placering, vilket möjliggör exakt manipulation och rendering i din applikation. |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| height | int | r | Hämtar objektets höjd. |
| height_f | float | r | Åtkomst till bildens höjd, som representerar antalet pixlar längs dess vertikala <br/>            axel. Använd denna egenskap för att fastställa bildens rumsliga dimensioner och bildförhållande, <br/>            vilket möjliggör korrekta layout- och renderingsjusteringar i din applikation. |
| tum | int | r/w | Åtkomst till eller ändring av tum‑egenskapen, som representerar en måttenhet som vanligtvis <br/>            används för att ange fysiska dimensioner i utskrifts‑ eller visningssammanhang. Använd denna <br/>            egenskap för att fastställa eller hämta tumvärden som är associerade med bilden, <br/>            vilket underlättar korrekt återgivning av fysiska dimensioner i din applikation. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämta ett booleskt värde som indikerar om objektets data för närvarande är cachad, <br/>            vilket eliminerar behovet av ytterligare data‑läsningsoperationer. Använd denna egenskap <br/>            för att optimera prestanda genom att avgöra om objektets data är omedelbart tillgängligt <br/>            utan behov av kostsamma data‑hämtningar i din applikation. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar bildens metadata. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| records | [MetaObjectList](/imaging/python-net/aspose.imaging.fileformats.emf/metaobjectlist/) | r/w | Hämtar eller anger posterna. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Hämtar objektets storlek i tum. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| width | int | r | Hämtar objektets bredd. |
| width_f | float | r | Åtkomst till bildens bredd, som indikerar antalet pixlar längs dess <br/>            horisontella axel. Använd denna egenskap för att fastställa bildens rumsliga dimensioner <br/>            och bildförhållande, vilket möjliggör exakt layout‑ och renderingsjusteringar i din <br/>            applikation. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_record(record)](#add_record_record_1) | Inkludera det specificerade postobjektet i bilden, vilket berikar dess innehåll med <br/>            ytterligare data eller metadata. Använd denna metod för att sömlöst integrera post- <br/>            objekt i bilden, vilket underlättar omfattande datalagring och organisering <br/>            i din applikation. |
| cache_data() | Cacha data effektivt, vilket eliminerar behovet av ytterligare inläsning från den <br/>            underliggande [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). Använd denna <br/>            metod för att optimera prestanda och minimera resursanvändning i din applikation <br/>            genom att lagra och komma åt lokalt datacache. |
| [can_load(file_path)](#can_load_file_path_2) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_3) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_4) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_5) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_6) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_7) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_8) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_save(options)](#can_save_options_9) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(files)](#create_files_10) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_11) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_12) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_13) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_14) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_15) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_16) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_files(files)](#create_from_files_files_17) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_18) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_images(images)](#create_from_images_images_19) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_20) | Skapar en ny bild från de angivna bilderna som sidor. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_21) | Beskär bild med förskjutningar. |
| [crop(rectangle)](#crop_rectangle_22) | Beskär den angivna rektangeln. |
| [get_default_options(args)](#get_default_options_args_23) | Hämtar standardalternativen för bild. |
| [get_embedded_images()](#get_embedded_images__24) | Hämtar de inbäddade bilderna. |
| [get_file_format(file_path)](#get_file_format_file_path_25) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_26) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_27) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_28) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_29) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_missed_fonts()](#get_missed_fonts__30) | Returnerar listan över teckensnitt som används i metafilen men inte hittas. |
| [get_original_options()](#get_original_options__31) | Hämtar de ursprungliga bildalternativen. |
| [get_post_script()](#get_post_script__32) | Åtkomst till PostScript-data som är associerad med bilden, vilket ger detaljerad <br/>            information om dess struktur eller innehåll. Använd denna metod för att hämta <br/>            PostScript-data för vidare analys eller bearbetning i din applikation, <br/>            vilket möjliggör avancerad funktionalitet relaterad till PostScript-rendering eller manipulation. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_33) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_34) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_35) | Konverterar till aps. |
| [get_used_fonts()](#get_used_fonts__36) | Hämta listan över teckensnitt som används i metafilen, vilket ger insikt i <br/>            teckensnittresurserna som används i bilden. Använd denna metod för att analysera teckensnittsanvändning <br/>            och säkerställa teckensnittstillgänglighet för rendering eller vidare bearbetning i din applikation. |
| [load(file_path)](#load_file_path_37) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_38) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_39) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_40) | Läser in en ny bild från den angivna strömmen. |
| [load_stream(stream)](#load_stream_stream_41) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_42) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_43) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| remove_background() | Tar bort bakgrunden. |
| [remove_background(settings)](#remove_background_settings_44) | Tar bort bakgrunden. |
| remove_metadata() | Tar bort metadata. |
| [resize(new_width, new_height)](#resize_new_width_new_height_45) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_46) | Ändrar storleken på den angivna nya bredden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_47) | Ändrar bildens storlek med utökade alternativ. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_48) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_49) | Ändrar storlek på bilden. |
| [resize_canvas(new_rectangle)](#resize_canvas_new_rectangle_50) | Ändra storlek på bildens canvas, justera dess dimensioner samtidigt som bildens <br/>            innehåll behålls. Använd denna metod för att ändra canvasens storlek utan att förändra <br/>            innehållet, vilket underlättar layoutjusteringar och kompositionsändringar i din <br/>            applikation. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_51) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_52) | Ändrar höjden proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_53) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_54) | Ändrar höjden proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_55) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_56) | Ändrar bredden proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_57) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_58) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_59) | Rotera bilden kring centrum. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_60) | Rotera, vänd eller rotera och vänd bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_61) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_62) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_63) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_64) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_65) | Sparar data till angiven _stream_. |
| [save(stream, options_base)](#save_stream_options_base_66) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_67) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream(stream)](#save_to_stream_stream_68) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_69) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_70) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_71) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_72) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_73) | Applicera en angiven palett på bilden, vilket möjliggör anpassning av färg <br/>            representation. Använd denna metod för att förbättra visuell rendering och uppnå <br/>            specifika färgeffekter i din applikation. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_74) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Constructor: WmfImage() {#WmfImage__1}


```
 WmfImage() 
```

Skapa en ny instans av klassen [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/), initierad för <br/>            vidare manipulation och bearbetning av Windows Metafile (WMF)-bilddata. Denna <br/>            konstruktor tillhandahåller ett grundläggande objekt för att arbeta med WMF‑bilder, vilket möjliggör <br/>            sömlös integration av WMF‑bildhanteringsfunktioner i din applikations <br/>            funktionalitet.

### Constructor: WmfImage(width, height) {#WmfImage_width_height_2}


```
 WmfImage(width, height) 
```

Instansiera en ny instans av klassen [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) med anpassningsbara <br/>            bredd- och höjdpunkter, vilket underlättar skapandet av tomma WMF‑bilder <br/>            anpassade till specifika dimensioner. Använd denna konstruktor för att dynamiskt generera <br/>            WMF‑bilder med exakta dimensioner, vilket möjliggör flexibel bildskapande och <br/>            manipulation i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| width | int | Bredden. |
| height | int | Höjden. |

### Method: add_record(record) {#add_record_record_1}


```
 add_record(record) 
```

Inkludera det specificerade postobjektet i bilden, vilket berikar dess innehåll med <br/>            ytterligare data eller metadata. Använd denna metod för att sömlöst integrera post- <br/>            objekt i bilden, vilket underlättar omfattande datalagring och organisering <br/>            i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| record | [WmfObject](/imaging/python-net/aspose.imaging.fileformats.wmf.objects/wmfobject/) | Posten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Antal poster. |


### Method: can_load(file_path)  [static] {#can_load_file_path_2}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_3}


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


### Method: can_load(stream)  [static] {#can_load_stream_4}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_5}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_6}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_7}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_8}


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


### Method: can_save(options) {#can_save_options_9}


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


### Method: create(files)  [static] {#create_files_10}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_11}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_12}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_13}


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


### Method: create(images)  [static] {#create_images_14}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_15}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_16}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_17}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_18}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_19}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_20}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_21}


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

### Method: crop(rectangle) {#crop_rectangle_22}


```
 crop(rectangle) 
```

Beskär den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: get_default_options(args) {#get_default_options_args_23}


```
 get_default_options(args) 
```

Hämtar standardalternativen för bild.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| args | System.Object | Argumenten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Standardalternativen för bild. |


### Method: get_embedded_images() {#get_embedded_images__24}


```
 get_embedded_images() 
```

Hämtar de inbäddade bilderna.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Array av bilder |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_25}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_26}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_27}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_28}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_29}


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


### Method: get_missed_fonts() {#get_missed_fonts__30}


```
 get_missed_fonts() 
```

Returnerar listan över teckensnitt som används i metafilen men inte hittas.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | Teckensnittlistan |


### Method: get_original_options() {#get_original_options__31}


```
 get_original_options() 
```

Hämtar de ursprungliga bildalternativen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | De ursprungliga bildalternativen. |


### Method: get_post_script() {#get_post_script__32}


```
 get_post_script() 
```

Åtkomst till PostScript-data som är associerad med bilden, vilket ger detaljerad <br/>            information om dess struktur eller innehåll. Använd denna metod för att hämta <br/>            PostScript-data för vidare analys eller bearbetning i din applikation, <br/>            vilket möjliggör avancerad funktionalitet relaterad till PostScript-rendering eller manipulation.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Postscriptet |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_33}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_34}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_35}


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


### Method: get_used_fonts() {#get_used_fonts__36}


```
 get_used_fonts() 
```

Hämta listan över teckensnitt som används i metafilen, vilket ger insikt i <br/>            teckensnittresurserna som används i bilden. Använd denna metod för att analysera teckensnittsanvändning <br/>            och säkerställa teckensnittstillgänglighet för rendering eller vidare bearbetning i din applikation.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | Teckensnittlistan |


### Method: load(file_path)  [static] {#load_file_path_37}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_38}


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


### Method: load(stream)  [static] {#load_stream_39}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_40}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_41}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_42}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_43}


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


### Method: remove_background(settings) {#remove_background_settings_44}


```
 remove_background(settings) 
```

Tar bort bakgrunden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Inställningarna. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_45}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_46}


```
 resize(new_width, new_height, resize_type) 
```

Ändrar storleken på den angivna nya bredden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_47}


```
 resize(new_width, new_height, settings) 
```

Ändrar bildens storlek med utökade alternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Resize-inställningarna. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_48}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_49}


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

### Method: resize_canvas(new_rectangle) {#resize_canvas_new_rectangle_50}


```
 resize_canvas(new_rectangle) 
```

Ändra storlek på bildens canvas, justera dess dimensioner samtidigt som bildens <br/>            innehåll behålls. Använd denna metod för att ändra canvasens storlek utan att förändra <br/>            innehållet, vilket underlättar layoutjusteringar och kompositionsändringar i din <br/>            applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den nya rektangeln. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_51}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_52}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_53}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_54}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_55}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_56}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_57}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_58}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_59}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_60}


```
 rotate_flip(rotate_flip_type) 
```

Rotera, vänd eller rotera och vänd bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Typ av rotate flip. |

### Method: save(file_path) {#save_file_path_61}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_62}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_63}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_64}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_65}


```
 save(stream) 
```

Sparar data till angiven _stream_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

### Method: save(stream, options_base) {#save_stream_options_base_66}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_67}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_68}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_69}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_70}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_71}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_72}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_73}


```
 set_palette(palette, update_colors) 
```

Applicera en angiven palett på bilden, vilket möjliggör anpassning av färg <br/>            representation. Använd denna metod för att förbättra visuell rendering och uppnå <br/>            specifika färgeffekter i din applikation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | om den är satt till <c>true</c> uppdateras färgerna enligt den nya paletten; annars <br/>                färgindexen förblir oförändrade. Observera att oförändrade index kan orsaka att bilden kraschar vid inläsning om vissa index saknar <br/>                motsvarande palettposter. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_74}


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


## **Examples**
### This example shows how to load a WMF image from a file and convert it to SVG using WmfRasterizationOptions. {#example_173}
``` python

from aspose.pycore import as_of, cast
from aspose.imaging import Image, Color, SizeF
from aspose.imaging.fileformats.wmf import WmfImage, WmfRenderMode
from aspose.imaging.imageoptions import SvgOptions, WmfRasterizationOptions

# Att använda Aspose.Imaging.Image.Load är ett enhetligt sätt att läsa in alla bildtyper inklusive WMF.
with as_of(Image.load("test.wmf") as image:
	saveOptions = SvgOptions()
	# Text kommer att konverteras till former.
	saveOptions.text_as_shapes = True
	rasterizationOptions = WmfRasterizationOptions()
	# Bakgrundsfärgen på ritytan.
	rasterizationOptions.background_color = Color.white_smoke
	# Sidstorleken.
	rasterizationOptions.page_size = cast(SizeF, wmfImage.size)
	# Om inbäddad emf finns, rendera emf; annars rendera wmf.
	rasterizationOptions.render_mode = WmfRenderMode.AUTO
	saveOptions.vector_rasterization_options = rasterizationOptions
	wmfImage.save("test.output.svg", saveOptions)


```

### The following example shows how to convert compressed images (*.emz,*.wmz, *.svgz) to a raster format {#example_190}
``` python
from aspose.imaging import Image, Color
from aspose.imaging.imageoptions import PngOptions, VectorRasterizationOptions
from os.path import join
from aspose.pycore import as_of

files = ["example.emz", "example.wmz", "example.svgz"]
base_folder: str = join("D:", "Compressed")
for file in files:
	input_file: str = join(base_folder, file)
	out_file: str = input_file + ".png"
	with Image.load(input_file) as image:
		vector_rasterization_options = aspycore.as_of(image.get_default_options([Color.white, image.width, image.height]), VectorRasterizationOptions)
		obj_init = PngOptions()
		obj_init.vector_rasterization_options = vector_rasterization_options
		image.save(out_file, obj_init)


```

### The following example shows how to convert a wmz images to wmf fromat {#example_192}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions
from os.path import join

file: str = "example.wmz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".wmf"
with Image.load(input_file) as image:
	obj_init = WmfRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a wmf images to wmz format {#example_195}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import WmfRasterizationOptions, WmfOptions

file = "castle.wmf"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".wmz"
with Image.load(input_file) as image:
	vector_rasterization_options = WmfRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = WmfOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

