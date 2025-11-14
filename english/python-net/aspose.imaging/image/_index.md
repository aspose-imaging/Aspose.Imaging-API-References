---
title: Image Class
type: docs
weight: 5610
url: /python-net/aspose.imaging/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DataStreamSupporter

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Gets the image bits per pixel count. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Gets the image bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Gets or sets the Exif data. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Gets a value of file format |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| height | int | r | Gets the image height. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Gets a value indicating whether object's data is cached currently and no data reading is required. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Gets the image metadata. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Gets the image size. |
| [use_palette](#use_palette1) | bool | r | Gets a value indicating whether the image palette is used. |
| width | int | r | Gets the image width. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets the Xmp data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Caches the data and ensures no additional data loading will be performed from the underlying [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). |
| [can_load(file_path)](#can_load_file_path_1) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_3) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_8) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [create(files)](#create_files_9) | Creates the multipage image containing the specified files. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Creates the multipage image containing the specified files. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Creates a new image using the specified create options. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Creates a [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) instance from the provided pixel array.<br/>            <br/>            Validates that the specified width and height match the dimensions of the pixel data.<br/>            This method can only be used when the library is in Licensed mode. |
| [create(images)](#create_images_13) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Creates the specified multipage create options. |
| [create_from_files(files)](#create_from_files_files_16) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_18) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Creates a new image the specified images as pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_21) | Crops the specified rectangle. |
| [get_default_options(args)](#get_default_options_args_22) | Gets the default options. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_24) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_25) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_26) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_27) | Gets rectangle which fits the current image. |
| [get_original_options()](#get_original_options__28) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <DOM Element: class at 0x20a547ca310>.DataStreamSupporter.save()(string) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <DOM Element: class at 0x20a54950280>.Image.save()(string,Aspose.Imaging.ImageOptionsBase) method as the second parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_29) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_30) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_31) | Converts to aps. |
| [load(file_path)](#load_file_path_32) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_33) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_34) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_35) | Loads a new image from the specified stream. |
| [load_stream(stream)](#load_stream_stream_36) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_37) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_38) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| remove_metadata() | Removes metadata. |
| [resize(new_width, new_height)](#resize_new_width_new_height_39) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_40) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_41) | Resizes the image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_42) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_43) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_44) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_45) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_46) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_47) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_48) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_49) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_50) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_51) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_52) | Rotate image around the center. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_53) | Rotates, flips, or rotates and flips the image. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_54) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_55) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_56) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_57) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_58) | Saves the object's data to the specified stream. |
| [save(stream, options_base)](#save_stream_options_base_59) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_60) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream(stream)](#save_to_stream_stream_61) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_62) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_64) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_65) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_66) | Sets the image palette. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_67) | Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) type. |


### Property: use_palette {#use_palette1}

Gets a value indicating whether the image palette is used.

**See also:**

**[Example # 1](#example_197)**: Determine if the palette is used by the image.


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


```
 can_load(file_path) 
```

Determines whether image can be loaded from the specified file path.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |



**See also:**

**[Example # 1](#example_22)**: This example determines whether image can be loaded from a file.


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_3}


```
 can_load(stream) 
```

Determines whether image can be loaded from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |



**See also:**

**[Example # 1](#example_23)**: This example determines whether image can be loaded from a file stream.


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


```
 can_load_stream(stream) 
```

Determines whether image can be loaded from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


```
 can_load_stream_with_options(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified stream; otherwise, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


```
 can_load_with_options(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be loaded from the specified file; otherwise, <c>false</c>. |


### Method: can_save(options) {#can_save_options_8}


```
 can_save(options) 
```

Determines whether image can be saved to the specified file format represented by the passed save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options to use. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be saved to the specified file format represented by the passed save options; otherwise, <c>false</c>. |



**See also:**

**[Example # 1](#example_26)**: This example shows how to determine whether image can be saved to the specifi...


### Method: create(files)  [static] {#create_files_9}


```
 create(files) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


```
 create(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> [throw exception on load error]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


```
 create(image_options, width, height) 
```

Creates a new image using the specified create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The newly created image. |



**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


```
 create(image_options, width, height, pixels) 
```

Creates a [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) instance from the provided pixel array.<br/>            <br/>            Validates that the specified width and height match the dimensions of the pixel data.<br/>            This method can only be used when the library is in Licensed mode.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options used to create the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | The width of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | The height of the [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| pixels | int[] | The array of pixel values used to populate the image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | A [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) populated with the provided pixel data. |


### Method: create(images)  [static] {#create_images_13}


```
 create(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


```
 create(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


```
 create(multipage_create_options) 
```

Creates the specified multipage create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | The multipage create options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


```
 create_from_files(files) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string[] | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> throw exception on load error. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The multipage image |


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


```
 create_from_images(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


```
 create_from_images(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The Image as IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Crop image with shifts.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| left_shift | int | The left shift. |
| right_shift | int | The right shift. |
| top_shift | int | The top shift. |
| bottom_shift | int | The bottom shift. |

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Crops the specified rectangle.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle. |

### Method: get_default_options(args) {#get_default_options_args_22}


```
 get_default_options(args) 
```

Gets the default options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | System.Object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Default options |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


```
 get_file_format(file_path) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |



**See also:**

**[Example # 1](#example_24)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


```
 get_file_format(stream) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |



**See also:**

**[Example # 1](#example_25)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_25}


```
 get_file_format_of_stream(stream) 
```

Gets the file format.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | The determined file format. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_26}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get fitting rectangle for. |
| pixels | int[] | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_27}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            <DOM Element: class at 0x20a547ca310>.DataStreamSupporter.save()(string) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the <DOM Element: class at 0x20a54950280>.Image.save()(string,Aspose.Imaging.ImageOptionsBase) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options based on the original file settings. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_29}


```
 get_proportional_height(width, height, new_width) 
```

Gets a proportional height.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_width | int | The new width. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional height. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_30}


```
 get_proportional_width(width, height, new_height) 
```

Gets a proportional width.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |
| new_height | int | The new height. |

**Returns**

| Type | Description |
| :- | :- |
| int | The proportional width. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_31}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Converts to aps.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The image options. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The clipping rectangle. |
| page_number | int[] | The page number. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The serialized stream |


### Method: load(file_path)  [static] {#load_file_path_32}


```
 load(file_path) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |



**See also:**

**[Example # 1](#example_1)**: This example demonstrates the loading of an existing Image file into an insta...


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_33}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_34}


```
 load(stream) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |



**See also:**

**[Example # 1](#example_6)**: This example demonstrates the use of a file stream objects to load an existin...


### Method: load(stream, load_options)  [static] {#load_stream_load_options_35}


```
 load(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_stream(stream)  [static] {#load_stream_stream_36}


```
 load_stream(stream) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_37}


```
 load_stream_with_options(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_38}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | The loaded image. |


### Method: resize(new_width, new_height) {#resize_new_width_new_height_39}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |


**See also:**

**[Example # 1](#example_167)**: The following example shows how to resize a metafile (WMF and EMF).


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_40}


```
 resize(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |


**See also:**

**[Example # 1](#example_187)**: Resize image using specific Resize Type.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_41}


```
 resize(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |


**See also:**

**[Example # 1](#example_28)**: This example loads an image and resizes it using various resizing settings.

**[Example # 2](#example_187)**: Resize image using specific Resize Type.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_42}


```
 resize_by_settings(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The resize settings. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_43}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | The resize type. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_44}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_45}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |


**See also:**

**[Example # 1](#example_30)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_46}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_47}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_48}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_49}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type of the resize. |


**See also:**

**[Example # 1](#example_29)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_50}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_51}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_52}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_53}


```
 rotate_flip(rotate_flip_type) 
```

Rotates, flips, or rotates and flips the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Type of the rotate flip. |


**See also:**

**[Example # 1](#example_8)**: This example demonstrates the use of Rotate operation on an image. Example lo...

**[Example # 2](#example_31)**: This example loads an image, rotates it by 90 degrees clockwise and optionall...


### Method: save(file_path) {#save_file_path_54}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_55}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |


**See also:**

**[Example # 1](#example_9)**: This example shows the simple steps to save an Image. To demonstrate this ope...

**[Example # 2](#example_32)**: The following example loads a BMP image from a file, then saves the image to ...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_56}


```
 save(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |


**See also:**

**[Example # 1](#example_33)**: The following example loads a BMP image from a file, then saves a rectangular...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, over_write) {#save_file_path_over_write_57}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_58}


```
 save(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save(stream, options_base) {#save_stream_options_base_59}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |


**See also:**

**[Example # 1](#example_10)**: This example shows the process of saving an Image to MemoryStream. To demonst...

**[Example # 2](#example_34)**: The following example loads an image from a file, then saves the image to a P...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_60}


```
 save(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |


**See also:**

**[Example # 1](#example_35)**: The following example loads an image from a file, then saves a rectangular pa...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save_to_stream(stream) {#save_to_stream_stream_61}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_62}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_64}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_65}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_66}


```
 set_palette(palette, update_colors) 
```

Sets the image palette.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_67}


```
 try_set_metadata(metadata) 
```

Tries to set a _metadata_ instance, if this [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) type.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | The metadata. |

**Returns**

| Type | Description |
| :- | :- |
| bool | True, if the [Image](/imaging/python-net/aspose.imaging/image/) instance supports and implements [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) type; otherwise, false. |


## **Examples**
### This example demonstrates the loading of an existing Image file into an instance of aspose.imaging.Image using file path specified {#example_1}
``` python

from aspose.imaging import Image
# Create Image instance and initialize it with an existing image file from disk location
with Image.load(r"C:\temp\sample.bmp") as image:
	# do some image processing
	pass


```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Create an instance of `BmpOptions` and set its various properties
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Create an instance of `FileCreateSource` and assign it as `source` for the instance of `BmpOptions`
	#Second `Boolean` parameter determines if the file to be created is_temporal or not
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Create an instance of Image and initialize it with instance of BmpOptions by calling Create method
	with Image.create(bmp_options, 500, 500) as image:
		#do some image processing
		# save all changes
		image.save()


```

### This example demonstrates the use of a file stream objects to load an existing Image file {#example_6}
``` python

from aspose.imaging import Image

# Create an instance of FileStream
with open(r"C:\temp\sample.bmp", "rb"):
	#Create an instance of Image class and load an existing file through FileStream object by calling Load method
	with Image.load(stream) as image:
		#do some image processing.
		pass

```

### This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the `Rotate` operation on the image according to the value of enumeration `aspose.imaging.RotateFlipType` {#example_8}
``` python

from aspose.imaging import Image, RotateFlipType
#Create an instance of image class and initialize it with an existing image file through File path
with Image.load(r"C:\temp\sample.bmp") as image:
	# rotate the image at 180 degree about X axis
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	# save all changes.
	image.save()


```

### This example shows the simple steps to save an Image. To demonstrate this operation, we load an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format using file path {#example_9}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from os.path import join as path_join

directory = "c:\\temp"

#Create an instance of image class and initialize it with an existing file through File path
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Rotate the image at 180 degree about X axis
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	#Save the Image as PSD to File Path with default PsdOptions settings
	image.save(path_join(directory, "output.psd"), PsdOptions())


```

### This example shows the process of saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format {#example_10}
``` python
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.extensions import StreamExtensions as stream_ext

#Create an instance of MemoryStream
with stream_ext.create_memory_stream() as stream:
	#Create an instance of image class and initialize it with an existing file through File path
	with Image.load(r"C:\temp\sample.bmp") as image:
		#Rotate the image at 180 degree about X axis
		image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
		#Save the Image as PSD to MemoryStream with default PsdOptions settings
		image.save(stream, PsdOptions())


```

### This example determines whether image can be loaded from a file. {#example_22}
``` python

from aspose.imaging import Image

# Use an absolute path to the file
can_load: bool = Image.can_load(r"c:\temp\sample.gif")


```

### This example determines whether image can be loaded from a file stream. {#example_23}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ext
import os.path import join

directory = r"c:\temp"

canLoad = False

# Use a file stream
with open(join(directory, "sample.bmp"), "rb"):
	canLoad = Image.can_load(stream)

print(f"Can load the file: {canLoad}")

# The following data is not a valid image stream, so CanLoad returns false.
imageData = [0, 0, 0, 0, 0, 0, 0, 0]
with strm_ext.create_memory_stream_from_bytes(imageData) as stream:
	canLoad = Image.can_load(stream)

print(f"Can load the byte buffer: {canLoad}")


```

### This example shows how to determine the image format without loading the entire image from a file. {#example_24}
``` python

from aspose.imaging import Image
from os.path import join as path_join

directory = "c:\\temp\\"

# Use an absolute path to the file
file_format = Image.get_file_format(path_join(directory, "sample.gif"))
print(f"The file format is {file_format}")


```

### This example shows how to determine the image format without loading the entire image from a file stream. {#example_25}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ex
from os.path import join as path_join

directory = "c:\\temp\\"

# Use a file stream
with open(path_join(directory, "sample.bmp"), "rb") as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")

# The following data is not a valid image stream, so get_file_format returns FileFormat.UNKNOWN
imageData = bytearray([0, 0, 0, 0, 0, 0, 0, 0])
with strm_ex.create_memory_stream_from_bytes(imageData) as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")


```

### This example shows how to determine whether image can be saved to the specified file format represented by the passed save options. {#example_26}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import JpegOptions
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	saveOptions = JpegOptions()
	saveOptions.quality = 50
	# Determine whether the image can be saved to jpeg
	canSave: bool = image.can_save(saveOptions)
	print(canSave)


```

### This example loads an image and resizes it using various resizing settings. {#example_28}
``` python
from aspose.imaging import Image, ImageResizeSettings, ResizeType, ImageFilterType,\
	ColorQuantizationMethod
from os.path import join as path_join

directory = "c:\\temp\\"

resizeSettings = ImageResizeSettings()

# The adaptive algorithm based on weighted and blended rational function and lanczos3 interpolation.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# The small rectangular filter
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# The number of colors in the palette.
resizeSettings.entries_count = 256
# The color quantization is not used
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE

# The euclidean method
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale down by 2 times using adaptive resampling.
	image.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(path_join(directory, "downsample.adaptive.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically. {#example_29}
``` python
from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale up by 2 times using Nearest Neighbour resampling.
	image.resize_width_proportionally(image.width * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale down by 2 times using Nearest Neighbour resampling.
	image.resize_width_proportionally(image.width // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale up by 2 times using Bilinear resampling.
	image.resize_width_proportionally(image.width * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale down by 2 times using Bilinear resampling.
	image.resize_width_proportionally(image.width // 2, ResizeType.BILINEAR_RESAMPLE);
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically. {#example_30}
``` python

from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale up by 2 times using Nearest Neighbour resampling.
	image.resize_height_proportionally(image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale down by 2 times using Nearest Neighbour resampling.
	image.resize_height_proportionally(image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale up by 2 times using Bilinear resampling.
	image.resize_height_proportionally(image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Scale down by 2 times using Bilinear resampling.
	image.resize_height_proportionally(image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_31}
``` python

from aspose.imaging import Image, RotateFlipType
from os.path import join as path_join

directory = "c:\\temp\\"

rotateFlipTypes = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X,
				   RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]

for rotateFlipType in rotateFlipTypes:
	# Rotate, flip and save to the output file.
	with Image.Load(path_join(directory, "sample.bmp")) as image:
		image.rotate_flip(rotateFlipType)
		image.save(path_join(directory, f"sample.{rotateFlipType}.bmp"))


```

### The following example loads a BMP image from a file, then saves the image to a PNG file. {#example_32}
``` python
from aspose.imaging import Image
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Save the entire image to a PNG file.
	save_options = PngOptions()
	image.save(path_join(dir, "output.png"), save_options)

```

### The following example loads a BMP image from a file, then saves a rectangular part of the image to a PNG file. {#example_33}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	# Save the upper half of the image to a PNG file.
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	image.save(path_join(dir, "output.png"), save_options, bounds)

```

### The following example loads an image from a file, then saves the image to a PNG file stream. {#example_34}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Save the entire image to a file stream.
		image.save(output_stream, save_options)

```

### The following example loads an image from a file, then saves a rectangular part of the image to a PNG file stream. {#example_35}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

with Image.load(path_join(dir, "sample.bmp")) as image:
	save_options = PngOptions()
	bounds = Rectangle(0, 0, image.width, image.height // 2)
	with open(path_join(dir, "output.png"), "w+b") as output_stream:
		# Save the upper half of the image to a file stream.
		image.save(output_stream, save_options, bounds)


```

### The following example shows how to save an entire BMP image or part of it to a file or stream. {#example_90}
``` python

from os.path import join as path_join
from aspose.pycore import as_of
from aspose.imaging import Image, ColorPaletteHelper
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.extensions import StreamExtensions as strm_ext

directory = "c:\\temp\\"
with Image.load(path_join(directory, "sample.bmp")) as image:
	bmpImage = as_of(image, BmpImage)
		
	# Convert to a black-white image
	bmpImage.binarize_otsu()

	# Save to the same location with default options.
	image.save()

	saveOptions = BmpOptions()

	# A palette contains only two colors: Black and White in this case.
	saveOptions.palette = ColorPaletteHelper.create_monochrome()

	# For all monochrome images (including black-white ones) it is enough to allocate 1 bit per pixel.
	saveOptions.bits_per_pixel = 1

	# Save to another location with the specified options.
	image.save(path_join(directory, "sample.bw.palettized.bmp"), saveOptions)

	# Save only the central part of the image.
	bounds = Rectangle(image.width // 4, image.height // 4, image.width // 2, image.height // 2)
	image.save(path_join(directory, "sample.bw.palettized.part.bmp"), saveOptions, bounds)

	# Save the entire image to a memory stream
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions);
		print("The size of the whole image in bytes:", stream.tell())

	# Save the central part of the image to a memory stream
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions, bounds)
		print("The size of the central part of the image in bytes: ", stream.tell())

#The output may look like this:
#The size of the whole image in bytes: 24062
#The size of the central part of the image in bytes: 6046

```

### The following example shows how to resize a metafile (WMF and EMF). {#example_167}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.emf import MetaImage
from os.path import join

dir_ = "c:\\temp"
file_names = ["image3.emf", "image4.wmf"]
for file_name in file_names:
	input_file_path = join(dir_, file_name)
	output_file_path = join(dir_, "Downscale_" + file_name)
	with aspycore.as_of(Image.load(input_file_path), MetaImage) as image:
		image.resize(image.width // 4, image.height // 4)
		image.save(output_file_path)


```

### Resize image using specific Resize Type. {#example_187}
``` python
from aspose.imaging import Image, ResizeType, ImageResizeSettings, ImageFilterType

with Image.load("Photo.jpg") as image:
	image.resize(640, 480, ResizeType.CATMULL_ROM)
	image.save("ResizedPhoto.jpg")
	image.resize(1024, 768, ResizeType.CUBIC_CONVOLUTION)
	image.save("ResizedPhoto2.jpg")
	resize_settings = ImageResizeSettings()
	resize_settings.mode = ResizeType.CUBIC_BSPLINE
	resize_settings.filter_type = ImageFilterType.SMALL_RECTANGULAR
	image.resize(800, 800, resize_settings)
	image.save("ResizedPhoto3.jpg")


```

### Determine if the palette is used by the image. {#example_197}
``` python

from aspose.imaging import Image

with Image.load("Sample.bmp") as image:
	if image.use_palette:
		print("The palette is used by the image")

```

