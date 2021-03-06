# JS Object Challenges

## Getting Started
* Fork and clone this repository
* Create a file in the `js` subdirectory named `pizza.js`
* Write your solution in that file
* Run the file by typing `node js/pizza.js`

---

### Pizza Parlor!
You've been tasked with making an app for a pizza parlor. You'll need an object to hold the menu data.

### 1. Make the Object
* Make a `menu` object with at least 5 pizza types as keys.
* Make each pizza value another nested object which contains a `toppings` key that is an array of at least 3 toppings and a `price` key telling what it costs.

### 2. Print the names of all Pizzas
* Using an appropriate Object method, print a list of all pizza names. (Hint: The pizza names are the keys in your object. Is there a way we can get a list of all keys in an object?)

### 3. Check for the existence of a special Pizza
* Using another appropriate Object method, check to see if the parlor offers a `banana` pizza. (Hint: Is there a method that can tell us whether or not an object contains a key of a certain name?)

## Bonus

Using a `for...in` loop, print out the full menu of pizza names with their prices. For example:

```
Supreme    $21
Hawaiian   $18
Veggie     $16
```

For an extra challenge, include the toppings under each pizza on their own line, like so:

```
Supreme    $21
pepperoni, sausage, onion, olive

Hawaiian   $18
ham, pineapple, onion

Veggie     $16
pepper, onion, mushroom
```

---

## Licensing
1. All content is licensed under a CC-BY-NC-SA 4.0 license.
2. All software code is licensed under GNU GPLv3. For commercial use or alternative licensing, please contact legal@ga.co.