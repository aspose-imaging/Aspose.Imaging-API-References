---
title: "Énumération EmfPlusRecordType"
type: docs
weight: 360
url: /fr/python-net/aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---

L'énumération RecordType définit les types d'enregistrements utilisés dans les métafichiers EMF+.

**Module:** [aspose.imaging.fileformats.emf.emfplus.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emfplus.consts.EmfPlusRecordType

## **Members**
| **Nom du membre** | **Description** |
| :- | :- |
| EMF_PLUS_BEGIN_CONTAINER | Cet enregistrement ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui‑ci. Les conteneurs graphiques sont utilisés pour conserver les éléments de l'état graphique. |
| EMF_PLUS_BEGIN_CONTAINER_NO_PARAMS | Cet enregistrement ouvre un nouveau conteneur d'état graphique. |
| EMF_PLUS_CLEAR | Cet enregistrement efface l'<c>espace de coordonnées</c> de sortie et l'initialise avec une couleur d'arrière‑plan et une transparence spécifiées. |
| EMF_PLUS_COMMENT | Cet enregistrement spécifie des données privées arbitraires. |
| EMF_PLUS_DRAW_ARC | L'enregistrement définit les traits du crayon pour dessiner un arc d'une ellipse. |
| EMF_PLUS_DRAW_BEZIERS | Cet enregistrement définit les traits du crayon pour dessiner une courbe de Bézier. |
| EMF_PLUS_DRAW_CLOSED_CURVE | Cet enregistrement définit le crayon et les traits pour dessiner une spline cardinal fermée. |
| EMF_PLUS_DRAW_CURVE | Cet enregistrement définit les traits du crayon pour dessiner une spline cardinal. |
| EMF_PLUS_DRAW_DRIVER_STRING | Cet enregistrement spécifie la sortie de texte avec les positions des caractères. |
| EMF_PLUS_DRAW_ELLIPSE | Cet enregistrement définit les traits du crayon pour dessiner une ellipse. |
| EMF_PLUS_DRAW_IMAGE | Cet enregistrement définit un objet [EmfPlusImage](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage/) mis à l'échelle (section 2.2.1.4). Une image peut être constituée de données bitmap ou de métafichier. |
| EMF_PLUS_DRAW_IMAGE_POINTS | Cet enregistrement définit un objet EmfPlusImage mis à l'échelle à l'intérieur d'un parallélogramme. Une image peut être constituée de données bitmap ou de métafichier. |
| EMF_PLUS_DRAW_LINES | Cet enregistrement définit les traits du crayon pour dessiner une série de lignes connectées. |
| EMF_PLUS_DRAW_PATH | L'enregistrement définit les traits de crayon pour dessiner les figures dans un chemin graphique. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes. |
| EMF_PLUS_DRAW_PIE | Cet enregistrement définit les traits de crayon pour dessiner une section d'une ellipse. |
| EMF_PLUS_DRAW_RECTS | Cet enregistrement définit les traits de crayon pour dessiner une série de rectangles. |
| EMF_PLUS_DRAW_STRING | Cet enregistrement définit une chaîne de texte basée sur une police, un rectangle de mise en page et un format. |
| EMF_PLUS_END_CONTAINER | Cet enregistrement ferme un conteneur d'état graphique qui avait été précédemment ouvert par une opération de début de conteneur. |
| EMF_PLUS_END_OF_FILE | Cet enregistrement spécifie la fin des données EMF+ dans le métafichier. |
| EMF_PLUS_FILL_CLOSED_CURVE | Cet enregistrement définit comment remplir l'intérieur d'une spline cardinal fermée à l'aide d'un pinceau spécifié. |
| EMF_PLUS_FILL_ELLIPSE | Cet enregistrement définit comment remplir l'intérieur d'une ellipse, à l'aide d'un pinceau spécifié. |
| EMF_PLUS_FILL_PATH | L'enregistrement définit comment remplir l'intérieur des figures définies dans un chemin graphique avec un pinceau spécifié. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes. |
| EMF_PLUS_FILL_PIE | Cet enregistrement définit comment remplir une section d'une partie intérieure d'une ellipse à l'aide d'un pinceau spécifié. |
| EMF_PLUS_FILL_POLYGON | Cet enregistrement définit les données pour remplir l'intérieur d'un polygone, à l'aide d'un pinceau spécifié. |
| EMF_PLUS_FILL_RECTS | Cet enregistrement définit comment remplir l'intérieur d'une série de rectangles, à l'aide d'un pinceau spécifié. |
| EMF_PLUS_FILL_REGION | Cet enregistrement définit comment remplir l'intérieur d'une région à l'aide d'un pinceau spécifié. |
| EMF_PLUS_GET_DC | Cet enregistrement spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DOIVENT être traités. Les enregistrements EMF cessent d'être traités lorsque le prochain enregistrement EMF+ est rencontré. |
| EMF_PLUS_HEADER | Cet enregistrement spécifie le début des données EMF+ dans le métafichier. Il DOIT être intégré dans le premier enregistrement EMF après l'enregistrement [EmfMetafileHeader](/imaging/python-net/aspose.imaging.fileformats.emf.emf.records/emfmetafileheader/) ([MS-EMF] section 2.3.4.2 enregistrement). |
| EMF_PLUS_MULTIPLY_WORLD_TRANSFORM | Cet enregistrement multiplie l'espace mondial actuel par une matrice de transformation spécifiée. |
| EMF_PLUS_MULTI_FORMAT_END | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EMF_PLUS_MULTI_FORMAT_SECTION | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EMF_PLUS_MULTI_FORMAT_START | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| EMF_PLUS_OBJECT | Cet enregistrement spécifie un objet à utiliser dans les opérations graphiques. |
| EMF_PLUS_OFFSET_CLIP | Cet enregistrement applique une transformation de translation sur la région de découpage actuelle de l'espace mondial. |
| EMF_PLUS_RESET_CLIP | Cet enregistrement réinitialise la région de découpage actuelle de l'espace mondial à l'infini. |
| EMF_PLUS_RESET_WORLD_TRANSFORM | Cet enregistrement réinitialise la transformation actuelle de l'espace mondial à la matrice identité. |
| EMF_PLUS_RESTORE | Cet enregistrement restaure l'état graphique, identifié par un index spécifié, à partir d'une pile d'états graphiques enregistrés. Chaque index de pile est associé à un état enregistré particulier, et l'index est défini par un enregistrement [EmfPlusSave](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplussave/) (section 2.3.7.5) pour enregistrer l'état. |
| EMF_PLUS_ROTATE_WORLD_TRANSFORM | Cet enregistrement fait pivoter l'espace mondial actuel d'un angle spécifié. |
| EMF_PLUS_SAVE | Cet enregistrement enregistre l'état graphique, identifié par un index spécifié, sur une pile d'états graphiques enregistrés. Chaque index de pile est associé à un état enregistré particulier, et l'index est utilisé par un enregistrement [EmfPlusRestore](/imaging/python-net/aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore/) (section 2.3.7.4) pour restaurer l'état. |
| EMF_PLUS_SCALE_WORLD_TRANSFORM | Cet enregistrement applique une transformation d'échelle à l'espace mondial actuel à l'aide de facteurs d'échelle horizontaux et verticaux spécifiés. |
| EMF_PLUS_SERIALIZABLE_OBJECT | Cet enregistrement définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données. |
| EMF_PLUS_SET_ANTI_ALIAS_MODE | Cet enregistrement définit s'il faut activer ou désactiver l'anticrénelage du texte. L'anticrénelage du texte est une méthode permettant de rendre les lignes et les bords des glyphes de caractères plus lisses lorsqu'ils sont dessinés sur une surface de sortie. |
| EMF_PLUS_SET_CLIP_PATH | Cet enregistrement combine la région de découpage actuelle avec un chemin graphique. |
| EMF_PLUS_SET_CLIP_RECT | Cet enregistrement combine la région de découpage actuelle avec un rectangle. |
| EMF_PLUS_SET_CLIP_REGION | Cet enregistrement combine la région de découpage actuelle avec une autre région graphique. |
| EMF_PLUS_SET_COMPOSITING_MODE | Cet enregistrement définit le mode de composition en fonction de l'état du mélange alpha, qui spécifie comment les couleurs source sont combinées avec les couleurs d'arrière-plan. |
| EMF_PLUS_SET_COMPOSITING_QUALITY | Cet enregistrement définit la qualité de composition, qui décrit le niveau de qualité souhaité pour créer des images composites à partir de plusieurs objets. |
| EMF_PLUS_SET_INTERPOLATION_MODE | Cet enregistrement définit le mode d'interpolation d'un objet en fonction du type de filtrage d'image spécifié. Le mode d'interpolation influence la façon dont le redimensionnement (étirement et réduction) est effectué. |
| EMF_PLUS_SET_PAGE_TRANSFORM | Cet enregistrement spécifie des facteurs d'échelle supplémentaires pour la transformation de l'espace mondial actuel. |
| EMF_PLUS_SET_PIXEL_OFFSET_MODE | Cet enregistrement définit le mode de décalage des pixels en fonction de la valeur de centrage des pixels spécifiée. |
| EMF_PLUS_SET_RENDERING_ORIGIN | Cet enregistrement définit l'origine du rendu aux coordonnées horizontales et verticales spécifiées. Cela s'applique aux pinceaux hachurés et aux motifs de tramage de 8 et 16 bits par pixel. |
| EMF_PLUS_SET_TEXT_CONTRAST | Cet enregistrement définit le contraste du texte en fonction de la valeur gamma du texte spécifiée. |
| EMF_PLUS_SET_TEXT_RENDERING_HINT | Cet enregistrement définit le processus utilisé pour le rendu du texte. |
| EMF_PLUS_SET_TS_CLIP | Cet enregistrement spécifie les zones de rognage dans le contexte du dispositif graphique pour un serveur terminal. |
| EMF_PLUS_SET_TS_GRAPHICS | Cet enregistrement spécifie l'état du contexte du dispositif graphique pour un serveur terminal. |
| EMF_PLUS_SET_WORLD_TRANSFORM | Cet enregistrement définit la transformation de l'espace mondial actuelle dans le device_context de lecture, selon une matrice de transformation spécifiée. |
| EMF_PLUS_STROKE_FILL_PATH | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel, et remplit son intérieur en utilisant la brosse actuelle. |
| EMF_PLUS_TRANSLATE_WORLD_TRANSFORM | Cet enregistrement applique une transformation de translation à l'espace mondial actuel selon des distances horizontales et verticales spécifiées. |
