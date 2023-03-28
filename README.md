# Personal Portfolio

Hello! This is the repo for my personal portfolio that I started as part of my assignment for the Web data course I took during my Masters at Pitt.
I developed it using HTML, CSS, JavaScript and some JQuery. I used this as a chance to get more familiar with JavaScript and CSS! It is currently available to view at https://nischitapai.com/.

## 1. What framework did I pick and why?

I picked **JQuery** as my framework for this **Portfolio**. I found it very easy to understand and use this framework since I am still learning
HTML, CSS and JS and I found that JQuery is a great starter for me. I have incorporated Bootstrap elements into the assignment and JQuery works
really well with Bootstrap as well.

JQuery is a JavaScript framework which facilitates the readability and the manipulation of HTML DOM elements, event handling, animations, and AJAX calls.
It's also free and an open-source software that adheres to the MIT License. As a result, it is one of the most popular JavaScript libraries.

The main purpose of JQuery is to make it much easier to use JavaScript on your website. JQuery takes a lot of common tasks that require many lines of
JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

Also, JQuery is one of the most popular frameworks of Javascript. It's free and open-source, making it an attractive option for many developers.
It also has a smaller learning curve than other frameworks, such as AngularJS or EmberJS.

## 2. What about that framework appealed to me, for this project?

JQuery was quite appealing to me for this project since I could use a couple of JQuery components for several features in my portfolio.
Some of them include the following :

- JQuery Easing plugin for page scrolling feature using _.bind(), .stop() and .animate()_ functions. Also, _scrollTop_ parameter that sets _.offset().top_
  which scrolls the page by default to top by an offset of 50. I have added _event.preventDefault()_ outside the animate() function to prevent the default
  settings as stated earlier from occuring in case of no animation mode.

- _.scrollspy()_ function to highlight the top navigation as we scroll the page. Here, I set the target to navigation top bar to be fixed and set
  offset to 51.

- _not(.dropdown-toggle)_ on click of the 'Menu' to close the Responsive Menu on Menu Item Click and _.navbar-toggle:visible_ - here, visible
  condition is applied to the class .navbar-toggle for the Menu item to become visible again on reclicking(toggling) the Menu item.

- .affix() on #mainNav to set offset of 100 from top of the page for main navigation.

So by using all of the above functions of JQuery, I was able to reduce my lines of code to a great extent that would have been the case
if it were not for this framework. Just with the help of these functions, I was able to get done my required tasks much faster.

Thus, the main purpose of jQuery is to make it much easier to use JavaScript on the website. JQuery takes a lot of common tasks that require many lines
of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

## 3. What alternative frameworks did I consider?

Being an Animations enthusiast, one of the framework that really appealed to me was the **AOS (Animate On Scroll)** JS library. AOS library allows you to animate
elements as you scroll down and up. If you scroll back to top, elements will animate to it's previous state and are ready to animate again if you scroll down.

The main idea behind AOS is very simple: watch all elements and their positions based on the settings you provide them. Then adding or removing the class with the
aos-animate library. Generally, it's not really easy at times, but the AOS idea is as simple as that and CSS handles animations in every aspect.

Here, I used the _data-aos_ and _data-aos-duration_ attributes in the <div> HTML tag, where the _data-aos_ was specified as "fade-up", i.e., as we scroll down
the page, the elements would fade upwards and _data-aos-duration_ woudl denote the time for which it would face up.
Also, I used _data-aos="zoom-in"_ which will zoom in the elements on the page as we scroll down.

I explored how to add **JQuery CDN** and **Bootstrap CDN** to Glitch project through some of the resources posted above -this was something really new to me
and I learnt this with the help of some YouTube videos.

I also got a chance to explore the AOS JS Library and also used couple of default parameters such as
startEvent, animatedClassName, initClassName and so on. Also, used few of the other settings that could be overridden on per-element basis,
by `data-aos-*` attributes.

Also, I used a lot of _media queries_ in css stylesheet for better responsive mobile design experience. Here, I have set a couple of max-width and max-height
parameters with varying screen widths so that my website is responsive on all device platforms. Different media queries consist of different classes and
id's that entail specific attributes such as margin, font-size, padding, border-radius etc. These elements are set addifferent values for different media
queries for better responsiveness.

## 4. What resources did I read/watch/listen to?

### JQuery in Glitch

https://www.youtube.com/watch?v=9ckzEmmlmzg

### Adding jQuery CDN to Glitch project

https://www.youtube.com/watch?v=59dsJu1VizU

### Adding Bootstrap CDN to Glitch project

https://www.youtube.com/watch?v=ZwFZ3-2xNBk

### AOS JS Library

https://michalsnik.github.io/aos/
https://www.youtube.com/watch?v=YTL0vrcvsOY
https://www.youtube.com/watch?v=ooErnLWWjnE

### Responsive Web Design With Bootstrap and Glitch

https://www.youtube.com/watch?v=c-RXvlBWKhw

## 5. Describe the site I built for this assignment. What does it do? What components or features of the framework did I explore for this project?

I built an Academic Portfolio for myself. It mainly consisits of my introduction, overview of my skills, my projects and contact section.

I explored several **JQuery** components for several features in my portfolio. Some of them include the following :

- JQuery Easing plugin for page scrolling feature using _.bind(), .stop() and .animate()_ functions. Also, _scrollTop_ parameter that sets _.offset().top_
  which scrolls the page by default to top by an offset of 50. I have added _event.preventDefault()_ outside the animate() function to prevent the default
  settings as stated earlier from occuring in case of no animation mode.

- _.scrollspy()_ function to highlight the top navigation as we scroll the page. Here, I set the target to navigation top bar to be fixed and set
  offset to 51.

- _not(.dropdown-toggle)_ on click of the 'Menu' to close the Responsive Menu on Menu Item Click and _.navbar-toggle:visible_ - here, visible
  condition is applied to the class .navbar-toggle for the Menu item to become visible again on reclicking(toggling) the Menu item.

- .affix() on #mainNav to set offset of 100 from top of the page for main navigation.

I also explored more about the **Bootstrap** components and the previous activity enhanced my skills in Bootstrap. I added a couple of Bootstrap elements
such as navigation bar and In-page reference links.

- Nav bar: I have added this component at the top most section of the website which consists of various options such as 'About me',
  'My Projects' and 'Contact me'

- In-page reference links: I have also linked these nav bar options to specific sections on the webpage. So, when we click on any one of the options,
  it directs us to that particular section of the page.

I explored how to add **JQuery CDN** and **Bootstrap CDN** to Glitch project through some of the resources posted above -this was something really new to me
and I learnt this with the help of some YouTube videos.

Since I am a lot into animation related stuiff, I also got a chance to explore the AOS JS Library and also used couple of default parameters such as
startEvent, animatedClassName, initClassName and so on. Also, used few of the other settings that could be overridden on per-element basis,
by `data-aos-*` attributes.

Also, I used a lot of **media queries** in css stylesheet for better responsive mobile design experience. Here, I have set a couple of max-width and max-height
parameters with varying screen widths so that my website is responsive on all device platforms. Different media queries consist of different classes and
id's that entail specific attributes such as margin, font-size, padding, border-radius etc. These elements are set addifferent values for different media
queries for better responsiveness.
