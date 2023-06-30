# NAct: The Nutrition and Activity Ontology
**NAct** is designed to drive personalised nutritional and physical activity recommendations and effectively
support healthy living, through a reasoning-based AI decision support system. NAct coalesces nutritional, medical, behavioural and lifestyle indicators with dietary and physical activity directives.
___
## IRI
<https://purl.org/nact>

## Website
<https://nutritionactivityontology.github.io/nact/> 

## Current version
v1.9.5

## Licence
Published under [Creative Commons Attribution Share Alike 4.0 International](https://creativecommons.org/licenses/by-sa/4.0/legalcode)
____
## About
The Nutrition and Activity Ontology (NAct) is designed to drive personalised nutritional and physical activity recommendations and effectively support healthy living, through a reasoning-based AI decision support system. NAct coalesces nutritional, medical, behavioural and lifestyle indicators with dietary and physical activity directives.

## News
NAct Ontology scientific publication accepted at FOIS 2021!

## Authorship and attributions
### Author 
Dorothea Tsatsou

*Information Technologies Institute ([ITI](https://www.iti.gr/))* -
*The Centre for Research and Technology Hellas ([CERTH](https://www.certh.gr/))*

### Acknowledgements
The work (since v1 and until v1.9.1) has been funded by the H2020 IA project [PROTEIN - PeRsOnalized nutriTion for hEalthy livINg](https://protein-h2020.eu/).

#### Main health and nutrition expertise contribution
Elena Lalama 

*[Charité – Universitätsmedizin Berlin](https://www.charite.de/en/)*

#### Scientific supervision
Dr. Kosmas Dimitropoulos,
Dr. Petros Daras 

*Information Technologies Institute ([ITI](https://www.iti.gr/))* -
*The Centre for Research and Technology Hellas ([CERTH](https://www.certh.gr/))*

## Reference
Tsatsou, D., Lalama, E., Wilson-Barnes, S.L., Hart, K., Cornelissen, V., Buys, R., Pagkalos, I., Balula Dias, S., Dimitropoulos, K. and Daras, P., 2021. NAct: The Nutrition & Activity Ontology for Healthy Living. In *Formal Ontology in Information Systems* (pp. 129-143). IOS Press.

## Publications
Tsatsou, D., Lalama, E., Wilson-Barnes, S.L., Hart, K., Cornelissen, V., Buys, R., Pagkalos, I., Balula Dias, S., Dimitropoulos, K. and Daras, P., 2021. NAct: The Nutrition & Activity Ontology for Healthy Living. In *Formal Ontology in Information Systems* (pp. 129-143). IOS Press.

Stefanidis, Kiriakos, Dorothea Tsatsou, Dimitrios Konstantinidis, Lazaros Gymnopoulos, Petros Daras, Saskia Wilson-Barnes, Kathryn Hart et al. "PROTEIN AI Advisor: A Knowledge-Based Recommendation Framework Using Expert-Validated Meals for Healthy Diets." Nutrients 14, no. 20 (2022): 4435.
____
## Changelog
*30 June 2023*
- Renamed some entities for better linguistic/semantic alignment of axioms. Notably:
  - allowedFood <-- excludeFood
  - allowedActivity <-- excludeActivity
  - allowedNutrient <-- restrictNutrient
  - hasPreference <-- hasInterest
- SKOS annotation properties now used to mark such changes (as the above) and provide alternate labels to entities.
- Further (lesser) improvements in entity annotations.

## Planned improvements
*For next release - version 2.0*
- Update documentation
- Further annotation improvements
- Eliminate all (or most) class equalities. Synonymous entities to be assigned **only one** (preferred) label and alternative labels (synonyms) to be moved to annotations as skos:altLabel

## Ways you can contribute
- Refine entity annotations (e.g. add language where not mentioned, add synonyms as skos:altLabel in English)
- Add entity alt labels in other languages
- Provide info on malformed semantics (as GitHub comments)
- Provide feedback on marked todos (as GitHub comments - see todos in entity annotations)

### Notes:
The purpose of alt labels is to enable classification of different expressions of entities in the main (English) or other languages to one unique representative entity that describes the same concept/relation. 

No expansion of the ontology will be pursued at this point in order to maintain reasoning efficiency. Expansion suggestions may be offered via GitHub comments and will be considerd. 