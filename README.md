# Awesome-Time-Series-Explainability with stars

A list of XAI for time series. This list focuses (currently) on Post-Hoc Explainability for time series data, including paper and github links. The list is expanded and updated gradually. Feel Free to update missing or new paper. <img src="https://github.com/fzi-forschungszentrum-informatik/TSInterpret/blob/main/docs/img/Post-Hoc.png" width="600"
/>

## Outline

* [Surveys](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Surveys) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Libraries ](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Libraries) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Classification ](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Classification) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Regression / Forecasting](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Regression-/-Forecasting) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Classification and Regression / Forcasting](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Classification-and-Regression-/-Forcasting) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Benchmarking and Evaluation](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Benchmarking-and-Evaluation) ⭐ 190 | 🐛 0 | 📅 2026-08-19
* [Ante-Hoc Explanations](https://github.com/JHoelli/Awesome-Time-Series-Explainability#Ante-Hoc-Explanation) ⭐ 190 | 🐛 0 | 📅 2026-08-19

## Surveys

* [**Explainable artificial intelligence (XAI) in finance: a systematic literature review**](https://link.springer.com/article/10.1007/s10462-024-10854-8) , (2024) by *Černevičienė, J., & Kabašinskas, A*
* [**A Survey of Explainable Artificial Intelligence (XAI) in Financial Time Series Forecasting**](https://arxiv.org/pdf/2407.15909) , (2024) by *Arsenault, P. D., Wang, S., & Patenande, J. M.*
* [**Post Hoc Explainability for Time Series Classification: Toward a signal processing perspective**](https://ieeexplore.ieee.org/document/9810094) , (2022) by *R. Mochaourab, A. Venkitaraman, I. Samsten, P. Papapetrou and C. R. Rojas*
* [**Explainable AI for time series classification: a review, taxonomy and research directions**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9895252) , (2022) by *A Theissler, F Spinnato, U Schlegel, R Guidotti*
* [**Explainable artificial intelligence (xai) on timeseries data: A survey**](https://arxiv.org/abs/2104.00950) , (2021) by *Rojat, T., Puget, R., Filliat, D., Del Ser, J., Gelin, R., & Díaz-Rodríguez, N.*
* [**XAI Methods for Neural Time Series Classification: A Brief Review**](https://arxiv.org/abs/2108.08009) , (2021) by *Simic, I., Sabol, V., Veas, E.*

## Libraries

* [**TSInterpret: A Python Package for the Interpretability of Time Series Classification**](https://joss.theoj.org/papers/10.21105/joss.05220.pdf) (2023) by *Höllig, J., Kulbach, C., & Thoma, S.* <https://github.com/fzi-forschungszentrum-informatik/TSInterpret> ⭐ 144 | 🐛 5 | 🌐 Python | 📅 2025-11-19, ![](https://img.shields.io/github/stars/fzi-forschungszentrum-informatik/TSInterpret.svg?style=social)
* [**Time Interpret: a Unified Model Interpretability Library for Time Series**](https://arxiv.org/abs/2306.02968) (2023) by *Enguehard, J.* <https://github.com/josephenguehard/time_interpret> ⭐ 72 | 🐛 2 | 🌐 Python | 📅 2026-05-18, ![](https://img.shields.io/github/stars/josephenguehard/time_interpret.svg?style=social)
* [**tslens: A PyTorch Toolkit for Interpreting Time-Series Deep Learning Models**](https://arxiv.org/abs/2412.04532) (2024) by *Islam, M. K., & Fox, J.* <https://github.com/khairulislam/tslens> ⭐ 13 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-25, ![](https://img.shields.io/github/stars/khairulislam/tslens.svg?style=social)
* [**TSGap: Composable time-series missingness simulation. Separates mechanisms (MCAR/MAR/MNAR) from patterns (pointwise/block/monotone/decay/markov)**](https://github.com/feruzoripov/tsgap) ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-08-25 (2025) by *Oripov, F.* <https://github.com/feruzoripov/tsgap> ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2026-08-25, ![](https://img.shields.io/github/stars/feruzoripov/tsgap.svg?style=social)

## Classification

### Feature Attribution

* [**Benchmarking Deep Learning Interpretability in Time Series Predictions**](https://arxiv.org/abs/2010.13924) (2020) by *Ismail, A. A., Gunady, M., Corrada Bravo, H., & Feizi, S.* <https://github.com/ayaabdelsalam91/TS-Interpretability-Benchmark> ⭐ 89 | 🐛 4 | 🌐 Python | 📅 2021-10-07, ![](https://img.shields.io/github/stars/ayaabdelsalam91/TS-Interpretability-Benchmark.svg?style=social)
* [**What went wrong and when? Instance-wise feature importance for time-series black-box models**](https://papers.nips.cc/paper_files/paper/2020/file/08fa43588c2571ade19bc0fa5936e028-Paper.pdf) (2020) by *Tonekaboni, S., Joshi, S., Campbell, K., Duvenaud, D. K., & Goldenberg, A.* <https://github.com/sanatonek/time_series_explainability> ⭐ 61 | 🐛 4 | 🌐 Python | 📅 2021-02-23, ![](https://img.shields.io/github/stars/sanatonek/time_series_explainability.svg?style=social)
* [**LIMESegment: Meaningful, Realistic Time Series Explanations**](https://proceedings.mlr.press/v151/sivill22a.html) , (2022) by *Sivill, T., & Flach, P.*, <https://github.com/TortySivill/LIMESegment> ⭐ 16 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-10-31, ![](https://img.shields.io/github/stars/TortySivill/LIMESegment.svg?style=social)
* [**Time is Not Enough: Time-Frequency based Explanation for
  Time-Series Black-Box Models**](https://arxiv.org/pdf/2408.03636), (2024), by \*Chung, H., Jo, S., Kwon, Y., & Choi, E. \* [https://github.com//gustmd0121/time\_is\_not\_enough](https://github.com/gustmd0121/time_is_not_enough) ⭐ 14 | 🐛 0 | 🌐 Python | 📅 2024-12-05, ![](https://img.shields.io/github/stars/gustmd0121/time_is_not_enough.svg?style=social)
* [**Class-Specific Explainability for Deep Time Series Classifiers**](https://arxiv.org/pdf/2210.05411.pdf) , (2022) by *Doddaiah, R., Parvatharaju, P., Rundensteiner, E., & Hartvigsen, T.*, <https://github.com/rameshdoddaiah/DEMUX> ⭐ 7 | 🐛 1 | 🌐 TypeScript | 📅 2023-05-21, ![](https://img.shields.io/github/stars/rameshdoddaiah/DEMUX.svg?style=social)
* [**timeXplain -- A Framework for Explaining the Predictions of Time Series Classifiers**](https://arxiv.org/abs/2007.07606) (2019) by *Mujkanovic, F., Doskoč, V., Schirneck, M., Schäfer, P., & Friedrich, T.* <https://github.com/LoadingByte/timeXplain> ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-11-21, ![](https://img.shields.io/github/stars/LoadingByte/timeXplain.svg?style=social)
* [**Translating Image XAI to Multivariate Time Series**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10439172), (2024), by *Tronchin, L., Cordelli, E., Celsi, L. R., Maccagnola, D., Natale, M., Soda, P., & Sicilia, R.* [https://github.com//ltronchin/translating-xai-mts](https://github.com/ltronchin/translating-xai-mts) ⭐ 3 | 🐛 0 | 🌐 Python | 📅 2023-11-25, ![](https://img.shields.io/github/stars/ltronchin/translating-xai-mts.svg?style=social)
* [**Explaining time series classifiers through meaningful perturbation and optimisation**](https://doi.org/10.1016/j.ins.2023.119334), (2023), by *H Meng, C Wagner, I Triguero* <https://github.com/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation> ⭐ 2 | 🐛 1 | 🌐 Python | 📅 2023-03-30, ![](https://img.shields.io/github/stars/menghan1994/ETSC_through_Meainingful_Perturbation_and_Optimisation.svg?style=social)
* [**Explainable AI for Time Series via Virtual Inspection Layers**](https://arxiv.org/pdf/2303.06365) , (2023) by *Vielhaben, J., Lapuschkin, S., Montavon, G., & Samek, W.*
* [**TSInsight: A local-global attribution framework for interpretability in time series data**](https://www.mdpi.com/1424-8220/21/21/7373)(2021) by *Siddiqui, S. A., Mercier, D., Dengel, A., & Ahmed, S.*
* [**Agnostic Local Explanation for Time Series Classification**](https://ieeexplore.ieee.org/document/8995349) (2019) by \*Guillemé, M., Masson, V., Rozé, L., & Termier, A. \*
* [**Tsxplain: Demystification of dnn decisions for time-series using natural language and statistical features**](https://link.springer.com/chapter/10.1007/978-3-030-30493-5_43) (2019) by *Munir, M., Siddiqui, S. A., Küsters, F., Mercier, D., Dengel, A., & Ahmed, S.*

### Counterfactuals

* [**Counterfactual explanations for multivariate time series**](https://ieeexplore.ieee.org/document/9462056) (2021) by *Ates, E., Aksar, B., Leung, V. J., & Coskun, A. K.* <https://github.com/peaclab/CoMTE> ⭐ 35 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2024-03-07, ![](https://img.shields.io/github/stars/peaclab/CoMTE.svg?style=social)
* [**Instance-based Counterfactual Explanations for Time Series Classification**](https://arxiv.org/abs/2009.13211) (2020) by *Delaney, E., Greene, D., & Keane, M. T.* <https://github.com/e-delaney/Instance-Based_CFE_TSC> ⭐ 22 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2021-06-24, ![](https://img.shields.io/github/stars/e-delaney/Instance-Based_CFE_TSC.svg?style=social)
* [**TSEvo: Evolutionary counterfactual explanations for time series classification**](https://ieeexplore.ieee.org/abstract/document/10069160) (2022) by *Höllig, J., Kulbach, C., & Thoma, S.* <https://github.com/JHoelli/TSEvo> ⭐ 15 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2022-12-22, ![](https://img.shields.io/github/stars/JHoelli/TSEvo.svg?style=social)
* [**Glacier: guided locally constrained counterfactual
  explanations for time series classification**](https://link.springer.com/content/pdf/10.1007/s10994-023-06502-x.pdf) (2024) by *Wang, Z., Samsten, I., Miliou, I., Mochaourab, R., & Papapetrou, P.* <https://github.com/zhendong3wang/learning-time-series-counterfactuals> ⭐ 12 | 🐛 0 | 🌐 Python | 📅 2024-03-15, ![](https://img.shields.io/github/stars/zhendong3wang/learning-time-series-counterfactuals.svg?style=social)
* [**Shapelet-Based Counterfactual Explanations for Multivariate Time Series**](https://arxiv.org/abs/2208.10462) (2022) by *Bahri, O., Boubrahimi, S. F., & Hamdi, S. M.* <https://github.com/omarbahri/SETS> ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2023-12-08, ![](https://img.shields.io/github/stars/omarbahri/SETS.svg?style=social)
* [**CELS: Counterfactual Explanations for Time Series Data via Learned Saliency Maps**](https://ieeexplore.ieee.org/abstract/document/10386229) (2023) by *Li, P., Bahri, O., Boubrahimi, S. F., & Hamdi, S. M.* <https://github.com/Luckilyeee/CELS> ⭐ 6 | 🐛 0 | 🌐 Python | 📅 2025-06-20, ![](https://img.shields.io/github/stars/Luckilyeee/CELS.svg?style=social)
* [**Motif-Guided Time Series Counterfactual Explanations**](https://link.springer.com/chapter/10.1007/978-3-031-37731-0_16) (2022) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* <https://github.com/Luckilyeee/Motif-guided-counterfactual-explanation> ⭐ 4 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-02-01, ![](https://img.shields.io/github/stars/Luckilyeee/Motif-guided-counterfactual-explanation.svg?style=social)
* [**Sub-SpaCE: Subsequence-Based Sparse Counterfactual Explanations for Time Series Classification Problems**](https://link.springer.com/chapter/10.1007/978-3-031-63800-8_1) (2024) by *Refoyo, M., & Luengo, D.* <https://github.com/MarioRefoyo/Sub-SpaCE> ⭐ 1 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2024-08-29, ![](https://img.shields.io/github/stars/MarioRefoyo/Sub-SpaCE.svg?style=social)
* [**Attention-Based Counterfactual Explanation for Multivariate Time Series**](https://link.springer.com/chapter/10.1007/978-3-031-39831-5_26) (2023) by *Li, P., Boubrahimi, S. F., & Hamdi, S. M.* <https://sites.google.com/view/attention-based-cf>

### Frameworks (Multiple Explanation Types)

* [**TimeSHAP: Explaining Recurrent Models through Sequence Perturbations**](https://arxiv.org/abs/2012.00073), (2020) by *Bento, J., Saleiro, P., Cruz, A. F., Figueiredo, M. A., & Bizarro, P.*, <https://github.com/feedzai/timeshap> ⭐ 201 | 🐛 15 | 🌐 Jupyter Notebook | 📅 2023-12-21, ![](https://img.shields.io/github/stars/feedzai/timeshap.svg?style=social)
* [**Understanding Any Time Series Classifier with a Subsequence-based Explainer**](https://dl.acm.org/doi/pdf/10.1145/3624480) , (2023) by *Spinnato, F., Guidotti, R., Monreale, A., Nanni, M., Pedreschi, D., & Giannotti, F.* <https://github.com/fspinna/lasts> ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2023-08-30, ![](https://img.shields.io/github/stars/fspinna/lasts.svg?style=social)
* [**ExTea: An Evolutionary Algorithm-Based Approach for Enhancing Explainability in Time-Series Models**](https://link.springer.com/chapter/10.1007/978-3-031-70381-2_27) (2024) by *Huang, Y., Zhou, Y., Zhao, H., Fang, L., Riedel, T., & Beigl, M* <https://github.com/HuangYiran/extea> ⭐ 0 | 🐛 0 | 📅 2024-05-28, ![](https://img.shields.io/github/stars/HuangYiran/extea.svg?style=social)

## Forecasting

* [**Explaining time series predictions with dynamic masks**](http://proceedings.mlr.press/v139/crabbe21a/crabbe21a.pdf) (2021) by *Crabbé, J., & Van Der Schaar, M.*  <https://github.com/JonathanCrabbe/Dynamask> ⭐ 77 | 🐛 5 | 🌐 Python | 📅 2022-05-31, ![](https://img.shields.io/github/stars/JonathanCrabbe/Dynamask.svg?style=social)
* [**TEMPORAL DEPENDENCIES IN FEATURE IMPORTANCE FOR TIME SERIES PREDICTION**](https://www.cs.toronto.edu/~mvolkovs/ICLR23_WinIT.pdf) (2023) by *Leung, K. K., Rooke, C., Smith, J., Zuberi, S., & Volkovs, M.*  <https://github.com/layer6ai-labs/WinIT> ⭐ 25 | 🐛 2 | 🌐 Jupyter Notebook | 📅 2023-03-31, ![](https://img.shields.io/github/stars/layer6ai-labs/WinIT.svg?style=social)
* [**TS-MULE: Local Interpretable Model-Agnostic Explanations for Time Series Forecast Models**](https://link.springer.com/chapter/10.1007/978-3-030-93736-2_1) (2021) by *Schlegel, U., Vo, D. L., Keim, D. A., & Seebacher, D.*  [https://github.comdbvis-ukon/ts-mule](https://github.com/dbvis-ukon/ts-mule) ⭐ 22 | 🐛 5 | 🌐 Python | 📅 2021-09-15, ![](https://img.shields.io/github/stars/dbvis-ukon/ts-mule.svg?style=social)
* [**Counterfactual Explanations for Time Series Forecasting**](https://arxiv.org/abs/2310.08137) (2023) by *Wang, Z., Miliou, I., Samsten, I., & Papapetrou, P.*  <https://github.com/zhendong3wang/counterfactual-explanations-for-forecasting> ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2024-02-14, ![](https://img.shields.io/github/stars/zhendong3wang/counterfactual-explanations-for-forecasting.svg?style=social)
* [**ShapTime: A General XAI Approach for Explainable Time Series Forecasting**](https://link.springer.com/chapter/10.1007/978-3-031-47721-8_45) (2024) by *Zhang, Y., Sun, Q., Qi, D., Liu, J., Ma, R., & Petrosian, O.* <https://github.com/Zhangyuyi-0825/ShapTime> ⭐ 15 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-03-08, ![](https://img.shields.io/github/stars/Zhangyuyi-0825/ShapTime.svg?style=social)
* [**TsSHAP: Robust model agnostic feature-based explainability for univariate time series forecasting**](https://arxiv.org/pdf/2303.12316.pdf) (2023) by *Raykar, V. C., Jati, A., Mukherjee, S., Aggarwal, N., Sarpatwar, K., Ganapavarapu, G., & Vaculin, R.*
* [**Series saliency: Temporal interpretation for multivariate time series forecasting**](https://arxiv.org/pdf/2012.09324.pdf) (2020) by *Pan, Q., Hu, W., & Zhu, J.*

## Classification and Regression / Forcasting

* [**Learning Perturbations to Explain Time Series Predictions**](https://arxiv.org/pdf/2305.18840.pdf) (2023) by *Enguehard, J.* <https://github.com/josephenguehard/time_interpret> ⭐ 72 | 🐛 2 | 🌐 Python | 📅 2026-05-18, ![](https://img.shields.io/github/stars/josephenguehard/time_interpret.svg?style=social)
* [**Tsviz: Demystification of deep learning models for time-series analysis**](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=8695734) (2019) by *Siddiqui, S. A., Mercier, D., Munir, M., Dengel, A., & Ahmed, S.* <https://github.com/shoaibahmed/TSViz-Core> ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2019-05-15, ![](https://img.shields.io/github/stars/shoaibahmed/TSViz-Core.svg?style=social)
* [**WinTSR: A Windowed Temporal Saliency Rescaling Method for Interpreting Time Series Deep Learning Models**](https://arxiv.org/abs/2412.04532) (2024) by *Islam, M. K., & Fox, J.* <https://github.com/khairulislam/tslens> ⭐ 13 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2026-08-25, ![](https://img.shields.io/github/stars/khairulislam/tslens.svg?style=social)

## Benchmarking and Evaluation

* [**Exathlon: A Benchmark for Explainable Anomaly Detection over Time Series**](https://arxiv.org/pdf/2010.05073.pdf), (2021) by *Jacob, V., Song, F., Stiegler, A., Rad, B., Diao, Y., & Tatbul, N.* <https://github.com/exathlonbenchmark/exathlon> ⭐ 69 | 🐛 2 | 🌐 Python | 📅 2024-03-13, ![](https://img.shields.io/github/stars/exathlonbenchmark/exathlon.svg?style=social)
* [**Evaluation of post-hoc interpretability methods in time-series classification**](https://www.nature.com/articles/s42256-023-00620-w), (2023) by *Turbé, H., Bjelogrlic, M., Lovis, C. et al.*, <https://github.com/hturbe/InterpretTime> ⭐ 56 | 🐛 1 | 🌐 Python | 📅 2023-04-13, ![](https://img.shields.io/github/stars/hturbe/InterpretTime.svg?style=social)
* [**Evaluating Explanation Methods for Multivariate Time Series Classification**](https://arxiv.org/abs/2308.15223), (2023) by \*Serramazza, D. I., Nguyen, T. T., Nguyen, T. L., & Ifrim, G. \* <https://github.com/mlgig/Evaluating-Explanation-Methods-for-MTSC> ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2026-06-09, ![](https://img.shields.io/github/stars/mlgig/Evaluating-Explanation-Methods-for-MTSC.svg?style=social)
* [**Robust Framework for Explanation Evaluation in Time Series Classification**](https://arxiv.org/abs/2306.05501), (2023) by *Nguyen, T. T., Nguyen, T. L., & Ifrim, G.* <https://github.com/mlgig/amee> ⭐ 7 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2024-06-26, ![](https://img.shields.io/github/stars/mlgig/amee.svg?style=social)
* [**A Deep Dive into Perturbations as Evaluation Technique for Time Series XAI**](https://arxiv.org/pdf/2307.05104.pdf), (2023) by *Schlegel, U., & Keim, D. A.*,  <https://github.com/visual-xai-for-time-series/time-series-xai-perturbation-analysis> ⭐ 4 | 🐛 0 | 🌐 HTML | 📅 2023-08-11, ![](https://img.shields.io/github/stars/visual-xai-for-time-series/time-series-xai-perturbation-analysis.svg?style=social)
* [**XTSC-Bench: Quantitative Benchmarking for Explainers on Time Series Classification**](https://arxiv.org/pdf/2310.14957.pdf), (2023) by *Höllig, J., Thoma, S., & Grimm, F.* <https://github.com/JHoelli/XTSC-Bench> ⭐ 4 | 🐛 0 | 🌐 Python | 📅 2023-10-24, ![](https://img.shields.io/github/stars/JHoelli/XTSC-Bench.svg?style=social)
* [**XAI for Time Series Classification: Evaluating the Benefits of Model Inspection for End-Users**](https://link.springer.com/chapter/10.1007/978-3-031-63800-8_22), (2024) by *Håvardstun, B., Ferri, C., Flikka, K., & Telle, J. A*
* [**A Deep Dive into Perturbations as Evaluation Technique for Time Series XAI**](https://arxiv.org/pdf/2307.05104), (2023) by *Schlegel, U., & Keim, D. A.*
* [**Introducing the Attribution Stability Indicator: a Measure for Time Series XAI Attributions**](https://arxiv.org/abs/2310.04178), (2023) by \*Schlegel, U., & Keim, D. A. \*
* [**Time to Focus: A Comprehensive Benchmark Using Time Series Attribution Methods**](https://arxiv.org/abs/2202.03759), (2022) by *Mercier, D., Bhatt, J., Dengel, A., & Ahmed, S.*
* [**Towards a rigorous evaluation of XAI methods on time series**](https://ieeexplore.ieee.org/document/9022428), (2019) by *Schlegel, U., Arnout, H., El-Assady, M., Oelke, D., & Keim, D. A.*

## Ante-Hoc Explanation

While this repository mostly focuses on post-hoc explanations - i.e. introducing the explanations after the training of the predictor, this section includes some approches that include explanability into the predicors design (e.g., via architecture or training).

### Classification

* [**Retain: An interpretable predictive model for healthcare using reverse time attention mechanism**](https://proceedings.neurips.cc/paper/2016/hash/231141b34c82aa95e48810a9d1b33a79-Abstract.html) (2016) by *Choi, E., Bahadori, M. T., Sun, J., Kulas, J., Schuetz, A., & Stewart, W.* <https://github.com/mp2893/retain> ⭐ 227 | 🐛 4 | 🌐 Python | 📅 2017-11-04, ![](https://img.shields.io/github/stars/mp2893/retain.svg?style=social)
* [**Xcm: An explainable convolutional neural network for multivariate time series classification**](https://www.mdpi.com/2227-7390/9/23/3137) (2021) by *Fauvel, K., Lin, T., Masson, V., Fromont, É., & Termier, A.* <https://github.com/XAIseries/XCM> ⭐ 50 | 🐛 2 | 🌐 Python | 📅 2022-11-27, ![](https://img.shields.io/github/stars/XAIseries/XCM.svg?style=social)
* [**XEM: An explainable-by-design ensemble method for multivariate time series classification**](https://link.springer.com/article/10.1007/s10618-022-00823-6) (2022) by *Fauvel, K., Fromont, É., Masson, V., Faverdin, P., & Termier, A* <https://github.com/XAIseries/XEM> ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2023-04-18, ![](https://img.shields.io/github/stars/XAIseries/XEM.svg?style=social)
* [**Fast, accurate and explainable time series classification through randomization**](https://link.springer.com/article/10.1007/s10618-023-00978-w) (2023) by *Cabello, N., Naghizade, E., Qi, J., & Kulik, L.* <https://github.com/stevcabello/r-STSF> ⭐ 11 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2023-10-17, ![](https://img.shields.io/github/stars/stevcabello/r-STSF.svg?style=social)
* [**Explaining Deep Classification of Time-Series Data with Learned Prototypes**](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC8050893/) (2019) by *Gee, A. H., Garcia-Olano, D., Ghosh, J., & Paydarfar, D.* <https://github.com/alangee/ijcai19-ts-prototypes> ⭐ 1 | 🐛 0 | 📅 2020-10-28, ![](https://img.shields.io/github/stars/alangee/ijcai19-ts-prototypes.svg?style=social)
* [**Medical Time Series Classification with Hierarchical Attention-based Temporal Convolutional Networks: A Case Study of Myotonic Dystrophy Diagnosis**](https://openaccess.thecvf.com/content_CVPRW_2019/papers/Explainable%20AI/Lin_Medical_Time_Series_Classification_with_Hierarchical_Attention-based_Temporal_Convolutional_Networks_CVPRW_2019_paper.pdf) (2019) by *Lin, L., Xu, B., Wu, W., Richardson, T. W., & Bernal, E. A.*
* [**Explainable Failure Predictions with RNN Classifiers based on Time Series Data**](https://arxiv.org/abs/1901.08554) (2019) by *Giurgiu, I., & Schumann, A.*
* [**MTEX-CNN: Multivariate Time Series EXplanations for Predictions with Convolutional Neural Networks**](https://ieeexplore.ieee.org/document/8970899) (2019) by *Assaf, R., Giurgiu, I., Bagehorn, F., & Schumann, A.*

### Forecasting

* [**Interpretable Multivariate Time Series Forecasting with Temporal Attention Convolutional Neural Networks**](https://research.vu.nl/en/publications/interpretable-multivariate-time-series-forecasting-with-temporal-) (2020) by *Pantiskas, L., Verstoep, K., & Bal, H.* <https://github.com/lpphd/multivariate-attention-tcn> ⭐ 99 | 🐛 3 | 🌐 Jupyter Notebook | 📅 2023-03-25, ![](https://img.shields.io/github/stars/lpphd/multivariate-attention-tcn.svg?style=social)
* [**Exploring interpretable LSTM neural networks over multi-variable data**](http://proceedings.mlr.press/v97/guo19b.html) (2019) by *Guo, Tian, Tao Lin, and Nino Antulov-Fantulin* <https://github.com/weilai0980/IMV-LSTM> ⭐ 49 | 🐛 4 | 🌐 Python | 📅 2021-06-18, ![](https://img.shields.io/github/stars/weilai0980/IMV-LSTM.svg?style=social)
* [**Temporal fusion transformers for interpretable multi-horizon time series forecasting**](https://www.sciencedirect.com/science/article/pii/S0169207021000637) (2021) by *Lim, B., Arık, S. Ö., Loeff, N., & Pfister, T.*
* [**A memory-network based solution for multivariate time-series forecasting**](https://arxiv.org/abs/1809.02105) (2018) by *Chang, Y. Y., Sun, F. Y., Wu, Y. H., & Lin, S. D.*

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
