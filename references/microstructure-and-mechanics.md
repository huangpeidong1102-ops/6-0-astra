# 从组织与性能图写成论文段落

在起草 Results、组织与性能相关 Discussion、图注或对应润色时读取。目标是把当前研究的图和数据组织为清楚的英文段落；不要求复现范例的合金、仪器组合或章节数量。

范例 P1–P8 的完整出处见[来源索引](nature-storyboarding.md#source-index)。以下页码指 PDF 页码。示例中的方括号是待替换槽位，不是实验结果。

## 1. 先决定这一组图回答什么

用一行工作笔记确定：`科学问题 → 图中关键观察 → 定量差异 → 本段结论`。这行笔记用于组织正文，无须每次作为清单交给用户。

常见问题包括：设计的相结构是否形成；处理改变的是晶粒、相比例还是纳米析出物；性能改善发生在屈服、持续硬化还是延迟失稳；哪些观察解释该变化。

| 当前研究主线 | 可借鉴的图文路径 | 范例位置 |
|---|---|---|
| 成分调控 | 相身份→形貌和相比例→性能最优点→组织与性能联系 | P1，第2–13页 |
| 温度对照 | 同一初始组织→不同温度曲线→变形缺陷差异 | P2，第2–9页 |
| 再结晶/异质组织 | 处理前后组织→局部组织差异→力学响应→变形分配 | P3，第2–7页 |
| 退火/析出调控 | 大尺度组织→析出相演变→力学变化→障碍机制 | P4，第5–15页 |
| 铸态片层合金 | 相与界面→相内析出物→性能→位错活动 | P6，第2–8页 |
| 高温/压缩 | 初始组织→分温度压缩→性能保留与组织解释 | P7，第2–9页 |
| 氧化 | 初始组织→增重动力学→氧化物及层结构→扩散解释 | P5，第2–11页 |

按当前问题选择顺序。P6没有EBSD；P8的TEM排在EBSD之前；P3合并Results与Discussion。不要为缺少范例中的一种仪器中止可以完成的写作。

## 2. 段落的默认推进

优先采用“主要发现→关键量化或对照→结构/性能解释”。图号服务于论点，不要每句都以 `Fig. ... shows` 开头。单纯描述的 Results 段可以在观察和对照处结束；深入机制放到 Discussion，或按合并章节的需要衔接。

> Annealing increased the mean [feature size] from [a] to [b] [unit] (Fig. [n]). The [large-scale morphology] was retained, while [local feature] changed from [state A] to [state B]. This change provides the structural basis for examining [specific mechanical response].

数值来自当前实验。不要用范例论文中的数值填槽；有据的观察直接陈述，机制只保留与证据相称的一个限定，不在段尾自动附加局限声明。

## 3. XRD：写清相身份与相对变化

先写检测到的相及样品间差异，再描述与研究问题有关的峰位、峰宽或强度变化。保留衍射峰标定与测试条件；若作定量精修，说明采用的模型和输出。

> The XRD patterns reveal [identified phases] in [specimens] (Fig. [n]). Following [treatment], the [reflection] shifts toward [direction], accompanied by [measured change].

`reveal/identify` 用于已完成标定的结果；只有基础FCC/BCC峰时，不据此直接确定L1₂/B2有序结构。P1/P2通过后续超点阵反射补充有序相证据（P1，第2–5页；P2，第2–3页）。峰强变化还涉及织构与采样，不能直接写成相体积分数变化。

## 4. OM/SEM与EDS：从整体组织到局部差异

推荐描述顺序：整体形貌和空间分布→相/区域之间的差异→尺度与比例→元素分配。只写图中可辨认的特征，不把SEM明暗直接当成相身份。

> The [specimen] exhibits [overall morphology] consisting of [identified constituents]. As [variable] increases, [feature] changes from [a] to [b], while [another feature] remains [measured state]. EDS maps show enrichment of [elements] in [region A], whereas [elements] preferentially partition to [region B].

可迁移术语：`alternating lamellae`、`primary dendrites`、`eutectic colonies`、`interdendritic regions`、`elemental partitioning`。只采用适合当前组织的词；单相或非共晶高熵合金不套片层软硬相叙事。

尺寸要明确对象及统计定义：晶粒尺寸、片层厚度、片层间距、颗粒半径和直径分别命名。多种测量方法给出不同比例时，写明区域和方法，不强行合成唯一值（P8，第2–3页）。

## 5. EBSD：围绕晶粒、取向与变形分布写

| 图或指标 | 正文应回答的问题 | 有用表达 |
|---|---|---|
| IPF/晶粒图 | 晶粒形貌、取向与尺寸如何变化 | `equiaxed grains`、`elongated grains`、`grain-size distribution` |
| 相图 | 各相在何处分布、统计比例是多少 | `phase fraction`、`spatial distribution` |
| PF/ODF | 织构组分与强度有何变化 | `preferred orientation`、`texture intensity` |
| KAM | 局部取向差分布在哪里、对照差异是什么 | `local misorientation`、`higher KAM values near ...` |
| 再结晶分类 | 所用判据下各类晶粒怎样分布 | `recrystallized/substructured/deformed grains` |

> The EBSD maps show [grain/phase arrangement] in [specimen]. [Region A] exhibits [measured distribution], whereas [region B] contains [contrasting feature]. The higher local misorientation near [location] accompanies [observed heterogeneity].

KAM比较使用相容的步长、邻域与筛选设置。KAM是局部取向差指标；有单独模型和必要输入时再写GND密度，不直接改称总位错密度。再结晶百分数需沿用实际分类判据。P3将EBSD与TEM联用描述部分再结晶组织（第2–3页）。

## 6. TEM/HRTEM：把相鉴定、界面和变形观察分清

组织段落可依次写：观察区域→形貌与尺寸→衍射/晶体学身份→元素分配或界面特征。变形段落聚焦缺陷的位置、形态和相互作用，不重复全部初始组织描述。

> Dark-field TEM images reveal [precipitates] within [matrix] (Fig. [n]). The corresponding [SAED/FFT] pattern contains [indexed reflections], identifying [structure]. HRTEM images show [resolved interfacial feature] at the [phase A]/[phase B] interface.

> After [defined deformation state], dense dislocation [tangles/cells/pile-ups] are observed in [region]. Their accumulation near [identified obstacle] indicates restricted slip and helps explain [measured hardening response].

写出衍射标定、晶带轴和所测区域；FFT/IFFT指出来自哪个图、选择哪些反射。局部取向关系不代表所有界面；共格性由匹配关系与界面结构共同支持，不仅凭两组晶格条纹相邻而定。

区分位错滑移、层错、孪晶及相变的证据。观察到孪晶可以写孪晶特征，进一步称TWIP需联系其随变形产生及性能作用；TRIP需相变证据。末态TEM可解释累积变形特征，不能自行赋予其精确起始应变。APT不是语料中的固定步骤，有当前数据时按其真实输出描述。

## 7. 工程应力–应变：先写最有意义的差异

按研究重点报告屈服强度、极限强度与定义明确的延伸率/压缩应变，再比较处理或温度的作用。比较量多时用表格承载数值，正文突出最关键的关系。

> [Treatment] increased the yield strength from [a] to [b] MPa and the ultimate tensile strength from [c] to [d] MPa, while the [uniform/fracture] elongation changed from [e] to [f]% (Fig. [n]).

> At [temperature], the alloy retained a compressive yield strength of [value] MPa, corresponding to [calculated fraction]% of its room-temperature value.

内部核对测试类型、温度、应变率、取样方向、屈服判据及误差含义。压缩的极限强度不要写成UTS；均匀延伸率、总延伸率与断裂应变不要互换。`±`定义不明时保留原信息，向作者简短标出待确认项，不编造SD/SE。

百分比从原始数值重算：增加百分比以起始值为分母；性能保留率以对应基线为分母。强度与延伸率的组合可称 `strength–ductility balance`，不能等同于断裂韧性。

## 8. 真应力–应变与加工硬化：阶段服从数据

交代加工硬化率采用的应力、应变定义，例如 `θ = dσ_true/dε_true`，并与实际处理一致；若使用真塑性应变，明确写出该定义。求导和平滑细节按实际方法报告，不能根据漂亮曲线补造处理过程。

先写总体硬化水平与样品对照，再描述有数据支撑的分段趋势、应变范围及相应变形观察。P1/P2/P4/P6使用三阶段，P8使用两阶段，P3重点为LUR；不设置固定阶段数。

> The strain-hardening rate decreases rapidly at low strains and then [measured trend] over [interval] (Fig. [n]). Compared with [reference], [specimen] maintains a higher hardening rate within [range]. The [independent deformation observation] provides a microstructural explanation for this response.

不要仅凭曲线波动判定孪生或相变。工程到真值的常用均匀变形换算不能无条件延伸到颈缩后；颈缩区、压缩鼓肚及局部应变分析采用用户实际处理方法。分析 Considère 条件时须匹配其所需的真应力与真应变定义。

## 9. 断口与裂纹：先位置、尺度和形貌，再解释

先低倍定位，再高倍描述韧窝、撕裂棱、河流花样、解理台阶或微裂纹。对比特征的大小、分布和比例；有相标定或配准证据后再把某片区域归属特定相。

> The fracture surface contains [features] in [location] (Fig. [n]). Higher-magnification images reveal [specific morphology], while [contrasting feature] appears in [other region]. These features indicate [supported fracture mode].

混合形貌可直接写 `mixed ductile and cleavage features`。孔洞成核位置、裂纹偏转或裂纹路径必须有对应观察；单张终态断口不写成实时传播历程。没有断口图时，不凭力学曲线生成断口描述。

## 10. 可选分支：氧化论文

仅在研究包含氧化时加载本节。采用P5的功能顺序：测试温度/时间→单位面积增重及动力学→氧化物种类→表面/截面层结构→元素分布与扩散解释（第3–11页）。

> At [temperature], the mass gain per unit area reached [value] after [time]. The [defined interval] followed [fitted kinetic law]. Cross-sectional observations reveal [layer arrangement], while [phase/element analysis] identifies [constituents and distribution]. The continuous [identified layer] limits [supported transport pathway].

只有形貌与EDS时避免单独完成精确氧化物物相鉴定；利用XRD或其他相证据。保持暴露时间、表面/截面位置及层序一致。氧化后室温压痕不称高温原位力学测试。拟合公式和参数见[模型参考](strengthening-models.md#oxidation)。

## 11. 将观察接入Discussion

选当前研究最强的一条联系展开：设计动作改变了哪种组织；该组织怎样改变滑移、储存、应变分配或扩散；哪项性能响应与之对应。比较不止列数值，也解释为什么最强样品与其他样品不同。

没有定量分解时，可以完成有证据的定性机制段落；只有用户要求计算或论证需要时，读取[强化模型](strengthening-models.md)。完整稿内部核对样品、图号、单位与结论，输出连贯正文及少量真正影响使用的作者备注，不默认输出审稿清单。
