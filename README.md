# Setup
This is under construction at the moment

## Create conda environment

``` bash
git clone https://github.com/The-Coastal-MicroEco-Lab/chironomid.git
cd chironomid
conda env create -f chironomid_paper.yml
conda activate chironomid_paper_v0.01
```

If you require packages not installed in the above environment, add them to chironomid_paper.yml and update the version number.

## Create symlinks in `data` to the location of these files in your system
*note: this is a placeholder, at the moment no external data files need to be added*

1. `<link to genomes>`

Example:

``` bash
cd data
ln -s <path/to/chironomid_mags> chironomid_mags
```

Large files or folders should also be added here and to `.gitignore`.

## Create your analysis file

Source `setup.R` for all inputs. *Note, setup.R doesn't exist yet*

## Output results from your analysis into results folder

Separate analysis subfolders for each subanalysis.

