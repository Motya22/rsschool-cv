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
Graduated from programming courses. On my graduation project, I Developed a weather forecast application. In the project I used React, Redux (thunk), i18next, mapbox-gl libraries. Tools such as Proxy-Object, Promise.all Settled, localStorage (when the page is reloaded, the selected temperature unit and language are saved). During the initial upload, the location is determined using the Geolocation API. The weather is displayed for today (updated once an hour) and for the next 3 days. I also deployed the application on a clean Ubuntu server with subsequent manual configuration, domain connection and SSL certificate using the Cloudflare service.
Now I am strengthening and developing programming skills.

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
JSX (Icon component with Proxy-object)
```jsx
import PropTypes from 'prop-types';
import { ReactComponent as RefreshBgIcon } from '../../assets/icons/refresh.svg';
import { ReactComponent as ThunderstormRainIcon } from '../../assets/icons/weather/tstorm.svg';
import { ReactComponent as ThunderstormDrizzleIcon } from '../../assets/icons/weather/tstormdrizzle.svg';
import { ReactComponent as FlurriesDayIcon } from '../../assets/icons/weather/flurriesd.svg';
import { ReactComponent as FlurriesNightIcon } from '../../assets/icons/weather/flurriesn.svg';
import { ReactComponent as RainIcon } from '../../assets/icons/weather/rain.svg';
import { ReactComponent as DefaultWeatherIcon } from '../../assets/icons/weather/default.svg';

let TypeToIconMap = {
  refreshBg: <RefreshBgIcon />,
  thunderstormRain: <ThunderstormRainIcon />,
  thunderstormDrizzle: <ThunderstormDrizzleIcon />,
  flurriesDay: <FlurriesDayIcon />,
  flurriesNight: <FlurriesNightIcon />,
  rain: <RainIcon />,
};

TypeToIconMap = new Proxy(TypeToIconMap, {
  get: (target, type) => {
    if (type in target) {
      return target[type];
    }

    return <DefaultWeatherIcon />;
  },
});

const Icon = ({ type }) => TypeToIconMap[type];

Icon.propTypes = { type: PropTypes.string };

Icon.defaultProps = { type: '' };

export default Icon;
```
## 👨‍💻 Experience

| :--------------------- | :-------------------------------------------------------------------------------------------- |
| 2021 — 2021 (9 months) | **Front-end Developer** <br> **TeachMeSkills** <br> - Development using Javascript <br> - Development of web applications on React <br> **Projects within the framework of teaching at TeachMeSkills:** <br> 1. Developed a weather forecast application. In the project I used React, Redux (thunk), i18next, mapbox-gl libraries. ([code](https://github.com/Motya22/react-weather-app)) <br> 2. To-do list application. In the project I used React, Redux, JSONPlaceholder API. ([code](https://github.com/Motya22/react-todolist-app)) <br> 3. Adaptive layout of Landing Pages using CSS, jQuery, animation (keyframes and transition). ([code](https://github.com/Motya22/ext-bel))                    |
| 2019 — Present         | **Tender manager** <br> **RPC "HIMMEDSINTEZ"** <br> - Monitoring of ETP <br> - Preparation of a package of documents <br> - Placement of offers on ETP                                                                 |
| 2018 — 2018 (6 months) | **Purchasing Specialist** <br> **Domashny store chain** <br> - Interaction with suppliers and retail facilities <br> - Drawing up a protocol for drawing up prices, product cards <br> - Working with 1C               |

## 🎓 Education

### Online learning

| :--- | :---                                                                                            |
| 2013 | **Bitrix Framework Developer**<br>Ltd "1C-Bitrix"                                               |
| 2013 | **Basic CSS** <br> NOU "INTUIT"                                                                 |
| 2010 | **Java Fundamental**<br>Java Fundamental сourses powered by Sun Microsystems <br>DonNTU UNITECH |

### Higher education

| :---------- | :---------------------------------------------------------------------------------------------------- |
| 2014 — 2018 | **University:** MITSO International University <br> **Faculty:** International Economic Relations and Management (IER and M) <br> **Speciality:** Logistician-economist                                                     |

## 📚 English

* Elemetary (A1)
