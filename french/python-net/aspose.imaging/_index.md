---
title: "aspose.imaging"
type: docs
weight: 10
url: /fr/python-net/aspose.imaging/
---


Le module est le cœur des modules imbriqués et les objets les plus basiques utilisés pour le traitement d'Aspose.Imaging.

## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [Blend](/imaging/python-net/aspose.imaging/blend/) | Définit un motif de mélange. Cette classe ne peut pas être héritée. |
| [Brush](/imaging/python-net/aspose.imaging/brush/) | La classe de brosse de base. |
| [BuildVersionInfo](/imaging/python-net/aspose.imaging/buildversioninfo/) | Contient les informations de version de construction actuelles. |
| [Cache](/imaging/python-net/aspose.imaging/cache/) | Contient les paramètres du cache. |
| [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/) | La couleur CMYK du pixel. |
| [CmykColorHelper](/imaging/python-net/aspose.imaging/cmykcolorhelper/) | Méthodes d'assistance pour travailler avec la couleur CMYK présentée comme une valeur entière signée de 32 bits.<br/>            Fournit une API similaire à la structure [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/).<br/>            Elle est plus légère car la couleur CMYK est présentée simplement comme un Int32 plutôt que comme une structure avec des champs internes.<br/>            Veuillez privilégier l'utilisation des méthodes statiques de cette classe lorsque cela est possible au lieu de la structure obsolète<br/>            [CmykColor](/imaging/python-net/aspose.imaging/cmykcolor/). |
| [Color](/imaging/python-net/aspose.imaging/color/) | La couleur du pixel. |
| [ColorBlend](/imaging/python-net/aspose.imaging/colorblend/) | Définit des tableaux de couleurs et de positions utilisés pour interpoler le mélange de couleurs dans un dégradé multicolore. Cette classe ne peut pas être héritée. |
| [ColorMap](/imaging/python-net/aspose.imaging/colormap/) | Définit une table de conversion des couleurs. Plusieurs méthodes de la classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) ajustent les couleurs de l'image en utilisant une table de remappage des couleurs, qui est un tableau de structures [ColorMap](/imaging/python-net/aspose.imaging/colormap/). Non héritable. |
| [ColorMatrix](/imaging/python-net/aspose.imaging/colormatrix/) | Définit une matrice 5 x 5 qui contient les coordonnées de l'espace RGBA. Plusieurs méthodes de la classe [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) ajustent les couleurs de l'image en utilisant une matrice de couleurs. Cette classe ne peut pas être héritée. |
| [ColorPalette](/imaging/python-net/aspose.imaging/colorpalette/) | Définit un tableau de couleurs qui compose une palette de couleurs. Les couleurs sont des couleurs ARGB 32 bits. Non héritable. |
| [ColorPaletteHelper](/imaging/python-net/aspose.imaging/colorpalettehelper/) | Classe d'assistance pour la manipulation des palettes de couleurs. |
| [ColorTranslator](/imaging/python-net/aspose.imaging/colortranslator/) | Traduit les couleurs vers et depuis les structures GDI+ Color. Cette classe ne peut pas être héritée. |
| [CustomLineCap](/imaging/python-net/aspose.imaging/customlinecap/) | Encapsule une extrémité de ligne personnalisée définie par l'utilisateur. |
| [DataStreamSupporter](/imaging/python-net/aspose.imaging/datastreamsupporter/) | Le conteneur de flux de données. |
| [DisposableObject](/imaging/python-net/aspose.imaging/disposableobject/) | Représente un objet jetable. |
| [EmbeddedImage](/imaging/python-net/aspose.imaging/embeddedimage/) | La classe d'image intégrée |
| [Figure](/imaging/python-net/aspose.imaging/figure/) | La figure. Un conteneur pour les formes. |
| [FileStreamContainer](/imaging/python-net/aspose.imaging/filestreamcontainer/) | Assistant pour le traitement des flux de fichiers. |
| [Font](/imaging/python-net/aspose.imaging/font/) | Définit un format particulier pour le texte, incluant la police, la taille et les attributs de style. Cette classe ne peut pas être héritée. |
| [FontSettings](/imaging/python-net/aspose.imaging/fontsettings/) | Paramètres de police du rendu des formats vectoriels d'imagerie généraux. |
| [Graphics](/imaging/python-net/aspose.imaging/graphics/) | Représente les graphiques selon le moteur graphique utilisé dans l'assembly actuel. |
| [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/) | Représente une série de lignes et de courbes connectées. Cette classe ne peut pas être héritée. |
| [IAdvancedBufferProcessor](/imaging/python-net/aspose.imaging/iadvancedbufferprocessor/) | Le processeur de tampon avancé. |
| [IAnimationFrame](/imaging/python-net/aspose.imaging/ianimationframe/) | Le cadre d'animation |
| [IBufferProcessor](/imaging/python-net/aspose.imaging/ibufferprocessor/) | Le processeur de tampon. |
| [IColorConverter](/imaging/python-net/aspose.imaging/icolorconverter/) | Le convertisseur de couleur. |
| [IColorPalette](/imaging/python-net/aspose.imaging/icolorpalette/) | L'interface de palette de couleur. |
| [IHasMetadata](/imaging/python-net/aspose.imaging/ihasmetadata/) | Interface des métadonnées d'image. |
| [IImageCreator](/imaging/python-net/aspose.imaging/iimagecreator/) | Le créateur d'image. |
| [IImageCreatorDescriptor](/imaging/python-net/aspose.imaging/iimagecreatordescriptor/) | Le descripteur du créateur d'image spécifiant les propriétés du créateur. Le descripteur du créateur est utilisé pour surmonter<br/>            la nécessité de contenir chaque instance de créateur d'image en mémoire et les problèmes de multithreading. |
| [IImageDescriptor](/imaging/python-net/aspose.imaging/iimagedescriptor/) | Le descripteur d'image. Contient les propriétés et méthodes de base pour tous les autres types de descripteurs d'image. |
| [IImageExporter](/imaging/python-net/aspose.imaging/iimageexporter/) | L'exportateur d'image. Peut exporter des données du format interne `aspose.imaging` vers un format de données spécifié. |
| [IImageExporterDescriptor](/imaging/python-net/aspose.imaging/iimageexporterdescriptor/) | Représente le descripteur d'exportateur d'image. Le descripteur d'exportateur est utilisé pour surmonter la nécessité de contenir chaque instance d'exportateur<br/>            en mémoire et les problèmes de multithreading. |
| [IImageLoader](/imaging/python-net/aspose.imaging/iimageloader/) | Le chargeur d'image. |
| [IImageLoaderDescriptor](/imaging/python-net/aspose.imaging/iimageloaderdescriptor/) | Le descripteur du chargeur d'image spécifiant les propriétés du chargeur. Le descripteur du chargeur est utilisé pour surmonter<br/>            la nécessité de contenir chaque instance de chargeur d'image en mémoire et les problèmes de multithreading. |
| [IIndexedColorConverter](/imaging/python-net/aspose.imaging/iindexedcolorconverter/) | Le convertisseur de couleur pour les formats d'image indexés. |
| [IMetadataContainer](/imaging/python-net/aspose.imaging/imetadatacontainer/) | Interface du conteneur de métadonnées d'image. |
| [IMultipageImage](/imaging/python-net/aspose.imaging/imultipageimage/) | L'interface d'image multipage |
| [IMultipageImageExt](/imaging/python-net/aspose.imaging/imultipageimageext/) | L'interface d'image multipage étendue |
| [IObjectWithBounds](/imaging/python-net/aspose.imaging/iobjectwithbounds/) | Représente un objet avec des limites. |
| [IOrderedShape](/imaging/python-net/aspose.imaging/iorderedshape/) | Représente une forme ordonnée. Une forme ordonnée est un ensemble continu de points ayant un point de départ et un point d'arrivée.<br/>            L'ensemble continu de points est relié selon une règle spécifique. |
| [IPartialArgb32PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb32pixelloader/) | Conforme aux pixels ARGB 32 bits chargés partiellement. |
| [IPartialArgb64PixelLoader](/imaging/python-net/aspose.imaging/ipartialargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits. |
| [IPartialPixelLoader](/imaging/python-net/aspose.imaging/ipartialpixelloader/) | Conforme aux pixels chargés partiellement. |
| [IPartialRawDataLoader](/imaging/python-net/aspose.imaging/ipartialrawdataloader/) | Le chargeur de données partielles. |
| [IRasterImageArgb32PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb32pixelloader/) | Le chargeur de pixels ARGB 32 bits d'image raster. |
| [IRasterImageArgb64PixelLoader](/imaging/python-net/aspose.imaging/irasterimageargb64pixelloader/) | Le chargeur de pixels ARGB 64 bits d'image raster. |
| [IRasterImagePixelLoader](/imaging/python-net/aspose.imaging/irasterimagepixelloader/) | Le chargeur de pixels d'image raster. |
| [IRasterImageRawDataLoader](/imaging/python-net/aspose.imaging/irasterimagerawdataloader/) | Le chargeur de données brutes d'image raster. |
| [Image](/imaging/python-net/aspose.imaging/image/) | L'image est la classe de base pour tous les types d'images. |
| [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) | Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) contient des informations sur la façon dont les couleurs des bitmap et des métafichiers sont manipulées lors du rendu. Un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) maintient plusieurs paramètres de réglage des couleurs, y compris les matrices de réglage des couleurs, les matrices de réglage en niveaux de gris, les valeurs de correction gamma, les tables de correspondance des couleurs et les valeurs de seuil de couleur. Lors du rendu, les couleurs peuvent être corrigées, assombries, éclaircies et supprimées. Pour appliquer de telles manipulations, initialisez un objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) et transmettez le chemin de cet objet [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/) (ainsi que le chemin d'une [Image](/imaging/python-net/aspose.imaging/image/)) à la méthode DrawImage. |
| [ImageCreatorsRegistry](/imaging/python-net/aspose.imaging/imagecreatorsregistry/) | Représente le registre des créateurs d'images. |
| [ImageExportersRegistry](/imaging/python-net/aspose.imaging/imageexportersregistry/) | Représente le registre des exportateurs d'images. |
| [ImageLoadersRegistry](/imaging/python-net/aspose.imaging/imageloadersregistry/) | Représente le registre des chargeurs d'images. |
| [ImageOptionsBase](/imaging/python-net/aspose.imaging/imageoptionsbase/) | Les options de base de l'image. |
| [ImageResizeSettings](/imaging/python-net/aspose.imaging/imageresizesettings/) | Classe des paramètres de redimensionnement d'image |
| [IntRange](/imaging/python-net/aspose.imaging/intrange/) | Classe pour représenter une séquence d'éléments |
| [License](/imaging/python-net/aspose.imaging/license/) | Fournit des méthodes pour licencier le composant. |
| [LoadOptions](/imaging/python-net/aspose.imaging/loadoptions/) | Représente les options de chargement. |
| [Matrix](/imaging/python-net/aspose.imaging/matrix/) | Remplace la matrice GDI+. |
| [Metered](/imaging/python-net/aspose.imaging/metered/) | Fournit des méthodes mesurées pour l'intégration |
| [NonGenericDictionary](/imaging/python-net/aspose.imaging/nongenericdictionary/) | Représente un dictionnaire non générique. |
| [NonGenericList](/imaging/python-net/aspose.imaging/nongenericlist/) | Liste non générique d'objets |
| [ObjectWithBounds](/imaging/python-net/aspose.imaging/objectwithbounds/) | L'objet ayant des limites. |
| [OpenTypeFontsCache](/imaging/python-net/aspose.imaging/opentypefontscache/) | Cache pour les polices OpenType installées dans le système. |
| [Pen](/imaging/python-net/aspose.imaging/pen/) | Définit un objet utilisé pour dessiner des lignes, des courbes et des figures. |
| [PixelDataFormat](/imaging/python-net/aspose.imaging/pixeldataformat/) | Le format des données de pixel. C'est un objet immuable. |
| [Point](/imaging/python-net/aspose.imaging/point/) | Représente une paire ordonnée de coordonnées x et y entières qui définit un point dans un plan bidimensionnel. |
| [PointF](/imaging/python-net/aspose.imaging/pointf/) | Représente une paire ordonnée de coordonnées x et y à virgule flottante qui définit un point dans un plan bidimensionnel. |
| [RasterCachedImage](/imaging/python-net/aspose.imaging/rastercachedimage/) | Représente une image raster prenant en charge les opérations graphiques raster. Cette image met en cache les données de pixel lorsque cela est nécessaire. |
| [RasterCachedMultipageImage](/imaging/python-net/aspose.imaging/rastercachedmultipageimage/) | L'image raster multipage |
| [RasterImage](/imaging/python-net/aspose.imaging/rasterimage/) | Représente une image raster prenant en charge les opérations graphiques raster. |
| [RawDataSettings](/imaging/python-net/aspose.imaging/rawdatasettings/) | Les paramètres des données brutes |
| [Rectangle](/imaging/python-net/aspose.imaging/rectangle/) | Stocke un ensemble de quatre entiers représentant la position et la taille d'un rectangle. |
| [RectangleF](/imaging/python-net/aspose.imaging/rectanglef/) | Stocke un ensemble de quatre nombres à virgule flottante représentant la position et la taille d'un rectangle. |
| [Region](/imaging/python-net/aspose.imaging/region/) | Décrit l'intérieur d'une forme graphique composée de rectangles et de chemins. Cette classe ne peut pas être héritée. |
| [RemoveBackgroundSettings](/imaging/python-net/aspose.imaging/removebackgroundsettings/) | Les paramètres de suppression d'arrière-plan |
| [ResolutionSetting](/imaging/python-net/aspose.imaging/resolutionsetting/) | Le paramètre de résolution pour les options d'enregistrement d'image. |
| [Shape](/imaging/python-net/aspose.imaging/shape/) | La forme. Un ensemble continu de points connectés selon une règle spécifique. |
| [ShapeSegment](/imaging/python-net/aspose.imaging/shapesegment/) | Représente un segment de forme. Un segment est une ligne ou une courbe reliant deux points. |
| [Size](/imaging/python-net/aspose.imaging/size/) | Représente la taille. |
| [SizeF](/imaging/python-net/aspose.imaging/sizef/) | Stocke une paire ordonnée de nombres à virgule flottante, généralement la largeur et la hauteur d'un rectangle. |
| [Source](/imaging/python-net/aspose.imaging/source/) | La source est utilisée pour contenir toutes les informations pertinentes pour un tuyau d'objet. |
| [SplitStreamContainer](/imaging/python-net/aspose.imaging/splitstreamcontainer/) | Représente un conteneur de flux fractionné qui contient le flux et fournit des routines de traitement du flux. |
| [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) | Représente un conteneur de flux qui contient le flux et fournit des routines de traitement du flux. |
| [StringFormat](/imaging/python-net/aspose.imaging/stringformat/) | Encapsule les informations de mise en page du texte (telles que l'alignement, l'orientation et les tabulations) les manipulations d'affichage (telles que l'insertion d'ellipses et la substitution de chiffres nationaux) et les fonctionnalités OpenType. Cette classe ne peut pas être héritée. |
| [TransparencySupporter](/imaging/python-net/aspose.imaging/transparencysupporter/) | L'objet prenant en charge la transparence. |
| [VectorImage](/imaging/python-net/aspose.imaging/vectorimage/) | L'image vectorielle est la classe de base pour tous les types d'images vectorielles. |
| [VectorMultipageImage](/imaging/python-net/aspose.imaging/vectormultipageimage/) | L'image multipage Vector |
## **Enumerations**
| **Énumération** | **Description** |
| :- | :- |
| [AnimationDisposalMethods](/imaging/python-net/aspose.imaging/animationdisposalmethods/) | Indique la manière dont le graphique doit être traité après son affichage. |
| [CacheType](/imaging/python-net/aspose.imaging/cachetype/) | Spécifie le type de cache à utiliser. |
| [CharacterSet](/imaging/python-net/aspose.imaging/characterset/) | Représente le jeu de caractères utilisé. |
| [ColorAdjustType](/imaging/python-net/aspose.imaging/coloradjusttype/) | Spécifie quels objets utilisent les informations d'ajustement des couleurs. |
| [ColorChannelFlag](/imaging/python-net/aspose.imaging/colorchannelflag/) | Spécifie les canaux individuels dans l'espace colorimétrique CMJN (cyan, magenta, jaune, noir). Cette énumération est utilisée par les méthodes SetOutputChannel. |
| [ColorCompareMethod](/imaging/python-net/aspose.imaging/colorcomparemethod/) | Méthode de comparaison des couleurs pour ajuster au voisin le plus proche |
| [ColorMatrixFlag](/imaging/python-net/aspose.imaging/colormatrixflag/) | Spécifie les types d'images et de couleurs qui seront affectés par les paramètres d'ajustement des couleurs et des niveaux de gris d'un [ImageAttributes](/imaging/python-net/aspose.imaging/imageattributes/). |
| [ColorQuantizationMethod](/imaging/python-net/aspose.imaging/colorquantizationmethod/) | Méthodes de quantification des couleurs |
| [CompositingQuality](/imaging/python-net/aspose.imaging/compositingquality/) | Spécifie le niveau de qualité à utiliser lors du compositing. |
| [DashCap](/imaging/python-net/aspose.imaging/dashcap/) | Spécifie le type de forme graphique à utiliser aux deux extrémités de chaque tiret dans une ligne pointillée. |
| [DashStyle](/imaging/python-net/aspose.imaging/dashstyle/) | Spécifie le style des lignes pointillées dessinées avec un objet [Pen](/imaging/python-net/aspose.imaging/pen/). |
| [DataRecoveryMode](/imaging/python-net/aspose.imaging/datarecoverymode/) | Le mode de récupération des données. |
| [DitheringMethod](/imaging/python-net/aspose.imaging/ditheringmethod/) | Méthode de tramage. |
| [DitheringMethods](/imaging/python-net/aspose.imaging/ditheringmethods/) | Les méthodes de tramage utilisées pour contrôler la conversion des couleurs. |
| [FileFormat](/imaging/python-net/aspose.imaging/fileformat/) | L'un des formats de fichier d'imagerie pris en charge. |
| [FillMode](/imaging/python-net/aspose.imaging/fillmode/) | Spécifie comment l'intérieur d'un chemin fermé est rempli. |
| [FontStyle](/imaging/python-net/aspose.imaging/fontstyle/) | Spécifie les informations de style appliquées au texte. |
| [GraphicsUnit](/imaging/python-net/aspose.imaging/graphicsunit/) | Spécifie l'unité de mesure des données fournies. |
| [HatchStyle](/imaging/python-net/aspose.imaging/hatchstyle/) | Spécifie les différents motifs disponibles pour les objets [HatchBrush](/imaging/python-net/aspose.imaging.brushes/hatchbrush/). |
| [HotkeyPrefix](/imaging/python-net/aspose.imaging/hotkeyprefix/) | Spécifie le type d'affichage des préfixes de raccourcis clavier liés au texte. |
| [ImageFilterType](/imaging/python-net/aspose.imaging/imagefiltertype/) | Filtres d'image à utiliser |
| [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) | L'énumération [InterpolationMode](/imaging/python-net/aspose.imaging/interpolationmode/) spécifie l'algorithme utilisé lorsque les images sont redimensionnées ou pivotées. |
| [KnownColor](/imaging/python-net/aspose.imaging/knowncolor/) | Spécifie les couleurs système connues. |
| [LineCap](/imaging/python-net/aspose.imaging/linecap/) | Spécifie les styles de bout disponibles avec lesquels un objet [Pen](/imaging/python-net/aspose.imaging/pen/) peut terminer une ligne. |
| [LineJoin](/imaging/python-net/aspose.imaging/linejoin/) | Spécifie comment joindre des segments de ligne ou de courbe consécutifs dans une figure (sous-chemin) contenue dans un objet [GraphicsPath](/imaging/python-net/aspose.imaging/graphicspath/). |
| [MatrixOrder](/imaging/python-net/aspose.imaging/matrixorder/) | Spécifie l'ordre des opérations de transformation de matrice. |
| [PaletteMiningMethod](/imaging/python-net/aspose.imaging/paletteminingmethod/) | La méthode d'extraction de palette d'image |
| [PdfComplianceVersion](/imaging/python-net/aspose.imaging/pdfcomplianceversion/) | Spécifie le niveau de conformité PDF du fichier de sortie. |
| [PenAlignment](/imaging/python-net/aspose.imaging/penalignment/) | Spécifie l'alignement d'un objet [Pen](/imaging/python-net/aspose.imaging/pen/) par rapport à la ligne théorique de largeur nulle. |
| [PenType](/imaging/python-net/aspose.imaging/pentype/) | Spécifie le type de remplissage qu'un objet [Pen](/imaging/python-net/aspose.imaging/pen/) utilise pour remplir les lignes. |
| [PixelFormat](/imaging/python-net/aspose.imaging/pixelformat/) | La signification réelle du format de données pixel. |
| [ProcessingType](/imaging/python-net/aspose.imaging/processingtype/) | Le type de traitement. |
| [ResizeType](/imaging/python-net/aspose.imaging/resizetype/) | Spécifie le type de redimensionnement. |
| [ResolutionUnit](/imaging/python-net/aspose.imaging/resolutionunit/) | Énumération de l'unité de résolution. |
| [RotateFlipType](/imaging/python-net/aspose.imaging/rotatefliptype/) | Spécifie de combien une image est pivotée et l'axe utilisé pour la retourner. |
| [SeekOrigin](/imaging/python-net/aspose.imaging/seekorigin/) | Fournit les champs qui représentent les points de référence dans [StreamContainer](/imaging/python-net/aspose.imaging/streamcontainer/) pour la recherche. |
| [SmoothingMode](/imaging/python-net/aspose.imaging/smoothingmode/) | Spécifie si le lissage (antialiasing) est appliqué aux lignes et aux courbes ainsi qu'aux bords des zones remplies. |
| [StringAlignment](/imaging/python-net/aspose.imaging/stringalignment/) | Spécifie l'alignement d'une chaîne de texte par rapport à son rectangle de mise en page. |
| [StringDigitSubstitute](/imaging/python-net/aspose.imaging/stringdigitsubstitute/) | L'énumération spécifie comment substituer les chiffres dans une chaîne selon la locale ou la langue de l'utilisateur. |
| [StringFormatFlags](/imaging/python-net/aspose.imaging/stringformatflags/) | Spécifie les informations d'affichage et de mise en page pour les chaînes de texte. |
| [StringTrimming](/imaging/python-net/aspose.imaging/stringtrimming/) | Spécifie comment tronquer les caractères d'une chaîne qui ne tient pas complètement dans une forme de mise en page. |
| [TextRenderingHint](/imaging/python-net/aspose.imaging/textrenderinghint/) | Spécifie la qualité du rendu du texte. |
| [WarpMode](/imaging/python-net/aspose.imaging/warpmode/) | Spécifie le type de transformation de déformation appliquée. |
| [WrapMode](/imaging/python-net/aspose.imaging/wrapmode/) | Spécifie comment une texture ou un dégradé est répété lorsqu'il est plus petit que la zone à remplir. |
