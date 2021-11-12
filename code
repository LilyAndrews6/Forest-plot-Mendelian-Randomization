install.packages("remotes")
remotes::install_github("MRCIEU/TwoSampleMR")

mr_res <- mr_single_SNP_effect #rename your file

#create a png file to save the forest plot
png(file='nongbm_forestplot.png', width=500, height=1400)

#alter the code to your specific requirements and run to produce forest plot
forest_plot_1_to_many(
  mr_res,
  b = "b",
  se = "se",
  TraitM = "exposure",
  col1_width = 1,
  col1_title = "gbm",
  exponentiate = FALSE,
  trans = "identity",
  ao_slc = FALSE
)
dev.off()
