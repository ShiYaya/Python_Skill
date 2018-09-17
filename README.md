# Python_Skill
* append() 函数直接将object整体当作一个元素追加到列表中，而extend()函数则是将可迭代对象中的元素逐个追加到列表中。
In [1]: lt1=['A','B','C']

   ...: lt2=['D','E','F']
   
   ...: lt1.append(lt2)#将lt2整体当作一个元素追加到到lt1中
   
   ...: print(lt1)
   
   ...: lt3=['A','B','C']
   
   ...: lt2=['D','E','F']
   
   ...: lt3.extend(lt2)#将lt2中每个元素逐个追加到t3中
   
   ...: print(lt3)
   
   ...:
['A', 'B', 'C', ['D', 'E', 'F']]
['A', 'B', 'C', 'D', 'E', 'F']

