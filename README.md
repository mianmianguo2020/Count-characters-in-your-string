The main idea is to count all the occurring characters in a string. If you have a string like aba, then the result should be {'a': 2, 'b': 1}.
What if the string is empty? Then the result should be empty object literal, {}.
https://www.codewars.com/kata/52efefcbcdf57161d4000091/train/javascript

# Count-characters-in-your-string

function count (str) {  
  // The function code should be here
  let map = {}; //create empty object
  str.split('').forEach((s) => map[s]? map[s]++ : map[s] = 1); //create key value pair
  return map;
}

