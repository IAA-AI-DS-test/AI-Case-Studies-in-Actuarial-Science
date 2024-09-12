<img src="logo.png" width="300px">

<br>
<p style="font-size:19px; text-align:left; margin-top: 15px; margin-bottom: 15px">IAA Taskforce <i>Artificial Intelligence</i></p>
<p style="font-size:25px; text-align:left; margin-bottom: 25px"><b>AI Case Studies in Actuarial Science</b></p>
<br>

| # | Date&nbsp;Added | Author | Title | Resource(s) | Type | Level | Primary&nbsp;Topics | Secondary&nbsp;Topics | Language(s) | Programming Language(s) | Methods&nbsp;and/or&nbsp;Models | AI&nbsp;Control Cycle | Notes | Abstract/Summary
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 1 | 2024-05-08 | DAV&nbsp;🇩🇪 | Binary&nbsp;Classification: Credit&nbsp;Scoring | [Notebook](https://kaggle.com/code/floser/binary-classification-credit-scoring) | Case Study | 🟨🟨⬜ <br> Advanced | `Machine Learning` `Classification` | `Explainable AI` `Hyperparameter Tuning` `GPU Usage` | English | Python | CatBoost, XGBoost, LightGBM, Deep Learning, Logarithmic Regression, SHAP | (?) | Data&nbsp;derived&nbsp;from&nbsp;a&nbsp;Kaggle competition's real-world dataset | This Jupyter Notebook offers a hands-on tutorial on binary classification using the Home Credit Default Risk dataset from Kaggle. Our focus is on predicting loan repayment difficulties, equipping actuaries with skills applicable to common insurance scenarios like churn prediction and fraud detection. Structured in three parts, the notebook progresses from simple to advanced modeling techniques: Part A sets a performance benchmark with an initial CatBoost model, a gradient boosting algorithm that requires minimal data preprocessing. Part B explores logistic regression, then delves into a brief exploratory data analysis, feature engineering, and model interpretability – all essential for making informed decisions. We cover data preprocessing, including encoding, scaling, and subsampling for imbalanced data, and investigate the impact on modeling. Part C is devoted to the optimization and practical application of machine learning models. It first addresses overfitting using the example of regularized logistic regression, as well as hyperparameter tuning in artificial neural networks and gradient boosting methods CatBoost, LightGBM, and XGBoost. After a comprehensive model evaluation using validation and test data, we discuss application aspects in high-risk areas and conclude by summarizing the key insights we have learned. The appendix provides further information on CatBoost and GPU-accelerated training.
| 2 | 2024-05-08 | SAV&nbsp;🇨🇭 | SHAP&nbsp;for&nbsp;Actuaries: Explain&nbsp;Any&nbsp;Model | [Article](https://papers.ssrn.com/sol3/papers.cfm?abstract_id=4389797), <br> [Notebook](https://github.com/actuarial-data-science/Tutorials/tree/master/14%20-%20SHAP) | Educational | 🟨🟨⬜ <br> Advanced | `Explainable AI` `Interpretable ML` | `Regression` `Synthetic Data` `Claims Prediction` | English | Python, R | GLM, LightGBM, Deep Learning, SHAP | (?) | Data&nbsp;generation&nbsp;process&nbsp;and ground truth given | This&nbsp;tutorial&nbsp;gives&nbsp;an&nbsp;overview&nbsp;of&nbsp;SHAP&nbsp;(SHapley&nbsp;Additive&nbsp;exPlanation),&nbsp;one&nbsp;of&nbsp;the&nbsp;most&nbsp;commonly&nbsp;used&nbsp;techniques&nbsp;for&nbsp;examining&nbsp;a&nbsp;black‑box&nbsp;machine&nbsp;learning&nbsp;(ML)&nbsp;model.<br>Besides&nbsp;providing&nbsp;the&nbsp;necessary&nbsp;game&nbsp;theoretic&nbsp;background,&nbsp;we&nbsp;show&nbsp;how&nbsp;typical&nbsp;SHAP&nbsp;analyses&nbsp;are&nbsp;performed&nbsp;and&nbsp;used&nbsp;to&nbsp;gain&nbsp;insights&nbsp;about&nbsp;the&nbsp;model.<br>The&nbsp;methods&nbsp;are&nbsp;illustrated&nbsp;on&nbsp;a&nbsp;simulated&nbsp;insurance&nbsp;data&nbsp;set&nbsp;of&nbsp;car&nbsp;claim&nbsp;frequencies&nbsp;using&nbsp;different&nbsp;ML&nbsp;models&nbsp;and&nbsp;different&nbsp;SHAP&nbsp;algorithms.
| 3 | 2024-05-11 | Caesar&nbsp;Balona&nbsp;🇿🇦 | Case&nbsp;Study&nbsp;1: Parsing&nbsp;Claims&nbsp;Descriptions | [Article](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi_toXSoYWGAxXUVPEDHcPkAOI4ChAWegQICxAB&url=https%3A%2F%2Factuaries.org.uk%2Fmedia%2Fpurp2kk5%2Factuary-gpt-applications-of-large-language-models-to-insurance-and-actuarial-work.pdf&usg=AOvVaw1KRTDCIgv9IHZ5XlztvoWk&opi=89978449), <br> [Code](https://github.com/cbalona/actuarygpt-code/tree/main/case-study-1) | Case Study | 🟨🟨⬜ <br> Advanced | `Large Language Models` | `Information Extraction` `Parsing` | English | Python | ChatGPT with GPT-4 | (?) | – | TODO
| 4 | 2024-05-11 | Caesar&nbsp;Balona&nbsp;🇿🇦 | Case&nbsp;Study&nbsp;2: Identifying&nbsp;Emerging&nbsp;Risks | [Article](https://www.google.com/url?sa=t&rct=j&q=&esrc=s&source=web&cd=&cad=rja&uact=8&ved=2ahUKEwi_toXSoYWGAxXUVPEDHcPkAOI4ChAWegQICxAB&url=https%3A%2F%2Factuaries.org.uk%2Fmedia%2Fpurp2kk5%2Factuary-gpt-applications-of-large-language-models-to-insurance-and-actuarial-work.pdf&usg=AOvVaw1KRTDCIgv9IHZ5XlztvoWk&opi=89978449), <br> [Code](https://github.com/cbalona/actuarygpt-code/tree/main/case-study-2) | Case Study | 🟩⬜⬜ <br> Beginner | `Large Language Models` | `Text Generation` | English | Python | ChatGPT with GPT-4 | (?) | – | TODO
| 5 | 2024-06-13 | Simon&nbsp;Hatzesberger&nbsp;🇩🇪 | Model-Agnostic Explainability Methods for Regression Problems: A Case Study on Medical Costs Data | see folder ['Case&nbsp;Study&nbsp;#5'](https://github.com/IAA-AI-DS-test/AI-Case-Studies-in-Actuarial-Science/tree/main/Case%20Study%20%235) in this repository | Educational | 🟨🟨⬜ <br> Advanced | `Explainable AI` | `Machine Learning` `Regression` | English | Python | CatBoost, PDP, ALE, PFI, SHAP, LIME | (?) | – | In this Jupyter notebook, we offer a comprehensive walkthrough for actuaries and data scientists on applying model-agnostic explainability methods to regression tasks, using a medical costs dataset as our case study. With the growing prevalence of modern black box machine learning models, which often lack the interpretability of classical statistical models, these explainability methods become increasingly important to ensure transparency and trust in predictive modeling. We illuminate both global methods – such as global surrogate models, PDPs, ALE plots, and permutation feature importances – for a thorough understanding of model behavior, and local methods – like SHAP, LIME, and ICE plots – for detailed insights into individual predictions. In addition to concise overviews of these methods, the notebook provides practical code examples that readers can easily adopt, offering a user-friendly introduction to explainable artificial intelligence.
| 6 | 2024-07-16 | MAS (Monetary Authority of Singapore) 🇸🇬 | FEAT Principles Assessment Case Studies | [Website](https://www.mas.gov.sg/news/media-releases/2022/mas-led-industry-consortium-publishes-assessment-methodologies-for-responsible-use-of-ai-by-financial-institutions), <br> [White Paper](https://www.mas.gov.sg/-/media/mas-media-library/news/media-releases/2022/veritas-document-4---feat-principles-assessment-case-studies.pdf) | Case Study | 🟩⬜⬜ <br> Beginner | `Fairness` `Ethics` `Accountability` `Transparency` | `Life Insurance Underwriting` `Fraud Detection` `Retail Marketing` `Credit Decisioning` `Customer Marketing` | English | – | Gradient Boosting Model, PDP, SHAP, PFI | (?) | Data&nbsp;derived&nbsp;from&nbsp;a&nbsp;Kaggle competition's real-world dataset | TODO
| 7 | 2024-07-16 | Personal Data Protection Commission 🇸🇬 | Compendium of Use Cases: Practical Illustrations of the Model AI Governance Framework | [Website](https://www.pdpc.gov.sg/help-and-resources/2020/01/model-ai-governance-framework/), <br> [White Paper (Volume 1)](https://go.gov.sg/ai-gov-use-cases), <br> [White Paper (Volume 2)](https://go.gov.sg/ai-gov-use-cases-2) | Case Study | 🟩⬜⬜ <br> Beginner | `Governance` | TODO | English | – | Gradient Boosting Model, PDP, SHAP, PFI | (?) | Data&nbsp;derived&nbsp;from&nbsp;a&nbsp;Kaggle competition's real-world dataset | TODO
| 8 | 2024-07-16 | SAV&nbsp;🇨🇭 (Andreas Troxler, Jürg Schelldorfer) | Actuarial Applications of Natural Language Processing Using Transformers | [Article](https://arxiv.org/pdf/2206.02014), <br> [Notebook](https://github.com/actuarial-data-science/Tutorials/tree/master/12%20-%20NLP%20Using%20Transformers) | Educational | 🟥🟥🟥 <br> Expert | `Natural Language Processing` `Transformers` | `Property Insurance Claims Descriptions` `Recurrent Neural Networks` | English | Python | Transformers, Recurrent Neural Networks, Integrated Gradients | (?) | – | This tutorial demonstrates workflows to incorporate text data into actuarial classification and regression tasks. The main focus is on methods employing transformer-based models. A dataset of car accident descriptions with an average length of 400 words, available in English and German, and a dataset with short property insurance claims descriptions are used to demonstrate these techniques. The case studies tackle challenges related to a multi-lingual setting and long input sequences. They also show ways to interpret model output, to assess and improve model performance, by fine-tuning the models to the domain of application or to a specific prediction task. Finally, the tutorial provides practical approaches to handle classification tasks in situations with no or only few labeled data, including but not limited to ChatGPT. The results achieved by using the language-understanding skills of off-the-shelf natural language processing (NLP) models with only minimal pre-processing and fine-tuning clearly demonstrate the power of transfer learning for practical applications. |
| ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... | ... |

*Notes:*
- *The dates are formatted in ISO 8601 standard (*`YYYY-MM-DD`*).*
- *The "Author" column incorporates both the individual author and the member association.*
- *The "Resource(s)" column provides direct links to articles and code repositories.*
