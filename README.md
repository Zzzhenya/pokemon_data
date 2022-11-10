Source: https://www.kaggle.com/datasets/rounakbanik/pokemon
This dataset contains information on all 802 Pokemon from all Seven 
Generations of Pokemon.

# 
Type/Strength Matrix

'against_bug',
'against_dark',
'against_dragon',
'against_electric',
'against_fairy',
'against_fight',
'against_fire',
'against_flying',
'against_ghost',
'against_grass',
'against_ground',
'against_ice',
'against_normal',
'against_poison',
'against_psychic',
'against_rock',
'against_steel',
'against_water',
#
Base stats

'base_total', = hp + attack + defense + sp_ttack + sp_defense + speed
'hp',
'attack',
'defense',
'sp_attack',
'sp_defense',
'speed',
'base_egg_steps',
'base_happiness',
'experience_growth',
'capture_rate',
#
About the Pokemon

'name',
'pokedex_number',
'japanese_name',
'generation',
'classfication',
'is_legendary'
'abilities'
'type1',
'type2',
'height_m',
'weight_kg',
'percentage_male',

#

# **Conclusion**


*   The data can be grouped into 3 sections: Pokemon information, strength 
matrix and stats

**Considering pokemon information:**


*   All Pokemon have a pokedex number, a name and a Japanese name.

*   Pokedex number is given to the Pokemon based on the order of 
generation. eg.: First generation Pokemon are numbered first and then the 
second generation...etc.

*   All Pokemon also have a type 1 power out of 18 ('grass', 'fire', 
'water','bug', 'normal', 'poison', 'electric', 'ground', 'fairy', 
'fighting', 'psychic','rock', 'ghost', 'ice', 'dragon', 'dark', 'steel', 
'flying')

*   Not all Pokemon have a type 2 power.

*  Taller Pokemon(height_m) have higher weight (weight_kg), taller Pokemon 
have a lower base_happiness.

*  Some Pokemon do not have a male percentage, weight or height. The 
Pokemon who do not have a height are the same Pokemon who do not have a 
weight.

**Considering strength matrix:**

*   The columns with names starting with "against" describe the effect of 
each Pokemon against another Pokemon with each of type 1 powers. This 
shows that the game involves Pokemon battling against each other. 

*  This matrix probably help users or the game decision making system in 
choosing the opponent Pokemon to fight.(With 
advantage/disadvantage/fairness)

**Considering stats:** 

*  base_total has a positive association with hp, attack, defense, 
sp_ttack, sp_defense, and speed

*  'base_egg_steps', 'base_happiness','experience_growth', 'capture_rate' 
are discrete value fields. There is a small number of clearly defined 
levels/values for these.

> * base egg steps : 1280 , 2560 , 3840 , 5120 , 6400 , 7680 , 8960 , 
10240 , 20480 , 30720
> * base happiness : 0 , 35 , 70 , 90 , 100 , 140
> * experience growth : 600000 , 800000 , 1000000 , 1059860 , 1250000 , 
1640000  

*  Base_egg_steps value is very high in legendary Pokemon (more than 
15000)

*  Base happiness of most legendary Pokemon is very low (0).

*  Even though there are  6 discrete experience growth values, generations 
1, 2, 5, 6, 7 Pokemon only have 4 values. It is only in Pokemon of 
generations 3, 4 the other two values are in use.

*  Type1 and Type2 variation against experience growth, over generations 
is interesting. The common trend being few options are available for 
Type1,Type2 at lower experience growth levels. Though there is no clear 
trend of Type1,Type2 options against experience growth.

*  Dataset can be further analyzed considering legendary pokemon as a 
special scenario. 

**Overall:**

*  It can be concluded that some more game trends may be extracted by 
analyzing the dataset with more specific questions but all game rules 
might not be extracted from the data set. 


