### The model showed the garden paths deserved further investigation
Andrew Perun, Mandy Osuji, Rishika Veeramachaneni
December 2024

#### Data Preprocessing:
Download [word frequency data](https://github.com/caplabnyu/sapbenchmark/blob/main/Surprisals/analysis/freqs_coca.csv), surprisal [data](https://github.com/SArehalli/SyntacticSurprisal/tree/main/surps) from Arehalli et al.'s supertag-trained models (2023), and [reading times](https://drive.google.com/drive/folders/1g-oyH-XuB2oolo1d8KZfuFtiimuNyhjc) (ClassicGardenPathSet.csv and Fillers.csv) into main directory defined at "base_path" path.
Run the code in LING_380_Preprocess.ipynb to produce fmerged_mod.csv and merged_mod.csv files, to be used in LME experiments.

#### Fitting LME Models:
Define a base path for experiment results in Project_Final.ipynb at "base". More pre-processing to create lagged datasets is necessary before creating new combined datasets and producing reading time predictions.
