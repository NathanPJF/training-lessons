# HTML - Class attribute

Adding the **class attribute** to HTML elements makes it possible to apply additional styling to elements. For example: make the font color red, or increasing font size to 16px.

Classes are defined in a markup language called "CSS". 

#### HTML

`<h3 class="notice">This is how CSS works</h3>`

#### CSS

```
.notice {
  color:red;
  font-size:16px;
}
```

The above code would style the heading "This is how CSS works" to be the color red with a font size of 16px.

Classes are always defined using the name/value pair syntax: **class="class-name"**. 

`<h1 class="product-title">Title/h1>`

`<p class="product-description">Paragraph</p>`


You can have multiple values in the **class attribute** by separating them with a space.

`<h2 class="product-price sale">Unordered List</h2>`

*Fun fact:* A class attribute can be used as many times as you'd like on the page.

```
<h2 class="description">Contact information</h2>

<p class="description">Location: 150 Elgin St, Ottawa, ON</p>

<p class="description">Support hours: 24/7</p>
```


## Exercise 3:

In this exercise we'll give this product page a legit makeover by applying the appropriate `class` attributes.

### Tasks

Head to the exercise [HTML: Class attribute](http://codepen.io/NathanPJF/pen/LVZrGr)

You won't be writing any new CSS to complete this exercise.  Use the existing classes in the exercise's CSS section and apply them to HTML tags.  The goal is to make it look like this:

![https://cdn.shopify.com/s/files/1/0300/9217/files/HTML_Class_exercise.png](https://cdn.shopify.com/s/files/1/0300/9217/files/HTML_Class_exercise.png)

*Pro Tip #1*: You'll have to apply **two classes** to one of the HTML tags to finish.

*Pro Tip #2*: Save your work.

Once done, submit you link for this exercise below.
