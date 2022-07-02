# Dictionary-App
Build A Dictionary App in HTML CSS & JavaScript.
<br>
<br>
In this project (Dictionary App in JavaScript), at first, on the webpage, there is only a search input and when you enter any existing word and press enter then there is shown a loading text of “Searching the meaning of…..”.
<br>
<br>
If the searched word exists then there is shown the meaning, example, synonyms, etc. of the searched word with a slide animation else there is shown a message of “Can’t find the meaning of ……”. There is also a pronunciation icon to pronunciation your searched word.
<br>
<br>
To create this project, there is used API with fetch() method of JavaScript.At first, I got the user searched input, and then using the fetch API method I sent a get request to an API (dictionaryapi.dev) with passing the user searched word.
<br>
<br>
If the searched word exists then API returns an object of the searched word which holds many details (definition, example, synonyms) of the word else it returns a message of “Can’t find the definitions”. Once I fetched the data from API then I inserted each data into a particular HTML element.
<br>
<br>
