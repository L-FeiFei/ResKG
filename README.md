# Abstract
As heterogeneous entities and intricate interactions proliferate in Internet of Things (IoT) environments, addressing the challenge of reasoning over incomplete structured knowledge has become crucial. Consequently, knowledge graph completion (KGC) has gained considerable attention as an essential approach for inferring missing data and enhancing knowledge structures. Despite notable advancements, KGC continues to face structural challenges, particularly when dealing with complex multihop relations and many-to-many relational patterns. To address these issues, we propose ResKG, a resonant framework that improves link prediction by leveraging structural resonance across isomorphic subgraphs. The design of ResKG is driven by two key observations: (1) local subgraphs with similar topologies tend to exhibit consistent structural patterns, and (2) neighboring entities contribute differently to relation inference based on their structural importance. On the basis of these insights, ResKG introduces two core components: (1) topology-aware dependency, which captures structural consistency across isomorphic subgraphs, and (2) resonance relationship mining, which adaptively highlights structurally important neighbors through a resonant bias mechanism. Experimental results on several public benchmarks show that ResKG achieves state-of-the-art performance in link prediction, highlighting the importance of structural resonance modeling for knowledge graph completion. Our work offers valuable new perspectives on structural property modeling for KGC. 
## Resonance topology-guided transformer architecture
<img width="1765" height="957" alt="image" src="https://github.com/user-attachments/assets/91aaff99-c30c-4d1e-b5c2-6ca767d8bc7a" />


## Comparison
Considering that benchmark datasets such as FB15k-237, WN18RR, and YAGO3-10 share the same structural modeling and completion challenges as knowledge graphs in IoT systems, ResKG is compared with a variety of state-of-the-art methods on general knowledge graph datasets, and the performance of different approaches is analyzed. The best results are highlighted in bold, and the second-best results are underlined.
### Comparison on WN18 and FB15K datasets:
<img width="1101" height="551" alt="image" src="https://github.com/user-attachments/assets/2128adfc-8568-441a-9e75-6dccf75583aa" />
### Comparison on WN18RR, FB15K-237, and YAGO3-10 datasets:
<img width="1343" height="943" alt="image" src="https://github.com/user-attachments/assets/602f5462-b9f6-4ec7-bc6c-ba0c4fbe3a35" />









