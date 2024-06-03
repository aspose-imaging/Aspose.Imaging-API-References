---
title: EmfImage Class
type: docs
weight: 670
url: /python-net/aspose.imaging.fileformats.emf/emfimage/
---

**Summary:** The API for Enhanced Metafile Format (EMF) vector image format support is<br/>            a comprehensive tool for processing graphical images in a device-independent<br/>            manner while preserving their original properties. Developed to maintain<br/>            proportions, dimensions, colors, and other graphic attributes, it includes<br/>            EMF Plus format support and features for cropping regions, resizing canvas<br/>            and images, rotating, flipping, setting image palettes, exporting and importing<br/>            to APS device context, compressing and converting EMF to other formats, ensuring<br/>            versatile manipulation and seamless integration of EMF images across applications.

**Module:** [aspose.imaging.fileformats.emf](/imaging/python-net/aspose.imaging.fileformats.emf/)

**Full Name:** aspose.imaging.fileformats.emf.EmfImage

**Inheritance:** IObjectWithBounds, IObjectWithSizeF, MetaImage

**Aspose.Imaging Version:** 24.6.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfImage()](#EmfImage__1) | Start working with EMF images by initializing a new instance of the<br/>            [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) class. Ideal for quickly incorporating EMF images into <br/>            your projects with ease and efficiency. |
| [EmfImage(width, height)](#EmfImage_width_height_2) | Create a new instance of the [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) class by specifying the width <br/>            and height parameters. This constructor simplifies the process of initializing <br/>            EMF images with specific dimensions, enhancing the efficiency of your development <br/>            workflow. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Gets or sets a value indicating whether automatic adjust palette. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color) | r/w | Gets or sets a value for the background color. |
| bits_per_pixel | int | r | Retrieve the bit-per-pixel count specific to raster images, as this parameter <br/>            doesn't apply to vector images. Quickly ascertain the pixel depth of raster <br/>            images for precise analysis and manipulation, ensuring accurate handling<br/>            of image data. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | r | Gets the object bounds. |
| buffer_size_hint | int | r/w | Gets or sets the buffer size hint which is defined max allowed size for all internal buffers. |
| container | [Image](/imaging/python-net/aspose.imaging/image) | r | Gets the [Image](/imaging/python-net/aspose.imaging/image/) container. |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer) | r | Gets the object's data stream. |
| disposed | bool | r | Gets a value indicating whether this instance is disposed. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat) | r | Access the file format value associated with the object. Easily determine the <br/>            format of the file associated with the object for streamlined processing and <br/>            compatibility checks. Simplify your workflow by retrieving the file format <br/>            information with ease. |
| has_background_color | bool | r/w | Gets or sets a value indicating whether image has background color. |
| header | [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) | r/w | Retrieve or modify the EMF metafile header record with this property. Ideal for <br/>            managing metafile data efficiently within your application. Improve your workflow <br/>            with streamlined access to metafile header information. |
| height | int | r | Retrieve the image's height, facilitating accurate rendering and layout adjustments. <br/>            Accessing the height property ensures compatibility and seamless integration across <br/>            different platforms and applications. |
| height_f | float | r | Gets the object height, in inches. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Gets or sets the interrupt monitor. |
| is_cached | bool | r | Access a value indicating whether the object's data is currently cached, <br/>            eliminating the need for additional data reading. Enhance efficiency by quickly <br/>            determining if cached data is available for immediate access. Optimize your <br/>            workflow with streamlined data retrieval processes. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | r/w | Gets or sets the color palette. The color palette is not used when pixels are represented directly. |
| records | [MetaObjectList](/imaging/python-net/aspose.imaging.fileformats.emf/metaobjectlist) | r/w | Retrieve or modify the records associated with the object. Efficiently access and <br/>            manage the collection of records for enhanced data manipulation and processing. <br/>            Optimize your workflow by seamlessly interacting with the object's records. |
| size | [Size](/imaging/python-net/aspose.imaging/size) | r | Gets the object size. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef) | r | Gets the object size, in inches. |
| use_palette | bool | r | Gets a value indicating whether the image palette is used. |
| width | int | r | Access to the width of the image, providing essential information for precise <br/>            rendering and processing. Quickly retrieve the image's width to ensure compatibility <br/>            and proper layout within various applications and platforms. |
| width_f | float | r | Gets the object width, in inches. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Efficiently cache data and prevent redundant loading from the underlying<br/>            [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) with this method. Enhance <br/>            performance and streamline data access in your application, optimizing resource <br/>            utilization for improved responsiveness. |
| [can_load(file_path)](#can_load_file_path_1) | Determines whether image can be loaded from the specified file path. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_load(stream)](#can_load_stream_3) | Determines whether image can be loaded from the specified stream. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Determines whether image can be loaded from the specified stream. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Determines whether image can be loaded from the specified stream and optionally using the specified _loadOptions_. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Determines whether image can be loaded from the specified file path and optionally using the specified open options. |
| [can_save(options)](#can_save_options_8) | Determines whether image can be saved to the specified file format represented by the passed save options. |
| [create(image_options, width, height)](#create_image_options_width_height_9) | Creates a new image using the specified create options. |
| [create(images)](#create_images_10) | Creates a new image using the specified images as pages |
| [create(images, dispose_images)](#create_images_dispose_images_11) | Creates a new image the specified images as pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_12) | Crop image with shifts. |
| [crop(rectangle)](#crop_rectangle_13) | Crop the specified rectangle using this function. Ideal for refining image <br/>            composition and focusing on specific areas of interest within the image. Improve <br/>            visual clarity and highlight key details with precise cropping functionality. |
| [get_default_options(args)](#get_default_options_args_14) | Retrieve the default options for your image effortlessly. With this feature, you <br/>            can quickly access the preset configurations, ensuring seamless integration and <br/>            optimal performance for your projects. Ideal for streamlining your workflow and <br/>            achieving consistent results across your images. |
| [get_embedded_images()](#get_embedded_images__15) | Gets the embedded images. |
| [get_file_format(file_path)](#get_file_format_file_path_16) | Gets the file format. |
| [get_file_format(stream)](#get_file_format_stream_17) | Gets the file format. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_18) | Gets the file format. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_19) | Gets rectangle which fits the current image. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_20) | Gets rectangle which fits the current image. |
| [get_missed_fonts()](#get_missed_fonts__21) | Returns the list of fonts which used inside metafile but not found. |
| [get_original_options()](#get_original_options__22) | Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_23) | Gets a proportional height. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_24) | Gets a proportional width. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_25) | Converts to aps. |
| [get_used_fonts()](#get_used_fonts__26) | Retrieve the list of fonts utilized within the metafile with this method. Gain <br/>            insights into font usage, facilitating efficient management and optimization of font <br/>            resources for enhanced rendering and display fidelity. |
| [load(file_path)](#load_file_path_27) | Loads a new image from the specified file. |
| [load(file_path, load_options)](#load_file_path_load_options_28) | Loads a new image from the specified file. |
| [load(stream)](#load_stream_29) | Loads a new image from the specified stream. |
| [load(stream, load_options)](#load_stream_load_options_30) | Loads a new image from the specified stream. |
| [load_stream(stream)](#load_stream_stream_31) | Loads a new image from the specified stream. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_32) | Loads a new image from the specified stream. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_33) | Loads a new image from the specified file. |
| remove_background() | Removes the background. |
| [remove_background(settings)](#remove_background_settings_34) | Removes the background. |
| remove_metadata() | Removes metadata. |
| [resize(new_width, new_height)](#resize_new_width_new_height_35) | Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_36) | Resizes the image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_37) | Resizes the image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_38) | Resizes the image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_39) | Resizes the image. |
| [resize_canvas(new_rectangle)](#resize_canvas_new_rectangle_40) | Resize the canvas with ease using this function. Perfect for adjusting the overall <br/>            dimensions of the image without altering its content. Enhance presentation and <br/>            prepare images for various display sizes effortlessly. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_41) | Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_42) | Resizes the height proportionally. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_43) | Resizes the height proportionally. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_44) | Resizes the height proportionally. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_45) | Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_46) | Resizes the width proportionally. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_47) | Resizes the width proportionally. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_48) | Resizes the width proportionally. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_49) | Easily rotate, flip, or perform both operations simultaneously on your image using <br/>            this simple `RotateFlip()` method. Perfect for adjusting orientation and enhancing <br/>            visual appeal without hassle. Ideal for achieving the desired presentation of your <br/>            images in any project or application. |
| save() | Saves the image data to the underlying stream. |
| [save(file_path)](#save_file_path_50) | Saves the image to the specified file location. |
| [save(file_path, options)](#save_file_path_options_51) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_52) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save(file_path, over_write)](#save_file_path_over_write_53) | Saves the object's data to the specified file location. |
| [save(stream)](#save_stream_54) | Saves the data. |
| [save(stream, options_base)](#save_stream_options_base_55) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_56) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream(stream)](#save_to_stream_stream_57) | Saves the object's data to the specified stream. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_58) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_59) | Saves the image's data to the specified stream in the specified file format according to save options. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_60) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_61) | Saves the object's data to the specified file location in the specified file format according to save options. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_62) | Enhance your image's color palette by setting it with the specified <br/>            `IColorPalette`. Achieve vivid, vibrant visuals with ease, ensuring your images <br/>            stand out and captivate viewers. Ideal for optimizing color schemes and achieving <br/>            the perfect look for your projects. |


### Constructor: EmfImage() {#EmfImage__1}


```
 EmfImage() 
```

Start working with EMF images by initializing a new instance of the<br/>            [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) class. Ideal for quickly incorporating EMF images into <br/>            your projects with ease and efficiency.

### Constructor: EmfImage(width, height) {#EmfImage_width_height_2}


```
 EmfImage(width, height) 
```

Create a new instance of the [EmfImage](/imaging/python-net/aspose.imaging.fileformats.emf/emfimage/) class by specifying the width <br/>            and height parameters. This constructor simplifies the process of initializing <br/>            EMF images with specific dimensions, enhancing the efficiency of your development <br/>            workflow.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| width | int | The width. |
| height | int | The height. |

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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_9}


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


### Method: create(images)  [static] {#create_images_10}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_11}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_12}


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

### Method: crop(rectangle) {#crop_rectangle_13}


```
 crop(rectangle) 
```

Crop the specified rectangle using this function. Ideal for refining image <br/>            composition and focusing on specific areas of interest within the image. Improve <br/>            visual clarity and highlight key details with precise cropping functionality.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The rectangle. |

### Method: get_default_options(args) {#get_default_options_args_14}


```
 get_default_options(args) 
```

Retrieve the default options for your image effortlessly. With this feature, you <br/>            can quickly access the preset configurations, ensuring seamless integration and <br/>            optimal performance for your projects. Ideal for streamlining your workflow and <br/>            achieving consistent results across your images.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| args | object | The arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | Default options |


### Method: get_embedded_images() {#get_embedded_images__15}


```
 get_embedded_images() 
```

Gets the embedded images.

**Returns**

| Type | Description |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage) | Array of images |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_16}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_17}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_18}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_19}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_20}


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


### Method: get_missed_fonts() {#get_missed_fonts__21}


```
 get_missed_fonts() 
```

Returns the list of fonts which used inside metafile but not found.

**Returns**

| Type | Description |
| :- | :- |
| string | The font list |


### Method: get_original_options() {#get_original_options__22}


```
 get_original_options() 
```

Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the<br/>            [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) method, the output PNG image with 8-bit per pixel will be produced.<br/>            To avoid it and save PNG image with 1-bit per pixel, use this method to get corresponding saving options and pass them<br/>            to the [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) method as the second parameter.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options based on the original file settings. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_23}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_24}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_25}


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


### Method: get_used_fonts() {#get_used_fonts__26}


```
 get_used_fonts() 
```

Retrieve the list of fonts utilized within the metafile with this method. Gain <br/>            insights into font usage, facilitating efficient management and optimization of font <br/>            resources for enhanced rendering and display fidelity.

**Returns**

| Type | Description |
| :- | :- |
| string | The font list |


### Method: load(file_path)  [static] {#load_file_path_27}


```
 load(file_path) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_28}


```
 load(file_path, load_options) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(stream)  [static] {#load_stream_29}


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
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_30}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_31}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_32}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_33}


```
 load_with_options(file_path, load_options) 
```

Loads a new image from the specified file.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to load image from. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions) | The load options. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image) | The loaded image. |


### Method: remove_background(settings) {#remove_background_settings_34}


```
 remove_background(settings) 
```

Removes the background.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings) | The settings. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_35}


```
 resize(new_width, new_height) 
```

Resizes the image. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_36}


```
 resize(new_width, new_height, resize_type) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | The resize type. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_37}


```
 resize(new_width, new_height, settings) 
```

Resizes the image.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The resize settings. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_38}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_39}


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

### Method: resize_canvas(new_rectangle) {#resize_canvas_new_rectangle_40}


```
 resize_canvas(new_rectangle) 
```

Resize the canvas with ease using this function. Perfect for adjusting the overall <br/>            dimensions of the image without altering its content. Enhance presentation and <br/>            prepare images for various display sizes effortlessly.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle) | The new rectangle. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_41}


```
 resize_height_proportionally(new_height) 
```

Resizes the height proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_42}


```
 resize_height_proportionally(new_height, resize_type) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_43}


```
 resize_height_proportionally(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_44}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Resizes the height proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_height | int | The new height. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_45}


```
 resize_width_proportionally(new_width) 
```

Resizes the width proportionally. The default [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_46}


```
 resize_width_proportionally(new_width, resize_type) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype) | Type of the resize. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_47}


```
 resize_width_proportionally(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_48}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Resizes the width proportionally.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_width | int | The new width. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings) | The image resize settings. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_49}


```
 rotate_flip(rotate_flip_type) 
```

Easily rotate, flip, or perform both operations simultaneously on your image using <br/>            this simple `RotateFlip()` method. Perfect for adjusting orientation and enhancing <br/>            visual appeal without hassle. Ideal for achieving the desired presentation of your <br/>            images in any project or application.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype) | Type of the rotate flip. |

### Method: save(file_path) {#save_file_path_50}


```
 save(file_path) 
```

Saves the image to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the image to. |

### Method: save(file_path, options) {#save_file_path_options_51}


```
 save(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_52}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_53}


```
 save(file_path, over_write) 
```

Saves the object's data to the specified file location.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path to save the object's data to. |
| over_write | bool | if set to <c>true</c> over write the file contents, otherwise append will occur. |

### Method: save(stream) {#save_stream_54}


```
 save(stream) 
```

Saves the data.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save data to. |

### Method: save(stream, options_base) {#save_stream_options_base_55}


```
 save(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_56}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_57}


```
 save_to_stream(stream) 
```

Saves the object's data to the specified stream.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the object's data to. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_58}


```
 save_to_stream_with_options(stream, options_base) 
```

Saves the image's data to the specified stream in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom | The stream to save the image's data to. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The save options. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_59}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_60}


```
 save_with_options(file_path, options) 
```

Saves the object's data to the specified file location in the specified file format according to save options.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| file_path | string | The file path. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase) | The options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_61}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_62}


```
 set_palette(palette, update_colors) 
```

Enhance your image's color palette by setting it with the specified <br/>            `IColorPalette`. Achieve vivid, vibrant visuals with ease, ensuring your images <br/>            stand out and captivate viewers. Ideal for optimizing color schemes and achieving <br/>            the perfect look for your projects.

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette) | The palette to set. |
| update_colors | bool | if set to <c>true</c> colors will be updated according to the new palette; otherwise color indexes remain unchanged. Note that unchanged indexes may crash the image on loading if some indexes have no corresponding palette entries. |

