---
title: Aspose.Imaging
second_title: Référence de l'API Aspose.Imaging pour .NET
description: Lespace de noms est le cœur des espaces de noms imbriqués et les objets les plus élémentaires utilisés pour le traitement Aspose.Imaging.
type: docs
weight: 10
url: /fr/aspose.imaging/
---
L'espace de noms est le cœur des espaces de noms imbriqués et les objets les plus élémentaires utilisés pour le traitement Aspose.Imaging.

## Des classes

| Classer | La description |
| --- | --- |
| [AggregateException](./aggregateexception) | Regroupe plusieurs exceptions. |
| [Blend](./blend) | Définit un motif de fusion. Cette classe ne peut pas être héritée. |
| [Brush](./brush) | La classe de brosse de base. |
| [BuildVersionInfo](./buildversioninfo) | Contient les informations sur la version actuelle de la version. |
| [Cache](./cache) | Contient les paramètres de cache. |
| [CmykColorHelper](./cmykcolorhelper) | Méthodes d'assistance pour travailler avec la couleur CMJN présentée sous la forme d'une valeur entière 32 bits signée. Fournit l'API similaire à[`CmykColor`](../aspose.imaging/cmykcolor) struct. C'est plus léger car la couleur CMJN est présentée comme Int32 plutôt que comme une structure avec des champs internes. Veuillez préférer utiliser les méthodes statiques de cette classe lorsque cela est possible au lieu de l'obsolète [`CmykColor`](../aspose.imaging/cmykcolor) structure. |
| [ColorBlend](./colorblend) | Définit les tableaux de couleurs et les positions utilisées pour interpoler le mélange des couleurs dans un dégradé multicolore. Cette classe ne peut pas être héritée. |
| [ColorMap](./colormap) | Définit une carte pour convertir les couleurs. Plusieurs méthodes de la[`ImageAttributes`](../aspose.imaging/imageattributes) classe ajuste les couleurs de l'image à l'aide d'une table de remappage des couleurs, qui est un tableau de[`ColorMap`](../aspose.imaging/colormap) structures. Non héréditaire. |
| [ColorMatrix](./colormatrix) | Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la[`ImageAttributes`](../aspose.imaging/imageattributes) ajuste les couleurs de l'image à l'aide d'une matrice de couleurs. Cette classe ne peut pas être héritée. |
| [ColorPalette](./colorpalette) | Définit un tableau de couleurs qui composent une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héréditaire. |
| [ColorPaletteHelper](./colorpalettehelper) | Classe d'assistance pour la manipulation des palettes de couleurs. |
| [ColorTranslator](./colortranslator) | Traduit les couleurs vers et depuis les structures GDI+ Color. Cette classe ne peut pas être héritée. |
| [CompositeException](./compositeexception) | L'exception composite |
| [CustomFontSource](./customfontsource) | Fonction de fournisseur de sources de polices personnalisées |
| [CustomLineCap](./customlinecap) | Encapsule une limite de ligne personnalisée définie par l'utilisateur. |
| [DataStreamSupporter](./datastreamsupporter) | Le conteneur de flux de données. |
| [DisposableObject](./disposableobject) | Représente un objet jetable. |
| [EmbeddedImage](./embeddedimage) | La classe d'image intégrée |
| [Figure](./figure) | Le chiffre. Un conteneur pour les formes. |
| [FileStreamContainer](./filestreamcontainer) | Aide pour le traitement du flux de fichiers. |
| [Font](./font) | Définit un format particulier pour le texte, y compris les attributs de police, de taille et de style. Cette classe ne peut pas être héritée. |
| [FontSettings](./fontsettings) | Paramètres généraux de police de rendu des formats vectoriels d'imagerie. |
| [Graphics](./graphics) | Représente les graphiques selon le moteur graphique utilisé dans l'assemblage courant. |
| [GraphicsPath](./graphicspath) | Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée. |
| [Image](./image) | L'image est la classe de base pour tous les types d'images. |
| [ImageAttributes](./imageattributes) | Un[`ImageAttributes`](../aspose.imaging/imageattributes) L'objet contient des informations sur la manière dont les couleurs des bitmaps et des métafichiers sont manipulées lors du rendu. Un[`ImageAttributes`](../aspose.imaging/imageattributes)L'objet conserve plusieurs paramètres d'ajustement des couleurs, notamment les matrices d'ajustement des couleurs, les matrices d'ajustement des niveaux de gris, les valeurs de correction gamma, les tables de cartes de couleurs et les valeurs de seuil de couleur. Pendant le rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un[`ImageAttributes`](../aspose.imaging/imageattributes) objet et passez le chemin de celui-ci[`ImageAttributes`](../aspose.imaging/imageattributes) objet (ainsi que le chemin d'un[`Image`](../aspose.imaging/image) ) à la méthode DrawImage. |
| [ImageCreatorsRegistry](./imagecreatorsregistry) | Représente le registre des créateurs d'images. |
| [ImageExportersRegistry](./imageexportersregistry) | Représente le registre des exportateurs d'images. |
| [ImageLoadersRegistry](./imageloadersregistry) | Représente le registre des chargeurs d'images. |
| [ImageOptionsBase](./imageoptionsbase) | Les options de base de l'image. |
| [ImageResizeSettings](./imageresizesettings) | Classe de paramètres de redimensionnement d'image |
| [IntRange](./intrange) | Classe pour représenter la séquence d'éléments |
| [License](./license) | Fournit des méthodes pour autoriser le composant. |
| [LoadOptions](./loadoptions) | Représente les options de chargement. |
| [Matrix](./matrix) | Remplace la matrice GDI+. |
| [Metered](./metered) | Fournit des méthodes pour définir la clé mesurée. |
| [NonGenericDictionary](./nongenericdictionary) | Représente un dictionnaire non générique. |
| [NonGenericList](./nongenericlist) | Liste non générique d'objets |
| [ObjectWithBounds](./objectwithbounds) | L'objet ayant des limites. |
| [OpenTypeFontsCache](./opentypefontscache) | Cache pour les polices OpenType installées dans le système. |
| [PageExportingAction](./pageexportingaction) | Délégué pour le déclenchement avant l'exportation de la page |
| [Pen](./pen) | Définit un objet utilisé pour dessiner des lignes, des courbes et des figures. |
| [PixelDataFormat](./pixeldataformat) | Le format de données en pixels. Ceci est un objet immuable. |
| [ProgressEventHandler](./progresseventhandler) | Référence de la fonction de gestionnaire d'événements Progress |
| [RasterCachedImage](./rastercachedimage) | Représente une image raster prenant en charge les opérations graphiques raster. Cette image met en cache les données de pixel lorsque cela est nécessaire. |
| [RasterCachedMultipageImage](./rastercachedmultipageimage) | L'image raster multipage |
| [RasterImage](./rasterimage) | Représente une image raster prenant en charge les opérations graphiques raster. |
| [RawDataSettings](./rawdatasettings) | Les paramètres de données brutes |
| [Region](./region) | Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée. |
| [ResolutionSetting](./resolutionsetting) | Le paramètre de résolution pour les options d'enregistrement d'image. |
| [Shape](./shape) | La forme. Un ensemble continu de points connectés à l'aide d'une règle spécifique. |
| [ShapeSegment](./shapesegment) | Représente un segment de forme. Un segment est une ligne ou une courbe reliant deux points. |
| [Source](./source) | La source est utilisée pour contenir toutes les informations pertinentes pour un objet pipe. |
| [SplitStreamContainer](./splitstreamcontainer) | Représente le conteneur de flux divisé qui contient le flux et fournit des routines de traitement de flux. |
| [StreamContainer](./streamcontainer) | Représente le conteneur de flux qui contient le flux et fournit des routines de traitement de flux. |
| [StringFormat](./stringformat) | Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les taquets de tabulation), les manipulations d'affichage (telles que l'insertion de points de suspension et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée. |
| [TransparencySupporter](./transparencysupporter) | L'objet prenant en charge la transparence. |
| [VectorImage](./vectorimage) | L'image vectorielle est la classe de base pour tous les types d'images vectorielles. |
| [VectorMultipageImage](./vectormultipageimage) | L'image vectorielle multipage |
## Interfaces

| Interface | La description |
| --- | --- |
| [IAdvancedBufferProcessor](./iadvancedbufferprocessor) | Le processeur de tampon avancé. |
| [IAnimationFrame](./ianimationframe) | Le cadre d'animation |
| [IBufferProcessor](./ibufferprocessor) | Le processeur de tampon. |
| [IColorConverter](./icolorconverter) | Le convertisseur de couleurs. |
| [IColorPalette](./icolorpalette) | L'interface de la palette de couleurs. |
| [IImageCreator](./iimagecreator) | Le créateur d'images. |
| [IImageCreatorDescriptor](./iimagecreatordescriptor) | Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur de créateur est utilisé pour surmonter la nécessité de contenir chaque instance de créateur d'image dans la mémoire et les problèmes de multithreading. |
| [IImageDescriptor](./iimagedescriptor) | Le descripteur d'image. Contient les propriétés et méthodes de base pour tous les autres types de descripteurs d'image. |
| [IImageExporter](./iimageexporter) | L'exportateur d'images. Peut exporter des données du format Aspose.Imaging interne vers un format de données spécifié. |
| [IImageExporterDescriptor](./iimageexporterdescriptor) | Représente le descripteur de l'exportateur d'image. Le descripteur d'exportateur est utilisé pour surmonter la nécessité de contenir chaque instance d'exportateur dans la mémoire et les problèmes de multithreading. |
| [IImageLoader](./iimageloader) | Le chargeur d'images. |
| [IImageLoaderDescriptor](./iimageloaderdescriptor) | Le descripteur de chargeur d'image spécifiant les propriétés du chargeur. Le descripteur de chargeur est utilisé pour surmonter la nécessité de contenir chaque instance de chargeur d'image dans la mémoire et les problèmes de multithreading. |
| [IIndexedColorConverter](./iindexedcolorconverter) | Le convertisseur de couleurs pour les formats d'image indexés. |
| [IKeyedObject](./ikeyedobject) | Représente l'interface pour les objets avec des clés. |
| [IMultipageImage](./imultipageimage) | L'interface d'images multipages |
| [IMultipageImageExt](./imultipageimageext) | L'interface d'image multipage étendue |
| [IObjectWithBounds](./iobjectwithbounds) | Représente un objet avec des bornes. |
| [IOrderedShape](./iorderedshape) | Représente une forme ordonnée. Une forme ordonnée est un ensemble continu de points ayant un point de départ et un point final. L'ensemble continu de points connectés à l'aide d'une règle spécifique. |
| [IPartialArgb32PixelLoader](./ipartialargb32pixelloader) | Conforme aux pixels ARGB 32 bits chargés partiellement. |
| [IPartialArgb64PixelLoader](./ipartialargb64pixelloader) | Le chargeur de pixels ARGB 64 bits. |
| [IPartialPixelLoader](./ipartialpixelloader) | Conforme aux pixels chargés partiellement. |
| [IPartialRawDataLoader](./ipartialrawdataloader) | Le chargeur de données partiel. |
| [IRasterImageArgb32PixelLoader](./irasterimageargb32pixelloader) | Le chargeur de pixels ARGB 32 bits d'image raster. |
| [IRasterImagePixelLoader](./irasterimagepixelloader) | Le chargeur de pixels d'image raster. |
| [IRasterImageRawDataLoader](./irasterimagerawdataloader) | Le chargeur de données brutes d'image raster. |
## Énumération

| Énumération | La description |
| --- | --- |
| [AnimationDisposalMethods](./animationdisposalmethods) | Indique la manière dont le graphique doit être traité après son affichage. |
| [CacheType](./cachetype) | Spécifie le type de cache à utiliser. |
| [CharacterSet](./characterset) | Représente le jeu de caractères utilisé. |
| [ColorAdjustType](./coloradjusttype) | Spécifie quels objets utilisent les informations de réglage des couleurs. |
| [ColorChannelFlag](./colorchannelflag) | Spécifie les canaux individuels dans l'espace colorimétrique CMJN (cyan, magenta, jaune, noir). Cette énumération est utilisée par les méthodes SetOutputChannel. |
| [ColorCompareMethod](./colorcomparemethod) | Méthode de comparaison des couleurs pour ajuster au voisin le plus proche |
| [ColorMatrixFlag](./colormatrixflag) | Spécifie les types d'images et de couleurs qui seront affectés par les paramètres de réglage des couleurs et des niveaux de gris d'un[`ImageAttributes`](../aspose.imaging/imageattributes) . |
| [ColorQuantizationMethod](./colorquantizationmethod) | Méthodes de quantification des couleurs |
| [CompositingQuality](./compositingquality) | Spécifie le niveau de qualité à utiliser lors de la composition. |
| [DashCap](./dashcap) | Spécifie le type de forme graphique à utiliser aux deux extrémités de chaque tiret dans une ligne pointillée. |
| [DashStyle](./dashstyle) | Spécifie le style des lignes pointillées dessinées avec un[`Pen`](../aspose.imaging/pen) objet. |
| [DataRecoveryMode](./datarecoverymode) | Le mode de récupération de données. |
| [DitheringMethod](./ditheringmethod) | Méthode de tramage. |
| [DitheringMethods](./ditheringmethods) | Les méthodes de tramage utilisées pour contrôler la conversion des couleurs. |
| [FileFormat](./fileformat) | L'un des formats de fichier d'imagerie pris en charge. |
| [FillMode](./fillmode) | Spécifie comment l'intérieur d'un chemin fermé est rempli. |
| [FontStyle](./fontstyle) | Spécifie les informations de style appliquées au texte. |
| [GraphicsUnit](./graphicsunit) | Spécifie l'unité de mesure pour les données données. |
| [HatchStyle](./hatchstyle) | Spécifie les différents modèles disponibles pour[`HatchBrush`](../aspose.imaging.brushes/hatchbrush) objets. |
| [HotkeyPrefix](./hotkeyprefix) | Spécifie le type d'affichage des préfixes de raccourcis clavier liés au texte. |
| [ImageFilterType](./imagefiltertype) | Filtres d'images à utiliser |
| [InterpolationMode](./interpolationmode) | Le[`InterpolationMode`](../aspose.imaging/interpolationmode) l'énumération spécifie l'algorithme utilisé lorsque les images sont mises à l'échelle ou pivotées. |
| [KnownColor](./knowncolor) | Spécifie les couleurs système connues. |
| [LineCap](./linecap) | Spécifie les styles de capuchon disponibles avec lesquels un[`Pen`](../aspose.imaging/pen) l'objet peut terminer une ligne. |
| [LineJoin](./linejoin) | Spécifie comment joindre des segments de ligne ou de courbe consécutifs dans une figure (sous-chemin) contenue dans un[`GraphicsPath`](../aspose.imaging/graphicspath) objet. |
| [MatrixOrder](./matrixorder) | Spécifie l'ordre des opérations de transformation matricielle. |
| [PaletteMiningMethod](./paletteminingmethod) | La méthode d'exploration de palette d'images |
| [PdfComplianceVersion](./pdfcomplianceversion) | Spécifie le niveau de conformité PDF du fichier de sortie. |
| [PenAlignment](./penalignment) | Spécifie l'alignement d'un[`Pen`](../aspose.imaging/pen)objet par rapport à la ligne théorique de largeur nulle. |
| [PenType](./pentype) | Spécifie le type de remplissage a[`Pen`](../aspose.imaging/pen) objet utilise pour remplir les lignes. |
| [PixelFormat](./pixelformat) | La signification réelle du format de données pixel. |
| [ResizeType](./resizetype) | Spécifie le type de redimensionnement. |
| [ResolutionUnit](./resolutionunit) | Énumération d'unité de résolution. |
| [RotateFlipType](./rotatefliptype) | Spécifie le degré de rotation d'une image et l'axe utilisé pour retourner l'image. |
| [SeekOrigin](./seekorigin) | Fournit les champs qui représentent les points de référence dans[`StreamContainer`](../aspose.imaging/streamcontainer) pour chercher. |
| [SmoothingMode](./smoothingmode) | Spécifie si le lissage (anticrénelage) est appliqué aux lignes et aux courbes et aux bords des zones remplies. |
| [StringAlignment](./stringalignment) | Spécifie l'alignement d'une chaîne de texte par rapport à son rectangle de mise en page. |
| [StringDigitSubstitute](./stringdigitsubstitute) | L'énumération spécifie comment substituer des chiffres dans une chaîne en fonction des paramètres régionaux ou de la langue d'un utilisateur. |
| [StringFormatFlags](./stringformatflags) | Spécifie les informations d'affichage et de mise en page pour les chaînes de texte. |
| [StringTrimming](./stringtrimming) | Spécifie comment couper les caractères d'une chaîne qui ne rentre pas complètement dans une forme de mise en page. |
| [TextRenderingHint](./textrenderinghint) | Spécifie la qualité du rendu du texte. |
| [WarpMode](./warpmode) | Spécifie le type de transformation Warp appliquée. |
| [WrapMode](./wrapmode) | Spécifie comment une texture ou un dégradé est carrelé lorsqu'il est plus petit que la zone à remplir. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
