## Paper Reading of Machine Learning and Deep Learning

大致整理一些覺得不錯的paper，順便附上讀後簡略心得與摘要。

## General Introduction
- [Deep EHR: A Survey of Recent Advances in Deep Learning Techniques for Electronic Health Record (EHR) Analysis](Intro/Deep_EHR.pdf), IEEE Journal of Biomedical Health Informatics, 2017. 
```markdown
基礎深度學習演算法的介紹，架構完整。
```
- [Opportunities and challenges in developing deep learning models using electronic health records data: a systematic review](Intro/EHRreview.pdf), Journal of the American Medical Informatics Association, 2018.
```markdown
基礎深度學習演算法的介紹，架構完整。
```
- [Deep learning for healthcare: review, opportunities and challenges](Intro/DeepHealthcare.pdf), Briefings in Bioinformatics, 2018.
```markdown
看完有點久....只記得還不錯XD
```


## Application 
- [Hospital Admission Location Prediction via Deep Interpretable Networks for the Year-Round Improvement of Emergency Patient Care](Application/2021_HospitalAdmission.pdf), IEEE Journal of Biomedical Health Informatics, 2020.
```markdown
架構完整，後面驗證更完整，interpretation的部分用一層logisticregression處理，值得思考。
```
- [A Deep Neural Network Application for Improved Prediction of HbA1c in Type 1 Diabetes](Application/2020_CNN_HbA1c_JBHI.pdf), IEEE Journal of Biomedical Health Informatics, 2020.
```markdown
進階CNN處理，預測連續數值HbA1c。
```
- [Using recurrent neural network models for early detection of heart failure onset](Application/2017_RNN_HeartFailureOnset_2017.pdf), Journal of the American Medical Informatics Association, 2017.
```markdown
簡易的representation＋RNN time serious資料的處理。
```

## Explainable AI
- [Explainable machine-learning predictions for the prevention of hypoxaemia during surgery](Explainable/2018_ExplainableMachinLearning.pdf), Nature Biomedical Engineering, 2018.
```markdown
解釋性模型的範例
```
### 已開發的套件
- `SHAP` [A Unified Approach to Interpreting Model Predictions](https://arxiv.org/abs/1705.07874), arXiv.org, 2017. [GitHub](https://github.com/slundberg/shap)
- `LIME` ["Why Should I Trust You?": Explaining the Predictions of Any Classifier](https://arxiv.org/abs/1602.04938), arXiv.org, 2016. [GitHub](https://github.com/marcotcr/lime)
- `InterpretML` [InterpretML: A Unified Framework for Machine Learning Interpretability](https://arxiv.org/abs/1909.09223), arXiv.org, 2019. [GitHub](https://github.com/interpretml/interpret)
- `CAPTUM` [Captum: A unified and generic model interpretability library for PyTorch](https://arxiv.org/abs/2009.07896), arXiv.org, 2020. [GitHub](https://github.com/pytorch/captum)
### 其他方法
- [Explaining nonlinear classification decisions with deep Taylor decomposition](Explainable/2017_ExplainingNonlinearClassification.pdf), Pattern Recognition, 2017. 








<!-- 
You can use the [editor on GitHub](https://github.com/ishiou/PaperReading/edit/gh-pages/index.md) to maintain and preview the content for your website in Markdown files.

Whenever you commit to this repository, GitHub Pages will run [Jekyll](https://jekyllrb.com/) to rebuild the pages in your site, from the content in your Markdown files.

### Markdown

Markdown is a lightweight and easy-to-use syntax for styling your writing. It includes conventions for

```markdown
Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

For more details see [GitHub Flavored Markdown](https://guides.github.com/features/mastering-markdown/).

### Jekyll Themes

Your Pages site will use the layout and styles from the Jekyll theme you have selected in your [repository settings](https://github.com/ishiou/PaperReading/settings). The name of this theme is saved in the Jekyll `_config.yml` configuration file.

### Support or Contact

Having trouble with Pages? Check out our [documentation](https://docs.github.com/categories/github-pages-basics/) or [contact support](https://support.github.com/contact) and we’ll help you sort it out.
 -->
