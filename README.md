<!-- markdownlint-disable -->
<h1 align="center">
    Best-of Machine Learning with Python
    <br>
</h1>

<p align="center">
    <strong>🏆&nbsp; A ranked list of awesome machine learning Python libraries. Updated weekly.</strong>
</p>

<p align="center">
    <a href="https://github.com/ml-tooling/best-of" title="Best-of-badge"><img src="http://bit.ly/3o3EHNN"></a>
    <a href="#Contents" title="Project Count"><img src="https://img.shields.io/badge/projects-900-blue.svg?color=5ac4bf"></a>
    <a href="#Contribution" title="Contributions are welcome"><img src="https://img.shields.io/badge/contributions-welcome-green.svg"></a>
    <a href="https://github.com/ml-tooling/best-of-ml-python/releases" title="Best-of Updates"><img src="https://img.shields.io/github/release-date/ml-tooling/best-of-ml-python?color=green&label=updated"></a>
    <a href="https://mltooling.substack.com/subscribe" title="Subscribe to newsletter"><img src="http://bit.ly/2Md9rxM"></a>
    <a href="https://twitter.com/mltooling" title="Follow on Twitter"><img src="https://img.shields.io/twitter/follow/mltooling.svg?style=social&label=Follow"></a>
</p>

This curated list contains 900 awesome open-source projects with a total of 4.2M stars grouped into 34 categories. All projects are ranked by a project-quality score, which is calculated based on various metrics automatically collected from GitHub and different package managers. If you like to add or update projects, feel free to open an [issue](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose), submit a [pull request](https://github.com/ml-tooling/best-of-ml-python/pulls), or directly edit the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml). Contributions are very welcome!

---

<p align="center">
     🧙‍♂️&nbsp; Discover other <a href="https://best-of.org">best-of lists</a> or create <a href="https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md">your own</a>.<br>
    📫&nbsp; Subscribe to our <a href="https://mltooling.substack.com/subscribe">newsletter</a> for updates and trending projects.
</p>

---


## Contents

- [Machine Learning Frameworks](#machine-learning-frameworks) _56 projects_
- [Data Visualization](#data-visualization) _51 projects_
- [Text Data & NLP](#text-data--nlp) _96 projects_
- [Image Data](#image-data) _60 projects_
- [Graph Data](#graph-data) _36 projects_
- [Audio Data](#audio-data) _27 projects_
- [Geospatial Data](#geospatial-data) _22 projects_
- [Financial Data](#financial-data) _25 projects_
- [Time Series Data](#time-series-data) _26 projects_
- [Medical Data](#medical-data) _19 projects_
- [Tabular Data](#tabular-data) _5 projects_
- [Optical Character Recognition](#optical-character-recognition) _12 projects_
- [Data Containers & Structures](#data-containers--structures) _0 projects_
- [Data Loading & Extraction](#data-loading--extraction) _2 projects_
- [Web Scraping & Crawling](#web-scraping--crawling) _1 projects_
- [Data Pipelines & Streaming](#data-pipelines--streaming) _43 projects_
- [Distributed Machine Learning](#distributed-machine-learning) _33 projects_
- [Hyperparameter Optimization & AutoML](#hyperparameter-optimization--automl) _47 projects_
- [Reinforcement Learning](#reinforcement-learning) _23 projects_
- [Recommender Systems](#recommender-systems) _16 projects_
- [Privacy Machine Learning](#privacy-machine-learning) _6 projects_
- [Workflow & Experiment Tracking](#workflow--experiment-tracking) _39 projects_
- [Model Serialization & Deployment](#model-serialization--deployment) _16 projects_
- [Model Interpretability](#model-interpretability) _51 projects_
- [Vector Similarity Search (ANN)](#vector-similarity-search-ann) _12 projects_
- [Probabilistics & Statistics](#probabilistics--statistics) _22 projects_
- [Adversarial Robustness](#adversarial-robustness) _9 projects_
- [GPU Utilities](#gpu-utilities) _17 projects_
- [Tensorflow Utilities](#tensorflow-utilities) _15 projects_
- [Jax Utilities](#jax-utilities) _2 projects_
- [Sklearn Utilities](#sklearn-utilities) _17 projects_
- [Pytorch Utilities](#pytorch-utilities) _32 projects_
- [Database Clients](#database-clients) _1 projects_
- [Others](#others) _61 projects_

## Explanation
- 🥇🥈🥉&nbsp; Combined project-quality score
- ⭐️&nbsp; Star count from GitHub
- 🐣&nbsp; New project _(less than 6 months old)_
- 💤&nbsp; Inactive project _(6 months no activity)_
- 💀&nbsp; Dead project _(12 months no activity)_
- 📈📉&nbsp; Project is trending up or down
- ➕&nbsp; Project was recently added
- ❗️&nbsp; Warning _(e.g. missing/risky license)_
- 👨‍💻&nbsp; Contributors count from GitHub
- 🔀&nbsp; Fork count from GitHub
- 📋&nbsp; Issue count from GitHub
- ⏱️&nbsp; Last update timestamp on package manager
- 📥&nbsp; Download count from package manager
- 📦&nbsp; Number of dependent projects
- <img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13">&nbsp; Tensorflow related project
- <img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13">&nbsp; Sklearn related project
- <img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13">&nbsp; PyTorch related project
- <img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13">&nbsp; MxNet related project
- <img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13">&nbsp; Apache Spark related project
- <img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13">&nbsp; Jupyter related project
- <img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13">&nbsp; PaddlePaddle related project
- <img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13">&nbsp; Pandas related project
- <img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13">&nbsp; Jax related project

<br>

## Machine Learning Frameworks

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose machine learning and deep learning frameworks._

<details><summary><b><a href="https://github.com/tensorflow/tensorflow">Tensorflow</a></b> (🥇55 ·  ⭐ 180K) - An Open Source Machine Learning Framework for Everyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorflow) (👨‍💻 4.5K · 🔀 72K · 📦 310K · 📋 38K - 4% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/tensorflow/tensorflow
	```
- [PyPi](https://pypi.org/project/tensorflow) (📥 18M / month):
	```
	pip install tensorflow
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow) (📥 4.4M · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge tensorflow
	```
- [Docker Hub](https://hub.docker.com/r/tensorflow/tensorflow) (📥 75M · ⭐ 2.2K · ⏱️ 12.10.2023):
	```
	docker pull tensorflow/tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/pytorch">PyTorch</a></b> (🥇53 ·  ⭐ 72K) - Tensors and Dynamic neural networks in Python with strong GPU.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/pytorch) (👨‍💻 4.4K · 🔀 19K · 📥 25K · 📦 330K · 📋 37K - 32% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pytorch/pytorch
	```
- [PyPi](https://pypi.org/project/torch) (📥 12M / month):
	```
	pip install torch
	```
- [Conda](https://anaconda.org/pytorch/pytorch) (📥 19M · ⏱️ 03.10.2023):
	```
	conda install -c pytorch pytorch
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn/scikit-learn">scikit-learn</a></b> (🥇52 ·  ⭐ 56K) - scikit-learn: machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn/scikit-learn) (👨‍💻 3K · 🔀 24K · 📥 900 · 📦 610K · 📋 10K - 15% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/scikit-learn/scikit-learn
	```
- [PyPi](https://pypi.org/project/scikit-learn) (📥 42M / month):
	```
	pip install scikit-learn
	```
- [Conda](https://anaconda.org/conda-forge/scikit-learn) (📥 25M · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge scikit-learn
	```
</details>
<details><summary><b><a href="https://github.com/google/jax">jax</a></b> (🥇45 ·  ⭐ 25K) - Composable transformations of Python+NumPy programs: differentiate,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/jax) (👨‍💻 580 · 🔀 2.3K · 📦 18K · 📋 4.6K - 27% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/google/jax
	```
- [PyPi](https://pypi.org/project/jax) (📥 3.5M / month):
	```
	pip install jax
	```
- [Conda](https://anaconda.org/conda-forge/jaxlib) (📥 950K · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge jaxlib
	```
</details>
<details><summary><b><a href="https://github.com/Lightning-AI/lightning">pytorch-lightning</a></b> (🥇45 ·  ⭐ 25K) - Deep learning framework to train, deploy, and ship AI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Lightning-AI/lightning) (👨‍💻 910 · 🔀 3K · 📥 13K · 📦 25K · 📋 6.5K - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/PyTorchLightning/pytorch-lightning
	```
- [PyPi](https://pypi.org/project/pytorch-lightning) (📥 3.9M / month):
	```
	pip install pytorch-lightning
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-lightning) (📥 970K · ⏱️ 15.09.2023):
	```
	conda install -c conda-forge pytorch-lightning
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/Paddle">PaddlePaddle</a></b> (🥇45 ·  ⭐ 21K) - PArallel Distributed Deep LEarning: Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/Paddle) (👨‍💻 1.1K · 🔀 5.1K · 📥 15K · 📦 4.1K · 📋 17K - 6% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/PaddlePaddle/Paddle
	```
- [PyPi](https://pypi.org/project/paddlepaddle) (📥 170K / month):
	```
	pip install paddlepaddle
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras">Keras</a></b> (🥈44 ·  ⭐ 60K) - Deep Learning for humans. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras) (👨‍💻 1.2K · 🔀 19K · 📦 18 · 📋 11K - 0% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/keras-team/keras
	```
- [PyPi](https://pypi.org/project/keras) (📥 13M / month):
	```
	pip install keras
	```
- [Conda](https://anaconda.org/conda-forge/keras) (📥 3.3M · ⏱️ 28.07.2023):
	```
	conda install -c conda-forge keras
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/xgboost">XGBoost</a></b> (🥈44 ·  ⭐ 25K) - Scalable, Portable and Distributed Gradient Boosting (GBDT, GBRT or.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/xgboost) (👨‍💻 620 · 🔀 8.1K · 📥 7.3K · 📦 69K · 📋 4.9K - 6% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dmlc/xgboost
	```
- [PyPi](https://pypi.org/project/xgboost) (📥 11M / month):
	```
	pip install xgboost
	```
- [Conda](https://anaconda.org/conda-forge/xgboost) (📥 4.3M · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge xgboost
	```
</details>
<details><summary><b><a href="https://github.com/statsmodels/statsmodels">StatsModels</a></b> (🥈44 ·  ⭐ 8.9K) - Statsmodels: statistical modeling and econometrics in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/statsmodels/statsmodels) (👨‍💻 420 · 🔀 2.6K · 📥 29 · 📦 100K · 📋 5.2K - 48% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/statsmodels/statsmodels
	```
- [PyPi](https://pypi.org/project/statsmodels) (📥 11M / month):
	```
	pip install statsmodels
	```
- [Conda](https://anaconda.org/conda-forge/statsmodels) (📥 12M · ⏱️ 05.10.2023):
	```
	conda install -c conda-forge statsmodels
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/LightGBM">LightGBM</a></b> (🥈43 ·  ⭐ 16K) - A fast, distributed, high performance gradient boosting (GBT, GBDT, GBRT,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/LightGBM) (👨‍💻 290 · 🔀 3.6K · 📥 200K · 📦 26K · 📋 3.1K - 9% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/microsoft/LightGBM
	```
- [PyPi](https://pypi.org/project/lightgbm) (📥 6.9M / month):
	```
	pip install lightgbm
	```
- [Conda](https://anaconda.org/conda-forge/lightgbm) (📥 2M · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge lightgbm
	```
</details>
<details><summary><b><a href="https://github.com/jina-ai/jina">Jina</a></b> (🥈40 ·  ⭐ 19K) - Build multimodal AI applications with cloud-native stack. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/jina-ai/jina) (👨‍💻 170 · 🔀 2.1K · 📦 1.2K · 📋 1.9K - 0% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/jina-ai/jina
	```
- [PyPi](https://pypi.org/project/jina) (📥 79K / month):
	```
	pip install jina
	```
- [Conda](https://anaconda.org/conda-forge/jina-core) (📥 56K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge jina-core
	```
- [Docker Hub](https://hub.docker.com/r/jinaai/jina) (📥 1.3M · ⭐ 8 · ⏱️ 11.10.2023):
	```
	docker pull jinaai/jina
	```
</details>
<details><summary><b><a href="https://github.com/catboost/catboost">Catboost</a></b> (🥈39 ·  ⭐ 7.4K) - A fast, scalable, high performance Gradient Boosting on Decision.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/catboost/catboost) (👨‍💻 1.2K · 🔀 1.1K · 📥 180K · 📦 11 · 📋 2.1K - 23% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/catboost/catboost
	```
- [PyPi](https://pypi.org/project/catboost) (📥 2M / month):
	```
	pip install catboost
	```
- [Conda](https://anaconda.org/conda-forge/catboost) (📥 1.4M · ⏱️ 19.09.2023):
	```
	conda install -c conda-forge catboost
	```
</details>
<details><summary><b><a href="https://github.com/apache/spark">PySpark</a></b> (🥈38 ·  ⭐ 37K) - Apache Spark Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/spark) (👨‍💻 3K · 🔀 26K · ⏱️ 12.10.2023):

	```
	git clone https://github.com/apache/spark
	```
- [PyPi](https://pypi.org/project/pyspark) (📥 25M / month):
	```
	pip install pyspark
	```
- [Conda](https://anaconda.org/conda-forge/pyspark) (📥 2.9M · ⏱️ 04.10.2023):
	```
	conda install -c conda-forge pyspark
	```
</details>
<details><summary><b><a href="https://github.com/fastai/fastai">Fastai</a></b> (🥈38 ·  ⭐ 25K) - The fastai deep learning library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fastai/fastai) (👨‍💻 240 · 🔀 7.2K · 📦 15K · 📋 1.8K - 9% open · ⏱️ 18.09.2023):

	```
	git clone https://github.com/fastai/fastai
	```
- [PyPi](https://pypi.org/project/fastai) (📥 290K / month):
	```
	pip install fastai
	```
</details>
<details><summary><b><a href="https://github.com/apache/mxnet">MXNet</a></b> (🥈38 ·  ⭐ 21K · 💤) - Lightweight, Portable, Flexible Distributed/Mobile Deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/apache/mxnet) (👨‍💻 980 · 🔀 6.5K · 📥 26K · 📦 6.8K · 📋 9.6K - 18% open · ⏱️ 26.01.2023):

	```
	git clone https://github.com/apache/incubator-mxnet
	```
- [PyPi](https://pypi.org/project/mxnet) (📥 340K / month):
	```
	pip install mxnet
	```
- [Conda](https://anaconda.org/anaconda/mxnet) (📥 10K · ⏱️ 16.06.2023):
	```
	conda install -c anaconda mxnet
	```
</details>
<details><summary><b><a href="https://github.com/google/flax">Flax</a></b> (🥈37 ·  ⭐ 4.8K) - Flax is a neural network library for JAX that is designed for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/flax) (👨‍💻 200 · 🔀 510 · 📥 49 · 📦 4.5K · 📋 740 - 12% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/google/flax
	```
- [PyPi](https://pypi.org/project/flax) (📥 2.2M / month):
	```
	pip install flax
	```
- [Conda](https://anaconda.org/conda-forge/flax) (📥 35K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge flax
	```
</details>
<details><summary><b><a href="https://github.com/explosion/thinc">Thinc</a></b> (🥈36 ·  ⭐ 2.8K) - A refreshing functional take on deep learning, compatible with your favorite.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/thinc) (👨‍💻 62 · 🔀 270 · 📦 38K · 📋 140 - 12% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/explosion/thinc
	```
- [PyPi](https://pypi.org/project/thinc) (📥 5.7M / month):
	```
	pip install thinc
	```
- [Conda](https://anaconda.org/conda-forge/thinc) (📥 2.6M · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge thinc
	```
</details>
<details><summary><b><a href="https://github.com/arogozhnikov/einops">einops</a></b> (🥈35 ·  ⭐ 7.3K) - Deep learning operations reinvented (for pytorch, tensorflow, jax and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/arogozhnikov/einops) (👨‍💻 24 · 🔀 310 · 📦 18K · 📋 150 - 17% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/arogozhnikov/einops
	```
- [PyPi](https://pypi.org/project/einops) (📥 4.3M / month):
	```
	pip install einops
	```
- [Conda](https://anaconda.org/conda-forge/einops) (📥 150K · ⏱️ 01.10.2023):
	```
	conda install -c conda-forge einops
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/ignite">Ignite</a></b> (🥈35 ·  ⭐ 4.3K) - High-level library to help with training and evaluating neural.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/ignite) (👨‍💻 200 · 🔀 590 · 📦 2.4K · 📋 1.3K - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pytorch/ignite
	```
- [PyPi](https://pypi.org/project/pytorch-ignite) (📥 160K / month):
	```
	pip install pytorch-ignite
	```
- [Conda](https://anaconda.org/pytorch/ignite) (📥 160K · ⏱️ 16.06.2023):
	```
	conda install -c pytorch ignite
	```
</details>
<details><summary><b><a href="https://github.com/apache/flink">PyFlink</a></b> (🥈34 ·  ⭐ 22K) - Apache Flink Python API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/flink) (👨‍💻 1.8K · 🔀 12K · 📦 18 · ⏱️ 12.10.2023):

	```
	git clone https://github.com/apache/flink
	```
- [PyPi](https://pypi.org/project/apache-flink) (📥 160K / month):
	```
	pip install apache-flink
	```
</details>
<details><summary><b><a href="https://github.com/chainer/chainer">Chainer</a></b> (🥈34 ·  ⭐ 5.8K · 💤) - A flexible framework of neural networks for deep learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/chainer/chainer) (👨‍💻 330 · 🔀 1.3K · 📦 3.1K · 📋 2K - 0% open · ⏱️ 17.10.2022):

	```
	git clone https://github.com/chainer/chainer
	```
- [PyPi](https://pypi.org/project/chainer) (📥 16K / month):
	```
	pip install chainer
	```
- [Conda](https://anaconda.org/conda-forge/chainer) (📥 16K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge chainer
	```
</details>
<details><summary><b><a href="https://github.com/ludwig-ai/ludwig">Ludwig</a></b> (🥉33 ·  ⭐ 9.9K) - Low-code framework for building custom LLMs, neural networks,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ludwig-ai/ludwig) (👨‍💻 140 · 🔀 1K · 📦 200 · 📋 980 - 25% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/ludwig-ai/ludwig
	```
- [PyPi](https://pypi.org/project/ludwig) (📥 6.7K / month):
	```
	pip install ludwig
	```
</details>
<details><summary><b><a href="https://github.com/VowpalWabbit/vowpal_wabbit">Vowpal Wabbit</a></b> (🥉33 ·  ⭐ 8.3K) - Vowpal Wabbit is a machine learning system which pushes the.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/VowpalWabbit/vowpal_wabbit) (👨‍💻 330 · 🔀 1.9K · 📋 1.3K - 10% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/VowpalWabbit/vowpal_wabbit
	```
- [PyPi](https://pypi.org/project/vowpalwabbit) (📥 94K / month):
	```
	pip install vowpalwabbit
	```
- [Conda](https://anaconda.org/conda-forge/vowpalwabbit) (📥 130K · ⏱️ 08.10.2023):
	```
	conda install -c conda-forge vowpalwabbit
	```
</details>
<details><summary><b><a href="https://github.com/skorch-dev/skorch">skorch</a></b> (🥉32 ·  ⭐ 5.3K) - A scikit-learn compatible neural network library that wraps.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/skorch-dev/skorch) (👨‍💻 60 · 🔀 350 · 📦 960 · 📋 490 - 9% open · ⏱️ 07.09.2023):

	```
	git clone https://github.com/skorch-dev/skorch
	```
- [PyPi](https://pypi.org/project/skorch) (📥 70K / month):
	```
	pip install skorch
	```
- [Conda](https://anaconda.org/conda-forge/skorch) (📥 780K · ⏱️ 06.09.2023):
	```
	conda install -c conda-forge skorch
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/dm-haiku">Haiku</a></b> (🥉32 ·  ⭐ 2.6K) - JAX-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/dm-haiku) (👨‍💻 79 · 🔀 220 · 📦 1.5K · 📋 240 - 28% open · ⏱️ 15.09.2023):

	```
	git clone https://github.com/deepmind/dm-haiku
	```
- [PyPi](https://pypi.org/project/dm-haiku) (📥 270K / month):
	```
	pip install dm-haiku
	```
- [Conda](https://anaconda.org/conda-forge/dm-haiku) (📥 13K · ⏱️ 14.07.2023):
	```
	conda install -c conda-forge dm-haiku
	```
</details>
<details><summary><b><a href="https://github.com/tensorpack/tensorpack">tensorpack</a></b> (🥉31 ·  ⭐ 6.3K) - A Neural Net Training Interface on TensorFlow, with focus.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorpack/tensorpack) (👨‍💻 58 · 🔀 1.8K · 📥 160 · 📦 1.4K · 📋 1.4K - 0% open · ⏱️ 06.08.2023):

	```
	git clone https://github.com/tensorpack/tensorpack
	```
- [PyPi](https://pypi.org/project/tensorpack) (📥 15K / month):
	```
	pip install tensorpack
	```
- [Conda](https://anaconda.org/conda-forge/tensorpack) (📥 10K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tensorpack
	```
</details>
<details><summary><b><a href="https://github.com/ROCmSoftwarePlatform/tensorflow-upstream">tensorflow-upstream</a></b> (🥉31 ·  ⭐ 660) - TensorFlow ROCm port. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ROCmSoftwarePlatform/tensorflow-upstream) (👨‍💻 4.5K · 🔀 79 · 📥 21 · 📋 350 - 21% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/ROCmSoftwarePlatform/tensorflow-upstream
	```
- [PyPi](https://pypi.org/project/tensorflow-rocm) (📥 3.5K / month):
	```
	pip install tensorflow-rocm
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/sonnet">Sonnet</a></b> (🥉30 ·  ⭐ 9.6K) - TensorFlow-based neural network library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-deepmind/sonnet) (👨‍💻 58 · 🔀 1.3K · 📦 1.2K · 📋 190 - 16% open · ⏱️ 21.07.2023):

	```
	git clone https://github.com/deepmind/sonnet
	```
- [PyPi](https://pypi.org/project/dm-sonnet) (📥 15K / month):
	```
	pip install dm-sonnet
	```
- [Conda](https://anaconda.org/conda-forge/sonnet) (📥 26K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge sonnet
	```
</details>
<details><summary><b><a href="https://github.com/amaiya/ktrain">ktrain</a></b> (🥉30 ·  ⭐ 1.2K) - ktrain is a Python library that makes deep learning and AI more.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/amaiya/ktrain) (👨‍💻 16 · 🔀 260 · 📦 460 · 📋 480 - 0% open · ⏱️ 05.09.2023):

	```
	git clone https://github.com/amaiya/ktrain
	```
- [PyPi](https://pypi.org/project/ktrain) (📥 20K / month):
	```
	pip install ktrain
	```
</details>
<details><summary><b><a href="https://github.com/sony/nnabla">Neural Network Libraries</a></b> (🥉27 ·  ⭐ 2.6K) - Neural Network Libraries. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/sony/nnabla) (👨‍💻 73 · 🔀 330 · 📥 710 · 📋 79 - 25% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/sony/nnabla
	```
- [PyPi](https://pypi.org/project/nnabla) (📥 3.4K / month):
	```
	pip install nnabla
	```
</details>
<details><summary><b><a href="https://github.com/google/neural-tangents">Neural Tangents</a></b> (🥉27 ·  ⭐ 2.1K) - Fast and Easy Infinite Neural Networks in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/neural-tangents) (👨‍💻 27 · 🔀 230 · 📥 330 · 📦 81 · 📋 140 - 36% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/google/neural-tangents
	```
- [PyPi](https://pypi.org/project/neural-tangents) (📥 2.2K / month):
	```
	pip install neural-tangents
	```
</details>
<details><summary><b><a href="https://github.com/towhee-io/towhee">Towhee</a></b> (🥉26 ·  ⭐ 2.7K) - Towhee is a framework that is dedicated to making neural data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/towhee-io/towhee) (👨‍💻 33 · 🔀 230 · 📥 2.6K · 📋 640 - 0% open · ⏱️ 15.09.2023):

	```
	git clone https://github.com/towhee-io/towhee
	```
- [PyPi](https://pypi.org/project/towhee) (📥 4.5K / month):
	```
	pip install towhee
	```
</details>
<details><summary><b><a href="https://github.com/nubank/fklearn">fklearn</a></b> (🥉24 ·  ⭐ 1.5K) - fklearn: Functional Machine Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nubank/fklearn) (👨‍💻 52 · 🔀 160 · 📦 13 · 📋 50 - 52% open · ⏱️ 11.04.2023):

	```
	git clone https://github.com/nubank/fklearn
	```
- [PyPi](https://pypi.org/project/fklearn) (📥 2.5K / month):
	```
	pip install fklearn
	```
</details>
<details><summary><b><a href="https://github.com/itdxer/neupy">NeuPy</a></b> (🥉24 ·  ⭐ 740 · 💤) - NeuPy is a Tensorflow based python library for prototyping and building.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/itdxer/neupy) (👨‍💻 8 · 🔀 160 · 📦 160 · 📋 270 - 12% open · ⏱️ 03.01.2023):

	```
	git clone https://github.com/itdxer/neupy
	```
- [PyPi](https://pypi.org/project/neupy) (📥 5.5K / month):
	```
	pip install neupy
	```
</details>
<details><summary><b><a href="https://github.com/neoml-lib/neoml">NeoML</a></b> (🥉21 ·  ⭐ 740) - Machine learning framework for both deep learning and traditional.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neoml-lib/neoml) (👨‍💻 34 · 🔀 120 · 📋 65 - 23% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/neoml-lib/neoml
	```
- [PyPi](https://pypi.org/project/neoml) (📥 1K / month):
	```
	pip install neoml
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundersvm">ThunderSVM</a></b> (🥉20 ·  ⭐ 1.5K) - ThunderSVM: A Fast SVM Library on GPUs and CPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundersvm) (👨‍💻 35 · 🔀 200 · 📥 2.7K · 📋 220 - 32% open · ⏱️ 15.09.2023):

	```
	git clone https://github.com/Xtra-Computing/thundersvm
	```
- [PyPi](https://pypi.org/project/thundersvm) (📥 300 / month):
	```
	pip install thundersvm
	```
</details>
<details><summary><b><a href="https://github.com/serengil/chefboost">chefboost</a></b> (🥉17 ·  ⭐ 420) - A Lightweight Decision Tree Framework supporting regular algorithms:.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/chefboost) (👨‍💻 6 · 🔀 95 · 📦 48 · 📋 30 - 10% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/serengil/chefboost
	```
- [PyPi](https://pypi.org/project/chefboost) (📥 430 / month):
	```
	pip install chefboost
	```
</details>
<details><summary><b><a href="https://github.com/Xtra-Computing/thundergbm">ThunderGBM</a></b> (🥉16 ·  ⭐ 680) - ThunderGBM: Fast GBDTs and Random Forests on GPUs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Xtra-Computing/thundergbm) (👨‍💻 11 · 🔀 81 · 📦 2 · 📋 78 - 46% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/Xtra-Computing/thundergbm
	```
- [PyPi](https://pypi.org/project/thundergbm) (📥 76 / month):
	```
	pip install thundergbm
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/davisking/dlib">dlib</a></b> (🥈40 ·  ⭐ 12K) - A toolkit for making real world machine learning and data analysis.. <code><a href="https://tldrlegal.com/search?q=BSL-1.0">❗️BSL-1.0</a></code>
- <b><a href="https://github.com/Theano/Theano">Theano</a></b> (🥈34 ·  ⭐ 9.8K · 💤) - Theano was a Python library that allows you to define,.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mindsdb/mindsdb">MindsDB</a></b> (🥉33 ·  ⭐ 18K) - MindsDB connects AI models to datasources. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/apple/turicreate">Turi Create</a></b> (🥉32 ·  ⭐ 11K · 💀) - Turi Create simplifies the development of custom machine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/clab/dynet">dyNET</a></b> (🥉32 ·  ⭐ 3.4K · 💀) - DyNet: The Dynamic Neural Network Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/tflearn/tflearn">TFlearn</a></b> (🥉31 ·  ⭐ 9.6K · 💀) - Deep learning library featuring a higher-level API for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mlpack/mlpack">mlpack</a></b> (🥉30 ·  ⭐ 4.6K) - mlpack: a fast, header-only C++ machine learning library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/numenta/nupic-legacy">NuPIC</a></b> (🥉27 ·  ⭐ 6.3K) - Numenta Platform for Intelligent Computing is an implementation of.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/microsoft/CNTK">CNTK</a></b> (🥉26 ·  ⭐ 17K · 💀) - Microsoft Cognitive Toolkit (CNTK), an open source deep-learning.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/aksnzhy/xlearn">xLearn</a></b> (🥉26 ·  ⭐ 3.1K · 💀) - High performance, easy-to-use, and scalable machine learning (ML).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/shogun-toolbox/shogun">SHOGUN</a></b> (🥉26 ·  ⭐ 3K · 💀) - Unified and efficient Machine Learning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Lasagne/Lasagne">Lasagne</a></b> (🥉25 ·  ⭐ 3.8K · 💀) - Lightweight library to build and train neural networks in.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/XiaoMi/mace">mace</a></b> (🥉22 ·  ⭐ 4.8K · 💀) - MACE is a deep learning inference framework optimized for mobile.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/NervanaSystems/neon">neon</a></b> (🥉22 ·  ⭐ 3.9K · 💀) - Intel Nervana reference deep learning framework committed to best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/google/objax">Objax</a></b> (🥉21 ·  ⭐ 740) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pytorchbearer/torchbearer">Torchbearer</a></b> (🥉21 ·  ⭐ 630 · 💀) - torchbearer: A model fitting library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/poets-ai/elegy">elegy</a></b> (🥉17 ·  ⭐ 450 · 💀) - A High Level API for Deep Learning in JAX. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/StarSpace">StarSpace</a></b> (🥉16 ·  ⭐ 3.9K · 💀) - Learning embeddings for classification, retrieval and ranking. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Data Visualization

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose and task-specific data visualization libraries._

<details><summary><b><a href="https://github.com/matplotlib/matplotlib">Matplotlib</a></b> (🥇48 ·  ⭐ 18K) - matplotlib: plotting with Python. <code>❗Unlicensed</code></summary>

- [GitHub](https://github.com/matplotlib/matplotlib) (👨‍💻 1.6K · 🔀 7K · 📦 970K · 📋 9.8K - 12% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/matplotlib/matplotlib
	```
- [PyPi](https://pypi.org/project/matplotlib) (📥 40M / month):
	```
	pip install matplotlib
	```
- [Conda](https://anaconda.org/conda-forge/matplotlib) (📥 21M · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge matplotlib
	```
</details>
<details><summary><b><a href="https://github.com/plotly/plotly.py">Plotly</a></b> (🥇44 ·  ⭐ 14K) - The interactive graphing library for Python This project now includes.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/plotly.py) (👨‍💻 240 · 🔀 2.4K · 📦 210K · 📋 2.7K - 50% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/plotly/plotly.py
	```
- [PyPi](https://pypi.org/project/plotly) (📥 11M / month):
	```
	pip install plotly
	```
- [Conda](https://anaconda.org/conda-forge/plotly) (📥 4.9M · ⏱️ 15.09.2023):
	```
	conda install -c conda-forge plotly
	```
- [npm](https://www.npmjs.com/package/plotlywidget) (📥 38K / month):
	```
	npm install plotlywidget
	```
</details>
<details><summary><b><a href="https://github.com/bokeh/bokeh">Bokeh</a></b> (🥇43 ·  ⭐ 18K) - Interactive Data Visualization in the browser, from Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bokeh/bokeh) (👨‍💻 670 · 🔀 4K · 📦 77K · 📋 7.4K - 9% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/bokeh/bokeh
	```
- [PyPi](https://pypi.org/project/bokeh) (📥 3.5M / month):
	```
	pip install bokeh
	```
- [Conda](https://anaconda.org/conda-forge/bokeh) (📥 13M · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge bokeh
	```
</details>
<details><summary><b><a href="https://github.com/mwaskom/seaborn">Seaborn</a></b> (🥇43 ·  ⭐ 11K) - Statistical data visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mwaskom/seaborn) (👨‍💻 200 · 🔀 1.7K · 📥 280 · 📦 310K · 📋 2.4K - 4% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/mwaskom/seaborn
	```
- [PyPi](https://pypi.org/project/seaborn) (📥 10M / month):
	```
	pip install seaborn
	```
- [Conda](https://anaconda.org/conda-forge/seaborn) (📥 7.6M · ⏱️ 02.10.2023):
	```
	conda install -c conda-forge seaborn
	```
</details>
<details><summary><b><a href="https://github.com/altair-viz/altair">Altair</a></b> (🥇42 ·  ⭐ 8.5K) - Declarative statistical visualization library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/altair-viz/altair) (👨‍💻 160 · 🔀 700 · 📥 88 · 📦 79K · 📋 1.9K - 8% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/altair-viz/altair
	```
- [PyPi](https://pypi.org/project/altair) (📥 15M / month):
	```
	pip install altair
	```
- [Conda](https://anaconda.org/conda-forge/altair) (📥 2M · ⏱️ 03.10.2023):
	```
	conda install -c conda-forge altair
	```
</details>
<details><summary><b><a href="https://github.com/plotly/dash">dash</a></b> (🥇40 ·  ⭐ 19K) - Data Apps & Dashboards for Python. No JavaScript Required. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/plotly/dash) (👨‍💻 140 · 🔀 1.9K · 📦 53K · 📋 1.6K - 47% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/plotly/dash
	```
- [PyPi](https://pypi.org/project/dash) (📥 2.2M / month):
	```
	pip install dash
	```
- [Conda](https://anaconda.org/conda-forge/dash) (📥 1.1M · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge dash
	```
</details>
<details><summary><b><a href="https://github.com/ydataai/ydata-profiling">pandas-profiling</a></b> (🥈37 ·  ⭐ 11K) - 1 Line of code data quality profiling & exploratory.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ydataai/ydata-profiling) (👨‍💻 120 · 🔀 1.5K · 📦 1.5K · 📋 730 - 24% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/ydataai/pandas-profiling
	```
- [PyPi](https://pypi.org/project/pandas-profiling) (📥 700K / month):
	```
	pip install pandas-profiling
	```
- [Conda](https://anaconda.org/conda-forge/pandas-profiling) (📥 400K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pandas-profiling
	```
</details>
<details><summary><b><a href="https://github.com/pyecharts/pyecharts">pyecharts</a></b> (🥈36 ·  ⭐ 14K) - Python Echarts Plotting Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyecharts/pyecharts) (👨‍💻 39 · 🔀 2.8K · 📦 3.5K · 📋 1.8K - 0% open · ⏱️ 21.08.2023):

	```
	git clone https://github.com/pyecharts/pyecharts
	```
- [PyPi](https://pypi.org/project/pyecharts) (📥 110K / month):
	```
	pip install pyecharts
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/umap">UMAP</a></b> (🥈36 ·  ⭐ 6.5K) - Uniform Manifold Approximation and Projection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/lmcinnes/umap) (👨‍💻 120 · 🔀 720 · 📦 11K · 📋 740 - 55% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/lmcinnes/umap
	```
- [PyPi](https://pypi.org/project/umap-learn) (📥 970K / month):
	```
	pip install umap-learn
	```
- [Conda](https://anaconda.org/conda-forge/umap-learn) (📥 2.2M · ⏱️ 16.09.2023):
	```
	conda install -c conda-forge umap-learn
	```
</details>
<details><summary><b><a href="https://github.com/has2k1/plotnine">plotnine</a></b> (🥈35 ·  ⭐ 3.6K) - A Grammar of Graphics for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/has2k1/plotnine) (👨‍💻 100 · 🔀 200 · 📦 5.9K · 📋 580 - 12% open · ⏱️ 08.08.2023):

	```
	git clone https://github.com/has2k1/plotnine
	```
- [PyPi](https://pypi.org/project/plotnine) (📥 1.2M / month):
	```
	pip install plotnine
	```
- [Conda](https://anaconda.org/conda-forge/plotnine) (📥 310K · ⏱️ 01.09.2023):
	```
	conda install -c conda-forge plotnine
	```
</details>
<details><summary><b><a href="https://github.com/voxel51/fiftyone">FiftyOne</a></b> (🥈34 ·  ⭐ 5.2K) - Visualize, create, and debug image and video datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/voxel51/fiftyone) (👨‍💻 96 · 🔀 420 · 📦 410 · 📋 1.3K - 30% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/voxel51/fiftyone
	```
- [PyPi](https://pypi.org/project/fiftyone) (📥 41K / month):
	```
	pip install fiftyone
	```
</details>
<details><summary><b><a href="https://github.com/pyvista/pyvista">PyVista</a></b> (🥈34 ·  ⭐ 2K) - 3D plotting and mesh analysis through a streamlined interface for the.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyvista/pyvista) (👨‍💻 140 · 🔀 380 · 📥 780 · 📦 2.3K · 📋 1.3K - 27% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pyvista/pyvista
	```
- [PyPi](https://pypi.org/project/pyvista) (📥 200K / month):
	```
	pip install pyvista
	```
- [Conda](https://anaconda.org/conda-forge/pyvista) (📥 410K · ⏱️ 07.10.2023):
	```
	conda install -c conda-forge pyvista
	```
</details>
<details><summary><b><a href="https://github.com/xflr6/graphviz">Graphviz</a></b> (🥈34 ·  ⭐ 1.5K) - Simple Python interface for Graphviz. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/xflr6/graphviz) (👨‍💻 19 · 🔀 200 · 📦 54K · 📋 160 - 4% open · ⏱️ 22.07.2023):

	```
	git clone https://github.com/xflr6/graphviz
	```
- [PyPi](https://pypi.org/project/graphviz) (📥 8M / month):
	```
	pip install graphviz
	```
- [Conda](https://anaconda.org/anaconda/python-graphviz) (📥 41K · ⏱️ 16.06.2023):
	```
	conda install -c anaconda python-graphviz
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/datashader">datashader</a></b> (🥈33 ·  ⭐ 3.1K) - Quickly and accurately render even the largest data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/datashader) (👨‍💻 53 · 🔀 350 · 📦 3K · 📋 560 - 22% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/holoviz/datashader
	```
- [PyPi](https://pypi.org/project/datashader) (📥 75K / month):
	```
	pip install datashader
	```
- [Conda](https://anaconda.org/conda-forge/datashader) (📥 690K · ⏱️ 17.08.2023):
	```
	conda install -c conda-forge datashader
	```
</details>
<details><summary><b><a href="https://github.com/finos/perspective">Perspective</a></b> (🥈32 ·  ⭐ 6.8K) - A data visualization and analytics component, especially.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/finos/perspective) (👨‍💻 92 · 🔀 830 · 📥 1.3K · 📦 620 · 📋 670 - 14% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/finos/perspective
	```
- [PyPi](https://pypi.org/project/perspective-python) (📥 6.8K / month):
	```
	pip install perspective-python
	```
- [Conda](https://anaconda.org/conda-forge/perspective) (📥 460K · ⏱️ 09.10.2023):
	```
	conda install -c conda-forge perspective
	```
- [npm](https://www.npmjs.com/package/@finos/perspective-jupyterlab) (📥 2.3K / month):
	```
	npm install @finos/perspective-jupyterlab
	```
</details>
<details><summary><b><a href="https://github.com/man-group/dtale">D-Tale</a></b> (🥈31 ·  ⭐ 4.3K) - Visualizer for pandas data structures. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/man-group/dtale) (👨‍💻 30 · 🔀 350 · 📦 890 · 📋 540 - 9% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/man-group/dtale
	```
- [PyPi](https://pypi.org/project/dtale) (📥 100K / month):
	```
	pip install dtale
	```
- [Conda](https://anaconda.org/conda-forge/dtale) (📥 250K · ⏱️ 02.10.2023):
	```
	conda install -c conda-forge dtale
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/holoviews">HoloViews</a></b> (🥈31 ·  ⭐ 2.5K) - With Holoviews, your data visualizes itself. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/holoviz/holoviews) (👨‍💻 140 · 🔀 370 · 📋 3.1K - 32% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/holoviz/holoviews
	```
- [PyPi](https://pypi.org/project/holoviews) (📥 300K / month):
	```
	pip install holoviews
	```
- [Conda](https://anaconda.org/conda-forge/holoviews) (📥 1.4M · ⏱️ 17.08.2023):
	```
	conda install -c conda-forge holoviews
	```
- [npm](https://www.npmjs.com/package/@pyviz/jupyterlab_pyviz) (📥 980 / month):
	```
	npm install @pyviz/jupyterlab_pyviz
	```
</details>
<details><summary><b><a href="https://github.com/JetBrains/lets-plot">lets-plot</a></b> (🥈31 ·  ⭐ 1.2K) - Multiplatform plotting library based on Grammar of Graphics. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/JetBrains/lets-plot) (👨‍💻 20 · 🔀 45 · 📥 540 · 📦 48 · 📋 440 - 26% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/JetBrains/lets-plot
	```
- [PyPi](https://pypi.org/project/lets-plot) (📥 28K / month):
	```
	pip install lets-plot
	```
</details>
<details><summary><b><a href="https://github.com/amueller/word_cloud">wordcloud</a></b> (🥉30 ·  ⭐ 9.7K) - A little word cloud generator in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/amueller/word_cloud) (👨‍💻 69 · 🔀 2.2K · 📦 18 · 📋 500 - 18% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/amueller/word_cloud
	```
- [PyPi](https://pypi.org/project/wordcloud) (📥 1.4M / month):
	```
	pip install wordcloud
	```
- [Conda](https://anaconda.org/conda-forge/wordcloud) (📥 440K · ⏱️ 07.07.2023):
	```
	conda install -c conda-forge wordcloud
	```
</details>
<details><summary><b><a href="https://github.com/bqplot/bqplot">bqplot</a></b> (🥉30 ·  ⭐ 3.5K) - Plotting library for IPython/Jupyter notebooks. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bqplot/bqplot) (👨‍💻 64 · 🔀 450 · 📦 49 · 📋 590 - 37% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/bqplot/bqplot
	```
- [PyPi](https://pypi.org/project/bqplot) (📥 140K / month):
	```
	pip install bqplot
	```
- [Conda](https://anaconda.org/conda-forge/bqplot) (📥 1.2M · ⏱️ 12.07.2023):
	```
	conda install -c conda-forge bqplot
	```
- [npm](https://www.npmjs.com/package/bqplot) (📥 5.3K / month):
	```
	npm install bqplot
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/hvplot">hvPlot</a></b> (🥉30 ·  ⭐ 810) - A high-level plotting API for pandas, dask, xarray, and networkx built on.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/hvplot) (👨‍💻 43 · 🔀 86 · 📦 3.7K · 📋 660 - 42% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/holoviz/hvplot
	```
- [PyPi](https://pypi.org/project/hvplot) (📥 120K / month):
	```
	pip install hvplot
	```
- [Conda](https://anaconda.org/conda-forge/hvplot) (📥 480K · ⏱️ 20.06.2023):
	```
	conda install -c conda-forge hvplot
	```
</details>
<details><summary><b><a href="https://github.com/fbdesignpro/sweetviz">Sweetviz</a></b> (🥉29 ·  ⭐ 2.6K) - Visualize and compare datasets, target values and associations, with one.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fbdesignpro/sweetviz) (👨‍💻 9 · 🔀 260 · 📦 1.7K · 📋 120 - 28% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/fbdesignpro/sweetviz
	```
- [PyPi](https://pypi.org/project/sweetviz) (📥 72K / month):
	```
	pip install sweetviz
	```
- [Conda](https://anaconda.org/conda-forge/sweetviz) (📥 25K · ⏱️ 28.08.2023):
	```
	conda install -c conda-forge sweetviz
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/data-validation">data-validation</a></b> (🥉29 ·  ⭐ 730) - Library for exploring and validating machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/data-validation) (👨‍💻 25 · 🔀 150 · 📥 470 · 📦 740 · 📋 160 - 14% open · ⏱️ 27.09.2023):

	```
	git clone https://github.com/tensorflow/data-validation
	```
- [PyPi](https://pypi.org/project/tensorflow-data-validation) (📥 370K / month):
	```
	pip install tensorflow-data-validation
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/facets">Facets Overview</a></b> (🥉28 ·  ⭐ 7.2K) - Visualizations for machine learning datasets. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PAIR-code/facets) (👨‍💻 31 · 🔀 870 · 📦 200 · 📋 160 - 49% open · ⏱️ 24.05.2023):

	```
	git clone https://github.com/pair-code/facets
	```
- [PyPi](https://pypi.org/project/facets-overview) (📥 190K / month):
	```
	pip install facets-overview
	```
</details>
<details><summary><b><a href="https://github.com/ResidentMario/missingno">missingno</a></b> (🥉28 ·  ⭐ 3.7K · 💤) - Missing data visualization module for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ResidentMario/missingno) (👨‍💻 18 · 🔀 440 · 📦 13K · 📋 130 - 6% open · ⏱️ 26.02.2023):

	```
	git clone https://github.com/ResidentMario/missingno
	```
- [PyPi](https://pypi.org/project/missingno) (📥 370K / month):
	```
	pip install missingno
	```
- [Conda](https://anaconda.org/conda-forge/missingno) (📥 310K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge missingno
	```
</details>
<details><summary><b><a href="https://github.com/pavlin-policar/openTSNE">openTSNE</a></b> (🥉26 ·  ⭐ 1.3K) - Extensible, parallel implementations of t-SNE. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pavlin-policar/openTSNE) (👨‍💻 11 · 🔀 140 · 📦 660 · 📋 130 - 1% open · ⏱️ 21.08.2023):

	```
	git clone https://github.com/pavlin-policar/openTSNE
	```
- [PyPi](https://pypi.org/project/opentsne) (📥 32K / month):
	```
	pip install opentsne
	```
- [Conda](https://anaconda.org/conda-forge/opentsne) (📥 230K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge opentsne
	```
</details>
<details><summary><b><a href="https://github.com/spotify/chartify">Chartify</a></b> (🥉25 ·  ⭐ 3.4K) - Python library that makes it easy for data scientists to create.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/chartify) (👨‍💻 25 · 🔀 300 · 📦 73 · 📋 75 - 57% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/spotify/chartify
	```
- [PyPi](https://pypi.org/project/chartify) (📥 2.1K / month):
	```
	pip install chartify
	```
- [Conda](https://anaconda.org/conda-forge/chartify) (📥 29K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge chartify
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/AutoViz">AutoViz</a></b> (🥉25 ·  ⭐ 1.5K) - Automatically Visualize any dataset, any size with a single line of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/AutoViz) (👨‍💻 14 · 🔀 180 · 📦 560 · 📋 78 - 2% open · ⏱️ 04.07.2023):

	```
	git clone https://github.com/AutoViML/AutoViz
	```
- [PyPi](https://pypi.org/project/autoviz) (📥 160K / month):
	```
	pip install autoviz
	```
- [Conda](https://anaconda.org/conda-forge/autoviz) (📥 42K · ⏱️ 21.07.2023):
	```
	conda install -c conda-forge autoviz
	```
</details>
<details><summary><b><a href="https://github.com/PatrikHlobil/Pandas-Bokeh">Pandas-Bokeh</a></b> (🥉24 ·  ⭐ 860 · 💤) - Bokeh Plotting Backend for Pandas and GeoPandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PatrikHlobil/Pandas-Bokeh) (👨‍💻 15 · 🔀 110 · 📦 530 · 📋 100 - 33% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/PatrikHlobil/Pandas-Bokeh
	```
- [PyPi](https://pypi.org/project/pandas-bokeh) (📥 30K / month):
	```
	pip install pandas-bokeh
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/hiplot">HiPlot</a></b> (🥉23 ·  ⭐ 2.6K) - HiPlot makes understanding high dimensional data easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/hiplot) (👨‍💻 9 · 🔀 130 · 📦 310 · 📋 85 - 14% open · ⏱️ 19.07.2023):

	```
	git clone https://github.com/facebookresearch/hiplot
	```
- [PyPi](https://pypi.org/project/hiplot) (📥 24K / month):
	```
	pip install hiplot
	```
- [Conda](https://anaconda.org/conda-forge/hiplot) (📥 160K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge hiplot
	```
</details>
<details><summary><b><a href="https://github.com/DmitryUlyanov/Multicore-TSNE">Multicore-TSNE</a></b> (🥉23 ·  ⭐ 1.8K) - Parallel t-SNE implementation with Python and Torch.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DmitryUlyanov/Multicore-TSNE) (👨‍💻 17 · 🔀 200 · 📦 410 · 📋 59 - 64% open · ⏱️ 26.05.2023):

	```
	git clone https://github.com/DmitryUlyanov/Multicore-TSNE
	```
- [PyPi](https://pypi.org/project/MulticoreTSNE) (📥 30K / month):
	```
	pip install MulticoreTSNE
	```
- [Conda](https://anaconda.org/conda-forge/multicore-tsne) (📥 29K · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge multicore-tsne
	```
</details>
<details><summary><b><a href="https://github.com/marcharper/python-ternary">python-ternary</a></b> (🥉22 ·  ⭐ 650) - Ternary plotting library for python with matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/marcharper/python-ternary) (👨‍💻 27 · 🔀 150 · 📥 25 · 📦 150 · 📋 130 - 21% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/marcharper/python-ternary
	```
- [PyPi](https://pypi.org/project/python-ternary) (📥 37K / month):
	```
	pip install python-ternary
	```
- [Conda](https://anaconda.org/conda-forge/python-ternary) (📥 78K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge python-ternary
	```
</details>
<details><summary><b><a href="https://github.com/ing-bank/popmon">Popmon</a></b> (🥉21 ·  ⭐ 470) - Monitor the stability of a Pandas or Spark dataframe. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ing-bank/popmon) (👨‍💻 17 · 🔀 34 · 📥 120 · 📦 20 · 📋 53 - 24% open · ⏱️ 18.07.2023):

	```
	git clone https://github.com/ing-bank/popmon
	```
- [PyPi](https://pypi.org/project/popmon) (📥 7.9K / month):
	```
	pip install popmon
	```
</details>
<details><summary><b><a href="https://github.com/vega/ipyvega">vega</a></b> (🥉21 ·  ⭐ 360) - IPython/Jupyter notebook module for Vega and Vega-Lite. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/vega/ipyvega) (👨‍💻 15 · 🔀 60 · 📦 2 · 📋 100 - 10% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/vega/ipyvega
	```
- [PyPi](https://pypi.org/project/vega) (📥 12K / month):
	```
	pip install vega
	```
- [Conda](https://anaconda.org/conda-forge/vega) (📥 570K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge vega
	```
</details>
<details><summary><b><a href="https://github.com/SauceCat/PDPbox">PDPbox</a></b> (🥉19 ·  ⭐ 780) - python partial dependence plot toolbox. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SauceCat/PDPbox) (👨‍💻 7 · 🔀 130 · 📋 65 - 40% open · ⏱️ 05.06.2023):

	```
	git clone https://github.com/SauceCat/PDPbox
	```
- [PyPi](https://pypi.org/project/pdpbox) (📥 25K / month):
	```
	pip install pdpbox
	```
- [Conda](https://anaconda.org/conda-forge/pdpbox) (📥 19K · ⏱️ 10.06.2023):
	```
	conda install -c conda-forge pdpbox
	```
</details>
<details><summary><b><a href="https://github.com/beringresearch/ivis">ivis</a></b> (🥉17 ·  ⭐ 300 · 💤) - Dimensionality reduction in very large datasets using Siamese.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/beringresearch/ivis) (👨‍💻 10 · 🔀 39 · 📦 30 · 📋 59 - 5% open · ⏱️ 11.01.2023):

	```
	git clone https://github.com/beringresearch/ivis
	```
- [PyPi](https://pypi.org/project/ivis) (📥 200 / month):
	```
	pip install ivis
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/SciTools/cartopy">cartopy</a></b> (🥈34 ·  ⭐ 1.3K) - Cartopy - a cartographic python library with matplotlib support. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/vispy/vispy">VisPy</a></b> (🥈33 ·  ⭐ 3.1K) - High-performance interactive 2D/3D data visualization library. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pyqtgraph/pyqtgraph">PyQtGraph</a></b> (🥈32 ·  ⭐ 3.4K) - Fast data visualization and GUI tools for scientific /.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/santosjorge/cufflinks">Cufflinks</a></b> (🥉27 ·  ⭐ 2.9K · 💀) - Productivity Tools for Plotly + Pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ContextLab/hypertools">HyperTools</a></b> (🥉26 ·  ⭐ 1.8K · 💀) - A Python toolbox for gaining geometric insights into high-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jupyter-widgets/pythreejs">pythreejs</a></b> (🥉24 ·  ⭐ 900 · 💤) - A Jupyter - Three.js bridge. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adamerose/PandasGUI">PandasGUI</a></b> (🥉23 ·  ⭐ 3K · 💀) - A GUI for Pandas DataFrames. <code><a href="https://tldrlegal.com/search?q=MIT-0">❗️MIT-0</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/nicolaskruchten/jupyter_pivottablejs">pivottablejs</a></b> (🥉21 ·  ⭐ 600 · 💀) - Dragndrop Pivot Tables and Charts for Jupyter/IPython.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/leotac/joypy">joypy</a></b> (🥉20 ·  ⭐ 500 · 💀) - Joyplots in Python with matplotlib & pandas. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/gyli/PyWaffle">PyWaffle</a></b> (🥉19 ·  ⭐ 560 · 💀) - Make Waffle Charts in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/t-makaro/animatplot">animatplot</a></b> (🥉18 ·  ⭐ 400 · 💀) - A python package for animating plots build on matplotlib. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/altair-viz/pdvega">pdvega</a></b> (🥉16 ·  ⭐ 350 · 💀) - Interactive plotting for Pandas using Vega-Lite. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/data-describe/data-describe">data-describe</a></b> (🥉15 ·  ⭐ 300 · 💀) - datadescribe: Pythonic EDA Accelerator for Data.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Zsailer/nx_altair">nx-altair</a></b> (🥉13 ·  ⭐ 220 · 💀) - Draw interactive NetworkX graphs with Altair. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/biovault/nptsne">nptsne</a></b> (🥉10 ·  ⭐ 31 · 💀) - nptsne is a numpy compatible python binary package that offers a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Text Data & NLP

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing, cleaning, manipulating, and analyzing text data as well as libraries for NLP tasks such as language detection, fuzzy matching, classification, seq2seq learning, conversational AI, keyword extraction, and translation._

<details><summary><b><a href="https://github.com/huggingface/transformers">transformers</a></b> (🥇50 ·  ⭐ 110K) - Transformers: State-of-the-art Machine Learning for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/transformers) (👨‍💻 2.2K · 🔀 22K · 📥 140 · 📦 110K · 📋 13K - 5% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/huggingface/transformers
	```
- [PyPi](https://pypi.org/project/transformers) (📥 18M / month):
	```
	pip install transformers
	```
- [Conda](https://anaconda.org/conda-forge/transformers) (📥 1.4M · ⏱️ 07.10.2023):
	```
	conda install -c conda-forge transformers
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spaCy">spaCy</a></b> (🥇44 ·  ⭐ 27K) - Industrial-strength Natural Language Processing (NLP) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/spaCy) (👨‍💻 740 · 🔀 4.1K · 📦 71K · 📋 5.5K - 1% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/explosion/spaCy
	```
- [PyPi](https://pypi.org/project/spacy) (📥 6.6M / month):
	```
	pip install spacy
	```
- [Conda](https://anaconda.org/conda-forge/spacy) (📥 3.2M · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge spacy
	```
</details>
<details><summary><b><a href="https://github.com/RasaHQ/rasa">Rasa</a></b> (🥇41 ·  ⭐ 17K) - Open source machine learning framework to automate text- and voice-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RasaHQ/rasa) (👨‍💻 590 · 🔀 4.3K · 📦 3.7K · 📋 6.6K - 0% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/RasaHQ/rasa
	```
- [PyPi](https://pypi.org/project/rasa) (📥 120K / month):
	```
	pip install rasa
	```
</details>
<details><summary><b><a href="https://github.com/RaRe-Technologies/gensim">gensim</a></b> (🥇41 ·  ⭐ 15K) - Topic Modelling for Humans. <code><a href="https://tldrlegal.com/search?q=LGPL-2.1">❗️LGPL-2.1</a></code></summary>

- [GitHub](https://github.com/RaRe-Technologies/gensim) (👨‍💻 450 · 🔀 4.1K · 📥 4.5K · 📦 51K · 📋 1.8K - 20% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/RaRe-Technologies/gensim
	```
- [PyPi](https://pypi.org/project/gensim) (📥 4M / month):
	```
	pip install gensim
	```
- [Conda](https://anaconda.org/conda-forge/gensim) (📥 1.2M · ⏱️ 24.08.2023):
	```
	conda install -c conda-forge gensim
	```
</details>
<details><summary><b><a href="https://github.com/nltk/nltk">nltk</a></b> (🥇40 ·  ⭐ 12K) - Suite of libraries and programs for symbolic and statistical natural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nltk/nltk) (👨‍💻 440 · 🔀 2.7K · 📦 220K · 📋 1.7K - 14% open · ⏱️ 28.09.2023):

	```
	git clone https://github.com/nltk/nltk
	```
- [PyPi](https://pypi.org/project/nltk) (📥 12M / month):
	```
	pip install nltk
	```
- [Conda](https://anaconda.org/conda-forge/nltk) (📥 2.3M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge nltk
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/tokenizers">Tokenizers</a></b> (🥇38 ·  ⭐ 7.7K) - Fast State-of-the-Art Tokenizers optimized for Research and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/tokenizers) (👨‍💻 79 · 🔀 620 · 📥 33 · 📦 44K · 📋 830 - 30% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/huggingface/tokenizers
	```
- [PyPi](https://pypi.org/project/tokenizers) (📥 14M / month):
	```
	pip install tokenizers
	```
- [Conda](https://anaconda.org/conda-forge/tokenizers) (📥 1.3M · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge tokenizers
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairseq">fairseq</a></b> (🥇37 ·  ⭐ 28K) - Facebook AI Research Sequence-to-Sequence Toolkit written in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairseq) (👨‍💻 420 · 🔀 5.9K · 📥 320 · 📦 2.1K · 📋 4K - 24% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/pytorch/fairseq
	```
- [PyPi](https://pypi.org/project/fairseq) (📥 550K / month):
	```
	pip install fairseq
	```
- [Conda](https://anaconda.org/conda-forge/fairseq) (📥 50K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge fairseq
	```
</details>
<details><summary><b><a href="https://github.com/deepset-ai/haystack">haystack</a></b> (🥇37 ·  ⭐ 11K) - LLM orchestration framework to build customizable, production-ready.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/deepset-ai/haystack) (👨‍💻 200 · 🔀 1.4K · 📥 23 · 📦 950 · 📋 2.6K - 16% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/deepset-ai/haystack
	```
- [PyPi](https://pypi.org/project/haystack) (📥 2.2K / month):
	```
	pip install haystack
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/NeMo">NeMo</a></b> (🥇36 ·  ⭐ 8.1K · 📈) - NeMo: a toolkit for conversational AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/NeMo) (👨‍💻 250 · 🔀 1.7K · 📥 81K · 📦 18 · 📋 1.8K - 2% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/NVIDIA/NeMo
	```
- [PyPi](https://pypi.org/project/nemo-toolkit) (📥 43K / month):
	```
	pip install nemo-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/JohnSnowLabs/spark-nlp">spark-nlp</a></b> (🥇36 ·  ⭐ 3.5K) - State of the Art Natural Language Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/JohnSnowLabs/spark-nlp) (👨‍💻 110 · 🔀 660 · 📦 340 · 📋 820 - 3% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/JohnSnowLabs/spark-nlp
	```
- [PyPi](https://pypi.org/project/spark-nlp) (📥 3.8M / month):
	```
	pip install spark-nlp
	```
</details>
<details><summary><b><a href="https://github.com/UKPLab/sentence-transformers">sentence-transformers</a></b> (🥈35 ·  ⭐ 12K) - Multilingual Sentence & Image Embeddings with BERT. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/UKPLab/sentence-transformers) (👨‍💻 120 · 🔀 2.1K · 📦 17K · 📋 1.8K - 55% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/UKPLab/sentence-transformers
	```
- [PyPi](https://pypi.org/project/sentence-transformers) (📥 3M / month):
	```
	pip install sentence-transformers
	```
- [Conda](https://anaconda.org/conda-forge/sentence-transformers) (📥 170K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge sentence-transformers
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ParlAI">ParlAI</a></b> (🥈35 ·  ⭐ 10K) - A framework for training and evaluating AI models on a variety of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ParlAI) (👨‍💻 220 · 🔀 2K · 📦 210 · 📋 1.5K - 3% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/facebookresearch/ParlAI
	```
- [PyPi](https://pypi.org/project/parlai) (📥 1.6K / month):
	```
	pip install parlai
	```
</details>
<details><summary><b><a href="https://github.com/google/sentencepiece">sentencepiece</a></b> (🥈35 ·  ⭐ 8.3K) - Unsupervised text tokenizer for Neural Network-based text.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/sentencepiece) (👨‍💻 78 · 🔀 1K · 📥 31K · 📦 43K · 📋 660 - 4% open · ⏱️ 05.08.2023):

	```
	git clone https://github.com/google/sentencepiece
	```
- [PyPi](https://pypi.org/project/sentencepiece) (📥 10M / month):
	```
	pip install sentencepiece
	```
- [Conda](https://anaconda.org/conda-forge/sentencepiece) (📥 630K · ⏱️ 08.10.2023):
	```
	conda install -c conda-forge sentencepiece
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/text">TensorFlow Text</a></b> (🥈35 ·  ⭐ 1.1K) - Making text a first-class citizen in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/text) (👨‍💻 110 · 🔀 300 · 📦 5.9K · 📋 230 - 28% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/tensorflow/text
	```
- [PyPi](https://pypi.org/project/tensorflow-text) (📥 3.4M / month):
	```
	pip install tensorflow-text
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fastText">fastText</a></b> (🥈34 ·  ⭐ 25K) - Library for fast text representation and classification. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/fastText) (👨‍💻 64 · 🔀 4.5K · 📦 5.1K · 📋 1.1K - 42% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/facebookresearch/fastText
	```
- [PyPi](https://pypi.org/project/fasttext) (📥 1.1M / month):
	```
	pip install fasttext
	```
- [Conda](https://anaconda.org/conda-forge/fasttext) (📥 65K · ⏱️ 26.09.2023):
	```
	conda install -c conda-forge fasttext
	```
</details>
<details><summary><b><a href="https://github.com/allenai/allennlp">AllenNLP</a></b> (🥈34 ·  ⭐ 12K · 💤) - An open-source NLP research library, built on PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/allenai/allennlp) (👨‍💻 260 · 🔀 2.2K · 📥 61 · 📦 3.8K · 📋 2.6K - 3% open · ⏱️ 22.11.2022):

	```
	git clone https://github.com/allenai/allennlp
	```
- [PyPi](https://pypi.org/project/allennlp) (📥 44K / month):
	```
	pip install allennlp
	```
- [Conda](https://anaconda.org/conda-forge/allennlp) (📥 120K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge allennlp
	```
</details>
<details><summary><b><a href="https://github.com/sloria/TextBlob">TextBlob</a></b> (🥈34 ·  ⭐ 8.7K · 💤) - Simple, Pythonic, text processing--Sentiment analysis, part-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sloria/TextBlob) (👨‍💻 36 · 🔀 1.1K · 📥 110 · 📦 33K · 📋 260 - 39% open · ⏱️ 11.03.2023):

	```
	git clone https://github.com/sloria/TextBlob
	```
- [PyPi](https://pypi.org/project/textblob) (📥 600K / month):
	```
	pip install textblob
	```
- [Conda](https://anaconda.org/conda-forge/textblob) (📥 240K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge textblob
	```
</details>
<details><summary><b><a href="https://github.com/OpenNMT/OpenNMT-py">OpenNMT</a></b> (🥈34 ·  ⭐ 6.3K) - Open Source Neural Machine Translation and (Large) Language Models.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenNMT/OpenNMT-py) (👨‍💻 190 · 🔀 2.1K · 📦 230 · 📋 1.4K - 1% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/OpenNMT/OpenNMT-py
	```
- [PyPi](https://pypi.org/project/OpenNMT-py) (📥 6.3K / month):
	```
	pip install OpenNMT-py
	```
</details>
<details><summary><b><a href="https://github.com/argilla-io/argilla">rubrix</a></b> (🥈34 ·  ⭐ 2.6K · 📈) - Argilla: the open-source data curation platform for LLMs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/argilla-io/argilla) (👨‍💻 64 · 🔀 240 · 📦 1.9K · 📋 1.5K - 14% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/recognai/rubrix
	```
- [PyPi](https://pypi.org/project/rubrix) (📥 210 / month):
	```
	pip install rubrix
	```
- [Conda](https://anaconda.org/conda-forge/rubrix) (📥 27K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge rubrix
	```
</details>
<details><summary><b><a href="https://github.com/deeppavlov/DeepPavlov">DeepPavlov</a></b> (🥈31 ·  ⭐ 6.4K) - An open source library for deep learning end-to-end dialog.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deeppavlov/DeepPavlov) (👨‍💻 76 · 🔀 1.1K · 📦 360 · 📋 630 - 2% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/deepmipt/DeepPavlov
	```
- [PyPi](https://pypi.org/project/deeppavlov) (📥 7.7K / month):
	```
	pip install deeppavlov
	```
</details>
<details><summary><b><a href="https://github.com/jamesturk/jellyfish">jellyfish</a></b> (🥈31 ·  ⭐ 1.9K) - a python library for doing approximate and phonetic matching of strings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jamesturk/jellyfish) (👨‍💻 30 · 🔀 160 · 📦 7.1K · 📋 130 - 5% open · ⏱️ 18.09.2023):

	```
	git clone https://github.com/jamesturk/jellyfish
	```
- [PyPi](https://pypi.org/project/jellyfish) (📥 2.3M / month):
	```
	pip install jellyfish
	```
- [Conda](https://anaconda.org/conda-forge/jellyfish) (📥 710K · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge jellyfish
	```
</details>
<details><summary><b><a href="https://github.com/allenai/scispacy">SciSpacy</a></b> (🥈31 ·  ⭐ 1.5K) - A full spaCy pipeline and models for scientific/biomedical documents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allenai/scispacy) (👨‍💻 31 · 🔀 200 · 📦 770 · 📋 300 - 9% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/allenai/scispacy
	```
- [PyPi](https://pypi.org/project/scispacy) (📥 63K / month):
	```
	pip install scispacy
	```
</details>
<details><summary><b><a href="https://github.com/explosion/spacy-transformers">spacy-transformers</a></b> (🥈31 ·  ⭐ 1.3K) - Use pretrained transformers like BERT, XLNet and GPT-2.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code></summary>

- [GitHub](https://github.com/explosion/spacy-transformers) (👨‍💻 21 · 🔀 150 · 📦 1.3K · ⏱️ 11.10.2023):

	```
	git clone https://github.com/explosion/spacy-transformers
	```
- [PyPi](https://pypi.org/project/spacy-transformers) (📥 360K / month):
	```
	pip install spacy-transformers
	```
- [Conda](https://anaconda.org/conda-forge/spacy-transformers) (📥 23K · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge spacy-transformers
	```
</details>
<details><summary><b><a href="https://github.com/life4/textdistance">TextDistance</a></b> (🥈30 ·  ⭐ 3.2K) - Compute distance between sequences. 30+ algorithms, pure python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/life4/textdistance) (👨‍💻 14 · 🔀 240 · 📥 920 · 📦 5K · ⏱️ 28.09.2023):

	```
	git clone https://github.com/life4/textdistance
	```
- [PyPi](https://pypi.org/project/textdistance) (📥 370K / month):
	```
	pip install textdistance
	```
- [Conda](https://anaconda.org/conda-forge/textdistance) (📥 470K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge textdistance
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-nlp">GluonNLP</a></b> (🥈30 ·  ⭐ 2.5K · 💤) - Toolkit that enables easy text preprocessing, datasets.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-nlp) (👨‍💻 85 · 🔀 510 · 📦 1.4K · 📋 530 - 44% open · ⏱️ 25.12.2022):

	```
	git clone https://github.com/dmlc/gluon-nlp
	```
- [PyPi](https://pypi.org/project/gluonnlp) (📥 76K / month):
	```
	pip install gluonnlp
	```
</details>
<details><summary><b><a href="https://github.com/rspeer/python-ftfy">ftfy</a></b> (🥈29 ·  ⭐ 3.6K · 💤) - Fixes mojibake and other glitches in Unicode text, after the fact. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/rspeer/python-ftfy) (👨‍💻 18 · 🔀 110 · 📦 14K · 📋 130 - 9% open · ⏱️ 25.10.2022):

	```
	git clone https://github.com/rspeer/python-ftfy
	```
- [PyPi](https://pypi.org/project/ftfy) (📥 3.2M / month):
	```
	pip install ftfy
	```
- [Conda](https://anaconda.org/conda-forge/ftfy) (📥 270K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ftfy
	```
</details>
<details><summary><b><a href="https://github.com/dedupeio/dedupe">Dedupe</a></b> (🥈28 ·  ⭐ 3.8K · 💤) - A python library for accurate and scalable fuzzy matching, record.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dedupeio/dedupe) (👨‍💻 70 · 🔀 510 · 📦 300 · 📋 800 - 8% open · ⏱️ 17.02.2023):

	```
	git clone https://github.com/dedupeio/dedupe
	```
- [PyPi](https://pypi.org/project/dedupe) (📥 70K / month):
	```
	pip install dedupe
	```
- [Conda](https://anaconda.org/conda-forge/dedupe) (📥 40K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dedupe
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/text">torchtext</a></b> (🥈28 ·  ⭐ 3.4K) - Models, data loaders and abstractions for language processing,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/text) (👨‍💻 150 · 🔀 770 · 📋 770 - 33% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/pytorch/text
	```
- [PyPi](https://pypi.org/project/torchtext) (📥 380K / month):
	```
	pip install torchtext
	```
</details>
<details><summary><b><a href="https://github.com/miso-belica/sumy">Sumy</a></b> (🥈28 ·  ⭐ 3.3K) - Module for automatic summarization of text documents and HTML pages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/miso-belica/sumy) (👨‍💻 28 · 🔀 500 · 📦 2.2K · 📋 110 - 14% open · ⏱️ 11.08.2023):

	```
	git clone https://github.com/miso-belica/sumy
	```
- [PyPi](https://pypi.org/project/sumy) (📥 26K / month):
	```
	pip install sumy
	```
- [Conda](https://anaconda.org/conda-forge/sumy) (📥 6.8K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge sumy
	```
</details>
<details><summary><b><a href="https://github.com/DerwenAI/pytextrank">PyTextRank</a></b> (🥈28 ·  ⭐ 2.1K) - Python implementation of TextRank algorithms (textgraphs) for phrase.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/DerwenAI/pytextrank) (👨‍💻 19 · 🔀 310 · 📦 470 · 📋 98 - 7% open · ⏱️ 22.08.2023):

	```
	git clone https://github.com/DerwenAI/pytextrank
	```
- [PyPi](https://pypi.org/project/pytextrank) (📥 49K / month):
	```
	pip install pytextrank
	```
</details>
<details><summary><b><a href="https://github.com/qdrant/qdrant">qdrant</a></b> (🥈27 ·  ⭐ 13K) - Qdrant - High-performance, massive-scale Vector Database for the next.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/qdrant/qdrant) (👨‍💻 70 · 🔀 730 · 📥 1.5K · 📋 730 - 17% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/qdrant/qdrant
	```
</details>
<details><summary><b><a href="https://github.com/fastnlp/fastNLP">fastNLP</a></b> (🥈27 ·  ⭐ 3K · 💤) - fastNLP: A Modularized and Extensible NLP Framework. Currently.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/fastnlp/fastNLP) (👨‍💻 61 · 🔀 450 · 📥 74 · 📦 160 · 📋 210 - 26% open · ⏱️ 13.12.2022):

	```
	git clone https://github.com/fastnlp/fastNLP
	```
- [PyPi](https://pypi.org/project/fastnlp) (📥 22K / month):
	```
	pip install fastnlp
	```
</details>
<details><summary><b><a href="https://github.com/snowballstem/snowball">snowballstemmer</a></b> (🥈27 ·  ⭐ 690) - Snowball compiler and stemming algorithms. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/snowballstem/snowball) (👨‍💻 34 · 🔀 160 · 📦 4 · 📋 72 - 22% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/snowballstem/snowball
	```
- [PyPi](https://pypi.org/project/snowballstemmer) (📥 11M / month):
	```
	pip install snowballstemmer
	```
- [Conda](https://anaconda.org/conda-forge/snowballstemmer) (📥 7.3M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge snowballstemmer
	```
</details>
<details><summary><b><a href="https://github.com/Ciphey/Ciphey">Ciphey</a></b> (🥉26 ·  ⭐ 14K) - Automatically decrypt encryptions without knowing the key or cipher, decode.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Ciphey/Ciphey) (👨‍💻 48 · 🔀 850 · 📋 310 - 15% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/Ciphey/Ciphey
	```
- [PyPi](https://pypi.org/project/ciphey) (📥 44K / month):
	```
	pip install ciphey
	```
- [Docker Hub](https://hub.docker.com/r/remnux/ciphey) (📥 21K · ⭐ 14 · ⏱️ 11.08.2023):
	```
	docker pull remnux/ciphey
	```
</details>
<details><summary><b><a href="https://github.com/cltk/cltk">CLTK</a></b> (🥉26 ·  ⭐ 800 · 💤) - The Classical Language Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cltk/cltk) (👨‍💻 120 · 🔀 320 · 📥 42 · 📦 250 · 📋 560 - 6% open · ⏱️ 06.03.2023):

	```
	git clone https://github.com/cltk/cltk
	```
- [PyPi](https://pypi.org/project/cltk) (📥 970 / month):
	```
	pip install cltk
	```
</details>
<details><summary><b><a href="https://github.com/EricFillion/happy-transformer">happy-transformer</a></b> (🥉26 ·  ⭐ 470) - Happy Transformer makes it easy to fine-tune and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code></summary>

- [GitHub](https://github.com/EricFillion/happy-transformer) (👨‍💻 14 · 🔀 60 · 📦 200 · 📋 130 - 14% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/EricFillion/happy-transformer
	```
- [PyPi](https://pypi.org/project/happytransformer) (📥 3.4K / month):
	```
	pip install happytransformer
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenPrompt">OpenPrompt</a></b> (🥉25 ·  ⭐ 3.8K) - An Open-Source Framework for Prompt-Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenPrompt) (👨‍💻 22 · 🔀 400 · 📦 78 · 📋 240 - 28% open · ⏱️ 06.05.2023):

	```
	git clone https://github.com/thunlp/OpenPrompt
	```
- [PyPi](https://pypi.org/project/openprompt) (📥 2.4K / month):
	```
	pip install openprompt
	```
</details>
<details><summary><b><a href="https://github.com/explosion/sense2vec">sense2vec</a></b> (🥉25 ·  ⭐ 1.5K) - Contextually-keyed word vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/explosion/sense2vec) (👨‍💻 19 · 🔀 230 · 📥 59K · 📦 290 · 📋 110 - 18% open · ⏱️ 20.04.2023):

	```
	git clone https://github.com/explosion/sense2vec
	```
- [PyPi](https://pypi.org/project/sense2vec) (📥 1.7K / month):
	```
	pip install sense2vec
	```
- [Conda](https://anaconda.org/conda-forge/sense2vec) (📥 35K · ⏱️ 22.09.2023):
	```
	conda install -c conda-forge sense2vec
	```
</details>
<details><summary><b><a href="https://github.com/dwyl/english-words">english-words</a></b> (🥉24 ·  ⭐ 9.4K · 💤) - A text file containing 479k English words for all your.. <code><a href="http://bit.ly/3rvuUlR">Unlicense</a></code></summary>

- [GitHub](https://github.com/dwyl/english-words) (👨‍💻 30 · 🔀 1.7K · 📦 1 · 📋 110 - 69% open · ⏱️ 08.11.2022):

	```
	git clone https://github.com/dwyl/english-words
	```
- [PyPi](https://pypi.org/project/english-words) (📥 650K / month):
	```
	pip install english-words
	```
</details>
<details><summary><b><a href="https://github.com/PetrochukM/PyTorch-NLP">pytorch-nlp</a></b> (🥉24 ·  ⭐ 2.2K) - Basic Utilities for PyTorch Natural Language Processing (NLP). <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PetrochukM/PyTorch-NLP) (👨‍💻 18 · 🔀 260 · 📦 580 · 📋 69 - 27% open · ⏱️ 04.07.2023):

	```
	git clone https://github.com/PetrochukM/PyTorch-NLP
	```
- [PyPi](https://pypi.org/project/pytorch-nlp) (📥 4.8K / month):
	```
	pip install pytorch-nlp
	```
</details>
<details><summary><b><a href="https://github.com/JasonKessler/scattertext">scattertext</a></b> (🥉24 ·  ⭐ 2.1K) - Beautiful visualizations of how language differs among document.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JasonKessler/scattertext) (👨‍💻 14 · 🔀 280 · 📦 430 · 📋 99 - 21% open · ⏱️ 05.09.2023):

	```
	git clone https://github.com/JasonKessler/scattertext
	```
- [PyPi](https://pypi.org/project/scattertext) (📥 9K / month):
	```
	pip install scattertext
	```
- [Conda](https://anaconda.org/conda-forge/scattertext) (📥 84K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge scattertext
	```
</details>
<details><summary><b><a href="https://github.com/jbesomi/texthero">Texthero</a></b> (🥉23 ·  ⭐ 2.8K) - Text preprocessing, representation and visualization from zero to hero. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jbesomi/texthero) (👨‍💻 21 · 🔀 230 · 📥 120 · 📋 120 - 46% open · ⏱️ 29.08.2023):

	```
	git clone https://github.com/jbesomi/texthero
	```
- [PyPi](https://pypi.org/project/texthero) (📥 11K / month):
	```
	pip install texthero
	```
</details>
<details><summary><b><a href="https://github.com/VKCOM/YouTokenToMe">YouTokenToMe</a></b> (🥉23 ·  ⭐ 910 · 💤) - Unsupervised text tokenizer focused on computational efficiency. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/VKCOM/YouTokenToMe) (👨‍💻 8 · 🔀 78 · 📦 530 · 📋 59 - 54% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/vkcom/youtokentome
	```
- [PyPi](https://pypi.org/project/youtokentome) (📥 39K / month):
	```
	pip install youtokentome
	```
- [Conda](https://anaconda.org/conda-forge/youtokentome) (📥 37K · ⏱️ 27.09.2023):
	```
	conda install -c conda-forge youtokentome
	```
</details>
<details><summary><b><a href="https://github.com/unitaryai/detoxify">detoxify</a></b> (🥉23 ·  ⭐ 720) - Trained models & code to predict toxic comments on all 3 Jigsaw.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unitaryai/detoxify) (👨‍💻 11 · 🔀 94 · 📥 290K · 📦 410 · 📋 56 - 57% open · ⏱️ 23.08.2023):

	```
	git clone https://github.com/unitaryai/detoxify
	```
- [PyPi](https://pypi.org/project/detoxify) (📥 26K / month):
	```
	pip install detoxify
	```
</details>
<details><summary><b><a href="https://github.com/google-research/text-to-text-transfer-transformer">T5</a></b> (🥉22 ·  ⭐ 5.5K) - Code for the paper Exploring the Limits of Transfer Learning with a.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/text-to-text-transfer-transformer) (👨‍💻 56 · 🔀 720 · 📋 400 - 14% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/google-research/text-to-text-transfer-transformer
	```
- [PyPi](https://pypi.org/project/t5) (📥 13K / month):
	```
	pip install t5
	```
</details>
<details><summary><b><a href="https://github.com/nyu-mll/jiant">jiant</a></b> (🥉22 ·  ⭐ 1.6K · 💤) - jiant is an nlp toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nyu-mll/jiant) (👨‍💻 60 · 🔀 290 · 📦 3 · 📋 550 - 12% open · ⏱️ 17.10.2022):

	```
	git clone https://github.com/nyu-mll/jiant
	```
- [PyPi](https://pypi.org/project/jiant) (📥 56 / month):
	```
	pip install jiant
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/sockeye">Sockeye</a></b> (🥉22 ·  ⭐ 1.2K) - Sequence-to-sequence framework with a focus on Neural Machine.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/sockeye) (👨‍💻 60 · 🔀 310 · 📥 17 · 📋 300 - 0% open · ⏱️ 07.09.2023):

	```
	git clone https://github.com/awslabs/sockeye
	```
- [PyPi](https://pypi.org/project/sockeye) (📥 390 / month):
	```
	pip install sockeye
	```
</details>
<details><summary><b><a href="https://github.com/IndicoDataSolutions/finetune">finetune</a></b> (🥉22 ·  ⭐ 690) - Scikit-learn style model finetuning for NLP. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/IndicoDataSolutions/finetune) (👨‍💻 21 · 🔀 77 · 📦 11 · 📋 140 - 15% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/IndicoDataSolutions/finetune
	```
- [PyPi](https://pypi.org/project/finetune) (📥 240 / month):
	```
	pip install finetune
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/nlp-architect">NLP Architect</a></b> (🥉20 ·  ⭐ 2.9K · 💤) - A model library for exploring state-of-the-art deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/nlp-architect) (👨‍💻 38 · 🔀 440 · 📦 9 · 📋 130 - 11% open · ⏱️ 07.11.2022):

	```
	git clone https://github.com/IntelLabs/nlp-architect
	```
- [PyPi](https://pypi.org/project/nlp-architect) (📥 83 / month):
	```
	pip install nlp-architect
	```
</details>
<details><summary><b><a href="https://github.com/utterworks/fast-bert">fast-bert</a></b> (🥉20 ·  ⭐ 1.8K) - Super easy library for BERT based NLP models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/utterworks/fast-bert) (👨‍💻 36 · 🔀 330 · 📋 250 - 61% open · ⏱️ 27.07.2023):

	```
	git clone https://github.com/utterworks/fast-bert
	```
- [PyPi](https://pypi.org/project/fast-bert) (📥 1K / month):
	```
	pip install fast-bert
	```
</details>
<details><summary><b><a href="https://github.com/dsfsi/textaugment">textaugment</a></b> (🥉19 ·  ⭐ 340) - TextAugment: Text Augmentation Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dsfsi/textaugment) (👨‍💻 8 · 🔀 56 · 📥 61 · 📦 64 · 📋 20 - 35% open · ⏱️ 12.09.2023):

	```
	git clone https://github.com/dsfsi/textaugment
	```
- [PyPi](https://pypi.org/project/textaugment) (📥 3.6K / month):
	```
	pip install textaugment
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNRE">OpenNRE</a></b> (🥉16 ·  ⭐ 4.1K · 💤) - An Open-Source Package for Neural Relation Extraction (NRE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/thunlp/OpenNRE) (👨‍💻 12 · 🔀 980 · 📋 360 - 2% open · ⏱️ 03.01.2023):

	```
	git clone https://github.com/thunlp/OpenNRE
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/TextBox">TextBox</a></b> (🥉16 ·  ⭐ 1K) - TextBox 2.0 is a text generation library with pre-trained language models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RUCAIBox/TextBox) (👨‍💻 18 · 🔀 120 · 📦 5 · 📋 69 - 2% open · ⏱️ 18.05.2023):

	```
	git clone https://github.com/RUCAIBox/TextBox
	```
- [PyPi](https://pypi.org/project/textbox):
	```
	pip install textbox
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vizseq">VizSeq</a></b> (🥉12 ·  ⭐ 440) - An Analysis Toolkit for Natural Language Generation (Translation,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/vizseq) (👨‍💻 3 · 🔀 57 · 📦 7 · 📋 15 - 40% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/facebookresearch/vizseq
	```
- [PyPi](https://pypi.org/project/vizseq) (📥 33 / month):
	```
	pip install vizseq
	```
</details>
<details><summary>Show 42 hidden projects...</summary>

- <b><a href="https://github.com/flairNLP/flair">flair</a></b> (🥇36 ·  ⭐ 13K) - A very simple framework for state-of-the-art Natural Language.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/gunthercox/ChatterBot">ChatterBot</a></b> (🥈35 ·  ⭐ 14K · 💀) - ChatterBot is a machine learning, conversational dialog engine.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/seatgeek/fuzzywuzzy">fuzzywuzzy</a></b> (🥈33 ·  ⭐ 9K · 💀) - Fuzzy String Matching in Python. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/stanfordnlp/stanza">stanza</a></b> (🥈33 ·  ⭐ 6.8K) - Stanford NLP Python library for tokenization, sentence.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/makcedward/nlpaug">nlpaug</a></b> (🥈29 ·  ⭐ 4.1K · 💀) - Data augmentation for NLP. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/chartbeat-labs/textacy">textacy</a></b> (🥈29 ·  ⭐ 2.1K) - NLP, before and after spaCy. <code>❗Unlicensed</code>
- <b><a href="https://github.com/deepset-ai/FARM">FARM</a></b> (🥈27 ·  ⭐ 1.7K · 💀) - Fast & easy transfer learning for NLP. Harvesting language.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vi3k6i5/flashtext">flashtext</a></b> (🥉26 ·  ⭐ 5.5K · 💀) - Extract Keywords from sentence or Replace keywords in sentences. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/cjhutto/vaderSentiment">vaderSentiment</a></b> (🥉25 ·  ⭐ 4.1K · 💀) - VADER Sentiment Analysis. VADER (Valence Aware Dictionary.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/huggingface/neuralcoref">neuralcoref</a></b> (🥉25 ·  ⭐ 2.8K · 💀) - Fast Coreference Resolution in spaCy with Neural Networks. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nipunsadvilkar/pySBD">pySBD</a></b> (🥉25 ·  ⭐ 660 · 💀) - pySBD (Python Sentence Boundary Disambiguation) is a rule-based sentence.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aboSamoor/polyglot">polyglot</a></b> (🥉24 ·  ⭐ 2.2K · 💀) - Multilingual text (NLP) processing toolkit. <code>❗Unlicensed</code>
- <b><a href="https://github.com/saffsd/langid.py">langid</a></b> (🥉24 ·  ⭐ 2.2K · 💀) - Stand-alone language identification system. <code>❗Unlicensed</code>
- <b><a href="https://github.com/facebookresearch/pytext">PyText</a></b> (🥉23 ·  ⭐ 6.4K · 💤) - A natural language modeling framework based on PyTorch. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/snipsco/snips-nlu">Snips NLU</a></b> (🥉23 ·  ⭐ 3.8K · 💀) - Snips Python library to extract meaning from text. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/NTMC-Community/MatchZoo">MatchZoo</a></b> (🥉23 ·  ⭐ 3.8K · 💀) - Facilitating the design, comparison and sharing of deep.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/BrikerMan/Kashgari">Kashgari</a></b> (🥉23 ·  ⭐ 2.4K · 💀) - Kashgari is a production-level NLP Transfer learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/minimaxir/textgenrnn">textgenrnn</a></b> (🥉22 ·  ⭐ 4.9K · 💀) - Easily train your own text-generating neural network.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/asyml/texar">Texar</a></b> (🥉22 ·  ⭐ 2.4K · 💀) - Toolkit for Machine Learning, Natural Language Processing, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Alir3z4/python-stop-words">stop-words</a></b> (🥉22 ·  ⭐ 150 · 💀) - Get list of common stop words in various languages in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Delta-ML/delta">DELTA</a></b> (🥉21 ·  ⭐ 1.6K · 💀) - DELTA is a deep learning based natural language and speech.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Hironsan/anago">anaGo</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - Bidirectional LSTM-CRF and ELMo for Named-Entity Recognition,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vrasneur/pyfasttext">pyfasttext</a></b> (🥉20 ·  ⭐ 230 · 💀) - Yet another Python binding for fastText. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/minimaxir/gpt-2-simple">gpt-2-simple</a></b> (🥉19 ·  ⭐ 3.3K · 💀) - Python package to easily retrain OpenAIs GPT-2 text-.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/jaidevd/numerizer">numerizer</a></b> (🥉19 ·  ⭐ 210) - A Python module to convert natural language numerics into ints and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/bytedance/lightseq">lightseq</a></b> (🥉18 ·  ⭐ 2.9K) - LightSeq: A High Performance Library for Sequence Processing.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/anhaidgroup/deepmatcher">DeepMatcher</a></b> (🥉17 ·  ⭐ 510 · 💀) - Python package for performing Entity and Text Matching using.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/mchaput/whoosh">whoosh</a></b> (🥉17 ·  ⭐ 460 · 💀) - Pure-Python full-text search library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/PKSHATechnology-Research/camphr">Camphr</a></b> (🥉17 ·  ⭐ 340 · 💀) - Camphr - NLP libary for creating pipeline components. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>spacy</code>
- <b><a href="https://github.com/shaypal5/skift">skift</a></b> (🥉17 ·  ⭐ 230 · 💀) - scikit-learn wrappers for Python fastText. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Ki6an/fastT5">fastT5</a></b> (🥉16 ·  ⭐ 500 · 💀) - boost inference speed of T5 models by 5x & reduce the model size.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/textpipe/textpipe">textpipe</a></b> (🥉16 ·  ⭐ 300 · 💀) - Textpipe: clean and extract metadata from text. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Franck-Dernoncourt/NeuroNER">NeuroNER</a></b> (🥉15 ·  ⭐ 1.7K · 💀) - Named-entity recognition using neural networks. Easy-to-use and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/BLINK">BLINK</a></b> (🥉15 ·  ⭐ 1.1K · 💀) - Entity Linker solution. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytorch/translate">Translate</a></b> (🥉15 ·  ⭐ 800 · 💀) - Translate - a PyTorch Language Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/koursaros-ai/nboost">nboost</a></b> (🥉15 ·  ⭐ 670 · 💀) - NBoost is a scalable, search-api-boosting platform for deploying.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/feedly/transfer-nlp">TransferNLP</a></b> (🥉13 ·  ⭐ 290 · 💀) - NLP library designed for reproducible experimentation.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/abelriboulot/onnxt5">ONNX-T5</a></b> (🥉13 ·  ⭐ 240 · 💀) - Summarization, translation, sentiment-analysis, text-generation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/victordibia/neuralqa">NeuralQA</a></b> (🥉13 ·  ⭐ 220 · 💀) - NeuralQA: A Usable Library for Question Answering on Large Datasets.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/textvec/textvec">textvec</a></b> (🥉12 ·  ⭐ 190 · 💀) - Text vectorization tool to outperform TFIDF for classification.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MartinoMensio/spacy-dbpedia-spotlight">spacy-dbpedia-spotlight</a></b> (🥉12 ·  ⭐ 91 · 💤) - A spaCy wrapper for DBpedia Spotlight. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>spacy</code>
- <b><a href="https://github.com/as-ideas/headliner">Headliner</a></b> (🥉10 ·  ⭐ 230 · 💀) - Easy training and deployment of seq2seq models. <code>❗Unlicensed</code>
</details>
<br>

## Image Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for image & video processing, manipulation, and augmentation as well as libraries for computer vision tasks such as facial recognition, object detection, and classification._

<details><summary><b><a href="https://github.com/python-pillow/Pillow">Pillow</a></b> (🥇47 ·  ⭐ 11K) - Python Imaging Library (Fork). <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code></summary>

- [GitHub](https://github.com/python-pillow/Pillow) (👨‍💻 450 · 🔀 1.9K · 📦 1.4M · 📋 2.9K - 2% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/python-pillow/Pillow
	```
- [PyPi](https://pypi.org/project/Pillow) (📥 66M / month):
	```
	pip install Pillow
	```
- [Conda](https://anaconda.org/conda-forge/pillow) (📥 34M · ⏱️ 03.10.2023):
	```
	conda install -c conda-forge pillow
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/pytorch-image-models">PyTorch Image Models</a></b> (🥇40 ·  ⭐ 27K) - PyTorch image models, scripts, pretrained weights --.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/pytorch-image-models) (👨‍💻 110 · 🔀 4.2K · 📥 5.6M · 📦 17K · 📋 810 - 8% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/rwightman/pytorch-image-models
	```
- [PyPi](https://pypi.org/project/timm) (📥 3.4M / month):
	```
	pip install timm
	```
- [Conda](https://anaconda.org/conda-forge/timm) (📥 100K · ⏱️ 05.09.2023):
	```
	conda install -c conda-forge timm
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmdetection">MMDetection</a></b> (🥇39 ·  ⭐ 26K) - OpenMMLab Detection Toolbox and Benchmark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmdetection) (👨‍💻 440 · 🔀 8K · 📦 1.8K · 📋 7.5K - 12% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/open-mmlab/mmdetection
	```
- [PyPi](https://pypi.org/project/mmdet) (📥 150K / month):
	```
	pip install mmdet
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/vision">torchvision</a></b> (🥇38 ·  ⭐ 15K) - Datasets, Transforms and Models specific to Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/vision) (👨‍💻 560 · 🔀 6.6K · 📥 32K · 📦 18 · 📋 3K - 24% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/pytorch/vision
	```
- [PyPi](https://pypi.org/project/torchvision) (📥 8.1M / month):
	```
	pip install torchvision
	```
- [Conda](https://anaconda.org/conda-forge/torchvision) (📥 880K · ⏱️ 02.10.2023):
	```
	conda install -c conda-forge torchvision
	```
</details>
<details><summary><b><a href="https://github.com/kornia/kornia">Kornia</a></b> (🥇38 ·  ⭐ 8.7K) - Computer Vision and Robotics Library for AI. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kornia/kornia) (👨‍💻 230 · 🔀 870 · 📥 840 · 📦 6.6K · 📋 820 - 28% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/kornia/kornia
	```
- [PyPi](https://pypi.org/project/kornia) (📥 2.1M / month):
	```
	pip install kornia
	```
- [Conda](https://anaconda.org/conda-forge/kornia) (📥 100K · ⏱️ 04.08.2023):
	```
	conda install -c conda-forge kornia
	```
</details>
<details><summary><b><a href="https://github.com/imageio/imageio">imageio</a></b> (🥇38 ·  ⭐ 1.3K) - Python library for reading and writing image data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/imageio/imageio) (👨‍💻 110 · 🔀 270 · 📥 860 · 📦 100K · 📋 570 - 15% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/imageio/imageio
	```
- [PyPi](https://pypi.org/project/imageio) (📥 17M / month):
	```
	pip install imageio
	```
- [Conda](https://anaconda.org/conda-forge/imageio) (📥 5.7M · ⏱️ 09.10.2023):
	```
	conda install -c conda-forge imageio
	```
</details>
<details><summary><b><a href="https://github.com/Zulko/moviepy">MoviePy</a></b> (🥈37 ·  ⭐ 11K) - Video editing with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Zulko/moviepy) (👨‍💻 160 · 🔀 1.4K · 📦 29K · 📋 1.4K - 25% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/Zulko/moviepy
	```
- [PyPi](https://pypi.org/project/moviepy) (📥 690K / month):
	```
	pip install moviepy
	```
- [Conda](https://anaconda.org/conda-forge/moviepy) (📥 210K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge moviepy
	```
</details>
<details><summary><b><a href="https://github.com/albumentations-team/albumentations">Albumentations</a></b> (🥈35 ·  ⭐ 13K) - Fast image augmentation library and an easy-to-use wrapper.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albumentations-team/albumentations) (👨‍💻 130 · 🔀 1.5K · 📦 18K · 📋 790 - 46% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/albumentations-team/albumentations
	```
- [PyPi](https://pypi.org/project/albumentations) (📥 990K / month):
	```
	pip install albumentations
	```
- [Conda](https://anaconda.org/conda-forge/albumentations) (📥 140K · ⏱️ 12.06.2023):
	```
	conda install -c conda-forge albumentations
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detectron2">detectron2</a></b> (🥈34 ·  ⭐ 27K) - Detectron2 is a platform for object detection, segmentation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detectron2) (👨‍💻 260 · 🔀 6.7K · 📦 1.4K · 📋 3.4K - 10% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/facebookresearch/detectron2
	```
- [PyPi](https://pypi.org/project/detectron2):
	```
	pip install detectron2
	```
- [Conda](https://anaconda.org/conda-forge/detectron2) (📥 210K · ⏱️ 23.06.2023):
	```
	conda install -c conda-forge detectron2
	```
</details>
<details><summary><b><a href="https://github.com/emcconville/wand">Wand</a></b> (🥈34 ·  ⭐ 1.3K) - The ctypes-based simple ImageMagick binding for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/emcconville/wand) (👨‍💻 100 · 🔀 190 · 📥 26K · 📦 17K · 📋 400 - 4% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/emcconville/wand
	```
- [PyPi](https://pypi.org/project/wand) (📥 820K / month):
	```
	pip install wand
	```
- [Conda](https://anaconda.org/conda-forge/wand) (📥 31K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge wand
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleSeg">PaddleSeg</a></b> (🥈32 ·  ⭐ 7.6K) - Easy-to-use image segmentation library with awesome pre-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleSeg) (👨‍💻 120 · 🔀 1.5K · 📦 1K · 📋 1.9K - 16% open · ⏱️ 28.09.2023):

	```
	git clone https://github.com/PaddlePaddle/PaddleSeg
	```
- [PyPi](https://pypi.org/project/paddleseg) (📥 1.9K / month):
	```
	pip install paddleseg
	```
</details>
<details><summary><b><a href="https://github.com/lightly-ai/lightly">lightly</a></b> (🥈31 ·  ⭐ 2.5K) - A python library for self-supervised learning on images. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lightly-ai/lightly) (👨‍💻 33 · 🔀 220 · 📦 170 · 📋 470 - 18% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/lightly-ai/lightly
	```
- [PyPi](https://pypi.org/project/lightly) (📥 36K / month):
	```
	pip install lightly
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/vit-pytorch">vit-pytorch</a></b> (🥈30 ·  ⭐ 15K) - Implementation of Vision Transformer, a simple way to achieve.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/vit-pytorch) (👨‍💻 19 · 🔀 2.5K · 📦 320 · 📋 230 - 45% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/lucidrains/vit-pytorch
	```
- [PyPi](https://pypi.org/project/vit-pytorch) (📥 17K / month):
	```
	pip install vit-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleDetection">PaddleDetection</a></b> (🥈30 ·  ⭐ 11K) - Object Detection toolkit based on PaddlePaddle. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleDetection) (👨‍💻 150 · 🔀 2.7K · 📦 110 · 📋 5.1K - 24% open · ⏱️ 27.09.2023):

	```
	git clone https://github.com/PaddlePaddle/PaddleDetection
	```
- [PyPi](https://pypi.org/project/paddledet) (📥 690 / month):
	```
	pip install paddledet
	```
</details>
<details><summary><b><a href="https://github.com/JohannesBuchner/imagehash">ImageHash</a></b> (🥈30 ·  ⭐ 2.8K) - A Python Perceptual Image Hashing Module. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/JohannesBuchner/imagehash) (👨‍💻 25 · 🔀 320 · 📦 11K · 📋 120 - 5% open · ⏱️ 05.08.2023):

	```
	git clone https://github.com/JohannesBuchner/imagehash
	```
- [PyPi](https://pypi.org/project/ImageHash) (📥 1.4M / month):
	```
	pip install ImageHash
	```
- [Conda](https://anaconda.org/conda-forge/imagehash) (📥 340K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge imagehash
	```
</details>
<details><summary><b><a href="https://github.com/OlafenwaMoses/ImageAI">imageai</a></b> (🥈29 ·  ⭐ 8.1K) - A python library built to empower developers to build applications and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/OlafenwaMoses/ImageAI) (👨‍💻 19 · 🔀 2.1K · 📥 880K · 📦 1.4K · 📋 730 - 38% open · ⏱️ 26.08.2023):

	```
	git clone https://github.com/OlafenwaMoses/ImageAI
	```
- [PyPi](https://pypi.org/project/imageai) (📥 6.6K / month):
	```
	pip install imageai
	```
- [Conda](https://anaconda.org/conda-forge/imageai) (📥 6.5K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge imageai
	```
</details>
<details><summary><b><a href="https://github.com/serengil/deepface">deepface</a></b> (🥈29 ·  ⭐ 7.6K) - A Lightweight Face Recognition and Facial Attribute Analysis (Age,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/serengil/deepface) (👨‍💻 44 · 🔀 1.5K · 📦 2K · 📋 780 - 1% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/serengil/deepface
	```
- [PyPi](https://pypi.org/project/deepface) (📥 43K / month):
	```
	pip install deepface
	```
</details>
<details><summary><b><a href="https://github.com/1adrianb/face-alignment">Face Alignment</a></b> (🥈29 ·  ⭐ 6.5K) - 2D and 3D Face alignment library build using pytorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/1adrianb/face-alignment) (👨‍💻 26 · 🔀 1.3K · 📦 18 · 📋 300 - 22% open · ⏱️ 16.08.2023):

	```
	git clone https://github.com/1adrianb/face-alignment
	```
- [PyPi](https://pypi.org/project/face-alignment) (📥 50K / month):
	```
	pip install face-alignment
	```
</details>
<details><summary><b><a href="https://github.com/abhiTronix/vidgear">vidgear</a></b> (🥈29 ·  ⭐ 3K) - A High-performance cross-platform Video Processing Python framework.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/abhiTronix/vidgear) (👨‍💻 14 · 🔀 230 · 📥 930 · 📦 460 · 📋 270 - 1% open · ⏱️ 10.09.2023):

	```
	git clone https://github.com/abhiTronix/vidgear
	```
- [PyPi](https://pypi.org/project/vidgear) (📥 16K / month):
	```
	pip install vidgear
	```
</details>
<details><summary><b><a href="https://github.com/dmlc/gluon-cv">GluonCV</a></b> (🥉27 ·  ⭐ 5.6K · 💤) - Gluon CV Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dmlc/gluon-cv) (👨‍💻 120 · 🔀 1.2K · 📦 18 · 📋 820 - 4% open · ⏱️ 19.01.2023):

	```
	git clone https://github.com/dmlc/gluon-cv
	```
- [PyPi](https://pypi.org/project/gluoncv) (📥 48K / month):
	```
	pip install gluoncv
	```
</details>
<details><summary><b><a href="https://github.com/opencv/opencv-python">opencv-python</a></b> (🥉27 ·  ⭐ 3.8K · 📉) - Automated CI toolchain to produce precompiled opencv-python,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/opencv/opencv-python) (👨‍💻 47 · 🔀 720 · 📋 700 - 9% open · ⏱️ 27.09.2023):

	```
	git clone https://github.com/opencv/opencv-python
	```
- [PyPi](https://pypi.org/project/opencv-python) (📥 11M / month):
	```
	pip install opencv-python
	```
</details>
<details><summary><b><a href="https://github.com/obss/sahi">sahi</a></b> (🥉27 ·  ⭐ 3.1K) - Framework agnostic sliced/tiled inference + interactive ui + error analysis.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/obss/sahi) (👨‍💻 31 · 🔀 450 · 📥 19K · 📦 670 · ⏱️ 26.08.2023):

	```
	git clone https://github.com/obss/sahi
	```
- [PyPi](https://pypi.org/project/sahi) (📥 130K / month):
	```
	pip install sahi
	```
- [Conda](https://anaconda.org/conda-forge/sahi) (📥 49K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge sahi
	```
</details>
<details><summary><b><a href="https://github.com/timesler/facenet-pytorch">facenet-pytorch</a></b> (🥉26 ·  ⭐ 3.8K) - Pretrained Pytorch face detection (MTCNN) and facial.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/timesler/facenet-pytorch) (👨‍💻 16 · 🔀 780 · 📥 690K · 📦 1.3K · 📋 160 - 35% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/timesler/facenet-pytorch
	```
- [PyPi](https://pypi.org/project/facenet-pytorch) (📥 25K / month):
	```
	pip install facenet-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pytorchvideo">pytorchvideo</a></b> (🥉25 ·  ⭐ 3K) - A deep learning library for video understanding research. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pytorchvideo) (👨‍💻 55 · 🔀 360 · 📋 170 - 40% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/facebookresearch/pytorchvideo
	```
- [PyPi](https://pypi.org/project/pytorchvideo) (📥 93K / month):
	```
	pip install pytorchvideo
	```
</details>
<details><summary><b><a href="https://github.com/tryolabs/norfair">Norfair</a></b> (🥉25 ·  ⭐ 2.2K) - Lightweight Python library for adding real-time multi-object tracking.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/tryolabs/norfair) (👨‍💻 24 · 🔀 210 · 📥 290 · 📦 130 · 📋 130 - 3% open · ⏱️ 15.05.2023):

	```
	git clone https://github.com/tryolabs/norfair
	```
- [PyPi](https://pypi.org/project/norfair) (📥 5.4K / month):
	```
	pip install norfair
	```
</details>
<details><summary><b><a href="https://github.com/mdbloice/Augmentor">Augmentor</a></b> (🥉24 ·  ⭐ 5K · 💤) - Image augmentation library in Python for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mdbloice/Augmentor) (👨‍💻 23 · 🔀 840 · 📦 650 · 📋 190 - 61% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/mdbloice/Augmentor
	```
- [PyPi](https://pypi.org/project/Augmentor) (📥 11K / month):
	```
	pip install Augmentor
	```
</details>
<details><summary><b><a href="https://github.com/idealo/imagededup">Image Deduplicator</a></b> (🥉24 ·  ⭐ 4.7K) - Finding duplicate images made easy!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/idealo/imagededup) (👨‍💻 15 · 🔀 420 · 📦 64 · 📋 110 - 22% open · ⏱️ 28.04.2023):

	```
	git clone https://github.com/idealo/imagededup
	```
- [PyPi](https://pypi.org/project/imagededup) (📥 2.2K / month):
	```
	pip install imagededup
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/mmf">MMF</a></b> (🥉23 ·  ⭐ 5.3K) - A modular framework for vision & language multimodal research from.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/mmf) (👨‍💻 110 · 🔀 880 · 📦 14 · 📋 650 - 16% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/facebookresearch/mmf
	```
- [PyPi](https://pypi.org/project/mmf) (📥 210 / month):
	```
	pip install mmf
	```
</details>
<details><summary><b><a href="https://github.com/libvips/pyvips">pyvips</a></b> (🥉23 ·  ⭐ 540) - python binding for libvips using cffi. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/libvips/pyvips) (👨‍💻 16 · 🔀 48 · 📦 600 · 📋 380 - 41% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/libvips/pyvips
	```
- [PyPi](https://pypi.org/project/pyvips) (📥 51K / month):
	```
	pip install pyvips
	```
- [Conda](https://anaconda.org/conda-forge/pyvips) (📥 68K · ⏱️ 26.09.2023):
	```
	conda install -c conda-forge pyvips
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/vissl">vissl</a></b> (🥉22 ·  ⭐ 3.1K) - VISSL is FAIRs library of extensible, modular and scalable components.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/vissl) (👨‍💻 37 · 🔀 320 · 📦 30 · 📋 170 - 37% open · ⏱️ 25.08.2023):

	```
	git clone https://github.com/facebookresearch/vissl
	```
- [PyPi](https://pypi.org/project/vissl) (📥 200 / month):
	```
	pip install vissl
	```
</details>
<details><summary><b><a href="https://github.com/airctic/icevision">icevision</a></b> (🥉22 ·  ⭐ 830 · 💤) - An Agnostic Computer Vision Framework - Pluggable to any.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/airctic/icevision) (👨‍💻 41 · 🔀 140 · 📋 570 - 10% open · ⏱️ 07.12.2022):

	```
	git clone https://github.com/airctic/icevision
	```
- [PyPi](https://pypi.org/project/icevision) (📥 5.1K / month):
	```
	pip install icevision
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/detr">DE⫶TR</a></b> (🥉21 ·  ⭐ 12K · 💤) - End-to-End Object Detection with Transformers. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/detr) (👨‍💻 26 · 🔀 2.1K · 📦 18 · 📋 510 - 44% open · ⏱️ 07.02.2023):

	```
	git clone https://github.com/facebookresearch/detr
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/pycls">pycls</a></b> (🥉21 ·  ⭐ 2.1K) - Codebase for Image Classification Research, written in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/pycls) (👨‍💻 19 · 🔀 230 · 📦 16 · 📋 80 - 30% open · ⏱️ 26.08.2023):

	```
	git clone https://github.com/facebookresearch/pycls
	```
- [PyPi](https://pypi.org/project/pycls) (📥 49K / month):
	```
	pip install pycls
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ClassyVision">Classy Vision</a></b> (🥉21 ·  ⭐ 1.6K · 💤) - An end-to-end PyTorch framework for image and video.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ClassyVision) (👨‍💻 77 · 🔀 280 · 📋 77 - 16% open · ⏱️ 23.03.2023):

	```
	git clone https://github.com/facebookresearch/ClassyVision
	```
- [PyPi](https://pypi.org/project/classy_vision) (📥 2.2K / month):
	```
	pip install classy_vision
	```
- [Conda](https://anaconda.org/conda-forge/classy_vision) (📥 18K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge classy_vision
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/graphics">tensorflow-graphics</a></b> (🥉20 ·  ⭐ 2.7K) - TensorFlow Graphics: Differentiable Graphics Layers.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/graphics) (👨‍💻 39 · 🔀 350 · 📋 180 - 48% open · ⏱️ 08.08.2023):

	```
	git clone https://github.com/tensorflow/graphics
	```
- [PyPi](https://pypi.org/project/tensorflow-graphics) (📥 4.5K / month):
	```
	pip install tensorflow-graphics
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/SlowFast">PySlowFast</a></b> (🥉19 ·  ⭐ 5.9K) - PySlowFast: video understanding codebase from FAIR for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/SlowFast) (👨‍💻 31 · 🔀 1.1K · 📦 14 · 📋 630 - 56% open · ⏱️ 26.08.2023):

	```
	git clone https://github.com/facebookresearch/SlowFast
	```
- [PyPi](https://pypi.org/project/pyslowfast) (📥 11 / month):
	```
	pip install pyslowfast
	```
</details>
<details><summary><b><a href="https://github.com/google-research/scenic">scenic</a></b> (🥉19 ·  ⭐ 2.5K) - Scenic: A Jax Library for Computer Vision Research and Beyond. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/scenic) (👨‍💻 70 · 🔀 340 · 📋 180 - 43% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/google-research/scenic
	```
</details>
<details><summary>Show 23 hidden projects...</summary>

- <b><a href="https://github.com/scikit-image/scikit-image">scikit-image</a></b> (🥇42 ·  ⭐ 5.6K) - Image processing in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/aleju/imgaug">imgaug</a></b> (🥈34 ·  ⭐ 14K · 💀) - Image augmentation for machine learning experiments. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/deepinsight/insightface">InsightFace</a></b> (🥈33 ·  ⭐ 18K) - State-of-the-art 2D and 3D Face Analysis Project. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/glfw/glfw">glfw</a></b> (🥈32 ·  ⭐ 11K) - A multi-platform library for OpenGL, OpenGL ES, Vulkan, window and input. <code><a href="https://tldrlegal.com/search?q=Zlib">❗️Zlib</a></code>
- <b><a href="https://github.com/ageitgey/face_recognition">Face Recognition</a></b> (🥈31 ·  ⭐ 50K · 💀) - The worlds simplest facial recognition api for Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/pytorch3d">PyTorch3D</a></b> (🥈29 ·  ⭐ 7.7K) - PyTorch3D is FAIRs library of reusable components for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/PyImageSearch/imutils">imutils</a></b> (🥈29 ·  ⭐ 4.4K · 💀) - A series of convenience functions to make basic image processing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Layout-Parser/layout-parser">layout-parser</a></b> (🥉27 ·  ⭐ 4K · 💀) - A Unified Toolkit for Deep Learning Based Document Image.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/chainer/chainercv">chainercv</a></b> (🥉27 ·  ⭐ 1.5K · 💀) - ChainerCV: a Library for Deep Learning in Computer Vision. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ipazc/mtcnn">mtcnn</a></b> (🥉26 ·  ⭐ 2K · 💀) - MTCNN face detection implementation for TensorFlow, as a PIP package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/CellProfiler/CellProfiler">CellProfiler</a></b> (🥉26 ·  ⭐ 800) - An open-source application for biological image analysis. <code>❗Unlicensed</code>
- <b><a href="https://github.com/luispedro/mahotas">mahotas</a></b> (🥉24 ·  ⭐ 810) - Computer Vision in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/qubvel/segmentation_models">segmentation_models</a></b> (🥉23 ·  ⭐ 4.4K · 💀) - Segmentation models with pretrained backbones. Keras.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/idealo/image-super-resolution">Image Super-Resolution</a></b> (🥉22 ·  ⭐ 4.3K · 💀) - Super-scale your images and run experiments with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tryolabs/luminoth">Luminoth</a></b> (🥉22 ·  ⭐ 2.4K · 💀) - Deep Learning toolkit for Computer Vision. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lucidrains/deep-daze">deep-daze</a></b> (🥉21 ·  ⭐ 4.4K · 💀) - Simple command line tool for text to image generation using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/uploadcare/pillow-simd">Pillow-SIMD</a></b> (🥉21 ·  ⭐ 2K) - The friendly PIL fork. <code><a href="https://tldrlegal.com/search?q=PIL">❗️PIL</a></code>
- <b><a href="https://github.com/hhatto/nude.py">nude.py</a></b> (🥉19 ·  ⭐ 920 · 💀) - Nudity detection with Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Oulu-IMEDS/solt">solt</a></b> (🥉18 ·  ⭐ 260 · 💀) - Streaming over lightweight data transformations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/rhsimplex/image-match">image-match</a></b> (🥉17 ·  ⭐ 2.9K · 💤) - Quickly search over billions of images. <code>❗Unlicensed</code>
- <b><a href="https://github.com/jasmcaus/caer">Caer</a></b> (🥉17 ·  ⭐ 720 · 💀) - A lightweight Computer Vision library. Scale your models, not boilerplate. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/qanastek/HugsVision">HugsVision</a></b> (🥉14 ·  ⭐ 180 · 💤) - HugsVision is a easy to use huggingface wrapper for state-of-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>huggingface</code>
- <b><a href="https://github.com/nicolas-chaulet/torch-points3d">Torch Points 3D</a></b> (🥉14 ·  ⭐ 160 · 💀) - Pytorch framework for doing deep learning on point.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Graph Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for graph processing, clustering, embedding, and machine learning tasks._

<details><summary><b><a href="https://github.com/dmlc/dgl">dgl</a></b> (🥇38 ·  ⭐ 12K) - Python package built to ease deep learning on graph, on top of existing DL.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dmlc/dgl) (👨‍💻 280 · 🔀 2.8K · 📦 150 · 📋 2.4K - 13% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dmlc/dgl
	```
- [PyPi](https://pypi.org/project/dgl) (📥 66K / month):
	```
	pip install dgl
	```
</details>
<details><summary><b><a href="https://github.com/pyg-team/pytorch_geometric">PyTorch Geometric</a></b> (🥇35 ·  ⭐ 19K) - Graph Neural Network Library for PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyg-team/pytorch_geometric) (👨‍💻 450 · 🔀 3.3K · 📋 3.2K - 23% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pyg-team/pytorch_geometric
	```
- [PyPi](https://pypi.org/project/torch-geometric) (📥 200K / month):
	```
	pip install torch-geometric
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_geometric) (📥 32K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pytorch_geometric
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/ogb">ogb</a></b> (🥇29 ·  ⭐ 1.8K) - Benchmark datasets, data loaders, and evaluators for graph machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/ogb) (👨‍💻 32 · 🔀 390 · 📦 1.1K · 📋 270 - 2% open · ⏱️ 10.06.2023):

	```
	git clone https://github.com/snap-stanford/ogb
	```
- [PyPi](https://pypi.org/project/ogb) (📥 38K / month):
	```
	pip install ogb
	```
- [Conda](https://anaconda.org/conda-forge/ogb) (📥 28K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ogb
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PGL">Paddle Graph Learning</a></b> (🥈28 ·  ⭐ 1.5K) - Paddle Graph Learning (PGL) is an efficient and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PGL) (👨‍💻 31 · 🔀 300 · 📦 45 · 📋 190 - 37% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/PaddlePaddle/PGL
	```
- [PyPi](https://pypi.org/project/pgl) (📥 1.4K / month):
	```
	pip install pgl
	```
</details>
<details><summary><b><a href="https://github.com/danielegrattarola/spektral">Spektral</a></b> (🥈27 ·  ⭐ 2.3K) - Graph Neural Networks with Keras and Tensorflow 2. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/danielegrattarola/spektral) (👨‍💻 27 · 🔀 330 · 📦 230 · 📋 260 - 23% open · ⏱️ 01.06.2023):

	```
	git clone https://github.com/danielegrattarola/spektral
	```
- [PyPi](https://pypi.org/project/spektral) (📥 4.6K / month):
	```
	pip install spektral
	```
</details>
<details><summary><b><a href="https://github.com/graphistry/pygraphistry">pygraphistry</a></b> (🥈27 ·  ⭐ 1.9K) - PyGraphistry is a Python library to quickly load, shape,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graphistry/pygraphistry) (👨‍💻 39 · 🔀 200 · 📦 100 · 📋 280 - 48% open · ⏱️ 16.09.2023):

	```
	git clone https://github.com/graphistry/pygraphistry
	```
- [PyPi](https://pypi.org/project/graphistry) (📥 1.7K / month):
	```
	pip install graphistry
	```
</details>
<details><summary><b><a href="https://github.com/Accenture/AmpliGraph">AmpliGraph</a></b> (🥈25 ·  ⭐ 2K) - Python library for Representation Learning on Knowledge.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Accenture/AmpliGraph) (👨‍💻 20 · 🔀 230 · 📦 44 · 📋 220 - 13% open · ⏱️ 12.07.2023):

	```
	git clone https://github.com/Accenture/AmpliGraph
	```
- [PyPi](https://pypi.org/project/ampligraph) (📥 670 / month):
	```
	pip install ampligraph
	```
</details>
<details><summary><b><a href="https://github.com/pykeen/pykeen">PyKEEN</a></b> (🥈25 ·  ⭐ 1.4K) - A Python library for learning and evaluating knowledge graph embeddings. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pykeen/pykeen) (👨‍💻 36 · 🔀 170 · 📥 180 · 📋 510 - 16% open · ⏱️ 07.10.2023):

	```
	git clone https://github.com/pykeen/pykeen
	```
- [PyPi](https://pypi.org/project/pykeen) (📥 3.4K / month):
	```
	pip install pykeen
	```
</details>
<details><summary><b><a href="https://github.com/benedekrozemberczki/pytorch_geometric_temporal">pytorch_geometric_temporal</a></b> (🥈24 ·  ⭐ 2.2K) - PyTorch Geometric Temporal: Spatiotemporal Signal.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/benedekrozemberczki/pytorch_geometric_temporal) (👨‍💻 28 · 🔀 310 · 📋 170 - 8% open · ⏱️ 01.07.2023):

	```
	git clone https://github.com/benedekrozemberczki/pytorch_geometric_temporal
	```
- [PyPi](https://pypi.org/project/torch-geometric-temporal) (📥 1.8K / month):
	```
	pip install torch-geometric-temporal
	```
</details>
<details><summary><b><a href="https://github.com/eliorc/node2vec">Node2Vec</a></b> (🥈24 ·  ⭐ 1.1K) - Implementation of the node2vec algorithm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/eliorc/node2vec) (👨‍💻 12 · 🔀 220 · 📦 480 · 📋 90 - 3% open · ⏱️ 29.08.2023):

	```
	git clone https://github.com/eliorc/node2vec
	```
- [PyPi](https://pypi.org/project/node2vec) (📥 65K / month):
	```
	pip install node2vec
	```
- [Conda](https://anaconda.org/conda-forge/node2vec) (📥 27K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge node2vec
	```
</details>
<details><summary><b><a href="https://github.com/graph4ai/graph4nlp">graph4nlp</a></b> (🥉21 ·  ⭐ 1.6K · 💤) - Graph4nlp is the library for the easy use of Graph.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/graph4ai/graph4nlp) (👨‍💻 29 · 🔀 190 · 📋 170 - 3% open · ⏱️ 13.11.2022):

	```
	git clone https://github.com/graph4ai/graph4nlp
	```
- [PyPi](https://pypi.org/project/graph4nlp) (📥 80 / month):
	```
	pip install graph4nlp
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_cluster">torch-cluster</a></b> (🥉21 ·  ⭐ 700) - PyTorch Extension Library of Optimized Graph Cluster.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_cluster) (👨‍💻 32 · 🔀 120 · 📋 140 - 15% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/rusty1s/pytorch_cluster
	```
- [PyPi](https://pypi.org/project/torch-cluster) (📥 10K / month):
	```
	pip install torch-cluster
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_cluster) (📥 80K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pytorch_cluster
	```
</details>
<details><summary><b><a href="https://github.com/snap-stanford/deepsnap">deepsnap</a></b> (🥉20 ·  ⭐ 500 · 💤) - Python library assists deep learning on graphs. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snap-stanford/deepsnap) (👨‍💻 17 · 🔀 51 · 📥 10 · 📦 68 · 📋 44 - 45% open · ⏱️ 27.03.2023):

	```
	git clone https://github.com/snap-stanford/deepsnap
	```
- [PyPi](https://pypi.org/project/deepsnap) (📥 540 / month):
	```
	pip install deepsnap
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/graph_nets">graph-nets</a></b> (🥉19 ·  ⭐ 5.3K · 💤) - Build Graph Nets in Tensorflow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-deepmind/graph_nets) (👨‍💻 11 · 🔀 770 · 📦 18 · 📋 130 - 5% open · ⏱️ 12.12.2022):

	```
	git clone https://github.com/deepmind/graph_nets
	```
- [PyPi](https://pypi.org/project/graph-nets) (📥 820 / month):
	```
	pip install graph-nets
	```
</details>
<details><summary><b><a href="https://github.com/THUMNLab/AutoGL">AutoGL</a></b> (🥉16 ·  ⭐ 960 · 💤) - An autoML framework & toolkit for machine learning on graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/THUMNLab/AutoGL) (👨‍💻 15 · 🔀 110 · 📋 32 - 31% open · ⏱️ 30.12.2022):

	```
	git clone https://github.com/THUMNLab/AutoGL
	```
- [PyPi](https://pypi.org/project/auto-graph-learning) (📥 3 / month):
	```
	pip install auto-graph-learning
	```
</details>
<details><summary><b><a href="https://github.com/vaticle/typedb-ml">kglib</a></b> (🥉16 ·  ⭐ 550 · 💤) - TypeDB-ML is the Machine Learning integrations library for TypeDB. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/vaticle/typedb-ml) (👨‍💻 11 · 🔀 94 · 📥 220 · 📋 62 - 17% open · ⏱️ 09.11.2022):

	```
	git clone https://github.com/vaticle/kglib
	```
- [PyPi](https://pypi.org/project/grakn-kglib) (📥 74 / month):
	```
	pip install grakn-kglib
	```
</details>
<details><summary><b><a href="https://github.com/thunlp/OpenNE">OpenNE</a></b> (🥉14 ·  ⭐ 1.7K · 💤) - An Open-Source Package for Network Embedding (NE). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/thunlp/OpenNE) (👨‍💻 11 · 🔀 480 · 📋 100 - 3% open · ⏱️ 02.11.2022):

	```
	git clone https://github.com/thunlp/OpenNE
	```
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/networkx/networkx">networkx</a></b> (🥇41 ·  ⭐ 13K) - Network Analysis in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/stellargraph/stellargraph">StellarGraph</a></b> (🥈28 ·  ⭐ 2.8K · 💀) - StellarGraph - Machine Learning on Graphs. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/igraph/python-igraph">igraph</a></b> (🥈28 ·  ⭐ 1.2K) - Python interface for igraph. <code><a href="http://bit.ly/2KucAZR">❗️GPL-2.0</a></code>
- <b><a href="https://github.com/benedekrozemberczki/karateclub">Karate Club</a></b> (🥈24 ·  ⭐ 2K) - Karate Club: An API Oriented Open-source Python Framework for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/Kozea/pygal">pygal</a></b> (🥈23 ·  ⭐ 2.6K) - PYthon svg GrAph plotting Library. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/facebookresearch/PyTorch-BigGraph">PyTorch-BigGraph</a></b> (🥉21 ·  ⭐ 3.3K) - Generate embeddings from large-scale graph-structured.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/divelab/DIG">DIG</a></b> (🥉21 ·  ⭐ 1.6K) - A library for graph deep learning research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/google-deepmind/jraph">jraph</a></b> (🥉20 ·  ⭐ 1.2K · 💀) - A Graph Neural Network Library in Jax. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/IBCNServices/pyRDF2Vec">pyRDF2Vec</a></b> (🥉20 ·  ⭐ 230) - Python Implementation and Extension of RDF2Vec. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/phanein/deepwalk">DeepWalk</a></b> (🥉18 ·  ⭐ 2.6K · 💀) - DeepWalk - Deep Learning for Graphs. <code>❗Unlicensed</code>
- <b><a href="https://github.com/gsi-upm/sematch">Sematch</a></b> (🥉17 ·  ⭐ 410 · 💀) - semantic similarity framework for knowledge graph. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/shenweichen/GraphEmbedding">GraphEmbedding</a></b> (🥉16 ·  ⭐ 3.4K · 💀) - Implementation and experiments of graph embedding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/alibaba/euler">Euler</a></b> (🥉16 ·  ⭐ 2.9K · 💀) - A distributed graph deep learning framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/snap-stanford/GraphGym">GraphGym</a></b> (🥉16 ·  ⭐ 1.5K · 💤) - Platform for designing and evaluating Graph Neural Networks.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/williamleif/GraphSAGE">GraphSAGE</a></b> (🥉14 ·  ⭐ 3.2K · 💀) - Representation learning on large graphs using stochastic.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/DeepGraphLearning/graphvite">GraphVite</a></b> (🥉14 ·  ⭐ 1.2K · 💀) - GraphVite: A General and High-performance Graph Embedding.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/microsoft/ptgnn">ptgnn</a></b> (🥉14 ·  ⭐ 370 · 💀) - A PyTorch Graph Neural Network Library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/deepgraph/deepgraph">DeepGraph</a></b> (🥉14 ·  ⭐ 280) - Analyze Data with Pandas-based Networks. Documentation:. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/thunlp/OpenKE">OpenKE</a></b> (🥉13 ·  ⭐ 3.5K · 💤) - An Open-Source Package for Knowledge Embedding (KE). <code>❗Unlicensed</code>
</details>
<br>

## Audio Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for audio analysis, manipulation, transformation, and extraction, as well as speech recognition and music generation tasks._

<details><summary><b><a href="https://github.com/speechbrain/speechbrain">speechbrain</a></b> (🥇38 ·  ⭐ 6.7K) - A PyTorch-based Speech Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/speechbrain/speechbrain) (👨‍💻 220 · 🔀 1.1K · 📦 990 · 📋 950 - 9% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/speechbrain/speechbrain
	```
- [PyPi](https://pypi.org/project/speechbrain) (📥 180K / month):
	```
	pip install speechbrain
	```
</details>
<details><summary><b><a href="https://github.com/espnet/espnet">espnet</a></b> (🥇37 ·  ⭐ 7.1K) - End-to-End Speech Processing Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/espnet/espnet) (👨‍💻 380 · 🔀 1.9K · 📥 79 · 📦 240 · 📋 2.2K - 7% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/espnet/espnet
	```
- [PyPi](https://pypi.org/project/espnet) (📥 28K / month):
	```
	pip install espnet
	```
</details>
<details><summary><b><a href="https://github.com/jiaaro/pydub">Pydub</a></b> (🥇33 ·  ⭐ 7.7K · 💤) - Manipulate audio with a simple and easy high level interface. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jiaaro/pydub) (👨‍💻 95 · 🔀 950 · 📦 40K · 📋 540 - 50% open · ⏱️ 08.12.2022):

	```
	git clone https://github.com/jiaaro/pydub
	```
- [PyPi](https://pypi.org/project/pydub) (📥 3.1M / month):
	```
	pip install pydub
	```
- [Conda](https://anaconda.org/conda-forge/pydub) (📥 69K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pydub
	```
</details>
<details><summary><b><a href="https://github.com/coqui-ai/TTS">Coqui TTS</a></b> (🥈32 ·  ⭐ 20K) - - a deep learning toolkit for Text-to-Speech, battle-.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/coqui-ai/TTS) (👨‍💻 150 · 🔀 2.2K · 📥 1.4M · 📋 730 - 3% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/coqui-ai/TTS
	```
- [PyPi](https://pypi.org/project/tts) (📥 84K / month):
	```
	pip install tts
	```
- [Conda](https://anaconda.org/conda-forge/tts) (📥 9.7K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tts
	```
</details>
<details><summary><b><a href="https://github.com/magenta/magenta">Magenta</a></b> (🥈32 ·  ⭐ 19K) - Magenta: Music and Art Generation with Machine Intelligence. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/magenta) (👨‍💻 160 · 🔀 3.6K · 📦 470 · 📋 940 - 37% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/magenta/magenta
	```
- [PyPi](https://pypi.org/project/magenta) (📥 2.6K / month):
	```
	pip install magenta
	```
</details>
<details><summary><b><a href="https://github.com/deezer/spleeter">spleeter</a></b> (🥈31 ·  ⭐ 24K) - Deezer source separation library including pretrained models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deezer/spleeter) (👨‍💻 19 · 🔀 2.6K · 📥 2.7M · 📦 590 · 📋 740 - 25% open · ⏱️ 13.07.2023):

	```
	git clone https://github.com/deezer/spleeter
	```
- [PyPi](https://pypi.org/project/spleeter) (📥 16K / month):
	```
	pip install spleeter
	```
- [Conda](https://anaconda.org/conda-forge/spleeter) (📥 78K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge spleeter
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/audio">torchaudio</a></b> (🥈31 ·  ⭐ 2.2K) - Data manipulation and transformation for audio signal.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/audio) (👨‍💻 220 · 🔀 570 · 📋 850 - 18% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pytorch/audio
	```
- [PyPi](https://pypi.org/project/torchaudio) (📥 1.5M / month):
	```
	pip install torchaudio
	```
</details>
<details><summary><b><a href="https://github.com/Uberi/speech_recognition">SpeechRecognition</a></b> (🥈30 ·  ⭐ 7.6K · 💤) - Speech recognition module for Python, supporting.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Uberi/speech_recognition) (👨‍💻 49 · 🔀 2.2K · 📦 18 · 📋 570 - 46% open · ⏱️ 13.03.2023):

	```
	git clone https://github.com/Uberi/speech_recognition
	```
- [PyPi](https://pypi.org/project/SpeechRecognition) (📥 450K / month):
	```
	pip install SpeechRecognition
	```
- [Conda](https://anaconda.org/conda-forge/speechrecognition) (📥 170K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge speechrecognition
	```
</details>
<details><summary><b><a href="https://github.com/iver56/audiomentations">audiomentations</a></b> (🥈30 ·  ⭐ 1.5K) - A Python library for audio data augmentation. Inspired by.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/iver56/audiomentations) (👨‍💻 24 · 🔀 170 · 📦 350 · 📋 160 - 25% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/iver56/audiomentations
	```
- [PyPi](https://pypi.org/project/audiomentations) (📥 11K / month):
	```
	pip install audiomentations
	```
</details>
<details><summary><b><a href="https://github.com/librosa/librosa">librosa</a></b> (🥈28 ·  ⭐ 6.2K) - Python library for audio and music analysis. <code><a href="http://bit.ly/3hkKRql">ISC</a></code></summary>

- [GitHub](https://github.com/librosa/librosa) (👨‍💻 120 · 🔀 870 · 📋 1.1K - 4% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/librosa/librosa
	```
- [PyPi](https://pypi.org/project/librosa) (📥 2.1M / month):
	```
	pip install librosa
	```
- [Conda](https://anaconda.org/conda-forge/librosa) (📥 700K · ⏱️ 16.08.2023):
	```
	conda install -c conda-forge librosa
	```
</details>
<details><summary><b><a href="https://github.com/beetbox/audioread">audioread</a></b> (🥈28 ·  ⭐ 450) - cross-library (GStreamer + Core Audio + MAD + FFmpeg) audio decoding.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/beetbox/audioread) (👨‍💻 24 · 🔀 100 · 📦 16K · 📋 86 - 37% open · ⏱️ 17.08.2023):

	```
	git clone https://github.com/beetbox/audioread
	```
- [PyPi](https://pypi.org/project/audioread) (📥 1.3M / month):
	```
	pip install audioread
	```
- [Conda](https://anaconda.org/conda-forge/audioread) (📥 710K · ⏱️ 30.09.2023):
	```
	conda install -c conda-forge audioread
	```
</details>
<details><summary><b><a href="https://github.com/Picovoice/porcupine">Porcupine</a></b> (🥉27 ·  ⭐ 3.2K) - On-device wake word detection powered by deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Picovoice/porcupine) (👨‍💻 36 · 🔀 440 · 📦 22 · ⏱️ 10.10.2023):

	```
	git clone https://github.com/Picovoice/Porcupine
	```
- [PyPi](https://pypi.org/project/pvporcupine) (📥 3.7K / month):
	```
	pip install pvporcupine
	```
</details>
<details><summary><b><a href="https://github.com/magenta/ddsp">DDSP</a></b> (🥉24 ·  ⭐ 2.6K) - DDSP: Differentiable Digital Signal Processing. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/magenta/ddsp) (👨‍💻 32 · 🔀 300 · 📦 44 · 📋 160 - 23% open · ⏱️ 30.06.2023):

	```
	git clone https://github.com/magenta/ddsp
	```
- [PyPi](https://pypi.org/project/ddsp) (📥 1.5K / month):
	```
	pip install ddsp
	```
- [Conda](https://anaconda.org/conda-forge/ddsp) (📥 14K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ddsp
	```
</details>
<details><summary><b><a href="https://github.com/bastibe/python-soundfile">python-soundfile</a></b> (🥉22 ·  ⭐ 590 · 💤) - SoundFile is an audio library based on libsndfile, CFFI,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/bastibe/python-soundfile) (👨‍💻 30 · 🔀 92 · 📥 16K · 📋 220 - 41% open · ⏱️ 24.03.2023):

	```
	git clone https://github.com/bastibe/python-soundfile
	```
- [PyPi](https://pypi.org/project/soundfile) (📥 1.4M / month):
	```
	pip install soundfile
	```
- [Conda](https://anaconda.org/anaconda/pysoundfile):
	```
	conda install -c anaconda pysoundfile
	```
</details>
<details><summary><b><a href="https://github.com/KinWaiCheuk/nnAudio">nnAudio</a></b> (🥉20 ·  ⭐ 900) - Audio processing by using pytorch 1D convolution network. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/KinWaiCheuk/nnAudio) (👨‍💻 15 · 🔀 85 · 📦 130 · 📋 59 - 28% open · ⏱️ 04.09.2023):

	```
	git clone https://github.com/KinWaiCheuk/nnAudio
	```
- [PyPi](https://pypi.org/project/nnAudio) (📥 2.7K / month):
	```
	pip install nnAudio
	```
</details>
<details><summary><b><a href="https://github.com/devsnd/tinytag">tinytag</a></b> (🥉20 ·  ⭐ 620 · 📉) - Read audio and music meta data and duration of MP3, OGG, OPUS, MP4,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/devsnd/tinytag) (👨‍💻 26 · 🔀 93 · 📋 100 - 8% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/devsnd/tinytag
	```
- [PyPi](https://pypi.org/project/tinytag) (📥 14K / month):
	```
	pip install tinytag
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/aubio/aubio">aubio</a></b> (🥈28 ·  ⭐ 3K · 💀) - a library for audio and music analysis. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/tyiannak/pyAudioAnalysis">pyAudioAnalysis</a></b> (🥉27 ·  ⭐ 5.4K · 💀) - Python Audio Analysis Library: Feature Extraction,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/MTG/essentia">Essentia</a></b> (🥉26 ·  ⭐ 2.5K) - C++ library for audio and music analysis, description and.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/mozilla/TTS">TTS</a></b> (🥉25 ·  ⭐ 8K · 💀) - Deep learning for Text to Speech (Discussion forum:.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/jameslyons/python_speech_features">python_speech_features</a></b> (🥉25 ·  ⭐ 2.3K · 💀) - This library provides common speech features for ASR.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/CPJKU/madmom">Madmom</a></b> (🥉25 ·  ⭐ 1.2K) - Python audio and music signal processing library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/worldveil/dejavu">Dejavu</a></b> (🥉21 ·  ⭐ 6.1K · 💀) - Audio fingerprinting and recognition in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/keunwoochoi/kapre">kapre</a></b> (🥉21 ·  ⭐ 900 · 💀) - kapre: Keras Audio Preprocessors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Ircam-WAM/TimeSide">TimeSide</a></b> (🥉20 ·  ⭐ 350 · 💤) - scalable audio processing framework and server written in.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/adefossez/julius">Julius</a></b> (🥉18 ·  ⭐ 370 · 💀) - Fast PyTorch based DSP for audio and 1D signals. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bmcfee/muda">Muda</a></b> (🥉17 ·  ⭐ 220 · 💀) - A library for augmenting annotated audio data. <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
</details>
<br>

## Geospatial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to load, process, analyze, and write geographic data as well as libraries for spatial analysis, map visualization, and geocoding._

<details><summary><b><a href="https://github.com/visgl/deck.gl">pydeck</a></b> (🥇42 ·  ⭐ 11K) - WebGL2 powered visualization framework. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/visgl/deck.gl) (👨‍💻 240 · 🔀 2K · 📦 6.6K · 📋 2.8K - 7% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/visgl/deck.gl
	```
- [PyPi](https://pypi.org/project/pydeck) (📥 1.5M / month):
	```
	pip install pydeck
	```
- [Conda](https://anaconda.org/conda-forge/pydeck) (📥 450K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pydeck
	```
- [npm](https://www.npmjs.com/package/deck.gl) (📥 500K / month):
	```
	npm install deck.gl
	```
</details>
<details><summary><b><a href="https://github.com/geopandas/geopandas">GeoPandas</a></b> (🥇39 ·  ⭐ 3.9K) - Python tools for geographic data. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/geopandas/geopandas) (👨‍💻 210 · 🔀 820 · 📥 2.2K · 📦 27K · 📋 1.5K - 23% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/geopandas/geopandas
	```
- [PyPi](https://pypi.org/project/geopandas) (📥 6M / month):
	```
	pip install geopandas
	```
- [Conda](https://anaconda.org/conda-forge/geopandas) (📥 3.2M · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge geopandas
	```
</details>
<details><summary><b><a href="https://github.com/python-visualization/folium">folium</a></b> (🥇38 ·  ⭐ 6.4K) - Python Data. Leaflet.js Maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/python-visualization/folium) (👨‍💻 150 · 🔀 2.2K · 📦 30K · 📋 1K - 5% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/python-visualization/folium
	```
- [PyPi](https://pypi.org/project/folium) (📥 670K / month):
	```
	pip install folium
	```
- [Conda](https://anaconda.org/conda-forge/folium) (📥 2.4M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge folium
	```
</details>
<details><summary><b><a href="https://github.com/shapely/shapely">Shapely</a></b> (🥈37 ·  ⭐ 3.4K) - Manipulation and analysis of geometric objects. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/shapely/shapely) (👨‍💻 150 · 🔀 530 · 📥 2.6K · 📦 54K · 📋 1.1K - 19% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/shapely/shapely
	```
- [PyPi](https://pypi.org/project/shapely) (📥 15M / month):
	```
	pip install shapely
	```
- [Conda](https://anaconda.org/conda-forge/shapely) (📥 8.5M · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge shapely
	```
</details>
<details><summary><b><a href="https://github.com/pyproj4/pyproj">pyproj</a></b> (🥈36 ·  ⭐ 920) - Python interface to PROJ (cartographic projections and coordinate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyproj4/pyproj) (👨‍💻 64 · 🔀 200 · 📦 24K · 📋 580 - 3% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/pyproj4/pyproj
	```
- [PyPi](https://pypi.org/project/pyproj) (📥 7.8M / month):
	```
	pip install pyproj
	```
- [Conda](https://anaconda.org/conda-forge/pyproj) (📥 6.8M · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge pyproj
	```
</details>
<details><summary><b><a href="https://github.com/Toblerity/Fiona">Fiona</a></b> (🥈34 ·  ⭐ 1.1K) - Fiona reads and writes geographic data files. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/Toblerity/Fiona) (👨‍💻 71 · 🔀 190 · 📦 15K · 📋 760 - 4% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/Toblerity/Fiona
	```
- [PyPi](https://pypi.org/project/fiona) (📥 6.3M / month):
	```
	pip install fiona
	```
- [Conda](https://anaconda.org/conda-forge/fiona) (📥 5M · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge fiona
	```
</details>
<details><summary><b><a href="https://github.com/jupyter-widgets/ipyleaflet">ipyleaflet</a></b> (🥈33 ·  ⭐ 1.4K) - A Jupyter - Leaflet.js bridge. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jupyter-widgets/ipyleaflet) (👨‍💻 85 · 🔀 340 · 📦 5.5K · 📋 570 - 39% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/jupyter-widgets/ipyleaflet
	```
- [PyPi](https://pypi.org/project/ipyleaflet) (📥 160K / month):
	```
	pip install ipyleaflet
	```
- [Conda](https://anaconda.org/conda-forge/ipyleaflet) (📥 1.1M · ⏱️ 11.09.2023):
	```
	conda install -c conda-forge ipyleaflet
	```
- [npm](https://www.npmjs.com/package/jupyter-leaflet) (📥 46K / month):
	```
	npm install jupyter-leaflet
	```
</details>
<details><summary><b><a href="https://github.com/Esri/arcgis-python-api">ArcGIS API</a></b> (🥉31 ·  ⭐ 1.6K) - Documentation and samples for ArcGIS API for Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Esri/arcgis-python-api) (👨‍💻 89 · 🔀 1K · 📥 9.4K · 📦 3 · 📋 620 - 5% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/Esri/arcgis-python-api
	```
- [PyPi](https://pypi.org/project/arcgis) (📥 72K / month):
	```
	pip install arcgis
	```
- [Docker Hub](https://hub.docker.com/r/esridocker/arcgis-api-python-notebook):
	```
	docker pull esridocker/arcgis-api-python-notebook
	```
</details>
<details><summary><b><a href="https://github.com/geopy/geopy">geopy</a></b> (🥉30 ·  ⭐ 4.1K) - Geocoding library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/geopy/geopy) (👨‍💻 130 · 🔀 600 · 📥 2 · 📋 270 - 8% open · ⏱️ 27.08.2023):

	```
	git clone https://github.com/geopy/geopy
	```
- [PyPi](https://pypi.org/project/geopy) (📥 4.1M / month):
	```
	pip install geopy
	```
- [Conda](https://anaconda.org/conda-forge/geopy) (📥 1.2M · ⏱️ 27.08.2023):
	```
	conda install -c conda-forge geopy
	```
</details>
<details><summary><b><a href="https://github.com/jazzband/geojson">geojson</a></b> (🥉28 ·  ⭐ 840) - Python bindings and utilities for GeoJSON. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/jazzband/geojson) (👨‍💻 54 · 🔀 120 · 📦 16K · 📋 96 - 23% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/jazzband/geojson
	```
- [PyPi](https://pypi.org/project/geojson) (📥 1.2M / month):
	```
	pip install geojson
	```
- [Conda](https://anaconda.org/conda-forge/geojson) (📥 760K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge geojson
	```
</details>
<details><summary><b><a href="https://github.com/holoviz/geoviews">GeoViews</a></b> (🥉28 ·  ⭐ 510) - Simple, concise geographical visualization in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/holoviz/geoviews) (👨‍💻 29 · 🔀 70 · 📦 780 · 📋 330 - 32% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/holoviz/geoviews
	```
- [PyPi](https://pypi.org/project/geoviews) (📥 7K / month):
	```
	pip install geoviews
	```
- [Conda](https://anaconda.org/conda-forge/geoviews) (📥 200K · ⏱️ 21.07.2023):
	```
	conda install -c conda-forge geoviews
	```
</details>
<details><summary><b><a href="https://github.com/earthlab/earthpy">EarthPy</a></b> (🥉26 ·  ⭐ 460) - A package built to support working with spatial data using open source.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/earthlab/earthpy) (👨‍💻 44 · 🔀 150 · 📦 250 · 📋 230 - 10% open · ⏱️ 23.08.2023):

	```
	git clone https://github.com/earthlab/earthpy
	```
- [PyPi](https://pypi.org/project/earthpy) (📥 4.6K / month):
	```
	pip install earthpy
	```
- [Conda](https://anaconda.org/conda-forge/earthpy) (📥 69K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge earthpy
	```
</details>
<details><summary><b><a href="https://github.com/pysal/pysal">PySAL</a></b> (🥉25 ·  ⭐ 1.2K) - PySAL: Python Spatial Analysis Library Meta-Package. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/pysal/pysal) (👨‍💻 78 · 🔀 270 · 📋 620 - 2% open · ⏱️ 05.09.2023):

	```
	git clone https://github.com/pysal/pysal
	```
- [PyPi](https://pypi.org/project/pysal) (📥 21K / month):
	```
	pip install pysal
	```
- [Conda](https://anaconda.org/conda-forge/pysal) (📥 520K · ⏱️ 04.10.2023):
	```
	conda install -c conda-forge pysal
	```
</details>
<details><summary><b><a href="https://github.com/geospace-code/pymap3d">pymap3d</a></b> (🥉23 ·  ⭐ 330 · 💤) - pure-Python (Numpy optional) 3D coordinate conversions for geospace.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/geospace-code/pymap3d) (👨‍💻 14 · 🔀 79 · 📦 320 · 📋 50 - 12% open · ⏱️ 05.03.2023):

	```
	git clone https://github.com/geospace-code/pymap3d
	```
- [PyPi](https://pypi.org/project/pymap3d) (📥 69K / month):
	```
	pip install pymap3d
	```
- [Conda](https://anaconda.org/conda-forge/pymap3d) (📥 61K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pymap3d
	```
</details>
<details><summary>Show 8 hidden projects...</summary>

- <b><a href="https://github.com/rasterio/rasterio">Rasterio</a></b> (🥈33 ·  ⭐ 2K) - Rasterio reads and writes geospatial raster datasets. <code>❗Unlicensed</code>
- <b><a href="https://github.com/DenisCarriere/geocoder">Geocoder</a></b> (🥈32 ·  ⭐ 1.6K · 💀) - Python Geocoder. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/pytroll/satpy">Satpy</a></b> (🥉30 ·  ⭐ 960) - Python package for earth-observing satellite data processing. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/sentinelsat/sentinelsat">Sentinelsat</a></b> (🥉27 ·  ⭐ 920 · 💤) - Search and download Copernicus Sentinel satellite images. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/mapbox/mapboxgl-jupyter">Mapbox GL</a></b> (🥉23 ·  ⭐ 640 · 💀) - Use Mapbox GL JS to visualize data in a Python Jupyter notebook. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/marceloprates/prettymaps">prettymaps</a></b> (🥉21 ·  ⭐ 10K · 💤) - A small set of Python functions to draw pretty maps from.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/pbugnion/gmaps">gmaps</a></b> (🥉20 ·  ⭐ 760 · 💀) - Google maps for Jupyter notebooks. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/andrea-cuttone/geoplotlib">geoplotlib</a></b> (🥉18 ·  ⭐ 1K · 💀) - python toolbox for visualizing geographical data and making maps. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Financial Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for algorithmic stock/crypto trading, risk analytics, backtesting, technical analysis, and other tasks on financial data._

<details><summary><b><a href="https://github.com/ranaroussi/yfinance">yfinance</a></b> (🥇39 ·  ⭐ 10K) - Download market data from Yahoo! Finances API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ranaroussi/yfinance) (👨‍💻 93 · 🔀 1.9K · 📦 28K · 📋 1.2K - 13% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/ranaroussi/yfinance
	```
- [PyPi](https://pypi.org/project/yfinance) (📥 1.2M / month):
	```
	pip install yfinance
	```
- [Conda](https://anaconda.org/ranaroussi/yfinance) (📥 81K · ⏱️ 16.06.2023):
	```
	conda install -c ranaroussi yfinance
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/qlib">Qlib</a></b> (🥈31 ·  ⭐ 13K) - Qlib is an AI-oriented quantitative investment platform that aims to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/qlib) (👨‍💻 120 · 🔀 2.1K · 📥 370 · 📦 18 · 📋 790 - 26% open · ⏱️ 15.09.2023):

	```
	git clone https://github.com/microsoft/qlib
	```
- [PyPi](https://pypi.org/project/pyqlib) (📥 1.9K / month):
	```
	pip install pyqlib
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/bt">bt</a></b> (🥈29 ·  ⭐ 1.8K) - bt - flexible backtesting for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/bt) (👨‍💻 28 · 🔀 370 · 📦 1.6K · 📋 330 - 23% open · ⏱️ 04.09.2023):

	```
	git clone https://github.com/pmorissette/bt
	```
- [PyPi](https://pypi.org/project/bt) (📥 9.2K / month):
	```
	pip install bt
	```
- [Conda](https://anaconda.org/conda-forge/bt) (📥 18K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge bt
	```
</details>
<details><summary><b><a href="https://github.com/pmorissette/ffn">ffn</a></b> (🥈29 ·  ⭐ 1.6K) - ffn - a financial function library for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pmorissette/ffn) (👨‍💻 30 · 🔀 260 · 📦 370 · 📋 120 - 18% open · ⏱️ 14.09.2023):

	```
	git clone https://github.com/pmorissette/ffn
	```
- [PyPi](https://pypi.org/project/ffn) (📥 160K / month):
	```
	pip install ffn
	```
- [Conda](https://anaconda.org/conda-forge/ffn) (📥 5.6K · ⏱️ 15.06.2023):
	```
	conda install -c conda-forge ffn
	```
</details>
<details><summary><b><a href="https://github.com/RomelTorres/alpha_vantage">Alpha Vantage</a></b> (🥈28 ·  ⭐ 4K · 💤) - A python wrapper for Alpha Vantage API for financial data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/RomelTorres/alpha_vantage) (👨‍💻 42 · 🔀 700 · 📦 400 · 📋 270 - 0% open · ⏱️ 25.12.2022):

	```
	git clone https://github.com/RomelTorres/alpha_vantage
	```
- [PyPi](https://pypi.org/project/alpha_vantage) (📥 25K / month):
	```
	pip install alpha_vantage
	```
- [Conda](https://anaconda.org/conda-forge/alpha_vantage) (📥 5.5K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge alpha_vantage
	```
</details>
<details><summary><b><a href="https://github.com/erdewit/ib_insync">IB-insync</a></b> (🥉25 ·  ⭐ 2.4K) - Python sync/async framework for Interactive Brokers API. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/erdewit/ib_insync) (👨‍💻 36 · 🔀 580 · 📋 540 - 0% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/erdewit/ib_insync
	```
- [PyPi](https://pypi.org/project/ib_insync) (📥 33K / month):
	```
	pip install ib_insync
	```
- [Conda](https://anaconda.org/conda-forge/ib-insync) (📥 36K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ib-insync
	```
</details>
<details><summary><b><a href="https://github.com/fmilthaler/FinQuant">FinQuant</a></b> (🥉23 ·  ⭐ 1.1K) - A program for financial portfolio management, analysis and optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/fmilthaler/FinQuant) (👨‍💻 7 · 🔀 160 · 📦 82 · 📋 47 - 31% open · ⏱️ 03.09.2023):

	```
	git clone https://github.com/fmilthaler/FinQuant
	```
- [PyPi](https://pypi.org/project/FinQuant) (📥 1.2K / month):
	```
	pip install FinQuant
	```
</details>
<details><summary><b><a href="https://github.com/gbeced/pyalgotrade">PyAlgoTrade</a></b> (🥉22 ·  ⭐ 4.2K · 💤) - Python Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gbeced/pyalgotrade) (👨‍💻 11 · 🔀 1.3K · 📦 170 · ⏱️ 05.03.2023):

	```
	git clone https://github.com/gbeced/pyalgotrade
	```
- [PyPi](https://pypi.org/project/pyalgotrade) (📥 580 / month):
	```
	pip install pyalgotrade
	```
</details>
<details><summary><b><a href="https://github.com/google/tf-quant-finance">tf-quant-finance</a></b> (🥉20 ·  ⭐ 4K) - High-performance TensorFlow library for quantitative.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/tf-quant-finance) (👨‍💻 47 · 🔀 510 · 📋 53 - 47% open · ⏱️ 15.08.2023):

	```
	git clone https://github.com/google/tf-quant-finance
	```
- [PyPi](https://pypi.org/project/tf-quant-finance) (📥 430 / month):
	```
	pip install tf-quant-finance
	```
</details>
<details><summary><b><a href="https://github.com/cuemacro/finmarketpy">finmarketpy</a></b> (🥉20 ·  ⭐ 3.2K) - Python library for backtesting trading strategies & analyzing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cuemacro/finmarketpy) (👨‍💻 14 · 🔀 460 · 📥 47 · 📦 10 · 📋 28 - 85% open · ⏱️ 26.04.2023):

	```
	git clone https://github.com/cuemacro/finmarketpy
	```
- [PyPi](https://pypi.org/project/finmarketpy) (📥 140 / month):
	```
	pip install finmarketpy
	```
</details>
<details><summary>Show 15 hidden projects...</summary>

- <b><a href="https://github.com/quantopian/zipline">zipline</a></b> (🥇32 ·  ⭐ 17K · 💀) - Zipline, a Pythonic Algorithmic Trading Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/pyfolio">pyfolio</a></b> (🥇32 ·  ⭐ 5.2K · 💀) - Portfolio and risk analytics in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/bashtage/arch">arch</a></b> (🥈31 ·  ⭐ 1.2K) - ARCH models in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/mementum/backtrader">backtrader</a></b> (🥈28 ·  ⭐ 12K) - Python Backtesting library for trading strategies. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/bukosabino/ta">ta</a></b> (🥈28 ·  ⭐ 3.8K · 💀) - Technical Analysis Library using Pandas and Numpy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/quantopian/empyrical">empyrical</a></b> (🥈28 ·  ⭐ 1.1K · 💀) - Common financial risk and performance metrics. Used by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/quantopian/alphalens">Alphalens</a></b> (🥉26 ·  ⭐ 2.8K · 💀) - Performance analysis of predictive (alpha) stock factors. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/tensortrade-org/tensortrade">TensorTrade</a></b> (🥉25 ·  ⭐ 4.3K · 💀) - An open source reinforcement learning framework for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jealous/stockstats">stockstats</a></b> (🥉24 ·  ⭐ 1.2K) - Supply a wrapper ``StockDataFrame`` based on the.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/scrtlabs/catalyst">Enigma Catalyst</a></b> (🥉23 ·  ⭐ 2.4K · 💀) - An Algorithmic Trading Library for Crypto-Assets in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/peerchemist/finta">FinTA</a></b> (🥉23 ·  ⭐ 2K · 💀) - Common financial technical indicators implemented in Pandas. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/CryptoSignal/Crypto-Signal">Crypto Signals</a></b> (🥉22 ·  ⭐ 4.5K · 💀) - Github.com/CryptoSignal - Trading & Technical Analysis Bot -.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kernc/backtesting.py">Backtesting.py</a></b> (🥉20 ·  ⭐ 4.1K · 💤) - Backtest trading strategies in Python. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/tradytics/surpriver">surpriver</a></b> (🥉12 ·  ⭐ 1.6K · 💀) - Find big moving stocks before they move using machine.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/alvarobartt/pyrtfolio">pyrtfolio</a></b> (🥉8 ·  ⭐ 140 · 💀) - Python package to generate stock portfolios. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
</details>
<br>

## Time Series Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for forecasting, anomaly detection, feature extraction, and machine learning on time-series and sequential data._

<details><summary><b><a href="https://github.com/sktime/sktime">sktime</a></b> (🥇39 ·  ⭐ 7K) - A unified framework for machine learning with time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/sktime/sktime) (👨‍💻 300 · 🔀 1.1K · 📥 84 · 📦 1.7K · 📋 2K - 34% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/alan-turing-institute/sktime
	```
- [PyPi](https://pypi.org/project/sktime) (📥 720K / month):
	```
	pip install sktime
	```
- [Conda](https://anaconda.org/conda-forge/sktime-all-extras) (📥 910K · ⏱️ 17.09.2023):
	```
	conda install -c conda-forge sktime-all-extras
	```
</details>
<details><summary><b><a href="https://github.com/facebook/prophet">Prophet</a></b> (🥇34 ·  ⭐ 17K) - Tool for producing high quality forecasts for time series data that has.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebook/prophet) (👨‍💻 170 · 🔀 4.4K · 📥 2.1K · 📦 18 · 📋 2.1K - 16% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/facebook/prophet
	```
- [PyPi](https://pypi.org/project/fbprophet) (📥 910K / month):
	```
	pip install fbprophet
	```
- [Conda](https://anaconda.org/conda-forge/prophet) (📥 1.1M · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge prophet
	```
</details>
<details><summary><b><a href="https://github.com/tslearn-team/tslearn">tslearn</a></b> (🥇33 ·  ⭐ 2.6K) - A machine learning toolkit dedicated to time-series data. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tslearn-team/tslearn) (👨‍💻 43 · 🔀 310 · 📦 970 · 📋 300 - 36% open · ⏱️ 28.09.2023):

	```
	git clone https://github.com/tslearn-team/tslearn
	```
- [PyPi](https://pypi.org/project/tslearn) (📥 290K / month):
	```
	pip install tslearn
	```
- [Conda](https://anaconda.org/conda-forge/tslearn) (📥 1.2M · ⏱️ 21.08.2023):
	```
	conda install -c conda-forge tslearn
	```
</details>
<details><summary><b><a href="https://github.com/TDAmeritrade/stumpy">STUMPY</a></b> (🥈32 ·  ⭐ 2.8K) - STUMPY is a powerful and scalable Python library for modern time series.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/TDAmeritrade/stumpy) (👨‍💻 34 · 🔀 270 · 📦 540 · 📋 450 - 10% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/TDAmeritrade/stumpy
	```
- [PyPi](https://pypi.org/project/stumpy) (📥 230K / month):
	```
	pip install stumpy
	```
- [Conda](https://anaconda.org/conda-forge/stumpy) (📥 940K · ⏱️ 21.08.2023):
	```
	conda install -c conda-forge stumpy
	```
</details>
<details><summary><b><a href="https://github.com/alkaline-ml/pmdarima">pmdarima</a></b> (🥈32 ·  ⭐ 1.4K) - A statistical library designed to fill the void in Pythons time series.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/alkaline-ml/pmdarima) (👨‍💻 22 · 🔀 220 · 📦 6.3K · 📋 320 - 15% open · ⏱️ 03.07.2023):

	```
	git clone https://github.com/alkaline-ml/pmdarima
	```
- [PyPi](https://pypi.org/project/pmdarima) (📥 1.6M / month):
	```
	pip install pmdarima
	```
- [Conda](https://anaconda.org/conda-forge/pmdarima) (📥 1M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pmdarima
	```
</details>
<details><summary><b><a href="https://github.com/unit8co/darts">Darts</a></b> (🥈31 ·  ⭐ 6.5K) - A python library for user-friendly forecasting and anomaly detection.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/unit8co/darts) (👨‍💻 100 · 🔀 720 · 📦 380 · 📋 1.2K - 20% open · ⏱️ 16.09.2023):

	```
	git clone https://github.com/unit8co/darts
	```
- [PyPi](https://pypi.org/project/u8darts) (📥 13K / month):
	```
	pip install u8darts
	```
- [Conda](https://anaconda.org/conda-forge/u8darts-all) (📥 36K · ⏱️ 16.09.2023):
	```
	conda install -c conda-forge u8darts-all
	```
- [Docker Hub](https://hub.docker.com/r/unit8/darts) (📥 410 · ⏱️ 16.09.2023):
	```
	docker pull unit8/darts
	```
</details>
<details><summary><b><a href="https://github.com/blue-yonder/tsfresh">tsfresh</a></b> (🥈30 ·  ⭐ 7.8K) - Automatic extraction of relevant features from time series:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/blue-yonder/tsfresh) (👨‍💻 90 · 🔀 1.2K · 📦 18 · 📋 520 - 9% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/blue-yonder/tsfresh
	```
- [PyPi](https://pypi.org/project/tsfresh) (📥 230K / month):
	```
	pip install tsfresh
	```
- [Conda](https://anaconda.org/conda-forge/tsfresh) (📥 1.3M · ⏱️ 30.07.2023):
	```
	conda install -c conda-forge tsfresh
	```
</details>
<details><summary><b><a href="https://github.com/Nixtla/statsforecast">StatsForecast</a></b> (🥈30 ·  ⭐ 3K) - Lightning fast forecasting with statistical and econometric.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Nixtla/statsforecast) (👨‍💻 31 · 🔀 210 · 📦 500 · 📋 240 - 43% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/Nixtla/statsforecast
	```
- [PyPi](https://pypi.org/project/statsforecast) (📥 390K / month):
	```
	pip install statsforecast
	```
- [Conda](https://anaconda.org/conda-forge/statsforecast) (📥 51K · ⏱️ 25.08.2023):
	```
	conda install -c conda-forge statsforecast
	```
</details>
<details><summary><b><a href="https://github.com/awslabs/gluonts">GluonTS</a></b> (🥈29 ·  ⭐ 3.8K) - Probabilistic time series modeling in Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/awslabs/gluonts) (👨‍💻 110 · 🔀 680 · 📋 880 - 30% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/awslabs/gluon-ts
	```
- [PyPi](https://pypi.org/project/gluonts) (📥 170K / month):
	```
	pip install gluonts
	```
- [Conda](https://anaconda.org/anaconda/gluonts) (📥 570 · ⏱️ 23.06.2023):
	```
	conda install -c anaconda gluonts
	```
</details>
<details><summary><b><a href="https://github.com/ourownstory/neural_prophet">NeuralProphet</a></b> (🥈28 ·  ⭐ 3.3K) - NeuralProphet: A simple forecasting package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/ourownstory/neural_prophet) (👨‍💻 45 · 🔀 430 · 📋 480 - 7% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/ourownstory/neural_prophet
	```
- [PyPi](https://pypi.org/project/neuralprophet) (📥 92K / month):
	```
	pip install neuralprophet
	```
</details>
<details><summary><b><a href="https://github.com/johannfaouzi/pyts">pyts</a></b> (🥈28 ·  ⭐ 1.6K) - A Python package for time series classification. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/johannfaouzi/pyts) (👨‍💻 14 · 🔀 150 · 📦 470 · 📋 75 - 54% open · ⏱️ 20.06.2023):

	```
	git clone https://github.com/johannfaouzi/pyts
	```
- [PyPi](https://pypi.org/project/pyts) (📥 130K / month):
	```
	pip install pyts
	```
- [Conda](https://anaconda.org/conda-forge/pyts) (📥 21K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge pyts
	```
</details>
<details><summary><b><a href="https://github.com/jdb78/pytorch-forecasting">pytorch-forecasting</a></b> (🥉27 ·  ⭐ 3.2K) - Time series forecasting with PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jdb78/pytorch-forecasting) (👨‍💻 43 · 🔀 510 · 📋 680 - 59% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/jdb78/pytorch-forecasting
	```
- [PyPi](https://pypi.org/project/pytorch-forecasting) (📥 57K / month):
	```
	pip install pytorch-forecasting
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-forecasting) (📥 51K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pytorch-forecasting
	```
</details>
<details><summary><b><a href="https://github.com/python-streamz/streamz">Streamz</a></b> (🥉25 ·  ⭐ 1.2K · 💤) - Real-time stream processing for python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/python-streamz/streamz) (👨‍💻 48 · 🔀 140 · 📦 420 · 📋 260 - 40% open · ⏱️ 22.12.2022):

	```
	git clone https://github.com/python-streamz/streamz
	```
- [PyPi](https://pypi.org/project/streamz) (📥 16K / month):
	```
	pip install streamz
	```
- [Conda](https://anaconda.org/conda-forge/streamz) (📥 730K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge streamz
	```
</details>
<details><summary><b><a href="https://github.com/fraunhoferportugal/tsfel">TSFEL</a></b> (🥉24 ·  ⭐ 730) - An intuitive library to extract features from time series. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/fraunhoferportugal/tsfel) (👨‍💻 18 · 🔀 110 · 📦 96 · 📋 62 - 1% open · ⏱️ 22.08.2023):

	```
	git clone https://github.com/fraunhoferportugal/tsfel
	```
- [PyPi](https://pypi.org/project/tsfel) (📥 23K / month):
	```
	pip install tsfel
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/greykite">greykite</a></b> (🥉21 ·  ⭐ 1.7K) - A flexible, intuitive and fast forecasting library. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/linkedin/greykite) (👨‍💻 9 · 🔀 98 · 📥 4 · 📦 23 · 📋 100 - 22% open · ⏱️ 07.06.2023):

	```
	git clone https://github.com/linkedin/greykite
	```
- [PyPi](https://pypi.org/project/greykite) (📥 13K / month):
	```
	pip install greykite
	```
</details>
<details><summary><b><a href="https://github.com/X-DataInitiative/tick">tick</a></b> (🥉21 ·  ⭐ 440 · 💤) - Module for statistical learning, with a particular emphasis on time-.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/X-DataInitiative/tick) (👨‍💻 19 · 🔀 96 · 📥 290 · 📦 71 · 📋 240 - 28% open · ⏱️ 05.03.2023):

	```
	git clone https://github.com/X-DataInitiative/tick
	```
- [PyPi](https://pypi.org/project/tick) (📥 1.1K / month):
	```
	pip install tick
	```
</details>
<details><summary><b><a href="https://github.com/linkedin/luminol">luminol</a></b> (🥉20 ·  ⭐ 1.1K) - Anomaly Detection and Correlation library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/linkedin/luminol) (👨‍💻 9 · 🔀 220 · 📦 76 · 📋 38 - 68% open · ⏱️ 09.05.2023):

	```
	git clone https://github.com/linkedin/luminol
	```
- [PyPi](https://pypi.org/project/luminol) (📥 11K / month):
	```
	pip install luminol
	```
</details>
<details><summary><b><a href="https://github.com/wwrechard/pydlm">pydlm</a></b> (🥉19 ·  ⭐ 460) - A python library for Bayesian time series modeling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/wwrechard/pydlm) (👨‍💻 6 · 🔀 95 · 📦 32 · 📋 47 - 78% open · ⏱️ 04.09.2023):

	```
	git clone https://github.com/wwrechard/pydlm
	```
- [PyPi](https://pypi.org/project/pydlm) (📥 32K / month):
	```
	pip install pydlm
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_TS">Auto TS</a></b> (🥉17 ·  ⭐ 620) - Automatically build ARIMA, SARIMAX, VAR, FB Prophet and XGBoost.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_TS) (👨‍💻 9 · 🔀 100 · 📋 83 - 1% open · ⏱️ 17.05.2023):

	```
	git clone https://github.com/AutoViML/Auto_TS
	```
- [PyPi](https://pypi.org/project/auto-ts) (📥 3.8K / month):
	```
	pip install auto-ts
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/Nixtla/neuralforecast">NeuralForecast</a></b> (🥉27 ·  ⭐ 1.8K · 📈) - Scalable and user friendly neural forecasting.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/RJT1990/pyflux">PyFlux</a></b> (🥉23 ·  ⭐ 2.1K · 💀) - Open source time series library for Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/arundo/adtk">ADTK</a></b> (🥉20 ·  ⭐ 970 · 💀) - A Python toolkit for rule-based/unsupervised anomaly detection in time.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code>
- <b><a href="https://github.com/dmbee/seglearn">seglearn</a></b> (🥉18 ·  ⭐ 560 · 💀) - Python module for machine learning time series:. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/target/matrixprofile-ts">matrixprofile-ts</a></b> (🥉17 ·  ⭐ 720 · 💀) - A Python library for detecting patterns and anomalies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/arundo/tsaug">tsaug</a></b> (🥉13 ·  ⭐ 320 · 💀) - A Python package for time series augmentation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/firmai/atspy">atspy</a></b> (🥉11 ·  ⭐ 500 · 💀) - AtsPy: Automated Time Series Models in Python (by @firmai). <code>❗Unlicensed</code>
</details>
<br>

## Medical Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing and analyzing medical data such as MRIs, EEGs, genomic data, and other medical imaging formats._

<details><summary><b><a href="https://github.com/mne-tools/mne-python">MNE</a></b> (🥇39 ·  ⭐ 2.4K) - MNE: Magnetoencephalography (MEG) and Electroencephalography (EEG) in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/mne-tools/mne-python) (👨‍💻 360 · 🔀 1.2K · 📦 3K · 📋 4.6K - 8% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/mne-tools/mne-python
	```
- [PyPi](https://pypi.org/project/mne) (📥 110K / month):
	```
	pip install mne
	```
- [Conda](https://anaconda.org/conda-forge/mne) (📥 330K · ⏱️ 06.09.2023):
	```
	conda install -c conda-forge mne
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAI">MONAI</a></b> (🥇36 ·  ⭐ 4.7K) - AI Toolkit for Healthcare Imaging. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAI) (👨‍💻 170 · 🔀 860 · 📦 1.4K · 📋 2.7K - 10% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/Project-MONAI/MONAI
	```
- [PyPi](https://pypi.org/project/monai) (📥 87K / month):
	```
	pip install monai
	```
- [Conda](https://anaconda.org/conda-forge/monai) (📥 18K · ⏱️ 08.06.2023):
	```
	conda install -c conda-forge monai
	```
</details>
<details><summary><b><a href="https://github.com/CamDavidsonPilon/lifelines">Lifelines</a></b> (🥈33 ·  ⭐ 2.2K) - Survival analysis in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/CamDavidsonPilon/lifelines) (👨‍💻 110 · 🔀 520 · 📦 1.9K · 📋 920 - 26% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/CamDavidsonPilon/lifelines
	```
- [PyPi](https://pypi.org/project/lifelines) (📥 400K / month):
	```
	pip install lifelines
	```
- [Conda](https://anaconda.org/conda-forge/lifelines) (📥 290K · ⏱️ 13.09.2023):
	```
	conda install -c conda-forge lifelines
	```
</details>
<details><summary><b><a href="https://github.com/hail-is/hail">Hail</a></b> (🥈33 ·  ⭐ 890) - Cloud-native genomic dataframes and batch computing. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hail-is/hail) (👨‍💻 90 · 🔀 220 · 📦 110 · 📋 2.2K - 5% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/hail-is/hail
	```
- [PyPi](https://pypi.org/project/hail) (📥 19K / month):
	```
	pip install hail
	```
</details>
<details><summary><b><a href="https://github.com/nipy/nipype">NIPYPE</a></b> (🥈33 ·  ⭐ 700) - Workflows and interfaces for neuroimaging packages. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nipy/nipype) (👨‍💻 250 · 🔀 480 · 📦 3.6K · 📋 1.3K - 29% open · ⏱️ 28.09.2023):

	```
	git clone https://github.com/nipy/nipype
	```
- [PyPi](https://pypi.org/project/nipype) (📥 76K / month):
	```
	pip install nipype
	```
- [Conda](https://anaconda.org/conda-forge/nipype) (📥 580K · ⏱️ 22.09.2023):
	```
	conda install -c conda-forge nipype
	```
</details>
<details><summary><b><a href="https://github.com/google/deepvariant">DeepVariant</a></b> (🥉24 ·  ⭐ 2.9K · 💤) - DeepVariant is an analysis pipeline that uses a deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/deepvariant) (👨‍💻 26 · 🔀 680 · 📥 4.7K · 📋 660 - 0% open · ⏱️ 28.02.2023):

	```
	git clone https://github.com/google/deepvariant
	```
- [Conda](https://anaconda.org/bioconda/deepvariant) (📥 58K · ⏱️ 16.06.2023):
	```
	conda install -c bioconda deepvariant
	```
</details>
<details><summary><b><a href="https://github.com/brainiak/brainiak">Brainiak</a></b> (🥉15 ·  ⭐ 310) - Brain Imaging Analysis Kit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/brainiak/brainiak) (👨‍💻 34 · 🔀 130 · 📋 200 - 38% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/brainiak/brainiak
	```
- [PyPi](https://pypi.org/project/brainiak) (📥 110 / month):
	```
	pip install brainiak
	```
- [Docker Hub](https://hub.docker.com/r/brainiak/brainiak) (📥 1.3K · ⭐ 1 · ⏱️ 15.10.2020):
	```
	docker pull brainiak/brainiak
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/nilearn/nilearn">Nilearn</a></b> (🥈33 ·  ⭐ 1K) - Machine learning for NeuroImaging in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/dipy/dipy">DIPY</a></b> (🥈31 ·  ⭐ 620) - DIPY is the paragon 3D/4D+ imaging library in Python. Contains.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nipy/nibabel">NiBabel</a></b> (🥈31 ·  ⭐ 590) - Python package to access a cacophony of neuro-imaging file formats. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nipy/nipy">NIPY</a></b> (🥉25 ·  ⭐ 350) - Neuroimaging in Python FMRI analysis package. <code>❗Unlicensed</code>
- <b><a href="https://github.com/NifTK/NiftyNet">NiftyNet</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - [unmaintained] An open-source convolutional neural.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/loli/medpy">MedPy</a></b> (🥉22 ·  ⭐ 510 · 💤) - Medical image processing in Python. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/projectglow/glow">Glow</a></b> (🥉19 ·  ⭐ 240 · 💤) - An open-source toolkit for large-scale genomic analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/DLTK/DLTK">DLTK</a></b> (🥉18 ·  ⭐ 1.4K · 💀) - Deep Learning Toolkit for Medical Image Analysis. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MIC-DKFZ/medicaldetectiontoolkit">Medical Detection Toolkit</a></b> (🥉15 ·  ⭐ 1.2K · 💀) - The Medical Detection Toolkit contains 2D + 3D.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/perone/medicaltorch">MedicalTorch</a></b> (🥉14 ·  ⭐ 820 · 💀) - A medical imaging framework for Pytorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Tencent/MedicalNet">MedicalNet</a></b> (🥉13 ·  ⭐ 1.7K · 💀) - Many studies have shown that the performance on deep learning is.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/QTIM-Lab/DeepNeuro">DeepNeuro</a></b> (🥉11 ·  ⭐ 120 · 💀) - A deep learning python package for neuroimaging data. Made by:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Tabular Data

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for processing tabular and structured data._

<details><summary><b><a href="https://github.com/carefree0910/carefree-learn">carefree-learn</a></b> (🥇20 ·  ⭐ 400) - Deep Learning PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/carefree0910/carefree-learn) (🔀 31 · 📦 4 · 📋 82 - 2% open · ⏱️ 14.09.2023):

	```
	git clone https://github.com/carefree0910/carefree-learn
	```
- [PyPi](https://pypi.org/project/carefree-learn) (📥 330 / month):
	```
	pip install carefree-learn
	```
</details>
<details><summary><b><a href="https://github.com/manujosephv/pytorch_tabular">pytorch_tabular</a></b> (🥉19 ·  ⭐ 1K) - A standard framework for modelling Deep Learning Models for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/manujosephv/pytorch_tabular) (👨‍💻 16 · 🔀 110 · 📥 21 · 📋 110 - 5% open · ⏱️ 19.07.2023):

	```
	git clone https://github.com/manujosephv/pytorch_tabular
	```
- [PyPi](https://pypi.org/project/pytorch_tabular) (📥 3.3K / month):
	```
	pip install pytorch_tabular
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/AnotherSamWilson/miceforest">miceforest</a></b> (🥇20 ·  ⭐ 260 · 💤) - Multiple Imputation with LightGBM in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/upgini/upgini">upgini</a></b> (🥉19 ·  ⭐ 250) - Data search & enrichment library for Machine Learning Easily find and add.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/firmai/deltapy">deltapy</a></b> (🥉10 ·  ⭐ 520 · 💀) - DeltaPy - Tabular Data Augmentation (by @firmai). <code>❗Unlicensed</code>
</details>
<br>

## Optical Character Recognition

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for optical character recognition (OCR) and text extraction from images or videos._

<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleOCR">PaddleOCR</a></b> (🥇39 ·  ⭐ 34K) - Awesome multilingual OCR toolkits based on PaddlePaddle.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleOCR) (👨‍💻 150 · 🔀 6.6K · 📦 1.9K · 📋 8.1K - 10% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/PaddlePaddle/PaddleOCR
	```
- [PyPi](https://pypi.org/project/paddleocr) (📥 76K / month):
	```
	pip install paddleocr
	```
</details>
<details><summary><b><a href="https://github.com/JaidedAI/EasyOCR">EasyOCR</a></b> (🥇36 ·  ⭐ 20K) - Ready-to-use OCR with 80+ supported languages and all popular writing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/JaidedAI/EasyOCR) (👨‍💻 130 · 🔀 2.7K · 📥 6.7M · 📦 3.9K · 📋 870 - 33% open · ⏱️ 04.09.2023):

	```
	git clone https://github.com/JaidedAI/EasyOCR
	```
- [PyPi](https://pypi.org/project/easyocr) (📥 180K / month):
	```
	pip install easyocr
	```
</details>
<details><summary><b><a href="https://github.com/ocrmypdf/OCRmyPDF">OCRmyPDF</a></b> (🥈33 ·  ⭐ 10K) - OCRmyPDF adds an OCR text layer to scanned PDF files, allowing them.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/ocrmypdf/OCRmyPDF) (👨‍💻 86 · 🔀 760 · 📥 590 · 📦 620 · 📋 1K - 9% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/ocrmypdf/OCRmyPDF
	```
- [PyPi](https://pypi.org/project/ocrmypdf) (📥 47K / month):
	```
	pip install ocrmypdf
	```
- [Conda](https://anaconda.org/conda-forge/ocrmypdf) (📥 57K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ocrmypdf
	```
</details>
<details><summary><b><a href="https://github.com/sirfz/tesserocr">tesserocr</a></b> (🥈31 ·  ⭐ 1.9K) - A Python wrapper for the tesseract-ocr API. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sirfz/tesserocr) (👨‍💻 29 · 🔀 250 · 📥 52 · 📦 890 · 📋 260 - 17% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/sirfz/tesserocr
	```
- [PyPi](https://pypi.org/project/tesserocr) (📥 62K / month):
	```
	pip install tesserocr
	```
- [Conda](https://anaconda.org/conda-forge/tesserocr) (📥 130K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tesserocr
	```
</details>
<details><summary><b><a href="https://github.com/madmaze/pytesseract">Tesseract</a></b> (🥈29 ·  ⭐ 5.1K) - Python-tesseract is an optical character recognition (OCR) tool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/madmaze/pytesseract) (👨‍💻 43 · 🔀 660 · 📋 340 - 2% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/madmaze/pytesseract
	```
- [PyPi](https://pypi.org/project/pytesseract) (📥 1.1M / month):
	```
	pip install pytesseract
	```
- [Conda](https://anaconda.org/conda-forge/pytesseract) (📥 590K · ⏱️ 12.09.2023):
	```
	conda install -c conda-forge pytesseract
	```
</details>
<details><summary><b><a href="https://github.com/open-mmlab/mmocr">MMOCR</a></b> (🥉27 ·  ⭐ 3.7K) - OpenMMLab Text Detection, Recognition and Understanding Toolbox. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/open-mmlab/mmocr) (👨‍💻 85 · 🔀 680 · 📦 88 · 📋 850 - 13% open · ⏱️ 01.09.2023):

	```
	git clone https://github.com/open-mmlab/mmocr
	```
- [PyPi](https://pypi.org/project/mmocr) (📥 4.9K / month):
	```
	pip install mmocr
	```
</details>
<details><summary><b><a href="https://github.com/faustomorales/keras-ocr">keras-ocr</a></b> (🥉24 ·  ⭐ 1.3K · 💤) - A packaged and flexible version of the CRAFT text detector.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/faustomorales/keras-ocr) (👨‍💻 17 · 🔀 300 · 📥 660K · 📦 330 · 📋 200 - 44% open · ⏱️ 24.12.2022):

	```
	git clone https://github.com/faustomorales/keras-ocr
	```
- [PyPi](https://pypi.org/project/keras-ocr) (📥 11K / month):
	```
	pip install keras-ocr
	```
- [Conda](https://anaconda.org/anaconda/keras-ocr) (📥 280 · ⏱️ 16.06.2023):
	```
	conda install -c anaconda keras-ocr
	```
</details>
<details><summary><b><a href="https://github.com/Calamari-OCR/calamari">calamari</a></b> (🥉21 ·  ⭐ 1K) - Line based ATR Engine based on OCRopy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Calamari-OCR/calamari) (👨‍💻 20 · 🔀 200 · 📋 260 - 22% open · ⏱️ 18.08.2023):

	```
	git clone https://github.com/Calamari-OCR/calamari
	```
- [PyPi](https://pypi.org/project/calamari_ocr) (📥 1.4K / month):
	```
	pip install calamari_ocr
	```
</details>
<details><summary>Show 4 hidden projects...</summary>

- <b><a href="https://github.com/emedvedev/attention-ocr">attention-ocr</a></b> (🥉21 ·  ⭐ 960 · 💀) - A Tensorflow model for text recognition (CNN + seq2seq.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/WZBSocialScienceCenter/pdftabextract">pdftabextract</a></b> (🥉19 ·  ⭐ 2.1K · 💀) - A set of tools for extracting tables from PDF files.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jlsutherland/doc2text">doc2text</a></b> (🥉18 ·  ⭐ 1.3K · 💀) - Detect text blocks and OCR poorly scanned PDFs in bulk. Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aashrafh/Mozart">Mozart</a></b> (🥉10 ·  ⭐ 510 · 💀) - An optical music recognition (OMR) system. Converts sheet.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Data Containers & Structures

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_General-purpose data containers & structures as well as utilities & extensions for pandas._

<br>

## Data Loading & Extraction

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for loading, collecting, and extracting data from a variety of data sources and formats._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-loading--extraction">best-of-python - Data Extraction</a></b> ( ⭐ 3.2K)  - Collection of data-loading and -extraction libraries.

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#data-containers--dataframes">best-of-python - Data Containers</a></b> ( ⭐ 3.2K)  - Collection of data-container, dataframe, and pandas-..

<br>

## Web Scraping & Crawling

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for web scraping, crawling, downloading, and mining as well as libraries._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-web-python#web-scraping--crawling">best-of-web-python - Web Scraping</a></b> ( ⭐ 2K)  - Collection of web-scraping and crawling libraries.

<br>

## Data Pipelines & Streaming

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for data batch- and stream-processing, workflow automation, job scheduling, and other data pipeline tasks._

<details><summary><b><a href="https://github.com/apache/airflow">Airflow</a></b> (🥇47 ·  ⭐ 33K) - Platform to programmatically author, schedule, and monitor workflows. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/airflow) (👨‍💻 3K · 🔀 12K · 📥 550K · 📦 8.2K · 📋 8.1K - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/apache/airflow
	```
- [PyPi](https://pypi.org/project/apache-airflow) (📥 10M / month):
	```
	pip install apache-airflow
	```
- [Conda](https://anaconda.org/conda-forge/airflow) (📥 950K · ⏱️ 11.09.2023):
	```
	conda install -c conda-forge airflow
	```
- [Docker Hub](https://hub.docker.com/r/apache/airflow) (📥 170M · ⭐ 480 · ⏱️ 12.10.2023):
	```
	docker pull apache/airflow
	```
</details>
<details><summary><b><a href="https://github.com/PrefectHQ/prefect">Prefect</a></b> (🥇43 ·  ⭐ 13K) - Prefect is a workflow orchestration tool empowering developers to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PrefectHQ/prefect) (👨‍💻 200 · 🔀 1.3K · 📦 3.8K · 📋 4.2K - 12% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/PrefectHQ/prefect
	```
- [PyPi](https://pypi.org/project/prefect) (📥 640K / month):
	```
	pip install prefect
	```
- [Conda](https://anaconda.org/conda-forge/prefect) (📥 540K · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge prefect
	```
</details>
<details><summary><b><a href="https://github.com/dagster-io/dagster">Dagster</a></b> (🥇41 ·  ⭐ 8.6K) - An orchestration platform for the development, production, and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dagster-io/dagster) (👨‍💻 350 · 🔀 1K · 📦 1.6K · 📋 6K - 27% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dagster-io/dagster
	```
- [PyPi](https://pypi.org/project/dagster) (📥 670K / month):
	```
	pip install dagster
	```
- [Conda](https://anaconda.org/conda-forge/dagster) (📥 1M · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge dagster
	```
</details>
<details><summary><b><a href="https://github.com/apache/beam">Beam</a></b> (🥇39 ·  ⭐ 7.2K) - Unified programming model to define and execute data processing.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/beam) (👨‍💻 1.6K · 🔀 3.9K · 📦 2 · 📋 6.1K - 68% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/apache/beam
	```
- [PyPi](https://pypi.org/project/apache-beam) (📥 7M / month):
	```
	pip install apache-beam
	```
- [Conda](https://anaconda.org/conda-forge/apache-beam-with-aws) (📥 54K · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge apache-beam-with-aws
	```
</details>
<details><summary><b><a href="https://github.com/joblib/joblib">joblib</a></b> (🥇39 ·  ⭐ 3.5K) - Computing with Python functions. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/joblib/joblib) (👨‍💻 120 · 🔀 370 · 📦 340K · 📋 810 - 42% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/joblib/joblib
	```
- [PyPi](https://pypi.org/project/joblib) (📥 38M / month):
	```
	pip install joblib
	```
- [Conda](https://anaconda.org/conda-forge/joblib) (📥 22M · ⏱️ 09.08.2023):
	```
	conda install -c conda-forge joblib
	```
</details>
<details><summary><b><a href="https://github.com/spotify/luigi">luigi</a></b> (🥈37 ·  ⭐ 17K) - Luigi is a Python module that helps you build complex pipelines of batch.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/luigi) (👨‍💻 600 · 🔀 2.3K · 📦 2.2K · 📋 970 - 9% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/spotify/luigi
	```
- [PyPi](https://pypi.org/project/luigi) (📥 540K / month):
	```
	pip install luigi
	```
- [Conda](https://anaconda.org/anaconda/luigi) (📥 14K · ⏱️ 16.06.2023):
	```
	conda install -c anaconda luigi
	```
</details>
<details><summary><b><a href="https://github.com/kedro-org/kedro">Kedro</a></b> (🥈37 ·  ⭐ 8.9K) - Kedro is a toolbox for production-ready data science. It uses software.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kedro-org/kedro) (👨‍💻 210 · 🔀 820 · 📦 1.9K · 📋 1.5K - 22% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/kedro-org/kedro
	```
- [PyPi](https://pypi.org/project/kedro) (📥 400K / month):
	```
	pip install kedro
	```
</details>
<details><summary><b><a href="https://github.com/great-expectations/great_expectations">Great Expectations</a></b> (🥈37 ·  ⭐ 8.9K) - Always know what to expect from your data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/great-expectations/great_expectations) (👨‍💻 410 · 🔀 1.4K · 📋 1.7K - 6% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/great-expectations/great_expectations
	```
- [PyPi](https://pypi.org/project/great_expectations) (📥 13M / month):
	```
	pip install great_expectations
	```
- [Conda](https://anaconda.org/conda-forge/great-expectations) (📥 720K · ⏱️ 07.10.2023):
	```
	conda install -c conda-forge great-expectations
	```
</details>
<details><summary><b><a href="https://github.com/dbt-labs/dbt-core">dbt</a></b> (🥈37 ·  ⭐ 7.6K) - dbt enables data analysts and engineers to transform their data using the.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/dbt-labs/dbt-core) (👨‍💻 300 · 🔀 1.3K · 📥 2.5K · 📦 3.4K · 📋 4.5K - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dbt-labs/dbt-core
	```
- [PyPi](https://pypi.org/project/dbt) (📥 120K / month):
	```
	pip install dbt
	```
- [Conda](https://anaconda.org/conda-forge/dbt) (📥 250K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dbt
	```
</details>
<details><summary><b><a href="https://github.com/activeloopai/deeplake">Activeloop</a></b> (🥈34 ·  ⭐ 7K) - Database for AI. Store Vectors, Images, Texts, Videos, etc. Use.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/activeloopai/deeplake) (👨‍💻 120 · 🔀 520 · 📦 2.4K · 📋 440 - 11% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/activeloopai/Hub
	```
- [PyPi](https://pypi.org/project/hub) (📥 3.2K / month):
	```
	pip install hub
	```
</details>
<details><summary><b><a href="https://github.com/petl-developers/petl">petl</a></b> (🥈33 ·  ⭐ 1.2K) - Python Extract Transform and Load Tables of Data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/petl-developers/petl) (👨‍💻 63 · 🔀 190 · 📦 3.5K · 📋 450 - 18% open · ⏱️ 22.08.2023):

	```
	git clone https://github.com/petl-developers/petl
	```
- [PyPi](https://pypi.org/project/petl) (📥 1.2M / month):
	```
	pip install petl
	```
- [Conda](https://anaconda.org/conda-forge/petl) (📥 210K · ⏱️ 22.08.2023):
	```
	conda install -c conda-forge petl
	```
</details>
<details><summary><b><a href="https://github.com/zenml-io/zenml">zenml</a></b> (🥈32 ·  ⭐ 3.1K) - ZenML : Build portable, production-ready MLOps pipelines... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/zenml-io/zenml) (👨‍💻 76 · 🔀 320 · 📥 1 · 📦 190 · 📋 210 - 5% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/zenml-io/zenml
	```
- [PyPi](https://pypi.org/project/zenml) (📥 9K / month):
	```
	pip install zenml
	```
</details>
<details><summary><b><a href="https://github.com/coleifer/huey">huey</a></b> (🥈31 ·  ⭐ 4.6K) - a little task queue for python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/coleifer/huey) (👨‍💻 67 · 🔀 360 · 📦 1.3K · ⏱️ 20.09.2023):

	```
	git clone https://github.com/coleifer/huey
	```
- [PyPi](https://pypi.org/project/huey) (📥 90K / month):
	```
	pip install huey
	```
- [Conda](https://anaconda.org/conda-forge/huey) (📥 33K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge huey
	```
</details>
<details><summary><b><a href="https://github.com/whylabs/whylogs">whylogs</a></b> (🥈30 ·  ⭐ 2.4K) - Open standard for end-to-end data and ML monitoring for any scale in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/whylabs/whylogs) (👨‍💻 23 · 🔀 100 · 📥 43 · 📦 190 · 📋 390 - 3% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/whylabs/whylogs
	```
- [PyPi](https://pypi.org/project/whylogs) (📥 110K / month):
	```
	pip install whylogs
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tfx">TFX</a></b> (🥈30 ·  ⭐ 2K) - TFX is an end-to-end platform for deploying production ML pipelines. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tfx) (👨‍💻 180 · 🔀 660 · 📋 870 - 4% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/tensorflow/tfx
	```
- [PyPi](https://pypi.org/project/tfx) (📥 46K / month):
	```
	pip install tfx
	```
</details>
<details><summary><b><a href="https://github.com/combust/mleap">mleap</a></b> (🥈30 ·  ⭐ 1.5K) - MLeap: Deploy ML Pipelines to Production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/combust/mleap) (👨‍💻 85 · 🔀 300 · 📦 220 · 📋 470 - 21% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/combust/mleap
	```
- [PyPi](https://pypi.org/project/mleap) (📥 270K / month):
	```
	pip install mleap
	```
- [Conda](https://anaconda.org/conda-forge/mleap) (📥 76K · ⏱️ 26.06.2023):
	```
	conda install -c conda-forge mleap
	```
</details>
<details><summary><b><a href="https://github.com/EntilZha/PyFunctional">PyFunctional</a></b> (🥉28 ·  ⭐ 2.2K) - Python library for creating data pipelines with chain functional.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/EntilZha/PyFunctional) (👨‍💻 31 · 🔀 130 · 📦 690 · 📋 130 - 7% open · ⏱️ 27.09.2023):

	```
	git clone https://github.com/EntilZha/PyFunctional
	```
- [PyPi](https://pypi.org/project/pyfunctional) (📥 330K / month):
	```
	pip install pyfunctional
	```
</details>
<details><summary><b><a href="https://github.com/ploomber/ploomber">ploomber</a></b> (🥉27 ·  ⭐ 3.2K) - The fastest way to build data pipelines. Develop iteratively,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ploomber/ploomber) (👨‍💻 76 · 🔀 220 · 📦 110 · 📋 850 - 11% open · ⏱️ 30.08.2023):

	```
	git clone https://github.com/ploomber/ploomber
	```
- [PyPi](https://pypi.org/project/ploomber) (📥 4.2K / month):
	```
	pip install ploomber
	```
- [Conda](https://anaconda.org/conda-forge/ploomber) (📥 76K · ⏱️ 30.08.2023):
	```
	conda install -c conda-forge ploomber
	```
</details>
<details><summary><b><a href="https://github.com/samuelcolvin/arq">arq</a></b> (🥉26 ·  ⭐ 1.7K) - Fast job queuing and RPC in python with asyncio and redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/samuelcolvin/arq) (👨‍💻 54 · 🔀 140 · 📦 450 · 📋 190 - 26% open · ⏱️ 20.05.2023):

	```
	git clone https://github.com/samuelcolvin/arq
	```
- [PyPi](https://pypi.org/project/arq) (📥 71K / month):
	```
	pip install arq
	```
- [Conda](https://anaconda.org/conda-forge/arq) (📥 8.8K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge arq
	```
</details>
<details><summary><b><a href="https://github.com/hi-primus/optimus">Optimus</a></b> (🥉25 ·  ⭐ 1.4K) - Agile Data Preparation Workflows madeeasy with Pandas, Dask,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hi-primus/optimus) (👨‍💻 24 · 🔀 230 · 📋 220 - 3% open · ⏱️ 19.05.2023):

	```
	git clone https://github.com/hi-primus/optimus
	```
- [PyPi](https://pypi.org/project/optimuspyspark) (📥 8.9K / month):
	```
	pip install optimuspyspark
	```
</details>
<details><summary><b><a href="https://github.com/cgarciae/pypeln">Pypeline</a></b> (🥉23 ·  ⭐ 1.5K · 💤) - Concurrent data pipelines in Python . <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/cgarciae/pypeln) (👨‍💻 13 · 🔀 90 · 📦 110 · 📋 68 - 30% open · ⏱️ 22.03.2023):

	```
	git clone https://github.com/cgarciae/pypeln
	```
- [PyPi](https://pypi.org/project/pypeln) (📥 26K / month):
	```
	pip install pypeln
	```
- [Conda](https://anaconda.org/conda-forge/pypeln) (📥 14K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pypeln
	```
</details>
<details><summary><b><a href="https://github.com/closeio/tasktiger">TaskTiger</a></b> (🥉23 ·  ⭐ 1.3K) - Python task queue using Redis. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/closeio/tasktiger) (👨‍💻 29 · 🔀 75 · 📦 26 · 📋 68 - 41% open · ⏱️ 05.09.2023):

	```
	git clone https://github.com/closeio/tasktiger
	```
- [PyPi](https://pypi.org/project/tasktiger) (📥 2.8K / month):
	```
	pip install tasktiger
	```
</details>
<details><summary><b><a href="https://github.com/pdpipe/pdpipe">pdpipe</a></b> (🥉20 ·  ⭐ 710 · 💤) - Easy pipelines for pandas DataFrames. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pdpipe/pdpipe) (👨‍💻 11 · 🔀 44 · 📦 56 · 📋 53 - 28% open · ⏱️ 24.12.2022):

	```
	git clone https://github.com/pdpipe/pdpipe
	```
- [PyPi](https://pypi.org/project/pdpipe) (📥 960 / month):
	```
	pip install pdpipe
	```
- [Conda](https://anaconda.org/conda-forge/pdpipe) (📥 27K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pdpipe
	```
</details>
<details><summary><b><a href="https://github.com/mara/mara-pipelines">Mara Pipelines</a></b> (🥉17 ·  ⭐ 2K) - A lightweight opinionated ETL framework, halfway between plain.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mara/mara-pipelines) (👨‍💻 17 · 🔀 100 · 📋 34 - 52% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/mara/mara-pipelines
	```
- [PyPi](https://pypi.org/project/mara-pipelines) (📥 47 / month):
	```
	pip install mara-pipelines
	```
</details>
<details><summary><b><a href="https://github.com/d6t/d6tflow">Databolt Flow</a></b> (🥉15 ·  ⭐ 950) - Python library for building highly effective data science workflows. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/d6t/d6tflow) (👨‍💻 13 · 🔀 74 · 📦 26 · 📋 23 - 43% open · ⏱️ 20.07.2023):

	```
	git clone https://github.com/d6t/d6tflow
	```
- [PyPi](https://pypi.org/project/d6tflow) (📥 140 / month):
	```
	pip install d6tflow
	```
</details>
<details><summary>Show 18 hidden projects...</summary>

- <b><a href="https://github.com/celery/celery">Celery</a></b> (🥇44 ·  ⭐ 22K) - Asynchronous task queue/job queue based on distributed message.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/rq/rq">rq</a></b> (🥈36 ·  ⭐ 9.2K) - Simple job queues for Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Yelp/mrjob">mrjob</a></b> (🥈30 ·  ⭐ 2.6K · 💀) - Run MapReduce jobs on Hadoop or Amazon Web Services. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/robinhood/faust">faust</a></b> (🥉26 ·  ⭐ 6.6K · 💤) - Python Stream Processing. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Parsely/streamparse">streamparse</a></b> (🥉26 ·  ⭐ 1.5K · 💀) - Run Python in Apache Storm topologies. Pythonic API, CLI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/python-bonobo/bonobo">bonobo</a></b> (🥉22 ·  ⭐ 1.6K · 💀) - Extract Transform Load for Python 3.5+. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/analysiscenter/batchflow">BatchFlow</a></b> (🥉22 ·  ⭐ 190) - BatchFlow helps you conveniently work with random or sequential.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/douban/dpark">dpark</a></b> (🥉21 ·  ⭐ 2.7K · 💀) - Python clone of Spark, a MapReduce alike framework in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/databand-ai/dbnd">dbnd</a></b> (🥉21 ·  ⭐ 240) - DBND is an agile pipeline framework that helps data engineering teams.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/svenkreiss/pysparkling">pysparkling</a></b> (🥉20 ·  ⭐ 260 · 💤) - A pure Python implementation of Apache Sparks RDD and.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/databricks/spark-deep-learning">spark-deep-learning</a></b> (🥉19 ·  ⭐ 2K · 💀) - Deep Learning Pipelines for Apache Spark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pricingassistant/mrq">mrq</a></b> (🥉19 ·  ⭐ 880 · 💀) - Mr. Queue - A distributed worker task queue in Python using Redis & gevent. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nerevu/riko">riko</a></b> (🥉15 ·  ⭐ 1.6K · 💀) - A Python stream processing engine modeled after Yahoo! Pipes. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/kubeflow-kale/kale">kale</a></b> (🥉15 ·  ⭐ 610 · 💀) - Kubeflows superfood for Data Scientists. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bodywork-ml/bodywork-core">bodywork-core</a></b> (🥉14 ·  ⭐ 430 · 💀) - ML pipeline orchestration and model deployments on.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/olirice/flupy">flupy</a></b> (🥉13 ·  ⭐ 180) - Fluent data pipelines for python and your shell. <code>❗Unlicensed</code>
- <b><a href="https://github.com/vincentclaes/datajob">datajob</a></b> (🥉13 ·  ⭐ 100 · 💤) - Build and deploy a serverless data pipeline on AWS with no effort. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/kkyon/botflow">Botflow</a></b> (🥉10 ·  ⭐ 1.2K · 💀) - Python Fast Dataflow programming framework for Data pipeline.. <code>❗Unlicensed</code>
</details>
<br>

## Distributed Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that provide capabilities to distribute and parallelize machine learning tasks across large-scale compute infrastructure._

<details><summary><b><a href="https://github.com/ray-project/ray">Ray</a></b> (🥇44 ·  ⭐ 28K) - Ray is a unified framework for scaling AI and Python applications. Ray.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ray-project/ray) (👨‍💻 930 · 🔀 4.7K · 📥 89 · 📦 12K · 📋 16K - 19% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/ray-project/ray
	```
- [PyPi](https://pypi.org/project/ray) (📥 2.3M / month):
	```
	pip install ray
	```
- [Conda](https://anaconda.org/conda-forge/ray-tune) (📥 170K · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge ray-tune
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/DeepSpeed">DeepSpeed</a></b> (🥇41 ·  ⭐ 29K · 📈) - DeepSpeed is a deep learning optimization library that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/DeepSpeed) (👨‍💻 250 · 🔀 3.3K · 📦 4.4K · 📋 2.1K - 33% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/microsoft/DeepSpeed
	```
- [PyPi](https://pypi.org/project/deepspeed) (📥 350K / month):
	```
	pip install deepspeed
	```
- [Docker Hub](https://hub.docker.com/r/deepspeed/deepspeed) (📥 17K · ⭐ 4 · ⏱️ 02.09.2022):
	```
	docker pull deepspeed/deepspeed
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask">dask</a></b> (🥇41 ·  ⭐ 11K) - Parallel computing with task scheduling. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask) (👨‍💻 590 · 🔀 1.6K · 📦 53K · 📋 4.8K - 16% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dask/dask
	```
- [PyPi](https://pypi.org/project/dask) (📥 8.2M / month):
	```
	pip install dask
	```
- [Conda](https://anaconda.org/conda-forge/dask) (📥 10M · ⏱️ 30.09.2023):
	```
	conda install -c conda-forge dask
	```
</details>
<details><summary><b><a href="https://github.com/dask/distributed">dask.distributed</a></b> (🥇38 ·  ⭐ 1.5K) - A distributed task scheduler for Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/distributed) (👨‍💻 320 · 🔀 680 · 📦 31K · 📋 3.4K - 33% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dask/distributed
	```
- [PyPi](https://pypi.org/project/distributed) (📥 4.3M / month):
	```
	pip install distributed
	```
- [Conda](https://anaconda.org/conda-forge/distributed) (📥 12M · ⏱️ 29.09.2023):
	```
	conda install -c conda-forge distributed
	```
</details>
<details><summary><b><a href="https://github.com/Lightning-AI/torchmetrics">metrics</a></b> (🥈35 ·  ⭐ 1.7K) - Torchmetrics - Machine learning metrics for distributed,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Lightning-AI/torchmetrics) (👨‍💻 210 · 🔀 330 · 📥 4K · 📦 16K · 📋 710 - 6% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/PyTorchLightning/metrics
	```
- [PyPi](https://pypi.org/project/metrics) (📥 7.2K / month):
	```
	pip install metrics
	```
- [Conda](https://anaconda.org/conda-forge/torchmetrics) (📥 1.1M · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge torchmetrics
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/BigDL">BigDL</a></b> (🥈34 ·  ⭐ 4.4K) - Accelerate LLM with low-bit (INT3 / INT4 / NF4 / INT5 / INT8).. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/intel-analytics/BigDL) (👨‍💻 180 · 🔀 1.1K · 📦 45 · 📋 1.9K - 32% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/intel-analytics/BigDL
	```
- [PyPi](https://pypi.org/project/bigdl) (📥 6.2K / month):
	```
	pip install bigdl
	```
- [Maven](https://search.maven.org/artifact/com.intel.analytics.bigdl/bigdl-SPARK_2.4):
	```
	<dependency>
		<groupId>com.intel.analytics.bigdl</groupId>
		<artifactId>bigdl-SPARK_2.4</artifactId>
		<version>[VERSION]</version>
	</dependency>
	```
</details>
<details><summary><b><a href="https://github.com/h2oai/h2o-3">H2O-3</a></b> (🥈33 ·  ⭐ 6.5K) - H2O is an Open Source, Distributed, Fast & Scalable Machine Learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/h2oai/h2o-3) (👨‍💻 250 · 🔀 1.9K · 📦 18 · 📋 9.1K - 28% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/h2oai/h2o-3
	```
- [PyPi](https://pypi.org/project/h2o) (📥 380K / month):
	```
	pip install h2o
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/fairscale">FairScale</a></b> (🥈31 ·  ⭐ 2.6K) - PyTorch extensions for high performance and large scale training. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/fairscale) (👨‍💻 72 · 🔀 240 · 📦 3.2K · 📋 350 - 19% open · ⏱️ 20.04.2023):

	```
	git clone https://github.com/facebookresearch/fairscale
	```
- [PyPi](https://pypi.org/project/fairscale) (📥 500K / month):
	```
	pip install fairscale
	```
- [Conda](https://anaconda.org/conda-forge/fairscale) (📥 160K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge fairscale
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">SynapseML</a></b> (🥈29 ·  ⭐ 4.6K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 110 · 🔀 760 · 📋 680 - 42% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/synapseml) (📥 300K / month):
	```
	pip install synapseml
	```
</details>
<details><summary><b><a href="https://github.com/dask/dask-ml">dask-ml</a></b> (🥈28 ·  ⭐ 870 · 💤) - Scalable Machine Learning with Dask. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/dask/dask-ml) (👨‍💻 77 · 🔀 240 · 📦 880 · 📋 480 - 46% open · ⏱️ 24.03.2023):

	```
	git clone https://github.com/dask/dask-ml
	```
- [PyPi](https://pypi.org/project/dask-ml) (📥 170K / month):
	```
	pip install dask-ml
	```
- [Conda](https://anaconda.org/conda-forge/dask-ml) (📥 770K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dask-ml
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/mesh">Mesh</a></b> (🥈27 ·  ⭐ 1.5K) - Mesh TensorFlow: Model Parallelism Made Easier. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/mesh) (👨‍💻 50 · 🔀 240 · 📦 860 · 📋 82 - 80% open · ⏱️ 16.05.2023):

	```
	git clone https://github.com/tensorflow/mesh
	```
- [PyPi](https://pypi.org/project/mesh-tensorflow) (📥 19K / month):
	```
	pip install mesh-tensorflow
	```
</details>
<details><summary><b><a href="https://github.com/facebookincubator/submitit">Submit it</a></b> (🥈27 ·  ⭐ 960) - Python 3.8+ toolbox for submitting jobs to Slurm. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookincubator/submitit) (👨‍💻 23 · 🔀 110 · 📦 1.6K · 📋 100 - 28% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/facebookincubator/submitit
	```
- [PyPi](https://pypi.org/project/submitit) (📥 160K / month):
	```
	pip install submitit
	```
- [Conda](https://anaconda.org/conda-forge/submitit) (📥 31K · ⏱️ 05.10.2023):
	```
	conda install -c conda-forge submitit
	```
</details>
<details><summary><b><a href="https://github.com/yahoo/TensorFlowOnSpark">TensorFlowOnSpark</a></b> (🥉26 ·  ⭐ 3.9K) - TensorFlowOnSpark brings TensorFlow programs to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/yahoo/TensorFlowOnSpark) (👨‍💻 34 · 🔀 920 · 📋 370 - 3% open · ⏱️ 27.04.2023):

	```
	git clone https://github.com/yahoo/TensorFlowOnSpark
	```
- [PyPi](https://pypi.org/project/tensorflowonspark) (📥 470K / month):
	```
	pip install tensorflowonspark
	```
- [Conda](https://anaconda.org/conda-forge/tensorflowonspark) (📥 20K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tensorflowonspark
	```
</details>
<details><summary><b><a href="https://github.com/learning-at-home/hivemind">Hivemind</a></b> (🥉26 ·  ⭐ 1.7K) - Decentralized deep learning in PyTorch. Built to train models on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/learning-at-home/hivemind) (👨‍💻 28 · 🔀 110 · 📦 72 · 📋 150 - 33% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/learning-at-home/hivemind
	```
- [PyPi](https://pypi.org/project/hivemind) (📥 4K / month):
	```
	pip install hivemind
	```
</details>
<details><summary><b><a href="https://github.com/uber/petastorm">petastorm</a></b> (🥉26 ·  ⭐ 1.7K · 💤) - Petastorm library enables single machine or distributed.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/uber/petastorm) (👨‍💻 49 · 🔀 270 · 📥 430 · 📦 140 · 📋 300 - 50% open · ⏱️ 03.02.2023):

	```
	git clone https://github.com/uber/petastorm
	```
- [PyPi](https://pypi.org/project/petastorm) (📥 33K / month):
	```
	pip install petastorm
	```
</details>
<details><summary><b><a href="https://github.com/mpi4py/mpi4py">mpi4py</a></b> (🥉25 ·  ⭐ 690) - Python bindings for MPI. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/mpi4py/mpi4py) (👨‍💻 26 · 🔀 100 · 📥 17K · 📋 130 - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/mpi4py/mpi4py
	```
- [PyPi](https://pypi.org/project/mpi4py) (📥 160K / month):
	```
	pip install mpi4py
	```
- [Conda](https://anaconda.org/conda-forge/mpi4py) (📥 2.2M · ⏱️ 23.09.2023):
	```
	conda install -c conda-forge mpi4py
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/SynapseML">MMLSpark</a></b> (🥉24 ·  ⭐ 4.6K) - Simple and Distributed Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/SynapseML) (👨‍💻 110 · 🔀 760 · 📋 680 - 42% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/microsoft/SynapseML
	```
- [PyPi](https://pypi.org/project/mmlspark):
	```
	pip install mmlspark
	```
</details>
<details><summary><b><a href="https://github.com/intel-analytics/analytics-zoo">analytics-zoo</a></b> (🥉23 ·  ⭐ 2.6K) - Distributed Tensorflow, Keras and PyTorch on Apache.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/intel-analytics/analytics-zoo) (👨‍💻 110 · 🔀 710 · 📦 4 · 📋 1.3K - 32% open · ⏱️ 06.09.2023):

	```
	git clone https://github.com/intel-analytics/analytics-zoo
	```
- [PyPi](https://pypi.org/project/analytics-zoo) (📥 900 / month):
	```
	pip install analytics-zoo
	```
</details>
<details><summary><b><a href="https://github.com/apache/singa">Apache Singa</a></b> (🥉21 ·  ⭐ 3K) - a distributed deep learning platform. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/apache/singa) (👨‍💻 81 · 🔀 1K · 📦 2 · 📋 96 - 25% open · ⏱️ 02.04.2023):

	```
	git clone https://github.com/apache/singa
	```
- [Conda](https://anaconda.org/nusdbsystem/singa) (📥 700 · ⏱️ 16.06.2023):
	```
	conda install -c nusdbsystem singa
	```
- [Docker Hub](https://hub.docker.com/r/apache/singa) (📥 4.1K · ⭐ 4 · ⏱️ 31.05.2022):
	```
	docker pull apache/singa
	```
</details>
<details><summary><b><a href="https://github.com/kingoflolz/mesh-transformer-jax">mesh-transformer-jax</a></b> (🥉18 ·  ⭐ 6.1K · 💤) - Model parallel transformers in JAX and Haiku. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/kingoflolz/mesh-transformer-jax) (👨‍💻 23 · 🔀 870 · 📦 18 · 📋 200 - 20% open · ⏱️ 12.01.2023):

	```
	git clone https://github.com/kingoflolz/mesh-transformer-jax
	```
</details>
<details><summary>Show 13 hidden projects...</summary>

- <b><a href="https://github.com/horovod/horovod">horovod</a></b> (🥈34 ·  ⭐ 14K) - Distributed training framework for TensorFlow, Keras, PyTorch,.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/DEAP/deap">DEAP</a></b> (🥈33 ·  ⭐ 5.3K) - Distributed Evolutionary Algorithms in Python. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code>
- <b><a href="https://github.com/maxpumperla/elephas">Elephas</a></b> (🥈27 ·  ⭐ 1.6K · 💀) - Distributed Deep learning with Keras & Spark. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code>keras</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ipython/ipyparallel">ipyparallel</a></b> (🥉24 ·  ⭐ 2.5K · 📉) - IPython Parallel: Interactive Parallel Computing in.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/databricks/tensorframes">TensorFrames</a></b> (🥉20 ·  ⭐ 750 · 💀) - [DEPRECATED] Tensorflow wrapper for DataFrames on.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/bytedance/byteps">BytePS</a></b> (🥉19 ·  ⭐ 3.5K · 💀) - A high performance and generic framework for distributed DNN.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/google-deepmind/launchpad">launchpad</a></b> (🥉19 ·  ⭐ 300) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Ibotta/sk-dist">sk-dist</a></b> (🥉18 ·  ⭐ 280 · 💤) - Distributed scikit-learn meta-estimators in PySpark. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/peterwittek/somoclu">somoclu</a></b> (🥉18 ·  ⭐ 250 · 💀) - Massively parallel self-organizing maps: accelerate training on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tunib-ai/parallelformers">parallelformers</a></b> (🥉17 ·  ⭐ 720 · 💀) - Parallelformers: An Efficient Model Parallelization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/uber/fiber">Fiber</a></b> (🥉15 ·  ⭐ 1K · 💀) - Distributed Computing for AI Made Simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/ml-tooling/lazycluster">LazyCluster</a></b> (🥉12 ·  ⭐ 49 · 💀) - Distributed machine learning made simple. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/petuum/autodist">autodist</a></b> (🥉10 ·  ⭐ 130 · 💀) - Simple Distributed Deep Learning on TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Hyperparameter Optimization & AutoML

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for hyperparameter optimization, automl and neural architecture search._

<details><summary><b><a href="https://github.com/alteryx/featuretools">featuretools</a></b> (🥇34 ·  ⭐ 6.8K) - An open source python library for automated feature engineering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/alteryx/featuretools) (👨‍💻 71 · 🔀 810 · 📦 1.4K · 📋 970 - 17% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/alteryx/featuretools
	```
- [PyPi](https://pypi.org/project/featuretools) (📥 65K / month):
	```
	pip install featuretools
	```
- [Conda](https://anaconda.org/conda-forge/featuretools) (📥 170K · ⏱️ 24.07.2023):
	```
	conda install -c conda-forge featuretools
	```
</details>
<details><summary><b><a href="https://github.com/facebook/Ax">Ax</a></b> (🥇34 ·  ⭐ 2.1K) - Adaptive Experimentation Platform. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebook/Ax) (👨‍💻 150 · 🔀 260 · 📦 560 · 📋 580 - 3% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/facebook/Ax
	```
- [PyPi](https://pypi.org/project/ax-platform) (📥 120K / month):
	```
	pip install ax-platform
	```
- [Conda](https://anaconda.org/conda-forge/ax-platform) (📥 14K · ⏱️ 12.08.2023):
	```
	conda install -c conda-forge ax-platform
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/nni">NNI</a></b> (🥇33 ·  ⭐ 13K) - An open source AutoML toolkit for automate machine learning lifecycle,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/nni) (👨‍💻 190 · 🔀 1.8K · 📦 480 · 📋 2K - 16% open · ⏱️ 07.08.2023):

	```
	git clone https://github.com/microsoft/nni
	```
- [PyPi](https://pypi.org/project/nni) (📥 23K / month):
	```
	pip install nni
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/botorch">BoTorch</a></b> (🥇33 ·  ⭐ 2.8K) - Bayesian optimization in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/botorch) (👨‍💻 100 · 🔀 330 · 📦 700 · 📋 420 - 11% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/pytorch/botorch
	```
- [PyPi](https://pypi.org/project/botorch) (📥 200K / month):
	```
	pip install botorch
	```
- [Conda](https://anaconda.org/conda-forge/botorch) (📥 87K · ⏱️ 11.08.2023):
	```
	conda install -c conda-forge botorch
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/keras-tuner">Keras Tuner</a></b> (🥈32 ·  ⭐ 2.8K) - A Hyperparameter Tuning Library for Keras. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/keras-tuner) (👨‍💻 58 · 🔀 370 · 📦 2.7K · 📋 460 - 42% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/keras-team/keras-tuner
	```
- [PyPi](https://pypi.org/project/keras-tuner) (📥 210K / month):
	```
	pip install keras-tuner
	```
- [Conda](https://anaconda.org/conda-forge/keras-tuner) (📥 25K · ⏱️ 15.06.2023):
	```
	conda install -c conda-forge keras-tuner
	```
</details>
<details><summary><b><a href="https://github.com/keras-team/autokeras">AutoKeras</a></b> (🥈31 ·  ⭐ 8.9K) - AutoML library for deep learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/keras-team/autokeras) (👨‍💻 140 · 🔀 1.4K · 📥 16K · 📦 580 · 📋 890 - 14% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/keras-team/autokeras
	```
- [PyPi](https://pypi.org/project/autokeras) (📥 13K / month):
	```
	pip install autokeras
	```
</details>
<details><summary><b><a href="https://github.com/automl/auto-sklearn">auto-sklearn</a></b> (🥈31 ·  ⭐ 7.2K) - Automated Machine Learning with scikit-learn. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/automl/auto-sklearn) (👨‍💻 88 · 🔀 1.2K · 📥 50 · 📦 490 · 📋 1K - 17% open · ⏱️ 18.04.2023):

	```
	git clone https://github.com/automl/auto-sklearn
	```
- [PyPi](https://pypi.org/project/auto-sklearn) (📥 27K / month):
	```
	pip install auto-sklearn
	```
- [Conda](https://anaconda.org/conda-forge/auto-sklearn) (📥 19K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge auto-sklearn
	```
</details>
<details><summary><b><a href="https://github.com/bayesian-optimization/BayesianOptimization">Bayesian Optimization</a></b> (🥈31 ·  ⭐ 7K) - A Python implementation of global optimization with.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bayesian-optimization/BayesianOptimization) (👨‍💻 41 · 🔀 1.4K · 📥 140 · 📦 2.1K · 📋 320 - 4% open · ⏱️ 14.07.2023):

	```
	git clone https://github.com/fmfn/BayesianOptimization
	```
- [PyPi](https://pypi.org/project/bayesian-optimization) (📥 190K / month):
	```
	pip install bayesian-optimization
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/nevergrad">nevergrad</a></b> (🥈31 ·  ⭐ 3.6K) - A Python toolbox for performing gradient-free optimization. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/nevergrad) (👨‍💻 50 · 🔀 330 · 📦 550 · 📋 240 - 29% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/facebookresearch/nevergrad
	```
- [PyPi](https://pypi.org/project/nevergrad) (📥 78K / month):
	```
	pip install nevergrad
	```
- [Conda](https://anaconda.org/conda-forge/nevergrad) (📥 42K · ⏱️ 21.09.2023):
	```
	conda install -c conda-forge nevergrad
	```
</details>
<details><summary><b><a href="https://github.com/mljar/mljar-supervised">mljar-supervised</a></b> (🥈29 ·  ⭐ 2.8K) - Python package for AutoML on Tabular Data with Feature.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/mljar/mljar-supervised) (👨‍💻 22 · 🔀 360 · 📦 88 · 📋 580 - 21% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/mljar/mljar-supervised
	```
- [PyPi](https://pypi.org/project/mljar-supervised) (📥 6.7K / month):
	```
	pip install mljar-supervised
	```
- [Conda](https://anaconda.org/conda-forge/mljar-supervised) (📥 11K · ⏱️ 27.09.2023):
	```
	conda install -c conda-forge mljar-supervised
	```
</details>
<details><summary><b><a href="https://github.com/autogluon/autogluon">AutoGluon</a></b> (🥈28 ·  ⭐ 6.3K) - AutoGluon: AutoML for Image, Text, Time Series, and Tabular.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/autogluon/autogluon) (👨‍💻 110 · 🔀 770 · 📦 2 · 📋 1.1K - 22% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/awslabs/autogluon
	```
- [PyPi](https://pypi.org/project/autogluon) (📥 43K / month):
	```
	pip install autogluon
	```
</details>
<details><summary><b><a href="https://github.com/maxpumperla/hyperas">Hyperas</a></b> (🥈25 ·  ⭐ 2.2K · 💤) - Keras + Hyperopt: A very simple wrapper for convenient.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/maxpumperla/hyperas) (👨‍💻 22 · 🔀 310 · 📦 330 · 📋 260 - 37% open · ⏱️ 05.01.2023):

	```
	git clone https://github.com/maxpumperla/hyperas
	```
- [PyPi](https://pypi.org/project/hyperas) (📥 11K / month):
	```
	pip install hyperas
	```
</details>
<details><summary><b><a href="https://github.com/SheffieldML/GPyOpt">GPyOpt</a></b> (🥈24 ·  ⭐ 890 · 💤) - Gaussian Process Optimization using GPy. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/SheffieldML/GPyOpt) (👨‍💻 49 · 🔀 250 · 📦 460 · 📋 290 - 35% open · ⏱️ 17.01.2023):

	```
	git clone https://github.com/SheffieldML/GPyOpt
	```
- [PyPi](https://pypi.org/project/gpyopt) (📥 7.8K / month):
	```
	pip install gpyopt
	```
</details>
<details><summary><b><a href="https://github.com/SimonBlanke/Hyperactive">Hyperactive</a></b> (🥈23 ·  ⭐ 470) - An optimization and data collection toolbox for convenient and fast.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SimonBlanke/Hyperactive) (👨‍💻 7 · 🔀 41 · 📥 130 · 📦 21 · 📋 60 - 15% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/SimonBlanke/Hyperactive
	```
- [PyPi](https://pypi.org/project/hyperactive) (📥 1.3K / month):
	```
	pip install hyperactive
	```
</details>
<details><summary><b><a href="https://github.com/ScottfreeLLC/AlphaPy">AlphaPy</a></b> (🥉19 ·  ⭐ 960) - Automated Machine Learning [AutoML] with Python, scikit-learn, Keras,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/ScottfreeLLC/AlphaPy) (👨‍💻 5 · 🔀 180 · 📦 4 · 📋 42 - 30% open · ⏱️ 31.08.2023):

	```
	git clone https://github.com/ScottfreeLLC/AlphaPy
	```
- [PyPi](https://pypi.org/project/alphapy) (📥 130 / month):
	```
	pip install alphapy
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/featurewiz">featurewiz</a></b> (🥉19 ·  ⭐ 470) - Use advanced feature engineering strategies and select best.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/featurewiz) (👨‍💻 9 · 🔀 75 · 📦 53 · 📋 71 - 2% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/AutoViML/featurewiz
	```
- [PyPi](https://pypi.org/project/featurewiz) (📥 9.6K / month):
	```
	pip install featurewiz
	```
</details>
<details><summary><b><a href="https://github.com/dragonfly/dragonfly">Dragonfly</a></b> (🥉17 ·  ⭐ 800 · 💤) - An open source python library for scalable Bayesian optimisation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dragonfly/dragonfly) (👨‍💻 13 · 🔀 220 · 📋 59 - 66% open · ⏱️ 01.10.2022):

	```
	git clone https://github.com/dragonfly/dragonfly
	```
- [PyPi](https://pypi.org/project/dragonfly-opt) (📥 41K / month):
	```
	pip install dragonfly-opt
	```
</details>
<details><summary><b><a href="https://github.com/AutoViML/Auto_ViML">Auto ViML</a></b> (🥉17 ·  ⭐ 470) - Automatically Build Multiple ML Models with a Single Line of Code... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/AutoViML/Auto_ViML) (👨‍💻 8 · 🔀 94 · 📦 22 · 📋 29 - 13% open · ⏱️ 21.05.2023):

	```
	git clone https://github.com/AutoViML/Auto_ViML
	```
- [PyPi](https://pypi.org/project/autoviml) (📥 1K / month):
	```
	pip install autoviml
	```
</details>
<details><summary>Show 29 hidden projects...</summary>

- <b><a href="https://github.com/optuna/optuna">Optuna</a></b> (🥇39 ·  ⭐ 8.7K) - A hyperparameter optimization framework. <code>❗Unlicensed</code>
- <b><a href="https://github.com/EpistasisLab/tpot">TPOT</a></b> (🥇33 ·  ⭐ 9.3K) - A Python Automated Machine Learning tool that optimizes machine.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-optimize/scikit-optimize">scikit-optimize</a></b> (🥇33 ·  ⭐ 2.7K · 💀) - Sequential model-based optimization with a.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/hyperopt/hyperopt">Hyperopt</a></b> (🥈30 ·  ⭐ 6.9K) - Distributed Asynchronous Hyperparameter Optimization in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/shankarpandala/lazypredict">lazypredict</a></b> (🥈25 ·  ⭐ 2.2K · 💀) - Lazy Predict help build a lot of basic models without much.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/adanet">AdaNet</a></b> (🥈23 ·  ⭐ 3.5K · 💀) - Fast and flexible AutoML with learning guarantees. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/autonomio/talos">Talos</a></b> (🥈23 ·  ⭐ 1.6K · 💀) - Hyperparameter Optimization for TensorFlow, Keras and PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Epistimio/orion">Orion</a></b> (🥈23 ·  ⭐ 270) - Asynchronous Distributed Hyperparameter Optimization. <code>❗Unlicensed</code>
- <b><a href="https://github.com/automl/SMAC3">SMAC3</a></b> (🥉22 ·  ⭐ 910) - SMAC3: A Versatile Bayesian Optimization Package for Hyperparameter.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/ClimbsRocks/auto_ml">auto_ml</a></b> (🥉21 ·  ⭐ 1.6K · 💀) - [UNMAINTAINED] Automated machine learning for analytics & production. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/AxeldeRomblay/MLBox">MLBox</a></b> (🥉21 ·  ⭐ 1.4K · 💀) - MLBox is a powerful Automated Machine Learning python library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/automl/HpBandSter">HpBandSter</a></b> (🥉21 ·  ⭐ 590 · 💀) - a distributed Hyperband implementation on Steroids. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/Neuraxio/Neuraxle">Neuraxle</a></b> (🥉21 ·  ⭐ 580 · 💀) - The worlds cleanest AutoML library - Do hyperparameter tuning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/claesenm/optunity">optunity</a></b> (🥉21 ·  ⭐ 410 · 💀) - optimization routines for hyperparameter tuning. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/rsteca/sklearn-deap">sklearn-deap</a></b> (🥉19 ·  ⭐ 740 · 💀) - Use evolutionary algorithms instead of gridsearch in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/williamFalcon/test-tube">Test Tube</a></b> (🥉19 ·  ⭐ 740 · 💀) - Python library to easily log experiments and parallelize.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HDI-Project/ATM">Auto Tune Models</a></b> (🥉18 ·  ⭐ 520 · 💀) - Auto Tune Models - A multi-tenant, multi-data system for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sherpa-ai/sherpa">Sherpa</a></b> (🥉18 ·  ⭐ 320 · 💀) - Hyperparameter optimization that enables researchers to.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/minimaxir/automl-gs">automl-gs</a></b> (🥉16 ·  ⭐ 1.8K · 💀) - Provide an input CSV and a target field to predict, generate a.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/HunterMcGushion/hyperparameter_hunter">HyperparameterHunter</a></b> (🥉16 ·  ⭐ 700 · 💀) - Easy hyperparameter optimization and automatic result.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tobegit3hub/advisor">Advisor</a></b> (🥉15 ·  ⭐ 1.5K · 💀) - Open-source implementation of Google Vizier for hyper parameters.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/reiinakano/xcessiv">Xcessiv</a></b> (🥉15 ·  ⭐ 1.3K · 💀) - A web-based application for quick, scalable, and automated.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jmcarpenter2/parfit">Parfit</a></b> (🥉15 ·  ⭐ 200 · 💀) - A package for parallelizing the fit and flexibly scoring of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/carpedm20/ENAS-pytorch">ENAS</a></b> (🥉13 ·  ⭐ 2.6K · 💀) - PyTorch implementation of Efficient Neural Architecture Search via.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/google/model_search">model_search</a></b> (🥉12 ·  ⭐ 3.2K · 💀) - AutoML algorithms for model architecture search at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/LGE-ARC-AdvancedAI/auptimizer">Auptimizer</a></b> (🥉12 ·  ⭐ 200 · 💀) - An automatic ML model optimization tool. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/joeddav/devol">Devol</a></b> (🥉11 ·  ⭐ 950 · 💀) - Genetic neural architecture search with Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/genixpro/hypermax">Hypermax</a></b> (🥉10 ·  ⭐ 110) - Better, faster hyper-parameter optimization. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/gdikov/hypertunity">Hypertunity</a></b> (🥉8 ·  ⭐ 140 · 💀) - A toolset for black-box hyperparameter optimisation. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Reinforcement Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating reinforcement learning & agent-based systems._

<details><summary><b><a href="https://github.com/openai/gym">OpenAI Gym</a></b> (🥇38 ·  ⭐ 33K · 💤) - A toolkit for developing and comparing reinforcement learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/gym) (👨‍💻 380 · 🔀 8K · 📦 46K · 📋 1.8K - 3% open · ⏱️ 30.01.2023):

	```
	git clone https://github.com/openai/gym
	```
- [PyPi](https://pypi.org/project/gym) (📥 390K / month):
	```
	pip install gym
	```
- [Conda](https://anaconda.org/conda-forge/gym) (📥 250K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge gym
	```
</details>
<details><summary><b><a href="https://github.com/AI4Finance-Foundation/FinRL">FinRL</a></b> (🥇29 ·  ⭐ 8.2K) - FinRL: Financial Reinforcement Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/AI4Finance-Foundation/FinRL) (👨‍💻 110 · 🔀 2K · 📦 23 · 📋 640 - 26% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/AI4Finance-Foundation/FinRL
	```
- [PyPi](https://pypi.org/project/finrl) (📥 1.2K / month):
	```
	pip install finrl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/agents">TF-Agents</a></b> (🥇29 ·  ⭐ 2.6K) - TF-Agents: A reliable, scalable and easy to use TensorFlow.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/agents) (👨‍💻 140 · 🔀 670 · 📦 1.3K · 📋 640 - 27% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/tensorflow/agents
	```
- [PyPi](https://pypi.org/project/tf-agents) (📥 32K / month):
	```
	pip install tf-agents
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/acme">Acme</a></b> (🥈28 ·  ⭐ 3.2K) - A library of reinforcement learning components and agents. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-deepmind/acme) (👨‍💻 84 · 🔀 390 · 📦 170 · 📋 250 - 20% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/deepmind/acme
	```
- [PyPi](https://pypi.org/project/dm-acme) (📥 1.1K / month):
	```
	pip install dm-acme
	```
- [Conda](https://anaconda.org/conda-forge/dm-acme) (📥 7.6K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dm-acme
	```
</details>
<details><summary><b><a href="https://github.com/tensorforce/tensorforce">TensorForce</a></b> (🥈27 ·  ⭐ 3.2K) - Tensorforce: a TensorFlow library for applied.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorforce/tensorforce) (👨‍💻 83 · 🔀 520 · 📦 430 · 📋 660 - 4% open · ⏱️ 14.08.2023):

	```
	git clone https://github.com/tensorforce/tensorforce
	```
- [PyPi](https://pypi.org/project/tensorforce) (📥 600 / month):
	```
	pip install tensorforce
	```
</details>
<details><summary><b><a href="https://github.com/google/dopamine">Dopamine</a></b> (🥈25 ·  ⭐ 10K) - Dopamine is a research framework for fast prototyping of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google/dopamine) (👨‍💻 15 · 🔀 1.3K · 📦 18 · 📋 160 - 46% open · ⏱️ 29.06.2023):

	```
	git clone https://github.com/google/dopamine
	```
- [PyPi](https://pypi.org/project/dopamine-rl) (📥 32K / month):
	```
	pip install dopamine-rl
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PARL">PARL</a></b> (🥉24 ·  ⭐ 3.1K) - A high-performance distributed training framework for Reinforcement.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PARL) (👨‍💻 41 · 🔀 810 · 📦 120 · 📋 500 - 20% open · ⏱️ 19.05.2023):

	```
	git clone https://github.com/PaddlePaddle/PARL
	```
- [PyPi](https://pypi.org/project/parl) (📥 590 / month):
	```
	pip install parl
	```
</details>
<details><summary><b><a href="https://github.com/rlworkgroup/garage">garage</a></b> (🥉24 ·  ⭐ 1.7K · 💤) - A toolkit for reproducible reinforcement learning research. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rlworkgroup/garage) (👨‍💻 79 · 🔀 290 · 📦 90 · 📋 1K - 19% open · ⏱️ 04.01.2023):

	```
	git clone https://github.com/rlworkgroup/garage
	```
- [PyPi](https://pypi.org/project/garage) (📥 460 / month):
	```
	pip install garage
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/ReAgent">ReAgent</a></b> (🥉22 ·  ⭐ 3.5K) - A platform for Reasoning systems (Reinforcement Learning,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/ReAgent) (👨‍💻 160 · 🔀 500 · 📋 110 - 30% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/facebookresearch/ReAgent
	```
- [PyPi](https://pypi.org/project/reagent) (📥 21 / month):
	```
	pip install reagent
	```
</details>
<details><summary><b><a href="https://github.com/pfnet/pfrl">PFRL</a></b> (🥉21 ·  ⭐ 1.1K) - PFRL: a PyTorch-based deep reinforcement learning library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pfnet/pfrl) (👨‍💻 19 · 🔀 140 · 📦 92 · 📋 72 - 37% open · ⏱️ 16.07.2023):

	```
	git clone https://github.com/pfnet/pfrl
	```
- [PyPi](https://pypi.org/project/pfrl) (📥 380 / month):
	```
	pip install pfrl
	```
</details>
<details><summary><b><a href="https://github.com/IntelLabs/coach">Coach</a></b> (🥉20 ·  ⭐ 2.3K · 💤) - Reinforcement Learning Coach by Intel AI Lab enables easy.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/IntelLabs/coach) (👨‍💻 38 · 🔀 450 · 📋 260 - 30% open · ⏱️ 11.12.2022):

	```
	git clone https://github.com/IntelLabs/coach
	```
- [PyPi](https://pypi.org/project/rl_coach) (📥 65 / month):
	```
	pip install rl_coach
	```
</details>
<details><summary><b><a href="https://github.com/google-research/rliable">rliable</a></b> (🥉13 ·  ⭐ 620) - [NeurIPS21 Outstanding Paper] Library for reliable evaluation on RL.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-research/rliable) (👨‍💻 6 · 🔀 41 · 📦 92 · 📋 13 - 15% open · ⏱️ 29.05.2023):

	```
	git clone https://github.com/google-research/rliable
	```
- [PyPi](https://pypi.org/project/rliable`):
	```
	pip install rliable`
	```
</details>
<details><summary>Show 11 hidden projects...</summary>

- <b><a href="https://github.com/keras-rl/keras-rl">keras-rl</a></b> (🥇29 ·  ⭐ 5.4K · 💀) - Deep Reinforcement Learning for Keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Farama-Foundation/ViZDoom">ViZDoom</a></b> (🥇29 ·  ⭐ 1.6K) - Reinforcement Learning environments based on the 1993 game Doom. <code>❗Unlicensed</code>
- <b><a href="https://github.com/openai/baselines">baselines</a></b> (🥈27 ·  ⭐ 15K · 💀) - OpenAI Baselines: high-quality implementations of reinforcement.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google-deepmind/rlax">RLax</a></b> (🥈25 ·  ⭐ 1.1K) -  <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/chainer/chainerrl">ChainerRL</a></b> (🥉24 ·  ⭐ 1.1K · 💀) - ChainerRL is a deep reinforcement learning library built on top of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/tensorlayer/TensorLayer">TensorLayer</a></b> (🥉23 ·  ⭐ 7.2K · 💤) - Deep Learning and Reinforcement Learning Library for.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/hill-a/stable-baselines">Stable Baselines</a></b> (🥉22 ·  ⭐ 3.9K · 💀) - A fork of OpenAI Baselines, implementations of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/google-deepmind/trfl">TRFL</a></b> (🥉20 ·  ⭐ 3.1K · 💀) - TensorFlow Reinforcement Learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/google-deepmind/lab">DeepMind Lab</a></b> (🥉17 ·  ⭐ 6.9K · 💤) - A customisable 3D platform for agent-based AI research. <code>❗Unlicensed</code>
- <b><a href="https://github.com/SerpentAI/SerpentAI">SerpentAI</a></b> (🥉16 ·  ⭐ 6.6K · 💀) - Game Agent Framework. Helping you create AIs / Bots that learn to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/enlite-ai/maze">Maze</a></b> (🥉12 ·  ⭐ 250 · 💤) - Maze Applied Reinforcement Learning Framework. <code><a href="https://tldrlegal.com/search?q=Custom">❗️Custom</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Recommender Systems

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for building and evaluating recommendation systems._

<details><summary><b><a href="https://github.com/recommenders-team/recommenders">Recommenders</a></b> (🥇34 ·  ⭐ 16K) - Best Practices on Recommendation Systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/recommenders-team/recommenders) (👨‍💻 130 · 🔀 2.8K · 📥 440 · 📦 84 · 📋 810 - 19% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/microsoft/recommenders
	```
- [PyPi](https://pypi.org/project/recommenders) (📥 50K / month):
	```
	pip install recommenders
	```
</details>
<details><summary><b><a href="https://github.com/benfred/implicit">implicit</a></b> (🥇32 ·  ⭐ 3.3K) - Fast Python Collaborative Filtering for Implicit Feedback Datasets. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/benfred/implicit) (👨‍💻 34 · 🔀 580 · 📥 580 · 📦 1.1K · 📋 470 - 15% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/benfred/implicit
	```
- [PyPi](https://pypi.org/project/implicit) (📥 130K / month):
	```
	pip install implicit
	```
- [Conda](https://anaconda.org/conda-forge/implicit) (📥 540K · ⏱️ 12.10.2023):
	```
	conda install -c conda-forge implicit
	```
</details>
<details><summary><b><a href="https://github.com/lyst/lightfm">lightfm</a></b> (🥈30 ·  ⭐ 4.4K) - A Python implementation of LightFM, a hybrid recommendation algorithm. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/lyst/lightfm) (👨‍💻 47 · 🔀 660 · 📦 1.2K · 📋 490 - 27% open · ⏱️ 30.04.2023):

	```
	git clone https://github.com/lyst/lightfm
	```
- [PyPi](https://pypi.org/project/lightfm) (📥 660K / month):
	```
	pip install lightfm
	```
- [Conda](https://anaconda.org/conda-forge/lightfm) (📥 170K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge lightfm
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/recommenders">TF Recommenders</a></b> (🥈29 ·  ⭐ 1.7K) - TensorFlow Recommenders is a library for building.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/recommenders) (👨‍💻 42 · 🔀 240 · 📦 250 · 📋 390 - 53% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/tensorflow/recommenders
	```
- [PyPi](https://pypi.org/project/tensorflow-recommenders) (📥 330K / month):
	```
	pip install tensorflow-recommenders
	```
</details>
<details><summary><b><a href="https://github.com/PreferredAI/cornac">Cornac</a></b> (🥈27 ·  ⭐ 750) - A Comparative Framework for Multimodal Recommender Systems. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PreferredAI/cornac) (👨‍💻 17 · 🔀 120 · 📦 170 · 📋 120 - 4% open · ⏱️ 25.09.2023):

	```
	git clone https://github.com/PreferredAI/cornac
	```
- [PyPi](https://pypi.org/project/cornac) (📥 100K / month):
	```
	pip install cornac
	```
- [Conda](https://anaconda.org/conda-forge/cornac) (📥 320K · ⏱️ 25.07.2023):
	```
	conda install -c conda-forge cornac
	```
</details>
<details><summary><b><a href="https://github.com/NicolasHug/Surprise">scikit-surprise</a></b> (🥈26 ·  ⭐ 6K · 💤) - A Python scikit for building and analyzing recommender.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/NicolasHug/Surprise) (👨‍💻 45 · 🔀 960 · 📦 18 · 📋 380 - 19% open · ⏱️ 27.01.2023):

	```
	git clone https://github.com/NicolasHug/Surprise
	```
- [PyPi](https://pypi.org/project/scikit-surprise) (📥 140K / month):
	```
	pip install scikit-surprise
	```
- [Conda](https://anaconda.org/conda-forge/scikit-surprise) (📥 340K · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge scikit-surprise
	```
</details>
<details><summary><b><a href="https://github.com/RUCAIBox/RecBole">RecBole</a></b> (🥈26 ·  ⭐ 2.9K) - A unified, comprehensive and efficient recommendation library. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/RUCAIBox/RecBole) (👨‍💻 69 · 🔀 540 · 📋 800 - 19% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/RUCAIBox/RecBole
	```
- [PyPi](https://pypi.org/project/recbole) (📥 2.7K / month):
	```
	pip install recbole
	```
- [Conda](https://anaconda.org/aibox/recbole) (📥 4K · ⏱️ 16.06.2023):
	```
	conda install -c aibox recbole
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/ranking">TF Ranking</a></b> (🥈26 ·  ⭐ 2.7K) - Learning to Rank in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/ranking) (👨‍💻 33 · 🔀 460 · 📋 310 - 22% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/tensorflow/ranking
	```
- [PyPi](https://pypi.org/project/tensorflow_ranking) (📥 100K / month):
	```
	pip install tensorflow_ranking
	```
</details>
<details><summary><b><a href="https://github.com/statisticianinstilettos/recmetrics">recmetrics</a></b> (🥉20 ·  ⭐ 530) - A library of metrics for evaluating recommender systems. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/statisticianinstilettos/recmetrics) (👨‍💻 20 · 🔀 95 · 📥 5 · 📦 45 · 📋 23 - 34% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/statisticianinstilettos/recmetrics
	```
- [PyPi](https://pypi.org/project/recmetrics) (📥 11K / month):
	```
	pip install recmetrics
	```
</details>
<details><summary>Show 7 hidden projects...</summary>

- <b><a href="https://github.com/lenskit/lkpy">lkpy</a></b> (🥉23 ·  ⭐ 240) - Python recommendation toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/jfkirk/tensorrec">tensorrec</a></b> (🥉19 ·  ⭐ 1.2K · 💀) - A TensorFlow recommendation algorithm and framework in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ibayer/fastFM">fastFM</a></b> (🥉19 ·  ⭐ 1.1K · 💀) - fastFM: A Library for Factorization Machines. <code>❗Unlicensed</code>
- <b><a href="https://github.com/maciejkula/spotlight">Spotlight</a></b> (🥉18 ·  ⭐ 2.9K · 💀) - Deep recommender models using PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/caserec/CaseRecommender">Case Recommender</a></b> (🥉18 ·  ⭐ 440 · 💀) - Case Recommender: A Flexible and Extensible Python.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ShopRunner/collie">Collie</a></b> (🥉14 ·  ⭐ 100 · 💤) - A library for preparing, training, and evaluating scalable deep.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ylongqi/openrec">OpenRec</a></b> (🥉12 ·  ⭐ 400 · 💀) - OpenRec is an open-source and modular library for neural network-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
</details>
<br>

## Privacy Machine Learning

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for encrypted and privacy-preserving machine learning using methods like federated learning & differential privacy._

<details><summary><b><a href="https://github.com/OpenMined/PySyft">PySyft</a></b> (🥇34 ·  ⭐ 9K) - Perform data science on data that remains in someone elses server. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/OpenMined/PySyft) (👨‍💻 500 · 🔀 1.9K · 📥 210 · 📋 3.4K - 3% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/OpenMined/PySyft
	```
- [PyPi](https://pypi.org/project/syft) (📥 4.5K / month):
	```
	pip install syft
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/opacus">Opacus</a></b> (🥈28 ·  ⭐ 1.5K) - Training PyTorch models with differential privacy. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/opacus) (👨‍💻 73 · 🔀 290 · 📥 99 · 📦 670 · 📋 260 - 27% open · ⏱️ 06.09.2023):

	```
	git clone https://github.com/pytorch/opacus
	```
- [PyPi](https://pypi.org/project/opacus) (📥 30K / month):
	```
	pip install opacus
	```
- [Conda](https://anaconda.org/conda-forge/opacus) (📥 12K · ⏱️ 18.06.2023):
	```
	conda install -c conda-forge opacus
	```
</details>
<details><summary><b><a href="https://github.com/FederatedAI/FATE">FATE</a></b> (🥈26 ·  ⭐ 5.2K) - An Industrial Grade Federated Learning Framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/FederatedAI/FATE) (👨‍💻 92 · 🔀 1.5K · 📋 1.8K - 43% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/FederatedAI/FATE
	```
- [PyPi](https://pypi.org/project/ETAF):
	```
	pip install ETAF
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/privacy">TensorFlow Privacy</a></b> (🥉25 ·  ⭐ 1.8K) - Library for training machine learning models with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/privacy) (👨‍💻 55 · 🔀 410 · 📥 120 · 📋 170 - 46% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/tensorflow/privacy
	```
- [PyPi](https://pypi.org/project/tensorflow-privacy) (📥 15K / month):
	```
	pip install tensorflow-privacy
	```
</details>
<details><summary><b><a href="https://github.com/tf-encrypted/tf-encrypted">TFEncrypted</a></b> (🥉22 ·  ⭐ 1.2K · 💤) - A Framework for Encrypted Machine Learning in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tf-encrypted/tf-encrypted) (👨‍💻 29 · 🔀 200 · 📦 64 · 📋 430 - 32% open · ⏱️ 08.02.2023):

	```
	git clone https://github.com/tf-encrypted/tf-encrypted
	```
- [PyPi](https://pypi.org/project/tf-encrypted) (📥 420 / month):
	```
	pip install tf-encrypted
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/CrypTen">CrypTen</a></b> (🥉21 ·  ⭐ 1.4K) - A framework for Privacy Preserving Machine Learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/CrypTen) (👨‍💻 33 · 🔀 250 · 📦 30 · 📋 240 - 20% open · ⏱️ 25.08.2023):

	```
	git clone https://github.com/facebookresearch/CrypTen
	```
- [PyPi](https://pypi.org/project/crypten) (📥 320 / month):
	```
	pip install crypten
	```
</details>
<br>

## Workflow & Experiment Tracking

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to organize, track, and visualize machine learning experiments._

<details><summary><b><a href="https://github.com/mlflow/mlflow">mlflow</a></b> (🥇44 ·  ⭐ 16K) - Open source platform for the machine learning lifecycle. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mlflow/mlflow) (👨‍💻 650 · 🔀 3.5K · 📦 25K · 📋 3.2K - 31% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/mlflow/mlflow
	```
- [PyPi](https://pypi.org/project/mlflow) (📥 14M / month):
	```
	pip install mlflow
	```
- [Conda](https://anaconda.org/conda-forge/mlflow) (📥 1.6M · ⏱️ 21.09.2023):
	```
	conda install -c conda-forge mlflow
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensorboard">Tensorboard</a></b> (🥇43 ·  ⭐ 6.4K) - TensorFlows Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensorboard) (👨‍💻 310 · 🔀 1.6K · 📦 190K · 📋 1.8K - 32% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/tensorflow/tensorboard
	```
- [PyPi](https://pypi.org/project/tensorboard) (📥 21M / month):
	```
	pip install tensorboard
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard) (📥 4.3M · ⏱️ 28.09.2023):
	```
	conda install -c conda-forge tensorboard
	```
</details>
<details><summary><b><a href="https://github.com/wandb/wandb">wandb client</a></b> (🥇41 ·  ⭐ 7.3K) - A tool for visualizing and tracking your machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wandb/wandb) (👨‍💻 160 · 🔀 540 · 📦 31K · 📋 2.8K - 26% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/wandb/client
	```
- [PyPi](https://pypi.org/project/wandb) (📥 6.8M / month):
	```
	pip install wandb
	```
- [Conda](https://anaconda.org/conda-forge/wandb) (📥 390K · ⏱️ 04.10.2023):
	```
	conda install -c conda-forge wandb
	```
</details>
<details><summary><b><a href="https://github.com/iterative/dvc">DVC</a></b> (🥇40 ·  ⭐ 12K) - Data Version Control | Git for Data & Models | ML Experiments Management. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/iterative/dvc) (👨‍💻 290 · 🔀 1.1K · 📥 41K · 📦 9.9K · 📋 4.5K - 12% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/iterative/dvc
	```
- [PyPi](https://pypi.org/project/dvc) (📥 740K / month):
	```
	pip install dvc
	```
- [Conda](https://anaconda.org/conda-forge/dvc) (📥 1.7M · ⏱️ 24.09.2023):
	```
	conda install -c conda-forge dvc
	```
</details>
<details><summary><b><a href="https://github.com/aws/sagemaker-python-sdk">SageMaker SDK</a></b> (🥈38 ·  ⭐ 1.9K) - A library for training and deploying machine learning.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/aws/sagemaker-python-sdk) (👨‍💻 400 · 🔀 1K · 📦 3.1K · 📋 1.3K - 32% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/aws/sagemaker-python-sdk
	```
- [PyPi](https://pypi.org/project/sagemaker) (📥 29M / month):
	```
	pip install sagemaker
	```
- [Conda](https://anaconda.org/conda-forge/sagemaker-python-sdk) (📥 680K · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge sagemaker-python-sdk
	```
</details>
<details><summary><b><a href="https://github.com/pycaret/pycaret">PyCaret</a></b> (🥈37 ·  ⭐ 7.8K) - An open-source, low-code machine learning library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pycaret/pycaret) (👨‍💻 130 · 🔀 1.6K · 📥 670 · 📦 4.5K · 📋 2.2K - 13% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/pycaret/pycaret
	```
- [PyPi](https://pypi.org/project/pycaret) (📥 230K / month):
	```
	pip install pycaret
	```
- [Conda](https://anaconda.org/conda-forge/pycaret) (📥 39K · ⏱️ 08.08.2023):
	```
	conda install -c conda-forge pycaret
	```
</details>
<details><summary><b><a href="https://github.com/snakemake/snakemake">snakemake</a></b> (🥈35 ·  ⭐ 2K) - This is the development home of the workflow management system.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/snakemake/snakemake) (👨‍💻 310 · 🔀 450 · 📦 1.7K · 📋 1.4K - 59% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/snakemake/snakemake
	```
- [PyPi](https://pypi.org/project/snakemake) (📥 100K / month):
	```
	pip install snakemake
	```
- [Conda](https://anaconda.org/bioconda/snakemake) (📥 880K · ⏱️ 19.09.2023):
	```
	conda install -c bioconda snakemake
	```
</details>
<details><summary><b><a href="https://github.com/allegroai/clearml">ClearML</a></b> (🥈33 ·  ⭐ 4.8K) - ClearML - Auto-Magical CI/CD to streamline your ML workflow... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/allegroai/clearml) (👨‍💻 85 · 🔀 600 · 📥 1.6K · 📦 750 · 📋 890 - 43% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/allegroai/clearml
	```
- [PyPi](https://pypi.org/project/clearml) (📥 230K / month):
	```
	pip install clearml
	```
- [Docker Hub](https://hub.docker.com/r/allegroai/trains) (📥 30K · ⏱️ 05.10.2020):
	```
	docker pull allegroai/trains
	```
</details>
<details><summary><b><a href="https://github.com/aimhubio/aim">aim</a></b> (🥈33 ·  ⭐ 4.3K) - Aim An easy-to-use modular observability for AI Systems. Extensible,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/aimhubio/aim) (👨‍💻 65 · 🔀 250 · 📦 330 · 📋 940 - 31% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/aimhubio/aim
	```
- [PyPi](https://pypi.org/project/aim) (📥 120K / month):
	```
	pip install aim
	```
- [Conda](https://anaconda.org/conda-forge/aim) (📥 39K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge aim
	```
</details>
<details><summary><b><a href="https://github.com/lanpa/tensorboardX">tensorboardX</a></b> (🥈32 ·  ⭐ 7.7K) - tensorboard for pytorch (and chainer, mxnet, numpy, ...). <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/lanpa/tensorboardX) (👨‍💻 81 · 🔀 850 · 📥 400 · 📦 35K · 📋 450 - 15% open · ⏱️ 03.09.2023):

	```
	git clone https://github.com/lanpa/tensorboardX
	```
- [PyPi](https://pypi.org/project/tensorboardX) (📥 2.2M / month):
	```
	pip install tensorboardX
	```
- [Conda](https://anaconda.org/conda-forge/tensorboardx) (📥 1.1M · ⏱️ 20.08.2023):
	```
	conda install -c conda-forge tensorboardx
	```
</details>
<details><summary><b><a href="https://github.com/Netflix/metaflow">Metaflow</a></b> (🥈32 ·  ⭐ 7K) - Build and manage real-life data science projects with ease!. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Netflix/metaflow) (👨‍💻 73 · 🔀 630 · 📦 540 · 📋 560 - 41% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/Netflix/metaflow
	```
- [PyPi](https://pypi.org/project/metaflow) (📥 160K / month):
	```
	pip install metaflow
	```
- [Conda](https://anaconda.org/conda-forge/metaflow) (📥 150K · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge metaflow
	```
</details>
<details><summary><b><a href="https://github.com/Azure/MachineLearningNotebooks">AzureML SDK</a></b> (🥈30 ·  ⭐ 3.8K) - Python notebooks with ML and deep learning examples with Azure.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Azure/MachineLearningNotebooks) (👨‍💻 64 · 🔀 2.3K · 📥 500 · 📋 1.4K - 23% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/Azure/MachineLearningNotebooks
	```
- [PyPi](https://pypi.org/project/azureml-sdk) (📥 1.5M / month):
	```
	pip install azureml-sdk
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/VisualDL">VisualDL</a></b> (🥈29 ·  ⭐ 4.7K) - Deep Learning Visualization Toolkit. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/VisualDL) (👨‍💻 33 · 🔀 630 · 📥 330 · 📦 2.3K · 📋 470 - 24% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/PaddlePaddle/VisualDL
	```
- [PyPi](https://pypi.org/project/visualdl) (📥 140K / month):
	```
	pip install visualdl
	```
</details>
<details><summary><b><a href="https://github.com/IDSIA/sacred">sacred</a></b> (🥈29 ·  ⭐ 4.1K) - Sacred is a tool to help you configure, organize, log and reproduce.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/IDSIA/sacred) (👨‍💻 100 · 🔀 360 · 📦 2.6K · 📋 560 - 17% open · ⏱️ 19.06.2023):

	```
	git clone https://github.com/IDSIA/sacred
	```
- [PyPi](https://pypi.org/project/sacred) (📥 38K / month):
	```
	pip install sacred
	```
- [Conda](https://anaconda.org/conda-forge/sacred) (📥 4.1K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge sacred
	```
</details>
<details><summary><b><a href="https://github.com/Kaggle/kaggle-api">kaggle</a></b> (🥈28 ·  ⭐ 5.6K) - Official Kaggle API. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Kaggle/kaggle-api) (👨‍💻 37 · 🔀 1K · 📦 18 · 📋 410 - 31% open · ⏱️ 17.07.2023):

	```
	git clone https://github.com/Kaggle/kaggle-api
	```
- [PyPi](https://pypi.org/project/kaggle) (📥 180K / month):
	```
	pip install kaggle
	```
- [Conda](https://anaconda.org/conda-forge/kaggle) (📥 140K · ⏱️ 18.07.2023):
	```
	conda install -c conda-forge kaggle
	```
</details>
<details><summary><b><a href="https://github.com/google/ml-metadata">ml-metadata</a></b> (🥉27 ·  ⭐ 560) - For recording and retrieving metadata associated with ML.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/ml-metadata) (👨‍💻 18 · 🔀 110 · 📥 2.1K · 📦 360 · 📋 100 - 25% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/google/ml-metadata
	```
- [PyPi](https://pypi.org/project/ml-metadata) (📥 110K / month):
	```
	pip install ml-metadata
	```
</details>
<details><summary><b><a href="https://github.com/neptune-ai/neptune-client">Neptune.ai</a></b> (🥉27 ·  ⭐ 410) - The MLOps stack component for experiment tracking. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/neptune-ai/neptune-client) (👨‍💻 52 · 🔀 48 · 📋 220 - 9% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/neptune-ai/neptune-client
	```
- [PyPi](https://pypi.org/project/neptune-client) (📥 540K / month):
	```
	pip install neptune-client
	```
- [Conda](https://anaconda.org/conda-forge/neptune-client) (📥 220K · ⏱️ 10.10.2023):
	```
	conda install -c conda-forge neptune-client
	```
</details>
<details><summary><b><a href="https://github.com/labmlai/labml">Labml</a></b> (🥉25 ·  ⭐ 1.6K) - Monitor deep learning model training and hardware usage from your mobile.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/labmlai/labml) (👨‍💻 9 · 🔀 110 · 📦 100 · 📋 34 - 41% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/labmlai/labml
	```
- [PyPi](https://pypi.org/project/labml) (📥 1.8K / month):
	```
	pip install labml
	```
</details>
<details><summary><b><a href="https://github.com/guildai/guildai">Guild AI</a></b> (🥉24 ·  ⭐ 820) - Experiment tracking, ML developer tools. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/guildai/guildai) (👨‍💻 29 · 🔀 81 · 📥 14 · 📦 82 · 📋 440 - 50% open · ⏱️ 12.08.2023):

	```
	git clone https://github.com/guildai/guildai
	```
- [PyPi](https://pypi.org/project/guildai) (📥 1.1K / month):
	```
	pip install guildai
	```
</details>
<details><summary><b><a href="https://github.com/studioml/studio">Studio.ml</a></b> (🥉20 ·  ⭐ 380) - Studio: Simplify and expedite model building process. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/studioml/studio) (👨‍💻 24 · 🔀 50 · 📦 5 · 📋 250 - 22% open · ⏱️ 06.09.2023):

	```
	git clone https://github.com/studioml/studio
	```
- [PyPi](https://pypi.org/project/studioml) (📥 130 / month):
	```
	pip install studioml
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/tensorwatch">TensorWatch</a></b> (🥉19 ·  ⭐ 3.3K) - Debugging, monitoring and visualization for Python Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/tensorwatch) (👨‍💻 15 · 🔀 350 · 📦 130 · 📋 68 - 75% open · ⏱️ 30.08.2023):

	```
	git clone https://github.com/microsoft/tensorwatch
	```
- [PyPi](https://pypi.org/project/tensorwatch) (📥 1K / month):
	```
	pip install tensorwatch
	```
</details>
<details><summary><b><a href="https://github.com/google/caliban">caliban</a></b> (🥉15 ·  ⭐ 490) - Research workflows made easy, locally and in the Cloud. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/caliban) (👨‍💻 10 · 🔀 71 · 📦 1 · 📋 26 - 42% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/google/caliban
	```
- [PyPi](https://pypi.org/project/caliban) (📥 36 / month):
	```
	pip install caliban
	```
</details>
<details><summary>Show 17 hidden projects...</summary>

- <b><a href="https://github.com/catalyst-team/catalyst">Catalyst</a></b> (🥈29 ·  ⭐ 3.2K · 💀) - Accelerated deep learning R&D. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MrPowers/quinn">quinn</a></b> (🥉25 ·  ⭐ 520) - pyspark methods to enhance developer productivity. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/huggingface/knockknock">knockknock</a></b> (🥉24 ·  ⭐ 2.6K · 💀) - Knock Knock: Get notified when your training ends with only two.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/m3dev/gokart">gokart</a></b> (🥉24 ·  ⭐ 290) - Gokart solves reproducibility, task dependencies, constraints of good code,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/stared/livelossplot">livelossplot</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - Live training loss plot in Jupyter Notebook for Keras,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/waleedka/hiddenlayer">hiddenlayer</a></b> (🥉21 ·  ⭐ 1.7K · 💀) - Neural network graphs and training metrics for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/EducationalTestingService/skll">SKLL</a></b> (🥉21 ·  ⭐ 540) - SciKit-Learn Laboratory (SKLL) makes it easy to run machine.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pytorch/tnt">TNT</a></b> (🥉20 ·  ⭐ 1.6K) - A lightweight library for PyTorch training tools and utilities. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/instacart/lore">lore</a></b> (🥉19 ·  ⭐ 1.5K · 💀) - Lore makes machine learning approachable for Software Engineers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/awslabs/mxboard">MXBoard</a></b> (🥉19 ·  ⭐ 320 · 💀) - Logging MXNet data for visualization in TensorBoard. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1X" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/replicate/keepsake">keepsake</a></b> (🥉18 ·  ⭐ 1.6K · 💀) - Version control for machine learning. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/TeamHG-Memex/tensorboard_logger">TensorBoard Logger</a></b> (🥉17 ·  ⭐ 620 · 💀) - Log TensorBoard events without touching TensorFlow. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/aniketmaurya/chitra">chitra</a></b> (🥉17 ·  ⭐ 220) - A multi-functional library for full-stack Deep Learning. Simplifies.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/minerva-ml/steppy">steppy</a></b> (🥉16 ·  ⭐ 140 · 💀) - Lightweight, Python library for fast and reproducible experimentation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/datmo/datmo">datmo</a></b> (🥉15 ·  ⭐ 340 · 💀) - Open source production model management tool for data scientists. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/ModelChimp/modelchimp">ModelChimp</a></b> (🥉13 ·  ⭐ 130 · 💀) - Experiment tracking for machine and deep learning projects. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/jrieke/traintool">traintool</a></b> (🥉6 ·  ⭐ 12 · 💀) - Train off-the-shelf machine learning models in one.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Model Serialization & Deployment

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to serialize models to files, convert between a variety of model formats, and optimize models for deployment._

<details><summary><b><a href="https://github.com/onnx/onnx">onnx</a></b> (🥇43 ·  ⭐ 16K) - Open standard for machine learning interoperability. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/onnx/onnx) (👨‍💻 300 · 🔀 3.5K · 📥 19K · 📦 19K · 📋 2.5K - 10% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/onnx/onnx
	```
- [PyPi](https://pypi.org/project/onnx) (📥 3.9M / month):
	```
	pip install onnx
	```
- [Conda](https://anaconda.org/conda-forge/onnx) (📥 850K · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge onnx
	```
</details>
<details><summary><b><a href="https://github.com/openai/triton">triton</a></b> (🥇38 ·  ⭐ 8.5K · 📈) - Development repository for the Triton language and compiler. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/openai/triton) (👨‍💻 170 · 🔀 870 · 📦 8.6K · 📋 840 - 39% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/openai/triton
	```
- [PyPi](https://pypi.org/project/triton) (📥 5.2M / month):
	```
	pip install triton
	```
</details>
<details><summary><b><a href="https://github.com/bentoml/BentoML">BentoML</a></b> (🥈35 ·  ⭐ 5.8K · 📈) - Build Production-Grade AI Applications. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/bentoml/BentoML) (👨‍💻 180 · 🔀 640 · 📥 2.1K · 📦 1.3K · 📋 930 - 17% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/bentoml/BentoML
	```
- [PyPi](https://pypi.org/project/bentoml) (📥 70K / month):
	```
	pip install bentoml
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/serve">TorchServe</a></b> (🥈35 ·  ⭐ 3.7K) - Serve, optimize and scale PyTorch models in production. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/serve) (👨‍💻 180 · 🔀 760 · 📥 5K · 📦 520 · 📋 1.4K - 21% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/pytorch/serve
	```
- [PyPi](https://pypi.org/project/torchserve) (📥 37K / month):
	```
	pip install torchserve
	```
- [Conda](https://anaconda.org/pytorch/torchserve) (📥 120K · ⏱️ 28.08.2023):
	```
	conda install -c pytorch torchserve
	```
- [Docker Hub](https://hub.docker.com/r/pytorch/torchserve) (📥 1.2M · ⭐ 21 · ⏱️ 28.08.2023):
	```
	docker pull pytorch/torchserve
	```
</details>
<details><summary><b><a href="https://github.com/apple/coremltools">Core ML Tools</a></b> (🥈32 ·  ⭐ 3.7K) - Core ML tools contain supporting tools for Core ML model.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/apple/coremltools) (👨‍💻 160 · 🔀 520 · 📥 8.2K · 📦 3.4K · 📋 1.2K - 19% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/apple/coremltools
	```
- [PyPi](https://pypi.org/project/coremltools) (📥 170K / month):
	```
	pip install coremltools
	```
- [Conda](https://anaconda.org/conda-forge/coremltools) (📥 52K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge coremltools
	```
</details>
<details><summary><b><a href="https://github.com/huggingface/huggingface_hub">huggingface_hub</a></b> (🥈31 ·  ⭐ 1.2K) - All the open source things related to the Hugging Face Hub. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/huggingface/huggingface_hub) (👨‍💻 110 · 🔀 280 · 📋 580 - 15% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/huggingface/huggingface_hub
	```
- [PyPi](https://pypi.org/project/huggingface_hub) (📥 19M / month):
	```
	pip install huggingface_hub
	```
- [Conda](https://anaconda.org/conda-forge/huggingface_hub) (📥 1.4M · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge huggingface_hub
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/hummingbird">Hummingbird</a></b> (🥉25 ·  ⭐ 3.2K) - Hummingbird compiles trained ML models into tensor computation for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/microsoft/hummingbird) (👨‍💻 39 · 🔀 260 · 📥 290 · 📋 300 - 18% open · ⏱️ 23.09.2023):

	```
	git clone https://github.com/microsoft/hummingbird
	```
- [PyPi](https://pypi.org/project/hummingbird-ml) (📥 12K / month):
	```
	pip install hummingbird-ml
	```
- [Conda](https://anaconda.org/conda-forge/hummingbird-ml) (📥 36K · ⏱️ 12.07.2023):
	```
	conda install -c conda-forge hummingbird-ml
	```
</details>
<details><summary><b><a href="https://github.com/BayesWitnesses/m2cgen">m2cgen</a></b> (🥉24 ·  ⭐ 2.6K · 💤) - Transform ML models into a native code (Java, C, Python, Go,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/BayesWitnesses/m2cgen) (👨‍💻 14 · 🔀 210 · 📥 54 · 📦 160 · 📋 100 - 32% open · ⏱️ 05.10.2022):

	```
	git clone https://github.com/BayesWitnesses/m2cgen
	```
- [PyPi](https://pypi.org/project/m2cgen) (📥 14K / month):
	```
	pip install m2cgen
	```
</details>
<details><summary><b><a href="https://github.com/cortexlabs/cortex">cortex</a></b> (🥉22 ·  ⭐ 8K · 💤) - Production infrastructure for machine learning at scale. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/cortexlabs/cortex) (👨‍💻 24 · 🔀 600 · 📋 1.1K - 10% open · ⏱️ 04.03.2023):

	```
	git clone https://github.com/cortexlabs/cortex
	```
- [PyPi](https://pypi.org/project/cortex) (📥 1.1K / month):
	```
	pip install cortex
	```
</details>
<details><summary><b><a href="https://github.com/nebuly-ai/nebuly">nebullvm</a></b> (🥉20 ·  ⭐ 8.3K) - Developer toolkit for making AI models better. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nebuly-ai/nebuly) (👨‍💻 40 · 🔀 650 · 📋 200 - 48% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/nebuly-ai/nebullvm
	```
- [PyPi](https://pypi.org/project/nebullvm) (📥 570 / month):
	```
	pip install nebullvm
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/microsoft/MMdnn">mmdnn</a></b> (🥈26 ·  ⭐ 5.7K · 💀) - MMdnn is a set of tools to help users inter-operate among different deep.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/nok/sklearn-porter">sklearn-porter</a></b> (🥉23 ·  ⭐ 1.3K · 💀) - Transpile trained scikit-learn estimators to C, Java,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/larq/compute-engine">Larq Compute Engine</a></b> (🥉20 ·  ⭐ 230) - Highly optimized inference engine for Binarized.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/gmalivenko/pytorch2keras">pytorch2keras</a></b> (🥉17 ·  ⭐ 840 · 💀) - PyTorch to Keras model convertor. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/riga/tfdeploy">tfdeploy</a></b> (🥉16 ·  ⭐ 350 · 💀) - Deploy tensorflow graphs for fast evaluation and export to.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/backprop-ai/backprop">backprop</a></b> (🥉9 ·  ⭐ 240 · 💀) - Backprop makes it simple to use, finetune, and deploy state-.. <code>❗Unlicensed</code>
</details>
<br>

## Model Interpretability

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries to visualize, explain, debug, evaluate, and interpret machine learning models._

<details><summary><b><a href="https://github.com/shap/shap">shap</a></b> (🥇41 ·  ⭐ 20K) - A game theoretic approach to explain the output of any machine learning model. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/shap/shap) (👨‍💻 220 · 🔀 2.9K · 📦 14K · 📋 2.3K - 60% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/slundberg/shap
	```
- [PyPi](https://pypi.org/project/shap) (📥 7.3M / month):
	```
	pip install shap
	```
- [Conda](https://anaconda.org/conda-forge/shap) (📥 2.1M · ⏱️ 09.10.2023):
	```
	conda install -c conda-forge shap
	```
</details>
<details><summary><b><a href="https://github.com/arviz-devs/arviz">arviz</a></b> (🥇34 ·  ⭐ 1.4K) - Exploratory analysis of Bayesian models with Python. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/arviz-devs/arviz) (👨‍💻 150 · 🔀 350 · 📥 130 · 📦 4.9K · 📋 820 - 19% open · ⏱️ 13.09.2023):

	```
	git clone https://github.com/arviz-devs/arviz
	```
- [PyPi](https://pypi.org/project/arviz) (📥 1.5M / month):
	```
	pip install arviz
	```
- [Conda](https://anaconda.org/conda-forge/arviz) (📥 2M · ⏱️ 19.09.2023):
	```
	conda install -c conda-forge arviz
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret">InterpretML</a></b> (🥇33 ·  ⭐ 5.7K) - Fit interpretable models. Explain blackbox machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret) (👨‍💻 39 · 🔀 670 · 📦 530 · 📋 390 - 17% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/interpretml/interpret
	```
- [PyPi](https://pypi.org/project/interpret) (📥 65K / month):
	```
	pip install interpret
	```
</details>
<details><summary><b><a href="https://github.com/lutzroeder/netron">Netron</a></b> (🥇32 ·  ⭐ 24K) - Visualizer for neural network, deep learning and machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lutzroeder/netron) (🔀 2.5K · 📥 26K · 📦 10 · 📋 990 - 2% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/lutzroeder/netron
	```
- [PyPi](https://pypi.org/project/netron) (📥 16K / month):
	```
	pip install netron
	```
</details>
<details><summary><b><a href="https://github.com/py-why/dowhy">DoWhy</a></b> (🥇31 ·  ⭐ 6.2K) - DoWhy is a Python library for causal inference that supports explicit.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/py-why/dowhy) (👨‍💻 82 · 🔀 850 · 📥 33 · 📦 300 · 📋 410 - 30% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/Microsoft/dowhy
	```
- [PyPi](https://pypi.org/project/dowhy) (📥 39K / month):
	```
	pip install dowhy
	```
- [Conda](https://anaconda.org/conda-forge/dowhy) (📥 17K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge dowhy
	```
</details>
<details><summary><b><a href="https://github.com/pytorch/captum">Captum</a></b> (🥈30 ·  ⭐ 4.2K) - Model interpretability and understanding for PyTorch. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pytorch/captum) (👨‍💻 100 · 🔀 430 · 📦 1.5K · 📋 480 - 32% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/pytorch/captum
	```
- [PyPi](https://pypi.org/project/captum) (📥 130K / month):
	```
	pip install captum
	```
- [Conda](https://anaconda.org/conda-forge/captum) (📥 16K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge captum
	```
</details>
<details><summary><b><a href="https://github.com/parrt/dtreeviz">dtreeviz</a></b> (🥈30 ·  ⭐ 2.7K) - A python library for decision tree visualization and model interpretation. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/parrt/dtreeviz) (👨‍💻 25 · 🔀 320 · 📦 910 · 📋 190 - 30% open · ⏱️ 13.07.2023):

	```
	git clone https://github.com/parrt/dtreeviz
	```
- [PyPi](https://pypi.org/project/dtreeviz) (📥 120K / month):
	```
	pip install dtreeviz
	```
- [Conda](https://anaconda.org/conda-forge/dtreeviz) (📥 60K · ⏱️ 13.07.2023):
	```
	conda install -c conda-forge dtreeviz
	```
</details>
<details><summary><b><a href="https://github.com/oegedijk/explainerdashboard">explainerdashboard</a></b> (🥈30 ·  ⭐ 2.1K) - Quickly build Explainable AI dashboards that show the inner.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/oegedijk/explainerdashboard) (👨‍💻 20 · 🔀 290 · 📦 370 · 📋 220 - 11% open · ⏱️ 01.08.2023):

	```
	git clone https://github.com/oegedijk/explainerdashboard
	```
- [PyPi](https://pypi.org/project/explainerdashboard) (📥 40K / month):
	```
	pip install explainerdashboard
	```
- [Conda](https://anaconda.org/conda-forge/explainerdashboard) (📥 40K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge explainerdashboard
	```
</details>
<details><summary><b><a href="https://github.com/MAIF/shapash">shapash</a></b> (🥈29 ·  ⭐ 2.5K) - Shapash: User-friendly Explainability and Interpretability to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MAIF/shapash) (👨‍💻 35 · 🔀 290 · 📦 130 · 📋 180 - 18% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/MAIF/shapash
	```
- [PyPi](https://pypi.org/project/shapash) (📥 8.4K / month):
	```
	pip install shapash
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi">Alibi</a></b> (🥈29 ·  ⭐ 2.2K) - Algorithms for explaining machine learning models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi) (👨‍💻 18 · 🔀 230 · 📦 520 · 📋 350 - 37% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/SeldonIO/alibi
	```
- [PyPi](https://pypi.org/project/alibi) (📥 25K / month):
	```
	pip install alibi
	```
</details>
<details><summary><b><a href="https://github.com/bmabey/pyLDAvis">pyLDAvis</a></b> (🥈29 ·  ⭐ 1.7K) - Python library for interactive topic model visualization. Port of.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/bmabey/pyLDAvis) (👨‍💻 39 · 🔀 350 · 📦 5.4K · 📋 180 - 45% open · ⏱️ 24.04.2023):

	```
	git clone https://github.com/bmabey/pyLDAvis
	```
- [PyPi](https://pypi.org/project/pyldavis) (📥 260K / month):
	```
	pip install pyldavis
	```
- [Conda](https://anaconda.org/conda-forge/pyldavis) (📥 75K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pyldavis
	```
</details>
<details><summary><b><a href="https://github.com/csinva/imodels">imodels</a></b> (🥈29 ·  ⭐ 1.2K) - Interpretable ML package for concise, transparent, and accurate.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/csinva/imodels) (👨‍💻 22 · 🔀 100 · 📦 55 · 📋 74 - 32% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/csinva/imodels
	```
- [PyPi](https://pypi.org/project/imodels) (📥 78K / month):
	```
	pip install imodels
	```
</details>
<details><summary><b><a href="https://github.com/microsoft/responsible-ai-toolbox">responsible-ai-widgets</a></b> (🥈29 ·  ⭐ 980) - Responsible AI Toolbox is a suite of tools providing.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/microsoft/responsible-ai-toolbox) (👨‍💻 38 · 🔀 240 · 📦 68 · 📋 270 - 16% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/microsoft/responsible-ai-toolbox
	```
- [PyPi](https://pypi.org/project/raiwidgets) (📥 5.5K / month):
	```
	pip install raiwidgets
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/lit">LIT</a></b> (🥈28 ·  ⭐ 3.2K) - The Learning Interpretability Tool: Interactively analyze ML models to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/lit) (👨‍💻 34 · 🔀 330 · 📦 24 · 📋 120 - 35% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/PAIR-code/lit
	```
- [PyPi](https://pypi.org/project/lit-nlp) (📥 3K / month):
	```
	pip install lit-nlp
	```
- [Conda](https://anaconda.org/conda-forge/lit-nlp) (📥 65K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge lit-nlp
	```
</details>
<details><summary><b><a href="https://github.com/fairlearn/fairlearn">fairlearn</a></b> (🥈27 ·  ⭐ 1.7K) - A Python package to assess and improve fairness of machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/fairlearn/fairlearn) (👨‍💻 75 · 🔀 350 · 📦 2 · 📋 430 - 35% open · ⏱️ 01.10.2023):

	```
	git clone https://github.com/fairlearn/fairlearn
	```
- [PyPi](https://pypi.org/project/fairlearn) (📥 390K / month):
	```
	pip install fairlearn
	```
- [Conda](https://anaconda.org/conda-forge/fairlearn) (📥 29K · ⏱️ 28.07.2023):
	```
	conda install -c conda-forge fairlearn
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIX360">Explainability 360</a></b> (🥈27 ·  ⭐ 1.4K) - Interpretability and explainability of data and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIX360) (👨‍💻 41 · 🔀 290 · 📦 84 · 📋 74 - 60% open · ⏱️ 22.08.2023):

	```
	git clone https://github.com/Trusted-AI/AIX360
	```
- [PyPi](https://pypi.org/project/aix360) (📥 610 / month):
	```
	pip install aix360
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-analysis">Model Analysis</a></b> (🥈27 ·  ⭐ 1.2K) - Model analysis tools for TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-analysis) (👨‍💻 56 · 🔀 250 · 📋 73 - 28% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/tensorflow/model-analysis
	```
- [PyPi](https://pypi.org/project/tensorflow-model-analysis) (📥 330K / month):
	```
	pip install tensorflow-model-analysis
	```
</details>
<details><summary><b><a href="https://github.com/Trusted-AI/AIF360">Fairness 360</a></b> (🥈26 ·  ⭐ 2.2K) - A comprehensive set of fairness metrics for datasets and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/AIF360) (👨‍💻 69 · 🔀 760 · 📦 310 · 📋 240 - 60% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/Trusted-AI/AIF360
	```
- [PyPi](https://pypi.org/project/aif360) (📥 6.6K / month):
	```
	pip install aif360
	```
- [Conda](https://anaconda.org/conda-forge/aif360) (📥 7K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge aif360
	```
</details>
<details><summary><b><a href="https://github.com/mckinsey/causalnex">CausalNex</a></b> (🥈26 ·  ⭐ 2K) - A Python library that helps data scientists to infer.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/mckinsey/causalnex) (👨‍💻 35 · 🔀 220 · 📦 98 · 📋 130 - 11% open · ⏱️ 11.07.2023):

	```
	git clone https://github.com/quantumblacklabs/causalnex
	```
- [PyPi](https://pypi.org/project/causalnex) (📥 5.2K / month):
	```
	pip install causalnex
	```
</details>
<details><summary><b><a href="https://github.com/albermax/innvestigate">iNNvestigate</a></b> (🥈26 ·  ⭐ 1.2K) - A toolbox to iNNvestigate neural networks predictions!. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/albermax/innvestigate) (👨‍💻 20 · 🔀 230 · 📥 79 · 📦 110 · 📋 260 - 20% open · ⏱️ 14.09.2023):

	```
	git clone https://github.com/albermax/innvestigate
	```
- [PyPi](https://pypi.org/project/innvestigate) (📥 710 / month):
	```
	pip install innvestigate
	```
</details>
<details><summary><b><a href="https://github.com/marcotcr/checklist">checklist</a></b> (🥉24 ·  ⭐ 1.9K) - Beyond Accuracy: Behavioral Testing of NLP models with CheckList. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/marcotcr/checklist) (👨‍💻 15 · 🔀 190 · 📦 280 · 📋 87 - 4% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/marcotcr/checklist
	```
- [PyPi](https://pypi.org/project/checklist) (📥 3.5K / month):
	```
	pip install checklist
	```
- [Conda](https://anaconda.org/conda-forge/checklist) (📥 6.4K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge checklist
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/DiCE">DiCE</a></b> (🥉24 ·  ⭐ 1.2K) - Generate Diverse Counterfactual Explanations for any machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/DiCE) (👨‍💻 19 · 🔀 160 · 📋 150 - 38% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/interpretml/DiCE
	```
- [PyPi](https://pypi.org/project/dice-ml) (📥 67K / month):
	```
	pip install dice-ml
	```
</details>
<details><summary><b><a href="https://github.com/philipperemy/keract">keract</a></b> (🥉24 ·  ⭐ 1K) - Layers Outputs and Gradients in Keras. Made easy. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/philipperemy/keract) (👨‍💻 16 · 🔀 180 · 📦 190 · 📋 88 - 2% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/philipperemy/keract
	```
- [PyPi](https://pypi.org/project/keract) (📥 4.5K / month):
	```
	pip install keract
	```
</details>
<details><summary><b><a href="https://github.com/DistrictDataLabs/yellowbrick">yellowbrick</a></b> (🥉23 ·  ⭐ 4.1K · 📉) - Visual analysis and diagnostic tools to facilitate.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/DistrictDataLabs/yellowbrick) (👨‍💻 110 · 🔀 530 · 📋 690 - 12% open · ⏱️ 05.07.2023):

	```
	git clone https://github.com/DistrictDataLabs/yellowbrick
	```
- [PyPi](https://pypi.org/project/yellowbrick) (📥 350K / month):
	```
	pip install yellowbrick
	```
- [Conda](https://anaconda.org/conda-forge/yellowbrick) (📥 70K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge yellowbrick
	```
</details>
<details><summary><b><a href="https://github.com/jalammar/ecco">ecco</a></b> (🥉21 ·  ⭐ 1.8K) - Explain, analyze, and visualize NLP language models. Ecco creates.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jalammar/ecco) (👨‍💻 11 · 🔀 140 · 📥 67 · 📦 26 · 📋 57 - 45% open · ⏱️ 10.08.2023):

	```
	git clone https://github.com/jalammar/ecco
	```
- [PyPi](https://pypi.org/project/ecco) (📥 500 / month):
	```
	pip install ecco
	```
- [Conda](https://anaconda.org/conda-forge/ecco) (📥 4K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge ecco
	```
</details>
<details><summary><b><a href="https://github.com/PAIR-code/what-if-tool">What-If Tool</a></b> (🥉21 ·  ⭐ 840) - Source code/webpage/demos for the What-If Tool. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PAIR-code/what-if-tool) (👨‍💻 20 · 🔀 150 · 📋 120 - 53% open · ⏱️ 27.04.2023):

	```
	git clone https://github.com/PAIR-code/what-if-tool
	```
- [PyPi](https://pypi.org/project/witwidget) (📥 4K / month):
	```
	pip install witwidget
	```
- [Conda](https://anaconda.org/conda-forge/tensorboard-plugin-wit) (📥 2.1M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tensorboard-plugin-wit
	```
- [npm](https://www.npmjs.com/package/wit-widget) (📥 860 / month):
	```
	npm install wit-widget
	```
</details>
<details><summary><b><a href="https://github.com/dssg/aequitas">aequitas</a></b> (🥉19 ·  ⭐ 570) - Bias and Fairness Audit Toolkit. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/dssg/aequitas) (👨‍💻 18 · 🔀 97 · 📦 140 · 📋 65 - 64% open · ⏱️ 20.08.2023):

	```
	git clone https://github.com/dssg/aequitas
	```
- [PyPi](https://pypi.org/project/aequitas) (📥 1.5K / month):
	```
	pip install aequitas
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-card-toolkit">model-card-toolkit</a></b> (🥉19 ·  ⭐ 390) - A toolkit that streamlines and automates the generation.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/tensorflow/model-card-toolkit) (👨‍💻 22 · 🔀 79 · 📥 8 · 📦 21 · 📋 29 - 20% open · ⏱️ 26.07.2023):

	```
	git clone https://github.com/tensorflow/model-card-toolkit
	```
- [PyPi](https://pypi.org/project/model-card-toolkit) (📥 1.4K / month):
	```
	pip install model-card-toolkit
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/fairness-indicators">fairness-indicators</a></b> (🥉19 ·  ⭐ 320) - Tensorflows Fairness Evaluation and Visualization.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/fairness-indicators) (👨‍💻 33 · 🔀 74 · 📋 15 - 40% open · ⏱️ 16.08.2023):

	```
	git clone https://github.com/tensorflow/fairness-indicators
	```
- [PyPi](https://pypi.org/project/fairness-indicators) (📥 3.6K / month):
	```
	pip install fairness-indicators
	```
</details>
<details><summary><b><a href="https://github.com/aerdem4/lofo-importance">LOFO</a></b> (🥉16 ·  ⭐ 770) - Leave One Feature Out Importance. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/aerdem4/lofo-importance) (👨‍💻 5 · 🔀 76 · 📦 27 · 📋 24 - 8% open · ⏱️ 14.04.2023):

	```
	git clone https://github.com/aerdem4/lofo-importance
	```
- [PyPi](https://pypi.org/project/lofo-importance) (📥 1.1K / month):
	```
	pip install lofo-importance
	```
</details>
<details><summary><b><a href="https://github.com/MisaOgura/flashtorch">FlashTorch</a></b> (🥉15 ·  ⭐ 710) - Visualization toolkit for neural networks in PyTorch! Demo --. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MisaOgura/flashtorch) (👨‍💻 2 · 🔀 88 · 📦 15 · 📋 31 - 29% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/MisaOgura/flashtorch
	```
- [PyPi](https://pypi.org/project/flashtorch) (📥 130 / month):
	```
	pip install flashtorch
	```
</details>
<details><summary><b><a href="https://github.com/interpretml/interpret-text">interpret-text</a></b> (🥉13 ·  ⭐ 380) - A library that incorporates state-of-the-art explainers for.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/interpretml/interpret-text) (👨‍💻 17 · 🔀 66 · 📋 56 - 69% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/interpretml/interpret-text
	```
- [PyPi](https://pypi.org/project/interpret-text) (📥 44 / month):
	```
	pip install interpret-text
	```
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/marcotcr/lime">Lime</a></b> (🥇33 ·  ⭐ 11K · 💀) - Lime: Explaining the predictions of any machine learning classifier. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/deepchecks/deepchecks">Deep Checks</a></b> (🥈28 ·  ⭐ 3.1K) - Deepchecks: Tests for Continuous Validation of ML Models &.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/reiinakano/scikit-plot">scikit-plot</a></b> (🥈28 ·  ⭐ 2.4K · 💀) - An intuitive library to add plotting functionality to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/lucid">Lucid</a></b> (🥉25 ·  ⭐ 4.6K · 💀) - A collection of infrastructure and tools for research in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/ModelOriented/DALEX">DALEX</a></b> (🥉24 ·  ⭐ 1.2K) - moDel Agnostic Language for Exploration and eXplanation. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/raghakot/keras-vis">keras-vis</a></b> (🥉23 ·  ⭐ 3K · 💀) - Neural network visualization toolkit for keras. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/eli5">eli5</a></b> (🥉22 ·  ⭐ 2.7K · 💀) - A library for debugging/inspecting machine learning classifiers and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/sicara/tf-explain">tf-explain</a></b> (🥉22 ·  ⭐ 1K · 💀) - Interpretability Methods for tf.keras models with Tensorflow.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/parrt/random-forest-importances">random-forest-importances</a></b> (🥉22 ·  ⭐ 570 · 💀) - Code to compute permutation and drop-column.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/kundajelab/deeplift">deeplift</a></b> (🥉20 ·  ⭐ 760 · 💀) - Public facing deeplift repo. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/andosa/treeinterpreter">TreeInterpreter</a></b> (🥉20 ·  ⭐ 730 · 💀) - Package for interpreting scikit-learns decision tree.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tensorflow/tcav">tcav</a></b> (🥉18 ·  ⭐ 590 · 💀) - Code for the TCAV ML interpretability project. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/EthicalML/xai">XAI</a></b> (🥉15 ·  ⭐ 940 · 💀) - XAI - An eXplainability toolbox for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/marcotcr/anchor">Anchor</a></b> (🥉15 ·  ⭐ 760 · 💀) - Code for High-Precision Model-Agnostic Explanations paper. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code>
- <b><a href="https://github.com/explainX/explainx">ExplainX.ai</a></b> (🥉14 ·  ⭐ 370 · 💀) - Explainable AI framework for data scientists. Explain & debug any.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/suinleelab/attributionpriors">Attribution Priors</a></b> (🥉11 ·  ⭐ 120 · 💀) - Tools for training explainable models using.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/SAP/contextual-ai">contextual-ai</a></b> (🥉11 ·  ⭐ 84 · 💀) - Contextual AI adds explainability to different stages of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/edublancas/sklearn-evaluation">sklearn-evaluation</a></b> (🥉10 ·  ⭐ 2 · 💤) - Machine learning model evaluation made easy: plots,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/intuit/bias-detector">bias-detector</a></b> (🥉9 ·  ⭐ 43 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## Vector Similarity Search (ANN)

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for Approximate Nearest Neighbor Search and Vector Indexing/Similarity Search._

🔗&nbsp;<b><a href="https://github.com/erikbern/ann-benchmarks">ANN Benchmarks</a></b> ( ⭐ 4.1K)  - Benchmarks of approximate nearest neighbor libraries in Python.

<details><summary><b><a href="https://github.com/milvus-io/milvus">Milvus</a></b> (🥇38 ·  ⭐ 23K) - A cloud-native vector database, storage for next generation AI.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/milvus-io/milvus) (👨‍💻 260 · 🔀 2.3K · 📥 46K · 📋 9.1K - 5% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/milvus-io/milvus
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 450K / month):
	```
	pip install pymilvus
	```
- [Docker Hub](https://hub.docker.com/r/milvusdb/milvus) (📥 6.3M · ⭐ 37 · ⏱️ 12.10.2023):
	```
	docker pull milvusdb/milvus
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/faiss">Faiss</a></b> (🥇37 ·  ⭐ 25K) - A library for efficient similarity search and clustering of dense vectors. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/faiss) (👨‍💻 140 · 🔀 3.1K · 📦 3.2K · 📋 2.2K - 16% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/facebookresearch/faiss
	```
- [PyPi](https://pypi.org/project/pymilvus) (📥 450K / month):
	```
	pip install pymilvus
	```
- [Conda](https://anaconda.org/conda-forge/faiss) (📥 930K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge faiss
	```
</details>
<details><summary><b><a href="https://github.com/spotify/annoy">Annoy</a></b> (🥈34 ·  ⭐ 12K) - Approximate Nearest Neighbors in C++/Python optimized for memory usage.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/spotify/annoy) (👨‍💻 88 · 🔀 1.1K · 📦 3.2K · 📋 390 - 12% open · ⏱️ 20.08.2023):

	```
	git clone https://github.com/spotify/annoy
	```
- [PyPi](https://pypi.org/project/annoy) (📥 970K / month):
	```
	pip install annoy
	```
- [Conda](https://anaconda.org/conda-forge/python-annoy) (📥 360K · ⏱️ 25.09.2023):
	```
	conda install -c conda-forge python-annoy
	```
</details>
<details><summary><b><a href="https://github.com/nmslib/hnswlib">hnswlib</a></b> (🥈31 ·  ⭐ 3.5K · 💤) - Header-only C++/python library for fast approximate nearest.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/nmslib/hnswlib) (👨‍💻 65 · 🔀 500 · 📦 5.1K · 📋 310 - 52% open · ⏱️ 05.02.2023):

	```
	git clone https://github.com/nmslib/hnswlib
	```
- [PyPi](https://pypi.org/project/hnswlib) (📥 710K / month):
	```
	pip install hnswlib
	```
- [Conda](https://anaconda.org/conda-forge/hnswlib) (📥 110K · ⏱️ 27.09.2023):
	```
	conda install -c conda-forge hnswlib
	```
</details>
<details><summary><b><a href="https://github.com/lmcinnes/pynndescent">PyNNDescent</a></b> (🥉29 ·  ⭐ 800) - A Python nearest neighbor descent for approximate nearest neighbors. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/lmcinnes/pynndescent) (👨‍💻 26 · 🔀 97 · 📦 4.5K · 📋 120 - 51% open · ⏱️ 12.09.2023):

	```
	git clone https://github.com/lmcinnes/pynndescent
	```
- [PyPi](https://pypi.org/project/pynndescent) (📥 940K / month):
	```
	pip install pynndescent
	```
- [Conda](https://anaconda.org/conda-forge/pynndescent) (📥 1.7M · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pynndescent
	```
</details>
<details><summary><b><a href="https://github.com/yahoojapan/NGT">NGT</a></b> (🥉22 ·  ⭐ 1.1K) - Nearest Neighbor Search with Neighborhood Graph and Tree for High-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/yahoojapan/NGT) (👨‍💻 14 · 🔀 100 · 📋 120 - 12% open · ⏱️ 31.08.2023):

	```
	git clone https://github.com/yahoojapan/NGT
	```
- [PyPi](https://pypi.org/project/ngt) (📥 6.5K / month):
	```
	pip install ngt
	```
</details>
<details><summary><b><a href="https://github.com/pixelogik/NearPy">NearPy</a></b> (🥉19 ·  ⭐ 750 · 💤) - Python framework for fast (approximated) nearest neighbour search in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pixelogik/NearPy) (👨‍💻 19 · 🔀 140 · 📦 90 · 📋 64 - 39% open · ⏱️ 22.01.2023):

	```
	git clone https://github.com/pixelogik/NearPy
	```
- [PyPi](https://pypi.org/project/NearPy) (📥 670 / month):
	```
	pip install NearPy
	```
</details>
<details><summary><b><a href="https://github.com/kakao/n2">N2</a></b> (🥉19 ·  ⭐ 550) - TOROS N2 - lightweight approximate Nearest Neighbor library which runs fast.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/kakao/n2) (👨‍💻 20 · 🔀 70 · 📦 28 · 📋 35 - 37% open · ⏱️ 27.06.2023):

	```
	git clone https://github.com/kakao/n2
	```
- [PyPi](https://pypi.org/project/n2) (📥 970 / month):
	```
	pip install n2
	```
</details>
<details><summary>Show 3 hidden projects...</summary>

- <b><a href="https://github.com/nmslib/nmslib">NMSLIB</a></b> (🥈31 ·  ⭐ 3.2K · 💀) - Non-Metric Space Library (NMSLIB): An efficient similarity search.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/plasticityai/magnitude">Magnitude</a></b> (🥉24 ·  ⭐ 1.6K · 💀) - A fast, efficient universal vector embedding utility package. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/facebookresearch/pysparnn">PySparNN</a></b> (🥉11 ·  ⭐ 910 · 💀) - Approximate Nearest Neighbor Search for Sparse Data in Python!. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
</details>
<br>

## Probabilistics & Statistics

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries providing capabilities for probabilistic programming/reasoning, bayesian inference, gaussian processes, or statistics._

<details><summary><b><a href="https://github.com/pyro-ppl/pyro">Pyro</a></b> (🥇36 ·  ⭐ 8.2K) - Deep universal probabilistic programming with Python and PyTorch. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pyro-ppl/pyro) (👨‍💻 140 · 🔀 940 · 📦 1.6K · 📋 1K - 20% open · ⏱️ 07.10.2023):

	```
	git clone https://github.com/pyro-ppl/pyro
	```
- [PyPi](https://pypi.org/project/pyro-ppl) (📥 580K / month):
	```
	pip install pyro-ppl
	```
- [Conda](https://anaconda.org/conda-forge/pyro-ppl) (📥 110K · ⏱️ 29.07.2023):
	```
	conda install -c conda-forge pyro-ppl
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/probability">tensorflow-probability</a></b> (🥇33 ·  ⭐ 4K) - Probabilistic reasoning and statistical analysis in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/probability) (👨‍💻 480 · 🔀 1K · 📋 1.3K - 43% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/tensorflow/probability
	```
- [PyPi](https://pypi.org/project/tensorflow-probability) (📥 1.3M / month):
	```
	pip install tensorflow-probability
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-probability) (📥 110K · ⏱️ 23.07.2023):
	```
	conda install -c conda-forge tensorflow-probability
	```
</details>
<details><summary><b><a href="https://github.com/cornellius-gp/gpytorch">GPyTorch</a></b> (🥈32 ·  ⭐ 3.2K) - A highly efficient implementation of Gaussian Processes in PyTorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cornellius-gp/gpytorch) (👨‍💻 120 · 🔀 490 · 📦 1.6K · 📋 1.3K - 23% open · ⏱️ 20.09.2023):

	```
	git clone https://github.com/cornellius-gp/gpytorch
	```
- [PyPi](https://pypi.org/project/gpytorch) (📥 230K / month):
	```
	pip install gpytorch
	```
- [Conda](https://anaconda.org/conda-forge/gpytorch) (📥 130K · ⏱️ 11.08.2023):
	```
	conda install -c conda-forge gpytorch
	```
</details>
<details><summary><b><a href="https://github.com/pgmpy/pgmpy">pgmpy</a></b> (🥈31 ·  ⭐ 2.5K) - Python Library for learning (Structure and Parameter), inference.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pgmpy/pgmpy) (👨‍💻 120 · 🔀 660 · 📥 290 · 📦 730 · 📋 820 - 26% open · ⏱️ 21.09.2023):

	```
	git clone https://github.com/pgmpy/pgmpy
	```
- [PyPi](https://pypi.org/project/pgmpy) (📥 49K / month):
	```
	pip install pgmpy
	```
</details>
<details><summary><b><a href="https://github.com/jmschrei/pomegranate">pomegranate</a></b> (🥈30 ·  ⭐ 3.2K) - Fast, flexible and easy to use probabilistic modelling in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/jmschrei/pomegranate) (👨‍💻 71 · 🔀 560 · 📦 990 · 📋 730 - 3% open · ⏱️ 26.08.2023):

	```
	git clone https://github.com/jmschrei/pomegranate
	```
- [PyPi](https://pypi.org/project/pomegranate) (📥 22K / month):
	```
	pip install pomegranate
	```
- [Conda](https://anaconda.org/conda-forge/pomegranate) (📥 140K · ⏱️ 07.09.2023):
	```
	conda install -c conda-forge pomegranate
	```
</details>
<details><summary><b><a href="https://github.com/GPflow/GPflow">GPflow</a></b> (🥈30 ·  ⭐ 1.8K) - Gaussian processes in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/GPflow/GPflow) (👨‍💻 83 · 🔀 420 · 📦 570 · 📋 800 - 15% open · ⏱️ 09.08.2023):

	```
	git clone https://github.com/GPflow/GPflow
	```
- [PyPi](https://pypi.org/project/gpflow) (📥 46K / month):
	```
	pip install gpflow
	```
- [Conda](https://anaconda.org/conda-forge/gpflow) (📥 24K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge gpflow
	```
</details>
<details><summary><b><a href="https://github.com/SALib/SALib">SALib</a></b> (🥈30 ·  ⭐ 750) - Sensitivity Analysis Library in Python. Contains Sobol, Morris, FAST, and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/SALib/SALib) (👨‍💻 43 · 🔀 210 · 📦 910 · 📋 310 - 13% open · ⏱️ 09.10.2023):

	```
	git clone https://github.com/SALib/SALib
	```
- [PyPi](https://pypi.org/project/salib) (📥 100K / month):
	```
	pip install salib
	```
- [Conda](https://anaconda.org/conda-forge/salib) (📥 140K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge salib
	```
</details>
<details><summary><b><a href="https://github.com/hmmlearn/hmmlearn">hmmlearn</a></b> (🥉28 ·  ⭐ 2.8K) - Hidden Markov Models in Python, with scikit-learn like API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/hmmlearn/hmmlearn) (👨‍💻 45 · 🔀 700 · 📦 2.1K · 📋 420 - 13% open · ⏱️ 31.08.2023):

	```
	git clone https://github.com/hmmlearn/hmmlearn
	```
- [PyPi](https://pypi.org/project/hmmlearn) (📥 160K / month):
	```
	pip install hmmlearn
	```
- [Conda](https://anaconda.org/conda-forge/hmmlearn) (📥 200K · ⏱️ 07.10.2023):
	```
	conda install -c conda-forge hmmlearn
	```
</details>
<details><summary><b><a href="https://github.com/bambinos/bambi">bambi</a></b> (🥉27 ·  ⭐ 940) - BAyesian Model-Building Interface (Bambi) in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/bambinos/bambi) (👨‍💻 35 · 🔀 110 · 📦 89 · 📋 360 - 18% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/bambinos/bambi
	```
- [PyPi](https://pypi.org/project/bambi) (📥 17K / month):
	```
	pip install bambi
	```
- [Conda](https://anaconda.org/conda-forge/bambi) (📥 26K · ⏱️ 02.07.2023):
	```
	conda install -c conda-forge bambi
	```
</details>
<details><summary><b><a href="https://github.com/baal-org/baal">Baal</a></b> (🥉25 ·  ⭐ 790) - Library to enable Bayesian active learning in your research or labeling.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/baal-org/baal) (👨‍💻 21 · 🔀 79 · 📦 52 · 📋 100 - 21% open · ⏱️ 02.10.2023):

	```
	git clone https://github.com/ElementAI/baal
	```
- [PyPi](https://pypi.org/project/baal) (📥 1.9K / month):
	```
	pip install baal
	```
- [Conda](https://anaconda.org/conda-forge/baal) (📥 7.1K · ⏱️ 12.06.2023):
	```
	conda install -c conda-forge baal
	```
</details>
<details><summary>Show 12 hidden projects...</summary>

- <b><a href="https://github.com/pymc-devs/pymc">PyMC3</a></b> (🥇38 ·  ⭐ 7.8K) - Bayesian Modeling in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/twopirllc/pandas-ta">pandas-ta</a></b> (🥈30 ·  ⭐ 4.1K · 💀) - Technical Analysis Indicators - Pandas TA is an easy to use.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/rlabbe/filterpy">filterpy</a></b> (🥈30 ·  ⭐ 2.9K · 💀) - Python Kalman filtering and optimal estimation library. Implements.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/raphaelvallat/pingouin">pingouin</a></b> (🥉29 ·  ⭐ 1.4K) - Statistical package in Python based on Pandas. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/pydata/patsy">patsy</a></b> (🥉28 ·  ⭐ 900 · 💤) - Describing statistical models in Python using symbolic formulas. <code>❗Unlicensed</code>
- <b><a href="https://github.com/blei-lab/edward">Edward</a></b> (🥉26 ·  ⭐ 4.8K · 💀) - A probabilistic programming language in TensorFlow. Deep.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/uber/orbit">Orbit</a></b> (🥉21 ·  ⭐ 1.7K) - A Python package for Bayesian forecasting with object-oriented.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/pyro-ppl/funsor">Funsor</a></b> (🥉21 ·  ⭐ 220) - Functional tensors for probabilistic programming. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stan-dev/pystan">PyStan</a></b> (🥉20 ·  ⭐ 280) - PyStan, a Python interface to Stan, a platform for statistical modeling... <code><a href="http://bit.ly/3hkKRql">ISC</a></code>
- <b><a href="https://github.com/maximtrp/scikit-posthocs">scikit-posthocs</a></b> (🥉19 ·  ⭐ 300) - Multiple Pairwise Comparisons (Post Hoc) Tests in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mattjj/pyhsmm">pyhsmm</a></b> (🥉17 ·  ⭐ 540 · 💀) -  <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/thu-ml/zhusuan">ZhuSuan</a></b> (🥉15 ·  ⭐ 2.2K · 💀) - A probabilistic programming library for Bayesian deep learning,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Adversarial Robustness

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for testing the robustness of machine learning models against attacks with adversarial/malicious examples._

<details><summary><b><a href="https://github.com/Trusted-AI/adversarial-robustness-toolbox">ART</a></b> (🥇34 ·  ⭐ 4K) - Adversarial Robustness Toolbox (ART) - Python Library for Machine Learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/Trusted-AI/adversarial-robustness-toolbox) (👨‍💻 130 · 🔀 1K · 📦 430 · 📋 840 - 12% open · ⏱️ 22.09.2023):

	```
	git clone https://github.com/Trusted-AI/adversarial-robustness-toolbox
	```
- [PyPi](https://pypi.org/project/adversarial-robustness-toolbox) (📥 28K / month):
	```
	pip install adversarial-robustness-toolbox
	```
- [Conda](https://anaconda.org/conda-forge/adversarial-robustness-toolbox) (📥 33K · ⏱️ 22.09.2023):
	```
	conda install -c conda-forge adversarial-robustness-toolbox
	```
</details>
<details><summary><b><a href="https://github.com/QData/TextAttack">TextAttack</a></b> (🥈30 ·  ⭐ 2.5K) - TextAttack is a Python framework for adversarial attacks, data.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/QData/TextAttack) (👨‍💻 60 · 🔀 330 · 📦 200 · 📋 260 - 16% open · ⏱️ 30.09.2023):

	```
	git clone https://github.com/QData/TextAttack
	```
- [PyPi](https://pypi.org/project/textattack) (📥 5.8K / month):
	```
	pip install textattack
	```
- [Conda](https://anaconda.org/conda-forge/textattack) (📥 6.7K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge textattack
	```
</details>
<details><summary><b><a href="https://github.com/cleverhans-lab/cleverhans">CleverHans</a></b> (🥈29 ·  ⭐ 5.9K · 💤) - An adversarial example library for constructing attacks,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/cleverhans-lab/cleverhans) (👨‍💻 130 · 🔀 1.3K · 📦 530 · 📋 450 - 5% open · ⏱️ 31.01.2023):

	```
	git clone https://github.com/cleverhans-lab/cleverhans
	```
- [PyPi](https://pypi.org/project/cleverhans) (📥 1.1K / month):
	```
	pip install cleverhans
	```
- [Conda](https://anaconda.org/conda-forge/cleverhans) (📥 7.1K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge cleverhans
	```
</details>
<details><summary>Show 6 hidden projects...</summary>

- <b><a href="https://github.com/bethgelab/foolbox">Foolbox</a></b> (🥈27 ·  ⭐ 2.6K · 💀) - A Python toolbox to create adversarial examples that fool neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/BorealisAI/advertorch">advertorch</a></b> (🥉21 ·  ⭐ 1.2K · 💀) - A Toolbox for Adversarial Robustness Research. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/MadryLab/robustness">robustness</a></b> (🥉18 ·  ⭐ 840 · 💀) - A library for experimenting with, training and evaluating neural.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/textflint/textflint">textflint</a></b> (🥉17 ·  ⭐ 620 · 💀) - Unified Multilingual Robustness Evaluation Toolkit for.. <code><a href="http://bit.ly/2M0xdwT">❗️GPL-3.0</a></code>
- <b><a href="https://github.com/advboxes/AdvBox">AdvBox</a></b> (🥉16 ·  ⭐ 1.3K · 💀) - Advbox is a toolbox to generate adversarial examples that fool.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/airbnb/artificial-adversary">Adversary</a></b> (🥉13 ·  ⭐ 380 · 💀) - Tool to generate adversarial text examples and test machine.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>
<br>

## GPU Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that require and make use of CUDA/GPU system capabilities to optimize data handling and machine learning tasks._

<details><summary><b><a href="https://github.com/rapidsai/cudf">cuDF</a></b> (🥇33 ·  ⭐ 6K) - cuDF - GPU DataFrame Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cudf) (👨‍💻 260 · 🔀 720 · 📦 46 · 📋 5.7K - 14% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/rapidsai/cudf
	```
- [PyPi](https://pypi.org/project/cudf) (📥 1.6K / month):
	```
	pip install cudf
	```
</details>
<details><summary><b><a href="https://github.com/wookayin/gpustat">gpustat</a></b> (🥇31 ·  ⭐ 3.6K) - A simple command-line utility for querying and monitoring GPU status. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wookayin/gpustat) (👨‍💻 17 · 🔀 240 · 📦 4.1K · 📋 110 - 22% open · ⏱️ 22.08.2023):

	```
	git clone https://github.com/wookayin/gpustat
	```
- [PyPi](https://pypi.org/project/gpustat) (📥 1.2M / month):
	```
	pip install gpustat
	```
- [Conda](https://anaconda.org/conda-forge/gpustat) (📥 260K · ⏱️ 23.08.2023):
	```
	conda install -c conda-forge gpustat
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/apex">Apex</a></b> (🥈30 ·  ⭐ 7.6K) - A PyTorch Extension: Tools for easy mixed precision and distributed.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/NVIDIA/apex) (👨‍💻 120 · 🔀 1.2K · 📦 2K · 📋 1.1K - 54% open · ⏱️ 03.10.2023):

	```
	git clone https://github.com/NVIDIA/apex
	```
- [Conda](https://anaconda.org/conda-forge/nvidia-apex) (📥 170K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge nvidia-apex
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cuml">cuML</a></b> (🥈29 ·  ⭐ 3.6K) - cuML - RAPIDS Machine Learning Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cuml) (👨‍💻 170 · 🔀 470 · 📋 2.3K - 33% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/rapidsai/cuml
	```
- [PyPi](https://pypi.org/project/cuml) (📥 1.6K / month):
	```
	pip install cuml
	```
</details>
<details><summary><b><a href="https://github.com/arrayfire/arrayfire">ArrayFire</a></b> (🥈27 ·  ⭐ 4.2K) - ArrayFire: a general purpose GPU library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/arrayfire/arrayfire) (👨‍💻 88 · 🔀 510 · 📥 4.6K · 📋 1.6K - 18% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/arrayfire/arrayfire
	```
- [PyPi](https://pypi.org/project/arrayfire) (📥 960 / month):
	```
	pip install arrayfire
	```
</details>
<details><summary><b><a href="https://github.com/rapidsai/cugraph">cuGraph</a></b> (🥈26 ·  ⭐ 1.4K) - cuGraph - RAPIDS Graph Analytics Library. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/rapidsai/cugraph) (👨‍💻 100 · 🔀 250 · 📦 2 · 📋 1.6K - 15% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/rapidsai/cugraph
	```
- [PyPi](https://pypi.org/project/cugraph) (📥 130 / month):
	```
	pip install cugraph
	```
- [Conda](https://anaconda.org/conda-forge/libcugraph) (📥 17K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge libcugraph
	```
</details>
<details><summary><b><a href="https://github.com/NVIDIA/DALI">DALI</a></b> (🥉25 ·  ⭐ 4.6K) - A GPU-accelerated library containing highly optimized building blocks.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/NVIDIA/DALI) (👨‍💻 87 · 🔀 570 · 📋 1.5K - 16% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/NVIDIA/DALI
	```
</details>
<details><summary><b><a href="https://github.com/KomputeProject/kompute">Vulkan Kompute</a></b> (🥉21 ·  ⭐ 1.3K) - General purpose GPU compute framework built on Vulkan to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/KomputeProject/kompute) (👨‍💻 22 · 🔀 92 · 📥 470 · 📦 7 · 📋 190 - 33% open · ⏱️ 12.08.2023):

	```
	git clone https://github.com/KomputeProject/kompute
	```
- [PyPi](https://pypi.org/project/kp) (📥 170 / month):
	```
	pip install kp
	```
</details>
<details><summary>Show 9 hidden projects...</summary>

- <b><a href="https://github.com/inducer/pycuda">PyCUDA</a></b> (🥈28 ·  ⭐ 1.6K) - CUDA integration for Python, plus shiny features. <code>❗Unlicensed</code>
- <b><a href="https://github.com/anderskm/gputil">GPUtil</a></b> (🥉23 ·  ⭐ 1K · 💀) - A Python module for getting the GPU status from NVIDA GPUs using nvidia-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/fbcotter/py3nvml">py3nvml</a></b> (🥉23 ·  ⭐ 220 · 💀) - Python 3 Bindings for NVML library. Get NVIDIA GPU status inside.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/lebedov/scikit-cuda">scikit-cuda</a></b> (🥉22 ·  ⭐ 940 · 💀) - Python interface to GPU-powered libraries. <code>❗Unlicensed</code>
- <b><a href="https://github.com/BlazingDB/blazingsql">BlazingSQL</a></b> (🥉20 ·  ⭐ 1.9K · 💀) - BlazingSQL is a lightweight, GPU accelerated, SQL engine for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/rapidsai/cusignal">cuSignal</a></b> (🥉16 ·  ⭐ 700) - GPU accelerated signal processing. <code>❗Unlicensed</code>
- <b><a href="https://github.com/nicolargo/nvidia-ml-py3">nvidia-ml-py3</a></b> (🥉14 ·  ⭐ 120 · 💀) - Python 3 Bindings for the NVIDIA Management Library. <code>❗Unlicensed</code>
- <b><a href="https://github.com/Santosh-Gupta/SpeedTorch">SpeedTorch</a></b> (🥉12 ·  ⭐ 670 · 💀) - Library for faster pinned CPU - GPU transfer in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/stas00/ipyexperiments">ipyexperiments</a></b> (🥉10 ·  ⭐ 160 · 💀) - jupyter/ipython experiment containers for GPU and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1E" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Tensorflow Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend TensorFlow with additional capabilities._

<details><summary><b><a href="https://github.com/tensorflow/datasets">TensorFlow Datasets</a></b> (🥇38 ·  ⭐ 4K) - TFDS is a collection of datasets ready to use with.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/datasets) (👨‍💻 300 · 🔀 1.4K · 📦 15K · 📋 1.1K - 36% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/tensorflow/datasets
	```
- [PyPi](https://pypi.org/project/tensorflow-datasets) (📥 1.9M / month):
	```
	pip install tensorflow-datasets
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-datasets) (📥 24K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge tensorflow-datasets
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/addons">TF Addons</a></b> (🥇34 ·  ⭐ 1.7K) - Useful extra functionality for TensorFlow 2.x maintained by.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/addons) (👨‍💻 200 · 🔀 550 · 📦 13K · 📋 970 - 7% open · ⏱️ 12.09.2023):

	```
	git clone https://github.com/tensorflow/addons
	```
- [PyPi](https://pypi.org/project/tensorflow-addons) (📥 840K / month):
	```
	pip install tensorflow-addons
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/tensor2tensor">tensor2tensor</a></b> (🥈32 ·  ⭐ 14K) - Library of deep learning models and datasets designed to.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/tensor2tensor) (👨‍💻 240 · 🔀 3.3K · 📦 1.4K · 📋 1.2K - 46% open · ⏱️ 01.04.2023):

	```
	git clone https://github.com/tensorflow/tensor2tensor
	```
- [PyPi](https://pypi.org/project/tensor2tensor) (📥 4.8K / month):
	```
	pip install tensor2tensor
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/model-optimization">TF Model Optimization</a></b> (🥈32 ·  ⭐ 1.4K) - A toolkit to optimize ML models for deployment for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/model-optimization) (👨‍💻 82 · 🔀 310 · 📦 3.2K · 📋 330 - 51% open · ⏱️ 14.09.2023):

	```
	git clone https://github.com/tensorflow/model-optimization
	```
- [PyPi](https://pypi.org/project/tensorflow-model-optimization) (📥 460K / month):
	```
	pip install tensorflow-model-optimization
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/transform">TensorFlow Transform</a></b> (🥈32 ·  ⭐ 970) - Input pipeline framework. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/transform) (👨‍💻 27 · 🔀 190 · 📦 1.5K · 📋 200 - 15% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/tensorflow/transform
	```
- [PyPi](https://pypi.org/project/tensorflow-transform) (📥 810K / month):
	```
	pip install tensorflow-transform
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/hub">tensorflow-hub</a></b> (🥈30 ·  ⭐ 3.4K) - A library for transfer learning by reusing parts of.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/hub) (👨‍💻 110 · 🔀 1.7K · 📋 680 - 0% open · ⏱️ 06.10.2023):

	```
	git clone https://github.com/tensorflow/hub
	```
- [PyPi](https://pypi.org/project/tensorflow-hub) (📥 2.4M / month):
	```
	pip install tensorflow-hub
	```
- [Conda](https://anaconda.org/conda-forge/tensorflow-hub) (📥 90K · ⏱️ 13.07.2023):
	```
	conda install -c conda-forge tensorflow-hub
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/io">TensorFlow I/O</a></b> (🥉28 ·  ⭐ 670) - Dataset, streaming, and file system extensions.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/io) (👨‍💻 110 · 🔀 250 · 📋 610 - 40% open · ⏱️ 07.10.2023):

	```
	git clone https://github.com/tensorflow/io
	```
- [PyPi](https://pypi.org/project/tensorflow-io) (📥 3.1M / month):
	```
	pip install tensorflow-io
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/cloud">TensorFlow Cloud</a></b> (🥉26 ·  ⭐ 360 · 💤) - The TensorFlow Cloud repository provides APIs that.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/cloud) (👨‍💻 27 · 🔀 80 · 📦 300 · 📋 87 - 68% open · ⏱️ 22.12.2022):

	```
	git clone https://github.com/tensorflow/cloud
	```
- [PyPi](https://pypi.org/project/tensorflow-cloud) (📥 70K / month):
	```
	pip install tensorflow-cloud
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/neural-structured-learning">Neural Structured Learning</a></b> (🥉25 ·  ⭐ 970) - Training neural models with structured signals. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/neural-structured-learning) (👨‍💻 38 · 🔀 180 · 📦 380 · ⏱️ 20.09.2023):

	```
	git clone https://github.com/tensorflow/neural-structured-learning
	```
- [PyPi](https://pypi.org/project/neural-structured-learning) (📥 14K / month):
	```
	pip install neural-structured-learning
	```
</details>
<details><summary><b><a href="https://github.com/tensorflow/compression">TF Compression</a></b> (🥉22 ·  ⭐ 780) - Data compression in TensorFlow. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tensorflow/compression) (👨‍💻 21 · 🔀 240 · 📋 98 - 7% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/tensorflow/compression
	```
- [PyPi](https://pypi.org/project/tensorflow-compression) (📥 6.7K / month):
	```
	pip install tensorflow-compression
	```
</details>
<details><summary>Show 5 hidden projects...</summary>

- <b><a href="https://github.com/qubvel/efficientnet">efficientnet</a></b> (🥉25 ·  ⭐ 2K · 💀) - Implementation of EfficientNet model. Keras and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/keras-team/keras-preprocessing">Keras-Preprocessing</a></b> (🥉22 ·  ⭐ 1K · 💀) - Utilities for working with image data, text data, and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/taehoonlee/tensornets">TensorNets</a></b> (🥉20 ·  ⭐ 1K · 💀) - High level network definitions with pre-trained weights in.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/PAIR-code/saliency">Saliency</a></b> (🥉19 ·  ⭐ 900 · 💀) - Framework-agnostic implementation for state-of-the-art.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/geffy/tffm">tffm</a></b> (🥉16 ·  ⭐ 780 · 💀) - TensorFlow implementation of an arbitrary order Factorization Machine. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Jax Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Jax with additional capabilities._

<details><summary><b><a href="https://github.com/patrick-kidger/equinox">equinox</a></b> (🥇29 ·  ⭐ 1.4K) - Elegant easy-to-use neural networks + scientific computing in.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/patrick-kidger/equinox) (👨‍💻 39 · 🔀 89 · 📦 250 · 📋 240 - 25% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/patrick-kidger/equinox
	```
- [PyPi](https://pypi.org/project/equinox) (📥 21K / month):
	```
	pip install equinox
	```
</details>
<details><summary>Show 1 hidden projects...</summary>

- <b><a href="https://github.com/ucl-bug/jaxdf">jaxdf</a></b> (🥉13 ·  ⭐ 98) - A JAX-based research framework for writing differentiable.. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://jax.readthedocs.io/en/latest/_static/favicon.png" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Sklearn Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend scikit-learn with additional capabilities._

<details><summary><b><a href="https://github.com/scikit-learn-contrib/imbalanced-learn">imbalanced-learn</a></b> (🥇36 ·  ⭐ 6.5K) - A Python Package to Tackle the Curse of Imbalanced.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/imbalanced-learn) (👨‍💻 80 · 🔀 1.2K · 📦 21K · 📋 560 - 4% open · ⏱️ 07.09.2023):

	```
	git clone https://github.com/scikit-learn-contrib/imbalanced-learn
	```
- [PyPi](https://pypi.org/project/imbalanced-learn) (📥 5M / month):
	```
	pip install imbalanced-learn
	```
- [Conda](https://anaconda.org/conda-forge/imbalanced-learn) (📥 480K · ⏱️ 08.07.2023):
	```
	conda install -c conda-forge imbalanced-learn
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/category_encoders">category_encoders</a></b> (🥇33 ·  ⭐ 2.3K) - A library of sklearn compatible categorical variable.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/category_encoders) (👨‍💻 64 · 🔀 380 · 📦 1.1K · 📋 280 - 15% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/scikit-learn-contrib/category_encoders
	```
- [PyPi](https://pypi.org/project/category_encoders) (📥 1.2M / month):
	```
	pip install category_encoders
	```
- [Conda](https://anaconda.org/conda-forge/category_encoders) (📥 240K · ⏱️ 15.08.2023):
	```
	conda install -c conda-forge category_encoders
	```
</details>
<details><summary><b><a href="https://github.com/scikit-multilearn/scikit-multilearn">scikit-multilearn</a></b> (🥈28 ·  ⭐ 870) - A scikit-learn based module for multi-label et. al... <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-multilearn/scikit-multilearn) (👨‍💻 28 · 🔀 170 · 📦 1.3K · 📋 200 - 38% open · ⏱️ 19.04.2023):

	```
	git clone https://github.com/scikit-multilearn/scikit-multilearn
	```
- [PyPi](https://pypi.org/project/scikit-multilearn) (📥 81K / month):
	```
	pip install scikit-multilearn
	```
</details>
<details><summary><b><a href="https://github.com/koaning/scikit-lego">scikit-lego</a></b> (🥈27 ·  ⭐ 1.1K) - Extra blocks for scikit-learn pipelines. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/koaning/scikit-lego) (👨‍💻 60 · 🔀 100 · 📦 120 · 📋 280 - 10% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/koaning/scikit-lego
	```
- [PyPi](https://pypi.org/project/scikit-lego) (📥 36K / month):
	```
	pip install scikit-lego
	```
- [Conda](https://anaconda.org/conda-forge/scikit-lego) (📥 43K · ⏱️ 19.07.2023):
	```
	conda install -c conda-forge scikit-lego
	```
</details>
<details><summary><b><a href="https://github.com/guofei9987/scikit-opt">scikit-opt</a></b> (🥉23 ·  ⭐ 4.5K · 💤) - Genetic Algorithm, Particle Swarm Optimization, Simulated.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/guofei9987/scikit-opt) (👨‍💻 17 · 🔀 900 · 📦 150 · 📋 170 - 36% open · ⏱️ 19.02.2023):

	```
	git clone https://github.com/guofei9987/scikit-opt
	```
- [PyPi](https://pypi.org/project/scikit-opt) (📥 3.5K / month):
	```
	pip install scikit-opt
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/combo">combo</a></b> (🥉19 ·  ⭐ 630 · 💤) - (AAAI 20) A Python Toolbox for Machine Learning Model.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code>xgboost</code></summary>

- [GitHub](https://github.com/yzhao062/combo) (👨‍💻 2 · 🔀 100 · 📦 580 · 📋 16 - 81% open · ⏱️ 14.01.2023):

	```
	git clone https://github.com/yzhao062/combo
	```
- [PyPi](https://pypi.org/project/combo) (📥 47K / month):
	```
	pip install combo
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/DESlib">DESlib</a></b> (🥉14 ·  ⭐ 440) - A Python library for dynamic classifier and ensemble selection. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/DESlib) (👨‍💻 16 · 🔀 73 · 📋 150 - 9% open · ⏱️ 18.06.2023):

	```
	git clone https://github.com/scikit-learn-contrib/DESlib
	```
- [PyPi](https://pypi.org/project/deslib) (📥 820 / month):
	```
	pip install deslib
	```
</details>
<details><summary>Show 10 hidden projects...</summary>

- <b><a href="https://github.com/rasbt/mlxtend">MLxtend</a></b> (🥈32 ·  ⭐ 4.5K) - A library of extension and helper modules for Pythons data.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/iskandr/fancyimpute">fancyimpute</a></b> (🥈26 ·  ⭐ 1.2K · 💀) - Multivariate imputation and matrix completion.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TeamHG-Memex/sklearn-crfsuite">sklearn-crfsuite</a></b> (🥈24 ·  ⭐ 420 · 💀) - scikit-learn inspired API for CRFsuite. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/trent-b/iterative-stratification">iterative-stratification</a></b> (🥉22 ·  ⭐ 800 · 💀) - scikit-learn cross validators for iterative.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/lightning">sklearn-contrib-lightning</a></b> (🥉20 ·  ⭐ 1.7K · 💀) - Large-scale linear classification, regression and.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-learn-contrib/skope-rules">skope-rules</a></b> (🥉19 ·  ⭐ 560 · 💤) - machine learning with logical rules in Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/mathurinm/celer">celer</a></b> (🥉18 ·  ⭐ 180) - Fast solver for L1-type problems: Lasso, sparse Logisitic regression,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/skggm/skggm">skggm</a></b> (🥉17 ·  ⭐ 230) - Scikit-learn compatible estimation of general graphical models. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/scikit-tda/scikit-tda">scikit-tda</a></b> (🥉16 ·  ⭐ 450 · 💀) - Topological Data Analysis for Python. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/amueller/dabl">dabl</a></b> (🥉12 ·  ⭐ 120 · 💤) - Data Analysis Baseline Library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Pytorch Utilities

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries that extend Pytorch with additional capabilities._

<details><summary><b><a href="https://github.com/huggingface/accelerate">accelerate</a></b> (🥇38 ·  ⭐ 5.8K) - A simple way to train and use PyTorch models with multi-.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/huggingface/accelerate) (👨‍💻 180 · 🔀 610 · 📦 15K · 📋 1K - 10% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/huggingface/accelerate
	```
- [PyPi](https://pypi.org/project/accelerate) (📥 7.2M / month):
	```
	pip install accelerate
	```
- [Conda](https://anaconda.org/conda-forge/accelerate) (📥 73K · ⏱️ 15.09.2023):
	```
	conda install -c conda-forge accelerate
	```
</details>
<details><summary><b><a href="https://github.com/KevinMusgrave/pytorch-metric-learning">PML</a></b> (🥇33 ·  ⭐ 5.5K) - The easiest way to use deep metric learning in your application. Modular,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/KevinMusgrave/pytorch-metric-learning) (👨‍💻 38 · 🔀 620 · 📦 920 · 📋 470 - 10% open · ⏱️ 25.07.2023):

	```
	git clone https://github.com/KevinMusgrave/pytorch-metric-learning
	```
- [PyPi](https://pypi.org/project/pytorch-metric-learning) (📥 310K / month):
	```
	pip install pytorch-metric-learning
	```
- [Conda](https://anaconda.org/metric-learning/pytorch-metric-learning) (📥 11K · ⏱️ 16.06.2023):
	```
	conda install -c metric-learning pytorch-metric-learning
	```
</details>
<details><summary><b><a href="https://github.com/tinygrad/tinygrad">tinygrad</a></b> (🥇31 ·  ⭐ 20K · 📈) - You like pytorch? You like micrograd? You love tinygrad!. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/tinygrad/tinygrad) (👨‍💻 220 · 🔀 2.1K · 📦 27 · 📋 380 - 16% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/geohot/tinygrad
	```
</details>
<details><summary><b><a href="https://github.com/Lightning-Universe/lightning-flash">lightning-flash</a></b> (🥇31 ·  ⭐ 1.7K) - Your PyTorch AI Factory - Flash enables you to easily.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/Lightning-Universe/lightning-flash) (👨‍💻 87 · 🔀 210 · 📦 250 · 📋 520 - 4% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/PyTorchLightning/lightning-flash
	```
- [PyPi](https://pypi.org/project/lightning-flash) (📥 1.8K / month):
	```
	pip install lightning-flash
	```
- [Conda](https://anaconda.org/conda-forge/lightning-flash) (📥 16K · ⏱️ 04.07.2023):
	```
	conda install -c conda-forge lightning-flash
	```
</details>
<details><summary><b><a href="https://github.com/google-research/torchsde">torchsde</a></b> (🥈30 ·  ⭐ 1.4K · 📈) - Differentiable SDE solvers with GPU support and efficient.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/google-research/torchsde) (👨‍💻 8 · 🔀 170 · 📦 1.6K · 📋 67 - 26% open · ⏱️ 26.09.2023):

	```
	git clone https://github.com/google-research/torchsde
	```
- [PyPi](https://pypi.org/project/torchsde) (📥 1M / month):
	```
	pip install torchsde
	```
- [Conda](https://anaconda.org/conda-forge/torchsde) (📥 19K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge torchsde
	```
</details>
<details><summary><b><a href="https://github.com/jettify/pytorch-optimizer">pytorch-optimizer</a></b> (🥈29 ·  ⭐ 2.9K) - torch-optimizer -- collection of optimizers for.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/jettify/pytorch-optimizer) (👨‍💻 26 · 🔀 280 · 📦 1K · 📋 61 - 50% open · ⏱️ 20.06.2023):

	```
	git clone https://github.com/jettify/pytorch-optimizer
	```
- [PyPi](https://pypi.org/project/torch_optimizer) (📥 110K / month):
	```
	pip install torch_optimizer
	```
- [Conda](https://anaconda.org/conda-forge/torch-optimizer) (📥 9K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge torch-optimizer
	```
</details>
<details><summary><b><a href="https://github.com/rtqichen/torchdiffeq">torchdiffeq</a></b> (🥈28 ·  ⭐ 4.9K) - Differentiable ODE solvers with full GPU support and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rtqichen/torchdiffeq) (👨‍💻 21 · 🔀 830 · 📦 2.3K · 📋 200 - 29% open · ⏱️ 30.08.2023):

	```
	git clone https://github.com/rtqichen/torchdiffeq
	```
- [PyPi](https://pypi.org/project/torchdiffeq) (📥 900K / month):
	```
	pip install torchdiffeq
	```
- [Conda](https://anaconda.org/conda-forge/torchdiffeq) (📥 13K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge torchdiffeq
	```
</details>
<details><summary><b><a href="https://github.com/dreamquark-ai/tabnet">TabNet</a></b> (🥈25 ·  ⭐ 2.3K) - PyTorch implementation of TabNet paper :.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/dreamquark-ai/tabnet) (👨‍💻 21 · 🔀 440 · 📋 280 - 7% open · ⏱️ 23.07.2023):

	```
	git clone https://github.com/dreamquark-ai/tabnet
	```
- [PyPi](https://pypi.org/project/pytorch-tabnet) (📥 39K / month):
	```
	pip install pytorch-tabnet
	```
- [Conda](https://anaconda.org/conda-forge/pytorch-tabnet) (📥 5.6K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pytorch-tabnet
	```
</details>
<details><summary><b><a href="https://github.com/BloodAxe/pytorch-toolbelt">Pytorch Toolbelt</a></b> (🥈24 ·  ⭐ 1.4K) - PyTorch extensions for fast R&D prototyping and Kaggle.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BloodAxe/pytorch-toolbelt) (👨‍💻 7 · 🔀 120 · 📋 30 - 3% open · ⏱️ 27.08.2023):

	```
	git clone https://github.com/BloodAxe/pytorch-toolbelt
	```
- [PyPi](https://pypi.org/project/pytorch_toolbelt) (📥 19K / month):
	```
	pip install pytorch_toolbelt
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_scatter">torch-scatter</a></b> (🥈23 ·  ⭐ 1.4K) - PyTorch Extension Library of Optimized Scatter Operations. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_scatter) (👨‍💻 28 · 🔀 160 · 📋 340 - 7% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/rusty1s/pytorch_scatter
	```
- [PyPi](https://pypi.org/project/torch-scatter) (📥 41K / month):
	```
	pip install torch-scatter
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_scatter) (📥 220K · ⏱️ 08.10.2023):
	```
	conda install -c conda-forge pytorch_scatter
	```
</details>
<details><summary><b><a href="https://github.com/rusty1s/pytorch_sparse">PyTorch Sparse</a></b> (🥉22 ·  ⭐ 880) - PyTorch Extension Library of Optimized Autograd Sparse.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/rusty1s/pytorch_sparse) (👨‍💻 44 · 🔀 140 · 📋 240 - 8% open · ⏱️ 05.10.2023):

	```
	git clone https://github.com/rusty1s/pytorch_sparse
	```
- [PyPi](https://pypi.org/project/torch-sparse) (📥 24K / month):
	```
	pip install torch-sparse
	```
- [Conda](https://anaconda.org/conda-forge/pytorch_sparse) (📥 230K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pytorch_sparse
	```
</details>
<details><summary><b><a href="https://github.com/lucidrains/reformer-pytorch">reformer-pytorch</a></b> (🥉20 ·  ⭐ 2K) - Reformer, the efficient Transformer, in Pytorch. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/lucidrains/reformer-pytorch) (👨‍💻 11 · 🔀 250 · 📋 120 - 11% open · ⏱️ 21.06.2023):

	```
	git clone https://github.com/lucidrains/reformer-pytorch
	```
- [PyPi](https://pypi.org/project/reformer-pytorch) (📥 1.8K / month):
	```
	pip install reformer-pytorch
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/madgrad">madgrad</a></b> (🥉15 ·  ⭐ 790) - MADGRAD Optimization Method. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/facebookresearch/madgrad) (👨‍💻 2 · 🔀 56 · 📦 61 · ⏱️ 11.04.2023):

	```
	git clone https://github.com/facebookresearch/madgrad
	```
- [PyPi](https://pypi.org/project/madgrad) (📥 3.1K / month):
	```
	pip install madgrad
	```
</details>
<details><summary>Show 19 hidden projects...</summary>

- <b><a href="https://github.com/Cadene/pretrained-models.pytorch">pretrainedmodels</a></b> (🥈26 ·  ⭐ 8.8K · 💀) - Pretrained ConvNets for pytorch: NASNet, ResNeXt,.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/sksq96/pytorch-summary">pytorch-summary</a></b> (🥈26 ·  ⭐ 3.9K · 💀) - Model summary in PyTorch similar to `model.summary()`.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/asappresearch/sru">SRU</a></b> (🥈23 ·  ⭐ 2.1K · 💀) - Training RNNs as Fast as CNNs (https://arxiv.org/abs/1709.02755). <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lukemelas/EfficientNet-PyTorch">EfficientNet-PyTorch</a></b> (🥉22 ·  ⭐ 7.5K · 💀) - A PyTorch implementation of EfficientNet and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/tristandeleu/pytorch-meta">Torchmeta</a></b> (🥉21 ·  ⭐ 1.9K · 💀) - A collection of extensions and data-loaders for few-shot.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/adobe/antialiased-cnns">Antialiased CNNs</a></b> (🥉21 ·  ⭐ 1.6K · 💀) - pip install antialiased-cnns to improve stability and.. <code><a href="https://tldrlegal.com/search?q=CC%20BY-NC-SA%204.0">❗️CC BY-NC-SA 4.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/rwightman/gen-efficientnet-pytorch">EfficientNets</a></b> (🥉21 ·  ⭐ 1.5K · 💀) - Pretrained EfficientNet, EfficientNet-Lite, MixNet,.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/szagoruyko/pytorchviz">pytorchviz</a></b> (🥉20 ·  ⭐ 2.8K · 💀) - A small package to create visualizations of PyTorch execution.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/lucidrains/lambda-networks">Lambda Networks</a></b> (🥉20 ·  ⭐ 1.5K · 💀) - Implementation of LambdaNetworks, a new approach to.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/GRAAL-Research/poutyne">Poutyne</a></b> (🥉20 ·  ⭐ 550) - A simplified framework and utilities for PyTorch. <code><a href="http://bit.ly/37RvQcA">❗️LGPL-3.0</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/Luolc/AdaBound">AdaBound</a></b> (🥉19 ·  ⭐ 2.9K · 💀) - An optimizer that trains as fast as Adam and as good as SGD. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/lucidrains/performer-pytorch">Performer Pytorch</a></b> (🥉19 ·  ⭐ 1K · 💀) - An implementation of Performer, a linear attention-.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/karpathy/micrograd">micrograd</a></b> (🥉17 ·  ⭐ 6.3K · 💀) - A tiny scalar-valued autograd engine and a neural net library.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/facebookresearch/higher">Higher</a></b> (🥉17 ·  ⭐ 1.6K · 💀) - higher is a pytorch library allowing users to obtain higher.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/harvardnlp/pytorch-struct">Torch-Struct</a></b> (🥉17 ·  ⭐ 1.1K · 💀) - Fast, general, and tested differentiable structured.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/parrt/tensor-sensor">Tensor Sensor</a></b> (🥉17 ·  ⭐ 740 · 💀) - The goal of this library is to generate more helpful.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/abhishekkrthakur/tez">Tez</a></b> (🥉16 ·  ⭐ 1.2K · 💀) - Tez is a super-simple and lightweight Trainer for PyTorch. It.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/achaiah/pywick">Pywick</a></b> (🥉13 ·  ⭐ 390 · 💀) - High-level batteries-included neural network training.. <code>❗Unlicensed</code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/TorchDrift/TorchDrift">TorchDrift</a></b> (🥉12 ·  ⭐ 300 · 💀) - Drift Detection for your PyTorch Models. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code>
</details>
<br>

## Database Clients

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

_Libraries for connecting to, operating, and querying databases._

🔗&nbsp;<b><a href="https://github.com/ml-tooling/best-of-python#database-clients">best-of-python - DB Clients</a></b> ( ⭐ 3.2K)  - Collection of database clients for python.

<br>

## Others

<a href="#contents"><img align="right" width="15" height="15" src="https://git.io/JtehR" alt="Back to top"></a>

<details><summary><b><a href="https://github.com/scipy/scipy">scipy</a></b> (🥇42 ·  ⭐ 12K · 📉) - Ecosystem of open-source software for mathematics, science, and.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/scipy/scipy) (👨‍💻 1.5K · 🔀 4.7K · 📥 380K · 📦 18 · 📋 9.4K - 15% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/scipy/scipy
	```
- [PyPi](https://pypi.org/project/scipy) (📥 61M / month):
	```
	pip install scipy
	```
- [Conda](https://anaconda.org/conda-forge/scipy) (📥 43M · ⏱️ 05.10.2023):
	```
	conda install -c conda-forge scipy
	```
</details>
<details><summary><b><a href="https://github.com/streamlit/streamlit">Streamlit</a></b> (🥇41 ·  ⭐ 28K) - Streamlit A faster way to build and share data apps. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/streamlit/streamlit) (👨‍💻 200 · 🔀 2.4K · 📦 1K · 📋 3.6K - 17% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/streamlit/streamlit
	```
- [PyPi](https://pypi.org/project/streamlit) (📥 2.3M / month):
	```
	pip install streamlit
	```
</details>
<details><summary><b><a href="https://github.com/gradio-app/gradio">Gradio</a></b> (🥇41 ·  ⭐ 23K · 📈) - Wrap UIs around any model, share with anyone. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/gradio-app/gradio) (👨‍💻 210 · 🔀 1.5K · 📦 15K · 📋 2.9K - 13% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/gradio-app/gradio
	```
- [PyPi](https://pypi.org/project/gradio) (📥 3.1M / month):
	```
	pip install gradio
	```
</details>
<details><summary><b><a href="https://github.com/deepchem/deepchem">DeepChem</a></b> (🥇36 ·  ⭐ 4.6K) - Democratizing Deep-Learning for Drug Discovery, Quantum Chemistry,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1A" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/deepchem/deepchem) (👨‍💻 230 · 🔀 1.5K · 📦 270 · 📋 1.6K - 25% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/deepchem/deepchem
	```
- [PyPi](https://pypi.org/project/deepchem) (📥 15K / month):
	```
	pip install deepchem
	```
- [Conda](https://anaconda.org/conda-forge/deepchem) (📥 100K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge deepchem
	```
</details>
<details><summary><b><a href="https://github.com/simonw/datasette">Datasette</a></b> (🥇35 ·  ⭐ 8.3K) - An open source multi-tool for exploring and publishing data. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/simonw/datasette) (👨‍💻 74 · 🔀 560 · 📥 58 · 📦 1.1K · 📋 1.6K - 29% open · ⏱️ 08.10.2023):

	```
	git clone https://github.com/simonw/datasette
	```
- [PyPi](https://pypi.org/project/datasette) (📥 33K / month):
	```
	pip install datasette
	```
- [Conda](https://anaconda.org/conda-forge/datasette) (📥 26K · ⏱️ 27.09.2023):
	```
	conda install -c conda-forge datasette
	```
</details>
<details><summary><b><a href="https://github.com/HIPS/autograd">Autograd</a></b> (🥇34 ·  ⭐ 6.5K) - Efficiently computes derivatives of numpy code. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/HIPS/autograd) (👨‍💻 55 · 🔀 840 · 📦 6.3K · 📋 390 - 40% open · ⏱️ 02.08.2023):

	```
	git clone https://github.com/HIPS/autograd
	```
- [PyPi](https://pypi.org/project/autograd) (📥 1.2M / month):
	```
	pip install autograd
	```
- [Conda](https://anaconda.org/conda-forge/autograd) (📥 360K · ⏱️ 26.06.2023):
	```
	conda install -c conda-forge autograd
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/hdbscan">hdbscan</a></b> (🥈33 ·  ⭐ 2.5K) - A high performance implementation of HDBSCAN clustering. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/hdbscan) (👨‍💻 85 · 🔀 440 · 📦 2.7K · 📋 480 - 66% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/scikit-learn-contrib/hdbscan
	```
- [PyPi](https://pypi.org/project/hdbscan) (📥 560K / month):
	```
	pip install hdbscan
	```
- [Conda](https://anaconda.org/conda-forge/hdbscan) (📥 1.7M · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge hdbscan
	```
</details>
<details><summary><b><a href="https://github.com/PaddlePaddle/PaddleHub">PaddleHub</a></b> (🥈32 ·  ⭐ 12K · 💤) - Awesome pre-trained models toolkit based on PaddlePaddle... <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code><img src="https://git.io/JLy1M" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/PaddlePaddle/PaddleHub) (👨‍💻 69 · 🔀 2.1K · 📥 660 · 📦 1.4K · 📋 1.3K - 44% open · ⏱️ 28.03.2023):

	```
	git clone https://github.com/PaddlePaddle/PaddleHub
	```
- [PyPi](https://pypi.org/project/paddlehub) (📥 5K / month):
	```
	pip install paddlehub
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/pyod">PyOD</a></b> (🥈32 ·  ⭐ 7.5K) - A Comprehensive and Scalable Python Library for Outlier Detection (Anomaly.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/pyod) (👨‍💻 48 · 🔀 1.3K · 📦 2.9K · 📋 310 - 54% open · ⏱️ 16.07.2023):

	```
	git clone https://github.com/yzhao062/pyod
	```
- [PyPi](https://pypi.org/project/pyod) (📥 600K / month):
	```
	pip install pyod
	```
- [Conda](https://anaconda.org/conda-forge/pyod) (📥 83K · ⏱️ 26.06.2023):
	```
	conda install -c conda-forge pyod
	```
</details>
<details><summary><b><a href="https://github.com/online-ml/river">River</a></b> (🥈32 ·  ⭐ 4.4K) - Online machine learning in Python. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/online-ml/river) (👨‍💻 100 · 🔀 480 · 📦 360 · 📋 450 - 2% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/online-ml/river
	```
- [PyPi](https://pypi.org/project/river) (📥 20K / month):
	```
	pip install river
	```
- [Conda](https://anaconda.org/conda-forge/river) (📥 50K · ⏱️ 06.10.2023):
	```
	conda install -c conda-forge river
	```
</details>
<details><summary><b><a href="https://github.com/PennyLaneAI/pennylane">PennyLane</a></b> (🥈32 ·  ⭐ 1.9K) - PennyLane is a cross-platform Python library for differentiable.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/PennyLaneAI/pennylane) (👨‍💻 140 · 🔀 480 · 📥 70 · 📦 640 · 📋 1K - 20% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/PennyLaneAI/PennyLane
	```
- [PyPi](https://pypi.org/project/pennylane) (📥 35K / month):
	```
	pip install pennylane
	```
- [Conda](https://anaconda.org/conda-forge/pennylane) (📥 25K · ⏱️ 11.09.2023):
	```
	conda install -c conda-forge pennylane
	```
</details>
<details><summary><b><a href="https://github.com/wireservice/agate">agate</a></b> (🥈32 ·  ⭐ 1.1K) - A Python data analysis library that is optimized for humans instead of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/wireservice/agate) (👨‍💻 52 · 🔀 140 · 📦 2.2K · 📋 640 - 1% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/wireservice/agate
	```
- [PyPi](https://pypi.org/project/agate) (📥 3.8M / month):
	```
	pip install agate
	```
- [Conda](https://anaconda.org/conda-forge/agate) (📥 150K · ⏱️ 11.10.2023):
	```
	conda install -c conda-forge agate
	```
</details>
<details><summary><b><a href="https://github.com/serge-sans-paille/pythran">Pythran</a></b> (🥈31 ·  ⭐ 1.9K) - Ahead of Time compiler for numeric kernels. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code></summary>

- [GitHub](https://github.com/serge-sans-paille/pythran) (👨‍💻 72 · 🔀 180 · 📦 1.3K · 📋 820 - 14% open · ⏱️ 06.09.2023):

	```
	git clone https://github.com/serge-sans-paille/pythran
	```
- [PyPi](https://pypi.org/project/pythran) (📥 190K / month):
	```
	pip install pythran
	```
- [Conda](https://anaconda.org/conda-forge/pythran) (📥 410K · ⏱️ 21.09.2023):
	```
	conda install -c conda-forge pythran
	```
</details>
<details><summary><b><a href="https://github.com/adapter-hub/adapter-transformers">adapter-transformers</a></b> (🥈30 ·  ⭐ 1.9K) - Huggingface Transformers + Adapters =. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code> <code>huggingface</code></summary>

- [GitHub](https://github.com/adapter-hub/adapter-transformers) (👨‍💻 1.7K · 🔀 280 · 📦 230 · 📋 340 - 16% open · ⏱️ 09.09.2023):

	```
	git clone https://github.com/Adapter-Hub/adapter-transformers
	```
- [PyPi](https://pypi.org/project/adapter-transformers) (📥 12K / month):
	```
	pip install adapter-transformers
	```
</details>
<details><summary><b><a href="https://github.com/ContinualAI/avalanche">avalanche</a></b> (🥈30 ·  ⭐ 1.5K) - Avalanche: an End-to-End Library for Continual Learning based on.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ContinualAI/avalanche) (👨‍💻 72 · 🔀 240 · 📥 4 · 📦 49 · 📋 740 - 11% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/ContinualAI/avalanche
	```
- [PyPi](https://pypi.org/project/avalanche-lib) (📥 1.5K / month):
	```
	pip install avalanche-lib
	```
</details>
<details><summary><b><a href="https://github.com/pyjanitor-devs/pyjanitor">pyjanitor</a></b> (🥈30 ·  ⭐ 1.2K) - Clean APIs for data cleaning. Python implementation of R package.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/pyjanitor-devs/pyjanitor) (👨‍💻 110 · 🔀 160 · 📦 480 · 📋 540 - 19% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/pyjanitor-devs/pyjanitor
	```
- [PyPi](https://pypi.org/project/pyjanitor) (📥 32K / month):
	```
	pip install pyjanitor
	```
- [Conda](https://anaconda.org/conda-forge/pyjanitor) (📥 180K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge pyjanitor
	```
</details>
<details><summary><b><a href="https://github.com/SeldonIO/alibi-detect">alibi-detect</a></b> (🥈29 ·  ⭐ 1.9K) - Algorithms for outlier, adversarial and drift detection. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/SeldonIO/alibi-detect) (👨‍💻 19 · 🔀 200 · 📦 370 · 📋 350 - 33% open · ⏱️ 07.10.2023):

	```
	git clone https://github.com/SeldonIO/alibi-detect
	```
- [PyPi](https://pypi.org/project/alibi-detect) (📥 23K / month):
	```
	pip install alibi-detect
	```
</details>
<details><summary><b><a href="https://github.com/tableau/TabPy">TabPy</a></b> (🥈28 ·  ⭐ 1.4K) - Execute Python code on the fly and display results in Tableau visualizations:. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/tableau/TabPy) (👨‍💻 49 · 🔀 560 · 📦 140 · 📋 310 - 2% open · ⏱️ 10.10.2023):

	```
	git clone https://github.com/tableau/TabPy
	```
- [PyPi](https://pypi.org/project/tabpy) (📥 12K / month):
	```
	pip install tabpy
	```
- [Conda](https://anaconda.org/anaconda/tabpy-client) (📥 4.4K · ⏱️ 16.06.2023):
	```
	conda install -c anaconda tabpy-client
	```
</details>
<details><summary><b><a href="https://github.com/scikit-learn-contrib/metric-learn">metric-learn</a></b> (🥈28 ·  ⭐ 1.3K) - Metric learning algorithms in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/scikit-learn-contrib/metric-learn) (👨‍💻 22 · 🔀 220 · 📦 300 · 📋 160 - 26% open · ⏱️ 29.09.2023):

	```
	git clone https://github.com/scikit-learn-contrib/metric-learn
	```
- [PyPi](https://pypi.org/project/metric-learn) (📥 8.2K / month):
	```
	pip install metric-learn
	```
- [Conda](https://anaconda.org/conda-forge/metric-learn) (📥 10K · ⏱️ 09.10.2023):
	```
	conda install -c conda-forge metric-learn
	```
</details>
<details><summary><b><a href="https://github.com/nicodv/kmodes">kmodes</a></b> (🥈28 ·  ⭐ 1.2K) - Python implementations of the k-modes and k-prototypes clustering.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/nicodv/kmodes) (👨‍💻 22 · 🔀 400 · 📦 2.3K · 📋 150 - 10% open · ⏱️ 20.04.2023):

	```
	git clone https://github.com/nicodv/kmodes
	```
- [PyPi](https://pypi.org/project/kmodes) (📥 160K / month):
	```
	pip install kmodes
	```
- [Conda](https://anaconda.org/conda-forge/kmodes) (📥 37K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge kmodes
	```
</details>
<details><summary><b><a href="https://github.com/google-deepmind/pysc2">pysc2</a></b> (🥉27 ·  ⭐ 7.8K) - StarCraft II Learning Environment. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google-deepmind/pysc2) (👨‍💻 39 · 🔀 1.1K · 📥 31K · 📦 610 · 📋 280 - 16% open · ⏱️ 19.04.2023):

	```
	git clone https://github.com/deepmind/pysc2
	```
- [PyPi](https://pypi.org/project/pysc2) (📥 1.6K / month):
	```
	pip install pysc2
	```
</details>
<details><summary><b><a href="https://github.com/sepandhaghighi/pycm">pycm</a></b> (🥉27 ·  ⭐ 1.4K) - Multi-class confusion matrix library in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/sepandhaghighi/pycm) (👨‍💻 17 · 🔀 120 · 📦 240 · 📋 200 - 4% open · ⏱️ 07.06.2023):

	```
	git clone https://github.com/sepandhaghighi/pycm
	```
- [PyPi](https://pypi.org/project/pycm) (📥 35K / month):
	```
	pip install pycm
	```
</details>
<details><summary><b><a href="https://github.com/ljvmiranda921/pyswarms">PySwarms</a></b> (🥉27 ·  ⭐ 1.1K) - A research toolkit for particle swarm optimization in Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/ljvmiranda921/pyswarms) (👨‍💻 45 · 🔀 320 · 📦 310 · 📋 220 - 9% open · ⏱️ 06.06.2023):

	```
	git clone https://github.com/ljvmiranda921/pyswarms
	```
- [PyPi](https://pypi.org/project/pyswarms) (📥 9K / month):
	```
	pip install pyswarms
	```
</details>
<details><summary><b><a href="https://github.com/MaxHalford/prince">Prince</a></b> (🥉27 ·  ⭐ 1.1K) - Multivariate exploratory data analysis in Python PCA, CA, MCA, MFA,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/MaxHalford/prince) (👨‍💻 16 · 🔀 170 · 📦 420 · 📋 130 - 1% open · ⏱️ 11.10.2023):

	```
	git clone https://github.com/MaxHalford/prince
	```
- [PyPi](https://pypi.org/project/prince) (📥 72K / month):
	```
	pip install prince
	```
- [Conda](https://anaconda.org/conda-forge/prince-factor-analysis) (📥 17K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge prince-factor-analysis
	```
</details>
<details><summary><b><a href="https://github.com/google/trax">Trax</a></b> (🥉26 ·  ⭐ 7.7K · 💤) - Trax Deep Learning with Clear Code and Speed. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/google/trax) (👨‍💻 78 · 🔀 790 · 📦 120 · 📋 230 - 45% open · ⏱️ 29.03.2023):

	```
	git clone https://github.com/google/trax
	```
- [PyPi](https://pypi.org/project/trax) (📥 4.4K / month):
	```
	pip install trax
	```
</details>
<details><summary><b><a href="https://github.com/dstackai/dstack">dstack</a></b> (🥉25 ·  ⭐ 820 · 📈) - dstack is an open-source framework for orchestrating GPU workloads.. <code><a href="http://bit.ly/3postzC">MPL-2.0</a></code></summary>

- [GitHub](https://github.com/dstackai/dstack) (👨‍💻 13 · 🔀 46 · 📦 12 · 📋 380 - 0% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/dstackai/dstack
	```
- [PyPi](https://pypi.org/project/dstack) (📥 800 / month):
	```
	pip install dstack
	```
</details>
<details><summary><b><a href="https://github.com/BioPandas/biopandas">BioPandas</a></b> (🥉25 ·  ⭐ 650) - Working with molecular structures in pandas DataFrames. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/BioPandas/biopandas) (👨‍💻 15 · 🔀 120 · 📦 200 · 📋 56 - 41% open · ⏱️ 19.09.2023):

	```
	git clone https://github.com/rasbt/biopandas
	```
- [PyPi](https://pypi.org/project/biopandas) (📥 62K / month):
	```
	pip install biopandas
	```
- [Conda](https://anaconda.org/conda-forge/biopandas) (📥 150K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge biopandas
	```
</details>
<details><summary><b><a href="https://github.com/mars-project/mars">Mars</a></b> (🥉24 ·  ⭐ 2.6K) - Mars is a tensor-based unified framework for large-scale data.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/mars-project/mars) (👨‍💻 52 · 🔀 310 · 📋 1.2K - 16% open · ⏱️ 25.09.2023):

	```
	git clone https://github.com/mars-project/mars
	```
- [PyPi](https://pypi.org/project/pymars) (📥 55K / month):
	```
	pip install pymars
	```
</details>
<details><summary><b><a href="https://github.com/modAL-python/modAL">modAL</a></b> (🥉24 ·  ⭐ 2K) - A modular active learning framework for Python. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/modAL-python/modAL) (👨‍💻 20 · 🔀 300 · 📥 29 · 📦 16 · 📋 140 - 59% open · ⏱️ 01.06.2023):

	```
	git clone https://github.com/modAL-python/modAL
	```
- [PyPi](https://pypi.org/project/modAL) (📥 100K / month):
	```
	pip install modAL
	```
</details>
<details><summary><b><a href="https://github.com/Project-MONAI/MONAILabel">MONAILabel</a></b> (🥉24 ·  ⭐ 460) - MONAI Label is an intelligent open source image labeling and.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code></summary>

- [GitHub](https://github.com/Project-MONAI/MONAILabel) (👨‍💻 52 · 🔀 160 · 📥 64K · 📋 460 - 18% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/Project-MONAI/MONAILabel
	```
- [PyPi](https://pypi.org/project/monailabel-weekly) (📥 640 / month):
	```
	pip install monailabel-weekly
	```
</details>
<details><summary><b><a href="https://github.com/trevorstephens/gplearn">gplearn</a></b> (🥉21 ·  ⭐ 1.4K) - Genetic Programming in Python, with a scikit-learn inspired API. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/trevorstephens/gplearn) (👨‍💻 10 · 🔀 250 · 📋 210 - 9% open · ⏱️ 12.08.2023):

	```
	git clone https://github.com/trevorstephens/gplearn
	```
- [PyPi](https://pypi.org/project/gplearn) (📥 5.3K / month):
	```
	pip install gplearn
	```
- [Conda](https://anaconda.org/conda-forge/gplearn) (📥 6.1K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge gplearn
	```
</details>
<details><summary><b><a href="https://github.com/pykale/pykale">pykale</a></b> (🥉21 ·  ⭐ 400) - Knowledge-Aware machine LEarning (KALE): accessible machine learning.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/pykale/pykale) (👨‍💻 22 · 🔀 57 · 📦 1 · 📋 110 - 4% open · ⏱️ 04.10.2023):

	```
	git clone https://github.com/pykale/pykale
	```
- [PyPi](https://pypi.org/project/pykale) (📥 24 / month):
	```
	pip install pykale
	```
</details>
<details><summary><b><a href="https://github.com/astroML/astroML">AstroML</a></b> (🥉19 ·  ⭐ 950 · 💤) - Machine learning, statistics, and data mining for astronomy and.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/astroML/astroML) (👨‍💻 30 · 🔀 280 · 📋 150 - 37% open · ⏱️ 12.12.2022):

	```
	git clone https://github.com/astroML/astroML
	```
- [PyPi](https://pypi.org/project/astroML) (📥 1K / month):
	```
	pip install astroML
	```
- [Conda](https://anaconda.org/conda-forge/astroml) (📥 41K · ⏱️ 16.06.2023):
	```
	conda install -c conda-forge astroml
	```
</details>
<details><summary><b><a href="https://github.com/kLabUM/rrcf">rrcf</a></b> (🥉19 ·  ⭐ 460) - Implementation of the Robust Random Cut Forest algorithm for anomaly detection.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/kLabUM/rrcf) (👨‍💻 7 · 🔀 100 · 📦 52 · 📋 47 - 57% open · ⏱️ 12.08.2023):

	```
	git clone https://github.com/kLabUM/rrcf
	```
- [PyPi](https://pypi.org/project/rrcf) (📥 2.9K / month):
	```
	pip install rrcf
	```
</details>
<details><summary><b><a href="https://github.com/yzhao062/SUOD">SUOD</a></b> (🥉19 ·  ⭐ 350) - (MLSys 21) An Acceleration System for Large-scare Unsupervised Heterogeneous.. <code><a href="http://bit.ly/3rqEWVr">BSD-2</a></code></summary>

- [GitHub](https://github.com/yzhao062/SUOD) (👨‍💻 3 · 🔀 46 · 📦 490 · 📋 10 - 70% open · ⏱️ 16.07.2023):

	```
	git clone https://github.com/yzhao062/SUOD
	```
- [PyPi](https://pypi.org/project/suod) (📥 39K / month):
	```
	pip install suod
	```
</details>
<details><summary><b><a href="https://github.com/facebookresearch/NeuralCompression">NeuralCompression</a></b> (🥉18 ·  ⭐ 400) - A collection of tools for neural compression enthusiasts. <code><a href="http://bit.ly/34MBwT8">MIT</a></code></summary>

- [GitHub](https://github.com/facebookresearch/NeuralCompression) (👨‍💻 9 · 🔀 37 · 📋 66 - 4% open · ⏱️ 12.10.2023):

	```
	git clone https://github.com/facebookresearch/NeuralCompression
	```
- [PyPi](https://pypi.org/project/neuralcompression) (📥 180 / month):
	```
	pip install neuralcompression
	```
</details>
<details><summary><b><a href="https://github.com/SforAiDl/KD_Lib">KD-Lib</a></b> (🥉15 ·  ⭐ 540 · 💤) - A Pytorch Knowledge Distillation library for benchmarking and.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1Q" style="display:inline;" width="13" height="13"></code></summary>

- [GitHub](https://github.com/SforAiDl/KD_Lib) (👨‍💻 6 · 🔀 50 · 📋 62 - 20% open · ⏱️ 01.03.2023):

	```
	git clone https://github.com/SforAiDl/KD_Lib
	```
- [PyPi](https://pypi.org/project/KD-Lib) (📥 40 / month):
	```
	pip install KD-Lib
	```
</details>
<details><summary>Show 24 hidden projects...</summary>

- <b><a href="https://github.com/sympy/sympy">SymPy</a></b> (🥇46 ·  ⭐ 11K) - A computer algebra system written in pure Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/carla-simulator/carla">carla</a></b> (🥈32 ·  ⭐ 9.7K) - Open-source simulator for autonomous driving research. <code>❗Unlicensed</code>
- <b><a href="https://github.com/cleanlab/cleanlab">cleanlab</a></b> (🥈30 ·  ⭐ 6.8K) - The standard data-centric AI package for data quality and machine.. <code><a href="http://bit.ly/3pwmjO5">❗️AGPL-3.0</a></code>
- <b><a href="https://github.com/inducer/pyopencl">pyopencl</a></b> (🥈30 ·  ⭐ 990) - OpenCL integration for Python, plus shiny features. <code>❗Unlicensed</code>
- <b><a href="https://github.com/uber/causalml">causalml</a></b> (🥈28 ·  ⭐ 4.3K) - Uplift modeling and causal inference with machine learning.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/tensorly/tensorly">tensorly</a></b> (🥈28 ·  ⭐ 1.4K) - TensorLy: Tensor Learning in Python. <code>❗Unlicensed</code>
- <b><a href="https://github.com/annoviko/pyclustering">pyclustering</a></b> (🥈28 ·  ⭐ 1.1K · 💀) - pyclustering is a Python, C++ data mining library. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/explosion/cython-blis">Cython BLIS</a></b> (🥈28 ·  ⭐ 200) - Fast matrix-multiplication as a self-contained Python.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/JustGlowing/minisom">minisom</a></b> (🥉26 ·  ⭐ 1.3K) - MiniSom is a minimalistic implementation of the Self Organizing.. <code><a href="https://tldrlegal.com/search?q=CC-BY-3.0">❗️CC-BY-3.0</a></code>
- <b><a href="https://github.com/datalad/datalad">datalad</a></b> (🥉25 ·  ⭐ 460 · 📉) - Keep code, data, containers under control with git and git-.. <code>❗Unlicensed</code>
- <b><a href="https://github.com/facebookresearch/AugLy">AugLy</a></b> (🥉22 ·  ⭐ 4.8K) - A data augmentations library for audio, image, text, and video. <code>❗Unlicensed</code>
- <b><a href="https://github.com/flennerhag/mlens">mlens</a></b> (🥉22 ·  ⭐ 810 · 💀) - ML-Ensemble high performance ensemble learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/minrk/findspark">findspark</a></b> (🥉22 ·  ⭐ 490 · 💀) - Find pyspark to make it importable. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1N" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/vecxoz/vecstack">vecstack</a></b> (🥉21 ·  ⭐ 680 · 💀) - Python package for stacking (machine learning technique). <code>❗Unlicensed</code>
- <b><a href="https://github.com/ml-tooling/opyrator">opyrator</a></b> (🥉20 ·  ⭐ 2.9K · 💀) - Turns your machine learning code into microservices with web API,.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/airbnb/streamalert">StreamAlert</a></b> (🥉20 ·  ⭐ 2.8K · 💀) - StreamAlert is a serverless, realtime data analysis.. <code><a href="http://bit.ly/3nYMfla">Apache-2</a></code>
- <b><a href="https://github.com/jmschrei/apricot">apricot</a></b> (🥉19 ·  ⭐ 480 · 💀) - apricot implements submodular optimization for the purpose of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/eltonlaw/impyute">impyute</a></b> (🥉19 ·  ⭐ 340 · 💀) - Data imputations library to preprocess datasets with missing data. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/alegonz/baikal">baikal</a></b> (🥉17 ·  ⭐ 590 · 💀) - A graph-based functional API for building complex scikit-learn.. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/EpistasisLab/scikit-rebate">scikit-rebate</a></b> (🥉16 ·  ⭐ 380 · 💀) - A scikit-learn-compatible Python implementation of.. <code><a href="http://bit.ly/34MBwT8">MIT</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/pandas-ml/pandas-ml">pandas-ml</a></b> (🥉16 ·  ⭐ 310 · 💀) - pandas, scikit-learn, xgboost and seaborn integration. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code> <code><img src="https://git.io/JLy1F" style="display:inline;" width="13" height="13"></code> <code><img src="https://git.io/JLy1S" style="display:inline;" width="13" height="13"></code>
- <b><a href="https://github.com/solegalli/feature_engine">Feature Engine</a></b> (🥉16 ·  ⭐ 35 · 💤) - Feature engineering package with sklearn like functionality. <code><a href="http://bit.ly/3aKzpTv">BSD-3</a></code>
- <b><a href="https://github.com/jrieke/traingenerator">traingenerator</a></b> (🥉14 ·  ⭐ 1.3K · 💀) - A web app to generate template code for machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
- <b><a href="https://github.com/Palashio/nylon">nylon</a></b> (🥉9 ·  ⭐ 82 · 💀) - An intelligent, flexible grammar of machine learning. <code><a href="http://bit.ly/34MBwT8">MIT</a></code>
</details>

---

## Related Resources

- [**Papers With Code**](https://paperswithcode.com): Discover ML papers, code, and evaluation tables.
- [**Sotabench**](https://sotabench.com): Discover & compare open-source ML models.
- [**Google Dataset Search**](https://toolbox.google.com/datasetsearch): Dataset search engine by Google.
- [**Dataset List**](https://www.datasetlist.com/): List of the biggest ML datasets from across the web.
- [**Awesome Public Datasets**](https://github.com/awesomedata/awesome-public-datasets): A topic-centric list of open datasets.
- [**Best-of lists**](https://best-of.org): Discover other best-of lists with awesome open-source projects on all kinds of topics.
- [**best-of-python-dev**](https://github.com/ml-tooling/best-of-python-dev): A ranked list of awesome python developer tools and libraries.
- [**best-of-web-python**](https://github.com/ml-tooling/best-of-web-python): A ranked list of awesome python libraries for web development.

## Contribution

Contributions are encouraged and always welcome! If you like to add or update projects, choose one of the following ways:

- Open an issue by selecting one of the provided categories from the [issue page](https://github.com/ml-tooling/best-of-ml-python/issues/new/choose) and fill in the requested information.
- Modify the [projects.yaml](https://github.com/ml-tooling/best-of-ml-python/blob/main/projects.yaml) with your additions or changes, and submit a pull request. This can also be done directly via the [Github UI](https://github.com/ml-tooling/best-of-ml-python/edit/main/projects.yaml).

If you like to contribute to or share suggestions regarding the project metadata collection or markdown generation, please refer to the [best-of-generator](https://github.com/best-of-lists/best-of-generator) repository. If you like to create your own best-of list, we recommend to follow [this guide](https://github.com/best-of-lists/best-of/blob/main/create-best-of-list.md).

For more information on how to add or update projects, please read the [contribution guidelines](https://github.com/ml-tooling/best-of-ml-python/blob/main/CONTRIBUTING.md). By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/ml-tooling/best-of-ml-python/blob/main/.github/CODE_OF_CONDUCT.md).

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](https://creativecommons.org/licenses/by-sa/4.0/)
