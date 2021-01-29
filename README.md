# lab-sumstats

This lab will introduce students to Jupyter Notebooks
as they use one to write functions to generate summary statistics.

## Jupyter notebooks setup (for Mac)
You can install Jupyter (and some helpful extensions) using pip in the Terminal:

    $ pip install --upgrade -r requirements.txt
    $ jupyter contrib nbextension install --user
    $ jupyter nbextension enable toc2/main && jupyter nbextension enable collapsible_headings/main && jupyter nbextension enable hide_input/main && jupyter nbextension enable varInspector/main && jupyter nbextension enable hinterland/hinterland && jupyter nbextension enable python-markdown/main && jupyter nbextension enable spellchecker/main && jupyter nbextension enable exercise2/main 

## Jupyter notebooks setup (for WINDOWS)
You can install Jupyter using pip in the Terminal:

    $ sudo apt update
    $ sudo apt install python3-pip
    $ pip3 install --upgrade pip
    $ pip3 install --upgrade --user -r requirements.txt
    $ vim ~/.bashrc

Inside bashrc, scroll to the very end of the document. Press `I`.
Then add:

    alias jupyter-notebook="~/.local/bin/jupyter-notebook --no-browser"

Once completed, press `ESC` button.

    $ source ~/.bashrc

Now, install some extensions to make your notebooks nicer:

    $ jupyter-notebook contrib nbextension install --user
    $ jupyter-notebook  nbextension enable toc2/main && jupyter-notebook nbextension enable collapsible_headings/main && jupyter-notebook nbextension enable hide_input/main && jupyter-notebook nbextension enable varInspector/main && jupyter-notebook nbextension enable hinterland/hinterland && jupyter-notebook nbextension enable python-markdown/main && jupyter-notebook nbextension enable spellchecker/main && jupyter-notebook nbextension enable exercise2/main 
