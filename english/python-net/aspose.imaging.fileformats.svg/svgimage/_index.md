---
title: SvgImage Class
type: docs
weight: 40
url: /python-net/aspose.imaging.fileformats.svg/svgimage/
---

**Summary:** Manipulate Scalar Vector Graphics (SVG) image files with our API, utilizing<br/>            the power of XML-based text format for seamless customization and scalability.<br/>            Easily load SVG images, rasterize vector elements, and convert to other formats,<br/>            while controlling compression levels to optimize file size and quality for your projects.

**Module:** [aspose.imaging.fileformats.svg](/imaging/python-net/aspose.imaging.fileformats.svg/)

**Full Name:** aspose.imaging.fileformats.svg.SvgImage

**Inheritance:** IObjectWithBounds, IObjectWithSizeF, IHasXmpData, IHasMetadata, VectorImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SvgImage(path)](#SvgImage_path_1) | Instantiates a new object of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class, utilizing the <br/>            specified path to locate and load the image. This constructor facilitates the <br/>            creation of SVG image instances from external files, enabling seamless <br/>            integration into software systems and workflows. |
| [SvgImage(stream)](#SvgImage_stream_2) | Creates a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class, loading the image <br/>            from the provided stream. This constructor enables the direct loading of SVG <br/>            images from streams, enhancing flexibility and efficiency in handling image <br/>            resources within software applications. |
| [SvgImage(svg_options, width, height)](#SvgImage_svg_options_width_height_3) | Creates a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class with specified SVG <br/>            options, image width, and height parameters. This constructor enables <br/>            developers to initialize SVG images with custom options and dimensions, <br/>            providing flexibility in managing SVG content and layout. |
| [SvgImage(width, height)](#SvgImage_width_height_4) | Instantiates a new [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) object with the specified width and <br/>            height. This constructor allows developers to create SVG images with predefined <br/>            dimensions, facilitating precise control over the image's size during <br/>            initialization. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Retrieves the bits per pixel count of the image. It's important to note that <br/>            this parameter is not applicable to vector images, as they are not measured in <br/>            pixels. This property provides crucial information about the image's color <br/>            depth, aiding in processing and manipulation tasks. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Retrieves the file format of the image, providing essential metadata for <br/>            processing and compatibility checks. This property is instrumental in <br/>            determining the appropriate decoding and encoding strategies for handling the <br/>            image data effectively across different systems and applications. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| height | int | r | Gets the image height. |
| height_f | float | r | Gets the object height, in inches. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Retrieves a boolean value indicating whether the object's data is presently <br/>            cached, eliminating the need for additional data reading operations. This <br/>            property provides insight into the current caching status, optimizing data <br/>            retrieval and processing workflows for enhanced performance and efficiency. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r | Gets the object size, in inches. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| width | int | r | Gets the image width. |
| width_f | float | r | Gets the object width, in inches. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Gets or sets XMP data. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Cache the data and guarantee that there will be no further loading of data from <br/>            the underlying [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/). This <br/>            optimization enhances performance by eliminating redundant data retrieval <br/>            operations, especially beneficial in scenarios requiring frequent access to the <br/>            image data. |
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
| [create(images)](#create_images_12) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_13) | Creates a new image the specified images as pages. |
| [create(multipage_create_options)](#create_multipage_create_options_14) | Creates the specified multipage create options. |
| [create_from_files(files)](#create_from_files_files_15) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_16) | Creates the multipage image containing the specified files as lazy loading pages. |
| [create_from_images(images)](#create_from_images_images_17) | Creates a new image using the specified images as pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_18) | Creates a new image the specified images as pages. |
| [create_from_stream(stream)](#create_from_stream_stream_19) | Initializes a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_21) | Crops the specified rectangle. |
| [get_default_options(args)](#get_default_options_args_22) | Gets the default image options. |
| [get_embedded_images()](#get_embedded_images__23) | Gets the embedded images. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_25) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Gets rectangle which fits the current image. |
| [get_original_options()](#get_original_options__29) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_30) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_31) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_32) | Converts to aps. |
| [load(file_path)](#load_file_path_33) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(file_path, load_options)](#load_file_path_load_options_34) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| [load(stream)](#load_stream_35) | Loads the SVG section. |
| [load(stream, load_options)](#load_stream_load_options_36) | Loads a new image from the specified stream. |
| [load_stream(stream)](#load_stream_stream_37) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_38) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_39) | Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it. |
| remove_background() | Removes the background. |
| [remove_background(settings)](#remove_background_settings_40) | Removes the background. |
| remove_metadata() | Removes metadata. |
| [resize(new_width, new_height)](#resize_new_width_new_height_41) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_42) | Resize the image to fit the specified dimensions while preserving its aspect <br/>            ratio. This method provides a convenient way to adjust the size of the image <br/>            without distorting its proportions, ensuring optimal display or storage <br/>            according to the desired dimensions. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_43) | Resizes the image with extended options. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_44) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_45) | Resizes the image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_46) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_47) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_48) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_49) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_50) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_51) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_52) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_53) | Resizes the width proportionally. |
| [rotate(angle)](#rotate_angle_54) | Rotate image around the center. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_55) | Rotates, flips, or rotates and flips the image. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_56) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_57) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_58) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_59) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_60) | Saves the data. |
| [save(stream, options_base)](#save_stream_options_base_61) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_62) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream(stream)](#save_to_stream_stream_63) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_64) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_66) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_67) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_68) | Applies a specified palette to the image, enabling customization of color <br/>            schemes for aesthetic or functional purposes. This method provides flexibility <br/>            in managing color palettes to suit various design or application requirements. |


### Constructor: SvgImage(path) {#SvgImage_path_1}


```
 SvgImage(path) 
```

Instantiates a new object of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class, utilizing the <br/>            specified path to locate and load the image. This constructor facilitates the <br/>            creation of SVG image instances from external files, enabling seamless <br/>            integration into software systems and workflows.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string | The path to load image from and initialize pixel and palette data with. |

### Constructor: SvgImage(stream) {#SvgImage_stream_2}


```
 SvgImage(stream) 
```

Creates a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class, loading the image <br/>            from the provided stream. This constructor enables the direct loading of SVG <br/>            images from streams, enhancing flexibility and efficiency in handling image <br/>            resources within software applications.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |


**See also:**

**[Example # 1](#example_157)**: This example shows how to load an SVG image from a file stream and rasterize ...


### Constructor: SvgImage(svg_options, width, height) {#SvgImage_svg_options_width_height_3}


```
 SvgImage(svg_options, width, height) 
```

Creates a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class with specified SVG <br/>            options, image width, and height parameters. This constructor enables <br/>            developers to initialize SVG images with custom options and dimensions, <br/>            providing flexibility in managing SVG content and layout.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| svg_options | [SvgOptions](/imaging/python-net/aspose.imaging.imageoptions/svgoptions/) | The SVG options. |
| width | int | Image width. |
| height | int | Image height. |

### Constructor: SvgImage(width, height) {#SvgImage_width_height_4}


```
 SvgImage(width, height) 
```

Instantiates a new [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) object with the specified width and <br/>            height. This constructor allows developers to create SVG images with predefined <br/>            dimensions, facilitating precise control over the image's size during <br/>            initialization.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The image width. |
| height | int | The image height. |

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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


```
 can_load(file_path, load_options) 
```

Determines whether image can be loaded from the specified file path and optionally using the specified open options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


```
 can_load(stream, load_options) 
```

Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

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
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

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
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

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
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options to use. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> if image can be saved to the specified file format represented by the passed save options; otherwise, <c>false</c>. |


### Method: create(files)  [static] {#create_files_9}


```
 create(files) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


```
 create(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> [throw exception on load error]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


```
 create(image_options, width, height) 
```

Creates a new image using the specified create options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |
| width | int | The width. |
| height | int | The height. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The newly created image. |


### Method: create(images)  [static] {#create_images_12}


```
 create(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_13}


```
 create(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_14}


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
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_files(files)  [static] {#create_from_files_files_15}


```
 create_from_files(files) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_16}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Creates the multipage image containing the specified files as lazy loading pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| files | string | The files. |
| throw_exception_on_load_error | bool | if set to <c>true</c> throw exception on load error. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The multipage image |


### Method: create_from_images(images)  [static] {#create_from_images_images_17}


```
 create_from_images(images) 
```

Creates a new image using the specified images as pages

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_18}


```
 create_from_images(images, dispose_images) 
```

Creates a new image the specified images as pages.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image) | The images. |
| dispose_images | bool | if set to <c>true</c> [dispose images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The Image as IMultipageImage |


### Method: create_from_stream(stream)  [static] {#create_from_stream_stream_19}


```
 create_from_stream(stream) 
```

Initializes a new instance of the [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage/) class.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from and initialize pixel and palette data with. |

**Returns**

| Type | Description |
| :- | :- |
| [SvgImage](/imaging/python-net/aspose.imaging.fileformats.svg/svgimage) |  |


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
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

### Method: get_default_options(args) {#get_default_options_args_22}


```
 get_default_options(args) 
```

Gets the default image options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The default image options. |


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Gets the embedded images.

**Returns**

| Type | Description |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage) | Array of images |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | The determined file format. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get fitting rectangle for. |
| pixels | int | The 32-bit ARGB pixels. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Gets rectangle which fits the current image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle to get fitting rectangle for. |
| width | int | The object width. |
| height | int | The object height. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The fitting rectangle or exception if no fitting rectangle can be found. |


### Method: get_original_options() {#get_original_options__29}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_30}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_31}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_32}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Converts to aps.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The image options. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The clipping rectangle. |
| page_number | int[] | The page number. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | The serialized stream |


### Method: load(file_path)  [static] {#load_file_path_33}


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
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_34}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_35}


```
 load(stream) 
```

Loads the SVG section.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) |  |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_36}


```
 load(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load_stream(stream)  [static] {#load_stream_stream_37}


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
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_38}


```
 load_stream_with_options(stream, load_options) 
```

Loads a new image from the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_39}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file path or URL.<br/>            If _filePath_ is a file path the method just opens the file.<br/>            If _filePath_ is an URL, the method downloads the file, stores it as a temporary one, and opens it.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path or URL to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: remove_background(settings) {#remove_background_settings_40}


```
 remove_background(settings) 
```

Removes the background.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings) | The settings. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_41}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_42}


```
 resize(new_width, new_height, resize_type) 
```

Resize the image to fit the specified dimensions while preserving its aspect <br/>            ratio. This method provides a convenient way to adjust the size of the image <br/>            without distorting its proportions, ensuring optimal display or storage <br/>            according to the desired dimensions.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_43}


```
 resize(new_width, new_height, settings) 
```

Resizes the image with extended options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_44}


```
 resize_by_settings(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_45}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_46}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_47}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_48}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_49}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_50}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_51}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_52}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_53}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: rotate(angle) {#rotate_angle_54}


```
 rotate(angle) 
```

Rotate image around the center.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| angle | float | The rotate angle in degrees. Positive values will rotate clockwise. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_55}


```
 rotate_flip(rotate_flip_type) 
```

Rotates, flips, or rotates and flips the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | Type of the rotate flip. |

### Method: save(file_path) {#save_file_path_56}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_57}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_58}


```
 save(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: save(file_path, over_write) {#save_file_path_over_write_59}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_60}


```
 save(stream) 
```

Saves the data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

### Method: save(stream, options_base) {#save_stream_options_base_61}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_62}


```
 save(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_to_stream(stream) {#save_to_stream_stream_63}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_64}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_65}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use source bounds. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_66}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_67}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The destination image bounds rectangle. Set the empty rectangle for use sourse bounds. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_68}


```
 set_palette(palette, update_colors) 
```

Applies a specified palette to the image, enabling customization of color <br/>            schemes for aesthetic or functional purposes. This method provides flexibility <br/>            in managing color palettes to suit various design or application requirements.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

## **Examples**
### This example shows how to load an SVG image from a file stream and rasterize it to PNG. {#example_157}
``` python
import aspose.pycore as aspycore
from os.path import join
from aspose.imaging.fileformats.svg import SvgImage
from aspose.imaging.imageoptions import PngOptions, SvgRasterizationOptions

dir_: str = "c:\\temp"
# Load an SVG image from a file stream.
with open(join(dir_, "test.svg"), "rb") as stream:
	with SvgImage(stream) as svg_image:
		# In order to rasterize SVG we need to specify rasterization options.
		rasterization_options = SvgRasterizationOptions()
		save_options = PngOptions()
		save_options.vector_rasterization_options = rasterization_options
		svg_image.save(join(dir_, "test.output.png"), save_options)


```

### The following example shows how to convert a svgz images to svg fromat {#example_171}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions
from os.path import join

file: str = "example.svgz"
base_folder: str = join("D:", "Compressed")
input_file: str = join(base_folder, file)
out_file: str = input_file + ".svg"
with Image.load(input_file) as image:
	obj_init = SvgRasterizationOptions()
	obj_init.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = obj_init
	image.save(out_file, obj_init2)


```

### The following example shows how to convert a svg images to svgz format {#example_174}
``` python

from os.path import join as path_combine
import aspose.pycore as aspycore
from aspose.imaging import Image, SizeF
from aspose.imaging.imageoptions import SvgRasterizationOptions, SvgOptions

file = "juanmontoya_lingerie.svg"
base_folder = path_combine("D:", "Compressed")
input_file = path_combine(base_folder, file)
out_file = input_file + ".svgz"
with Image.load(input_file) as image:
	vector_rasterization_options = SvgRasterizationOptions()
	vector_rasterization_options.page_size = aspycore.cast(SizeF, image.size)
	obj_init2 = SvgOptions()
	obj_init2.vector_rasterization_options = vector_rasterization_options
	obj_init2.compress = True
	image.save(out_file, obj_init2)            


```

