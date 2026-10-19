<a id="readme-top"></a>

[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]

<br />
<div align="center">
  <a href="https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf">
    <h3 align="center">Sentiment Analysis: BoW vs TF-IDF</h3>
  </a>

  <p align="center">
    Planned comparison of Bag-of-Words and TF-IDF representations on 50k IMDB reviews with logistic regression.
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf"><strong>Explore the repository »</strong></a>
    <br />
    <br />
    <a href="https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/issues/new?labels=bug">Report Bug</a>
    &middot;
    <a href="https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/issues/new?labels=enhancement">Request Feature</a>
  </p>
</div>

<details>
  <summary>Table of Contents</summary>
  <ol>
    <li><a href="#about-the-project">About The Project</a>
      <ul><li><a href="#built-with">Built With</a></li></ul>
    </li>
    <li><a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

## About The Project

This repository is the project space for a fourth-year PFM project at EMSI (semester S2): compare two classical text representations on a sentiment-classification task.

The plan is to train logistic-regression classifiers on the 50k IMDB review dataset, once with Bag-of-Words features and once with TF-IDF features, then compare their evaluation metrics. The repository is currently a scaffold: it contains only a `.gitkeep` placeholder and no implementation.

* Dataset: 50k IMDB movie reviews.
* Representations: Bag-of-Words and TF-IDF.
* Model: logistic regression.
* Evaluation: accuracy, precision, recall and F1 on a held-out split.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

### Built With

This repository is currently a scaffold, so no stack is wired up yet. The planned stack is:

* [![Python][python-badge]][python-url]
* [![scikit-learn][scikitlearn-badge]][scikitlearn-url]
* [![pandas][pandas-badge]][pandas-url]
* [![Jupyter][jupyter-badge]][jupyter-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Getting Started

The repository has no runnable code yet. The steps below only set up a local checkout for future work.

### Prerequisites

* Git
* The toolchain for the planned stack, installed when the implementation starts.

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf.git
   cd sentiment-analysis-bow-vs-tfidf
   ```

2. There is nothing to install or start at this stage.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Usage

There is no executable code in this repository. It currently serves as the project space for the
work described above; the usage instructions will be added together with the implementation.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Roadmap

- [x] Create the repository scaffold.
- [ ] Add the dataset download or preparation script.
- [ ] Implement the BoW + logistic-regression baseline.
- [ ] Implement the TF-IDF + logistic-regression model.
- [ ] Add the comparison notebook and report the metrics.

See the [open issues](https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Top contributors:

<a href="https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf" alt="contrib.rocks image" />
</a>

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## License

This project is not licensed — all rights reserved.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact

Naoufal Elouahabi - [LinkedIn](https://www.linkedin.com/in/elouahabi-naoufal/) - elouahabi-naoufal1@gmail.com

Project Link: [https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf](https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Acknowledgments

* [IMDB Large Movie Review Dataset](https://ai.stanford.edu/~amaas/data/sentiment/)
* [scikit-learn Documentation](https://scikit-learn.org/stable/)
* [Jupyter Documentation](https://docs.jupyter.org/)
* [Img Shields](https://shields.io)
* [Choose an Open Source License](https://choosealicense.com)
* [Best-README-Template](https://github.com/othneildrew/Best-README-Template)

<p align="right">(<a href="#readme-top">back to top</a>)</p>

[contributors-shield]: https://img.shields.io/github/contributors/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf.svg?style=for-the-badge
[contributors-url]: https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf.svg?style=for-the-badge
[forks-url]: https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/network/members
[stars-shield]: https://img.shields.io/github/stars/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf.svg?style=for-the-badge
[stars-url]: https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/stargazers
[issues-shield]: https://img.shields.io/github/issues/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf.svg?style=for-the-badge
[issues-url]: https://github.com/Elouahabi-Naoufal/sentiment-analysis-bow-vs-tfidf/issues
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/elouahabi-naoufal/
[python-badge]: https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white
[python-url]: https://www.python.org/
[scikitlearn-badge]: https://img.shields.io/badge/scikit--learn-F7931E?style=for-the-badge&logo=scikitlearn&logoColor=white
[scikitlearn-url]: https://scikit-learn.org/
[pandas-badge]: https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas&logoColor=white
[pandas-url]: https://pandas.pydata.org/
[jupyter-badge]: https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white
[jupyter-url]: https://jupyter.org/
