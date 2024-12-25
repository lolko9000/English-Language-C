# English-Language-C
This is an assignment from AUCSC 370 at UOFA.
Changes the english language based on a set of rules.
Uses an implementation of a singularly linked list to manipulate words.
# How the language is changed

Year 1
1. Change all double consonants and spaces to a single letter. Do not remove double line
spacing (i.e. “\n”) or double vowels as in “moose”. For example, “mess” becomes “mes”
and “little” becomes “little”,
Year 2
1. Replace all “c” with “s” if followed by the characters “e”, “i” or “y”; otherwise replace “c”
with “k”. For example, “conceive” becomes “konseive”.
2. Replace all instances of “ph” with the character “f”. For example, “phone” becomes
“fone”.
3. Replace instances of “eigh” with “a”. For example, “neighbor” becomes “nabor”.
4. Replace instances of “gh” at the end of a word with “f”. For example, “trough” becomes
“trouf”.
Year 3
1. Remove the “a” in all instances of “ea” or “oa”. For example, “early” becomes “erly” and
“oats” becomes “ots”.
2. Remove the “u” in all instances of “ui”. For example, “build” becomes “bild”.
Year 4
1. Remove one “e” from the end of words that are more than three characters long, if they
happen to end in “e”. For example, “make” becomes “mak”
© R. Heise 3
2. When a word ends in “ed”, change that to just “d”. For example, “baked” becomes “bakd”.
3. When a word ends in “ing”, change that to just “n”. For example, “singing” becomes
“singn”.
Year 5
1. Replace “tio” with “sho”. For example, “motion” becomes “moshon”.
2. Replace “th” with “z”. For example, “this” becomes “zis”.
3. Remove the “k” from words that start with “kn” and the “w” from words that start with
“wr”. For example “Knit” becomes “Nit” and “Write” becomes “Rite” (or “Rit” if
previous rule from year 4 has applied).

# Requirements
- A C compiler
- A txt file to manipulate

# Instructions
- Open the project file
- Change line 21 to the directory of the txt file to shorten
- Run the project
- Program will then output the shortened txt
