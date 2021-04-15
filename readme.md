# Space Missions

![Space Image](https://i1.wp.com/matmatch.com/blog/wp-content/uploads/2019/03/AdobeStock_80273384-compressor.jpeg?resize=2000%2C1125&ssl=1)

[![Contributors](https://img.shields.io/github/contributors/dsckgec/project-template.svg)](https://github.com/dsckgec/space-missions/graphs/contributors) [![Forks](https://img.shields.io/github/forks/dsckgec/project-template.svg)](https://github.com/dsckgec/space-missions/network/members) [![Issues](https://img.shields.io/github/issues/dsckgec/project-template.svg)](https://github.com/dsckgec/space-missions/issues) [![Pull Request](https://img.shields.io/github/issues-pr-closed-raw/dsckgec/project-template)](https://github.com/dsckgec/space-missions/pulls)

Exploratory Data Analysis and Data Visualisation of Space Missions Since 1957, with a little bit of feature engineering and predictive modelling.

## Contents

1. [Description](#description)
2. [Getting started](#getting-started)
3. [Project Structure](#project-structure)
4. [Live demo](#live-demo)
5. [Contributing](#contributing)
6. [Authors](#authors)
7. [License](#license)

## Description

Who does not love Space? 
The DataSet was scraped from https://nextspaceflight.com/launches/past/?page=1 and includes all the space missions since the beginning of Space Race (1957).

## Project structure

```
  ├── datasets/         Dataset of Space Missions.
  ├── notebooks/        Contains the jupyter notebook files of Space Missions.
```

## Getting started


### Prerequisites

#### Software Needed
 
  1. A web browser. 

         OR
         
  3. Anaconda software.

#### Knowledge Needed
- Very basic understanding of git and github:

    1.  What are repositories (local - remote - upstream), issues, pull requests
    2.   How to clone a repository, how to fork a repository, how to set upstreams
    3.   Adding, committing, pulling, pushing changes to remote repositories

- For EDA and Visualisation
 
    1. Basic syntax and working of ```python```.(This is a must)
    2. Basic knowledge of ```pandas``` library. [Reading this blog might help.](https://www.dataquest.io/blog/pandas-python-tutorial/)
    3. Basic knowledge of ```matplotlib``` library. [Reading this blog might help.](https://blog.quantinsti.com/python-matplotlib-tutorial/)
    4. Basic knowledge of ```seaborn``` library. [Reading this blog might help.](https://www.mygreatlearning.com/blog/seaborn-tutorial/)
    5. Basic knowledge of ```scikit learn``` library. [Reading this blog might help.](https://www.dataquest.io/blog/sci-kit-learn-tutorial/)

  However the code is well explained, so anyone knowing the basics of Python can get a idea of what's happenning and contribute to this.

### Installing

There are two ways of running the code.
  1. Running the code on web browser.(Google Colab) [Recommended]
      - Head on to [Google colab](https://www.colab.research.google.com)
      - Then click on ```Upload Notebook``` Tab.
      - Upload the notebook that you got from this repo.
        ![Colab-1](https://res.cloudinary.com/codehackerone/image/upload/v1618463907/ML/colab-2_c14swf.png)
      - Connect with the runtime.
        ![Colab-2](https://res.cloudinary.com/codehackerone/image/upload/v1618464955/ML/Colab-3_da822c.png)
      - Upload your dataset.
        ![Colab-3](https://res.cloudinary.com/codehackerone/image/upload/v1618464958/ML/Colab-04_sxfyjx.png)
      - Then Click on ```Run All```.
        ![Colab-4](https://res.cloudinary.com/codehackerone/image/upload/v1618465413/ML/colab-5_i92bzp.png)
      - Start Editing.

  2. You can also run the code locally in your computer by installing Anaconda.
      - Install Anaconda. [Follow these steps to install Anaconda on your computer](https://www.edureka.co/blog/python-anaconda-tutorial/#:~:text=on%20our%20systems.-,Installation%20And%20Setup,the%20instructions%20in%20the%20setup.)
      - Install jupyter notebook using ```conda```. [Follow these steps to install jupyter notebook.](https://test-jupyter.readthedocs.io/en/latest/install.html)
      - Make sure to install ```pandas```,```matplotlib```,```seaborn``` and ```scikit-learn``` to run the notebook.
      - Start Editing.
## Live demo

[Head to here for live preview](https://colab.research.google.com/drive/1xuvcWLHTTqqblZplYq8r83G6b5BzBycH?usp=sharing)

## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. 
Any contributions you make are **greatly appreciated**. 
Contributing is also a great way to learn more about social coding on Github, new technologies and and their ecosystems and how to make constructive, helpful bug reports, feature requests and the noblest of all contributions: a good, clean pull request.

### Guidelines

- Before starting to work on any issue or feature, open an issue explaining the changes you want to make and wait for any of the project maintainers to assign it to you.
- Once the issue has been assigned, we'd recommend you creating a new branch with name `issue-xx` where xx is the issue number that you were assigned to.
- Use better commit messages that explain the changes you make. View the example below:
    - Bad commit message: `updated readme`
    - Good commit message: `updated contributors list in readme`
- You **should not**, in any case, use resources or code snippets from sources that do not allow their public use.

### Steps to follow for Pull Request

- Create a folder in your repo in the notebook folder, which will contain a new notebook which solves a feature. Note that all issues dont require to create a folder. If required, it will be clearly mentioned.
- Before Submitting the PR, make sure to have a link of colab notebook of the feature/issue solved so that we can check easily. This even applies to those who are doing on anaconda.
## Authors

<a href="https://github.com/DSCKGEC/space-missions/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=DSCKGEC/space-missions" />
</a>

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

