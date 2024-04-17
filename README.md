# Frontend Mentor - Social Links Profile solution

This is a solution to the [Social Links Profile challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)


## Overview

The challenge is about taking a design of a Social links profile card design and creating a webpage that is similar to it. The webpage features html elements like anchor tag, image tag and paragraph tag.

### Screenshot

![](./screenshot.jpg)
(./screenshots/Frontend Mentor - Social links profile_Desktop-design.png)
(./screenshots/Frontend Mentor - Social links profile_Mobile-design.png)


### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS
- Mobile-first workflow
- Media queries

### What I learned

There are a couple of things I learnt while building this project;

- How to style the list items, specifically the numbers or bullet points, I did this by using the pseudo selector: "::marker" which enables the user to select the content before the list and style it to change the color, font-size, font-weight, and even change it to an image.

- Doing this project was also a re-introduction of tables as I haven't used the table tags in a while so learning about the elements and structure of the table was cool.

- I had also forgotten the syntax for media queries and so it was good to learn that and use it in a simple project like this one.

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html

	<table>
          <tr>
            <td>Calories</td>
            <td class="td_bold  td_r">227kcal</td>
          </tr>

          <tr>
            <td>Carbs</td>
            <td class="td_bold  td_r">0g</td>
          </tr>
          
          <tr>  
            <td>Protein</td>
            <td class="td_bold  td_r">20g</td>
          </tr>
          <tr>
            <td class="td_nbb">Fat</td>
            <td class="td_bold td_nbb td_r" >22g</td>
          </tr>
        </table>

```

```css

       .ing-section .list-items::marker, .ins-section .list-items::marker{
         color: #854632;
         font-weight: bold;
       }

       .prep-section li::marker, .ing-section li::marker{
         font-size: 12px;

       }
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

- I want to continue learning the cool ways to style list items, media queries and their best practices, page layout for mobile and desktop design as well as how to effectively create tables.


### Useful resources

https://scrimba.com/learn/responsive/media-query-basics - This helped me quickly understand media query syntax, the meaning behind each keywords used in the syntax and the appropriate situations to use certain syntax

https://www.youtube.com/watch?v=bRYwmmLC_Ns - This video created by Kevin Powell helped me understand how to create and style lists in css.

## Author

- Website - [Add your name here](https://www.your-site.com)
- Frontend Mentor - [@yourusername](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@yourusername](https://www.twitter.com/yourusername)

## Acknowledgments

- Kevin Powell - Youtube video on styling lists
