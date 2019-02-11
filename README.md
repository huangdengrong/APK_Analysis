# EAAC-Embedding Based Analyzer for APK Callbacks


## Introduction
The event-driven mechanism of mobile applications makes specific code defects and malicious attacks with significant callback characteristics. Due to the complexity and sequentiality of the callback structure, traditional analysis methods fail to take the callback characteristics into consideration, which makes the defect and security problems at the callback level difficult to detect. Aiming at the problem, the project introduces the vector representation technology based on the word embedding from the perspective of intelligent learning, and performs such a context-sensitive numerical vector representation for the callback structure of mobile applications. Afterwards, the correlation mechanism between vector representation and callback characteristics as well as its explanatory meaning is systematically analyzed. Then, based on the embedded vector and analysis results, methods such as intelligent learning, data mining and graph matching are employed to design supervised learning prediction models and unsupervised detection models, respectively. The designed models are then trained to detect callback related code anomalies defects and the malicious structures, and thus compensate for the lack of capacity and effectiveness of the traditional detection methods for mobile applications.

## Subjects
### AMD malware 
(Part of Samples)
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/AMD_malware
### F-Droid
(Part of Samples)
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/F-Droid
### Apps from Markets (Reverse Engineering)
(Part of Samples)
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/Apps_from_Markets

## Extraction of Callback Elements 
### Callback Datasets
https://github.com/huangdengrong/My_APK_Analysis_/blob/master/simility_analysis/callback_api.csv
### Related Elements
https://github.com/huangdengrong/APK_Analysis/blob/master/Table_related_elements.pdf

## Middle Extraction
https://github.com/huangdengrong/APK_Analysis/blob/master/Table_middle_abstraction.pdf

## Embedding
### source code
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/New_Final_APK_Project
### Embedded Vectors
https://github.com/huangdengrong/My_APK_Analysis_/blob/master/simility_analysis/my_apk_vector1.csv

## Analysis
### Similarities
https://github.com/huangdengrong/My_APK_Analysis_/blob/master/simility_analysis/sim_vector_.txt
https://github.com/huangdengrong/My_APK_Analysis_/blob/master/simility_analysis/sim_vector.xlsx
### Analogies
https://github.com/huangdengrong/My_APK_Analysis_/blob/master/simility_analysis/Analogy_Analisis.txt
### Callback Patterns
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/model/amd_model
https://github.com/huangdengrong/My_APK_Analysis_/tree/master/model/no_amd_model

## Detection and Prediction
### Detection for Malicious Structures
- Baseline: FlowDroid(<u>Arzt S, Rasthofer S, Fritz C, et al. Flowdroid: Precise context, flow, field, object-sensitive and lifecycle-aware taint analysis for android apps[J]. Acm Sigplan Notices, 2014, 49(6): 259-269.</u>)
- Dataset Description:
- Raw Results:https://github.com/huangdengrong/APK_Analysis/blob/master/result_malicious_structure_30.pdf

### Detection for Resource Leak
- Baseline: Relda2(<u>Wu T, Liu J, Deng X, et al. Relda2: an effective static analysis tool for resource leak detection in Android apps[C]. Proceedings of the 31st IEEE/ACM International Conference on Automated Software Engineering. ACM, 2016: 762-767. </u>)
- Dataset Description: https://github.com/huangdengrong/APK_Analysis/blob/master/dataset_resource_leak.pdf
- Raw Results:https://github.com/huangdengrong/APK_Analysis/blob/master/result_resourceleak1.jpg

### Prediction for Anomlies of Callbacks
- Baseline: 
--DEvA(<u>Safi G, Shahbazian A, Halfond W G J, et al. Detecting event anomalies in event-based systems[C]//Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering. ACM, 2015: 25-37.</u>)
--Event-racer(Bielik P, Raychev V, Vechev M. Scalable race detection for android applications[C]//ACM SIGPLAN Notices. ACM, 2015, 50(10): 332-348. https://eventracer.org/android/#traces)
- Dataset Description: https://github.com/huangdengrong/APK_Analysis/blob/master/dataset_anomalies.jpg
- Raw Results:https://github.com/huangdengrong/APK_Analysis/blob/master/result_anomalies.jpg

