<h1 align="center" style="border-bottom: none;">👥 Facebook Messages Analyzer 💬</h1>
<h3 align="center">You know you can quantify your friendships 👀</h3>

## Tabel of Contents
- [Getting Started](#getting-started)

## Getting Started
- You will need to download your Facebook messages history. You can do this by going to Settings → Your Facebook Information → Download Your Information. Deselect everything other than Messages and create the file. Make sure to specify the file type as **JSON**. This may take up to a few hours to prepare depending on how big the file is.

## Setting up python environment
I recommend you install miniconda.
https://docs.conda.io/en/latest/miniconda.html

Once you've installed miniconda, navigate to the wherever you cloned this repo and run the following three commands
```
$ conda create --name fb --file requirements.txt

$ source activate fb

$ jupyter notebook facebook.ipynb
```

This should open up the jupyter noteboot. All you need to do now is just run each cell from top to bottom. There will be a cell to fill out your name and some other options.

See this link for setting up a virtual environment.
https://uoa-eresearch.github.io/eresearch-cookbook/recipe/2014/11/20/conda/

See this stackoverflow thread for how to use the requirements.txt file.
https://stackoverflow.com/questions/7225900/how-to-install-packages-using-pip-according-to-the-requirements-txt-file-from-a
