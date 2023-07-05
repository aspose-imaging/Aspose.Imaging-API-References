---
title: WmfImage Class
type: docs
weight: 10
url: /python-net/aspose.imaging.fileformats.wmf/wmfimage/
---

The Wmf Image

**Namespace:** [aspose.imaging.fileformats.wmf](/imaging/python-net/aspose.imaging.fileformats.wmf/)

**Full Class Name:** aspose.imaging.fileformats.wmf.WmfImage

**Assembly:**  Aspose.Imaging Version: 23.6.0

The WmfImage type exposes the following members:
## **Constructors**
|**Name**|**Description**|
| :- | :- |
|WmfImage()|Initializes a new instance of the [WmfImage](/imaging/python-net/aspose.imaging.fileformats.wmf/wmfimage/) class.|
|WmfImage(width, height)|Initializes a new instance of the WmfImage class|
## **Properties**
|**Name**|**Description**|
| :- | :- |
|disposed|  |
|data_stream_container|  |
|is_cached|Gets a value indicating whether object's data is cached currently and no data readig is required.|
|bits_per_pixel|Gets the image bits per pixel count.|
|bounds|Gets the object bounds.|
|container|  |
|height|Gets the image height.|
|palette|  |
|use_palette|  |
|size|Gets the object size.|
|width|Gets the image width.|
|interrupt_monitor|  |
|buffer_size_hint|  |
|auto_adjust_palette|  |
|has_background_color|  |
|file_format|Gets a value of file format|
|background_color|  |
|size_f|Gets the object size, in inches.|
|width_f|Gets the object width, in inches.|
|height_f|Gets the object height, in inches.|
|records|Gets or sets the records.|
|inch|Gets or sets the inch.|
|frame_bounds|Gets the frame bounds.|
## **Methods**
|**Name**|**Description**|
| :- | :- |
|save()|Saves the data.|
|save(file_path)|Saves the data.|
|save(file_path, options)|Saves the data.|
|save(file_path, options, bounds_rectangle)|Saves the data.|
|save(stream, options_base)|Saves the data.|
|save(stream, options_base, bounds_rectangle)|Saves the data.|
|save(stream)|Saves the data.|
|save(file_path, over_write)|Saves the data.|
|can_load(file_path)|  |
|can_load(file_path, load_options)|  |
|can_load(stream)|  |
|can_load(stream, load_options)|  |
|create(image_options, width, height)|  |
|create(images)|  |
|create(images, dispose_images)|  |
|get_file_format(file_path)|  |
|get_file_format(stream)|  |
|get_fitting_rectangle(rectangle, width, height)|  |
|get_fitting_rectangle(rectangle, pixels, width, height)|  |
|load(file_path, load_options)|  |
|load(file_path)|  |
|load(stream, load_options)|  |
|load(stream)|  |
|resize(new_width, new_height, resize_type)|Resizes the image.|
|resize(new_width, new_height, settings)|Resizes the image.|
|resize(new_width, new_height)|Resizes the image.|
|resize_width_proportionally(new_width)|  |
|resize_width_proportionally(new_width, resize_type)|  |
|resize_width_proportionally(new_width, settings)|  |
|resize_height_proportionally(new_height)|  |
|resize_height_proportionally(new_height, resize_type)|  |
|resize_height_proportionally(new_height, settings)|  |
|crop(rectangle)|Crops the specified rectangle.|
|crop(left_shift, right_shift, top_shift, bottom_shift)|Crops the specified rectangle.|
|cache_data()|Caches the data and ensures no additional data loading will be performed from the underlying<br/>                [data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/).|
|save_to_stream(stream)|  |
|can_load_with_options(file_path, load_options)|  |
|can_load_stream(stream)|  |
|can_load_stream_with_options(stream, load_options)|  |
|get_file_format_of_stream(stream)|  |
|load_with_options(file_path, load_options)|  |
|load_stream_with_options(stream, load_options)|  |
|load_stream(stream)|  |
|can_save(options)|  |
|resize_by_type(new_width, new_height, resize_type)|Resizes the image.|
|resize_by_settings(new_width, new_height, settings)|Resizes the image.|
|get_default_options(args)|Gets the default options.|
|get_original_options()|  |
|resize_width_proportionally_settings(new_width, settings)|  |
|resize_height_proportionally_settings(new_height, settings)|  |
|rotate_flip(rotate_flip_type)|Rotates, flips, or rotates and flips the image.|
|save_with_options(file_path, options)|  |
|save_with_options_rect(file_path, options, bounds_rectangle)|  |
|save_to_stream_with_options(stream, options_base)|  |
|save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)|  |
|set_palette(palette, update_colors)|Sets the image palette.|
|get_proportional_width(width, height, new_height)|  |
|get_proportional_height(width, height, new_width)|  |
|get_embedded_images()|  |
|get_used_fonts()|Returns the list of font which used inside metafile.|
|get_missed_fonts()|Returns the list of fonts which used inside metafile but not found.|
|resize_canvas(new_rectangle)|Resizes the canvas.|
|add_record(record)|Adds the record.|
|get_post_script()|Gets the post script.|
