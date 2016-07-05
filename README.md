# Collaborating on Code
## Tutorial of Git and Github
html and basic directory structure template for (relatively) easily creating reveal.js slideshows with all dependencies locally so you do not need an internet connection while presenting.

## Basic installation:
1. Clone the reveal-presentation-template repository

    ```
    git clone https://github.com/harmslab/reveal-presentation-template
    ```
2. Grab reveal as submodule:

    ```
    cd reveal-presentation-template
    git submodule init
    git submodule update
    ```
3. If you want to run on local server, follow Reveal's instructions for node and grunt [here](https://github.com/hakimel/reveal.js/)
4. If you want mathjax locally, download the latest release (https://github.com/mathjax/MathJax/archive/master.zip) and unzip it into the reveal.js base directory.  This should create a directory called `MathJax-master`.
