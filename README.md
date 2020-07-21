# `spaces2tsv` converts regular text to TSV

1. Trims trailing left and right whitespace.
2. Converts multiple adjacent spaces into a single tab.
3. Pipe it to `column -t` for great good.

## How to use it

         cat my_file.txt | spaces2tsv 
         
The text in the file will be converted into cleanly formatted TSV.
         
