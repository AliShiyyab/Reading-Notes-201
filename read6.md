# Problem Domain, Objects, and the DOM

## problem domain

**A problem domain is the area of expertise or application that needs to be examined to solve a problem. A problem domain is simply looking at only the topics of an individual's interest, and excluding everything else.**
<br><br><br>

## DOM

**The HTML DOM is an Object Model for HTML. It defines:**

* HTML elements as objects
* Properties for all HTML elements
* Methods for all HTML elements
* Events for all HTML elements


**The HTML DOM is an API (Programming Interface) for JavaScript:**
* JavaScript can add/change/remove HTML elements
* JavaScript can add/change/remove HTML attributes
* JavaScript can add/change/remove CSS styles
* JavaScript can react to HTML events
* JavaScript can add/change/remove HTML events

### Finding HTML Elements

>Using `document.getelementby(TYPE)`

<br><br>

*There are a couple of ways to do this:*

* Finding HTML elements by id
* Finding HTML elements by tag name
* Finding HTML elements by class name
* Finding HTML elements by CSS selectors
* Finding HTML elements by HTML object collections



 ## Object 

*You have already learned that JavaScript variables are containers for data values, This code assigns a simple value (Fiat) to a variable named car:*

`var car = "Fiat";`

*Objects are variables too. But objects can contain many values, This code assigns many values (Fiat, 500, white) to a variable named car:*

`var car = {type:"Fiat", model:"500", color:"white"};`

### **Object Properties**

**The name:values pairs in JavaScript objects are called properties:**

Property	|   Property Value
----------- | ------------------
type    	|   Fiat
model   	|   500
Color	    |   White

### Accessing Object Properties

Call the name of variable like `car`

and call the `property`

like : `car.color;` or `car["color"];`