- pattern matching is not assignment. In Elixir the = symbol is the match operator
- when pattern matching, a value can be ignored with *_*
- in a pattern, a variable can be reused, and will hold the match value for the 
duration of the match. For instance, *[a, a] = [1, 1]* works, whereas 
*[a, a] = [1, 2]* does not.
- the caret (**^**) symbol forces a variable to match its existing binding instead
of rebinding. For instance: *a = 1;  [1,a,3] = [1,2,3]* both work as a is rebound;
whereas *a = 1;  [1,^a,3] = [1,2,3]* does not as *a* is used in its already bound
value, *1*.
- think of pattern matching as mathematical equations. This is the exact opposite of what you do in an imperative language.

