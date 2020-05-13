## Mouse lifespan synaptome project

Created by Zhen Qiu


### Introduction
Matlab code to generate figures of the our recent submisson to Science  for the manuscript 'Cizeron, M.*, Qiu, Z.*, Koniaris, B., Gokhale, R., Komiyama, N., Fransén, E., Grant, S.G.N. (2020). A brain-wide atlas of synapses across the mouse lifespan. (* Equal contribution)'.  



### License
The code  is licensed  under the MIT License (refer to the LICENSE file for details).


### Prerequisites
1. Mathworks Matlab 2014b or above
2. export_fig: A MATLAB toolbox for exporting publication quality figures https://github.com/altmany/export_fig
3. Matlab Toolbox for Bayesian Estimation (MBE) https://github.com/NilsWinter/matlab-bayesian-estimation


### Descriptions
#### 1. compare_3Mto18M_full_parameter
Matlab code to geneate Figure. 1C: compare the puncta parameters of 3M with that of 18M in 109 brain regions, 
#### 2. compare_3Mto18M_subtypes
Matlab code to geneate Figure. S13: compare the puncta subtype densities of 37 sbutypes between 3M with that of 18M in 109 brain regions, 
#### 3. compare_hypersimi_2Wto3M_2Wto18M 
matlab code to test (Figure S19) if the 18M, in contrast to 3M, is more similart to 2W. (18M2W V.S. 3M2W). THis was done by using the hypersimilarity matrix Figure 3C
#### 4. compare_hypersimi_2Wto3M_2Wto18M_HPF
matlab code to test (Figure S19) if the 18M in Hippocampal formation, in contrast to 3M, is more similart to 2W. (18M2W V.S. 3M2W). THis was done by using the hypersimilarity matrix Figure 3D
#### 5. permutation_test_simi_ratio, permutation_test_simi_ratio_time, permutation_test_simi_ratio_spacetime, 
permutation test figure 3A and S16 to test the significance of the similarity ratio. Firstly permute the regions  in space for each age group, then permute different age groups of the same region for time, finally permute the hyper-similarity matrix figure 3D in both space and time
#### 6. plot_heatmap_trajectories_full_parameters
matlab code to plot the heatmap(Figure S5) of trajectories of PSD95 and SAP102 parameters 
#### 7. plot_class_heatmap
matlab code to plot the heat maps (Figures 2A-C, S9-11)of 3 types and 37 subtypes on 12 brain regions
#### 8. plot_diversity_lifespan
matlab code to plot the diversity lifespan trajectories (Figure 2F) on 12 brain regions
#### 9. plot_diversity_lifespan_unsupervised
matlab code to  plot the unsupervised diversity brain maps (Figures 2G, S15)
#### 10. plot_correlation_classpercent_simiratio
matlab code to plot the correlation (Figure S20)between lifespan trajectories of synapse subtype percentage and similarity ratio in brain  regions 
#### 11. plot_hypersimi_matrix
matlab code to plot the hyper similarity matrix (Figures 3C and S18)for the whole section
#### 12. plot_hypersimi_matrix_HPF
matlab code to plot the hyper similarity matrix of hippocampal formation (Figures 3D)
#### 13. plot_ratio_withintobetweenregion
matlab code to calculat and plot the similarity ratio lifespan trajectories (Figure 3B)
#### 14. plot_ratio_withintobetweenregion_per_region.m
matlab code to calculat and plot the similarity ratio lifespan trajectories in 12 brain regions (Figure S17 )


###References

Cizeron, M.*, Qiu, Z.*, Koniaris, B., Gokhale, R., Komiyama, N., Fransén, E., Grant, S.G.N. (2020). A brain-wide atlas of synapses across the mouse lifespan. (* Equal contribution) Submitted to Science
