---
title: EmfRecordType
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lénumération RecordType définit des valeurs qui identifient de manière unique les enregistrements EMF. Ces valeurs sont fournies dans le champ Type de chaque enregistrement.
type: docs
weight: 2820
url: /fr/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
## EmfRecordType enumeration

L'énumération RecordType définit des valeurs qui identifient de manière unique les enregistrements EMF. Ces valeurs sont fournies dans le champ Type de chaque enregistrement.

```csharp
public enum EmfRecordType
```

### Valeurs

| Nom | Évaluer | La description |
| --- | --- | --- |
| EMR_HEADER | `1` | Cet enregistrement définit le début du métafichier et précise ses caractéristiques ; son contenu, incluant les dimensions de l'image intégrée ; le nombre d'enregistrements dans le métafichier ; et la résolution de l'appareil sur lequel l'image intégrée a été créée. Ces valeurs permettent au métafichier d'être indépendant du périphérique. |
| EMR_POLYBEZIER | `2` | Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes de Bézier cubiques sont définies à l'aide de extrémités et points de contrôle spécifiés, et sont tracées avec le stylet actuel. |
| EMR_POLYGON | `3` | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites . Le polygone est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier. |
| EMR_POLYLINE | `4` | Cet enregistrement définit une série de segments de ligne en reliant les points dans le tableau spécifié. |
| EMR_POLYBEZIERTO | `5` | Cet enregistrement définit une ou plusieurs courbes de Bézier en fonction de la position actuelle. |
| EMR_POLYLINETO | `6` | Cet enregistrement définit une ou plusieurs lignes droites en fonction de la position actuelle. Une ligne est tracée de la position actuelle au premier point spécifié par le champ de points en utilisant le stylo actuel. Pour chaque ligne supplémentaire, le dessin est effectué à partir du point de fin de la ligne précédente jusqu'au point suivant spécifié par points. |
| EMR_POLYPOLYLINE | `7` | Cet enregistrement définit plusieurs séries de segments de ligne connectés. Les segments de ligne sont dessinés en utilisant le stylet actuel. Les figures formées par les segments ne sont pas remplies. T la position actuelle n'est ni utilisée ni mise à jour par cet enregistrement. |
| EMR_POLYPOLYGON | `8` | Cet enregistrement définit une série de polygones fermés. Chaque polygone est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage de polygone. Les polygones définis par cet enregistrement peuvent se chevaucher. |
| EMR_SETWINDOWEXTEX | `9` | Cet enregistrement définit l'étendue de la fenêtre. |
| EMR_SETWINDOWORGEX | `10` | Cet enregistrement définit l'origine de la fenêtre. |
| EMR_SETVIEWPORTEXTEX | `11` | Cet enregistrement définit l'étendue de la fenêtre. |
| EMR_SETVIEWPORTORGEX | `12` | Cet enregistrement définit l'origine de la fenêtre. |
| EMR_SETBRUSHORGEX | `13` | Cet enregistrement définit l'origine du pinceau actuel. |
| EMR_EOF | `14` | Cet enregistrement indique la fin du métafichier. |
| EMR_SETPIXELV | `15` | Cet enregistrement définit la couleur du pixel aux coordonnées logiques spécifiées. |
| EMR_SETMAPPERFLAGS | `16` | Cet enregistrement spécifie les paramètres du processus de mise en correspondance des polices logiques avec les polices physiques , qui est effectué par le mappeur de polices. |
| EMR_SETMAPMODE | `17` | Cet enregistrement définit le mode de mappage du contexte de périphérique de lecture. Le mode de mappage définit l'unité de mesure utilisée pour transformer les unités d'espace de page en unités d'espace de périphérique, et définit également l'orientation des axes x et y du périphérique. |
| EMR_SETBKMODE | `18` | Cet enregistrement définit le mode de mixage d'arrière-plan du contexte de périphérique de lecture. Le mode background mix est utilisé avec du texte, des pinceaux hachurés et des styles de stylo qui ne sont pas des lignes pleines. |
| EMR_SETPOLYFILLMODE | `19` | Cet enregistrement définit le mode de remplissage du polygone. |
| EMR_SETROP2 | `20` | Cet enregistrement définit le mode de fonctionnement raster binaire. |
| EMR_SETSTRETCHBLTMODE | `21` | Cet enregistrement définit le mode d'étirement bitmap. |
| EMR_SETTEXTALIGN | `22` | Cet enregistrement définit l'alignement du texte. |
| EMR_SETCOLORADJUSTMENT | `23` | Cet enregistrement définit les valeurs de réglage des couleurs pour le contexte du périphérique de lecture à l'aide des valeurs spécifiées. |
| EMR_SETTEXTCOLOR | `24` | Cet enregistrement définit la couleur actuelle du texte. |
| EMR_SETBKCOLOR | `25` | Cet enregistrement définit la couleur de fond. |
| EMR_OFFSETCLIPRGN | `26` | Cet enregistrement redéfinit la région de découpage du contexte de périphérique de lecture par les décalages spécifiés. |
| EMR_MOVETOEX | `27` | Cet enregistrement définit les coordonnées de la nouvelle position courante, en unités logiques. |
| EMR_SETMETARGN | `28` | Cet enregistrement croise la région de découpage actuelle pour le contexte de périphérique de lecture avec la méta-région actuelle et enregistre la région combinée en tant que nouvelle méta-région. La région de découpage est réinitialisée à une région nulle. |
| EMR_EXCLUDECLIPRECT | `29` | Cet enregistrement définit une nouvelle zone de découpage composée de la zone de découpage existante moins le rectangle spécifié. |
| EMR_INTERSECTCLIPRECT | `30` | Cet enregistrement définit une nouvelle région de découpage à partir de l'intersection de la région de découpage actuelle et du rectangle spécifié. |
| EMR_SCALEVIEWPORTEXTEX | `31` | Cet enregistrement redéfinit la fenêtre d'affichage pour le contexte du périphérique de lecture à l'aide des ratios formés par les multiplicandes et diviseurs spécifiés. |
| EMR_SCALEWINDOWEXTEX | `32` | Cet enregistrement redéfinit la fenêtre du contexte de périphérique de lecture à l'aide des rapports formés par les multiplicandes et diviseurs spécifiés. |
| EMR_SAVEDC | `33` | Cet enregistrement enregistre l'état actuel du contexte du périphérique de lecture en copiant les données décrivant les objets et les modes graphiques sélectionnés, y compris le bitmap, le pinceau, la palette, la police , le stylo, la région, le mode de dessin et le mode de mappage, vers une pile d'images enregistrées. contextes de périphérique. |
| EMR_RESTOREDC | `34` | Cet enregistrement restaure le contexte du périphérique de lecture à l'état enregistré spécifié. Le contexte de périphérique de lecture est restauré en extrayant les informations d'état d'une pile de contextes de périphérique enregistrés créés par des enregistrements EMR_SAVEDC (section 2.3.11) antérieurs. |
| EMR_SETWORLDTRANSFORM | `35` | Cet enregistrement définit une transformation linéaire bidimensionnelle entre l'espace universel et l'espace de page (pour plus d'informations, consultez [MSDN-WRLDPGSPC]) pour le contexte de périphérique de lecture. Cette transformation peut être utilisée pour mettre à l'échelle, faire pivoter, cisailler ou traduire la sortie graphique. |
| EMR_MODIFYWORLDTRANSFORM | `36` | Cet enregistrement redéfinit la transformation du monde pour le contexte du périphérique de lecture à l'aide du mode spécifié. |
| EMR_SELECTOBJECT | `37` | Cet enregistrement ajoute un objet au contexte du périphérique de lecture, en l'identifiant par son index dans la table d'objets EMF (section 3.1.1.1). |
| EMR_CREATEPEN | `38` | Cet enregistrement définit un stylo logique qui a le style, la largeur et la couleur spécifiés. Le stylet peut ensuite être sélectionné dans le contexte de l'appareil de lecture et utilisé pour dessiner des lignes et des courbes. |
| EMR_CREATEBRUSHINDIRECT | `39` | Cet enregistrement définit un pinceau logique pour le remplissage des figures dans les opérations graphiques. |
| EMR_DELETEOBJECT | `40` | Cet enregistrement supprime un objet graphique, effaçant son index dans la table d'objets EMF. Si l'objet supprimé est sélectionné dans le contexte du périphérique de lecture, l'objet par défaut pour cette propriété de contexte DOIT être restauré. |
| EMR_ANGLEARC | `41` | Cet enregistrement définit un segment de ligne d'un arc. Le segment de ligne est tracé de la position actuelle au début de l'arc. L'arc est tracé le long du périmètre d'un cercle avec le rayon et le centre donnés. La longueur de l'arc est définie par les angles de départ et de balayage donnés. |
| EMR_ELLIPSE | `42` | Cet enregistrement définit une ellipse. Le centre de l'ellipse est le centre du rectangle englobant spécifié . L'ellipse est délimitée à l'aide du stylet actuel et est remplie à l'aide du pinceau actuel. |
| EMR_RECTANGLE | `43` | Cet enregistrement définit un rectangle. Le rectangle est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel. |
| EMR_ROUNDRECT | `44` | Cet enregistrement définit un rectangle aux coins arrondis. Le rectangle est délimité à l'aide du stylet actuel et rempli à l'aide du pinceau actuel. |
| EMR_ARC | `45` | Cet enregistrement définit un arc elliptique. |
| EMR_CHORD | `46` | Cet enregistrement définit une corde (une région délimitée par l'intersection d'une ellipse et d'un segment de droite, appelée sécante). L'accord est tracé à l'aide du stylo actuel et rempli à l'aide du pinceau actuel. |
| EMR_PIE | `47` | Cet enregistrement définit un coin en forme de tarte délimité par l'intersection d'une ellipse et de deux radiales. Le secteur est délimité à l'aide du stylo actuel et rempli à l'aide de le pinceau actuel. |
| EMR_SELECTPALETTE | `48` | Cet enregistrement ajoute un objet LogPalette (section 2.2.17) au contexte du périphérique de lecture , en l'identifiant par son index dans la table d'objets EMF. |
| EMR_CREATEPALETTE | `49` | Cet enregistrement définit un objet LogPalette. |
| EMR_SETPALETTEENTRIES | `50` | Cet enregistrement définit les valeurs de couleur RVB (rouge-vert-bleu) dans une plage d'entrées dans un objet LogPalette. |
| EMR_RESIZEPALETTE | `51` | Cet enregistrement augmente ou diminue la taille d'une palette logique. |
| EMR_REALIZEPALETTE | `52` | Cet enregistrement mappe les entrées de la palette logique actuelle vers la palette système. |
| EMR_EXTFLOODFILL | `53` | Cet enregistrement remplit une zone de la surface d'affichage avec le pinceau actuel. |
| EMR_LINETO | `54` | Cet enregistrement définit une ligne à partir de la position actuelle jusqu'à, mais sans inclure, le point spécifié. Il réinitialise la position actuelle au point spécifié. |
| EMR_ARCTO | `55` | Cet enregistrement définit un arc elliptique. Il réinitialise la position actuelle au point final de l'arc. |
| EMR_POLYDRAW | `56` | Cet enregistrement définit un ensemble de segments de droite et de courbes de Bézier. |
| EMR_SETARCDIRECTION | `57` | Cet enregistrement définit la direction de dessin à utiliser pour les opérations d'arc et de rectangle . |
| EMR_SETMITERLIMIT | `58` | Cet enregistrement définit la limite de longueur des jointures en onglet pour le contexte de périphérique de lecture . |
| EMR_BEGINPATH | `59` | Cet enregistrement ouvre une parenthèse de chemin dans le contexte du périphérique de lecture. |
| EMR_ENDPATH | `60` | Cet enregistrement ferme une parenthèse de chemin et sélectionne le chemin défini par la parenthèse dans le contexte du périphérique de lecture. |
| EMR_CLOSEFIGURE | `61` | Cet enregistrement ferme une figure ouverte dans un chemin. |
| EMR_FILLPATH | `62` | Cet enregistrement ferme toutes les figures ouvertes dans le chemin actuel et remplit l'intérieur du chemin en utilisant le pinceau actuel et le mode de remplissage des polygones. |
| EMR_STROKEANDFILLPATH | `63` | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin de en utilisant le stylo actuel et remplit son intérieur en utilisant le pinceau actuel. |
| EMR_STROKEPATH | `64` | Cet enregistrement rend le chemin spécifié en utilisant le stylet actuel. |
| EMR_FLATTENPATH | `65` | Cet enregistrement transforme toute courbe du chemin sélectionné dans le contexte du périphérique de lecture , transformant chaque courbe en une séquence de lignes. |
| EMR_WIDENPATH | `66` | Cet enregistrement redéfinit le chemin actuel comme la zone qui serait peinte si le chemin était tracé à l'aide du stylet actuellement sélectionné dans le contexte du périphérique de lecture. |
| EMR_SELECTCLIPPATH | `67` | Cet enregistrement définit le chemin actuel comme une région de découpage pour le contexte du périphérique de lecture , combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié. |
| EMR_ABORTPATH | `68` | Cet enregistrement annule une parenthèse de chemin ou supprime le chemin d'une parenthèse de chemin fermée. |
| EMR_COMMENT | `70` | Cet enregistrement spécifie des données privées arbitraires. |
| EMR_FILLRGN | `71` | Cet enregistrement remplit la région spécifiée à l'aide du pinceau spécifié. |
| EMR_FRAMERGN | `72` | Cet enregistrement dessine une bordure autour de la région spécifiée à l'aide du pinceau spécifié. |
| EMR_INVERTRGN | `73` | Cet enregistrement inverse les couleurs dans la région spécifiée. |
| EMR_PAINTRGN | `74` | Cet enregistrement peint la région spécifiée en utilisant le pinceau actuellement sélectionné dans le contexte du périphérique de lecture. |
| EMR_EXTSELECTCLIPRGN | `75` | Cet enregistrement combine la région spécifiée avec la région de clip actuelle en utilisant le mode spécifié . |
| EMR_BITBLT | `76` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée. |
| EMR_STRETCHBLT | `77` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire. |
| EMR_MASKBLT | `78` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau et avec l'application d'un bitmap de masque de couleur , selon les opérations de raster de premier plan et d'arrière-plan spécifiées. |
| EMR_PLGBLT | `79` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un parallélogramme de destination , avec l'application d'un bitmap de masque de couleur. |
| EMR_SETDIBITSTODEVICE | `80` | Cet enregistrement spécifie un transfert de bloc de pixels à partir de lignes de balayage spécifiées d'un bitmap source vers un rectangle de destination. |
| EMR_STRETCHDIBITS | `81` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération de trame spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire . |
| EMR_EXTCREATEFONTINDIRECTW | `82` | Cet enregistrement définit une police logique qui possède les caractéristiques spécifiées. La police peut ensuite être sélectionnée comme police actuelle pour le contexte du périphérique de lecture. |
| EMR_EXTTEXTOUTA | `83` | Cet enregistrement dessine une chaîne de texte ASCII en utilisant la police et les couleurs de texte actuelles. Remarque EMR_EXTTEXTOUTA DEVRAIT être émulé avec un enregistrement EMR_EXTTEXTOUTW (section 2.3.5.8). Cela nécessite que la chaîne de texte ASCII dans l'objet EmrText soit convertie en codage Unicode UTF16-LE. |
| EMR_EXTTEXTOUTW | `84` | Cet enregistrement dessine une chaîne de texte Unicode en utilisant la police et les couleurs de texte actuelles. |
| EMR_POLYBEZIER16 | `85` | Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes sont dessinées à l'aide du stylet actuel. |
| EMR_POLYGON16 | `86` | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. Le polygone est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage polygone . Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier. |
| EMR_POLYLINE16 | `87` | Cet enregistrement définit une série de segments de ligne en reliant les points dans le tableau spécifié. |
| EMR_POLYBEZIERTO16 | `88` | Cet enregistrement définit une ou plusieurs courbes de Bézier en fonction de la position actuelle. |
| EMR_POLYLINETO16 | `89` | Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. Une ligne est tracée de la position actuelle au premier point spécifié par le champ Points en utilisant le stylet actuel. Pour chaque ligne supplémentaire, le dessin est effectué à partir du point d'arrivée de la ligne précédente jusqu'au point suivant spécifié par Points. |
| EMR_POLYPOLYLINE16 | `90` | Cet enregistrement définit plusieurs séries de segments de ligne connectés. |
| EMR_POLYPOLYGON16 | `91` | Cet enregistrement définit une série de polygones fermés. Chaque polygone est délimité à l'aide de le stylet actuel et rempli à l'aide du pinceau actuel et du mode de remplissage de polygone. Les polygones spécifiés par cet enregistrement peuvent se chevaucher. |
| EMR_POLYDRAW16 | `92` | Cet enregistrement définit un ensemble de segments de droite et de courbes de Bézier. |
| EMR_CREATEMONOBRUSH | `93` | Cet enregistrement définit un pinceau logique avec le motif bitmap spécifié. Le bitmap peut être un bitmap de section indépendant du périphérique (DIB) ou il peut s'agir d'un bitmap dépendant du périphérique. |
| EMR_CREATEDIBPATTERNBRUSHPT | `94` | Cet enregistrement définit un pinceau logique qui a le motif spécifié par le DIB. |
| EMR_EXTCREATEPEN | `95` | Cet enregistrement définit un stylo cosmétique ou géométrique logique qui a le style, la largeur et les attributs de pinceau spécifiés. |
| EMR_POLYTEXTOUTA | `96` | Cet enregistrement dessine une ou plusieurs chaînes de texte ASCII en utilisant la police et les couleurs de texte actuelles. Remarque EMR_POLYTEXTOUTA DEVRAIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW, un par chaîne |
| EMR_POLYTEXTOUTW | `97` | Cet enregistrement dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles. Remarque EMR_POLYTEXTOUTW DEVRAIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW, un par chaîne |
| EMR_SETICMMODE | `98` | Cet enregistrement spécifie le mode de gestion des couleurs d'image (ICM) pour les opérations graphiques. |
| EMR_CREATECOLORSPACE | `99` | Cet enregistrement crée un objet d'espace colorimétrique logique à partir d'un profil de couleur avec un nom composé de caractères ASCII |
| EMR_SETCOLORSPACE | `100` | Cet enregistrement définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques. |
| EMR_DELETECOLORSPACE | `101` | Cet enregistrement supprime un objet d'espace colorimétrique logique. Remarque Un enregistrement EMR_DELETEOBJECT DEVRAIT être utilisé à la place de EMR_DELETECOLORSPACE pour supprimer un objet d'espace colorimétrique logique |
| EMR_GLSRECORD | `102` | Cet enregistrement spécifie une fonction OpenGL. |
| EMR_GLSBOUNDEDRECORD | `103` | Cet enregistrement spécifie une fonction OpenGL avec un rectangle englobant pour la sortie. |
| EMR_PIXELFORMAT | `104` | Cet enregistrement spécifie le format de pixel à utiliser pour les opérations graphiques |
| EMR_DRAWESCAPE | `105` | Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que les informations entraînent la réalisation du dessin. |
| EMR_EXTESCAPE | `106` | Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que les informations n'entraîneront pas la réalisation d'un dessin. |
| EMR_SMALLTEXTOUT | `108` | Cet enregistrement génère une chaîne. |
| EMR_FORCEUFIMAPPING | `109` | Cet enregistrement force le mappeur de polices à faire correspondre les polices en fonction de leur préférence UniversalFontId dans à leurs informations LogFont. |
| EMR_NAMEDESCAPE | `110` | Cet enregistrement transmet des informations arbitraires au pilote nommé donné. |
| EMR_COLORCORRECTPALETTE | `111` | Cet enregistrement spécifie comment corriger les entrées d'un objet de palette logique à l'aide de Windows Color System (WCS) 1.0 values |
| EMR_SETICMPROFILEA | `112` | Cet enregistrement spécifie un profil de couleur dans un fichier avec un nom composé de caractères ASCII, pour la sortie graphique. |
| EMR_SETICMPROFILEW | `113` | Cet enregistrement spécifie un profil de couleur dans un fichier dont le nom est composé de caractères Unicode, pour la sortie graphique |
| EMR_ALPHABLEND | `114` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination, comprenant des données de transparence alpha, selon une opération de fusion spécifiée. |
| EMR_SETLAYOUT | `115` | Cet enregistrement spécifie l'ordre dans lequel le texte et les graphiques sont dessinés |
| EMR_TRANSPARENTBLT | `116` | Cet enregistrement spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination, traitant une couleur spécifiée comme transparente, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire |
| EMR_GRADIENTFILL | `118` | Cet enregistrement spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur |
| EMR_SETLINKEDUFIS | `119` | Cet enregistrement définit les UniversalFontIds des polices liées à utiliser lors de la recherche de caractères. |
| EMR_SETTEXTJUSTIFICATION | `120` | Cet enregistrement spécifie la quantité d'espace supplémentaire à ajouter aux caractères de rupture à des fins de justification . |
| EMR_COLORMATCHTOTARGETW | `121` | Cet enregistrement spécifie s'il faut effectuer la correspondance des couleurs avec un profil de couleur spécifié dans un fichier dont le nom est composé de caractères Unicode. |
| EMR_CREATECOLORSPACEW | `122` | Cet enregistrement crée un objet d'espace colorimétrique logique à partir d'un profil de couleur avec un nom composé de caractères Unicode |

### Voir également

* espace de noms [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* Assemblée [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
