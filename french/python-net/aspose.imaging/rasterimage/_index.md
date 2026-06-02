---
title: "Classe RasterImage"
type: docs
weight: 7060
url: /fr/python-net/aspose.imaging/rasterimage/
---

**Summary:** Represents a raster image supporting raster graphics operations.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.RasterImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, Image

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| bits_per_pixel | int | r | Obtient le nombre de bits par pixel de l'image. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient les limites de l'image. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtient le conteneur [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtient le flux de données de l'objet. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit les données Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtient une valeur du format de fichier |
| [has_alpha](#has_alpha1) | bool | r | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| has_background_color | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| has_transparent_color | bool | r/w | Obtient ou définit une valeur indiquant si cette instance [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) possède une couleur transparente. |
| height | int | r | Obtient la hauteur de l'image. |
| horizontal_resolution | float | r/w | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Obtient l'opacité de cette image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| is_cached | bool | r | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| is_raw_data_available | bool | r | Obtient une valeur indiquant si le chargement de données brutes est disponible. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtient les métadonnées de l’image. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| [premultiply_components](#premultiply_components2) | bool | r/w | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtient ou définit le convertisseur de couleur personnalisé |
| [raw_data_format](#raw_data_format3) | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le format des données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtient les paramètres actuels des données brutes. Notez qu'en utilisant ces paramètres, les données se chargent sans conversion. |
| raw_fallback_index | int | r/w | Obtient ou définit l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtient ou définit le convertisseur de couleur indexée |
| raw_line_size | int | r | Obtient la taille de la ligne brute en octets. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtient la taille de l'image. |
| transparent_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient la couleur transparente de l'image. |
| update_xmp_data | bool | r/w | Obtient ou définit une valeur indiquant s'il faut mettre à jour les métadonnées XMP. |
| use_palette | bool | r | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| use_raw_data | bool | r/w | Obtient ou définit une valeur indiquant s'il faut utiliser le chargement de données brutes lorsque le chargement de données brutes est disponible. |
| vertical_resolution | float | r/w | Obtient ou définit la résolution verticale, en pixels par pouce, de ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | r | Obtient la largeur de l'image. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit les données Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_1) | Ajustement de la luminosité de l’image. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_2) | Contraste d'image |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_3) | Correction gamma d'une image. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_4) | Correction gamma d'une image. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_5) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| auto_brightness_contrast() | Normalisation automatique adaptative de la luminosité et du contraste pour l'ensemble de l'image. |
| auto_rotate() | Fait pivoter automatiquement l'image en fonction des données d'orientation extraites des métadonnées Exif <br/>            . Cette méthode garantit que les images sont affichées dans la bonne orientation, <br/>            améliorant l'expérience utilisateur et éliminant le besoin d'ajustements manuels. En <br/>            analysant les informations Exif, l'image est pivotée en conséquence, offrant une expérience de visualisation fluide <br/>            sur différentes plateformes et appareils. Ce processus de rotation automatisé <br/>            simplifie la gestion des images et améliore l'utilisabilité globale, surtout lorsqu'<br/>            on traite de gros lots d'images avec des orientations variées. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_6) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_7) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_8) | Binarisation d'une image avec un seuil prédéfini |
| binarize_otsu() | Binarisation d'une image avec le seuillage d'Otsu |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_9) | Mélange cette instance d'image avec l'image _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_10) | Mélange cette instance d'image avec l'image _overlay_. |
| cache_data() | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué à partir du [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) sous-jacent. |
| [can_load(file_path)](#can_load_file_path_11) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_12) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_load(stream)](#can_load_stream_13) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load(stream, load_options)](#can_load_stream_load_options_14) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_stream(stream)](#can_load_stream_stream_15) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_16) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_17) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_save(options)](#can_save_options_18) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [create(files)](#create_files_19) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_20) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(image_options, width, height)](#create_image_options_width_height_21) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_22) | Crée une instance de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) à partir du tableau de pixels fourni.<br/>            <br/>            Vérifie que la largeur et la hauteur spécifiées correspondent aux dimensions des données de pixels.<br/>            Cette méthode ne peut être utilisée que lorsque la bibliothèque est en mode Licensed. |
| [create(images)](#create_images_23) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(images, dispose_images)](#create_images_dispose_images_24) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [create(multipage_create_options)](#create_multipage_create_options_25) | Crée les options de création multipage spécifiées. |
| [create_from_files(files)](#create_from_files_files_26) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_27) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_images(images)](#create_from_images_images_28) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_29) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_30) | Recadrer l'image avec des déplacements. |
| [crop(rectangle)](#crop_rectangle_31) | Recadre le rectangle spécifié. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_32) | Effectue un tramage sur l'image actuelle. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_33) | Effectue un tramage sur l'image actuelle. |
| [embed_digital_signature(password)](#embed_digital_signature_password_34) | Intégrer une signature numérique basée sur le mot de passe fourni dans l'image en utilisant la stéganographie. |
| [filter(rectangle, options)](#filter_rectangle_options_35) | Filtre le rectangle spécifié. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_36) | Obtient un pixel ARGB 32 bits d'une image. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_37) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [get_default_options(args)](#get_default_options_args_38) | Obtient les options par défaut. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_39) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_41) | Obtient le tableau de données brutes par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_42) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_43) | Obtient le format de fichier. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_44) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_45) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_46) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_modify_date(use_default)](#get_modify_date_use_default_47) | Obtient la date et l'heure de la dernière modification de l'image ressource. |
| [get_original_options()](#get_original_options__48) | Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre. |
| [get_pixel(x, y)](#get_pixel_x_y_49) | Obtient un pixel d'image. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_50) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_51) | Obtient une largeur proportionnelle. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_52) | Convertit en aps. |
| [get_skew_angle()](#get_skew_angle__53) | Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan. |
| grayscale() | Transformation d'une image en sa représentation en niveaux de gris |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_54) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |
| [load(file_path)](#load_file_path_55) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(file_path, load_options)](#load_file_path_load_options_56) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(stream)](#load_stream_57) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_58) | Charge une nouvelle image depuis le flux spécifié. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_59) | Charge des pixels ARGB 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_60) | Charge des pixels ARGB 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_61) | Charge des pixels au format CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_62) | Charge des pixels au format CMYK.<br/>            Cette méthode est obsolète. Veuillez plutôt utiliser la méthode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63) | Charge partiellement les pixels ARGB 32 bits par paquets. |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64) | Charge partiellement des pixels ARGB 64 bits par paquets. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_65) | Charge partiellement des pixels par paquets. |
| [load_pixels(rectangle)](#load_pixels_rectangle_66) | Charge des pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67) | Charge des données brutes. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68) | Charge des données brutes. |
| [load_stream(stream)](#load_stream_stream_69) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_70) | Charge une nouvelle image depuis le flux spécifié. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_71) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| normalize_angle() | Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion de la numérisation.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_72) | Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/). |
| normalize_histogram() | Normalise l'histogramme de l'image — ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_73) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_74) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| remove_metadata() | Supprime les métadonnées de cette instance d'image en définissant la valeur de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) à **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_75) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_76) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_77) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_78) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha originale pour préserver des bords lisses.<br/>            Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_79) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha originale pour préserver des bords lisses.<br/>            Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [resize(new_width, new_height)](#resize_new_width_new_height_80) | Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_81) | Redimensionne l'image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_82) | Redimensionne l'image avec des options étendues. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_83) | Redimensionne l'image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_84) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_85) | Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_86) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_87) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_88) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_89) | Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_90) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_91) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_92) | Redimensionne la largeur proportionnellement. |
| [rotate(angle)](#rotate_angle_93) | Faire pivoter l'image autour du centre. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_94) | Faire pivoter l'image autour du centre. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_95) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_96) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_97) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_98) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_99) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_100) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(stream, options_base)](#save_stream_options_base_101) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_102) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_103) | Enregistre les pixels ARGB 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_104) | Enregistre les pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_105) | Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_106) | Enregistre les pixels. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_107) | Enregistre les données brutes. |
| [save_to_stream(stream)](#save_to_stream_stream_108) | Enregistre les données de l'objet dans le flux spécifié. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_109) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_111) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_112) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_113) | Définit un pixel d'image 32 bits ARGB pour la position spécifiée. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_114) | Définit la palette d'image. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_115) | Définit un pixel d'image pour la position spécifiée. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_116) | Définit la résolution pour ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_117) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente le type [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_119) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |


### Property: has_alpha {#has_alpha1}

Obtient une valeur indiquant si cette instance possède un canal alpha.

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...

**[Example # 2](#example_86)**: The following example shows how to extract information about raw data format ...


### Property: premultiply_components {#premultiply_components2}

Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés.

**See also:**

**[Example # 1](#example_37)**: The following example creates a new raster image, saves the specified semi-tr...


### Property: raw_data_format {#raw_data_format3}

Obtient le format des données brutes.

**See also:**

**[Example # 1](#example_38)**: The following example loads raster images and prints information about raw da...


### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_1}


```
 adjust_brightness(brightness) 
```

Ajustement de la luminosité de l’image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| luminosité | int | Valeur de luminosité. |


**See also:**

**[Example # 1](#example_57)**: The following example performs brightness correction of an image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_2}


```
 adjust_contrast(contrast) 
```

Contraste d'image

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| contraste | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**See also:**

**[Example # 1](#example_58)**: The following example performs contrast correction of an image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_3}


```
 adjust_gamma(gamma) 
```

Correction gamma d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**See also:**

**[Example # 1](#example_55)**: The following example performs gamma-correction of an image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_4}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Correction gamma d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma_red | float | Coefficient gamma pour le canal rouge |
| gamma_green | float | Coefficient gamma pour le canal vert |
| gamma_blue | float | Coefficient gamma pour le canal bleu |


**See also:**

**[Example # 1](#example_56)**: The following example performs gamma-correction of an image applying differen...


### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_5}


```
 analyze_percentage_digital_signature(password) 
```

Calcule le pourcentage de similarité entre les données extraites et le mot de passe original.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mot de passe | string | Le mot de passe utilisé pour extraire les données intégrées. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur de pourcentage de similarité. |



**See also:**

**[Example # 1](#example_234)**: The example illustrates how to determine the probability (from 0% to 100%) th...


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_6}


```
 binarize_bradley(brightness_difference) 
```

Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | float | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée autour de ce pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_7}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | float | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de s × s pixels centrée autour de ce pixel. |
| window_size | int | La taille de la fenêtre de pixels de s x s centrée autour de ce pixel |


**See also:**

**[Example # 1](#example_53)**: The following example binarizes a raster image with Bradley's adaptive thresh...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_8}


```
 binarize_fixed(threshold) 
```

Binarisation d'une image avec un seuil prédéfini

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| seuil | System.Byte | Valeur du seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de 255 lui sera attribuée, sinon 0. |


**See also:**

**[Example # 1](#example_51)**: The following example binarizes a raster image with the predefined threshold....


### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_9}


```
 blend(origin, overlay, overlay_alpha) 
```

Mélange cette instance d'image avec l'image _overlay_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de superposition. |
| overlay_alpha | System.Byte | L'alpha de superposition. |

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_10}


```
 blend(origin, overlay, overlay_area, overlay_alpha) 
```

Mélange cette instance d'image avec l'image _overlay_.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| origin | [Point](/imaging/python-net/aspose.imaging/point/) | L'origine du mélange de l'image d'arrière-plan. |
| overlay | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de superposition. |
| overlay_area | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | La zone de superposition. |
| overlay_alpha | System.Byte | L'alpha de superposition. |

### Method: can_load(file_path)  [static] {#can_load_file_path_11}


```
 can_load(file_path) 
```

Détermine si l'image peut être chargée depuis le chemin de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le fichier spécifié ; sinon, <c>false</c>. |


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_12}


```
 can_load(file_path, load_options) 
```

Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le fichier spécifié ; sinon, <c>false</c>. |


### Method: can_load(stream)  [static] {#can_load_stream_13}


```
 can_load(stream) 
```

Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_14}


```
 can_load(stream, load_options) 
```

Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_15}


```
 can_load_stream(stream) 
```

Détermine si l'image peut être chargée depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_16}


```
 can_load_stream_with_options(stream, load_options) 
```

Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux à charger. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le flux spécifié ; sinon, <c>false</c>. |


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_17}


```
 can_load_with_options(file_path, load_options) 
```

Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être chargée depuis le fichier spécifié ; sinon, <c>false</c>. |


### Method: can_save(options) {#can_save_options_18}


```
 can_save(options) 
```

Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <c>true</c> si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies ; sinon, <c>false</c>. |


### Method: create(files)  [static] {#create_files_19}


```
 create(files) 
```

Crée l'image multipage contenant les fichiers spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| files | string[] | Les fichiers. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image multipage |


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_20}


```
 create(files, throw_exception_on_load_error) 
```

Crée l'image multipage contenant les fichiers spécifiés.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| files | string[] | Les fichiers. |
| throw_exception_on_load_error | bool | si défini sur <c>true</c> [lancer une exception lors du chargement]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image multipage |


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_21}


```
 create(image_options, width, height) 
```

Crée une nouvelle image en utilisant les options de création spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image. |
| width | int | La largeur. |
| height | int | La hauteur. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image nouvellement créée. |


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_22}


```
 create(image_options, width, height, pixels) 
```

Crée une instance de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) à partir du tableau de pixels fourni.<br/>            <br/>            Vérifie que la largeur et la hauteur spécifiées correspondent aux dimensions des données de pixels.<br/>            Cette méthode ne peut être utilisée que lorsque la bibliothèque est en mode Licensed.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options utilisées pour créer le [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| width | int | La largeur du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| height | int | La hauteur du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| pixels | int[] | Le tableau des valeurs de pixels utilisé pour remplir l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | Une [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) remplie avec les données de pixels fournies. |


### Method: create(images)  [static] {#create_images_23}


```
 create(images) 
```

Crée une nouvelle image en utilisant les images spécifiées comme pages

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Les images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image en tant que IMultipageImage |


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_24}


```
 create(images, dispose_images) 
```

Crée une nouvelle image à partir des images spécifiées en tant que pages.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Les images. |
| dispose_images | bool | si défini sur <c>true</c> [supprimer les images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image en tant que IMultipageImage |


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_25}


```
 create(multipage_create_options) 
```

Crée les options de création multipage spécifiées.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| multipage_create_options | [MultipageCreateOptions](/imaging/python-net/aspose.imaging.imageoptions/multipagecreateoptions/) | Les options de création multipage. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image multipage |


### Method: create_from_files(files)  [static] {#create_from_files_files_26}


```
 create_from_files(files) 
```

Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| files | string[] | Les fichiers. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image multipage |


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_27}


```
 create_from_files(files, throw_exception_on_load_error) 
```

Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| files | string[] | Les fichiers. |
| throw_exception_on_load_error | bool | si défini sur <c>true</c> lancer une exception en cas d'erreur de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image multipage |


### Method: create_from_images(images)  [static] {#create_from_images_images_28}


```
 create_from_images(images) 
```

Crée une nouvelle image en utilisant les images spécifiées comme pages

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Les images. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image en tant que IMultipageImage |


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_29}


```
 create_from_images(images, dispose_images) 
```

Crée une nouvelle image à partir des images spécifiées en tant que pages.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| images | [Image[]](/imaging/python-net/aspose.imaging/image/) | Les images. |
| dispose_images | bool | si défini sur <c>true</c> [supprimer les images]. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'Image en tant que IMultipageImage |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_30}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Recadrer l'image avec des déplacements.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| left_shift | int | Le décalage à gauche. |
| right_shift | int | Le décalage à droite. |
| top_shift | int | Le décalage supérieur. |
| bottom_shift | int | Le décalage inférieur. |


**See also:**

**[Example # 1](#example_50)**: The following example crops a raster image. The cropping area is specified vi...


### Method: crop(rectangle) {#crop_rectangle_31}


```
 crop(rectangle) 
```

Recadre le rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |


**See also:**

**[Example # 1](#example_49)**: The following example crops a raster image. The cropping area is be specified...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_32}


```
 dither(dithering_method, bits_count) 
```

Effectue un tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |


**See also:**

**[Example # 1](#example_39)**: The following example loads a raster image and performs threshold and Floyd d...


### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_33}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Effectue un tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personnalisée pour le dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_34}


```
 embed_digital_signature(password) 
```

Intégrer une signature numérique basée sur le mot de passe fourni dans l'image en utilisant la stéganographie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mot de passe | string | Le mot de passe utilisé pour générer les données de signature numérique. |


**See also:**

**[Example # 1](#example_232)**: The example shows how to embed digital signature based on provided password i...


### Method: filter(rectangle, options) {#filter_rectangle_options_35}


```
 filter(rectangle, options) 
```

Filtre le rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Les options. |


**See also:**

**[Example # 1](#example_59)**: The following example applies various types of filters to a raster image.


### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_36}


```
 get_argb_32_pixel(x, y) 
```

Obtient un pixel ARGB 32 bits d'une image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le pixel ARGB 32 bits pour l'emplacement spécifié. |



**See also:**

**[Example # 1](#example_36)**: The following example shows how image caching affects performance. In general...

**[Example # 2](#example_40)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_37}


```
 get_default_argb_32_pixels(rectangle) 
```

Obtient le tableau de pixels ARGB 32 bits par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de pixels par défaut. |


### Method: get_default_options(args) {#get_default_options_args_38}


```
 get_default_options(args) 
```

Obtient les options par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | System.Object | Les arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Options par défaut |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_39}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les pixels. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Le chargeur partiel de pixels. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_40}


```
 get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) 
```

Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les pixels. |
| partial_raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Le chargeur partiel de données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes. |

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_41}


```
 get_default_raw_data(rectangle, raw_data_settings) 
```

Obtient le tableau de données brutes par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes. |

**Returns**

| Type | Description |
| :- | :- |
| System.Byte | Le tableau de données brutes par défaut. |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_42}


```
 get_file_format(file_path) 
```

Obtient le format de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Le format de fichier déterminé. |


### Method: get_file_format(stream)  [static] {#get_file_format_stream_43}


```
 get_file_format(stream) 
```

Obtient le format de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Le format de fichier déterminé. |


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_44}


```
 get_file_format_of_stream(stream) 
```

Obtient le format de fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

**Returns**

| Type | Description |
| :- | :- |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | Le format de fichier déterminé. |


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_45}


```
 get_fitting_rectangle(rectangle, pixels, width, height) 
```

Obtient le rectangle qui correspond à l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir le rectangle d'ajustement. |
| pixels | int[] | Les pixels ARGB 32 bits. |
| width | int | La largeur de l'objet. |
| height | int | La hauteur de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle d'ajustement ou une exception si aucun rectangle d'ajustement ne peut être trouvé. |


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_46}


```
 get_fitting_rectangle(rectangle, width, height) 
```

Obtient le rectangle qui correspond à l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir le rectangle d'ajustement. |
| width | int | La largeur de l'objet. |
| height | int | La hauteur de l'objet. |

**Returns**

| Type | Description |
| :- | :- |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle d'ajustement ou une exception si aucun rectangle d'ajustement ne peut être trouvé. |


### Method: get_modify_date(use_default) {#get_modify_date_use_default_47}


```
 get_modify_date(use_default) 
```

Obtient la date et l'heure de la dernière modification de l'image ressource.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| use_default | bool | si défini sur <c>true</c> utilise les informations de FileInfo comme valeur par défaut. |

**Returns**

| Type | Description |
| :- | :- |
| System.DateTime | La date et l'heure de la dernière modification de l'image de la ressource. |


### Method: get_original_options() {#get_original_options__48}


```
 get_original_options() 
```

Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options basées sur les paramètres du fichier original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_49}


```
 get_pixel(x, y) 
```

Obtient un pixel d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |

**Returns**

| Type | Description |
| :- | :- |
| [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du pixel pour l'emplacement spécifié. |



**See also:**

**[Example # 1](#example_41)**: The following example loads a raster image and obtains the color of an arbitr...


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_50}


```
 get_proportional_height(width, height, new_width) 
```

Obtient une hauteur proportionnelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur. |
| height | int | La hauteur. |
| new_width | int | La nouvelle largeur. |

**Returns**

| Type | Description |
| :- | :- |
| int | La hauteur proportionnelle. |


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_51}


```
 get_proportional_width(width, height, new_height) 
```

Obtient une largeur proportionnelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | int | La largeur. |
| height | int | La hauteur. |
| new_height | int | La nouvelle hauteur. |

**Returns**

| Type | Description |
| :- | :- |
| int | La largeur proportionnelle. |


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_52}


```
 get_serialized_stream(image_options, clipping_rectangle, page_number) 
```

Convertit en aps.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image_options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image. |
| clipping_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle de découpage. |
| page_number | int[] | Le numéro de page. |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom | Le flux sérialisé |


### Method: get_skew_angle() {#get_skew_angle__53}


```
 get_skew_angle() 
```

Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan.

**Returns**

| Type | Description |
| :- | :- |
| float | L'angle d'inclinaison, en degrés. |


### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_54}


```
 is_digital_signed(password, percentage_threshold) 
```

Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mot de passe | string | Le mot de passe pour vérifier la signature. |
| percentage_threshold | int | Le seuil (en pourcentage)[0-100] qui détermine si l'image est considérée comme signée.<br/>            Si non spécifié, un seuil par défaut (<c>75</c>) sera appliqué. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si l'image est signée, sinon faux. |



**See also:**

**[Example # 1](#example_231)**: The example shows how to validate that the embedded digital signature matches...

**[Example # 2](#example_233)**: The example demonstrates how to verify that the embedded digital signature ma...


### Method: load(file_path)  [static] {#load_file_path_55}


```
 load(file_path) 
```

Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier ou l'URL depuis lequel charger l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_56}


```
 load(file_path, load_options) 
```

Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier ou l'URL depuis lequel charger l'image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load(stream)  [static] {#load_stream_57}


```
 load(stream) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load(stream, load_options)  [static] {#load_stream_load_options_58}


```
 load(stream, load_options) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_59}


```
 load_argb_32_pixels(rectangle) 
```

Charge des pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de pixels ARGB 32 bits chargé. |



**See also:**

**[Example # 1](#example_43)**: The following example shows how to load and process pixels of a raster image....


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_60}


```
 load_argb_64_pixels(rectangle) 
```

Charge des pixels ARGB 64 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau de pixels ARGB 64 bits chargé. |



**See also:**

**[Example # 1](#example_44)**: The following example shows how to load and process pixels of a raster image....


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_61}


```
 load_cmyk_32_pixels(rectangle) 
```

Charge des pixels au format CMYK.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Les pixels CMYK chargés présentés sous forme de valeurs entières 32 bits. |


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_62}


```
 load_cmyk_pixels(rectangle) 
```

Charge des pixels au format CMYK.<br/>            Cette méthode est obsolète. Veuillez plutôt utiliser la méthode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le tableau de pixels CMYK chargé. |


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_63}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Charge partiellement les pixels ARGB 32 bits par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle souhaité. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Le chargeur de pixels ARGB 32 bits. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_64}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Charge partiellement des pixels ARGB 64 bits par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle souhaité. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_65}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Charge partiellement des pixels par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle souhaité. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Le chargeur de pixels. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_66}


```
 load_pixels(rectangle) 
```

Charge des pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau de pixels chargé. |



**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_45)**: The following example shows how to load and process pixels of a raster image....


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_67}


```
 load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) 
```

Charge des données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les données brutes. |
| dest_image_bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Les limites de l'image de destination. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas dans le format spécifié, une conversion des données sera effectuée. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Le chargeur de données brutes. |

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_68}


```
 load_raw_data(rectangle, raw_data_settings, raw_data_loader) 
```

Charge des données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes à utiliser pour les données chargées. Notez que si les données ne sont pas dans le format spécifié, une conversion des données sera effectuée. |
| raw_data_loader | [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Le chargeur de données brutes. |

### Method: load_stream(stream)  [static] {#load_stream_stream_69}


```
 load_stream(stream) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_70}


```
 load_stream_with_options(stream, load_options) 
```

Charge une nouvelle image depuis le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux depuis lequel charger l'image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_71}


```
 load_with_options(file_path, load_options) 
```

Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier ou l'URL depuis lequel charger l'image. |
| load_options | [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Les options de chargement. |

**Returns**

| Type | Description |
| :- | :- |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image chargée. |


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_72}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion du scan.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | si défini sur <c>true</c> votre taille d'image sera modifiée selon les projections du rectangle tourné (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |


**See also:**

**[Example # 1](#example_184)**: Skew is an artifact that might appear during document scanning process when t...


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_73}


```
 read_argb_32_scan_line(scan_line_index) 
```

Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns**

| Type | Description |
| :- | :- |
| int[] | Le tableau des valeurs de couleur ARGB 32 bits de la ligne de numérisation. |


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_74}


```
 read_scan_line(scan_line_index) 
```

Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |

**Returns**

| Type | Description |
| :- | :- |
| [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau des valeurs de couleur des pixels de la ligne de numérisation. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_75}


```
 replace_argb(old_color_argb, old_color_diff, new_color_argb) 
```

Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Valeur ARGB de l'ancienne couleur à remplacer. |
| old_color_diff | System.Byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| new_color_argb | int | Nouvelle valeur ARGB de couleur pour remplacer l'ancienne couleur. |

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_76}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) | Ancienne couleur à remplacer. |
| old_color_diff | System.Byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nouvelle couleur avec laquelle remplacer l'ancienne couleur. |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_77}


```
 replace_color(old_color_argb, old_color_diff, new_color_argb) 
```

Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| old_color_argb | int | Valeur ARGB de l'ancienne couleur à remplacer. |
| old_color_diff | System.Byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| new_color_argb | int | Nouvelle valeur ARGB de couleur pour remplacer l'ancienne couleur. |

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_78}


```
 replace_non_transparent_colors(new_color) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha originale pour préserver des bords lisses.<br/>            Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) | Nouvelle couleur avec laquelle remplacer les couleurs non transparentes. |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_79}


```
 replace_non_transparent_colors(new_color_argb) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et conserve la valeur alpha originale pour préserver des bords lisses.<br/>            Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_argb | int | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_80}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_81}


```
 resize(new_width, new_height, resize_type) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Le type de redimensionnement. |


**See also:**

**[Example # 1](#example_61)**: This example loads a raster image and resizes it using various resizing methods.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_82}


```
 resize(new_width, new_height, settings) 
```

Redimensionne l'image avec des options étendues.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement. |


**See also:**

**[Example # 1](#example_62)**: This example loads a raster image and resizes it using various resizing setti...


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_83}


```
 resize_by_settings(new_width, new_height, settings) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement. |

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_84}


```
 resize_by_type(new_width, new_height, resize_type) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Le type de redimensionnement. |

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_85}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_86}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_87}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_88}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_89}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_90}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_91}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_92}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle) {#rotate_angle_93}


```
 rotate(angle) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_94}


```
 rotate(angle, resize_proportionally, background_color) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resize_proportionally | bool | si défini sur <c>true</c> votre taille d'image sera modifiée selon les projections du rectangle tourné (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_95}


```
 rotate_flip(rotate_flip_type) 
```

Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Type de la rotation et du retournement. |

### Method: save(file_path) {#save_file_path_96}


```
 save(file_path) 
```

Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer l'image. |

### Method: save(file_path, options) {#save_file_path_options_97}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_98}


```
 save(file_path, options, bounds_rectangle) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Method: save(file_path, over_write) {#save_file_path_over_write_99}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_100}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save(stream, options_base) {#save_stream_options_base_101}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_102}


```
 save(stream, options_base, bounds_rectangle) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_103}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Enregistre les pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Le tableau de pixels ARGB 32 bits. |


**See also:**

**[Example # 1](#example_46)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_104}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Enregistre les pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |


**See also:**

**[Example # 1](#example_48)**: The following example fills the central area of a raster image with black pix...


### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_105}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le tableau de pixels CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_106}


```
 save_pixels(rectangle, pixels) 
```

Enregistre les pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau de pixels. |


**See also:**

**[Example # 1](#example_7)**: This example shows how to load a pixels information in an array of Color, man...

**[Example # 2](#example_47)**: The following example fills the central area of a raster image with black pix...


### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_107}


```
 save_raw_data(data, data_offset, rectangle, raw_data_settings) 
```

Enregistre les données brutes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| données | System.Byte | Les données brutes. |
| data_offset | int | Le décalage de départ des données brutes. |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes dans lesquelles les données se trouvent. |

### Method: save_to_stream(stream) {#save_to_stream_stream_108}


```
 save_to_stream(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_109}


```
 save_to_stream_with_options(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_110}


```
 save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites source. |

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_111}


```
 save_with_options(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_112}


```
 save_with_options_rect(file_path, options, bounds_rectangle) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |
| bounds_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle des limites de l'image de destination. Définissez le rectangle vide pour utiliser les limites de la source. |

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_113}


```
 set_argb_32_pixel(x, y, argb_32_color) 
```

Définit un pixel d'image 32 bits ARGB pour la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| argb_32_color | int | Le pixel ARGB 32 bits pour la position spécifiée. |


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_114}


```
 set_palette(palette, update_colors) 
```

Définit la palette d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_115}


```
 set_pixel(x, y, color) 
```

Définit un pixel d'image pour la position spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | L'emplacement x du pixel. |
| y | int | L'emplacement y du pixel. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du pixel pour la position spécifiée. |


**See also:**

**[Example # 1](#example_42)**: The following example loads a raster image, and sets the color of an arbitrar...


### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_116}


```
 set_resolution(dpi_x, dpi_y) 
```

Définit la résolution pour ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dpi_x | float | La résolution horizontale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La résolution verticale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_117}


```
 try_set_metadata(metadata) 
```

Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente le type [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Les métadonnées. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai, si l'instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente le type [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) ; sinon, faux. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_118}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| argb_32_pixels | int[] | Le tableau de couleurs ARGB 32 bits à écrire. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_119}


```
 write_scan_line(scan_line_index, pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Le tableau de couleurs de pixels à écrire. |

## **Examples**
### This example shows how to load a pixels information in an array of Color, manipulates the array and set it back to the image. To perform these operations, this example creates a new Image file (in GIF format) using MemoryStream object. {#example_7}
``` python

from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.externsions import StreamExtensions as strm_ext
from aspose.imaging.imageoptions import GifOptions
from aspose.imaging.sources import StreamSource

# Créer une instance de MemoryStream
with strm_ext.create_memory_stream() as stream:
	#Créez une instance de GifOptions et définissez ses différentes propriétés, y compris la propriété Source
	with GifOptions() as gifOptions:
		gifOptions.source = StreamSource(stream)

		# Créez une instance de Image
		with as_of(Image.create(gifOptions, 500, 500), RasterImage) as image:
			# Obtenez les pixels de l'image en spécifiant la zone comme la bordure de l'image
			pixels = image.load_pixels(image.bounds)

			yellow_color = Color.yellow
			blue_color = Color.blue
			#Parcourez le tableau et définissez la couleur des pixels indexés alternés
			for index in range(pixel.length):
				if index % 2 == 0:
					#Définissez la couleur du pixel indexé sur jaune
					pixels[index] = yellow_color
				else:
					#Définissez la couleur du pixel indexé sur bleu
					pixels[index] = blue_color

			#Appliquez les modifications de pixels à l'image
			image.save_pixels(image.bounds, pixels)

			# enregistrez toutes les modifications.
			image.save()

	# Écrire MemoryStream dans un fichier
	stream.seek(0)
	with open(r"C:\temp\output.gif", "wb") as fileStream:
		fileStream.write(stream.read())
}

```

### The following example shows how image caching affects performance. In general case, reading cached data is performed faster than reading non-cached data. {#example_36}
``` python
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from os.path import join as path_join

directory = r"c:\temp"

# Chargez une image à partir d'un fichier PNG.
with Image.load(path_join(directory, "sample.png")) as image:
	# Mettez en cache toutes les données de pixels afin qu'aucun chargement de données supplémentaire ne soit effectué depuis le flux de données sous-jacent
	image.cache_daata()

	start_time = timedelta()

	# Lire tous les pixels est assez rapide.
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)
			
	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all cached pixels took {time} ms.")


# Charger une image à partir d'un fichier PNG
with Image.load(path_join(directory, "sample.png")) as image:
	start_time = timedelta()

	# Lire tous les pixels n'est pas aussi rapide qu'avec la mise en cache
	rasterImage = as_of(image, RasterImage)
	for y in range(image.height):
		for x in range(image.width):
			color = rasterImage.get_argb_32_pixel(x, y)

	end_time = timedelta()
	time = (end_time.microseconds - start_time.microseconds) / 1000000
	print(f"Reading all pixels without preliminary caching took {time} ms.")

# La sortie peut ressembler à ceci :
# La lecture de tous les pixels mis en cache a pris 1500 ms.
# La lecture de tous les pixels sans mise en cache préliminaire a pris 150000 ms.


```

### The following example creates a new raster image, saves the specified semi-transparent pixels, then loads those pixels and gets final colors in the premultiplied form. {#example_37}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.sources import StreamSource
from aspose.imaging.fileformats.png import PngColorType

image_width = 3
image_height = 2

colors = [
	Color.from_argb(127, 255, 0, 0),
	Color.from_argb(127, 0, 255, 0),
	Color.from_argb(127, 0, 0, 255),
	Color.from_argb(127, 255, 255, 0),
	Color.from_argb(127, 255, 0, 255),
	Color.from_argb(127, 0, 255, 255)
]

create_options = PngOptions()
create_options.source = StreamSource()
create_options.color_type = PngColorType.TRUECOLOR_WITH_ALPHA

with Image.create(create_options, image_width, image_height) as image:
	raster_image = as_of(image, RasterImage)

	# Enregistrer les pixels pour l'image entière.
	raster_image.save_pixels(raster_image.bounds, colors)

	# Les pixels sont stockés dans l'image originale sous forme non prémultipliée.
	# Il faut spécifier explicitement l'option correspondante pour obtenir les composantes de couleur prémultipliées.
	# Les composantes de couleur prémultipliées sont calculées par les formules :
	# red = original_red * alpha / 255;
	# green = original_green * alpha / 255;
	# blue = original_blue * alpha / 255;
	raster_image.premultiply_components = True
	premultiplied_colors = raster_image.load_pixels(raster_image.bounds)
	for i in range(len(colors)):
		print(f"Original color: {colors[i]}")
		print(f"Premultiplied color: {premultiplied_colors[i]}")


```

### The following example loads raster images and prints information about raw data format and alpha channel. {#example_38}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

# Les fichiers image à charger.
fileNames = (r"c:\temp\sample.bmp", r"c:\temp\alpha.png")

for fileName in fileNames:
	with Image.load(fileName) as image:
		raster_image = as_of(image, RasterImage)
		print(f"ImageFile={fileName}, FileFormat={raster_image.raw_data_format}, HasAlpha={raster_image.has_alpha}")

# La sortie peut ressembler à ceci :
# ImageFile=c:\temp\sample.bmp, FileFormat=Rgb24Bpp, used channels: 8,8,8, HasAlpha=False
# ImageFile=c:\temp\alpha.png, FileFormat=RGBA32Bpp, used channels: 8,8,8,8, HasAlpha=True

```

### The following example loads a raster image and performs threshold and Floyd dithering using different palette depth. {#example_39}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, DitheringMethod
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Effectuez le tramage par seuillage en utilisant une palette de couleurs 4 bits contenant 16 couleurs.
	# Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
	# Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
	rasterImage.dither(DitheringMethod.THRESHOLD_DITHERING, 4)

	rasterImage.save(join_path(directory, "sample.ThresholdDithering4.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)

	# Effectuez le tramage Floyd en utilisant une palette de couleurs 1 bit contenant seulement 2 couleurs - noir et blanc.
	# Plus le nombre de bits spécifié est élevé, meilleure est la qualité et plus grande est la taille de l'image de sortie.
	# Notez que seules les palettes de 1 bit, 4 bits et 8 bits sont prises en charge pour le moment.
	rasterImage.dither(DitheringMethod.FLOYD_STEINBERG_DITHERING, 1)
	rasterImage.save(join_path(directory, "sample.FloydSteinbergDithering1.png"))


```

### The following example loads a raster image and obtains the color of an arbitrary pixel represented as a 32-bit integer value. {#example_40}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)

	# Obtenez une représentation entière de la couleur du pixel en haut à gauche de l'image.
	color = rasterImage.get_argb_32_pixel(0, 0)

	# Pour obtenir les valeurs des composantes de couleur individuelles, décalez la valeur de couleur d'un nombre de bits correspondant
	alpha = (color >> 24) & 0xff
	red = (color >> 16) & 0xff
	green = (color >> 8) & 0xff
	blue = (color >> 0) & 0xff

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image and obtains the color of an arbitrary pixel. {#example_41}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# Obtenez la couleur du pixel en haut à gauche de l'image.
	color = rasterImage.get_pixel(0, 0)

	# Obtenez les valeurs des composantes de couleur individuelles
	alpha = color.a
	red = color.r
	green = color.g
	blue = color.b

	print(f"The color of the pixel(0,0) is A={alpha},R={red},G={green},B={blue}")


```

### The following example loads a raster image, and sets the color of an arbitrary pixel. {#example_42}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Color

with Image.load("sample.png") as image:
	rasterImage = as_of(image, RasterImage)
	# Définit la couleur du pixel en haut à gauche.
	rasterImage.set_argb_32_pixel(0, 0, Color.aqua.to_argb())
	# Une autre façon consiste à transmettre directement une instance de aspose.imaging.Color
	rasterImage.set_pixel(0, 0, Color.aqua)


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 32-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_43}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)

	# Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode aspose.imaging.RasterImage.load_argb_32_pixels(rectangle).
	pixels = rasterImage.load_argb_32_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		alpha = (pixel >> 24) & 0xff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. The pixels are represented as 64-bit integer values. For example, consider a problem of counting of fully transparent pixels of an image. {#example_44}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("16rgba.png") as image:
	rasterImage = as_of(image, RasterImage)
	# Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode aspose.imaging.RasterImage.load_argb_64_pixels.
	# Notez que l'image elle-même doit avoir 16 bits par échantillon, car aspose.imaging.RasterImage.load_argb_64_pixels ne fonctionne pas avec 8 bits par échantillon.
	# Pour travailler avec 8 bits par échantillon, veuillez utiliser la bonne vieille méthode aspose.imaging.RasterImage.load_argb_64_pixels.
	pixels = rasterImage.load_argb_64_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		# Notez que tous les composants de couleur, y compris l'alpha, sont représentés par des valeurs sur 16 bits, de sorte que leurs valeurs autorisées se situent dans la plage [0, 63535].
		alpha = (pixel >> 48) & 0xffff
		if alpha == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example shows how to load and process pixels of a raster image. For example, consider a problem of counting of fully transparent pixels of an image. {#example_45}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage

with Image.load("alpha.png") as image:
	rasterImage = as_of(image, RasterImage)
	# Chargez les pixels pour l'image entière. Toute partie rectangulaire de l'image peut être spécifiée comme paramètre de la méthode aspose.imaging.RasterImage.load_pixels.
	pixels = rasterImage.load_pixels(rasterImage.bounds)

	count = 0
	for pixel in pixels:
		if pixel.a == 0:
			count += 1

	print(f"The number of fully transparent pixels is {count}")
	print(f"The total number of pixels is {image.width * image.height}")


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_argb_32_pixels method. {#example_46}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Le carré noir
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black.to_argb()
	pixels = [black_color] * pixel_count

	# Dessinez le carré noir au centre de l'image.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_argb_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveArgb32Pixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_pixels method. {#example_47}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Le carré noir
	pixel_count = ((rasterImage.width // 2) * (rasterImage.height // 2))
	black_color = Color.black
	pixels = [black_color] * pixel_count

	# Dessinez le carré noir au centre de l'image.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SavePixels.png"))


```

### The following example fills the central area of a raster image with black pixels using the aspose.imaging.RasterImage.save_cmyk_32_pixels method. {#example_48}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color, CmykColorHelper
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Obtenez une représentation entière du noir dans l'espace colorimétrique CMYK.
	blackCmyk = CmykColorHelper.to_cmyk(Color.black)
	# Le carré noir.
	pixel_count = (rasterImage.width // 2) * (rasterImage.height // 2)
	pixels = [blackCmyk] * pixel_count
	# Dessinez le carré noir au centre de l'image.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.save_cmyk_32_pixels(area, pixels)

	rasterImage.save(join_path(directory, "sample.SaveCmyk32Pixels.png"))


```

### The following example crops a raster image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_49}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
	area = Rectangle(rasterImage.width // 4, rasterImage.height // 4, rasterImage.width // 2, rasterImage.height // 2)
	rasterImage.crop(area)
	# Enregistrez l'image recadrée au format PNG
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example crops a raster image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_50}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, Rectangle, Color
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Recadrez à nouveau. Définissez une marge de 10% de la taille de l’image.
	horizontalMargin = rasterImage.width // 10
	verticalMargin = rasterImage.height // 10
	rasterImage.crop(horizontalMargin, horizontalMargin, verticalMargin, verticalMargin)
	# Enregistrez l’image recadrée au format PNG.
	rasterImage.save(join_path(directory, "sample.Crop.png"))


```

### The following example binarizes a raster image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_51}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Binarisez l’image avec une valeur de seuil de 127.
	# Si la valeur de gris correspondante d’un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
	rasterImage.binarize_fixed(127)
	rasterImage.save(join_path(directory, "sample.BinarizeFixed.png"))


```

### The following example binarizes a raster image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_53}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Binarisez l’image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d’une fenêtre de 10×10 pixels centrée sur ce pixel.
	rasterImage.binarize_bradley(5, 10)
	rasterImage.save(join_path(directory, "sample.BinarizeBradley5_10x10.png"))


```

### The following example performs gamma-correction of an image. {#example_55}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Définissez le coefficient gamma pour les canaux rouge, vert et bleu.
	rasterImage.adjust_gamma(2.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs gamma-correction of an image applying different coefficients for color components. {#example_56}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Définissez le coefficient gamma pour les canaux rouge, vert et bleu.
	rasterImage.adjust_gamma(1.5f, 2.5f, 3.5f)
	rasterImage.save(join_path(directory, "sample.AdjustGamma.png"))


```

### The following example performs brightness correction of an image. {#example_57}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
	rasterImage.adjust_brightness(50)
	rasterImage.save(join_path(directory, "sample.AdjustBrightness.png"))


```

### The following example performs contrast correction of an image. {#example_58}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
	rasterImage.adjust_contrast(50)
	rasterImage.save(join_path(directory, "sample.AdjustContrast.png"))


```

### The following example applies various types of filters to a raster image. {#example_59}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage
from aspose.imaging.imagefilters.filteroptions import *
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre médian avec une taille de rectangle de 5 à l'image entière.
	rasterImage.filter(rasterImage.bounds, MedianFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.MedianFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre de lissage bilatéral avec une taille de noyau de 5 à l'image entière.
	rasterImage.filter(rasterImage.bounds, BilateralSmoothingFilterOptions(5))
	rasterImage.save(join_path(directory, "sample.BilateralSmoothingFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre de flou gaussien avec un rayon de 5 et une valeur sigma de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, GaussianBlurFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussianBlurFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre Gauss-Wiener avec un rayon de 5 et une valeur de lissage de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, GaussWienerFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.GaussWienerFilter.png"))

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre wiener de mouvement avec une longueur de 5, une valeur de lissage de 4,0 et un angle de 90,0 degrés à l'image entière.
	rasterImage.filter(rasterImage.bounds, MotionWienerFilterOptions(10, 1.0, 90.0))
	rasterImage.save(join_path(directory, "sample.MotionWienerFilter.png"))
}

with Image.load(join_path(directory, "sample.png")) as image:
	rasterImage = as_of(image, RasterImage)
	# Appliquez un filtre d'accentuation avec une taille de noyau de 5 et une valeur sigma de 4,0 à l'image entière.
	rasterImage.filter(rasterImage.bounds, SharpenFilterOptions(5, 4.0))
	rasterImage.save(join_path(directory, "sample.SharpenFilter.png"))


```

### This example loads a raster image and resizes it using various resizing methods. {#example_61}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ResizeType
from os.path import join as join_path

directory = r"c:\temp"

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# Agrandissez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(join_path(directory, "upsample.nearestneighbour.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# Réduisez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE);
	image.Save(dir + "downsample.nearestneighbour.gif");

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# Agrandissez de 2 fois en utilisant le rééchantillonnage bilinéaire.
	rasterImage.resize(image.width * 2, image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(join_path(directory, "upsample.bilinear.gif"))

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# Réduisez de 2 fois en utilisant le rééchantillonnage bilinéaire.
	rasterImage.resize(image.width // 2, image.height // 2, ResizeType.BILINEAR_RESAMPLE)
	image.Save(dir + "downsample.bilinear.gif");


```

### This example loads a raster image and resizes it using various resizing settings. {#example_62}
``` python
from aspose.pycore import as_of
from aspose.imaging import Image, RasterImage, ImageResizeSettings, ResizeType,\
	ImageFilterType, ColorQuantizationMethod, ColorCompareMethod
from os.path import join as join_path

directory = r"c:\temp"

resizeSettings = ImageResizeSettings()
# L'algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée et l'interpolation lanczos3.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# Le petit filtre rectangulaire
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# Le nombre de couleurs dans la palette.
resizeSettings.entries_count = 256
# La quantification des couleurs n'est pas utilisée
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE
# La méthode euclidienne
resizeSettings.color_compare_method = ColorCompareMethod.EUCLIDIAN

with Image.load(join_path(directory, "sample.gif")) as image:
	rasterImage = as_of(image, RasterImage)
	# Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
	rasterImage.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(join_path(directory, "downsample.adaptive.gif"))


```

### The following example shows how to extract information about raw data format and alpha channel from a BMP image. {#example_86}
``` python
from aspose.imaging.fileformats.bmp import BmpImage

# Créez une image BMP 32 bpp de 100 x 100 px.
with BmpImage(100, 100, 32, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))


# Créez une image BMP 24 bpp de 100 x 100 px.
with BmpImage(100, 100, 24, None) as bmp_image:
	print("FileFormat={0}, RawDataFormat={1}, HasAlpha={2}".format(bmp_image.file_format.name, bmp_image.raw_data_format, bmp_image.has_alpha))

# En général, le BMP ne prend pas en charge le canal alpha, donc la sortie ressemblera à ceci :
# FileFormat = BMP, RawDataFormat = Rgb32Bpp, canaux utilisés : 8,8,8,8, HasAlpha = False
# FileFormat = BMP, RawDataFormat = Rgb24Bpp, canaux utilisés : 8,8,8, HasAlpha = False

```

### Skew is an artifact that might appear during document scanning process when the text/images of the document get rotated at a slight angle. It can have various causes but the most common is that the paper get misplaced during a scan. Therefore, deskew is the process of detecting and fixing this issue on scanned files(i.e. bitmap) so deskewed documents will have the text/images correctly and horizontally adjusted. {#example_184}
``` python
from aspose.imaging import Image, RasterImage, Color
from aspose.pycore import as_of

dir_: str = "c:\\3567\\"
input_file_path: str = dir_ + "skewed.png"
output_file_path: str = dir_ + "skewed.out.png"
# Éliminez le scan incliné avec les paramètres par défaut
with as_of(Image.load(input_file_path), RasterImage) as image:
	# Redressement
	image.normalize_angle(False, Color.light_gray)
	image.save(output_file_path)


```

### The example shows how to validate that the embedded digital signature matches the provided password. {#example_231}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, -1)


```

### The example shows how to embed digital signature based on provided password into image pixel data. {#example_232}
``` python

from aspose.imaging import Image

image_file_path = "ball.png"
password = "veryStr0ngPassword"
with Image.load(image_file_path) as image:
	image.embed_digital_signature(password)
	image.save(output_path)


```

### The example demonstrates how to verify that the embedded digital signature matches the provided password against the specified probability threshold. {#example_233}
``` python

from aspose.imaging import Image
  
threshold = 100
with Image.load(output_path) as image:
	is_signed = image.is_digital_signed(password, threshold)


```

### The example illustrates how to determine the probability (from 0% to 100%) that an image contains a digital signature created with the specified password. {#example_234}
``` python

from aspose.imaging import Image

with Image.load(output_path) as image:
	signed_percentage = image.analyze_percentage_digital_signature(password)


```

