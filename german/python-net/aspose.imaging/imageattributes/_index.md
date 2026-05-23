---
title: "ImageAttributes Klasse"
type: docs
weight: 5660
url: /de/python-net/aspose.imaging/imageattributes/
---

**Summary:** An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object contains information about how bitmap and metafile colors are manipulated during rendering. An [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object maintains several color-adjustment settings, including color-adjustment matrices, grayscale-adjustment matrices, gamma-correction values, color-map tables, and color-threshold values. During rendering, colors can be corrected, darkened, lightened, and removed. To apply such manipulations, initialize an [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object and pass the path of that [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) object (along with the path of an [Image](/imaging/python-net/aspose.imaging/image/)) to the DrawImage method.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.ImageAttributes

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [ImageAttributes()](#ImageAttributes__1) | Initialisiert eine neue Instanz der [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Klasse. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| clear_brush_remap_table() | Löscht die Pinsel-Farb-Remap-Tabelle dieses [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Objekts. |
| clear_color_key() | Löscht den Farbschlüssel (Transparenzbereich) für die Standardkategorie. |
| [clear_color_key(type)](#clear_color_key_type_1) | Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie. |
| clear_color_matrix() | Löscht die Farbkorrekturmatrix für die Standardkategorie. |
| [clear_color_matrix(type)](#clear_color_matrix_type_2) | Löscht die Farbkorrekturmatrix für eine angegebene Kategorie. |
| clear_gamma() | Deaktiviert die Gammakorrektur für die Standardkategorie. |
| [clear_gamma(type)](#clear_gamma_type_3) | Deaktiviert die Gammakorrektur für eine angegebene Kategorie. |
| clear_no_op() | Löscht die NoOp-Einstellung für die Standardkategorie. |
| [clear_no_op(type)](#clear_no_op_type_4) | Löscht die NoOp-Einstellung für eine angegebene Kategorie. |
| clear_output_channel() | Löscht die CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für die Standardkategorie. |
| [clear_output_channel(type)](#clear_output_channel_type_5) | Löscht die (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für eine angegebene Kategorie. |
| clear_output_channel_color_profile() | Löscht die Farbprofil-Einstellung des Ausgangskanals für die Standardkategorie. |
| [clear_output_channel_color_profile(type)](#clear_output_channel_color_profile_type_6) | Löscht die Farbprofil-Einstellung des Ausgangskanals für eine angegebene Kategorie. |
| clear_remap_table() | Löscht die Farb-Remap-Tabelle für die Standardkategorie. |
| [clear_remap_table(type)](#clear_remap_table_type_7) | Löscht die Farb-Remap-Tabelle für eine angegebene Kategorie. |
| clear_threshold() | Löscht den Schwellenwert für die Standardkategorie. |
| [clear_threshold(type)](#clear_threshold_type_8) | Löscht den Schwellenwert für eine angegebene Kategorie. |
| [set_brush_remap_table(map)](#set_brush_remap_table_map_9) | Legt die Farb-Remap-Tabelle für die Pinselkategorie fest. |
| [set_color_key(color_low, color_high)](#set_color_key_color_low_color_high_10) | Legt den Farbenschlüssel für die Standardkategorie fest. |
| [set_color_key(color_low, color_high, type)](#set_color_key_color_low_color_high_type_11) | Legt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie fest. |
| [set_color_matrices(new_color_matrix, gray_matrix)](#set_color_matrices_new_color_matrix_gray_matrix_12) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest. |
| [set_color_matrices(new_color_matrix, gray_matrix, flags)](#set_color_matrices_new_color_matrix_gray_matrix_flags_13) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest. |
| [set_color_matrices(new_color_matrix, gray_matrix, mode, type)](#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14) | Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie fest. |
| [set_color_matrix(new_color_matrix)](#set_color_matrix_new_color_matrix_15) | Legt die Farbkorrekturmatrix für die Standardkategorie fest. |
| [set_color_matrix(new_color_matrix, flags)](#set_color_matrix_new_color_matrix_flags_16) | Legt die Farbkorrekturmatrix für die Standardkategorie fest. |
| [set_color_matrix(new_color_matrix, mode, type)](#set_color_matrix_new_color_matrix_mode_type_17) | Legt die Farbkorrekturmatrix für eine angegebene Kategorie fest. |
| [set_gamma(gamma)](#set_gamma_gamma_18) | Legt den Gammawert für die Standardkategorie fest. |
| [set_gamma(gamma, type)](#set_gamma_gamma_type_19) | Legt den Gammawert für eine angegebene Kategorie fest. |
| set_no_op() | Schaltet die Farbkorrektur für die Standardkategorie aus. |
| [set_no_op(type)](#set_no_op_type_20) | Schaltet die Farbkorrektur für eine angegebene Kategorie aus. |
| [set_output_channel(flags)](#set_output_channel_flags_21) | Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie fest. |
| [set_output_channel(flags, type)](#set_output_channel_flags_type_22) | Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie fest. |
| [set_output_channel_color_profile(color_profile_filename)](#set_output_channel_color_profile_color_profile_filename_23) | Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest. |
| [set_output_channel_color_profile(color_profile_filename, type)](#set_output_channel_color_profile_color_profile_filename_type_24) | Legt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie fest. |
| [set_remap_table(map)](#set_remap_table_map_25) | Legt die Farb-Remap-Tabelle für die Standardkategorie fest. |
| [set_remap_table(map, type)](#set_remap_table_map_type_26) | Legt die Farb-Remap-Tabelle für eine angegebene Kategorie fest. |
| [set_threshold(threshold)](#set_threshold_threshold_27) | Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest. |
| [set_threshold(threshold, type)](#set_threshold_threshold_type_28) | Legt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie fest. |
| [set_wrap_mode(mode)](#set_wrap_mode_mode_29) | Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |
| [set_wrap_mode(mode, color)](#set_wrap_mode_mode_color_30) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |
| [set_wrap_mode(mode, color, clamp)](#set_wrap_mode_mode_color_clamp_31) | Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt. |


### Constructor: ImageAttributes() {#ImageAttributes__1}


```
 ImageAttributes() 
```

Initialisiert eine neue Instanz der [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) Klasse.

### Method: clear_color_key(type) {#clear_color_key_type_1}


```
 clear_color_key(type) 
```

Löscht den Farbschlüssel (Transparenzbereich) für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die der Farbenschlüssel gelöscht wird. |

### Method: clear_color_matrix(type) {#clear_color_matrix_type_2}


```
 clear_color_matrix(type) 
```

Löscht die Farbkorrekturmatrix für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farbkorrekturmatrix gelöscht wird. |

### Method: clear_gamma(type) {#clear_gamma_type_3}


```
 clear_gamma(type) 
```

Deaktiviert die Gammakorrektur für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Gammakorrektur deaktiviert ist. |

### Method: clear_no_op(type) {#clear_no_op_type_4}


```
 clear_no_op(type) 
```

Löscht die NoOp-Einstellung für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die NoOp‑Einstellung gelöscht wird. |

### Method: clear_output_channel(type) {#clear_output_channel_type_5}


```
 clear_output_channel(type) 
```

Löscht die (Cyan-Magenta-Gelb-Schwarz) Ausgangskanal-Einstellung für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Einstellung des Ausgabekanals gelöscht wird. |

### Method: clear_output_channel_color_profile(type) {#clear_output_channel_color_profile_type_6}


```
 clear_output_channel_color_profile(type) 
```

Löscht die Farbprofil-Einstellung des Ausgangskanals für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Einstellung des Ausgabekanal‑Profils gelöscht wird. |

### Method: clear_remap_table(type) {#clear_remap_table_type_7}


```
 clear_remap_table(type) 
```

Löscht die Farb-Remap-Tabelle für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Remap‑Tabelle gelöscht wird. |

### Method: clear_threshold(type) {#clear_threshold_type_8}


```
 clear_threshold(type) 
```

Löscht den Schwellenwert für eine angegebene Kategorie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die der Schwellenwert gelöscht wird. |

### Method: set_brush_remap_table(map) {#set_brush_remap_table_map_9}


```
 set_brush_remap_table(map) 
```

Legt die Farb-Remap-Tabelle für die Pinselkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Ein Array von [ColorMap](/imaging/python-net/aspose.imaging/colormap/)-Objekten. |

### Method: set_color_key(color_low, color_high) {#set_color_key_color_low_color_high_10}


```
 set_color_key(color_low, color_high) 
```

Legt den Farbenschlüssel für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Der niedrige Farbschlüsselwert. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Der hohe Farbschlüsselwert. |

### Method: set_color_key(color_low, color_high, type) {#set_color_key_color_low_color_high_type_11}


```
 set_color_key(color_low, color_high, type) 
```

Legt den Farbenschlüssel (Transparenzbereich) für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_low | [Color](/imaging/python-net/aspose.imaging/color/) | Der niedrige Farbschlüsselwert. |
| color_high | [Color](/imaging/python-net/aspose.imaging/color/) | Der hohe Farbschlüsselwert. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die der Farbschlüssel festgelegt wird. |

### Method: set_color_matrices(new_color_matrix, gray_matrix) {#set_color_matrices_new_color_matrix_gray_matrix_12}


```
 set_color_matrices(new_color_matrix, gray_matrix) 
```

Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Graustufen‑Korrekturmatrix. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, flags) {#set_color_matrices_new_color_matrix_gray_matrix_flags_13}


```
 set_color_matrices(new_color_matrix, gray_matrix, flags) 
```

Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Graustufen‑Korrekturmatrix. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ein Element von [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), das den Bild- und Farbtyp angibt, der von den Farb‑ und Graustufen‑Justierungsmatrizen betroffen ist. |

### Method: set_color_matrices(new_color_matrix, gray_matrix, mode, type) {#set_color_matrices_new_color_matrix_gray_matrix_mode_type_14}


```
 set_color_matrices(new_color_matrix, gray_matrix, mode, type) 
```

Legt die Farbkorrekturmatrix und die Graustufen-Korrekturmatrix für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |
| gray_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Graustufen‑Korrekturmatrix. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ein Element von [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), das den Bild- und Farbtyp angibt, der von den Farb‑ und Graustufen‑Justierungsmatrizen betroffen ist. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farb‑ und Graustufen‑Justierungsmatrizen festgelegt werden. |

### Method: set_color_matrix(new_color_matrix) {#set_color_matrix_new_color_matrix_15}


```
 set_color_matrix(new_color_matrix) 
```

Legt die Farbkorrekturmatrix für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |

### Method: set_color_matrix(new_color_matrix, flags) {#set_color_matrix_new_color_matrix_flags_16}


```
 set_color_matrix(new_color_matrix, flags) 
```

Legt die Farbkorrekturmatrix für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |
| flags | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ein Element von [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), das den Bild- und Farbtyp angibt, der von der Farb‑Justierungsmatrix betroffen ist. |

### Method: set_color_matrix(new_color_matrix, mode, type) {#set_color_matrix_new_color_matrix_mode_type_17}


```
 set_color_matrix(new_color_matrix, mode, type) 
```

Legt die Farbkorrekturmatrix für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_color_matrix | [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Die Farbkorrekturmatrix. |
| mode | [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Ein Element von [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/), das den Bild- und Farbtyp angibt, der von der Farb‑Justierungsmatrix betroffen ist. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farb‑Justierungsmatrix festgelegt wird. |

### Method: set_gamma(gamma) {#set_gamma_gamma_18}


```
 set_gamma(gamma) 
```

Legt den Gammawert für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Der Gamma‑Korrekturwert. |

### Method: set_gamma(gamma, type) {#set_gamma_gamma_type_19}


```
 set_gamma(gamma, type) 
```

Legt den Gammawert für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Gamma | float | Der Gamma‑Korrekturwert. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element der [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/)-Aufzählung, das die Kategorie angibt, für die der Gamma‑Wert festgelegt wird. |

### Method: set_no_op(type) {#set_no_op_type_20}


```
 set_no_op(type) 
```

Schaltet die Farbkorrektur für eine angegebene Kategorie aus.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farbkorrektur deaktiviert wird. |

### Method: set_output_channel(flags) {#set_output_channel_flags_21}


```
 set_output_channel(flags) 
```

Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Ein Element von [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/), das den Ausgabekanal angibt. |

### Method: set_output_channel(flags, type) {#set_output_channel_flags_type_22}


```
 set_output_channel(flags, type) 
```

Legt den CMYK (Cyan-Magenta-Gelb-Schwarz) Ausgabekanal für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| flags | [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Ein Element von [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/), das den Ausgabekanal angibt. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die der Ausgabekanal festgelegt wird. |

### Method: set_output_channel_color_profile(color_profile_filename) {#set_output_channel_color_profile_color_profile_filename_23}


```
 set_output_channel_color_profile(color_profile_filename) 
```

Legt die Farbprofildatei des Ausgabekanals für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_profile_filename | string | Der Pfadname einer Farbprofildatei. Befindet sich die Farbprofildatei im Verzeichnis %SystemRoot%\System32\Spool\Drivers\Color, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollqualifizierten Pfadnamen enthalten. |

### Method: set_output_channel_color_profile(color_profile_filename, type) {#set_output_channel_color_profile_color_profile_filename_type_24}


```
 set_output_channel_color_profile(color_profile_filename, type) 
```

Legt die Farbprofildatei des Ausgabekanals für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| color_profile_filename | string | Der Pfadname einer Farbprofildatei. Befindet sich die Farbprofildatei im Verzeichnis %SystemRoot%\System32\Spool\Drivers\Color, kann dieser Parameter der Dateiname sein. Andernfalls muss dieser Parameter den vollqualifizierten Pfadnamen enthalten. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farbprofildatei des Ausgabekanals festgelegt wird. |

### Method: set_remap_table(map) {#set_remap_table_map_25}


```
 set_remap_table(map) 
```

Legt die Farb-Remap-Tabelle für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Ein Array von Farbpaaren des Typs [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |

### Method: set_remap_table(map, type) {#set_remap_table_map_type_26}


```
 set_remap_table(map, type) 
```

Legt die Farb-Remap-Tabelle für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| map | [ColorMap[]](/imaging/python-net/aspose.imaging/colormap/) | Ein Array von Farbpaaren des Typs [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Jedes Farbpaar enthält eine vorhandene Farbe (den ersten Wert) und die Farbe, auf die sie abgebildet wird (den zweiten Wert). |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die die Farb‑Remap‑Tabelle festgelegt wird. |

### Method: set_threshold(threshold) {#set_threshold_threshold_27}


```
 set_threshold(threshold) 
```

Legt den Schwellenwert (Transparenzbereich) für die Standardkategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | float | Eine reelle Zahl, die den Schwellenwert angibt. |

### Method: set_threshold(threshold, type) {#set_threshold_threshold_type_28}


```
 set_threshold(threshold, type) 
```

Legt den Schwellenwert (Transparenzbereich) für eine angegebene Kategorie fest.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Schwellenwert | float | Ein Schwellenwert von 0.0 bis 1.0, der als Trennpunkt verwendet wird, um Farben zu sortieren, die entweder einem Maximal- oder Minimalwert zugeordnet werden. |
| type | [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Ein Element von [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/), das die Kategorie angibt, für die der Farbschwellenwert festgelegt wird. |

### Method: set_wrap_mode(mode) {#set_wrap_mode_mode_29}


```
 set_wrap_mode(mode) 
```

Legt den Wrap-Modus fest, der verwendet wird, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ein Element von [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |

### Method: set_wrap_mode(mode, color) {#set_wrap_mode_mode_color_30}


```
 set_wrap_mode(mode, color) 
```

Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ein Element von [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Ein [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/)-Objekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |

### Method: set_wrap_mode(mode, color, clamp) {#set_wrap_mode_mode_color_clamp_31}


```
 set_wrap_mode(mode, color, clamp) 
```

Legt den Wrap-Modus und die Farbe fest, die verwendet werden, um zu entscheiden, wie eine Textur über eine Form gekachelt wird oder an Formgrenzen. Eine Textur wird über eine Form gekachelt, um sie auszufüllen, wenn die Textur kleiner ist als die Form, die sie füllt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| mode | [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Ein Element von [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/), das angibt, wie wiederholte Kopien eines Bildes verwendet werden, um einen Bereich zu kacheln. |
| color | [Color](/imaging/python-net/aspose.imaging/color/) | Ein Farbobjekt, das die Farbe der Pixel außerhalb eines gerenderten Bildes angibt. Diese Farbe ist sichtbar, wenn der Modusparameter auf [WrapMode.CLAMP](/imaging/python-net/aspose.imaging/wrapmode/) gesetzt ist und das an DrawImage übergebene Quellrechteck größer ist als das Bild selbst. |
| clamp | bool | Dieser Parameter hat keine Wirkung. Setzen Sie ihn auf false. |

