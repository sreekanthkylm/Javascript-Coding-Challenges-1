# Javascript Coding Challenges
 A collection of JavaScript coding challenges

1)Find Highest Occurrence

Create a functon that takes an array, fnds the most repeated elements within the array and
returns them in an array (order not important). The functon should work for integers and
strings.

Examples
[ 2 , 3 , 2 , 5 , 6 , 7 , 2 ] [ 2 ] ➞
[ 1 , 2 , 3 , 3 , "a" , "b" , "b" , "c" ] [3 , "b" ] ➞
[ "it" , "keeps" , "coding" , "on" , "or" , "it" , "gets" , "the" , "hose" ] [ "it" ] ➞

Notes
Don't let integers become strings and/or string become integers in the result.

2)Object Diffing

Background

Ever wonder how tools like git parse your source code and determine what you've added
and subtracted from the last commit?
Build diffing tool to compare JavaScript obcects full of fruit data.

Diffing an Object

Given JavaScript obcects like this

newCode = {
 apples: 3,
 oranges: 4
}
oldCode = {
 apples: 3,
 grapes: 5
}

Create a functon that returns an array containing the obcect dif like this

dif(newCode, oldCode)

// returns:

// [ ['-', 'grapes', 5], ['+', 'oranges', 4] ]

