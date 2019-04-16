# in-place selection sort

Rearrange
an unordered `ArrayList<Integer>`
and use it as the data in an `OrderedList_inArraySlots`.

The re-use is probably contrary to Java's conventions
for its built-in classes. But as a pedagogical tool,
it has the advantage of allowing
the User program to check that the sort
is done in-place.

## count the cost

0. If the number of the elements in the input triples,
the time required to run the reigning champ algorithm
will grow by a factor of three. The reigning champ algorithm iterates through the list, visiting each element once, and it has three times as many elements to visit.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the number of times that the reigning champ algorithm
will be invoked 
will grow by three times. The reigning champ algorithm is invoked once for each index in the list, and a list three times as long has three times as many indexes on which the reigning champ is to be invoked.
[Justify, in about 2 sentences.]

0. If the number of the elements in the input triples,
the time required for the selection sort
will grow by ninefold. The reigning champ algorithm is invoked three times as much and takes three times longer per invocation. Therefore it take nine times as long.
[Justify, in about 2 sentences.]
