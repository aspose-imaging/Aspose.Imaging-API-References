---
title: "MetaImage‑klass"
type: docs
weight: 3140
url: /sv/python-net/aspose.imaging.fileformats.emf/metaimage/
---

**Summary:** Base class for Meta object classes

**Module:** [aspose.imaging.fileformats.emf](/imaging/python-net/aspose.imaging.fileformats.emf/)

**Full Name:** aspose.imaging.fileformats.emf.MetaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, VectorImage

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
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Hämtar ett värde för filformatet |
| has_background_color | bool | r/w | Hämtar eller anger ett värde som indikerar om bilden har bakgrundsfärg. |
| height | int | r | Hämtar bildens höjd. |
| height_f | float | r | Hämtar objektets höjd i tum. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Hämtar eller anger avbrottsövervakaren. |
| is_cached | bool | r | Hämtar ett värde som indikerar om objektets data för närvarande är cachad och ingen dataläsning krävs. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Hämtar bildens metadata. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Hämtar eller anger färgpaletten. Färgpaletten används inte när pixlar representeras direkt. |
| records | [MetaObjectList](/imaging/python-net/aspose.imaging.fileformats.emf/metaobjectlist/) | r/w | Hämtar eller anger posterna. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Hämtar objektets storlek. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Hämtar objektets storlek i tum. |
| use_palette | bool | r | Hämtar ett värde som indikerar om bildpaletten används. |
| width | int | r | Hämtar bildens bredd. |
| width_f | float | r | Hämtar objektets bredd i tum. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Hämtar eller anger Xmp-data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Cachar data och säkerställer att ingen ytterligare dataladdning kommer att utföras från den underliggande [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Bestämmer om bilden kan läsas in från den angivna filsökvägen. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_load(stream)](#can_load_stream_3) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Bestämmer om bilden kan läsas in från den angivna strömmen. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Bestämmer om bilden kan läsas in från den angivna strömmen och eventuellt med de angivna _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Bestämmer om bilden kan läsas in från den angivna filsökvägen och eventuellt med de angivna öppningsalternativen. |
| [can_save(options)](#can_save_options_8) | Bestämmer om bilden kan sparas till det angivna filformatet som representeras av de medföljande sparalternativen. |
| [create(files)](#create_files_9) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Skapar flersidig bild som innehåller de angivna filerna. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Skapar en ny bild med de angivna skapandealternativen. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Skapar en [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/)‑instans från den angivna pixelarrayen.<br/>            <br/>            Validerar att den angivna bredden och höjden matchar dimensionerna på pixeldata.<br/>            Denna metod kan endast användas när biblioteket är i licensierat läge. |
| [create(images)](#create_images_13) | Skapar en ny bild med de angivna bilderna som sidor |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Skapar en ny bild från de angivna bilderna som sidor. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Skapar de angivna flersidiga skapalternativen. |
| [create_from_files(files)](#create_from_files_files_16) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Skapar den flersidiga bilden som innehåller de angivna filerna som sidor med fördröjd inläsning. |
| [create_from_images(images)](#create_from_images_images_18) | Skapar en ny bild med de angivna bilderna som sidor |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Skapar en ny bild från de angivna bilderna som sidor. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Beskär bild med förskjutningar. |
| [crop(rectangle)](#crop_rectangle_21) | Beskär den angivna rektangeln. |
| [get_default_options(args)](#get_default_options_args_22) | Hämtar standardalternativen för bild. |
| [get_embedded_images()](#get_embedded_images__23) | Hämtar de inbäddade bilderna. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Hämtar filformatet. |
| [get_file_format(stream)](#get_file_format_stream_25) | Hämtar filformatet. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Hämtar filformatet. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Hämtar rektangeln som passar den aktuella bilden. |
| [get_missed_fonts()](#get_missed_fonts__29) | Returnerar listan över teckensnitt som används i metafilen men inte hittas. |
| [get_original_options()](#get_original_options__30) | Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_31) | Hämtar en proportionell höjd. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_32) | Hämtar en proportionell bredd. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_33) | Konverterar till aps. |
| [get_used_fonts()](#get_used_fonts__34) | Returnerar listan över teckensnitt som används i metafilen. |
| [load(file_path)](#load_file_path_35) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| [load(stream)](#load_stream_37) | Läser in en ny bild från den angivna strömmen. |
| [load(stream, load_options)](#load_stream_load_options_38) | Läser in en ny bild från den angivna strömmen. |
| [load_stream(stream)](#load_stream_stream_39) | Läser in en ny bild från den angivna strömmen. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_40) | Läser in en ny bild från den angivna strömmen. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_41) | Läser in en ny bild från den angivna filsökvägen eller URL:en.<br/>            Om _filePath_ är en filsökväg öppnar metoden bara filen.<br/>            Om _filePath_ är en URL laddar metoden ner filen, sparar den som en temporär och öppnar den. |
| remove_background() | Tar bort bakgrunden. |
| [remove_background(settings)](#remove_background_settings_42) | Tar bort bakgrunden. |
| remove_metadata() | Tar bort metadata. |
| [resize(new_width, new_height)](#resize_new_width_new_height_43) | Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_44) | Ändrar storleken på den angivna nya bredden. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_45) | Ändrar bildens storlek med utökade alternativ. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_46) | Ändrar storlek på bilden. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_47) | Ändrar storlek på bilden. |
| [resize_canvas(new_rectangle)](#resize_canvas_new_rectangle_48) | Ändrar storlek på duken. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_49) | Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_50) | Ändrar höjden proportionellt. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_51) | Ändrar höjden proportionellt. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_52) | Ändrar höjden proportionellt. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_53) | Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_54) | Ändrar bredden proportionellt. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_55) | Ändrar bredden proportionellt. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_56) | Ändrar bredden proportionellt. |
| [rotate(angle)](#rotate_angle_57) | Rotera bilden kring centrum. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | Rotera, vänd eller rotera och vänd bilden. |
| save() | Sparar bilddata till den underliggande strömmen. |
| [save(file_path)](#save_file_path_59) | Sparar bilden till den angivna filsökvägen. |
| [save(file_path, options)](#save_file_path_options_60) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save(file_path, over_write)](#save_file_path_over_write_62) | Sparar objektets data till den angivna filsökvägen. |
| [save(stream)](#save_stream_63) | Sparar data till angiven _stream_. |
| [save(stream, options_base)](#save_stream_options_base_64) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream(stream)](#save_to_stream_stream_66) | Sparar objektets data till den angivna strömmen. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_67) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_68) | Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_69) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_70) | Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_71) | Ställer in bildpaletten. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_72) | Försöker sätta en _metadata_-instans, om detta [Image](/imaging/python-net/aspose.imaging/image/)-instans stödjer och implementerar [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/)-instansen. |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Beskär den angivna rektangeln.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Rektangeln. |

### Method: get_default_options(args) {#get_default_options_args_22}


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


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Hämtar de inbäddade bilderna.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Array av bilder |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_missed_fonts() {#get_missed_fonts__29}


```
 get_missed_fonts() 
```

Returnerar listan över teckensnitt som används i metafilen men inte hittas.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | Teckensnittlistan |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Hämtar alternativen baserat på de ursprungliga filinställningarna.<br/>            Detta kan vara användbart för att behålla bitdjup och andra parametrar i den ursprungliga bilden oförändrade.<br/>            Till exempel, om vi laddar en svart‑vit PNG‑bild med 1 bit per pixel och sedan sparar den med hjälp av<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) metoden, kommer en PNG‑bild med 8‑bit per pixel att genereras.<br/>            För att undvika detta och spara PNG‑bilden med 1‑bit per pixel, använd denna metod för att hämta motsvarande sparalternativ och skicka dem<br/>            till [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) metoden som den andra parametern.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen baserade på de ursprungliga filinställningarna. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_31}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_32}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_33}


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


### Method: get_used_fonts() {#get_used_fonts__34}


```
 get_used_fonts() 
```

Returnerar listan över teckensnitt som används i metafilen.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string[] | Teckensnittlistan |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_39}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_40}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_41}


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


### Method: remove_background(settings) {#remove_background_settings_42}


```
 remove_background(settings) 
```

Tar bort bakgrunden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Inställningarna. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_43}


```
 resize(new_width, new_height) 
```

Ändrar bildens storlek. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| new_height | int | Den nya höjden. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_44}


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

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_45}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_46}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_47}


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

### Method: resize_canvas(new_rectangle) {#resize_canvas_new_rectangle_48}


```
 resize_canvas(new_rectangle) 
```

Ändrar storlek på duken.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Den nya rektangeln. |


**See also:**

**[Example # 1](#example_181)**: The following example shows how to add a border with the specified margins ar...


### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_49}


```
 resize_height_proportionally(new_height) 
```

Ändrar höjden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_50}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_51}


```
 resize_height_proportionally(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_52}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Ändrar höjden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_height | int | Den nya höjden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_53}


```
 resize_width_proportionally(new_width) 
```

Ändrar bredden proportionellt. Standardvärdet [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) används.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_54}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Typ av storleksändring. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_55}


```
 resize_width_proportionally(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_56}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Ändrar bredden proportionellt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_width | int | Den nya bredden. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Inställningarna för bildstorleksändring. |

### Method: rotate(angle) {#rotate_angle_57}


```
 rotate(angle) 
```

Rotera bilden kring centrum.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| vinkel | float | Rotationsvinkeln i grader. Positiva värden roterar medurs. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

Rotera, vänd eller rotera och vänd bilden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Typ av rotate flip. |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

Sparar bilden till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara bilden till. |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

Sparar objektets data till den angivna filsökvägen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filvägen för att spara objektets data till. |
| over_write | bool | om den är satt till <c>true</c> skriv över filinnehållet, annars kommer data att läggas till. |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

Sparar data till angiven _stream_.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen. |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_66}


```
 save_to_stream(stream) 
```

Sparar objektets data till den angivna strömmen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara objektets data till. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_67}


```
 save_to_stream_with_options(stream, options_base) 
```

Sparar bildens data till den angivna strömmen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom | Strömmen att spara bildens data till. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Sparalternativen. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_68}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_69}


```
 save_with_options(file_path, options) 
```

Sparar objektets data till den angivna filsökvägen i det specificerade filformatet enligt sparalternativ.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| file_path | string | Filsökvägen. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Alternativen. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_70}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_71}


```
 set_palette(palette, update_colors) 
```

Ställer in bildpaletten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | Paletten att ställa in. |
| update_colors | bool | Om den är inställd på <c>true</c> kommer färgerna att uppdateras enligt den nya paletten; annars förblir färgindex oförändrade. Observera att oförändrade index kan krascha bilden vid inläsning om vissa index saknar motsvarande palettposter. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_72}


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
### The following example shows how to add a border with the specified margins around a metafile (WMF and EMF). {#example_181}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.fileformats.emf import MetaImage

border_left: int = 50
border_top: int = 50
border_right: int = 50
border_bottom: int = 50
dir_: str = "c:\\aspose.imaging\\issues\\net\\3280\\"
file_names = ["image1.emf", "image2.wmf"]
for file_name in file_names:
	input_file_path: str = dir_ + file_name
	output_file_path: str = dir_ + "AddBorder_" + file_name
	with aspycore.as_of(Image.load(input_file_path), MetaImage) as image:
		image.resize_canvas(Rectangle(-border_left, -border_top, image.width + border_left + border_right, image.height + border_top + border_bottom))
		image.save(output_file_path)


```

