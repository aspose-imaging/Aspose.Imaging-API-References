---
title: "Classe ImageAttributes"
type: docs
weight: 5660
url: /fr/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initialise une nouvelle instance de la classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| clear_brush_remap_table() | Efface la table de remappage des couleurs du pinceau de cet objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| clear_color_key() | Efface la clé de couleur (plage de transparence) pour la catégorie par défaut. |
| [clear_color_key(type)](#clear_color_key_type_1) | Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| clear_color_matrix() | Efface la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| clear_gamma() | Désactive la correction gamma pour la catégorie par défaut. |
| [clear_gamma(type)](#clear_gamma_type_3) | Désactive la correction gamma pour une catégorie spécifiée. |
| clear_no_op() | Efface le paramètre NoOp pour la catégorie par défaut. |
| [clear_no_op(type)](#clear_no_op_type_4) | Efface le paramètre NoOp pour une catégorie spécifiée. |
| clear_output_channel() | Efface le paramètre du canal de sortie CMYK (cyan-magenta-jaune-noir) pour la catégorie par défaut. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Efface le paramètre du canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée. |
| clear_output_channel_color_profile() | Efface le paramètre du profil de couleur du canal de sortie pour la catégorie par défaut. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Efface le paramètre du profil de couleur du canal de sortie pour une catégorie spécifiée. |
| clear_remap_table() | Efface la table de remappage des couleurs pour la catégorie par défaut. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Efface la table de remappage des couleurs pour une catégorie spécifiée. |
| clear_threshold() | Efface la valeur du seuil pour la catégorie par défaut. |
| [clear_threshold(type)](#clear_threshold_type_8) | Efface la valeur du seuil pour une catégorie spécifiée. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Définit la table de remappage des couleurs pour la catégorie de pinceau. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Définit la clé de couleur pour la catégorie par défaut. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour une catégorie spécifiée. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Définit la matrice d'ajustement des couleurs pour la catégorie par défaut. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Définit la valeur gamma pour la catégorie par défaut. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Définit la valeur gamma pour une catégorie spécifiée. |
| set_no_op() | Désactive l'ajustement des couleurs pour la catégorie par défaut. |
| [set_no_op(type)](#set_no_op_type_20) | Désactive l'ajustement des couleurs pour une catégorie spécifiée. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour une catégorie spécifiée. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée. |
| [set_remap_table(map)](#set_remap_table_map_25) | Définit la table de remappage des couleurs pour la catégorie par défaut. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Définit la table de remappage des couleurs pour une catégorie spécifiée. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Définit le seuil (plage de transparence) pour la catégorie par défaut. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Définit le seuil (plage de transparence) pour une catégorie spécifiée. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Définit le mode d'enroulement utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initialise une nouvelle instance de la classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/).

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Efface la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la clé de couleur est effacée. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Efface la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est effacée. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Désactive la correction gamma pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la correction gamma est désactivée. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Efface le paramètre NoOp pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le paramètre NoOp est réinitialisé. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Efface le paramètre du canal de sortie (cyan-magenta-jaune-noir) pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le paramètre du canal de sortie est réinitialisé. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Efface le paramètre du profil de couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le paramètre du profil du canal de sortie est réinitialisé. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Efface la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la table de remappage est réinitialisée. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Efface la valeur du seuil pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le seuil est réinitialisé. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Définit la table de remappage des couleurs pour la catégorie de pinceau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Un tableau d'objets [ColorMap](/imaging/python-net/aspose.imaging/colormap/). |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Définit la clé de couleur pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | La valeur basse de la clé de couleur. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | La valeur haute de la clé de couleur. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Définit la clé de couleur (plage de transparence) pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | La valeur basse de la clé de couleur. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | La valeur haute de la clé de couleur. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la clé de couleur est définie. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement du niveau de gris. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement du niveau de gris. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un élément de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) qui spécifie le type d'image et de couleur qui seront affectés par les matrices d'ajustement des couleurs et d'ajustement du niveau de gris. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Définit la matrice d'ajustement des couleurs et la matrice d'ajustement du niveau de gris pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement du niveau de gris. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un élément de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) qui spécifie le type d'image et de couleur qui seront affectés par les matrices d'ajustement des couleurs et d'ajustement du niveau de gris. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle les matrices d'ajustement des couleurs et d'ajustement du niveau de gris sont définies. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Définit la matrice d'ajustement des couleurs pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un élément de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) qui spécifie le type d'image et de couleur qui seront affectés par la matrice d'ajustement des couleurs. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Définit la matrice d'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | La matrice d'ajustement des couleurs. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Un élément de [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) qui spécifie le type d'image et de couleur qui seront affectés par la matrice d'ajustement des couleurs. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la matrice d'ajustement des couleurs est définie. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Définit la valeur gamma pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | La valeur de correction gamma. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Définit la valeur gamma pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| gamma | float | La valeur de correction gamma. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de l'énumération [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la valeur gamma est définie. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Désactive l'ajustement des couleurs pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la correction des couleurs est désactivée. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Un élément de [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) qui spécifie le canal de sortie. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Définit le canal de sortie CMYK (cyan-magenta-yellow-black) pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Un élément de [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) qui spécifie le canal de sortie. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le canal de sortie est défini. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Définit le fichier de profil couleur du canal de sortie pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | Le nom de chemin d'un fichier de profil de couleur. Si le fichier de profil de couleur se trouve dans le répertoire %SystemRoot%\System32\Spool\Drivers\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Définit le fichier de profil couleur du canal de sortie pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| color_profile_filename | string | Le nom de chemin d'un fichier de profil de couleur. Si le fichier de profil de couleur se trouve dans le répertoire %SystemRoot%\System32\Spool\Drivers\Color, ce paramètre peut être le nom du fichier. Sinon, ce paramètre doit être le chemin d'accès complet. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le fichier de profil de couleur du canal de sortie est défini. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Définit la table de remappage des couleurs pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Un tableau de paires de couleurs de type [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Définit la table de remappage des couleurs pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Un tableau de paires de couleurs de type [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Chaque paire de couleurs contient une couleur existante (la première valeur) et la couleur vers laquelle elle sera mappée (la deuxième valeur). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle la table de remappage des couleurs est définie. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Définit le seuil (plage de transparence) pour la catégorie par défaut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| seuil | float | Un nombre réel qui spécifie la valeur du seuil. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Définit le seuil (plage de transparence) pour une catégorie spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| seuil | float | Une valeur de seuil de 0.0 à 1.0 qui est utilisée comme point de rupture pour trier les couleurs qui seront mappées à une valeur maximale ou minimale. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Un élément de [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) qui spécifie la catégorie pour laquelle le seuil de couleur est défini. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Définit le mode d'enroulement utilisé pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un élément de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un élément de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) qui spécifie la couleur des pixels à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est défini sur [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) et que le rectangle source passé à DrawImage est plus grand que l'image elle-même. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Définit le mode d'enroulement et la couleur utilisés pour déterminer comment répéter une texture sur une forme, ou aux limites de la forme. Une texture est répétée sur une forme pour la remplir lorsque la texture est plus petite que la forme qu'elle remplit.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Un élément de [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) qui spécifie comment les copies répétées d'une image sont utilisées pour couvrir une zone. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Un objet couleur qui spécifie la couleur des pixels à l'extérieur d'une image rendue. Cette couleur est visible si le paramètre mode est défini sur [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) et que le rectangle source passé à DrawImage est plus grand que l'image elle-même. |
| clamp | bool | Ce paramètre n'a aucun effet. Réglez-le sur false. |

