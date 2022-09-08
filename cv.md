<img src="./img/Photo.JPG" width="150px" style="border-radius: 50%">

# Denis Zhurov         

###  **Contacts**
* TG: @den4yck
* email: i.deniszh@gmail.com
* discord: Den4yck#5264

### About
    I am interesting in web development, modern technologies. At the moment my focus is on becoming front-end developer with evolving to full-stack and beyond.

### Skills
* HTML/CSS
* JS/TS
* PHP
* React
* NodeJS
* Git
* Express
* PostgreSQL
* MVC pattern

***

Code example from [codewars](https://www.codewars.com/kata/reviews/525b196eeb636fa0b600003f/groups/624491dbbe5665000100ce3c):
```js
// partition the items array so that all values for which pred returns true are
// at the end, returning the index of the first true value
function partitionOn(pred, items) {
  const arrTrue = [];
  const arrFalse = [];
  for(let i = 0; i < items.length; i++) {
    pred(items[i]) ? arrTrue.push(items[i]) : arrFalse.push(items[i]);
  }
  items.splice(0, items.length, ...arrFalse.concat(arrTrue));
  return arrFalse.length;
}
```
***

### My finished projects
 * [Video game selling web site on react](https://github.com/boffobos/react_lab)
 * [Simple weather application](https://joyd-weather-application.herokuapp.com/)
 

### Education
* **Belatusian State University Informatics and Radioelectronics**: Faculty of Radioengineering and electronics
* **Skillfactory online school**: web-development
* **iTechArt**: React/React native intern
* **Udemy**: OOP PHP & MVC, HTML/CSS, NodeJS

### Languages:
    * English - B1
    * Russian - Native
