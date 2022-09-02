---
title: BitmapV5Header
second_title: Référence de l'API Aspose.Imaging pour .NET
description: La structure BitmapV5Header est le fichier den-tête dinformations bitmap. Il sagit dune version étendue de la structure BITMAPINFOHEADER. Si bV5Height est négatif indiquant un DIB descendant bV5Compression doit être BI_RGB ou BI_BITFIELDS. Les fichiers DIB descendants ne peuvent pas être compressés. Linterface de gestion indépendante des couleurs ICM 2.0 permet aux profils de couleur ICC International Color Consortium dêtre liés ou intégrés dans des fichiers DIB DIB. Voir Utilisation des structures pour plus dinformations. Lorsquun DIB est chargé en mémoire les données de profil le cas échéant doivent suivre la table des couleurs et le bV5ProfileData doit fournir le décalage des données de profil depuis le début de la structure BITMAPV5HEADER. La valeur stockée dans bV5ProfileData sera différente de la valeur renvoyée par lopérateur sizeof étant donné largument BITMAPV5HEADER car bV5ProfileData est le décalage en octets entre le début de la structure BITMAPV5HEADER et le début des données de profil. les bits bitmap ne suivent pas la table des couleurs en mémoire. Les applications doivent modifier le membre bV5ProfileData après avoir chargé la DIB dans la mémoire. Pour les DIB compressés les données de profil doivent suivre les bits bitmap similaires au format de fichier. Le membre bV5ProfileData doit toujours donner le décalage des données de profil depuis le début du BITMAPV5HEADER. Les applications doivent accéder aux données de profil uniquement lorsque bV5Size est égal à la taille du BITMAPV5HEADER et bV5CSType est égal à PROFILE_EMBEDDED ou PROFILE_LINKED.
type: docs
weight: 1370
url: /fr/net/aspose.imaging.fileformats.bmp/bitmapv5header/
---
## BitmapV5Header class

La structure BitmapV5Header est le fichier d'en-tête d'informations bitmap. Il s'agit d'une version étendue de la structure BITMAPINFOHEADER. Si bV5Height est négatif, indiquant un DIB descendant, bV5Compression doit être BI_RGB ou BI_BITFIELDS. Les fichiers DIB descendants ne peuvent pas être compressés. L'interface de gestion indépendante des couleurs (ICM) 2.0 permet aux profils de couleur ICC (International Color Consortium) d'être liés ou intégrés dans des fichiers DIB (DIB). Voir Utilisation des structures pour plus d'informations. Lorsqu'un DIB est chargé en mémoire, les données de profil (le cas échéant) doivent suivre la table des couleurs, et le bV5ProfileData doit fournir le décalage des données de profil depuis le début de la structure BITMAPV5HEADER. La valeur stockée dans bV5ProfileData sera différente de la valeur renvoyée par l'opérateur sizeof étant donné l'argument BITMAPV5HEADER, car bV5ProfileData est le décalage en octets entre le début de la structure BITMAPV5HEADER et le début des données de profil. (les bits bitmap ne suivent pas la table des couleurs en mémoire). Les applications doivent modifier le membre bV5ProfileData après avoir chargé la DIB dans la mémoire. Pour les DIB compressés, les données de profil doivent suivre les bits bitmap similaires au format de fichier. Le membre bV5ProfileData doit toujours donner le décalage des données de profil depuis le début du BITMAPV5HEADER. Les applications doivent accéder aux données de profil uniquement lorsque bV5Size est égal à la taille du BITMAPV5HEADER et bV5CSType est égal à PROFILE_EMBEDDED ou PROFILE_LINKED.

```csharp
public class BitmapV5Header : BitmapV4Header
```

## Propriétés

| Nom | La description |
| --- | --- |
| [AlphaMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/alphamask) { get; set; } | Obtient ou définit le masque de couleur qui spécifie le composant alpha de chaque pixel. |
| [BitmapColorsImportant](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsimportant) { get; set; } | Obtient ou définit le nombre de couleurs de palette importantes. |
| [BitmapColorsUsed](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcolorsused) { get; set; } | Obtient ou définit le nombre de couleurs de palette utilisées. |
| [BitmapCompression](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapcompression) { get; set; } | Obtient ou définit la compression bitmap. |
| [BitmapHeight](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapheight) { get; set; } | Obtient ou définit la hauteur du bitmap. |
| [BitmapImageSize](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapimagesize) { get; set; } | Obtient ou définit la taille des données brutes bitmap en octets. |
| [BitmapPlanes](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapplanes) { get; set; } | Obtient ou définit le nombre de plans. |
| [BitmapWidth](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitmapwidth) { get; set; } | Obtient ou définit la largeur du bitmap. |
| [BitmapXPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapxpelspermeter) { get; set; } | Obtient ou définit la résolution horizontale en pixels. |
| [BitmapYPelsPerMeter](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/bitmapypelspermeter) { get; set; } | Obtient ou définit la résolution verticale en pixels. |
| [BitsPerPixel](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/bitsperpixel) { get; set; } | Obtient ou définit le nombre de bits par pixel. |
| [BlueMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/bluemask) { get; set; } | Obtient ou définit le masque de couleur qui spécifie la composante bleue de chaque pixel, valide uniquement si bV4Compression est défini sur BI_BITFIELDS. |
| [CSType](../../aspose.imaging.fileformats.bmp/bitmapv4header/cstype) { get; set; } | Obtient ou définit l'espace colorimétrique de la DIB. |
| [Endpoints](../../aspose.imaging.fileformats.bmp/bitmapv4header/endpoints) { get; set; } | Obtient ou définit la classe CoordinatesTriple. |
| [ExtraBitMasks](../../aspose.imaging.fileformats.bmp/bitmapinfoheader/extrabitmasks) { get; set; } | Obtient ou définit les masques de bits supplémentaires. Présent uniquement si l'en-tête DIB est le BITMAPINFOHEADER et le[`BitmapCompression`](../bitmapinfoheader/bitmapcompression) est réglé soit surBitfields (RVB) ouAlphaBitfields (RVBA). |
| [GammaBlue](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammablue) { get; set; } | Obtient ou définit le gamma bleu. |
| [GammaGreen](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammagreen) { get; set; } | Obtient ou définit le vert gamma. |
| [GammaRed](../../aspose.imaging.fileformats.bmp/bitmapv4header/gammared) { get; set; } | Obtient ou définit le gamma rouge. |
| [GreenMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/greenmask) { get; set; } | Obtient ou définit le masque de couleur qui spécifie la composante verte de chaque pixel, valide uniquement si bV4Compression est défini sur BI_BITFIELDS. |
| [HeaderSize](../../aspose.imaging.fileformats.bmp/bitmapcoreheader/headersize) { get; set; } | Obtient ou définit la taille de cette structure en octets. |
| [Intent](../../aspose.imaging.fileformats.bmp/bitmapv5header/intent) { get; set; } | Obtient ou définit l'intention de rendu pour le bitmap. |
| [ProfileData](../../aspose.imaging.fileformats.bmp/bitmapv5header/profiledata) { get; set; } | Obtient ou définit les données de profil. |
| [ProfileSize](../../aspose.imaging.fileformats.bmp/bitmapv5header/profilesize) { get; set; } | Obtient ou définit la taille du profil. |
| [RedMask](../../aspose.imaging.fileformats.bmp/bitmapv4header/redmask) { get; set; } | Obtient ou définit le masque de couleur qui spécifie la composante rouge de chaque pixel, valide uniquement si bV4Compression est défini sur BI_BITFIELDS. |
| [Reserved](../../aspose.imaging.fileformats.bmp/bitmapv5header/reserved) { get; set; } | Obtient ou définit le membre réservé. |

### Voir également

* class [BitmapV4Header](../bitmapv4header)
* espace de noms [Aspose.Imaging.FileFormats.Bmp](../../aspose.imaging.fileformats.bmp)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
