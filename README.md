# FIELDMIND🌿

An innovative Machine Learning (ML) and Deep Learning (DL) powered web platform designed to revolutionize agricultural practices. Our platform offers a trifecta of cutting-edge applications tailored to enhance crop management and maximize yields: Crop Intelligence, Fertilizer Insights, and Plant Health Diagnosis.

## RATIONALE

- In this project, I present a website in which the following applications are implemented; Crop recommendation, Fertilizer recommendation and Plant disease prediction, respectively.
- - In the crop recommendation application, the user can provide the soil data from their side and, By analyzing key soil parameters alongside climatic conditions fetched through real-time Weather APIs, our system delivers tailored recommendations, enhancing agricultural decision-making processes.
  - For the fertilizer recommendation application, the user can input the soil data and the type of crop they are growing, Leveraging advanced ML techniques, our platform assesses soil composition, identifying deficiencies or excesses in crucial nutrients. Armed with this insight, personalized fertilizer recommendations are generated, ensuring optimal nutrient balance tailored to crop requirements.
  - For the last application, that is the plant disease prediction application, the user can input an image of a diseased plant leaf, and Powered by DL models trained on extensive datasets, our system accurately identifies diseases and offers comprehensive insights into their nature. Furthermore, users receive actionable recommendations for effective disease management, bolstered by informative background summaries.

# Built with 🛠️

<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/python/python.png"></code>
<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/html/html.png"></code>`
`<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/css/css.png"></code>`
`<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/javascript/javascript.png">`</code>
`<code><img height="30" src="https://github.com/tomchen/stack-icons/raw/master/logos/bootstrap.svg"></code>`
`<code><img height="30" src="https://raw.githubusercontent.com/github/explore/80688e429a7d4ef2fca1e82350fe8e3517d3494d/topics/git/git.png"></code>`
`<code><img height="30" src="https://symbols.getvecta.com/stencil_80/56_flask.3a79b5a056.jpg"></code>`
`<code><img height="30" src="https://cdn.iconscout.com/icon/free/png-256/heroku-225989.png">``</code>

<code><img height="30" src="https://raw.githubusercontent.com/numpy/numpy/7e7f4adab814b223f7f917369a72757cd28b10cb/branding/icons/numpylogo.svg"></code><code><img height="30" src="https://raw.githubusercontent.com/pandas-dev/pandas/761bceb77d44aa63b71dda43ca46e8fd4b9d7422/web/pandas/static/img/pandas.svg"></code>`
`<code><img height="30" src="https://matplotlib.org/_static/logo2.svg"></code>`
`<code><img height="30" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/05/Scikit_learn_logo_small.svg/1280px-Scikit_learn_logo_small.svg.png"></code>`
`<code><img height="30" src="https://raw.githubusercontent.com/pytorch/pytorch/39fa0b5d0a3b966a50dcd90b26e6c36942705d6d/docs/source/_static/img/pytorch-logo-dark.svg">``</code>

## How to run locally 🛠️

- Before the following steps make sure you have [git](https://git-scm.com/download), [Anaconda](https://www.anaconda.com/) or [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed on your system
- Clone the complete project or you can just download the code and unzip it
- `deploy` branch has only the code required for deploying the app (rest of the code that was used for training the models, data preparation can be accessed on `master` branch)
- It is highly recommended to clone the deploy branch for running the project locally (the further steps apply only if you have the deploy branch cloned)
- Once the project is cloned or downloaded , open anaconda prompt in the directory where the project was cloned and paste the following block
  ```
  conda create -n fieldmind python=3.6.12
  conda activate fieldmind
  pip install -r requirements.txt
  ```
- And finally run the project with
  ```
  python app.py
  ```
- Open the localhost url provided after running `app.py` and now you can use the project locally in your web browser.

## DEMO

### HOME!!![1712307737345](image/README/1712307737345.png)

### Crop recommendation system

![1712307971135](image/README/1712307971135.png)

### Fertilizer suggestion system

![1712308023345](image/README/1712308023345.png)

### Disease Detection system

![1712308069228](image/README/1712308069228.png)

# RESULT DEMO!!

![1712308139112](image/README/1712308139112.png)![1712308124337](image/README/1712308124337.png)
