---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lespace de noms contient des types MS-EMFPLUS  Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 390
url: /fr/net/aspose.imaging.fileformats.emf.emfplus.records/
---
L'espace de noms contient des types [MS-EMFPLUS] : Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Des classes

| Classer | La description |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | L'enregistrement EmfPlusBeginContainer ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | L'enregistrement EmfPlusBeginContainerNoParams ouvre un nouveau conteneur d'état graphique. |
| [EmfPlusClear](./emfplusclear) | L'enregistrement EmfPlusClear efface l'espace de coordonnées de sortie et l'initialise avec une couleur d'arrière-plan et une transparence |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | Les types d'enregistrements de découpage spécifient les régions et les opérations de découpage. |
| [EmfPlusComment](./emfpluscomment) | L'enregistrement EmfPlusComment spécifie des données privées arbitraires. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | Les types d'enregistrement de contrôle spécifient les paramètres globaux pour le traitement du métafichier EMF+. |
| [EmfPlusDrawArc](./emfplusdrawarc) | L'enregistrement EmfPlusDrawArc spécifie le dessin de l'arc d'une ellipse. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | L'enregistrement EmfPlusDrawBeziers spécifie le dessin d'une séquence de courbes de Bézier connectées. L'ordre des points de données de Bézier est le point de départ, le point de contrôle 1, le point de contrôle 2 et le point final. Pour plus d'informations, consultez [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | L'enregistrement EmfPlusDrawClosedCurve spécifie le dessin d'une spline cardinale fermée |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | L'enregistrement EmfPlusDrawCurve spécifie le dessin d'une spline cardinale REMARQUE : ObjectID (1 octet) : l'index d'un objet EmfPlusPen (section 2.2.1.7) dans la table d'objets EMF+ pour dessiner la courbe. La valeur DOIT être de zéro à 63, inclus. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | L'enregistrement EmfPlusDrawDriverString spécifie une sortie de texte avec des positions de caractères. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | L'enregistrement EmfPlusDrawEllipse spécifie le dessin d'une ellipse. |
| [EmfPlusDrawImage](./emfplusdrawimage) | L'enregistrement EmfPlusDrawImage spécifie le dessin d'une image à l'échelle. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | L'enregistrement EmfPlusDrawImagePoints spécifie le dessin d'une image à l'échelle à l'intérieur d'un parallélogramme. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | Les types d'enregistrement de dessin spécifient la sortie graphique. |
| [EmfPlusDrawLines](./emfplusdrawlines) | L'enregistrement EmfPlusDrawlLines spécifie le dessin d'une série de lignes connectées |
| [EmfPlusDrawPath](./emfplusdrawpath) | L'enregistrement EmfPlusDrawPath spécifie le dessin d'un chemin graphique. |
| [EmfPlusDrawPie](./emfplusdrawpie) | L'enregistrement EmfPlusDrawPie spécifie le dessin d'une section de l'intérieur d'une ellipse. |
| [EmfPlusDrawRects](./emfplusdrawrects) | L'enregistrement EmfPlusDrawRects spécifie le dessin d'une série de rectangles |
| [EmfPlusDrawString](./emfplusdrawstring) | L'enregistrement EmfPlusDrawString spécifie la sortie de texte avec le formatage de chaîne |
| [EmfPlusEndContainer](./emfplusendcontainer) | L'enregistrement EmfPlusEndContainer ferme un conteneur d'état graphique qui a été précédemment ouvert par une opération de début de conteneur. |
| [EmfPlusEndOfFile](./emfplusendoffile) | L'enregistrement EmfPlusEndOfFile spécifie la fin des données EMF+ dans le métafichier. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | L'enregistrement EmfPlusFillClosedCurve spécifie le remplissage de l'intérieur d'une spline cardinale fermée |
| [EmfPlusFillEllipse](./emfplusfillellipse) | L'enregistrement EmfPlusFillEllipse spécifie le remplissage de l'intérieur d'une ellipse |
| [EmfPlusFillPath](./emfplusfillpath) | Fill path record FLAGS : Entier non signé de 16 bits qui fournit des informations sur la façon dont l'opération doit être effectuée, et sur la structure de l'enregistrement. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 bit) : Ce bit indique le type de données dans le champ BrushId. S'il est défini, BrushId spécifie une couleur en tant qu'objet EmfPlusARGB (section 2.2.2.1). S'il est clair, BrushId contient l'index d'un objet EmfPlusBrush (section 2.2.1.1) dans la table d'objets EMF+. X (1 bit) : réservé et DOIT être ignoré. ObjectId (1 octet) : l'index de l'objet EmfPlusPath ( section 2.2.1.6) à remplir, dans la table d'objets EMF+. La valeur DOIT être de zéro à 63, inclus. |
| [EmfPlusFillPie](./emfplusfillpie) | L'enregistrement EmfPlusFillPie spécifie le remplissage d'une section de l'intérieur d'une ellipse |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | L'enregistrement EmfPlusFillPolygon spécifie le remplissage de l'intérieur d'un polygone. |
| [EmfPlusFillRects](./emfplusfillrects) | L'enregistrement EmfPlusFillRects spécifie le remplissage de l'intérieur d'une série de rectangles |
| [EmfPlusFillRegion](./emfplusfillregion) | L'enregistrement EmfPlusFillRegion spécifie le remplissage de l'intérieur d'une région graphique |
| [EmfPlusGetDc](./emfplusgetdc) | L'enregistrement EmfPlusGetDC spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DEVRAIENT être traités. |
| [EmfPlusHeader](./emfplusheader) | L'enregistrement EmfPlusHeader spécifie le début des données EMF+ dans le métafichier. L'enregistrement EmfPlusHeader DOIT être intégré dans un enregistrement EMF EMR_COMMENT_EMFPLUS, qui DOIT être l'enregistrement suivant immédiatement l'en-tête EMF dans le métafichier. L'enregistrement EMR_COMMENT_EMFPLUS est spécifié dans [MS-EMF] section 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | L'enregistrement EmfPlusMultiplyWorldTransform multiplie la transformation de l'espace univers actuel par une matrice de transformation spécifiée. |
| [EmfPlusObject](./emfplusobject) | L'enregistrement EmfPlusObject spécifie un objet à utiliser dans les opérations graphiques. L'objet definition peut s'étendre sur plusieurs enregistrements, ce qui est indiqué par la valeur du champ Flags. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | Les types d'enregistrement d'objet définissent des objets graphiques réutilisables. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | L'enregistrement EmfPlusOffsetClip applique une transformation de traduction sur la région de découpage actuelle pour l'espace univers. La nouvelle région de découpage actuelle est définie sur le résultat de la transformation de traduction. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | Les types d'enregistrement de propriété spécifient les propriétés du contexte de périphérique de lecture. |
| [EmfPlusRecord](./emfplusrecord) | Le type d'enregistrement de base Emf+. |
| [EmfPlusResetClip](./emfplusresetclip) | L'enregistrement EmfPlusResetClip réinitialise la région de découpage actuelle pour l'espace mondial à l'infini. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | L'enregistrement EmfPlusResetWorldTransform réinitialise la transformation de l'espace mondial actuel sur la matrice d'identification. |
| [EmfPlusRestore](./emfplusrestore) | L'enregistrement EmfPlusRestore restaure l'état graphique, identifié par un index spécifié, à partir d'une pile d'états graphiques enregistrés. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | L'enregistrement EmfPlusRotateWorldTransform effectue une rotation sur la transformation de l'espace mondial actuel. |
| [EmfPlusSave](./emfplussave) | L'enregistrement EmfPlusSave enregistre l'état graphique, identifié par un index spécifié, sur une pile d'états graphiques enregistrés. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | L'enregistrement EmfPlusScaleWorldTransform effectue une mise à l'échelle sur la transformation de l'espace mondial actuel. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | L'enregistrement EmfPlusSerializableObject définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | L'enregistrement EmfPlusSetAntiAliasMode spécifie le mode d'anticrénelage pour la sortie de texte. |
| [EmfPlusSetClipPath](./emfplussetclippath) | L'enregistrement EmfPlusSetClipPath combine la zone de découpage actuelle avec un chemin graphique. La nouvelle région de découpage actuelle est définie sur le résultat de l'opération CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | L'enregistrement EmfPlusSetClipRect combine la zone de découpage actuelle avec un rectangle. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | L'enregistrement EmfPlusSetClipRegion combine la région de découpage actuelle avec une autre région graphique. La nouvelle région de découpage actuelle est définie sur le résultat de l'exécution de l'opération CombineMode sur la région de découpage actuelle précédente et l'objet EmfPlusRegion spécifié. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | L'enregistrement EmfPlusSetCompositingMode spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | L'enregistrement EmfPlusSetCompositingQuality spécifie le niveau de qualité souhaité pour la création d'images composites à partir de plusieurs objets. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | L'enregistrement EmfPlusSetInterpolationMode spécifie comment la mise à l'échelle de l'image, y compris l'étirement et la réduction, est effectuée. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | L'enregistrement EmfPlusSetPageTransform spécifie les facteurs et les unités de mise à l'échelle pour convertir les coordonnées de l'espace de la page en coordonnées de l'espace de l'appareil. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | L'enregistrement EmfPlusSetPixelOffsetMode spécifie comment les pixels sont centrés par rapport aux coordonnées de la surface de dessin. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | L'enregistrement EmfPlusSetRenderingOrigin spécifie l'origine du rendu pour la sortie graphique. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | L'enregistrement EmfPlusSetTextContrast spécifie le contraste du texte en fonction de la valeur de correction gamma. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | L'enregistrement EmfPlusSetTextRenderingHint spécifie la qualité du rendu du texte, y compris le type d'anticrénelage. |
| [EmfPlusSetTsClip](./emfplussettsclip) | L'enregistrement EmfPlusSetTSClip spécifie les zones de découpage dans le contexte du périphérique graphique pour un serveur Terminal Server. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | L'enregistrement EmfPlusSetTSGraphics spécifie l'état d'un contexte de périphérique graphique pour un serveur Terminal Server. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | L'enregistrement EmfPlusSetWorldTransform définit la transformation du monde en fonction des valeurs d'une matrice de transformation spécifiée. |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | Les types d'enregistrement d'état spécifient les opérations sur l'état du contexte du périphérique de lecture. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | Les types d'enregistrements Terminal Server spécifient le traitement graphique sur un serveur Terminal Server. Les suivants sont des types d'enregistrements de serveur de terminal EMF+. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | Les types d'enregistrement de transformation spécifient les propriétés et les transformations sur les espaces de coordonnées. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | L'enregistrement EmfPlusTranslateWorldTransform effectue une traduction sur la transformation de l'espace mondial actuel. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
