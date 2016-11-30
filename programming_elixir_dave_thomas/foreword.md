- Point for functional programming: this is driven by the change in hardware: 
memory is now super-cheap/available, however processor speed is not growing as 
fast as before. Computers have increasing numbers of cores, so in order to grow
with hardware, software needs to use these. State limits multi-core operations 
and slows them down, as the core all need to access the same representation of
state.
- “A functional programming language lets us think in terms of functions that 
transform data. This transformation never mutates data. Instead, each application 
of a function potentially creates a new, fresh version of the data. This greatly 
reduces the need for data-synchronization mechanisms.”
