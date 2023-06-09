# SAM Era: Can it Segment Any Industrial Surface Defects?
This repository contains a collection of research papers and benchmarking results for the task of industrial surface defect. To evaluate the applicability of SAM in real-world natural scenario, we select three representative and complex industrial surface defect detection scenarios, namely strip steel surface defects, tile surface defects, and rail surface defects, to evaluate the segmentation performance of SAM. 
•	Paper link: waiting
•	This project is under construction. If you would like to contribute to this repository, please submit a pull request.

# Background
The industrial surface defect detection task is an optimization task, which leads to the difficulty of obtaining large-scale defect data. At the same time, the high cost of labeling makes the supervised model difficult to implement in the real industrial environment. Therefore, we would like to explore the potential of SAM in industrial surface defect detection. We explore the segmentation capabilities of SAM compared with 13 state-of-the-art models in the field of industrial surface defect detection. We conduct a quantitative comparison and present visual results. The results show that SAM has limitations in industrial surface defect detection and performs averagely in industrial settings.  Furthermore, we believe that this provides an opportunity for further research into how SAM can be better applied to industrial surface defect detection tasks.
This letter makes two contributions:
1) This letter engages in discussions regarding the effect of the paradigm shift brought about by foundation models on the direction of defect detection. What's more, in light of the new era of SAM, we pioneer the analysis on how to use SAM to serve downstream defect detection tasks with the aim of providing insights and assistance to future researchers. 
2) To verify the performance of SAM, we conduct a series of experiments on three industrial benchmarks.  Experimental results show that SAM has a substantial gap in performance compared with state-of-the-art saliency detection methods.  However, some positive cases also illustrate the great potential of SAM for defect detection, which also proves that it is feasible to improve the model based on SAM.

# Qualitative Evaluation
The SAM test results on the industrial surface defect datasets are shown in the three folders above [NRSD-MN] [MT dataset] [SD900_dateset], and the following is only partially shown:

<img width="553" alt="R" src="https://github.com/VDT-2048/SAM-IS/assets/101933818/8c33d21b-7e60-4cde-840a-efa55863b57b">
