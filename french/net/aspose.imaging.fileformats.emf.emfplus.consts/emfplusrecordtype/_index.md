---
title: EmfPlusRecordType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération RecordType définit les types denregistrement utilisés dans les métafichiers EMF.
type: docs
weight: 5030
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
## EmfPlusRecordType enumeration

L'énumération RecordType définit les types d'enregistrement utilisés dans les métafichiers EMF+.

```csharp
public enum EmfPlusRecordType : short
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| EmfPlusHeader | `16385` | Cet enregistrement spécifie le début des données EMF+ dans le métafichier. Il DOIT être intégré dans le premier enregistrement EMF après le[`EmfMetafileHeader`](../../aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) record ([MS-EMF] section 2.3.4.2 record). |
| EmfPlusEndOfFile | `16386` | Cet enregistrement spécifie la fin des données EMF+ dans le métafichier. |
| EmfPlusComment | `16387` | Cet enregistrement spécifie des données privées arbitraires. |
| EmfPlusGetDC | `16388` | Cet enregistrement spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DEVRAIENT être traités. Les enregistrements EMF cessent d'être traités lorsque le prochain enregistrement EMF+ est rencontré. |
| EmfPlusMultiFormatStart | `16389` | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EmfPlusMultiFormatSection | `16390` | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EmfPlusMultiFormatEnd | `16391` | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EmfPlusObject | `16392` | Cet enregistrement spécifie un objet à utiliser dans les opérations graphiques. |
| EmfPlusClear | `16393` | Cet enregistrement efface la sortie`espace de coordonnées` et l'initialise avec une couleur d'arrière-plan et une transparence spécifiées. |
| EmfPlusFillRects | `16394` | Cet enregistrement définit comment remplir l'intérieur d'une série de rectangles, à l'aide d'un pinceau spécifié. |
| EmfPlusDrawRects | `16395` | Cet enregistrement définit les traits de stylo pour dessiner une série de rectangles. |
| EmfPlusFillPolygon | `16396` | Cet enregistrement définit les données pour remplir l'intérieur d'un polygone, à l'aide d'un pinceau spécifié. |
| EmfPlusDrawLines | `16397` | Cet enregistrement définit les traits de stylo pour dessiner une série de lignes connectées. |
| EmfPlusFillEllipse | `16398` | Cet enregistrement définit comment remplir l'intérieur d'une ellipse à l'aide d'un pinceau spécifié. |
| EmfPlusDrawEllipse | `16399` | Cet enregistrement définit les traits de stylo pour dessiner une ellipse. |
| EmfPlusFillPie | `16400` | Cet enregistrement définit comment remplir une section d'une section intérieure d'une ellipse à l'aide d'un pinceau spécifié. |
| EmfPlusDrawPie | `16401` | Cet enregistrement définit les traits de stylo pour dessiner une section d'ellipse. |
| EmfPlusDrawArc | `16402` | L'enregistrement définit les traits de stylo pour dessiner un arc d'ellipse. |
| EmfPlusFillRegion | `16403` | Cet enregistrement définit comment remplir l'intérieur d'une région à l'aide d'un pinceau spécifié. |
| EmfPlusFillPath | `16404` | L'enregistrement définit comment remplir l'intérieur des figures définies dans un chemin graphique avec un pinceau spécifié. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes. |
| EmfPlusDrawPath | `16405` | L'enregistrement définit les traits de stylo pour dessiner les figures dans un chemin graphique. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes. |
| EmfPlusFillClosedCurve | `16406` | Cet enregistrement définit comment remplir l'intérieur d'une spline cardinale fermée à l'aide d'un pinceau spécifié. |
| EmfPlusDrawClosedCurve | `16407` | Cet enregistrement définit la plume et les traits pour dessiner une spline cardinale fermée. |
| EmfPlusDrawCurve | `16408` | Cet enregistrement définit les traits de stylo pour dessiner une spline cardinale. |
| EmfPlusDrawBeziers | `16409` | Cet enregistrement définit les traits de stylo pour dessiner une spline de Bézier. |
| EmfPlusDrawImage | `16410` | Cet enregistrement définit une mise à l'échelle[`EmfPlusImage`](../../aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage)objet (section 2.2.1.4). Une image peut être constituée de données bitmap ou de métafichier. |
| EmfPlusDrawImagePoints | `16411` | Cet enregistrement définit un objet EmfPlusImage mis à l'échelle à l'intérieur d'un parallélogramme. Une image peut être constituée de données bitmap ou de métafichier. |
| EmfPlusDrawString | `16412` | Cet enregistrement définit une chaîne de texte basée sur une police, un rectangle de mise en page et un format. |
| EmfPlusSetRenderingOrigin | `16413` | Cet enregistrement définit l'origine du rendu aux coordonnées horizontales et verticales spécifiées. Cela s'applique aux brosses hachurées et aux motifs de tramage 8 et 16 bits par pixel. |
| EmfPlusSetAntiAliasMode | `16414` | Cet enregistrement définit s'il faut activer ou désactiver l'anticrénelage du texte. L'anti-crénelage du texte est une méthode permettant de rendre les lignes et les bords des glyphes de caractères plus lisses lorsqu'ils sont dessinés sur une surface de sortie. |
| EmfPlusSetTextRenderingHint | `16415` | Cet enregistrement définit le processus utilisé pour le rendu du texte. |
| EmfPlusSetTextContrast | `16416` | Cet enregistrement définit le contraste du texte en fonction de la valeur gamma du texte spécifiée. |
| EmfPlusSetInterpolationMode | `16417` | Cet enregistrement définit le mode d'interpolation d'un objet en fonction du type de filtrage d'image spécifié. Le mode d'interpolation influence la façon dont la mise à l'échelle (étirement et rétrécissement) est effectuée. |
| EmfPlusSetPixelOffsetMode | `16418` | Cet enregistrement définit le mode de décalage des pixels en fonction de la valeur de centrage des pixels spécifiée. |
| EmfPlusSetCompositingMode | `16419` | Cet enregistrement définit le mode de composition en fonction de l'état de la fusion alpha, qui spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. |
| EmfPlusSetCompositingQuality | `16420` | Cet enregistrement définit la qualité de composition, qui décrit le niveau de qualité souhaité pour créer des images composites à partir de plusieurs objets. |
| EmfPlusSave | `16421` | Cet enregistrement enregistre l'état graphique, identifié par un index spécifié, sur une pile d'états graphiques enregistrés. Chaque index de pile est associé à un état enregistré particulier, et l'index est utilisé par un[`EmfPlusRestore`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) record (section 2.3.7.4) pour restaurer l'état. |
| EmfPlusRestore | `16422` | Cet enregistrement restitue l'état graphique, identifié par un index spécifié, à partir d'une pile d'états graphiques sauvegardés. Chaque index de pile est associé à un état enregistré particulier, et l'index est défini par un[`EmfPlusSave`](../../aspose.imaging.fileformats.emf.emfplus.records/emfplussave) record (section 2.3.7.5) pour enregistrer l'état. |
| EmfPlusBeginContainer | `16423` | Cet enregistrement ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci. Les conteneurs graphiques sont utilisés pour conserver les éléments de l'état graphique. |
| EmfPlusBeginContainerNoParams | `16424` | Cet enregistrement ouvre un nouveau conteneur d'état graphique. |
| EmfPlusEndContainer | `16425` | Cet enregistrement ferme un conteneur d'état graphique qui a été précédemment ouvert par une opération de début de conteneur. |
| EmfPlusSetWorldTransform | `16426` | Cet enregistrement définit la transformation actuelle de l'espace mondial dans le contexte de périphérique de lecture, selon une matrice de transformation spécifiée. |
| EmfPlusResetWorldTransform | `16427` | Cet enregistrement réinitialise la transformation actuelle de l'espace mondial sur la matrice d'identification. |
| EmfPlusMultiplyWorldTransform | `16428` | Cet enregistrement multiplie l'espace mondial actuel par une matrice de transformation spécifiée. |
| EmfPlusTranslateWorldTransform | `16429` | Cet enregistrement applique une transformation de translation à l'espace mondial actuel par des distances horizontales et verticales spécifiées. |
| EmfPlusScaleWorldTransform | `16430` | Cet enregistrement applique une transformation de mise à l'échelle à l'espace mondial actuel par des facteurs d'échelle horizontaux et verticaux spécifiés. |
| EmfPlusRotateWorldTransform | `16431` | Cet enregistrement fait pivoter l'espace mondial actuel d'un angle spécifié. |
| EmfPlusSetPageTransform | `16432` | Cet enregistrement spécifie des facteurs d'échelle supplémentaires pour la transformation actuelle de l'espace mondial. |
| EmfPlusResetClip | `16433` | Cet enregistrement réinitialise la région de découpage actuelle pour l'espace mondial à l'infini. |
| EmfPlusSetClipRect | `16434` | Cet enregistrement combine la zone de découpage actuelle avec un rectangle. |
| EmfPlusSetClipPath | `16435` | Cet enregistrement combine la zone de découpage actuelle avec un chemin graphique. |
| EmfPlusSetClipRegion | `16436` | Cet enregistrement combine la région de découpage actuelle avec une autre région graphique. |
| EmfPlusOffsetClip | `16437` | Cet enregistrement applique une transformation de translation sur la région de découpage actuelle de l'espace univers. |
| EmfPlusDrawDriverString | `16438` | Cet enregistrement spécifie une sortie de texte avec des positions de caractères. |
| EmfPlusStrokeFillPath | `16439` | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel et remplit son intérieur en utilisant le pinceau actuel. |
| EmfPlusSerializableObject | `16440` | Cet enregistrement définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données. |
| EmfPlusSetTSGraphics | `16441` | Cet enregistrement spécifie l'état d'un contexte de périphérique graphique pour un serveur Terminal Server. |
| EmfPlusSetTSClip | `16442` | Cet enregistrement spécifie les zones de découpage dans le contexte du périphérique graphique pour un serveur Terminal Server. |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.EmfPlus.Consts](../../aspose.imaging.fileformats.emf.emfplus.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
