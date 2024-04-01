# OpenAstronomy: Astronomical data enhancement with DL 

## Contributor Information

<table>
    <tr>
        <td><b>Name</b></td>
        <td>Ye Li</td>
    </tr>
    <tr>
        <td><b>Github username</b></td>
        <td><a href="https://github.com/matixx2b7e">matixx2b7e</a></td>
    </tr>
    <tr>
        <td><b>Email</b></td>
        <td><a href="mailto:yeli2b7e@gmail.com">yeli2b7e@gmail.com</a></td>
    </tr>
    <tr>
        <td><b>Matrix</b></td>
        <td><a href="https://matrix.to/#/@matixx2b7e:matrix.org">https://matrix.to/#/@matixx2b7e:matrix.org</a></td>
    </tr>
    <tr>
        <td><b>PR link</b></td>
        <td><a href="https://github.com/fornax-navo/fornax-demo-notebooks/pull/264">https://github.com/fornax-navo/fornax-demo-notebooks/pull/264</a></td>
    </tr>
    <tr>
        <td><b>Time zone</b></td>
        <td>GMT+8</td>
    </tr>
</table> 


Hi! I am Ye Li, a junior student in physics major from Southern University of Science and Technology, Shenzhen, China. I'm interested in astronomy and have solid background knowledge in general relativity and cosmology. Besides, I'm also a big fan of open source and hope to contribute. 

I have experience in several programming languages including Python, Java and C++ while Python is the one I'm most familiar with right now. From my previous projects in data processing, I gained much experience in Python and packages like NumPy, pandas, and Matplotlib. For machine learning and deep learning, I usually use scikit-learn and PyTorch. My working environment was set up in Debian and I'm quite familiar with Linux commands.

### Experience in Machine Learning and Deep Learning

During the previous winter break, I worked on a classification problem on SDSS dataset. The goal is to classify observations into three groups: galaxies, stars, and quasars. The dataset was preprocessed by replacing abnormal values with mean and selecting important features including redshifts and flux in certain filters based on Pearson correlation coefficients. I tested several models including random forest, XGBoost, SVM, MLP, etc. and compared their accuracy and efficiency. 

Additionally, I have worked on a project on metaphor detection. I implemented a simple deep learning model with PyTorch which consists of transformer model BERT and CNN layers. Although CNN is mainly designed for computer vision, it works with NLP as well. Since this is a binary classification problem, the activation function for this model is sigmoid function. I also added a drop layer to prevent overfitting.

Currently, I'm actively learning deep learning and optimization methods. I'm also taking part in a weekly seminar on mathematics in machine learning algorithms. My current research mainly focuses on retrieving chemical states from X-ray absorption spectroscopy by advanced denoising neural networks and reconstrucing 3D images in deep learning approaches. 

### Interest in OpenAstronomy

As I am an astronomy lover, I'd love to make contributions to astronomy research. OpenAstronomy's projects are the most attractive ones so I didn't hesitate to apply. Besides, I'm qualified for most of the requirements except I'm not an expert in flow-based architectures, but I'm planning to study the algorithms in April. I believe I will build a workable and user-friendly schema with my knowledge and skills!

## Project Proposal

**Organisation:** OpenAstronomy

**Proposal Title:** Astronomical data enhancement with DL

Many large-scale astronomical data are available for research today. However, missing values and ununified schema can make them hard to use. In this project, I'm going to enhance astronomical data by means of deep learning, making the best use of incomplete data and simplifying data preprocessing process for various datasets. The methods will be tested on large samples of Active Galactic Nuclei (AGNs). 

### Main Tasks

#### 1. Augment incomplete datasets 

The data we need for research may not be directly recorded thus it's crucial to develop an accurate model to predict unknown values. I will try on diffrent deep learning architectures: flow-based systems, transformers, and a combination of them. The model will be implemented in class, with `train` and `predict` functions. Denoising, regularization techniques and other optimization methods will be implemented to prevent overfitting and improve the results. The models will be tested on AGNs and evaluated by loss with observations and theoretical values. The best model overall will be selected for future use.

#### 2. Design a data unification schema

I will use the architecture developed for data enhancement to generate data for the unified dataset. By looking into the structure of different datasets, I will design the structure of the data unification schema that is compatible with most datasets and easy to use. The new class for unification schema will be inherited from the model class and developed further with other functions, including: 

- replacing incomplete data with new data
- automatically detecting abnormal values and replacing or skipping them (based on user's demand)
- generating a unified dataset

### Timeline

| Period | Time commitment (hours per week) | Description |
| --- | :--: | -- |
| May 1 - 26  | 10 - 15 | Community bonding period: Get familiar with current code and dataset, set up the development environment. |
| May 27 - June 7 | 10 - 15 | Develop a flow-based architecture for gap filling and test it on AGNs. |
| June 8 - 14 | 0 - 5 | Temporary break: I will be preparing for final exams so I may not be available for the project. |
| June 15 - 22 | 20 - 25 | Improve the flow-based architecture, test on AGNs. |
| June 23 - 30 | 35+ | Develop a transformer, test on AGNs. |
| July 1 - 8 | 35+ | Continue improving flow-based and transformer models, explore other architectures like FlowTransformer, test on AGNs, commit the best model. |
| July 12 | | Midterm evaluation deadline. |
| July 9 - 21 | 35+ | Develop a deep learning model to detect abnormal values and missing values. |
| July 22 - August 4 | 35+ | Develop the schema with automatic data preprocessing. |
| August 5 - 18 | 35+ | Write functions for users to generate unified data. |
| August 19 - 30 | 35+ | Test and improve, commit the final architecture. |
| September 2 | | Final evaluation deadline. |

The summer break in my university officially starts on June 22 so my schedule is tight before that. Starting from June 15 (as the last week in a semester is usually flexible), I will be able to fully commit myself to the project. I don't have big plans for the summer but there might be some small trips which will generally not influence the schedule.

## GSoC

**Have you participated previously in GSoC? When? With which project?**

No

**Are you also applying to other projects?**

No
