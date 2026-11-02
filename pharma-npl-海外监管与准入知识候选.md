# Pharma NPL 海外监管与准入知识候选（原文补读，未入库）

- 研究日期：2026-10-31（已执行系统date核验，CST）。
- 对象：同时服务中国与海外新药上市团队的顾问；用于上市依赖项、地区证据差异和待确认问题管理。
- 权限边界：仅本地Markdown候选；未调用任何知识库提案、新增、导入、确认或写入工具；未修改`pharma-npl-海外知识候选.md`。
- 与前件关系：前件当前为9卡（6张ICH/AMCP入口卡＋3张M4E指定章节实质卡）；本件27卡为补充，不覆盖前件的阅读边界，也不代表全部海外资料已精读。
- 阅读口径：网页全文指本次返回的正文全部读完，不包括外链子文件；选章指原文件或网页中明确限定部分；全文解析成功不自动等于全文已读。WebFetch返回摘要时只按可见章节摘录记证据，不把摘要升级为逐字全文。
- PDF口径：使用workbuddy-pdf CLI读取；FDA2014为40页，C2H2026英文指南36页、收载通知18页、定价通知76页。前三份文字全文已读；定价通知选章。FDA对照表、日本收载时限、C2H贴现和重复条款号已看原页核对。未逐页目视校验所有图表、公式，卡片不转录未核对公式。
- 所有“事实”限于对应已读版本；“建议”是顾问工作建议，不是原文新增强制要求；文件不提供任何具体产品的法律适用性或申报充分性结论。

## 一、逐来源阅读台账

| ID | 原文及URL | 版本/日期 | 实际阅读范围与状态 | 剩余边界 |
|---|---|---|---|---|
| US01-A | https://www.fda.gov/drugs/developmentapprovalprocess/ | 页面未显示可核定更新时间；读取2026-10-31 | 网页返回正文全文：获益风险框架、Accelerated Approval、三类designation介绍 | 外链独立指南未全部读；六个月不等于上市承诺 |
| US01-B | https://www.fda.gov/regulatory-information/search-fda-guidance-documents/expedited-programs-serious-conditions-drugs-and-biologics | 2014-05 | 指南入口正文已读 | 仅入口不能替代附件；附件另列 |
| US01-B1 | https://www.fda.gov/files/drugs/published/Expedited-Programs-for-Serious-Conditions-Drugs-and-Biologics.pdf | 正文2014-05；本次下载件PRA封面注明2017-09-21更新、到期2020-05-31 | 40页文字全文已读；I—X、附录1—2；印刷p8表格看图核对 | 2014历史版本；不可当作2026全套现行规则，尤其加速批准撤回程序/PDUFA承诺/过期PRA；本次未完成后续全套修订追踪 |
| US01-C | https://www.fda.gov/regulatory-information/search-fda-guidance-documents/accelerated-approval-expedited-program-serious-conditions | 2024-12；入口写Not for implementation | 入口正文已读；指出涉及后续加速批准及撤回程序变化 | 附件未下载未读；不能用其取代final规则，也不能凭2014冻结现行要求 |
| EU01-A | https://www.ema.europa.eu/en/human-regulatory-overview/marketing-authorisation/obtaining-eu-marketing-authorisation-step-step | 本页无可核定总体更新时间；读取2026-10-31 | 网页返回正文全文：申报前、提交验证、科学评估、意见与决定、已关闭试点 | 仅集中程序；pre-authorisation细则、eCTD规范、其他程序未读 |
| EU02-B | https://health.ec.europa.eu/publications/procedural-guidance-jca-medicinal-products_en | 2024-11-28 | 入口全文；确认附件准确URL | 未取得PDF正文，不形成JCA流程卡 |
| EU02-B1 | https://health.ec.europa.eu/document/download/0929cd01-619d-4456-a1c4-d8e33f9e36bf_en?filename=hta_jca_mp_procedural-guidance_en.pdf | 入口2024-11-28 | 下载HTTP429，访问失败 | 全文未读；PICO、提交时限、保密/问答与更新均待原文 |
| EU03-DE | https://www.g-ba.de/english/benefitassessment/ | 页面混合2011背景及后续更新；无可核定总体更新日 | 英文概览返回正文全文：dossier、对照、3+3月流程、谈判、EU-HTA衔接及咨询 | 德文现行VerfO/AM-NutzenV及最新模板未读；英文时间表不是具体产品现行适用性意见 |
| EU03-FR | https://has-sante.fr/jcms/c_1729421/en/jcms/fc_2875208/ | 未核定 | 本件未处理 | 法国常规HTA/SMR/ASMR原文待补；不能用早期准入替代 |
| EU04-A | https://has-sante.fr/jcms/r_1500918/en/early-access-to-medicinal-products | 未核定 | 两次WebFetch terminated；搜索发现www标准地址，访问 https://www.has-sante.fr/jcms/r_1500918/en/early-access-to-medicinal-products 返回403 | 搜索结果只用于发现，不计正文精读；HAS doctrine、2026企业指南、PUT-RD模板均未读 |
| UK01-A | https://www.gov.uk/government/publications/international-recognition-procedure/international-recognition-procedure | 更新2026-10-09；程序2024-01-01起；本轮调整2026-07-13起 | 网页选章摘录：1—5、6、7.1/7.4—7.6、8.3—8.5/8.10、10；重复核对冲突句 | 未逐项精读全部RR附件清单、所有上市后变更/续展与启动日表；8周/6周及5年/10年残留冲突必须保留 |
| UK02-A | https://www.nice.org.uk/process/pmg36 | 发布2022-01-31；Last reviewed 2026-10-13 | 概览全文 | 全手册并未读完 |
| UK02-A1 | https://www.nice.org.uk/process/pmg36/chapter/economic-evaluation-2 | PMG36页面版本见上；读取2026-10-31 | 第4章4.1—4.12.8选章摘录；EQ-5D旧文字不作为现行规则 | 图4.1未由此页正文读出；临床证据、委员会决策、流程其他章未读 |
| UK02-A2 | https://www.nice.org.uk/process/pmg36/chapter/developing-the-guidance-2#varying-the-funding-requirement-to-take-account-of-net-budget-impact | 2026-10-13概览称此部分已更新 | 页面返回截断于5.9.43；目标5.10正文未获得 | 不形成净预算影响阈值/资金延缓时限卡；注意该页目标为5.10，不臆造第6章 |
| UK02-B | https://www.nice.org.uk/process/pmg51 | 发布/Last reviewed 2026-08-27 | 概览、resources、Introduction 1.1—1.4全文 | 概览称替代2017声明，PMG36称2019；保留版本表述差异 |
| UK02-B1 | https://www.nice.org.uk/process/pmg51/chapter/appendix-a-changes-to-nice-manuals | 2026-08-27 | 附录A表A1、A2实际替代文字及参考文献已读 | 不是PMG51其余全部章节 |
| UK02-B2 | https://www.nice.org.uk/process/pmg51/chapter/appendix-b-changes-to-figure-4_1 | 2026-08-27 | 附录B正文已读，链接至图4.1变更资源 | 没有凭空补画图表；优先级精细排序需结合图/FAQ |
| UK02-B3 | https://www.nice.org.uk/process/pmg51/chapter/appendix-c-technical-frequently-asked-questions-faqs | 2026-08-27 | 选读可见FAQ1、2、3、5—9、12、15—17、19、20、23；返回正文有[…]，不能称附录C全文 | FAQ4、10—11、13—14、18、21—22未完整读到；映射工具/TSD22原文和软件实现未核验 |
| JP01-A | https://www.pmda.go.jp/files/000282949.pdf | 未核定题名与版本 | 两次下载HTTP502/未取得文件 | 未读取任何正文，不猜其具体题名、页数或结论 |
| JP01-B | https://www.pmda.go.jp/english/review-services/reviews/approved-information/drugs/0001.html | 页面未显示可核定更新时间 | 索引正文、翻译说明、字段和A—K目录摘录 | 不是A—Z全目录；未逐份读取药品审评报告 |
| JP02-A | https://c2h.niph.go.jp/en/tools/guideline | 入口列2026附件；通知日期2026-02-13 | 入口返回正文全文 | 其他通知/说明文章未全读 |
| JP02-A1 | https://c2h.niph.go.jp/tools/guideline/guideline_en_2026.pdf | 封面：2026-01-16批准 | 36页文字全文：1—14章、术语、AD治疗附录、缩写；p25、p28看图核对 | 英译本以日文为准；公式和全部图表未逐一目视复核；不作为所有药品首发前强制成本效果评价要求 |
| JP02-A2 | https://c2h.niph.go.jp/tools/system/notification_drug_listing_2026.pdf | 2026-02-13；2026-04-01起；旧通知2026-03-31废止 | 18页文字全文，含1—4及附表1—8；收载时限PDF p3/印刷p2看图核对 | 日文技术资料的工作译读，不替代日本申报专家复核 |
| JP02-A3 | https://c2h.niph.go.jp/tools/system/notification_drug_pricing_2026.pdf | 2026-02-13；2026-04-01起，部分另有实施/过渡条款 | 76页全文解析成功但仅选章：封面、目录、第1章15—22定义、第2章第1部第1—2节、第3章第12节及第4章相关实施条款 | 第3章其余多数重定价条款、全部加算条件、外价调整公式、别表12计算未完整读核，不生成数值计算器 |
| US03-A | https://www.cms.gov/medicare/coverage/coverage-evidence-development/monoclonal-antibodies-directed-against-amyloid-treatment-alzheimers-disease-ad | 未核定 | 本件未处理 | CMS覆盖与CED原文另补；FDA批准不能替代支付覆盖 |
| EU02-A | https://ec.europa.eu/commission/presscorner/api/files/document/print/en/qanda_25_227/QANDA_25_227_EN.pdf | 未核定 | 本件未处理 | 不用新闻问答替代JCA程序原文 |

### 取证与版本异常，必须跟随知识卡保留

1. FDA2014下载URL是搜索结果发现的准确官方链接，经HTTP200/application/pdf验证，不是猜测。该文件封面PRA信息与搜索中另一副本PRA信息不同，不能把PRA更新误记为核心指南修订。FDA2024-12另有Not for implementation的加速批准入口，本件没有把草案作为现行规则。
2. MHRA现第4.2节写5年，第10节MRP repeat-use仍写“2 or 10 year”；7.5正文8周，表格6周。原句复核如下：
   - 4.2：“the RR approval must have been granted within the previous 5 years”；“Authorisations more than 5 years old are not eligible for IRP.”
   - 7.5：“at least 8 weeks before the planned date of MAA submission”；表格triage/NAS仍为“at least 6 weeks”。
   - 10：“The end of procedure date of the latest MRP Repeat-Use Procedure can be used for the purpose of establishing the 2 or 10 year eligibility periods.”
   不将残留10年作为现行可用资格；也不暗中删除6周冲突。具体申请需书面确认。
3. NICE PMG36概览称PMG51取代2019声明；PMG51概览称取代2017年11月声明；PMG51 resources另列“superseded - October 2019”。三项分别记载，不臆造已解决的版本沿革。
4. NICE 2026-08-27概览切换须结合项目实施节点；FAQ16限定前瞻性，不能把所有2026-08-27之后最终发布的评估都认定自动切换。
5. C2H英文指南p28确有两个“14.6”（第二个为PSA条款），已看原页确认；引用时以“p28第二个14.6（PSA）”标识，不擅改为14.7。

## 二、知识卡

### OR-US01｜批准判断是目标人群与治疗背景下的获益风险判断
- 事实：FDA流程页把批准解释为对预定人群的已知及潜在风险与获益的综合判断；框架包括目标疾病及现有治疗、临床获益风险及其不确定性、风险管理。标签是风险管理工具，适用时还需REMS；FDA主要审查申请人证据，不是代申请人完成开发试验。
- 来源章节及URL：US01-A，FDA Approval: What it means；https://www.fda.gov/drugs/developmentapprovalprocess/ 。
- 日期/版本：2026-10-31读取；页面未核定更新日。
- 适用边界：一般介绍，不是某适应证最低试验数或充分性决定；不能据一般“两项研究”描述否定特定情形的一项充分研究路径。
- NPL用途：组织目标人群、获益、风险、不确定性和风险缓释的证据叙事。
- 建议：注册、医学和药物警戒共用一份获益风险问题表，但与支付方价值评价分开。
- tags：FDA；benefit-risk；label；REMS；上市叙事
- 检索问句：FDA批准为什么不等于产品没有风险，上市故事应如何呈现证据不确定性？

### OR-US02｜四类加速工具不是同一件事，资格证据等级不同
- 事实：2014指南IV表、V、VI、VIII区分Fast Track/Breakthrough/Priority Review三种designation与Accelerated Approval批准路径。Fast Track可依据非临床或临床潜力；Breakthrough需要初步临床证据支持在临床重要终点上相对现有治疗可能实质改善；Priority Review关注申请如获批是否显著改善安全性或有效性。一个项目可符合不止一种工具。
- 来源章节及URL：US01-B1，IV印刷p7—8/PDF p11—12，V p9—10，VI p10—15，VIII p24—25；https://www.fda.gov/files/drugs/published/Expedited-Programs-for-Serious-Conditions-Drugs-and-Biologics.pdf 。
- 日期/版本：2014-05历史指南；2026-10-31读取。
- 适用边界：非约束性指南框架；不能将designation等同批准、自动优先审评或自动支付。2014时钟脚注涉及当时PDUFA V，不直接复制为2026项目时钟。
- NPL用途：定义路径选择、资格申请和申报审评的不同里程碑。
- 建议：路径台账分列资格门槛、请求节点、证据成熟度、机构反馈和失去资格风险。
- tags：Fast Track；Breakthrough Therapy；Priority Review；Accelerated Approval
- 检索问句：Fast Track、Breakthrough、Priority Review和Accelerated Approval应怎样分别排入上市计划？

### OR-US03｜现有治疗与未满足需求需在关键决策点持续刷新
- 事实：2014指南III.B将available therapy通常限定为美国同适应证已批准/许可且与当前标准治疗相关的治疗；考虑具体疾病阶段、人群和治疗实践。III.B、附录1指出标准治疗可随开发演变，后续新治疗获批或本品数据变化可能使Fast Track/Breakthrough不再满足条件。VI明确初步突破性认定标准不同于最终批准标准，撤销认定也不必然排除完成开发后的批准。
- 来源章节及URL：US01-B1，III.B—C印刷p3—6/PDF p7—10；VI p10；附录1.A.5、B.5 p29—33；同US01-B1 PDF URL。
- 日期/版本：2014-05历史框架；2026-10-31读取。
- 适用边界：本件不将2014关于特殊加速批准对照的细节当作2026最终现行规则；地区对照不能无核实共用。
- NPL用途：竞争情报与注册资格、临床设计、价值叙事联动。
- 建议：每次关键数据读出、竞品批准和申报前更新标准治疗快照并检查路径假设。
- tags：available therapy；unmet need；SOC；竞争证据
- 检索问句：竞品在开发后期获批，会不会影响原有加速资格和证据定位？

### OR-US04｜替代终点证据与验证临床获益是一条连续工作链
- 事实：2014指南VII.B—D区分已验证替代终点、合理可能预测临床获益的替代终点、证据不足的生物标志物；药理活性本身不足以证明合理预测关系。确认试验用于验证及描述预期临床获益，方案与时间线应尽早开发；指南讨论同一随机试验早期替代终点分析后继续随访验证临床终点的可能性。当前FDA流程页也说明上市后确认试验及不能验证获益时可能撤回。
- 来源章节及URL：US01-B1，VII.B—D印刷p17—24/PDF p21—28；同US01-B1 PDF URL。交叉证据US01-A Accelerated Approval，https://www.fda.gov/drugs/developmentapprovalprocess/ 。后续版本警示US01-C，https://www.fda.gov/regulatory-information/search-fda-guidance-documents/accelerated-approval-expedited-program-serious-conditions 。
- 日期/版本：指南2014-05；流程页2026-10-31读取；2024-12后续入口明确Not for implementation，附件未读。
- 适用边界：不提供现行撤回听证时限、确认试验启动法定要求或特定终点已被接受的结论；必须补核后续final文件及产品沟通。
- NPL用途：识别注册获益、HTA长期获益与上市后证据之间的缺口。
- 建议：确认试验、长期随访、HTA外推和风险缓释分别有负责人，勿把上市日当作证据工作的结束。
- tags：surrogate endpoint；confirmatory trial；生命周期证据；不确定性
- 检索问句：采用替代终点加速批准时，为什么上市计划必须同时安排确认性证据？

### OR-US05｜加速临床不能把CMC、核查和伴随诊断留到后面
- 事实：2014指南IX.A—D要求早期沟通制造与质量、非临床计划、临床核查准备和伴随诊断；制造能力时间线应与临床开发相配，考虑预计需求、生产场地及工艺验证。附录2说明rolling review通常提交完整且可审评章节，草稿不应提交；接受部分申请不保证立即启动审评；审评计时不会因首个部分递交而自动开始。
- 来源章节及URL：US01-B1，IX印刷p25—27/PDF p29—31；附录2.A—E p35—36/PDF p39—40；同US01-B1 PDF URL。
- 日期/版本：2014-05历史指南；2026-10-31读取。
- 适用边界：不构成2026 eCTD技术规范、用户费数额或特定PDUFA目标；CMC灵活性是逐案讨论，非免除质量要求。
- NPL用途：跨职能关键路径、商业供货、核查与分批递交准备。
- 建议：路径提速评审同时审CMC、供应、CDx及核查成熟度，rolling review单独确认可接受单元与计划。
- tags：CMC；rolling review；inspection；CDx；供应准备
- 检索问句：rolling review是否意味着一交首批材料就开始六个月审评？

### OR-EU01｜欧盟集中程序申报前准备有明确提前窗口
- 事实：EMA流程页建议始终提交eligibility request及论证，时间18至7个月前；提交意向通知7个月前；推荐pre-submission meeting在6至7个月前；2至3个月前再次确认申报日，发生变更须通知。通过eCTD与eSubmission渠道提交，技术验证先于科学评估。
- 来源章节及URL：EU01-A，Steps prior to submitting an application、Submission of the application；https://www.ema.europa.eu/en/human-regulatory-overview/marketing-authorisation/obtaining-eu-marketing-authorisation-step-step 。
- 日期/版本：2026-10-31读取；无可核定总体更新日。
- 适用边界：集中程序的概览建议，不是所有欧盟注册路径的通用倒排表；验证补正可影响启动。
- NPL用途：全球申报日倒排、eligibility与申报资源预留。
- 建议：把“计划递交日”“技术验证完成”“科学评估开始”分成独立里程碑。
- tags：EMA；centralised procedure；pre-submission；eCTD
- 检索问句：欧盟集中申报前多久安排资格确认、意向通知和申报前会议？

### OR-EU02｜210活跃审评日不等于210天可销售
- 事实：EMA流程页称科学评估最多210 active days；CHMP出具科学意见后进入批准决定步骤，页面写收到CHMP意见后67天内；获授权后发布EPAR。页面还明确曾收集孤儿药及肿瘤药上市意向的试点已于2022年8月关闭。
- 来源章节及URL：EU01-A，Assessment of the application、decision on the marketing authorisation、Voluntary sharing of market launch intentions；同EU01-A URL。
- 日期/版本：2026-10-31读取；试点已关闭是页面明确状态。
- 适用边界：active days不是日历总历时，也不是成员市场可及性、定价或首发日期保证；本卡不替代详细clock stop规则。
- NPL用途：注册、获授权、国家准入、首批供货拆解。
- 建议：商业首发时间线不要把CHMP积极意见当成全部市场上市完成；对已关闭试点不得列现行必做任务。
- tags：CHMP；active days；EPAR；launch readiness
- 检索问句：CHMP意见、集中授权和国家市场首发为何不是同一天？

### OR-DE01｜德国额外获益证据以当地指定对照为核心
- 事实：GBA英文页称企业需提交基于授权文件及全部相关研究的dossier，论证相对于GBA指定appropriate comparator的额外获益；可就提交研究资料及对照申请咨询，III期前的设计咨询涉及相应专业评估协同；新版模块模板需使用最新版本。
- 来源章节及URL：EU03-DE，Submission of dossiers、Dossier submission、Request for consultation；https://www.g-ba.de/english/benefitassessment/ 。
- 日期/版本：2026-10-31读取；页面无可核定总体更新日。
- 适用边界：仅英文概览；未读德文现行规则及附件，不能据此确认孤儿药例外、当前模块逐项要求或具体适应证对照。
- NPL用途：发现全球注册对照与德国额外获益对照的差距。
- 建议：尽早将注册试验对照、德国对照和可支持的亚组做证据映射，必要时在III期前咨询。
- tags：GBA；AMNOG；appropriate comparator；dossier
- 检索问句：为何全球注册研究获批后仍可能无法证明德国额外获益？

### OR-DE02｜JCA可减少重复材料，不代替国家问题与获益决定
- 事实：GBA英文页允许已完成欧洲JCA时在dossier中引用先前EU提交信息；国家评估应在数据适用于国家问题时考虑JCA报告。英文页描述结果3个月内发布、再3个月形成决议，并另述价格谈判阶段；企业材料最迟首次流通日递交。
- 来源章节及URL：EU03-DE，Submission of dossiers、Benefit assessment、Consultation and decision-making、Dossier submission；同EU03-DE URL。
- 日期/版本：2026-10-31英文概览观察。
- 适用边界：本件未读JCA程序PDF；不得由本页推导JCA具体提交时钟。页面还以“market authorization”描述六个月起点，不能无提示与“first circulation”合并为同一事件；德文现行规则及具体触发情形优先核验。英文页谈判时限不能直接固化为2026项目日历。
- NPL用途：建立EU共享临床核心与德国本地补充层，避免“JCA完成=各国准入完成”。
- 建议：把英文概览3+3月作为待核流程结构，不作为未经核验的承诺日期；单列当地PICO、亚组和对照差异。
- tags：JCA；EU-HTA；本地适配；德国；时限边界
- 检索问句：欧洲JCA完成后，德国dossier和国家特定问题是否仍需准备？

### OR-UK01｜IRP依赖完整独立审评，不是自动承认批准
- 事实：MHRA第1—3节要求指定RR已进行full and standalone review；不能用RR依赖其他地区认可所得评估支撑IRP。same product涉及活性成分/辅料定性定量组成、剂型、治疗用途一致；需批准证明和完整未删节审评报告。MHRA仍可因证据不够稳健拒绝；无法取得报告时应考虑国家路径。
- 来源章节及URL：UK01-A，1 Overview、2 Scope、3 Reference regulators、7.1、7.6.1；https://www.gov.uk/government/publications/international-recognition-procedure/international-recognition-procedure 。
- 日期/版本：更新2026-10-09；2026-10-31读取。
- 适用边界：特定IRP路径；紧急批准、取消批准和若干其他申请类型不适用；不保证所有境外获批品种都可进入。
- NPL用途：license-in资料可得性、产品一致性及全球批准顺序决策。
- 建议：交易/授权尽调加入未删节审评报告和全生命周期数据访问权，先核RR依据是否独立。
- tags：MHRA；IRP；reliance；RR；资料权利
- 检索问句：境外获批产品为什么仍可能不具备英国IRP申请资格？

### OR-UK02｜A/B时限是有条件审评安排，不能直接当首发日
- 事实：第4节A为60日、B为110日日历时限；A通常无clock stop，重大问题可转B；B在day70有一次暂停、最多60日答复，仍有问题可转国家时限。第4.3保留必要时延长及暂停权；第5节validation14日，VCR仅一次补正机会。B触发因素包括单臂关键证据、RWD关键证据、ATMP、若干质量/RMP/ERA变化等。
- 来源章节及URL：UK01-A，4.1—4.3、5、8.3—8.5及8.10；同UK01-A URL。
- 日期/版本：更新2026-10-09；2026-10-31读取。
- 适用边界：初始MAA与line extension；variations/renewals不直接使用A/B；110日不包含所有暂停与申请前准备，批准非保证。
- NPL用途：路径风险与英国上市情景倒排。
- 建议：按validation、A/B、答复暂停、转换、供货分别建情景，不只保留一个“60天/110天”日期。
- tags：Recognition A；Recognition B；clock stop；validation；上市情景
- 检索问句：英国IRP的60/110天是否是从提交到批准的固定自然日承诺？

### OR-UK03｜2026版IRP资格窗口与预通知文本存在残留冲突
- 事实：现第4.1写A要求RR批准在前2年内；第4.2写B前5年内、超过5年不适用；第10节MRP Repeat-Use仍残留“2 or 10 year”。7.5通则至少提前8周完成/适用时发送资格表，而triage与NAS表格仍写6周。EMA的CHMP积极意见及MR/DC积极程序结束结果可作相应提交批准依据，具体文件见第10节。
- 来源章节及URL：UK01-A，4.1、4.2、7.5、10；同UK01-A URL；原句见本文件版本异常区。
- 日期/版本：更新2026-10-09；页面说明调整2026-07-13起，旧程序过渡至2026-08-31。
- 适用边界：本卡记录冲突，不代替MHRA解释；不认定10年仍可用、不擅定回溯基准日，不能将残留6周当安全最晚日期。
- NPL用途：英国申报日期与参考批准有效窗口的质控。
- 建议：计划至少按8周预留并向机构确认；保存当次版本、适用路径与书面反馈。
- tags：IRP2026；版本冲突；资格窗口；pre-notification
- 检索问句：IRP页面同时写5年/10年、8周/6周时，上市团队应怎样管理？

### OR-NICE01｜NICE参考方案不等于全球HEOR模型原样复用
- 事实：PMG36第4章规定参考方案以NHS/PSS成本视角、患者及适用照护者健康效果、成本效用/QALY和完全增量分析为主；时限覆盖重要成本和结局差异，影响生存或终身获益时通常需终身时限；成本/健康效果默认均3.5%年贴现。1.5%只能在严格条件下另呈非参考方案，非所有长期获益治疗自动适用。
- 来源章节及URL：UK02-A1，4.2.1—4.2.25、4.5.1—4.5.5；https://www.nice.org.uk/process/pmg36/chapter/economic-evaluation-2 。
- 日期/版本：PMG36概览Last reviewed 2026-10-13；读取2026-10-31；EQ-5D按PMG51更新。
- 适用边界：本卡不替代适用技术类别与完整决策方法；生产力成本不直接进入参考方案；使用偏离方案需单列并论证。
- NPL用途：全球模型英国本地化的差异清单。
- 建议：分离模型结构复用与视角/参数/效用版本本地化，记录每项偏离与影响。
- tags：NICE；reference case；NHS/PSS；discounting；HEOR
- 检索问句：全球成本效果模型进入NICE前至少应核查哪些本地方法差异？

### OR-NICE02｜2026成人reference-case转向英国5L，须结合项目节点
- 事实：PMG36概览写2026-08-27起成人reference-case使用EQ-5D-5L描述系统及英国5L价值集，PMG51优先于尚未同步的手册。PMG51附录A表A1替换4.2.2、4.3.6等并删除旧4.3.16。附录C可见FAQ16称前瞻适用：TA/HST以声明后发出invitation to participate的主题为节点，非一律按最终指导发布日期；HealthTech和指南另有启动节点。
- 来源章节及URL：UK02-A https://www.nice.org.uk/process/pmg36 ；UK02-B1 https://www.nice.org.uk/process/pmg51/chapter/appendix-a-changes-to-nice-manuals ；UK02-B3 FAQ16 https://www.nice.org.uk/process/pmg51/chapter/appendix-c-technical-frequently-asked-questions-faqs 。
- 日期/版本：PMG51发布2026-08-27；PMG36 reviewed2026-10-13；2026-10-31读取。
- 适用边界：成人方法；不要把所有既往已发布评估强制追溯重算。PMG36称替代2019声明、PMG51概览称2017，版本差异保留。
- NPL用途：效用输入版本和在研NICE项目切换判断。
- 建议：记录项目邀请参与日、适用方法与原始量表数据；不要直接沿用PMG36旧3L段落。
- tags：PMG51；EQ-5D-5L；2026更新；前瞻实施
- 检索问句：NICE2026年采用5L后，所有尚未发布结果的评估是否都必须切换？

### OR-NICE03｜有原始5L重新计分，旧3L证据须映射而非直接比较
- 事实：附录A表A1与附录C可见FAQ1—3、8—9、12、15、23说明：已有5L描述数据直接以Rowen2026英国价值集计分；只有3L时使用相应DSU/EEPRU映射方法；历史5L也可重计分，不预期仅为新手册另采全部5L。3L与5L效用值不可直接数值比较；减损映射需要先确定绝对基准状态，不能把减损数直接当绝对效用。附录A要求解释替代数据选择并开展敏感性分析。
- 来源章节及URL：UK02-B1表A1，同附录A URL；UK02-B3可见FAQ1—3、8—9、12、15、23，同附录C URL。
- 日期/版本：PMG51 2026-08-27；2026-10-31选章读取。
- 适用边界：未核验映射工具代码/TSD22原文，不能据卡直接自动转换输入；附录C返回不完整。儿童需单独适龄方法（FAQ19），成人规则不机械外推。
- NPL用途：历史试验数据再利用、模型效用资产和审计轨迹。
- 建议：保留原始描述回答、量表版本、国家value set及映射步骤；先确认基准再处理效用减损。
- tags：utility；mapping；historical data；EQ-5D；数据溯源
- 检索问句：历史EQ-5D-5L数据已转成3L后，新NICE模型应如何重新利用？

### OR-NICE04｜不确定性、阈值输出与预算影响必须分别管理
- 事实：PMG36第4.6—4.11要求模型结构和外推透明、检验结构/参数/数据不确定性、合理亚组、完全增量结果和实施预算影响。4.2.16及4.10.8在适用时按£25,000和£35,000/QALY呈现净健康获益，4.7.15涉及相应范围内概率输出；这些不是自动推荐保证。净预算影响资金安排部分已在2026-10-13更新，但本次其5.10目标正文未成功取得。
- 来源章节及URL：UK02-A1，4.2.16、4.6—4.11；同economic-evaluation-2 URL；UK02-A概览更新说明 https://www.nice.org.uk/process/pmg36 。
- 日期/版本：2026-10-31读取；PMG36 reviewed2026-10-13。
- 适用边界：未读完整委员会决策章，不把上述数值写成统一必过阈值；资金延缓时限与净预算影响触发数值本件不下结论。
- NPL用途：区分价值判断、证据风险与可负担性/实施可行性。
- 建议：上市商业案例并列ICER/NHB、不确定性和净预算影响；资金变更机制需另补原文再建规则。
- tags：NICE；uncertainty；NHB；budget impact；证据边界
- 检索问句：ICER达到某个数值是否意味着NICE必然推荐且立即按标准资金要求实施？

### OR-JP01｜PMDA英译审评报告是有选择的学习样本，不是完整批准库
- 事实：PMDA索引说明英文报告为方便使用的参考翻译，与日文不一致时以日文为准；翻译选择考虑新活性成分、创新性和优先性等。目录字段有商品名、通用名、批准年月、英文/日文报告及部分勘误；同药存在首次批准和部分变更批准，Approved In不是网页更新日期。
- 来源章节及URL：JP01-B，Review Reports: Drugs开头说明及目录字段；https://www.pmda.go.jp/english/review-services/reviews/approved-information/drugs/0001.html 。
- 日期/版本：2026-10-31读取；页面更新日未核定。
- 适用边界：只读到说明和A—K摘录，不是A—Z全目录；指定000282949.pdf两次502，未读，不从索引补造该附件内容。
- NPL用途：同类产品证据设计、审评关注点和先例检索。
- 建议：按产品/适应证变更/批准年月配对日英文、勘误；引用具体结论须再读相应PDF。
- tags：PMDA；review report；translation；precedent；版本匹配
- 检索问句：为什么不能仅以PMDA英文索引证明某药适应证的具体审评结论？

### OR-JP02｜日本成本效果指南仅适用于被选定评价产品，标准视角本地化
- 事实：C2H指南1.1—1.3适用于被选定成本效果评价的药物、器械和再生医疗产品，以及企业提交和学术评价团队分析。2.2以public healthcare payer为标准，并反映日本成本、对照、人群；其他视角分析仍须同时提供标准视角。公共长期照护或生产力可在符合条件时另呈。
- 来源章节及URL：JP02-A1，1—2章PDF/印刷p4—5；https://c2h.niph.go.jp/tools/guideline/guideline_en_2026.pdf 。
- 日期/版本：封面批准2026-01-16；2026-10-31读取。
- 适用边界：以日文原文优先；不是所有新药获批前必须做成本效果评价的证明，也不是日本完整上市收载制度。
- NPL用途：确定是否需启动正式本地HEOR提交及附加视角。
- 建议：先核产品选定状态、评估框架和本地证据，再判断资源配置；不可因英国模型已完成便认定日本已就绪。
- tags：C2H；Japan；selected product；payer perspective
- 检索问句：C2H2026成本效果方法是否意味着所有日本新药都需在首发前提交ICER？

### OR-JP03｜目标人群与对照须按日本实践和适应证分层
- 事实：第3章以评价选定时适应证人群为起点，框架确定前新增适应证纳入；影响结果的新适应证可在初评后另评。多适应证/亚组若结局、剂量、给药或对照不同需分层；第4章对照取日本临床广泛使用且预期被替代的候选，优先最佳结局，不仅以销量判断标准治疗，选择需说明。
- 来源章节及URL：JP02-A1，3—4章PDF/印刷p6—7；同JP02-A1 URL。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：无法唯一确定对照时需咨询讨论，不直接把注册试验对照、定价比较药或海外HTA对照视为同一项；人群省略需影响有限且适当。
- NPL用途：全球人群/试验对照与日本正式评价范围的差距识别。
- 建议：建立适应证、亚组、剂量、对照与本地使用比例矩阵；保留框架冻结日与新增适应证影响。
- tags：target population；comparator；Japan；indication expansion
- 检索问句：日本经济评价为何可能需要按多个适应证分别建模，试验对照能否直接沿用？

### OR-JP04｜先证实额外获益，再决定ICER或成本比较
- 事实：第5章先用经验数据评价相对额外获益，以RCT系统综述为起点；明确PICO、纳排、数据库、检索及PRISMA流程，考虑未发表研究与更新截止。缺RCT时转比较性非随机研究，质量和日本外推需解释；单臂情形需基于综述间接比较。第6章额外获益确认时算ICER；无确认额外获益时做成本比较；明显优势支配时不需要ICER；第5.11若结局劣于对照则不做成本效果分析。
- 来源章节及URL：JP02-A1，5.1—5.11及6.1—6.5，PDF/印刷p8—12；同JP02-A1 URL。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：不能把“未确认额外获益”解读为产品无效或未获批准；本卡不评判具体研究是否足够。
- NPL用途：证据综合计划与模型方法选择，避免先算一个ICER再倒推证据。
- 建议：HEOR先输出额外获益证据评估及对照匹配，再锁定经济分析形式。
- tags：additional benefit；systematic review；ICER；CMA；PRISMA
- 检索问句：C2H评价没有确认额外获益时，是否仍应强行计算ICER？

### OR-JP05｜单臂和真实世界数据不是自动低风险捷径
- 事实：第5.3指出大型回顾数据库并不必然高质量，须解释数据库特征、变量定义及验证、背景差异、分析和日本可推广性；5.7优先有锚间接比较，MAIC/NMA需解释假设与方法选择，naïve比较仅别无选择时并详述可比性。14.3特别要求单臂间接比较用足够宽范围敏感性分析。
- 来源章节及URL：JP02-A1，5.3—5.7 PDF/印刷p9—11；14.3 p28；同JP02-A1 URL。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：不是对所有RWD一概否定，也不是认可任意MAIC必然解决未测量混杂；需具体设计判断。
- NPL用途：评估注册可接受证据与日本相对效果/经济评价证据之间的风险。
- 建议：在单臂开发策略形成时同步规划外部对照、共同变量、可迁移性及不确定性，不等获批后补救。
- tags：RWD；MAIC；NMA；single-arm；transitivity；uncertainty
- 检索问句：单臂注册成功后，日本成本效果评价需要补充哪些相对效果证据？

### OR-JP06｜日本效用采用本国偏好，儿童和照护者有独立边界
- 事实：第8章原则使用QALY，PBM效用反映日本一般人群偏好，初选推荐日版EQ-5D-5L；优先患者回答，不能回答时可代理，避免医务人员代理。外国产生的描述数据可在适当情形套日本value set，映射需充分报告；8.9明确成人部分原则不直接适用于儿童青少年，需解释工具和选择。8.7的照护者QOL限公共医疗/长期照护视角且有经验数据，方法逐案。
- 来源章节及URL：JP02-A1，8.1—8.9.1，PDF/印刷p14—17；同JP02-A1 URL。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：不能直接使用英国Rowen2026价值集作为日本标准；不能把一般PRO分数视为可直接计算QALY的效用。
- NPL用途：全球试验PRO采集和地区效用再分析设计。
- 建议：共同保留原始描述回答，但按地区偏好体系产生效用；儿童与照护者单独预设证据和分析。
- tags：EQ-5D-5L；Japanese value set；QALY；PRO；儿童
- 检索问句：同一全球EQ-5D-5L试验数据能否不重新赋值直接用于英国和日本？

### OR-JP07｜成本需贴近日本实际资源，并可追溯到数量与单价
- 事实：第9章治疗路径反映日本标准实践；第10章只纳入本技术直接影响的相关公共医疗成本，优先适当日本claims数据，说明健康状态定义、异常值及无关成本处理；微观成本法时数量与单价分列，注射产品按瓶数而非患者剂量成本。采用最新价目，已上市仿制对照还应提供相应成本分析；海外资源用量需关注实践差异并套日本单价。
- 来源章节及URL：JP02-A1，9.1—9.4、10.1—10.12，PDF/印刷p18—22；同JP02-A1 URL。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：公共医疗成本在指南定义内包含保险方、公共资金及患者分担，不可误读成仅保险方实际出账；长期照护/生产力另见第11章。
- NPL用途：全球成本模型本地化、用药瓶数/浪费和监测路径规划。
- 建议：模型输入附日本资源量、当期价格、数据来源与更新时间，避免直接转换海外总成本汇率。
- tags：costing；claims data；micro-costing；Japan；resource use
- 检索问句：日本HEOR成本本地化为什么不等于把海外总成本换成日元？

### OR-JP08｜贴现、模型交付与不确定性要求不能从NICE直接复制
- 事实：第7章成本与效果用相同时限且足够覆盖影响；第12章默认成本/效果均2%年贴现，并0%—4%同率敏感性分析，足够短时限可不贴现；第13章要求电子模型可被第三方理解、主要参数可修改，随机模型固定种子并展示稳定性；第14章包括场景、长时限短期分析、关键假设/地区差异敏感性。p28第二个14.6称PSA desirable，若做需呈分布、成本效果平面和CEAC。
- 来源章节及URL：JP02-A1，7章p13、12—14章p25—28；同JP02-A1 URL；p25/p28已看原页。
- 日期/版本：2026-01-16批准版本；2026-10-31读取。
- 适用边界：不要把PSA desirable改写成不分情形一律强制；原文重复14.6已保留；本卡不转录未核对公式。
- NPL用途：多市场模型参数与质量保证、可复现交付。
- 建议：日本2%与英国默认3.5%分别配置并验证，模型交付包含可编辑参数、种子和替代情景记录。
- tags：discounting；2%；model validation；PSA；CEAC；reproducibility
- 检索问句：英国NICE模型移植日本时，贴现和模型可审计性有哪些差异？

### OR-JP09｜日本新药获批、药价收载与商业供货是不同节点
- 事实：2026收载通知1(1)列希望书递交时点：批准后一周或批准前最近药品部会结束后三周，两者较早者，另有指定期限/特殊情形；1(2)标准处理从批准起原则60日内、最迟90日内，但迟交、异议、特殊情况及补正资料等有例外；1(6)除正当不可避免理由外，收载后三个月内开始供应并持续供应，提交供货开始报告。
- 来源章节及URL：JP02-A2，1(1)、1(2)、1(6)，PDF p2—5/印刷p1—4；https://c2h.niph.go.jp/tools/system/notification_drug_listing_2026.pdf 。时限原页PDF p3已核对。
- 日期/版本：2026-02-13发布；2026-04-01起；2026-10-31读取。
- 适用边界：日文工作译读；60/90日是带例外标准行政处理期，不是批准后自动收载或固定首发保证；其他品类另有流程。
- NPL用途：日本批准、收载希望书、定价、供货的串联倒排。
- 建议：批准前准备收载附件及价格证据，同时核查实际供应能力；不要批准后才开始资料编制。
- tags：Japan；NHI listing；60/90 days；supply；上市依赖项
- 检索问句：日本药品批准后是否自动在90天内有医保价格并开始供货？

### OR-JP10｜日本初次定价比较药与成本效果对照不能自动等同
- 事实：2026定价标准第1章15—22分别定义类似药、最类似药、比较药、类似药效比较I/II与成本计算法；第2章第1部区分有类似药与无类似药新药，前者再按加算/组成等条件分支，后者原则成本计算，适用时另做外国平均价格调整。C2H方法第4章的经济评价对照另以日本实践和被替代治疗为起点。
- 来源章节及URL：JP02-A3，第1章15—22（PDF p5—8/印刷p4—7）、第2章第1部第1—2节（PDF p13—16/印刷p12—15）；https://c2h.niph.go.jp/tools/system/notification_drug_pricing_2026.pdf 。JP02-A1第4章p7，同指南URL。
- 日期/版本：定价通知2026-02-13、2026-04-01起；指南2026-01-16。
- 适用边界：只是已读分支概念，不包含全部加算条件、外价公式或特例；不能据此计算某产品预期药价。
- NPL用途：区分临床试验对照、收载定价比较药和经济评价比较治疗。
- 建议：三类对照分别建字段与选择理由，避免全球单一comparator栏覆盖不同目的。
- tags：Japan pricing；comparator；cost calculation；NHI；证据分层
- 检索问句：日本药价算定的比较药与C2H成本效果评价对照是不是同一个？

### OR-JP11｜既收载品成本效果价格调整有选定、结果与过渡版本条件
- 事实：2026定价标准第3章第12节针对被指定评价且结果已确定的既收载品，描述每年4次可进行的价格调整，并要求与其他调价同时发生时用调价后价格计算相关ICER；同节保留2026-03-31前已指定产品适用旧评价通知的条款。第4章1(9)还指出相应适用时间及别表12可能由后续另定通知接替。
- 来源章节及URL：JP02-A3，第3章第12节、第4章1(9)，PDF p45—46/印刷p44—45；同notification_drug_pricing_2026.pdf URL。
- 日期/版本：2026-02-13原通知；2026-10-31选章读取。
- 适用边界：本次没有追踪后续别表12通知是否已发、没读完计算表，不将此卡写成截至2026-10-31的完整计算规范；不把价格调整视为首次覆盖资格一刀切决定。
- NPL用途：产品上市后价格生命周期、旧新制度分界和模型更新。
- 建议：逐品记录选定日、评价结果节点、价格版本和后续通知，价格预测需由当地专家复核。
- tags：C2H；price adjustment；lifecycle；transition；version control
- 检索问句：日本成本效果评价价格调整是否一律适用同一版规则，已有产品需核哪些日期？

## 三、综合应用建议（顾问推论，非原文要求）

1. **用一套证据资产、多个地区决策问题。** 可复用原始临床/PRO及综合方法，但注册对照、德国额外获益对照、日本定价比较药、日本经济评价对照和NICE比较方案分别管理。
2. **把批准和准入拆开。** FDA批准、CHMP意见、集中授权、英国IRP、国家HTA/支付、药价收载与供应启动不互相替代。CMS未读，不对美国覆盖作推断。
3. **把提速的证据风险转成上市依赖项。** 单臂、替代终点、长期外推会影响后续相对效果和经济评价；CMC、CDx、确认试验及本地数据应并行准备。
4. **版本检查进入项目门禁。** NICE5L、MHRA资格窗口冲突、日本旧新指定边界，均须在实际申报前保留快照和机构/当地专家确认；不靠“官方入口存在”证明全套规则已审查。

## 四、全部未完成项与后续阅读优先级

### 需补原文或访问失败
- JCA：准确附件已定位但下载429；2024程序指南全文未读，不能形成PICO scoping、dossier、问题澄清和提交日历结论；最新修订状态也未核定。
- PMDA：指定000282949.pdf两次502，题名版本及全文均未核定；索引只到A—K摘录，产品报告均未逐份读。
- HAS早期准入：入口terminated/403；搜索显示有2026企业指南、申请模板和PUT-RD等，只能作待取清单，不作原文事实。常规HTA/SMR/ASMR入口本件未处理。
- FDA：2014历史指南已全文读，但后续加速批准final更新、确认试验/撤回新程序及现行PDUFA目标未完整追踪；2024-12 Not for implementation附件未读。

### 已选章但不能称整包完成
- MHRA：剩余全部RR文件要求、上市后变更/续展细则、启动日表未全读；需确认8周/6周及5年/10年冲突。
- NICE：PMG36除经济评价章及概览之外尚未全读；最新资金变更目标5.10正文未取得；PMG51核心statement、process considerations独立章节及附录C遗漏FAQ未全读，不能猜slug；TSD22和新版计分/映射实现未核验；figure4.1未完整进行视觉核对。
- 德国：德文现行VerfO、AM-NutzenV、对照/孤儿药特殊要求、最新dossier模板和国家EU-HTA衔接细则未全文读；英文概览时限不能作为现行适用性结论。
- 日本：定价通知虽全文解析，但只读所列章；其余再算定、加算、外价公式、别表12、后续通知未完整核验。C2H正式cost-effectiveness通知（notification_cost-effectiveness_2026.pdf）尚未下载读；不能仅靠收载附表证明完整H1—H5选定范围。
- EMA：集中程序子指南、科学咨询及其他注册路径没有因本页已读而自动完成。

### 本件未处理，与团队其他交付合并判断
- CMS Alzheimer’s mAb覆盖/CED；EU2025问答PDF；ICH各指南与AMCP6.0全文由其他子任务继续。
- 不补造未读文件的知识卡、不以卡数替代覆盖率。本文共27张候选卡，含入口方法/选章/历史版本卡；任何正式知识新增仍需用户另行明确授权。

## 五、解析证据定位

- 原文、CLI提取及页图已由主助手复制留存至项目相对目录`npl-sources/overseas-regulatory/`；未删除原暂存文件。原暂存路径`/tmp/pharma-overseas.xZVPE9/`可能被系统清理，后续以项目留存为准。该目录仅为研究证据，不是已入库内容，也不表示获得全文再分发许可。
- `fda-2014.pdf` / `fda-2014.txt`：40页，CLI无扫描页/无警告；印刷页码=PDF页序减4。
- `c2h-guideline.pdf` / `c2h-guideline.txt`：36页，CLI无扫描页/无警告；正文印刷页与PDF页序一致。
- `c2h-listing.pdf` / `c2h-listing.txt`：18页，CLI无扫描页/无警告；附件正文印刷页=PDF页序减1。
- `c2h-pricing.pdf` / `c2h-pricing.txt`：76页，CLI无扫描页/无警告；正文印刷页=PDF页序减1；仅台账所列选章已读。
- 图像核查：`fda-pages/page-0012.png`、`c2h-listing-pages/page-0003.png`、`c2h-guideline-pages/page-0025.png`、`c2h-guideline-pages/page-0028.png`。
