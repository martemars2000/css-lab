# Basics of HTML and CSS

Before to start the training, take a look the [tools](https://github.com/nuriasuarez/web-fundamentals-tools) needed to do the work easily.

After you install all the tools, fork this repo [https://github.com/nuriasuarez/startup/](https://github.com/nuriasuarez/startup/) to use as a base to host the project code.

The goal of this guide is to create a web page with the following requirement:
* An area that contains a logo and a nav.
* An area that describes at a high-level of Bootcamp HTML course.
* A form to collect information from users who are interested in our trainning
* An in depth description, images of the main web languages and video
* An area that describes who can attend the training
* An area that describes the tools needed to work
* An area that contains the footer

Mockups of the information architecture for both the narrow and wide viewport:
![narrow viewport](/images/mockup.jpg)

##1. HTML

For an introduction to HTML please see [WebPlatform](http://docs.webplatform.org/wiki/html/tutorials).

W3C's HTML5 specification can be found here: [http://www.w3.org/TR/html5/](http://www.w3.org/TR/html5/)

Through the rest of this section you will create a basic HTML document. After finishing this section you will: 

* be able to create HTML documents that displays text, images, tables, lists
* understand how to structure HTML documents, and what the basic building blocks are
* understand best practices to write valid, accessible, and semantic HTML markup.

### 1.1. Basic HTML tags

###### Resources
* [Slides Intro](http://nuriasuarez.github.io/htmlcss-topic0/html-intro/slides.html)
* [WebPlatform](http://docs.webplatform.org/wiki/html/tutorials)

###### Exercise
* [Create a basic page](http://nuriasuarez.github.io/htmlcss-topic0/html-intro/exercise/exercise2.html)
* [Posible Solution](http://nuriasuarez.github.io/htmlcss-topic0/solution/partial/exercise1/)

###### Optional Exercise
* [Code Academy](http://www.codecademy.com/tracks/web): It is a site that contains interactive courses on how to program

### 1.2. HTML5 Semantics & Markup

###### Resources
* [Slides HTML 5](http://nuriasuarez.github.io/htmlcss-topic0/html5/slides.html)
* [http://diveintohtml5.info/](http://diveintohtml5.info/)

###### Exercise
* [Exercise 1 - HTML5](http://nuriasuarez.github.io/htmlcss-topic0/html5/exercise/exercise1.html)
* [Posible Solution](http://nuriasuarez.github.io/htmlcss-topic0/solution/partial/exercise2/)

###### More Documentation
* [Create the page structure](https://developers.google.com/web/fundamentals/getting-started/your-first-multi-screen-site/content)

### 1.3. Doctypes & Metatags:

###### Resources
* [Slides Doctype](http://nuriasuarez.github.io/htmlcss-topic0/html-doctype-meta/slides.html#slide1)
* [HTML Validation](https://docs.webplatform.org/wiki/guides/html_validation)
* [WHAT DOES IT ALL MEAN?](http://diveintohtml5.info/semantics.html)
* [Meta viewport tag](http://www.quirksmode.org/mobile/metaviewport/)


###### Exercise
* [Exercise 1 - Doctype](http://nuriasuarez.github.io/htmlcss-topic0/html-doctype-meta/exercise/exercise1.html)


###### More Documentation
* [W3C Validator](http://validator.w3.org/)
* [The HTML5 Boilerplate](https://github.com/h5bp/html5-boilerplate)

### 1.4. Accessibility
* Understand **why** accessibility is important:
	* [W3C Accessibility](http://www.w3.org/standards/webdesign/accessibility)
* Understand **how** to make web document accessible:
	* [508 checklist](http://webaim.org/standards/508/checklist)
	* [BBC Accessibility Guideline](http://www.bbc.co.uk/guidelines/futuremedia/accessibility/html/).
	* [Leverage HTML5 features to improve accessibility](http://www.w3.org/Talks/2014/0317-HTML5-A11Y/)
	* [Accessibility: The Missing Ingredient](http://alistapart.com/article/accessibility-the-missing-ingredient)
* **Validate** your markup to see if it is accessible:
	* Install a screen reader like [ChromeVox](https://chrome.google.com/webstore/detail/chromevox/kgejglhpjiefppelpmljglcjbhoiplfn?hl=en), and test your HTML document.
	* Install [Accessibility Developer Tools](https://chrome.google.com/webstore/detail/accessibility-developer-t/fpkknkljclfencbdbgkenhalefipecmb?hl=en), and perform an audit on your markup.

###Extra Documentation###
* [Lear about performance](https://developers.google.com/web/fundamentals/performance/)

##2. CSS

### 2.1 Selectors and properties

###### Resources
* [Introduction to selectors Slides](http://nuriasuarez.github.io/htmlcss-topic0/css/css-selectors.html#slide1)
* [Brief of CSS selectors](http://www.sitepoint.com/web-foundations/css-selectors/)
* [Slides selectors - complete](http://estelle.github.io/selectors/#slide1)

###### Exercise
* [Exercise 1 - CSS](http://nuriasuarez.github.io/htmlcss-topic0/css/exercise/exercise1.html)

###### More Documentation
* [CSS3 selectors sheet](http://www.w3.org/TR/css3-selectors/)
* [Box Shadow](http://css3gen.com/box-shadow/)
* [Multiple Background](http://www.css3.info/preview/multiple-backgrounds/)
* [Play a little game to consolidate your knowledge](http://flukeout.github.io/)
* [Bookmark the following list of properties for future reference](http://ref.openweb.io/CSS/)
* [Bookmark a reference of CSS Vocabulary](http://pumpula.net/p/apps/css-vocabulary/)


### 2.2 Specificity
###### Materials
* [Slides specificity] (http://estelle.github.io/CSS-Workshop/part_02_specificity.html#slide1)
* [Learn about CSS Specificity (basically how the rules override others)](http://www.w3.org/TR/CSS21/cascade.html#specificity)

###### Exercise
* [Posible Solution](http://nuriasuarez.github.io/htmlcss-topic0/css/exercise/solution/exercise_solution_2.html)
* How could you add weight to the global font definition to override all the overrides provided by point c?
* Imagine you have something like class=”oh-no-inline-styles” style=”background:red” and you should change the background to green but without changing the inline style, How could you accomplish this?

###### Optional Exercise
* [Experiment specificity right now using CSS3 selectors](http://specificity.keegan.st/)


### 2.3 CSS Units
###### Documentation
* [Video](http://www.sitepoint.com/css3-rem-units/)
* [CSS Concepts Common Units of Measurement - Video] (http://www.dailymotion.com/video/x242ej5_2-0-css-fundamentals-common-css-concepts-common-units-of-measurement_lifestyle)
* [Which CSS Measurements To Use When](http://demosthenes.info/blog/775/Which-CSS-Measurements-To-Use-When)
* [Learning to love the boring bits of CSS] (http://alistapart.com/article/love-the-boring-bits-of-css)

##3. CSS Layout

### 3.1. Block elements

###### Resources
* [Grouping elements Slides](https://nuriasuarez.github.io/htmlcss-topic0/css/css-grouping.html#slide1)
* [Learn CSS fundamentals that are used in any website's layout] (http://learnlayout.com/)

### 3.2. Box Model

###### Resources
* [Box Model Slides](https://nuriasuarez.github.io/htmlcss-topic0/css/css-boxmodel.html#slide1)
* [Learn about the Box Model (how the browser calculate boxes size)](http://www.w3.org/TR/CSS21/box.html)
  * [Play with it here changing width / margin / padding / box-sizing](http://dabblet.com/gist/2986528)
* [How to alter the box model calculations](http://quirksmode.org/css/user-interface/boxsizing.html)
* [Extra about box-sizing](http://adamschwartz.co/magic-of-css/chapters/1-the-box/)
  * Use the playground provided above to change *box-sizing* and see the changes.

### 3.3. Floats

###### Resources
* [Floats Slides](https://nuriasuarez.github.io/htmlcss-topic0/css/css-floats.html#slide1)

###### Exercise

### 3.4. Positioning

###### Resources
* [Positioning Slides](https://nuriasuarez.github.io/htmlcss-topic0/css/css-positioning.html#slide1)

### 3.5. Exercise

##4. Responsive Web Design

###### Resources
* [Video Responsive Web Design Tutorial and Explanation - Desktop First](https://www.youtube.com/watch?v=BIz02qY5BRA)
* [A simple guide to responsive web design] (http://www.adamkaplan.me/grid/)
* [Media queries](http://estelle.github.io/html5training/css_media.html#slide1)

###### More Documentation
* [Responsive Web Design](http://learn.shayhowe.com/advanced-html-css/responsive-web-design/)

###### Exercise
* Make the page created before to be responsive. 
