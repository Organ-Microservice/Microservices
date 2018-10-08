# Functionality-Oriented Microservice Extraction Based on Execution Trace Clustering
  
**Abstract:**  
The main task of microservice extraction is to find which software entities (e.g., methods, classes) should be grouped together from existing monolithic software as candidate microservices, responsible for specific functionalities and evolving independently. Current methods extract microservices by analyzing source code and following the assumption that "classes with strong relation should be in the same service", which originates from software structure analysis. We find that 1) many program behaviors cannot be explicitly reflected in the source code, and 2) the relation at code-level is not equivalent to the same functionality. Thus, we propose a functionality-oriented microservice extraction (FoME) method in this study by monitoring program dynamic behavior and clustering execution traces. Instead of source code analysis, the execution traces of a program are applied to group source code entities that are dedicated to the same functionality. We also construct a systematic measurement of microservice by integrating five complementary metrics of service cohesion and coupling. These metrics measure Functional Independence of microservices. That is, it qualifies whether a microservices can have its own responsibilities independently. In the experiment, our method is compared with three state-of-the-art methods on four open-source projects. The microservice candidates generated using our method present similar functional cohesion to the services produced using the other methods, but have considerably looser coupling measurements (dramatically reducing measurements of IRN and OPN).
</br>  
**Keywords:**  
Software
,
Measurement
,
Business
,
Monitoring
,
Couplings
,
Skeleton
,
Systematics
</br>  
**Authors:**  
Wuxia Jin  
Ting Liu  
Qinghua Zheng  
Di Cui  
Yuanfang Cai
</br>  
**References：**  
1. S. Newman, Building microservices: designing fine-grained systems, O'Reilly Media, Inc, 2015.  
2. N. Dragoni, S. Giallorenzo, A. L. Lafuente, M. Mazzara, F. Montesi, R. Mustafin, L. Safina, "Microservices: yesterday today and tomorrow" in Present and Ulterior Software Engineering, Springer, pp. 195-216, 2017.  
3. G. Mazlami, J. Cito, P. Leitner, "Extraction of mi-croservices from monolithic software architectures", Web Services (ICWS) 2017 IEEE International Conference on, pp. 524-531, 2017.  
4. S. Mancoridis, B. S. Mitchell, Y. Chen, E. R. Gansner, "Bunch: A clustering tool for the recovery and maintenance of software system structures", Software Maintenance 1999. (ICSM'99) Proceedings. IEEE International Conference on, pp. 50-59, 1999.  
5. V. Tzerpos, R. C. Holt, "Accd: an algorithm for comprehension-driven clustering", Reverse Engineering 2000. Proceedings. Seventh Working Conference on, pp. 258-267, 2000.  
6. I. Candela, G. Bavota, B. Russo, R. Oliveto, "Using cohesion and coupling for software remodularization: Is it enough?", ACM Transactions on Software Engineering and Methodology (TOSEM), vol. 25, no. 3, pp. 24, 2016.   
7. J. Garcia, D. Popescu, C. Mattmann, N. Medvidovic, Y. Cai, "Enhancing architectural recovery using concerns", Proceedings of the 2011 26th IEEE/ACM International Conference on Automated Software Engineering, pp. 552-555, 2011.  
8. B. Dit, M. Revelle, M. Gethers, D. Poshyvanyk, "Feature location in source code: a taxonomy and survey", Journal of software. Evolution and Process, vol. 25, pp. 53-95, 2013.  
9. M. Fan, J. Liu, X. Luo, K. Chen, Z. Tian, Q. Zheng, T. Liu, "Android malware familial classification and representative sample selection via frequent subgraph analysis" in IEEE Transactions on Information Forensics and Security, 2018.  
10. M. Fan, J. Liu, W. Wang, H. Li, Z. Tian, T. Liu, "Dapasa: detecting android piggybacked apps through sensitive subgraph analysis", IEEE Transactions on Information Forensics and Security, vol. 12, no. 8, pp. 1772-1785, 2017.  
11. A. Van Hoorn, J. Waller, W. Hasselbring, "Kieker: A framework for application performance monitoring and dynamic software analysis", Proceedings of the 3rd ACM/SPEC International Conference on Performance Engineering, pp. 247-248, 2012.  
12. N. Alshuqayran, N. Ali, R. Evans, "A systematic mapping study in microservice architecture", Service-Oriented Computing and Applications (SOCA) 2016 IEEE 9th International Conference on, pp. 44-51, 2016.  
13. P. Di Francesco, I. Malavolta, P. Lago, "Research on architecting microservices: Trends focus and potential for industrial adoption", Software Architecture (ICSA) 2017 IEEE International Conference on, pp. 21-30, 2017.  
14. M. Chatterjee, S. K. Das, D. Turgut, "Wca: A weighted clustering algorithm for mobile ad hoc networks", Cluster computing, vol. 5, no. 2, pp. 193-204, 2002.  
15. S. Millett, Patterns Principles and Practices of Domain-Driven Design, John Wiley & Sons, 2015. 
16. T. Lutellier, D. Chollak, J. Garcia, L. Tan, D. Rayside, N. Medvidovic, R. Kroeger, "Measuring the impact of code dependencies on software architecture recovery techniques" in IEEE Transactions on Software Engineering, 2017.  
17. M. Fowler, K. Beck, Refactoring: improving the design of existing code, Addison-Wesley Professional, 1999.  
18. W. Jin, T. Liu, Y. Qu, Q. Zheng, D. Cui, J. Chi, "Dynamic structure measurement for distributed software" in Software Quality Journal, pp. 1-27, 2017.  
19. W. Jin, T. Liu, Y. Qu, J. Chi, D. Cui, Q. Zheng, "Dynamic cohesion measurement for distributed system", International Workshop on Specification Comprehension Testing and Debugging of Concurrent Programs, pp. 20-26, 2016.  
20. D. Athanasopoulos, A. V. Zarras, G. Miskos, V. Issarny, P. Vassiliadis, "Cohesion-driven decomposition of service interfaces without access to source code", IEEE Transactions on Services Computing, vol. 8, no. 4, pp. 550-562, 2015.  
21. A. Ouni, M. Kessentini, K. Inoue, M. O. Cinneidc, "Search-based web service antipatterns detection", IEEE Transactions on Services Computing, vol. 10, no. 4, pp. 603-617, 2017.  
22. S. Adjoyan, A.-D. Seriai, A. Shatnawi, "Service identification based on quality metrics object-oriented legacy system migration towards soa" in SEKE: Software Engineering and Knowledge Engineering. Knowledge Systems Institute Graduate School, pp. 1-6, 2014.  
23. P. Andritsos, V. Tzerpos, "Information-theoretic software clustering", IEEE Transactions on Software Engineering, vol. 31, no. 2, pp. 150-165, 2005.  
24. J. Garcia, I. Ivkovic, N. Medvidovic, "A comparative analysis of software architecture recovery techniques", Proceedings of 28th IEEE/ACM International Conference on Automated Software Engineering, pp. 486-496, 2013.  
25. A. Levcovitz, R. Terra, M. T. Valente, "Towards a technique for extracting microservices from monolithic enterprise systems", CoRR, vol. abs/1605. 03175, 2016.  
