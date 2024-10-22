## Machine Learning and Physics, Sheet 1

### Setup
Install [anaconda](https://docs.anaconda.com/anaconda/install/index.html),
or [miniconda](https://docs.conda.io/en/latest/miniconda.html) if you prefer a more lightweight setup.

Install [git](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)
(On windows, this is included in anaconda and will be available in the anaconda prompt). 
There are many tutorials online, e.g. [this one](https://www.notion.so/zarkom/Introduction-to-Git-ac396a0697704709a12b6a0e545db049).

Clone this repo and navigate into the folder for sheet01:
```bash
git clone https://github.com/sciai-lab/mlph_w24.git
cd mlph_w24/sheet01
```

Or alternatively, download it as zip.

Next, to set up your conda environment, run
```bash
conda env create --file=environment.yml
```
and to activate it
```bash
conda activate mlph
```
Then you can start jupyter (run `jupyter notebook`) and open sheet01.ipynb, 
which you should use as the basis for the solution of the practical excercises.


### Hand in
 Hand in both your jupyter notebook, and an exported pdf (File -> Download as -> pdf). 
 If you encounter problems exporting the pdf like this, please print your notebook to pdf and hand this in.
