# Coding is Communication

> “Always code as if the guy who ends up maintaining your code will be a violent psychopath who knows where you live” - _John Woods_

Software developers, especially in small to medium sized companies, are responsible for more than just typing code.  You will sit in a key position between customers, marketers, designers, managers, deployment machines, and your fellow developers.  At the end of the day it is your responsibility to ensure that there is a working application which fits the end user's needs, deploys smoothly on the necessary platforms, and is scalable and maintainable. 

Source code is your final product.  After hours of planning, emailing, testing, coding, and getting stuck on bugs, all that's left is the source code.  And there's no guarantee that you'll be the one to maintain your code.  This means it's crucial for you to embed everything you know about the project directly into your code. Completed source code is the most powerful tool you have for sharing your knowledge of the application. 

Your finished code needs to be understandable to 3 very different, and equally important audiences:
1. End Users must understand why they're using your software and how to use it
2. Developers must understand how to test, maintain, expand, and re-use your code
3. Deployment Environments must receive carefully tuned, compiled code or risk crashing

We like to think a lot about number 2, and hopefully you will too.

Before you dive into the hard stuff, it's worth taking a moment to get your head in the right place.  Some of the resources below will help you set expectations for how much you'll need to work and what kind of progress you can expect to make in your time with Elewa.  Some of these resources are about what developers actually do in their work.  The rest of the resources will give you an overview of the technologies you will be learning.

### Index
* [Learning Objectives](#learning-objectives)
* [Your Task](#your-task)
* [Resources](#resources)

---

## Learning Objectives

* What's software development really like?
* Ethical Programming
* Communicating with Code
* The development environment
  * [The Internet](#the-internet)
  * [Browsers](#browsers)
  * [JS, HTML & CSS](#js-html-css)
  * [Web Apps](#web-apps)

[TOP](#index)

---

### The Internet


What is it?  Read and take notes then keep noticing.  As you code, continue to take note of when and how you come across the concepts you learned here.


* Outstanding introduction: [Foundations of the Web](https://shawnr.gitbooks.io/foundations-of-the-web/)
* [Khan Academy's Intro](https://www.khanacademy.org/computing/computer-science/internet-intro)
* [The Odin Project's intro](https://www.theodinproject.com/courses/web-development-101/lessons/how-does-the-web-work)
* [Time-Lapse Maps of the Internet](https://www.vox.com/a/internet-maps) 
* [internet for webdevs](https://www.youtube.com/watch?v=e4S8zfLdLgQ).  And there's a part two.     
* [OSI model](http://www.webopedia.com/quick_ref/OSI_Layers.asp)
* Good videos: [part 1](https://www.youtube.com/watch?v=e4S8zfLdLgQ), [part 2](https://www.youtube.com/watch?v=FTAPjr7vgxE)

HTTP:
* [http video](https://www.youtube.com/watch?v=eesqK59rhGA)  
* [Easy HTTP](https://www.jmarshall.com/easy/http/)
* [HTTP Video](https://www.youtube.com/watch?v=eesqK59rhGA)


### Browsers

In the simplest definition, a browser is an application that imports and renders HTML, CSS & JS from anywhere in the internet.  Check out the resources below for a better overview.

* [LifeWire](https://www.lifewire.com/what-is-a-browser-446234)
* [Foxy Video](https://www.google.com/search?q=what+is+a+web+browser&client=safari&rls=en&source=lnms&tbm=vid&sa=X&ved=0ahUKEwjT_fHmrubbAhWszIMKHYArAKUQ_AUICigB&biw=1280&bih=739)
* [Browser vs Search Engine](https://www.computer-geek.net/what-is-the-difference-be-va-47.html)


### JS, HTML & CSS

These three tools are usually grouped together because they are all necessary to build interesting websites, but each one totally unique.

__JavaScript__

JS is a [_programming language_](https://techterms.com/definition/programming_language), it is the meat in your cake.  JavaScript is a full programming language with super powers.  Along with the standard functionalities of any programming language JavaScript can:
* Manipulate the DOM in your browser
* Send and receive HTTP requests
* Perform asynchronous operations
* Offload work to 3rd party services

You'll learn more about all these features later on in this bootcamp.  For now you'll just have to worry about the basics (functions, variables, control flow), and a little bit of DOM manipulation.


__HTML__

HTML is a [_markup language_](https://techterms.com/definition/markup_language) used to define layout and appearance of your website.  At least until [HTML5](https://www.portent.com/blog/design-dev/html5-like-really-important.htm) came out.  HTML5 adds a lot of functionality to your markup, but is still not as powerful as JavaScript or CSS.

__CSS__

CSS isn't quite a Markup Language, and isn't quite a programming language.  You can think of it as a tool for changing the way your looks without changing how it's structured in your source code.  [CSS is it's own strange beast](http://www.webmasterview.com/2017/11/css/), some love it and some hate it.

__Web Apps__

In simplest words a web application is just software that its split across the internet.  The part you see runs on your computer, but it talks with other parts anywhere in the world using HTTP.   Those other parts usually do all the hard work.

* [Being a Web Developer](https://www.theodinproject.com/courses/web-development-101/lessons/introduction-to-web-development)
* [great video](https://www.youtube.com/watch?v=RsQ1tFLwldY)
* [another video](https://www.youtube.com/watch?v=_E8qXBHI4cg)
* [what exactly is a web app](https://www.lifewire.com/what-is-a-web-application-3486637)
* [what's a web app, how's it work?](https://www.quora.com/What-is-a-web-app-and-how-does-it-work-Please-explain-what-it-is-how-it-works-architecture-wise-and-whatever-else-you-think-is-important-and-in-which-way-it-is-different-than-the-previous-way-of-doing-things)
* [web-app vs web-site 1](https://stackoverflow.com/questions/8694922/whats-the-difference-between-a-web-site-and-a-web-application)
* [web-app vs web-site 2](https://www.seguetech.com/website-vs-web-application-whats-the-difference/)

[TOP](#precourse)

---

## Your task


1. Every time you read or write a line of code ask yourself three questions:
    * Does this help the user?
    * Does this help the maintainer?
    * Does this help runtime execution?
2. Read A LOT of code.  Print it out on paper if you have to.
3. Start building your Developer Vocabulary.


[TOP](#index)

---

## Resources

The Programmer's Oath:
* @ Uncle Bob:  [Videos](https://www.youtube.com/watch?v=36NgPu9OyRM), [Text](https://blog.cleancoder.com/uncle-bob/2015/11/18/TheProgrammersOath.html)
* [@ FreeCodeCamp](https://medium.freecodecamp.org/the-programmers-oath-db782efd958b)


Absolute must-reads:  
* [Be reasonable with yourself](http://norvig.com/21-days.html) - Programming takes work, then more work, followed by a lot of practice.  
* [What is programming?](https://shawnr.gitbooks.io/practical-introduction-to-javascript/content/what-is-programming/)
* Be bad at something, it's [good for you](https://www.ted.com/talks/eduardo_briceno_how_to_get_better_at_the_things_you_care_about). 
* Study [smarter](https://youtu.be/Xt5qpbiqw2g?t=297), not harder!   
* [Tips to the beginner developer](https://www.codementor.io/learn-programming/tips-on-becoming-a-software-engineer).
* [What do programmers do?](https://www.youtube.com/watch?v=g4a7_HH9Wbg)
  
Web Development:
* [Enormous Overview](https://www.youtube.com/watch?v=MLXj0hd3usk)
* [A Coggle](https://coggle.it/diagram/Uul_jFoUPeI5AF0b/t/web-development

Other good reads:  
* [Killer Article](http://peternixey.com/post/83510597580/how-to-be-a-great-software-developer) - long, but worth every word.  
* [Top 8 Developer Habits](https://www.youtube.com/watch?v=DwQ7psiU23I&index=1&list=PL0zVEGEvSaeGY3RMjGo4CgMPN42_U9Glu) - Video series by Mr. Funfunfuncion.  He'll become your good friend. 
* Software development [isn't about the code](http://elewa.education/2018/01/20/solution-design/).
* Freecodecamp's article on [comparing yourself to others](https://medium.freecodecamp.org/a-better-way-to-compare-yourself-43cf37616570).  
* Is programming [like learning a language](http://elewa.education/2018/01/22/thinking-computer-thoughts/)?
* [Odin's Web Dev 101](https://www.theodinproject.com/courses/web-development-101/lessons/introduction-to-web-development)


More:
* [Communicating with Code](http://elewa.education/2018/01/25/carving-thoughts-code/)
* [Is Coding Literacy?](http://d-scholarship.pitt.edu/21695/1/24-33-1-PB.pdf)
* Code Quality: [one](https://xkcd.com/1513/), [two](https://xkcd.com/1695/), [three](https://m.xkcd.com/1833/), [counterpoint](http://xkcdisntfunny.blogspot.be/2015/04/xkcd-isnt-funny-1513-code-quality.html)
* [13 Principles of Readable Code](https://gist.github.com/peterhurford/3ad9f48071bd2665a8af)
* [Writing Clean Code](https://github.com/elewa-academy/General-Resources/blob/master/programming-resources/clean-code.md)
* [Beautiful & Clean](https://hackernoon.com/how-to-make-your-code-clean-and-beautiful-5ff7aee03be6)
* Linters & Style:
  * [Code Style & Style Guides](https://codeburst.io/5-javascript-style-guides-including-airbnb-github-google-88cbc6b2b7aa)
  * [Linting](https://medium.com/@danielsternlicht/thoughts-about-javascript-linters-and-lint-driven-development-7c8f17e7e1a0)

Happy readings!  And please do email us with any great links we might have missed, your classmates will appreciate it.


[TOP](#index)

___
___
### <a href="http://elewa.education/blog" target="_blank"><img src="https://user-images.githubusercontent.com/18554853/34921062-506450ae-f97d-11e7-875f-6feeb26ad72d.png" width="100" height="40"/></a>


