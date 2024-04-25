---
title: Aspose.Imaging.FileFormats.Emf.EmfPlus.Records
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lo spazio dei nomi contiene i tipi MS-EMFPLUS Enhanced Metafile Format Plus Extensions 2.3 EMF Records
type: docs
weight: 390
url: /it/aspose.imaging.fileformats.emf.emfplus.records/
---
Lo spazio dei nomi contiene i tipi [MS-EMFPLUS]: Enhanced Metafile Format Plus Extensions 2.3 EMF+ Records

## Classi

| Classe | Descrizione |
| --- | --- |
| [EmfPlusBeginContainer](./emfplusbegincontainer) | Il record EmfPlusBeginContainer apre un nuovo contenitore di stato grafico e specifica una trasformazione per esso. |
| [EmfPlusBeginContainerNoParams](./emfplusbegincontainernoparams) | Il record EmfPlusBeginContainerNoParams apre un nuovo contenitore di stato grafico. |
| [EmfPlusClear](./emfplusclear) | Il record EmfPlusClear cancella lo spazio delle coordinate di output e lo inizializza con un colore di sfondo e una trasparenza |
| [EmfPlusClippingRecordType](./emfplusclippingrecordtype) | I tipi di record di ritaglio specificano le aree di ritaglio e le operazioni. |
| [EmfPlusComment](./emfpluscomment) | Il record EmfPlusComment specifica dati privati arbitrari. |
| [EmfPlusControlRecordType](./emfpluscontrolrecordtype) | I tipi di record di controllo specificano i parametri globali per l'elaborazione del metafile EMF+. |
| [EmfPlusDrawArc](./emfplusdrawarc) | Il record EmfPlusDrawArc specifica il disegno dell'arco di un'ellisse. |
| [EmfPlusDrawBeziers](./emfplusdrawbeziers) | Il record EmfPlusDrawBeziers specifica il disegno di una sequenza di curve di Bezier collegate. L'ordine dei punti dati Bezier è il punto iniziale, il punto di controllo 1, il punto di controllo 2 e il punto finale. Per ulteriori informazioni, vedere [MSDN-DrawBeziers]. |
| [EmfPlusDrawClosedCurve](./emfplusdrawclosedcurve) | Il record EmfPlusDrawClosedCurve specifica il disegno di una spline cardinale chiusa |
| [EmfPlusDrawCurve](./emfplusdrawcurve) | Il record EmfPlusDrawCurve specifica il disegno di una spline cardinale NOTA: ObjectID (1 byte): l'indice di un oggetto EmfPlusPen (sezione 2.2.1.7) nella tabella oggetti EMF+ per disegnare la curva. Il valore DEVE essere da zero a 63, inclusi. |
| [EmfPlusDrawDriverString](./emfplusdrawdriverstring) | Il record EmfPlusDrawDriverString specifica l'output di testo con le posizioni dei caratteri. |
| [EmfPlusDrawEllipse](./emfplusdrawellipse) | Il record EmfPlusDrawEllipse specifica il disegno di un'ellisse. |
| [EmfPlusDrawImage](./emfplusdrawimage) | Il record EmfPlusDrawImage specifica il disegno di un'immagine in scala. |
| [EmfPlusDrawImagePoints](./emfplusdrawimagepoints) | Il record EmfPlusDrawImagePoints specifica il disegno di un'immagine in scala all'interno di un parallelogramma. |
| [EmfPlusDrawingRecordType](./emfplusdrawingrecordtype) | I tipi di record di disegno specificano l'output grafico. |
| [EmfPlusDrawLines](./emfplusdrawlines) | Il record EmfPlusDrawlLines specifica il disegno di una serie di linee connesse |
| [EmfPlusDrawPath](./emfplusdrawpath) | Il record EmfPlusDrawPath specifica il disegno di un percorso grafico. |
| [EmfPlusDrawPie](./emfplusdrawpie) | Il record EmfPlusDrawPie specifica il disegno di una sezione dell'interno di un'ellisse. |
| [EmfPlusDrawRects](./emfplusdrawrects) | Il record EmfPlusDrawRects specifica il disegno di una serie di rettangoli |
| [EmfPlusDrawString](./emfplusdrawstring) | Il record EmfPlusDrawString specifica l'output di testo con formattazione stringa |
| [EmfPlusEndContainer](./emfplusendcontainer) | Il record EmfPlusEndContainer chiude un contenitore dello stato grafico che era stato precedentemente aperto da un'operazione di inizio contenitore. |
| [EmfPlusEndOfFile](./emfplusendoffile) | Il record EmfPlusEndOfFile specifica la fine dei dati EMF+ nel metafile. |
| [EmfPlusFillClosedCurve](./emfplusfillclosedcurve) | Il record EmfPlusFillClosedCurve specifica il riempimento dell'interno di una spline cardinale chiusa |
| [EmfPlusFillEllipse](./emfplusfillellipse) | Il record EmfPlusFillEllipse specifica il riempimento dell'interno di un'ellisse |
| [EmfPlusFillPath](./emfplusfillpath) | Fill path record FLAGS: intero senza segno a 16 bit che fornisce informazioni su come deve essere eseguita l'operazione, e sulla struttura del record. 0 1 2 3 4 5 6 7 8 9 1 0 1 2 3 4 5 6 7 8 9 2 0 1 2 3 4 5 6 7 8 9 3 0 1 SXXXXXXX &#x7C; ObjectId &#x7C; S (1 bit): questo bit indica il tipo di dati nel campo BrushId. Se impostato, BrushId specifica un colore come oggetto EmfPlusARGB (sezione 2.2.2.1). Se deselezionato, BrushId contiene l'indice di un oggetto EmfPlusBrush (sezione 2.2.1.1) nella tabella oggetti EMF+. X (1 bit): riservato e DEVE essere ignorato. ObjectId (1 byte): l'indice dell'oggetto EmfPlusPath ( sezione 2.2.1.6) da compilare, nella Tabella Oggetti EMF+. Il valore DEVE essere da zero a 63, inclusi. |
| [EmfPlusFillPie](./emfplusfillpie) | Il record EmfPlusFillPie specifica il riempimento di una sezione dell'interno di un'ellisse |
| [EmfPlusFillPolygon](./emfplusfillpolygon) | Il record EmfPlusFillPolygon specifica il riempimento dell'interno di un poligono. |
| [EmfPlusFillRects](./emfplusfillrects) | Il record EmfPlusFillRects specifica il riempimento degli interni di una serie di rettangoli |
| [EmfPlusFillRegion](./emfplusfillregion) | Il record EmfPlusFillRegion specifica il riempimento dell'interno di una regione grafica |
| [EmfPlusGetDc](./emfplusgetdc) | Il record EmfPlusGetDC specifica che i record EMF successivi incontrati nel metafile DOVREBBE essere elaborati. |
| [EmfPlusHeader](./emfplusheader) | Il record EmfPlusHeader specifica l'inizio dei dati EMF+ nel metafile. Il record EmfPlusHeader DEVE essere incorporato in un record EMF EMR_COMMENT_EMFPLUS, che DEVE essere il record immediatamente successivo all'intestazione EMF nel metafile. Il record EMR_COMMENT_EMFPLUS è specificato nella sezione [MS-EMF] 2.3.3.2. |
| [EmfPlusMultiplyWorldTransform](./emfplusmultiplyworldtransform) | Il record EmfPlusMultiplyWorldTransform moltiplica la trasformazione dello spazio mondiale corrente per una matrice di trasformazione specificata . |
| [EmfPlusObject](./emfplusobject) | Il record EmfPlusObject specifica un oggetto da utilizzare nelle operazioni grafiche. La definizione dell'oggetto può estendersi su più record, che è indicato dal valore del campo Flags. |
| [EmfPlusObjectRecordType](./emfplusobjectrecordtype) | I tipi di record oggetto definiscono oggetti grafici riutilizzabili. |
| [EmfPlusOffsetClip](./emfplusoffsetclip) | Il record EmfPlusOffsetClip applica una trasformazione di traslazione all'area di ritaglio corrente per lo spazio mondiale. La nuova area di ritaglio corrente viene impostata sul risultato della trasformazione di traslazione. |
| [EmfPlusPropertyRecordType](./emfpluspropertyrecordtype) | I tipi di record di proprietà specificano le proprietà del contesto del dispositivo di riproduzione. |
| [EmfPlusRecord](./emfplusrecord) | Il tipo di record di base Emf+. |
| [EmfPlusResetClip](./emfplusresetclip) | Il record EmfPlusResetClip reimposta la regione di ritaglio corrente per lo spazio mondiale su infinito. |
| [EmfPlusResetWorldTransform](./emfplusresetworldtransform) | Il record EmfPlusResetWorldTransform reimposta la trasformazione dello spazio mondiale corrente sulla matrice di identificazione. |
| [EmfPlusRestore](./emfplusrestore) | Il record EmfPlusRestore ripristina lo stato grafico, identificato da un indice specificato, da uno stack di stati grafici salvati. |
| [EmfPlusRotateWorldTransform](./emfplusrotateworldtransform) | Il record EmfPlusRotateWorldTransform esegue una rotazione sulla trasformazione dello spazio mondiale corrente. |
| [EmfPlusSave](./emfplussave) | Il record EmfPlusSave salva lo stato grafico, identificato da un indice specificato, su una pila di stati grafici salvati. |
| [EmfPlusScaleWorldTransform](./emfplusscaleworldtransform) | Il record EmfPlusScaleWorldTransform esegue un ridimensionamento sulla trasformazione dello spazio mondiale corrente. |
| [EmfPlusSerializableObject](./emfplusserializableobject) | Il record EmfPlusSerializableObject definisce un blocco di parametri degli effetti immagine che è stato serializzato in un buffer di dati. |
| [EmfPlusSetAntiAliasMode](./emfplussetantialiasmode) | Il record EmfPlusSetAntiAliasMode specifica la modalità anti-alias per l'output di testo. |
| [EmfPlusSetClipPath](./emfplussetclippath) | Il record EmfPlusSetClipPath combina l'area di ritaglio corrente con un percorso grafico. La nuova area di ritaglio corrente viene impostata sul risultato dell'operazione CombineMode. |
| [EmfPlusSetClipRect](./emfplussetcliprect) | Il record EmfPlusSetClipRect combina l'area di ritaglio corrente con un rettangolo. |
| [EmfPlusSetClipRegion](./emfplussetclipregion) | Il record EmfPlusSetClipRegion combina l'area di ritaglio corrente con un'altra area grafica. La nuova area di ritaglio corrente viene impostata sul risultato dell'esecuzione dell'operazione CombineMode su l'area di ritaglio corrente precedente e l'oggetto EmfPlusRegion specificato. |
| [EmfPlusSetCompositingMode](./emfplussetcompositingmode) | Il record EmfPlusSetCompositingMode specifica come i colori di origine vengono combinati con i colori di sfondo. |
| [EmfPlusSetCompositingQuality](./emfplussetcompositingquality) | Il record EmfPlusSetCompositingQuality specifica il livello di qualità desiderato per la creazione di immagini composite da più oggetti. |
| [EmfPlusSetInterpolationMode](./emfplussetinterpolationmode) | Il record EmfPlusSetInterpolationMode specifica come viene eseguito il ridimensionamento dell'immagine, inclusi allungamento e rimpicciolimento. |
| [EmfPlusSetPageTransform](./emfplussetpagetransform) | Il record EmfPlusSetPageTransform specifica i fattori di scala e le unità per convertire le coordinate dello spazio della pagina in coordinate dello spazio del dispositivo. |
| [EmfPlusSetPixelOffsetMode](./emfplussetpixeloffsetmode) | Il record EmfPlusSetPixelOffsetMode specifica come i pixel sono centrati rispetto alle coordinate della superficie di disegno. |
| [EmfPlusSetRenderingOrigin](./emfplussetrenderingorigin) | Il record EmfPlusSetRenderingOrigin specifica l'origine del rendering per l'output grafico. |
| [EmfPlusSetTextContrast](./emfplussettextcontrast) | Il record EmfPlusSetTextContrast specifica il contrasto del testo in base al valore di correzione gamma. |
| [EmfPlusSetTextRenderingHint](./emfplussettextrenderinghint) | Il record EmfPlusSetTextRenderingHint specifica la qualità del rendering del testo, incluso il tipo di anti-aliasing. |
| [EmfPlusSetTsClip](./emfplussettsclip) | Il record EmfPlusSetTSClip specifica le aree di ritaglio nel contesto del dispositivo grafico per un server terminal. |
| [EmfPlusSetTsGraphics](./emfplussettsgraphics) | Il record EmfPlusSetTSGraphics specifica lo stato di un contesto di dispositivo grafico per un server terminal. |
| [EmfPlusSetWorldTransform](./emfplussetworldtransform) | Il record EmfPlusSetWorldTransform imposta la trasformazione mondiale in base ai valori in una matrice di trasformazione specificata . |
| [EmfPlusStateRecordType](./emfplusstaterecordtype) | I tipi di record di stato specificano le operazioni sullo stato del contesto del dispositivo di riproduzione. |
| [EmfPlusTerminalServerRecordType](./emfplusterminalserverrecordtype) | I tipi di record del server terminal specificano l'elaborazione grafica su un server terminal. I seguenti sono tipi di record del server terminal EMF+. |
| [EmfPlusTransformRecordType](./emfplustransformrecordtype) | I tipi di record di trasformazione specificano le proprietà e le trasformazioni sugli spazi di coordinate. |
| [EmfPlusTranslateWorldTransform](./emfplustranslateworldtransform) | Il record EmfPlusTranslateWorldTransform esegue una traduzione sulla trasformazione dello spazio mondiale corrente. |

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
