# Pokemon_Seaborn-Matplotlib
Machine Learning
## Data Description

Dataset comprised of attributes of creatures in the video game series Pokémon. The data was assembled from the database of information found in this GitHub repository -> https://github.com/veekun/pokedex/tree/master/pokedex/data/csv

You can find data on https://data.world/data-society/pokemon-with-stats or
https://www.kaggle.com/abcsds/pokemon

This data set includes 721 Pokemon, including their number, name, first and second type, and basic stats: HP, Attack, Defense, Special Attack, Special Defense, and Speed. It has been of great use when teaching statistics to kids. With certain types you can also give a geeky introduction to machine learning.

This are the raw attributes that are used for calculating how much damage an attack will do in the games. This dataset is about the pokemon games (NOT pokemon cards or Pokemon

#: ID for each pokemon

Name: Name of each pokemon

Type 1: Each pokemon has a type, this determines weakness/resistance to attacks

Type 2: Some pokemon are dual type and have 2

Total: sum of all stats that come after this, a general guide to how strong a pokemon is

HP: hit points, or health, defines how much damage a pokemon can withstand before fainting

Attack: the base modifier for normal attacks (eg. Scratch, Punch)

Defense: the base damage resistance against normal attacks

SP Atk: special attack, the base modifier for special attacks (e.g. fire blast, bubble beam)

SP Def: the base damage resistance against special attacks

Speed: determines which pokemon attacks first each round

Inspiration: The type of a pokemon cannot be inferred only by it's Attack and Deffence. It would be worthy to find which two variables can define the type of a pokemon, if any. Two variables can be plotted in a 2D space, and used as an example for machine learning. This could mean the creation of a visual example any geeky Machine Learning class would love.

## Analysis
###### Bar Chart
* Task 1: There have been quite a few Pokémon introduced over the series' history. How many were introduced in each generation?
* Task 2: Each Pokémon species has one or two 'types' that play a part in its offensive and defensive capabilities. How frequent is each type? 
###### Histogram
* Task 1: Pokémon have a number of different statistics that describe their combat capabilities. Here, create a histogram that depicts the distribution of 'special-defense' values taken
###### Scales and Transformation
* Task 1: There are also variables in the dataset that don't have anything to do with the game mechanics, and are just there for flavor. Try plotting the distribution of Pokémon heights (given in meters).
* Task 2: In this task, you should plot the distribution of Pokémon weights (given in kilograms).
