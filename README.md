## Table Of Contents
- [Machine Learning for Healthcare](#machine-learning-for-healthcare)
    - [Introduction](#introduction)
    - [Genomics](#genomics)
    - [Precision Medicine/Drug Discovery](#precision-medicinedrug-discovery)
        - [Tools](#tools)
    - [Medical Imaging](#medical-imaging)
        - [Papers](#papers)
        - [Blogs, blog posts, and reddit discussions](#blogs-blog-posts-and-reddit-discussions)
        - [Conferences and Workshops](#conferences-and-workshops)
        - [Research Groups](#research-groups)
        - [Competitions](#competitions)
        - [Videos](#videos)
        - [Datasets](#datasets)
        - [Code Repositories](#code-repositories)
        - [Tools](#tools)
        - [Other](#other)
    - [Hospital Operations (i.e. OR Utilization, Scheduling, Discharge planning, HAIs...)](#hospital-operations-ie-or-utilization-scheduling-discharge-planning-hais)
    - [Signal processing, forecasting, and adverse event prediction](#signal-processing-forecasting-and-adverse-event-prediction)
        - [Papers](#papers)
    - [Other and Multiple Categories](#other-and-multiple-categories)
        - [Datasets](#datasets)
        - [Conferences](#conferences)
        - [Papers](#papers)
- [Companies](#companies)

# Machine Learning for Healthcare
This repository is a list of the all the relevant resources on applying machine learning to healthcare. If you see an article, repository, or other useful addition please make a pull request. At the moment structure of the repository is as follows: instead of being broken down by machine learning domains as you would technically expect (i.e. computer vision, NLP, audio...etc), it is broken down by application area (i.e. precision medicine, genomics, medical imaging/radiology, hospital operations...). Papers, conferences, tools, or courses that cover multiple areas of healthcare are moved to the "other/overlapping" category. If you think that this is confusing or there is a better way of doing things please post in the [issues discussion](https://github.com/isaacmg/healthcare_ml/issues/6)

## Introduction

## Genomics

[AffinityNet](https://arxiv.org/abs/1805.08905)

[Bayesian multi-domain learning for cancer subtype discovery from next-generation sequencing count data](https://arxiv.org/pdf/1810.09433.pdf)

[Machine Learning Genomic Medicine](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=7347331)

[Deep learning for Genomics a Overview](https://arxiv.org/abs/1802.00810)

## Precision Medicine/Drug Discovery

[Assessing Disparate Impacts of Personalized Interventions: Identifiability and Bounds](https://arxiv.org/abs/1906.01552)

[Adapting Neural Networks for the Estimation of Treatment Effects](https://arxiv.org/pdf/1906.02120.pdf)

[Attentive State-Space Modeling of Disease Progression](https://nips.cc/Conferences/2019/Schedule?showEvent=14124)

[Dr. VAE](https://arxiv.org/pdf/1706.08203.pdf)

[Deep generative models of genetic variation capture the effects of mutations](https://arxiv.org/abs/1712.06527)

[Deep learning with multimodal representation for pancancer prognosis prediction](https://academic.oup.com/bioinformatics/article/35/14/i446/5529139)

[Deep RL for Radiation Therapy](https://aapm.onlinelibrary.wiley.com/doi/pdf/10.1002/mp.12625)

[GAMENet: Graph Augmented MEmory Networks for Recommending Medication Combination](https://github.com/sjy1203/GAMENet)

[The cornucopia of meaningful leads: Applying deep adversarial autoencoders for new molecule development in oncology](http://www.oncotarget.com/index.php?journal=oncotarget&page=article&op=view&path%5B0%5D=14073&path%5B1%5D=44886)

[End-to-end training of deep probabilistic CCA for
joint modeling of paired biomedical observations](http://bayesiandeeplearning.org/2018/papers/113.pdf)


[Fréchet ChemNet Distance: A metric for generative models for molecules in drug discovery](https://arxiv.org/pdf/1803.09518.pdf) 

[Lesson Learned from Natural Language Inference in the Clinical Domain](https://arxiv.org/pdf/1808.06752.pdf)


[Molecular De Novo design using Recurrent Neural Networks and Reinforcement Learning Code](https://github.com/MarcusOlivecrona/REINVENT)


[NAACL Paper on Cross Speciality Entity Recognition for Medicine](https://aclanthology.coli.uni-saarland.de/papers/N18-1001/n18-1001)

[ Natural Language Processing for Precision Medicine](https://www.microsoft.com/en-us/research/wp-content/uploads/2017/07/1707_tutorial.pdf) ACL 2017 Tutorial.

[Near-Optimal Reinforcement Learning in Dynamic Treatment Regimes](https://causalai.net/r48.pdf)

[Predicting drug response of tumors from integrated genomic profiles by deep neural networks](https://bmcmedgenomics.biomedcentral.com/articles/10.1186/s12920-018-0460-9)

[Regression tree methods for precision medicine](https://www.youtube.com/watch?v=jpUItf0Wt4Y) talk by Wei-Yin Loh
University of Wisconsin-Madison, USA.

[Survey of Computational Methods for Drug Discovery](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC4719067/)

### Tools
[DeepChem](https://deepchem.io)


## Medical Imaging

### Papers

[A Two-Stream Mutual Attention Network for Semi-supervised Biomedical Segmentation with Noisy Labels](https://arxiv.org/abs/1807.11719)

[Clinically Applicable deep learning for retinal disease diagnosis and referal](https://lmb.informatik.uni-freiburg.de/Publications/2018/Ron18/paper-De_Fauw_et_al_2018_Nature_Medicine.pdf)

[CheXNet: Radiologist-Level Pneumonia Detection on Chest X-Rays with Deep Learning](https://arxiv.org/pdf/1711.05225.pdf)

[Domain Generalization via Model-Agnostic Learning of Semantic Features (with application to medical image segmentation](https://arxiv.org/abs/1910.13580)

[Dermatologist Level Skin Classification of skin cancer with deep neural networks](https://www.nature.com/articles/nature21056)

[Discrepancy Ratio: Evaluating Model Performance When Even Experts Disagree on the Truth](https://openreview.net/forum?id=Byg-wJSYDS)

[Explanation by Progressive Exaggeration](https://openreview.net/pdf?id=H1xFWgrFPS)


[Overview of Deep Learning in Medical Imaging](https://arxiv.org/pdf/1702.05747.pdf)

[On the Automatic Generation of Medical Imaging Reports](https://arxiv.org/abs/1711.08195)

[OBELISK - One Kernel to Solve Nearly Everything: Unified 3D Binary Convolutions for Image Analysis](https://openreview.net/forum?id=BkZu9wooz)

[PGANs: Personalized Generative Adversarial Networks for ECG Generation to improve Patient-Specific Deep ECG Classification](http://www.kiraradinsky.com/files/pgans-personalized-generative.pdf)

[Hybrid Retrieval-Generation Reinforced Agent for Medical Image Report Generation](https://arxiv.org/abs/1805.08298)


[Recurrent Registration Neural Networks for Deformable Image Registration](https://arxiv.org/abs/1906.09988)

[Robust breast cancer detection in mammography and digital breast tomosynthesis using annotation-efficient deep learning approach](https://arxiv.org/abs/1912.11027)

[Transfusion: Understanding Transfer Learning for Medical Imaging](http://arxiv.org/abs/1902.07208)

[Towards Deep Cellular Phenotyping in Placental Histology](https://arxiv.org/pdf/1804.03270.pdf)



### Blogs, blog posts, and reddit discussions

[Luke Oakden Rayner's blog](https://lukeoakdenrayner.wordpress.com)

[A case study of text annotation for medical imaging - LightTag](https://lighttag.io/blog/embrace-the-noise/)

### Conferences and Workshops

[Deep learning for healthcare video series MIT](https://www.youtube.com/watch?v=k0LacC4hyY8&list=PLdPz9_rcdD97b3iExKYmla8vjlsc_k1ee&index=5)

[Harvard Digital Doctor Symposium](https://youtu.be/CiqYtZWBXqE)

[Medical Imaging with deep learning MIDL](https://sites.google.com/view/midl)

[Medical Imaging meets NIPS](https://sites.google.com/view/med-nips-2017)

[Medical Imaging Summer School 2014](http://iplab.dmi.unict.it/miss14/)

[Medical Image Computing and Computer Assisted Intervention](http://www.miccai2017.org)

[Machine Learning in Medical Imaging](http://mlmi2016.web.unc.edu)

[SIM Conference on Machine Intelligence in Medical Imaging](http://siim.org/page/2017CMIMI)

[CVPR 2018 Medical Imaging Workshop](https://sites.google.com/site/cvprmcv18/)

### Research Groups
[Imperial University](https://biomedia.doc.ic.ac.uk)

[Images Science Institute at Utrecht](https://www.isi.uu.nl/Research/Publications/index.html)

### Competitions

[Digital Mammography Recall Challenge](https://www.synapse.org/#!Synapse:syn4224222)

[Kaggle 2017 Data Science Bowl-Lung diagnosis](https://www.kaggle.com/c/data-science-bowl-2017)

[NIPS 2018 Prothestics Challenge](https://www.crowdai.org/challenges/nips-2018-ai-for-prosthetics-challenge)

LUNA 16

[Kaggle 2016 Data Science Bowl-Measuring ejection fraction](https://www.kaggle.com/c/second-annual-data-science-bowl#description)

### Videos
[Learning to read deep learning papers -i.e. dicussion of ChexNet by Stanford](https://www.youtube.com/watch?v=xoUpKjxbeC0&t=2s)



### Datasets
[CheX-Ray14](https://nihcc.app.box.com/v/ChestXray-NIHCC)


### Code Repositories

### Tools
[DeepInfer](http://www.deepinfer.org)

### Other
[Medical Image Analysis Network (UK)](https://www.median.ac.uk/network)


## Hospital Operations (i.e. OR Utilization, Scheduling, Discharge planning, HAIs, EMRs...)

[Attend and Diagnose](https://arxiv.org/pdf/1711.03905.pdf)

[Adversarial Learning of Privacy-Preserving Text Representations for De-Identification of Medical Records](https://arxiv.org/abs/1906.05000)

[Detecting Hospital Acquired Infections with SVMs](http://journals.sagepub.com/doi/full/10.1177/1460458216656471)

[Deep EHR: a survey of recent deep learning techniques for EHR analysis](https://arxiv.org/pdf/1706.03446.pdf)

[Emergency Department Online Patient-Caregiver Scheduling](https://ojs.aaai.org//index.php/AAAI/article/view/3745)

[Few-Shot and Zero-Shot Multi-Label Learning for Structured Label Spaces (focuses on ICD Coding)](https://aclanthology.org/D18-1352.pdf)

[Learning to predict post-hospitalization VTE risk from EHR data](http://europepmc.org/articles/pmc3540493)

[Multitask Learning and Benchmarking with Clinical Time Series Data](https://arxiv.org/abs/1703.07771)

[Machine-learning Algorithm to Predict Hypotension Based on High- delity Arterial Pressure Waveform Analysis](https://sci-hub.tw/10.1097/ALN.0000000000002300#)

[Privacy-Preserving Classification of Personal Text Messages with Secure Multi-Party Computation](https://arxiv.org/abs/1906.02325) 

[Smart Hospital Hand Hygiene (Stanford)](http://ai.stanford.edu/~syyeung/resources/vision_hand_hh_nipsmlhc.pdf)

[Unsupervised Domain Adaptation for Clinical Negation Detection](http://www.aclweb.org/anthology/W17-2320)

[Vision Based Prediction of ICU Mobility with RNNs](https://www.semanticscholar.org/paper/Vision-Based-Prediction-of-ICU-Mobility-Care-using-Bianconi-Mehra/db6cf1ac611668fb61921cd98b9fb14525b7c2a6)

## Signal processing, forecasting, and adverse event prediction


### Papers

[Analysing and Improving the Diagnosis of Ischaemic Heart Disease with Machine Learning](https://www.ncbi.nlm.nih.gov/pubmed/10225345) NIH Article

[Asthma Incidence Prediction with DNN](https://www.medrxiv.org/content/10.1101/19012161v1)

[Doctor AI: Predicting Clinical Events via Recurrent Neural Network](https://arxiv.org/abs/1511.05942)s published in MLR

[Cardiologist level classification of arrhythmia (Stanford)](https://arxiv.org/pdf/1707.01836.pdf) 

[Dynamic Bayesian Flu Forecasting](https://arxiv.org/abs/1708.09481)

[Deep Self Organization with application to ICU](https://openreview.net/pdf?id=rygjcsR9Y7)

[Interpretable AI for beat-to-beat cardiac function assessment](https://www.medrxiv.org/content/10.1101/19012419v2)

[GRU-ODE-Bayes: Continuous modeling of sporadically-observed time series](https://arxiv.org/pdf/1905.12374v1.pdf)

[Manifold-regression to predict from MEG/EEG brain signals without source modeling](https://arxiv.org/abs/1906.02687)

[U-Time: A Fully Convolutional Network for Time Series Segmentation Applied to Sleep Staging](https://arxiv.org/abs/1910.11162)

[Forecasting Treatment Responses Over Time Using Recurrent Marginal Structural Networks](https://github.com/sjblim/rmsn_nips_2018)


## Other and Multiple Categories


### Datasets

[Clinical Case Reports Dataset for machine comprehension](https://github.com/clips/clicr)

[HEAD-QA: A Healthcare Dataset for Complex Reasoning](https://arxiv.org/abs/1906.04701)

[NLP Datasets from i2b2](https://www.i2b2.org/NLP/DataSets/Main.php)

[EBM-NLP 5,000 richly annotated abstracts of medical articles](http://www.ccis.northeastern.edu/home/bennye/EBM-NLP/browse.html)

[EMR-Question and Answering Code](https://github.com/panushri25/emrQA)

[OncoKB](http://oncokb.org/)

[MeDAL: A large medical text dataset curated for abbreviation disambiguation](https://github.com/BruceWen120/medal)

[MIMIC - Medical Information Mart for Intensive Care - A large dataset by MIT and made available through Github] (https://mimic.mit.edu/)



### Conferences

[BioNLP Workshops](https://aclweb.org/aclwiki/BioNLP_Workshop)

[Clinical NLP](https://clinical-nlp.github.io/2019/index.html)

[Machine Learning for Healthcare Conference](http://mucmd.org)

[HealthTac](http://healtex.org/healtac-2019/)

[Trec Clinical Decision Support](http://www.trec-cds.org)

[Machine Learning for Healthcare 2018](https://www.mlforhc.org)

[2017 ICML Healthcare Related Talks](https://2017.icml.cc/Conferences/2017/Schedule?showParentSession=1379)

[ICML AI and Health Workshop](http://sots.brookes.ac.uk/~p0072382/ai4h2018/)

[Ninth Workshop on Health Text Mining at EMNLP](https://louhi2018.fbk.eu)

[NAACL 2019 On Tutorial Applications of Natural Language Processing in Clinical Research and Practice](https://www.aclweb.org/anthology/attachments/N19-5006.Presentation.pdf)

[Rework Healthcare 2018](https://www.re-work.co/events/deep-learning-health-boston-2018)



### Papers

[Active Learning for Decision-Making from Imbalanced Observational Data (application to personalized treatment](https://arxiv.org/pdf/1904.05268.pdf)

[Adversarial Attacks Against Medical Deep Learning Systems](https://arxiv.org/pdf/1804.05296.pdf)

[Annotating a Large Representative Corpus of Clinical Notes for Parts of Speech](https://www.researchgate.net/publication/301404639_Annotating_a_Large_Representative_Corpus_of_Clinical_Notes_for_Parts_of_Speech)

[Automated Medical Scribe for recording clinical encounters](http://aclweb.org/anthology/N18-5003)

[Deep Learning for Healthcare Review, Opportunities, Challenges](https://www.ncbi.nlm.nih.gov/pubmed/28481991) published Oxford Academic.

[Deep Neural Models for Medical Concept Normalization in User-Generated Texts](link coming)

[Direct Uncertainty Prediction for Medical Second Opinions](https://arxiv.org/abs/1807.01771)

[EMER-QA A large corpus for question answering on electronic medical records](https://arxiv.org/pdf/1809.00732.pdf)

[GAMENet: Graph Augmented MEmory Networks for Recommending Medication Combination](https://arxiv.org/abs/1809.01852)

[Leveraging uncertainty information from deep neural networks for disease detection](https://www.nature.com/articles/s41598-017-17876-z)

[Label-aware Double Transfer Learning for Cross-Specialty Medical Named Entity Recognition](http://aclweb.org/anthology/N18-1001)

[Machine Learning for Medical Diagnosis](https://dl.acm.org/citation.cfm?id=2306356) PSU article 2006

[MiME: Multilevel Medical Embedding of Electronic Health Records for Predictive Healthcare](https://nips.cc/Conferences/2018/Schedule?showEvent=11448)

[Novel Exploration Techniques (NETs) for Malaria Policy Interventions](https://arxiv.org/pdf/1712.00428.pdf)

[Opportunistic Learning: Budgeted Cost-Sensitive Learning from Data Streams with application to diabetes](https://openreview.net/pdf?id=S1eOHo09KX)

[Patient2Vec: A Personalized Interpretable Deep Representation of the Longitudinal Electronic Health Record](https://arxiv.org/abs/1810.04793)

[Towards Automating Healthcare Question Answering in a Noisy Multilingual Low-Resource Setting](https://www.aclweb.org/anthology/P19-1090)

[Learning Phenotypes and Dynamic Patient Representations via RNN Regularized Collective Non-negative Tensor Factorization](https://dmas.lab.mcgill.ca/fung/pub/YQCFP19aaai_postprint.pdf)

[Uncertainty-Aware Attention for Reliable Interpretation and Prediction](https://nips.cc/Conferences/2018/Schedule?showEvent=11112)

### Additional Natural Language Processing for Healthcare Tools

[BioBERT](https://github.com/dmis-lab/biobert)

[Clinical Named Entity Recognition system (CliNER)](https://github.com/text-machine-lab/CliNER)

[Clinical Text Analysis Knowledge Extraction System (cTAKES)](http://ctakes.apache.org/)


### Courses

[Machine Learning for Medicine MIT Course](https://mlhc17mit.github.io)


# Companies
Companies are arranged alphabetical order.
![Image of stratups](https://cbi-blog.s3.amazonaws.com/blog/wp-content/uploads/2017/01/healthcare_AI_map_2016_1.png)

[Benevolent AI](https://benevolent.ai)

[Camereyes](http://camereyes.com)

[Center Clinical Data Science Mass General](https://www.ccds.io)

[Deep Genomics](https://www.deepgenomics.com)

[Etiometry](http://www.etiometry.com)

[Heartflow](https://www.google.com/search?client=opera&q=heartflow&sourceid=opera&ie=UTF-8&oe=UTF-8)

[Hemonitor](https://www.hemonitor.co)

[Healthcare at Google](https://research.google.com/teams/brain/healthcare/)

[Insitrio](http://www.insitro.com)

[Path.AI](http://path.ai)

[RadAI](https://www.crunchbase.com/organization/radai)

[Recursion Pharmaceuticals](https://www.recursionpharma.com)

[Siemens AI Document](http://www.usa.siemens.com/pool/news_events/innovation-day/10_usinnoday2017_artificial_intelligence.pdf)
