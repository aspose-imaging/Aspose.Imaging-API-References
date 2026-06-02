---
title: "EmfPlusRecordType"
second_title: "Référence de l'API Aspose.Imaging pour Java"
description: "L'énumération RecordType définit les types d'enregistrements utilisés dans les métafichiers EMF."
type: docs
weight: 45
url: /fr/java/com.aspose.imaging.fileformats.emf.emfplus.consts/emfplusrecordtype/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType, com.aspose.ms.System.Enum
```
public final class EmfPlusRecordType extends System.Enum
```

L'énumération RecordType définit les types d'enregistrements utilisés dans les métafichiers EMF+.
## Champs

| Champ | Description |
| --- | --- |
| [EmfPlusHeader](#EmfPlusHeader) | Cet enregistrement spécifie le début des données EMF+ dans le métafichier. |
| [EmfPlusEndOfFile](#EmfPlusEndOfFile) | Cet enregistrement spécifie la fin des données EMF+ dans le métafichier. |
| [EmfPlusComment](#EmfPlusComment) | Cet enregistrement spécifie des données privées arbitraires. |
| [EmfPlusGetDC](#EmfPlusGetDC) | Cet enregistrement spécifie que les enregistrements EMF suivants rencontrés dans le métafichier DOIVENT être traités. |
| [EmfPlusMultiFormatStart](#EmfPlusMultiFormatStart) | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| [EmfPlusMultiFormatSection](#EmfPlusMultiFormatSection) | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| [EmfPlusMultiFormatEnd](#EmfPlusMultiFormatEnd) | Cet enregistrement est réservé et NE DOIT PAS être utilisé. |
| [EmfPlusObject](#EmfPlusObject) | Cet enregistrement spécifie un objet à utiliser dans les opérations graphiques. |
| [EmfPlusClear](#EmfPlusClear) | Cet enregistrement efface l'`coordinate space` de sortie et l'initialise avec une couleur d'arrière-plan et une transparence spécifiées. |
| [EmfPlusFillRects](#EmfPlusFillRects) | Cet enregistrement définit comment remplir l'intérieur d'une série de rectangles, en utilisant un pinceau spécifié. |
| [EmfPlusDrawRects](#EmfPlusDrawRects) | Cet enregistrement définit les traits du crayon pour dessiner une série de rectangles. |
| [EmfPlusFillPolygon](#EmfPlusFillPolygon) | Cet enregistrement définit les données pour remplir l'intérieur d'un polygone, en utilisant un pinceau spécifié. |
| [EmfPlusDrawLines](#EmfPlusDrawLines) | Cet enregistrement définit les traits du crayon pour dessiner une série de lignes connectées. |
| [EmfPlusFillEllipse](#EmfPlusFillEllipse) | Cet enregistrement définit comment remplir l'intérieur d'une ellipse, en utilisant un pinceau spécifié. |
| [EmfPlusDrawEllipse](#EmfPlusDrawEllipse) | Cet enregistrement définit les traits du crayon pour dessiner une ellipse. |
| [EmfPlusFillPie](#EmfPlusFillPie) | Cet enregistrement définit comment remplir une section d'une partie intérieure d'une ellipse à l'aide d'un pinceau spécifié. |
| [EmfPlusDrawPie](#EmfPlusDrawPie) | Cet enregistrement définit les traits de crayon pour dessiner une section d'une ellipse. |
| [EmfPlusDrawArc](#EmfPlusDrawArc) | L'enregistrement définit les traits de crayon pour dessiner un arc d'une ellipse. |
| [EmfPlusFillRegion](#EmfPlusFillRegion) | Cet enregistrement définit comment remplir l'intérieur d'une région à l'aide d'un pinceau spécifié. |
| [EmfPlusFillPath](#EmfPlusFillPath) | L'enregistrement définit comment remplir les intérieurs des figures définies dans un chemin graphique avec un pinceau spécifié. |
| [EmfPlusDrawPath](#EmfPlusDrawPath) | L'enregistrement définit les traits de crayon pour dessiner les figures dans un chemin graphique. |
| [EmfPlusFillClosedCurve](#EmfPlusFillClosedCurve) | Cet enregistrement définit comment remplir l'intérieur d'une spline cardinale fermée à l'aide d'un pinceau spécifié. |
| [EmfPlusDrawClosedCurve](#EmfPlusDrawClosedCurve) | Cet enregistrement définit le crayon et les traits pour dessiner une spline cardinale fermée. |
| [EmfPlusDrawCurve](#EmfPlusDrawCurve) | Cet enregistrement définit les traits de crayon pour dessiner une spline cardinale. |
| [EmfPlusDrawBeziers](#EmfPlusDrawBeziers) | Cet enregistrement définit les traits de crayon pour dessiner une spline de Bézier. |
| [EmfPlusDrawImage](#EmfPlusDrawImage) | Cet enregistrement définit un objet [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) mis à l'échelle (section 2.2.1.4). |
| [EmfPlusDrawImagePoints](#EmfPlusDrawImagePoints) | Cet enregistrement définit un objet EmfPlusImage mis à l'échelle à l'intérieur d'un parallélogramme. |
| [EmfPlusDrawString](#EmfPlusDrawString) | Cet enregistrement définit une chaîne de texte basée sur une police, un rectangle de mise en page et un format. |
| [EmfPlusSetRenderingOrigin](#EmfPlusSetRenderingOrigin) | Cet enregistrement définit l'origine du rendu aux coordonnées horizontales et verticales spécifiées. |
| [EmfPlusSetAntiAliasMode](#EmfPlusSetAntiAliasMode) | Cet enregistrement définit s'il faut activer ou désactiver l'anticrénelage du texte. |
| [EmfPlusSetTextRenderingHint](#EmfPlusSetTextRenderingHint) | Cet enregistrement définit le processus utilisé pour le rendu du texte. |
| [EmfPlusSetTextContrast](#EmfPlusSetTextContrast) | Cet enregistrement définit le contraste du texte selon la valeur gamma du texte spécifiée. |
| [EmfPlusSetInterpolationMode](#EmfPlusSetInterpolationMode) | Cet enregistrement définit le mode d'interpolation d'un objet selon le type de filtrage d'image spécifié. |
| [EmfPlusSetPixelOffsetMode](#EmfPlusSetPixelOffsetMode) | Cet enregistrement définit le mode de décalage des pixels selon la valeur de centrage des pixels spécifiée. |
| [EmfPlusSetCompositingMode](#EmfPlusSetCompositingMode) | Cet enregistrement définit le mode de composition selon l'état du mélange alpha, qui spécifie comment les couleurs sources sont combinées avec les couleurs d'arrière-plan. |
| [EmfPlusSetCompositingQuality](#EmfPlusSetCompositingQuality) | Cet enregistrement définit la qualité de composition, qui décrit le niveau de qualité souhaité pour créer des images composites à partir de plusieurs objets. |
| [EmfPlusSave](#EmfPlusSave) | Cet enregistrement enregistre l'état graphique, identifié par un index spécifié, sur une pile d'états graphiques enregistrés. |
| [EmfPlusRestore](#EmfPlusRestore) | Cet enregistrement restaure l'état graphique, identifié par un index spécifié, depuis une pile d'états graphiques enregistrés. |
| [EmfPlusBeginContainer](#EmfPlusBeginContainer) | Cet enregistrement ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci. |
| [EmfPlusBeginContainerNoParams](#EmfPlusBeginContainerNoParams) | Cet enregistrement ouvre un nouveau conteneur d'état graphique. |
| [EmfPlusEndContainer](#EmfPlusEndContainer) | Cet enregistrement ferme un conteneur d'état graphique qui avait été précédemment ouvert par une opération de démarrage de conteneur. |
| [EmfPlusSetWorldTransform](#EmfPlusSetWorldTransform) | Cet enregistrement définit la transformation de l'espace mondial actuel dans le playback device\_context, selon une matrice de transformation spécifiée. |
| [EmfPlusResetWorldTransform](#EmfPlusResetWorldTransform) | Cet enregistrement réinitialise la transformation de l'espace mondial actuel à la matrice d'identité. |
| [EmfPlusMultiplyWorldTransform](#EmfPlusMultiplyWorldTransform) | Cet enregistrement multiplie l'espace mondial actuel par une matrice de transformation spécifiée. |
| [EmfPlusTranslateWorldTransform](#EmfPlusTranslateWorldTransform) | Cet enregistrement applique une transformation de translation à l'espace mondial actuel selon des distances horizontales et verticales spécifiées. |
| [EmfPlusScaleWorldTransform](#EmfPlusScaleWorldTransform) | Cet enregistrement applique une transformation d'échelle à l'espace mondial actuel selon des facteurs d'échelle horizontaux et verticaux spécifiés. |
| [EmfPlusRotateWorldTransform](#EmfPlusRotateWorldTransform) | Cet enregistrement fait pivoter l'espace mondial actuel d'un angle spécifié. |
| [EmfPlusSetPageTransform](#EmfPlusSetPageTransform) | Cet enregistrement spécifie des facteurs d'échelle supplémentaires pour la transformation de l'espace mondial actuel. |
| [EmfPlusResetClip](#EmfPlusResetClip) | Cet enregistrement réinitialise la région de découpage actuelle de l'espace mondial à l'infini. |
| [EmfPlusSetClipRect](#EmfPlusSetClipRect) | Cet enregistrement combine la région de découpage actuelle avec un rectangle. |
| [EmfPlusSetClipPath](#EmfPlusSetClipPath) | Cet enregistrement combine la région de découpage actuelle avec un chemin graphique. |
| [EmfPlusSetClipRegion](#EmfPlusSetClipRegion) | Cet enregistrement combine la région de découpage actuelle avec une autre région graphique. |
| [EmfPlusOffsetClip](#EmfPlusOffsetClip) | Cet enregistrement applique une transformation de translation sur la région de découpage actuelle de l'espace mondial. |
| [EmfPlusDrawDriverString](#EmfPlusDrawDriverString) | Cet enregistrement spécifie la sortie de texte avec les positions des caractères. |
| [EmfPlusStrokeFillPath](#EmfPlusStrokeFillPath) | Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel, et remplit son intérieur en utilisant le pinceau actuel. |
| [EmfPlusSerializableObject](#EmfPlusSerializableObject) | Cet enregistrement définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données. |
| [EmfPlusSetTSGraphics](#EmfPlusSetTSGraphics) | Cet enregistrement spécifie l'état d'un contexte de périphérique graphique pour un serveur terminal. |
| [EmfPlusSetTSClip](#EmfPlusSetTSClip) | Cet enregistrement spécifie les zones de découpage dans le contexte de périphérique graphique pour un serveur terminal. |
### EmfPlusHeader {#EmfPlusHeader}
```
public static final short EmfPlusHeader
```


Cet enregistrement spécifie le début des données EMF+ dans le métafichier. Il DOIT être intégré dans le premier enregistrement EMF après l'enregistrement [EmfMetafileHeader](../../com.aspose.imaging.fileformats.emf.emf.records/emfmetafileheader) ([MS-EMF] section 2.3.4.2 record).

### EmfPlusEndOfFile {#EmfPlusEndOfFile}
```
public static final short EmfPlusEndOfFile
```


Cet enregistrement spécifie la fin des données EMF+ dans le métafichier.

### EmfPlusComment {#EmfPlusComment}
```
public static final short EmfPlusComment
```


Cet enregistrement spécifie des données privées arbitraires.

### EmfPlusGetDC {#EmfPlusGetDC}
```
public static final short EmfPlusGetDC
```


Cet enregistrement indique que les enregistrements EMF suivants rencontrés dans le métafichier DOIVENT être traités. Les enregistrements EMF cessent d'être traités lorsque le prochain enregistrement EMF+ est rencontré.

### EmfPlusMultiFormatStart {#EmfPlusMultiFormatStart}
```
public static final short EmfPlusMultiFormatStart
```


Cet enregistrement est réservé et NE DOIT PAS être utilisé.

### EmfPlusMultiFormatSection {#EmfPlusMultiFormatSection}
```
public static final short EmfPlusMultiFormatSection
```


Cet enregistrement est réservé et NE DOIT PAS être utilisé.

### EmfPlusMultiFormatEnd {#EmfPlusMultiFormatEnd}
```
public static final short EmfPlusMultiFormatEnd
```


Cet enregistrement est réservé et NE DOIT PAS être utilisé.

### EmfPlusObject {#EmfPlusObject}
```
public static final short EmfPlusObject
```


Cet enregistrement spécifie un objet à utiliser dans les opérations graphiques.

### EmfPlusClear {#EmfPlusClear}
```
public static final short EmfPlusClear
```


Cet enregistrement efface l'`coordinate space` de sortie et l'initialise avec une couleur d'arrière-plan et une transparence spécifiées.

### EmfPlusFillRects {#EmfPlusFillRects}
```
public static final short EmfPlusFillRects
```


Cet enregistrement définit comment remplir l'intérieur d'une série de rectangles, en utilisant un pinceau spécifié.

### EmfPlusDrawRects {#EmfPlusDrawRects}
```
public static final short EmfPlusDrawRects
```


Cet enregistrement définit les traits du crayon pour dessiner une série de rectangles.

### EmfPlusFillPolygon {#EmfPlusFillPolygon}
```
public static final short EmfPlusFillPolygon
```


Cet enregistrement définit les données pour remplir l'intérieur d'un polygone, en utilisant un pinceau spécifié.

### EmfPlusDrawLines {#EmfPlusDrawLines}
```
public static final short EmfPlusDrawLines
```


Cet enregistrement définit les traits du crayon pour dessiner une série de lignes connectées.

### EmfPlusFillEllipse {#EmfPlusFillEllipse}
```
public static final short EmfPlusFillEllipse
```


Cet enregistrement définit comment remplir l'intérieur d'une ellipse, en utilisant un pinceau spécifié.

### EmfPlusDrawEllipse {#EmfPlusDrawEllipse}
```
public static final short EmfPlusDrawEllipse
```


Cet enregistrement définit les traits du crayon pour dessiner une ellipse.

### EmfPlusFillPie {#EmfPlusFillPie}
```
public static final short EmfPlusFillPie
```


Cet enregistrement définit comment remplir une section d'une partie intérieure d'une ellipse à l'aide d'un pinceau spécifié.

### EmfPlusDrawPie {#EmfPlusDrawPie}
```
public static final short EmfPlusDrawPie
```


Cet enregistrement définit les traits de crayon pour dessiner une section d'une ellipse.

### EmfPlusDrawArc {#EmfPlusDrawArc}
```
public static final short EmfPlusDrawArc
```


L'enregistrement définit les traits de crayon pour dessiner un arc d'une ellipse.

### EmfPlusFillRegion {#EmfPlusFillRegion}
```
public static final short EmfPlusFillRegion
```


Cet enregistrement définit comment remplir l'intérieur d'une région à l'aide d'un pinceau spécifié.

### EmfPlusFillPath {#EmfPlusFillPath}
```
public static final short EmfPlusFillPath
```


L'enregistrement définit comment remplir les intérieurs des figures définies dans un chemin graphique avec un pinceau spécifié. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes.

### EmfPlusDrawPath {#EmfPlusDrawPath}
```
public static final short EmfPlusDrawPath
```


L'enregistrement définit les traits de crayon pour dessiner les figures dans un chemin graphique. Un chemin est un objet qui définit une séquence arbitraire de lignes, de courbes et de formes.

### EmfPlusFillClosedCurve {#EmfPlusFillClosedCurve}
```
public static final short EmfPlusFillClosedCurve
```


Cet enregistrement définit comment remplir l'intérieur d'une spline cardinale fermée à l'aide d'un pinceau spécifié.

### EmfPlusDrawClosedCurve {#EmfPlusDrawClosedCurve}
```
public static final short EmfPlusDrawClosedCurve
```


Cet enregistrement définit le crayon et les traits pour dessiner une spline cardinale fermée.

### EmfPlusDrawCurve {#EmfPlusDrawCurve}
```
public static final short EmfPlusDrawCurve
```


Cet enregistrement définit les traits de crayon pour dessiner une spline cardinale.

### EmfPlusDrawBeziers {#EmfPlusDrawBeziers}
```
public static final short EmfPlusDrawBeziers
```


Cet enregistrement définit les traits de crayon pour dessiner une spline de Bézier.

### EmfPlusDrawImage {#EmfPlusDrawImage}
```
public static final short EmfPlusDrawImage
```


Cet enregistrement définit un objet [EmfPlusImage](../../com.aspose.imaging.fileformats.emf.emfplus.objects/emfplusimage) mis à l'échelle (section 2.2.1.4). Une image peut être composée de données bitmap ou de métafichier.

### EmfPlusDrawImagePoints {#EmfPlusDrawImagePoints}
```
public static final short EmfPlusDrawImagePoints
```


Cet enregistrement définit un objet EmfPlusImage mis à l'échelle à l'intérieur d'un parallélogramme. Une image peut être composée de données bitmap ou de métafichier.

### EmfPlusDrawString {#EmfPlusDrawString}
```
public static final short EmfPlusDrawString
```


Cet enregistrement définit une chaîne de texte basée sur une police, un rectangle de mise en page et un format.

### EmfPlusSetRenderingOrigin {#EmfPlusSetRenderingOrigin}
```
public static final short EmfPlusSetRenderingOrigin
```


Cet enregistrement définit l'origine du rendu aux coordonnées horizontales et verticales spécifiées. Cela s'applique aux pinceaux hachurés et aux motifs de tramage de 8 et 16 bits par pixel.

### EmfPlusSetAntiAliasMode {#EmfPlusSetAntiAliasMode}
```
public static final short EmfPlusSetAntiAliasMode
```


Cet enregistrement définit s'il faut activer ou désactiver l'anticrénelage du texte. L'anticrénelage du texte est une méthode permettant de rendre les lignes et les bords des glyphes de caractères plus lisses lorsqu'ils sont dessinés sur une surface de sortie.

### EmfPlusSetTextRenderingHint {#EmfPlusSetTextRenderingHint}
```
public static final short EmfPlusSetTextRenderingHint
```


Cet enregistrement définit le processus utilisé pour le rendu du texte.

### EmfPlusSetTextContrast {#EmfPlusSetTextContrast}
```
public static final short EmfPlusSetTextContrast
```


Cet enregistrement définit le contraste du texte selon la valeur gamma du texte spécifiée.

### EmfPlusSetInterpolationMode {#EmfPlusSetInterpolationMode}
```
public static final short EmfPlusSetInterpolationMode
```


Cet enregistrement définit le mode d'interpolation d'un objet selon le type de filtrage d'image spécifié. Le mode d'interpolation influence la façon dont le redimensionnement (étirement et réduction) est effectué.

### EmfPlusSetPixelOffsetMode {#EmfPlusSetPixelOffsetMode}
```
public static final short EmfPlusSetPixelOffsetMode
```


Cet enregistrement définit le mode de décalage des pixels selon la valeur de centrage des pixels spécifiée.

### EmfPlusSetCompositingMode {#EmfPlusSetCompositingMode}
```
public static final short EmfPlusSetCompositingMode
```


Cet enregistrement définit le mode de composition selon l'état du mélange alpha, qui spécifie comment les couleurs sources sont combinées avec les couleurs d'arrière-plan.

### EmfPlusSetCompositingQuality {#EmfPlusSetCompositingQuality}
```
public static final short EmfPlusSetCompositingQuality
```


Cet enregistrement définit la qualité de composition, qui décrit le niveau de qualité souhaité pour créer des images composites à partir de plusieurs objets.

### EmfPlusSave {#EmfPlusSave}
```
public static final short EmfPlusSave
```


Cet enregistrement enregistre l'état graphique, identifié par un index spécifié, sur une pile d'états graphiques enregistrés. Chaque index de pile est associé à un état enregistré particulier, et l'index est utilisé par un enregistrement [EmfPlusRestore](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplusrestore) (section 2.3.7.4) pour restaurer l'état.

### EmfPlusRestore {#EmfPlusRestore}
```
public static final short EmfPlusRestore
```


Cet enregistrement restaure l'état graphique, identifié par un index spécifié, à partir d'une pile d'états graphiques enregistrés. Chaque index de pile est associé à un état enregistré particulier, et l'index est défini par un enregistrement [EmfPlusSave](../../com.aspose.imaging.fileformats.emf.emfplus.records/emfplussave) (section 2.3.7.5) pour enregistrer l'état.

### EmfPlusBeginContainer {#EmfPlusBeginContainer}
```
public static final short EmfPlusBeginContainer
```


Cet enregistrement ouvre un nouveau conteneur d'état graphique et spécifie une transformation pour celui-ci. Les conteneurs graphiques sont utilisés pour conserver les éléments de l'état graphique.

### EmfPlusBeginContainerNoParams {#EmfPlusBeginContainerNoParams}
```
public static final short EmfPlusBeginContainerNoParams
```


Cet enregistrement ouvre un nouveau conteneur d'état graphique.

### EmfPlusEndContainer {#EmfPlusEndContainer}
```
public static final short EmfPlusEndContainer
```


Cet enregistrement ferme un conteneur d'état graphique qui avait été précédemment ouvert par une opération de démarrage de conteneur.

### EmfPlusSetWorldTransform {#EmfPlusSetWorldTransform}
```
public static final short EmfPlusSetWorldTransform
```


Cet enregistrement définit la transformation de l'espace mondial actuel dans le playback device\_context, selon une matrice de transformation spécifiée.

### EmfPlusResetWorldTransform {#EmfPlusResetWorldTransform}
```
public static final short EmfPlusResetWorldTransform
```


Cet enregistrement réinitialise la transformation de l'espace mondial actuel à la matrice d'identité.

### EmfPlusMultiplyWorldTransform {#EmfPlusMultiplyWorldTransform}
```
public static final short EmfPlusMultiplyWorldTransform
```


Cet enregistrement multiplie l'espace mondial actuel par une matrice de transformation spécifiée.

### EmfPlusTranslateWorldTransform {#EmfPlusTranslateWorldTransform}
```
public static final short EmfPlusTranslateWorldTransform
```


Cet enregistrement applique une transformation de translation à l'espace mondial actuel selon des distances horizontales et verticales spécifiées.

### EmfPlusScaleWorldTransform {#EmfPlusScaleWorldTransform}
```
public static final short EmfPlusScaleWorldTransform
```


Cet enregistrement applique une transformation d'échelle à l'espace mondial actuel selon des facteurs d'échelle horizontaux et verticaux spécifiés.

### EmfPlusRotateWorldTransform {#EmfPlusRotateWorldTransform}
```
public static final short EmfPlusRotateWorldTransform
```


Cet enregistrement fait pivoter l'espace mondial actuel d'un angle spécifié.

### EmfPlusSetPageTransform {#EmfPlusSetPageTransform}
```
public static final short EmfPlusSetPageTransform
```


Cet enregistrement spécifie des facteurs d'échelle supplémentaires pour la transformation de l'espace mondial actuel.

### EmfPlusResetClip {#EmfPlusResetClip}
```
public static final short EmfPlusResetClip
```


Cet enregistrement réinitialise la région de découpage actuelle de l'espace mondial à l'infini.

### EmfPlusSetClipRect {#EmfPlusSetClipRect}
```
public static final short EmfPlusSetClipRect
```


Cet enregistrement combine la région de découpage actuelle avec un rectangle.

### EmfPlusSetClipPath {#EmfPlusSetClipPath}
```
public static final short EmfPlusSetClipPath
```


Cet enregistrement combine la région de découpage actuelle avec un chemin graphique.

### EmfPlusSetClipRegion {#EmfPlusSetClipRegion}
```
public static final short EmfPlusSetClipRegion
```


Cet enregistrement combine la région de découpage actuelle avec une autre région graphique.

### EmfPlusOffsetClip {#EmfPlusOffsetClip}
```
public static final short EmfPlusOffsetClip
```


Cet enregistrement applique une transformation de translation sur la région de découpage actuelle de l'espace mondial.

### EmfPlusDrawDriverString {#EmfPlusDrawDriverString}
```
public static final short EmfPlusDrawDriverString
```


Cet enregistrement spécifie la sortie de texte avec les positions des caractères.

### EmfPlusStrokeFillPath {#EmfPlusStrokeFillPath}
```
public static final short EmfPlusStrokeFillPath
```


Cet enregistrement ferme toutes les figures ouvertes dans un chemin, trace le contour du chemin en utilisant le stylo actuel, et remplit son intérieur en utilisant le pinceau actuel.

### EmfPlusSerializableObject {#EmfPlusSerializableObject}
```
public static final short EmfPlusSerializableObject
```


Cet enregistrement définit un bloc de paramètres d'effets d'image qui a été sérialisé dans un tampon de données.

### EmfPlusSetTSGraphics {#EmfPlusSetTSGraphics}
```
public static final short EmfPlusSetTSGraphics
```


Cet enregistrement spécifie l'état d'un contexte de périphérique graphique pour un serveur terminal.

### EmfPlusSetTSClip {#EmfPlusSetTSClip}
```
public static final short EmfPlusSetTSClip
```


Cet enregistrement spécifie les zones de découpage dans le contexte de périphérique graphique pour un serveur terminal.

