---
title: "Publications"
weight: 3
header_menu: true
---
&nbsp;

#### Dealing with Small Datasets for Deep Learning in Medical Imaging: An Evaluation of Self-Supervised Pre-Training on CT Scans Comparing Contrastive and Masked Autoencoder Methods for Convolutional Models

![Example image](/images/Wolf_SparK_PreTrain.png)


&nbsp;

##### Abstract
Deep learning in medical imaging has the potential to minimize the risk of diagnostic errors, reduce radiologist workload, and accelerate diagnosis. Training such deep learning models requires large and accurate datasets, with annotations for all training samples. However, in the medical imaging domain, annotated datasets for specific tasks are often small due to the high complexity of annotations, limited access, or the rarity of diseases. To address this challenge, deep learning models can be pre-trained on large image datasets without annotations using methods from the field of self-supervised learning. After pre-training, small annotated datasets are sufficient to fine-tune the models for a specific task. The most popular self-supervised pre-training approaches in medical imaging are based on contrastive learning. However, recent studies in natural image processing indicate a strong potential for masked autoencoder approaches. Our work compares state-of-the-art contrastive learning methods with the recently introduced masked autoencoder approach "SparK" for convolutional neural networks (CNNs) on medical images. Therefore we pre-train on a large unannotated CT image dataset and fine-tune on several CT classification tasks. Due to the challenge of obtaining sufficient annotated training data in medical imaging, it is of particular interest to evaluate how the self-supervised pre-training methods perform when fine-tuning on small datasets. By experimenting with gradually reducing the training dataset size for fine-tuning, we find that the reduction has different effects depending on the type of pre-training chosen. The SparK pre-training method is more robust to the training dataset size than the contrastive methods. Based on our results, we propose the SparK pre-training for medical imaging tasks with only small annotated datasets.

&nbsp;

##### Reference
<cite id="Wolf_PreTrain">Wolf, D., Payer, T., Lisson, C. S., Lisson, C. G., Beer, M., Ropinski, T., & Götz, M.. Dealing with Small Annotated Datasets for Deep Learning in Medical Imaging: An Evaluation of Self-Supervised Pre-Training on CT Scans Comparing Contrastive and Masked Autoencoder Methods for Convolutional Models.. <em>arXiv preprint</em>. 2023.</cite>
[Link](https://arxiv.org/abs/2308.06534)

---

#### Medical volume segmentation by overfitting sparsely annotated data

![Example image](/images/Tristan_2023_Seg.png)


&nbsp;

##### Abstract
Purpose:
Semantic segmentation is one of the most significant tasks in medical image computing, whereby deep neural networks have shown great success. Unfortunately, supervised approaches are very data-intensive, and obtaining reliable annotations is time-consuming and expensive. Sparsely labeled approaches, such as bounding boxes, have shown some success in reducing the annotation time. However, in 3D volume data, each slice must still be manually labeled.

Approach:
We evaluate approaches that reduce the annotation effort by reducing the number of slices that need to be labeled in a 3D volume. In a two-step process, a similarity metric is used to select slices that should be annotated by a trained radiologist. In the second step, a predictor is used to predict the segmentation mask for the rest of the slices. We evaluate different combinations of selectors and predictors on medical CT and MRI volumes. Thus we can determine that combination works best, and how far slice annotations can be reduced.

Results:
Our results show that for instance for the Medical Segmentation Decathlon—heart dataset, some selector, and predictor combinations allow for a Dice score 0.969 when only annotating 20% of slices per volume. Experiments on other datasets show a similarly positive trend.

Conclusions:
We evaluate a method that supports experts during the labeling of 3D medical volumes. Our approach makes it possible to drastically reduce the number of slices that need to be manually labeled. We present a recommendation in which selector predictor combination to use for different tasks and goals.
&nbsp;

##### Reference
<cite id="Payer_2023">Payer, T., Nizamani, F., Beer, M., Götz, M., & Ropinski, T.. Medical volume segmentation by overfitting sparsely annotated data. <em>SPEE Journal of Medical Imaging</em>. 2023.</cite>
[Link](https://www.spiedigitallibrary.org/journals/journal-of-medical-imaging/volume-10/issue-4/044007/Medical-volume-segmentation-by-overfitting-sparsely-annotated-data/10.1117/1.JMI.10.4.044007.short)


---

#### Artificial intelligence in radiology – beyond the black box

![Example image](/images/Gallee_RöFo_2023.png)


&nbsp;

##### Abstract
Background:Artificial intelligence is playing an increasingly important role in radiology. However, more and more often it is no longer possible to reconstruct decisions, especially in the case of new and powerful methods from the field of deep learning. The resulting models fulfill their function without the users being able to understand the internal processes and are used as so-called black boxes. Especially in sensitive areas such as medicine, the explainability of decisions is of paramount importance in order to verify their correctness and to be able to evaluate alternatives. For this reason, there is active research going on to elucidate these black boxes.

Method: This review paper presents different approaches for explainable artificial intelligence with their advantages and disadvantages. Examples are used to illustrate the introduced methods. This study is intended to enable the reader to better assess the limitations of the corresponding explanations when meeting them in practice and strengthen the integration of such solutions in new research projects.

Results and Conclusion: Besides methods to analyze black-box models for explainability, interpretable models offer an interesting alternative. Here, explainability is part of the process and the learned model knowledge can be verified with expert knowledge.

Key Points:

- The use of artificial intelligence in radiology offers many possibilities to provide safer and more efficient medical care. This includes, but is not limited to support during image acquisition and processing or for diagnosis.

- Complex models can achieve high accuracy, but make it difficult to understand data processing.

- If the explainability is already taken into account during the planning of the model, methods can be developed that are powerful and interpretable at the same time.

&nbsp;

##### Reference
<cite id="Gallee">Gallée L., Kniesel H., Ropinski T., Götz M.. Artificial intelligence in radiology – beyond the black box. <em>RöFo</em>. 2023.</cite>
[Link](https://www.thieme-connect.com/products/ejournals/html/10.1055/a-2076-6736)

---
&nbsp;

#### CT Radiomics and Clinical Feature Model to Predict Lymph Node Metastases in Early-Stage Testicular Cancer

![Example image](/images/CathiTirdPaper.png)


&nbsp;

##### Abstract
Accurate retroperitoneal lymph node metastasis (LNM) prediction in early-stage testicular germ cell tumours (TGCT) harbours the potential to significantly reduce over- or undertreatment and treatment-related morbidity in this group of young patients as an important survivorship imperative. We investigated the role of computed tomography (CT) radiomics models integrating clinical predictors for the individualized prediction of LNM in early-stage TGCT. Ninety-one patients with surgically proven testicular germ cell tumours and contrast-enhanced CT were included in this retrospective study. Dedicated radiomics software was used to segment 273 retroperitoneal lymph nodes and extract features. After feature selection, radiomics-based machine learning models were developed to predict LN metastasis. The robustness of the procedure was controlled by 10-fold cross-validation. Using multivariable logistic regression modelling, we developed three prediction models: A radiomics-only model, a clinical-only model and a combined radiomics-clinical model. The models' performance was evaluated using the area under the receiver operating characteristic curve (AUC). Finally, decision curve analysis was performed to estimate the clinical usefulness of the predictive model. The radiomics-only model for predicting lymph node metastasis reached a greater discrimination power than the clinical-only model, with an AUC of 0.84 (± 0.17; 95% CI ) vs 0.60 (± 0.22; 95% CI) in our study cohort. The combined model integrating clinical risk factors and selected radiomics features outperformed the clinical-only and the radiomics-only prediction models and showed good discrimination with an area under the curve of 0.94 ( ± 0.10; 95% CI). The decision curve analysis demonstrated the clinical usefulness of our proposed combined model. The presented combined CT-based radiomics-clinical model represents an exciting non-invasive prediction tool for individualized prediction of LN metastasis in testicular germ cell tumours. Multi-centre validation is required to generate high-quality evidence for its clinical application.

&nbsp;

##### Reference
<cite id="Lisson">Lisson, C. S., Manoj, S., Wolf, D., Schrader, J., Schmidt, S. A., Beer, M., ... & Lisson, C. G.. CT Radiomics and Clinical Feature Model to Predict Lymph Node Metastases in Early-Stage Testicular Cancer. <em>Onco</em>. 2023.</cite>
[Link](https://www.mdpi.com/2673-7523/3/2/6)

---
&nbsp;

#### Weakly Supervised Learning with Positive and Unlabeled Data for Automatic Brain Tumor Segmentation

![Example image](/images/applsci-12-10763-g001.png)


&nbsp;

##### Abstract
A major obstacle to the learning-based segmentation of healthy and tumorous brain tissue is the requirement of having to create a fully labeled training dataset. Obtaining these data requires tedious and error-prone manual labeling with respect to both tumor and non-tumor areas. To mitigate this problem, we propose a new method to obtain high-quality classifiers from a dataset with only small parts of labeled tumor areas. This is achieved by using positive and unlabeled learning in conjunction with a domain adaptation technique. The proposed approach leverages the tumor volume, and we show that it can be either derived with simple measures or completely automatic with a proposed estimation method. While learning from sparse samples allows reducing the necessary annotation time from 4 h to 5 min, we show that the proposed approach further reduces the necessary annotation by roughly 50% while maintaining comparative accuracies compared to traditionally trained classifiers with this approach.

&nbsp;

##### Reference
<cite id="Wolf">Wolf, D., Regnery, S., Tarnawski, R., Bobek-Billewicz, B., Polańska, J., & Götz, M.. Weakly Supervised Learning with Positive and Unlabeled Data for Automatic Brain Tumor Segmentation. <em>Applied Sciences</em>. 2022.</cite>
[Link](https://www.mdpi.com/2076-3417/12/21/10763)

---

&nbsp;

#### Deep Neural Networks and Machine Learning Radiomics Modelling for Prediction of Relapse in Mantle Cell Lymphoma

![Example image](/images/CathiPaper1.png)

![Example image](/images/Cathipaper2.png)

&nbsp;

##### Abstract
Mantle cell lymphoma (MCL) is a rare lymphoid malignancy with a poor prognosis characterised by frequent relapse and short durations of treatment response. Most patients present with aggressive disease, but there exist indolent subtypes without the need for immediate intervention. The very heterogeneous behaviour of MCL is genetically characterised by the translocation t(11;14)(q13;q32), leading to Cyclin D1 overexpression with distinct clinical and biological characteristics and outcomes. There is still an unfulfilled need for precise MCL prognostication in real-time. Machine learning and deep learning neural networks are rapidly advancing technologies with promising results in numerous fields of application. This study develops and compares the performance of deep learning (DL) algorithms and radiomics-based machine learning (ML) models to predict MCL relapse on baseline CT scans. Five classification algorithms were used, including three deep learning models (3D SEResNet50, 3D DenseNet, and an optimised 3D CNN) and two machine learning models based on K-nearest Neighbor (KNN) and Random Forest (RF). The best performing method, our optimised 3D CNN, predicted MCL relapse with a 70% accuracy, better than the 3D SEResNet50 (62%) and the 3D DenseNet (59%). The second-best performing method was the KNN-based machine learning model (64%) after principal component analysis for improved accuracy. Our optimised CNN developed by ourselves correctly predicted MCL relapse in 70% of the patients on baseline CT imaging. Once prospectively tested in clinical trials with a larger sample size, our proposed 3D deep learning model could facilitate clinical management by precision imaging in MCL.

&nbsp;

##### Reference
<cite id="Lisson">Lisson, C. S., Lisson, C. G., Mezger, M. F., Wolf, D., Schmidt, S. A., Thaiss, W., Tausch, E., Beer A. J., Stilgenbauer, S., Beer, M., Goetz, M.. Deep Neural Networks and Machine Learning Radiomics Modelling for Prediction of Relapse in Mantle Cell Lymphoma. <em>Cancers</em>. 2022.</cite>
[Link](https://www.mdpi.com/2072-6694/14/8/2008)

---


#### Longitudinal CT Imaging to Explore the Predictive Power of 3D Radiomic Tumour Heterogeneity in Precise Imaging of Mantle Cell Lymphoma (MCL)

![Example image](/images/CathiPaper3.png)

&nbsp;

##### Abstract
The study’s primary aim is to evaluate the predictive performance of CT-derived 3D radiomics for MCL risk stratification. The secondary objective is to search for radiomic features associated with sustained remission. Included were 70 patients: 31 MCL patients and 39 control subjects with normal axillary lymph nodes followed over five years. Radiomic analysis of all targets (n = 745) was performed and features selected using the Mann Whitney U test; the discriminative power of identifying “high-risk MCL” was evaluated by receiver operating characteristics (ROC). The four radiomic features, “Uniformity”, “Entropy”, “Skewness” and “Difference Entropy” showed predictive significance for relapse (p < 0.05)—in contrast to the routine size measurements, which showed no relevant difference. The best prognostication for relapse achieved the feature “Uniformity” (AUC-ROC-curve 0.87; optimal cut-off ≤0.0159 to predict relapse with 87% sensitivity, 65% specificity, 69% accuracy). Several radiomic features, including the parameter “Short Axis,” were associated with sustained remission. CT-derived 3D radiomics improves the predictive estimation of MCL patients; in combination with the ability to identify potential radiomic features that are characteristic for sustained remission, it may assist physicians in the clinical management of MCL.

&nbsp;

##### Reference
<cite id="Lisson2">Lisson, C. S., Lisson, C. G., Achilles, S., Mezger, M. F., Wolf, D., Schmidt, S. A, Thaiss, W., Johannes, B., Beer A. J., Stilgenbauer, S., Beer, M., Goetz, M.. Longitudinal CT Imaging to Explore the Predictive Power of 3D Radiomic Tumour Heterogeneity in Precise Imaging of Mantle Cell Lymphoma (MCL). <em>Cancers</em>. 2022.</cite>
[Link](https://www.mdpi.com/2072-6694/14/2/393)


