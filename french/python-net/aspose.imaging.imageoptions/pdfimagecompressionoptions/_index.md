---
title: "Énumération PdfImageCompressionOptions"
type: docs
weight: 400
url: /fr/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/
---

Options de compression d'images PDF

**Module:** [aspose.imaging.imageoptions](/imaging/python-net/aspose.imaging.imageoptions/)

**Full Name:** aspose.imaging.imageoptions.PdfImageCompressionOptions

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| AUTO | Sélectionne automatiquement la compression la plus appropriée pour chaque image. |
| CCITT3 | /CCITTFaxDecode/DecodeParms/K 0/Columns 173<br/>            Ne prend pas en charge la transparence. |
| CCITT4 | /CCITTFaxDecode/DecodeParms/K -1/Columns 173<br/>            Ne prend pas en charge la transparence. |
| FLATE | Compression Flate. |
| JPEG | Compression Jpeg.<br/>            Ne prend pas en charge la transparence. |
| LZW_BASELINE_PREDICTOR | La sélection du prédicteur est limitée au prédicteur PNG Paeth pour accélérer le processus. En pratique<br/>            donne des résultats étonnamment bons. Meilleur que [PdfImageCompressionOptions.LZW_OPTIMIZED_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/). |
| LZW_OPTIMIZED_PREDICTOR | La sélection du prédicteur est plus compliquée et devrait donner des tailles d'image plus petites mais<br/>            prend plus de temps. La RFC 2083 indique que c'est la meilleure approche. Mais sur les données de test, le prédicteur de référence
            [PdfImageCompressionOptions.LZW_BASELINE_PREDICTOR](/imaging/python-net/aspose.imaging.imageoptions/pdfimagecompressionoptions/) déchire, laissant le prédicteur optimisé derrière <br/>            avec des gains de taux de compression de 25 à 40 %. |
| NONE | Enregistre les octets d'image bruts, ce qui entraîne des tailles de fichiers PDF plus importantes. |
| RLE | Compression Run Length. |
