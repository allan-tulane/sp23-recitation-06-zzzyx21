# CMPS 2200 Recitation 6
## Answers

**Name:**________Kyra Zhu_________________


Place all written answers from `recitation-06.md` here for easier grading.



- **d.**

File | Fixed-Length Coding | Huffman Coding | Huffman vs. Fixed-Length
----------------------------------------------------------------------
f1.txt    |125                     |826                |6.608
alice29.txt    |511                     |676374                |1323.628
asyoulik.txt    |476                     |606448                |1274.050
grammar.lsp    |532                     |17356                |32.624
fields.c    |630                     |56206                |89.216

I think there is a consistent trend. Huffman cost is a much more than fixed-length cost for all the cases and as fixed-length cost increases, huffman cost increases.


- **e.**

If every character had the same frequency, the characters can be considered to be paired arbitrarity and a balanced tree could be established bottom up. It wuold be logarithmic in alphabet order with different depth.
