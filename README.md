# Nextstrain Runs for the paper "Co-circulation of multiple enterovirus D68 subclades, including a novel B3 cluster, across Europe in a year of expected low prevalence"

This repository contains the Nextstrain augur pipeline output files which allow vizualisation of the result via the 'community' feature on Nextstrain. 

You can view the 300bp VP1 run here: [nextstrain.org/community/enterovirus-phylo/evd68-2019/vp1-300](https://nextstrain.org/community/enterovirus-phylo/evd68-2019/vp1-300).

You can view the whole manuscript [here](https://www.eurosurveillance.org/content/10.2807/1560-7917.ES.2020.25.2.1900749).

This analysis was created with sequences of EV-D68 sampled from across Europe in 2019, mainly during the Autumn. VP1 sequences from 2019 with >=300bp were included in a background of all publicly available VP1 sequences at least >=700bp. 

This was run with the Nextstrain augur Enterovirus D68 pipeline. You can see the current code [here](https://github.com/nextstrain/enterovirus_d68), and the frozen version (the exact version used to run this result) [here](https://github.com/nextstrain/enterovirus_d68/releases/tag/1.0).

---

Some 2019 sequences were only available at time of publication as VP4/VP2 fragments. In order to comment briefly on the clustering patterns of these samples, a VP4/VP2 build was created. This was done using the Nextstrain Enterovirus D68 pipeline for full-genome builds with a modification to align to and annotate with a EV-D68 reference that included only the VP4/VP2 genes. For full-genome samples, this means only the VP4/VP2 genes were used in this build. 

Apart from these 2019 VP4/VP2 samples, the build includes all publicly available full-genome EV-D68, all full-genome EV-D68 samples sequenced by Jan Albert's lab from 2018 (soon to be released publicly), and all samples from this 2019 paper with >=5,000bp.

You can view this build here: [nextstrain.org/community/enterovirus-phylo/evd68-2019/vp4vp2](https://nextstrain.org/community/enterovirus-phylo/evd68-2019/vp4vp2)

