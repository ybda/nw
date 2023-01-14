# nw
New random word from local list of words with translation. Might be helpful for learning foreign language. Remove a word from the list when you sure you know it

Usage: nw [OPTION]
New random word from a list of words. Might be helpful for learning foreign language. Remove a word from the list when you sure you know it

  -d	enable dictionary mode for translate-shell
  -p	disable bat's paging
  -P	always bat's paging
  -e	edit dictionary
  -b	edit this bash script

Examples:
  nw      Basically show new word
  nw -d   Show new word in dictionary mode
  nw -e   Edit your list of words
  nw -b   Edit this bash script
  while true; do nw -P; done   Infinite repeat of new words with paging
