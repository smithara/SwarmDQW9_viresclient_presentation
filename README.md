# SwarmDQW9_viresclient_presentation

View the slides at https://smithara.github.io/SwarmDQW9_viresclient_presentation/viresclient.slides.html

To generate the pdf go to https://smithara.github.io/SwarmDQW9_viresclient_presentation/viresclient.slides.html?print-pdf and print it as a pdf

View the Jupyter notebook at https://nbviewer.jupyter.org/github/smithara/SwarmDQW9_viresclient_presentation/blob/gh-pages/viresclient.ipynb


## Technical setup

Use [RISE](https://rise.readthedocs.io) to run the presentation interactively, but will require a little setup:
 - This requires a Jupyter notebook installation as well as RISE (e.g. `conda install -c conda-forge rise`)
 - clone this repository, `git clone https://github.com/smithara/SwarmDQW9_viresclient_presentation.git`
 - NB: RISE is not yet compatible with jupyter lab, but will work from the classic notebook view

To generate the static HTML:
```
jupyter nbconvert --to slides viresclient.ipynb
```

Temporary requirements:

```
conda install -c conda-forge rise --use-local
pip install --user ~/SwarmPyFAC/.
```