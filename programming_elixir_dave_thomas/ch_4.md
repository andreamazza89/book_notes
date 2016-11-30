- Elixir has 3 main types of types: valus, system and collection. and functions
- 1000 is the same as 1_000
- tuples are normally under 5 elements. If you are writing a longer tuple, you 
probably want to use something else, like maps or structs
- lists are linked lists. It is expensive to randomly access a certain value in the middle of the list.
- Lists have a really cool performance characteristic: 
if you want the tail of a list, since the list is immutable, there is no copying or manipulation involved, as all you need is a pointer to the tail of the list.
- as a rule of thumb, use keyword-lists for parameter options, and maps when you want an associative array.

