# Programming for Non-Programmers

# Objectives
Students will be able to
- communicate and work more effectively with developers
- clearly explain different parts of the development ecosystem and workflow
- identify next steps if they want to learn to code

# Case Study
We're building an education search engine that allows a user to find courses and workshops in their city that are relevant to their interests.

1. What positions on your team do you need to build this service?
2. What do you think would be an ideal development workflow between those team members?

### Waterfall
![Waterfall development](https://upload.wikimedia.org/wikipedia/commons/thumb/e/e2/Waterfall_model.svg/700px-Waterfall_model.svg.png)

### Agile
![Agile](http://arborseed.com/wp-content/uploads/2015/09/AgileD.png)

## Features [00:25]
- users can search for upcoming classes/workshops by indicating their city and typing in a query, selecting a category, and/or selecting a timeframe.
- users can create an account but not required for search
- users must have an account to sign up for a class

## Exercise (Data)
Get into groups of 3 and answer the following:

1. What pieces of information do we want to collect when the user signs up?
2. What pieces of information do we need to display search results?
3. What usage information do we want to track?
4. Where should we store this information?

## Databases [00:35]
- SQL (has schema, is relational)
- noSQL (non-relational)

### Video
We'll watch 3 minutes of [this video](https://www.youtube.com/watch?v=EUB113i_mzA) on `What is SQL?`

Questions:

1. What is SQL?
2. What is a table?
3. What is a query?
4. What does `SELECT` do?
5. What does `WHERE` do?

Note: SQL is a core skill that a product analyst should have.

## Exercise
Together, on the board, we will hand-write a table with user info, a table with search result info and a table with event info and see how they relate.

## Building the App / How does the web work? [00:50]
Let's check out this [video](https://www.youtube.com/watch?v=D8c4JZW73cM) on how the web works.

### Questions
1. What does a domain name service (DNS) do?
2. What language are websites written in?
3. What is a server?

### Languages of the web
#### Front-end
- HTML
- CSS
- JavaScript

#### Back-end
- PHP
- Python
- Ruby
- Java

### Web Frameworks
Read [this article](http://tutorial.djangogirls.org/en/django/index.html) on Django and web frameworks.

#### Questions:
1. What does a web framework do?

#### Some other frameworks:

- In Ruby: Rails, Sinatra
- In Python: [Django](https://www.djangoproject.com/start/overview/), Flask
- In PHP: CakePHP, CodeIgniter

## More Development Process [01:10]
Ok, we have the features. We decided what language to use on the back-end and what framework to use.

1. How do we communicate with the developers?
2. How do the developers work with each other?

## Communication
- [Trello](https://trello.com/b/JrhD1plm/course-search-engine-pfnp)
- Slack

## Developer Collaboration [01:20]
- git
- github

### Version Control
Let's watch [this clip](http://git-scm.com/video/what-is-version-control) on what version control is.

Questions:

1. What is version control?
2. Why is it useful?
3. In what setting does git really shine?
4. What is a merge?

### Exercise (Git Reading)
Together, we will read [this quora answer](https://www.quora.com/How-can-I-explain-what-Git-is-does-to-someone-who-is-not-a-programmer/answer/Jake-Boxer) on what `git` is.

### GitHub
- [Example Public (Open Source) GitHub Repository](https://github.com/django/django)
- [Another Github Repo Example](https://github.com/suneel0101/django-easyrest)
- [Example Pull Request](https://github.com/pennypacker-labs/partake/pull/111)

## Testing [01:30]
How do we know if what we built works? Manual QA? Pros/Cons?

## Types of Automated Tests
- unit tests ([example](https://gist.github.com/suneel0101/d60d375c0f285b56d68e))
- functional tests
- integration tests ([Selenium](http://www.seleniumhq.org/))

### Exercise
Get in groups of 3 and discuss the following:

1. When and why you would have your developers write automated tests for the application
2. When and why you would not have them write automated tests

## Deployment [01:45]
Ok now we built it. How do we publish it to the world? Where does our code live?

### Web Hosting
### Exercise (Hosting Reading)
Read [this article](http://smashingboxes.com/blog/heroku-vs-amazon-web-services) and discuss with a partner:

1. What is AWS?
2. What is Heroku?
3. How are they different?
4. When would you choose one over the other?

- [Amazon Web Services (AWS)](https://aws.amazon.com/)
- [Heroku](https://www.heroku.com/)

## APIs
### Exercise
Read: [What is an API?](http://readwrite.com/2013/09/19/api-defined)

### Questions
1. What is an API?
2. When would you use one?
3. What are some common ones?
4. When should you create one?

## Analysis
### Third-Party Tools
- [Google Analytics](https://www.google.com/analytics/)
- [Mixpanel](https://mixpanel.com/)

### Visualization
- [Obama's Budget Proposal](http://www.nytimes.com/interactive/2012/02/13/us/politics/2013-budget-proposal-graphic.html)
- [D3 collision detection](http://mbostock.github.io/d3/talk/20111018/collision.html)
- [CrimeTimeline](http://crimetimeline.io/)
- [Tableau](http://www.tableau.com/)

### In-house
- analyst with SQL/Excel skills
- create internal dashboard
- google analytics

## Data Science
- big data
- predictions
- data mining

### Exercise
In your everyday lives, where is data science/ predictive technology being used? What are some examples?

### Examples
Read: [Netflix](http://www.nytimes.com/2013/02/25/business/media/for-house-of-cards-using-big-data-to-guarantee-its-popularity.html)

### How does machine learning work?
- features
- target
- test set vs. training set

### Skills Required
- R / Python
- Stats, linear algebra

## Dive into Front-end [2:30]
We will use [CodePen](http://codepen.io/pen/) to build a webpage.

### Skeleton
```html
<html>
<body>
  <p>Hello!</p>
</body>
</html>
```

### Let's Add More Content
- header text
- links
- divs

### Exercise
1. Create a page that contains a list of 4 course entries, displaying the title, rating number (between 1 and 5) and description.
2. Then link each title to any external webpage.

### Let's add SEO tags
1. We'll add a page title
2. We'll add the description
3. We'll add SEO keywords

### Let's Style Our Page with CSS
0. Let's add a background color
1. Let's add a different color for links
2. Make the title bold.

### Exercise
1. Make the color of the description text green.
2. Make the font size of the title 24px.

### Let's make our page interactive
Let's create an alert when a user clicks on the description.

## Dive into Back-end [03:00]
Let's learn some basic Python.

### Instructions
Open [Repl.it](http://repl.it) and select `Python 3`.

- Basic Data Types
- If / Else
- Lists

## Possible Next Steps [03:40]
- Learn to code (Intro Python / Bootcamp / WDI / Flatiron)
- Learn to design
- Learn to product manage
- Learn data analytics (Intro to Data Analytics, Data Analytics Part-Time)
