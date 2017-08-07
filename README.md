## What is it?
This scripts was my first attempt to work with python, so they have a hundreds of problems that I hope to fix if not forget about them.

## How to use it?
formatText.py -- take from the file with text English and Russian words and write them into output.txt file in output folder.

    Example: python formatText.py "file_with_text.ext"

    Output: /output/output.txt -- where words separated by space
    
With optional *-lowercase* argument:

    Example: python formatText.py "file_with_text.ext" -lowercase

    Output: /output/output_lwc.txt -- words separated by space, and transfer in lowercase

word_freq.py -- compare two words together in given file from the previous script output or just a word separated by space.

    Example: python word_freq.py firstWord secondWord "file_with_words.ext"
    
    Output: A graph where a word with higher frequency appears a top of the graph.
