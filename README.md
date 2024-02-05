# C Language Algorithms and Problem Sets

This repository contains various C programs designed to solve specific problems. Below, you'll find brief descriptions of each program along with instructions on how to compile and run them.

## wav_reverse.c / wav_volume.c

![WAV Reverse](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/83f24ea7-db7a-4159-a3a4-47289da04a45)


### Description:
- This program reverses the audio data in a WAV file, effectively playing the audio backward and change wav volume.

### Usage:
- To compile:
  `gcc -o reverse wav_reverse.c wav.c`
  
- To run:
  `reverse INPUTFILENAME OUTPUTFILENAME`

### Dependencies:
- Make sure you have GCC installed to compile the program.

  

## image_filter_manipulation.c

![Image Filter and Manipulation](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/47d6e04c-2543-4792-bb45-f5a507c55d25)

### Description:
- This program applies various filters to a BMP image, including grayscale, sepia, blur, reflective, and edge detection.

### Usage:
- To compile:
  `gcc -o filter image_manipulation.c filter.c`
  
- To run:
  `filter [-FILTER_NAME] [INPUT_BMP] [OUTPUT_BMP]`
  (Replace `[-FILTER_NAME]` with one of the filter options: -g, -s, -r, -b, -e)

- You can alternatively run the provided `compile.bat` file to compile the code.

### Dependencies:
- The program requires a BMP image as input and uses the BMP file format for image processing.

  

## word_speller.c

- ![Word Speller](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/770508cc-684a-4362-8afc-4590b6f29324)
  
- ![spell c check](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/a867c2be-dc22-4136-969d-3ea86dfc897f)


### Description:
- This program checks the spelling of words in a text file using a dictionary implemented with a trie data structure.

### Usage:
- To compile:
  `gcc -o speller spell_check.c dictionary.c`
  
- To run: `speller [DICTIONARY NAME] [TEXT NAME]`
  (Replace `[DICTIONARY NAME]` with the name of the dictionary file and `[TEXT NAME]` with the name of the text file)

- You can alternatively run the provided `compile.bat` file to compile the code.

### Dependencies:
- The program requires a dictionary file and a text file as input.

  

## wordle.c

![Wordle](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/9c459e99-5188-4044-8ee5-1ee18cc61c37)

### Description:
- This program implements the game Wordle, where the player must guess a secret word within a limited number of tries.

### Usage:
- To compile:
  `gcc -o wordle wordle.c`
  
- To run: `wordle WORDSIZE`
  (Replace `WORDSIZE` with the length of the word to guess, e.g., 5 for a five-letter word)

### Dependencies:
- No external dependencies are required.

  

## trie-insert-search.c

### Description:
- This program implements a trie data structure for efficient word insertion and search operations.
- 
![trie](https://github.com/Baniya-sen/C-Lang-Algo-Sets/assets/144620117/7f2b2de4-fb84-4bc0-9aee-b5694f55594a)


### Usage:
- To compile:
  `gcc -o trie_insert_search trie-insert-search.c`
  
- To run: `trie_insert_search [Text_File]`
  (Replace `[Text_File]` with the name of the text file containing words to insert into the trie)

### Dependencies:
- The program requires a text file containing a list of words to populate the trie.

  

## Instructions for New Users:
1. Clone or download this repository to your local machine.
2. Navigate to the directory containing the C problem sets.
3. Follow the usage instructions provided for each program to compile and run them.
4. Make sure to provide the necessary input files and command-line arguments as specified in the usage instructions.
5. Enjoy exploring and experimenting with the C programs!
