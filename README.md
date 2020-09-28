# Yahoo-Financial-Text-Analysis
Analysing articles in Yahoo!Finance

# Text Analysis
 
## Objective
Using Python programming language and any publicly available libraries analysing articles in Yahoo!Finance area (https://finance.yahoo.com/). The code is able to process first page articles from available current set
 
## Named Entity Extraction
Extracting all available entities (person names, organizations, locations, medical codes, time expressions, quantities, monetary values, percentages, etc). Building Key/Value pairs for numeric values (quantities, monetary values etc) - for example: revenue =  $123,456. Building weight of each "key" based on frequency of appearance in currently analyzed articles.
 
## Relation Extraction
Identifying relation between entities (Affiliation, Location, Part of, Social). Identifying if entity is object or subject (Subject does the action. Object is the center of action.)
 
## Events Identification
Based on the article content identifying if it cover specific event or not.
 
## Sentiment Analysis
Analyzing each paragraph of the article and providing sentiment score for it based on Financial context of it.
