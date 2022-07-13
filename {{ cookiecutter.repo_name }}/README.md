<div id="top"></div>
<!--
*** Thanks for checking out the {{cookiecutter.project_name}} webscraping bot. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D 
*** Replace {username} with username
-->


[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]



<!-- PROJECT LOGO -->
<br /> 
<div align="center">
  <a href="https://github.com/{username}/{{cookiecutter.project_name}}">
    <img src="references/figures/{{cookiecutter.project_name}}_logo.png" alt="Logo" width="500" height="250">
  </a>

  <h3 align="center">{{cookiecutter.project_name}}</h3>

  <p align="center">
    Try demo for {{cookiecutter.project_name}} if applicable. 
    <br />
    <a href="https://github.com/{username}/{{cookiecutter.project_name}}"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/{username}/{{cookiecutter.project_name}}">View Demo</a>
    ·
    <a href="https://github.com/{username}/{{cookiecutter.project_name}}/issues">Report Bug</a>
    ·
    <a href="https://github.com/{username}/{{cookiecutter.project_name}}/issues">Request Feature</a>
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#project-organization">Project Organization</a></li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]](https://{{cookiecutter.project_name}}.com/example)

{{cookiecutter.description}} 

Use the `README.md` to get started.

<p align="right">(<a href="#top">back to top</a>)</p>



### Built With

This section should list any major frameworks/libraries used to bootstrap your project. Leave any add-ons/plugins for the acknowledgements section. Here are a few examples.

* [Python](https://www.python.org/)


<p align="right">(<a href="#top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

This is an example of how you may give instructions on setting up your project locally.
To get a local copy up and running follow these simple example steps.

### Prerequisites

This is an example of how to to use the software for initial setup. This can replace the installation process.
* {{cookiecutter.project_name}}
  ```sh
  sh {{cookiecutter.project_name}}/setup.sh
  ```

### Installation

_Below is an example of how you can instruct your audience on installing and setting up your app. This template doesn't rely on any external dependencies or services._


1. Clone the repo
   ```Git Clone
   git clone git@github.com:{username}/{{cookiecutter.project_name}}.git
   ```
2. Virtual Environment
   ```sh
   mkvirtualenv
   ```
3. Install pip
   ```py
   python3 -m pip install --upgrade pip
   ```
 4. Install requirements
   ```py
   pip install requirements.txt 
   ```
 5. Add dependencies
   ```py
   pip freeze > requirements.txt
   ```

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- USAGE EXAMPLES -->
## Usage

This space is used to show useful examples of how a project can be used. Additional screenshots, code examples and demos work well in this space. You may also link to more resources.

_For examples, please refer to the [Documentation]("https://github.com/{username}/{{cookiecutter.project_name}}". After completing installations. 

   Use environment verses downloading all dependencies
   ```sh
   pipenv shell 
   ```

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- Project Organization -->
## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    │
    ├── docs               <- A default Sphinx project; see sphinx-doc.org for details
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. Naming convention is a number (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `1.0-jqp-initial-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
    │                         generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to download or generate data
    │   │   └── make_dataset.py
    │   │
    │   ├── features       <- Scripts to turn raw data into features for modeling
    │   │   └── build_features.py
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │   ├── predict_model.py
    │   │   └── train_model.py
    │   │
    │   └── visualization  <- Scripts to create exploratory and results oriented visualizations
    │       └── visualize.py
    │
    └── tox.ini            <- tox file with settings for running tox; see tox.readthedocs.io


-------- 

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [x] Add Changelogs
- [x] Add back to top links
- [ ] Add Additional Templates w/ Examples
- [ ] Add "components" for other related MXA to MXC datapump issues until the product is sunsetted. 


See the [open issues](https://github.com/{username}/{{cookiecutter.project_name}}/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/{your_feature_name}`)
3. Commit your Changes (`git commit -m 'Add some {your_feature_name}'`)
4. Push to the Branch (`git push origin {your_feature_name}`)
5. Open a Pull Request

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Project Link: [https://github.com/{username}/{{cookiecutter.project_name}}](https://github.com/{username}/{{cookiecutter.project_name}})

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

Use this link to get a list resources you might find helpful. It also contains a list of resources I would like to give credit to. 

* [REFRENCES](https://github.com/{username}/{{cookiecutter.project_name}}/references/references.txt)

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
[contributors-shield]: https://img.shields.io/github/contributors/{username}/{{cookiecutter.project_name}}.svg?style=for-the-badge
[contributors-url]: https://github.com/{username}/{{cookiecutter.project_name}}/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/{username}/{{cookiecutter.project_name}}.svg?style=for-the-badge
[forks-url]: https://github.com/{username}/{{cookiecutter.project_name}}/network/members
[stars-shield]: https://img.shields.io/github/stars/{username}/{{cookiecutter.project_name}}.svg?style=for-the-badge
[stars-url]: https://github.com/{username}/{{cookiecutter.project_name}}/stargazers
[issues-shield]: https://img.shields.io/github/issues/{username}/{{cookiecutter.project_name}}.svg?style=for-the-badge
[issues-url]: https://github.com/{username}/{{cookiecutter.project_name}}/issues
[license-shield]: https://img.shields.io/github/license/{username}/{{cookiecutter.project_name}}.svg?style=for-the-badge
[license-url]: https://github.com/{username}/{{cookiecutter.project_name}}/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: [https://linkedin.com/in/donleygustave](https://www.linkedin.com/in/donleygustave/)
[product-screenshot]: references/figures/{{cookiecutter.project_name}}_product.png


<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookie-data-science/">cookiecutter data science project template</a>. #cookiecutterdatascience</small></p>
