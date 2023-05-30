---
title: VectorImage Class
type: docs
weight: 870
url: /python-net/aspose.imaging/vectorimage/
---

The vector image is the base class for all type of vector images.

**Namespace:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Class Name:** aspose.imaging.VectorImage

**Assembly:**  Aspose.Imaging Version: 23.5.6

The VectorImage type exposes the following members:
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|  |
|bits_per_pixel|Gets the image bits per pixel count.|
|bounds|Gets the image bounds.|
|container|Gets the [Image](/imaging/python-net/aspose.imaging/image/) container.|
|height|Gets the image height.|
|palette|Gets or sets the color palette. The color palette is not used when pixels are represented directly.|
|use_palette|Gets a value indicating whether the image palette is used.|
|size|Gets the image size.|
|width|Gets the image width.|
|interrupt_monitor|Gets or sets the interrupt monitor.|
|buffer_size_hint|Gets or sets the buffer size hint which is defined max allowed size for all internal buffers.|
|auto_adjust_palette|Gets or sets a value indicating whether automatic adjust palette.|
|has_background_color|Gets or sets a value indicating whether image has background color.|
|file_format|Gets a value of file format|
|background_color|Gets or sets a value for the background color.|
|size_f|Gets the object size, in inches.|
|width_f|Gets the object width, in inches.|
|height_f|Gets the object height, in inches.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save()|Saves the image data to the underlying stream.|
|save(file_path)|Saves the image to the specified file location.|
|save(file_path, options)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save(file_path, options, bounds_rectangle)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save(stream, options_base)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(stream, options_base, bounds_rectangle)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(stream)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save(file_path, over_write)|  |
|can_load(file_path)|Determines whether image can be loaded from the specified file path.|
|can_load(file_path, load_options)|Determines whether image can be loaded from the specified file path and optionally using the specified open options.|
|can_load(stream)|Determines whether image can be loaded from the specified stream.|
|can_load(stream, load_options)|Determines whether image can be loaded from the specified stream and optionally using the specified|
|create(image_options, width, height)|Creates a new image using the specified create options.|
|create(images)|Creates a new image using the specified images as pages|
|create(images, dispose_images)|Creates a new image the specified images as pages.|
|get_file_format(file_path)|Gets the file format.|
|get_file_format(stream)|Gets the file format.|
|get_fitting_rectangle(rectangle, width, height)|Gets rectangle which fits the current image.|
|get_fitting_rectangle(rectangle, pixels, width, height)|Gets rectangle which fits the current image.|
|load(file_path, load_options)|Loads a new image from the specified file.|
|load(file_path)|Loads a new image from the specified file.|
|load(stream, load_options)|Loads a new image from the specified stream.|
|load(stream)|Loads a new image from the specified stream.|
|resize(new_width, new_height)|Resizes the image. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.|
|resize(new_width, new_height, resize_type)|Resizes the image.|
|resize(new_width, new_height, settings)|Resizes the image.|
|resize_width_proportionally(new_width)|Resizes the width proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.|
|resize_width_proportionally(new_width, resize_type)|Resizes the width proportionally.|
|resize_width_proportionally(new_width, settings)|Resizes the width proportionally.|
|resize_height_proportionally(new_height)|Resizes the height proportionally. The default [NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) is used.|
|resize_height_proportionally(new_height, resize_type)|Resizes the height proportionally.|
|resize_height_proportionally(new_height, settings)|Resizes the height proportionally.|
|cache_data()|  |
|save_to_stream(stream)|Saves the image's data to the specified stream in the specified file format according to save options.|
|can_load_with_options(file_path, load_options)|Determines whether image can be loaded from the specified file path and optionally using the specified open options.|
|can_load_stream(stream)|Determines whether image can be loaded from the specified stream.|
|can_load_stream_with_options(stream, load_options)|Determines whether image can be loaded from the specified stream and optionally using the specified|
|get_file_format_of_stream(stream)|Gets the file format.|
|load_with_options(file_path, load_options)|Loads a new image from the specified file.|
|load_stream_with_options(stream, load_options)|Loads a new image from the specified stream.|
|load_stream(stream)|Loads a new image from the specified stream.|
|can_save(options)|Determines whether image can be saved to the specified file format represented by the passed save options.|
|resize_by_type(new_width, new_height, resize_type)|Resizes the image.|
|resize_by_settings(new_width, new_height, settings)|Resizes the image.|
|get_default_options(args)|Gets the default options.|
|get_original_options()|Gets the options based on the original file settings.<br/>            This can be helpful to keep bit-depth and other parameters of the original image unchanged.<br/>            For example, if we load a black-white PNG image with 1 bit per pixel and then save it using the|
|resize_width_proportionally_settings(new_width, settings)|Resizes the width proportionally.|
|resize_height_proportionally_settings(new_height, settings)|Resizes the height proportionally.|
|rotate_flip(rotate_flip_type)|Rotates, flips, or rotates and flips the image.|
|save_with_options(file_path, options)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save_with_options_rect(file_path, options, bounds_rectangle)|Saves the object's data to the specified file location in the specified file format according to save options.|
|save_to_stream_with_options(stream, options_base)|Saves the image's data to the specified stream in the specified file format according to save options.|
|save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)|Saves the image's data to the specified stream in the specified file format according to save options.|
|set_palette(palette, update_colors)|Sets the image palette.|
|get_proportional_width(width, height, new_height)|Gets a proportional width.|
|get_proportional_height(width, height, new_width)|Gets a proportional height.|
|get_embedded_images()|Gets the embedded images.|
