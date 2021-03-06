# TOPSIS_AnmoldeepSingh_101983056



## What is TOPSIS

The Technique for Order of Preference by Similarity to Ideal Solution is a multi-criteria decision analysis method, which was originally developed by Ching-Lai Hwang and Yoon in 1981 with further developments by Yoon in 1987, and Hwang, Lai and Liu in 1993.
## Purpose

Package for Multiple-criteria decision-making using TOPSIS. Requires input file,weights and impacts. Returns a data frame which has score and rank of every label. This package can help improve decision-making.

### Use the package manager [pip](https://pip.pypa.io/en/stable/) to install TOPSIS_AnmoldeepSingh_101983056.

```bash
pip install TOPSIS_AnmoldeepSingh_101983056
```

## Usage

```python
from TOPSIS_AnmoldeepSingh_101983056 import rank_score_Topsis
Topsis_rank("input.csv","1,1,1,2","+,+,+,-")
# Outputs a dataframe with score and rank columns

```
```python
from TOPSIS_AnmoldeepSingh_101983056 import rank_score_Topsis
# if output file name is provided,output file is saved in your current directory
Topsis_rank("input.csv","1,1,1,2","+,+,+,-","output.csv")
# Dataframe named output.csv will be saved in your current directory.

```
## Note

1) Weights and Impacts provided as arguments should be separated by comma's and equal to number of numerical columns.
2) Categorical columns are not supported yet. They should be dropped or feature engineered into numerical columns using techniques like One Hot encoding etc.
3) First column should be label column.

## License
[MIT](https://choosealicense.com/licenses/mit/)
