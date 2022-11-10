Source: https://www.kaggle.com/datasets/rounakbanik/pokemon

This dataset contains information on all 802 Pokemon from all Seven 
Generations of Pokemon.

#

Variables:

name: The English name of the Pokemon
japanese_name: The Original Japanese name of the Pokemon
pokedex_number: The entry number of the Pokemon in the National Pokedex
percentage_male: The percentage of the species that are male. Blank if the 
Pokemon is genderless.
type1: The Primary Type of the Pokemon
type2: The Secondary Type of the Pokemon
classification: The Classification of the Pokemon as described by the Sun 
and Moon Pokedex
height_m: Height of the Pokemon in metres weight_kg: The Weight of the 
Pokemon in kilograms
capture_rate: Capture Rate of the Pokemon baseeggsteps: The number of 
steps required to hatch an egg of the Pokemon
abilities: A stringified list of abilities that the Pokemon is capable of 
having
experience_growth: The Experience Growth of the Pokemon
base_happiness: Base Happiness of the Pokemon
against_?: Eighteen features that denote the amount of damage taken 
against an attack of a particular type
hp: The Base HP of the Pokemon
attack: The Base Attack of the Pokemon
defense: The Base Defense of the Pokemon
sp_attack: The Base Special Attack of the Pokemon
sp_defense: The Base Special Defense of the Pokemon
speed: The Base Speed of the Pokemon
generation: The numbered generation which the Pokemon was first introduced
is_legendary: Denotes if the Pokemon is legendary.

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
