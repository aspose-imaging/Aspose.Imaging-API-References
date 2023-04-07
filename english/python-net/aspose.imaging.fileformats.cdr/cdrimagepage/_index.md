---
title: CdrImagePage Class
type: docs
weight: 20
url: /python-net/api-reference/aspose.imaging.fileformats.cdr/cdrimagepage/
---

The Cdr image page

**Namespace:** [aspose.imaging.fileformats.cdr](/imaging/python-net/api-reference/aspose.imaging.fileformats.cdr/)

**Full Class Name:** aspose.imaging.fileformats.cdr.CdrImagePage

**Assembly:**  Aspose.Imaging Version: 23.3.0

The CdrImagePage type exposes the following members:
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
|parent_image|Gets the parent image.|
|page_number|Gets the page number.|
|cdr_document|Gets or sets the CDR document.|
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
|cache_data()|Caches the data and ensures no additional data loading will be performed from the underlying [data_stream_container](/imaging/python-net/api-reference/aspose.imaging/datastreamsupporter/).|
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
|get_default_options(args)|  |
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
|is_multipage()|  |
|as_multipage()|  |
|get_embedded_images()|Gets the embedded images.|
