# learnyouahaskell

#Lessons in haskell

ghci             = haskell console
myfunctions.hs   = haskell file
:l myfunctions   = load haskel file
:r               = reload files
:set prompt "ghci> "
:bowse
:?
:! clear         = clears console

functions: 

>succ 8    #successor
9

min 9 10
max 100 101
:set prompt "ghci> "


ghci> 92 `div` 10   #infix function
9
ghci> div 92 10
9

let lostNumbers = [4,8,15,16,23,42] #define list
[1,2,3,4] ++ [9,10,11,12]    #adding lists
"hello" ++ " " ++ "world"    #concat strings
['w','o'] ++ ['o','t']       #combine characters
'A':" SMALL CAT"    #combine string characters
5:[1,2,3,4,5]      #5 gets added to array
"Steve Buscemi" !! 6  #get 6th index from string
head [5,4,3,2,1]  #get the first element in list
[1..20]           #create a list from 1 to 20
[1,2,3] == 1:2:3:[]   #creates a list

