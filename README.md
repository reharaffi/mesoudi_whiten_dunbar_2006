Data and reanalysis in R for Mesoudi, Whiten & Dunbar (2006) A bias for social information in human cultural transmission. _British Journal of Psychology_ 97, 405–423.

**mesoudi2006_exp1_data.csv** and **mesoudi2006_exp2_data.csv** contain data for Experiments 1 and 2 respectively. Participants (indexed in column 'participant') are in independent transmission chains (indexed in column 'chain') in which material is passed along linear generations (indexed in column 'generation'). Gender is coded as m=male and f=female, with all participants within a single chain the same gender. The 'material' column codes the type of material transmitted. Column 'correct_recall' contains the number of propositions in the original material that each participant recalled, while column 'total_recall' contains the total number of propositions whether in the original or invented somewhere along the chain.

**mesoudi2006_reanalysis.R** contains R code to recreate the figures and rerun the analyses. It uses multi-level regression models instead of mixed ANOVAs as in the original (these are equivalent, but regression is more standard these days). I also include a model comparison approach using AIC/BIC rather than p-values.

**Mesoudi_Whiten_Dunbar_BJP_2006.pdf** is a pdf of the original published study.
