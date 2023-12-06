# Exploring the Cognitive Effects of Ambiguity in Process Models
This online appendix includes the supplementary material referenced in the article "Exploring the Cognitive Effects of Ambiguity in Process Models", submitted to CAiSE'24.

## Contents
 * [Analysis](https://github.com/aminobest/Caise24ProcessModelAmbiguity/tree/main/Analysis)
This folder contains the Python Notebook used for analyzing the eye-tracking data collected in the study, and the process maps that illustrate the visual behavior of the study participants while solving the tasks.
	 * [Analysis-CAiSE2024.ipynb](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Analysis/Analysis-CAiSE2024.ipynb): the Python Notebook.
	 * [processMaps](https://github.com/aminobest/Caise24ProcessModelAmbiguity/tree/main/Analysis/processMaps): folder with all process maps in .png format. Within the folder, the files are named *task\$XX\$\$amb\$_ambiguous-subProcess\_\$participantID\$-withinTab.png*, where *XX* is the task id, *amb* is whether the sub-process is ambigious or not, and *participantID* is the ID of the participant.

* [Process_models](https://github.com/aminobest/Caise24ProcessModelAmbiguity/tree/main/Process_models)
This folder contains all the BPMN process models used in the experiment, which have been generated using Camunda Modeler v8. The folder is further divided into sub-folders, one per task in the experiment. Within each task sub-folder, four .bpmn files can be found: one for the main process containing three sub-processes, and one for each of the three sub-processes. The task sub-folder names follow the same convention used for the prefix of the process maps file names, i.e., *task\$XX\$\$amb\$*.

* [Experiment_procedure_BPMN_diagram.pdf](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Experiment_procedure_BPMN_diagram.pdf)
This document contains a BPMN collaboration diagram detailing the experiment procedure.

* [Participants_demographics.xlsx](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Participants_demographics.xlsx "Participants_demographics.xlsx")
This document contains a table reporting the demographic data of the study participants.

* [Process_maps.pdf](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Process_maps.pdf "Process_maps.pdf")
This document contains a higher resolution version of the figure shown in the article (Figure 4) with two exemplary process maps illustrating the visual behavior of one participant while solving the task on sub-process models without and with ambiguity.

* [Process_models_complexity_metrics.xlsx](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Process_models_complexity_metrics.xlsx "Process_models_complexity_metrics.xlsx")
This document contains a detailed report on the values of all 17 process complexity metrics for all sub-process models used in the study. It also includes notes motivating certain values deviations, which are due to specific ambiguities introduced in the models. Additionally, it includes a link to the R package used to compute the metrics and the corresponding documentation.

* [Tasks_and_guidelines_violations.pdf](https://github.com/aminobest/Caise24ProcessModelAmbiguity/blob/main/Tasks_and_guidelines_violations.pdf "Tasks_and_guidelines_violations.pdf")
This document lists all the ambiguities introduced in the sub-process models, explaining them, and indicating the corresponding guidelines violations.
