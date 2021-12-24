# Analysis-on-Movie-lens-dataset


The 1 million Movie Lens data set was used, to work on features such as ‘Age’, ‘Genres’, ‘Gender’, ‘Occupation’, ‘Title’. Used pandas to merge and manipulate the data, from this we got an overview of the dataset. 
Pandas pd. merge function was used to combine all three tables. 

Stored the combined dataset in an HDF5 file so that it can be accessed efficiently

# Findings

1. People from age group 18-25 tends to rate movies more

2. Distribution of ratings for Females and Males from age group of 50+ tends positive ratings.

3. Retired people or people from customer service are easy to please

4. Older people are hard to please (>45)

5. Females over 55 of age give higher rating

6. Given that the genre of the movie is 'Sci-Fi', we can predict the we can predict the ratings given by one gender to predict the rating given by the other gender

7. Given that the age group of the user is 25, we can predict the ratings given by one gender to predict the rating given by the other gender

8. Given that we know the genre of the movie is Sci-Fi and the age group of the user is 18 or 35, we can predict the the ratings given by one gender to predict the rating given by the other gender

# Conclusion

• After observing and analyzing the data we can say that movie ratings are hugely affected by people’s personality and their identity.

• All the factors, especially gender, age, occupation, etc. mostly affect the ratings in some way or the other.

Some interesting things that we observed were that:

• Male watch more drama movies as compared to Female which conflicts with the popular belief.

• People with technical background or interest in technology are more probable to watch Sci-Fi movies if recommended. This can be used by a movie or streaming company for their recommendation system.
