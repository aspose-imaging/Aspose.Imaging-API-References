---
title: "Énumération EmfRecordType"
type: docs
weight: 290
url: /fr/python-net/aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---

L'énumération RecordType définit des valeurs qui identifient de manière unique les enregistrements EMF.<br/>            Ces valeurs sont fournies dans le champ Type de chaque enregistrement.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfRecordType

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| EMR_ABORTPATH | Cet enregistrement annule une parenthèse de chemin ou supprime le chemin d'une parenthèse de chemin fermée. |
| EMR_ALPHABLEND | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination,<br/>             incluant les données de transparence alpha, selon une opération de fusion spécifiée. |
| EMR_ANGLEARC | Cet enregistrement définit un segment de ligne d'un arc. Le segment de ligne est tracé depuis la <br/>            position actuelle jusqu'au début de l'arc. L'arc est dessiné le long du périmètre <br/>            d'un cercle de rayon et de centre donnés. La longueur de l'arc est définie par <br/>            les angles de départ et de balayage fournis. |
| EMR_ARC | Cet enregistrement définit un arc elliptique. |
| EMR_ARCTO | Cet enregistrement définit un arc elliptique. Il réinitialise la position actuelle au <br/>            point final de l'arc. |
| EMR_BEGINPATH | Cet enregistrement ouvre un délimiteur de chemin dans le contexte du dispositif de lecture. |
| EMR_BITBLT | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination<br/>, éventuellement en combinaison avec un motif de brosse, selon une opération raster spécifiée. |
| EMR_CHORD | Cet enregistrement définit une corde (une région délimitée par l'intersection d'une ellipse <br/> et d'un segment de ligne, appelée sécante). La corde est contournée en utilisant le stylo actuel <br/> et remplie en utilisant la brosse actuelle. |
| EMR_CLOSEFIGURE | Cet enregistrement ferme une figure ouverte dans un chemin. |
| EMR_COLORCORRECTPALETTE | Cet enregistrement spécifie comment corriger les entrées d'un objet palette logique en utilisant les valeurs du Windows <br/> Color System (WCS) 1.0. |
| EMR_COLORMATCHTOTARGETW | Cet enregistrement indique s'il faut effectuer une correspondance des couleurs avec un profil couleur qui est spécifié dans un fichier dont le nom est composé de caractères Unicode. |
| EMR_COMMENT | Cet enregistrement spécifie des données privées arbitraires. |
| EMR_CREATEBRUSHINDIRECT | Cet enregistrement définit une brosse logique pour le remplissage de formes dans les opérations graphiques. |
| EMR_CREATECOLORSPACE | Cet enregistrement crée un objet d'espace couleur logique à partir d'un profil couleur dont le nom est composé de caractères ASCII |
| EMR_CREATECOLORSPACEW | Cet enregistrement crée un objet d'espace couleur logique à partir d'un profil couleur dont le nom est composé de caractères Unicode |
| EMR_CREATEDIBPATTERNBRUSHPT | Cet enregistrement définit une brosse logique dont le motif est spécifié par le DIB. |
| EMR_CREATEMONOBRUSH | Cet enregistrement définit une brosse logique avec le motif bitmap spécifié. Le bitmap peut<br/>             être un bitmap indépendant du dispositif (DIB) ou un bitmap dépendant du dispositif. |
| EMR_CREATEPALETTE | Cet enregistrement définit un objet LogPalette. |
| EMR_CREATEPEN | Cet enregistrement définit un stylo logique qui possède le style, la largeur et la couleur spécifiés. <br/>            Le stylo peut ensuite être sélectionné dans le contexte de périphérique de lecture et utilisé pour tracer des lignes et des courbes. |
| EMR_DELETECOLORSPACE | Cet enregistrement supprime un objet d'espace couleur logique. Notez qu'un enregistrement EMR_DELETEOBJECT DOIT être <br/>            utilisé à la place d'EMR_DELETECOLORSPACE pour supprimer un objet d'espace couleur logique |
| EMR_DELETEOBJECT | Cet enregistrement supprime un objet graphique, en effaçant son index dans la table d'objets EMF. <br/>            Si l'objet supprimé est sélectionné dans le contexte de périphérique de lecture, l'objet par défaut <br/>            pour cette propriété de contexte DOIT être restauré. |
| EMR_DRAWESCAPE | Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que ces informations <br/>            entraînent la réalisation d'un dessin. |
| EMR_ELLIPSE | Cet enregistrement définit une ellipse. Le centre de l'ellipse est le centre du <br/>            rectangle englobant spécifié. L'ellipse est contournée en utilisant le stylo actuel et <br/>            remplie en utilisant la brosse actuelle. |
| EMR_ENDPATH | Cet enregistrement ferme une accolade de chemin et sélectionne le chemin défini par l'accolade <br/>            dans le contexte de périphérique de lecture. |
| EMR_EOF | Cet enregistrement indique la fin du métafichier. |
| EMR_EXCLUDECLIPRECT | Cet enregistrement définit une nouvelle région de découpage qui consiste en la région de découpage existante <br/>            moins le rectangle spécifié. |
| EMR_EXTCREATEFONTINDIRECTW | Cet enregistrement définit une police logique qui possède les caractéristiques spécifiées. La police <br/>            peut ensuite être sélectionnée comme police actuelle pour le contexte de périphérique de lecture. |
| EMR_EXTCREATEPEN | Cet enregistrement définit un stylo cosmétique ou géométrique logique qui possède le style, la <br/>            largeur et les attributs de brosse spécifiés. |
| EMR_EXTESCAPE | Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que ces informations <br/>            ne entraînent pas de dessin. |
| EMR_EXTFLOODFILL | Cet enregistrement remplit une zone de la surface d'affichage avec la brosse actuelle. |
| EMR_EXTSELECTCLIPRGN | Cet enregistrement combine la région spécifiée avec la région de découpage actuelle en utilisant le <br/>            mode spécifié. |
| EMR_EXTTEXTOUTA | Cet enregistrement dessine une chaîne de texte ASCII en utilisant la police actuelle et les couleurs du texte. Remarque <br/>            EMR_EXTTEXTOUTA SHOULD be emulated with an EMR_EXTTEXTOUTW record (section 2.3.5.8).  <br/>            This requires the ASCII text string in the EmrText object to be converted to Unicode UTF16-LE encoding. |
| EMR_EXTTEXTOUTW | Cet enregistrement dessine une chaîne de texte Unicode en utilisant la police actuelle et les couleurs du texte. |
| EMR_FILLPATH | Cet enregistrement ferme toutes les figures ouvertes dans le chemin actuel et remplit l'intérieur du chemin <br/>            en utilisant la brosse actuelle et le mode de remplissage de polygone. |
| EMR_FILLRGN | Cet enregistrement remplit la région spécifiée en utilisant la brosse spécifiée. |
| EMR_FLATTENPATH | Cet enregistrement transforme toute courbe du chemin qui est sélectionnée en le contexte du dispositif de lecture <br/>            contexte, transformant chaque courbe en une séquence de lignes. |
| EMR_FORCEUFIMAPPING | Cet enregistrement force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId <br/>            plutôt que de leurs informations LogFont. |
| EMR_FRAMERGN | Cet enregistrement dessine une bordure autour de la région spécifiée en utilisant le pinceau spécifié. |
| EMR_GLSBOUNDEDRECORD | Cet enregistrement spécifie une fonction OpenGL avec un rectangle de délimitation pour la sortie. |
| EMR_GLSRECORD | Cet enregistrement spécifie une fonction OpenGL. |
| EMR_GRADIENTFILL | Cet enregistrement spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur |
| EMR_HEADER | Cet enregistrement définit le début du métafichier et spécifie ses caractéristiques ; son contenu, <br/>            y compris les dimensions de l'image incorporée ; le nombre d'enregistrements dans le métafichier ; et la <br/>            résolution du dispositif sur lequel l'image incorporée a été créée. Ces valeurs permettent au métafichier d'être indépendant du dispositif. |
| EMR_INTERSECTCLIPRECT | Cet enregistrement définit une nouvelle région de découpage à partir de l'intersection de la région de découpage actuelle <br/>            et du rectangle spécifié. |
| EMR_INVERTRGN | Cet enregistrement inverse les couleurs dans la région spécifiée. |
| EMR_LINETO | Cet enregistrement définit une ligne depuis la position actuelle jusqu'à, mais sans inclure,<br/>             le point spécifié. Il réinitialise la position actuelle au point spécifié. |
| EMR_MASKBLT | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle<br/>             de destination, éventuellement en combinaison avec un motif de pinceau et avec l'application d'un <br/>            bitmap de masque de couleur, selon les opérations raster de premier plan et d'arrière-plan spécifiées. |
| EMR_MODIFYWORLDTRANSFORM | Cet enregistrement redéfinit la transformation du monde pour le contexte du dispositif de lecture en utilisant le mode spécifié. |
| EMR_MOVETOEX | Cet enregistrement définit les coordonnées de la nouvelle position actuelle, en unités logiques. |
| EMR_NAMEDESCAPE | Cet enregistrement transmet des informations arbitraires au pilote nommé fourni. |
| EMR_OFFSETCLIPRGN | Cet enregistrement redéfinit la région de découpage du contexte de périphérique de lecture en fonction des décalages spécifiés. |
| EMR_PAINTRGN | Cet enregistrement peint la région spécifiée en utilisant le pinceau actuellement sélectionné dans <br/>            le contexte de périphérique de lecture. |
| EMR_PIE | Cet enregistrement définit un secteur en forme de tarte limité par l'intersection d'une ellipse <br/>            et de deux rayons. Le secteur est contourné en utilisant le stylo actuel et rempli en utilisant <br/>            le pinceau actuel. |
| EMR_PIXELFORMAT | Cet enregistrement spécifie le format de pixel à utiliser pour les opérations graphiques |
| EMR_PLGBLT | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un parallélogramme de destination <br/>            avec l'application d'un bitmap de masque de couleur. |
| EMR_POLYBEZIER | Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes de Bézier cubiques sont définies en utilisant<br/>            des points d'extrémité et des points de contrôle spécifiés, et sont tracées avec le stylo actuel. |
| EMR_POLYBEZIER16 | Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes sont dessinées en utilisant le stylo actuel. |
| EMR_POLYBEZIERTO | Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle. |
| EMR_POLYBEZIERTO16 | Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle. |
| EMR_POLYDRAW | Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier. |
| EMR_POLYDRAW16 | Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier. |
| EMR_POLYGON | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites <br/>            . Le polygone est contourné en utilisant le stylo actuel et rempli en utilisant la brosse actuelle <br/>            et le mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier. |
| EMR_POLYGON16 | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. <br/>            Le polygone est contourné en utilisant le stylo actuel et rempli en utilisant la brosse actuelle et le mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier. |
| EMR_POLYLINE | Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié <br/>            . |
| EMR_POLYLINE16 | Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié. |
| EMR_POLYLINETO | Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. <br/>            Une ligne est tracée depuis la position actuelle jusqu'au premier point spécifié par le champ points <br/>            en utilisant le stylo actuel. Pour chaque ligne supplémentaire, le dessin est effectué depuis le point final <br/>            de la ligne précédente jusqu'au point suivant spécifié par les points. |
| EMR_POLYLINETO16 | Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle.<br/>             Une ligne est tracée depuis la position actuelle jusqu'au premier point spécifié par le champ Points <br/>            en utilisant le stylo actuel. Pour chaque ligne supplémentaire, le dessin est effectué depuis le <br/>            point final de la ligne précédente jusqu'au point suivant spécifié par Points. |
| EMR_POLYPOLYGON | Cet enregistrement définit une série de polygones fermés. Chaque polygone est contourné en utilisant le <br/>            stylo actuel et rempli en utilisant la brosse actuelle et le mode de remplissage du polygone. Les polygones définis par cet enregistrement peuvent se chevaucher. |
| EMR_POLYPOLYGON16 | Cet enregistrement définit une série de polygones fermés. Chaque polygone est contourné en utilisant <br/>            le stylo actuel et rempli en utilisant la brosse actuelle et le mode de remplissage du polygone. Les polygones<br/>             spécifiés par cet enregistrement peuvent se chevaucher. |
| EMR_POLYPOLYLINE | Cet enregistrement définit plusieurs séries de segments de ligne connectés. Les segments de ligne sont <br/>            tracés en utilisant le stylo actuel. Les figures formées par les segments ne sont pas remplies. T<br/>            la position actuelle n'est ni utilisée ni mise à jour par cet enregistrement. |
| EMR_POLYPOLYLINE16 | Cet enregistrement définit plusieurs séries de segments de ligne connectés. |
| EMR_POLYTEXTOUTA | Cet enregistrement dessine une ou plusieurs chaînes de texte ASCII en utilisant la police actuelle et les couleurs du texte.<br/>             Note EMR_POLYTEXTOUTA DOIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW, un par chaîne |
| EMR_POLYTEXTOUTW | Cet enregistrement dessine une ou plusieurs chaînes de texte Unicode en utilisant la police actuelle et les couleurs du texte.<br/>            Note EMR_POLYTEXTOUTW DOIT être émulé avec une série d'enregistrements EMR_EXTTEXTOUTW, un par chaîne |
| EMR_REALIZEPALETTE | Cet enregistrement mappe les entrées de la palette logique actuelle vers la palette du système. |
| EMR_RECTANGLE | Cet enregistrement définit un rectangle. Le rectangle est contourné en utilisant le stylo actuel <br/>            et rempli en utilisant la brosse actuelle. |
| EMR_RESIZEPALETTE | Cet enregistrement augmente ou diminue la taille d'une palette logique. |
| EMR_RESTOREDC | Cet enregistrement restaure le contexte du dispositif de lecture à l'état enregistré spécifié. <br/>            Le contexte du dispositif de lecture est restauré en dépilant les informations d'état d'une pile de <br/>            contextes de dispositif enregistrés créés par les enregistrements EMR_SAVEDC précédents (section 2.3.11). |
| EMR_ROUNDRECT | Cet enregistrement définit un rectangle avec des coins arrondis. Le rectangle est contourné <br/>            en utilisant le stylo actuel et rempli en utilisant la brosse actuelle. |
| EMR_SAVEDC | Cet enregistrement enregistre l'état actuel du contexte du dispositif de lecture en copiant les données <br/>            décrivant les objets sélectionnés et les modes graphiques—y compris le bitmap, la brosse, la palette, <br/>            la police, le stylo, la région, le mode de dessin et le mode de cartographie—vers une pile de contextes de dispositif enregistrés. |
| EMR_SCALEVIEWPORTEXTEX | Cet enregistrement redéfinit la fenêtre d'affichage pour le contexte du dispositif de lecture en utilisant les rapports <br/>            formés par les multiplicateurs et diviseurs spécifiés. |
| EMR_SCALEWINDOWEXTEX | Cet enregistrement redéfinit la fenêtre pour le contexte du dispositif de lecture en utilisant les rapports formés <br/>            par les multiplicateurs et diviseurs spécifiés. |
| EMR_SELECTCLIPPATH | Cet enregistrement définit le chemin actuel comme une région de découpage pour le contexte du dispositif de lecture <br/>            en combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié. |
| EMR_SELECTOBJECT | Cet enregistrement ajoute un objet au contexte du dispositif de lecture, en l'identifiant par son <br/>            index dans la table d'objets EMF (section 3.1.1.1). |
| EMR_SELECTPALETTE | Cet enregistrement ajoute un objet LogPalette (section 2.2.17) au contexte du dispositif de lecture <br/>            en l'identifiant par son index dans la table d'objets EMF. |
| EMR_SETARCDIRECTION | Cet enregistrement définit la direction de dessin à utiliser pour les arcs et les rectangles<br/>             opérations. |
| EMR_SETBKCOLOR | Cet enregistrement définit la couleur d'arrière-plan. |
| EMR_SETBKMODE | Cet enregistrement définit le mode de mélange d'arrière-plan du contexte de périphérique de lecture. Le mode de mélange<br/>             d'arrière-plan est utilisé avec du texte, des brosses hachurées et des styles de stylo qui ne sont pas des lignes pleines. |
| EMR_SETBRUSHORGEX | Cet enregistrement définit l'origine de la brosse actuelle. |
| EMR_SETCOLORADJUSTMENT | Cet enregistrement définit les valeurs d'ajustement des couleurs pour le contexte de périphérique de lecture en utilisant les valeurs spécifiées. |
| EMR_SETCOLORSPACE | Cet enregistrement définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques. |
| EMR_SETDIBITSTODEVICE | Cet enregistrement spécifie un transfert de bloc de pixels depuis les lignes de balayage spécifiées d'une image source<br/>             vers un rectangle de destination. |
| EMR_SETICMMODE | Cet enregistrement spécifie le mode de la gestion des couleurs d'image (ICM) pour les opérations graphiques. |
| EMR_SETICMPROFILEA | Cet enregistrement spécifie un profil de couleur dans un fichier dont le nom est composé de caractères ASCII,<br/>             pour la sortie graphique. |
| EMR_SETICMPROFILEW | Cet enregistrement spécifie un profil de couleur dans un fichier dont le nom est composé de caractères Unicode,<br/>             pour la sortie graphique |
| EMR_SETLAYOUT | Cet enregistrement spécifie l'ordre dans lequel le texte et les graphiques sont dessinés |
| EMR_SETLINKEDUFIS | Cet enregistrement définit les UniversalFontIds des polices liées à utiliser lors de la recherche de caractères. |
| EMR_SETMAPMODE | Cet enregistrement définit le mode de cartographie du contexte de périphérique de lecture. Le mode de cartographie<br/>             définit l'unité de mesure utilisée pour transformer les unités d'espace de page en unités d'espace de périphérique,<br/>             et définit également l'orientation des axes x et y du périphérique. |
| EMR_SETMAPPERFLAGS | Cet enregistrement spécifie les paramètres du processus d'appariement des polices logiques aux polices physiques <br/>            qui est effectué par le mappeur de polices. |
| EMR_SETMETARGN | Cet enregistrement intersecte la région de découpage actuelle du contexte de périphérique de lecture avec la <br/>            région méta actuelle et enregistre la région combinée comme nouvelle région méta. La région de découpage est réinitialisée à une région nulle. |
| EMR_SETMITERLIMIT | Cet enregistrement définit la limite de la longueur des jointures en onglet pour la lecture <br/>            le contexte du périphérique. |
| EMR_SETPALETTEENTRIES | Cet enregistrement définit les valeurs de couleur RVB (rouge-vert-bleu) dans une plage d'entrées <br/>            d'un objet LogPalette. |
| EMR_SETPIXELV | Cet enregistrement définit la couleur du pixel aux coordonnées logiques spécifiées. |
| EMR_SETPOLYFILLMODE | Cet enregistrement définit le mode de remplissage du polygone. |
| EMR_SETROP2 | Cet enregistrement définit le mode d'opération raster binaire. |
| EMR_SETSTRETCHBLTMODE | Cet enregistrement définit le mode d'étirement du bitmap. |
| EMR_SETTEXTALIGN | Cet enregistrement définit l'alignement du texte. |
| EMR_SETTEXTCOLOR | Cet enregistrement définit la couleur actuelle du texte. |
| EMR_SETTEXTJUSTIFICATION | Cet enregistrement spécifie la quantité d'espace supplémentaire à ajouter aux caractères de rupture pour la justification<br/>             à des fins de justification. |
| EMR_SETVIEWPORTEXTEX | Cet enregistrement définit l'étendue du viewport. |
| EMR_SETVIEWPORTORGEX | Cet enregistrement définit l'origine du viewport. |
| EMR_SETWINDOWEXTEX | Cet enregistrement définit l'étendue de la fenêtre. |
| EMR_SETWINDOWORGEX | Cet enregistrement définit l'origine de la fenêtre. |
| EMR_SETWORLDTRANSFORM | Cet enregistrement définit une transformation linéaire bidimensionnelle entre l'espace monde et <br/>            l'espace page (pour plus d'informations, voir [MSDN-WRLDPGSPC]) pour le contexte de dispositif de lecture. <br/>            Cette transformation peut être utilisée pour mettre à l'échelle, faire pivoter, ciseler ou translater la sortie graphique. |
| EMR_SMALLTEXTOUT | Cet enregistrement produit une chaîne. |
| EMR_STRETCHBLT | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination<br/>             , éventuellement en combinaison avec un motif de brosse, selon une opération raster spécifiée<br/>             , étirant ou compressant la sortie pour s'adapter aux dimensions de la destination, si nécessaire. |
| EMR_STRETCHDIBITS | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination <br/>            , éventuellement en combinaison avec un motif de brosse, selon une opération raster spécifiée, <br/>            étirant ou compressant la sortie pour s'adapter aux dimensions de la destination, si nécessaire. |
| EMR_STROKEANDFILLPATH | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en <br/>            utilisant le stylo actuel, et remplit son intérieur en utilisant la brosse actuelle. |
| EMR_STROKEPATH | Cet enregistrement rend le chemin spécifié en utilisant le stylo actuel. |
| EMR_TRANSPARENTBLT | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination,<br/>             traitant une couleur spécifiée comme transparente, étirant ou compressant la sortie pour s'adapter aux dimensions de la destination, si nécessaire. |
| EMR_WIDENPATH | Cet enregistrement redéfinit le chemin actuel comme la zone qui serait peinte si le chemin <br/>            était tracé en utilisant le stylo actuellement sélectionné dans le contexte de dispositif de lecture. |
