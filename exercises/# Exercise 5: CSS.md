# CSS

CSS is a "mark-up" language used to style HTML elements on the page.  You know how to assign different classes to an HTML element with the **class attribute**, but now we'll learn how to write the actual CSS to match.

A CSS **declaration** has three parts: selector, property, and value.

```
selector {
  property: value;
}
```

If we want to select all paragraph tags and make their font-size 16px, we would write:

```
p {
  font-size: 16px;
}
```

### Specificity in CSS

If we wanted to select just *one particular paragraph* and change its font color to `red`, then we need a way to **specify** that.  The best way is with adding a class attribtue. In the example below, we add the attribute `class="note"` to one of the paragraph tags.

**HTML**

```
<p>First line of description</p>
<p class="note">Important line of description</p>
<p>Last line of description</p>
```

Now let's make our CSS selector any paragraph tag *with* the class of "note".  Do this by writing `p.note`.  The period in `.note` tells CSS that "note" is a class, and not another HTML element.

**CSS**

```
p.note {
  color: red;
}
```


## Exercise 5

In the **final** exercise, you will need to write CSS declarations to style the page's
various HTML elements.

### Tasks

Portal to boss battle stage: [CSS](http://codepen.io/NathanPJF/pen/zGBLpQ)

Below are a list of styles you will need to write with CSS.  The HTML on the page
is not to be changed, so your style declarations will need to match the `class` attributes
that have already been applied to the HTML tags.

If you are feeling stuck be sure to check out the [CSS Reference page](http://www.w3schools.com/cssref/) at W3Schools.  Another valid tool is Google.

**Product title**

  - font size of 44px
  - a hex-color of #d83e3e;
  - text centered on the page;

**Price**

  - color #798c9c;
  - font size of 20px;

**Paragraphs**

  - font size of 14px;
  - line height of 22px;

**Shipping notice**

  - color of #852929
  - CSS class specified to accompany a paragraph tag

**Images**

 - maximum width of 300px

### Final result

![https://cdn.shopify.com/s/files/1/0300/9217/files/Final_exercise.png](https://cdn.shopify.com/s/files/1/0300/9217/files/Final_exercise.png)


Please **Save** your work and submit that sweet, sweet link below.
