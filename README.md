# people-based-modelling (Audience Analytics)
One of the important techiques in People based marketing for targeted marketing.

Hi all, This reposirory contains codes for look-a-like modelling, an approach used in People based marketing, to find audiences similar to a particular small set of users, preferably obtained through some other dataset.

This is one of the important steps in Audience analytics for targeting audience for marketing campaigns. Followed later on by A/B tests, or some form of reporting (Closed Loop Reporting, for eg.)

**Objective** :- 
The goal of a look a like model is to find/ score a populus based on the maximum likelihood of behaviors they have over a seed data, something we want to find the users against. This seed data are usually identifiers of a certian set of people, whose behaviors we are trying to map over our dimensions and look for the most likelihood people. Once acheived, we sort them by score, and divide into equal decile segments, and check for lift on seed responses present in each decile, which tells us how many of the base audience subgroups are best for marketing.

This approach helps us to target the best potential customers who can give us better engagement, instead of targeting the entire audience base, for them to selectively get great potential customers, and save cost.

Remember this process is a recreation of PySpark version that used Big Data, as the real world implementation of this works usually on Big Data.
(Although they are pretty similar).


Requirements :
  # Languages
    Python 3.0
    PySpark (latest; for supporting hyperopt)

  # Modules/Libraries :
    numpy
    pandas
    seaborn
    sklearn
    xgboost
    hyperopt
    mlflow (latest ver.)

You might need to install some of these libraries before hand, type in anaconda prompt, or at the start of the notebook :
  pip install pyspark
  pip install hyperopt
  pip install mlflow

Run these on your command line, to install xgboost
  conda install -c conda-forge xgboost
  conda install -c anaconda py-xgboost
