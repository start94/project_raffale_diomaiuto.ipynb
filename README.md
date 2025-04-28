# AutoCorrector - Simple Query Correction System

This project implements a basic query correction system using the **Levenshtein distance** algorithm.  
It automatically suggests corrections for misspelled words based on a predefined English dictionary.

## Features
- Calculates the minimum edit distance (insertions, deletions, substitutions) between words.
- Suggests the most probable correct word for each term in a query.
- Handles multi-word queries.
- Tested on realistic typo scenarios.

## Technologies used
- Python (basic programming structures)
- Dynamic Programming (for efficient computation of Levenshtein distance)

## How it works
1. For each word in the input query:
   - Compare it against every word in the dictionary.
   - Calculate the Levenshtein distance.
   - Select the word with the minimum distance.
2. Replace misspelled words with the best match.
3. Return the corrected query.

## Example usage
Input:
