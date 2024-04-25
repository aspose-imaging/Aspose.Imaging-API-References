---
title: Aspose.Imaging.FileFormats.Emf.Emf.Records
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lo spazio dei nomi contiene i tipi MS-EMF Enhanced Metafile Format. 2.3 EMF Records
type: docs
weight: 360
url: /it/aspose.imaging.fileformats.emf.emf.records/
---
Lo spazio dei nomi contiene i tipi [MS-EMF]: Enhanced Metafile Format. 2.3 EMF Records

## Classi

| Classe | Descrizione |
| --- | --- |
| [EmfAbortPath](./emfabortpath) | Questo record interrompe una parentesi di percorso o elimina il percorso da una parentesi di percorso chiusa. |
| [EmfAlphaBlend](./emfalphablend) | Il record EMR_ALPHABLEND specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , inclusi i dati di trasparenza alfa, in base a un'operazione di fusione specificata. |
| [EmfAngleArc](./emfanglearc) | Il record EMR_ANGLEARC specifica un segmento di linea di un arco. Il segmento di linea viene disegnato dalla posizione corrente all'inizio dell'arco. L'arco viene disegnato lungo il perimetro di un cerchio con raggio e centro dati . La lunghezza dell'arco è definita dagli angoli di inizio e di ampiezza indicati |
| [EmfArc](./emfarc) | Il record EMR_ARC specifica un arco ellittico. |
| [EmfArcTo](./emfarcto) | Il record EMR_ARCTO specifica un arco ellittico. Reimposta la posizione corrente al punto finale dell'arco. |
| [EmfBeginPath](./emfbeginpath) | Questo record apre una parentesi di percorso nel contesto del dispositivo di riproduzione corrente. Dopo che una parentesi di percorso è stata aperta, un'applicazione può iniziare a elaborare i record per definire i punti che si trovano nel percorso. Un'applicazione DEVE chiudere una parentesi di percorso aperta tramite elaborando EMR_ENDPATH record. Quando un'applicazione elabora il record EMR_BEGINPATH, tutti i percorsi precedenti DEVONO essere eliminati dal contesto del dispositivo di riproduzione. |
| [EmfBitBlt](./emfbitblt) | Il record EMR_BITBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione, opzionalmente in combinazione con un pattern di pennello, in base a un'operazione raster specificata. |
| [EmfBitmapRecordType](./emfbitmaprecordtype) | I tipi di record bitmap eseguono trasferimenti a blocchi di immagini bitmap. |
| [EmfChord](./emfchord) | Il record EMR_CHORD specifica una corda, che è una regione delimitata dall'intersezione di un'ellisse e un segmento di linea, chiamato secante. L'accordo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| [EmfClippingRecordType](./emfclippingrecordtype) | I tipi di record di ritaglio specificano e gestiscono le regioni di ritaglio. Nota Il record EMR_SETMETARGN non specifica i parametri. |
| [EmfCloseFigure](./emfclosefigure) | Questo record chiude una figura aperta in un percorso. Elaborazione del record EMR_CLOSEFIGURE DEVE chiudere la figura tracciando una linea dalla posizione corrente al primo punto della figura, e quindi DEVE collegare le linee utilizzando lo stile di giunzione della linea. Se una figura viene chiusa elaborando il record EMR_LINETO invece del record EMR_CLOSEFIGURE, le estremità terminali vengono utilizzate per creare l'angolo anziché un join.EMR_LINETO è specificato nella sezione 2.3.5.13. Il record EMR_CLOSEFIGURE DOVREBBE essere utilizzato solo se esiste un open path parentesi nel contesto del dispositivo di riproduzione. Una figura in un percorso è aperta a meno che non venga chiusa esplicitamente elaborando questo record. |
| [EmfColorCorrectPalette](./emfcolorcorrectpalette) | Il record EMR_COLORCORRECTPALETTE specifica come correggere le voci di un oggetto tavolozza logica utilizzando i valori WCS 1.0. |
| [EmfColorMatchToTargetW](./emfcolormatchtotargetw) | Il record EMR_COLORMATCHTOTargetW specifica se eseguire la corrispondenza dei colori con un profilo color specificato in un file con un nome composto da caratteri Unicode. |
| [EmfComment](./emfcomment) | Il record EMR_COMMENT contiene dati privati arbitrari. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.3. |
| [EmfCommentBeginGroup](./emfcommentbegingroup) | Il record EMR_COMMENT_BEGINGROUP specifica l'inizio di un gruppo di record di disegno. |
| [EmfCommentEmfPlus](./emfcommentemfplus) | Il record EMR_COMMENT_EMFPLUS contiene record EMF+ incorporati. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.3. |
| [EmfCommentEmfSpool](./emfcommentemfspool) | Il record EMR_COMMENT_EMFSPOOL contiene record EMFSPOOL incorporati. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.3. |
| [EmfCommentEndGroup](./emfcommentendgroup) | Il record EMR_COMMENT_ENDGROUP specifica la fine di un gruppo di record di disegno. |
| [EmfCommentMultiFormats](./emfcommentmultiformats) | Il record EMR_COMMENT_MULTIFORMATS specifica un'immagine in più formati grafici. |
| [EmfCommentPublicRecordType](./emfcommentpublicrecordtype) | I tipi di record EMR_COMMENT_PUBLIC specificano le estensioni all'elaborazione EMF. |
| [EmfCommentRecordType](./emfcommentrecordtype) | I tipi di record di commento definiscono i formati per specificare dati privati arbitrari, incorporare record in altri formati di metafile e aggiungere comandi nuovi o per scopi speciali. |
| [EmfCommentWindowsMetaFile](./emfcommentwindowsmetafile) | Il record EMR_COMMENT_WINDOWS_METAFILE specifica un'immagine in un metafile WMF incorporato. |
| [EmfControlRecordType](./emfcontrolrecordtype) | I tipi di record di controllo definiscono l'inizio e la fine di un metafile EMF e le proprietà del metafile. |
| [EmfCreateBrushIndirect](./emfcreatebrushindirect) | Il record EMR_CREATEBRUSHINDIRECT definisce un pennello logico per le operazioni grafiche. |
| [EmfCreateColorSpace](./emfcreatecolorspace) | Il record EMR_CREATECOLORSPACE crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri ASCII. |
| [EmfCreateColorSpaceW](./emfcreatecolorspacew) | Il record EMR_CREATECOLORSPACEW crea un oggetto spazio colore logico da un profilo colore con un nome composto da caratteri Unicode. |
| [EmfCreateDibPatternBrushPt](./emfcreatedibpatternbrushpt) | Il record EMR_CREATEDIBPATTERNBRUSHPT definisce un pennello pattern per le operazioni grafiche. Il modello è specificato da un DIB. |
| [EmfCreateMonoBrush](./emfcreatemonobrush) | Il record EMR_CREATEMONOBRUSH definisce un pennello pattern monocromatico per le operazioni grafiche. Il pattern è specificato da un DIB monocromatico. |
| [EmfCreatePalette](./emfcreatepalette) | Il record EMR_CREATEPALETTE definisce una tavolozza logica per le operazioni grafiche. |
| [EmfCreatePen](./emfcreatepen) | Il record EMR_CREATEPEN definisce una penna logica per le operazioni grafiche. |
| [EmfDeleteColorSpace](./emfdeletecolorspace) | Il record EMR_DELETECOLORSPACE elimina un oggetto spazio colore logico. |
| [EmfDeleteObject](./emfdeleteobject) | Il record EMR_DELETEOBJECT elimina un oggetto grafico, specificato dal suo indice nella tabella oggetti EMF (sezione 3.1.1.1). |
| [EmfDrawEscape](./emfdrawescape) | Il record EMR_DRAWESCAPE trasmette informazioni arbitrarie a un driver della stampante. L'intento è che le informazioni comporteranno l'esecuzione del disegno. |
| [EmfDrawingRecordType](./emfdrawingrecordtype) | I tipi di record di disegno eseguono il disegno grafico. |
| [EmfEllipse](./emfellipse) | Il record EMR_ELLIPSE specifica un'ellisse. Il centro dell'ellisse è il centro del rettangolo di delimitazione specificato. L'ellisse viene delineata utilizzando la penna corrente e riempita utilizzando il pennello corrente. |
| [EmfEndPath](./emfendpath) | Questo record chiude una parentesi di percorso e seleziona il percorso definito dalla parentesi nel il contesto del dispositivo di riproduzione. |
| [EmfEof](./emfeof) | Il record EMR_EOF indica la fine del metafile e specifica una tavolozza. |
| [EmfEscapeRecordType](./emfescaperecordtype) | I tipi di record di escape eseguono le funzioni del driver della stampante. |
| [EmfExcludeClipRect](./emfexcludecliprect) | Il record EMR_EXCLUDECLIPRECT specifica una nuova area di ritaglio che consiste nell'area di ritaglio esistente meno il rettangolo specificato. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.2. |
| [EmfExtCreateFontIndirectW](./emfextcreatefontindirectw) | Il record EMR_EXTCREATEFONTINDIRECTW definisce un carattere logico per le operazioni grafiche. |
| [EmfExtCreatePen](./emfextcreatepen) | Il record EMR_EXTCREATEPEN definisce una penna logica estesa per le operazioni grafiche. È possibile specificare un DIB opzionale da utilizzare come stile di linea. |
| [EmfExtEscape](./emfextescape) | Il record EMR_EXTESCAPE trasmette informazioni arbitrarie a un driver di stampa. L'intento è che le informazioni non risulteranno nell'esecuzione del disegno. |
| [EmfExtFloodFill](./emfextfloodfill) | Il record EMR_EXTFLOODFILL riempie un'area della superficie di visualizzazione con il pennello corrente |
| [EmfExtSelectClipRgn](./emfextselectcliprgn) | Il record EMR_EXTSELECTCLIPRGN combina la regione specificata con la regione di clip corrente utilizzando la modalità specificata. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.2. |
| [EmfExtTextOutA](./emfexttextouta) | Il record EMR_EXTTEXTOUTA disegna una stringa di testo ASCII utilizzando il font e i colori del testo correnti. |
| [EmfExtTextOutW](./emfexttextoutw) | Il record EMR_EXTTEXTOUTW disegna una stringa di testo ASCII utilizzando il font e i colori del testo correnti. |
| [EmfFillPath](./emffillpath) | Il record EMR_FILLPATH chiude tutte le figure aperte nel percorso corrente e riempie l'interno del percorso di usando il pennello corrente e la modalità di riempimento del poligono. |
| [EmfFillRgn](./emffillrgn) | Il record EMR_FILLRGN riempie l'area specificata utilizzando il pennello specificato. |
| [EmfFlatternPath](./emfflatternpath) | Questo record trasforma qualsiasi curva nel percorso selezionato nel contesto del dispositivo di riproduzione ; ogni curva DEVE essere trasformata in una sequenza di linee. |
| [EmfForceUfiMapping](./emfforceufimapping) | Il record EMR_FORCEUFIAPPING forza il mappatore dei caratteri a far corrispondere i caratteri in base al loro UniversalFontId anziché alle informazioni LogFont (sezione 2.2.13). |
| [EmfFrameRgn](./emfframergn) | Il record EMR_FRAMERGN disegna un bordo attorno alla regione specificata utilizzando il pennello specificato. |
| [EmfGlsBoundedRecord](./emfglsboundedrecord) | Il record EMR_GLSBOUNDEDRECORD specifica una funzione OpenGL con un rettangolo di delimitazione per l'output. |
| [EmfGlsRecord](./emfglsrecord) | Il record EMR_GLSRECORD specifica una funzione OpenGL. |
| [EmfGradientFill](./emfgradientfill) | Il record EMR_GRADIENTFILL specifica il riempimento di rettangoli o triangoli con sfumature di colore. |
| [EmfIntersectClipRect](./emfintersectcliprect) | Il record EMR_INTERSECTCLIPRECT specifica una nuova area di ritaglio dall'intersezione dell'area di ritaglio corrente e il rettangolo specificato. Nota I campi non descritti in questa sezione sono specificati nella sezione 2.3.2. |
| [EmfInvertRgn](./emfinvertrgn) | Il record EMR_INVERTRGN inverte i colori nella regione specificata. |
| [EmfLineTo](./emflineto) | Il record EMR_LINETO specifica una linea dalla posizione corrente fino a, ma escluso, il punto specificato . Reimposta la posizione corrente al punto specificato. |
| [EmfMaskBlt](./emfmaskblt) | Il record EMR_MASKBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione, opzionalmente in combinazione con un pattern di pennello e con l'applicazione di una bitmap maschera di colore, in base alle operazioni raster in primo piano e sullo sfondo specificate. |
| [EmfMetafileHeader](./emfmetafileheader) | I tipi di record EMR_HEADER definiscono i punti di partenza dei metafile EMF e specificano le proprietà del dispositivo su cui è stata creata l'immagine nel metafile . Le informazioni nel record di intestazione consentono a metafile EMF di essere indipendenti da qualsiasi dispositivo di output specifico. Il valore del campo Dimensione può essere utilizzato per distinguere tra i diversi tipi di record EMR_HEADER elencati in precedenza in questa sezione. Sono possibili tre headers: L'intestazione di base, che è il record EmfMetafileHeader. La parte a dimensione fissa di questa intestazione è 88 byte e contiene un oggetto Header. La prima intestazione di estensione, che è il record EmfMetafileHeaderExtension1. La dimensione fissa parte di questa intestazione è di 100 byte e contiene un oggetto Header e un oggetto HeaderExtension1 (sezione 2.2.10). La seconda intestazione di estensione, che è il record EmfMetafileHeaderExtension2. La parte a dimensione fissa di questa intestazione è 108 byte, e contiene un oggetto Header, un oggetto HeaderExtension1 e un oggetto HeaderExtension2 (sezione 2.2.11). |
| [EmfMetafileHeaderExtension1](./emfmetafileheaderextension1) | Il record EmfMetafileHeaderExtension1 è il record di intestazione utilizzato nella prima estensione ai metafile EMF. Dopo il campo EmfHeaderExtension1, i campi rimanenti sono facoltativi e possono essere presenti in qualsiasi ordine. |
| [EmfMetafileHeaderExtension2](./emfmetafileheaderextension2) | Il record EmfMetafileHeaderExtension2 è il record di intestazione utilizzato nella seconda estensione ai metafile EMF . Dopo il campo EmfHeaderExtension2, i campi rimanenti sono facoltativi e possono essere presenti in qualsiasi ordine. |
| [EmfModifyWorldTransform](./emfmodifyworldtransform) | Il record EMR_MODIFYWORLDTRANSFORM modifica lo spazio mondiale corrente in page-space trasforma nel contesto del dispositivo di riproduzione. |
| [EmfMoveToEx](./emfmovetoex) | Il record EMR_MOVETOEX specifica le coordinate della nuova posizione corrente, in unità logiche. |
| [EmfNamedEscape](./emfnamedescape) | Il record MR_NAMEDESCAPE trasmette informazioni arbitrarie a un driver della stampante specificato. |
| [EmfObjectCreationRecordType](./emfobjectcreationrecordtype) | I tipi di record di creazione oggetto creano oggetti grafici. |
| [EmfObjectManipulationRecordType](./emfobjectmanipulationrecordtype) | I tipi di record di manipolazione degli oggetti gestiscono e modificano gli oggetti grafici. |
| [EmfOffsetClipRgn](./emfoffsetcliprgn) | Il record EMR_OFFSETCLIPRGN sposta l'area di ritaglio corrente nel contesto del dispositivo di riproduzione degli offset specificati. |
| [EmfOpenGlRecordType](./emfopenglrecordtype) | I tipi di record OpenGL specificano le funzioni OpenGL. |
| [EmfPaintRgn](./emfpaintrgn) | Il record EMR_PAINTRGN dipinge l'area specificata utilizzando il pennello attualmente selezionato nel contesto del dispositivo di riproduzione . |
| [EmfPathBracketRecordType](./emfpathbracketrecordtype) | I tipi di record di parentesi di percorso specificano e manipolano i percorsi tra parentesi di percorso. Nota: nessuno dei record di parentesi di percorso specifica i parametri. |
| [EmfPie](./emfpie) | Il record EMR_PIE specifica un cuneo a forma di torta delimitato dall'intersezione di un'ellisse e due radiali . La torta viene delineata usando la penna corrente e riempita usando il pennello corrente. |
| [EmfPixelFormat](./emfpixelformat) | Il record EMR_PIXELFORMAT specifica il formato pixel da utilizzare per le operazioni grafiche. |
| [EmfPlgBlt](./emfplgblt) | Il record EMR_PLGBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un parallelogramma di destinazione, con l'applicazione di una bitmap di maschera a colori. |
| [EmfPolyBezier](./emfpolybezier) | Il record EMR_POLYBEZIER specifica una o più curve di Bézier. |
| [EmfPolyBezier16](./emfpolybezier16) | Il record EMR_POLYBEZIER16 specifica una o più curve di Bezier. Le curve vengono disegnate utilizzando la penna corrente. |
| [EmfPolyBezierTo](./emfpolybezierto) | Il record EMR_POLYBEZIERTO specifica una o più curve di Bézier in base alla posizione corrente. |
| [EmfPolyBezierTo16](./emfpolybezierto16) | Il record EMR_POLYBEZIERTO16 specifica una o più curve di Bezier in base alla posizione corrente. |
| [EmfPolyDraw](./emfpolydraw) | Il record EMR_POLYDRAW specifica un insieme di segmenti di linea e curve di Bezier. |
| [EmfPolyDraw16](./emfpolydraw16) | Il record EMR_POLYDRAW16 specifica un insieme di segmenti di linea e curve di Bezier. |
| [EmfPolygon](./emfpolygon) | Il record EMR_POLYGON specifica un poligono costituito da due o più vertici collegati da linee rette. |
| [EmfPolygon16](./emfpolygon16) | Il record EMR_POLYGON16 specifica un poligono costituito da due o più vertici collegati da linee rette. Il poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità riempimento poligono. Il poligono viene chiuso automaticamente tracciando una linea dall'ultimo vertice al primo. |
| [EmfPolyline](./emfpolyline) | Il record EMR_POLYLINE specifica una serie di segmenti di linea collegando i punti nell'array specificato . |
| [EmfPolyline16](./emfpolyline16) | Il record EMR_POLYLINE16 specifica una serie di segmenti di linea collegando i punti nell'array specificato . |
| [EmfPolylineTo](./emfpolylineto) | Il record EMR_POLYLINETO specifica una o più linee rette in base alla posizione corrente. |
| [EmfPolylineTo16](./emfpolylineto16) | Il record EMR_POLYLINETO16 specifica una o più linee rette in base alla posizione corrente. Viene tracciata una linea dalla posizione corrente al primo punto specificato dal campo aPoints utilizzando la penna corrente . Per ogni linea aggiuntiva, il disegno viene eseguito dal punto finale della linea precedente al punto successivo specificato da aPoints. |
| [EmfPolyPolygon](./emfpolypolygon) | Il record EMR_POLYPOLYGON specifica una serie di poligoni chiusi. |
| [EmfPolyPolygon16](./emfpolypolygon16) | Il record EMR_POLYPOLYGON16 specifica una serie di poligoni chiusi. Ciascun poligono viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente e la modalità di riempimento del poligono. I poligoni disegnati da questo record possono sovrapporsi. |
| [EmfPolyPolyline](./emfpolypolyline) | Il record EMR_POLYPOLYLINE specifica più serie di segmenti di linea collegati. |
| [EmfPolyPolyline16](./emfpolypolyline16) | Il record EMR_POLYPOLYLINE16 specifica più serie di segmenti di linea collegati. |
| [EmfPolyTextOutA](./emfpolytextouta) | Il record EMR_POLYTEXTOUTA disegna una o più stringhe di testo ASCII utilizzando il font e i colori del testo correnti. |
| [EmfPolyTextOutW](./emfpolytextoutw) | Il record EMR_POLYTEXTOUTW disegna una o più stringhe di testo Unicode utilizzando il font e i colori del testo correnti. |
| [EmfRealizePalette](./emfrealizepalette) | Questo record mappa le voci della tavolozza dall'oggetto LogPalette corrente (sezione 2.2.17) alla tavolozza_sistema. Questo record EMF non specifica alcun parametro. |
| [EmfRecord](./emfrecord) | Classe base per record EMF Tutti i record EMF DEVONO avere una lunghezza che è un multiplo di 4 byte. Ciò è rappresentato nelle strutture generiche dei precedenti tipi di record EMF includendo i campi AlignmentPadding ove appropriato alle estremità di queste strutture. Il contenuto di AlignmentPadding fields DEVE essere sempre ignorato. Per brevità, questi campi non sono mostrati in ogni singola definizione di record EMF . |
| [EmfRectangle](./emfrectangle) | Il record EMR_RECTANGLE disegna un rettangolo. Il rettangolo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| [EmfResizePalette](./emfresizepalette) | Il record EMR_RESIZEPALETTE aumenta o diminuisce la dimensione di un oggetto LogPalette esistente (sezione 2.2.17). |
| [EmfRestoreDc](./emfrestoredc) | Il record EMR_RESTOREDC ripristina il contesto del dispositivo di riproduzione allo stato specificato. Il contesto del dispositivo di riproduzione viene ripristinato eliminando le informazioni sullo stato da uno stack creato da precedenti record EMR_SAVEDC (sezione 2.3.11). |
| [EmfRop4](./emfrop4) | Un'operazione raster quaternaria, che specifica le operazioni raster ternarie per i colori di primo piano e di sfondo di una bitmap. Questi valori definiscono come i dati colore di il rettangolo di origine devono essere combinati con i dati colore del rettangolo di destinazione. |
| [EmfRoundRect](./emfroundrect) | Il record EMR_ROUNDRECT specifica un rettangolo con angoli arrotondati. Il rettangolo viene delineato utilizzando la penna corrente e riempito utilizzando il pennello corrente. |
| [EmfSaveDc](./emfsavedc) | Salva lo stato corrente del contesto del dispositivo di riproduzione su uno stack di stati salvati dai record EMR_SAVEDC precedenti, se presenti. Lo stato è costituito da proprietà grafiche e oggetti, inclusa la bitmap attualmente selezionata, il pennello , la tavolozza, il carattere, la penna e l'area. Un record EMR_RESTOREDC viene utilizzato per ripristinare lo stato. Questo record EMF non specifica alcun parametro. |
| [EmfScaleViewportExtex](./emfscaleviewportextex) | Il record EMR_SCALEVIEWPORTTEXX ridefinisce il viewport per un contesto di dispositivo utilizzando i rapporti formati dai moltiplicandi e dai divisori specificati. |
| [EmfScaleWindowExtex](./emfscalewindowextex) | Il record EMR_SCALEWINDOWEXTEX ridefinisce la finestra per il contesto di un dispositivo di riproduzione tramite utilizzando i rapporti formati dai moltiplicandi e dai divisori specificati. |
| [EmfSelectClipPath](./emfselectclippath) | Il record EMR_SELECTCLIPPATH specifica il percorso corrente come area di ritaglio per un contesto di dispositivo di riproduzione, combinando la nuova regione con qualsiasi area di ritaglio esistente utilizzando la modalità specificata. |
| [EmfSelectObject](./emfselectobject) | Il record EMR_SELECTOBJECT aggiunge un oggetto grafico al contesto attuale del dispositivo di riproduzione del metafile . L'oggetto è specificato dal suo indice nella tabella oggetti EMF (sezione 3.1.1.1) o dal suo valore dall'enumerazione StockObject (sezione 2.1.31). |
| [EmfSelectPalette](./emfselectpalette) | Il record EMR_SELECTPALETTE specifica una tavolozza logica per il contesto del dispositivo di riproduzione. |
| [EmfSetArcDirection](./emfsetarcdirection) | Il record EMR_SETARCDIRECTION specifica la direzione del disegno da utilizzare per l'output di archi e rettangoli. |
| [EmfSetBkColor](./emfsetbkcolor) | Il record EMR_SETBKCOLOR specifica il colore di sfondo. |
| [EmfSetBkMode](./emfsetbkmode) | Il record EMR_SETBKMODE specifica la modalità di mix in background del contesto del dispositivo di riproduzione. La modalità di mix in background viene utilizzata con testo, pennelli tratteggiati e stili di penna che non sono linee continue. |
| [EmfSetBrushOrgEx](./emfsetbrushorgex) | Il record EMR_SETBRUSHORGEX specifica l'origine del pennello corrente. |
| [EmfSetColorAdjustment](./emfsetcoloradjustment) | Il record EMR_SETCOLORADJUSTMENT specifica le proprietà di regolazione del colore nel contesto del dispositivo di riproduzione . |
| [EmfSetColorSpace](./emfsetcolorspace) | Il record EMR_SETCOLORSPACE definisce l'oggetto spazio colore logico corrente per le operazioni grafiche. |
| [EmfSetDiBitsToDevice](./emfsetdibitstodevice) | Il record EMR_SETDIBITSTODEVICE specifica un trasferimento a blocchi di pixel da linee di scansione specificate di una bitmap di origine a un rettangolo di destinazione. |
| [EmfSetIcmMode](./emfseticmmode) | Il record EMR_SETICMMODE specifica la modalità di gestione del colore dell'immagine (ICM) per le operazioni grafiche. |
| [EmfSetIcmProfileA](./emfseticmprofilea) | Il record EMR_SETICMPROFILEA specifica un profilo colore in un file con un nome composto da caratteri ASCII , per l'output grafico. |
| [EmfSetIcmProfileW](./emfseticmprofilew) | Il record EMR_SETICMPROFILEW specifica un profilo colore in un file con un nome composto da caratteri Unicode, per l'output grafico. |
| [EmfSetLayout](./emfsetlayout) | Il record EMR_SETLAYOUT specifica l'ordine in cui vengono disegnati testo e grafica. |
| [EmfSetLinkedUfis](./emfsetlinkedufis) | Il record EMR_SETLINKEDUFIS imposta gli UniversalFontIds (sezione 2.2.27) dei caratteri collegati da da utilizzare durante la ricerca dei caratteri. |
| [EmfSetMapMode](./emfsetmapmode) | Il record EMR_SETMAPMODE specifica la modalità di mappatura del contesto del dispositivo di riproduzione. La modalità di mappatura specifica l'unità di misura utilizzata per trasformare le unità di spazio pagina in unità di spazio dispositivo e specifica anche l'orientamento degli assi x e y del dispositivo. |
| [EmfSetMapperFlags](./emfsetmapperflags) | Il record EMR_SETMAPPERFLAGS specifica i parametri del processo di corrispondenza dei caratteri logici con i caratteri fisici , che viene eseguito dal mappatore dei caratteri. |
| [EmfSetMetaRgn](./emfsetmetargn) | Inter imposta la meta regione corrente con la regione di ritaglio corrente per formare una nuova meta regione per il contesto del dispositivo di riproduzione. L'attuale regione di ritaglio DOVREBBE essere reimpostata su null. Questo record EMF non specifica alcun parametro. |
| [EmfSetMiterLimit](./emfsetmiterlimit) | Il record EMR_SETMITERLIMIT specifica il limite per la lunghezza dei join angolari per il contesto del dispositivo di riproduzione. |
| [EmfSetPaletteEntries](./emfsetpaletteentries) | Il record EMR_SETPALETTEENTRIES definisce i valori di colore RGB in un intervallo di voci per un oggetto LogPalette esistente (sezione 2.2.17). |
| [EmfSetPixelV](./emfsetpixelv) | Il record EMR_SETPIXELV definisce il colore del pixel alle coordinate logiche specificate. |
| [EmfSetPolyFillMode](./emfsetpolyfillmode) | Il record EMR_SETPOLYFILLMODE definisce la modalità di riempimento del poligono. |
| [EmfSetRop2](./emfsetrop2) | Il record EMR_SETROP2 definisce una modalità operativa raster binaria. |
| [EmfSetStrechBltMode](./emfsetstrechbltmode) | Il record EMR_SETSTRETCHBLTMODE specifica la modalità di estensione bitmap. |
| [EmfSetTextAlign](./emfsettextalign) | Il record EMR_SETTEXTALIGN specifica l'allineamento del testo. |
| [EmfSetTextColor](./emfsettextcolor) | Il record EMR_SETTEXTCOLOR definisce il colore del testo corrente. |
| [EmfSetTextJustification](./emfsettextjustification) | Il record EMR_SETTEXTJUSTIFICATION specifica la quantità di spazio extra da aggiungere ai caratteri break per la giustificazione del testo. |
| [EmfSetViewportExtEx](./emfsetviewportextex) | Il record EMR_SETVIEWPORTTEXX definisce l'estensione della finestra. |
| [EmfSetViewportOrgEx](./emfsetviewportorgex) | Il record EMR_SETVIEWPORTORGEX definisce l'origine del viewport. |
| [EmfSetWindowExtEx](./emfsetwindowextex) | Il record EMR_SETWINDOWEXTEX definisce l'estensione della finestra. |
| [EmfSetWindowOrgEx](./emfsetwindoworgex) | Il record EMR_SETWINDOWORGEX definisce l'origine della finestra. |
| [EmfSetWorldTransform](./emfsetworldtransform) | Il record EMR_SETWORLDTRANSFORM specifica una trasformazione per l'attuale trasformazione da spazio mondiale a spazio pagina nel contesto del dispositivo di riproduzione. |
| [EmfSmallTextOut](./emfsmalltextout) | Il record EMR_SMALLTEXTOUT emette una stringa. |
| [EmfStateRecordType](./emfstaterecordtype) | I tipi di record di stato specificano e gestiscono le proprietà grafiche che definiscono lo stato del contesto del dispositivo di riproduzione. |
| [EmfStretchBlt](./emfstretchblt) | Il record EMR_STRETCHBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario . |
| [EmfStretchDiBits](./emfstretchdibits) | Il record EMR_STRETCHDIBITS specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , opzionalmente in combinazione con un pattern di pennello, secondo un'operazione raster specificata, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario. |
| [EmfStrokeAndFillPath](./emfstrokeandfillpath) | Il record EMR_STROKEANDFILLPATH chiude tutte le figure aperte in un tracciato, traccia il contorno del tracciato utilizzando la penna corrente e ne riempie l'interno utilizzando il pennello corrente. |
| [EmfStrokePath](./emfstrokepath) | Classe EMR_STROKEPATH |
| [EmfTransformRecordType](./emftransformrecordtype) | I tipi di record di trasformazione specificano e modificano le trasformazioni da spazio mondiale a spazio pagina. |
| [EmfTransparentBlt](./emftransparentblt) | Il record EMR_TRANSPARENTBLT specifica un trasferimento a blocchi di pixel da una bitmap di origine a un rettangolo di destinazione , trattando un colore specificato come trasparente, allungando o comprimendo l'output per adattarlo alle dimensioni della destinazione, se necessario |
| [EmfVertexData](./emfvertexdata) | Oggetti che specificano i vertici di rettangoli o triangoli e i colori che corrispondono ad essi. |
| [EmfWidenPath](./emfwidenpath) | Questo record ridefinisce il percorso corrente come l'area che verrebbe dipinta se il percorso fosse disegnato utilizzando la penna attualmente selezionata nel contesto del dispositivo di riproduzione. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
