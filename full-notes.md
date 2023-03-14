# Learning to code
## What is this repo? 
Naomi's 60 minute learn-to-code workshop. I'll take you all the way from "Hello World" (in Python &amp; HTML) to setting up your own static GitHub Page (HTML &amp; CSS)!

# What is "coding"? 
 - Writing/creating instructions that a computer can understand and execute to:
   - Create, read, update, delete data
   - Create websites, apps, software
 - It's often compared to writing a recipe - but a very exact recipe
   - [Exact instructions for making PB&J sandwich](https://www.youtube.com/watch?v=Ct-lOOUqmyY)

# What is a programming language? 
 - " a system of notation for writing computer programs... a kind of computer language." [1](https://en.wikipedia.org/wiki/Programming_language)
 - It is made up of both "syntax (form) and semantics (meaning), which are usually defined by a formal language." [1](https://en.wikipedia.org/wiki/Programming_language)
 
## Where do programming languages come from? 
 - Academic institutions, industry, open source, etc. 
 - Why? Usually either for fun or to address problems or limitations that an exisiting language has
   - Make syntax easier to read & write (reducing risk of errors)
   - To improve performance (often for a particular platform
   - To expirment with new ideas (and maybe provide a competitive advantage) 

## Why are there updates and new versions of programming languages? 
 - Fixing bugs and security vulnerabilities
 - Adding new features
 - Improving performance
 - Maintaining compatibility 
 - Enhancing usability
 - etc. 
 
## How do programming languages work? 
1. Person writes code
2. Code is either
 - Compiled (converted directly into machine code that can be executed by a computer)
 - Executed (translated into machine code at runtime, as they are executed by a computer)
3. Code is executed by the computer
4. Output may (or may not) be created

## Types of programming langauges
There are lots of different ways to do this! It's like asking someone what kinds of salads there are. 

Types of salads: 
 - What types of salads are there? 
   - caesar v. ceviche v. coleslaw v. cobb salad... 

 - What situation do these salads work in? (what can you accomplish with this programming language?)
   - Different courses: side salads v. main course salads v. dessert salads
   - Different situations: formal v. casual settings
   - Ingredients: romaine lettuce, iceberg lettuce, etc... 
   - Allergens: salads that have peanuts, salads that have walnuts...
  
 - What salad do you want to have now? (what programming language would "hit the spot" for you?)
   - This probably comes down to some of the factor's we've already discussed
   - Maybe you feel like some salads are "real" or "fake": "fruit salad" or "pasta salad" or "chicken salad sandwiches" or "jello salad"... are these real salads?
   
Types of languages: 
 - [Programming paradigms](https://en.wikipedia.org/wiki/Programming_paradigm)
   - Imperative
     - Procedural
     - Object oriented
   - Declarative
     - Functional
     - Logic
     - Mathematical
     - Reactive
 - [Low level](https://en.wikipedia.org/wiki/Low-level_programming_language) v. [High level languages
](https://en.wikipedia.org/wiki/High-level_programming_language) - Compiled v. Interpreted languages
 - [Strong v. weak typing](https://en.wikipedia.org/wiki/Strong_and_weak_typing)
   - Static vs. dynamic typing
   - Manifest vs. inferred
   - Nominal vs. structural
   - Duck typing
 - [Declarative](https://en.wikipedia.org/wiki/Declarative_programming) v. [Imperative](https://en.wikipedia.org/wiki/Imperative_programming) languages
   - [Object oriented](https://en.wikipedia.org/wiki/Object-oriented_programming)
   - [Functional programming languages](https://en.wikipedia.org/wiki/Functional_programming)
 - [Event driven](https://en.wikipedia.org/wiki/Event-driven_programming)
 - [Dynamic programming language](https://en.wikipedia.org/wiki/Dynamic_programming_language) - often called "scripting languages"
 - [Domain-specific languages (DSL)](https://en.wikipedia.org/wiki/Domain-specific_language) v. [General-purpose language (GPL)](https://en.wikipedia.org/wiki/General-purpose_language)
   - Database management (e.g., SQL)
   - Creating documents (e.g., LaTeX)
   - Creating websites (e.g., HTML)
   - Styling websites (e.g., CSS)
   - Data analysis (e.g., R)

   
"There is no overarching classification scheme for programming languages... partially because languages can be classified along multiple axes" [1](https://en.wikipedia.org/wiki/Programming_language#Taxonomies)
 
# Learning to Code
## How to pick a language? 
1. Consider your goals (make a website, build an app, analyze data, etc)
2. Pick a "beginner-friendly" language (Python and Java are often recommended; as are HTML/CSS, R, and SQL)
3. Consider the community (tutorials, documentation, online forums, etc)
4. Be patient & open to switching languages

## How to pick a class? 
Consider whether you have a preference around: 
 - Course content (introductory v. advanced concepts? Quizzes? Online forums?)
 - Course format (reading? lectures to watch?)
 - Course duration (self-paced? hours? months?)
 - Instructor quality
 - Program quality
 - Certificate, degree, neither? 

## Python
### About Python
 - Python is best known for: 
   - Being a high-level programming language
   - Emphasis on code readability
   - Extensive standard library 
 - Pros of Python
   - Readability (due to simple syntax)
   - Versatile (can use for web development, data analysis, machine learning, etc)
   - Interpreted language (can test and run code in real-time)
   - Large community (lots of courses, debugging resources, & in-demand)
 - Cons of Python
   - Slower processing speed (this makes Python a poor choice for: app dev and low-level programming)
   - Python's high-level abstractions & automated memory management can impact performance
 - Resources
   - [The 10 Best Online Python Classes of 2023](https://www.intelligent.com/best-online-courses/python-classes/#Udacity)
   
### How do I start writing Python? 
 - [Command line](https://www.cs.utexas.edu/~mitra/csSummer2019/cs313/start.html)
 - [Jupyter Notebook](https://jupyter.org/try-jupyter/retro/notebooks/?path=notebooks/Intro.ipynb)
 
 ```
# Simple version
print("Hello, world!!")
```
 
## Introductory SQL
 - Programming language designed for managing and manipulating relational databases
 - Four essential operations for creating and managing persistent databases are "CRUD" = Create, Read, Update, Delete
 - Pros
   - Simple syntax and clear structure
   - Widely used and supported 
   - Can scale up as data volumes grow & efficient with relational databases
 - Cons
   - Not great with processing data (even thought SQL is good at retrieving and processing data)
   - All programming languages for relational databases: 
     - Can be vulnerable to security risks (like SQL injection)
     - Changes to the database may mean your SQL code will no longer work
     - Not great with unstructured data (images, videos, audio files) or semi-structured data (hierarchical data like trees or graphs, XML, JSON)
 - Resources
   - [Top 6 Online SQL Courses for Beginners in 2023](https://learnsql.com/blog/best-online-sql-courses-2023/) 
   
 ```
-- Simple version: 
CREATE TABLE helloworld (phrase TEXT);
INSERT INTO helloworld VALUES ("Hello, World!");
INSERT INTO helloworld VALUES ("Goodbye, World!");
SELECT COUNT(*) FROM helloworld;
SELECT * FROM helloworld WHERE phrase = "Hello, World!";
```

## HTML (Hypertext Markup Language) 
 - HTML is best known for providing the basic structure of web pages, defining headings, paragraphs, links, images, etc
 - Pros
   - Easy to learn & use
   - Supported by all modern web browsers
 - Cons
   - Limited functionality
   - Time consuming, especially if you don't use tools to help
   - You'll likely need to add ARIA (Accessible Rich Internet Applications) to your HTML in order to make your web page accessible 
 - Resources
   - [W3School's HTML Tutorial](https://www.w3schools.com/html/)
   - [Codepen](https://codepen.io/) (for HTML, CSS, and JS)
     - To use Bootstrap in your Codepen, select the settings gear for your CSS section, type "Bootstrap", and select the version you want (currently 5.0.2)
   - [Bootstrap](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
   
```
/*simple one*/
<!DOCTYPE html>
<html>
    <head>
        <title>Example</title>
    </head>
    <body>
    <div class="container">
      <div class="row">
        <div class="col left">
        </div>
        <div class="col-lg-auto hellos">
          <div class="one-hello simple">
            hello  world
          </div>
        </div>
        <div class="col right">
        </div>
      </div>
    </div>
    </body>
</html>

/* complicated one */
/* Notice that Codepen only contains the body of a HTML file! */
/*https://codepen.io/naomi789/pen/abaYRWx*/

```
   
## CSS (Cascading Style Sheets)
 - CSS is used to style and format web pages (fonts, colors, layouts, etc)
 - Pros
   - Allows you to separate content & presentation
   - Simple syntax makes CSS easy to learn
   - Enables you to easily make multiple pages on a website look & feel consistent
 - Cons
   - Limited dynamic functionality (no built-in support for interactivity, animations, etc)
     - That being said, there are amazing artists on Codepen who make animation and other art with only HTML and CSS 
   - Different browsers can & do interpret CSS differently
   - Complex to manage in large projects
 - Resources
   - [CSS Tutorial](https://www.w3schools.com/CSS/default.asp)
   - [Codepen](https://codepen.io/) (for HTML, CSS, and JS)
   - [Linear gradient generator](https://cssgradient.io/)
   - [Google fonts](https://fonts.google.com/)
     - Getting started with the [API](https://developers.google.com/fonts/docs/getting_started)
   - [CSS Grid Generator](https://cssgrid-generator.netlify.app/)
   - [Wave generator](https://getwaves.io/)
   - [Shadow generator](https://shadows.brumm.af/)
   - [Shape & shadow generator](https://neumorphism.io/#e0e0e0)
```
/*simple one*/
.simple {
  background-color: black;
  color: white;
  font-family: Arial;
}

/* complicated one */
/*https://codepen.io/naomi789/pen/abaYRWx*/
```
 
## CodeSpaces
 - [insert definition] 
 - [insert why it is helpful] 
 - How to set up CodeSpaces from the [web browser](https://docs.github.com/en/codespaces/developing-in-codespaces/creating-a-codespace-for-a-repository)

# GitHub pages
 - GitHub Pages is a free hosting service provided by GitHub that allows you to create a website using your GitHub repository. It's a simple and easy way to host a static website without the need for a separate web hosting service.
 - Pros: 
   - Easy setup
   - Integrated with GitHub
   - Free web hosting for everyone
   - Template friendly - no need to be a coding expert! 
 - Cons: 
   - Limited functionality (no server-side scripting, no database support)
   - Limited storage (can't store terabytes of videos, etc)

## How do I get started? 
 - [Follow these directions](https://docs.github.com/en/pages/quickstart)
1. Create a repo name "username.github.io" (where "username" is your name)
2. Let's put some HTML in your repo
3. Turn GitHub pages on
4. Set your publishing branch (I'd recommend using your "main" branch)
5. Visit username.github.io to view your new website (it may take 10 minutes to percolate) 
6. Change your title and descreption in the _config.yml file




# Buying a domain name
 - A domain name is a unique web address that identifies a website on the internet.
 - Pros: 
   - Builds branding & credibility
   - Can increase search engine optimization (SEO)
   - Gives you more control
 - Cons: 
   - Annual fee
   - Takes some time & effort to setup
   - Your name & contract info will go on a the WHOIS records
 - Resources
   - [https://www.namecheap.com/](https://www.namecheap.com/)
   - [https://www.godaddy.com/](https://www.godaddy.com/)
   - Other sites where you can host a website (eg, Squarespace, Wix)
  
# HTML & CSS Templates
 - [insert definition] 
 - [insert why it is helpful] 
 - [insert resources] 

