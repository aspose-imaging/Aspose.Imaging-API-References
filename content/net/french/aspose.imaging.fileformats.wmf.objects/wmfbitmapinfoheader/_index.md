---
title: WmfBitmapInfoHeader
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lobjet BitmapInfoHeader contient des informations sur les dimensions et le format de couleur dun bitmap indépendant du périphérique DIB.
type: docs
weight: 8470
url: /fr/aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/
---
## WmfBitmapInfoHeader class

L'objet BitmapInfoHeader contient des informations sur les dimensions et le format de couleur d'un bitmap indépendant du périphérique (DIB).

```csharp
public class WmfBitmapInfoHeader : WmfBitmapBaseHeader
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [WmfBitmapInfoHeader](wmfbitmapinfoheader)() | Default_Constructor |

## Propriétés

| Nom | La description |
| --- | --- |
| [BitCount](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/bitcount) { get; set; } | Obtient ou définit un entier non signé 16 bits qui définit le format de chaque pixel et le nombre maximal de couleurs dans la DIB. Cette valeur DOIT être dans le[`BitCount`](../wmfbitmapbaseheader/bitcount) Énumération (section 2.1.1.3). |
| [ColorImportant](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorimportant) { get; set; } | Obtient ou définit un entier non signé 32 bits qui définit le nombre d'index de couleur requis pour afficher la DIB. Si cette valeur est zéro, tous les index de couleur sont requis |
| [ColorUsed](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/colorused) { get; set; } | Obtient ou définit un entier non signé 32 bits qui spécifie le nombre d'index dans la table de couleurs utilisée par la DIB, car suit : Si cette valeur est zéro, la DIB utilise le nombre maximal de couleurs correspondant à la valeur BitCount. Si cette valeur est différente de zéro et que la valeur BitCount est inférieure à 16, cette valeur spécifie le nombre de couleurs utilisées par la DIB. Si cette valeur est différente de zéro et que la valeur BitCount est supérieure ou égale à 16, cette valeur spécifie la taille de la couleur table utilisée pour optimiser les performances de la palette système. Remarque Si cette valeur est différente de zéro et supérieure à la taille maximale possible de la table des couleurs basée sur la valeur BitCount , la taille maximale de la table des couleurs DEVRAIT être supposée. |
| [Compression](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/compression) { get; set; } | Obtient ou définit un entier non signé 32 bits qui définit le mode de compression de la DIB. Cette valeur DOIT figurer dans l' Compression Enumeration (section 2.1.1.7). Cette valeur NE DOIT PAS spécifier un format compressé si la DIB est une image bitmap descendante, comme indiqué par la valeur Height. |
| [HeaderSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/headersize) { get; set; } | Obtient ou définit un entier non signé 32 bits qui définit la taille de cet objet , en octets. |
| [Height](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/height) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit la hauteur de la DIB, en pixels. Cette valeur NE DOIT PAS être zéro. Si cette valeur est positive, le DIB est un bitmap ascendant et son origine est le coin inférieur gauche. Si cette valeur est négative, le DIB est un bitmap descendant et son origine est le coin supérieur gauche. Les bitmaps descendants ne prennent pas en charge la compression. Ce champ DEVRAIT spécifier la hauteur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG . |
| [ImageSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/imagesize) { get; set; } | Obtient ou définit un entier non signé de 32 bits qui définit la taille, en octets, de l'image. Si la valeur de compression est BI_RGB, cette valeur DEVRAIT être zéro et DOIT être ignorée. Si la valeur de compression est BI_JPEG ou BI_PNG, cette valeur DOIT spécifier la taille du tampon d'image JPEG ou PNG, respectivement. |
| [Planes](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapbaseheader/planes) { get; set; } | Obtient ou définit un entier non signé 16 bits qui définit le nombre de planes pour l'appareil cible. Cette valeur DOIT être 0x0001. |
| [Width](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/width) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit la largeur de la DIB, en pixels. Cette valeur DOIT être positive. Ce champ DEVRAIT spécifier la largeur du fichier image décompressé, si la valeur Compression spécifie le format JPEG ou PNG . |
| [XPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/xpelspermeter) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit la résolution horizontale, en pixels par mètre, du périphérique cible pour le DIB |
| [YPelsPerMeter](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/ypelspermeter) { get; set; } | Obtient ou définit un entier signé 32 bits qui définit la résolution verticale, en pixels par mètre, du périphérique cible pour le DIB |

## Des champs

| Nom | La description |
| --- | --- |
| const [StructureSize](../../aspose.imaging.fileformats.wmf.objects/wmfbitmapinfoheader/structuresize) | La taille de la structure |

### Voir également

* class [WmfBitmapBaseHeader](../wmfbitmapbaseheader)
* espace de noms [Aspose.Imaging.FileFormats.Wmf.Objects](../../aspose.imaging.fileformats.wmf.objects)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
