# Health-Data-Mining

Problems I faced so far:
 - UnicodeDecodeError: 'ascii' codec can't decode byte 0xe2 in position 1387: ordinal not in range(128) 
 Solved by doing changing these lines
with open('acetazolamide.html') as html_file:
to
with open('acetazolamide.html',encoding="utf-8") as html_file:
and 
with open('acetazolamide.csv', 'w') as csvfile:
to
with open('acetazolamide.csv', 'w',encoding="utf-8") as csvfile:
