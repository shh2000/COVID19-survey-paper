## 分类字段介绍

* 从属：属于哪个期刊及其子刊
* 编号：对应原论文pdf用
* 见刊时间：通常比发表时间晚1-4个月，比工作时间晚2-5个月
* 作者国际机构：国内能查到的写人名，英美等著名高校写校名，其他写国籍
* 研究兴趣：这个论文的写作目的是什么

## 研究兴趣

* 疫情建模：试图提高对于疫情预测的精度、适用于具体、综合场景的建模
* 输入数据分析：提高输入数据的可用性
* 影响因素分析：分析某类因素、数据对于疫情的影响
* 影响分析：分析疫情对于某类因素、数据的影响
* 综述介绍类：综述文章，或者介绍某一客观事实规律

## 分类结果

1. 从研究兴趣来说：
   * 综述介绍类8篇，影响因素分析40篇，影响分析5篇，疫情建模40篇，输入数据分析5篇，其他1篇
   * 疫情建模与影响因素分析为主流研究方向
   * 单纯的影响分析较少，自耦合模型也较少，仍有研究空间
   * 专门的输入数据分析类较少，但大多数论文都使用了各种渠道统计出来的数据，这些数据的可信性存疑
2. 从模型类别来看：
   * 仅使用仓室模型35篇，此外还有大量的静态统计分析、回归模型用到了仓室模型中人群状态、Rt等关键信息及其意义
   * 智能体模型16篇
   * 静态统计模型、计算28篇，大多数为影响因素分析类文章，综述介绍类可放入此
   * 目前大多数文章集中于仓室模型及其变体，纯ML或智能体模型较少，此类模型应用于传染病建模尚有挖掘空间

| 序号 | 题目                                                         | 类型(主刊/子刊)                | 文章类型（Article, Research, Letter） | 方法类型（compartment model, agent-based model,  epidemic characteristic） |
| ---- | ------------------------------------------------------------ | ------------------------------ | ------------------------------------- | ------------------------------------------------------------ |
| 1    | A guideline to limit indoor airborne transmission of COVID-19 | 主刊                           | Research                              | Well-mixed room model for airborne transmission              |
| 22   | Impact of international travel and border control measures on the global  spread of the novel 2019 coronavirus outbreak | 主刊                           | Research                              | risk estimation model                                        |
| 6    | Cell-phone traces reveal infection-associated behavioral change | 主刊                           | Research                              | regression                                                   |
| 10   | Economic and social consequences of human mobility restrictions under  COVID-19 | 主刊                           | Research                              | regression                                                   |
| 12   | Evaluating the effects of shelter-in-place policies during the COVID-19  pandemic | 主刊                           | Research                              | regression                                                   |
| 15   | Explaining the homogeneous diffusion of COVID-19 nonpharmaceutical  interventions across heterogeneous countries | 主刊                           | Research                              | regression                                                   |
| 16   | Face masks considerably reduce  COVID-19 cases in Germany    | 主刊                           | Research                              | regression                                                   |
| 21   | Identifying airborne transmission as the dominant route for the spread of  COVID-19 | 主刊                           | Research                              | regression                                                   |
| 25   | Mobile device data reveal the dynamics in a positive relationship between  human mobility and COVID-19 infections | 主刊                           | Brief Report                          | regression                                                   |
| 30   | Public health interventions and epidemic intensity during the 1918  influenza pandemic | 主刊                           | Research                              | regression                                                   |
| 32   | Rationing social contact during the COVID-19 pandemic: Transmission risk  and social benefits of US locations | 主刊                           | Brief Report                          | regression                                                   |
| 35   | Seasonality and uncertainty in global COVID-19 growth rates  | 主刊                           | Research                              | regression                                                   |
| 37   | Social distancing decreases an individual’s likelihood of contracting  COVID-19 | 主刊                           | Research                              | regression                                                   |
| 38   | Social distancing responses to COVID-19 emergency declarations strongly  differentiated by income | 主刊                           | Brief Report                          | regression                                                   |
| 41   | The effects of school closures on SARS-CoV-2 among parents and teachers | 主刊                           | Research                              | regression                                                   |
| 13   | Estimating internationally imported cases during the early COVID-19  pandemic | Nature Communications          | Article                               | other model                                                  |
| 18   | Machine learning model to project the impact of COVID-19 on US motor  gasoline demand | Nature energy                  | Article                               | ML model                                                     |
| 13   | Event-specific interventions to minimize COVID-19 transmission | 主刊                           | Research                              | mathematical equations                                       |
| 3    | Acceleration of plague outbreaks in the second pandemic      | 主刊                           | Research                              | logistic model                                               |
| 36   | Short-term forecasts of expected deaths                      | 主刊                           | Research                              | linear equation                                              |
| 48   | Vaccinating the oldest against COVID-19 saves both the most lives and  most years of life | 主刊                           | Brief Report                          | linear equation                                              |
| 4    | An interpretable mortality prediction model for COVID-19 patients | Nature Machine Intelligence    | Article                               | epidemic characteristic + interpretable model                |
| 2    | Accommodating individual travel history and unsampled diversity in  Bayesian phylogeographic inference of SARS-CoV-2 | Nature Communications          | Article                               | epidemic characteristic                                      |
| 3    | Age-specific mortality and immunity patterns of SARS-CoV-2   | Nature Research                | Article                               | epidemic characteristic                                      |
| 6    | Assessing transmissibility of SARS-CoV-2 lineage B.1.1.7 in England | Nature Research                | Article                               | epidemic characteristic                                      |
| 7    | Associations between blood type and COVID-19 infection, intubation, and  death | Nature Communications          | Article                               | epidemic characteristic                                      |
| 8    | Changing travel patterns in China during the early stages of the COVID-19  pandemic | Nature Communications          | Article                               | epidemic characteristic                                      |
| 9    | Characteristics of SARS-CoV-2 and COVID-19                   | Nature Reviews:Microbiology    | Reviews                               | epidemic characteristic                                      |
| 10   | Disease burden and clinical severity of the first pandemic wave of  COVID-19 in Wuhan, China | Nature Communications          | Article                               | epidemic characteristic                                      |
| 12   | Epidemiological and clinical characteristics of the COVID-19 epidemic in  Brazil | Nature Human Behaviour         | Article                               | epidemic characteristic                                      |
| 17   | Forward-looking serial intervals correctly link epidemic growth to  reproduction number | 主刊                           | Research                              | epidemic characteristic                                      |
| 19   | Global evidence for ultraviolet radiation decreasing COVID-19 growth  rates | 主刊                           | Research                              | epidemic characteristic                                      |
| 20   | Higher airborne pollen concentrations correlated with increased  SARS-CoV-2 infection rates, as evidenced from 31 countries across the globe | 主刊                           | Research                              | epidemic characteristic                                      |
| 1    | A mathematical model reveals the influence of population  heterogeneity on herd immunity to SARS-CoV-2 | 主刊                           | Research                              | epidemic characteristic                                      |
| 2    | Age groups that sustain resurging COVID-19 epidemics in the  United States | 主刊                           | Research                              | epidemic characteristic                                      |
| 3    | An investigation of transmission control measures during the  first 50 days of the COVID-19 epidemic in China | 主刊                           | Research                              | epidemic characteristic                                      |
| 4    | Anatomy of digital contact tracing_ Role of age, transmission  setting, adoption and case detection | SCIENCE ADVANCES               | Research                              | epidemic characteristic                                      |
| 5    | Assessing the impact of coordinated COVID-19 exit strategies  across Europe | 主刊                           | Research                              | epidemic characteristic                                      |
| 9    | Epidemiology and transmission dynamics of COVID-19 in two  Indian states | 主刊                           | Research                              | epidemic characteristic                                      |
| 10   | Establishment and lineage dynamics of the SARS-CoV-2 epidemic  in the UK | 主刊                           | Research                              | epidemic characteristic                                      |
| 11   | Estimated transmissibility and impact of SARS-CoV-2 lineage  B.1.1.7 in England | 主刊                           | Research                              | epidemic characteristic                                      |
| 13   | Estimation of incubation period distribution of COVID-19 using  disease onset forward time_ a novel cross-sectional and forward follow-up  study | SCIENCE ADVANCES               | Research                              | epidemic characteristic                                      |
| 18   | Quantifying SARS-CoV-2 transmission suggests epidemic control  with digital contact tracing | 主刊                           | Research                              | epidemic characteristic                                      |
| 21   | Susceptible supply limits the role of climate in the early  SARS-CoV-2 pandemic | 主刊                           | Research                              | epidemic characteristic                                      |
| 22   | Test sensitivity is secondary to frequency and turnaround time  for COVID-19 screening | SCIENCE ADVANCES               | Research                              | epidemic characteristic                                      |
| 23   | The effect of human mobility and control measures on the  COVID-19 epidemic in China | 主刊                           | Research                              | epidemic characteristic                                      |
| 24   | The effect of travel restrictions on the spread of the 2019  novel coronavirus (COVID-19) outbreak | 主刊                           | Research                              | epidemic characteristic                                      |
| 25   | The impact of COVID-19 and strategies for mitigation and  suppression in low- and middle-income countries | 主刊                           | Research                              | epidemic characteristic                                      |
| 26   | The unfolding COVID-19 pandemic_ A probability-based,  nationally representative study of mental health in the U.S. | SCIENCE ADVANCES               | Research                              | epidemic characteristic                                      |
| 27   | Unexpected air pollution with marked emission reductions  during the COVID-19 outbreak in China | 主刊                           | Research                              | epidemic characteristic                                      |
| 24   | Mechanistic transmission modeling of COVID-19 on the Diamond Princess  cruise ship demonstrates the importance of aerosol transmission | 主刊                           | Research                              | computational fluid dynamics simulation                      |
| 2    | A network-based explanation of why most COVID-19 infection curves are  linear | 主刊                           | Research                              | compartment model; metapopulation                            |
| 8    | COVID-19 lockdown induces disease-mitigating structural changes in  mobility networks | 主刊                           | Research                              | compartment model; metapopulation                            |
| 14   | Evidence that coronavirus superspreading is fat-tailed       | 主刊                           | Research                              | compartment model; metapopulation                            |
| 18   | Global COVID-19 pandemic demands joint interventions for the suppression  of future waves | 主刊                           | Research                              | compartment model; metapopulation                            |
| 40   | Spread and dynamics of the COVID-19 epidemic in Italy: Effects of  emergency containment measures | 主刊                           | Research                              | compartment model; metapopulation                            |
| 44   | The interplay of movement and spatiotemporal variation in transmission  degrades pandemic control | 主刊                           | Brief Report                          | compartment model; metapopulation                            |
| 46   | Timing social distancing to avert unmanageable COVID-19 hospital surges | 主刊                           | Research                              | compartment model; metapopulation                            |
| 47   | Transmission dynamics reveal the impracticality of COVID-19 herd immunity  strategies | 主刊                           | Research                              | compartment model; metapopulation                            |
| 5    | Assessing the influence of climate on wintertime SARS-CoV-2 outbreaks | Nature Communications          | Article                               | compartment model + epidemic characteristic                  |
| 1    | A model to rate strategies     for managing disease due     to COVID‑19 infection | Nature Research                | Scitific Reports                      | compartment model                                            |
| 11   | Effect of non-pharmaceutical interventions to contain COVID-19 in China | Nature Research                | Article                               | compartment model                                            |
| 14   | Estimating the effects of non-pharmaceutical interventions on COVID-19 in  Europe | Nature Research                | Article                               | compartment model                                            |
| 15   | Evaluating the impact of curfews and other measures on SARS-CoV-2  transmission in French Guiana | Nature Communications          | Article                               | compartment model                                            |
| 17   | Infectivity, susceptibility, and risk factors associated with SARS-CoV-2  transmission under intensive contact tracing in Hunan, China | Nature Communications          | Article                               | compartment model                                            |
| 19   | Mathematical model of COVID-19 intervention scenarios for São  Paulo—Brazil | Nature Communications          | Article                               | compartment model                                            |
| 20   | Mobility network models of COVID-19 explain inequities and inform  reopening | Nature Research                | Article                               | compartment model                                            |
| 21   | Modelling safe protocols for reopening schools during the COVID-19  pandemic in France | Nature Communications          | Article                               | compartment model                                            |
| 23   | Optimal, near-optimal, and robust epidemic control           | Communications physics         | Article                               | compartment model                                            |
| 24   | Real-time tracking and prediction of COVID-19 infection using digital  proxies of population mobility and mixing | Nature Communications          | Article                               | compartment model                                            |
| 25   | Reconstruction of the full transmission dynamics of COVID-19 in Wuhan | Nature Research                | Article                               | compartment model                                            |
| 26   | Reduction in mobility and COVID-19 transmission              | Nature Communications          | Article                               | compartment model                                            |
| 4    | Awareness-driven behavior changes can shift the shape of epidemics away  from peaks and toward plateaus, shoulders, and oscillations | 主刊                           | Research                              | compartment model                                            |
| 9    | Dynamic prioritization of COVID-19 vaccines when social distancing is  limited for essential workers | 主刊                           | Research                              | compartment model                                            |
| 11   | Estimating unobserved SARS-CoV-2 infections in the United States | 主刊                           | Research                              | compartment model                                            |
| 23   | Local lockdowns outperform global lockdown on the far side of the  COVID-19 epidemic curve | 主刊                           | Research                              | compartment model                                            |
| 29   | Projecting hospital utilization during the COVID-19 outbreaks in the  United States | 主刊                           | Research                              | compartment model                                            |
| 31   | Quantifying asymptomatic infection and transmission of COVID-19 in New  York City using observed cases, serology, and testing capacity | 主刊                           | Research                              | compartment model                                            |
| 34   | Retrospective analysis of the  Italian exit strategy from COVID-19 lockdown | 主刊                           | Research                              | compartment model                                            |
| 42   | The impact of COVID-19 nonpharmaceutical interventions on the future  dynamics of endemic infections | 主刊                           | Research                              | compartment model                                            |
| 45   | The turning point and end of an expanding epidemic cannot be precisely  forecast | 主刊                           | Research                              | compartment model                                            |
| 7    | Effective containment explains sub-exponential growth in  recent confirmed COVID-19 cases in China | 主刊                           | Research                              | compartment model                                            |
| 8    | Epidemiological and evolutionary considerations of SARS-CoV-2  vaccine dosing regimes | 主刊                           | Research                              | compartment model                                            |
| 15   | Immune life history, vaccination, and the dynamics of  SARS-CoV-2 over the next 5 years | 主刊                           | Research                              | compartment model                                            |
| 16   | Inferring change points in the spread of COVID-19 reveals the  effectiveness of interventions | 主刊                           | Research                              | compartment model                                            |
| 28   | Using influenza surveillance networks to estimate  state-specific prevalence of SARS-CoV-2 in the United States | SCIENCE TRANSLATIONAL MEDICINE | Report                                | compartment model                                            |
| 28   | State-level tracking of COVID-19 in the United States        | Nature Communications          | Article                               | bayesian model                                               |
| 29   | Substantial underestimation of SARS-CoV-2 infection in the United States | Nature Communications          | Article                               | bayesian model                                               |
| 30   | The impact of uncertainty on predictions of the CovidSim epidemiological  code | Nature Computational Science   | Article                               | bayesian model                                               |
| 5    | Bayesian estimation of SARS-CoV-2 prevalence in Indiana by random testing | 主刊                           | Research                              | Bayesian methods                                             |
| 39   | Spatial heterogeneity can lead to substantial local variations in  COVID-19 timing and severity | 主刊                           | Research                              | agent-based model; social network                            |
| 16   | Implications of the school-household network structure on SARS-CoV-2  transmission under school reopening strategies in England | Nature Communications          | Article                               | agent-based model                                            |
| 22   | Modelling transmission and control of the COVID-19 pandemic in Australia | Nature Communications          | Article                               | agent-based model                                            |
| 27   | Revealing COVID-19 transmission in Australia by SARS-CoV-2 genome  sequencing and agent-based modeling | Nature Medicine                | Letter                                | agent-based model                                            |
| 7    | Characterizing superspreading events and age-specific infectiousness of  SARS-CoV-2 transmission in Georgia, USA | 主刊                           | Research                              | agent-based model                                            |
| 26   | Modeling between-population variation in COVID-19 dynamics in Hubei,  Lombardy, and New York City | 主刊                           | Research                              | agent-based model                                            |
| 27   | Network interventions for managing the COVID-19 pandemic and sustaining  economy | 主刊                           | Research                              | agent-based model                                            |
| 28   | Overdispersion in COVID-19 increases the effectiveness of limiting  nonrepetitive contacts for transmission control | 主刊                           | Research                              | agent-based model                                            |
| 33   | Retail store customer flow and COVID-19 transmission         | 主刊                           | Research                              | agent-based model                                            |
| 43   | The implications of silent transmission for the control of COVID-19  outbreaks | 主刊                           | Brief Report                          | agent-based model                                            |
| 6    | Changes in contact patterns shape the dynamics of the COVID-19  outbreak in China | 主刊                           | Research                              | agent-based model                                            |
| 12   | Estimating the burden of SARS-CoV-2 in France                | 主刊                           | Research                              | agent-based model                                            |
| 14   | Evolution and epidemic spread of SARS-CoV-2 in Brazil        | 主刊                           | Research                              | agent-based model                                            |
| 17   | Projecting the transmission dynamics of SARS-CoV-2 through the  postpandemic period | 主刊                           | Research                              | agent-based model                                            |
| 19   | Serial interval of SARS-CoV-2 was shortened over time by  nonpharmaceutical interventions | 主刊                           | Research                              | agent-based model                                            |
| 20   | Substantial undocumented infection facilitates the rapid  dissemination of novel coronavirus (SARS-CoV2) | 主刊                           | Research                              | agent-based model                                            |

| 从属    | 编号 | 见刊时间 | 作者/机构/国籍（完成者身份）    | 研究兴趣     | 解决了什么问题/面向什么问题提出讨论                    | 一句话描述解决方案/文章讲述内容/main contribution            |
| ------- | ---- | -------- | ------------------------------- | ------------ | ------------------------------------------------------ | ------------------------------------------------------------ |
| Nature  | 9    | 2021.3   | 中科院，胡犇                    | 综述介绍类   | 新冠肺炎病毒的基础特征（包含流行病学特征）             | 综述类                                                       |
| Nature  | 10   | 2020     | 复旦大学+英美，杨娟             | 综述介绍类   | 武汉爆发疫情的医疗需求与传播范围介绍                   | 偏静态统计学特征                                             |
| Nature  | 17   | 2021     | 与Nature.10属同一大团队         | 综述介绍类   | 介绍了年龄、是否有症状和流行病学传播机制的关系         | 偏静态统计学特征                                             |
| PNAS    | 1    | 2021.3   | MIT                             | 综述介绍类   | 介绍个人防护的准则，基于室内个体传播模型               | 结合了具体物理环境，建模很复杂                               |
| PNAS    | 6    | 2020.12  | 埃默里大学                      | 综述介绍类   | 介绍了mobility（手机信令）在患者、健康人群中的不同特征 | 分类细化、静态统计                                           |
| PNAS    | 14   | 2020.9   | 剑桥                            | 综述介绍类   | 描述疫情发展规律的分布是长尾分布                       | 统计分析                                                     |
| PNAS    | 45   | 2020.9   | 西班牙高校                      | 综述介绍类   | 表明疫情的结束时间无法被精确预测                       | SIR                                                          |
| Science | 9    | 2020.11  | 印度高校                        | 综述介绍类   | 介绍欠发达地区的病例数据分布特征                       | 统计数据结果                                                 |
| Nature  | 5    | 2021     | 普林斯顿                        | 影响因素分析 | 气候影响大吗（冬季会消退吗）                           | 大数据估Rt，随后仓室模型                                     |
| Nature  | 7    | 2020     | 哥大                            | 影响因素分析 | 血型对各类参数的影响                                   | 经典仓室模型                                                 |
| Nature  | 11   | 2020.9   | 与Nature.10属同一大团队         | 影响因素分析 | 非药物干预措施的影响                                   | 空间细化，基于旅行网络的SEIR（信令+旅游网络构建mobiliity）   |
| Nature  | 12   | 2020.8   | 巴西                            | 影响因素分析 | 流行病学、诊所和收入对疫情的影响                       | 部分大数据估Rt，随后仓室模型中融合其他数据                   |
| Nature  | 14   | 2020.8   | 帝国理工                        | 影响因素分析 | 非药物干预措施的影响（特指欧洲）                       | 大数据估Rt，随后仓室模型，拟合死亡观测值                     |
| Nature  | 15   | 2021     | 法国、法属圭亚那                | 影响因素分析 | 宵禁类措施（特指法属圭亚那）                           | 年龄结构横向分层                                             |
| Nature  | 16   | 2021     | LSHTM                           | 影响因素分析 | 放宽学校管制措施的后果（政策仿真）                     | 构建传播网络，基于网络（图）建模SEIR                         |
| Nature  | 21   | 2021     | 法国、日本高校                  | 影响因素分析 | 放宽学校管制措施的后果（政策仿真）（特指法国）         | 仓室模型+不同政策大数据构建对应参数                          |
| Nature  | 26   | 2021     | 帝国理工等英国高校              | 影响因素分析 | 探究流动性和疫情传播的综合关联                         | SEIR改，流动大数据估算Rt                                     |
| PNAS    | 12   | 2021.2   | 芝加哥大学                      | 影响因素分析 | 估算居家隔离？（直译为就地避难）措施的影响             | 仓室+统计分析                                                |
| PNAS    | 13   | 2020.11  | 加拿大高校                      | 影响因素分析 | 建立框架，建模一切额外事件的影响                       | 传统的物理数学模型，预留了额外事件的嵌入接口                 |
| PNAS    | 15   | 2020.7   | 林雪平大学                      | 影响因素分析 | 解释非药物干预措施在不同国家的同质化                   | 偏社科，介绍了为什么国家间会跟随非药物干预措施，含有政治、社会分析等 |
| PNAS    | 16   | 2020.11  | 丹麦高校                        | 影响因素分析 | 估算口罩在疫情中的作用                                 | 统计分析                                                     |
| PNAS    | 19   | 2020.11  | 加州大学                        | 影响因素分析 | 紫外线对于疫情发展的影响                               | 先Rt的偏静态统计模型                                         |
| PNAS    | 20   | 2021.1   | 慕尼黑大学等德国高校            | 影响因素分析 | 探究花粉传播对于新冠的影响？？？                       | 多国家、物理数学模型，设计了好的指标                         |
| PNAS    | 21   | 2020.5   | 德州农工                        | 影响因素分析 | 介绍了空气传播是新冠传播的主要因素                     | 偏静态物理数学模型                                           |
| PNAS    | 22   | 2020.2   | 耶鲁、多伦多等高校              | 影响因素分析 | 探究国际旅行、禁令的影响                               | 数学物理模型+蒙特卡洛模拟风险                                |
| PNAS    | 23   | 2020.8   | 加拿大高校                      | 影响因素分析 | 介绍了本地封锁相比于国际间封锁更优                     | SEIR+传播旅游网络图                                          |
| PNAS    | 24   | 2021.1   | 哈佛、伊利诺伊理工              | 影响因素分析 | 介绍了气溶胶传播方式的显著影响                         | 仓室+物理数学模型仿真                                        |
| PNAS    | 25   | 2020.9   | 马里兰大学                      | 影响因素分析 | 介绍了移动强度对于疫情的影响                           | 建模疫情后与手机信令数据进行统计学分析                       |
| PNAS    | 32   | 2020.5   | MIT                             | 影响因素分析 | 探究在考虑社会影响、成本等综合因素下，关闭哪些场所最优 | 静态统计学模型，时间对轴疫情                                 |
| PNAS    | 34   | 2020.12  | 意大利高校                      | 影响因素分析 | 研究不再执行特定策略后的疫情发展                       | 仓室+政策仿真                                                |
| PNAS    | 35   | 2020.9   | 康涅狄格大学                    | 影响因素分析 | 天气、季节对疫情的影响                                 | 静态统计学模型，时间对轴疫情                                 |
| PNAS    | 37   | 2021.1   | 荷兰高校                        | 影响因素分析 | 社交距离对于新冠的影响                                 | 静态统计分析                                                 |
| PNAS    | 38   | 2020.7   | 加州大学                        | 影响因素分析 | 收入不同人们对于新冠社交距离的反映不同                 | 静态统计分析                                                 |
| PNAS    | 40   | 2020.4   | 意大利高校                      | 影响因素分析 | 考虑防控措施的影响（特指意大利）                       | 仓室+大数据对轴                                              |
| PNAS    | 41   | 2021.1   | 瑞典高校                        | 影响因素分析 | 探究停课的影响                                         | 社会角色分类（教师、家长等）+统计分析                        |
| PNAS    | 42   | 2021.1   | 普林斯顿                        | 影响因素分析 | 探究非药物干预措施的影响                               | 仓室+大数据政策+拟合参数+对轴                                |
| PNAS    | 46   | 2020.7   | 西北大学                        | 影响因素分析 | 探究政策执行力弱条件下的防疫措施                       | 在SEIR应用时按照时间段进行分段动态参数，取最优化结果         |
| PNAS    | 47   | 2020.8   | 佐治亚大学                      | 影响因素分析 | 探究社交疏远的综合影响                                 | SEIR+动态政策+医疗需求、容量                                 |
| PNAS    | 48   | 2021.1   | 加州大学                        | 影响因素分析 | 探究老年打疫苗的影响                                   | 统计静态分析+SEIR+人口横向细分+疫苗                          |
| Science | 1    | 2020.8   | 瑞典高校                        | 影响因素分析 | 探究人口异质化对于社区传播原理的影响                   | 偏静态统计模型                                               |
| Science | 2    | 2021.3   | 帝国理工                        | 影响因素分析 | 探究哪个年龄结构组最影响疫情发展                       | 偏静态统计模型+物理数学模型                                  |
| Science | 5    | 2020.9   | 南安普顿大学                    | 影响因素分析 | 研究不再执行特定策略后的疫情发展                       | 仓室+政策仿真                                                |
| Science | 6    | 2020.6   | 于宏洁                          | 影响因素分析 | 探究武汉、上海社交接触模式的影响                       | 仓室+社交距离+年龄结构细分                                   |
| Science | 8    | 2021.3   | 普林斯顿                        | 影响因素分析 | 考虑抗病性、成本等综合条件下的第二针疫苗接种策略       | 仓室数量非常多，按照疫苗接种情况、是否生效、生效程度等细分   |
| Science | 16   | 2020.6   | 德国高校                        | 影响因素分析 | 通过疫情发展变化点探究政策影响                         | 仓室+细分政策数据                                            |
| Science | 18   | 2020.5   | 牛津大学                        | 影响因素分析 | 探究数字化追踪的作用机制与影响                         | 大数据估beta等参数，参数细化                                 |
| Science | 19   | 2020.8   | 港大                            | 影响因素分析 | 探究政策对于病毒繁殖时间？的影响                       | agent-based                                                  |
| Science | 21   | 2020.6   | 普林斯顿                        | 影响因素分析 | 气候对于疫情的影响                                     | 体现气候的多种指标与疫情发展建模结果对轴                     |
| Nature  | 8    | 2020     | 伦敦卫生和热带医学学院（LSHTM） | 影响分析     | 疫情对mobility/travel patern的影响                     | 时空轨迹统计模型，做好结果后在时间轴上与疫情发展对应         |
| Nature  | 18   | 2020.9   | 美国橡树岭国家实验室            | 影响分析     | 疫情对于机动车汽油需求的分析                           | 机器学习模型                                                 |
| PNAS    | 8    | 2020.11  | 德国高校                        | 影响分析     | 分析疫情造成流动性下降，在流动网络结构上的影响         | 输入疫情数据，多模式移动方式                                 |
| PNAS    | 10   | 2020.6   | 意大利高校                      | 影响分析     | 新冠隔离措施导致的经济和社会学影响                     | 基于传播网络建模疫情影响，随后与经济、社会数据进行统计分析   |
| PNAS    | 29   | 2020.3   | 加拿大、美国高校、医院          | 影响分析     | 预测新冠导致的医疗资源需求                             | 医疗资源需求+SEIR                                            |
| Nature  | 1    | 2020.1   | 普渡大学，WangShiyan            | 疫情建模     | 建模多种传播方式及每种受到的影响（政策）               | SEIR改，每种政策引入了传染率、时间差等参数                   |
| Nature  | 3    | 2021.2   | 剑桥，法、美若干高校            | 疫情建模     | 观测数据（确诊、报告等）不匹配（特别是死亡患者数）     | 死亡年龄比例+血清数据判断传染规模（医学原理+数据）           |
| Nature  | 4    | 2020.5   | 同济、华科，严丽                | 疫情建模     | 预测可能死亡的病例                                     | 用到了流行病学数据输入，输出可用于改进疫情预测模型           |
| Nature  | 6    | 2021.3   | 帝国理工、剑桥、爱丁堡等        | 疫情建模     | 建模一个新变种（B.1.1.7）                              | 分地区、分年龄，经典而全面的流行病学模型                     |
| Nature  | 13   | 2021     | 哈佛、多伦多、帝国理工          | 疫情建模     | 建模、分析国际性输入病例                               | 大量横向、纵向细化仓室类别                                   |
| Nature  | 19   | 2021     | 巴西                            | 疫情建模     | 考虑防控措施的情况下建模巴西圣保罗疫情                 | SUEIHCDR（SEIR变种，起的名字挺长）                           |
| Nature  | 20   | 2021.1   | 斯坦福、西北大学                | 疫情建模     | 考虑疫情传播的时空、病例不均衡性                       | SEIR+传播网络图                                              |
| Nature  | 22   | 2020     | 悉尼大学                        | 疫情建模     | 考虑防控措施的情况下建模澳大利亚疫情                   | 大数据估Rt+时空横向细分                                      |
| Nature  | 23   | 2021     | 普林斯顿                        | 疫情建模     | 考虑干预措施实施成本情况下的最佳策略                   | 疫情方面为SEIR，辅以实施成本、可行性建模                     |
| Nature  | 24   | 2021     | 香港大学                        | 疫情建模     | 利用实时传感器获取人口流动数据，建模疫情               | SEIR改，抹除了感染-确诊报告的时间差，达到实时预测            |
| Nature  | 25   | 2020.8   | 同济、华科                      | 疫情建模     | 复盘武汉爆发的疫情                                     | SAHPIRE，和wuhan-mobility那个模型较像，加入了未确诊、无症状、症状前等仓室 |
| Nature  | 27   | 2020.9   | 悉尼大学等澳洲高校              | 疫情建模     | 利用agent-based+病毒基因测序建立传播路径，建模疫情     | 智能体模型                                                   |
| Nature  | 28   | 2020     | 帝国理工、牛津                  | 疫情建模     | 建立州粒度的综合模型                                   | SEIR+政策改beta+流动性                                       |
| PNAS    | 2    | 2020.7   | 维也纳高校与医院                | 疫情建模     | 为何确诊病例呈近乎线性增长                             | 基于了传播网络的阈值模型                                     |
| PNAS    | 3    | 2020.8   | 加拿大高校（McMaster）          | 疫情建模     | 14-17世纪英国流行病的增长趋势（与新冠无关）            | 先R0后仓室                                                   |
| PNAS    | 4    | 2020.11  | 佐治亚理工                      | 疫情建模     | 解决观测发病率、死亡率不匹配的问题                     | mobility矩阵+PCA                                             |
| PNAS    | 7    | 2020.8   | 埃默里、普林斯顿等              | 疫情建模     | 理解、建模传播异质性                                   | 时空大数据+agent-based                                       |
| PNAS    | 9    | 2021.3   | 加州大学                        | 疫情建模     | 综合考虑规模、成本、死亡时的疫苗策略                   | 多模型融合（其中单模型为仓室）                               |
| PNAS    | 11   | 2020.7   | 圣母大学                        | 疫情建模     | 估算未观测患者数量的模型                               | 随机模型+仓室模型                                            |
| PNAS    | 18   | 2020.6   | 清华、中科院、卫健委，          | 疫情建模     | 建模综合防控策略组合及组合推荐（这个团队规模也较大）   | 人口细分、气候、移动、政策                                   |
| PNAS    | 26   | 2020.8   | 哈佛、MIT                       | 疫情建模     | 探究针对不同家庭、年龄类型的不同最优政策               | 年龄+家庭结构+agent-based                                    |
| PNAS    | 27   | 2020.1   | 加州大学                        | 疫情建模     | 探究维持经济活动情况下的疫情发展                       | 传播网络图+物理模型+agent-based                              |
| PNAS    | 28   | 2021.3   | 丹麦高校                        | 疫情建模     | 探究超级传播者的作用机制与原理                         | 年龄结构+agent-based，同时引入超级传播个体                   |
| PNAS    | 30   | 2007     | 美国医疗研究机构                | 疫情建模     | 建模、复盘1918流感（与新冠无关）                       | 统计学模型                                                   |
| PNAS    | 31   | 2021.1   | 芝加哥大学                      | 疫情建模     | 通过可观测数据计算、推断无症状感染者等隐性数据         | SEIR改+统计学指标                                            |
| PNAS    | 33   | 2021.1   | 达特茅斯大学                    | 疫情建模     | 研究零售店内的疫情传播                                 | 物理模型仿真+agent-based                                     |
| PNAS    | 36   | 2020.12  | 丹麦高校                        | 疫情建模     | 更准确的预测死亡率（丹麦限定）                         | SEIR+年龄性别+丹麦历史流行病数据                             |
| PNAS    | 39   | 2020.8   | 加州大学                        | 疫情建模     | 考虑特定设施场所与空间网络上的疫情传播建模             | 空间网络图+POI分析+agent-based                               |
| PNAS    | 43   | 2020.6   | 加拿大高校                      | 疫情建模     | 探究隐性患病人和隐性传播方式                           | agent-based+年龄细分                                         |
| PNAS    | 44   | 2020.1   | 弗罗里达大学                    | 疫情建模     | 探究多群体的政策影响交互作用                           | 多个群体，群体内部为仓室模型，政策“此起彼伏”                 |
| Science | 3    | 2020.5   | 田怀玉                          | 疫情建模     | 建模中国爆发疫情的过程                                 | 仓室+静态统计+政策大数据                                     |
| Science | 4    | 2021.4   | 法国研究机构                    | 疫情建模     | 探究数字化追踪的作用机制与影响                         | agent-based                                                  |
| Science | 7    | 2020.5   | 德国高校                        | 疫情建模     | 探究中国病例增长不再呈指数的原因                       | 仓室+政策大数据                                              |
| Science | 10   | 2021.2   | 爱丁堡大学                      | 疫情建模     | 通过病例+病原基因组数据建立流行病学谱系                | 偏静态统计模型，涉及到基因比对相关细节技术                   |
| Science | 11   | 2021.4   | 帝国理工、剑桥、爱丁堡等        | 疫情建模     | 建模一个新变种（B.1.1.7）                              | 分地区、分年龄，经典而全面的流行病学模型                     |
| Science | 12   | 2020.6   | 法国研究机构、高校              | 疫情建模     | 建模法国疫情（考虑了重症轻症区别）                     | 年龄结构+重症轻症+性别+政策+仓室模型                         |
| Science | 14   | 2020.9   | 巴西高校、研究机构              | 疫情建模     | 建模巴西疫情（引入了病毒不同变种的进化轨迹）           | 政策+流行+仓室模型，基于病毒进化变体构建传播路径             |
| Science | 15   | 2020.11  | 普林斯顿                        | 疫情建模     | 探究群体免疫的条件与效果                               | 仓室+疫苗效果                                                |
| Science | 17   | 2020.5   | 哈佛大学                        | 疫情建模     | 考虑季节、变异情况下的长期疫情规模预测                 | 大数据估Rt+核酸、血清相关基因数据                            |
| Science | 20   | 2020.5   | 哥大等英美高校                  | 疫情建模     | 估算确诊患者实际感染时间分布                           | 基于传播网络的agent-based                                    |
| Nature  | 2    | 2020     | 鲁汶大学、爱丁堡大学、UCLA等    | 输入数据分析 | 提高追踪患者的精度                                     | 贝叶斯推断 apply in 时空数据                                 |
| Nature  | 29   | 2020     | 伯克利                          | 输入数据分析 | 分析确诊病例数据的不可信度                             | 半贝叶斯概率分析模型                                         |
| PNAS    | 5    | 2020.12  | 印第安纳大学                    | 输入数据分析 | 估算流行病实际传播范围                                 | 随机取样+贝叶斯模型                                          |
| PNAS    | 17   | 2020.12  | 普林斯顿                        | 输入数据分析 | 解决确诊序列分隔不当导致的R0、Rt估计错误               | 偏静态统计学模型                                             |
| Science | 13   | 2020.8   | 北大                            | 输入数据分析 | 精确的估计病毒潜伏期                                   | 偏统计计算，算法类似agent-based（个体建模）                  |
| Nature  | 30   | 2021.2   | 荷兰、英国高校                  | 其他         | 分析现有建模工具链的不可信度                           | 这个类似于软件测试了？可能在综述中有帮助，支撑更全面（很多人都是用这类工具建立SEIR的） |