# X.-laevis-and-X.-gilli-introgression

We are using different methods to identify and quantify introgression between  *Xenopus laevis* and *X. gilli*: the 2 African clawed frogs are thought to hybridize in their contact zone in southwest Cape Province (South Africa) but no evidence of gene flow between the 2 species has been found.
In particular, we use MIMAR software from [Becquet and Przewroski (2007)](http://genome.cshlp.org/content/early/2007/08/21/gr.6409707.abstract?ck=nck). It is a Markov chain Monte Carlo method to estimate parameters of isolation-migration models. Some information of [how to make input files] () and [how to specify a model] () are given here. 
For our project, 4 cases are studied: 
- all the populations (after refered as all_XLXG) are considered together (*i.e.* east and west populations are included) of *X. gilli* and *X. laevis* (in the model we consider *X.gilli* as population 1 and *X. laevis* as population 2) 
- *X. gilli* (XG_only) populations (*i.e.* east, considered as population 1, and west populations, considered as population 2 are included) 
- West population (XLXG_west) of *X. gilli* and *X. laevis* (*X.gilli* as population 1 and *X. laevis* as population 2)
- East population (XLXG_east) of *X. gilli* and *X. laevis* (*X.gilli* as population 1 and *X. laevis* as population 2).</p></li>
For each of them we tried different models of migration and non-migration. Models with different and equal population sizes, with non-fixed and fixed time since the 2 populations, split were used. 
