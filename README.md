# infoviz-baby-names

Interactive visualizations of French baby-name data (1900–2020), built with
[Altair](https://altair-viz.github.io/) in Jupyter notebooks.

## Run the project

Cloning the repository and running the following commands is enough to launch it:

```bash
git clone <repo-url>
cd infoviz-baby-names

python3 -m venv venv
source venv/bin/activate          # Windows: venv\Scripts\activate

pip install -r requirements.txt
jupyter lab
```

Then, in the Jupyter Lab tab that opens, open one of the notebooks in
`notebooks/` and run all cells (menu **Run ▸ Run All Cells**):

- `notebooks/Visualization-1.ipynb`
- `notebooks/Visualization-2.ipynb`
- `notebooks/Visualization-3.ipynb`

The dataset (`data/dpt2020.csv`) is included in the repository, so no extra
download is required.

## Project assignment

Check the link: [assignment](https://perso.telecom-paristech.fr/eagan/class/igr204/baby-names)

## Project structure

- `data/` : contains the data files
- `notebooks/` : contains a Jupyter notebook for each visualization
- `requirements.txt` : Python dependencies
