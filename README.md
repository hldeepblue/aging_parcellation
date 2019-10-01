# Functional Parcellation of the Cerebral Cortex Across the Human Adult Lifespan
This package contains functional boundary & parcellation maps of the cerebral cortex for 5 age cohorts that span across the adult lifespan (20–93 years). Functional boundary maps depict locations where resting-state functional correlation (RSFC) patterns exhibit abrupt transitions across the cortical surface (RSFC boundary mapping). Parcellation maps depict putative functional areas (enclosed parcels) of the cerebral cortex derived from the boundary maps using image processing techniques. Details of the generation and evaluation of all maps are fully described in our manuscript (Han et al., Cerebral Cortex, 2018). Please cite this paper when incorporating these maps into your own work and presentations.

<img src="https://github.com/hldeepblue/aging_parcellation/blob/master/maps/pngs/figure3.png" width="850" height="528">


For additional information, please contact the corresponding author: Dr. Gagan S. Wig (gwig@utdallas.edu)

__Age cohorts:__
* Younger adults (YA)      20–34 y
* Middle early adults (ME) 35–49 y
* Middle late adults (ML)  50–64 y
* Older early adults (OE)  65–79 y
* Older late adults (OL)   80–93 y

__Files:__
* ./maps/parcel_community.xlsx - community assignments of the parcels
* ./maps/surface_map/\<AgeCohort>\_boundary\_32k\_fsLR\_\<hemisphere>.func.gii  - functional boundary map in 32k fs\_LR surface atlas
* ./maps/surface_map/\<AgeCohort>\_parcel\_32k\_fsLR\_\<hemisphere>.func.gii    - functional parcellation map in 32k fs\_LR surface atlas
* ./maps/volume_map/\<AgeCohort>\_parcel\_MNI\_\<voxelsize>mm.nii.gz            - functional parcellation map in MNI volume space

__Reference:__
* Han, L., Savalia, N. K., Chan, M. Y., Agres, P. F., Nair, A. S., & Wig, G. S. (2018). Functional Parcellation of the Cerebral Cortex Across the Human Adult Lifespan. Cerebral Cortex, 28(12), 4403–4423. https://doi.org/10.1093/cercor/bhy218
