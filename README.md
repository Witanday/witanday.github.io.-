# Sprint-Challenge Applied Javascript

We've covered a lot this week. We've learned how to plug Javascript up to our HTML/CSS static pages and create dynamic content. We learned about the DOM and how we can modify HTML elements dynamically. We've learned about events and how to listen for, and act on them. And finally, we learned about component architecture and how to build components that share functionality and styling with many elements. In this Sprint Challenge we will be utilizing all of the above.

## Assessing your Applied Javascript Fu

- Answers to your written questions will be recorded in _ANSWERS.md_
- This is to be worked on alone but you can use outside resources. You can _reference_ any old code you may have, and documentation, however, please refrain from copying and pasting any of your answers. Try and understand the question and put your responses in your own words.

### Questions:

1. What is the DOM?
2. What is an event?
3. What is an event listener?
4. Why would we convert a NodeList into an Array?
5. What is a component?

## Challenge

We are going to create a Lambda Newspaper. The styling is modeled after the [LA Times Website](http://www.latimes.com). Open it up and you will notice all of the HTML and CSS has already been created and imported properly. Our job is going to be to add functionality to the tabs below the 'Lambda Times' logo. These tabs will act as filters for our articles, and when clicked on, should filter out all articles except those with that tag.

- Look through the HTML code paying particular attention to the Tabs component, and the Cards components. You will notice they share a data attribute. We will be using this data attribute to determine which cards should show when each tab is selected.
- Following the instructions in the `Tabs.js` file, complete the `TabLink`, and `TabCard` class components. It will look and feel very similar to the last project we worked on, but with a twist. Now, instead of one `Item` to display, we will need to display a collection of `Cards`. Think about ways to iterate over an array and manipulate each item.
- Once you get your `Tab` component working properly add a couple more articles yourself and check out how it works.

![Working Sprint Challenge Gif](./Sprint-Challenge.gif 'Example of working project')

## Stretch Challenge

Your stretch challenge is to write the functionality of a `Carousel` component. You have the HTML and CSS already in place, simply uncomment the HTML in the `index.html` file. This is an advanced challenge, so you are not expected to be able to complete it. If you begin and don't finish, you should still submit with what you have. You may reference the `Tabs.js` file for assistance.

- Complete the carousel functionality in `Carousel.js`
- If you complete the Carousel, add functionality so that the carousel slides when the buttons are pressed instead of just appearing.
- Create an 'infinite loop' carousel. In which as long as you click on an arrow, the array of images will loop over iteself.
- If you have finished the above, play around with the styling on all the components, and understand how each is built.
