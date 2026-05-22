---
title: "EmfPixelFormatDescriptor Classe"
type: docs
weight: 220
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---

**Summary:** The PixelFormatDescriptor object can be used in EMR_HEADER records (section 2.3.4.2) to specify the pixel format of the output surface for the playback device context.

**Module:** [aspose.imaging.fileformats.emf.emf.objects](/imaging/python-net/aspose.imaging.fileformats.emf.emf.objects/)

**Full Name:** aspose.imaging.fileformats.emf.emf.objects.EmfPixelFormatDescriptor

**Inheritance:** EmfObject

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [EmfPixelFormatDescriptor()](#EmfPixelFormatDescriptor__1) | Initialise une nouvelle instance de la classe EmfPixelFormatDescriptor |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| b_reserved | System.Byte | r/w | Obtient ou définit spécifie le nombre de plans de superposition et de sous‑couche. Les bits 0 à 3 spécifient <br/>            jusqu’à 15 plans de superposition et les bits 4 à 7 spécifient jusqu’à 15 plans de sous‑couche |
| c_accum_alpha_bits | System.Byte | r/w | Obtient ou définit spécifie le nombre de plans de bits alpha dans le tampon d’accumulation |
| c_accum_bits | System.Byte | r/w | Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation. |
| c_accum_blue_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation. |
| c_accum_green_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits verts dans l'accumulation |
| c_accum_red_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation. |
| c_alpha_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits alpha dans chaque tampon de couleur RGBA. |
| c_alpha_shift | System.Byte | r/w | Obtient ou définit le nombre de décalage pour les plans de bits alpha dans chaque tampon de couleur RGBA. |
| c_aux_buffers | System.Byte | r/w | Obtient ou définit le nombre de tampons auxiliaires. Les tampons auxiliaires ne sont pas pris en charge |
| c_blue_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits bleus dans chaque tampon de couleur RGBA. |
| c_blue_shift | System.Byte | r/w | Obtient ou définit le nombre de décalage pour les plans de bits bleus dans chaque tampon de couleur RGBA. |
| c_color_bits | System.Byte | r/w | Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, excluant les plans de bits alpha. Pour les pixels de table de couleurs, il s'agit de la taille de chaque index de table de couleurs |
| c_depth_bits | System.Byte | r/w | Obtient ou définit la profondeur du tampon de profondeur (axe z). |
| c_green_bits | System.Byte | r/w | Obtient ou définit le nombre de plans de bits verts dans chaque tampon de couleur RGBA |
| c_green_shift | System.Byte | r/w | Obtient ou définit  Spécifie le nombre de décalages pour les plans de bits verts dans chaque tampon de couleur RGBA. |
| c_red_bits | System.Byte | r/w | Obtient ou définit  Spécifie le nombre de plans de bits rouges dans chaque tampon de couleur RGBA |
| c_red_shift | System.Byte | r/w | Obtient ou définit  Spécifie le nombre de décalages en bits pour les plans de bits rouges dans chaque tampon de couleur RGBA. |
| c_stencil_bits | System.Byte | r/w | Obtient ou définit la profondeur du tampon de pochoir. |
| dw_damage_mask | int | r/w | Obtient ou définit Ce champ PEUT être ignoré |
| dw_flags | int | r/w | Obtient ou définit des indicateurs binaires qui spécifient les propriétés du tampon de pixels utilisé <br/>            pour la sortie vers la surface de dessin. Ces propriétés ne sont pas toutes mutuellement <br/>            exclusives ; des combinaisons d'indicateurs sont autorisées, sauf indication contraire. |
| dw_layer_mask | int | r/w | Obtient ou définit Ce champ PEUT être ignoré. |
| dw_visible_mask | int | r/w | Obtient ou définit spécifie la couleur transparente ou l'index d'un plan sous-jacent. Lorsque le type de pixel <br/>            est RGBA, dwVisibleMask est une valeur de couleur RGB transparente. Lorsque le type de pixel <br/>            est un index de couleur, il s'agit d'une valeur d'index transparente. |
| layer_type | System.Byte | r/w | Obtient ou définit Ce champ PEUT être ignoré |
| n_size | int | r/w | Obtient ou définit un entier de 16 bits qui spécifie la taille, en octets, de cette structure de données. |
| n_version | int | r/w | Obtient ou définit un entier de 16 bits qui DOIT être fixé à 0x0001. |
| pixel_type | System.Byte | r/w | Obtient ou définit le type de données de pixel<br/>            PFD_TYPE_RGBA       0x00 Le format de pixel est RGBA.<br/>            PFD_TYPE_COLORINDEX 0x01 Chaque pixel est un index dans une table de couleurs. |


### Constructor: EmfPixelFormatDescriptor() {#EmfPixelFormatDescriptor__1}


```
 EmfPixelFormatDescriptor() 
```

Initialise une nouvelle instance de la classe EmfPixelFormatDescriptor

