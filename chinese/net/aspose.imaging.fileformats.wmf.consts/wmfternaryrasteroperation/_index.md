---
title: WmfTernaryRasterOperation
second_title: Aspose.Imaging for .NET API 参考
description: 枚举指定三元光栅操作代码它定义 如何将源位图中的位与目标位图中的位组合
type: docs
weight: 8330
url: /zh/net/aspose.imaging.fileformats.wmf.consts/wmfternaryrasteroperation/
---
## WmfTernaryRasterOperation enumeration

枚举指定三元光栅操作代码，它定义 如何将源位图中的位与目标位图中的位组合。

```csharp
public enum WmfTernaryRasterOperation
```

### 价值观

| 姓名 | 价值 | 描述 |
| --- | --- | --- |
| BLACKNESS | `66` | 使用与物理调色板中索引 0 关联的颜色填充目标矩形。 （默认物理调色板的颜色为 黑色。） |
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
| NOTSRCERASE | `1114278` | 使用布尔 OR 运算符组合源矩形和目标矩形的颜色，然后反转 结果颜色。 |
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
| NOTSRCCOPY | `3342344` | 将反转的源矩形复制到目标。 |
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
| SRCERASE | `4457256` | 使用 布尔 AND 运算符将目标矩形的反转颜色与源矩形的颜色组合。 |
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
| DSTINVERT | `5570569` | 反转目标矩形。 |
| DPSOX | `5636521` |  |
| DPSOAN | `5702537` |  |
| PDSPOAX | `5769093` |  |
| DPSNOX | `5834249` |  |
| PATINVERT | `5898313` | 将当前在 hdcDest 中选择的画笔的颜色与目标矩形的颜色结合起来 使用布尔异或运算符。 |
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
| SRCINVERT | `6684742` | 使用布尔 XOR 运算符组合源矩形和目标矩形的颜色。 |
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
| SRCAND | `8913094` | 使用布尔 AND 运算符组合源矩形和目标矩形的颜色。 |
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
| MERGEPAINT | `12255782` | 使用 布尔 OR 运算符将反转源矩形的颜色与目标矩形的颜色合并。 |
| SPDSANAX | `12328164` |  |
| SDXPDXAN | `12389757` |  |
| DPSXO | `12452457` |  |
| DPSANO | `12519625` |  |
| MERGECOPY | `12583114` | 使用布尔 AND 运算符将源矩形的颜色与当前在 hdcDest 中选择的画笔合并。 |
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
| SRCCOPY | `13369376` | 将源矩形直接复制到目标矩形。 |
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
| SRCPAINT | `15597702` | 使用布尔 OR 运算符组合源矩形和目标矩形的颜色。 |
| SDPNOO | `15665672` |  |
| PATCOPY | `15728673` | 将 hdcDest 中当前选定的画笔复制到目标位图中。 |
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
| PATPAINT | `16452105` | 将 hdcDest 中当前选择的画笔的颜色与 使用布尔 OR 运算符的反转源矩形的颜色相结合。此操作的结果通过使用布尔 OR 运算符与目标 矩形的颜色组合。 |
| PSO | `16515210` |  |
| PSDNOO | `16583178` |  |
| DPSOO | `16646825` |  |
| WHITENESS | `16711778` | 使用与物理调色板中索引 1 关联的颜色填充目标矩形。 （对于默认的物理调色板，此颜色为 白色。） |

### 也可以看看

* 命名空间 [Aspose.Imaging.FileFormats.Wmf.Consts](../../aspose.imaging.fileformats.wmf.consts)
* 部件 [Aspose.Imaging](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.Imaging.dll -->