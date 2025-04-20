Now we are going to run a Jupyter notebook. This where we will run most of our Python scripts.

First we need to get the code for this unit onto our local machines.

### GitHub App

By now, you should all have your GitHub app and credentials running. If you are still having trouble, please reach out!


Clone the Repo
- Go to repo (https://github.com/yadlra/pervasive-media-nlp.git)
- Click Clone or download
- Open in App
- Choose an install location on your computer (by default this is a Github folder)

Get updates (in App)
- Click Fetch origin
- Click Pull origin

### Running Jupyter Notebook

#### From Terminal/Console
1. ``conda activate nlp`` (or a different name if your environment isn't called __nlp__)
2. Type `jupyter notebook`
3. Use the file explorer that opens in the browser to locate the downloaded Github repo

What has happened here is we have launched the notebook program from the terminal, and we have then opened a web browser and navigated to localhost:8888.  

It's important to understand this split, the program is running in the terminal, and we have a view on it through the browser. This client – server set up means that if we close the browser, the notebook doesn’t close. It also means we can run notebooks on servers in the cloud, and then interact with them through the browsers on our local machines.  

### Troubleshooting Python

- Which install of Python are you using? `which python` (unix) `where python` (windows)
- Which version of Python are you using? `python —-version`
- Which install of pip are you using? `which pip` (unix) `where pip` (windows)
- Which version of package is installed using pip? `pip show [package name]`
- Which install of Anaconda are you using? `which conda` (unix) `where conda` (windows)
- Which version of package is installed using Anaconda? `conda list [package name]`