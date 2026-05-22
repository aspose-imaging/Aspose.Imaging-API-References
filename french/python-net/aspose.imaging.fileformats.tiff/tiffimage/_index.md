---
title: "Classe TiffImage"
type: docs
weight: 200
url: /fr/python-net/aspose.imaging.fileformats.tiff/tiffimage/
---

**Summary:** Process Tagged Image File Format (TIFF) raster images with our API, offering<br/>            comprehensive support for various resolutions and advanced editing capabilities<br/>            like EXIF data manipulation and alpha channels. Normalize angles for scanned images,<br/>            resize, transform to grayscale, and apply filters, gamma corrections and image<br/>            parameters adjustments with ease. Seamlessly handle multi-frame TIFF files,<br/>            create graphics paths, add shapes, and effortlessly save images to different formats.

**Module:** [aspose.imaging.fileformats.tiff](/imaging/python-net/aspose.imaging.fileformats.tiff/)

**Full Name:** aspose.imaging.fileformats.tiff.TiffImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IRasterImageArgb32PixelLoader, IRasterImageRawDataLoader, IMultipageImage, IMultipageImageExt, RasterCachedMultipageImage

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [TiffImage(frame)](#TiffImage_frame_1) | Initialisez un nouvel objet de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/), en spécifiant le paramètre <br/>            frame. Ce constructeur facilite la création d’une instance TiffImage <br/>            , permettant aux développeurs de spécifier le cadre à charger ou à traiter, <br/>            simplifiant les tâches de gestion des images Tiff dans leurs applications. |
| [TiffImage(frames)](#TiffImage_frames_2) | Créez une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/), en fournissant une liste de <br/>            frames comme paramètre. Ce constructeur permet l’initialisation d’un objet TiffImage <br/>            avec plusieurs frames, facilitant la gestion efficace et le traitement des <br/>            séquences d’images TIFF dans les applications logicielles. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| active_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r/w | Gérez le cadre actif de manière fluide, facilitant la navigation dynamique et <br/>            la manipulation dans le contexte désigné. Permettez à votre application d'interagir <br/>            efficacement avec le contenu multimédia, améliorant l'engagement des utilisateurs et la productivité. |
| auto_adjust_palette | bool | r/w | Obtient ou définit une valeur indiquant si la palette d'ajustement automatique est activée. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | r/w | Obtient ou définit une valeur pour la couleur d'arrière-plan. |
| bits_per_pixel | int | r | Obtient le nombre de bits par pixel de l'image. |
| bounds | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | r | Obtient les limites de l'objet. |
| buffer_size_hint | int | r/w | Obtient ou définit l'indice de taille du tampon, qui correspond à la taille maximale autorisée pour tous les tampons internes. |
| byte_order | [TiffByteOrder](/imaging/python-net/aspose.imaging.fileformats.tiff.enums/tiffbyteorder/) | r/w | Basculez l'ordre des octets pour les fichiers TIFF de manière fluide, assurant un contrôle précis sur <br/>            l'interprétation des données. Donnez à vos applications la flexibilité de s'adapter aux <br/>            différentes spécifications de fichiers, améliorant la compatibilité et l'efficacité du traitement des données. |
| container | [Image](/imaging/python-net/aspose.imaging/image/) | r | Obtient le conteneur [Image](/imaging/python-net/aspose.imaging/image/). |
| data_stream_container | [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | r | Obtient le flux de données de l'objet. |
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit l'instance Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Récupérez la valeur du format de fichier associée à l’image. Cette propriété constitue <br/>            un aspect crucial de la récupération des métadonnées d’image, permettant aux applications logicielles de <br/>            identifier et d’interpréter le format des données d’image de manière efficace. |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | r | Récupérez un tableau d'instances [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/), permettant un accès complet <br/>            et une manipulation des cadres individuels au sein de l'image TIFF. Exploitez la <br/>            puissance de ce tableau pour rationaliser les flux de travail de traitement d'image, assurant un contrôle précis <br/>            et une optimisation du contenu visuel. |
| [has_alpha](#has_alpha1) | bool | r | Déterminez si l'image possède un canal alpha, fournissant des informations essentielles <br/>            pour les opérations de rendu et de composition. Intégrez cette fonctionnalité pour optimiser <br/>            les flux de travail de traitement visuel, assurant une représentation précise et une manipulation des <br/>            éléments transparents. |
| has_background_color | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| has_transparent_color | bool | r/w | Obtient une valeur indiquant si l'image possède une couleur transparente. |
| height | int | r | Obtient la hauteur de l'image. |
| horizontal_resolution | float | r/w | Récupérez la résolution horizontale de l'[Image](/imaging/python-net/aspose.imaging/image/) spécifiée en pixels <br/>            par pouce, facilitant des ajustements précis et des capacités de rendu. Accédez <br/>            aux métadonnées essentielles de l'image sans effort, permettant des flux de travail de traitement d'image rationalisés <br/>            pour offrir une meilleure expérience utilisateur. |
| image_opacity | float | r | Obtient l'opacité de cette image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| is_cached | bool | r | Obtient une valeur indiquant si les données de l'image sont actuellement en cache. |
| is_raw_data_available | bool | r | Obtient une valeur indiquant si le chargement de données brutes est pris en charge. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtient ou définit les données XMP à partir de la trame. |
| page_count | int | r | Récupérez le nombre total de pages du document spécifié, facilitant <br/>            une navigation efficace et la gestion de contenu multi-pages. Intégrez cette <br/>            fonctionnalité pour améliorer l'expérience utilisateur, permettant un accès fluide aux <br/>            structures complètes du document. |
| pages | [Image[]](/imaging/python-net/aspose.imaging/image/) | r | Accédez aux pages du document de manière fluide, permettant une navigation dynamique et <br/>            la manipulation au sein de la structure du contenu. Donnez à votre application un accès efficace <br/>            aux pages individuelles, facilitant le traitement rationalisé des documents et <br/>            une interaction utilisateur améliorée. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| premultiply_components | bool | r/w | Indiquez si les composants nécessitent une prémultiplication, assurant une gestion efficace <br/>            des éléments visuels. Améliorez les processus de rendu en basculant cette propriété, <br/>            rationalisant les flux de travail graphiques pour une performance optimisée. |
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
| vertical_resolution | float | r/w | Accédez à la résolution verticale de l'[Image](/imaging/python-net/aspose.imaging/image/) désignée en pixels par <br/>            pouce, permettant des ajustements précis et des optimisations de rendu. Utilisez les données essentielles <br/>            de l'image sans effort pour rationaliser les flux de travail de traitement d'image, assurant <br/>            une qualité supérieure et des performances optimales dans vos applications. |
| width | int | r | Obtient la largeur de l'image. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit les données Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(image)](#add_image_1) | Ajoutez les cadres de l'image spécifiée de manière fluide au cadre actuel, <br/>            consolidant leur contenu et améliorant la flexibilité de composition. Intégrez <br/>            cette méthode pour rationaliser la gestion et la manipulation des cadres au sein de votre <br/>            application, facilitant la gestion efficace des images multi-cadres. |
| [add_frame(frame)](#add_frame_frame_2) | Incorporez le cadre spécifié de manière fluide dans l'image, élargissant son contenu <br/>            et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion des images, <br/>            permettant une manipulation efficace des images multi-cadres au sein de votre application. |
| [add_frames(frames)](#add_frames_frames_3) | Intégrez le tableau de cadres de manière fluide dans l'image, enrichissant son contenu et <br/>            sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion des images, <br/>            permettant une manipulation efficace des images multi-cadres au sein de votre application. |
| [add_page(page)](#add_page_page_4) | Incorporez une nouvelle page dans l’image existante de manière fluide, en élargissant son contenu <br/>            et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la <br/>            gestion de documents, permettant une manipulation efficace des images multipages dans votre application. |
| [adjust_brightness(brightness)](#adjust_brightness_brightness_5) | Mettez en œuvre le réglage de la _luminosité_ pour l'image, permettant la <br/>            modification des niveaux de luminance globaux. Intégrez cette méthode dans votre flux de travail de traitement d'image <br/>            pour améliorer la visibilité et la qualité visuelle des <br/>            images au sein de votre application. |
| [adjust_contrast(contrast)](#adjust_contrast_contrast_6) | Améliorez le contraste de l'[Image](/imaging/python-net/aspose.imaging/image/) instance, <br/>            amplifiant les différences entre ses zones claires et sombres. Intégrez cette <br/>            fonctionnalité pour améliorer la clarté visuelle et la qualité globale de l'image <br/>            au sein de votre application. |
| [adjust_gamma(gamma)](#adjust_gamma_gamma_7) | Appliquez une correction gamma à l'image, ajustant les intensités des pixels pour obtenir <br/> l'équilibre des couleurs souhaité. Intégrez cette méthode dans votre flux de traitement d'image <br/> afin d'améliorer la qualité visuelle et d'augmenter la précision des analyses ou affichages subséquents <br/> au sein de votre application. |
| [adjust_gamma(gamma_red, gamma_green, gamma_blue)](#adjust_gamma_gamma_red_gamma_green_gamma_blue_8) | Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, <br/> vert et bleu, permettant des ajustements fins de l'équilibre des couleurs <br/> et du contraste. Intégrez cette méthode dans votre pipeline de traitement d'image pour <br/> obtenir un contrôle précis du rendu des couleurs et améliorer la fidélité visuelle au sein <br/> de votre application. |
| align_resolutions() | Implémentez la méthode d'assistance AlignResolutions pour synchroniser les résolutions horizontale et <br/> verticale, assurant l'uniformité des dimensions de l'image. Cette fonctionnalité <br/> facilite des flux de travail de traitement d'image rationalisés en harmonisant les paramètres de résolution, <br/> optimisant la qualité visuelle et la cohérence sur diverses plateformes et <br/> appareils. |
| [analyze_percentage_digital_signature(password)](#analyze_percentage_digital_signature_password_9) | Calcule le pourcentage de similarité entre les données extraites et le mot de passe original. |
| auto_brightness_contrast() | Effectue une normalisation automatique adaptative de la luminosité et du contraste pour l'image entière. |
| auto_rotate() | Fait pivoter automatiquement l'image en fonction des données d'orientation extraites des métadonnées Exif <br/>            . Cette méthode garantit que les images sont affichées dans la bonne orientation, <br/>            améliorant l'expérience utilisateur et éliminant le besoin d'ajustements manuels. En <br/>            analysant les informations Exif, l'image est pivotée en conséquence, offrant une expérience de visualisation fluide <br/>            sur différentes plateformes et appareils. Ce processus de rotation automatisé <br/>            simplifie la gestion des images et améliore l'utilisabilité globale, surtout lorsqu'<br/>            on traite de gros lots d'images avec des orientations variées. |
| [binarize_bradley(brightness_difference)](#binarize_bradley_brightness_difference_10) | Binarisation d'une image à l'aide de l'algorithme de seuillage adaptatif de Bradley utilisant le seuillage d'image intégrale |
| [binarize_bradley(brightness_difference, window_size)](#binarize_bradley_brightness_difference_window_size_11) | Mettez en œuvre la binarisation de l'image en utilisant l'algorithme de seuillage adaptatif de Bradley <br/> avec seuillage d'image intégrale. Cette approche calcule dynamiquement les seuils locaux <br/> en fonction du voisinage de l'image, améliorant l'adaptabilité aux <br/> variations d'éclairage et assurant une segmentation robuste pour les tâches de traitement <br/> subséquentes au sein de votre application. |
| [binarize_fixed(threshold)](#binarize_fixed_threshold_12) | Appliquez la binarisation à l'image en utilisant un seuil prédéfini, la convertissant en <br/> une image binaire avec des régions de premier plan et d'arrière-plan distinctes. Intégrez cette <br/> méthode dans votre flux de traitement d'image pour faciliter la segmentation et l'extraction de caractéristiques <br/> , améliorant la précision et l'efficacité de l'analyse d'image au sein <br/> de votre application. |
| binarize_otsu() | Utilisez le seuillage d'Otsu pour effectuer la binarisation de l'image, déterminant automatiquement <br/> la valeur de seuil optimale basée sur l'histogramme de l'image. Intégrez <br/> cette méthode dans votre flux de traitement d'image pour obtenir une segmentation efficace <br/> et l'extraction de caractéristiques, améliorant la précision et la fiabilité de l'analyse d'image <br/> au sein de votre application. |
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
| [create_with_frame(frame)](#create_with_frame_frame_34) | Initialise une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/). |
| [create_with_frames(frames)](#create_with_frames_frames_35) | Initialise une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/). |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_36) | Effectuez un recadrage de l'image en spécifiant des déplacements vers la gauche, la droite, le haut et <br/> le bas. Cette méthode permet une sélection précise de la partie souhaitée de <br/> l'image, facilitant la suppression efficace des zones indésirables et la mise en avant du <br/> contenu essentiel. Intégrez cette fonctionnalité dans votre pipeline de traitement d'image <br/> pour améliorer la clarté et la composition selon les besoins au sein de votre application. |
| [crop(rectangle)](#crop_rectangle_37) | Recadrez l'image en utilisant une région rectangulaire spécifiée, permettant une sélection précise du <br/> contenu souhaité. Intégrez cette méthode dans votre flux de traitement d'image pour <br/> supprimer efficacement les zones indésirables et vous concentrer sur les détails essentiels, améliorant la <br/> clarté globale et la composition de l'image. |
| [dither(dithering_method, bits_count)](#dither_dithering_method_bits_count_38) | Effectue un tramage sur l'image actuelle. |
| [dither(dithering_method, bits_count, custom_palette)](#dither_dithering_method_bits_count_custom_palette_39) | Exécutez le dithering sur l'image actuelle pour améliorer sa qualité visuelle et réduire les artefacts de bandes de couleur. Intégrez cette méthode dans votre flux de traitement d'image <br/> afin d'assurer des transitions plus fluides entre les couleurs, résultant en une apparence d'image globale <br/> améliorée et une meilleure clarté. |
| [embed_digital_signature(password)](#embed_digital_signature_password_40) | Intégrez une signature numérique basée sur le mot de passe fourni dans chaque page de l'image. |
| [filter(rectangle, options)](#filter_rectangle_options_41) | Filtrez le contenu à l'intérieur du rectangle spécifié, en appliquant un filtre de traitement d'image <br/>            désigné pour améliorer ou modifier la région sélectionnée. Intégrez cette méthode <br/>            dans votre flux de manipulation d'images pour obtenir des améliorations ciblées ou <br/>            des transformations dans votre application. |
| [get_argb_32_pixel(x, y)](#get_argb_32_pixel_x_y_42) | Obtient un pixel ARGB 32 bits d'une image. |
| [get_default_argb_32_pixels(rectangle)](#get_default_argb_32_pixels_rectangle_43) | Obtient le tableau de pixels ARGB 32 bits par défaut. |
| [get_default_options(args)](#get_default_options_args_44) | Obtient les options par défaut. |
| [get_default_pixels(rectangle, partial_pixel_loader)](#get_default_pixels_rectangle_partial_pixel_loader_45) | Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings)](#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46) | Obtient le tableau de données brutes par défaut en utilisant le chargeur de pixels partiel. |
| [get_default_raw_data(rectangle, raw_data_settings)](#get_default_raw_data_rectangle_raw_data_settings_47) | Obtient le tableau de données brutes par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_48) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_49) | Obtient le format de fichier. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_50) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_51) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_52) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_modify_date(use_default)](#get_modify_date_use_default_53) | Obtient la date et l'heure de la dernière modification de l'image ressource. |
| [get_original_options()](#get_original_options__54) | Récupérez les options dérivées des paramètres du fichier original, facilitant la préservation transparente <br/> des paramètres clés tels que la profondeur de couleur et d'autres attributs essentiels de <br/> l'image originale. Utilisez cette méthode pour maintenir la fidélité et la cohérence dans <br/> les tâches de traitement d'image, garantissant des résultats optimaux sans altérations inutiles.<br/> Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant le<br/> [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/> Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre. |
| [get_pixel(x, y)](#get_pixel_x_y_55) | Obtient un pixel d'image. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_56) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_57) | Obtient une largeur proportionnelle. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_58) | Convertit en aps. |
| [get_skew_angle()](#get_skew_angle__59) | Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan. |
| grayscale() | Convertissez l'image en sa représentation en niveaux de gris, la transformant en <br/> une image à canal unique où chaque pixel représente l'intensité. Intégrez cette méthode <br/> dans votre pipeline de traitement d'image pour simplifier l'analyse et améliorer <br/> la compatibilité avec les algorithmes basés sur le niveau de gris, facilitant diverses tâches de vision par ordinateur <br/> et d'analyse d'image au sein de votre application. |
| [insert_frame(index, frame)](#insert_frame_index_frame_60) | Insérez la nouvelle trame à l'index spécifié dans la séquence de trames, assurant <br/> un contrôle précis de l'agencement des trames. Utilisez cette méthode pour gérer les séquences de trames <br/> efficacement, facilitant la manipulation dynamique et l'organisation du contenu d'image <br/> au sein de votre application. |
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
| [normalize_angle(resize_proportionally, background_color)](#normalize_angle_resize_proportionally_background_color_79) | Utilisez la méthode NormalizeAngle spécifiquement conçue pour les documents texte numérisés <br/> afin de rectifier les scans inclinés, assurant un alignement précis. Intégrez sans couture <br/> cette fonctionnalité dans vos flux de traitement de texte pour améliorer la <br/> lisibilité et la qualité des documents, augmentant l'efficacité globale de la reconnaissance <br/> de texte et des tâches d'analyse.<br/> Cette méthode utilise [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) méthodes. |
| normalize_histogram() | Normalise l'histogramme de l'image — ajuste les valeurs des pixels pour utiliser toute la plage disponible. |
| [read_argb_32_scan_line(scan_line_index)](#read_argb_32_scan_line_scan_line_index_80) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [read_scan_line(scan_line_index)](#read_scan_line_scan_line_index_81) | Lit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [remove_frame(frame)](#remove_frame_frame_82) | Supprimez efficacement la trame spécifiée de la séquence d'images, facilitant <br/> une gestion simplifiée des trames au sein de votre application. Intégrez cette fonctionnalité <br/> pour améliorer la précision et la flexibilité de la manipulation des trames, assurant une <br/> organisation et une présentation fluides du contenu d'image. |
| [remove_frame(index)](#remove_frame_index_83) | Supprime la trame par son index. |
| [remove_frame_by_index(index)](#remove_frame_by_index_index_84) | Supprime la trame par son index. |
| remove_metadata() | Supprime les métadonnées de cette instance d'image en définissant les valeurs de [IHasXmpData.xmp_data](/imaging/python-net/aspose.imaging.xmp/ihasxmpdata/) et [IHasExifData.exif_data](/imaging/python-net/aspose.imaging.exif/ihasexifdata/) sur **None**. |
| [replace_argb(old_color_argb, old_color_diff, new_color_argb)](#replace_argb_old_color_argb_old_color_diff_new_color_argb_85) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color, old_color_diff, new_color)](#replace_color_old_color_old_color_diff_new_color_86) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_color(old_color_argb, old_color_diff, new_color_argb)](#replace_color_old_color_argb_old_color_diff_new_color_argb_87) | Remplace une couleur par une autre avec une différence autorisée et préserve la valeur alpha originale pour conserver des bords lisses. |
| [replace_frame(index, new_frame)](#replace_frame_index_new_frame_88) | Remplacez la trame à la position désignée par une autre trame de manière fluide, <br/> facilitant la gestion dynamique des trames au sein de la séquence d'images. Intégrez cette <br/> méthode pour améliorer la flexibilité et la précision de la manipulation des trames, assurant <br/> une organisation optimale et une présentation du contenu d'image au sein de votre application. |
| [replace_non_transparent_colors(new_color)](#replace_non_transparent_colors_new_color_89) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [replace_non_transparent_colors(new_color_argb)](#replace_non_transparent_colors_new_color_argb_90) | Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule. |
| [resize(new_width, new_height)](#resize_new_width_new_height_91) | Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_92) | Effectuez une opération de redimensionnement proportionnel de l'image, en conservant son ratio d'aspect <br/> tout en ajustant ses dimensions. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images <br/> au sein de votre application, assurant une représentation visuelle cohérente de l'intégrité du contenu <br/> .<br/> Le redimensionnement proportionnel redimensionnera chaque trame selon le ratio de _newWidth_/width et _newHeight_/height. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_93) | Ajustez la taille de l'image en fonction des paramètres spécifiés, permettant un contrôle précis <br/> des dimensions, du ratio d'aspect et du comportement de mise à l'échelle. Intégrez cette <br/> méthode dans votre flux de traitement d'image pour réaliser des opérations de redimensionnement personnalisées <br/> adaptées aux exigences spécifiques de votre application. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_94) | Redimensionne l'image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_95) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_96) | Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_97) | Effectuez un ajustement proportionnel de la hauteur de l'image, en conservant son ratio d'aspect <br/> pour une intégrité visuelle cohérente. Utilisez cette méthode pour redimensionner dynamiquement <br/> les images au sein de votre application, assurant un affichage optimal sur diverses plateformes <br/> et appareils sans compromettre la qualité du contenu. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_98) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_99) | Redimensionne la hauteur proportionnellement. |
| [resize_proportional(new_width, new_height, resize_type)](#resize_proportional_new_width_new_height_resize_type_100) | Effectuez une opération de redimensionnement proportionnel de l'image, en conservant son ratio d'aspect <br/> tout en ajustant ses dimensions. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images <br/> au sein de votre application, assurant une représentation visuelle cohérente de l'intégrité du contenu <br/> .<br/> Le redimensionnement proportionnel redimensionnera chaque trame selon le ratio de _newWidth_/width et _newHeight_/height. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_101) | Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_102) | Ajustez la largeur de l'image tout en maintenant son ratio d'aspect, assurant <br/> un redimensionnement proportionnel pour une présentation visuelle optimale. Utilisez cette méthode pour <br/> mettre à l'échelle dynamiquement les images au sein de votre application, facilitant un rendu cohérent et <br/> esthétiquement agréable sur divers contextes d'affichage. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_103) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_104) | Redimensionne la largeur proportionnellement. |
| [rotate(angle)](#rotate_angle_105) | Faire pivoter l'image autour du centre. |
| [rotate(angle, resize_proportionally, background_color)](#rotate_angle_resize_proportionally_background_color_106) | Faites pivoter l'image autour de son point central d'un angle spécifié, permettant des ajustements d'orientation précis <br/> . Intégrez cette fonctionnalité dans votre pipeline de traitement d'image <br/> pour faciliter des transformations précises, assurant un alignement optimal et <br/> la présentation du contenu visuel au sein de votre application. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_107) | Effectuez une rotation, un retournement ou une combinaison des deux opérations exclusivement sur la <br/> trame active. Cette méthode permet une manipulation précise des trames individuelles au sein <br/> de la séquence d'images, améliorant la flexibilité de l'édition et de la composition d'images au <br/> sein de votre application. |
| [rotate_flip_all(rotate_flip)](#rotate_flip_all_rotate_flip_108) | Fait pivoter le retournement complet. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_109) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_110) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_111) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_112) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_113) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(stream, options_base)](#save_stream_options_base_114) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_115) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_argb_32_pixels(rectangle, pixels)](#save_argb_32_pixels_rectangle_pixels_116) | Enregistre les pixels ARGB 32 bits. |
| [save_cmyk_32_pixels(rectangle, pixels)](#save_cmyk_32_pixels_rectangle_pixels_117) | Enregistre les pixels. |
| [save_cmyk_pixels(rectangle, pixels)](#save_cmyk_pixels_rectangle_pixels_118) | Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/). |
| [save_pixels(rectangle, pixels)](#save_pixels_rectangle_pixels_119) | Enregistre les pixels internes principaux. |
| [save_raw_data(data, data_offset, rectangle, raw_data_settings)](#save_raw_data_data_data_offset_rectangle_raw_data_settings_120) | Enregistre les données brutes. |
| [save_to_stream(stream)](#save_to_stream_stream_121) | Enregistre l'image dans le flux |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_122) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_124) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_125) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [set_argb_32_pixel(x, y, argb_32_color)](#set_argb_32_pixel_x_y_argb_32_color_126) | Définit un pixel d'image 32 bits ARGB pour la position spécifiée. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_127) | Définit la palette d'image. |
| [set_pixel(x, y, color)](#set_pixel_x_y_color_128) | Définit un pixel d'image pour la position spécifiée. |
| [set_resolution(dpi_x, dpi_y)](#set_resolution_dpi_x_dpi_y_129) | Établit la résolution pour le [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), permettant <br/>            un contrôle précis du rendu et des propriétés d'affichage de l'image. Intégrez cette <br/>            fonctionnalité pour optimiser la sortie visuelle et garantir la compatibilité avec divers <br/>            appareils et plateformes de sortie, améliorant l'expérience utilisateur globale. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_130) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |
| [write_argb_32_scan_line(scan_line_index, argb_32_pixels)](#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |
| [write_scan_line(scan_line_index, pixels)](#write_scan_line_scan_line_index_pixels_132) | Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié. |


### Constructor: TiffImage(frame) {#TiffImage_frame_1}


```
 TiffImage(frame) 
```

Initialisez un nouvel objet de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/), en spécifiant le paramètre <br/>            frame. Ce constructeur facilite la création d’une instance TiffImage <br/>            , permettant aux développeurs de spécifier le cadre à charger ou à traiter, <br/>            simplifiant les tâches de gestion des images Tiff dans leurs applications.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre tiff avec lequel initialiser l'image. |

### Constructor: TiffImage(frames) {#TiffImage_frames_2}


```
 TiffImage(frames) 
```

Créez une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/), en fournissant une liste de <br/>            frames comme paramètre. Ce constructeur permet l’initialisation d’un objet TiffImage <br/>            avec plusieurs frames, facilitant la gestion efficace et le traitement des <br/>            séquences d’images TIFF dans les applications logicielles.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Les cadres. |

### Property: has_alpha {#has_alpha1}

Déterminez si l'image possède un canal alpha, fournissant des informations essentielles <br/>            pour les opérations de rendu et de composition. Intégrez cette fonctionnalité pour optimiser <br/>            les flux de travail de traitement visuel, assurant une représentation précise et une manipulation des <br/>            éléments transparents.

**See also:**

**[Example # 1](#example_119)**: The following example loads a TIFF image and prints information about raw dat...


### Method: add(image) {#add_image_1}


```
 add(image) 
```

Ajoutez les cadres de l'image spécifiée de manière fluide au cadre actuel, <br/>            consolidant leur contenu et améliorant la flexibilité de composition. Intégrez <br/>            cette méthode pour rationaliser la gestion et la manipulation des cadres au sein de votre <br/>            application, facilitant la gestion efficace des images multi-cadres.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| image | [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) | L'image source. |

### Method: add_frame(frame) {#add_frame_frame_2}


```
 add_frame(frame) 
```

Incorporez le cadre spécifié de manière fluide dans l'image, élargissant son contenu <br/>            et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion des images, <br/>            permettant une manipulation efficace des images multi-cadres au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre à ajouter. |

### Method: add_frames(frames) {#add_frames_frames_3}


```
 add_frames(frames) 
```

Intégrez le tableau de cadres de manière fluide dans l'image, enrichissant son contenu et <br/>            sa polyvalence. Utilisez cette méthode pour améliorer la composition et la gestion des images, <br/>            permettant une manipulation efficace des images multi-cadres au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le tableau de cadres à ajouter |

### Method: add_page(page) {#add_page_page_4}


```
 add_page(page) 
```

Incorporez une nouvelle page dans l’image existante de manière fluide, en élargissant son contenu <br/>            et sa polyvalence. Utilisez cette méthode pour améliorer la composition et la <br/>            gestion de documents, permettant une manipulation efficace des images multipages dans votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| page | [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | La page à ajouter. |

### Method: adjust_brightness(brightness) {#adjust_brightness_brightness_5}


```
 adjust_brightness(brightness) 
```

Mettez en œuvre le réglage de la _luminosité_ pour l'image, permettant la <br/>            modification des niveaux de luminance globaux. Intégrez cette méthode dans votre flux de travail de traitement d'image <br/>            pour améliorer la visibilité et la qualité visuelle des <br/>            images au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| luminosité | int | Valeur de luminosité. |


**See also:**

**[Example # 1](#example_128)**: The following example performs brightness correction of a TIFF image.


### Method: adjust_contrast(contrast) {#adjust_contrast_contrast_6}


```
 adjust_contrast(contrast) 
```

Améliorez le contraste de l'[Image](/imaging/python-net/aspose.imaging/image/) instance, <br/>            amplifiant les différences entre ses zones claires et sombres. Intégrez cette <br/>            fonctionnalité pour améliorer la clarté visuelle et la qualité globale de l'image <br/>            au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| contraste | float | Valeur de contraste (dans la plage [-100 ; 100]) |


**See also:**

**[Example # 1](#example_129)**: The following example performs contrast correction of a TIFF image.


### Method: adjust_gamma(gamma) {#adjust_gamma_gamma_7}


```
 adjust_gamma(gamma) 
```

Appliquez une correction gamma à l'image, ajustant les intensités des pixels pour obtenir <br/> l'équilibre des couleurs souhaité. Intégrez cette méthode dans votre flux de traitement d'image <br/> afin d'améliorer la qualité visuelle et d'augmenter la précision des analyses ou affichages subséquents <br/> au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | Coefficient gamma pour les canaux rouge, vert et bleu |


**See also:**

**[Example # 1](#example_126)**: The following example performs gamma-correction of a TIFF image.


### Method: adjust_gamma(gamma_red, gamma_green, gamma_blue) {#adjust_gamma_gamma_red_gamma_green_gamma_blue_8}


```
 adjust_gamma(gamma_red, gamma_green, gamma_blue) 
```

Effectuez une correction gamma sur l'image en utilisant des coefficients individuels pour les canaux rouge, <br/> vert et bleu, permettant des ajustements fins de l'équilibre des couleurs <br/> et du contraste. Intégrez cette méthode dans votre pipeline de traitement d'image pour <br/> obtenir un contrôle précis du rendu des couleurs et améliorer la fidélité visuelle au sein <br/> de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma_red | float | Coefficient gamma pour le canal rouge |
| gamma_green | float | Coefficient gamma pour le canal vert |
| gamma_blue | float | Coefficient gamma pour le canal bleu |


**See also:**

**[Example # 1](#example_127)**: The following example performs gamma-correction of a TIFF image applying diff...


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

Mettez en œuvre la binarisation de l'image en utilisant l'algorithme de seuillage adaptatif de Bradley <br/> avec seuillage d'image intégrale. Cette approche calcule dynamiquement les seuils locaux <br/> en fonction du voisinage de l'image, améliorant l'adaptabilité aux <br/> variations d'éclairage et assurant une segmentation robuste pour les tâches de traitement <br/> subséquentes au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| brightness_difference | float | La différence de luminosité entre le pixel et la moyenne d'une fenêtre de pixels de s x s<br/>            centrée autour de ce pixel. |
| window_size | int | La taille de la fenêtre de pixels de s x s centrée autour de ce pixel |


**See also:**

**[Example # 1](#example_124)**: The following example binarizes a TIFF image with Bradley's adaptive threshol...


### Method: binarize_fixed(threshold) {#binarize_fixed_threshold_12}


```
 binarize_fixed(threshold) 
```

Appliquez la binarisation à l'image en utilisant un seuil prédéfini, la convertissant en <br/> une image binaire avec des régions de premier plan et d'arrière-plan distinctes. Intégrez cette <br/> méthode dans votre flux de traitement d'image pour faciliter la segmentation et l'extraction de caractéristiques <br/> , améliorant la précision et l'efficacité de l'analyse d'image au sein <br/> de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| seuil | System.Byte | Valeur de seuil. Si la valeur de gris correspondante d'un pixel est supérieure au seuil, une valeur de<br/>            255 lui sera attribuée, 0 sinon. |


**See also:**

**[Example # 1](#example_122)**: The following example binarizes a TIFF image with the predefined threshold. B...


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


### Method: create_with_frame(frame)  [static] {#create_with_frame_frame_34}


```
 create_with_frame(frame) 
```

Initialise une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre tiff avec lequel initialiser l'image. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: create_with_frames(frames)  [static] {#create_with_frames_frames_35}


```
 create_with_frames(frames) 
```

Initialise une nouvelle instance de la classe [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frames | [TiffFrame[]](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Les cadres. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffImage](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) |  |


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_36}


```
 crop(left_shift, right_shift, top_shift, bottom_shift) 
```

Effectuez un recadrage de l'image en spécifiant des déplacements vers la gauche, la droite, le haut et <br/> le bas. Cette méthode permet une sélection précise de la partie souhaitée de <br/> l'image, facilitant la suppression efficace des zones indésirables et la mise en avant du <br/> contenu essentiel. Intégrez cette fonctionnalité dans votre pipeline de traitement d'image <br/> pour améliorer la clarté et la composition selon les besoins au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| left_shift | int | Le décalage à gauche. |
| right_shift | int | Le décalage à droite. |
| top_shift | int | Le décalage supérieur. |
| bottom_shift | int | Le décalage inférieur. |


**See also:**

**[Example # 1](#example_121)**: The following example crops a TIFF image. The cropping area is specified via ...


### Method: crop(rectangle) {#crop_rectangle_37}


```
 crop(rectangle) 
```

Recadrez l'image en utilisant une région rectangulaire spécifiée, permettant une sélection précise du <br/> contenu souhaité. Intégrez cette méthode dans votre flux de traitement d'image pour <br/> supprimer efficacement les zones indésirables et vous concentrer sur les détails essentiels, améliorant la <br/> clarté globale et la composition de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |


**See also:**

**[Example # 1](#example_120)**: The following example crops a TIFF image. The cropping area is be specified v...


### Method: dither(dithering_method, bits_count) {#dither_dithering_method_bits_count_38}


```
 dither(dithering_method, bits_count) 
```

Effectue un tramage sur l'image actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |

### Method: dither(dithering_method, bits_count, custom_palette) {#dither_dithering_method_bits_count_custom_palette_39}


```
 dither(dithering_method, bits_count, custom_palette) 
```

Exécutez le dithering sur l'image actuelle pour améliorer sa qualité visuelle et réduire les artefacts de bandes de couleur. Intégrez cette méthode dans votre flux de traitement d'image <br/> afin d'assurer des transitions plus fluides entre les couleurs, résultant en une apparence d'image globale <br/> améliorée et une meilleure clarté.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dithering_method | [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | La méthode de tramage. |
| bits_count | int | Le nombre final de bits pour le dithering. |
| custom_palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette personnalisée pour le dithering. |

### Method: embed_digital_signature(password) {#embed_digital_signature_password_40}


```
 embed_digital_signature(password) 
```

Intégrez une signature numérique basée sur le mot de passe fourni dans chaque page de l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mot de passe | string | Le mot de passe utilisé pour générer les données de signature numérique. |

### Method: filter(rectangle, options) {#filter_rectangle_options_41}


```
 filter(rectangle, options) 
```

Filtrez le contenu à l'intérieur du rectangle spécifié, en appliquant un filtre de traitement d'image <br/>            désigné pour améliorer ou modifier la région sélectionnée. Intégrez cette méthode <br/>            dans votre flux de manipulation d'images pour obtenir des améliorations ciblées ou <br/>            des transformations dans votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| options | [FilterOptionsBase](/imaging/python-net/aspose.imaging.imagefilters.filteroptions/filteroptionsbase/) | Les options. |

### Method: get_argb_32_pixel(x, y) {#get_argb_32_pixel_x_y_42}


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


### Method: get_default_argb_32_pixels(rectangle) {#get_default_argb_32_pixels_rectangle_43}


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


### Method: get_default_options(args) {#get_default_options_args_44}


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


### Method: get_default_pixels(rectangle, partial_pixel_loader) {#get_default_pixels_rectangle_partial_pixel_loader_45}


```
 get_default_pixels(rectangle, partial_pixel_loader) 
```

Obtient le tableau de pixels par défaut en utilisant le chargeur de pixels partiel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle pour obtenir les pixels. |
| partial_pixel_loader | [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Le chargeur partiel de pixels. |

### Method: get_default_raw_data(rectangle, partial_raw_data_loader, raw_data_settings) {#get_default_raw_data_rectangle_partial_raw_data_loader_raw_data_settings_46}


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

### Method: get_default_raw_data(rectangle, raw_data_settings) {#get_default_raw_data_rectangle_raw_data_settings_47}


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


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_48}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_49}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_50}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_51}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_52}


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


### Method: get_modify_date(use_default) {#get_modify_date_use_default_53}


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


### Method: get_original_options() {#get_original_options__54}


```
 get_original_options() 
```

Récupérez les options dérivées des paramètres du fichier original, facilitant la préservation transparente <br/> des paramètres clés tels que la profondeur de couleur et d'autres attributs essentiels de <br/> l'image originale. Utilisez cette méthode pour maintenir la fidélité et la cohérence dans <br/> les tâches de traitement d'image, garantissant des résultats optimaux sans altérations inutiles.<br/> Par exemple, si nous chargeons une image PNG noir et blanc avec 1 bit par pixel puis l'enregistrons en utilisant le<br/> [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/) méthode, l'image PNG de sortie avec 8 bits par pixel sera produite.<br/> Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options basées sur les paramètres du fichier original. |


### Method: get_pixel(x, y) {#get_pixel_x_y_55}


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


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_56}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_57}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_58}


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


### Method: get_skew_angle() {#get_skew_angle__59}


```
 get_skew_angle() 
```

Obtient l'angle d'inclinaison.<br/>            Cette méthode s'applique aux documents texte numérisés, pour déterminer l'angle d'inclinaison lors du scan.

**Returns**

| Type | Description |
| :- | :- |
| float | L'angle d'inclinaison, en degrés. |


### Method: insert_frame(index, frame) {#insert_frame_index_frame_60}


```
 insert_frame(index, frame) 
```

Insérez la nouvelle trame à l'index spécifié dans la séquence de trames, assurant <br/> un contrôle précis de l'agencement des trames. Utilisez cette méthode pour gérer les séquences de trames <br/> efficacement, facilitant la manipulation dynamique et l'organisation du contenu d'image <br/> au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index du _frame_. |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre pour l'insertion. |

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

Utilisez la méthode NormalizeAngle spécifiquement conçue pour les documents texte numérisés <br/> afin de rectifier les scans inclinés, assurant un alignement précis. Intégrez sans couture <br/> cette fonctionnalité dans vos flux de traitement de texte pour améliorer la <br/> lisibilité et la qualité des documents, augmentant l'efficacité globale de la reconnaissance <br/> de texte et des tâches d'analyse.<br/> Cette méthode utilise [RasterImage.get_skew_angle()](/imaging/python-net/aspose.imaging/rasterimage/) et [TiffImage.rotate(angle, resize_proportionally, background_color)](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffimage/) méthodes.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| resize_proportionally | bool | si défini sur <c>true</c> votre taille d'image sera modifiée selon les projections du rectangle tourné (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |

### Method: read_argb_32_scan_line(scan_line_index) {#read_argb_32_scan_line_scan_line_index_80}


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


### Method: read_scan_line(scan_line_index) {#read_scan_line_scan_line_index_81}


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


### Method: remove_frame(frame) {#remove_frame_frame_82}


```
 remove_frame(frame) 
```

Supprimez efficacement la trame spécifiée de la séquence d'images, facilitant <br/> une gestion simplifiée des trames au sein de votre application. Intégrez cette fonctionnalité <br/> pour améliorer la précision et la flexibilité de la manipulation des trames, assurant une <br/> organisation et une présentation fluides du contenu d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre à supprimer. |

### Method: remove_frame(index) {#remove_frame_index_83}


```
 remove_frame(index) 
```

Supprime la trame par son index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index du cadre à supprimer. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre supprimé. |


### Method: remove_frame_by_index(index) {#remove_frame_by_index_index_84}


```
 remove_frame_by_index(index) 
```

Supprime la trame par son index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Index du cadre à supprimer. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre supprimé. |


### Method: replace_argb(old_color_argb, old_color_diff, new_color_argb) {#replace_argb_old_color_argb_old_color_diff_new_color_argb_85}


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

### Method: replace_color(old_color, old_color_diff, new_color) {#replace_color_old_color_old_color_diff_new_color_86}


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

### Method: replace_color(old_color_argb, old_color_diff, new_color_argb) {#replace_color_old_color_argb_old_color_diff_new_color_argb_87}


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

### Method: replace_frame(index, new_frame) {#replace_frame_index_new_frame_88}


```
 replace_frame(index, new_frame) 
```

Remplacez la trame à la position désignée par une autre trame de manière fluide, <br/> facilitant la gestion dynamique des trames au sein de la séquence d'images. Intégrez cette <br/> méthode pour améliorer la flexibilité et la précision de la manipulation des trames, assurant <br/> une organisation optimale et une présentation du contenu d'image au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | La position du cadre basée sur zéro. |
| new_frame | [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre pour remplacer celui à l'_index_ spécifié. |

**Returns**

| Type | Description |
| :- | :- |
| [TiffFrame](/imaging/python-net/aspose.imaging.fileformats.tiff/tiffframe/) | Le cadre supprimé. |


### Method: replace_non_transparent_colors(new_color) {#replace_non_transparent_colors_new_color_89}


```
 replace_non_transparent_colors(new_color) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color | [Color](/imaging/python-net/aspose.imaging/color/) |  |

### Method: replace_non_transparent_colors(new_color_argb) {#replace_non_transparent_colors_new_color_argb_90}


```
 replace_non_transparent_colors(new_color_argb) 
```

Remplace toutes les couleurs non transparentes par une nouvelle couleur et préserve la valeur alpha originale pour conserver des bords lisses.<br/>                Note : si vous l'utilisez sur des images sans transparence, toutes les couleurs seront remplacées par une seule.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_argb | int | Nouvelle valeur ARGB de couleur pour remplacer les couleurs non transparentes. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_91}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_92}


```
 resize(new_width, new_height, resize_type) 
```

Effectuez une opération de redimensionnement proportionnel de l'image, en conservant son ratio d'aspect <br/> tout en ajustant ses dimensions. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images <br/> au sein de votre application, assurant une représentation visuelle cohérente de l'intégrité du contenu <br/> .<br/> Le redimensionnement proportionnel redimensionnera chaque trame selon le ratio de _newWidth_/width et _newHeight_/height.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Le type de redimensionnement. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_93}


```
 resize(new_width, new_height, settings) 
```

Ajustez la taille de l'image en fonction des paramètres spécifiés, permettant un contrôle précis <br/> des dimensions, du ratio d'aspect et du comportement de mise à l'échelle. Intégrez cette <br/> méthode dans votre flux de traitement d'image pour réaliser des opérations de redimensionnement personnalisées <br/> adaptées aux exigences spécifiques de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement. |

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_94}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_95}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_96}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_97}


```
 resize_height_proportionally(new_height, resize_type) 
```

Effectuez un ajustement proportionnel de la hauteur de l'image, en conservant son ratio d'aspect <br/> pour une intégrité visuelle cohérente. Utilisez cette méthode pour redimensionner dynamiquement <br/> les images au sein de votre application, assurant un affichage optimal sur diverses plateformes <br/> et appareils sans compromettre la qualité du contenu.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_98}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_99}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_proportional(new_width, new_height, resize_type) {#resize_proportional_new_width_new_height_resize_type_100}


```
 resize_proportional(new_width, new_height, resize_type) 
```

Effectuez une opération de redimensionnement proportionnel de l'image, en conservant son ratio d'aspect <br/> tout en ajustant ses dimensions. Utilisez cette méthode pour mettre à l'échelle dynamiquement les images <br/> au sein de votre application, assurant une représentation visuelle cohérente de l'intégrité du contenu <br/> .<br/> Le redimensionnement proportionnel redimensionnera chaque trame selon le ratio de _newWidth_/width et _newHeight_/height.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Le type de redimensionnement. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_101}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_102}


```
 resize_width_proportionally(new_width, resize_type) 
```

Ajustez la largeur de l'image tout en maintenant son ratio d'aspect, assurant <br/> un redimensionnement proportionnel pour une présentation visuelle optimale. Utilisez cette méthode pour <br/> mettre à l'échelle dynamiquement les images au sein de votre application, facilitant un rendu cohérent et <br/> esthétiquement agréable sur divers contextes d'affichage.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_103}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_104}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle) {#rotate_angle_105}


```
 rotate(angle) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |

### Method: rotate(angle, resize_proportionally, background_color) {#rotate_angle_resize_proportionally_background_color_106}


```
 rotate(angle, resize_proportionally, background_color) 
```

Faites pivoter l'image autour de son point central d'un angle spécifié, permettant des ajustements d'orientation précis <br/> . Intégrez cette fonctionnalité dans votre pipeline de traitement d'image <br/> pour faciliter des transformations précises, assurant un alignement optimal et <br/> la présentation du contenu visuel au sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |
| resize_proportionally | bool | si défini sur <c>true</c> votre taille d'image sera modifiée selon les projections du rectangle tourné (points d'angle); sinon les dimensions restent inchangées et seul le contenu interne de l'image est tourné. |
| background_color | [Color](/imaging/python-net/aspose.imaging/color/) | Couleur de l'arrière-plan. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_107}


```
 rotate_flip(rotate_flip_type) 
```

Effectuez une rotation, un retournement ou une combinaison des deux opérations exclusivement sur la <br/> trame active. Cette méthode permet une manipulation précise des trames individuelles au sein <br/> de la séquence d'images, améliorant la flexibilité de l'édition et de la composition d'images au <br/> sein de votre application.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Le type de retournement de rotation. |


**See also:**

**[Example # 1](#example_118)**: This example loads a TIFF image, rotates it by 90 degrees clockwise and optio...


### Method: rotate_flip_all(rotate_flip) {#rotate_flip_all_rotate_flip_108}


```
 rotate_flip_all(rotate_flip) 
```

Fait pivoter le retournement complet.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Le retournement de rotation. |

### Method: save(file_path) {#save_file_path_109}


```
 save(file_path) 
```

Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer l'image. |

### Method: save(file_path, options) {#save_file_path_options_110}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_111}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_112}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_113}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save(stream, options_base) {#save_stream_options_base_114}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_115}


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

### Method: save_argb_32_pixels(rectangle, pixels) {#save_argb_32_pixels_rectangle_pixels_116}


```
 save_argb_32_pixels(rectangle, pixels) 
```

Enregistre les pixels ARGB 32 bits.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Le tableau de pixels ARGB 32 bits. |

### Method: save_cmyk_32_pixels(rectangle, pixels) {#save_cmyk_32_pixels_rectangle_pixels_117}


```
 save_cmyk_32_pixels(rectangle, pixels) 
```

Enregistre les pixels.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | int[] | Les pixels CMYK présentés sous forme de valeurs entières 32 bits. |

### Method: save_cmyk_pixels(rectangle, pixels) {#save_cmyk_pixels_rectangle_pixels_118}


```
 save_cmyk_pixels(rectangle, pixels) 
```

Enregistre les pixels.<br/>            Cette méthode est obsolète. Veuillez utiliser de manière plus efficace la méthode [RasterImage.save_cmyk_32_pixels(rectangle, pixels)](/imaging/python-net/aspose.imaging/rasterimage/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle où enregistrer les pixels. |
| pixels | [CmykColor[]](/imaging/python-net/aspose.imaging/cmykcolor/) | Le tableau de pixels CMYK. |

### Method: save_pixels(rectangle, pixels) {#save_pixels_rectangle_pixels_119}


```
 save_pixels(rectangle, pixels) 
```

Enregistre les pixels internes principaux.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |
| pixels | [Color[]](/imaging/python-net/aspose.imaging/color/) | Les pixels. |

### Method: save_raw_data(data, data_offset, rectangle, raw_data_settings) {#save_raw_data_data_data_offset_rectangle_raw_data_settings_120}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_121}


```
 save_to_stream(stream) 
```

Enregistre l'image dans le flux

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom |  |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_122}


```
 save_to_stream_with_options(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_123}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_124}


```
 save_with_options(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_125}


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

### Method: set_argb_32_pixel(x, y, argb_32_color) {#set_argb_32_pixel_x_y_argb_32_color_126}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_127}


```
 set_palette(palette, update_colors) 
```

Définit la palette d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: set_pixel(x, y, color) {#set_pixel_x_y_color_128}


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

### Method: set_resolution(dpi_x, dpi_y) {#set_resolution_dpi_x_dpi_y_129}


```
 set_resolution(dpi_x, dpi_y) 
```

Établit la résolution pour le [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/), permettant <br/>            un contrôle précis du rendu et des propriétés d'affichage de l'image. Intégrez cette <br/>            fonctionnalité pour optimiser la sortie visuelle et garantir la compatibilité avec divers <br/>            appareils et plateformes de sortie, améliorant l'expérience utilisateur globale.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| dpi_x | float | La résolution horizontale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |
| dpi_y | float | La résolution verticale, en points par pouce, du [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/). |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_130}


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


### Method: write_argb_32_scan_line(scan_line_index, argb_32_pixels) {#write_argb_32_scan_line_scan_line_index_argb_32_pixels_131}


```
 write_argb_32_scan_line(scan_line_index, argb_32_pixels) 
```

Écrit la ligne de numérisation complète à l'index de ligne de numérisation spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| scan_line_index | int | Indice basé sur zéro de la ligne de numérisation. |
| argb_32_pixels | int[] | Le tableau de couleurs ARGB 32 bits à écrire. |

### Method: write_scan_line(scan_line_index, pixels) {#write_scan_line_scan_line_index_pixels_132}


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
### This example loads a TIFF image, rotates it by 90 degrees clockwise and optionally flips the image horizontally and(or) vertically. {#example_118}
``` python

from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
rotate_flip_types = [RotateFlipType.ROTATE_90_FLIP_NONE, RotateFlipType.ROTATE_90_FLIP_X, RotateFlipType.ROTATE_90_FLIP_XY, RotateFlipType.ROTATE_90_FLIP_Y]
for rotate_flip_type in rotate_flip_types:
	# Tournez, retournez et enregistrez dans le fichier de sortie.
	with aspycore.as_of(Image.load(join(dir_, "sample.tif")), TiffImage) as image:
		image.rotate_flip(rotate_flip_type)
		image.save(join(dir_, "sample." + rotate_flip_type + ".png"), PngOptions())


```

### The following example loads a TIFF image and prints information about raw data format and alpha channel. {#example_119}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join as path_join


dir_ = "c:\\temp"
file_name = path_join(dir_, "sample.tif")
with Image.load(file_name) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Si la trame TIFF active possède un canal alpha, alors l'ensemble de l'image TIFF est considéré comme ayant un canal alpha.
	print("ImageFile={0}, FileFormat={1}, HasAlpha={2}".format(file_name, tiff_image.raw_data_format, tiff_image.has_alpha))
	i = 1
	for frame in tiff_image.frames:
		print("Frame={0}, FileFormat={1}, HasAlpha={2}".format(i, frame.raw_data_format, frame.has_alpha))
		i += 1

# La sortie peut ressembler à ceci :
# ImageFile=c:\temp\sample.tif, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=1, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False
# Frame=2, FileFormat=RgbIndexed1Bpp, used channels: 1, HasAlpha=False


```

### The following example crops a TIFF image. The cropping area is be specified via aspose.imaging.Rectangle. {#example_120}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image, Rectangle
from aspose.imaging.imageoptions import PngOptions
from aspose.imaging.fileformats.tiff import TiffImage
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Recadrez l'image. La zone de recadrage est la zone centrale rectangulaire de l'image.
	area = Rectangle(tiff_image.width // 4, tiff_image.height // 4, tiff_image.width // 2,
					 tiff_image.height // 2)
	tiff_image.crop(area)
	# Enregistrez l'image recadrée au format PNG
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example crops a TIFF image. The cropping area is specified via Left, Top, Right, Bottom margins. {#example_121}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image       
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = r"c:\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Recadrez à nouveau. Définissez une marge de 10% de la taille de l’image.
	horizontal_margin: int = tiff_image.width // 10
	vertical_margin: int = tiff_image.height // 10
	tiff_image.crop(horizontal_margin, horizontal_margin, vertical_margin, vertical_margin)
	# Enregistrez l’image recadrée au format PNG.
	tiff_image.save(join(dir_, "sample.Crop.png"), PngOptions())


```

### The following example binarizes a TIFF image with the predefined threshold. Binarized images contain only 2 colors - black and white. {#example_122}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Binarisez l’image avec une valeur de seuil de 127.
	# Si la valeur de gris correspondante d’un pixel est supérieure à 127, une valeur de 255 lui sera attribuée, sinon 0.
	tiff_image.binarize_fixed(127)
	tiff_image.save(join(dir_, "sample.BinarizeFixed.png"), PngOptions())


```

### The following example binarizes a TIFF image with Bradley's adaptive thresholding algorithm with the specified window size. Binarized images contain only 2 colors - black and white. {#example_124}
``` python
from os.path import join
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Binarisez l’image avec une différence de luminosité de 5. La luminosité est une différence entre un pixel et la moyenne d’une fenêtre de 10×10 pixels centrée sur ce pixel.
	tiff_image.binarize_bradley(5, 10)
	tiff_image.save(join(dir_, "sample.BinarizeBradley5_10x10.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image. {#example_126}
``` python
import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_: str = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Définissez le coefficient gamma pour les canaux rouge, vert et bleu.
	tiff_image.adjust_gamma(2.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs gamma-correction of a TIFF image applying different coefficients for color components. {#example_127}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Définissez des coefficients gamma individuels pour les canaux rouge, vert et bleu.
	tiff_image.adjust_gamma(1.5, 2.5, 3.5)
	tiff_image.save(join(dir_, "sample.AdjustGamma.png"), PngOptions())


```

### The following example performs brightness correction of a TIFF image. {#example_128}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Définissez la valeur de luminosité. Les valeurs acceptées de luminosité sont dans la plage [-255, 255].
	tiff_image.adjust_brightness(50)
	tiff_image.save(join(dir_, "sample.AdjustBrightness.png"), PngOptions())


```

### The following example performs contrast correction of a TIFF image. {#example_129}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.imageoptions import PngOptions
from os.path import join

dir_ = "c:\\temp"
with Image.load(join(dir_, "sample.tif")) as image:
	tiff_image = aspycore.as_of(image, TiffImage)
	# Définissez la valeur de contraste. Les valeurs acceptées de contraste sont dans la plage [-100f, 100f].
	tiff_image.adjust_contrast(50.0)
	tiff_image.save(join(dir_, "sample.AdjustContrast.png"), PngOptions())


```

### Create Graphics Path from Path Resources in TIFF image. {#example_210}
``` python

import aspose.pycore as aspycore
from aspose.imaging import Image, Graphics, Color, Pen
from aspose.imaging.fileformats.tiff import TiffImage
from aspose.imaging.fileformats.tiff.pathresources import PathResourceConverter

with aspycore.as_of(Image.load("Bottle.tif"), TiffImage) as image:
	# Crée le GraphicsPath en utilisant les PathResources de l'image TIFF
	active_frame = image.active_frame
	graphics_path = PathResourceConverter.to_graphics_path(active_frame.path_resource, active_frame.size)
	graphics = Graphics(image)
	# Dessinez une ligne rouge et enregistrez l'image
	graphics.draw_path(Pen(Color.red, 10), graphics_path)
	image.save("BottleWithRedBorder.tif")


```

