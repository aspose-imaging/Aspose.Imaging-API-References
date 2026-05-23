---
title: "Enumeración EmfExtTextOutOptions"
type: docs
weight: 100
url: /es/python-net/aspose.imaging.fileformats.emf.emf.consts/emfexttextoutoptions/
---

La enumeración ExtTextOutOptions especifica parámetros que controlan varios aspectos de la<br/>            salida de texto mediante los registros EMR_SMALLTEXTOUT (sección 2.3.5.37) y en objetos EmrText.

**Module:** [aspose.imaging.fileformats.emf.emf.consts](/imaging/python-net/aspose.imaging.fileformats.emf.emf.consts/)

**Full Name:** aspose.imaging.fileformats.emf.emf.consts.EmfExtTextOutOptions

## **Members**
| **Nombre del miembro** | **Descripción** |
| :- | :- |
| ETO_CLIPPED | Este bit indica que el texto DEBE recortarse al rectángulo. |
| ETO_GLYPH_INDEX | Este bit indica que los códigos de los caracteres en una cadena de texto de salida son en realidad <br/>            índices de los glifos de caracteres en una fuente TrueType. Los índices de glifos son específicos de la fuente, <br/>            por lo que para mostrar los caracteres correctos durante la reproducción, la fuente que se utiliza DEBE ser <br/>            idéntica a la fuente utilizada para generar los índices. |
| ETO_IGNORELANGUAGE | Este bit indica que no se debe realizar ningún procesamiento especial del sistema operativo para la colocación de glifos <br/>            en cadenas de derecha a izquierda; es decir, todo el posicionamiento de glifos DEBE ser manejado por <br/>            los registros de dibujo y estado en el metafile. |
| ETO_NO_RECT | Este bit indica que el registro no especifica un rectángulo delimitador para la salida de texto. |
| ETO_NUMERICSLATIN | Este bit indica que, para mostrar números, se DEBEN usar dígitos europeos. |
| ETO_NUMERICSLOCAL | Este bit indica que, para mostrar números, se DEBEN usar dígitos apropiados a la configuración regional. |
| ETO_OPAQUE | Este bit indica que el color de fondo actual DEBE usarse para rellenar el rectángulo |
| ETO_PDY | Este bit indica que se DEBEN proporcionar los valores de desplazamiento horizontal y vertical de los caracteres. |
| ETO_REVERSE_INDEX_MAP | Este bit está reservado y NO DEBE ser usado |
| ETO_RTLREADING | Este bit indica que el texto DEBE disponerse en orden de lectura de derecha a izquierda, <br/>            en lugar del orden predeterminado de izquierda a derecha. Esto DEBERÍA aplicarse solo cuando la fuente<br/>            seleccionada en el contexto del dispositivo de reproducción sea hebreo o árabe |
| ETO_SMALL_CHARS | Este bit indica que los códigos de los caracteres en una cadena de texto de salida son de 8 bits, <br/>            derivados de los bytes bajos de códigos de caracteres Unicode UTF16-LE de 16 bits, <br/>            en los que se asume que el byte alto es 0. |
