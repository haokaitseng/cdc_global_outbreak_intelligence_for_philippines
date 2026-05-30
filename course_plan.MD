# Course title: AI-enabled Intelligent Transformation of International Outbreak Monitoring
# Speaker: Hao-Kai Tseng

# Rules: 
- The presentation deck should be written in English, where (Traditional Mandarin) can be supplement when more clear.
- Fonts using Noto series
- Color: 
Sage 主色 as main tone
#739A6D
Slate Blue
#587A9D
Mustard
#C8A041
Teal
#49888D
Bronze
#916E46
Plum
#955F71
- deck desgin style: simple, morden, white back ground in general. You may use color background as a whole to emphasize 反差. ; Do not say too much words for narratives.
- when I use double "##" as a page of slide
- presetation time: 45 minutes.
- audience: officers from Ministry of Health, Philippines (can only read Eng)
------------------------------------------------------
# Part 0: About the Speaker
Hao-Kai Tseng is a contract assistant at the Taiwan CDC's Epidemic Intelligence Center,
leading the international outbreak monitoring team. With seven years in public health data
science, he previously supported sustainable immunisation programmes at Gavi, the
Vaccine Alliance. For more on his work, visit his portfolio at haokaitseng.github.io.


# Part 1: Taiwan

## Lesson's learnt from SARS
Need to mention SARS outbreak as a opening and reminder that a nation's globaloutbreak monitoring should not rely only on others, need also self monitoring. Reference : 17年前的歷史瘟疫：當年 SARS 疫情爆發時，發生了什麼事？天下雜誌 (https://www.cw.com.tw/article/5099181)

Qoute the words below in english
> 目前可追溯並證實的初始病發時間及地點可能是2002年11月的中國廣東省佛山，之後傳播至廣東其他地區，並透過香港的機場蔓延到台灣、越南等境外，最終造成約30個國家淪陷、8,096名病例、774人死亡；台灣346名患者，73人死亡。
> 而飽受爭議的是，疑似病例首次在2002年11月發生，然而世界衛生組織（World Health Organization, WHO）直到隔年2月11日才收到通報，此時已有305名病例。同月下旬，某位染病的患者抵達香港九龍酒店，將病毒傳染給酒店員工；病發後因醫院未能及時發覺，引發院內感染；香港就此淪陷，而病毒也透過機場飛往全球。

## Milestones
use the page of  Resource/20250910 Taiwan CDC's approach to international outbreak monitoring.pdf - a call with Singapore.pdf as reference . Use Claude to create a similar and more pretty version, where the date should be extanded to year 2026.

## The process of international epidemic intelligence

use the page 4 from the resource/20250910 Taiwan CDC's approach to international outbreak monitoring.pdf. Claude may retweak but need to retain every word and structure.

## Workflow -1
reference the page 5 of "resource/20250910 Taiwan CDC's approach to international outbreak monitoring.pdf", into two pages. restructure the sources, data processing, and disseminations as the main point.

add a secontion different method of crawler using Python and popular packages, as a table 

use "OSINT" as a big word in background, refelcting open source intelligence

## Workflow -2
IEN in morning meetings should be revised as :
- Wed: airborne & aerosol ; 
- Thus: Food & water borne
- Fri: contact transmitted
you may draw each transmission route using graphic icons


also translate in eng below : 
> 菲律賓國家首都區奎松市今年截至 4/16 報告 143 確診病例，其中 1 例死亡。76%病患為 10 歲以下兒童(109 例)，且其中 23 例為未達接種疫苗年齡嬰兒，當局已啟動相關防治及疫苗接種措施。該國今年第一季累計報告 1,627 例麻疹/德國麻疹確定病例，較去年同期增加 45%。
this is a IEN on 2026/4/21 from Outbreak News Today
visually presented as a story book style

## Daily job in numbers (suggest better title)
please use big numbers styles to present below: 

- 國際重要疫情資訊(IEN)2009-2025年累計公布7萬3,344則國家疾病資訊，平均每年公布4,314則，相當於平均每週74則(country-disease reported every week)

- 159 countries/territories covered annually

- 國際重要疫情資訊每年從來源資訊蒐集至公布的平均時間差為3天 (3 days source-to-publication interval)

- 481 unique sources used annually (Top 13 Sources: WHO, outbreak news today, PROMED, OIE, US CDC, CIDRAP, Hong Kong CHP, Xinhuanet, GPEI, ECDC, PAHO, Reuters, Singapore MoH).

## Course activity! (refine title like now it is your editorial desk? )
Asking participant's opinion, which diseases will they pick. I will provide some options of diseases and others can add their options and vote in the slido producet connected in powerpoint.

## IEN’s focus has been closely linked to domestic & global outbreaks
Only use the Resource/disease_proportion_annual_trend.png
前15名累計占整體公布則數82%

Also compare to WHO DON : simplify below in eng
前述15個疾病中，有10個（占67%）同樣列於WHO 2009–2025年的DON前15名疾病，顯示我國國際疫情監測焦點符合與國際同步之原則；另5個DON關注的疾病（中東呼吸症候群冠狀病毒感染症、黃熱病、馬堡病毒出血熱、拉薩熱、克里米雅-剛果出血熱），除馬堡病毒出血熱以外，其餘4項疾病仍在國際重要疫情資訊前28名蒐集範圍，並無遺漏蒐集的情形。

## A risk-based intelligent focus (refine title)
Only use the Resource/global.png
also list below country names:
國際重要疫情資訊常見的前15名國家（地區）依序為美國、中國、香港、日本、英國、印度、巴西、韓國、德國、法國、越南、奈及利亞、菲律賓、新加坡及泰國

## Comparing with WHO DON
Reference: The World Health Organization’s Disease Outbreak News: A retrospective database
Colin J. Carlson,Matthew R. Boyce,Margaret Dunne,Ellie Graeden,Jessica Lin,Yasser Omar Abdellatif,Max A. Palys,Munir Pavez,Alexandra L. Phelan,Rebecca Katz 
Published: January 25, 2023 https://doi.org/10.1371/journal.pgph.0001083

use resource/journal.pgph.0001083.t001

translate below in eng: 台灣排名前15個疾病中，有10個（占67%）同樣列於WHO 2009–2025年的DON前
15名疾病，顯示我國國際疫情監測焦點符合與國際同步之原則

## Philippines in spot light
rank the number of diseases in phlippine that we report mostly in IEN. 
I will provide the deatil.

## Early alert & enhanced monitoring during WHO PHEICs
Directly use the resource/pheic_timeline_plot.png

# Travel health notices -1 
copy the page ten of the "resource/20250910 Taiwan CDC's approach to international outbreak monitoring.pdf". you may refine the visuals.
note that this time add "Nipah" to the left hand list, so that the nubmer of diseases in focus should be 20.
You must include the exact pic of resource/travel_health_alert.png, no additional changes.

# Travel health notices -2 
Use resource/travel_alert_severity_disease_stacked.png 

# AI-driven intelligence pipeline
 use resource/acer_screenshot.png. you may consider the arrangement like page 11 of resource/20250910 Taiwan CDC's approach to international outbreak monitoring.pdf.

------------------------------------------------------
# Part 2: Global AI advances
In part 2, you (Claude) may mostly use the information from LLM_AI_Surveillance_Scoping_Analysis_v4_2026.md or search online if I don't provide too much hint


## Various Functions of AI for Infectious-Disease Surveillance
| Function | Examples |
|---|---|
| Early warning | NLP of news sources; unsupervised ML of social media to detect unknown infections |
| Pathogen classification | CNN for reading antibiograms; CNN to automate malaria microscopy and diagnosis |
| Risk assessment | Reinforcement learning for COVID-19 testing targeting; random forest/XGBoost for syndromic surveillance COVID-19 risk prediction |
| Source identification | Automated data mining of EMR to uncover transmission routes; supervised ML + digital signal processing for genomic tracing |
| Hotspot detection | Neural computing using hospital waiting room sound for influenza spikes; ANN for TB spatial clustering |
| Tracking & forecasting | Real-time model stacking for seasonal influenza forecasts; ML combining multiple data sources for COVID-19 monitoring |

REF: Advances in Artificial Intelligence for Infectious-Disease Surveillance
Authors: John S. Brownstein, Ph.D., Benjamin Rader, M.P.H. https://orcid.org/0000-0002-6095-0193, Christina M. Astley, M.D., Sc.D., and Huaiyu Tian, Ph.D.Author Info & Affiliations Published April 26, 2023 N Engl J Med 2023;388:1597-1607 DOI: 10.1056/NEJMra2119215

## The land scape -1 
Today’s bio-surveillance landscape is built on established intelligence systems like below: make a table for overview and comparison

| System | Access / Type | Core Focus & Technology |
| :--- | :--- | :--- |
| **WHO EIS** | Restricted / Official | Secure IHR portal for sensitive, official country alerts. |
| **WHO DON** | Public / Official | Verified, authoritative global public outbreak notices. |
| **WHO Regional** | Public / Official | Routine regional bulletins. |
| **ECDC / EuroSurv**| Public / Regional | Peer-reviewed science paired with official EU tracking. |
| **WOAH** | Public / Official | Animal health and zoonotic spillover. |
| **GPHIN** | Restricted / Gov | Canadian EBS pioneer; automated multi-lingual email alerts. |
| **HealthMap** | Public / Automated | 2006 pioneer; automated web-scraping and live mapping. |
| **ProMED** | Paid / Expert | Crowdsourced alerts verified by experts + AI summaries. |
| **BlueDot** | Paid / Enterprise | Recommended with 3 risk concern levels and flight data. |
| **CIDRAP** | Public / Academic | High-quality news and policy. |
| **EPIWATCH** | Paid / Enterprise | 50+ language AI OSINT for early outbreak detection. |
| **BEACON** | Public / Academic | Founded in 2025. Highly recommended. Custom AI agents & LLMs. Comparative analysis is a plus. |
| **Outbreak News Today** | Public / Media | Active independent news hub. |
| **Avian Flu Diary**| Public / Expert Blog | Rapid expert analysis of influenza and avian threat data. |

## WHO EIS
Building on this base, a remarkable technological leap has emerged. The WHO EIOS 2.0 now utilizes AI-powered tools for automated analysis, 

## BEACON
while BEACON leverages its PandemIQ Llama model for informal event-based surveillance. 

- Our disease experts use PandemIQ Llama to extract key information and conduct preliminary assessment of incoming biothreat signals from our partner HealthMap, alongside manual submissions 
- BEACON editorial staff then choose which signals to report on and use PandemIQ Llama to generate an initial draft report for us to edit, expand on and provide additional contextual information to before publishing
- By training the LLM on pandemic-specific text, we've created a domain-adapted foundation model specifically designed for high-stakes health intelligence. 
- PandemIQ Llama was built to help close that gap, trained on 5.7 billion tokens (or roughly 4.3 billion words) of authoritative epidemiological knowledge spanning 31 languages and 16 priority pathogens
Reference: https://beaconbio.org/en/blog/post/?slug=pandemiq-llama-llm

use reference/large_BEACON_workflow_6ab9503d42.png


## Knowledge graph for WHO DON

Reference: Consoli, S., Coletti, P., Markov, P.V. et al. An epidemiological knowledge graph extracted from the World Health Organization’s Disease Outbreak News. Sci Data 12, 970 (2025). https://doi.org/10.1038/s41597-025-05276-2

Claude make a short summary in two sentence for this paper

- Use resource/41597_2025_5276_Fig2_HTML
- Use resource/41597_2025_5276_Fig6_HTML


- Entity linking74, i.e. grounding the facts in domain ontologies, is a technique used to reduce this phenomenon and an essential feature of knowledge graphs. In our case, the data resources of eKG have been linked to biomedical ontologies using the NCBO BioPortal (https://bioportal.bioontology.org/), and to geo-locations using GeoNames (https://www.geonames.org/), ensuring consistent and accurate entity representation across datasets.


## Two New Global Platforms 
Announced at WEF Annual Meeting 2026 as global public goods:

| Platform | Function |
|----------|----------|
| **Pandemic Preparedness Engine (PPX)** | End-to-end R&D platform integrating genomic surveillance + epidemiological modeling + viral evolution + antigen design via agentic AI |
| **Global Pathogen Analysis Platform (GPAP)** | World's first globally accessible, AI-powered platform turning pathogen data (human, animal, plant, environmental — **One Health**) into standardized, actionable intelligence |


## ARIES Agentic Framework Formalized (better title ?)

The ARIES framework received expanded formalization in early 2026:

- Components: Flows, Crews, Agents, Process, Tasks
- Configurable: Memory, LLMs, Knowledge, Reasoning, Training, Tools
- Inspired by Sara De Luca's zero-shot LLM classification (90.2% precision) on COVID-19 (2020–2022) and Mpox (Europe)
- **Goal**: Decision Intelligence System reducing hallucination, retrieving updated information only, task-specific

**Reference**: Wattamwar A, Akwafuo S. ARIES: A Scalable Multi-Agent Orchestration Framework. *arXiv* 2601.01831, January 2026.  https://arxiv.org/pdf/2601.01831

> 💭 **[KAI]:** manager agent + Sepcialized agents (A layer of sub-agents, each assigned a domain-specific
persona and toolset: Senior Medical Scientist, CDC Data Analyst, WHOIntelligence Officer ). a Hierarchical Multi-Agent Architecture is not only capable of replicating the investigative workflows of a human epidemiologist but can do so with a level of speed and cross-source verification that exceeds manual capabilities. 
Future roadmap: MCP, Agentic Self-Correction, Integration of Unconventional Data Streams, Weeky Epidemiological Records


## AI Agents for Respiratory Diseases — Quadripartite Framework (2026 peer-reviewed)

The Yang et al. 2026 paper in JMIR formalizes the **quadripartite framework**:

1. Surveillance
2. Risk evaluation
3. Early warning
4. **Decision support and intervention optimization through AI agents** ← NEW PILLAR

**Application example**: Given an emerging RSV outbreak in a region with limited ICU capacity, AI agents synthesize epidemiological forecasts, resource availability, and intervention effectiveness data to recommend optimal response strategies.

**Reference**: Yang L, Shan L, Cao X, Cui J, Tong M, Niu Y, Zhang T. AI Agents and Epidemic Intelligence on Respiratory Infectious Diseases: Toward a Conceptual Framework Integrating Decision Support. *J Med Internet Res.* 2026;28:e86936. DOI: 10.2196/86936
**URL**: https://www.jmir.org/2026/1/e86936

> 💭 **[KAI]:** relevant. universal epidemic intelligence model. only single country implementation
Furthermore, hierarchical multi-agent systems now act as 24/7 digital epidemiologists—synthesizing multilingual signals and supporting decisions that once relied solely on human analysts. 

## EIS in Germany
- Surveillance system attributes for evaluating the Epidemic Intelligence from Open Sources system for international public health intelligence ranked

use resource/tileshop.jpeg

- During the evaluation of the EIOS system, the PHI team used a customised EIOS board with 56 sources, which detected 15 of 20 reported PHI-relevant signals. Approximately 76 articles had to be screened to detect one signal. Using a higher number of EIOS sources would have detected one more signal and improved timeliness by half a day, but would have required screening 35,546 articles instead of 1,138

recommend integrating EIOS with an event management system to facilitate signal documentation and reporting
increasing the number of EIOS sources increased timeliness and sensitivity only slightly, but caused a 35-fold increase in articles requiring screening — from 1,138 to 35,546

ref: Martín-Sánchez M, Esquevin S, Jansen A, Gillesberg Lassen S. Design and implementation of an evaluation framework for the Epidemic Intelligence from Open Sources (EIOS) system for international public health intelligence at the Robert Koch Institute, Germany, 2023. Euro Surveill. 2026 Feb;31(5):2500363. doi: 10.2807/1560-7917.ES.2026.31.5.2500363. PMID: 41645798; PMCID: PMC12881845.



## An indicator framework for Event-based surveillance systems
reference: Lancet Glob Health. Author manuscript; available in PMC: 2024 Aug 27.
Published in final edited form as: Lancet Glob Health. 2024 Feb 13;12(4):e707–e711. doi: 10.1016/S2214-109X(24)00034-2 An indicator framework for the monitoring and evaluation of event-based surveillance systems

use pic from resource/nihms-2011590-f0001.png

## The Innovation Forum AI podcast
Artificial Public Health Intelligence Weekly Journal Digest
Oliver Morgan
use pic from resource/2dd3dfa8-55ba-4ecc-af31-3a7fbdb6c6c3_3000x3000
You can listen to the full episode here: YouTube, Apple Podcasts, Spotify, and Amazon Music.

ref: https://aipublichealth.substack.com/

## Concerns 
### 8-2. Why can’t epidemiology be automated (yet)? Perhaps it shouldn’t be Roemer J. Janse 1,2, and Amber Meulenbeld
International Journal of Epidemiology, 2026, 55(3), dyag065 
https://doi.org/10.1093/ije/dyag065 







------------------------------------------------------
# Part 3: Taiwan's Blue print


## AI-first System design

- Architecture & Sovereignty: Deploys a modular, containerized cloud-based system utilizing microservices with active-backup load balancing and strict data localization completely inside Taiwan.  
- Database Engineering: Builds a cloud-based system database under 3NF relational modeling with explicit ACID traits and temporal partitioning to maximize LLM fetch speeds.  
- Core AI Architecture: Powers an advanced AI pipeline running Context Window Management, paid AI API keys and dynamic multi-version model management to easily switch underlying commercial LLMs.  
- Agentic AI Workflows: Utilizes autonomous AI Agents to execute multi-source fact-checking and automated risk reasoning alongside human-in-the-loop validation gates.  - Security & Compliance: Secures the cloud-based system under the SSDLC framework to satisfy the "Ordinary" defense tier using RBAC tied directly to institutional Active Directory accounts.  



## AI-powered busniness process optimisation

- Data Ingestion: Automated incremental global scraping from common source, disease-specific source, country specific source, AI multi-format file parsing, data upload manually, and live cross-system data streaming to CDC's systems. Multi AI agent collaborate: crawler, verify, extract, assess, compare, notify, summary.  
- Daily Intelligence: AI priority triaging , smart summary fusion , map-linked briefing dashboards with text-to-speech , and public portal syncs.  
- Deliverable Generation: One-click automated formatting for PPTX epidemic weeklies , LLM media press releases , and executive briefing sheets.  
- Situation Dashboards: Secure dual-network separation (secured vs public), conversational natural language chart generation , electronic maps , and open public APIs, subscribtion. Special action to pandemic response and monitoring.  
- Risk Assessment: Autonomous AI Agents querying literature to output quantitative reports with manual parameter overrides.
- Travel Health notices: Algorithmic metric evaluation for automated tier shifts , instant safety threshold alerts , and dynamic pathogen auto-enrollment

> Take Ebola, the system should be able to verify and examine the data across various time points, different expressions (case, confirmed, probable, suspicious), different agencies, and even when data go back ward modification (today's accumulated count less than yesterday's count) 

## A matter of 'when', not 'if'
style: big quotes.
We haven't learnt the full lession of COVID pandemic, given the failure of reaching consensus of Pandemic Agreement's PABS
Why trust remains key? -> 
> Nonetheless, as the protracted Ebola epidemic in DRC and epidemics of a different Ebola strain in Uganda in 2022-2023 have shown, having effective vaccines is not enough. In the immediate aftermath of the West African epidemic, expert panels reflected on lessons to prevent future outbreaks. A key insight that shapes future response is recognising the need to build the trust of communities affected by health emergencies. The work done by social scientists and community activists during the Ebola outbreak highlighted the importance of two-way dialogue and the development of response measures that take into account people’s experiences and perspectives. For example, such dialogue led to the integration of local funerary practices in the ways safe and dignified burials were conducted. Community engagement is now an established component of any international response. ref: https://www.lshtm.ac.uk/newsevents/expert-opinion/ebola-10-years-why-trust-remains-key


