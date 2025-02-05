# Data-objects
Store an object (data and methods) in a self-contained file.

I was thinking about how we store binary data and how it is disconnected from its methods. In object-oriented programming this is solved with classes but I don't know an analogue for files so I wrote a notebook to do precisely that. In the notebook we instantiate an object and then save it with everything including and methods. Once read, methods can be executed on the object without needing to know the class from which it was instantiated. This way we can send a single file and the recreated object contains all the data and methods needed to analyze it.
