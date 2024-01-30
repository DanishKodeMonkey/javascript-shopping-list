# Javascript Shopping list

### A minimalist javascript shopping list

## Description

In an effort to put practise into DOM manipulation using javascript
I made this simple shopping list application using various methods and techniques I have learned during the [The Odin Project, DOM manipulation](https://www.theodinproject.com/lessons/foundations-dom-manipulation-and-events) curriculum.

## The process

During the exercise, I am granted a basic html starting point with minimal CSS added to it featuring a div, label, input, button, and an empty list. Ass well as a script element. All additions to the exercise is made inside the script.

#### Note: While aware that a separated JS/CSS reference solution would be best. For the purpose of the exercise, this is all done in the html.

It's important to note that the entire purpose of the exercise, is that any further manipulation of the DOM is made solely through javascript.

So, the exercise itself, what is the problem case to solve?
I have to create a script that will manipulate the DOM of the already established HTML, that will enable the input fields value to save on the add item buttons press, and create a list item below the input field. The list item will consist of the aforementioned input value, and a delete button, that can self-delete the item if needed.

Breaking down the solution will therefore include

```
Create variables storing the references to the ul, input, and button elements

Create a a function that runs when the add item button is clicked
    The function should do the following:
        store the input elements value in a variable
        empty the input elements value with an empty string
        create a new list item
            create three new elements, in function, li, span, and button
            store the three new elements in variables
            append the span and button as children of the list item
            set text content of the span the input values variable
            set the text content of the delete button to.. well, delete.
            append the list item to the ul shopping list
            establish focus on input field with focus()
        make the delete button functional, deleting the list item
            use event handlers that, when clicked, deletes the list item
            establish focus on input field with focus()

```

#### That sure is a hefty function.

putting all item list related features, including the dom manipulation, inside the function. Limits the scope of the different DOM manipulation, isolating it and ensuring the features outside the list items is not messed with.

## The result

The result is a simple shopping list programmed mainly using javascript (although stored inside the html)

The project works as intended, the user is able to input an item, add it to a list, and remove it from the list without messing with other entries as a result.

I got a good grasp of powers of DOM manipulation using javascript, it is a truly powerful tool that allows for dynamic interaction from the user. Creating a responsive and pleasant experience.

### Try it out!

Check it out [here](danishkodemonkey.github.io/javascript-shopping-list/)
