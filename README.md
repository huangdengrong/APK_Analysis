# EAAC-Embedding Based Analyzer for APK Callbacks


## Introduction
The event-driven mechanism of mobile applications makes specific code defects and malicious attacks with significant callback characteristics. Due to the complexity and sequentiality of the callback structure, traditional analysis methods fail to take the callback characteristics into consideration, which makes the defect and security problems at the callback level difficult to detect. Aiming at the problem, the project introduces the vector representation technology based on the word embedding from the perspective of intelligent learning, and performs such a context-sensitive numerical vector representation for the callback structure of mobile applications. Afterwards, the correlation mechanism between vector representation and callback characteristics as well as its explanatory meaning is systematically analyzed. Then, based on the embedded vector and analysis results, methods such as intelligent learning, data mining and graph matching are employed to design supervised learning prediction models and unsupervised detection models, respectively. The designed models are then trained to detect callback related code anomalies defects and the malicious structures, and thus compensate for the lack of capacity and effectiveness of the traditional detection methods for mobile applications.

## Subjects
### AMD malware 
TODO:Examples
### F-Droid
TODO:Examples
### Apps from Markets (Reverse Engineering)
TODO:Examples

## Extraction of Callback Elements 
### Callback Datasets
TODO:hypelink to the table
### Related Elements
TODO:hypelink to the table

## Middle Extraction
TODO:hypelink to the table

## Embedding
### source code
TODO:hypelink to source code
### Embedded Vectors
TODO:hypelink to Embedded Vectors

## Analysis
### Similarities
TODO: typical similarity groups
### Analogies
TODO: typical Analogies groups
### Callback Patterns
TODO: typical Callback Patterns

## Detection and Prediction
### Detection for Malcious Structures
- Baseline: FlowDroid(<u>Arzt S, Rasthofer S, Fritz C, et al. Flowdroid: Precise context, flow, field, object-sensitive and lifecycle-aware taint analysis for android apps[J]. Acm Sigplan Notices, 2014, 49(6): 259-269.</u>)
- Dataset:
- Raw Results:
### Detection for Resource Leak
- Baseline: Relda2(<u>Wu T, Liu J, Deng X, et al. Relda2: an effective static analysis tool for resource leak detection in Android apps[C]. Proceedings of the 31st IEEE/ACM International Conference on Automated Software Engineering. ACM, 2016: 762-767. </u>)
- Dataset:
- Raw Results:
### Prediction for Anomlies of Callbacks
- Baseline: DEvA(<u>Safi G, Shahbazian A, Halfond W G J, et al. Detecting event anomalies in event-based systems[C]//Proceedings of the 2015 10th Joint Meeting on Foundations of Software Engineering. ACM, 2015: 25-37.</u>)
- Dataset:
- Raw Results:

