# Objectify
Turns dictionary objects into classes




# Example
 ```python
 dictionary = {
     "name": "Steve",
     "age": 18,
     "dob": "08/23/2000",
     0: {
         "name": "April",
         "age": 23,
         "hi-how-are-you": "good",
         "steve joe": "o"
         }
     }
 }
as you can see the it supports nested dictionarys also ints as keys

object = Object(dictionary)
object.name -> Steve
object['name'] -> Steve
object._0.name -> April
object[0].name -> April
object[0].hi_how_are_you -> good
object[0]['hi-how-you'] > good
object[0]['steve joe'] ->
object[0].steve_joe -> o
 ```
