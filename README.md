                                                                    Movie-Recommendation-system
Basic info about this project:

Movie recommendation system is performed on the TMDB Dataset  on the basis of content based filtering this project gives us top five movies form our recent search to develop the to acquire the customer. 

library used in this projects:
Pandas
Numpy
Sklearn
NLTK

steps use for processing:

we have use 2 data set and merge them to using pd.merge operation and then started the exploring the size and shape og the given data.

then we started the data cleaning process like transformation of some columns , removing unnecessary data.

after that we have perform the EDA(Exploratory Data Analysis) for taking the insights,at the end we perform the feature extraction to get the important features for our recommendation system and create the new pandas dataframe from it.

after that we perform the some transformation on the gener column because it is the main aspect of this project based on this colunmn we are going to recommend the movies to the users.

then we fetch the director name from the columns by creating function.
after that we have use the stemming form the NLTK library for wraping the words ex=['Loved ','Loving ','Lovely'] to "Love".

the to convert the text we use the Countvectorizer form the sklearn library .

to show the /create the relation ship betwwen the movies we have used the Cosine_similarity
then at the end we create the recommendation function we gives five movies as output.

Web application :

after that project we dump the files using pickle for the web application  which we use by creating the streamilt in the pycharm enviromnent 
