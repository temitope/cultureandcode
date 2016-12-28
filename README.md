####Pre-requisites
  * Access to http://JSFiddle.net  (students can save their work exercises here for future reference and indepedent exploration if they choose)
  * Google Chrome Browser ( https://www.google.com/chrome/ )

##Introduction 
Variables and symbols within and beyond contemporary Computer Science. Examining history to find the parallels.
Since antiquity humans have used symbols to hold value for society, in Computer Science “variables” are used as a type of symbol to hold values for programs. Own and relate a story about a culture’s values. Notice the system of values and systems in the culture. By doing this you are already preparing to understand the function of variables in the realm of Computer Science. 

>Teacher notes: Tell a story about a culture. It is important to understand and tell the story of a particular culture in order to authentically convey how ingrained and longstanding symbology and logic is to the human experience. See links below for areas of exploration that will give background for this course and inspiration for a cultural story to tell. It is important to think about what values from a cultural story are particularly relevant.

  + Patanjali’s 8 limbs of Yoga from India. Explanation of an ancient science for self-realization https://en.wikipedia.org/wiki/Yoga_Sutras_of_Patanjali 
  + The wisdom of Ifa (Afa) from west Africa. A corpus of wisdom stored in song and symbol. https://en.wikipedia.org/wiki/If%C3%A1 
  + Divination - https://en.wikipedia.org/wiki/Cleromancy 
  + Oracles https://en.wikipedia.org/wiki/Oracle#Greece 

###Exercise 1 (variables):   
Let’s learn how how to create variables as model for cultural symbols. We will store values in variables (strings, numbers, other variables) and retrieve them.

>Teacher notes: Here we look at using the Javascript (JS) language to store values in variables to make the connection between symbols and values in cultures. We will make it very simple by storing string based values in the variables for now. Students should be mindful in the naming of their variables, just as they would imagine the choosing of symbols in a culture would be meaningful. It doesn’t have to be super esoteric or deep necessarily, but there should be a logical explanation for why something has a certain variable name.
P.S. variable names must be alphanumeric and contain no whitespace

Examples and Code: (create meaningful variables names and values, use console.log to confirm)
1. Go to jsfiddle.net using your Google Chrome Browser (Chrome)
2. In the Javascript (JS) box section create your first variable by typing: 
```javascript
var a_variable_name = “a value corresponding to this symbol”;
```
You just stored value in a symbol, make sure it reflects part of the story of a culture you understand/know.
1. In Chrome open the Javascript console View>Developer>Javascript Console
2. In JSFiddle type the following code on the next available line in the JS section: 
```javascript
console.log(a_variable_name);
```
3. Click the “Run” button in the upper-left hand corner of the JSFiddle page
You have just retrieved the value of your symbol and printed it out in the console. You should be able to see the value you stored for your symbol printed out in the Javascript Console section you opened in Chrome.
![https://www.dropbox.com/s/idpby1wq2gzd1bk/Screenshot%202016-12-27%2017.55.28.png?dl=0]
1. In JSFiddle type the following code on the next available line in the JS section. Then click “Run” again: 
```javasript
alert(a_variable_name);
```
You should now see a box pop up with the value of the variable in addition to the console area print out of the value.
See this fiddle for reference: <script async src="//jsfiddle.net/topeson/hx7n607u/embed/"></script> 


###Exercise 2 (arrays):  
A set of variables in an array can be said to model a set of symbols in a culture  - store sets of variables in an array structure and retrieve them (introduce random retrieval to model oracle systems)

A collection of variables can be grouped together. In a culture it may be called a book if put into physical form, but often they do exist simply in consciousness. See akashic records https://en.wikipedia.org/wiki/Akashic_records . Where retrieval is through memory (invoked by symbols in song or otherwise). In computer science we will group our variables using what is called an array structure. Arrays are created and referenced like variables (so there is a bit of a recursive/fractal idea happening here where variables are stored in variables).

Examples and Code: (simply put variables into an array with pertinent variable name.)
In the JS section of the JSFiddle site:
1. Create a set of variables with corresponding values that could define an aspect of the culture you are focusing on.
2. Create an array and put those variables into that array by typing: 
```javascript
var my_array = [var1, var2, var3];
```
  *If you wish add two more lines of code to print out the array variable in the console and show it in the pop up using the console.log and alert methods described in Exercise 1.
 https://jsfiddle.net/topeson/vnkhuLrn/ 

###Exercise 3 (functions):  
Now that we have a set of our variables representing an aspect of a culture, we can look at retrieving them and thinking about the manner in which we do so. Sometimes we just want to display everything and see what we have. But sometimes there is a specific application to life. We take the book from the library or open the chapter that is particularly useful at this juncture in our lives. In some oracle-based cultures we invoke a sort of cosmic randomness and trust in an expression of fate, that it will align with our purpose (similar to tarot cards, fortune cookies, casting dice, etc). Sometimes the cultural “keeper of wisdom” the babalawo, shaman, priest is best versed in the corpus and dispensation, so one might imagine the different scenarios at play here. In this new age of computational science and the tools of light and light manipulation (computer science) the knowledge is more accessible by all.

Examples and Code: [alert functions for - full display, specific display, random display]



--optional exercises if time & scope permits--
- optional (moving beyond JS) - hooking it all up to a user interface (buttons and inputs). 
- Optional (more CS concepts) - logic and recursion : if/else, loops to represent logic and fractal infinity 




