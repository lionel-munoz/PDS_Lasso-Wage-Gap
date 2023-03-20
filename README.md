# Final Project for Computational Statistics Lecture | University of Bonn | Summer Semester 2022

You can see the Project [here](C:\Users\lione\Desktop\Uni\Master\Jobs\2023-2\For_github\PDS_Lasso-Wage_Gap).

This project explores the performance of the Post Double Selection (PDS) Lasso Methodology when analysing Wage Gaps. Here, the use of least squares regressions is widespread, but potentially biased. In such a case, practitioners need to decide what variables to use for a regression and therefore might undergo an Omitted Variable Bias. The PDS Lasso methodology of [Belloni et al. (2014a)](https://doi.org/10.1257/jep.28.2.29) and [Belloni et al. (2014b)](https://doi.org/10.1093/restud/rdt044) is designed to overcome such an issue in the context of treatment and structural effects. Arguably, Wage Gaps fall under this definition and thus the method becomes ideal for their analysis. 

In this project, I first design a Data Generating Process (DGP) that resembles an empirical setting where individuals belonging to a certain group are subject to a wage penalty. This DGP is designed to have the flexibility to mask the Wage Gap by other variables through randomly chosen interaction terms, to produce wages with different sparsity values and gaps by a chosen percentual difference. I then apply different methods, including the PDS Lasso, to see which method infers the true wage gap the best. The PDS Lasso does not yield the best results overall and I discuss why this might be the case in the specific setting I design. However, the most straightforward (and maybe overall) solution would be to implement the method together with the one proposed in [Chernozhukov et al. (2018)](https://doi.org/10.1111/ectj.12097). Nevertheless, this will remain a task for a future exercise. 

In a final step, I apply the PDS Lasso to Web Appendix data of [Rubinstein and Brenner (2013)](https://doi.org/10.1093/restud/rdt031) and demonstrate that statistical significances improve when in comparison to the OLS regression authors use. 

# References <a class="anchor" id="ref"></a>

* **Bach, P., Chernozhukov, V., Spindler, M. (2018a)**. *[Closing the U.S. Gender wage gap requires understanding its heterogeneity](https://doi.org/10.48550/arXiv.1812.04345)*.

* **Bach, P., Chernozhukov, V., Spindler, M. (2018b)**. *[Valid simultaneous inference in high-dimensional settings (with the hdm package for r)](https://doi.org/10.48550/arXiv.1809.04951)*.

* **Belloni, A., Chen, D., Chernozhukov, V., Hansen, C. (2012)**. *[Sparse models and methods for optimal instruments with an application to eminent domain](https://doi.org/10.3982/ECTA9626)*, Econometrica 80, 2369–2429.

* **Belloni, A., Chernozhukov, V., Hansen, C. (2014a)**. *[High-dimensional methods and inference on structural and treatment effects](hhttps://doi.org/10.1257/jep.28.2.29),Journal of Economic Perspectives 28, 29–50.

* **Belloni, A., Chernozhukov, V., Hansen, C. (2014b)** *[Inference on treatment effects after selection among high-dimensional controls](https://doi.org/10.1093/restud/rdt044), The Review of Economic Studies 81, 608–650.

* **Böheim, R., Stöllinger, P. (2020).** *[Decomposition of the gender wage gap using the LASSO estimator](https://doi.org/10.1080/13504851.2020.1782332)*, Applied Economics Letters 28, 817–828.

* **Bonaccolto-Töpfer, M., Briel, S. (2022)**. *[The gender pay gap revisited: Does machine learning offer new insights?](https://doi.org/10.1016/j.labeco.2022.102223)*, 31(2), Labour Economics 78.

* **Chernozhukov, V., Chetverikov, D., Demirer, M., Duflo, E., Hansen, C., Newey, W., Robins, J. (2018)**. *[Double/debiased machine learning for treatment and structural parameters](https://doi.org/10.1111/ectj.12097)*, The Econometrics Journal 21, 1–68.

* **Danquah, M., Iddrisu, A.M., Boakye, E.O., Owusu, S. (2021)**. *[Do gender wage differences within households influence womens empowerment and welfare? Evidence from ghana](https://doi.org/10.1016/j.jebo.2021.06.014)*, Journal of Economic Behavior and Organization 188, 916–932.

* **Rubinstein, Y., Brenner, D. (2013)**. *[Pride and prejudice: Using ethnic-sounding names and inter-ethnic marriages to identify labour market discrimination](https://doi.org/10.1093/restud/rdt031)*, The Review of Economic Studies 81, 389–425.

* **Spindler, M. (2015)**. *[Lasso for instrumental variable selection: A replication study](https://doi.org/10.1002/jae.2432)*, Journal of Applied Econometrics 31, 450–454.

* **Strittmatter, A., Wunsch, C. (2021)**. *[The gender pay gap revisited with big data: Do methodological choices matter?](https://doi.org/10.2139/ssrn.3798933)*, SSRN Electronic Journal.
