---
title: "aspose.imaging.fileformats.bmp"
type: docs
weight: 140
url: /fr/python-net/aspose.imaging.fileformats.bmp/
---


Le module gère le traitement du format de fichier Bmp.

## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [BitmapCoreHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcoreheader/) | Dimensions et format couleur du DIB.<br/>            Nom d'en-tête BITMAPCOREHEADER alias OS21XBITMAPHEADER. |
| [BitmapInfoHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapinfoheader/) | Spécifie BITMAPINFOHEADER. <br/>                Support OS : Windows NT, 3.1x ou ultérieur.<br/>                Fonctionnalités : Ajoute les formats 16 bpp et 32 bpp. Ajoute la compression RLE. |
| [BitmapV4Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv4header/) | La structure BitmapV4Header est le fichier d'en-tête d'information bitmap. C'est une version étendue de la structure BITMAPINFOHEADER.<br/>            <br/>La structure BitmapV4Header est étendue pour permettre à une image JPEG ou PNG d'être transmise comme image source à StretchDIBits.<br/> |
| [BitmapV5Header](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapv5header/) | La structure BitmapV5Header est le fichier d'en-tête d'information bitmap. C'est une version étendue de la structure BITMAPINFOHEADER.<br/>            <br/>Si bV5Height est négatif, indiquant un DIB top‑down, bV5Compression doit être soit BI_RGB soit BI_BITFIELDS. Les DIB top‑down ne peuvent pas être compressés.<br/>            L'interface Independent Color Management (ICM) 2.0 permet aux profils couleur du International Color Consortium (ICC) d'être liés ou incorporés dans les DIB (DIB). <br/>            Voir Using Structures pour plus d'informations. Lorsqu'un DIB est chargé en mémoire, les données de profil (si présentes) doivent suivre la table de couleurs, <br/>            et bV5ProfileData doit fournir le décalage des données de profil depuis le début de la structure BITMAPV5HEADER. <br/>            La valeur stockée dans bV5ProfileData sera différente de celle renvoyée par l'opérateur sizeof appliqué à l'argument BITMAPV5HEADER, <br/>            car bV5ProfileData représente le décalage en octets depuis le début de la structure BITMAPV5HEADER jusqu'au début des données de profil. <br/>            (Les bits du bitmap ne suivent pas la table de couleurs en mémoire). Les applications doivent modifier le membre bV5ProfileData après le chargement du DIB en mémoire.<br/>            Pour les DIB empaquetés, les données de profil doivent suivre les bits du bitmap comme dans le format de fichier. <br/>            Le membre bV5ProfileData doit toujours fournir le décalage des données de profil depuis le début de la BITMAPV5HEADER.<br/>            Les applications ne doivent accéder aux données de profil que lorsque bV5Size est égal à la taille de la BITMAPV5HEADER et que bV5CSType est égal à PROFILE_EMBEDDED ou PROFILE_LINKED.<br/> |
| [BmpImage](/imaging/python-net/aspose.imaging.fileformats.bmp/bmpimage/) | Vous pouvez gérer sans effort les fichiers Bitmap (BMP) et Device Independent Bitmap<br/>            (DIB), facilitant la manipulation et le traitement efficaces des images raster.<br/>            En effectuant diverses opérations sur les images, cette API simplifie le<br/>            flux de travail, offrant aux développeurs une boîte à outils fiable pour travailler avec les formats BMP et<br/>            DIB dans leurs applications logicielles. |
| [Os22XBitmapHeader](/imaging/python-net/aspose.imaging.fileformats.bmp/os22xbitmapheader/) | Un OS/2 2.x OS22XBITMAPHEADER alias BITMAPCOREHEADER2. |
## **Enumerations**
| **Énumération** | **Description** |
| :- | :- |
| [BitmapCompression](/imaging/python-net/aspose.imaging.fileformats.bmp/bitmapcompression/) | Spécifie différentes méthodes de compression bitmap. |
