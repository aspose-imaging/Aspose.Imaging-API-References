---
title: "Classe ApngImage"
type: docs
weight: 20
url: /fr/python-net/aspose.imaging.fileformats.apng/apngimage/
---

**Summary:** The API for Animated PNG (Animated Portable Network Graphics) image file<br/>            format is a versatile solution for developers looking to integrate<br/>            animated content into their applications. This API offers extensive<br/>            control over frame settings, allowing users to define frame-specific<br/>            parameters, including loop duration and PNG file settings. With this<br/>            feature-rich tool, you can effortlessly manage and optimize the display<br/>            of APNG images, import and export images, enhancing the dynamic and<br/>            interactive aspects of your applications.

**Module:** [aspose.imaging.fileformats.apng](/imaging/python-net/aspose.imaging.fileformats.apng/)

**Full Name:** aspose.imaging.fileformats.apng.ApngImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ApngImage(options, width, height)](#ApngImage_options_width_height_1) | Commencez à travailler avec la classe [ApngImage](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) en initialisant<br/>            une nouvelle instance sans effort. Idéal pour les développeurs souhaitant démarrer<br/>            l'utilisation des objets ApngImage rapidement et efficacement dans leurs projets. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| auto_adjust_palette | bool | r/w | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| bits_per_pixel | int | r | Obtient le nombre de bits par pixel de l'image. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient les limites de l'objet. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtient le conteneur [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtient le flux de données de l'objet. |
| default_frame_time | int | r/w | Ajustez facilement la durée d'image par défaut pour créer de nouvelles images avec<br/>            cette propriété flexible. Idéal pour les développeurs cherchant à personnaliser le timing des images<br/>            efficacement dans leurs animations. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit l'instance Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Accédez rapidement aux informations sur le format de fichier avec cette propriété pratique.<br/>            Idéal pour les développeurs qui doivent récupérer facilement les détails du format<br/>            de leurs fichiers Apng. |
| has_alpha | bool | r | Obtient une valeur indiquant si cette instance possède un canal alpha. |
| has_background_color | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| has_transparent_color | bool | r/w | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| height | int | r | Obtient la hauteur de l'image. |
| horizontal_resolution | float | r/w | Obtient ou définit la résolution horizontale, en pixels par pouce, de ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| image_opacity | float | r | Obtient l'opacité de cette image. |
| interlaced | bool | r | Déterminez rapidement si cet objet [PngImage](/imaging/python-net/aspose.imaging.fileformats.png/pngimage/) est entrelacé<br/>            grâce à cette propriété pratique. Idéal pour les développeurs qui ont besoin de vérifier<br/>            facilement le statut d'entrelacement des images PNG. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| is_cached | bool | r | Obtient une valeur indiquant si les données de l'image sont actuellement en cache. |
| is_raw_data_available | bool | r | Obtient une valeur indiquant si le chargement de données brutes est pris en charge. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtient ou définit les données XMP à partir de la trame. |
| num_plays | int | r/w | Contrôlez sans effort le nombre de répétitions de votre animation avec cette<br/>            propriété polyvalente. Idéal pour les développeurs recherchant un contrôle précis du<br/>            comportement de l'animation, avec prise en charge de la boucle infinie lorsque la<br/>            valeur est égale à 0. |
| page_count | int | r | Récupérez facilement le nombre total de pages de votre fichier image avec cette propriété.<br/>            Idéal pour les développeurs ayant besoin d'un accès rapide aux informations de comptage des pages. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Accédez sans effort aux pages de votre image avec cette propriété pratique.<br/>            Idéal pour les développeurs cherchant un accès rapide et facile aux pages individuelles pour les manipuler. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| premultiply_components | bool | r/w | Obtient ou définit une valeur indiquant si les composants de l'image doivent être prémultipliés. |
| raw_custom_color_converter | [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | r/w | Obtient ou définit le convertisseur de couleur personnalisé |
| raw_data_format | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le format des données brutes. |
| raw_data_settings | [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | r | Obtient les paramètres actuels des données brutes. Notez qu'en utilisant ces paramètres, les données se chargent sans conversion. |
| raw_fallback_index | int | r/w | Obtient ou définit l'index de secours à utiliser lorsque l'index de la palette est hors limites |
| raw_indexed_color_converter | [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | r/w | Obtient ou définit le convertisseur de couleur indexée |
| raw_line_size | int | r | Obtient la taille de la ligne brute en octets. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtient la taille de l'objet. |
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
| [add_frame()](#add_frame__1) | Ajoutez facilement un nouveau cadre à la fin de votre collection de cadres avec cette<br/>            méthode simple. Idéal pour les développeurs souhaitant étendre leur<br/>            collection de cadres dynamiquement pour des animations avec des images multi-cadres.<br/>            Un nouveau cadre sera créé en fonction de la taille de l'image actuelle. |
| [add_frame(frame_image)](#add_frame_frame_image_2) | Élargissez sans effort votre collection de cadres en ajoutant un nouveau cadre à la fin<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à améliorer leurs<br/>            animations d'images multi-cadres dynamiquement.<br/>            Le contenu du nouveau cadre sera rempli à partir de l'image spécifiée. |
| [add_frame(frame_image, frame_time)](#add_frame_frame_image_frame_time_3) | Élargissez votre collection de cadres de manière fluide en ajoutant un nouveau cadre au<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à enrichir leurs<br/>            animations d'images multi-cadres.<br/>            Le contenu du nouveau cadre sera rempli à partir de l'image spécifiée. |
| [add_page(page)](#add_page_page_4) | Ajoutez une nouvelle page à l'image sans effort avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant étendre dynamiquement le contenu de leurs fichiers image. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Ajustez facilement la _luminosité_ de l'image avec cette méthode intuitive,<br/>            en utilisant le paramètre de luminosité spécifié. Idéal pour les développeurs cherchant à augmenter ou diminuer<br/>            la luminosité globale des images dynamiquement. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | Améliorez le contraste de [Image](/imaging/python-net/aspose.imaging/image/)<br/>            pour faire ressortir les détails avec cette méthode intuitive. Idéal pour les développeurs<br/>            cherchant à améliorer la clarté visuelle et l'impact de leurs images dynamiquement. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Appliquez une correction gamma à l'image en utilisant un coefficient à virgule flottante<br/>            avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis des couleurs<br/>            dans leurs images. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Effectuez une correction gamma sur l'image séparément pour les canaux rouge, vert et bleu<br/>            en utilisant des coefficients individuels avec cette méthode intuitive. Idéal pour les développeurs cherchant<br/>            à affiner l'équilibre des couleurs et à améliorer la qualité visuelle de leurs images. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| auto_brightness_contrast() | Effectue une normalisation automatique adaptative de la luminosité et du contraste pour l'image entière. |
| auto_rotate() | Fait pivoter automatiquement l'image en fonction des données d'orientation extraites des métadonnées Exif <br/>            . Cette méthode garantit que les images sont affichées dans la bonne orientation, <br/>            améliorant l'expérience utilisateur et éliminant le besoin d'ajustements manuels. En <br/>            analysant les informations Exif, l'image est pivotée en conséquence, offrant une expérience de visualisation fluide <br/>            sur différentes plateformes et appareils. Ce processus de rotation automatisé <br/>            simplifie la gestion des images et améliore l'utilisabilité globale, surtout lorsqu'<br/>            on traite de gros lots d'images avec des orientations variées. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Binarisez sans effort l'image en utilisant un seuil prédéfini avec cette<br/>            méthode intuitive. Idéal pour les développeurs cherchant à convertir les images en forme binaire,<br/>            les simplifiant pour un traitement ou une analyse ultérieure. |
| binarize_otsu() | Effectuez une binarisation de l'image en utilisant le seuillage d'Otsu avec cette méthode intuitive.<br/>            Idéal pour les développeurs cherchant à déterminer automatiquement le seuil optimal pour<br/>            convertir les images en forme binaire, améliorant leur clarté et leur adéquation pour une analyse ultérieure. |
| [blend(origin, overlay, overlay_alpha)](#blend_origin_overlay_overlay_alpha_13) | Mélange cette instance d'image avec l'image _overlay_. |
| [blend(origin, overlay, overlay_area, overlay_alpha)](#blend_origin_overlay_overlay_area_overlay_alpha_14) | Mélange cette instance d'image avec l'image _overlay_. |
| cache_data() | Met en cache les données privées. |
| [can_load(file_path)](#can_load_file_path_15) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_16) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_load(stream)](#can_load_stream_17) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load(stream, load_options)](#can_load_stream_load_options_18) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_stream(stream)](#can_load_stream_stream_19) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_20) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_21) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_save(options)](#can_save_options_22) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [create(files)](#create_files_23) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_24) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(image_options, width, height)](#create_image_options_width_height_25) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_26) | Crée une instance de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) à partir du tableau de pixels fourni.<br/>            <br/>            Vérifie que la largeur et la hauteur spécifiées correspondent aux dimensions des données de pixels.<br/>            Cette méthode ne peut être utilisée que lorsque la bibliothèque est en mode Licensed. |
| [create(images)](#create_images_27) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(images, dispose_images)](#create_images_dispose_images_28) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [create(multipage_create_options)](#create_multipage_create_options_29) | Crée les options de création multipage spécifiées. |
| [create_from_files(files)](#create_from_files_files_30) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_31) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_images(images)](#create_from_images_images_32) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_33) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_34) | Recadrez l'image tout en ajustant les déplacements de manière fluide avec cette méthode intuitive.<br/>            Idéal pour les développeurs recherchant un contrôle précis du processus de recadrage<br/>            afin de se concentrer sur des zones spécifiques de leurs images Apng. |
| [crop(rectangle)](#crop_rectangle_35) | Recadrez l'image sans effort pour vous concentrer sur des zones spécifiques avec cette méthode intuitive.<br/>            Parfait pour les développeurs souhaitant affiner dynamiquement la composition de leurs images. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_36) | Effectue un tramage sur l'image actuelle. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_37) | Appliquez facilement des effets de tramage à l'image actuelle avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant ajouter de la texture ou réduire le banding des couleurs dans leurs images. |
| [embed_digital_signature(password)](#embed_digital_signature_password_38) | Intégrez une signature numérique basée sur le mot de passe fourni dans chaque page de l'image. |
| [filter(rectangle, options)](#filter_rectangle_options_39) | Appliquez sans effort des filtres au rectangle spécifié de l'image avec cette<br/>            méthode intuitive. Parfait pour les développeurs cherchant à améliorer ou modifier des zones spécifiques. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_40) | Obtient un pixel ARGB 32 bits d'une image. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_41) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [get_default_options(args)](#get_default_options_args_42) | Récupérez les options par défaut sans effort avec cette méthode simple.<br/>            Idéal pour les développeurs recherchant un accès rapide aux paramètres d'image Apng par défaut. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_43) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_45) | Obtient le tableau de données brutes par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_46) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_47) | Obtient le format de fichier. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_48) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_49) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_50) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_modify_date(use_default)](#get_modify_date_use_default_51) | Obtenez rapidement la date et l'heure de la dernière modification de l'image ressource<br/>            avec cette méthode conviviale. Idéal pour les développeurs ayant besoin de suivre les changements<br/>            et de gérer efficacement les ressources. |
| [get_original_options()](#get_original_options__52) | Récupérez les options basées sur les paramètres du fichier original sans effort avec cette méthode intuitive.<br/>            Parfait pour les développeurs cherchant à accéder et à utiliser des paramètres qui correspondent aux caractéristiques<br/>            du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre. |
| [get_pixel(x, y)](#get_pixel_x_y_53) | Obtient un pixel d'image. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_54) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_55) | Obtient une largeur proportionnelle. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_56) | Convertit en aps. |
| [get_skew_angle()](#get_skew_angle__57) | Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan. |
| grayscale() | Transformez facilement l'image en sa représentation en niveaux de gris avec cette méthode intuitive.<br/>            Idéal pour les développeurs cherchant à convertir des images couleur en niveaux de gris, simplifiant leurs<br/>            processus de visualisation ou d'analyse. |
| [insert_frame(index)](#insert_frame_index_58) | Insérez sans effort une nouvelle trame dans votre collection de trames à l'index spécifié<br/>            avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis sur<br/>            l'agencement des trames dans leurs animations d'images multi-trames.<br/>            Une nouvelle trame sera créée en fonction de la taille de l'image actuelle. |
| [insert_frame(index, frame_image)](#insert_frame_index_frame_image_59) | Insère une nouvelle trame dans la collection de trames propre à l'index spécifié.<br/>            Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée. |
| [insert_frame(index, frame_image, frame_time)](#insert_frame_index_frame_image_frame_time_60) | Insère une nouvelle trame dans la collection de trames propre à l'index spécifié.<br/>            Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée. |
| [is_digital_signed(password, percentage_threshold)](#is_digital_signed_password_percentage_threshold_61) | Effectue une vérification rapide pour déterminer si l'image est signée numériquement, en utilisant le mot de passe fourni et le seuil. |
| [load(file_path)](#load_file_path_62) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(file_path, load_options)](#load_file_path_load_options_63) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(stream)](#load_stream_64) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_65) | Charge une nouvelle image depuis le flux spécifié. |
| [load_argb_32_pixels(rectangle)](#load_argb_32_pixels_rectangle_66) | Charge des pixels ARGB 32 bits. |
| [load_argb_64_pixels(rectangle)](#load_argb_64_pixels_rectangle_67) | Charge des pixels ARGB 64 bits. |
| [load_cmyk_32_pixels(rectangle)](#load_cmyk_32_pixels_rectangle_68) | Charge des pixels au format CMYK. |
| [load_cmyk_pixels(rectangle)](#load_cmyk_pixels_rectangle_69) | Charge des pixels au format CMYK.<br/>            Cette méthode est obsolète. Veuillez plutôt utiliser la méthode [RasterImage.load_cmyk_32_pixels(rectangle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [load_partial_argb_32_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70) | Charge partiellement des pixels ARGB 32 bits (par blocs). |
| [load_partial_argb_64_pixels(rectangle, partial_pixel_loader)](#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71) | Charge partiellement des pixels ARGB 64 bits par paquets. |
| [load_partial_pixels(desired_rectangle, pixel_loader)](#load_partial_pixels_desired_rectangle_pixel_loader_72) | Charge partiellement des pixels par paquets. |
| [load_pixels(rectangle)](#load_pixels_rectangle_73) | Charge des pixels. |
| [load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74) | Charge des données brutes. |
| [load_raw_data(rectangle, raw_data_settings, raw_data_loader)](#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75) | Charge des données brutes. |
| [load_stream(stream)](#load_stream_stream_76) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_77) | Charge une nouvelle image depuis le flux spécifié. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_78) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| normalize_angle() | Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion de la numérisation.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterImage.rotate(angle)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion de la numérisation.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/). |
| normalize_histogram() | Normalise l'histogramme de l'image — ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [pop_frame_at(index)](#pop_frame_at_index_80) | Supprimez et récupérez la trame à l'index spécifié de votre collection de trames<br/>            avec cette méthode intuitive. Parfait pour les développeurs recherchant une gestion efficace<br/>            des trames dans leurs animations. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_81) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_82) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| remove_all_frames() | Videz votre collection de trames en supprimant toutes les trames avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant réinitialiser ou rafraîchir leurs animations. |
| [remove_frame_at(index)](#remove_frame_at_index_83) | Supprimez la trame à l'index spécifié de votre collection de trames de manière fluide<br/>            avec cette méthode. Parfait pour les développeurs recherchant une gestion simplifiée des trames<br/>            dans leurs images multi-trames.<br/>            La trame à supprimer sera libérée. |
| remove_metadata() | Supprime les métadonnées de cette instance d'image en définissant la valeur de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) à **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_84) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_85) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_86) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_87) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_88) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| reset_default_image() | Supprimez une image par défaut précédemment définie avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant réinitialiser ou effacer l'image par défaut dans leur animation.<br/>            Après cela, l'image par défaut est la première trame de la collection de trames propre<br/>            (elle ne peut pas être supprimée avec cette méthode). |
| [resize(new_width, new_height)](#resize_new_width_new_height_89) | Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_90) | Redimensionnez l'image de manière fluide avec cette méthode intuitive. Parfait pour les développeurs<br/>            cherchant à ajuster dynamiquement les dimensions de leurs images. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_91) | Redimensionne l'image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_92) | Redimensionne l'image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_93) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_94) | Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_95) | Ajustez sans effort la hauteur de votre image tout en conservant ses proportions<br/>            avec cette méthode intuitive. Parfait pour les développeurs souhaitant redimensionner les images<br/>            dynamiquement tout en préservant leur ratio d'aspect. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_96) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_97) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_98) | Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_99) | Redimensionnez proportionnellement la largeur de l'image sans effort avec cette méthode intuitive.<br/>            Idéal pour les développeurs cherchant à maintenir le ratio d'aspect de leurs images tout en<br/>            ajustant leurs dimensions. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_100) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_101) | Redimensionne la largeur proportionnellement. |
| [rotate(angle)](#rotate_angle_102) | Faire pivoter l'image autour du centre. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_103) | Faites pivoter l'image autour de son centre sans effort avec cette méthode intuitive.<br/>            Parfait pour les développeurs cherchant à ajuster dynamiquement l'orientation de leurs images. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_104) | Manipulez sans effort la trame active en la faisant pivoter, retourner, ou les deux<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à personnaliser<br/>            les orientations des trames d'image. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_105) | Fait pivoter le retournement complet. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_106) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_107) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_108) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_109) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_110) | Enregistre les données. |
| [save(stream, options_base)](#save_stream_options_base_111) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_112) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_113) | Enregistre les pixels ARGB 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_114) | Enregistre les pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_115) | Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_116) | Enregistre les pixels internes principaux. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_117) | Enregistre les données brutes. |
| [save_to_stream(stream)](#save_to_stream_stream_118) | Enregistre les données de l'objet dans le flux spécifié. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_119) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_121) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_122) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_123) | Définit un pixel d'image 32 bits ARGB pour la position spécifiée. |
| [set_default_image(image)](#set_default_image_image_124) | Définit l\"image par défaut\" qui est affichée par les décodeurs ne supportant pas APNG.<br/>            La classe [ApngImage](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) utilise le premier élément de [ApngImage.pages](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) comme page par défaut (principale). |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_125) | Définit la palette d'image. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_126) | Définit un pixel d'image pour la position spécifiée. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_127) | Définit la résolution pour ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_128) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_129) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_130) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |


### Constructor: ApngImage(options, width, height) {#ApngImage_options_width_height_1}


```
 ApngImage(options, width, height) 
```

Commencez à travailler avec la classe [ApngImage](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) en initialisant<br/>            une nouvelle instance sans effort. Idéal pour les développeurs souhaitant démarrer<br/>            l'utilisation des objets ApngImage rapidement et efficacement dans leurs projets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [ApngOptions](/imaging/python-net/aspose.imaging.imageoptions/apngoptions/) | Les options. |
| width | int | La largeur. |
| height | int | La hauteur. |

### Method: add_frame() {#add_frame__1}


```
 add_frame() 
```

Ajoutez facilement un nouveau cadre à la fin de votre collection de cadres avec cette<br/>            méthode simple. Idéal pour les développeurs souhaitant étendre leur<br/>            collection de cadres dynamiquement pour des animations avec des images multi-cadres.<br/>            Un nouveau cadre sera créé en fonction de la taille de l'image actuelle.

**Returns**

| Type | Description |
| :- | :- |
| [ApngFrame](/imaging/python-net/aspose.imaging.fileformats.apng/apngframe/) | La trame APNG nouvellement créée. |


### Method: add_frame(frame_image) {#add_frame_frame_image_2}


```
 add_frame(frame_image) 
```

Élargissez sans effort votre collection de cadres en ajoutant un nouveau cadre à la fin<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à améliorer leurs<br/>            animations d'images multi-cadres dynamiquement.<br/>            Le contenu du nouveau cadre sera rempli à partir de l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de la trame. |

### Method: add_frame(frame_image, frame_time) {#add_frame_frame_image_frame_time_3}


```
 add_frame(frame_image, frame_time) 
```

Élargissez votre collection de cadres de manière fluide en ajoutant un nouveau cadre au<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à enrichir leurs<br/>            animations d'images multi-cadres.<br/>            Le contenu du nouveau cadre sera rempli à partir de l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de la trame. |
| frame_time | int | La durée de la trame, en millisecondes. |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Ajoutez une nouvelle page à l'image sans effort avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant étendre dynamiquement le contenu de leurs fichiers image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La page à ajouter. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Ajustez facilement la _luminosité_ de l'image avec cette méthode intuitive,<br/>            en utilisant le paramètre de luminosité spécifié. Idéal pour les développeurs cherchant à augmenter ou diminuer<br/>            la luminosité globale des images dynamiquement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| luminosité | int | Valeur de luminosité. |

### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

Améliorez le contraste de [Image](/imaging/python-net/aspose.imaging/image/)<br/>            pour faire ressortir les détails avec cette méthode intuitive. Idéal pour les développeurs<br/>            cherchant à améliorer la clarté visuelle et l'impact de leurs images dynamiquement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| contraste | float | Valeur de contraste (dans la plage [-100 ; 100]) |

### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Appliquez une correction gamma à l'image en utilisant un coefficient à virgule flottante<br/>            avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis des couleurs<br/>            dans leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |

### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Effectuez une correction gamma sur l'image séparément pour les canaux rouge, vert et bleu<br/>            en utilisant des coefficients individuels avec cette méthode intuitive. Idéal pour les développeurs cherchant<br/>            à affiner l'équilibre des couleurs et à améliorer la qualité visuelle de leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma_red | float | Coefficient gamma pour le canal rouge |
| gamma_green | float | Coefficient gamma pour le canal vert |
| gamma_blue | float | Coefficient gamma pour le canal bleu |

### Method: analyze_percentage_digital_signature(password) {#analyze_percentage_digital_signature_password_9}


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


### Method: binarize_bradley(brightness_difference) {#binarize_bradley_brightness_difference_10}


```
 binarize_bradley(brightness_difference) 
```

Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | float | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de pixels de s x s<br/>                centrée autour de ce pixel. |

### Method: binarize_bradley(brightness_difference, window_size) {#binarize_bradley_brightness_difference_window_size_11}


```
 binarize_bradley(brightness_difference, window_size) 
```

Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | float | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de pixels de s x s<br/>            centrée autour de ce pixel. |
| window_size | int | La taille de la fenêtre de pixels de s x s centrée autour de ce pixel |

### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Binarisez sans effort l'image en utilisant un seuil prédéfini avec cette<br/>            méthode intuitive. Idéal pour les développeurs cherchant à convertir les images en forme binaire,<br/>            les simplifiant pour un traitement ou une analyse ultérieure.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| seuil | System.Byte | Valeur de seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de<br/>            255 lui sera attribuée, 0 sinon. |

### Method: blend(origin, overlay, overlay_alpha) {#blend_origin_overlay_overlay_alpha_13}


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

### Method: blend(origin, overlay, overlay_area, overlay_alpha) {#blend_origin_overlay_overlay_area_overlay_alpha_14}


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

### Method: can_load(file_path)  [static] {#can_load_file_path_15}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_16}


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


### Method: can_load(stream)  [static] {#can_load_stream_17}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_18}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_19}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_20}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_21}


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


### Method: can_save(options) {#can_save_options_22}


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


### Method: create(files)  [static] {#create_files_23}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_24}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_25}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_26}


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


### Method: create(images)  [static] {#create_images_27}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_28}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_29}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_30}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_31}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_32}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_33}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_34}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Recadrez l'image tout en ajustant les déplacements de manière fluide avec cette méthode intuitive.<br/>            Idéal pour les développeurs recherchant un contrôle précis du processus de recadrage<br/>            afin de se concentrer sur des zones spécifiques de leurs images Apng.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| left_shift | int | Le décalage à gauche. |
| right_shift | int | Le décalage à droite. |
| top_shift | int | Le décalage supérieur. |
| bottom_shift | int | Le décalage inférieur. |

### Method: crop(rectangle) {#crop_rectangle_35}


```
 crop(rectangle) 
```

Recadrez l'image sans effort pour vous concentrer sur des zones spécifiques avec cette méthode intuitive.<br/>            Parfait pour les développeurs souhaitant affiner dynamiquement la composition de leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |

### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_36}


```
 dither(dithering_method, bits_count) 
```

Effectue un tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_37}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Appliquez facilement des effets de tramage à l'image actuelle avec cette méthode intuitive.<br/>            Idéal pour les développeurs souhaitant ajouter de la texture ou réduire le banding des couleurs dans leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personnalisée pour le dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_38}


```
 embed_digital_signature(password) 
```

Intégrez une signature numérique basée sur le mot de passe fourni dans chaque page de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mot de passe | string | Le mot de passe utilisé pour générer les données de signature numérique. |

### Method: filter(rectangle, options) {#filter_rectangle_options_39}


```
 filter(rectangle, options) 
```

Appliquez sans effort des filtres au rectangle spécifié de l'image avec cette<br/>            méthode intuitive. Parfait pour les développeurs cherchant à améliorer ou modifier des zones spécifiques.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Les options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_40}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_41}


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


### Method: get_default_options(args) {#get_default_options_args_42}


```
 get_default_options(args) 
```

Récupérez les options par défaut sans effort avec cette méthode simple.<br/>            Idéal pour les développeurs recherchant un accès rapide aux paramètres d'image Apng par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | System.Object | Les arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Options par défaut |


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_43}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les pixels. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Le chargeur partiel de pixels. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_44}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_45}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_46}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_47}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_48}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_49}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_50}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_51}


```
 get_modify_date(use_default) 
```

Obtenez rapidement la date et l'heure de la dernière modification de l'image ressource<br/>            avec cette méthode conviviale. Idéal pour les développeurs ayant besoin de suivre les changements<br/>            et de gérer efficacement les ressources.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| use_default | bool | si défini sur <c>true</c> utilise les informations de FileInfo comme valeur par défaut. |

**Returns**

| Type | Description |
| :- | :- |
| System.DateTime | La date et l'heure de la dernière modification de l'image de la ressource. |


### Method: get_original_options() {#get_original_options__52}


```
 get_original_options() 
```

Récupérez les options basées sur les paramètres du fichier original sans effort avec cette méthode intuitive.<br/>            Parfait pour les développeurs cherchant à accéder et à utiliser des paramètres qui correspondent aux caractéristiques<br/>            du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), l'image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options basées sur les paramètres du fichier original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_53}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_54}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_55}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_56}


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


### Method: get_skew_angle() {#get_skew_angle__57}


```
 get_skew_angle() 
```

Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan.

**Returns**

| Type | Description |
| :- | :- |
| float | L'angle d'inclinaison, en degrés. |


### Method: insert_frame(index) {#insert_frame_index_58}


```
 insert_frame(index) 
```

Insérez sans effort une nouvelle trame dans votre collection de trames à l'index spécifié<br/>            avec cette méthode intuitive. Idéal pour les développeurs recherchant un contrôle précis sur<br/>            l'agencement des trames dans leurs animations d'images multi-trames.<br/>            Une nouvelle trame sera créée en fonction de la taille de l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |

**Returns**

| Type | Description |
| :- | :- |
| [ApngFrame](/imaging/python-net/aspose.imaging.fileformats.apng/apngframe/) | La trame APNG nouvellement créée. |


### Method: insert_frame(index, frame_image) {#insert_frame_index_frame_image_59}


```
 insert_frame(index, frame_image) 
```

Insère une nouvelle trame dans la collection de trames propre à l'index spécifié.<br/>            Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |
| frame_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de la trame. |

### Method: insert_frame(index, frame_image, frame_time) {#insert_frame_index_frame_image_frame_time_60}


```
 insert_frame(index, frame_image, frame_time) 
```

Insère une nouvelle trame dans la collection de trames propre à l'index spécifié.<br/>            Le contenu de la nouvelle trame sera rempli à partir de l'image spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |
| frame_image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image de la trame. |
| frame_time | int | La durée de la trame, en millisecondes. |

### Method: is_digital_signed(password, percentage_threshold) {#is_digital_signed_password_percentage_threshold_61}


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


### Method: load(file_path)  [static] {#load_file_path_62}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_63}


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


### Method: load(stream)  [static] {#load_stream_64}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_65}


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


### Method: load_argb_32_pixels(rectangle) {#load_argb_32_pixels_rectangle_66}


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


### Method: load_argb_64_pixels(rectangle) {#load_argb_64_pixels_rectangle_67}


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


### Method: load_cmyk_32_pixels(rectangle) {#load_cmyk_32_pixels_rectangle_68}


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


### Method: load_cmyk_pixels(rectangle) {#load_cmyk_pixels_rectangle_69}


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


### Method: load_partial_argb_32_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_32_pixels_rectangle_partial_pixel_loader_70}


```
 load_partial_argb_32_pixels(rectangle, partial_pixel_loader) 
```

Charge partiellement des pixels ARGB 32 bits (par blocs).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle depuis lequel charger les pixels. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Le chargeur partiel de pixels. |

### Method: load_partial_argb_64_pixels(rectangle, partial_pixel_loader) {#load_partial_argb_64_pixels_rectangle_partial_pixel_loader_71}


```
 load_partial_argb_64_pixels(rectangle, partial_pixel_loader) 
```

Charge partiellement des pixels ARGB 64 bits par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle souhaité. |
| partial_pixel_loader | [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits. |

### Method: load_partial_pixels(desired_rectangle, pixel_loader) {#load_partial_pixels_desired_rectangle_pixel_loader_72}


```
 load_partial_pixels(desired_rectangle, pixel_loader) 
```

Charge partiellement des pixels par paquets.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| desired_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle souhaité. |
| pixel_loader | [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Le chargeur de pixels. |

### Method: load_pixels(rectangle) {#load_pixels_rectangle_73}


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


### Method: load_raw_data(rectangle, dest_image_bounds, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_dest_image_bounds_raw_data_settings_raw_data_loader_74}


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

### Method: load_raw_data(rectangle, raw_data_settings, raw_data_loader) {#load_raw_data_rectangle_raw_data_settings_raw_data_loader_75}


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

### Method: load_stream(stream)  [static] {#load_stream_stream_76}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_77}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_78}


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


### Method: normalize_angle(resize_proportionally, background_color) {#normalize_angle_resize_proportionally_background_color_79}


```
 normalize_angle(resize_proportionally, background_color) 
```

Normalise l'angle.<br/>            Cette méthode s'applique aux documents texte numérisés pour éliminer la distorsion de la numérisation.<br/>            Cette méthode utilise les méthodes [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [RasterCachedMultipageImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | si défini sur <c>true</c> votre taille d'image sera modifiée selon les projections du rectangle tourné (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |

### Method: pop_frame_at(index) {#pop_frame_at_index_80}


```
 pop_frame_at(index) 
```

Supprimez et récupérez la trame à l'index spécifié de votre collection de trames<br/>            avec cette méthode intuitive. Parfait pour les développeurs recherchant une gestion efficace<br/>            des trames dans leurs animations.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |

**Returns**

| Type | Description |
| :- | :- |
| [ApngFrame](/imaging/python-net/aspose.imaging.fileformats.apng/apngframe/) | Le cadre APNG supprimé. |


### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_81}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_82}


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


### Method: remove_frame_at(index) {#remove_frame_at_index_83}


```
 remove_frame_at(index) 
```

Supprimez la trame à l'index spécifié de votre collection de trames de manière fluide<br/>            avec cette méthode. Parfait pour les développeurs recherchant une gestion simplifiée des trames<br/>            dans leurs images multi-trames.<br/>            La trame à supprimer sera libérée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index. |

### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_84}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_85}


```
 replace_color(old_color, old_color_diff, new_color) 
```

Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| old_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |
| old_color_diff | System.Byte | Différence autorisée dans l'ancienne couleur pour pouvoir élargir la teinte de couleur remplacée. |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_86}


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

### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_87}


```
 replace_non_transparent_colors(new_color) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_88}


```
 replace_non_transparent_colors(new_color_argb) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_argb | int | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_89}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_90}


```
 resize(new_width, new_height, resize_type) 
```

Redimensionnez l'image de manière fluide avec cette méthode intuitive. Parfait pour les développeurs<br/>            cherchant à ajuster dynamiquement les dimensions de leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Le type de redimensionnement. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_91}


```
 resize(new_width, new_height, settings) 
```

Redimensionne l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_92}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_93}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_94}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_95}


```
 resize_height_proportionally(new_height, resize_type) 
```

Ajustez sans effort la hauteur de votre image tout en conservant ses proportions<br/>            avec cette méthode intuitive. Parfait pour les développeurs souhaitant redimensionner les images<br/>            dynamiquement tout en préservant leur ratio d'aspect.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_96}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_97}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_98}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_99}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionnez proportionnellement la largeur de l'image sans effort avec cette méthode intuitive.<br/>            Idéal pour les développeurs cherchant à maintenir le ratio d'aspect de leurs images tout en<br/>            ajustant leurs dimensions.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_100}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_101}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle) {#rotate_angle_102}


```
 rotate(angle) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_103}


```
 rotate(angle, resize_proportionally, background_color) 
```

Faites pivoter l'image autour de son centre sans effort avec cette méthode intuitive.<br/>            Parfait pour les développeurs cherchant à ajuster dynamiquement l'orientation de leurs images.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resize_proportionally | bool | si défini sur <c>true</c> la taille de votre image sera modifiée<br/>            selon les projections du rectangle tourné (points d'angle) dans les autres<br/>            cas, les dimensions restent inchangées et seuls<br/>            __internal__ le contenu de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_104}


```
 rotate_flip(rotate_flip_type) 
```

Manipulez sans effort la trame active en la faisant pivoter, retourner, ou les deux<br/>            avec cette méthode intuitive. Idéal pour les développeurs cherchant à personnaliser<br/>            les orientations des trames d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Le type de retournement de rotation. |

### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_105}


```
 rotate_flip_all(rotate_flip) 
```

Fait pivoter le retournement complet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Le retournement de rotation. |

### Method: save(file_path) {#save_file_path_106}


```
 save(file_path) 
```

Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer l'image. |

### Method: save(file_path, options) {#save_file_path_options_107}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_108}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_109}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_110}


```
 save(stream) 
```

Enregistre les données.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données. |

### Method: save(stream, options_base) {#save_stream_options_base_111}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_112}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_113}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Enregistre les pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Le tableau de pixels ARGB 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_114}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Enregistre les pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_115}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le tableau de pixels CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_116}


```
 save_pixels(rectangle, pixels) 
```

Enregistre les pixels internes principaux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les pixels. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_117}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_118}


```
 save_to_stream(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_119}


```
 save_to_stream_with_options(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_120}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_121}


```
 save_with_options(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_122}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_123}


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

### Method: set_default_image(image) {#set_default_image_image_124}


```
 set_default_image(image) 
```

Définit l\"image par défaut\" qui est affichée par les décodeurs ne supportant pas APNG.<br/>            La classe [ApngImage](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) utilise le premier élément de [ApngImage.pages](/imaging/python-net/aspose.imaging.fileformats.apng/apngimage/) comme page par défaut (principale).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | L'image. |

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_125}


```
 set_palette(palette, update_colors) 
```

Définit la palette d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_126}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_127}


```
 set_resolution(dpi_x, dpi_y) 
```

Définit la résolution pour ce [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dpi_x | float | La résolution horizontale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La résolution verticale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_128}


```
 try_set_metadata(metadata) 
```

Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| metadata | [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) | Les métadonnées. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Vrai si _metadata_ n'est pas nul et que l'instance [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) <br/>            prend en charge et/ou implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/) ; sinon, faux. |


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_129}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| argb_32_pixels | int[] | Le tableau de couleurs ARGB 32 bits à écrire. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_130}


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
### The following example shows how to export to APNG file format. {#example_197}
``` python

import aspose.pycore as aspycore
from aspose.imaging import *
from aspose.imaging.imageoptions import *

with Image.load("Animation1.webp") as image:
	# Exporter vers une animation APNG avec des cycles d'animation illimités par défaut
	image.save("Animation1.webp.png", ApngOptions())
	# Configuration des cycles d'animation
	obj_init = ApngOptions()
	# 5 cycles
	obj_init.num_plays = 5
	image.save("Animation2.webp.png", obj_init)


```

### The following example shows how to export apng APNG file format from other non-animated multi-page format. {#example_198}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import ApngOptions

with Image.load("img4.tif") as image:
	# Configuration de la durée du cadre par défaut
	obj_init = ApngOptions()
	# 500 ms
	obj_init.default_frame_time = 500
	image.save("img4.tif.500ms.png", obj_init)
	obj_init2 = ApngOptions()
	# 250 ms
	obj_init2.default_frame_time = 250
	image.save("img4.tif.250ms.png", obj_init2)


```

