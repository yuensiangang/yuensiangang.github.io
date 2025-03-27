[About](/index.md) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Research](/tools.md) &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; [Publications](/publications.md)
 
### Current Projects
#### 1. Enhancing Adult Learning Through Metacognitive Training

In today’s fast-changing world, the ability to learn effectively and continuously is more important than ever. In this project, we are developing and validating a tech-augmented learning programme designed to strengthen metacognition — the capacity to understand, monitor and regulate one’s own thinking processes — in adult learners.

Bringing together insights from cognitive science, educational psychology and human-centred design, we are creating innovative digital tools that go beyond content delivery. These tools aim to cultivate the skills that make learning itself more effective, adaptive and lifelong. In close collaboration with educators and pedagogical experts, our goal is to redefine what adult education can look like: accessible, personalised and empowering — with a strong foundation in scientific rigour. Ultimately, we hope to unlock individual potential at scale and equip people to thrive in increasingly complex environments.

#### 2. Transforming Autism Screening Through Home-Based, Multimodal Assessment

Early identification of neurodevelopmental conditions like autism is critical, but access to timely screening remains a major global challenge. In this project, we are working with clinicians to co-develop a novel, multimodal autism screening and assessment tool designed for use in both home and clinical settings.

By leveraging advances in AI, behavioural science and digital phenotyping, our goal is to shift the first step of developmental surveillance from the clinic to the home — making it more flexible, scalable and family-centred. This approach has the potential to reduce missed or delayed diagnoses, lower the burden on healthcare systems and improve equity of access for families who might otherwise be left behind. Ultimately, we aim to empower caregivers, support clinicians and build a future where every child has the opportunity for timely appropriate support.

### Selected Tools & Previous Projects
#### Option Generation Task - Understanding how we initiate action
Loss of motivation is a core feature of many psychiatric and neurological disorders, often marked by difficulty in initiating behaviour without external prompting. Yet the cognitive mechanisms behind self-generated action remain poorly understood.

To address this, we developed the Option Generation Task — a behavioural paradigm designed to quantify how people spontaneously generate actions. Participants draw as many unique paths as possible between two points on a touchscreen within a time limit. Using a mathematical framework for measuring similarity between paths, the task yields objective metrics of Fluency (number of actions generated), Uniqueness (how distinct each option is relative to others) and Diversity (how varied a participant’s responses are).

This task provided the first causal evidence that dopamine modulates option generation in humans (Ang et al., Current Biology, 2018). Subsequent studies linked impaired option generation to clinical depression and dopaminergic activity in the putamen, and showed that modafinil may reduce the creativity of generated options (Ang et al., Brain, 2022). Our most recent work dived into the cognitive heuristics that drive the option generation process, revealing that our seemingly spontaneous acts are, in fact, guided by systematic and quantifiable strategies (Chen et al., in press). We have since developed a mobile app version (Android) and a web-based analysis platform, enabling scalable data collection and automated processing of task metrics.

#### Cognitive Motivation Task - Quantifying the willingness to invest mental effort
Motivational deficits can stem not just from emotional factors, but from altered cost-benefit decision-making — particularly around whether the effort is “worth it.”

The Cognitive Motivation Task measures how willing someone is to exert cognitive effort in pursuit of reward. Participants perform mental tasks with varying effort demands and rewards, while underlying motivational parameters are inferred using computational models. This task has been validated in both healthy adults and individuals with Major Depressive Disorder (Ang et al., Psychological Medicine, 2023), offering a quantitative window into individual differences in cognitive motivation. We have also developed a streamlined mobile version, successfully deployed in adolescents within the nationwide Growing Up in Singapore Towards Healthy Outcomes (GUSTO) longitudinal study (manuscript in preparation). 

#### Apathy Motivation Index (AMI) - A multidimensional self-report tool for assessing motivation
The AMI is a brief, validated self-report measure designed to assess apathy and motivation across three domains: behavioural activation, social engagement and emotional sensitivity.

Originally developed and validated in healthy and clinical populations (Ang et al., PLoS One, 2017), the AMI has shown robust psychometric properties and has been translated into multiple languages, including Chinese, Dutch and German. A caregiver-rated version has also been validated (Klar et al., Journal of Neuropsychology, 2022), expanding its use in developmental and clinical settings. The AMI is currently in use by over 20 research groups worldwide and is freely available for non-commercial research use with appropriate citation.

### Useful Code

* [Batch Dicom Convert](https://github.com/yuensiangang/scripts/blob/05230066dbca892e1e6fe09c1990347a973b4980/spm_job_dicom_convert.m). Batch converts all dicom files of interest to nifti format.  
* [Batch Preprocessing](https://github.com/yuensiangang/scripts/blob/05230066dbca892e1e6fe09c1990347a973b4980/spm_job_preprocessing_new_job.m). Batch preprocesses fMRI nifti files. The preprocessing pipeline involves realignment and unwarping, slice-timing correction, coregistration, segmentation, normalization and smoothing. 
* [Check Motion Parameters](https://github.com/yuensiangang/scripts/blob/05230066dbca892e1e6fe09c1990347a973b4980/script_check_motion.m). Plots the six motion parameters obtained from the preprocessing pipeline, allowing us to visualize movement for subjects and conduct QC.
* [SPM12 remove quarantine attribute on Mac](https://github.com/yuensiangang/scripts/blob/8757e795d2a5a8b4030e8262f13cbe51d8024f43/mac_remove_quarantine_attribute). The new macOS has a security feature that restricts the execution of applications and files from unidentified developers, resulting in errors when running SPM12 batch scripts. To resolve this, we need to recursively remove the quarantine attribute from all files in the SPM12 directory, allowing them to be opened without issues. 
* [PsychoPy Task](https://github.com/yuensiangang/scripts/blob/7497500ef86e635a178d1aafdfd05efbf5155393/task_template_DMS.py). Template for coding a cognitive task on PsychoPy, using the delayed match-to-sampling task as an example.
* [Create Grouped Plot with Errorbar](https://github.com/yuensiangang/scripts/blob/6e0463d26c6f18162e697d5c27e9853dfe30da4b/createGroupedBarPlot.m). It is surprisingly cumbersome to create a nice-looking group barplot with errorbars, so a simple script to handle that.
* [Morph Images](https://github.com/yuensiangang/scripts/blob/2cb53426c6be5e468a26af2cb9b006ebc636f215/morphImages.m). Script to mesh two (same-sized) images together.
* [Random Forest PDP](https://github.com/yuensiangang/scripts/blob/f2d7ab1f9f353a05a74edbfa2f89970f3e8e06f5/pdp_plot.m). Matlab function to generate the partial dependence plot of any variable in a trained random forest model (TreeBagger).
* [SMOTE](https://github.com/yuensiangang/scripts/blob/eb6ace61295442c1418125cfc6a5692edaf59bb4/smote.m). Function to implement SMOTE (Synthetic Minority Over-sampling Technique). Idea is to create new synthetic samples from the minority class in a dataset in order to address imbalances between classes in a dataset used for training machine learning models.
