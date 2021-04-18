# Instances for Multi-Person Pose Estimation Problem

Folder containing the datasets for the Multi-Person Pose Estimation Problem (MPPEP) that were considered in the paper "Costa, Luciano; Contardo, Claudio; Desaulniers, Guy; Yarkony, Julian. Stabilized column generation via the dynamic separation of aggregated rows" accepted to be published in INFORM Journal on Computing. The datasets have been proposed by Andriluka et al. (2014) but were made available in this repository for the convenience of the reader.

Each instance file is organized as follows:

1) At first, one presents the number (n) of detections considered in the instance.

2) Then, it follows n entries, where each line corresponds to the following information: id of detection, Body part number, and the cost to associate a detection to a person. Body part numbers are mapped to real body parts as follows: 1: neck, 2: head, 3: left-shoulder, 4: left-elbow, 5: left-wrist, 6: right-shoulder, 7: right-elbow, 8: right-wrist, 9: left-hip, 10: left-knee, 11: left-ankle, 12: right-hip, 13: right-knee, 14: right-ankle

3) List of tuples (detection 1, detection 2, cost), where each entry of the list indicates the cost of including two given detections in a common person.

4) Offset term: Indicate the offset to instance a person in the problem


### Reference

Andriluka,  M.; Pishchulin,  L.;  Gehler,  P. B.  S. (2014) 2D  human pose estimation:  New benchmark and state of the art analysis. Proc.  27th  Conference on  Computer  Vision and  Pattern  Recognition,  3686-3693 (Columbus, Ohio). 
