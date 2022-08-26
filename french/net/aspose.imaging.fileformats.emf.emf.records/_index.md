---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lespace de noms contient des types MS-EMF  Enhanced Metafile Format. 2.3 EMF Records
type: docs
weight: 360
url: /fr/net/aspose.imaging.fileformats.emf.emf.records/
---
L'espace de noms contient des types [MS-EMF] : Enhanced Metafile Format. 2.3 EMF Records

## Des classes

| Classer | La description |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Cet enregistrement annule une parenthèse de chemin ou supprime le chemin d'une parenthèse de chemin fermée. |
| [EmfAlphaBlend](./emfalphablend) | L'enregistrement EMR_ALPHABLEND spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , y compris les données de transparence alpha, selon une opération de fusion spécifiée. |
| [EmfAngleArc](./emfanglearc) | L'enregistrement EMR_ANGLEARC spécifie un segment de ligne d'un arc. Le segment de ligne est tracé de la position actuelle au début de l'arc. L'arc est tracé le long du périmètre d'un cercle avec le rayon et le centre donnés . La longueur de l'arc est définie par les angles de départ et de balayage donnés |
| [EmfArc](./emfarc) | L'enregistrement EMR_ARC spécifie un arc elliptique. |
| [EmfArcTo](./emfarcto) | L'enregistrement EMR_ARCTO spécifie un arc elliptique. Il réinitialise la position actuelle au point final de l'arc. |
| [EmfBeginPath](./emfbeginpath) | Cet enregistrement ouvre une parenthèse de chemin dans le contexte de périphérique de lecture actuel. Une fois qu'une parenthèse de chemin est ouverte, une application peut commencer à traiter les enregistrements pour définir les points qui se trouvent dans le chemin. Une application DOIT fermer une parenthèse de chemin ouverte en traitant l'EMR_ENDPATH record. Lorsqu'une application traite l'enregistrement EMR_BEGINPATH, tous les chemins précédents DOIVENT être supprimés du contexte de périphérique de lecture. |
| [EmfBitBlt](./emfbitblt) | L'enregistrement EMR_BITBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | Les types d'enregistrement bitmap effectuent des transferts de blocs d'images bitmap. |
| [EmfChord](./emfchord) | L'enregistrement EMR_CHORD spécifie une corde, qui est une région délimitée par l'intersection d'une ellipse et d'un segment de droite, appelée sécante. L'accord est tracé à l'aide du stylo actuel et rempli à l'aide du pinceau actuel. |
| [EmfClippingRecordType](./emfclippingrecordtype) | Les types d'enregistrements de découpage spécifient et gèrent les régions de découpage. Remarque L'enregistrement EMR_SETMETARGN ne spécifie pas de paramètres. |
| [EmfCloseFigure](./emfclosefigure) | Cet enregistrement ferme une figure ouverte dans un chemin. Le traitement de l'enregistrement EMR_CLOSEFIGURE DOIT fermer la figure en traçant une ligne de la position actuelle au premier point de la figure, puis il DOIT connecter les lignes en utilisant le style de jointure de ligne. Si une figure est fermée en traitant l'enregistrement EMR_LINETO au lieu de l'enregistrement EMR_CLOSEFIGURE, les majuscules sont utilisées pour créer le coin au lieu d'une jointure. open path bracket dans le contexte du périphérique de lecture. Une figure dans un chemin est ouverte à moins qu'elle ne soit explicitement fermée en traitant cet enregistrement. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | L'enregistrement EMR_COLORCORRECTPALETTE spécifie comment corriger les entrées d'un objet logique palette à l'aide des valeurs WCS 1.0. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | L'enregistrement EMR_COLORMATCHTOTargetW spécifie s'il faut effectuer la correspondance des couleurs avec un profil color spécifié dans un fichier dont le nom est composé de caractères Unicode. |
| [EmfComment](./emfcomment) | L'enregistrement EMR_COMMENT contient des données privées arbitraires. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | L'enregistrement EMR_COMMENT_BEGINGROUP spécifie le début d'un groupe d'enregistrements de dessin. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | L'enregistrement EMR_COMMENT_EMFPLUS contient des enregistrements EMF+ intégrés. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | L'enregistrement EMR_COMMENT_EMFSPOOL contient des enregistrements EMFSPOOL intégrés. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup) | L'enregistrement EMR_COMMENT_ENDGROUP spécifie la fin d'un groupe d'enregistrements de dessin. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | L'enregistrement EMR_COMMENT_MULTIFORMATS spécifie une image dans plusieurs formats graphiques. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | Les types d'enregistrement EMR_COMMENT_PUBLIC spécifient les extensions du traitement EMF. |
| [EmfCommentRecordType](./emfcommentrecordtype) | Les types d'enregistrement de commentaire définissent des formats pour spécifier des données privées arbitraires, incorporer des enregistrements dans d'autres formats de métafichier et ajouter de nouvelles commandes ou des commandes spéciales. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | L'enregistrement EMR_COMMENT_WINDOWS_METAFILE spécifie une image dans un métafichier WMF intégré. |
| [EmfControlRecordType](./emfcontrolrecordtype) | Les types d'enregistrement de contrôle définissent le début et la fin d'un métafichier EMF et les propriétés du métafichier. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | L'enregistrement EMR_CREATEBRUSHINDIRECT définit un pinceau logique pour les opérations graphiques. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | L'enregistrement EMR_CREATECOLORSPACE crée un objet d'espace colorimétrique logique à partir d'un profil de couleur avec un nom composé de caractères ASCII. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | L'enregistrement EMR_CREATECOLORSPACEW crée un objet d'espace colorimétrique logique à partir d'un profil de couleur avec un nom composé de caractères Unicode. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | L'enregistrement EMR_CREATEDIBPATTERNBRUSHPT définit un pinceau à motif pour les opérations graphiques. Le modèle est spécifié par un DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | L'enregistrement EMR_CREATEMONOBRUSH définit un pinceau à motif monochrome pour les opérations graphiques. Le motif est spécifié par un DIB monochrome. |
| [EmfCreatePalette](./emfcreatepalette) | L'enregistrement EMR_CREATEPALETTE définit une palette logique pour les opérations graphiques. |
| [EmfCreatePen](./emfcreatepen) | L'enregistrement EMR_CREATEPEN définit une plume logique pour les opérations graphiques. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | L'enregistrement EMR_DELETECOLORSPACE supprime un objet d'espace colorimétrique logique. |
| [EmfDeleteObject](./emfdeleteobject) | L'enregistrement EMR_DELETEOBJECT supprime un objet graphique, qui est spécifié par son index dans la table d'objets EMF (section 3.1.1.1). |
| [EmfDrawEscape](./emfdrawescape) | L'enregistrement EMR_DRAWESCAPE transmet des informations arbitraires à un pilote d'imprimante. L'intention est que les informations entraînent la réalisation du dessin. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | Les types d'enregistrement de dessin effectuent le dessin graphique. |
| [EmfEllipse](./emfellipse) | L'enregistrement EMR_ELLIPSE spécifie une ellipse. Le centre de l'ellipse est le centre du rectangle englobant spécifié. L'ellipse est délimitée à l'aide du stylet actuel et remplie à l'aide du pinceau actuel. |
| [EmfEndPath](./emfendpath) | Cet enregistrement ferme une parenthèse de chemin et sélectionne le chemin défini par la parenthèse dans le contexte du périphérique de lecture. |
| [EmfEof](./emfeof) | L'enregistrement EMR_EOF indique la fin du métafichier et spécifie une palette. |
| [EmfEscapeRecordType](./emfescaperecordtype) | Les types d'enregistrements d'échappement exécutent les fonctions du pilote d'imprimante. |
| [EmfExcludeClipRect](./emfexcludecliprect) | L'enregistrement EMR_EXCLUDECLIPRECT spécifie une nouvelle zone de découpage composée de la zone de découpage existante moins le rectangle spécifié. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | L'enregistrement EMR_EXTCREATEFONTINDIRECTW définit une police logique pour les opérations graphiques. |
| [EmfExtCreatePen](./emfextcreatepen) | L'enregistrement EMR_EXTCREATEPEN définit une plume logique étendue pour les opérations graphiques. Un DIB facultatif peut être spécifié pour être utilisé comme style de ligne. |
| [EmfExtEscape](./emfextescape) | L'enregistrement EMR_EXTESCAPE transmet des informations arbitraires à un pilote d'imprimante. L'intention est que les informations n'entraîneront pas la réalisation d'un dessin. |
| [EmfExtFloodFill](./emfextfloodfill) | L'enregistrement EMR_EXTFLOODFILL remplit une zone de la surface d'affichage avec le pinceau actuel |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | L'enregistrement EMR_EXTSELECTCLIPRGN combine la région spécifiée avec la région de clip actuelle en utilisant le mode spécifié. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta) | L'enregistrement EMR_EXTTEXTOUTA dessine une chaîne de texte ASCII en utilisant la police et les couleurs de texte actuelles. |
| [EmfExtTextOutW](./emfexttextoutw) | L'enregistrement EMR_EXTTEXTOUTW dessine une chaîne de texte ASCII en utilisant la police et les couleurs de texte actuelles. |
| [EmfFillPath](./emffillpath) | L'enregistrement EMR_FILLPATH ferme toutes les figures ouvertes dans le chemin actuel et remplit l'intérieur du chemin de en utilisant le pinceau actuel et le mode de remplissage des polygones. |
| [EmfFillRgn](./emffillrgn) | L'enregistrement EMR_FILLRGN remplit la région spécifiée à l'aide du pinceau spécifié. |
| [EmfFlatternPath](./emfflatternpath) | Cet enregistrement transforme toutes les courbes du chemin sélectionné en contexte de périphérique de lecture ; chaque courbe DOIT être transformée en une séquence de lignes. |
| [EmfForceUfiMapping](./emfforceufimapping) | L'enregistrement EMR_FORCEUFIMAPPING force le mappeur de polices à faire correspondre les polices en fonction de leur UniversalFontId de préférence à leurs informations LogFont (section 2.2.13). |
| [EmfFrameRgn](./emfframergn) | L'enregistrement EMR_FRAMERGN dessine une bordure autour de la région spécifiée à l'aide du pinceau spécifié. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | L'enregistrement EMR_GLSBOUNDEDRECORD spécifie une fonction OpenGL avec un rectangle de délimitation pour la sortie. |
| [EmfGlsRecord](./emfglsrecord) | L'enregistrement EMR_GLSRECORD spécifie une fonction OpenGL. |
| [EmfGradientFill](./emfgradientfill) | L'enregistrement EMR_GRADIENTFILL spécifie le remplissage de rectangles ou de triangles avec des dégradés de couleur. |
| [EmfIntersectClipRect](./emfintersectcliprect) | L'enregistrement EMR_INTERSECTCLIPRECT spécifie une nouvelle région de découpage à partir de l'intersection de la région de découpage actuelle et du rectangle spécifié. Remarque Les champs qui ne sont pas décrits dans cette section sont spécifiés dans la section 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn) | L'enregistrement EMR_INVERTRGN inverse les couleurs dans la région spécifiée. |
| [EmfLineTo](./emflineto) | L'enregistrement EMR_LINETO spécifie une ligne à partir de la position actuelle jusqu'au point spécifié , mais sans l'inclure. Il réinitialise la position actuelle au point spécifié. |
| [EmfMaskBlt](./emfmaskblt) | L'enregistrement EMR_MASKBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau et avec l'application d'un masque de couleur bitmap, selon les opérations de raster de premier plan et d'arrière-plan spécifiées. |
| [EmfMetafileHeader](./emfmetafileheader) | Les types d'enregistrement EMR_HEADER définissent les points de départ des métafichiers EMF et spécifient les propriétés de l'appareil sur lequel l'image dans le métafichier a été créée. Les informations contenues dans l'enregistrement d'en-tête permettent aux métafichiers EMF d'être indépendants de tout périphérique de sortie spécifique. La valeur du champ Taille peut être utilisée pour distinguer les différents types d'enregistrement EMR_HEADER répertoriés plus haut dans cette section. Il existe trois possibilités headers : L'en-tête de base, qui est l'enregistrement EmfMetafileHeader. La partie à taille fixe de cet en-tête est de 88 octets et contient un objet Header. Le premier en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension1. La partie à taille fixe partie de cet en-tête est de 100 octets et contient un objet Header et un objet HeaderExtension1 (section 2.2.10). Le deuxième en-tête d'extension, qui est l'enregistrement EmfMetafileHeaderExtension2. La partie à taille fixe de cet en-tête est de 108 octets, et il contient un objet Header, un objet HeaderExtension1 et un objet HeaderExtension2 (section 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | L'enregistrement EmfMetafileHeaderExtension1 est l'enregistrement d'en-tête utilisé dans la première extension des métafichiers EMF. Après le champ EmfHeaderExtension1, les champs restants sont facultatifs et peuvent être présents dans n'importe quel ordre. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | L'enregistrement EmfMetafileHeaderExtension2 est l'enregistrement d'en-tête utilisé dans la deuxième extension des métafichiers EMF . Après le champ EmfHeaderExtension2, les champs restants sont facultatifs et peuvent être présents dans n'importe quel ordre. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | L'enregistrement EMR_MODIFYWORLDTRANSFORM modifie la transformation actuelle de l'espace mondial en espace de page dans le contexte du périphérique de lecture. |
| [EmfMoveToEx](./emfmovetoex) | L'enregistrement EMR_MOVETOEX spécifie les coordonnées de la nouvelle position actuelle, en unités logiques. |
| [EmfNamedEscape](./emfnamedescape) | L'enregistrement MR_NAMEDESCAPE transmet des informations arbitraires à un pilote d'imprimante spécifié. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | Les types d'enregistrement de création d'objet créent des objets graphiques. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | Les types d'enregistrement de manipulation d'objet gèrent et modifient les objets graphiques. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | L'enregistrement EMR_OFFSETCLIPRGN déplace la région de découpage actuelle dans le contexte du périphérique de lecture par les décalages spécifiés. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | Les types d'enregistrement OpenGL spécifient les fonctions OpenGL. |
| [EmfPaintRgn](./emfpaintrgn) | L'enregistrement EMR_PAINTRGN peint la région spécifiée à l'aide du pinceau actuellement sélectionné dans le contexte de périphérique de lecture . |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | Les types d'enregistrements entre crochets de chemin spécifient et manipulent les chemins entre crochets de chemin. Remarque : Aucun des enregistrements de crochet de chemin ne spécifie de paramètres. |
| [EmfPie](./emfpie) | L'enregistrement EMR_PIE spécifie un coin en forme de tarte délimité par l'intersection d'une ellipse et de deux radiales . Le secteur est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel. |
| [EmfPixelFormat](./emfpixelformat) | L'enregistrement EMR_PIXELFORMAT spécifie le format de pixel à utiliser pour les opérations graphiques. |
| [EmfPlgBlt](./emfplgblt) | L'enregistrement EMR_PLGBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un parallélogramme de destination , avec l'application d'un bitmap de masque de couleur. |
| [EmfPolyBezier](./emfpolybezier) | L'enregistrement EMR_POLYBEZIER spécifie une ou plusieurs courbes de Bézier. |
| [EmfPolyBezier16](./emfpolybezier16) | L'enregistrement EMR_POLYBEZIER16 spécifie une ou plusieurs courbes de Bézier. Les courbes sont dessinées en utilisant la plume actuelle. |
| [EmfPolyBezierTo](./emfpolybezierto) | L'enregistrement EMR_POLYBEZIERTO spécifie une ou plusieurs courbes de Bézier en fonction de la position actuelle. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | L'enregistrement EMR_POLYBEZIERTO16 spécifie une ou plusieurs courbes de Bézier en fonction de la position actuelle. |
| [EmfPolyDraw](./emfpolydraw) | L'enregistrement EMR_POLYDRAW spécifie un ensemble de segments de ligne et de courbes de Bézier. |
| [EmfPolyDraw16](./emfpolydraw16) | L'enregistrement EMR_POLYDRAW16 spécifie un ensemble de segments de ligne et de courbes de Bézier. |
| [EmfPolygon](./emfpolygon) | L'enregistrement EMR_POLYGON spécifie un polygone composé de deux sommets ou plus reliés par lignes droites. |
| [EmfPolygon16](./emfpolygon16) | L'enregistrement EMR_POLYGON16 spécifie un polygone composé de deux sommets ou plus reliés par lignes droites. Le polygone est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel et du mode de remplissage du polygone. Le polygone est fermé automatiquement en traçant une ligne du dernier sommet au premier. |
| [EmfPolyline](./emfpolyline) | L'enregistrement EMR_POLYLINE spécifie une série de segments de ligne en reliant les points dans le tableau spécifié. |
| [EmfPolyline16](./emfpolyline16) | L'enregistrement EMR_POLYLINE16 spécifie une série de segments de ligne en reliant les points dans le tableau spécifié . |
| [EmfPolylineTo](./emfpolylineto) | L'enregistrement EMR_POLYLINETO spécifie une ou plusieurs lignes droites en fonction de la position actuelle. |
| [EmfPolylineTo16](./emfpolylineto16) | L'enregistrement EMR_POLYLINETO16 spécifie une ou plusieurs lignes droites en fonction de la position actuelle. Une ligne est tracée de la position actuelle au premier point spécifié par le champ aPoints en utilisant le stylo actuel . Pour chaque ligne supplémentaire, le dessin est effectué à partir du point d'arrivée de la ligne précédente jusqu'au point suivant spécifié par aPoints. |
| [EmfPolyPolygon](./emfpolypolygon) | L'enregistrement EMR_POLYPOLYGON spécifie une série de polygones fermés. |
| [EmfPolyPolygon16](./emfpolypolygon16) | L'enregistrement EMR_POLYPOLYGON16 spécifie une série de polygones fermés. Chaque polygone est délimité à l'aide du stylet actuel et rempli à l'aide du pinceau et du mode de remplissage de polygone actuels. Les polygones dessinés par cet enregistrement peuvent se chevaucher. |
| [EmfPolyPolyline](./emfpolypolyline) | L'enregistrement EMR_POLYPOLYLINE spécifie plusieurs séries de segments de ligne connectés. |
| [EmfPolyPolyline16](./emfpolypolyline16) | L'enregistrement EMR_POLYPOLYLINE16 spécifie plusieurs séries de segments de ligne connectés. |
| [EmfPolyTextOutA](./emfpolytextouta) | L'enregistrement EMR_POLYTEXTOUTA dessine une ou plusieurs chaînes de texte ASCII en utilisant la police et les couleurs de texte actuelles. |
| [EmfPolyTextOutW](./emfpolytextoutw) | L'enregistrement EMR_POLYTEXTOUTW dessine une ou plusieurs chaînes de texte Unicode en utilisant la police et les couleurs de texte actuelles. |
| [EmfRealizePalette](./emfrealizepalette) | Cet enregistrement mappe les entrées de la palette de l'objet current LogPalette (section 2.2.17) à la system_palette. Cet enregistrement EMF ne spécifie aucun paramètre. |
| [EmfRecord](./emfrecord) | Classe de base pour les enregistrements EMF Tous les enregistrements EMF DOIVENT avoir une longueur qui est un multiple de 4 octets. Ceci est illustré dans les structures génériques des types d'enregistrements EMF précédents en incluant les champs AlignmentPadding , le cas échéant, aux extrémités de ces structures. Le contenu de AlignmentPadding fields DOIT toujours être ignoré. Par souci de concision, ces champs ne sont pas affichés dans chaque définition d'enregistrement EMF . |
| [EmfRectangle](./emfrectangle) | L'enregistrement EMR_RECTANGLE dessine un rectangle. Le rectangle est délimité à l'aide du stylo actuel et rempli à l'aide du pinceau actuel. |
| [EmfResizePalette](./emfresizepalette) | L'enregistrement EMR_RESIZEPALETTE augmente ou diminue la taille d'un objet LogPalette existant (section 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | L'enregistrement EMR_RESTOREDC restaure le contexte du périphérique de lecture à l'état spécifié. Le contexte du périphérique de lecture est restauré en extrayant les informations d'état d'une pile qui a été créée par les enregistrements EMR_SAVEDC précédents (section 2.3.11). |
| [EmfRop4](./emfrop4) | Une opération raster quaternaire, qui spécifie les opérations raster ternaires pour les couleurs de premier plan et d'arrière-plan d'un bitmap. Ces valeurs définissent comment les données de couleur de le rectangle source doivent être combinées avec les données de couleur du rectangle de destination. |
| [EmfRoundRect](./emfroundrect) | L'enregistrement EMR_ROUNDRECT spécifie un rectangle avec des coins arrondis. Le rectangle est délimité à l'aide du stylet actuel et rempli à l'aide du pinceau actuel. |
| [EmfSaveDc](./emfsavedc) | Enregistre l'état actuel du contexte de périphérique de lecture sur une pile d'états enregistrés par les enregistrements EMR_SAVEDC précédents, le cas échéant. L'état se compose de propriétés graphiques et d'objets, y compris le bitmap actuellement sélectionné, le pinceau , la palette, la police, le stylo et la région. Un enregistrement EMR_RESTOREDC est utilisé pour restaurer l'état. Cet enregistrement EMF ne spécifie aucun paramètre. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | L'enregistrement EMR_SCALEVIEWPORTEXTEX respécifie la fenêtre d'affichage pour un contexte de périphérique en utilisant les ratios formés par les multiplicandes et diviseurs spécifiés. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | L'enregistrement EMR_SCALEWINDOWEXTEX respécifie la fenêtre d'un contexte de périphérique de lecture en en utilisant les rapports formés par les multiplicandes et diviseurs spécifiés. |
| [EmfSelectClipPath](./emfselectclippath) | L'enregistrement EMR_SELECTCLIPPATH spécifie le chemin actuel en tant que région de découpage pour un contexte de périphérique de lecture , combinant la nouvelle région avec toute région de découpage existante en utilisant le mode spécifié. |
| [EmfSelectObject](./emfselectobject) | L'enregistrement EMR_SELECTOBJECT ajoute un objet graphique au contexte actuel de périphérique de lecture du métafichier . L'objet est spécifié soit par son index dans la table d'objets EMF (section 3.1.1.1) soit par sa valeur de l'énumération StockObject (section 2.1.31). |
| [EmfSelectPalette](./emfselectpalette) | L'enregistrement EMR_SELECTPALETTE spécifie une palette logique pour le contexte du périphérique de lecture. |
| [EmfSetArcDirection](./emfsetarcdirection) | L'enregistrement EMR_SETARCDIRECTION spécifie la direction de dessin à utiliser pour la sortie d'arc et de rectangle. |
| [EmfSetBkColor](./emfsetbkcolor) | L'enregistrement EMR_SETBKCOLOR spécifie la couleur d'arrière-plan. |
| [EmfSetBkMode](./emfsetbkmode) | L'enregistrement EMR_SETBKMODE spécifie le mode de mélange d'arrière-plan du contexte du périphérique de lecture. Le mode de mélange d'arrière-plan est utilisé avec du texte, des pinceaux hachurés et des styles de stylo qui ne sont pas des lignes pleines. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | L'enregistrement EMR_SETBRUSHORGEX spécifie l'origine du pinceau actuel. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | L'enregistrement EMR_SETCOLORADJUSTMENT spécifie les propriétés de réglage des couleurs dans le contexte de l'appareil playback . |
| [EmfSetColorSpace](./emfsetcolorspace) | L'enregistrement EMR_SETCOLORSPACE définit l'objet d'espace colorimétrique logique actuel pour les opérations graphiques. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | L'enregistrement EMR_SETDIBITSTODEVICE spécifie un transfert en bloc de pixels à partir de lignes de balayage spécifiées de une image bitmap source vers un rectangle de destination. |
| [EmfSetIcmMode](./emfseticmmode) | L'enregistrement EMR_SETICMMODE spécifie le mode de gestion des couleurs d'image (ICM) pour les opérations graphiques. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | L'enregistrement EMR_SETICMPROFILEA spécifie un profil de couleur dans un fichier dont le nom est composé de caractères ASCII , pour la sortie graphique. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | L'enregistrement EMR_SETICMPROFILEW spécifie un profil de couleur dans un fichier dont le nom est composé de caractères Unicode, pour la sortie graphique. |
| [EmfSetLayout](./emfsetlayout) | L'enregistrement EMR_SETLAYOUT spécifie l'ordre dans lequel le texte et les graphiques sont dessinés. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | L'enregistrement EMR_SETLINKEDUFIS définit les UniversalFontIds (section 2.2.27) des polices liées à utiliser lors de la recherche de caractères. |
| [EmfSetMapMode](./emfsetmapmode) | L'enregistrement EMR_SETMAPMODE spécifie le mode de mappage du contexte de périphérique de lecture. Le mode de mappage spécifie l'unité de mesure utilisée pour transformer les unités d'espace de page en unités d'espace de périphérique, et spécifie également l'orientation des axes x et y du périphérique. |
| [EmfSetMapperFlags](./emfsetmapperflags) | L'enregistrement EMR_SETMAPPERFLAGS spécifie les paramètres du processus de mise en correspondance des polices logiques avec les polices physiques , qui est effectué par le mappeur de polices. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter définit la méta-région actuelle avec la région de découpage actuelle pour former une nouvelle méta-région pour le contexte du périphérique de lecture. La région de découpage actuelle DEVRAIT être réinitialisée à null. Cet enregistrement EMF ne spécifie aucun paramètre. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | L'enregistrement EMR_SETMITERLIMIT spécifie la limite de longueur des jointures en onglet pour le contexte du périphérique de lecture. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | L'enregistrement EMR_SETPALETTEENTRIES définit les valeurs de couleur RVB dans une plage d'entrées pour un objet LogPalette existant (section 2.2.17). |
| [EmfSetPixelV](./emfsetpixelv) | L'enregistrement EMR_SETPIXELV définit la couleur du pixel aux coordonnées logiques spécifiées. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | L'enregistrement EMR_SETPOLYFILLMODE définit le mode de remplissage du polygone. |
| [EmfSetRop2](./emfsetrop2) | L'enregistrement EMR_SETROP2 définit un mode de fonctionnement raster binaire. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | L'enregistrement EMR_SETSTRETTCHBLTMODE spécifie le mode d'étirement bitmap. |
| [EmfSetTextAlign](./emfsettextalign) | L'enregistrement EMR_SETTEXTALIGN spécifie l'alignement du texte. |
| [EmfSetTextColor](./emfsettextcolor) | L'enregistrement EMR_SETTEXTCOLOR définit la couleur actuelle du texte. |
| [EmfSetTextJustification](./emfsettextjustification) | L'enregistrement EMR_SETTEXTJUSTIFICATION spécifie la quantité d'espace supplémentaire à ajouter aux caractères break pour la justification du texte. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | L'enregistrement EMR_SETVIEWPORTEXTEX définit l'étendue de la fenêtre. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | L'enregistrement EMR_SETVIEWPORTORGEX définit l'origine de la fenêtre. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | L'enregistrement EMR_SETWINDOWEXTEX définit l'étendue de la fenêtre. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | L'enregistrement EMR_SETWINDOWORGEX définit l'origine de la fenêtre. |
| [EmfSetWorldTransform](./emfsetworldtransform) | L'enregistrement EMR_SETWORLDTRANSFORM spécifie une transformation pour la transformation actuelle de l'espace universel en espace de page dans le contexte du périphérique de lecture. |
| [EmfSmallTextOut](./emfsmalltextout) | L'enregistrement EMR_SMALLTEXTOUT génère une chaîne. |
| [EmfStateRecordType](./emfstaterecordtype) | Les types d'enregistrement d'état spécifient et gèrent les propriétés graphiques qui définissent l'état du contexte du périphérique de lecture. |
| [EmfStretchBlt](./emfstretchblt) | L'enregistrement EMR_STRETCHBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire . |
| [EmfStretchDiBits](./emfstretchdibits) | L'enregistrement EMR_STRETCHDIBITS spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , éventuellement en combinaison avec un motif de pinceau, selon une opération raster spécifiée, étirant ou comprimant la sortie pour l'adapter aux dimensions de la destination, si nécessaire. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | L'enregistrement EMR_STROKEANDFILLPATH ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin the en utilisant le stylo actuel et remplit son intérieur en utilisant le pinceau actuel. |
| [EmfStrokePath](./emfstrokepath) | classe EMR_STROKEPATH |
| [EmfTransformRecordType](./emftransformrecordtype) | Les types d'enregistrement de transformation spécifient et modifient les transformations de l'espace mondial en espace de page. |
| [EmfTransparentBlt](./emftransparentblt) | L'enregistrement EMR_TRANSPARENTBLT spécifie un transfert en bloc de pixels d'un bitmap source vers un rectangle de destination , traitant une couleur spécifiée comme transparente, étirant ou compressant la sortie pour l'adapter aux dimensions de la destination, si nécessaire |
| [EmfVertexData](./emfvertexdata) | Objets qui spécifient les sommets de rectangles ou de triangles et les couleurs qui leur correspondent. |
| [EmfWidenPath](./emfwidenpath) | Cet enregistrement redéfinit le chemin actuel comme la zone qui serait peinte si le chemin était dessiné à l'aide du stylet actuellement sélectionné dans le contexte du périphérique de lecture. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
