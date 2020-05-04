# hello-python
python code

import re
a = 'python00liuyuwoainijava@@phpjiushi屎'

c = re.findall('[a-z]{3,6}',a)
print(c)

a1 = 'pythonpythonpythonpythonpythonpythonpythonjs'
c1 = re.findall('(python){2}(js)',a1)   # [] 和() 的区别，前者是‘或’关系，后者是‘且’的关系
print(c1)


