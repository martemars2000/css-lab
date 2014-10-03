# Basics of HTML and CSS

# HTML

#####Reading:#####
All the basics about the markup language are available at [WebPlatform](http://docs.webplatform.org/wiki/html/tutorials). Please follow the different tutorials and you will be learning from basic tag semantics (span, p, div) to others more specific as (section, article, nav, etc).

Also you can learn and do exercise in [codecademy](http://www.codecademy.com/tracks/web).

#####Practice:#####

1. **The Basics of HTML:** create a basic `.html` file and experiment a little with your browser modifying and reloading to see the changes reflected.
2. **Doctypes and Validations:** Keep focus on validate what you have written (DOCTYPES defines how you should write your content). [Validate your file](http://validator.w3.org/)
3. **The HTML head:** You will see how to link your html file with other assets as `js` and `css`, for now keep focus on markup semantics and make some examples changing your already created file.
4. **The HTML body:** Keep focus on markup semantics and understand default behaviors provided by the different types of inputs (`type=text`, `type=number`, `type=date`, etc). Do not care about browsers compatibility, just use lastest chrome or firefox to experiment.

Once you finish with **The HTML body**, you should have a `html` file with several examples applying the different tags you were playing in the tutorial (do not include any JS o CSS code).

Now we will start with the creation of our web page.
Based on this [Design](images/desktop.png "Design") and the experience on the practices that you did before:

1. Create a basic `index.html` with the corresponding tags. (use the new html5 tags)

  Notes:
  - You can create your own logo or use this [Logo](images/logo.jpg "Logo")
  - For the rest of the image, you can create new images in [placehold](http://placehold.it/) or use these:
  - 1000x400&: http://placehold.it/1000x400&text=[img
  - 400x300: http://placehold.it/400x300&text=[img]

# CSS


#####Practice:#####

* Create an empty style.css file and link it to the index.html using [<link> tag](https://developer.mozilla.org/en-US/docs/Web/HTML/Element/link#Examples).
* Include [normalize.css](http://necolas.github.io/normalize.css/) before your style.css to fix cross-browser problems.

## Rules
  
### Selectors and properties 
![alt text](images/anatomy-of-a-css-rule.gif "Anatomy of a CSS rule")

#####Reading:#####

* [Brief of CSS selectors](http://www.sitepoint.com/web-foundations/css-selectors/)
* [More Css selectors](http://estelle.github.io/selectors/#slide1)
* [CSS3 selectors sheet](http://www.w3.org/TR/css3-selectors/)
* [Play a little game to consolidate your knowledge](http://flukeout.github.io/)
* [Bookmark the following list of properties for future reference](http://ref.openweb.io/CSS/)
* [Bookmark a reference of CSS Vocabulary](http://pumpula.net/p/apps/css-vocabulary/)

#####Practice:#####
  * Add background to the sections and the links on the nav.
  * Add a global font definition (at html element) with a value of 14px, using a font-family you like.
  * Make the page center.
    
### Specificity
![alt text](images/specifishity.gif "Specificity")
[Learn about CSS Specificity (basically how the rules override others)](http://www.w3.org/TR/CSS21/cascade.html#specificity)

* [Experiment specificity right now using CSS3 selectors](http://specificity.keegan.st/)
* Now add classes to the different HTML tags with the following names:
    * To &lt;header&gt;  add class .header
    * To &lt;footer&gt;  add class .footer
    * To &lt;section&gt;  add class .content
    * To &lt;nav&gt;  add class  .navigation
* Using the new added classes figure out how to override:
    * .header must define a font-size: 46px;
    * .footer must define a font-size: 10px;
    * .content must define a font-size: 14px;
    * .navigation must define a font-size: 12px;
* When the mouse hover on the nav links, the background must be #BD8A00
* The first paragraph of each article or section (depends how you made it) must have padding-top:10px; 
* How could you add weight to the global font definition to override all the overrides provided by point c?
* Imagine you have something like class=”oh-no-inline-styles” style=”background:red” and you should change the background to green but without changing the inline style, How could you accomplish this?

### The Box Model
* [Learn about the Box Model (how the browser calculate boxes size)](http://www.w3.org/TR/CSS21/box.html)
  * [Play with it here changing width / margin / padding / box-sizing](http://dabblet.com/gist/2986528)
* [How to alter the box model calculations](http://quirksmode.org/css/user-interface/boxsizing.html)
* [Extra about box-sizing](http://adamschwartz.co/magic-of-css/chapters/1-the-box/)
  * Use the playground provided above to change *box-sizing* and see the changes.

### Layout

#### The display property
* [Learn how to handle the display property (block, inline, inline-block, none)](http://learnlayout.com/display.html)
* [An extra documentation (only read display property for now)](http://adamschwartz.co/magic-of-css/chapters/2-layout/)
  * Now modify your CSS to reach something similar to the initial layout asked. You will need to be smart with the use of *display: inline-block*.
  
#### Layout systems  
* [Learn how to create your own layout system](http://www.adamkaplan.me/grid/)
  * [Checkout floats and fully understand them](http://alistapart.com/article/css-floats-101)
  * [Review your knowledge about CSS relative units](http://alistapart.com/article/love-the-boring-bits-of-css)
* Using your own layout system, implement the following page (only desktop).
  ![alt text](images/example-layout.png)
  * When the user **:hover** the right side black box (observe at middle right of the screen shot) it must show a “hello world” message and go back when move the mouse out. To accomplish this [Learn about CSS position](http://learnlayout.com/position.html).

### Media queries
* [Learn Media Queries](http://css-tricks.com/css-media-queries/) and Adapt the given layout to be ready for mobile screens using the following design as guide [example](http://mediaqueri.es/ity/).
* [Media Query Bookmarklet](http://seesparkbox.com/foundry/media_query_bookmarklet)

### Preprocessors

Preprocessors compile the CSS code we write in a processed language to the pure CSS syntax we’re all used to. 

* [Introduction to preprocessors](http://cdharrison.com/presentations/awdgcss/#/)
* [Getting started with LESS](http://www.hongkiat.com/blog/less-basic/)
* [LESS](http://lesscss.org/)
