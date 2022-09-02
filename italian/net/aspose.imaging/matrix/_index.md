---
title: Matrix
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Sostituisce la matrice GDI.
type: docs
weight: 10550
url: /it/net/aspose.imaging/matrix/
---
## Matrix class

Sostituisce la matrice GDI+.

```csharp
public class Matrix
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [Matrix](matrix#constructor)() | Inizializza una nuova istanza della classe Matrix come matrice di identità. |
| [Matrix](matrix#constructor_1)(Matrix) | Crea una copia di[`Matrix`](../matrix) classe. |
| [Matrix](matrix#constructor_2)(Rectangle, Point[]) | Inizializza una nuova istanza di[`Matrix`](../matrix) classe alla trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| [Matrix](matrix#constructor_3)(RectangleF, PointF[]) | Inizializza una nuova istanza di[`Matrix`](../matrix) classe alla trasformazione geometrica definita dal rettangolo e dall'array di punti specificati. |
| [Matrix](matrix#constructor_4)(float, float, float, float, float, float) | Inizializza una nuova istanza di[`Matrix`](../matrix) classe. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [Elements](../../aspose.imaging/matrix/elements) { get; } | Ottiene una matrice di valori a virgola mobile che rappresenta gli elementi di questo[`Matrix`](../matrix) . |
| [M11](../../aspose.imaging/matrix/m11) { get; } | Ottiene l'elemento della matrice nella prima riga e prima colonna. Rappresenta la scala lungo l'asse X. |
| [M12](../../aspose.imaging/matrix/m12) { get; } | Ottiene l'elemento della matrice nella prima riga nella seconda colonna. Rappresenta il taglio lungo l'asse Y. |
| [M21](../../aspose.imaging/matrix/m21) { get; } | Ottiene l'elemento della matrice nella prima colonna della seconda riga. Rappresenta il taglio lungo l'asse X. |
| [M22](../../aspose.imaging/matrix/m22) { get; } | Ottiene l'elemento della matrice nella seconda riga della seconda colonna. Rappresenta la scala lungo l'asse Y. |
| [M31](../../aspose.imaging/matrix/m31) { get; } | Ottiene l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse X. |
| [M32](../../aspose.imaging/matrix/m32) { get; } | Ottiene l'elemento della matrice alla terza riga prima colonna. Rappresenta la traslazione lungo l'asse Y. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Equals](../../aspose.imaging/matrix/equals)(object) | Determina se è specificatoObject è uguale a questa istanza. |
| [GetElements](../../aspose.imaging/matrix/getelements)() | Ottiene la copia degli elementi della matrice. |
| override [GetHashCode](../../aspose.imaging/matrix/gethashcode)() | Restituisce un codice hash per questa istanza. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply)(Matrix) | Moltiplica questa matrice per la matrice specificata nel parametro della matrice utilizzando (predefinito) Ordine antepone. |
| [Multiply](../../aspose.imaging/matrix/multiply#multiply_1)(Matrix, MatrixOrder) | Moltiplica questa matrice per la matrice specificata nel parametro matrix e nell'ordine specificato nel parametro order. |
| [Reset](../../aspose.imaging/matrix/reset)() | Reimposta questa matrice per avere gli elementi della matrice di identità. |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate)(float) | Applica una rotazione in senso orario di un importo specificato nel parametro dell'angolo, attorno all'origine (coordinate xey zero) per questa matrice nell'ordine predefinito (Anteprima). |
| [Rotate](../../aspose.imaging/matrix/rotate#rotate_1)(float, MatrixOrder) | Applica una rotazione in senso orario di un importo specificato nel parametro dell'angolo, attorno all'origine (coordinate xey zero) per questa matrice nell'ordine specificato. |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat)(float, PointF) | Applica una rotazione in senso orario attorno al punto specificato a questa matrice nell'ordine predefinito (Anteprima). |
| [RotateAt](../../aspose.imaging/matrix/rotateat#rotateat_1)(float, PointF, MatrixOrder) | Applica una rotazione in senso orario attorno al punto specificato a questa matrice nell'ordine specificato. |
| [Scale](../../aspose.imaging/matrix/scale#scale)(float, float) | Applica il vettore di scala specificato (scaleX e scaleY) a questa matrice utilizzando (predefinito) Ordine di anteporre. |
| [Scale](../../aspose.imaging/matrix/scale#scale_1)(float, float, MatrixOrder) | Applica il vettore di scala specificato (scaleX e scaleY) a questo[`Matrix`](../matrix) utilizzando l'ordine specificato. |
| override [ToString](../../aspose.imaging/matrix/tostring)() | Restituisce aString che rappresenta questa istanza. |
| [TransformPoints](../../aspose.imaging/matrix/transformpoints)(PointF[]) | Applica la trasformata geometrica rappresentata da questo[`Matrix`](../matrix) una matrice di punti specificata. |
| [Translate](../../aspose.imaging/matrix/translate#translate)(float, float) | Applica a questo il vettore di traslazione specificato[`Matrix`](../matrix) utilizzando (predefinito) Ordine anteposto. |
| [Translate](../../aspose.imaging/matrix/translate#translate_1)(float, float, MatrixOrder) | Applica il vettore di traslazione specificato a questa matrice nell'ordine specificato. |
| static [Equals](../../aspose.imaging/matrix/equals)(Matrix, Matrix) | Determina se due matrici sono uguali. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [TypeFlip](../../aspose.imaging/matrix/typeflip) | Questo bit flag indica che la trasformazione definita da questo oggetto esegue un capovolgimento dell'immagine speculare attorno a un asse che cambia il sistema di coordinate normalmente destrorso in un sistema sinistro oltre alle conversioni indicate da altri bit flag. Un sistema di coordinate destrorso è quello in cui l'asse X positivo ruota in senso antiorario per sovrapporre l'asse Y positivo in modo simile alla direzione in cui le dita della mano destra si piegano quando si fissa il pollice. Un sistema di coordinate per mancini è quello in cui ruota l'asse X positivo in senso orario per sovrapporre l'asse Y positivo in modo simile alla direzione in cui le dita della mano sinistra si curvano. Non esiste un modo matematico per determinare l'angolo della trasformazione di ribaltamento o specchiatura originale poiché tutti gli angoli di ribaltamento sono identici data una rotazione di regolazione appropriata. NOTA: TypeFlip è stato aggiunto dopo GENERAL_TRANSFORM era in circolazione pubblica e i bit flag non potevano più essere convenientemente rinumerati senza introdurre incompatibilità binaria nel codice esterno . |
| const [TypeGeneralRotation](../../aspose.imaging/matrix/typegeneralrotation) | Questo bit flag indica che la trasformazione definita da questo oggetto esegue una rotazione di un angolo arbitrario oltre alle conversioni indicate da altri bit flag. Una rotazione cambia gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo bit flag si esclude a vicenda con il |
| const [TypeGeneralScale](../../aspose.imaging/matrix/typegeneralscale) | Una scala generale moltiplica la lunghezza dei vettori per importi diversi nelle direzioni xey senza modificare l'angolo tra i vettori perpendicolari. Questo bit flag si esclude a vicenda con il flag TypeUniformScale. |
| const [TypeGeneralTransform](../../aspose.imaging/matrix/typegeneraltransform) | Questa costante indica che la trasformazione definita da questo oggetto esegue una conversione arbitraria delle coordinate di input. Se questa trasformazione può essere classificata da una qualsiasi delle costanti precedenti, il tipo sarà la costante TypeIdentity o una combinazione di del flag appropriato bit per le varie conversioni coordinate eseguite da questa trasformazione. |
| const [TypeIdentity](../../aspose.imaging/matrix/typeidentity) | Una trasformazione di identità è quella in cui le coordinate di output sono sempre le stesse delle coordinate di input. Se questa trasformazione è diversa dalla trasformazione di identità, il tipo sarà o la costante GENERAL_TRANSFORM o una combinazione di dei bit flag appropriati per le varie conversioni coordinate eseguite da questa trasformazione. |
| const [TypeMaskRotation](../../aspose.imaging/matrix/typemaskrotation) | Questa costante è una maschera di bit per qualsiasi bit di flag di rotazione. |
| const [TypeMaskScale](../../aspose.imaging/matrix/typemaskscale) | Questa costante è una maschera di bit per qualsiasi bit flag di scala. |
| const [TypeQuadrantRotation](../../aspose.imaging/matrix/typequadrantrotation) | Questo bit flag indica che la trasformazione definita da questo oggetto esegue una rotazione del quadrante di alcuni multipli di 90 gradi in oltre alle conversioni indicate da altri bit flag. Una rotazione cambia gli angoli dei vettori della stessa quantità indipendentemente dalla direzione originale del vettore e senza modificare la lunghezza del vettore. Questo bit flag si esclude a vicenda con il flag TypeGeneralRotation. |
| const [TypeTranslation](../../aspose.imaging/matrix/typetranslation) | Una traslazione sposta le coordinate di una quantità costante in x e y senza modificare la lunghezza o l'angolo dei vettori. |
| const [TypeUniformScale](../../aspose.imaging/matrix/typeuniformscale) | Una scala uniforme moltiplica la lunghezza dei vettori per la stessa quantità in entrambe le direzioni xey senza modificare l'angolo tra vettori. Questo bit flag si esclude a vicenda con il flag TypeGeneralScale. |

### Osservazioni

La maggior parte degli algoritmi presi da AffineTransform.java di Sun. Nomi Java per gli elementi di matrice utilizzati internamente. Mappa dei nomi java in quelli .net alla descrizione: m00 M11 Scale X m10 M12 Shear Y m01 M21 Shear X m11 M22 Scale Y_0 Traduci X m12 M32 Traduci Y

### Guarda anche

* spazio dei nomi [Aspose.Imaging](../../aspose.imaging)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
