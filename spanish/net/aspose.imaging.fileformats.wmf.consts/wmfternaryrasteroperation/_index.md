---
title: WmfTernaryRasterOperation
second_title: Aspose.Imaging para la referencia de la API de .NET
description: La enumeración especifica códigos de operación de ráster ternarios que definen cómo combinar los bits en un mapa de bits de origen con los bits en un mapa de bits de destino.
type: docs
weight: 8330
url: /es/net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/
---
## WmfTernaryRasterOperation enumeration

La enumeración especifica códigos de operación de ráster ternarios, que definen cómo combinar los bits en un mapa de bits de origen con los bits en un mapa de bits de destino.

```csharp
public enum WmfTernaryRasterOperation
```

### Valores

| Nombre | Valor | Descripción |
| --- | --- | --- |
| BLACKNESS | `66` | Rellena el rectángulo de destino utilizando el color asociado con el índice 0 en la paleta física. (Este color es negro para la paleta física predeterminada.) |
| DPSOON | `66185` |  |
| DPSONA | `134281` |  |
| PSON | `196778` |  |
| SDPONA | `265352` |  |
| DPON | `327849` |  |
| PDSXNON | `395365` |  |
| PDSAON | `459461` |  |
| SDPNAA | `528136` |  |
| PDSXON | `590405` |  |
| DPNA | `656169` |  |
| PSDNAON | `723754` |  |
| SPNA | `787236` |  |
| PDSNAON | `854821` |  |
| PDSONON | `919717` |  |
| PN | `983041` |  |
| PDSONA | `1051781` |  |
| NOTSRCERASE | `1114278` | Combina los colores de los rectángulos de origen y destino mediante el operador booleano OR y luego invierte el color resultante . |
| SDPXNON | `1181800` |  |
| SDPAON | `1245896` |  |
| DPSXNON | `1312873` |  |
| DPSAON | `1376969` |  |
| PSDPSANAXX | `1465546` |  |
| SSPXDSXAXN | `1514836` |  |
| SPXPDXA | `1576281` |  |
| SDPSANAXN | `1645768` |  |
| PDSPAOX | `1705669` |  |
| SDPSXAXN | `1771368` |  |
| PSDPAOX | `1836746` |  |
| DSPDXAXN | `1902438` |  |
| PDSOX | `1966501` |  |
| PDSOAN | `2032517` |  |
| DPSNAA | `2101001` |  |
| SDPXON | `2163272` |  |
| DSNA | `2229030` |  |
| SPDNAON | `2296612` |  |
| SPXDSXA | `2362709` |  |
| PDSPANAXN | `2432197` |  |
| SDPSAOX | `2492104` |  |
| SDPSXNOX | `2562152` |  |
| DPSXA | `2622313` |  |
| PSDPSAOXXN | `2692810` |  |
| DPSANA | `2755785` |  |
| SSPXPDXAXN | `2825560` |  |
| SPDSOAX | `2885508` |  |
| PSDNOX | `2950666` |  |
| PSDPXOX | `3016266` |  |
| PSDNOAN | `3083818` |  |
| PSNA | `3146538` |  |
| SDPNAON | `3214120` |  |
| SDPSOOX | `3278472` |  |
| NOTSRCCOPY | `3342344` | Copia el rectángulo de origen invertido en el destino. |
| SPDSAOX | `3409604` |  |
| SPDSXNOX | `3479652` |  |
| SDPOX | `3539368` |  |
| SDPOAN | `3605384` |  |
| PSDPOAX | `3671946` |  |
| SPDNOX | `390604` |  |
| SPDSXOX | `3802692` |  |
| SPDNOAN | `3870244` |  |
| PSX | `3932234` |  |
| SPDSONOX | `4004004` |  |
| SPDSNAOX | `4070180` |  |
| PSAN | `4129002` |  |
| PSDNAA | `4198154` |  |
| DPSXON | `4260425` |  |
| SDXPDXA | `4328797` |  |
| SPDSANAXN | `4398276` |  |
| SRCERASE | `4457256` | Combina los colores invertidos del rectángulo de destino con los colores del rectángulo de origen utilizando el operador booleano AND . |
| DPSNAON | `4524841` |  |
| DSPDAOX | `4589254` |  |
| PSDPXAXN | `4654954` |  |
| SDPXA | `4719464` |  |
| PDSPDAOXXN | `4789957` |  |
| DPSDOAX | `4851593` |  |
| PDSNOX | `4916741` |  |
| SDPANA | `4984008` |  |
| SSPXDSXOXN | `5052756` |  |
| PDSPXOX | `5113413` |  |
| PDSNOAN | `5180965` |  |
| PDNA | `5243685` |  |
| DSPNAON | `5311270` |  |
| DPSDAOX | `5375689` |  |
| SPDSXAXN | `5441380` |  |
| DPSONON | `5507241` |  |
| DSTINVERT | `5570569` | Invierte el rectángulo de destino. |
| DPSOX | `5636521` |  |
| DPSOAN | `5702537` |  |
| PDSPOAX | `5769093` |  |
| DPSNOX | `5834249` |  |
| PATINVERT | `5898313` | Combina los colores del pincel actualmente seleccionado en hdcDest, con los colores del rectángulo de destino by utilizando el operador booleano XOR. |
| DPSDONOX | `5970089` |  |
| DPSDXOX | `6030921` |  |
| DPSNOAN | `6098473` |  |
| DPSDNAOX | `6167337` |  |
| DPAN | `6226153` |  |
| PDSXA | `6292325` |  |
| DSPDSAOXXN | `6362822` |  |
| DSPDOAX | `6424454` |  |
| SDPNOX | `6489608` |  |
| SDPSOAX | `6555528` |  |
| DSPNOX | `6620678` |  |
| SRCINVERT | `6684742` | Combina los colores de los rectángulos de origen y destino mediante el operador booleano XOR. |
| SDPSONOX | `6756520` |  |
| DSPDSONOXXN | `6838438` |  |
| PDSXXN | `6881605` |  |
| DPSAX | `6947305` |  |
| PSDPSOAXXN | `7018378` |  |
| SDPAX | `7078376` |  |
| PDSPDOAXXN | `7149445` |  |
| SDPSNOAX | `7216680` |  |
| PDXNAN | `7277669` |  |
| PDSANA | `7343301` |  |
| SSDXPDXAXN | `7413084` |  |
| SDPSXOX | `7472712` |  |
| SDPNOAN | `7540264` |  |
| DSPDXOX | `7603782` |  |
| DSPNOAN | `7671334` |  |
| SDPSNAOX | `7740200` |  |
| DSAN | `7799014` |  |
| PDSAX | `7864805` |  |
| DSPDSOAXXN | `7935878` |  |
| DPSDNOAX | `8003113` |  |
| SDPXNAN | `8064104` |  |
| SPDSNOAX | `8134180` |  |
| DPSXNAN | `8195177` |  |
| SPXDSXO | `8259925` |  |
| DPSAAN | `8324041` |  |
| DPSAA | `8389609` |  |
| SPXDSXON | `8456565` |  |
| DPSXNA | `8522825` |  |
| SPDSNOAXN | `8592900` |  |
| SDPXNA | `8653896` |  |
| PDSPNOAXN | `8723973` |  |
| DSPDSOAXX | `8787878` |  |
| PDSAXN | `8847813` |  |
| SRCAND | `8913094` | Combina los colores de los rectángulos de origen y destino mediante el operador booleano AND. |
| SDPSNAOXN | `8985352` |  |
| DSPNOA | `9047558` |  |
| DSPDXOXN | `9111142` |  |
| SDPNOA | `9178632` |  |
| SDPSXOXN | `9242216` |  |
| SSDXPDXAX | `9313660` |  |
| PDSANAN | `9374949` |  |
| PDSXNA | `9440325` |  |
| SDPSNOAXN | `9510408` |  |
| DPSDPOAXX | `9574313` |  |
| SPDAXN | `9634244` |  |
| PSDPSOAXX | `9705386` |  |
| DPSAXN | `9765321` |  |
| DPSXX | `9830761` |  |
| PSDPSONOXX | `9918602` |  |
| SDPSONOXN | `9967752` |  |
| DSXN | `10027110` |  |
| DPSNAX | `10094345` |  |
| SDPSOAXN | `10160040` |  |
| SPDNAX | `10225412` |  |
| DSPDOAXN | `10291110` |  |
| DSPDSAOXX | `10360550` |  |
| PDSXAN | `10421061` |  |
| DPA | `10485961` |  |
| PDSPNAOXN | `10558213` |  |
| DPSNOA | `10620425` |  |
| DPSDXOXN | `10684009` |  |
| PDSPONOXN | `10754181` |  |
| PDXN | `10813541` |  |
| DSPNAX | `10880774` |  |
| PDSPOAXN | `10946469` |  |
| DPSOA | `11010985` |  |
| DPSOXN | `11075977` |  |
| D | `11141161` |  |
| DPSONO | `11208841` |  |
| SPDSXAX | `11274052` |  |
| DPSDAOXN | `11339497` |  |
| DSPNAO | `11406086` |  |
| DPNO | `11469353` |  |
| PDSNOA | `11537925` |  |
| PDSPXOXN | `11601509` |  |
| SSPXDSXOX | `11671924` |  |
| SDPANAN | `11734248` |  |
| PSDNAX | `11798282` |  |
| DPSDOAXN | `11863977` |  |
| DPSDPAOXX | `11933417` |  |
| SDPXAN | `11993928` |  |
| PSDPXAX | `12060490` |  |
| DSPDAOXN | `12125926` |  |
| DPSNAO | `12192521` |  |
| MERGEPAINT | `12255782` | Combina los colores del rectángulo de origen invertido con los colores del rectángulo de destino utilizando el operador booleano OR . |
| SPDSANAX | `12328164` |  |
| SDXPDXAN | `12389757` |  |
| DPSXO | `12452457` |  |
| DPSANO | `12519625` |  |
| MERGECOPY | `12583114` | Combina los colores del rectángulo de origen con el pincel actualmente seleccionado en hdcDest, utilizando el operador booleano AND . |
| SPDSNAOXN | `12655364` |  |
| SPDSONOXN | `12720260` |  |
| PSXN | `12779626` |  |
| SPDNOA | `12848644` |  |
| SPDSXOXN | `12912228` |  |
| SDPNAX | `12977928` |  |
| PSDPOAXN | `13043626` |  |
| SDPOA | `13108136` |  |
| SPDOXN | `13173124` |  |
| DPSDXAX | `13240137` |  |
| SPDSAOXN | `13305572` |  |
| SRCCOPY | `13369376` | Copia el rectángulo de origen directamente al rectángulo de destino. |
| SDPONO | `13437064` |  |
| SDPNAO | `13503240` |  |
| SPNO | `13566500` |  |
| PSDNOA | `13635082` |  |
| PSDPXOXN | `13698666` |  |
| PDSNAX | `13764357` |  |
| SPDSOAXN | `13830052` |  |
| SSPXPDXAX | `13901176` |  |
| DPSANAN | `13962473` |  |
| PSDPSAOXX | `14030570` |  |
| DPSXAN | `14091081` |  |
| PDSPXAX | `14157637` |  |
| SDPSAOXN | `14223080` |  |
| DPSDANAX | `14294249` |  |
| SPXDSXAN | `14355829` |  |
| SPDNAO | `14420740` |  |
| SDNO | `14484008` |  |
| SDPXO | `14549608` |  |
| SDPANO | `14616776` |  |
| PDSOA | `14680997` |  |
| PDSOXN | `14745989` |  |
| DSPDXAX | `14812998` |  |
| PSDPAOXN | `14878442` |  |
| SDPSXAX | `14944072` |  |
| PDSPAOXN | `15009509` |  |
| SDPSANAX | `15080680` |  |
| SPXPDXAN | `15142265` |  |
| SSPXDSXAX | `15211892` |  |
| DSPDSANAXXN | `15293670` |  |
| DPSAO | `15336169` |  |
| DPSXNO | `15403081` |  |
| SDPAO | `15467240` |  |
| SDPXNO | `15534152` |  |
| SRCPAINT | `15597702` | Combina los colores de los rectángulos de origen y destino mediante el operador booleano OR. |
| SDPNOO | `15665672` |  |
| PATCOPY | `15728673` | Copia el pincel actualmente seleccionado en hdcDest, en el mapa de bits de destino. |
| PDSONO | `15796357` |  |
| PDSNAO | `15862533` |  |
| PSNO | `15925802` |  |
| PSDNAO | `15993610` |  |
| PDNO | `16056869` |  |
| PDSXO | `16122469` |  |
| PDSANO | `16189637` |  |
| PDSAO | `16253669` |  |
| PDSXNO | `16320581` |  |
| DPO | `16384137` |  |
| PATPAINT | `16452105` | Combina los colores del pincel actualmente seleccionado en hdcDest, con los colores del rectángulo fuente invertido by utilizando el operador booleano OR. El resultado de esta operación se combina con los colores del rectángulo destino utilizando el operador booleano OR. |
| PSO | `16515210` |  |
| PSDNOO | `16583178` |  |
| DPSOO | `16646825` |  |
| WHITENESS | `16711778` | Rellena el rectángulo de destino utilizando el color asociado con el índice 1 en la paleta física. (Este color es blanco para la paleta física predeterminada.) |

### Ver también

* espacio de nombres [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* asamblea [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->
