# Spotify-Sorting-Hat

Project aimed to see if we could analyse audio features for different playlists and train a model to predict where tracks would fall when tested against an unseen playlist

1. Retrieve data from playlists using Spotipy API packages
2. Exploratory Data Analysis
3. Executed Classification models (Logistic Regression, K-NN, Random Forest, SVC) to with highest classification predict ~ 84% 

Summary:

Overall, the model was able to classify songs with reasonable accuracy in our training model although further improvements can be made in future revisions by incorporating more features with stronger correlations. The model can be improved by incorporating more features such as genre or artist name, however for an initial model I thought that would be 'cheating' as the inclusion of these aforementioned features would make it too easy and the focus was more on seeing if we could diffrentiate songs using the audio features. 

The model could also have been improved if we chose two playlists which were more dissimilar, the two playlists we chose can be somewhat comparable in terms of their style and underlying audio features (hence the low feature importance of many features aside from speechiness) which meant that determining differences between those two playlists were difficult, if we chose a playlist with a 'hip-hop' genre to it against a rock or country playlist I predict the model would perform much better.

Other interesting points to raise was the inclusion of popularity or not. Popularity seemed to be a strong feature in separating the two playlists however, given that the popularity of the song can change over time, I'm not sure whether it makes sense to include it as a feature.
