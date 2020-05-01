# Word Classifier - Is it gibberish?

## Turkish
This project is done in order to propose a solution to distinguish junk words from genuine words. The algorithm works based on **4 rules** and utilizes a .csv file as a genuine Turkish word dictionary (2235 words). The algorithm has an average accuracy rate of **93.48%**, which is significantly high.

### Rules
- If a word contains non-alpha character after leading and trailing characters are removed, it is junk.
- If a word contains *3 or more* consecutive vowels or consonants, it is junk.
- If the median of probabilities of two consecutive letters being consecutive is *greater* than the thereshold, the word is genuine.
- If the median of probabilities of two consecutive letters being consecutive is *less* than the thereshold **and** the median of euclidean distances of consecutive letters are less than the thereshold, the word is junk.


## English
This project is done in order to propose a solution to distinguish junk words from genuine words. The algorithm works based on **4 rules** and utilizes a .csv file as a genuine English word dictionary (21666 words). The algorithm has an average accuracy rate of **84.68%**, which is significantly high.

### Rules
- If a word contains non-alpha character after leading and trailing characters are removed, it is junk.
- If a word contains *4 or more* consecutive vowels or consonants, it is junk.
- If the median of probabilities of two consecutive letters being consecutive is *greater* than the thereshold, the word is genuine.
- If the median of probabilities of two consecutive letters being consecutive is *less* than the thereshold **and** the median of euclidean distances of consecutive letters are less than the thereshold, the word is junk.


# Datasets
Datasets were provided by a private company which is why publicly sharing them is not allowed. However, new dictionary files will be created by myself and the repo will be updated accordingly. Until then, you can try the code yourself if you have your own datasets! Please enjoy :)
