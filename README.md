# Column-Transformer-in-Machine-Learning

Dataset Link: 'https://raw.githubusercontent.com/campusx-official/100-days-of-machine-learning/main/day28-column-transformer/covid_toy.csv'

# feature engineering:
  **feature Transform**
          |--Feature Scaling
          |--Encoding

          Data
        /     \
    Numaric   Categorical
              /    \
          Nominal  Ordinal




# How to import ordinal encode,OneHotEncoder
from sklearn.preprocessing import OrdinalEncoder,OneHotEncoder


# How to import Column Transform
from sklearn.compose import ColumnTransformer
