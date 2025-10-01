# DSC 261 Fall 24 Projects

### Explainable AI Frameworks for Time-series in Healthcare - A Comparative Evaluation
Time-series interpretability in healthcare presents unique challenges in understanding how deep learning models derive predictions from sequential medical data. This study evaluates four key explainable
AI methodologies—backpropagation-based, perturbation-
based, and counterfactual-based techniques—to determine their effectiveness
for interpreting time-series models in healthcare. Through
comprehensive analysis using ECG and EEG datasets, we identify
the most suitable approaches for providing meaningful insights
in healthcare applications while maintaining model accuracy and
interpretability. Our evaluation encompasses multiple dimensions
including complexity, faithfulness, reliability, and counterfactual
analysis, providing a thorough framework for selecting appropriate
interpretability methods based on specific healthcare contexts and
requirements.

### Unveiling the Influence of Text Prompt Variations on CLIP’s Visual Understanding
This study explores the impact of text prompt variations on CLIP’s
visual understanding and classification accuracy. As a foundational
zero-shot classifier, CLIP aligns image and text representations,
but its sensitivity to subtle prompt changes raises concerns about
robustness and reliability. By systematically varying prompt phrasing, 
including contextual and hallucination-based descriptions, we
analyze their influence on object localization and attention alignment. 
Our methodology integrates GradCAM for visualization and
evaluates performance using metrics such as AUC-ROC, PR-AUC,
and IoU. Key findings reveal that enriched prompts enhance interpretability
and attention concentration, improving object isolation
in cluttered scenes. These results underscore the importance of
effective prompt design in advancing CLIP’s real-world applicability. 

### Investigating Score-Based Causal Discovery Methods for Manufacturing Systems
Causal discovery methods have advanced significantly, yet their
potential in manufacturing systems remains underutilized. This
project investigates the applicability and performance of score-
based causal discovery methods, including GES, NOTEARS, DAG-
GNN, and GOLEM, in manufacturing contexts. Using the causalAssembly dataset, a semisynthetic data generator grounded in real-world
manufacturing data, we benchmark these methods against traditional constraints-based and functional approaches. Our analysis evaluates their ability to uncover causal relationships in high-dimensional, noisy, and dynamic industrial data, focusing on key
metrics such as Structural Hamming Distance (SHD) and F1 score.
The results provide valuable insight into the strengths, limitations,
and practical applicability of causal discovery methods, guiding
their adaptation to tasks such as quality assurance, root cause analysis, and predictive maintenance in complex manufacturing environments.

###  Analysis and Improvements of CARL in Game-Based Reinforcement Learning
Reinforcement Learning (RL) and Causal Discovery (CD) are key areas in artificial intelligence. RL helps optimize decisions using
interaction data, while CD identifies cause-and-effect relationships.
The Causality Aware Reinforcement Learning (CARL) framework
combines these approaches to enhance decision-making and interpretability. This report reproduces the CARL framework, confirming its effectiveness in improving decision-making and model
performance across different scenarios.
The original CARL framework uses fixed exploration strategies
and simple causal models, which limit its adaptability in complex
environments. To address these issues, an enhancement called Dynamic Causal Exploration (DCE) is proposed. DCE adjusts explo-
ration based on the accuracy of causal models, aiming to improve
learning and adaptability.
While the original CARL framework was tested with two simulated tasks, the Coffee and Taxi environments, this report focuses
on reproducing these results and exploring the limitations. The
proposed DCE method remains theoretical and was not fully tested
in these tasks due to time constraints.

### Designing an Interactive Visualization Interface to Enhance Interpretability of AI Models for Non-Technical Stakeholders
This project aims to create an interactive visualization tool to enhance the interpretability of complex machine learning models for
non-technical stakeholders. Using local (LIME, SHAP) and global
interpretability methods, our tool will provide clear, interactive explanations for individual model predictions and overall feature importance, enabling users to explore how specific features influence
outcomes. This approach is designed to improve comprehension
and trust in AI systems, especially in high-stakes fields like healthcare and finance. Experimental metrics will assess the effectiveness
of different interpretability methods, contributing insights into the
usability of XAI tools for responsible AI practice.

### Concept-Labeled Neurons Reveal Bias in Vision CNNs
High performing deep neural networks in computer vision often
function as black boxes, making fairness and explainability challenging due to limited insight into their decision-making processes.
In this paper, we propose a method for bias detection in vision
networks by leveraging automatic concept labeling of neurons. We
present an approach to evaluate biases related to sensitive attributes
including race, gender, and age by analyzing how these attributes
are internally represented when predicting people’s professions
from images. Our method enables the identification of biases within
the model’s internal representations through explanations. Using
datasets such as IdenProf and Meta FACET, we demonstrate the effectiveness of our approach in detecting biases, providing valuable
insights that can lead to more equitable outcomes in real-world
applications.

### Explainable Adaptive Weight Tuning for Language Models
This project introduces Explainable Adaptive Weight Tuning (ExAWT), a framework designed to enhance the interpretability and
performance of the language models. The study applies two complementary approaches: fine-tuning a baseline BERT model, where
interpretability is evaluated using LIME, and implementing the ExAWT method, which utilizes gradient-based weighting to optimize
layer-specific contributions during fine-tuning. Both approaches are
evaluated on the BoolQ dataset from SuperGLUE, with the baseline
showcasing enhanced task-specific accuracy and interpretability
through explainability techniques, and the ExAWT method demonstrating efficiency and scalability by incorporating gradient insights
directly into the fine-tuning process. Together, these approaches
highlight innovative pathways for creating transparent, efficient,
and robust language models tailored to domain-specific applications.

### ECG Classification to Detect Congestive Heart Failure
Congestive Heart Failure (CHF) is a chronic condition in which the
heart’s ability to pump blood is compromised, leading to reduced
oxygen supply to vital organs. Early detection of CHF is critical
to improve patient outcomes and reduce healthcare costs. In this
project, we aim to reimplement the convolutional neural network
(CNN) approach for detecting congestive heart failure as outlined
in the paper "A convolutional neural network approach to detect
congestive heart failure." With no publicly available code, we will
reproduce the methodology by developing a CNN-based model that
processes electrocardiogram (ECG) signals to classify CHF. Our
focus will be on ensuring the model’s interpretability by employing
an Explainable AI technique called GradCAM to provide insights
into the factors driving predictions. This will enhance the model’s
transparency and potential clinical applicability, improving trust in
AI-assisted diagnostics.

### Revisiting MINE: Implementation and Adaptation for CI Testing
Conditional independence (CI) testing is a fundamental problem in
causal discovery, feature selection, machine learning and statistics,
and this is particularly challenging in high-dimensional settings. In
higher dimensions, there is increased data requirements and more
non-linear relationships and we cannot use simple tests like chi-
squared and t tests. Therefore, we use more complex sophisticated
approaches like Hilbert-Schmidt independence criterion (HSIC)
and Mutual information neural estimation (MINE). Here we have
tried to implement and identify the shortcomings of MINE
and tried to present a theoretical framework for modifying
MINE for conditional independence testing. Though the results
were not really convincing the theoretical framework behind is
expected to be foolproof.

