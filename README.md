# shitty-programming-language
A meme programming language I created using shell script

The interpreter starts searching for a main function, so make sure you created one

# Commands
- diga -> prints something in the stdout
- calc -> do math calculations
- var  -> declare a variable (syntax: var name = value)
- return: -> return a value from a function
- print -> prints something pre formatted in the stdout

# Print variables in diga or print command
- To print a variable value, encapsulate the variable between $()
      var name = Luis
      diga "The name is $(name)"

- To print a function return (still not working with user-made function), encapsulate the function between $<>
      var age = $<calc 18+1>
      diga "The age is $(age)"

# Functions

You can create functions too, using: 

    function_name(param1, param2){
      function_body
    }

and call them using:    function_name param1, param2
