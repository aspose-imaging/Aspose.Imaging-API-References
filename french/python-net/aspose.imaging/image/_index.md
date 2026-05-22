---
title: "Classe Image"
type: docs
weight: 5650
url: /fr/python-net/aspose.imaging/image/
---

**Summary:** The image is the base class for all type of images.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.Image

**Inheritance:** IObjectWithBounds, IMetadataContainer, IHasExifData, IHasMetadata, IHasXmpData, DataStreamSupporter

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
| has_background_color | bool | r/w | Obtient ou définit une valeur indiquant si l'image possède une couleur d'arrière-plan. |
| height | int | r | Obtient la hauteur de l'image. |
| interrupt_monitor | [InterruptMonitor](/imaging/python-net/aspose.imaging.multithreading/interruptmonitor/) | r/w | Obtient ou définit le moniteur d'interruption. |
| is_cached | bool | r | Obtient une valeur indiquant si les données de l'objet sont actuellement en cache et aucune lecture de données n'est requise. |
| metadata | [ImageMetadata](/imaging/python-net/aspose.imaging.metadata/imagemetadata/) | r | Obtient les métadonnées de l’image. |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | r/w | Obtient ou définit la palette de couleurs. La palette de couleurs n'est pas utilisée lorsque les pixels sont représentés directement. |
| size | [Size](/imaging/python-net/aspose.imaging/size/) | r | Obtient la taille de l'image. |
| [use_palette](#use_palette1) | bool | r | Obtient une valeur indiquant si la palette de l'image est utilisée. |
| width | int | r | Obtient la largeur de l'image. |
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
| [get_default_options(args)](#get_default_options_args_22) | Obtient les options par défaut. |
| [get_file_format(file_path)](#get_file_format_file_path_23) | Obtient le format de fichier. |
| [get_file_format(stream)](#get_file_format_stream_24) | Obtient le format de fichier. |
| [get_file_format_of_stream(stream)](#get_file_format_of_stream_stream_25) | Obtient le format de fichier. |
| [get_fitting_rectangle(rectangle, pixels, width, height)](#get_fitting_rectangle_rectangle_pixels_width_height_26) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_fitting_rectangle(rectangle, width, height)](#get_fitting_rectangle_rectangle_width_height_27) | Obtient le rectangle qui correspond à l'image actuelle. |
| [get_original_options()](#get_original_options__28) | Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre. |
| [get_proportional_height(width, height, new_width)](#get_proportional_height_width_height_new_width_29) | Obtient une hauteur proportionnelle. |
| [get_proportional_width(width, height, new_height)](#get_proportional_width_width_height_new_height_30) | Obtient une largeur proportionnelle. |
| [get_serialized_stream(image_options, clipping_rectangle, page_number)](#get_serialized_stream_image_options_clipping_rectangle_page_number_31) | Convertit en aps. |
| [load(file_path)](#load_file_path_32) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(file_path, load_options)](#load_file_path_load_options_33) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| [load(stream)](#load_stream_34) | Charge une nouvelle image depuis le flux spécifié. |
| [load(stream, load_options)](#load_stream_load_options_35) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream(stream)](#load_stream_stream_36) | Charge une nouvelle image depuis le flux spécifié. |
| [load_stream_with_options(stream, load_options)](#load_stream_with_options_stream_load_options_37) | Charge une nouvelle image depuis le flux spécifié. |
| [load_with_options(file_path, load_options)](#load_with_options_file_path_load_options_38) | Charge une nouvelle image depuis le chemin de fichier ou l'URL spécifié.<br/>            Si _filePath_ est un chemin de fichier, la méthode ouvre simplement le fichier.<br/>            Si _filePath_ est une URL, la méthode télécharge le fichier, le stocke temporairement, puis l'ouvre. |
| remove_metadata() | Supprime les métadonnées. |
| [resize(new_width, new_height)](#resize_new_width_new_height_39) | Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize(new_width, new_height, resize_type)](#resize_new_width_new_height_resize_type_40) | Redimensionne l'image. |
| [resize(new_width, new_height, settings)](#resize_new_width_new_height_settings_41) | Redimensionne l'image. |
| [resize_by_settings(new_width, new_height, settings)](#resize_by_settings_new_width_new_height_settings_42) | Redimensionne l'image. |
| [resize_by_type(new_width, new_height, resize_type)](#resize_by_type_new_width_new_height_resize_type_43) | Redimensionne l'image. |
| [resize_height_proportionally(new_height)](#resize_height_proportionally_new_height_44) | Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_height_proportionally(new_height, resize_type)](#resize_height_proportionally_new_height_resize_type_45) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally(new_height, settings)](#resize_height_proportionally_new_height_settings_46) | Redimensionne la hauteur proportionnellement. |
| [resize_height_proportionally_settings(new_height, settings)](#resize_height_proportionally_settings_new_height_settings_47) | Redimensionne la hauteur proportionnellement. |
| [resize_width_proportionally(new_width)](#resize_width_proportionally_new_width_48) | Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé. |
| [resize_width_proportionally(new_width, resize_type)](#resize_width_proportionally_new_width_resize_type_49) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally(new_width, settings)](#resize_width_proportionally_new_width_settings_50) | Redimensionne la largeur proportionnellement. |
| [resize_width_proportionally_settings(new_width, settings)](#resize_width_proportionally_settings_new_width_settings_51) | Redimensionne la largeur proportionnellement. |
| [rotate(angle)](#rotate_angle_52) | Faire pivoter l'image autour du centre. |
| [rotate_flip(rotate_flip_type)](#rotate_flip_rotate_flip_type_53) | Fait pivoter, retourner, ou pivoter et retourner l'image. |
| save() | Enregistre les données de l'image dans le flux sous-jacent. |
| [save(file_path)](#save_file_path_54) | Enregistre l'image à l'emplacement de fichier spécifié. |
| [save(file_path, options)](#save_file_path_options_55) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, options, bounds_rectangle)](#save_file_path_options_bounds_rectangle_56) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(file_path, over_write)](#save_file_path_over_write_57) | Enregistre les données de l'objet à l'emplacement de fichier spécifié. |
| [save(stream)](#save_stream_58) | Enregistre les données de l'objet dans le flux spécifié. |
| [save(stream, options_base)](#save_stream_options_base_59) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save(stream, options_base, bounds_rectangle)](#save_stream_options_base_bounds_rectangle_60) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream(stream)](#save_to_stream_stream_61) | Enregistre les données de l'objet dans le flux spécifié. |
| [save_to_stream_with_options(stream, options_base)](#save_to_stream_with_options_stream_options_base_62) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_to_stream_with_options_rect(stream, options_base, bounds_rectangle)](#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63) | Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options(file_path, options)](#save_with_options_file_path_options_64) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [save_with_options_rect(file_path, options, bounds_rectangle)](#save_with_options_rect_file_path_options_bounds_rectangle_65) | Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement. |
| [set_palette(palette, update_colors)](#set_palette_palette_update_colors_66) | Définit la palette d'image. |
| [try_set_metadata(metadata)](#try_set_metadata_metadata_67) | Essaie de définir une instance _metadata_, si cette instance [Image](/imaging/python-net/aspose.imaging/image/) prend en charge et implémente le type [IImageMetadataFormat](/imaging/python-net/aspose.imaging.metadata/iimagemetadataformat/). |


### Property: use_palette {#use_palette1}

Obtient une valeur indiquant si la palette de l'image est utilisée.

**See also:**

**[Example # 1](#example_221)**: Determine if the palette is used by the image.


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



**See also:**

**[Example # 1](#example_22)**: This example determines whether image can be loaded from a file.


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



**See also:**

**[Example # 1](#example_23)**: This example determines whether image can be loaded from a file stream.


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



**See also:**

**[Example # 1](#example_26)**: This example shows how to determine whether image can be saved to the specifi...


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



**See also:**

**[Example # 1](#example_4)**: This example creates a new Image file at some disk location as specified by S...


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

Obtient les options par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| args | System.Object | Les arguments. |

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Options par défaut |


### Method: get_file_format(file_path)  [static] {#get_file_format_file_path_23}


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



**See also:**

**[Example # 1](#example_24)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format(stream)  [static] {#get_file_format_stream_24}


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



**See also:**

**[Example # 1](#example_25)**: This example shows how to determine the image format without loading the enti...


### Method: get_file_format_of_stream(stream)  [static] {#get_file_format_of_stream_stream_25}


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


### Method: get_fitting_rectangle(rectangle, pixels, width, height)  [static] {#get_fitting_rectangle_rectangle_pixels_width_height_26}


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


### Method: get_fitting_rectangle(rectangle, width, height)  [static] {#get_fitting_rectangle_rectangle_width_height_27}


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


### Method: get_original_options() {#get_original_options__28}


```
 get_original_options() 
```

Obtient les options basées sur les paramètres du fichier original.<br/>            Cela peut être utile pour conserver la profondeur de couleur et d'autres paramètres de l'image originale inchangés.<br/>            Par exemple, si nous chargeons une image PNG noir-et-blanc avec 1 bit par pixel puis l'enregistrons en utilisant la<br/>            méthode [DataStreamSupporter.save(file_path)](/imaging/python-net/aspose.imaging/datastreamsupporter/), une image PNG de sortie avec 8 bits par pixel sera produite.<br/>            Pour éviter cela et enregistrer l'image PNG avec 1 bit par pixel, utilisez cette méthode pour obtenir les options d'enregistrement correspondantes et les transmettre<br/>            à la méthode [Image.save(file_path, options)](/imaging/python-net/aspose.imaging/image/) en tant que deuxième paramètre.

**Returns**

| Type | Description |
| :- | :- |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options basées sur les paramètres du fichier original. |


### Method: get_proportional_height(width, height, new_width)  [static] {#get_proportional_height_width_height_new_width_29}


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


### Method: get_proportional_width(width, height, new_height)  [static] {#get_proportional_width_width_height_new_height_30}


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


### Method: get_serialized_stream(image_options, clipping_rectangle, page_number) {#get_serialized_stream_image_options_clipping_rectangle_page_number_31}


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


### Method: load(file_path)  [static] {#load_file_path_32}


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



**See also:**

**[Example # 1](#example_1)**: This example demonstrates the loading of an existing Image file into an insta...


### Method: load(file_path, load_options)  [static] {#load_file_path_load_options_33}


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


### Method: load(stream)  [static] {#load_stream_34}


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



**See also:**

**[Example # 1](#example_6)**: This example demonstrates the use of a file stream objects to load an existin...


### Method: load(stream, load_options)  [static] {#load_stream_load_options_35}


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


### Method: load_stream(stream)  [static] {#load_stream_stream_36}


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


### Method: load_stream_with_options(stream, load_options)  [static] {#load_stream_with_options_stream_load_options_37}


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


### Method: load_with_options(file_path, load_options)  [static] {#load_with_options_file_path_load_options_38}


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


### Method: resize(new_width, new_height) {#resize_new_width_new_height_39}


```
 resize(new_width, new_height) 
```

Redimensionne l'image. Le paramètre par défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| new_height | int | La nouvelle hauteur. |


**See also:**

**[Example # 1](#example_182)**: The following example shows how to resize a metafile (WMF and EMF).

**[Example # 2](#example_185)**: The following example shows how to resize SVG image and save it to PNG.


### Method: resize(new_width, new_height, resize_type) {#resize_new_width_new_height_resize_type_40}


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

**[Example # 1](#example_209)**: Resize image using specific Resize Type.


### Method: resize(new_width, new_height, settings) {#resize_new_width_new_height_settings_41}


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


**See also:**

**[Example # 1](#example_28)**: This example loads an image and resizes it using various resizing settings.

**[Example # 2](#example_209)**: Resize image using specific Resize Type.


### Method: resize_by_settings(new_width, new_height, settings) {#resize_by_settings_new_width_new_height_settings_42}


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

### Method: resize_by_type(new_width, new_height, resize_type) {#resize_by_type_new_width_new_height_resize_type_43}


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

### Method: resize_height_proportionally(new_height) {#resize_height_proportionally_new_height_44}


```
 resize_height_proportionally(new_height) 
```

Redimensionne la hauteur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |

### Method: resize_height_proportionally(new_height, resize_type) {#resize_height_proportionally_new_height_resize_type_45}


```
 resize_height_proportionally(new_height, resize_type) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |


**See also:**

**[Example # 1](#example_30)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_height_proportionally(new_height, settings) {#resize_height_proportionally_new_height_settings_46}


```
 resize_height_proportionally(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_height_proportionally_settings(new_height, settings) {#resize_height_proportionally_settings_new_height_settings_47}


```
 resize_height_proportionally_settings(new_height, settings) 
```

Redimensionne la hauteur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_height | int | La nouvelle hauteur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally(new_width) {#resize_width_proportionally_new_width_48}


```
 resize_width_proportionally(new_width) 
```

Redimensionne la largeur proportionnellement. Le défaut [ResizeType.NEAREST_NEIGHBOUR_RESAMPLE](/imaging/python-net/aspose.imaging/resizetype/) est utilisé.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |

### Method: resize_width_proportionally(new_width, resize_type) {#resize_width_proportionally_new_width_resize_type_49}


```
 resize_width_proportionally(new_width, resize_type) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| resize_type | [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Type de redimensionnement. |


**See also:**

**[Example # 1](#example_29)**: This example loads an image and resizes it proportionally using various resiz...


### Method: resize_width_proportionally(new_width, settings) {#resize_width_proportionally_new_width_settings_50}


```
 resize_width_proportionally(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: resize_width_proportionally_settings(new_width, settings) {#resize_width_proportionally_settings_new_width_settings_51}


```
 resize_width_proportionally_settings(new_width, settings) 
```

Redimensionne la largeur proportionnellement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_width | int | La nouvelle largeur. |
| settings | [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Les paramètres de redimensionnement de l'image. |

### Method: rotate(angle) {#rotate_angle_52}


```
 rotate(angle) 
```

Faire pivoter l'image autour du centre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| angle | float | L'angle de rotation en degrés. Les valeurs positives feront pivoter dans le sens horaire. |

### Method: rotate_flip(rotate_flip_type) {#rotate_flip_rotate_flip_type_53}


```
 rotate_flip(rotate_flip_type) 
```

Fait pivoter, retourner, ou pivoter et retourner l'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rotate_flip_type | [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Type de la rotation et du retournement. |


**See also:**

**[Example # 1](#example_8)**: This example demonstrates the use of Rotate operation on an image. Example lo...

**[Example # 2](#example_31)**: This example loads an image, rotates it by 90 degrees clockwise and optionall...


### Method: save(file_path) {#save_file_path_54}


```
 save(file_path) 
```

Enregistre l'image à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer l'image. |

### Method: save(file_path, options) {#save_file_path_options_55}


```
 save(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |


**See also:**

**[Example # 1](#example_9)**: This example shows the simple steps to save an Image. To demonstrate this ope...

**[Example # 2](#example_32)**: The following example loads a BMP image from a file, then saves the image to ...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, options, bounds_rectangle) {#save_file_path_options_bounds_rectangle_56}


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


**See also:**

**[Example # 1](#example_33)**: The following example loads a BMP image from a file, then saves a rectangular...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(file_path, over_write) {#save_file_path_over_write_57}


```
 save(file_path, over_write) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier où enregistrer les données de l'objet. |
| over_write | bool | si défini sur <c>true</c> écrase le contenu du fichier, sinon une addition sera effectuée. |

### Method: save(stream) {#save_stream_58}


```
 save(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save(stream, options_base) {#save_stream_options_base_59}


```
 save(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |


**See also:**

**[Example # 1](#example_10)**: This example shows the process of saving an Image to MemoryStream. To demonst...

**[Example # 2](#example_34)**: The following example loads an image from a file, then saves the image to a P...

**[Example # 3](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save(stream, options_base, bounds_rectangle) {#save_stream_options_base_bounds_rectangle_60}


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


**See also:**

**[Example # 1](#example_35)**: The following example loads an image from a file, then saves a rectangular pa...

**[Example # 2](#example_90)**: The following example shows how to save an entire BMP image or part of it to ...


### Method: save_to_stream(stream) {#save_to_stream_stream_61}


```
 save_to_stream(stream) 
```

Enregistre les données de l'objet dans le flux spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'objet. |

### Method: save_to_stream_with_options(stream, options_base) {#save_to_stream_with_options_stream_options_base_62}


```
 save_to_stream_with_options(stream, options_base) 
```

Enregistre les données de l'image dans le flux spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flux | _io.BufferedRandom | Le flux où enregistrer les données de l'image. |
| options_base | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options d'enregistrement. |

### Method: save_to_stream_with_options_rect(stream, options_base, bounds_rectangle) {#save_to_stream_with_options_rect_stream_options_base_bounds_rectangle_63}


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

### Method: save_with_options(file_path, options) {#save_with_options_file_path_options_64}


```
 save_with_options(file_path, options) 
```

Enregistre les données de l'objet à l'emplacement de fichier spécifié dans le format de fichier indiqué selon les options d'enregistrement.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| file_path | string | Le chemin du fichier. |
| options | [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options. |

### Method: save_with_options_rect(file_path, options, bounds_rectangle) {#save_with_options_rect_file_path_options_bounds_rectangle_65}


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

### Method: set_palette(palette, update_colors) {#set_palette_palette_update_colors_66}


```
 set_palette(palette, update_colors) 
```

Définit la palette d'image.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| palette | [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | La palette à définir. |
| update_colors | bool | si défini sur <c>true</c> les couleurs seront mises à jour selon la nouvelle palette ; sinon les index de couleur restent inchangés. Notez que les index inchangés peuvent provoquer un plantage de l'image lors du chargement si certains index n'ont aucune entrée correspondante dans la palette. |

### Method: try_set_metadata(metadata) {#try_set_metadata_metadata_67}


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


## **Examples**
### This example demonstrates the loading of an existing Image file into an instance of aspose.imaging.Image using file path specified {#example_1}
``` python

from aspose.imaging import Image
# Créez une instance Image et initialisez‑la avec un fichier image existant depuis l'emplacement disque.
with Image.load(r"C:\temp\sample.bmp") as image:
	# effectuer un traitement d'image
	pass


```

### This example creates a new Image file at some disk location as specified by Source property of the BmpOptions instance. Several properties for BmpOptions instance are set before creating the actual image. Especially the Source property, that refers to the actual disk location in this case. {#example_4}
``` python

from aspose.imaging import Image
from aspose.imaging.imageoptions import BmpOptions
from aspose.imaging.sources import FileCreateSource

#Créez une instance de `BmpOptions` et définissez ses différentes propriétés
with BmpOptions() as bmp_options:
	bmp_options.bits_per_pixel = 24

	#Créez une instance de `FileCreateSource` et assignez‑la comme `source` pour l'instance de `BmpOptions`
	#Le deuxième paramètre `Boolean` détermine si le fichier à créer est is_temporal ou non
	bmp_options.source = FileCreateSource(r"C:\temp\output.bmp", False)

	#Créez une instance de Image et initialisez‑la avec une instance de BmpOptions en appelant la méthode Create
	with Image.create(bmp_options, 500, 500) as image:
		#effectuer un traitement d'image
		# enregistrer toutes les modifications
		image.save()


```

### This example demonstrates the use of a file stream objects to load an existing Image file {#example_6}
``` python

from aspose.imaging import Image

# Créez une instance de FileStream
with open(r"C:\temp\sample.bmp", "rb"):
	#Créez une instance de la classe Image et chargez un fichier existant via l'objet FileStream en appelant la méthode Load
	with Image.load(stream) as image:
		#effectuer un traitement d'image.
		pass

```

### This example demonstrates the use of Rotate operation on an image. Example loads an existing image file from some disk location and performs the `Rotate` operation on the image according to the value of enumeration `aspose.imaging.RotateFlipType` {#example_8}
``` python

from aspose.imaging import Image, RotateFlipType
#Créer une instance de la classe image et l'initialiser avec un fichier image existant via le chemin du fichier
with Image.load(r"C:\temp\sample.bmp") as image:
	# faire pivoter l'image de 180 degrés autour de l'axe X
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	# enregistrez toutes les modifications.
	image.save()


```

### This example shows the simple steps to save an Image. To demonstrate this operation, we load an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format using file path {#example_9}
``` python

from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from os.path import join as path_join

directory = "c:\\temp"

#Créer une instance de la classe image et l'initialiser avec un fichier existant via le chemin du fichier
with Image.load(path_join(directory, "sample.bmp")) as image:
	#Faire pivoter l'image de 180 degrés autour de l'axe X
	image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
	#Enregistrer l'Image au format PSD vers le chemin du fichier avec les paramètres par défaut de PsdOptions
	image.save(path_join(directory, "output.psd"), PsdOptions())


```

### This example shows the process of saving an Image to MemoryStream. To demonstrate this operation, example loads an existing file from some disk location, performs `rotate` operation on the image and save the image in PSD format {#example_10}
``` python
from aspose.imaging import Image, RotateFlipType
from aspose.imaging.imageoptions import PsdOptions
from aspose.imaging.extensions import StreamExtensions as stream_ext

#Créer une instance de MemoryStream
with stream_ext.create_memory_stream() as stream:
	#Créer une instance de la classe image et l'initialiser avec un fichier existant via le chemin du fichier
	with Image.load(r"C:\temp\sample.bmp") as image:
		#Faire pivoter l'image de 180 degrés autour de l'axe X
		image.rotate_flip(RotateFlipType.ROTATE_180_FLIP_X)
		#Enregistrer l'Image au format PSD vers MemoryStream avec les paramètres par défaut de PsdOptions
		image.save(stream, PsdOptions())


```

### This example determines whether image can be loaded from a file. {#example_22}
``` python

from aspose.imaging import Image

# Utiliser un chemin absolu vers le fichier
can_load: bool = Image.can_load(r"c:\temp\sample.gif")


```

### This example determines whether image can be loaded from a file stream. {#example_23}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ext
import os.path import join

directory = r"c:\temp"

canLoad = False

# Utiliser un flux de fichier
with open(join(directory, "sample.bmp"), "rb"):
	canLoad = Image.can_load(stream)

print(f"Can load the file: {canLoad}")

# Les données suivantes ne sont pas un flux d'image valide, donc CanLoad renvoie false.
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

# Utiliser un chemin absolu vers le fichier
file_format = Image.get_file_format(path_join(directory, "sample.gif"))
print(f"The file format is {file_format}")


```

### This example shows how to determine the image format without loading the entire image from a file stream. {#example_25}
``` python

from aspose.imaging import Image
from aspose.imaging.extensions import StreamExtensions as strm_ex
from os.path import join as path_join

directory = "c:\\temp\\"

# Utiliser un flux de fichier
with open(path_join(directory, "sample.bmp"), "rb") as stream:
	file_format = Image.get_file_format(stream)
	print(f"The file format is {file_format}")

# Les données suivantes ne sont pas un flux d'image valide, donc get_file_format renvoie FileFormat.UNKNOWN
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
	# Déterminer si l'image peut être enregistrée au format jpeg
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

# L'algorithme adaptatif basé sur une fonction rationnelle pondérée et mélangée et l'interpolation lanczos3.
resizeSettings.mode = ResizeType.ADAPTIVE_RESAMPLE
# Le petit filtre rectangulaire
resizeSettings.filter_type = ImageFilterType.SMALL_RECTANGULAR
# Le nombre de couleurs dans la palette.
resizeSettings.entries_count = 256
# La quantification des couleurs n'est pas utilisée
resizeSettings.color_quantization_method = ColorQuantizationMethod.NONE

# La méthode euclidienne
resizeSettings.ColorCompareMethod = ColorCompareMethod.Euclidian;

with Image.load(path_join(directory, "sample.gif")) as image:
	# Réduisez de 2 fois en utilisant le rééchantillonnage adaptatif.
	image.resize(image.width // 2, image.height // 2, resizeSettings)
	image.save(path_join(directory, "downsample.adaptive.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the width is specified, the height is calculated automatically. {#example_29}
``` python
from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Agrandissez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	image.resize_width_proportionally(image.width * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Réduisez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	image.resize_width_proportionally(image.width // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Agrandissez de 2 fois en utilisant le rééchantillonnage bilinéaire.
	image.resize_width_proportionally(image.width * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Réduisez de 2 fois en utilisant le rééchantillonnage bilinéaire.
	image.resize_width_proportionally(image.width // 2, ResizeType.BILINEAR_RESAMPLE);
	image.save(path_join(directory, "downsample.bilinear.gif"))


```

### This example loads an image and resizes it proportionally using various resizing methods. Only the height is specified, the width is calculated automatically. {#example_30}
``` python

from aspose.imaging import Image, ResizeType
from os.path import join as path_join

directory = "c:\\temp\\"

with Image.load(path_join(directory, "sample.gif")) as image:
	# Agrandissez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	image.resize_height_proportionally(image.height * 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "upsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Réduisez de 2 fois en utilisant le rééchantillonnage du plus proche voisin.
	image.resize_height_proportionally(image.height // 2, ResizeType.NEAREST_NEIGHBOUR_RESAMPLE)
	image.save(path_join(directory, "downsample.nearestneighbour.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Agrandissez de 2 fois en utilisant le rééchantillonnage bilinéaire.
	image.resize_height_proportionally(image.height * 2, ResizeType.BILINEAR_RESAMPLE)
	image.save(path_join(directory, "upsample.bilinear.gif"))

with Image.load(path_join(directory, "sample.gif")) as image:
	# Réduisez de 2 fois en utilisant le rééchantillonnage bilinéaire.
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
	# Tournez, retournez et enregistrez dans le fichier de sortie.
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
	# Enregistrer l'image entière dans un fichier PNG.
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
	# Enregistrer la moitié supérieure de l'image dans un fichier PNG.
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
		# Enregistrer l'image entière dans un flux de fichier.
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
		# Enregistrer la moitié supérieure de l'image dans un flux de fichier.
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
		
	# Convertir en image noir et blanc
	bmpImage.binarize_otsu()

	# Enregistrer au même emplacement avec les options par défaut.
	image.save()

	saveOptions = BmpOptions()

	# Une palette ne contient que deux couleurs : Noir et Blanc dans ce cas.
	saveOptions.palette = ColorPaletteHelper.create_monochrome()

	# Pour toutes les images monochromes (y compris les noir et blanc), il suffit d'allouer 1 bit par pixel.
	saveOptions.bits_per_pixel = 1

	# Enregistrer à un autre emplacement avec les options spécifiées.
	image.save(path_join(directory, "sample.bw.palettized.bmp"), saveOptions)

	# Enregistrer uniquement la partie centrale de l'image.
	bounds = Rectangle(image.width // 4, image.height // 4, image.width // 2, image.height // 2)
	image.save(path_join(directory, "sample.bw.palettized.part.bmp"), saveOptions, bounds)

	# Enregistrer l'image entière dans un flux mémoire
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions);
		print("The size of the whole image in bytes:", stream.tell())

	# Enregistrez la partie centrale de l'image dans un flux mémoire
	with strm_ext.create_memory_stream() as stream:
		image.save(stream, saveOptions, bounds)
		print("The size of the central part of the image in bytes: ", stream.tell())

#La sortie peut ressembler à ceci :
#La taille de l'image complète en octets : 24062
#La taille de la partie centrale de l'image en octets : 6046

```

### The following example shows how to resize a metafile (WMF and EMF). {#example_182}
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

### The following example shows how to resize SVG image and save it to PNG. {#example_185}
``` python

from aspose.imaging import PointF, Image
from aspose.imaging.imageoptions import PngOptions
from os import path

dir_ = "c:\\aspose.imaging\\net\\issues\\3549"
file_names = ["Logotype.svg", "sample_car.svg", "rg1024_green_grapes.svg", "MidMarkerFigure.svg", "embeddedFonts.svg"]
scales = [PointF(0.5, 0.5), PointF(1.0, 1.0), PointF(2.0, 2.0), PointF(3.5, 9.2)]
for input_file in file_names:
	for scale in scales:
		output_file = "{0}_{1}_{2}.png".format(input_file, str(scale.x), str(scale.y))
		with Image.load(path.join(dir_, input_file)) as image:
			image.resize(int(image.width * scale.x), int(image.height * scale.y))
			image.save(path.join(dir_, output_file), PngOptions())


```

### Resize image using specific Resize Type. {#example_209}
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

### Determine if the palette is used by the image. {#example_221}
``` python

from aspose.imaging import Image

with Image.load("Sample.bmp") as image:
	if image.use_palette:
		print("The palette is used by the image")

```

