---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>


高倩，1997年10月生，湖北人。2015.9-2019.6于武汉理工大学交通学院就读交通工程专业，排名1/65，2019年9月通过保送研究生至同济大学交通运输工程学院综合交通信息与控制工程系，直接攻读博士研究生，并于2023年10月受国家留学基金委资助前往加拿大多伦多大学联培。

博士期间深耕道路交通基础设施数字化运维领域，针对“路面服役性能多维度解析”的科学问题以及“数据驱动的养护决策”的工程问题展开研究，至今本人已在《Automation in Construction》（JCR Engineering排名第一）、《IEEE Transactions on Intelligent Transportation Systems》（JCR Engineering排名第三）、《中国公路学报》（公路交通领域中文期刊TOP1）等领域内顶级期刊发表论文共**12篇**，其中**5篇1作**（SCI论文8篇，中文顶刊论文1篇，国际会议论文2篇)，申请国际专利PCT**2项**，国家发明专利**14项（授权3项）**。

作为学生负责人先后参与国家重点专项、面上项目、上海市科委研究等纵向项目，负责项目从申报、推进到结题全流程的材料撰写、对接汇报等工作，拥有丰富的项目组织与管理经验。在科学研究的同时，同样注重科研成果的落地应用，参与研发的路面多维高频检测与智能养护技术在全国10余省市超20万公里道路上推广使用，社会经济效益明显，获得中国公路学会科技进步**一等奖**、中国交通运输协会科技进步**一等奖**、上海市公路学会科学技术**二等奖**。此外斩获众多创新大赛奖项，获中国国际“互联网+”大学生创新创业大赛**全国银奖**、高等院校发明选拔赛**金奖**、雄安数字城市大赛**一等奖**、“上港杯”长三角智能交通创新技术应用大赛**二等奖**、中国研究生智慧城市技术与创意设计大赛**二等奖**等国家级奖项**4项**，省部级奖项**10项**。

**研究方向：道路基础设施数字化运维，路面性能高频多维时空分析，数据驱动的养护决策**


# 📖 Educations
- *2019.09 - 2025.06 (now)*，同济大学，交通运输工程，博士（直接攻博）.
- *2023.10 - 2024.10*，多伦多大学，基础设施与建筑信息系统中心，CSC联合培养博士生.
- *2015.09 - 2019.06*，武汉理工大学，交通工程，学士. 


# 💻 Projects
1. **道路基础设施性能高频多维数字化运维技术研发（国家自然科学基金面上项目）**                                                  2019.09-至今
- **职责**：**项目骨干**，**（1）感知技术研发**：基于目标检测、雷达信号处理、关联分析等技术，研发路面病害识别、路内空洞探伤、路表LiDAR扫描的感知算法，实现设施状况的多维检测与评估，在路面、路内、路表检测3个方向上均发表了SCI论文；**（2）多维性能分析**：综合图像、振动、雷达、历史记录等多维数据，以数据挖掘分析为核心，解析数据蕴含的设施状态信息，交叉解释设施病害的实际致因，实现海量异构监检测数据由“可视化展示”到“可计算分析”，支持数据驱动的科学决策制定；**（3）落地应用实施**：参与该技术在港珠澳大桥、雄安新区、大兴机场高速、杭州亚运会赛道等地的应用，与行业上下游企业对接，负责装备的应用测试、效果后评估，以及项目从申报到结题的全流程材料汇报、对接推进等工作。
- **成果**：发表SCI论文7篇（3篇1作），撰写专著《道路设施性能高频多维感知与数字化管理技术》，获中国交通运输协会科技进步一等奖、中国国际“互联网+”大学生创新创业大赛全国银奖、数字城市大赛雄安站智慧城市专题赛一等奖、高等院校发明选拔赛金奖等。
2. **基于细时空粒度数据的路面性能时空追溯分析及养护决策研究（博士论文）**                                                      2022.10-至今
- **职责**：**项目负责人**，**（1）时空连续数据集**：基于累积的一千多万条高频巡检数据，建立“GPS-方位角-环境特征”的三级匹配框架，实现路面病害的时空连续追溯，形成路网性能时空连续数据集；**（2）性能劣化预测**：利用因果推理分析路面性能在多致因影响下的时滞演化，进一步利用贝叶斯网络和LSTM构建路面病害级性能预测模型；**（3）养护决策支持**：采用地理探测器分析城市路面性能空间分布的差异及其成因，划分得到具有不同养护需求的差异化养护分区，以优化养护资源配置。
- **成果**：发表SCI论文5篇（2篇1作），Nature子刊Scientific Data在投，授权国家发明专利2项，申请PCT国际专利2项。
3. **上海市徐汇区市政管养数字化转型升级（产学研合作项目）**                                                                   2020.11-至今
- **职责**：**项目负责人**，**（1）装备应用**：将产学研合作研发的轻量化智能巡检设备、探地雷达等装备在全区270余公里道路上进行试点应用，负责装备的调试及使用，牵头装备测试通过国家计量站校准Ⅰ级标准认证；**（2）数据分析**：基于MySQL、Python等技术对采集数据进行处理，融合多维检测分析道路状况，联合解释病害诱因，负责出具每周巡检结果与后评估报告，为大中修方案和科学管养决策制定提供支持；**（3）项目管理**：同徐汇市政中心各部门、合作企业对接，负责项目推进、对接、软课题申请等事宜，结合技术与业务需求，厘定技术发展与业务拓展的方向，推动创新的同时确保落地可行性。
- **成果**：牵头编制的《2022年上海市道路行驶质量报告》作为成果，上报到上海路政局及市长办公室，项目获上海市公路学会科学技术二等奖。
4. **交通基础设施检测维护关键技术、算法和验证平台研究（教育部-中国移动科研基金研发项目）**                                        2019.07-2021.09
- **职责**：**子课题骨干**，**（1）项目推进**：负责项目开展过程中，中移动企业与高校之间设备、算法、数据等需求的对接，参与项目从开题、推进、到结题的全过程事务，熟悉项目全流程；**（2）平台设计与装备测试**：负责中移动基于5G通讯的智能化路面质量数据管理平台的逻辑框架与平台界面设计，以及轻量化路面行驶质量检测设备的测试、维修与应用；**（3）标准撰写**：负责《基于5G通讯的基础设施智能化检测装备测试标准指南》撰写。
- **成果**：平台设计报告《基于5G通讯的智能化检测与预测性维护应用技术研发测试平台设计报告》，标准指南《基于5G通讯的基础设施智能化检测装备测试标准指南》。
5. **港珠澳大桥智能化运维技术集成应用（国家重点研发计划项目）**                                                                2019.12-2022.11
- **职责**：**项目骨干**，**（1）装备研发**：负责分析车载信息感知装备和显示终端的需求、功能定位、系统架构，进行试制方案的比选和实地测试，支撑融合5G+北斗的车载智慧终端研发，赋能港珠澳大桥营运车辆（穿梭巴士）与桥隧运维；**（2）国标撰写**：面向港珠澳大桥桥岛隧公路的全生命周期智能运维工作，负责撰写了公路基础设施智能巡查技术规范和长封闭隧道内定位服务标准的初稿。
- **成果**：国家标准《跨海集群设施公路数字化智能巡查技术规范》，《跨海集群设施公路数字化基于北斗的长封闭隧道内定位服务》。
6. **金鼎天地超大地下空间交通组织规划项目（横向项目）**                                                                        2020.07-2022.01
- **职责**：**子课题负责人**，**（1）标准研究**：带领3名硕士开展上海市金鼎天地九宫格超大停车场库设计与智能化标准研究，从建造标准、信息发布、智能化规范、交通组织、管理决策等方面规范超大型停车场的建设、管理、运营和智慧化全流程；**（2）可行性研究**：面向园区“最后一公里”自动驾驶的场景需求，设计满足自动驾驶功能的超大型地下车库通道的专用道及附属设施，分析金鼎超导社区自动驾驶落地应用可行性，服务园区地下场景的自动驾驶落地。
- **成果**：牵头编制《金鼎天地停车场库设计建造及其智能化标准》、《金鼎超导社区自动驾驶多维落地应用可行性研究》，支撑了后续项目的持续展开。


# 📝 Publications  
## 📃 Papers
1. **高倩**, 杜豫川, 刘成龙, 李亦舜, 吴荻非, 李峰. [城市路面性能分布空间异质性解析及差异化养护分区研究](https://kns.cnki.net/kcms2/article/abstract?v=8pq0kR8SZyUqt9TxV4gegfdfKVntxh-s7RwYiYMg_7TzQ4rEWKriG8VEAq9HULjj2eYMqgGuv8mdzs_QvL7zsrWh8QiEn3l8Hf_rY9yhwo4nAhStnB5hjdDTdNEm3thJEbnEY_MTT2AnysrKVAdNUz65mPuDGJ7bzSv9A-GvFimHUItD_Nsa3IZ4JZNxwT9ZxCY_NfNk3h7so-982Zz9rxt-Js2JsHzoJcglp-ssVqsLzYoPnDg9HKpLxiH4ERIiEdGRBSqUJL5-PH1f1Y7eiJadl5gigpSIc4DNYP7BzNXvjxlcNmJkKiUpf1iKhMjxeSCOCEVlLUbdpbuJuZryhA==&uniplatform=NZKPT&language=CHS)[J]. _中国公路学报_, 2024. **（中文论文，公路领域中文期刊TOP1）**
2. **Qian Gao**, Chenglong Liu, Yishun Li, Yuchuan Du, Guanghua Yue, and Bing Liu. ["Mining co-occurrence patterns among deep road distresses using association rule analysis."](https://ascelibrary.org/doi/10.1061/JPEODX.0000328) _Journal of Transportation Engineering, Part B: Pavements_ 148, no. 1 (2022): 04021078.  **SCI论文, IF: 2.1, Q3**
3. **Qian Gao**, Lei Fan, Siyu Wei, Yishun Li, Yuchuan Du, and Chenglong Liu. ["Differences evaluation of pavement roughness distribution based on light detection and ranging data."](https://ascelibrary.org/doi/10.1061/JPEODX.0000328) _Applied Sciences_ 13, no. 14 (2023): 8080.  **（SCI论文, IF: 2.7, Q1）**
4. **Qian Gao**, Xinhua Yu , Yuchuan Du, Chenglong Liu, Difei Wu, Yishun Li, Xiaoming Zhang. "Digital operation and maintenance system of highway infrastructure." _29th ITS World Congress_. (2023)  **（公路交通领域顶级国际会议）**
5. **Qian Gao**, Shuyang Zhang, Guojun Chen, and Yuchuan Du. ["Two-way cooperative priority control of bus transit with stop capacity constraint."](https://www.mdpi.com/2071-1050/12/4/1405) _Sustainability_ 12, no. 4 (2020): 1405.  **（SCI论文, IF: 3.6, Q2）**
6. Yishun Li, Chenglong Liu, **Qian Gao**, Difei Wu, Feng Li, and Yuchuan Du. ["ConTrack Distress Dataset: A Continuous Observation for Pavement Deterioration Spatio-Temporal Analysis."](https://ieeexplore.ieee.org/document/9899382) _IEEE Transactions on Intelligent Transportation Systems_ 23, no. 12 (2022): 25004-25017.  **（SCI论文, IF: 8.3, Q1）**
7. Yishun Li, Chenglong Liu, Guanghua Yue, **Qian Gao**, and Yuchuan Du. ["Deep learning-based pavement subsurface distress detection via ground penetrating radar data."](https://www.sciencedirect.com/science/article/pii/S0926580522003892) _Automation in Construction_ 142 (2022): 104516.  **（SCI论文, IF: 10.6, Q1）**
8. Guanghua Yue, Yuchuan Du, Chenglong Liu, Shili Guo, Yishun Li, and **Qian Gao**. ["Road subsurface distress recognition method using multiattribute feature fusion with ground penetrating radar."](https://www.tandfonline.com/doi/abs/10.1080/10298436.2022.2037591) _International Journal of Pavement Engineering_ 24, no. 2 (2023): 2037591.  **（SCI论文, IF: 3.8, Q2）**
9. Guanghua Yue, Chenglong Liu, Yishun Li, Yuchuan Du, and **Qian Gao**. ["Automatic Detection of Road Subsurface Distress via Curriculum Learning: Learn Like an Expert."](https://journals.sagepub.com/doi/abs/10.1177/03611981241248164) _Transportation Research Record_ (2024): 03611981241248164.  **（SCI论文, IF: 1.9, Q3）**
10. Wenyuan Cai, Chenglong Liu, **Qian Gao**, Yishun Li, Yuchuan Du. "Scene-adaptive pavement maintenance optimization model: a reinforcement learning approach from expert feedback. _103nd TRB Annual Meeting_. (2024).  **（公路交通领域顶级国际会议）**
11. Haobing Liu, Shuyang Zhang, Guojun Chen, and **Qian Gao**. ["Observed Characteristics and Modeled Emissions of Transit Buses on Ramps."](https://journals.sagepub.com/doi/abs/10.1177/03611981241248164) _Sustainability_ 12, no. 7 (2020): 2770.  **（SCI论文, IF: 3.6, Q2）**
12. Yuchuan Du, Han Wang, **Qian Gao**, Ning Pan, Cong Zhao, and Chenglong Liu. ["Resilience concepts in integrated urban transport: a comprehensive review on multi-mode framework."](https://www.emerald.com/insight/content/doi/10.1108/SRT-06-2022-0013/full/html) _Smart and resilient transportation_ 4, no. 2 (2022): 105-133.

## 📃 Patents
**国际PCT专利：**
- 一种基于高频巡检数据的道路性能更新与分析方法. PCT/CN2023/096970.
- 一种路面损伤匹配与连续跟踪方法. PCT/CN2023/096969.

**国家发明专利：**
- 一种基于关联规则分析的道路深层病害预警方法. ZL202110215728.6.
- 一种考虑碳排放的路网级全生命养护优化方法. ZL202210139768.1.
- 一种基于超车行为特征的疲劳驾驶监测方法. ZL201810481127.8.
- 一种面向气象灾害的路网道路基础设施韧性评价方法. CN202310533463.3.
- 一种公路桥梁灾后的安全韧性评估方法. CN202310539432.9.
- 基于车载面阵结构光的道路病害体积检测方法. CN202210937371.7.
- 一种交通基础设施裂缝图像数据增广方法、装置及介质. CN202310778335.5.
- 一种基于城市路面性能空间异质性的道路养护分区方法. CN202410287302.5.
- 一种面向路面病害检测的道路巡查车辆路径规划方法. CN202410287300.6.
- 一种多无人机系统城市不规则区域交通巡查的方法. CN202410557261.7.
- 一种探地雷达数据异常区域自动识别方法. CN202410728557.0.
- 一种基于变化检测的城市道路探地雷达规模普查方法. CN202410728441.7.

## 📃 Book
- 专著：《道路设施性能高频多维感知与数字化管理技术》. 北京：人民交通出版社, 2024.


# 🏆 Honors and Awards
## 🏅 荣誉表彰
- *2024.11*，中国公路学会科技进步**一等奖**
- *2024.06*， 同济大学卓越研究生**导学团队标兵**
- *2024.02*， 2023年度中国交通运输协会科技进步**一等奖**
- *2023.10*， 同济大学**优秀博士生奖学金**
- *2023.02*， 2021年上海市公路学会科学技术**二等奖**
- *2017.09*， 武汉理工大学校级**二等奖学金**
- *2017.09*， 武汉理工大学**校三好学生**
- *2016.09*， 武汉理工大学**校优秀共青团员**
- *2016.09*， 武汉理工大学**国家励志奖学金**
- *2016.09*， 武汉理工大学**校三好学生标兵**

## 🏅 竞赛奖项
- *2024.11*， “上港杯”长三角智能交通创新技术应用大赛**二等奖**
- *2024.11*， 盐城数据开放创新应用大赛**二等奖**
- *2024.06*， 高等院校发明选拔赛**金奖**
- *2024.04*， 江苏大数据开发与应用大赛（SEED）**数据创新应用优秀成果**
- *2023.12*， 江苏省“大运河杯”数据开发应用创新大赛**二等奖**
- *2023.10*， 雄安数字城市大赛**一等奖**
- *2023.09*， “姑苏杯”长三角智能交通创新技术应用大赛**三等奖**
- *2023.03*， 中国研究生智慧城市技术与创意设计大赛**二等奖**
- *2021.10*， 中国国际“互联网+”大学生创新创业大赛**全国银奖**
- *2021.12*， “华为杯”第十八届中国研究生数学建模竞赛**二等奖**
- *2020.12*， “华为杯”第十七届中国研究生数学建模竞赛**二等奖**
- *2019.12*， “华为杯”第十六届中国研究生数学建模竞赛**二等奖**
- *2016.05*， 第十二届全国大学生交通科技大赛校**一等奖**

