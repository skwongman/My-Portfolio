<h1 align="center">My Portfolio</h1>

## Table of Contents

- [Individual Side Projects](#individual-side-projects)
  - [(1) Listify Mobile App (React Native) (*Feb to Mar 2025*)](#1-listify-mobile-app-feb-to-march-2025)
  - [(2) My Portfolio Webite (*Apr 2024*)](#1-my-portfolio-website-apr-2024)
  - [(3) Job Application Histories System (*Mar 2024*)](#2-job-application-histories-system-mar-2024)
  - [(4) Drama Website (*Feb 2024*)](#3-drama-website-feb-2024)
  - [(5) Shopping Cart Calculator Website (*Jan 2024*)](#4-shopping-cart-calculator-website-jan-2024)
  - [(6) Message Board Website (*Sept to Dec 2023*)](#5-message-board-website-sept-to-dec-2023)
  - [(7) Listify Mobile App (Flutter) (*Sept 2023*)](#6-listify-mobile-app-sept-2023)
  - [(8) Listify Website (*Jul to Aug 2023*)](#7-listify-website-jul-to-aug-2023)
  - [(9) News Website (*May to Jun 2023*)](#8-news-website-may-to-jun-2023)
  - [(10) JProgrammer Website (*Jan to Mar 2023*)](#9-jprogrammer-website-jan-to-mar-2023)
  - [(11) Blog Website (*Jan 2023*)](#10-blog-website-jan-2023)
  - [(12) Taipei-Day-Trip Website (*Nov to Dec 2022*)](#11-taipei-day-trip-website-nov-to-dec-2022)
  - [(13) To-Do-List Website (*Aug 2022*)](#12-to-do-list-website-aug-2022)
  - [(14) Python Telegram Bot (*Sept 2018*)](#13-python-telegram-bot-sept-2018)

- [Group Side Project](#group-side-project-1)
  - [(1) Weather Forecast Website (*Dec 2022*)](#1-weather-forecast-website-dec-2022)

- [Contact](#contact-1)

## Individual Side Projects:

- ### **(1) Listify Mobile App (React Native) (*Feb to Mar 2025*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_15.png" alt="preview"></p>

  - **Theme:** A mobile app version of Listify website (Jul to Aug 2023), it is a to-do list app which can be launched in the mobile. Since it is connected to the same backend API of Listify Website, users can use either website or mobile app up to their own preference.

  - **Stacks Used:** React Native, Create-Expo-App, Expo, Java, Spring Boot, Maven, Hibernate, Lombok, JPA, MySQL, ORM, RESTful API, MVC Pattern (Models, Dtos, Mappers, Controllers, Repositories, Services, Implementations, Dependency Injection, Views), Global Exception Handler, Postman, Docker, Portainer, CICD (Jenkins), Git, GitHub, Nginx, Slack Chat Bot, Linux Cron Jobs <br><br>

- ### **(2) My Portfolio Website (*Apr 2024*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_14.png" alt="preview"></p>
  
  - **Live Demo:** https://project.jprogrammer.online/

  - **Theme:** This website aims to summarize all of my side projects in one go. It allows the web owner to easily create their portfolio. They can view, create, edit, and delete each portfolio with ease (only logged-in user can credit, edit and delete portfolio). Also, Nuxt Router Middleware was used to control the permission to each page. The frontend of the website primarily uses Vue.js with the Nuxt.js framework. In the backend, it primarily uses C# and ASP.NET Core Web API to create API routes.

  - **Stacks Used:** Nuxt.js, Vue.js, Composition API, Options API, Pinia (Global State Management), Nuxt Router Middleware (user authentication and permission), Tailwind CSS, Responsive Web Design, Routes, Routing, Client Side Rendering, Server Side Rendering, C#, ASP.NET Core Web API, .NET 8.0, .NET Entitiy Framework, LINQ, ORM, RESTful API, Swagger API, MVC Pattern (Models, DTOs, Mappers, Controllers, Interfaces, Repositories, Dependency Injection, Views), SQL Server, Code First Approach, Docker, Portainer, CICD (Jenkins), Git, GitHub, Nginx <br><br>

- ### **(3) Job Application Histories System (*Mar 2024*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_13.png" alt="preview"></p>
  
  - **Live Demo:** https://job.jprogrammer.online/

  - **Theme:** This system allows users to quickly search through their past job application histories. Users can search for all jobs applied by using the company name in the top search bar. Each table header has a sorting function, making it easy for users to get a quick overview. Also, there is a show/hide button that provides flexibility for users to display or hide specific columns of the table. Frontend primarily uses React table with Shadcn, while the backend relies on Nest.js with GraphQL. Furthermore, a Node.js program is used for the Extract, Transform, and Load (ETL) process, which loads job data into the MySQL database on a daily basis.

  - **Stacks Used:** React.js, Next.js, Tailwind CSS, React Table, Shadcn, Skeleton Loading Effect, GraphQL, Apollo Client, Client Side Rendering, Node.js, Express.js, Nest.js, TypeScript, Sequelize, Apollo Server, Apollo Sandbox, Schema First, TypeDefs, Resolver, MySQL, Docker, CICD (Jenkins) <br><br>

- ### **(4) Drama Website (*Feb 2024*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_12.png" alt="preview"></p>
  
  - **Live Demo:** https://dramaweb.jprogrammer.online/

  - **Theme:** This website provides the latest Japanese drama information. Instead of Client Side Rendering, this website was built with Node.js and Express.js with Server Side Rendering by using EJS. Also, a Python program was used for web crawling for Japanese drama data on a daily basis. Once the web crawling is completed, it will send a notification to the Slack chat bot right away.

  - **Stacks Used:** HTML, CSS, JavaScript, EJS, View / Template Enginee, Server Side Rendering, Node.js, Express.js, MongoDB, Mongoose, MVC Pattern, Python (Web Crawling), Slack Chat Bot, Linux Cron Jobs, Docker, CICD (Jenkins) <br><br>

- ### **(5) Shopping Cart Calculator Website (*Jan 2024*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_10.png" alt="preview"></p>

  - **Live Demo:** https://skwongman.github.io/Shopping-Cart-Website/

  - **Theme:** TypeScript and Object-oriented Programming were particularly adopted in this project. It is a simple counter to calculate the total amounts spent for all shopping cart items added. Also, it allows users to copy the pre-definied texts to the clipboard (viz. ctrl + c) by clicking nearby buttons. Webpack was also used for codes bundling to achieve an easy way for website deployment.

  - **Stacks Used:** HTML, CSS, TypeScript, Object-oriented Programming, Local Storage, Webpack <br><br>

- ### **(6) Message Board Website (*Sept to Dec 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_9.png" alt="preview"></p>

  - **Live Demo:** https://message.jprogrammer.online/

  - **Theme:** It was built with the modern frontend and backend frameworks, which are Next.js (React.js) and Nest.js (Node.js and Express.js with TypeScript). It is a message board which allows users to post, like, unlike messages, and upload images onto the website. Also, there is a member login system, only registered members can read and post message here.

  - **Stacks Used:** React.js, Next.js, TypeScript, Tailwind CSS, React Hooks (useState, useEffect, useContext), Redux, Props, Custom Hooks, Uploadthing (image uploader), Responsive Web Design, Prettier, EsLint, Node.js, Express.js, Nest.js, Sequelize, Pipes, Guards, RESTful API, MySQL, Swagger API, Bcrypt, JWT, MVC Pattern, Docker, CICD (Jenkins) <br><br>

- ### **(7) Listify Mobile App (Flutter) (*Sept 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_8.png" alt="preview"></p>

  - **Theme:** A mobile app version of Listify website (Jul to Aug 2023), it is a to-do list app which can be launched in the mobile. Since it is connected to the same backend API of Listify Website, users can use either website or mobile app up to their own preference.

  - **Stacks Used:** Flutter, Dart, Widget, Java, Spring Boot, Maven, Hibernate, Lombok, JPA, MySQL, ORM, RESTful API, MVC Pattern (Models, Dtos, Mappers, Controllers, Repositories, Services, Implementations, Dependency Injection, Views), Global Exception Handler, Postman, Docker, Portainer, CICD (Jenkins), Git, GitHub, Nginx, Slack Chat Bot, Linux Cron Jobs <br><br>

- ### **(8) Listify Website (*Jul to Aug 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_7.png" alt="preview"></p>

  - **Live Demo:** https://listify.jprogrammer.online/

  - **Theme:** It is a to-do list website. Users can check, add, update, and delete the to-do items easily. Also, it is connected to an instant chat bot called "Slack", so that users will be reminded right on the due date of each to-do task.

  - **Stacks Used:** Vue.js, Vuetify, Options API, Composition API, Composable Custom Hooks, Routes, Routing, Responsive Web Design, Java, Spring Boot, Maven, Hibernate, Lombok, JPA, MySQL, ORM, RESTful API, MVC Pattern (Models, Dtos, Mappers, Controllers, Repositories, Services, Implementations, Dependency Injection, Views), Global Exception Handler, Postman, Docker, Portainer, CICD (Jenkins), Git, GitHub, Nginx, Slack Chat Bot, Linux Cron Jobs <br><br>

- ### **(9) News Website (*May to Jun 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_6.png" alt="preview"></p>

  - **Live Demo:** https://news.jprogrammer.online/

  - **Theme:** It is a MERN (MongoDB, Express.js, React.js, Node.js) stack project. It allows users to browser the latest Hong Kong news information.

  - **Stacks Used:** React.js, Create-React-App, React Hooks (useState, useEffect, useRef), Routes, Routing, Responsive Web Design, Python (Web Crawling), Node.js, Express.js, MongoDB, Mongoose, Docker, CICD (Jenkins) <br><br>

- ### **(10) JProgrammer Website (*Jan to Mar 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_5.png" alt="preview"></p>

  - **Live Demo:** https://jprogrammer.online/

  - **GitHub:** https://github.com/skwongman/JProgrammer/

  - **Theme:** It is my second full stack individual side project during my study in the Web Development Bootcamp without any guidance. It is an online platform which allows users to browse the latest information on Japanese dramas. Members can also 1) create & update drama information, 2) post & reply in the discussion forum, and 3) chat instantly with other members.

  - **Stacks Used:** HTML, CSS, JavaScript, jQuery, Bootstrap, Chart.js, View Engine (EJS), Responsive Web Design, Node.js, Express.js, MongoDB, WebSocket, Docker, Nginx, Redis, Python (Web Crawling), Bcrypt, JWT, MVC Pattern, AWS (EC2, S3, CloudFront), GitHub, Git, Google Analytics <br><br>

- ### **(11) Blog Website (*Jan 2023*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_4.png" alt="preview"></p>

  - **Live Demo:** https://blog.jprogrammer.online/

  - **Theme:** It is one of my assignments during my study in the Web Development Bootcamp. It allows users to post messages and upload photos onto the blog easily.

  - **Stacks Used:** HTML, CSS, JavaScript, jQuery, Bootstrap, Responsive Web Design, Node.js, Express.js, MySQL, MVC Pattern, Firebase, Docker <br><br>

- ### **(12) Taipei-Day-Trip Website (*Nov to Dec 2022*)**

  <p style="width: 800px; margin: auto;" align="center"><img src="/screenshots/screenshot_3.png" alt="preview"></p>

  - **Live Demo:** https://taipeidaytrip.jprogrammer.online/

  - **GitHub:** https://github.com/skwongman/taipei-day-trip/

  - **Theme:** It is my first full stack individual side project during my study in the Web Development Bootcamp with minimal guidance. It is an E-commerce online platform which allows customers to search, compare, and make one-day attraction booking in Taipei City of Taiwan.

  - **Stacks Used:** HTML, CSS, Vanilla JavaScript, Responsive Web Design, Python, Flask, MySQL, Bcrypt, JWT, TapPay (Third-party Payment System), MVC Pattern, AWS (EC2 & S3), GitHub, Git, Google Analytics <br><br>

- ### **(13) To-Do-List Website (*Aug 2022*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_2.png" alt="preview"></p>

  - **Live Demo:** https://skwongman.github.io/To-Do-List-Website/

  - **Theme:** It is my first web development project before I got into the Web Development Bootcamp. It is a simple to-do-list website. Users can add to-do items and delete them after they are completed.

  - **Stacks Used:** HTML, CSS, Vanilla JavaScript <br><br>

- ### **(14) Python Telegram Bot (*Sept 2018*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_1.png" alt="preview"></p>

  - **Theme:** It is an instant message telegram bot which allows users to retrieve latest 1) weather, 2) Hong Kong news, and 3) KMB bus waiting time information after sending a simple prompt.

  - **Stacks Used**: Python, Web Crawling (Beautiful Soup), Linux Cron Jobs, HKSAR Gov API <br><br>

## Group Side Project:

- ### **(1) Weather Forecast Website (*Dec 2022*)**

  <p style="width: 800px; margin: auto;"><img src="/screenshots/screenshot_11.png" alt="preview"></p>

  - **Live Demo:** https://skwongman.github.io/team-project/

  - **GitHub:** https://github.com/skwongman/team-project/

  - **Theme:** It is my first team project with another four teammates during my study in the Web Development Bootcamp. I was also the team leader for this team project. It is a Taiwan weather forecast website which allows users to brower the latest weather and UV index information. Alternatively, users can opt to move the mouse onto the Taiwan map liked figure on the right-hand side to check the weather forecast of all cities in one go.

  - **Stacks Used:** HTML, CSS, JavaScript, Vue.js (CDN), jQuery, Responsive Web Design, Taiwan Gov API, GitHub, Git, Pull Request, Fork Repository <br><br>

## Contact:
- **E-mail:** siukwongman@gmail.com