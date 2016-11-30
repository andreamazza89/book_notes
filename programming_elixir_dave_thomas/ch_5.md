- with default parameters, if you pass in more parameters than required, Elixir 
updates the default using the excess input
- nesting modules is purely for namespacing, in fact, when you define a module 
nested inside another, under the hood Elixir just writes a module called *Module1.Module2*
- loading functions,macros,etc from other modules can be done with *import*. *Alias* 
lets you rename the module on import and *require* loads all the macros from the 
module
- all names starting with a capital letter are internally converted to an atom,
 with *Elixir.* prefixed to it


