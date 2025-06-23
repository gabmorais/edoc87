# Exploratory study of microservices' operational stability

This repository contains the data used in and produced by our experiments, serving as supporting material for reproduction and further analysis. Confidential information acquired from the participating case study is not available; some information may be disclosed upon request, provided authorization is obtained from the case study.

## Research Design
This research was conducted in four phases, each incrementally building upon the previous one. First, we built a conceptual framework that served as a guide to the exploration and execution. Second, we conducted interviews to acquire general knowledge about the case context. Third, we conducted on-site observations. Finally, we performed data analysis supported by data triangulation, case internal documentation exploration and supplementary literature review. During this process, the conceptual framework has been continually updated and refined in response to emerging facts.

### Conceptual framework
The folder [`conceptual_framework`](conceptual_framework) contains the final conceptual framework files, which comprise the definition of the key concepts used in this research and serve as a classification system for our findings. This conceptual framework was initially created from the first literature review on software operations, software dependability and sustainability, and operational aspects of microservices architectures.

We queried [`Google Scholar`](https://scholar.google.com/),[`Science Direct`](https://www.sciencedirect.com/), and [`ACM Digital Library`](https://dl.acm.org/) using the following search chain:

```('software operation' or 'software dependability' or 'software sustainability' or (('microservice' or 'micro-service') and 'operation') ) and ('taxonomy' or 'ontology' or 'framework').```

We selected taxonomies, ontologies, conceptual frameworks, and definition-focused papers. We considered works written in the English language and having an explicit definition schema. The file [`references`](conceptual_framework\references.bib) lists the papers selected for the initial conceptual framework.

### Interviews - Problem Identification and Case Exploration
The folder [`interviews`](interviews) contains the guidelines we used to conduct interviews. It comprises the initial set of [`questions`](interviews\questions.csv), their knowledge goal, and target role. These initial questions fed the initial [`questions_backlog`](questions_backlog.csv), which serves as a gauge for the saturation indicator of this study. We identified saturation as reached when no new questions emerged.

### Observations - Process Execution, Exploration, and Data Analysis
The folder [`observations`](observations) contains the template of the observation journal we used and the minute template.

#### Data Analysis
We conducted a data triangulation analysis, comparing data collected from interviews, observations, and internal case documentation. We explored process-specific, stability lexicon and practice documentation from the case. This process allowed us to link participants' responses and practices to the organization's operational stability vision and standards.

We also conducted opportunistic literature reviews to link our findings to existing research. On the one hand, we aimed to identify the transferability of our findings, as if a finding was observed elsewhere, it indicated that the finding was transferable to and from our studied case. On the other hand, this literature review supported our efforts in identifying case-specific details, deepening our understanding of the observed facts, and uncovering new ones.

We queried [`Google Scholar`](https://scholar.google.com/),[`Science Direct`](https://www.sciencedirect.com/), and [`ACM Digital Library`](https://dl.acm.org/) using terms extracted from interview and observation minutes, as well as from the questions added to the *questions backlog*. It is worth noting that we initially explored the literature when new questions arose before conducting subsequent interviews and observations.

## Citation
```text
@article{msaoperationalstability2025,
 author = {Morais, Gabriel and Adda, Mehdi and Bork, Dominik},
 title = {A Decade of Challenges: A Practitioners Exploratory Study of Microservices Operational Stability},
 year = {2025}
}
```