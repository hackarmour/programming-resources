# Programming Resources
List of resources for aspiring contributors related to technologies we use here at hackarmour. These resources are targetted mostly towards beginner to intermediate level programmers. These resources are separated in different categories and time taken to cover each may vary from the estimated time mentioned here.

# Introduction
We use a lot of tech at hackarmour. We are mostly a security community but this repository is mainly focused on development and programming side of things. Please [google](https://www.google.com) the terms you don't understand. Some of the projects or assignments may look confusing and you may not find everything here to master a particular topic so you will need to research and find the answers on your own, so cope harder.

# Table of Contents
We are working on a search engine and also make some security challenges. You may find a lot of web development stuff here, including some malware and system programming resources. This will mostly tend to start with the basics and then will move to more advanced stuff.
- Basics Of Computer Science
- Web Development
- System Programming
- Conclusion

## The Basics of Computer Science ~ 3-4 months
- [CS50 by Harvard](https://www.edx.org/course/introduction-computer-science-harvardx-cs50x)
  
  Will teach you the basics of computational thinking, basic data structures & algorithms, programming with C, python, javascript and also a good introduction to web development. Complete the exercises and assignments of the course for some practical work
  
- [CS50's Introduction to Programming with Python](https://www.edx.org/course/cs50s-introduction-to-programming-with-python)

  This course is mostly focused towards the python programming language, including in depth knowledge of python. Python is a good programming language for beginners, but we dont recommend it using outside data science circles. We can, however, create some cool security challenges and tools with it.

- [Git and GitHub Lecture by CS50](https://www.youtube.com/watch?v=eulnSXkhE7I) is a must. The version control system helps us to manage our code and we can host out code easily on github.
  
- Projects: All the assignments given in the CS50 course should be enough.

## Web Development [MERN] ~ 5-6 months
This section consists of almost all the tooling and languages required to learn web development. Remember, this section isn't only about making websites, it is also about programming servers which can also power a mobile app or a multiplayer game.

- [MDN](https://developer.mozilla.org/en-US/docs/Learn) is one of the best guides as well as a great reference to all the languages and tooling required to learn web development. One of them is an article about [How the Web works](https://developer.mozilla.org/en-US/docs/Learn/Getting_started_with_the_web/How_the_Web_works). However this does not cover hands on exercises.

- [FreeCodeCamp](https://freecodecamp.org) is a great place where you can learn by doing. I recommend this mostly for HTML CSS and basic JavaScript.

- Web Project I - By this time you must have mastered the basics of front end development. I suggest to check out the [Stanford Web Homeworks](https://web.stanford.edu/class/archive/cs/cs193x/cs193x.1176/homework/) and try to complete [Listicle](https://web.stanford.edu/class/archive/cs/cs193x/cs193x.1176/homework/1-listicle), And after that for a JavaScript fresher, try to make a quiz website.

- [ReactJs](https://reactjs.org) is a library for creating javaScript web apps. Try to learn about the react ecosystem, things like nextjs and styled-components. They are going to make your life way easier. You can also choose another framework/library, but we recommend reactjs.

- [NodeJs](https://nodejs.dev/) is a way of running javaScript outside of a browser. Which makes it an awesome fit for server programming. After that you can use [ExpressJs](https://expressjs.com) to make it easier for you to create server side apps. Follow the [Local Library Tutorial](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs) where you can also get exposure to mongodb, a database to store all your user generated data. 
  For connecting with SQL databases, [knex](http://knexjs.org/), [objection](https://vincit.github.io/objection.js/), [typeORM](https://typeorm.io/) and [prisma](https://typeorm.io/) are pretty good.
  
- [The Odin Project](https://www.theodinproject.com/)'s full stack JasvaScript is an amazing resource for project based learning. You can make it your primary guide too.

- You should also look into [TypeScript](https://www.typescriptlang.org/), which is basically JavaScript with types. It helps to let u write more structured and bug free code. Try to implement expressjs and react apps with TypeScript, and if possible implement the rest of the web projects in TypeScript as well.

- After knowledge of Node, Express and mongodb, you can learn how to implement REST APIs and connect your server to the client (let us assume its reactjs). Congratulations, you are now a MERN stack developer [Mongo, Express, React, Node].

- You may also want to "containerize" your app which essentially means running it in a well defined, controlled and secured environment. You can read about docker [here](https://www.ibm.com/in-en/cloud/learn/docker). You may also wana look at [docker-compose](https://docs.docker.com/compose/) which makes it easier for you to spin up multiple containers using a config file.

- Web Project II - Now you can make the [final project](https://web.stanford.edu/class/archive/cs/cs193x/cs193x.1176/final-project/) of stanford web fundamentals class. Also, you can now experiment with different file structures, and design patterns for your apps.

- Learn about how [JWT](https://jwt.io/) works and how to implement it in your node application, so that you can authenticate and authorise users. This is very helpful if you want people to log in and perform certain account based actions in your app. Use the [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken) library to implement that in your node app and you can later save the authentication information in your client side, send it with all the requests to perform authentication.

- Web Project III - [A social media app](https://www.crio.do/projects/javascript-socail-media-nodejs/) by crio. I would not suggest following the instructions; make your own decisions as you already are familiar with the technologies. Do see the introduction page where they show the screenshots and stack of the app, including a demo video and all the features. Try to make your own version of it.

- [Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/v41/): Make sure the applications you create is secure. 

## Golang ~ 2 months

MERN is an excellent stack for web programming as all the tooling is in javaScript. We do not any alternative for javaScript in a web browser but we have plenty of languages to choose from if we are making servers, you don't always have to use nodejs. Nodejs is fast (atleast more than python or ruby) and pretty popular hence it has a lot of library and community support. But when it comes to reliable, stable and blazingly fast backends, I prefer [Go](https://go.dev/). A significant amout of the hackarmour search engine is written in go. Here are some resources you can use to master it.

- [Introduction to programming with Go](https://www.golang-book.com/books/intro): It is an amazing free book to get started with golang. Also teaches stuff beyond basics like crypto and servers in go
- After you are done with the basics, now u can directly jump into server programming. You can follow [writing web applications](https://go.dev/doc/articles/wiki/) and then you can try [Developing a RESTful API with gin](https://go.dev/doc/tutorial/web-service-gin) (a framework for go)
- As with Js, you can find many golang packages like JWT or bcrypt. Also including a sql query builder like [sqlx](http://jmoiron.github.io/sqlx/), or an ORM like [Ent](https://entgo.io/) or [Gorm](https://gorm.io).
- Go Project I - Make a password manager backend with encryption. [Instructions](https://cdn.discordapp.com/attachments/872862958345142394/1014138422190952458/unknown.png).
- Go Project II - Remake the Social media backend in Web Project III with go

## System Design

As now you know how to work with docker and docker compose to containerize your apps and manage deployments, it is now time to learn some effective ways to design a large scale system. Most startups these days, use different languages for different tasks and a lot of them use [microservices](https://microservices.io/). Using them brings a lot of new changes to the infrastructure and makes the code too complex to maintain. So there are a few things you need to take care of:

- [Load Balancing](https://www.youtube.com/watch?v=K0Ta65OqQkY): which request goes to which service.
- [Docker Compose networking](https://docs.docker.com/compose/networking/), [GRPC](https://grpc.io/): understand how services talk to each other using communication protocols.
- [Message brokers](https://www.ibm.com/in-en/topics/message-brokers), [Rabbit MQ](https://www.rabbitmq.com/): a service for sending messages to other containers.
- [Event Streaming](https://tanzu.vmware.com/event-streaming), [Kafka](https://kafka.apache.org/): streaming events such as logs of statistics data.
- [DB Sharding](https://en.wikipedia.org/wiki/Shard_(database_architecture)): distributed databases.
- [Redis](https://redis.io/): a very fast in-memory DB can be used for caching.
- [Kubernetes](https://kubernetes.io/), [Kubernetes and Microservices Course by Udacity](https://www.udacity.com/course/scalable-microservices-with-kubernetes--ud615): Important for horizontal scaling and availability across the globe, self healing deployments and so on.

These are just few topics you need to know about when starting to learn microservices. System design includes a lot of things. Please follow the [System Design Roadmap](https://roadmap.sh/system-design) to get a wider look at what stuff you will be working with. Don't get overwhelmed with it just yet, as everything is incrementally adoptable to your backend, and often you wont need everything in your codebase.

### Projects
- Try to make the Social Media Backend as a microservice
   - You can make different services which handle users, posts, monitoring, admin stuff.
- Try to implement your own load balancer in Golang.
    - This is a good cloud systems project. Use goroutines. [The Wikipedia Page](https://en.wikipedia.org/wiki/Load_balancing_(computing)) should be a good starting point.
- Design the system of backends like amazon, uber, netflix, twitter or equivalent. You can find handful of tutorials on youtube.
- Design Wikipedia, and implement it. You can find how wikipedia works in the website itself. You can also create your own version of it, but make sure to implement it's core features such as adding a page, editing by other users, and validation of edits. Try to use distributed database management system and a lot of caching here as availability across the globe is an important priority.

## System Programming & Malware ~ 3 years

System software is something which runs very close to the hardware. They include OS, drivers, compilers, runtime environments, etc. It's often challenging to deal with such a thing for a beginner but I have made and entire repository called [System Programming Roadmap](https://github.com/ujjwal-kr/system-programming-roadmap) which also includes exploitation of system software. Keep in mind that it is a THREE YEAR long roadmap so have some patience. It also includes malware research materials. I'll update the repo with more meaningful projects soon.

## Conclusion
As you know things can get complex at times if you are a beginner. I wish I had the same resources when I started but this can also lead you to become overwhelmed by these materials, and if that happens, you are not alone. Just be slow and steady and never hesitate to ask questions. Try to complete all the projects and if you think you are still facing problems or errors while making them, don't feel like it's not for you, again you are not alone in that situation. Enjoy the process of iterating over the learning material and trying to solve the problems in the projects. It's still what I do to learn something new.
  

