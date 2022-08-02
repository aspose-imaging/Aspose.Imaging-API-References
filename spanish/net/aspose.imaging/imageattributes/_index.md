---
title: ImageAttributes
second_title: Aspose.Imaging para la referencia de la API de .NET
description: UnImageAttributes./imageattributes El objeto contiene información sobre cómo se manipulan los colores del mapa de bits y del metarchivo durante la representación. UnImageAttributes./imageattributesEl objeto mantiene varias configuraciones de ajuste de color incluidas matrices de ajuste de color matrices de ajuste de escala de grises valores de corrección gamma tablas de mapa de color y valores de umbral de color. Durante el renderizado los colores se pueden corregir oscurecer aclarar y eliminar. Para aplicar tales manipulaciones inicialice unImageAttributes./imageattributes objeto y pasar el camino de eseImageAttributes./imageattributes objeto junto con la trayectoria de unImage./image  al método DrawImage.
type: docs
weight: 9680
url: /es/net/aspose.imaging/imageattributes/
---
## ImageAttributes class

Un[`ImageAttributes`](../imageattributes) El objeto contiene información sobre cómo se manipulan los colores del mapa de bits y del metarchivo durante la representación. Un[`ImageAttributes`](../imageattributes)El objeto mantiene varias configuraciones de ajuste de color, incluidas matrices de ajuste de color, matrices de ajuste de escala de grises, valores de corrección gamma, tablas de mapa de color y valores de umbral de color. Durante el renderizado, los colores se pueden corregir, oscurecer, aclarar y eliminar. Para aplicar tales manipulaciones, inicialice un[`ImageAttributes`](../imageattributes) objeto y pasar el camino de ese[`ImageAttributes`](../imageattributes) objeto (junto con la trayectoria de un[`Image`](../image) ) al método DrawImage.

```csharp
public sealed class ImageAttributes
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [ImageAttributes](imageattributes)() | Constructor predeterminado |

## Métodos

| Nombre | Descripción |
| --- | --- |
| [ClearBrushRemapTable](../../aspose.imaging/imageattributes/clearbrushremaptable)() | Borra la tabla de reasignación de color del pincel de este[`ImageAttributes`](../imageattributes) objeto. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey)() | Borra la clave de color (rango de transparencia) para la categoría predeterminada. |
| [ClearColorKey](../../aspose.imaging/imageattributes/clearcolorkey#clearcolorkey_1)(ColorAdjustType) | Borra la clave de color (rango de transparencia) para una categoría específica. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix)() | Borra la matriz de ajuste de color para la categoría predeterminada. |
| [ClearColorMatrix](../../aspose.imaging/imageattributes/clearcolormatrix#clearcolormatrix_1)(ColorAdjustType) | Borra la matriz de ajuste de color para una categoría específica. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma)() | Deshabilita la corrección gamma para la categoría predeterminada. |
| [ClearGamma](../../aspose.imaging/imageattributes/cleargamma#cleargamma_1)(ColorAdjustType) | Deshabilita la corrección gamma para una categoría específica. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop)() | Borra la configuración NoOp para la categoría predeterminada. |
| [ClearNoOp](../../aspose.imaging/imageattributes/clearnoop#clearnoop_1)(ColorAdjustType) | Borra la configuración de NoOp para una categoría específica. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel)() | Borra la configuración del canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [ClearOutputChannel](../../aspose.imaging/imageattributes/clearoutputchannel#clearoutputchannel_1)(ColorAdjustType) | Borra la configuración del canal de salida (cian-magenta-amarillo-negro) para una categoría específica. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile)() | Borra la configuración del perfil de color del canal de salida para la categoría predeterminada. |
| [ClearOutputChannelColorProfile](../../aspose.imaging/imageattributes/clearoutputchannelcolorprofile#clearoutputchannelcolorprofile_1)(ColorAdjustType) | Borra la configuración del perfil de color del canal de salida para una categoría específica. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable)() | Borra la tabla de reasignación de color para la categoría predeterminada. |
| [ClearRemapTable](../../aspose.imaging/imageattributes/clearremaptable#clearremaptable_1)(ColorAdjustType) | Borra la tabla de reasignación de colores para una categoría específica. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold)() | Borra el valor de umbral para la categoría predeterminada. |
| [ClearThreshold](../../aspose.imaging/imageattributes/clearthreshold#clearthreshold_1)(ColorAdjustType) | Borra el valor de umbral para una categoría específica. |
| [SetBrushRemapTable](../../aspose.imaging/imageattributes/setbrushremaptable)(ColorMap[]) | Establece la tabla de reasignación de color para la categoría de pincel. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey)(Color, Color) | Establece la clave de color para la categoría predeterminada. |
| [SetColorKey](../../aspose.imaging/imageattributes/setcolorkey#setcolorkey_1)(Color, Color, ColorAdjustType) | Establece la clave de color (rango de transparencia) para una categoría específica. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices)(ColorMatrix, ColorMatrix) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_1)(ColorMatrix, ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para la categoría predeterminada. |
| [SetColorMatrices](../../aspose.imaging/imageattributes/setcolormatrices#setcolormatrices_2)(ColorMatrix, ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color y la matriz de ajuste de escala de grises para una categoría específica. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix)(ColorMatrix) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_1)(ColorMatrix, ColorMatrixFlag) | Establece la matriz de ajuste de color para la categoría predeterminada. |
| [SetColorMatrix](../../aspose.imaging/imageattributes/setcolormatrix#setcolormatrix_2)(ColorMatrix, ColorMatrixFlag, ColorAdjustType) | Establece la matriz de ajuste de color para una categoría específica. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma)(float) | Establece el valor gamma para la categoría predeterminada. |
| [SetGamma](../../aspose.imaging/imageattributes/setgamma#setgamma_1)(float, ColorAdjustType) | Establece el valor gamma para una categoría específica. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop)() | Desactiva el ajuste de color para la categoría predeterminada. |
| [SetNoOp](../../aspose.imaging/imageattributes/setnoop#setnoop_1)(ColorAdjustType) | Desactiva el ajuste de color para una categoría específica. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel)(ColorChannelFlag) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para la categoría predeterminada. |
| [SetOutputChannel](../../aspose.imaging/imageattributes/setoutputchannel#setoutputchannel_1)(ColorChannelFlag, ColorAdjustType) | Establece el canal de salida CMYK (cian-magenta-amarillo-negro) para una categoría específica. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile)(string) | Establece el archivo de perfil de color del canal de salida para la categoría predeterminada. |
| [SetOutputChannelColorProfile](../../aspose.imaging/imageattributes/setoutputchannelcolorprofile#setoutputchannelcolorprofile_1)(string, ColorAdjustType) | Establece el archivo de perfil de color del canal de salida para una categoría específica. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable)(ColorMap[]) | Establece la tabla de reasignación de colores para la categoría predeterminada. |
| [SetRemapTable](../../aspose.imaging/imageattributes/setremaptable#setremaptable_1)(ColorMap[], ColorAdjustType) | Establece la tabla de reasignación de colores para una categoría específica. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold)(float) | Establece el umbral (rango de transparencia) para la categoría predeterminada. |
| [SetThreshold](../../aspose.imaging/imageattributes/setthreshold#setthreshold_1)(float, ColorAdjustType) | Establece el umbral (rango de transparencia) para una categoría específica. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode)(WrapMode) | Establece el modo de ajuste que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_1)(WrapMode, Color) | Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |
| [SetWrapMode](../../aspose.imaging/imageattributes/setwrapmode#setwrapmode_2)(WrapMode, Color, bool) | Establece el modo de ajuste y el color que se usa para decidir cómo colocar una textura en mosaico a lo largo de una forma o en los límites de la forma. Una textura se coloca en mosaico a lo largo de una forma para rellenarla cuando la textura es más pequeña que la forma que está rellenando. |

### Ver también

* espacio de nombres [Aspose.Imaging](../../aspose.imaging)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
