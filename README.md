# zwordle

Introducing tcode ZWORDLE, a handy WORDLE Assistant! 

Specify black, orange and allowed letters for a letter position, and it generates a list of possible words. 

Have fun ... and amaze your friends with your Wordle skills! :-)

![Selection Screen](/zwordle_selection_screen.jpg)

![Output](/zwordle_output.jpg)

# Word List

ZWORDLE uses the list of 5-letter words found here: [https://www-cs-faculty.stanford.edu/~knuth/sgb-words.txt](https://www-cs-faculty.stanford.edu/~knuth/sgb-words.txt)

# Word Score

[Marc Bernard](https://github.com/mbtools) added a feature to "score" words based on the letter Frequency for English Dictionary Words.
See: [Source of Letter Frequency for English Dictionary Words](https://en.wikipedia.org/wiki/Letter_frequency)

# God Mode

Run ZWORDLE in "God Mode" to get the word of the day right away :-) How is that possible, you ask? Read this [article](https://arstechnica.com/gaming/2022/01/beware-trolls-are-out-to-spoil-tomorrows-wordle-for-you) for an explanation.

# Installation

## Easiest Method

Use [abapGit](https://abapgit.org/)!

## Manual Installation

1. Tcode SE38: Create program ZWORDLE.
2. Copy-paste the [ZWORDLE source code](https://github.com/hdegroot/zwordle/blob/main/src/zwordle.prog.abap) into the just created program.
3. Populate Text Symbols and Selection Texts (see selection screen screenshot). (Annoying, yes I know. That's why you should use abapGit!)
3. Tcode SE93: Create transaction code ZWORDLE.






