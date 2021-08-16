# Practical English
## Sales Funnel for Online English Courses

Practical English is a website for students stuck at upper-beginner English level and want to advance to intermidiate level. 
There are three sections that will help students do this.

The blog which focuses around the common problems student shave when studying.

The newsletter, which customizes the content that students see based on the answers to a quiz. This then delivers customized study timetables to students. (using Activecampaign)

Finally we have the courses, there are four courses. 
- Conversation (intermidiate)
- Grammar hero (upper-beginner)
- English uncovered (beginner)
- Bullet proof memory (cheaper course to teach students memory techniques)

Students are encouraged to sign up for the newsletter, throughout the website. The newsletter and a combination of Google Analytics and Google Tag manager will be used to segment the audience and understand which of our audience is the most engaged. 

The cheaper course, the bullet proof memory is then used to figure out who is interested in our courses and willing to spend money. 

Then using the data about what the users are viewing (the blog categories and the quiz answers) students will then be targeted with ads designed around the material they have been viewing the most, promoting courses that are close to their level, at various discounts. 

What was needed to make this website was html, css and a minimual amount of javascript (for the menu overlay). 

We needed five pages for the main site plus six articles and one landing page. 

## UX

### Ideal User Demographic

The ideal user for this website is 

- University students who need to pass English courses to pass their semester. 

- Individuals who want to learn English to get a better job 

- Students who have tried to study English in the past but have been unsuccessful.


## User Stories 

### New/Potential Customers Goals:
- I want to be able to search for activities that I can use to learn English fast. 

- I want activities for listening, reading, writing and speaking. 

- I want to know how I should be studying English


### Current Customers  
- I want to know how I should be studying each day and for how long

- I want a clear study plan that is not complicated to follow

- I want to be able to see I am improving and what my next step is



## Development plans 

In order to create a comprehensive and informative website, the developer worked closely with the students to distinguish the required functionality of the site and how it would answer the user stories, as described above.


### Strategy

Broken into three categories, the website will focus on the following target audiences:

Roles

- University students interested in taking IELTS. 

- Students who are not good enough yet to take the IELTS test. 

- Students who have gotten a 5.5 or lower on the IELTS test. 

Demographic

- 18- 22 year olds 
- Studying medical degree
- Studying Import and export 
- Studying English

The website needs to enable the user to:

- Be able to find problems they are having studying English and activities to help them.
- Identify activities based on desired result (improve speaking, listening, reading, writing)
- Be easily able to identify activities that are suitable for them. 

The website owner needs to be able to
- Identify which users are looking at which articles 
- Which users are looking at the most articles
- Be able to recommend further relevant resources to the users, providing value and building trust. 
- Send ads that are based on what the users.
- Create trust and authority among the users

### Scope 

Content Requirements

The user will be looking for 

- Articles 
- Related Resources 
- Social Links 
- Recommended Resources 


### Functionality Requirements

- Easily browse through the website to find the info they want 
- Easily see how resources and activities connect to other resources and activities 

## Design 

### Color

The main color scheme will be orange and blue. due to the contrast when next to each other this will allow us to guide the users eye to call to action buttons and key information. 

### Typography

Asul Roboto where the main fonts used, with Asul being used for the text and Roboto being used for the Titles.

## Features
This section we will go over the features of the website and why they are useful for our target niche. 

### Navbar

![Github  navbar](/images/Untitled-design-(14).png )


Featured on all three pages, the full responsive navigation bar includes links to the Logo, Home page, Gallery and Sign Up page and is identical in each page to allow for easy navigation.

This section will allow the user to easily navigate from page to page across all devices without having to revert back to the previous page via the ‘back’ button.

It also shows students that we are focusing on common student problems and has a call to action for the courses that stands out from the rest of the nav items. 

This menu is also sticky, showing these menus whereever the students are on the page. 

The responsive overlay menu also highlights the courses options

### Banner heading (home page)

![Github  heading](/images/Untitled-design-(15).png )

The banner is made so students can identify with our chosen nich. It has a call to action button taking students to our courses page, which students see to who these courses are aimed for and why we created them. 

The page is also set next to a video introduction that will give a more detailed explaination about our courses and give further instructions to the users. 

### Mission statment 
![Github  mission](/images/Untitled-design-(16).png )


The mission statment was used so the users could quickly identfy how our courses are different from other similar courses online. 

### Common student problems
![Github  problems](/images/Untitled-design-(17).png )

This section leads into our blog section, which focuses on study activities based on the main problems that students have. 

The articles on the main page are not random and a the highest converrting aritcles or the mosst visisted articles on th site. 

The article cards have buttons that can be clicked to take the user to the article and have images that further support the title of the article and allow students to relate to the problem the article addresses. 

The article card also shows the student what the activity is focusing on (Vocabualry, listening, reading, writing, grammar or speaking), further helping the user understand what they are looking at and if they will find this resource useful.

### Cheap course promotion 
![Github  course](/images/Untitled-design-(18).png )


This is the bullet proof memory course, which we use to understand who is interested in our material and willing to spend money. 

This offers a title exclaming steal my method, an image with the name and discount of the course. 

It also has a call to action next to several of flex wraps, which give quick summaries of the course content. 

### Reviews 
![Github  reviews](/images/Untitled-design-(19).png )

The reviews are used under the course to give credability to the course above and the courses below. 

It consists of a name tag, star rating, location of the studet and description. The description is focusing on why the courses helped the student advance to the next level. 

### Other courses 
![Github  other-courses](/images/Untitled-design-(20).png )

The item cards here are different to the blog cards to avoid confusion and make them stand out. 

We have the name ofthe course, an image, description of the course, call to action linking the course card to the course page. And the price of the courses. 

The courses are designed to be a lot more expensive than the bullet proof memory course. This is because it will make the bullet proof memory course look more attractive and cheaper and most of our sales will be coming from the specific offers in the retargeting ads. 

### sign up 
![Github  signup](/images/Untitled-design-(21).png )

This is the news letter sign up, called the custom study timetable. 

It is a form that collects the basic information (name and email address) but also more specific information such as english level and city. This information will then be sent to our esp using Activiecampaigns Api and will be used to customize the cotent that the users will see. (beginner level students will not see content for intermidiate courses and vice versa).

Please note:The signup form has been used on many different pages and all the blog pages. One of the main goals of the site is to increase the email sign ups and one of the best ways to do this is to make it easy for students to sign up. This means that the form is always at the bottom of the page next to the footer, after students have been given value in the form of an article. 

Due to several of the courses not being made yet, I created a coming soon page, using the same form design. Allowing students to keep informed about upcoming releases. 

### footer 
![Github  footer](/images/Untitled-design-(22).png )


The footer section is broken down into four sections. Each section has the title underlined and allows for easier navigation around site. 

It contains the privacy policies, navigation, contact and social media we are using.

### study activities/blog page 
![Github  blog](/images/Untitled-design-(23).png )


The blog page page is broken down into four sections. 

The banner section: This section encourages students to read one article (the grading article), which allows students to quickly access their English level. This is a good place to start because it makes the sign ups more accurate.

The most common student problems, which students are told to read first as it gives them a good foundation to start from. 
These will be the articles created for this purpose, which will include high converting artilces and an artcle that shows students a quick wway to grade there English level, which makes the sign ups more acurate. 

The second section is the rest of the articles. The artcle cards are the same style as the home page to keep it consistent.

Sign up to our newsletter: One of the resonse that there are a lot of articles is we want to show students that we can provid value but we also want to overwhelm them with a lot of information. Then the bottom of the page we have the sign up form which tells them that we will send them the activities they personally need for there level, which further encorages signups. 

## About page 

![Github  about](/images/Websites.png )


The about page is one of the higest converting pages on a website. 

We have the title of the page and an image with a quote. 

We then have some of the most common frustrations that students have when studying English and the reason why we started the blog. This style is the same style as the steal my method on the homepage. 

This then leads to high converting articles that funnel students back into the student problems section. 

##contact 
The contact page consists of a contact form where students can input their name, email address and the question they have in the form of text. 

##articles

The top of the aticle has a navigation section. 

This section does two things
One: It shows the different sections of the article and allows for jump link navigation to that section. 
Two: Has related articles that support this activity or study skill, providing students with direction to the next related articles (all of which is being tracked).

The article body is then broken up into sections with subheadings and icons with contrasting colors for readability/ scrolling. 

there is a signup form at the bottom of the page for the newsletter. 

##landing page- bullet proof memoery 
The landing page was created from the perspective of a copy wirter. It details the problem and the problem it fixes. 

It has a different style of review than the home page because here we are aiming for quantity over quality and will be putting all the reviews we have as social proof. These review cards have the review, name and the icon of the platform where they submitted the review. 

The price card is holds the price of the course and the course index/lesson names of the course.

### All Courses 

![Github  blog](/images/Untitled-design-(24).png )

This page is broken down into three sections. 

The first section is a banner section, which gives instructions to sign up for the newsletter for our personal recomendations for courses. It also has a video that further explains the courses and gives direction to the users. 

Course Cards: Style is different to the blog cards (same design as the home page for consistency)

Sign up form: Students can get a lot of our information from the course from our news letter and are encouraged to sign up to the news letter here as well. 

Imortant: I must stress that I do not expect to make many direct sales from this page, the marketing plan for this site is to get users to sign up to the newsletter and then send custom ads (with deals and discounts to different users)


### Features in the future 

A multiple choice for the email sign-up. 

This would then allow us to segment the audience more and deliver more personalized content. 

Chatbot (Manychat) embeded onto the website to link the automation on the website and the social media and grow the facebook group (well engaged facebook groups are more effective at sales than most email lists). 



## Issues and Bugs

The developer ran into a number of issues during the development of the websites, with the noteworthy ones listed below, along with solutions or ideas to implement in the future.

### Navbar Bug 
 A bug was detected early on with the Navigation bar. In implementing a responsive navigation system, Bootstrap was used but there was bug that would not allow the navbar to be recolored to suit the the chosen colour scheme. In researching a cause (and solution) the developer found a question posted on Stack Overflow with a similar problem. It was from here that the developer was able to copy and edit the code given as a solution on Stack in order to implement a solution to the bug, with celebratory success.


## Technologies used

- html5
- CSS
- JS6
- Google Fonts
- Fontawsome 
- Github 


## Testing 







Markdown is a lightweight markup language based on the formatting conventions
that people naturally use in email.
As [John Gruber] writes on the [Markdown site][df1]

> The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

This text you see here is *actually- written in Markdown! To get a feel
for Markdown's syntax, type some text into the left window and
watch the results in the right.

## Tech

Dillinger uses a number of open source projects to work properly:

- [AngularJS] - HTML enhanced for web apps!
- [Ace Editor] - awesome web-based text editor
- [markdown-it] - Markdown parser done right. Fast and easy to extend.
- [Twitter Bootstrap] - great UI boilerplate for modern web apps
- [node.js] - evented I/O for the backend
- [Express] - fast node.js network app framework [@tjholowaychuk]
- [Gulp] - the streaming build system
- [Breakdance](https://breakdance.github.io/breakdance/) - HTML
to Markdown converter
- [jQuery] - duh

And of course Dillinger itself is open source with a [public repository][dill]
 on GitHub.

## Installation

Dillinger requires [Node.js](https://nodejs.org/) v10+ to run.

Install the dependencies and devDependencies and start the server.

```sh
cd dillinger
npm i
node app
```

For production environments...

```sh
npm install --production
NODE_ENV=production node app
```

## Plugins

Dillinger is currently extended with the following plugins.
Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantaneously see your updates!

Open your favorite Terminal and run these commands.

First Tab:

```sh
node app
```

Second Tab:

```sh
gulp watch
```

(optional) Third:

```sh
karma test
```

#### Building for source

For production release:

```sh
gulp build --prod
```

Generating pre-built zip archives for distribution:

```sh
gulp build dist --prod
```

## Docker

Dillinger is very easy to install and deploy in a Docker container.

By default, the Docker will expose port 8080, so change this within the
Dockerfile if necessary. When ready, simply use the Dockerfile to
build the image.

```sh
cd dillinger
docker build -t <youruser>/dillinger:${package.json.version} .
```

This will create the dillinger image and pull in the necessary dependencies.
Be sure to swap out `${package.json.version}` with the actual
version of Dillinger.

Once done, run the Docker image and map the port to whatever you wish on
your host. In this example, we simply map port 8000 of the host to
port 8080 of the Docker (or whatever port was exposed in the Dockerfile):

```sh
docker run -d -p 8000:8080 --restart=always --cap-add=SYS_ADMIN --name=dillinger <youruser>/dillinger:${package.json.version}
```

> Note: `--capt-add=SYS-ADMIN` is required for PDF rendering.

Verify the deployment by navigating to your server address in
your preferred browser.

```sh
127.0.0.1:8000
```

## License

MIT

**Free Software, Hell Yeah!**

[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)

   [dill]: <https://github.com/joemccann/dillinger>
   [git-repo-url]: <https://github.com/joemccann/dillinger.git>
   [john gruber]: <http://daringfireball.net>
   [df1]: <http://daringfireball.net/projects/markdown/>
   [markdown-it]: <https://github.com/markdown-it/markdown-it>
   [Ace Editor]: <http://ace.ajax.org>
   [node.js]: <http://nodejs.org>
   [Twitter Bootstrap]: <http://twitter.github.com/bootstrap/>
   [jQuery]: <http://jquery.com>
   [@tjholowaychuk]: <http://twitter.com/tjholowaychuk>
   [express]: <http://expressjs.com>
   [AngularJS]: <http://angularjs.org>
   [Gulp]: <http://gulpjs.com>

   [PlDb]: <https://github.com/joemccann/dillinger/tree/master/plugins/dropbox/README.md>
   [PlGh]: <https://github.com/joemccann/dillinger/tree/master/plugins/github/README.md>
   [PlGd]: <https://github.com/joemccann/dillinger/tree/master/plugins/googledrive/README.md>
   [PlOd]: <https://github.com/joemccann/dillinger/tree/master/plugins/onedrive/README.md>
   [PlMe]: <https://github.com/joemccann/dillinger/tree/master/plugins/medium/README.md>
   [PlGa]: <https://github.com/RahulHP/dillinger/blob/master/plugins/googleanalytics/README.md>
