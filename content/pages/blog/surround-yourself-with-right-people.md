---
title: Building a production ready website
slug: surround-yourself-with-right-people
date: '2023-03-26'
excerpt: >-
  Facilisis dui. Nulla molestie risus in mi dapibus, eget porta lorem semper.
  Donec sed facilisis nibh.
featuredImage:
  altText: Thumbnail
  type: ImageBlock
  url: /images/abstract-feature1.svg
  styles:
    self:
      borderRadius: medium
seo:
  metaTitle: Surround Yourself With the Right People
  metaDescription: You can add the excerpt and main keywords of your blog post here.
  socialImage: /images/abstract-feature1.svg
  type: Seo
colors: bg-light-fg-dark
type: PostLayout
author: content/data/person1.json
styles:
  self:
    flexDirection: col
isFeatured: false
---
 Right. So, uh, we're diving deep today into building like a website, but not just any website. Right. A production class website. That sounds intense.

It is kind of, yeah. It's a whole other level than just like throwing together a few pages.

Yeah, so what do we got here? Like, just, how much information are we talking about?

Well, we've got a ton of sources. Like, a mountain of them, really. Okay. And they cover, well, pretty much everything. The front end, the back end.

Okay.

Deployment, security, best practices. I mean, like, it's the whole shebang. Oh,

whoa, okay. Well, okay. I gotta say, one thing, uh, one thing that really caught my eye Yeah.

in like skimming this stuff is that there are these like frameworks

Right.

that can actually make your website super fast like right from the start.

Yeah, yeah, they're pretty awesome. They do a lot of the heavy lifting during the build process so users don't have to wait around for things to load.

So that's like before the website even goes live.

Exactly, yeah. It's all about building in that speed from the ground up.

Okay, so I guess my first question then is like, where do we even begin with all of this? I mean, it seems like a lot to take in.

Well, I think a good place to start is with the front end, right? That's the part of the website that, you know, people actually see and interact with.

And the foundation of that is HTML. Like, it's the basic structure of the page. But we're not just aiming for any old HTML here. We want what they call semantic HTML.

Okay, so what, uh, what's that?

It's about using the right HTML elements to give meaning to your content. It's not just about how it looks. Mm hmm.

It's about structuring it in a way that makes sense for, like, screen readers and search engines. Oh,

so it's like, it's like accessibility and SEO kind of all rolled into one.

Exactly, yeah. It's like building a house with a blueprint that everyone can understand.

Okay, so  Like, semantic HTML is the blueprint, then what?

Like, what comes next?

Well, then you gotta make it look good, right? That's where CSS comes in. Right,

CSS, that's the styling, right?

Exactly. And, uh, to make writing CSS more efficient, Our sources recommend using CSS preprocessors.

Like, what, what, what are some examples?

Like, uh, Sass or Less. These tools, they let you use things like variables and functions and mixins, which can really help keep your style sheets organized and, like, manageable, especially as your site grows.

Right, right. Okay, so we've got this structure and this style. Mm

hmm.

But what about making things, you know, interactive?

Ah, yeah, that's where Javascript comes in.

Right, Javascript.

It's what brings your website to life. Like, it handles all the dynamic stuff. Animations, user interactions, you know.

Right, right.

Any particular Javascript things we should be focusing on?

Our sources really emphasize understanding modern Javascript practices, particularly asynchronous programming.

Asynchronous programming.

Yeah.

Okay, so for those of us who, uh, might not be super familiar with that, can you break that down a bit?

Yeah, so think of it like this.  You send a request to a server for some data, right? With asynchronous programming, your website can keep doing other things while it waits for that data to come back.

Oh, okay. Instead of

just like freezing up.

I see. So it keeps things running smoothly.

Exactly. It's all about creating a smooth and responsive user experience.

Gotcha. Okay, so we've got HTML, CSS, and JavaScript. Those are like our core building blocks. Yep. But then, uh, our sources also mentioned front end frameworks.

Yeah. And

I gotta say, there are a lot of them. There

are, yeah.

React, Angular, Vue. js. Mm hmm. And then there's this newer one, Svelte.

Right.

How do we even choose?

Yeah, it can be a bit overwhelming.

Yeah.

But, uh, I guess the best way to think about it is that each framework has its own strengths. Okay. Like React, for example, it's really popular. And it uses this thing called a virtual DOM. Mm hmm. Okay, which basically means it can update the page super efficiently, so it's great for like complex applications with lots of moving parts.

Angular is another big one. It's favored for larger enterprise level applications because it provides a very structured, like almost rigid framework for building things. I see. And then Vue. js. Yeah. Um, it's often praised for being easy to learn and integrate into existing projects. Okay. It's known for its performance, and it's a good choice for, like, single page applications and those really interactive elements you see on modern websites.

Cool. And then there's Svelte. You mentioned that one earlier.

Yeah, Svelte's a bit newer, but it's gaining popularity fast.

Why is that? What makes it different?

Well, it's all about speed, really.

Okay.

It shifts a lot of the work that traditionally happens in the browser, like, while the user's waiting. Mm. It shifts that to the build process.

Oh, okay. So it

can create some seriously fast websites.

So, like, it does a lot of the work ahead of time.

Exactly. Interesting.

It's like

pre cooking your ingredients before a big dinner party, you know?

Yeah, I like that analogy. Okay, so we've got all these frameworks. Mm hmm. Where do we even start learning them?

Well, the official documentation for each framework is a good starting point.

Right.

Our sources actually include links to those, so you can check those out. And there are also tons of great courses and tutorials available online.

Okay, so one thing I keep seeing pop up with these frameworks is this idea of state management.

Ah, yes. State management.

What is that exactly?  Is it something we need to worry about right away?

Well, it's basically about keeping track of all the data that changes in your application.

You

know, things like user input, loading states, all that stuff.

Right.

And as your application grows, it can get pretty complex.

I can imagine. Like,

think of it like juggling. As you add more balls, you need a good system to keep them all in the air.

Right, so you don't drop everything.

Exactly, and that's where state management libraries come in. Like, for React, there's Redux, there's Zustand. For Vue. js, there's Vuex or Pina. Okay.

These libraries provide structured ways to manage that data flow so your app's more predictable and easier to debug.

Gotcha. So maybe not crucial for small projects. Right. But as things scale up. Definitely. State management becomes really important.

Yeah, it can save you a lot of headaches down the road.

Okay. Well, I think we've laid a pretty solid foundation for the front end here. But, uh, before we move on, I think we need to talk about testing.

Ah, yes. Testing. It's not always the The most glamorous part of web development, but it's absolutely crucial.

Why is that?

Well, because it helps ensure that your code actually does what it's supposed to do.

Right. And that you haven't introduced any bugs. Like, imagine building a bridge without testing its structural integrity. That's what coding without testing feels like.

Yeah, that's a scary thought.

Yeah.

Yeah.

So, uh, there are different types of testing, too.

Okay.

There's unit testing, where you test individual components in isolation.

There's integration testing, where you see how different parts of your app work together. Okay. And there's end to end testing, where you simulate real user interactions.

So that's, like, testing the entire flow of, say, like, a checkout process.

Exactly.

Yeah. Okay.  And, uh,  I'm guessing there are tools for all this?

Oh, tons of tools. Jest, Mocha, React Testing Library, Cypress, just to name a few.

Wow, it's a whole other world.

It is, yeah, but you don't need to become a testing expert overnight.

Right.

Just start with the basics and gradually incorporate more advanced techniques as you go.

Okay, so, we've covered the front end basics, talked about different frameworks, we've even touched on testing.

Now what?

Now, I think it's time to dive into the back end, the brains of the operation, if you will.

Okay, let's do it.

This is where things start to get really interesting.

Alright, I'm ready, let's get into it.

Welcome back. Last time we, uh, we kind of laid the groundwork for the front end and back end, but now I think it's time to talk about the database.

Okay, the database. So like, what is that exactly? It's

basically, uh, like the heart of your website.

It's where

all the information is stored, you know, like user data, content, all that stuff.

So it's like the library of the website.

Yeah, exactly. A library for all your website's information.

Okay, that makes sense.

Yeah. But there are so many different types of databases. Right. I mean, our sources mentioned relational databases. No SQL databases.

Yeah, yeah, there are a lot of options.

How do we even choose?

Well, it depends on like, what kind of information you need to store. And how you need to access it, like relational databases, those are kind of the traditional ones.

They're good for storing structured data.

Structured data, so that's like, what?

Like, data that fits neatly into rows and columns.

Uh huh.

Think of it like a spreadsheet, you know, with all the information organized in a very specific way.

Right, right. And you said these are good for certain types of information.

Yeah, like customer information, product details, financial records, that kind of stuff.

Okay. So what are some examples of relational databases?

Uh, some popular ones are PostgreSQL and MySQL.

Okay, those sound familiar. And then there are NoSQL databases.

Right. Those are a bit more, uh, flexible. They can handle a wider variety of data, including unstructured data.

Unstructured data. Yeah. So that's like the opposite. It's

like data that doesn't fit neatly into those rows and columns. Right. Like social media posts, sensor data, user preferences, stuff like that.

Okay. So If you need more flexibility, NoSQL might be a better choice.

Yeah, exactly. It all depends on your specific needs.

Like, MongoDB is a popular NoSQL database that's good for document based data, and then Cassandra is another one that's designed for handling massive amounts of data with high availability.

Okay, so, we choose our database, we figure out what kind of information we need to store, and how we need to access it,

mm hmm.

But then how do we actually interact with the database from our code?

Ah, well that's where RMs and ODMs come in.

ORMs? ODMs, what are those?

Think of them as, uh, like, translators. They allow you to work with database records as objects in your programming language. So you don't have to write all these complex SQL queries.

Yeah, that's the language you use to talk to relational databases. But ORMs, they let you use your regular programming language, so it's much easier to work with.

So it's like, it simplifies the communication between our code and the database.

Exactly, yeah. It

makes it more developer friendly.

Right, and there are specific ORMs for different programming languages and databases.

For Python with Django, there's the Django ORM. Mm hmm. For Node. js and MongoDB, there's Mongoose.

Okay, so we've got our database set up. Yeah. We've got our RRM or ODM in place. What's next?

Well, databases, they change over time.

Okay.

As you add new features, you might need to update your database structure, add new tables, change existing ones.

Right,

right. And

that's where migrations come in.

Migrations. Okay, tell me more.

They're basically like version control for your database.

Hmm, interesting.

They keep track of all the changes you make, so you can apply them to different environments in a controlled way.

So it's like, if we make a change to the database, we can keep track of it, and then easily roll it out to, say, our staging server, and then to production.

Exactly. Okay, that makes sense. Any specific  tools for migrations?

Yeah, there are some popular ones, like for Python, there's Alembic, and for Java, there's Flyway.

Okay, cool. So, we've talked a lot about the database. But there's another big piece of the puzzle here, right?

I think it's time to talk about DevOps.

DevOps.

I've heard that term thrown around a lot.

Yeah.

But I'm not really sure what it means. Can you break it down for us? Sure.

It's kind of a, uh, a philosophy. It's about collaboration, automation, efficiency. It's about bringing together the development team and the operations team to create a smoother workflow for, you know, building, testing, and deploying software.

So it's like, Breaking down the silos between those two.

Exactly. Yeah, it's about working together more effectively.

Okay, I like that. And our sources mentioned a few specific things related to DevOps. Right. Version control, continuous integration, continuous deployment.

Yeah, those are some of the key components of DevOps.

Okay, so version control, what is that?

Well, it's basically a way to track Changes to your code over time. Okay. So you can see who made what changes when they made them and you can revert back to previous versions if you need to.

So like a time machine for your code.

Yeah, exactly. Like Git is a popular version control system.

Okay, Git. I've heard of that.

Yeah, it's pretty much the industry standard these days.

Okay, cool. And then what about continuous integration and continuous deployment?

Right? So continuous integration or CI is about continuous deployment. Yeah. Automatically building and testing your code whenever you make changes.

So you can catch errors early on. Right. And continuous deployment, or CD is about automatically deploying your code to your servers.

Okay.

Once it passes all the tests.

So like, Every time we make a change, it automatically gets tested, and then if everything's good, it gets pushed live.

Exactly. It's all about automating that process, so you can release new features faster.

Okay, that sounds pretty powerful. Any particular tools for CICD?

Yeah, there are a bunch of them, like GitHub Actions. GitLab CI, Jenkins, those are just a few examples.

So we've got our code under version control.

We've

got our CICD pipeline set up.  What else do we need to think about in terms of deployment?

Well, our sources mention containerization as a really useful technique.

Containerization, what's that?

It's about packaging your application and all its dependencies into a self contained unit called a container.

Okay.

And then you can run that container on any system that supports it. Docker.

Docker.

Yeah.

It's a popular containerization platform.

Okay. So it's like, we're creating a little mini environment for our application to live in.

Exactly. It makes deployment much easier and it ensures that your application will run the same way on any system.

So it's like, it's taking the guesswork out of deployment.

Right. You don't have to worry about like different server configurations or anything like that.

Makes sense. And are there tools for managing these containers? Yeah.

Yeah. Like. Docker Compose is a popular one. It lets you define and manage multi container Docker applications.

So you can have like a container for your web server, a container for your database, and they can all talk to each other.

Exactly, yeah.

Okay, cool. So we've got our database. We've got our code. We've got our containers. Where do we actually put all of this? Like, where does our website actually live?

Ah, that's a great question. Choosing the right deployment platform is important.

Yeah, I can imagine.

There are a lot of options out there, like cloud providers, specialized platforms, all sorts of stuff.

Okay, so break it down for us. What are some of the options?

Well, you've got your big cloud providers, like AWS, Azure, Google Cloud.

Okay, those are the big names, yeah.

They offer a ton of flexibility and control, but they can also be a bit complex to manage.

Right.

Right. And then you've got platforms like Netlify, Vercel, Heroku.

Okay, I've heard of those.

Those are more specialized, and they offer a more streamlined deployment experience. Like Netlify and Vercel, those are great for static websites. Yeah. And Heroku is a good choice for deploying web applications built with different programming languages.

So it really just depends on the specific needs of the website.

Exactly. It's about finding the right balance between control, ease of use, and cost.

Okay, so, we choose our platform, and then what? Like, how do we actually get our website up and running on that platform?

Well, that's where build processes and CICD pipelines come in.

Okay, so, those are important for deployment too.

Definitely. Okay,

remind me, what are those again?

So build processes involve like compiling your code, bundling your assets, getting everything ready for deployment. Okay. And CICD pipelines, they automate those processes. Right. And they integrate with your version control system. So everything happens automatically.

So it's like, we push our code to our repository. Yeah. And then the pipeline takes over. It builds the code. Okay. Tests it, and then deploys it to our chosen platform.

Right. It streamlines the entire process.

Okay, I see. So, our website is live, everything's working, are we done?

Well, not quite. There's one more thing we need to talk about, and that's monitoring.

Monitoring. Okay, so why is that important?

Because, once your website is live, you need to make sure it's actually working properly. Right. You need to keep an eye on things like server load, response times, error rates.

Okay.

Basically, you need to make sure everything's running smoothly.

So, it's like having a dashboard that shows us all the vital signs of our website.

Exactly, yeah. There are tools for that, like New Relic, Datadog, Prometheus.

Okay.

That they can help you collect and visualize all that data.

Cool. And, uh, what about logging? Our sources mention that too.

Right. Logging is basically keeping a record of everything that happens on your website.

Hmm.

So you can troubleshoot problems.

Okay. And see

what's going on. So

it's like a history of all the activity on the site.

Exactly. And there are libraries that can help you with that too.

Okay.

Like Winston for Node. js or the built in logging module for Python.

Okay. I think I'm starting to get a sense of the scope of all of this.

Yeah. It's definitely a lot to take in.

It is.

But we've covered a lot of ground here.

We have. We talked about databases, DevOps,  deployment, monitoring, logging. It's a lot.

Yeah. But it's all essential for building a production class website.

Okay. So. Where do we go from here?

Well, I think in the final part of our deep dive,

Okay.

We should take a step back and talk about some general best practices and principles that can help you really elevate your website to the next level.

Okay, I'm ready for that. Okay. Okay, so, uh, welcome back. We've, we've covered a lot of ground in this deep dive. Yep. Front end, back end, databases, deployment, like all that stuff. Mm hmm. But now I think it's time to talk about Those like finishing touches those best practices that really

right

make a website stand out

exactly.

Yeah, it's like we've built the house now We need to you know,

decorate it

decorate it furnish it make it like a home, you know,

yeah Yeah, I like that and uh I think a good place to start is with security.

Ah, yes. Security. Always important.

So we've, we've touched on security a bit throughout this deep dive.

Right.

But why is it, like, especially important at this stage?

Well, because security is not just something you tack on at the end. Mm hmm. It needs to be baked in from the beginning. Right. Like, it's an ongoing process, you know?

Okay, so what are some of the key things we need to keep in mind?

Well, first of all, you need to understand the common vulnerabilities.

Like, what are the ways that attackers might try to exploit your website?

Okay, so how do we learn about that?

Well, a good place to start is with the OWASP Top 10.

The OWASP Top 10.

Yeah, it's basically a list of the most common web security risks.

Oh, okay.

Like things like SQL injection, cross site scripting, that kind of stuff.

Right, right. Okay, so We know what to look out for, then what?

Well, then you need to implement strong authentication.

Okay.

Make sure you're using HTTPS.

Right, for secure communication.

Exactly.

Okay, so, it's like, We're building a fortress around our website.

Yeah, pretty much.

Okay, so, security check. What's next?

Well, another big one is performance.

Performance. Okay, so, why is that so important?

Because nobody likes a slow website, right?

No, definitely not. I've definitely left websites that were taking too long to load.

Exactly. So, you need to make sure your website is as fast and efficient as possible.

Okay, so, how do we do that?

Well, we've talked about some techniques already, like Code splitting, lazy loading, image optimization, caching.

Right, right. A lot of things to keep in mind.

Yeah, it's all about optimizing every aspect of your website.

So it's like fine tuning a race car, kind of?

Yeah, exactly. You want to make sure everything's running as smoothly as possible.

Okay, I like that analogy. Yep. So, security and performance, those are two big ones. What else is there?

Well, another important aspect is maintainability.

Maintainability. Okay, so, what does that mean exactly?

It means building your website in a way that makes it easy to understand, modify, and extend in the future.

So it's like, future proofing our code.

Exactly. Yeah, it's about making sure that you or someone else can come back to the code later and easily figure out what's going on.

Makes sense. So how do we make our code more maintainable?

Well, clean code is a big part of it.

Okay. Using

meaningful variable names, adding comments, following coding standards.

It's like writing the code in a way that's easy to read.

Yeah, exactly. Like you're writing it for a human, not just for a computer. Makes sense. Yeah.

Anything else?

Modular design is another important aspect.

Modular design. Yeah,

breaking down your code into smaller, self contained modules.

Okay.

So you can easily update or modify one part of the code.

Right. Without affecting the rest of it.

Okay, I see.  And, uh, what about design patterns? I've heard that term before.

Ah, yes, design patterns. Those are really useful.

Okay, so what are they?

They're basically reusable solutions to common software design problems. Like they're tried and true approaches that can save you a lot of time and effort.

So it's like having a library of best practices to draw from.

Exactly, yeah. But you have to use them wisely, you know. It's not just about blindly applying a pattern.

Right.

You have to understand the problem you're trying to solve and choose the right pattern. for the job.

Okay, that makes sense. So clean code, modular design, design patterns, all

good

for maintainability.

Yeah, and don't forget about testing.

Right, testing. We talked about that before.

Yeah, but it's important for maintainability too.

Okay, why is that?

Because when you have a well tested code base, you  can be more confident about making changes. Right. You know that you're not going to break anything.

Okay, so testing is like a safety net.

Exactly.

It gives us the confidence to make changes without. Like, breaking everything.

Right. So, make sure you're testing regularly and addressing any issues that come up.

Okay. Testing, check. What about working together as a team?

Ah, yes. Collaboration is key, especially on larger projects.

Right. Any tips for that?

Well, our sources recommend Agile development methodologies.

Agile, okay. So what's that all about?

It's a way of working that emphasizes iterative development, frequent communication, and adapting to change. It's all about being flexible and responsive, you know?

Okay, so it's not just about following a rigid plan.

Right. It's about being able to adjust as needed.

Right. So we've talked about a lot of  best practices here. We have. Security, performance, maintainability, collaboration. It's a lot to take in.

It is. Yeah.

Yeah.

But it's all important for building a successful website.

Okay. So as we wrap up this deep dive, what are like the key takeaways?

Well, I think the main thing is that building a production class website, it's not just about writing code, it's about taking a holistic approach, you know, it's about thinking about security, performance, maintainability, collaboration, all those things.

It's about the big picture.

Exactly, and it's about constantly learning and evolving, you know.

Right, because the web development world is always changing.

Always, yeah.

Okay, well, I think that's a great place to leave it. Thanks for taking us on this deep dive.

My pleasure.

And to all of you listening, remember, building a website can be challenging, but it's also incredibly rewarding.

Absolutely. So

keep learning, keep experimenting, and keep building amazing things.

And hey, maybe someday we'll be featuring your website on the deep dive.

That would be awesome. Until

next time.
