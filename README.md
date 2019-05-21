# TeamTingus

# Introduction/Modified Proposal

https://www.kaggle.com/c/pubg-finish-placement-prediction
Our team has chosen the Kaggle challenge of predicting player placements in the Player Unknown
Battle Grounds (PUBG) video game. The project link is given above. By using the algorithms and
techniques learned in this class, we can use various methods to determine the relevance of different
aspects of the player statistics, and decide on how different features affect the scoring. A possible
challenge would be that the players performance is not strictly linked to either pure skill or their
in-game statistics, and instead has an immeasurable and more random quality. We hope to show that
this is not the case and that the players’ observable statistics have a large bearing on performance.

## 1.1 Why Use Machine Learning

Machine learning techniques are appropriate for this data because we must predict the final placement
of players using their statistics gathered in the game. We must see how different features such as the
number of eliminations, the amount of boosts used, etc impact the possibility of a player winning.
Noting patterns manually given a small enough set of data is personally intensive, and the accuracy
becomes limited to the size of training set a person is able to analyze. However, a machine learning
algorithm begins in the training effort how we do, by knowing nothing about these patterns, then
gaining knowledge in a measurable way, and can eventually come to classify the data to a notable
accuracy.

## 1.2 Dataset Acquisition

The dataset is available on the main Kaggle project page, under the “Data” tab. We are provided
with two sets of data; the training set, and the test set, which contain a large number of anonymous
PUBG game stats from around 65000 games, formatted so that each row contains one player’s
post-game stats. The data comes from matches of all types: solos, duos, squads, and custom; there is
no guarantee of there being 100 players per match, nor at most 4 players per group. So while a player
may choose different strategies to play in solo games compared to games with 4-person teams, we
must account for all data equally in order to determine common elements of success for all of these
game modes. The data itself is provided by the PUBG Developer API.

## 1.3 Initial thoughts on Possible Approaches

Our goal is to implement a Multi-layered Neural Network for this dataset. This type of neural
net requires minimal pre-processing, making it optimal for the large amount of data and is able to
accommodate for non-linear trends in the data. We will start off with a simple, single layered Neural
Network baseline and train our data using that. Once we are able to do that, we intend to build our
MNN from the baseline.
31st Conference on Neural Information Processing Systems (NIPS 2017), Long Beach, CA, USA.

# The Benefits/Drawbacks of this Project

This project intrigued us mainly because we are involved in this gaming community. It seemed an
interesting idea to apply the machine learning techniques we have discovered in this class, and to
explore statistics for predictions that we otherwise would not have thought about. The idea to predict
how a player will place is a very good idea, and can have a great impact on competitive matches where
professional gamers can train using the data provided by this exploration. They can, for example, see
where their skills/play-style is lacking and improve on that, since there will be evidence to suggest
that improving on a certain feature heavily increases the likelihood of winning. This can be also used
internally by the PUBG Development team if they were ever to introduce an actual ranking system
where the player base is grouped into tiers based on their performance and their predicted placements.
In addition, if factors such as boosters and other health regenerating items were the soul determiner
of success in a match, it may be worthwhile for the developers to reduce the impact of such items so
as to create a more even playing field among the players. We also realised from the start that this
operation is very time expensive, and there are a lot of steps needed to be done before we can even
begin implementing our algorithms.
