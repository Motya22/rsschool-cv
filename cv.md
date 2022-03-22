![Matvei Ryzhkov](assets/img/avatarforcv.jpeg)
# Matvei Ryzhkov

## 📞 Contacts

| :------- | :----------------------------------------------------------- |
| email    | [motya2222@gmail.com](motya2222@gmail.com)                   |
| discord  | Matvei (@matvei)                                             |
| github   | [Motya22](https://github.com/Motya22)                        |
| telegram | [@motya22](https://t.me/motya22)                             |
| linkedin | [Matvei Ryzhkov](https://www.linkedin.com/in/matveiryzhkov/) |

## 📝 Summary
Graduated from programming courses "TeachMeSkills". On my graduation project, I developed a weather forecast application. In the project I used React, Redux (thunk), i18next, mapbox-gl libraries. Tools such as Proxy-Object, Promise.all Settled, localStorage (when the page is reloaded, the selected temperature unit and language are saved). During the initial upload, the location is determined using the Geolocation API. The weather is displayed for today (updated once an hour) and for the next 3 days. I also deployed the application on a clean Ubuntu server with subsequent manual configuration, domain connection and SSL certificate using the Cloudflare service.

After completing the courses, I realized that I felt insecure about creating Vanilla Javascript applications and decided to take free, but high-quality courses from The Rolling Scopes School. I have now completed stage #0 of JS/FE Pre-School and am determined to strengthen and develop my programming skills at stage#1 of JavaScript/Front-end.

Objective — starting my career as a Junior Front-End developer.

## ✔ Skills
* HTML 5, CSS3 
* SASS / SCSS
* JavaScript
* React, Redux (thunk), React-Router
* Node.js
* Webpack
* GIT

## 💾 Example of My Code
JS (Function check(str, bracketsConfig), that for given brackets sequence will return true if it is correct and false otherwise)
```js
const check = (str, bracketsConfig) => {
  const brackets = str.split('');
  const arrayLikeStack = [];
	
  for (const bracket of brackets) {
    const lastOfStack = arrayLikeStack[arrayLikeStack.length - 1];
    const neededPair = bracketsConfig.find((bracketsPair) => bracketsPair[0] === lastOfStack);
        
    if (arrayLikeStack.length && neededPair && bracket === neededPair[1]) {
      arrayLikeStack.pop();
    } else  {
      arrayLikeStack.push(bracket);
    }
  }
  
  return arrayLikeStack.length === 0;
}
```
## 👨‍💻 Experience

| :--------------------- | :-------------------------------------------------------------------------------------------- |
| 2021 — 2022 (3 months) | **Front-end Developer (stage#0)** <br> **The Rolling Scopes School** <br> - Development using HTML5 and CSS3 <br> - Development using Vanilla Javascript <br> **Projects within the framework of teaching at The Rolling Scopes School (stage#0):** <br> 1. Adaptive Portfolio layout with added functionality. Valid, semantic layout. Interactivity implemented through css. Adaptability is implemented using media queries, css variables, burger menu. From the functionality, the change of images in the portfolio section, the translation of the page into two languages, the ability to switch light and dark themes has been added. ([code](https://rolling-scopes-school.github.io/motya22-JSFEPRESCHOOL/portfolio/)) <br> 2. Developed a custom video player. To create a player whose design meets the requirements, I used JavaScript (an HTMLMediaElement object). ([code](https://rolling-scopes-school.github.io/motya22-JSFEPRESCHOOL/portfolio/#video)) <br> 3. Developed a video search engine. To process asynchronous code, I used Promise & Async/await. I used TMDB as an API. ([code](https://rolling-scopes-school.github.io/motya22-JSFEPRESCHOOL/movie-app/)) <br> 4. Developed the game Whack a Mole. The goal of the game is to score as many points as possible in time. The last ten results are displayed in the table and saved when you restart. ([code](https://rolling-scopes-school.github.io/motya22-JSFEPRESCHOOL/whackamole-game/))                  |
| 2021 — 2021 (9 months) | **Front-end Developer** <br> **TeachMeSkills** <br> - Development using Javascript <br> - Development of web applications on React <br> **Projects within the framework of teaching at TeachMeSkills:** <br> 1. Developed a weather forecast application. In the project I used React, Redux (thunk), i18next, mapbox-gl libraries. ([code](https://github.com/Motya22/react-weather-app)) <br> 2. To-do list application. In the project I used React, Redux, JSONPlaceholder API. ([code](https://github.com/Motya22/react-todolist-app)) <br> 3. Adaptive layout of Landing Pages using CSS, jQuery, animation (keyframes and transition). ([code](https://github.com/Motya22/ext-bel))                    |
| 2019 — Present         | **Tender manager** <br> **RPC "HIMMEDSINTEZ"** <br> - Monitoring of ETP <br> - Preparation of a package of documents <br> - Placement of offers on ETP                                                                 |
| 2018 — 2018 (6 months) | **Purchasing Specialist** <br> **Domashny store chain** <br> - Interaction with suppliers and retail facilities <br> - Drawing up a protocol for drawing up prices, product cards <br> - Working with 1C               |

## 🎓 Education

### Online learning

| :--- | :---------------------------------------------------------- |
| 2021 | **Javascript Marathon** <br> Vladilen Minin                 |
| 2021 | **learn.javascript.ru** <br> Ilya Kantor                    |
| 2021 | **CS50** <br> Harvard, Fundamentals of Programming          |
| 2021 | **HTML for beginners** <br> Code Basics                     |

### Higher education

| :--- | :--- |
| 2014 — 2018 | **University:** MITSO International University <br> **Faculty:** International Economic Relations and Management (IER and M) <br> **Speciality:** Logistician-economist |

## 📚 English

* Pre-intermediate (A2)
