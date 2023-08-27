# CSS-for-begginers

1. CSS Introduction
   1. What is CSS?
   2. What are selectors
      
2. Ways to give style
   1. Inline
   2. Internal
   3. External
3. Selectors
   1. Type selectors
   2. id selectors
   3. Class selectors
   4. Child selectors


# 1.CSS Introduction:

## What is CSS?

CSS stands for Cascading Style Sheets
CSS describes how HTML elements are to be displayed on screen, paper, or in other media.

CSS saves a lot of work. It can control the layout of multiple web pages all at once.

External stylesheets are stored in CSS files.

## What are selectors

CSS selectors are used to "find" (or select) the HTML elements you want to style.

### Example:

```css
selector{
      background-color : red;
}
```


# 2.Ways to give style

## Inline

You can use the style attribute inside HTML elements.

## Internal 

You can use a <style> element in the <head> section.

## External

You can use <link> element to link to an external CSS file.

# 3.Selectors

## Type selectors:

you should use the type of your element.
For example if you wanna give style to paragraphs you can use `p`

```css

p{
   background-color : blue;
}
```

## id selector

yo should first give an id to the element that you want, then use the id with a # to give style to it.

For example if we wanna give style to `<p id="p1">Hello World</p>`

```css

#p1{
   color : green;
}
```

## Class selectors

HTML👇👇
```html
<h1 class = "heading">Heading1</h1>

```

CSS👇👇

```css
.heading{
    background-color: green;
    color: white;
}
```

## Child selectors

HTML 👇👇

```html
<blockquote class="test">
    <p>Hello World</p>
</blockquote>
```

CSS👇👇

```css
blockquote.test>p{
     color: crimson; 
}
```
