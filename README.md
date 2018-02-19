# huffman code
The following example bases on a data source using a set of five different symbols. The symbol's frequencies are:

Symbol  Frequency
   A       24
   B       12
   C       10
   D        8
   E        8
          ----> total 186 bit
         (with 3 bit per code word)


The two rarest symbols 'E' and 'D' are connected first, followed by 'C' and 'D'. The new parent nodes have the frequency 16 and 22 respectively and are brought together in the next step. The resulting node and the remaining symbol 'A' are subordinated to the root node that is created in a final step.

Code Tree according to Huffman

we use a priority queue on the tree carrying the codes 
Symbol Frequency  Code  Code   total
                       Length  Length
   A      24      0      1      24
   B      12      100    3      36
   C      10      101    3      30
   D       8      110    3      24
   E       8      111    3      24
---------------------------------------
    ges. 186 bit          tot. 138 bit
    (3 bit code)

