# 3rd-A-5th-question
 
A) input
    3
    1 2
    2 2
    8 7
     
    2
    3 3
    4 4
    
    the output had to be 
    {1:2,8:7,3:3}
    [[3,3],[2,9]]
    {2,[2,9]}
    but this is not what we get.
    

  B)  if k in data1:
            v1 = data1[k]
        if v1 != v2:
            dupKeys[k] = [v1, v2]
            del data1[k]
        else:
            data1[k] = v2
      return dupKeys

  C) 
      TEST CASE 1:
       4
       1 2
       3 3
       3 8
       4 9
       2
       3 3 
       4 4
       
       TEST CASE 2:
       4
       1 2
       2 2
       3 3
       4 19
       2
       3 13
       4 19
        
       TEST CASE 3:
       the test case written in 5a,whichbbreaks the initially written code can we written.
       
