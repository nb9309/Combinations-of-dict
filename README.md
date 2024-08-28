# Combinations-of-dict

1)dict in dict (possible)
eg: d = {5:23,10:'hii',15 : {15:25, 12:'hii'},20:'goo'}

2) set in dict (possible)
   eg: d = {10:'hii', 20:'hoo', 25:{20,1,3,4},30:7.8}

3)tuple in dict (possible)
  eg:  d = {10:'hii', 20:'hoo', 25:(20,1,3,4,'hii'),30:7.8}

4)list in dict (possible)
  eg:  d = {10:'hii', 20:'hoo', 25:[20,1,3,4,'hii'],30:7.8}

5)dict in set (possible)
 eg:   d = {10:'hii', 20:'hoo', 25:[20,1,3,4,'hii'],30:7.8}

code:
 d5[-2]['school'] = 'nagarjuna'
 print(d5)
output:(2, 'hii', 8.9, {'name': 'naresh', 'marks': 90, 'school': 'nagarjuna'}, (3+4j))

6)dict in set (not possible)
output: Type error: unhasable : dict

7)dict in list (possible)
eg: [2, 'hii', 8.9, {'name': 'naresh', 'marks': 90, 'school': 'nagarjuna'}, (3+4j)]

