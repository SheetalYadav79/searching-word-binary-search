# Word Search and Highlighting

This project searches for a specific word within a text file and highlights it if found. It uses binary search for efficient searching in a sorted list of words.

## Features

- **Binary Search**: Efficiently finds a word within a sorted list of words.
- **Highlighting**: Highlights the searched word within the content.

## Usage

1. **Place your text file**: Ensure you have a text file (e.g., `daa.txt`) in the same directory as the script.
2. **Run the script**:
   ```bash
   python searching_word.py
   ```
3. **Provide inputs**:
   - Enter the filename when prompted.
   - Enter the word you wish to search for.
4. **Output**: The script will display the word's position (if found) and print the highlighted content.

## Functions

- `binary_search(words, target)`: Performs binary search on a sorted list of words.
- `highlight_word(content, word)`: Highlights the target word within the content.

## Requirements

- Python 3.x

## Example

For a `daa.txt` file containing:
```
The quick brown fox jumps over the lazy dog
```

**Search Query**: `previous`

**Output**:
```
Word 'fox' found at index: 2
Highlighted content:
The quick brown __**fox**__ jumps over the lazy dog
```
