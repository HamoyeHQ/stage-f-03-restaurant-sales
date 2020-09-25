# Dataset Folder
This folder consists of the datasets needed for this project i.e the train and test datasets. It also consists of a sample submission file. All the files are in csv format, hence they can be loaded into the working environment using the read_csv() function in pandas:

```python
    import pandas as pd
    # read the train.csv file
    train = pd.read_csv('train.csv')

    # load the train.csv file
    train = pd.read_csv('test.csv')

    # load the sampleSubmission.csv file
    train = pd.read_csv('sampleSubmission.csv')

```
> # Note
>
If you are working outside the data folder, then you need to specify the relative path of the dataset you are trying to load within the read_csv function. For example, say I created a file called `regression_model.py` inside the `model` folder, loading the train dataset from within this file would look something like:

```python
# model/regression_model.py
import pandas as pd
# load the train.csv file
train = pd.read_csv('../data/train.csv')
```
