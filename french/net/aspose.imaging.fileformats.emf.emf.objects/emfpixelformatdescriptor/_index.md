---
title: EmfPixelFormatDescriptor
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet PixelFormatDescriptor peut être utilisé dans les enregistrements EMR_HEADER section 2.3.4.2 pour spécifier le format de pixel de la surface de sortie pour le contexte du périphérique de lecture.
type: docs
weight: 3120
url: /fr/net/aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/
---
## EmfPixelFormatDescriptor class

L'objet PixelFormatDescriptor peut être utilisé dans les enregistrements EMR_HEADER (section 2.3.4.2) pour spécifier le format de pixel de la surface de sortie pour le contexte du périphérique de lecture.

```csharp
public sealed class EmfPixelFormatDescriptor : EmfObject
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [EmfPixelFormatDescriptor](emfpixelformatdescriptor)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BReserved](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/breserved) { get; set; } | Gets ou sets spécifie le nombre de plans de superposition et de sous-couche. Les bits 0 à 3 spécifient jusqu'à 15 plans de superposition et les bits 4 à 7 spécifient jusqu'à 15 plans de sous-couche |
| [CAccumAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumalphabits) { get; set; } | Obtient ou définit le nombre de plans de bits alpha dans le tampon d'accumulation |
| [CAccumBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbits) { get; set; } | Obtient ou définit le nombre total de plans de bits dans le tampon d'accumulation. |
| [CAccumBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumbluebits) { get; set; } | Obtient ou définit le nombre de plans de bits bleus dans le tampon d'accumulation. |
| [CAccumGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumgreenbits) { get; set; } | Obtient ou définit le nombre de plans de bits verts dans l'accumulation |
| [CAccumRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/caccumredbits) { get; set; } | Obtient ou définit le nombre de plans de bits rouges dans le tampon d'accumulation |
| [CAlphaBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphabits) { get; set; } | Obtient ou définit le nombre de plans de bits alpha dans chaque tampon de couleur RGBA |
| [CAlphaShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/calphashift) { get; set; } | Obtient ou définit le nombre de décalages pour les plans de bits alpha dans chaque tampon de couleur RGBA |
| [CAuxBuffers](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cauxbuffers) { get; set; } | Gets ou sets spécifie le nombre de tampons auxiliaires. Les tampons auxiliaires ne sont pas pris en charge |
| [CBlueBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cbluebits) { get; set; } | Obtient ou définit le nombre de plans de bits bleus dans chaque tampon de couleur RGBA. |
| [CBlueShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cblueshift) { get; set; } | Obtient ou définit le nombre de décalages pour les plans de bits bleus dans chaque tampon de couleur RGBA. |
| [CColorBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ccolorbits) { get; set; } | Obtient ou définit le nombre de bits par pixel pour les types de pixels RGBA, à l'exclusion des plans de bits alpha. Pour les pixels de la table des couleurs, il s'agit de la taille de chaque table des couleurs index |
| [CDepthBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cdepthbits) { get; set; } | Obtient ou définit la profondeur du tampon de profondeur (axe z). |
| [CGreenBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenbits) { get; set; } | Obtient ou définit le nombre de plans de bits verts dans chaque tampon de couleur RGBA |
| [CGreenShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cgreenshift) { get; set; } | Obtient ou définit le nombre de décalages pour les plans de bits verts dans chaque tampon de couleur RGBA. |
| [CRedBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credbits) { get; set; } | Obtient ou définit le nombre de plans de bits rouges dans chaque tampon de couleur RGBA |
| [CRedShift](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/credshift) { get; set; } | Obtient ou définit le nombre de décalages en bits pour les plans de bits rouges dans chaque tampon de couleur RGBA. |
| [CStencilBits](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/cstencilbits) { get; set; } | Obtient ou définit la profondeur du tampon de gabarit. |
| [DwDamageMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwdamagemask) { get; set; } | Obtient ou définit Ce champ PEUT être ignoré |
| [DwFlags](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwflags) { get; set; } | Obtient ou définit des indicateurs de bits qui spécifient les propriétés du tampon de pixels utilisé pour la sortie sur la surface de dessin. Ces propriétés ne sont pas toutes mutuellement exclusives ; les combinaisons de drapeaux sont autorisées, sauf indication contraire. |
| [DwLayerMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwlayermask) { get; set; } | Obtient ou définit Ce champ PEUT être ignoré. |
| [DwVisibleMask](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/dwvisiblemask) { get; set; } | Gets ou sets spécifie la couleur transparente ou l'indice d'un plan sous-jacent. Lorsque le type de pixel est RGBA, dwVisibleMask est une valeur de couleur RVB transparente. Lorsque le type de pixel est un index de couleur, il s'agit d'une valeur d'index transparent. |
| [ILayerType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ilayertype) { get; set; } | Obtient ou définit Ce champ PEUT être ignoré |
| [IPixelType](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/ipixeltype) { get; set; } | Obtient ou définit le type de données de pixel PFD_TYPE_RGBA 0x00 Le format de pixel est RGBA. PFD_TYPE_COLORINDEX 0x01 Chaque pixel est un index dans une table de couleurs. |
| [NSize](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nsize) { get; set; } | Obtient ou définit un entier 16 bits qui spécifie la taille, en octets, de cette structure de données. |
| [NVersion](../../aspose.imaging.fileformats.emf.emf.objects/emfpixelformatdescriptor/nversion) { get; set; } | Obtient ou définit un entier 16 bits qui DOIT être défini sur 0x0001. |

### Voir également

* class [EmfObject](../emfobject)
* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Objects](../../aspose.imaging.fileformats.emf.emf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
