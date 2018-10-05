# Microservices 
关于微服务的书籍和论文的笔记整理集合

------
# 会议论文分类

## 一.会议名称：[Foundations of Software Engineering (SIGSOFT FSE)](https://dblp.uni-trier.de/db/conf/sigsoft/)

### 1.会议时间: [25. SIGSOFT FSE / 16. ESEC 2017: Paderborn, Germany](https://dblp.uni-trier.de/db/conf/sigsoft/fse2017.html)

#### Proceedings of the 2017 11th Joint Meeting on Foundations of Software Engineering, ESEC/FSE 2017,

* [Guidelines for adopting frontend architectures and patterns in microservices-based systems.(Paderborn, Germany — September 04 - 08, 2017 )](https://dl.acm.org/citation.cfm?doid=3106237.3117775) 
> Abstract:
Microservice-based systems enable the independent development, deployment, and scalability for separate system components of enterprise applications. A significant aspect during development is the microservice integration in frontends of web, mobile, and desktop applications. One challenge here is the selection of an adequate frontend architecture as well as suitable patterns that satisfy the application requirements. This paper analyses available strategies for organizing and implementing microservices frontends. These approaches are then evaluated based on a quality model and various prototypes of the same application implemented using the distinct approaches. The results of this analysis are generalized to a guideline that supports the selection of a suitable architecture.




## 二.会议名称：[International Conference on Software Engineering (ICSE)](https://dblp.uni-trier.de/db/conf/icse/)

### 1.会议时间：[ICSE 2018: Gothenburg, Sweden - Companion Volume（May 27 - June 03, 2018 ）](https://dblp.uni-trier.de/db/conf/icse/icse2018c.html)

#### 会议主题：Companion Proceeedings
* [Exploration of academic and industrial evidence about architectural tactics and patterns in microservices. 256-257](https://dl.acm.org/citation.cfm?doid=3183440.3194958) 
> Abstract:
Microservices are quickly becoming an outstanding architectural choice in the service-oriented software industry. This approach proposes to develop each application as a collection of small services, each running on its process and inter-communicating with lightweight mechanisms. Currently, there is still no clear perspective of emerging recurrent solutions (architectural patterns) or design decisions (architectural tactics) in microservices both in industry and academia. This article describes a systematic review of the academic and industrial literature on architectural patterns and tactics proposed for microservices. The study reported: 44 architectural patterns of microservices in academia and 80 in the industry; architectural tactics related to microservices dependent on other disciplines; and it was also found that most of architectural patterns and tactics are associated to five quality attributes: scalability, flexibility, testability, performance, and elasticity. Added to that results, it was noticed that most microservices in the academic area are reported in evidence related to DevOps and IoT, but the industry is not interested in associating disciplines. Finally, a new proposal of microservices pattern taxonomy is suggested.

* [Benchmarking microservice systems for software engineering research. 323-324（复旦）](https://dl.acm.org/citation.cfm?doid=3183440.3194991) 
> Abstract:Despite the prevalence and importance of microservices in industry, there exists limited research on microservices, partly due to lacking a benchmark system that reflects the characteristics of industrial microservice systems. To fill this gap, we conduct a review of literature and open source systems to identify the gap between existing benchmark systems and industrial microservice systems. Based on the results of the gap analysis, we then develop and release a medium-size benchmark system of microservice architecture.


* [A declarative approach for updating distributed microservices.](https://dl.acm.org/citation.cfm?doid=3183440.3195023) 
> Abstract:One of the greatest benefits of microservices is to sensitively ease changing applications by splitting these into independently deployable units [5]. Combined with Continuous Delivery (CD) -that aims at delivering quickly and safely every software releases- and Platform as a Service (PaaS) automating application management in a on-demand virtualized environment, the microservice paradigm has become essential to implement agile processes.


#### 会议主题：Companion ProceeedingsNew Ideas and Emerging Results

* [Deep customization of multi-tenant SaaS using intrusive microservices. 97-100](https://dblp.uni-trier.de/db/conf/icse/nier2018.html) 
> Abstract:
Enterprise software needs to be customizable, and the customization needs from a customer are often beyond what the software vendor can predict in advance. In the on-premises era, customers do deep customizations beyond vendor's prediction by directly modifying the vendor's source code and then build and operate it on their own premises. When enterprise software is moving to cloud-based multi-tenant SaaS (Software as a Service), it is no longer possible for customers to directly modify the vendor's source code, because the same instance of code is shared by multiple customers at runtime. Therefore, the question is whether it is still possible to do deep customization on multi-tenant SaaS. In this paper, we give an answer to this question with a novel architecture style to realize deep customization of SaaS using intrusive microservices. We evaluate the approach on an open source online commercial system, and discuss the further research questions to make deep customization applicable in practice.

### 2.会议时间：[39th IEEE/ACM International Conference on Software Engineering: Software Engineering in Society Track, ICSE-SEIS 2017, Bueons Aires, Argentina, May 20-28, 2017.](https://dblp.uni-trier.de/db/conf/ispw/icssp2016.html)

#### 会议主题：Software Engineering in Society Track
* [Exploration of academic and industrial evidence about architectural tactics and patterns in microservices. 256-257](https://dl.acm.org/citation.cfm?doid=2904354.2904368) 
> Abstract:
Over the decades, a variety of software development processes have been proposed, each with their own advantages and disadvantages. It is however widely accepted that there is no single process that is perfectly suited to all settings, thus a software process should be molded to the needs of its situational context. In previous work, we have consolidated a substantial body of related research into an initial reference framework of the situational factors affecting the software development process. Practitioners can consult this framework in order to profile their context, a step necessary for effective software process decision making. In this paper, we report on the findings from a case study involving process discovery in a small but successful and growing software development firm. In this organization, which has a focus on continuous software evolution and delivery, we also applied the situational factors reference framework, finding that context is a complex and key informant for software process decisions. Studies of this type highlight the role of situational context in software process definition and evolution, and they raise awareness not just of the importance of situational context, but also of the complexity surrounding software process contexts, a complexity which may not be fully appreciated in all software development settings.


## 三.会议名称：[International Conference on Service Oriented Computing(ICSOC)](https://dblp.uni-trier.de/db/conf/icsoc/)

### 1.会议时间：[15th ICSOC 2017: Malaga, Spain（November 13-16, 2017）](https://dblp.uni-trier.de/db/conf/icsoc/icsoc2017.html)

#### 会议主题：Proceedings
* [Inferring Calling Relationship Based on External Observation for Microservice Architecture](https://link.springer.com/chapter/10.1007%2F978-3-319-69035-3_16) 
> Abstract:
In recent years, a web service architecture namely microservices has attracted attention. Although the microservice architecture provides various advantages, it also has the disadvantage of making the root cause analysis of the complicated system. For root cause analysis, it is important to know the calling relationships between services since the service may call the other service and the latency of the called service may be wrong. Therefore, in this paper, we propose a method to infer the calling relationship between the services from communication logs observed from outside of the services.  
Keywords：
Microservice architecture， Distributed， tracing system， Visualization PaaS 

* [Ensuring and Assessing Architecture Conformance to Microservice Decomposition Patterns.](https://link.springer.com/chapter/10.1007%2F978-3-319-69035-3_29) 
> Abstract:
Microservice-based software architecture design has been widely discussed, and best practices have been published as architecture design patterns. However, conformance to those patterns is hard to ensure and assess automatically, leading to problems such as architectural drift and erosion, especially in the context of continued software evolution or large-scale microservice systems. In addition, not much in the component and connector architecture models is specific (only) to the microservices approach, whereas other aspects really specific to that approach, such as independent deployment of microservices, are usually modeled in other views or not at all. We suggest a set of constraints to check and metrics to assess architecture conformance to microservice patterns. In comparison to expert judgment derived from the patterns, a subset of these constraints and metrics shows a good relative performance and potential for automation.

* [Supporting the Decision of Migrating to Microservices Through Multi-layer Fuzzy Cognitive Maps. 471-480](https://link.springer.com/chapter/10.1007%2F978-3-319-69035-3_34) 
> Abstract:
Microservices architectures are gaining momentum for the development of applications as suites of small, autonomous, and conversational services, which are then easy to understand, deploy and scale. However, one of today’s problems is that microservices introduce new complexities to the system and, despite the hype, many factors should be considered when deciding to adopt a microservices architecture. This paper proposes the first Decision Support System (DSS) to migrate to microservices, by identifying the key concepts and drivers regarding through a literature review and feedback from a group of experts from industry and academia. Then, these concepts are organized as a Multi-Layer Fuzzy Cognitive Map (ML-FCM), a graph-based computational intelligence model that captures the behavior of a given problem in nodes that represent knowledge in the domain, and offers the means to study their influence and interrelation. Static and dynamic analysis over the resulting ML-FCM helped us identify the prevailing drivers towards the migration to a microservices architecture.  
keywords：Microservices architectures, Monolith migration, Multi-layer Fuzzy Cognitive Maps 


## 2.会议名称：[International Conference on Web Services [ICWS]](https://dblp.uni-trier.de/db/conf/icws/)

### 会议时间：[ICWS 2018: San Francisco, CA, USA(July 2-7, 2018)](https://dblp.uni-trier.de/db/conf/icws/icws2018.html)

#### 会议主题： Applications and Big Data and Cloud Services
* [Microservice Based Video Cloud Platform with Performance-Aware Service Path Selection. 306-309](https://ieeexplore.ieee.org/document/8456365) 
> Abstract:
Microservice based cloud architecture becomes a promising solution to deal with the challenges of large-scale intelligent video applications. However, the current service selection methods usually do not consider both the fine-grained online service capability and the features of video tasks, and this will result in the degradation of the overall efficiency of the service composition. In this paper, we propose a novel Performance-aware Service PAth Selection (PSPAS) approach for the microservice based video cloud computing platform. Firstly, we establish a fine-grained time estimation model which synthetically considers the processing capability of microservice instances, the characteristics of video processing tasks, and the data transfer conditions between microservice instances. Then, based on the proposed performance model, we search and update the optimal microservice path by using the shortest path algorithm. Finally, the experiment evaluation results demonstrate the effectiveness of our method.
Keywords：
Microservice, service path selection, cloud computing, video processing

### 3.会议时间：[ICWS 2017: Honolulu, HI, USA(June 25-30, 2017)](https://dblp.uni-trier.de/db/conf/icws/icws2017.html)

#### 会议主题： Applications and Big Data and Cloud Services
* [Extraction of Microservices from Monolithic Software Architectures. 524-531
](https://ieeexplore.ieee.org/document/8029803) 
> Abstract:
Driven by developments such as mobile computing, cloud computing infrastructure, DevOps and elastic computing, the microservice architectural style has emerged as a new alternative to the monolithic style for designing large software systems. Monolithic legacy applications in industry undergo a migration to microservice-oriented architectures. A key challenge in this context is the extraction of microservices from existing monolithic code bases. While informal migration patterns and techniques exist, there is a lack of formal models and automated support tools in that area. This paper tackles that challenge by presenting a formal microservice extraction model to allow algorithmic recommendation of microservice candidates in a refactoring and migration scenario. The formal model is implemented in a web-based prototype. A performance evaluation demonstrates that the presented approach provides adequate performance. The recommendation quality is evaluated quantitatively by custom microservice-specific metrics. The results show that the produced microservice candidates lower the average development team size down to half of the original size or lower. Furthermore, the size of recommended microservice conforms with microservice sizing reported by empirical surveys and the domain-specific redundancy among different microservices is kept at a low rate.
Keywords：
Couplings ,Clustering algorithms, Computer architecture, Cloud computing, Industries, Tools




## 会议：[Automated Software Engineering(ASE), Volume 25 ,2018](https://dblp.uni-trier.de/db/journals/ase/ase25.html)







------

### 《Building MicroServices》摘要
[Chapter1. Microservices]: /1_microservices   "第一章"

* [Chapter1. Microservices]

------

### surveys摘要
[Migrating towards Microservice Architectures: an Industrial Survey]: /survey_1.md
[Survey on Microservice Architecture - Security, Privacy and Standardization on
Cloud Computing Environment]: /survey_2.md

* ICSA_2018: [Migrating towards Microservice Architectures: an Industrial Survey] （不重要）
* ICSEA_2017: [Survey on Microservice Architecture - Security, Privacy and Standardization on
Cloud Computing Environment]










