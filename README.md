# assignm1.What does an empty dictionary's code look like?
Ans: An empty dictionary is often represented by two empty curly brackets
d = {} or d = dict()
2.what is the value of dictionary value with key 'foo' and the value 42 ?
Ans: {'foo':42}
3.What is the most significant distinction between a dictionary and a list?
Ans: Dictionaries are represented by {} where as listed are represented by []
The Items stored in a dictionary are Unordered , while the items in a list are ordered
4.What happens if you try to access spam ['foo'] if spam is {'bar':100} ?
Ans: we will get a keyError KeyError: 'foo'
5.if a dictionary is stored in spam,what is the difference between the expressions 'cat' in spam and 'cat' in spam.keys() ?
Ans: There is no difference . The operator checks whether a value exits as a key in the dictionary or not
6.if a dictionary is stored in spam,what is the difference between the expressions 'cat' in spam and 'cat' in spam.values() ?
Ans:'cat' in spam checks whether there is a 'cat' key in the dictionary, while 'cat' in spam.values() checks whether there is a value 'cat' for one of the keys in spam.
7.what is a shortcut for the following code ?
if 'color' not in spam: spam['color'] ='black'
Ans: spam.setdefault('color','black')
8.How do you 'pretty print' dictionary values using which modules and function ?
Ans: we can pretty print a dictionary using three functions
1.	by using pprint() function of pprint module
•	Note: pprint() function doesnot prettify nested dictionaries
2.	by using dumps() method of json module
3.	by using dumps() method of yaml module


ent_5
