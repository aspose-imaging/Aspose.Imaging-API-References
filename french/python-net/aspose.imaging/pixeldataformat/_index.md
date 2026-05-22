---
title: "Classe PixelDataFormat"
type: docs
weight: 6920
url: /fr/python-net/aspose.imaging/pixeldataformat/
---

**Summary:** The pixel data format. This is an immutable object.

**Module:** [aspose.imaging](/imaging/python-net/aspose.imaging/)

**Full Name:** aspose.imaging.PixelDataFormat

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| GRAYSCALE16 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Défini pour 16 bits par pixel avec jusqu'à 16 bits représentant l'intensité en niveaux de gris. |
| bits_per_pixel | int | r | Obtient les bits par pixel. |
| légende | string | r | Obtient la légende du format de données de pixel. |
| channel_bits | int[] | r | Obtient le nombre de bits pour chaque canal. |
| channels_count | int | r | Obtient le nombre de canaux. |
| cmyk [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 32 bits par pixel avec 8 bits pour chacun du cyan, magenta, jaune et noir. |
| cmyka [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le acmyk. |
| grayscale [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r/w | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 8 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255. |
| grayscale_alpha [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 16 bits par pixel avec 8 bits représentant l'intensité en niveaux de gris dans l'intervalle 0-255 et un composant alpha supplémentaire de 8 bits. |
| pixel_format | [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | r | Obtient le format de pixel. |
| rgb_16_bpp_555 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 16 bits par pixel avec 5 bits pour chacun du rouge, vert et bleu, l'alpha n'est pas défini. |
| rgb_16_bpp_565 [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 16 bits par pixel avec 5 bits pour le rouge, 6 bits pour le vert et 5 bits pour le bleu, l'alpha n'est pas défini. |
| rgb_24_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini. |
| rgb_24_bpp_png [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 24 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu, l'alpha n'est pas défini. |
| rgb_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu. |
| rgb_indexed_1_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour un indexé de 1 bit par couleur.<br/>            Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée.<br/>            Utilisez-le avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou du RGBA vers un modèle de couleur indexé. |
| rgb_indexed_2_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour un indexé de 2 bits par couleur.<br/>            Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée.<br/>            Utilisez-le avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou du RGBA vers un modèle de couleur indexé. |
| rgb_indexed_4_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour un indexé de 4 bits par couleur.<br/>            Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée.<br/>            Utilisez-le avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou du RGBA vers un modèle de couleur indexé. |
| rgb_indexed_8_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour un indexé de 8 bits par couleur.<br/>            Le stockage de données de pixels indexés est destiné à permettre le stockage et la récupération des données partout où la palette de couleurs est utilisée.<br/>            Utilisez-le avec prudence, car cela peut nécessiter une conversion d'une palette à une autre ou du RGBA vers un modèle de couleur indexé. |
| rgba_32_bpp [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 32 bits par pixel avec 8 bits pour chacun des canaux alpha, rouge, vert et bleu. |
| y_cb_cr [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 24 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence-bleu et différence-rouge. |
| ycck [static] | [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | r | Obtient le [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) défini pour 32 bits par pixel avec 8 bits pour chacun des composants chroma luma, différence-bleu, différence-rouge et noir. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_bgr(bits_per_sample)](#get_bgr_bits_per_sample_1) | Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon. |
| [get_bgra(bits_per_sample)](#get_bgra_bits_per_sample_2) | Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon. |
| [get_cie_lab(bits_per_l, bits_per_a, bits_per_b)](#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3) | Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon. |
| [get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)](#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [get_cmyk(bits_per_sample)](#get_cmyk_bits_per_sample_5) | Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon. |
| [get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)](#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6) | Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon. |
| [get_grayscale(bits_per_sample)](#get_grayscale_bits_per_sample_7) | Obtient la couleur Niveaux de gris avec un nombre spécifié de bits par échantillon. |
| [get_grayscale_alpha(bits_per_sample)](#get_grayscale_alpha_bits_per_sample_8) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [get_grayscale_alpha(bits_per_sample, alpha_channel_bits)](#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9) | Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon. |
| [get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)](#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [get_rgb(bits_per_sample)](#get_rgb_bits_per_sample_11) | Obtient la couleur RGB avec un nombre spécifié de bits par échantillon. |
| [get_rgb_indexed(bits_per_sample)](#get_rgb_indexed_bits_per_sample_12) | Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon. |
| [get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)](#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [get_rgba(bits_per_sample)](#get_rgba_bits_per_sample_14) | Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon. |
| [get_y_cb_cr(bits_per_sample)](#get_y_cb_cr_bits_per_sample_15) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)](#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16) | Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon. |
| [get_ycck(bits_per_sample)](#get_ycck_bits_per_sample_17) | Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon. |


### Method: get_bgr(bits_per_sample)  [static] {#get_bgr_bits_per_sample_1}


```
 get_bgr(bits_per_sample) 
```

Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur BGRA. |


### Method: get_bgra(bits_per_sample)  [static] {#get_bgra_bits_per_sample_2}


```
 get_bgra(bits_per_sample) 
```

Obtient la couleur BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur BGRA. |


### Method: get_cie_lab(bits_per_l, bits_per_a, bits_per_b)  [static] {#get_cie_lab_bits_per_l_bits_per_a_bits_per_b_3}


```
 get_cie_lab(bits_per_l, bits_per_a, bits_per_b) 
```

Obtient la couleur CIE Lab avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_l | int | Le nombre de bits par canal L. |
| bits_per_a | int | Le nombre de bits par canal A. |
| bits_per_b | int | Le nombre de bits par canal B. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur CIE Lab. |


### Method: get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel)  [static] {#get_cmyk_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_4}


```
 get_cmyk(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel) 
```

Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | Le nombre de bits par canal Cyan. |
| bits_per_magenta_channel | int | Le nombre de bits par canal Magenta. |
| bits_per_yellow_channel | int | Le nombre de bits par canal Jaune. |
| bits_per_key_channel | int | Le nombre de bits par canal Key. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur CMYK. |


### Method: get_cmyk(bits_per_sample)  [static] {#get_cmyk_bits_per_sample_5}


```
 get_cmyk(bits_per_sample) 
```

Obtient la couleur CMYK avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur CMYK. |


### Method: get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel)  [static] {#get_cmyka_bits_per_cyan_channel_bits_per_magenta_channel_bits_per_yellow_channel_bits_per_key_channel_bits_per_alpha_channel_6}


```
 get_cmyka(bits_per_cyan_channel, bits_per_magenta_channel, bits_per_yellow_channel, bits_per_key_channel, bits_per_alpha_channel) 
```

Obtient la couleur CMYKA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_cyan_channel | int | Le nombre de bits par canal Cyan. |
| bits_per_magenta_channel | int | Le nombre de bits par canal Magenta. |
| bits_per_yellow_channel | int | Le nombre de bits par canal Jaune. |
| bits_per_key_channel | int | Le nombre de bits par canal Key. |
| bits_per_alpha_channel | int | Le nombre de bits par canal Alpha. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur CMYK. |


### Method: get_grayscale(bits_per_sample)  [static] {#get_grayscale_bits_per_sample_7}


```
 get_grayscale(bits_per_sample) 
```

Obtient la couleur Niveaux de gris avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur Niveaux de gris. |


### Method: get_grayscale_alpha(bits_per_sample)  [static] {#get_grayscale_alpha_bits_per_sample_8}


```
 get_grayscale_alpha(bits_per_sample) 
```

Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur GrayscaleAlpha. |


### Method: get_grayscale_alpha(bits_per_sample, alpha_channel_bits)  [static] {#get_grayscale_alpha_bits_per_sample_alpha_channel_bits_9}


```
 get_grayscale_alpha(bits_per_sample, alpha_channel_bits) 
```

Obtient la couleur GrayscaleAlpha avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |
| alpha_channel_bits | int | Le nombre de bits par échantillon dans le canal alpha. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur GrayscaleAlpha. |


### Method: get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel)  [static] {#get_rgb_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_10}


```
 get_rgb(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel) 
```

Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | Le nombre de bits par canal Rouge. |
| bits_per_green_channel | int | Le nombre de bits par canal Vert. |
| bits_per_blue_channel | int | Le nombre de bits par canal Bleu. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur RGB. |


### Method: get_rgb(bits_per_sample)  [static] {#get_rgb_bits_per_sample_11}


```
 get_rgb(bits_per_sample) 
```

Obtient la couleur RGB avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur RGB. |


### Method: get_rgb_indexed(bits_per_sample)  [static] {#get_rgb_indexed_bits_per_sample_12}


```
 get_rgb_indexed(bits_per_sample) 
```

Obtient la couleur indexée BGRA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur BGRA. |


### Method: get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel)  [static] {#get_rgba_bits_per_red_channel_bits_per_green_channel_bits_per_blue_channel_bits_per_alpha_channel_13}


```
 get_rgba(bits_per_red_channel, bits_per_green_channel, bits_per_blue_channel, bits_per_alpha_channel) 
```

Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_red_channel | int | Le nombre de bits par canal Rouge. |
| bits_per_green_channel | int | Le nombre de bits par canal Vert. |
| bits_per_blue_channel | int | Le nombre de bits par canal Bleu. |
| bits_per_alpha_channel | int | Le nombre de bits par canal Alpha. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur RGBA. |


### Method: get_rgba(bits_per_sample)  [static] {#get_rgba_bits_per_sample_14}


```
 get_rgba(bits_per_sample) 
```

Obtient la couleur RGBA avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur RGBA. |


### Method: get_y_cb_cr(bits_per_sample)  [static] {#get_y_cb_cr_bits_per_sample_15}


```
 get_y_cb_cr(bits_per_sample) 
```

Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur YCbCr. |


### Method: get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr)  [static] {#get_y_cb_cr_bits_per_y_bits_per_cb_bits_per_cr_16}


```
 get_y_cb_cr(bits_per_y, bits_per_cb, bits_per_cr) 
```

Obtient la couleur YCbCr avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_y | int | Le nombre de bits par canal Y. |
| bits_per_cb | int | Le nombre de bits par canal Cb. |
| bits_per_cr | int | Le nombre de bits par canal Cr. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur YCbCr. |


### Method: get_ycck(bits_per_sample)  [static] {#get_ycck_bits_per_sample_17}


```
 get_ycck(bits_per_sample) 
```

Obtient la couleur YCCK avec un nombre spécifié de bits par échantillon.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| bits_per_sample | int | Le nombre de bits par échantillon. |

**Returns**

| Type | Description |
| :- | :- |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | La couleur YCCK. |


