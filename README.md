# Fake-tweet-classification-for-disaster-management
Project to extract real time tweets (Tweepy- using Nitter scraper) and classify as fake or real for disaster management using LSTM and BERT model.

## Tweet Analytics for Disaster & Calamity Management

Social media platforms like Twitter provide an unprecedented opportunity to access a vast amount of information and gain insights directly from those affected by disasters. By analyzing the conversations and trends on Twitter during such situations, the project aims to uncover patterns, validate the truthfulness of information, improve situational awareness, and ultimately contribute to the resilience and safety of individuals and communities faced with critical events.\
The major motivation behind the proposed project is to save lives and improve public safety by harnessing the power of Twitter data to access real-time information, understand & validate public sentiment.

## Pre-processing visualization

Unique word count distribution:
![Unique word count distribution](https://github.com/shakir-flash/Fake-tweet-classification-for-disaster-management/assets/59859522/7d3a2ee2-69e5-4a80-8474-ce8c0b585146)

Average word length distribution:
![Average word length distribution](https://github.com/shakir-flash/Fake-tweet-classification-for-disaster-management/assets/59859522/4ef38466-7d89-4d6d-a9e7-5276076b5281)


## Deployment

🔗 The GUI made with the script in the `disastertweetapp/` folder has been deployed on this link: (https://disaster-tweet-app-algorhythms.streamlit.app/)

## GUI Output from website:

Input- #earthquake, location- usa, number of tweets- 10
<img width="1239" alt="hashtag_earthquake" src="https://github.com/shakir-flash/Fake-tweet-classification-for-disaster-management/assets/59859522/0a1f6a6d-1415-4f20-9d7c-d76ba046f2a4">

Input- #flood, location- usa, number of tweets- 10
![hashtag_flood](https://github.com/shakir-flash/Fake-tweet-classification-for-disaster-management/assets/59859522/c2602a54-7105-4028-80d0-0509d1f84d79)

Input- #hurricane, location- usa, number of tweets- 10
![hashtag_hurricane](https://github.com/shakir-flash/Fake-tweet-classification-for-disaster-management/assets/59859522/49fe09ef-0d83-4214-9fc5-b4804dc903d2)


## Repo Organization

-   `.github`: This directory contain files related to GitHub, such as workflows, issue templates, or other configurations.

-   `. _extra`: Contains code, notes and other files used during experimentation. Contents of this folder is not a part of the final output.

-   `_freeze`: The folder created to store files generated during project render.

-   `analysis/`: This folder contains the analysis scripts used to generate output for the project outline.

    -   README.md describes the steps to run and generate the results using scripts

    -   Other code files are added to review and understand the source of the output

    -   Relevant datasets used for the scripts are under the `data/` folder in the main directory.

-   `disastertweetapp/`: This folder contains the code for GUI built using streamlit

    -   `app.py`: Main folder containing the GUI code of the app.

    -   `classification_script.py`: This file contains code for loading the trained models and functions to predict the class labels if given text. It also contains the code to extract location from the tweet.

    -   `embedtweet.py`: This file contains code to embed tweets in the GUI

    -   `fetchtweets.py`: This file contains the streaming client script to fetch real-time tweets using keywords.

    -   `requirements.py`: requirements file containing package details

    -   `models/`: Folder containing the serialized models

-   `data/`: This folder contains data files or datasets that are used in the project.

    -   README.md : A readme file that describes the datasets in more detail.

-   `images`: This folder contains image files that are used in the project, such as illustrations, diagrams, or other visual assets.

-   `.gitignore`: This file specifies which files or directories should be ignored by version control.

-   `README.md`: This file usually contains documentation or information about the project. It's often the first thing someone reads when they visit the project repository.

-   `_quarto.yml`: This is likely a configuration file

-   `about.qmd` : This quarto document contains the information about team members.

-   `index.qmd` : This quarto document contains the approach and analysis and results of the project.

-   `presentation.qmd` : It contains the slides for the presentation.

-   `proposal.qmd` : This quarto documents has the proposal of the project.

-   `project-final.Rproj` : This is an RStudio project file, which helps organize R-related files and settings for the project.

