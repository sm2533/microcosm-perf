# microcosm-perf
A performance oriented implementation of the microcosm algorithm (with brute forcing) to aid in solving the microcosm puzzle.<br><br>See https://www.youtube.com/watch?v=HT-y6Bi5mSY to learn about the puzzle, and head over to [r/solvingmicrocosm](https://www.reddit.com/r/solvingmicrocosm/)  to join the discussion.

This is just derfarctor's version with a slight tweak/modification

**To run the program, you will need a copy of a word list (one word per line) named words.txt inside the same directory as the program.**

### Features
- Interactive console application UI
- Nemesizer shift option
- Flexible input whereby a number of potential lines can be specified for each page, a number of potential keys, or none at all in which case all are used in brute forcing
- Multithreading
- Logging
- NEW - Goes through the inputted pages, however eventually runs through every possible combiantion in an order where combinations which are closer to the inputted version get done first. In otherwords after it has finished running through combinations inputted, the code runs through all pages, assuming you are wrong, then it runs through every pair of pages etc theoretically until every combination has been done (or the more likely option, the program is closed)

<br>
Python implementation by nemesizer: https://github.com/nemesizer/microcosm
