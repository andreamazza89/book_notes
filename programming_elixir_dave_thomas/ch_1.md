- programming should be about transforming data
- comparison with object-oriented programming: classes and objects hide data and 
keep state, sending messages to each other, which alter the state of objects. The
goal is data-hiding. Instead, we want to explicitly take data and transform it as 
required
- pipelining as in Unix language, is awesome. It alows you to have simple small
functions that do one thing well and pass the result to another functions. also 
notice that the functions in the pipeline can work in parallel, so in *a |> b*, 
if the result of a is a list, b starts to consume it while it is being evalutated.
