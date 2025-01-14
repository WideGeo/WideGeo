# WideGeo: An Accurate, Scalable, and Fast IP Geolocation System
IP geolocation is essential for various location-aware Internet applications spanning from targeted online advertising to cybercrime traceability. However, previous works are hampered by accuracy degradation in sparse landmark scenarios and poor accuracy in IPv6 geolocation. In this paper, we propose a novel IP geolocation framework, WideGeo, which innovatively constructs a global heterogeneous graph to improve accuracy in sparse landmark scenarios, and uses dual-stack landmarks to solve the accuracy bottleneck in IPv6 geolocation. WideGeo combines offline landmark learning and online geolocation for IP geolocation for the first time to address time efficiency challenges caused by the global heterogeneous graph. Based on these designs, we implement the WideGeo system and conduct real-world experiments, providing high-accuracy IP geolocation efficiently in different scenarios. For IPv4, WideGeo improves accuracy by 321% and over 500% than state-of-the-art methods in sparse and dense landmark scenarios, achieving median errors of 0.815km and 40.829km, respectively. For IPv6, the improvement is even greater, enabling IPv6 accuracy to the same level as IPv4. WideGeo improves accuracy by 354% and over 550% in sparse and dense landmark scenarios, reaching median errors of 3.038km and 43.051km. Furthermore, the average time for online geolocation is sub-minute, 12x shorter than state-of-the-art methods. 

## Introduction
To make it easier for readers to reproduce our research, we make the source code, test data, and graph datasets of WideGeo publically available. Please cite our paper if you use the WideGeo code and dataset, thank you! 

Our project mainly consists of three parts: GeoNetGraph, GraphBert and GeolocationService. 

## Misc
### Ethical and Privacy Concerns
All code and data we publish has been desensitized and does not involve user privacy. Please cite our paper when using. 

### Future work
We are actively deploying the distributed BertGeo IP geolocation system and are constantly updating our datasets and services. If you would like to join us, please send us emails. 
