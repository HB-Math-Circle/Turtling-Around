# Turtle Graphics for HB Math Circle

So I am not sure I understood the requirements. _A_ said maybe Colab notebook? _I_ said something he can run locally, and J said just tell me what to get ready.
This can run offline in jupyter notebook, or it can run in vscode, and probably more? Oooh! It looks like it works ok also in codespaces...

probably if I put enough exclammation points in there it can run in Colab too? (need to install dependencies )

## Getting Started: Method 1

1. download or clone the code
2. open the folder in vscode
3. open a terminal pane within vscode (so it starts with its current working directory being `Turtling-Around/`)
4. make a python virtual environment to keep the dependencies from mucking up other python stuff you might be doing. from the terminal in that directory,
    `python -m venv .venv`
5. activate the virtual environment
    1. mac or linux: `source .venv/bin/activate`
    2. windows (I think): `.venv\Scripts\Activate.ps1`
6. install the python required dependencies: `pip install -r requirements.txt`
7. open the [Intro](./Intro.ipynb) or [OGIntro](./OGIntro.ipynb) notebook and explore!

### Helpful VSCode Extensions for this
1. [Python](https://marketplace.visualstudio.com/items?itemName=ms-python.python)
2. [Jupyter](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)