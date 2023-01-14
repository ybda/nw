# nw
This basic script shows you new random word from local list of words with translation. Might be helpful for learning foreign language. Remove a word from the list when you sure you know it. In this repo for example placed list of Oxford 3000 + Oxford 5000.


## Dependencies: 
[translate-shell](https://github.com/soimort/translate-shell), [bat](https://github.com/sharkdp/bat)


## Installation 
Put bash script "nw" and any list of words (you could use oxford list from this repo) wherever you want and change first few variables as you need. In variables you may want to change paths and languages.


### Usage: nw [OPTION]


  -d	enable dictionary mode for translate-shell
  
  -p	disable bat's paging

  -P	enable bat's paging

  -e	edit dictionary

  -b	edit this bash script

  --help help stuff


#### Examples:

  nw      Basically show new word

  nw -d   Show new word in dictionary mode

  nw -e   Edit your list of words

  nw -b   Edit this bash script

  while true; do nw -P; done   Infinite repeat of new words with paging
