This project contains examples of common JS Array functions. 

This project originates from and is largely based on a tutorial from Wes Bos.

This project demonstrates examples of common array functions such as the following: 

* filter, which returns a subset array. See examples 1 and 6.

* map, which returns the same number of elements as the original array, but transformed.
  See examples 2 and 6.

* sort, which returns the same number of elements, but rearranaged (ie. sorted). The
  function used by sort always takes two elements, and the function compares those two 
  elements. If a positive value is returned, it implies the first value is larger. If a 
  negative value is returned, it implies the first value is smaller. The array returned 
  from sort puts the lowest value items first, highest value items last in the resulting 
  array. 
  See examples 3, 5, and 7 for sort.

* reduce, is useful to "build something on top of each entry in the array". And if you found 
  that definition to be nebulous, so did I. Here is another way to view it: A way to do a 
  forloop on the array to arrive at a cumulative total based on some common property from 
  each element in the array. Still nebulous? Yeah, me too. The good news is the code in 
  this project contains both a basic example (see example number 4 in the code) and a more 
  complex example (see example number 8 in the code). 

* Usage of chaining a couple array functions (see example 6 in the code).

* Usage of a string split (see example 7 in the code).

* Usage of "contains", really known as "includes". See example 6.

* Usage of anonymous arrays. See example 7.

* Usage of console.table.

* Usage of arrow functions (ie. (param1, param2) => {//function body}). 
