# Python for Data Science

## How to setup your Anaconda environment and repository

- Make sure you have **Anaconda distribution**, if not then visit: [Miniconda Installation](https://conda.io/miniconda.html) to install it (Especially for Windows folks).
- For a faster installation on MacOS and Linux distributions, run command (on terminal): `curl -L mini.conda.ml | bash` (Courtesy: [@mikb0b](https://twitter.com/mikb0b))
- Use `git` to clone this repository. Run command: `git clone https://github.com/pratos/python4ds.git`
- This would ask you your github credentials, enter them and the repository to should be downloaded instantly to your repo.
- For any queries regarding conda environment, visit: [Managing Conda Environments](https://conda.io/docs/user-guide/tasks/manage-environments.html)
- You'll encounter `greyatom.yml` file.
- In the terminal run command: `conda env create -f greyatom.yml`
- Once done, run: `source activate greyatom`. Your virtual environment is setup successfully!

##Add packages to Anaconda environment
Using pip command :

Open Anaconda Command prompt as administrator
Use cd\ to come out of set directory or path.
Run pip install command.

Using git :

Download git files
Clone or download git hub files in some directory.
Open Anaconda Command prompt as administrator.
Use cd C:\Users\... to locate downloaded site.
Then run pip install setup.py.

Using wheel :

Download wheel package.
Download binary files or .whl file from authentic website.
Open Anaconda Command prompt as administrator.
Use cd C:\Users\... to locate downloaded site.
Then run pip install ___.whl


Using Conda forge Command :
This type of installation will guarantee that package will be downloaded to the system. Because this type of installation resolves environments, package-package conflicts, etc.

Self Upgrade related packages to the downloading package.
Open Anaconda Command prompt as administrator.
Then run conda install -c conda-forge ___


**NOTE: If you aren't successful with using git then you can view the snippets directly by finding /notebooks folder and clicking on the notebook that you want. Github renders those notebooks automatically in a readable format. Copy and paste the code in your own notebook or python shell**
