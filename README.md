# StatisticalAnalysis4CDRsSurvey
Statistical Analysis Scripts used in CDRs survey analysis (appendix c)

contents
README: this file
DimensionsReductionSurvey2023_MCA_ALLVAR.ipynb : jupyter notebook for MCA on all variables
DimensionsReductionSurvey2023_orig-4diagram.ipynb : jupyter notebook for decision diagram
test_gower_pam_silhouetteNoNoneNOTWEIGHTED_ALLVAR.ipynb : jupyter notebook for pam tests
test_kmodes_elbow_NoNone_ALLVAR.ipynb : jupyter notebook for kmodes tests
test_kprototypes_elbowNoNone_ALLVAR.ipynb  : jupyter notebook for kprototypes tests
SurveyAnswers4ClusteringUpdated2023_ALLCATEGORICAL.csv :  input for DimensionsReductionSurvey2023_MCA_ALLVAR.ipynb and test_kmodes_elbow_NoNone_ALLVAR.ipynb
SurveyAnswers4ClusteringUpdated2023_apiguinumbers_flat5_mixedcategnumeric_diagramvariables.csv :  input for DimensionsReductionSurvey2023_orig-4diagram.ipynb
SurveyAnswers.csv : input for test_gower_pam_silhouetteNoNoneNOTWEIGHTED_ALLVAR.ipynb and test_kprototypes_elbowNoNone_ALLVAR.ipynb

Configuration used in tests
For python notebooks
Jupyter Notebook version 6.03
Python 3.8.10
Numpy 1.23.0
Pandas 1.3.2
Prince 0.7.1
matplotlib==3.4.3
matplotlib-inline==0.1.6
plotly==5.4.0
scikit-learn==0.24.2
scikit-learn-extra==0.2.0
gower==0.0.5
scipy==1.10.0
kmodes==0.11.0
chart-studio==1.1.0

# Acknowledgments
This work has been partially funded by the following sources:
<ul>
<li>    the “Total Patient Management” (ToPMa) project (grant by the Sardinian Regional Authority, grant number RC_CRP_077);</li>
<li>    the “Processing, Analysis, Exploration, and Sharing of Big and/or Complex Data” (XDATA) project (grant by the Sardinian Regional Authority);</li>
<li>    the “Piattaforma avanzata per Analisi massiva e Medicina digitale” project (grant by Sardegna Ricerche, ex art 9 L.R. 20/2015-year 2020).</li>
<li>    the “Pathology in Automated Traceable Healthcare” (PATH) project (grant by the Italian Ministry of Education, University and Research. grant number PON04a2_0055).</li>
</ul>
