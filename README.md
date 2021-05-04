# Hachidaishu classical Japanese poetic vocabulary dataset
## Hilofumi Yamamoto, Ph.D. (Tokyo Institute of Technology)

### Data offset

Example: \# 1 Kokinshu
```
01:000001:0001 A00 BG-01-1630-01-0100 $BG/(B $B$H$7(B $BG/(B 02 
01:000001:0001 A10 BG-01-1911-03-1800 $BG/(B $B$H$7(B $BG/(B 02 
01:000001:0002 A00 BG-08-0061-07-0100 $B$N(B $B$N(B $B$N(B 61 
01:000001:0003 A00 BG-01-1770-01-0300 $BFb(B $B$&$A(B $BFb(B 02 
01:000001:0004 A00 BG-08-0061-05-0100 $B$K(B $B$K(B $B$K(B 61 
01:000001:0005 A00 BG-01-1624-02-0100 $B=U(B $B$O$k(B $B=U(B 02 
01:000001:0006 A00 BG-08-0065-07-0100 $B$O(B $B$O(B $B$O(B 65 
01:000001:0007 A00 BG-02-1527-01-0100 $BMh(B $B$/(B $BMh(B 47 
01:000001:0008 A00 BG-03-1200-02-0900 $B$L(B $B$L(B $B$L(B 74 
01:000001:0008 A10 BG-09-0010-01-0100 $B$L(B $B$L(B $B$L(B 74 
01:000001:0008 A20 BG-09-0010-03-0200 $B$L(B $B$L(B $B$L(B 74 
01:000001:0009 A00 BG-09-0010-04-0300 $B$1$j(B $B$1$j(B $B$1$j(B 74 
01:000001:0010 B00 BG-01-1950-14-0100 $B0lG/(B $B$R$H$H$;(B $B0lG/(B 02 
01:000001:0010 C00 BG-01-1950-01-0300 $B0l(B $B$$$A(B $B0l(B 19 
01:000001:0010 C01 BG-01-1630-01-0100 $BG/(B $B$H$7(B $BG/(B 02 
01:000001:0011 A00 BG-08-0061-10-0100 $B$r(B $B$r(B $B$r(B 61 
01:000001:0012 A00 BG-01-1642-02-0100 $B5nG/(B $B$3$>(B $B5nG/(B 02 
01:000001:0013 A00 BG-08-0061-04-0100 $B$H(B $B$H(B $B$H(B 61 
01:000001:0014 A00 BG-08-0065-14-0100 $B$d(B $B$d(B $B$d(B 65 
01:000001:0015 A00 BG-02-3120-01-0100 $B8@$U(B $B$$$U(B $B8@$U(B 47 
01:000001:0016 A00 BG-03-3012-03-2600 $B$`(B $B$`(B $B$`(B 74 
01:000001:0016 A10 BG-09-0010-02-0100 $B$`(B $B$`(B $B$`(B 74 
01:000001:0017 B00 BG-01-1641-02-0100 $B:#G/(B $B$3$H$7(B $B:#G/(B 02 
01:000001:0017 C00 BG-03-1000-01-0100 $B:!$N(B $B$3$N(B $B:!$N(B 57 
01:000001:0017 C01 BG-01-1630-01-0100 $BG/(B $B$H$7(B $BG/(B 02 
01:000001:0018 A00 BG-08-0061-04-0100 $B$H(B $B$H(B $B$H(B 61 
01:000001:0019 A00 BG-08-0065-14-0100 $B$d(B $B$d(B $B$d(B 65 
01:000001:0020 A00 BG-02-3120-01-0100 $B8@$U(B $B$$$U(B $B8@$U(B 47 
01:000001:0021 A00 BG-03-3012-03-2600 $B$`(B $B$`(B $B$`(B 74 
01:000001:0021 A10 BG-09-0010-02-0100 $B$`(B $B$`(B $B$`(B 74 
``` 
### A line consists of 7 columns separated by spaces.
1. 1st column consists of 3 fields: 1) anthology, 2) number of poem, and 3) token ID.
The anthology ID indicates respectively: 01..Kokinshu, 02..Gosenshu, 03..Shuishu, 04..Goshuishu, 05..Kin'yoshu, 06..Shikashu, 07..Senzaishu, and 08..Shinkokinshu.
1. 2nd column indicates type of token: A type is a single token; B type is a compound token; C type is a breakdown of B type.
A00 indicates a single token; A01 indicates a single token and has another meaning; 
B00 indicates a compound token; B01 indicates a compound token which has another meaning;
C00 indicates the first element of the B00/B01.. breakdown; C01 indicates the second element of the B00/B01.. breakdown.
1. 3rd column: classification ID based on semantic categories according to Bunruigoihyo.
  yamagen2009ae
  yamagen2007de
1. 4th column indicates original (appearing form).
1. 5th column indicates kana writing form.
1. 6th column indicates lemma.
1. 7th column indicates a Chasen POS number.

