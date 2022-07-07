# Heleno
## Syntax

### Dictionary
#### Pronouns

I : Ko [ko]
You (singular) : Gyo [ɟo]
She : Nyo [ɲo]
He : Ngo [ŋo]
Neutral He : wo [wo]
Informal We : jo [dʒo]
We : Cho [ço]
You (plural) : hyo [hjo]
They : Lyo [ʎo]
Moi : Kè [kɛ]
Toi : Gyè [ɟɛ]
Lui : Ngè [ŋɛ]
Elle : Nyè [ɲɛ]
Neutral Lui : wè [wɛ]
Informal Nous : jè [dʒɛ]
Nous : Chè [çɛ]
Vous : hyè [hjɛ]
Eux : Lyè [ʎɛ]



#### Nouns
Animal : Phooneu [ɸo:nø]
Person : Shèneu [ʂɛnø]
Color : Fôbreu [fɔʙø]
Skin : Shèteu [ʂɛtø]
Bag : Paisheu [paiʂø]
Group : braisheu [ʙaiʂø]
Sun  : Aifeu [aifø]
Moon : Wèfeu [wɛfø]
Salute : Kilyeu [kiʎø]

#### Verbs
To see : Shieni [ʂieni]
To sit : Voti [voti]
To be : Soumi [sumi] 
To have : Pashi [paʂi]
Saluer : Kili [kili]

#### Adjective
Blue : Fôlyu [fɔʎy] 
Red  : Fôsu [fɔsy]
Yellow : Fôju [fɔdʒy]
Green : Fôgu [fɔgy]
Female : Yangu [jaŋy] 
Male : Sangu  [saŋy]
Black Skin : Danshètu [danʂɛty]
White Skin : Kanshètu [kanʂɛty]
Asian Skin : Gyanshètu [ɟanʂɛty]
Together : shalyu [ʂaʎy]


#### Interjection
Bonjour : Aikifi [aikifi]
Bonsoir : Wèkifi [wɛkifi]

#### Postposition
At : ba [ba]
In : ha [ha]
And : sha [ʂa]

### Nouns particule 
After a consonant : eu [ø]
After a vowel : leu [leu]

### Plurality particule
Before a consonant : ngi [ŋi]
Before a vowel : ng [ŋ]

### Adjective particule 
After a consonant : u [y]
After a vowel : shu [ʂy]

### Subject particule
After a consonant :  go|wo
After a vowel : o|yo
(the second is formal)

### Syntax itself 
Adjective : Noun | Verb derived
```rust
match origin {
    noun => before completed word
    verb => after completed word
} 
```
Preposition
Possessor -> Possessee
|         |           |          |         |          |                     |                                    |
|---------|-----------|----------|---------|----------|---------------------|------------------------------------|
| NPosp   | DemN      | NumN     | PossN   | AdjN     | GenN                | NRel                               |
| goat of | this goat | one goat | my goat | big goat | the goat's sandwich | the goat, who eats the sandwich, … |
| NPosp   | DemN      | NumN     | PossN   | NAdj     | GenN                | NRel                               |
| goat of | this goat | one goat | my goat | goat big | the goat's sandwich | the goat, who eats the sandwich, … |
