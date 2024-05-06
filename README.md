# A01639055---Lab4---Analizador-l-xico

lex lex_analyzer.l

gcc lex.yy.c -ll

cat example.ac | ./a.out

cat test.txt | ./a.out

python3 code_generator.py > example.ac

### Input:
//4GORBR1AI5

f q

i t

q = 39

u = o / 84

p d

### Output:
COMMENT

floatdcl id

intdcl id

id assign inum

id assign id div inum

print id
