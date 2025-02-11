# Nilearn tutorial for EBRAINS PFC Workshop

March 16, 2023 (11:45–13:30)

This repository holds the materials for the Nilearn tutorial for the EBRAINS PFC workshop in Paris.
[Click here to access the official website of the PFC workshop](https://www.humanbrainproject.eu/en/education-training-career/workshops/pfc/)

## Running the notebooks online on EBRAINS

You can run these notebook on EBRAINS Lab following this link: [nilearn PFC materials](https://lab.ebrains.eu/hub/user-redirect/git-pull?repo=https%3A%2F%2Fgithub.com%2Fymzayek%2Fnilearn-PFC-Workshop&urlpath=lab%2Ftree%2Fnilearn-PFC-Workshop%2F)


## Local installation instructions:

If you would like to run the tutorial locally you will need a few things:

- **Python 3:** Most recent systems come with Python pre-installed. **Nilearn supports Python>=3.7.**
- **git:** `git` is the most popular VCS (version controlled software). Although we recommend having `git` installed to download these notebooks, you can also use the download button on GitHub. You can learn more on `git` [here](https://git-scm.com/book/en/v2/Getting-Started-What-is-Git%3F).

If you have these tools installed, you can download the repository with the notebooks:

```
$ git clone https://github.com/ymzayek/nilearn-PFC-Workshop.git
$ cd nilearn-PFC-Workshop
```

Although not required, we recommend creating and activating a virtual environment before installing the requirements. The example shows how to do this using Python venv module but you can use any environment management tool you're used to:

```
python3 -m venv nilearn_tutorial
source nilearn_tutorial/bin/activate
```

Install the requirements (this will install nilearn and its dependencies, as well as Jupyter-notebooks):

```
$ pip install -r requirements.txt
```

Launch the notebooks:

```
$ cd Notebooks
$ jupyter-notebook
```

 The notebooks are based on previous nilearn tutorials:

+ - [Nilearn tutorial EUGLOH 2021](https://github.com/NicolasGensollen/nilearn-tutorial-EUGLOH-2021) given by [Nicolas Gensollen](https://github.com/NicolasGensollen)
  - [Resting State and Brain Connectivity 2018 satellite workshop](https://github.com/illdopejake/RS2018_Nilearn_tutorial) given by [Gaël Varoquaux](https://github.com/GaelVaroquaux) and [Jacob Vogel](https://github.com/illdopejake).
  - [NHA 2020 tutorial](https://emdupre.github.io/nha2020-nilearn/01-data-structures.html) given by [Elizabeth Dupre](https://github.com/emdupre).
