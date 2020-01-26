# __Python__ Science _"Pipeline"/"Flow"_

This document is created to link my personal files, and locate faster some resources, concepts, codes that I found inside the books in previous lectures. It tends to guide my AI team easy and faster to resources very spread on Internet.

The order here is important, is the way in which I see the process:

#### About _Science Pipelines_: [Python Data Sci Essentials, Chapter 3](./SCIENCE/2015_Boschetti_and_Massaron-Py_Data_Sci_Essentials.pdf)

#### About _Machine Learning_: [Practical Machine Learning](./04_ML/2018_Practical_ML_with_Py.pdf)

Contain the basics on ML. The second part is a broad description of ML pipeline. And the last part is well detailed (by chapter) exposition of Real World Case Studies.

## General Pipeline

- Collecting Data
- Data Munging
- Data Wrangling
- Data Analysis/Exploring
    1. Feature Extraction
    2. Dimensionality Reduction
    3. Outliers Treatment
    4. Testing & Validation
    5. Hyper-param optimization
    6. Feature Selection
    7. Data Plotting/Visualization
- Building Models
- Model Evaluation
- [__Deploying Models into Apps__](./04_ML/2015_Sebastian_Raschka-Py_ML.pdf)
- Monitoring Models (Feedback)

## Basik Knowledge

<p><img align='left' src="./imgs/DataSci_Skills_Moscu_Metro.png" alt='Tensorflow logo' height="200" width="700"></p><br clear='left'>

## Baselines Methods / Important Knowledge
* About Machine Learning
    1. _Supervised_ __Classification__
    2. _Semi-Supervised_ [__Reinforcement Learning__](./05_Deep_Learning/2018_Reinforcement_Learning.pdf)
    3. _Unsupervised_ __Clustering__, __Anomaly detection__
* About Software Architecture
    1. Microservices
* Any other?


## Resources

### [Corpus](./mapmind/corpus.html)
### [Models]()

## Applications - Products
- Text Classifier
- __Recommendation Systems__
    1. [Content & Collaborative Filtering](./04_ML/2016_ML_for_the_web/ML_4the_Web.pdf)
    2. [Afinity Analysis: Apriori algthm](./04_ML/2015_Learning_Data_Mining/2015_Learning_Data_Mining_with_Py.pdf)
    3. [The million Song Dataset Example](./04_ML/2018_Practical_ML_with_Py.pdf)

# Technologies

### Data Base Management System
* mariadb/mysql
* Mongodb
* Clickhouse

### Text Wrangling
- Spacy & sus modelos
- lib propia: preprocess (depend on scipy, nltk & sklearn)
- Stanford library y su api de python (inside NLTK)

### Data Analysis
- Sklearn
- spark.ml
- Scipy

### Visualization with _Altair_
_notebook collection_
[Altair](../pyVideosData/06_Visualization/SCI_PLOT_Altair_2018_PyCon-Jake_VanderPlas-Exploratory_Data_Visualization_with_Vega_Vega-Lite_and_Altair/notebooks)
<p><img align='left' src="./imgs/altair-gallery.png" alt='Tensorflow logo' height="200" width="700"></p><br clear='left'>

### Deep Learning

* [Tensorflow](./04_ML/2017_Hands_on_ML/2017_Hands_On_ML_with_Sklearn_and_Tf.pdf)
* pandas.visualization
* __Model Visualization__: Tensorboard

### Optimization

- Usar cython
- GPU con PyCuda
- Usar Fortran
- Ver paralelización con Apache Spark

### Deploying & Scaling Services

* AWS
* Apache Spark
* Hadoop

### Web UI:

* VUE

## Pipeline Introspection

- Models Deployment:
    1. [Model Deployment as a Service](./04_ML/2018_Practical_ML_with_Py.pdf)
- Monitoring
    1. [Strategies to managing model robustness](./04_ML/2016_Advanced_ML.pdf)

## Standards

#### DataTypes

- Apache Parquet: A columnar data format.
- Apache Arrow: In memory columnar data format
- CSV
- [HDF5](./01_Numpy/2019_Numerical_Python_2ndE.pdf)
- pandas.DataFrame

#### Links

- [Google DeepMind Team](https://deepmind.com/)
- [Kaggle Blog](http://blog.kaggle.com) especialized on ML topics
- About [Netflix Recommendation System Algorithm](http://techblog.netflix.com/2012/04/netflix-recommendations-beyond-5-stars.html)
