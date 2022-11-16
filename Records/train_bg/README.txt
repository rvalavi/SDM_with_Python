README file for .csv files of background locations
These files are part of the data publication: Elith, J., Graham, C.H., Valavi, R., Abegg, M., Bruce, C., Ferrier, S., Ford, A., Guisan, A., Hijmans, R.J., Huettmann, F., Lohmann, L.G., Loiselle, B.A., Moritz, C., Overton, J.McC., Peterson, A.T., Phillips, S., Richardson, K., Williams, S., Wiser, S.K., Wohlgemuth, T. & Zimmermann, N.E. (2020) Presence-only and presence-absence data for comparing species distribution modeling methods. Biodiversity Informatics 15:69-80.

These files all have a structure matched to the PO species data files found in /train_po 
See the metadata files in that folder, for explanation of the meanings of each column. 

The only variations to details are:
Variable_name: occ - in the background (bg) files, occ is filled with zeros, which is what is expected in most modelling methods
Variable_name: group - for all regions, group is filled with NAÕs. For all regions, including those with more than one biological group, the same background file can be used for all species. 

