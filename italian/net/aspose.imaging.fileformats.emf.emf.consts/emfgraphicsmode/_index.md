---
title: EmfGraphicsMode
second_title: Riferimento all'API di Aspose.Imaging per .NET
description: Lenumerazione GraphicsMode viene utilizzata per specificare come interpretare i dati della forma come le coordinate del rettangolo.
type: docs
weight: 2680
url: /it/net/aspose.imaging.fileformats.emf.emf.consts/emfgraphicsmode/
---
## EmfGraphicsMode enumeration

L'enumerazione GraphicsMode viene utilizzata per specificare come interpretare i dati della forma come le coordinate del rettangolo.

```csharp
public enum EmfGraphicsMode
```

### I valori

| Nome | Valore | Descrizione |
| --- | --- | --- |
| GM_COMPATIBLE | `1` | Il testo TrueType DEVE essere scritto da sinistra a destra e da destra in alto, anche se il resto della grafica viene ruotato attorno all'asse x o y a causa dell'attuale trasformazione da mondo a dispositivo in il contesto del dispositivo di riproduzione . Solo l'altezza del testo DOVREBBE essere ridimensionata. Gli archi DEVONO essere disegnati usando la direzione dell'arco corrente nel contesto del dispositivo di riproduzione, ma NON DEVONO rispettare l'attuale trasformazione da mondo a dispositivo, che potrebbe richiedere una rotazione lungo l'asse x o y-asse. Il mondo- La trasformazione verso il dispositivo DOVREBBE essere modificata solo modificando le estensioni e le origini della finestra e della finestra , utilizzando i record EMR_SETWINDOWORGEX (sezione 2.3.11.30) e EMR_SETVIEWPORTEXTEX (sezione 2.3.11.28) e EMR_SETWINDOWORGEX (sezione 2.3.11.31) e EMR_SETVIEWPORTORGEX (sezione 2.3.11.30), rispettivamente. bLa modifica diretta della trasformazione utilizzando i record EMR_MODIFYWORLDTRANSFORM (sezione 2.3.12.1) o EMR_SETWORLDTRANSFORM (sezione 2.3.12.2) POTREBBE NON essere supportata. In modalità grafica GM_COMPATIBLE, i bordi inferiore e più a destra DEVONO essere esclusi quando vengono disegnati i rettangoli |
| GM_ADVANCED | `2` | L'output di testo TrueType DEVE essere completamente conforme all'attuale trasformazione da mondo a dispositivo nel contesto del dispositivo di riproduzione. Gli archi DEVONO essere disegnati in senso antiorario nello spazio mondiale; tuttavia, entrambi i punti di controllo dell'arco e gli archi stessi DEVONO rispettare pienamente l'attuale trasformazione da mondo a dispositivo nel contesto del dispositivo di riproduzione. La trasformazione da mondo a dispositivo PUÒ essere modificata direttamente utilizzando i record EMR_MODIFYWORLDTRANSFORM o EMR_SETWORLDTRANSFORM, oppure indirettamente modificando le estensioni e le origini della finestra e della finestra, utilizzando i record EMR_SETWINDOWEXTEX (sezione 2.3.11.30) ed EMR_SETVIEWPORTEXTEX (sezione 2.3.11.28), e i record EMR_SETWINDOWORGEX (sezione 2.3.11.31) ed EMR_SETVIEWPORTORGEX (sezione 2.3.11.30) , rispettivamente. Nella modalità grafica GM_ADVANCED, i bordi inferiore e più a destra DEVONO essere inclusi quando si disegnano i rettangoli. |

### Guarda anche

* spazio dei nomi [Aspose.Imaging.FileFormats.Emf.Emf.Consts](../../aspose.imaging.fileformats.emf.emf.consts)
* assemblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
