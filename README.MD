###### TITANIC CLASSIFICATION #####

### Task

 For this project i am  to get a titanic dataset from any source,analyse the data and build a model or system that wil help tell us wether a person will be save from sinking or not. We are also going to provide whaat factors will likely lead to socio-economique status, age, gender and more.


## Description

 i loaded the titanic data set from a git hub ripository snd sotresd in a data frame, from there, the data copied the data was copied so that we could use a copy of the dataframe to work with.

The data was displayed and information on the dataset was also displayed so as we could see which type of data we are working with and the number of lines  of our dataframe.

Exploratoiry data anlysys was made and a correlation matrix was plote to see the correlation between each column in our dataframe. some visualisations was made to see the distribution of Survived with ages, gender(sex), Pclass to see the average ages or gender of passenger who survived or not to help us bluid our model.

The data was pretreted this encoding the nominal values so that it could be used easily for training our model. Deleting nan values for columns with more than 50% of the data and for columns with less were just deleted.

The data was spleated into target and features then the train data was normalised to train the models.
we trained 3 model for and compared thier precissions and accuracy score.Logistical reression, SVM, and Random Forest(RF). each model was optimised using a cross validation and grid search.

the optimal model (RF) was used to test with external data.


## Instalation

 The installation of the project is made by installing all neccessary libries need after that you just have to load a data set with thesame features used to train the model and run each cell to see the output.

## Usage

 run each cell of the file.