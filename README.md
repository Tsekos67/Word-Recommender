# Word Recommender

A simple **Word Recommender** system implemented in **Java**, using the **Trie data structure**.  
It suggests words based on similarity, making it useful for **autocomplete**, **spell checking**, and **search engines**.

## Features
- **Fast word lookups** using a Trie.
- **Word importance ranking** based on frequency.
- **Smart word suggestions**:
  - Words with similar prefixes.
  - Words with small character differences.
  - Words with slightly different lengths.

## How It Works
1. Loads words from a dictionary file.
2. Reads a text file to rank words based on usage frequency.
3. Suggests **top-k** most relevant words for a given input.

## Technologies Used
- **Java** 
- **Trie Data Structure**
- **Min-Heap** for ranking

