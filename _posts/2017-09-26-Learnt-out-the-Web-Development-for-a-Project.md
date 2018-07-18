---
layout: post
title:  "Learnt out the Web Development for a Project | HTML5 and CSS"
category: Blog
---

Today, I did start learning Web Development to some extent for a Project.

> Never Stop Learning is the Key to Success!.

1. I learnt (or say, revisited) HTML5 today. Elements are simplified; h1, h2, h3 and so on keep decreasing their sizes when going from 1 to below.

2. Of course, p is for Paragraph and "lorem epsum text" is a kind of Template text used be Web Devs for a long period of time.

3. Every element ends up with "/" is a good thing.

4. Styling out to change the Color of Text using style = "color : <color> is really as simple as jumping off a table!.
  
5. Styling can be further simplified using CSS, Of course using style tags.

6. color, font-size, font-family are life of an HTML.

7. Images, their sources and alt can be added in a single tag as ```img=" ", src=" ", alt=" ".```

8. Border has color, width, style and radius.

9. Two classes attributes can be added in a tag as ```class = "class1, class2".```

10. Remember to add ; or {} everywhere in a class (wherever necessary).

11. To make a hyperlink, use ```<a href" ">Text<a>``` between the Paragraph
  
12. We can give user, an opportunity to enter in the field. We use ```<input type = "text">``` for text inputs and placeholder can be added like a watermark!.

13. Data from your website can be submitted to a server using form Element, ```<form action = "locaton">(anything can be nested here)</form>.```

14. Button can be created using ```<button type = "">text_on_button</button>```.

15. Button, Input Element can be nested in the form element.

16. Require a field using HTML5 so that form is not submitted without filling it out, adding a _required_ in the input element will do.

17. Radiobuttons and Checkboxes can also be added and checked by default using "checked" keyword, ```<label><input type = "radio" name = "button_radio" checked></label>.```

18. Div is most commonly used element, it's a container. it's useful for styling the webpage together.

19. Classes are always defined in a style tag and can be implemented wherever necessary.

20. Give unique id to the elements.

21. As Classes start with . id starts with #.

22. Id attributes always take precedence over Class attributes and it overrides the Class.

23. !important is used to put 100% chances of what you want.

24. hexcodes and rgb are the two types to represent colors in CSS.

25. #000000 for hexcodes and rgb(R, G, B) for RGBs. 

27. Simple Cat App

<link href="https://fonts.googleapis.com/css?family=Lobster" rel="stylesheet" type="text/css">
<style>
  .red-text {
    color: red;
  }

  h2 {
    font-family: Lobster, Monospace;
  }

  p {
    font-size: 16px;
    font-family: Monospace;
  }

  .thick-green-border {
    border-color: green;
    border-width: 10px;
    border-style: solid;
    border-radius: 50%;
  }

  .smaller-image {
    width: 100px;
  }
</style>

<h2 class="red-text">CatPhotoApp</h2>

<p>Click here for <a href="#">cat photos</a>.</p>

<a href="#"><img class="smaller-image thick-green-border" src="https://bit.ly/fcc-relaxing-cat" alt="A cute orange cat lying on its back. "></a>

<p>Things cats love:</p>
<ul>
  <li>cat nip</li>
  <li>laser pointers</li>
  <li>lasagna</li>
</ul>
<p>Top 3 things cats hate:</p>
<ol>
  <li>flea treatment</li>
  <li>thunder</li>
  <li>other cats</li>
</ol>
<form action="/submit-cat-photo">
  <label><input type="radio" name="indoor-outdoor"> Indoor</label>
  <label><input type="radio" name="indoor-outdoor"> Outdoor</label>
  <label><input type="checkbox" name="personality"> Loving</label>
  <label><input type="checkbox" name="personality"> Lazy</label>
  <label><input type="checkbox" name="personality"> Crazy</label>
  <input type="text" placeholder="cat photo URL" required>
  <button type="submit">Submit</button>
</form>



**AND MY LEARNING GOES ON**



