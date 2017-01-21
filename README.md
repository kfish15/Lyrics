
## Synopsis

Counts the number of times a word is used in a given song or album. This only works for lyrics on the website Genius. 

## Process
For an individual song, all that needs to be done is to insert the url to the song from the website Genius into the program and it will output the song name, the song artist, the words said in the song, and how many times each word is said. 

## Problems
1) This currently counts all words in the within a particular HTML tag of the page regardless of whether they are in the song or not. In particular, words like "Intro" and "Verse" could end up being counted despite not actually being part of the song. I've taken out some common words to remove (line 59).

2) I infrequently run into errors related to ASCII conversion on some albums. I could put in a try-catch to just not read in those pages, but am hoping to eventually figure out an actual solution so that those pages can still be read in. 

## Next Steps
1) Put everything into functions (should have been done at the start, I know)

2) Create a script to run the album skeleton on a long list of albums to see if it produces errors unrelated to problem #2. I've tested it on 10-20 pages and it works for those, but want to see how it does on 100+ pages. 

3) Fix remaining problems

## Author/Maintainer
Kody Fisher (@kfish_15)

Would love to hear your comments or suggestions!


