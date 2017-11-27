## What is it?
Mostly it is a my attempt to work with a Python, not a first though but not a last also, this two scripts was written to help me
identify clone words and display them in a graph (which is broken). The scripts was made when I work with a translation on a 
ProtonMail project in Crodwin.

Functions of the scripts can be easily replaced by Notepad++ with great combination of key **CTRL+F** but I tried anyway, seriously!

## How to use it?
**formatText.py** -- take from the file with text English and Russian words and write them into an output.txt file in output folder.

    Example: python formatText.py "file_with_text.ext"

    Output: /output/output.txt -- where words separated by a space
    
With optional *-lowercase* argument:

    Example: python formatText.py file_with_text.ext -lowercase

    Output: /output/output_lwc.txt -- words separated by a space, and transfer in lowercase

**word_freq.py** -- compare words together from a given file of previous script output or just from a file where words separated by a space.

*-l, --list* -- is required. 

    Example: python word_freq.py file_with_words.ext -l firstWord secondWord thirdWord
    
    Output: A graph where a word with higher frequency appears a top of the graph.

    Bug: A graph created for each word and joined in one, from which appears high spikes in the graph.
