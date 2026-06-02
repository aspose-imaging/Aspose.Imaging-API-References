---
title: "Classe MetaImage"
type: docs
weight: 3140
url: /fr/python-net/aspose.imaging.fileformats.emf/metaimage/
---

**Summary:** Base class for Meta object classes

**Module:** [aspose.imaging.fileformats.emf](/imaging/python-net/aspose.imaging.fileformats.emf/)

**Full Name:** aspose.imaging.fileformats.emf.MetaImage

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, IObjectWithSizeF, VectorImage

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
| libéré | bool | r | Obtient une valeur indiquant si cette instance est libérée. |
| exif_data | [ExifData](/imaging/python-net/aspose.imaging.exif/exifdata/) | r/w | Obtient ou définit l'instance Exif. |
| file_format | [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | r | Obtient une valeur du format de fichier |
| has_background_color | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| height | int | r | Obtient la hauteur de l'image. |
| height_f | float | r | Obtient la hauteur de l'objet, en pouces. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| is_cached | bool | r | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtient les métadonnées de l’image. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| records | [MetaObjectList](/imaging/python-net/aspose.imaging.fileformats.emf/metaobjectlist/) | r/w | Obtient ou définit les enregistrements. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtient la taille de l'objet. |
| size_f | [SizeF](/imaging/python-net/aspose.imaging/sizef/) | r | Obtient la taille de l'objet, en pouces. |
| use_palette | bool | r | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| width | int | r | Obtient la largeur de l'image. |
| width_f | float | r | Obtient la largeur de l'objet, en pouces. |
| xmp_data | [XmpPacketWrapper](/imaging/python-net/aspose.imaging.xmp/xmppacketwrapper/) | r/w | Obtient ou définit les données Xmp. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| cache_data() | Met en cache les données et garantit qu'aucun chargement supplémentaire de données ne sera effectué à partir du [DataStreamSupporter.data_stream_container](/imaging/python-net/aspose.imaging/datastreamsupporter/) sous-jacent. |
| [can_load(file_path)](#can_load_file_path_1) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié. |
| [can_load(file_path, load_options)](#can_load_file_path_load_options_2) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_load(stream)](#can_load_stream_3) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load(stream, load_options)](#can_load_stream_load_options_4) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_stream(stream)](#can_load_stream_stream_5) | Détermine si l'image peut être chargée depuis le flux spécifié. |
| [can_load_stream_with_options(stream, load_options)](#can_load_stream_with_options_stream_load_options_6) | Détermine si l'image peut être chargée depuis le flux spécifié et éventuellement en utilisant les _loadOptions_ spécifiés. |
| [can_load_with_options(file_path, load_options)](#can_load_with_options_file_path_load_options_7) | Détermine si l'image peut être chargée depuis le chemin de fichier spécifié et éventuellement en utilisant les options d'ouverture spécifiées. |
| [can_save(options)](#can_save_options_8) | Détermine si l'image peut être enregistrée au format de fichier spécifié représenté par les options d'enregistrement fournies. |
| [create(files)](#create_files_9) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(files, throw_exception_on_load_error)](#create_files_throw_exception_on_load_error_10) | Crée l'image multipage contenant les fichiers spécifiés. |
| [create(image_options, width, height)](#create_image_options_width_height_11) | Crée une nouvelle image en utilisant les options de création spécifiées. |
| [create(image_options, width, height, pixels)](#create_image_options_width_height_pixels_12) | Crée une instance de [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) à partir du tableau de pixels fourni.<br/>            <br/>            Vérifie que la largeur et la hauteur spécifiées correspondent aux dimensions des données de pixels.<br/>            Cette méthode ne peut être utilisée que lorsque la bibliothèque est en mode Licensed. |
| [create(images)](#create_images_13) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create(images, dispose_images)](#create_images_dispose_images_14) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [create(multipage_create_options)](#create_multipage_create_options_15) | Crée les options de création multipage spécifiées. |
| [create_from_files(files)](#create_from_files_files_16) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_files(files, throw_exception_on_load_error)](#create_from_files_files_throw_exception_on_load_error_17) | Crée l'image multipage contenant les fichiers spécifiés en tant que pages à chargement différé. |
| [create_from_images(images)](#create_from_images_images_18) | Crée une nouvelle image en utilisant les images spécifiées comme pages |
| [create_from_images(images, dispose_images)](#create_from_images_images_dispose_images_19) | Crée une nouvelle image à partir des images spécifiées en tant que pages. |
| [crop(left_shift, right_shift, top_shift, bottom_shift)](#crop_left_shift_right_shift_top_shift_bottom_shift_20) | Recadrer l'image avec des déplacements. |
| [crop(rectangle)](#crop_rectangle_21) | Recadre le rectangle spécifié. |
| [get_default_options(args)](#get_default_options_args_22) | Obtient les options d'image par défaut. |
| [get_embedded_images()](#get_embedded_images__23) | Obtient les images intégrées. |
| [get_file_format(file_path)](#get_file_format_file_path_24) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_25) | Obtient le format de fichier. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_26) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_27) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_28) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_missed_fonts()](#get_missed_fonts__29) | Renvoie la liste des polices utilisées à l'intérieur du métafichier mais non trouvées. |
| [get_original_options()](#get_original_options__30) | Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_31) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_32) | Obtient une largeur proportionnelle. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_33) | Convertit en aps. |
| [get_used_fonts()](#get_used_fonts__34) | Renvoie la liste des polices utilisées dans le métafichier. |
| [load(file_path)](#load_file_path_35) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(file_path, load_options)](#load_file_path_load_options_36) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(stream)](#load_stream_37) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_38) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream(stream)](#load_stream_stream_39) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_40) | Charge une nouvelle image depuis le flux spécifié. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_41) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| remove_background() | Supprime l'arrière-plan. |
| [remove_background(settings)](#remove_background_settings_42) | Supprime l'arrière-plan. |
| remove_metadata() | Supprime les métadonnées. |
| [resize(new_width, new_height)](#resize_new_width_new_height_43) | Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_44) | Redimensionne la nouvelle largeur spécifiée. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_45) | Redimensionne l'image avec des options étendues. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_46) | Redimensionne l'image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_47) | Redimensionne l'image. |
| [resize_canvas(new_rectangle)](#resize_canvas_new_rectangle_48) | Redimensionne le canevas. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_49) | Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_50) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_51) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_52) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_53) | Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_54) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_55) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_56) | Redimensionne la largeur proportionnellement. |
| [rotate(angle)](#rotate_angle_57) | Faire pivoter l'image autour du centre. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_58) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_59) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_60) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_61) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_62) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_63) | Enregistre les données dans le _stream_ spécifié. |
| [save(stream, options_base)](#save_stream_options_base_64) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_65) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream(stream)](#save_to_stream_stream_66) | Enregistre les données de l'objet dans le flux spécifié. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_67) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_68) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_69) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_70) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_71) | Définit la palette d'image. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_72) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente l'instance [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Method: can_load(file_path)  [static] {#can_load_file_path_1}


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


### Method: can_load(file_path, load_options)  [static] {#can_load_file_path_load_options_2}


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


### Method: can_load(stream)  [static] {#can_load_stream_3}


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


### Method: can_load(stream, load_options)  [static] {#can_load_stream_load_options_4}


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


### Method: can_load_stream(stream)  [static] {#can_load_stream_stream_5}


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


### Method: can_load_stream_with_options(stream, load_options)  [static] {#can_load_stream_with_options_stream_load_options_6}


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


### Method: can_load_with_options(file_path, load_options)  [static] {#can_load_with_options_file_path_load_options_7}


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


### Method: can_save(options) {#can_save_options_8}


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


### Method: create(files)  [static] {#create_files_9}


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


### Method: create(files, throw_exception_on_load_error)  [static] {#create_files_throw_exception_on_load_error_10}


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


### Method: create(image_options, width, height)  [static] {#create_image_options_width_height_11}


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


### Method: create(image_options, width, height, pixels)  [static] {#create_image_options_width_height_pixels_12}


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


### Method: create(images)  [static] {#create_images_13}


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


### Method: create(images, dispose_images)  [static] {#create_images_dispose_images_14}


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


### Method: create(multipage_create_options)  [static] {#create_multipage_create_options_15}


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


### Method: create_from_files(files)  [static] {#create_from_files_files_16}


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


### Method: create_from_files(files, throw_exception_on_load_error)  [static] {#create_from_files_files_throw_exception_on_load_error_17}


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


### Method: create_from_images(images)  [static] {#create_from_images_images_18}


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


### Method: create_from_images(images, dispose_images)  [static] {#create_from_images_images_dispose_images_19}


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


### Method: crop(left_shift, right_shift, top_shift, bottom_shift) {#crop_left_shift_right_shift_top_shift_bottom_shift_20}


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

### Method: crop(rectangle) {#crop_rectangle_21}


```
 crop(rectangle) 
```

Recadre le rectangle spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le rectangle. |

### Method: get_default_options(args) {#get_default_options_args_22}


```
 get_default_options(args) 
```

Obtient les options d'image par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | System.Object | Les arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'image par défaut. |


### Method: get_embedded_images() {#get_embedded_images__23}


```
 get_embedded_images() 
```

Obtient les images intégrées.

**Returns**

| Type | Description |
| :- | :- |
| [EmbeddedImage[]](/imaging/python-net/aspose.imaging/embeddedimage/) | Tableau d'images |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_24}


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


### Method: get_file_format(stream)  [static] {#get_file_format_stream_25}


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


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_26}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_27}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_28}


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


### Method: get_missed_fonts() {#get_missed_fonts__29}


```
 get_missed_fonts() 
```

Renvoie la liste des polices utilisées à l'intérieur du métafichier mais non trouvées.

**Returns**

| Type | Description |
| :- | :- |
| string[] | La liste des polices |


### Method: get_original_options() {#get_original_options__30}


```
 get_original_options() 
```

Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options basées sur les paramètres du fichier original. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_31}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_32}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_33}


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


### Method: get_used_fonts() {#get_used_fonts__34}


```
 get_used_fonts() 
```

Renvoie la liste des polices utilisées dans le métafichier.

**Returns**

| Type | Description |
| :- | :- |
| string[] | La liste des polices |


### Method: load(file_path)  [static] {#load_file_path_35}


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


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_36}


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


### Method: load(stream)  [static] {#load_stream_37}


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


### Method: load(stream, load_options)  [static] {#load_stream_load_options_38}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_39}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_40}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_41}


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


### Method: remove_background(settings) {#remove_background_settings_42}


```
 remove_background(settings) 
```

Supprime l'arrière-plan.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| settings | [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Les paramètres. |

### Method: resize(new_width, new_height) {#resize_new_width_new_height_43}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |

### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_44}


```
 resize(new_width, new_height, resize_type) 
```

Redimensionne la nouvelle largeur spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_45}


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

### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_46}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_47}


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

### Method: resize_canvas(new_rectangle) {#resize_canvas_new_rectangle_48}


```
 resize_canvas(new_rectangle) 
```

Redimensionne le canevas.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_rectangle | [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Le nouveau rectangle. |


**See also:**

**[Example # 1](#example_181)**: The following example shows how to add a border with the specified margins ar...


### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_49}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_50}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_51}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_52}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_53}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_54}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |

### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_55}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_56}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle) {#rotate_angle_57}


```
 rotate(angle) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_58}


```
 rotate_flip(rotate_flip_type) 
```

Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Type de la rotation et du retournement. |

### Method: save(file_path) {#save_file_path_59}


```
 save(file_path) 
```

Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer l'image. |

### Method: save(file_path, options) {#save_file_path_options_60}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_61}


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

### Method: save(file_path, over_write) {#save_file_path_over_write_62}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_63}


```
 save(stream) 
```

Enregistre les données dans le _stream_ spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux. |

### Method: save(stream, options_base) {#save_stream_options_base_64}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_65}


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

### Method: save_to_stream(stream) {#save_to_stream_stream_66}


```
 save_to_stream(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_67}


```
 save_to_stream_with_options(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_68}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_69}


```
 save_with_options(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_70}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_71}


```
 set_palette(palette, update_colors) 
```

Définit la palette d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_72}


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

