## What is it?
The scripts were my first attempt to work with python, so they have a hundred of problems that I hope to fix if not forget about them.

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