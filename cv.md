# Mariia Moniakova
![my photo](avatar.jpeg)

## My contacts:
* **Phone:** +79502263735
* **Email:** improverall-mm@gmail.com
* **GitHub:** [@kotovi4](https://github.com/kotovi4)
* **Discord:** Mariia M.(@kotovi4)

## About me:
I have been interested in the topic of creating websites and applications for a long time. As part of my work, I had to deal with the administration of the company's websites and I decided to delve deeper into the study of front-end development. I have completed the Frontend Developer course from HTML-Academy, completed several training projects and am currently working on a commercial project. My dream is to get into EPAM.

## My skills:
- HTML (BEM methodology, cross-browser and responsive layout)
- CSS (Less/SASS, PostCSS, Preprocessor)
- JavaScript
- Vue.js
- Git
- Gulp
- Webpack
- Figma
- studying unit tests for Jest и Vue Test Utils

## Code Example:
```
let id = offerResponse.data.PRODUCTS
.map((group) => group.items
  .filter((item) => 'id' in item)
  .map((item) => item.id))
.flat();

id = [...new Set(id)];

if (id.length > 0) {
const productResponse = await api.get('product.php', { params: { id } });
const products = productResponse.data.reduce(
  /**
    * @param {Object} acc
    * @param {{
    *   ID: string,
    *   NAME: string,
    *   TEXT: string,
    *   URL: string,
    *   PICTURE: string,
    * }} item
    */
  (acc, item) => {
    acc[item.ID] = {
      name: item.NAME,
      text: item.TEXT,
      url: item.URL,
      picture: item.PICTURE,
    };
    return acc;
  }, {}
);
```

## My progects
* [Bicycles](https://github.com/kotovi4/bicycles) - online bike shop
* [Way](https://github.com/kotovi4/monyakova_way) - travel agency
* [Pink](https://github.com/kotovi4/1314303-pink-22) - photo application site
* [Keksobooking](https://github.com/kotovi4/1314303-keksobooking-23) - accommodation booking
## Education
* HTML-Academy
    - HTML & CSS. Professional Website Codings and
    - HTML & CSS. Adaptive Website Codings and Automation
    - JavaScript. Professional Development of Web Interface
    - Profession "Front-end Developer"
* Udemy
    - JavaScript + React from Ivan Petrichenko

## Language
**English:** A1