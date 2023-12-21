#Song themes over time: comparing the lyrics of the top 10 songs of 2013 and 2013

# Corpus Description
This corpus contains the lyrics of 20 songs - the top 10 Billboard songs from 2013 and 2023. It was created to explore thematic changes in popular music over the past decade, with a focus on love, relationships, and the theme of party and celebration.

## Target Audience
The dataset is intended for musicologists, cultural analysts, sociologists, linguists, and data scientists interested in the evolution of pop culture, thematic trends in music, and linguistic analysis within song lyrics.

## Intended Use
The corpus is designed for research and educational purposes, allowing for the study of linguistic and thematic elements within popular music across a ten-year span.

## Text Selection Criteria
The songs were selected based on their ranking in the Billboard Top 10 charts for the years 2013 and 2023, ensuring that the dataset represents influential and popular music from these periods.

## Data Collection Process
Lyrics were collected from licensed online music databases and lyric repositories. Metadata was created according to the criteria for this assignment.

## Cleaning and Preprocessing
The lyrics underwent several preprocessing steps:
- Encoding normalization to UTF-8 for consistency.
- Tokenization and lemmatization using spaCy to standardize word forms.

## Annotations
Annotations were added to identify and count thematic keywords, with the following tools employed:
- spaCy for NLP tasks such as tokenization and lemmatization.
- Custom Python scripts for keyword frequency analysis.

## File Format and Columns Description
The corpus files are formatted as follows:
- `.txt`: Raw lyrics of each song.
- `.csv`: Song metadata, which includes:
  - `Filename`: Identifier corresponding to the song's text file.
  - `Song`: The title of the song.
  - `Artist_s`: The performing artist(s).
  - `Year`: The year the song was a top hit.
  - `Genre`: The genre classification from Billboard.
  - `Text`: Unedited lyrics collected from the website.
  - `Doc`: Texts processed using spaCy.
  - `Tokens`:Tokenized song lyrics.
  - `Lemmas`: Lemmatized song lyrics.
  - `POS`:The types of proper nouns.
  - `Proper_Nouns`: The words identified as proper nouns.
  - `Named_Entities`: The types of the entities.
  - `NE_Words`: The words assigned to the entity types.
    
## Additional Notes
- The corpus is limited to songs with English lyrics.
- Thematic analysis is based on keyword frequency and does not account for semantic depth or context.
- Further research could expand the analysis to include sentiment, emotion, and more nuanced thematic exploration using advanced NLP techniques.

