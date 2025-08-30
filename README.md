# LogiSec of Thoughts - Data

This repository contains supplementary materials for the paper:

**Reasoning Over Vulnerabilities via LogiSec of Thoughts: A Reductio Ad Absurdum-Based LLM Framework**

**Authors:**
- Claudio A. S. Lelis¹  
- Cesar A. C. Marcondes¹  
- Kevin Fealey²  

¹ Divisão de Ciência da Computação – Instituto Tecnológico de Aeronáutica (ITA)  
São José dos Campos – SP – Brazil  
² AppSecAI, Inc. – Los Altos – California – USA

**Contact Emails:**  
claudio.lelis@ga.ita.br  
cesar.marcondes@gp.ita.br  
kevin@appsecure.ai

This paper was accepted for presentation in the **Main Track of the 14th Latin-American Symposium on Dependable and Secure Computing (LADC 2025)**.

## Repository Content

This repository includes:
- the SARIF file used in the experiments, considering only the 300 cases selected for the experiments;
- CSV file, based on OWASP BenchmarkJava expected-results1.2.csv file, considering only the 300 cases selected for the experiments;
- FLAGS intervention constraint;
- the LSoT prompts for "assuming secure" variation;
- the LSoT for "assuming vulnerable" variation;
- a folder with the raw transcripts of per-intervention explanations for `BenchmarkTest00251.java`, also the original and anonymized version for the Java code, as commented in the paper.


## Citation

If you use this data or refer to it in academic work, please cite our paper and reference this repository.

## License and Use Disclaimer

⚠️ **Disclaimer:**  
All contents of this repository are provided strictly for academic transparency and reproducibility in support of the LADC 2025 publication. **No part of this material may be used, copied, stored, modified, or redistributed—whether in whole or in part—without prior written permission from the authors.**

© 2025 AppSecAI, Inc. All rights reserved.  
This software and its source code are the proprietary information of AppSecAI, Inc.  
**Unauthorized copying, modification, distribution, or use of this software is strictly prohibited.**
