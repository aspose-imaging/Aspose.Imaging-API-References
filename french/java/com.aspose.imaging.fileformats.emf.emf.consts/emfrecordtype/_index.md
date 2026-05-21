---
title: "EmfRecordType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération RecordType définit des valeurs qui identifient de manière unique les enregistrements EMF."
type: docs
weight: 38
url: /fr/java/com.aspose.imaging.fileformats.emf.emf.consts/emfrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfRecordType extends System.Enum
```

L'énumération RecordType définit des valeurs qui identifient de manière unique les enregistrements EMF. Ces valeurs sont fournies dans le champ Type de chaque enregistrement.
## Champs

| Champ | Description |
| --- | --- |
| [EMR_HEADER](#EMR-HEADER) | Cet enregistrement définit le début du métafichier et spécifie ses caractéristiques ; son contenu, y compris les dimensions de l'image intégrée ; le nombre d'enregistrements dans le métafichier ; et la résolution de l'appareil sur lequel l'image intégrée a été créée. |
| [EMR_POLYBEZIER](#EMR-POLYBEZIER) | Cet enregistrement définit une ou plusieurs courbes de Bézier. |
| [EMR_POLYGON](#EMR-POLYGON) | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. |
| [EMR_POLYLINE](#EMR-POLYLINE) | Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié. |
| [EMR_POLYBEZIERTO](#EMR-POLYBEZIERTO) | Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle. |
| [EMR_POLYLINETO](#EMR-POLYLINETO) | Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. |
| [EMR_POLYPOLYLINE](#EMR-POLYPOLYLINE) | Cet enregistrement définit plusieurs séries de segments de ligne connectés. |
| [EMR_POLYPOLYGON](#EMR-POLYPOLYGON) | Cet enregistrement définit une série de polygones fermés. |
| [EMR_SETWINDOWEXTEX](#EMR-SETWINDOWEXTEX) | Cet enregistrement définit l'étendue de la fenêtre. |
| [EMR_SETWINDOWORGEX](#EMR-SETWINDOWORGEX) | Cet enregistrement définit l'origine de la fenêtre. |
| [EMR_SETVIEWPORTEXTEX](#EMR-SETVIEWPORTEXTEX) | Cet enregistrement définit l'étendue du viewport. |
| [EMR_SETVIEWPORTORGEX](#EMR-SETVIEWPORTORGEX) | Cet enregistrement définit l'origine du viewport. |
| [EMR_SETBRUSHORGEX](#EMR-SETBRUSHORGEX) | Cet enregistrement définit l'origine du pinceau actuel. |
| [EMR_EOF](#EMR-EOF) | Cet enregistrement indique la fin du métafichier. |
| [EMR_SETPIXELV](#EMR-SETPIXELV) | Cet enregistrement définit la couleur du pixel aux coordonnées logiques spécifiées. |
| [EMR_SETMAPPERFLAGS](#EMR-SETMAPPERFLAGS) | Cet enregistrement spécifie les paramètres du processus d'appariement des polices logiques aux polices physiques, qui est effectué par le mappeur de polices. |
| [EMR_SETMAPMODE](#EMR-SETMAPMODE) | Cet enregistrement définit le mode de mappage du contexte de périphérique de lecture. |
| [EMR_SETBKMODE](#EMR-SETBKMODE) | Cet enregistrement définit le mode de mélange d'arrière-plan du contexte de périphérique de lecture. |
| [EMR_SETPOLYFILLMODE](#EMR-SETPOLYFILLMODE) | Cet enregistrement définit le mode de remplissage du polygone. |
| [EMR_SETROP2](#EMR-SETROP2) | Cet enregistrement définit le mode d'opération raster binaire. |
| [EMR_SETSTRETCHBLTMODE](#EMR-SETSTRETCHBLTMODE) | Cet enregistrement définit le mode d'étirement du bitmap. |
| [EMR_SETTEXTALIGN](#EMR-SETTEXTALIGN) | Cet enregistrement définit l'alignement du texte. |
| [EMR_SETCOLORADJUSTMENT](#EMR-SETCOLORADJUSTMENT) | Cet enregistrement définit les valeurs d'ajustement des couleurs pour le contexte du dispositif de lecture en utilisant les valeurs spécifiées. |
| [EMR_SETTEXTCOLOR](#EMR-SETTEXTCOLOR) | Cet enregistrement définit la couleur actuelle du texte. |
| [EMR_SETBKCOLOR](#EMR-SETBKCOLOR) | Cet enregistrement définit la couleur d'arrière-plan. |
| [EMR_OFFSETCLIPRGN](#EMR-OFFSETCLIPRGN) | Cet enregistrement redéfinit la région de découpage du contexte du dispositif de lecture selon les décalages spécifiés. |
| [EMR_MOVETOEX](#EMR-MOVETOEX) | Cet enregistrement définit les coordonnées de la nouvelle position actuelle, en unités logiques. |
| [EMR_SETMETARGN](#EMR-SETMETARGN) | Cet enregistrement intersecte la région de découpage actuelle du contexte du dispositif de lecture avec la méta-région actuelle et enregistre la région combinée comme la nouvelle méta-région. |
| [EMR_EXCLUDECLIPRECT](#EMR-EXCLUDECLIPRECT) | Cet enregistrement définit une nouvelle région de découpage qui consiste en la région de découpage existante moins le rectangle spécifié. |
| [EMR_INTERSECTCLIPRECT](#EMR-INTERSECTCLIPRECT) | Cet enregistrement définit une nouvelle région de découpage à partir de l'intersection de la région de découpage actuelle et du rectangle spécifié. |
| [EMR_SCALEVIEWPORTEXTEX](#EMR-SCALEVIEWPORTEXTEX) | Cet enregistrement redéfinit le viewport du contexte du dispositif de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés. |
| [EMR_SCALEWINDOWEXTEX](#EMR-SCALEWINDOWEXTEX) | Cet enregistrement redéfinit la fenêtre du contexte du dispositif de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés. |
| [EMR_SAVEDC](#EMR-SAVEDC) | Cet enregistrement enregistre l'état actuel du contexte du dispositif de lecture en copiant les données décrivant les objets sélectionnés et les modes graphiques\u2014y compris le bitmap, le pinceau, la palette, la police, le crayon, la région, le mode de dessin et le mode de cartographie\u2014dans une pile de contextes de dispositif enregistrés. |
| [EMR_RESTOREDC](#EMR-RESTOREDC) | Cet enregistrement restaure le contexte du dispositif de lecture à l'état enregistré spécifié. |
| [EMR_SETWORLDTRANSFORM](#EMR-SETWORLDTRANSFORM) | Cet enregistrement définit une transformation linéaire bidimensionnelle entre l'espace monde et l'espace page (pour plus d'informations, voir [MSDN-WRLDPGSPC]) pour le contexte du dispositif de lecture. |
| [EMR_MODIFYWORLDTRANSFORM](#EMR-MODIFYWORLDTRANSFORM) | Cet enregistrement redéfinit la transformation du monde pour le contexte du dispositif de lecture en utilisant le mode spécifié. |
| [EMR_SELECTOBJECT](#EMR-SELECTOBJECT) | Cet enregistrement ajoute un objet au contexte du dispositif de lecture, en l'identifiant par son index dans la table d'objets EMF (section 3.1.1.1). |
| [EMR_CREATEPEN](#EMR-CREATEPEN) | Cet enregistrement définit un crayon logique qui possède le style, la largeur et la couleur spécifiés. |
| [EMR_CREATEBRUSHINDIRECT](#EMR-CREATEBRUSHINDIRECT) | Cet enregistrement définit un pinceau logique pour le remplissage de formes dans les opérations graphiques. |
| [EMR_DELETEOBJECT](#EMR-DELETEOBJECT) | Cet enregistrement supprime un objet graphique, en effaçant son index dans la table d'objets EMF. |
| [EMR_ANGLEARC](#EMR-ANGLEARC) | Cet enregistrement définit un segment de ligne d'un arc. |
| [EMR_ELLIPSE](#EMR-ELLIPSE) | Cet enregistrement définit une ellipse. |
| [EMR_RECTANGLE](#EMR-RECTANGLE) | Cet enregistrement définit un rectangle. |
| [EMR_ROUNDRECT](#EMR-ROUNDRECT) | Cet enregistrement définit un rectangle avec des coins arrondis. |
| [EMR_ARC](#EMR-ARC) | Cet enregistrement définit un arc elliptique. |
| [EMR_CHORD](#EMR-CHORD) | Cet enregistrement définit une corde (une région délimitée par l'intersection d'une ellipse et d'un segment de ligne, appelée une sécante). |
| [EMR_PIE](#EMR-PIE) | Cet enregistrement définit un coin en forme de part de tarte délimité par l'intersection d'une ellipse et de deux rayons. |
| [EMR_SELECTPALETTE](#EMR-SELECTPALETTE) | Cet enregistrement ajoute un objet LogPalette (section 2.2.17) au contexte du dispositif de lecture, en l'identifiant par son indice dans la table des objets EMF. |
| [EMR_CREATEPALETTE](#EMR-CREATEPALETTE) | Cet enregistrement définit un objet LogPalette. |
| [EMR_SETPALETTEENTRIES](#EMR-SETPALETTEENTRIES) | Cet enregistrement définit les valeurs de couleur RVB (rouge-vert-bleu) dans une plage d'entrées d'un objet LogPalette. |
| [EMR_RESIZEPALETTE](#EMR-RESIZEPALETTE) | Cet enregistrement augmente ou diminue la taille d'une palette logique. |
| [EMR_REALIZEPALETTE](#EMR-REALIZEPALETTE) | Cet enregistrement mappe les entrées de la palette logique actuelle vers la palette système. |
| [EMR_EXTFLOODFILL](#EMR-EXTFLOODFILL) | Cet enregistrement remplit une zone de la surface d'affichage avec le pinceau actuel. |
| [EMR_LINETO](#EMR-LINETO) | Cet enregistrement définit une ligne depuis la position actuelle jusqu'au point spécifié, sans l'inclure. |
| [EMR_ARCTO](#EMR-ARCTO) | Cet enregistrement définit un arc elliptique. |
| [EMR_POLYDRAW](#EMR-POLYDRAW) | Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier. |
| [EMR_SETARCDIRECTION](#EMR-SETARCDIRECTION) | Cet enregistrement définit la direction de dessin à utiliser pour les opérations d'arc et de rectangle. |
| [EMR_SETMITERLIMIT](#EMR-SETMITERLIMIT) | Cet enregistrement définit la limite de la longueur des jointures en onglet pour le contexte du dispositif de lecture. |
| [EMR_BEGINPATH](#EMR-BEGINPATH) | Cet enregistrement ouvre une parenthèse de chemin dans le contexte du dispositif de lecture. |
| [EMR_ENDPATH](#EMR-ENDPATH) | Cet enregistrement ferme une parenthèse de chemin et sélectionne le chemin défini par la parenthèse dans le contexte du dispositif de lecture. |
| [EMR_CLOSEFIGURE](#EMR-CLOSEFIGURE) | Cet enregistrement ferme une figure ouverte dans un chemin. |
| [EMR_FILLPATH](#EMR-FILLPATH) | Cet enregistrement ferme toutes les figures ouvertes dans le chemin actuel et remplit l'intérieur du chemin en utilisant le pinceau actuel et le mode de remplissage de polygone. |
| [EMR_STROKEANDFILLPATH](#EMR-STROKEANDFILLPATH) | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel, et remplit son intérieur en utilisant le pinceau actuel. |
| [EMR_STROKEPATH](#EMR-STROKEPATH) | Cet enregistrement rend le chemin spécifié en utilisant le stylo actuel. |
| [EMR_FLATTENPATH](#EMR-FLATTENPATH) | Cet enregistrement transforme toute courbe du chemin sélectionnée dans le contexte du dispositif de lecture, en convertissant chaque courbe en une séquence de lignes. |
| [EMR_WIDENPATH](#EMR-WIDENPATH) | Cet enregistrement redéfinit le chemin actuel comme la zone qui serait peinte si le chemin était tracé en utilisant le stylo actuellement sélectionné dans le contexte du dispositif de lecture. |
| [EMR_SELECTCLIPPATH](#EMR-SELECTCLIPPATH) | Cet enregistrement définit le chemin actuel comme une région de découpage pour le contexte du dispositif de lecture, en combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié. |
| [EMR_ABORTPATH](#EMR-ABORTPATH) | Cet enregistrement annule un crochet de chemin ou supprime le chemin d'un crochet de chemin fermé. |
| [EMR_COMMENT](#EMR-COMMENT) | Cet enregistrement spécifie des données privées arbitraires. |
| [EMR_FILLRGN](#EMR-FILLRGN) | Cet enregistrement remplit la région spécifiée en utilisant le pinceau spécifié. |
| [EMR_FRAMERGN](#EMR-FRAMERGN) | Cet enregistrement dessine une bordure autour de la région spécifiée en utilisant le pinceau spécifié. |
| [EMR_INVERTRGN](#EMR-INVERTRGN) | Cet enregistrement inverse les couleurs dans la région spécifiée. |
| [EMR_PAINTRGN](#EMR-PAINTRGN) | Cet enregistrement peint la région spécifiée en utilisant le pinceau actuellement sélectionné dans le contexte du dispositif de lecture. |
| [EMR_EXTSELECTCLIPRGN](#EMR-EXTSELECTCLIPRGN) | Cet enregistrement combine la région spécifiée avec la région de découpage actuelle en utilisant le mode spécifié. |
| [EMR_BITBLT](#EMR-BITBLT) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée. |
| [EMR_STRETCHBLT](#EMR-STRETCHBLT) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire. |
| [EMR_MASKBLT](#EMR-MASKBLT) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau et avec l'application d'un bitmap de masque de couleur, selon des opérations raster de premier plan et d'arrière-plan spécifiées. |
| [EMR_PLGBLT](#EMR-PLGBLT) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un parallélogramme de destination, avec l'application d'un bitmap de masque de couleur. |
| [EMR_SETDIBITSTODEVICE](#EMR-SETDIBITSTODEVICE) | Cet enregistrement spécifie un transfert de bloc de pixels à partir de lignes de balayage spécifiées d'un bitmap source vers un rectangle de destination. |
| [EMR_STRETCHDIBITS](#EMR-STRETCHDIBITS) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire. |
| [EMR_EXTCREATEFONTINDIRECTW](#EMR-EXTCREATEFONTINDIRECTW) | Cet enregistrement définit une police logique qui possède les caractéristiques spécifiées. |
| [EMR_EXTTEXTOUTA](#EMR-EXTTEXTOUTA) | Cet enregistrement dessine une chaîne de texte ASCII en utilisant la police et les couleurs de texte actuelles.Note EMR\_EXTTEXTOUTA DOIT être émulé avec un enregistrement EMR\_EXTTEXTOUTW (section 2.3.5.8). |
| [EMR_EXTTEXTOUTW](#EMR-EXTTEXTOUTW) | Cet enregistrement dessine une chaîne de texte Unicode en utilisant la police et les couleurs de texte actuelles. |
| [EMR_POLYBEZIER16](#EMR-POLYBEZIER16) | Cet enregistrement définit une ou plusieurs courbes de Bézier. |
| [EMR_POLYGON16](#EMR-POLYGON16) | Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. |
| [EMR_POLYLINE16](#EMR-POLYLINE16) | Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié. |
| [EMR_POLYBEZIERTO16](#EMR-POLYBEZIERTO16) | Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle. |
| [EMR_POLYLINETO16](#EMR-POLYLINETO16) | Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. |
| [EMR_POLYPOLYLINE16](#EMR-POLYPOLYLINE16) | Cet enregistrement définit plusieurs séries de segments de ligne connectés. |
| [EMR_POLYPOLYGON16](#EMR-POLYPOLYGON16) | Cet enregistrement définit une série de polygones fermés. |
| [EMR_POLYDRAW16](#EMR-POLYDRAW16) | Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier. |
| [EMR_CREATEMONOBRUSH](#EMR-CREATEMONOBRUSH) | Cet enregistrement définit un pinceau logique avec le motif bitmap spécifié. |
| [EMR_CREATEDIBPATTERNBRUSHPT](#EMR-CREATEDIBPATTERNBRUSHPT) | Cet enregistrement définit un pinceau logique qui possède le motif spécifié par le DIB. |
| [EMR_EXTCREATEPEN](#EMR-EXTCREATEPEN) | Cet enregistrement définit un stylo cosmétique ou géométrique logique qui possède le style, la largeur et les attributs de pinceau spécifiés. |
| [EMR_POLYTEXTOUTA](#EMR-POLYTEXTOUTA) | Cet enregistrement dessine une ou plusieurs chaînes de texte ASCII en utilisant la police et les couleurs de texte actuelles. |
| [EMR_POLYTEXTOUTW](#EMR-POLYTEXTOUTW) | Cet enregistrement dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles. |
| [EMR_SETICMMODE](#EMR-SETICMMODE) | Cet enregistrement spécifie le mode de gestion des couleurs d'image (ICM) pour les opérations graphiques. |
| [EMR_CREATECOLORSPACE](#EMR-CREATECOLORSPACE) | Cet enregistrement crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères ASCII |
| [EMR_SETCOLORSPACE](#EMR-SETCOLORSPACE) | Cet enregistrement définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques. |
| [EMR_DELETECOLORSPACE](#EMR-DELETECOLORSPACE) | Cet enregistrement supprime un objet d'espace colorimétrique logique. |
| [EMR_GLSRECORD](#EMR-GLSRECORD) | Cet enregistrement spécifie une fonction OpenGL. |
| [EMR_GLSBOUNDEDRECORD](#EMR-GLSBOUNDEDRECORD) | Cet enregistrement spécifie une fonction OpenGL avec un rectangle de délimitation pour la sortie. |
| [EMR_PIXELFORMAT](#EMR-PIXELFORMAT) | Cet enregistrement spécifie le format de pixel à utiliser pour les opérations graphiques |
| [EMR_DRAWESCAPE](#EMR-DRAWESCAPE) | Cet enregistrement transmet des informations arbitraires au pilote. |
| [EMR_EXTESCAPE](#EMR-EXTESCAPE) | Cet enregistrement transmet des informations arbitraires au pilote. |
| [EMR_SMALLTEXTOUT](#EMR-SMALLTEXTOUT) | Cet enregistrement génère une chaîne. |
| [EMR_FORCEUFIMAPPING](#EMR-FORCEUFIMAPPING) | Cet enregistrement force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId plutôt que de leurs informations LogFont. |
| [EMR_NAMEDESCAPE](#EMR-NAMEDESCAPE) | Cet enregistrement transmet des informations arbitraires au pilote nommé fourni. |
| [EMR_COLORCORRECTPALETTE](#EMR-COLORCORRECTPALETTE) | Cet enregistrement spécifie comment corriger les entrées d'un objet palette logique en utilisant les valeurs du Windows Color System (WCS) 1.0. |
| [EMR_SETICMPROFILEA](#EMR-SETICMPROFILEA) | Cet enregistrement spécifie un profil couleur dans un fichier dont le nom est composé de caractères ASCII, pour la sortie graphique. |
| [EMR_SETICMPROFILEW](#EMR-SETICMPROFILEW) | Cet enregistrement spécifie un profil couleur dans un fichier dont le nom est composé de caractères Unicode, pour la sortie graphique. |
| [EMR_ALPHABLEND](#EMR-ALPHABLEND) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, incluant les données de transparence alpha, selon une opération de fusion spécifiée. |
| [EMR_SETLAYOUT](#EMR-SETLAYOUT) | Cet enregistrement spécifie l'ordre dans lequel le texte et les graphiques sont dessinés. |
| [EMR_TRANSPARENTBLT](#EMR-TRANSPARENTBLT) | Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, en traitant une couleur spécifiée comme transparente, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire. |
| [EMR_GRADIENTFILL](#EMR-GRADIENTFILL) | Cet enregistrement spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur. |
| [EMR_SETLINKEDUFIS](#EMR-SETLINKEDUFIS) | Cet enregistrement définit les UniversalFontIds des polices liées à utiliser lors de la recherche de caractères. |
| [EMR_SETTEXTJUSTIFICATION](#EMR-SETTEXTJUSTIFICATION) | Cet enregistrement spécifie la quantité d'espace supplémentaire à ajouter aux caractères de césure à des fins de justification. |
| [EMR_COLORMATCHTOTARGETW](#EMR-COLORMATCHTOTARGETW) | Cet enregistrement spécifie s'il faut effectuer une correspondance de couleur avec un profil couleur qui est spécifié dans un fichier dont le nom est composé de caractères Unicode. |
| [EMR_CREATECOLORSPACEW](#EMR-CREATECOLORSPACEW) | Cet enregistrement crée un objet d'espace couleur logique à partir d'un profil couleur dont le nom est composé de caractères Unicode. |
### EMR_HEADER {#EMR-HEADER}
```
public static final int EMR_HEADER
```


Cet enregistrement définit le début du métafichier et spécifie ses caractéristiques ; son contenu, y compris les dimensions de l'image incorporée ; le nombre d'enregistrements dans le métafichier ; et la résolution de l'appareil sur lequel l'image incorporée a été créée. Ces valeurs permettent au métafichier d'être indépendant du dispositif.

### EMR_POLYBEZIER {#EMR-POLYBEZIER}
```
public static final int EMR_POLYBEZIER
```


Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes de Bézier cubiques sont définies à l'aide des points d'extrémité et des points de contrôle spécifiés, et sont tracées avec le crayon actuel.

### EMR_POLYGON {#EMR-POLYGON}
```
public static final int EMR_POLYGON
```


Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. Le polygone est contourné en utilisant le crayon actuel et rempli en utilisant le pinceau actuel et le mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier.

### EMR_POLYLINE {#EMR-POLYLINE}
```
public static final int EMR_POLYLINE
```


Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié.

### EMR_POLYBEZIERTO {#EMR-POLYBEZIERTO}
```
public static final int EMR_POLYBEZIERTO
```


Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle.

### EMR_POLYLINETO {#EMR-POLYLINETO}
```
public static final int EMR_POLYLINETO
```


Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. Une ligne est tracée de la position actuelle au premier point spécifié par le champ points en utilisant le crayon actuel. Pour chaque ligne supplémentaire, le tracé s'effectue du point final de la ligne précédente au point suivant spécifié par points.

### EMR_POLYPOLYLINE {#EMR-POLYPOLYLINE}
```
public static final int EMR_POLYPOLYLINE
```


Cet enregistrement définit plusieurs séries de segments de ligne connectés. Les segments de ligne sont tracés en utilisant le crayon actuel. Les figures formées par les segments ne sont pas remplies. La position actuelle n'est ni utilisée ni mise à jour par cet enregistrement.

### EMR_POLYPOLYGON {#EMR-POLYPOLYGON}
```
public static final int EMR_POLYPOLYGON
```


Cet enregistrement définit une série de polygones fermés. Chaque polygone est contourné en utilisant le crayon actuel et rempli en utilisant le pinceau actuel et le mode de remplissage du polygone. Les polygones définis par cet enregistrement peuvent se chevaucher.

### EMR_SETWINDOWEXTEX {#EMR-SETWINDOWEXTEX}
```
public static final int EMR_SETWINDOWEXTEX
```


Cet enregistrement définit l'étendue de la fenêtre.

### EMR_SETWINDOWORGEX {#EMR-SETWINDOWORGEX}
```
public static final int EMR_SETWINDOWORGEX
```


Cet enregistrement définit l'origine de la fenêtre.

### EMR_SETVIEWPORTEXTEX {#EMR-SETVIEWPORTEXTEX}
```
public static final int EMR_SETVIEWPORTEXTEX
```


Cet enregistrement définit l'étendue du viewport.

### EMR_SETVIEWPORTORGEX {#EMR-SETVIEWPORTORGEX}
```
public static final int EMR_SETVIEWPORTORGEX
```


Cet enregistrement définit l'origine du viewport.

### EMR_SETBRUSHORGEX {#EMR-SETBRUSHORGEX}
```
public static final int EMR_SETBRUSHORGEX
```


Cet enregistrement définit l'origine du pinceau actuel.

### EMR_EOF {#EMR-EOF}
```
public static final int EMR_EOF
```


Cet enregistrement indique la fin du métafichier.

### EMR_SETPIXELV {#EMR-SETPIXELV}
```
public static final int EMR_SETPIXELV
```


Cet enregistrement définit la couleur du pixel aux coordonnées logiques spécifiées.

### EMR_SETMAPPERFLAGS {#EMR-SETMAPPERFLAGS}
```
public static final int EMR_SETMAPPERFLAGS
```


Cet enregistrement spécifie les paramètres du processus d'appariement des polices logiques aux polices physiques, qui est effectué par le mappeur de polices.

### EMR_SETMAPMODE {#EMR-SETMAPMODE}
```
public static final int EMR_SETMAPMODE
```


Cet enregistrement définit le mode de cartographie du contexte de périphérique de lecture. Le mode de cartographie définit l'unité de mesure utilisée pour transformer les unités d'espace de page en unités d'espace de périphérique, et définit également l'orientation des axes x et y du périphérique.

### EMR_SETBKMODE {#EMR-SETBKMODE}
```
public static final int EMR_SETBKMODE
```


Cet enregistrement définit le mode de mélange d'arrière-plan du contexte de périphérique de lecture. Le mode de mélange d'arrière-plan est utilisé avec le texte, les pinceaux hachurés et les styles de crayon qui ne sont pas des lignes pleines.

### EMR_SETPOLYFILLMODE {#EMR-SETPOLYFILLMODE}
```
public static final int EMR_SETPOLYFILLMODE
```


Cet enregistrement définit le mode de remplissage du polygone.

### EMR_SETROP2 {#EMR-SETROP2}
```
public static final int EMR_SETROP2
```


Cet enregistrement définit le mode d'opération raster binaire.

### EMR_SETSTRETCHBLTMODE {#EMR-SETSTRETCHBLTMODE}
```
public static final int EMR_SETSTRETCHBLTMODE
```


Cet enregistrement définit le mode d'étirement du bitmap.

### EMR_SETTEXTALIGN {#EMR-SETTEXTALIGN}
```
public static final int EMR_SETTEXTALIGN
```


Cet enregistrement définit l'alignement du texte.

### EMR_SETCOLORADJUSTMENT {#EMR-SETCOLORADJUSTMENT}
```
public static final int EMR_SETCOLORADJUSTMENT
```


Cet enregistrement définit les valeurs d'ajustement des couleurs pour le contexte du dispositif de lecture en utilisant les valeurs spécifiées.

### EMR_SETTEXTCOLOR {#EMR-SETTEXTCOLOR}
```
public static final int EMR_SETTEXTCOLOR
```


Cet enregistrement définit la couleur actuelle du texte.

### EMR_SETBKCOLOR {#EMR-SETBKCOLOR}
```
public static final int EMR_SETBKCOLOR
```


Cet enregistrement définit la couleur d'arrière-plan.

### EMR_OFFSETCLIPRGN {#EMR-OFFSETCLIPRGN}
```
public static final int EMR_OFFSETCLIPRGN
```


Cet enregistrement redéfinit la région de découpage du contexte du dispositif de lecture selon les décalages spécifiés.

### EMR_MOVETOEX {#EMR-MOVETOEX}
```
public static final int EMR_MOVETOEX
```


Cet enregistrement définit les coordonnées de la nouvelle position actuelle, en unités logiques.

### EMR_SETMETARGN {#EMR-SETMETARGN}
```
public static final int EMR_SETMETARGN
```


Cet enregistrement intersecte la région de découpage actuelle du contexte de périphérique de lecture avec la méta-région actuelle et enregistre la région combinée comme nouvelle méta-région. La région de découpage est réinitialisée à une région nulle.

### EMR_EXCLUDECLIPRECT {#EMR-EXCLUDECLIPRECT}
```
public static final int EMR_EXCLUDECLIPRECT
```


Cet enregistrement définit une nouvelle région de découpage qui consiste en la région de découpage existante moins le rectangle spécifié.

### EMR_INTERSECTCLIPRECT {#EMR-INTERSECTCLIPRECT}
```
public static final int EMR_INTERSECTCLIPRECT
```


Cet enregistrement définit une nouvelle région de découpage à partir de l'intersection de la région de découpage actuelle et du rectangle spécifié.

### EMR_SCALEVIEWPORTEXTEX {#EMR-SCALEVIEWPORTEXTEX}
```
public static final int EMR_SCALEVIEWPORTEXTEX
```


Cet enregistrement redéfinit le viewport du contexte du dispositif de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés.

### EMR_SCALEWINDOWEXTEX {#EMR-SCALEWINDOWEXTEX}
```
public static final int EMR_SCALEWINDOWEXTEX
```


Cet enregistrement redéfinit la fenêtre du contexte du dispositif de lecture en utilisant les rapports formés par les multiplicateurs et diviseurs spécifiés.

### EMR_SAVEDC {#EMR-SAVEDC}
```
public static final int EMR_SAVEDC
```


Cet enregistrement enregistre l'état actuel du contexte du dispositif de lecture en copiant les données décrivant les objets sélectionnés et les modes graphiques\u2014y compris le bitmap, le pinceau, la palette, la police, le crayon, la région, le mode de dessin et le mode de cartographie\u2014dans une pile de contextes de dispositif enregistrés.

### EMR_RESTOREDC {#EMR-RESTOREDC}
```
public static final int EMR_RESTOREDC
```


Cet enregistrement restaure le contexte de périphérique de lecture à l'état enregistré spécifié. Le contexte de périphérique de lecture est restauré en dépilant les informations d'état d'une pile de contextes de périphérique enregistrés créés par les enregistrements EMR\_SAVEDC (section 2.3.11) précédents.

### EMR_SETWORLDTRANSFORM {#EMR-SETWORLDTRANSFORM}
```
public static final int EMR_SETWORLDTRANSFORM
```


Cet enregistrement définit une transformation linéaire bidimensionnelle entre l'espace monde et l'espace page (pour plus d'informations, voir [MSDN-WRLDPGSPC]) pour le contexte de périphérique de lecture. Cette transformation peut être utilisée pour mettre à l'échelle, faire pivoter, ciseler ou translater la sortie graphique.

### EMR_MODIFYWORLDTRANSFORM {#EMR-MODIFYWORLDTRANSFORM}
```
public static final int EMR_MODIFYWORLDTRANSFORM
```


Cet enregistrement redéfinit la transformation du monde pour le contexte du dispositif de lecture en utilisant le mode spécifié.

### EMR_SELECTOBJECT {#EMR-SELECTOBJECT}
```
public static final int EMR_SELECTOBJECT
```


Cet enregistrement ajoute un objet au contexte du dispositif de lecture, en l'identifiant par son index dans la table d'objets EMF (section 3.1.1.1).

### EMR_CREATEPEN {#EMR-CREATEPEN}
```
public static final int EMR_CREATEPEN
```


Cet enregistrement définit un crayon logique ayant le style, la largeur et la couleur spécifiés. Le crayon peut ensuite être sélectionné dans le contexte de périphérique de lecture et utilisé pour tracer des lignes et des courbes.

### EMR_CREATEBRUSHINDIRECT {#EMR-CREATEBRUSHINDIRECT}
```
public static final int EMR_CREATEBRUSHINDIRECT
```


Cet enregistrement définit un pinceau logique pour le remplissage de formes dans les opérations graphiques.

### EMR_DELETEOBJECT {#EMR-DELETEOBJECT}
```
public static final int EMR_DELETEOBJECT
```


Cet enregistrement supprime un objet graphique, en effaçant son index dans la table d'objets EMF. Si l'objet supprimé est sélectionné dans le contexte de périphérique de lecture, l'objet par défaut pour cette propriété de contexte DOIT être restauré.

### EMR_ANGLEARC {#EMR-ANGLEARC}
```
public static final int EMR_ANGLEARC
```


Cet enregistrement définit un segment de ligne d'un arc. Le segment de ligne est tracé de la position actuelle au début de l'arc. L'arc est tracé le long du périmètre d'un cercle avec le rayon et le centre donnés. La longueur de l'arc est définie par les angles de départ et de balayage fournis.

### EMR_ELLIPSE {#EMR-ELLIPSE}
```
public static final int EMR_ELLIPSE
```


Cet enregistrement définit une ellipse. Le centre de l'ellipse est le centre du rectangle englobant spécifié. L'ellipse est contournée en utilisant le stylo actuel et remplie en utilisant le pinceau actuel.

### EMR_RECTANGLE {#EMR-RECTANGLE}
```
public static final int EMR_RECTANGLE
```


Cet enregistrement définit un rectangle. Le rectangle est contourné en utilisant le stylo actuel et rempli en utilisant le pinceau actuel.

### EMR_ROUNDRECT {#EMR-ROUNDRECT}
```
public static final int EMR_ROUNDRECT
```


Cet enregistrement définit un rectangle à coins arrondis. Le rectangle est contourné en utilisant le stylo actuel et rempli en utilisant le pinceau actuel.

### EMR_ARC {#EMR-ARC}
```
public static final int EMR_ARC
```


Cet enregistrement définit un arc elliptique.

### EMR_CHORD {#EMR-CHORD}
```
public static final int EMR_CHORD
```


Cet enregistrement définit une corde (une région délimitée par l'intersection d'une ellipse et d'un segment de ligne, appelée sécante). La corde est contournée en utilisant le stylo actuel et remplie en utilisant le pinceau actuel.

### EMR_PIE {#EMR-PIE}
```
public static final int EMR_PIE
```


Cet enregistrement définit un secteur en forme de part de tarte délimité par l'intersection d'une ellipse et de deux rayons. Le secteur est contourné en utilisant le stylo actuel et rempli en utilisant le pinceau actuel.

### EMR_SELECTPALETTE {#EMR-SELECTPALETTE}
```
public static final int EMR_SELECTPALETTE
```


Cet enregistrement ajoute un objet LogPalette (section 2.2.17) au contexte du dispositif de lecture, en l'identifiant par son indice dans la table des objets EMF.

### EMR_CREATEPALETTE {#EMR-CREATEPALETTE}
```
public static final int EMR_CREATEPALETTE
```


Cet enregistrement définit un objet LogPalette.

### EMR_SETPALETTEENTRIES {#EMR-SETPALETTEENTRIES}
```
public static final int EMR_SETPALETTEENTRIES
```


Cet enregistrement définit les valeurs de couleur RVB (rouge-vert-bleu) dans une plage d'entrées d'un objet LogPalette.

### EMR_RESIZEPALETTE {#EMR-RESIZEPALETTE}
```
public static final int EMR_RESIZEPALETTE
```


Cet enregistrement augmente ou diminue la taille d'une palette logique.

### EMR_REALIZEPALETTE {#EMR-REALIZEPALETTE}
```
public static final int EMR_REALIZEPALETTE
```


Cet enregistrement mappe les entrées de la palette logique actuelle vers la palette système.

### EMR_EXTFLOODFILL {#EMR-EXTFLOODFILL}
```
public static final int EMR_EXTFLOODFILL
```


Cet enregistrement remplit une zone de la surface d'affichage avec le pinceau actuel.

### EMR_LINETO {#EMR-LINETO}
```
public static final int EMR_LINETO
```


Cet enregistrement définit une ligne depuis la position actuelle jusqu'au point spécifié, sans l'inclure. Il réinitialise la position actuelle au point spécifié.

### EMR_ARCTO {#EMR-ARCTO}
```
public static final int EMR_ARCTO
```


Cet enregistrement définit un arc elliptique. Il réinitialise la position actuelle au point final de l'arc.

### EMR_POLYDRAW {#EMR-POLYDRAW}
```
public static final int EMR_POLYDRAW
```


Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier.

### EMR_SETARCDIRECTION {#EMR-SETARCDIRECTION}
```
public static final int EMR_SETARCDIRECTION
```


Cet enregistrement définit la direction de dessin à utiliser pour les opérations d'arc et de rectangle.

### EMR_SETMITERLIMIT {#EMR-SETMITERLIMIT}
```
public static final int EMR_SETMITERLIMIT
```


Cet enregistrement définit la limite de la longueur des jointures en onglet pour le contexte du dispositif de lecture.

### EMR_BEGINPATH {#EMR-BEGINPATH}
```
public static final int EMR_BEGINPATH
```


Cet enregistrement ouvre une parenthèse de chemin dans le contexte du dispositif de lecture.

--------------------

Après l'ouverture d'une accolade de chemin, une application peut commencer à traiter les enregistrements pour définir les points qui se trouvent dans le chemin. Une application DOIT fermer une accolade de chemin ouverte en traitant l'enregistrement EMR\_ENDPATH. Lorsqu'une application traite l'enregistrement EMR\_BEGINPATH, tous les chemins précédents DOIVENT être supprimés du contexte de périphérique de lecture.

### EMR_ENDPATH {#EMR-ENDPATH}
```
public static final int EMR_ENDPATH
```


Cet enregistrement ferme une parenthèse de chemin et sélectionne le chemin défini par la parenthèse dans le contexte du dispositif de lecture.

### EMR_CLOSEFIGURE {#EMR-CLOSEFIGURE}
```
public static final int EMR_CLOSEFIGURE
```


Cet enregistrement ferme une figure ouverte dans un chemin.

--------------------

Le traitement de l'enregistrement EMR\_CLOSEFIGURE DOIT fermer la figure en traçant une ligne de la position actuelle au premier point de la figure, puis il DOIT connecter les lignes en utilisant le style de jointure de ligne. Si une figure est fermée en traitant l'enregistrement EMR\_LINETO au lieu de l'enregistrement EMR\_CLOSEFIGURE, des embouts sont utilisés pour créer le coin au lieu d'une jointure. EMR\_LINETO est spécifié dans la section 2.3.5.13. L'enregistrement EMR\_CLOSEFIGURE NE DOIT être utilisé que s'il existe une accolade de chemin ouverte dans le contexte de périphérique de lecture. Une figure dans un chemin est ouverte à moins d'être explicitement fermée en traitant cet enregistrement. Note : une figure peut être ouverte même si le point actuel et le point de départ de la figure sont identiques. Après le traitement de l'enregistrement EMR\_CLOSEFIGURE, l'ajout d'une ligne ou d'une courbe au chemin DOIT démarrer une nouvelle figure.

### EMR_FILLPATH {#EMR-FILLPATH}
```
public static final int EMR_FILLPATH
```


Cet enregistrement ferme toutes les figures ouvertes dans le chemin actuel et remplit l'intérieur du chemin en utilisant le pinceau actuel et le mode de remplissage de polygone.

### EMR_STROKEANDFILLPATH {#EMR-STROKEANDFILLPATH}
```
public static final int EMR_STROKEANDFILLPATH
```


Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel, et remplit son intérieur en utilisant le pinceau actuel.

### EMR_STROKEPATH {#EMR-STROKEPATH}
```
public static final int EMR_STROKEPATH
```


Cet enregistrement rend le chemin spécifié en utilisant le stylo actuel.

### EMR_FLATTENPATH {#EMR-FLATTENPATH}
```
public static final int EMR_FLATTENPATH
```


Cet enregistrement transforme toute courbe du chemin sélectionnée dans le contexte du dispositif de lecture, en convertissant chaque courbe en une séquence de lignes.

### EMR_WIDENPATH {#EMR-WIDENPATH}
```
public static final int EMR_WIDENPATH
```


Cet enregistrement redéfinit le chemin actuel comme la zone qui serait peinte si le chemin était tracé en utilisant le stylo actuellement sélectionné dans le contexte du dispositif de lecture.

### EMR_SELECTCLIPPATH {#EMR-SELECTCLIPPATH}
```
public static final int EMR_SELECTCLIPPATH
```


Cet enregistrement définit le chemin actuel comme une région de découpage pour le contexte du dispositif de lecture, en combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié.

### EMR_ABORTPATH {#EMR-ABORTPATH}
```
public static final int EMR_ABORTPATH
```


Cet enregistrement annule un crochet de chemin ou supprime le chemin d'un crochet de chemin fermé.

### EMR_COMMENT {#EMR-COMMENT}
```
public static final int EMR_COMMENT
```


Cet enregistrement spécifie des données privées arbitraires.

### EMR_FILLRGN {#EMR-FILLRGN}
```
public static final int EMR_FILLRGN
```


Cet enregistrement remplit la région spécifiée en utilisant le pinceau spécifié.

### EMR_FRAMERGN {#EMR-FRAMERGN}
```
public static final int EMR_FRAMERGN
```


Cet enregistrement dessine une bordure autour de la région spécifiée en utilisant le pinceau spécifié.

### EMR_INVERTRGN {#EMR-INVERTRGN}
```
public static final int EMR_INVERTRGN
```


Cet enregistrement inverse les couleurs dans la région spécifiée.

### EMR_PAINTRGN {#EMR-PAINTRGN}
```
public static final int EMR_PAINTRGN
```


Cet enregistrement peint la région spécifiée en utilisant le pinceau actuellement sélectionné dans le contexte du dispositif de lecture.

### EMR_EXTSELECTCLIPRGN {#EMR-EXTSELECTCLIPRGN}
```
public static final int EMR_EXTSELECTCLIPRGN
```


Cet enregistrement combine la région spécifiée avec la région de découpage actuelle en utilisant le mode spécifié.

### EMR_BITBLT {#EMR-BITBLT}
```
public static final int EMR_BITBLT
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée.

### EMR_STRETCHBLT {#EMR-STRETCHBLT}
```
public static final int EMR_STRETCHBLT
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.

### EMR_MASKBLT {#EMR-MASKBLT}
```
public static final int EMR_MASKBLT
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau et avec l'application d'un bitmap de masque de couleur, selon des opérations raster de premier plan et d'arrière-plan spécifiées.

### EMR_PLGBLT {#EMR-PLGBLT}
```
public static final int EMR_PLGBLT
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un parallélogramme de destination, avec l'application d'un bitmap de masque de couleur.

### EMR_SETDIBITSTODEVICE {#EMR-SETDIBITSTODEVICE}
```
public static final int EMR_SETDIBITSTODEVICE
```


Cet enregistrement spécifie un transfert de bloc de pixels à partir de lignes de balayage spécifiées d'un bitmap source vers un rectangle de destination.

### EMR_STRETCHDIBITS {#EMR-STRETCHDIBITS}
```
public static final int EMR_STRETCHDIBITS
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.

### EMR_EXTCREATEFONTINDIRECTW {#EMR-EXTCREATEFONTINDIRECTW}
```
public static final int EMR_EXTCREATEFONTINDIRECTW
```


Cet enregistrement définit une police logique possédant les caractéristiques spécifiées. La police peut ensuite être sélectionnée comme police actuelle pour le contexte de périphérique de lecture.

### EMR_EXTTEXTOUTA {#EMR-EXTTEXTOUTA}
```
public static final int EMR_EXTTEXTOUTA
```


Cet enregistrement dessine une chaîne de texte ASCII en utilisant la police actuelle et les couleurs de texte. Note : EMR\_EXTTEXTOUTA DOIT être émulé avec un enregistrement EMR\_EXTTEXTOUTW (section 2.3.5.8). Cela nécessite que la chaîne de texte ASCII dans l'objet EmrText soit convertie en encodage Unicode UTF16-LE.

### EMR_EXTTEXTOUTW {#EMR-EXTTEXTOUTW}
```
public static final int EMR_EXTTEXTOUTW
```


Cet enregistrement dessine une chaîne de texte Unicode en utilisant la police et les couleurs de texte actuelles.

### EMR_POLYBEZIER16 {#EMR-POLYBEZIER16}
```
public static final int EMR_POLYBEZIER16
```


Cet enregistrement définit une ou plusieurs courbes de Bézier. Les courbes sont dessinées en utilisant le stylo actuel.

### EMR_POLYGON16 {#EMR-POLYGON16}
```
public static final int EMR_POLYGON16
```


Cet enregistrement définit un polygone composé de deux sommets ou plus reliés par des lignes droites. Le polygone est contourné en utilisant le crayon actuel et rempli en utilisant le pinceau actuel et le mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier.

### EMR_POLYLINE16 {#EMR-POLYLINE16}
```
public static final int EMR_POLYLINE16
```


Cet enregistrement définit une série de segments de ligne en reliant les points du tableau spécifié.

### EMR_POLYBEZIERTO16 {#EMR-POLYBEZIERTO16}
```
public static final int EMR_POLYBEZIERTO16
```


Cet enregistrement définit une ou plusieurs courbes de Bézier basées sur la position actuelle.

### EMR_POLYLINETO16 {#EMR-POLYLINETO16}
```
public static final int EMR_POLYLINETO16
```


Cet enregistrement définit une ou plusieurs lignes droites basées sur la position actuelle. Une ligne est dessinée de la position actuelle au premier point spécifié par le champ Points en utilisant le stylo actuel. Pour chaque ligne supplémentaire, le dessin est effectué du point final de la ligne précédente au point suivant spécifié par Points.

### EMR_POLYPOLYLINE16 {#EMR-POLYPOLYLINE16}
```
public static final int EMR_POLYPOLYLINE16
```


Cet enregistrement définit plusieurs séries de segments de ligne connectés.

### EMR_POLYPOLYGON16 {#EMR-POLYPOLYGON16}
```
public static final int EMR_POLYPOLYGON16
```


Cet enregistrement définit une série de polygones fermés. Chaque polygone est contourné en utilisant le stylo actuel et rempli en utilisant le pinceau actuel ainsi que le mode de remplissage des polygones. Les polygones spécifiés par cet enregistrement peuvent se chevaucher.

### EMR_POLYDRAW16 {#EMR-POLYDRAW16}
```
public static final int EMR_POLYDRAW16
```


Cet enregistrement définit un ensemble de segments de ligne et de courbes de Bézier.

### EMR_CREATEMONOBRUSH {#EMR-CREATEMONOBRUSH}
```
public static final int EMR_CREATEMONOBRUSH
```


Cet enregistrement définit un pinceau logique avec le motif bitmap spécifié. Le bitmap peut être une section bitmap indépendante du dispositif (DIB) ou un bitmap dépendant du dispositif.

### EMR_CREATEDIBPATTERNBRUSHPT {#EMR-CREATEDIBPATTERNBRUSHPT}
```
public static final int EMR_CREATEDIBPATTERNBRUSHPT
```


Cet enregistrement définit un pinceau logique qui possède le motif spécifié par le DIB.

### EMR_EXTCREATEPEN {#EMR-EXTCREATEPEN}
```
public static final int EMR_EXTCREATEPEN
```


Cet enregistrement définit un stylo cosmétique ou géométrique logique qui possède le style, la largeur et les attributs de pinceau spécifiés.

### EMR_POLYTEXTOUTA {#EMR-POLYTEXTOUTA}
```
public static final int EMR_POLYTEXTOUTA
```


Cet enregistrement dessine une ou plusieurs chaînes de texte ASCII en utilisant la police actuelle et les couleurs de texte. Note : EMR\_POLYTEXTOUTA DOIT être émulé avec une série d'enregistrements EMR\_EXTTEXTOUTW, un par chaîne.

### EMR_POLYTEXTOUTW {#EMR-POLYTEXTOUTW}
```
public static final int EMR_POLYTEXTOUTW
```


Cet enregistrement dessine une ou plusieurs chaînes de texte Unicode en utilisant la police actuelle et les couleurs de texte. Note : EMR\_POLYTEXTOUTW DOIT être émulé avec une série d'enregistrements EMR\_EXTTEXTOUTW, un par chaîne.

### EMR_SETICMMODE {#EMR-SETICMMODE}
```
public static final int EMR_SETICMMODE
```


Cet enregistrement spécifie le mode de gestion des couleurs d'image (ICM) pour les opérations graphiques.

### EMR_CREATECOLORSPACE {#EMR-CREATECOLORSPACE}
```
public static final int EMR_CREATECOLORSPACE
```


Cet enregistrement crée un objet d'espace colorimétrique logique à partir d'un profil couleur dont le nom est composé de caractères ASCII

### EMR_SETCOLORSPACE {#EMR-SETCOLORSPACE}
```
public static final int EMR_SETCOLORSPACE
```


Cet enregistrement définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques.

### EMR_DELETECOLORSPACE {#EMR-DELETECOLORSPACE}
```
public static final int EMR_DELETECOLORSPACE
```


Cet enregistrement supprime un objet d'espace colorimétrique logique. Note : un enregistrement EMR\_DELETEOBJECT DOIT être utilisé à la place de EMR\_DELETECOLORSPACE pour supprimer un objet d'espace colorimétrique logique.

### EMR_GLSRECORD {#EMR-GLSRECORD}
```
public static final int EMR_GLSRECORD
```


Cet enregistrement spécifie une fonction OpenGL.

### EMR_GLSBOUNDEDRECORD {#EMR-GLSBOUNDEDRECORD}
```
public static final int EMR_GLSBOUNDEDRECORD
```


Cet enregistrement spécifie une fonction OpenGL avec un rectangle de délimitation pour la sortie.

### EMR_PIXELFORMAT {#EMR-PIXELFORMAT}
```
public static final int EMR_PIXELFORMAT
```


Cet enregistrement spécifie le format de pixel à utiliser pour les opérations graphiques

### EMR_DRAWESCAPE {#EMR-DRAWESCAPE}
```
public static final int EMR_DRAWESCAPE
```


Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que ces informations entraînent la réalisation d'un dessin.

### EMR_EXTESCAPE {#EMR-EXTESCAPE}
```
public static final int EMR_EXTESCAPE
```


Cet enregistrement transmet des informations arbitraires au pilote. L'intention est que ces informations n'entraînent pas la réalisation d'un dessin.

### EMR_SMALLTEXTOUT {#EMR-SMALLTEXTOUT}
```
public static final int EMR_SMALLTEXTOUT
```


Cet enregistrement génère une chaîne.

### EMR_FORCEUFIMAPPING {#EMR-FORCEUFIMAPPING}
```
public static final int EMR_FORCEUFIMAPPING
```


Cet enregistrement force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId plutôt que de leurs informations LogFont.

### EMR_NAMEDESCAPE {#EMR-NAMEDESCAPE}
```
public static final int EMR_NAMEDESCAPE
```


Cet enregistrement transmet des informations arbitraires au pilote nommé fourni.

### EMR_COLORCORRECTPALETTE {#EMR-COLORCORRECTPALETTE}
```
public static final int EMR_COLORCORRECTPALETTE
```


Cet enregistrement spécifie comment corriger les entrées d'un objet palette logique en utilisant les valeurs du Windows Color System (WCS) 1.0.

### EMR_SETICMPROFILEA {#EMR-SETICMPROFILEA}
```
public static final int EMR_SETICMPROFILEA
```


Cet enregistrement spécifie un profil couleur dans un fichier dont le nom est composé de caractères ASCII, pour la sortie graphique.

### EMR_SETICMPROFILEW {#EMR-SETICMPROFILEW}
```
public static final int EMR_SETICMPROFILEW
```


Cet enregistrement spécifie un profil couleur dans un fichier dont le nom est composé de caractères Unicode, pour la sortie graphique.

### EMR_ALPHABLEND {#EMR-ALPHABLEND}
```
public static final int EMR_ALPHABLEND
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, incluant les données de transparence alpha, selon une opération de fusion spécifiée.

### EMR_SETLAYOUT {#EMR-SETLAYOUT}
```
public static final int EMR_SETLAYOUT
```


Cet enregistrement spécifie l'ordre dans lequel le texte et les graphiques sont dessinés.

### EMR_TRANSPARENTBLT {#EMR-TRANSPARENTBLT}
```
public static final int EMR_TRANSPARENTBLT
```


Cet enregistrement spécifie un transfert de bloc de pixels d'un bitmap source vers un rectangle de destination, en traitant une couleur spécifiée comme transparente, en étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire.

### EMR_GRADIENTFILL {#EMR-GRADIENTFILL}
```
public static final int EMR_GRADIENTFILL
```


Cet enregistrement spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur.

### EMR_SETLINKEDUFIS {#EMR-SETLINKEDUFIS}
```
public static final int EMR_SETLINKEDUFIS
```


Cet enregistrement définit les UniversalFontIds des polices liées à utiliser lors de la recherche de caractères.

### EMR_SETTEXTJUSTIFICATION {#EMR-SETTEXTJUSTIFICATION}
```
public static final int EMR_SETTEXTJUSTIFICATION
```


Cet enregistrement spécifie la quantité d'espace supplémentaire à ajouter aux caractères de césure à des fins de justification.

### EMR_COLORMATCHTOTARGETW {#EMR-COLORMATCHTOTARGETW}
```
public static final int EMR_COLORMATCHTOTARGETW
```


Cet enregistrement spécifie s'il faut effectuer une correspondance de couleur avec un profil couleur qui est spécifié dans un fichier dont le nom est composé de caractères Unicode.

### EMR_CREATECOLORSPACEW {#EMR-CREATECOLORSPACEW}
```
public static final int EMR_CREATECOLORSPACEW
```


Cet enregistrement crée un objet d'espace couleur logique à partir d'un profil couleur dont le nom est composé de caractères Unicode.

