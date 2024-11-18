mh\_answers
===========

Answers from the MIT Mystery Hunt

This repository contains a list of answers from the MIT Mystery Hunt
from 1994-present.  A few answers from 1998 are missing.

The files `mystery????.txt` contain a list of puzzle answers from the
corresponding year, as well as the type of puzzle.  Usually the type
is "Puzzle" or "Meta", although there are some exceptions as described
below.
Notes on puzzles from individual hunts:
* 1999 - One of the metapuzzles yielded a (presumably unintentional) misspelled answer.  The correct spelling is used here.
* 2003 - In one round, the puzzle answers were physical objects.  These
answers are not included, but the metapuzzle answer is included.
Answers to training puzzles are classified as "Training".  Both
untrained and trained answers are included and classified as "Puzzle".
* 2005 - In one round, the puzzle answers were physical objects.  These
answers are not included, but the metapuzzle answer is included.
* 2006 - The ante puzzles are classified as "Ante".
* 2008 - One answer was given away for free; it is classified as "Free".
* 2012 - Some cluephrases (which were not puzzle answers) are included;
these are classified as "Clue".
* 2014 - The mid-hunt runaround puzzles are classified as "Runaround".
* 2020 - The tiger answers are not included in `mystery2020.txt` since they could not be called in; however, they are included in `metapuzzles.yml`.
* 2021 - The answers from the 100000 procedurally generated puzzles in the Infinite Corridor round are not included.  The metapuzzle answer is included in `mystery2021.txt`.  Some answers in another round needed to be backsolved; these are classified as "Meta" in `mystery2021.txt` but appear as normal answers in `metapuzzles.yml`.  One answer was given away for free; it is classified as "Free".  Attack of the Lobsters is classifed as a regular puzzle despite being bolded on the hunt's puzzle list.
* 2022 - Answers that could be called in on the Once Upon a Time in the Quest page are classified as "Quest".  Some puzzles had multiple answers that were supposed to be called in simultaneously, but these are listed as separate answers.  Fruit Around is classified as "Puzzle" rather than "Meta" since its minipuzzles do not have separate pages.
* 2023 - Some answers consisted of multiple lines of text; lines are separated by a forward slash.  A few answers could be called in twice, but they are only listed once.
* 2024 - The answers from the procedurally generated puzzles in the Hydra round are not included.

The file `metapuzzles.yml` contains a list of metapuzzles from
2000-present and the answers that feed them.  The `tag` field refers
to the identifier used by /dev/joe's puzzle index.  For example, a
puzzle with the tag `mit20001m` is indexed at the page
http://devjoe.appspot.com/huntindex/puzzle/mit20001m.
As mentioned above, in 2003 and 2005, there were rounds where the
answers were physical objects; the corresponding metapuzzles are not
included in `metapuzzles.yml`.

The order of the puzzle answers in `metapuzzles.yml` does not necessarily reflect how they were presented during the hunt; in fact they may be in an order that makes the metapuzzle easier to solve.

Acknowledgments
===============
Thanks to Alex Schwendner and Elia Robyn Lake for compiling lists of
answers from 2004-2008 and 2011-2012, respectively.

See also
========
https://puzzles.mit.edu/answers.tsv has answers from 1999-2016.
