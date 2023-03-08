# rsschool-cv

# Yulia Lugovaya

### Junior Front-end Developer

**********

### Contact Information

* **Location:** Gomel, Belarus
* **Phone:** +375 29 152 18 80
* **Email:** yulialugovaya9.12@gmail.com
* **GitHub:** [YuliaLugovaya](https://github.com/YuliaLugovaya)
* **Linkedin:** [Yulia Lugovaya](https://www.linkedin.com/in/%D1%8E%D0%BB%D0%B8%D1%8F-%D0%BB%D1%83%D0%B3%D0%BE%D0%B2%D0%B0%D1%8F-b8ab19256/)

**********

### Summary

I aspire to be a part of a friendly and professional team, where I can develop my JavaScript development skills and learn new skills to achieve team results.

My strengths: attentive to detail, energetic, creative, highly motivated and come up with solutions to seemingly intractable problems.

**********

### Skills

* HTML5, CSS3/SCSS, BEM, Bootstrap
* JavaScript ES6+ (Basics, DOM, JSON, Asynchronous JavaScript)
* React (Basics)
* Git, GitHub
* Webpack
* Figma, Adobe Photoshop

**********

### Code example

**From Codewars**

**Coding Meetup #16 - Higher-Order Functions Series - Ask for missing details**

*You will be given an array of objects representing data about developers who have signed up to attend the next coding meetup that you are organising. Given the following input array:*
```
let list = [
  { firstName: null, lastName: 'I.', country: 'Argentina', continent: 'Americas', age: 35, language: 'Java' },
  { firstName: 'Lukas', lastName: 'X.', country: 'Croatia', continent: 'Europe', age: 35, language: null },
  { firstName: 'Madison', lastName: 'U.', country: 'United States', continent: 'Americas', age: 32, language: 'Ruby' } 
];
```
*Write a function that*
* *adds the question property to each object in the input array where the developer has not provided the relevant details (marked with a null value in JavaScript, with the default value in COBOL). The value of the question property should be the following string:*
`Hi, could you please provide your <property name>`;
* *and returns only the developers with missing details.*

**My solution:**
```
function askForMissingDetails(list) {
  return list.filter(function(el) {
   for(let key in el) {
      if(el[key] === null) {
        el.question = `Hi, could you please provide your ${key}.`;
        return el;
      }
    }
 }) 
}
```

**********

### Experience

Academic projects:

* teamwork: website for **quiz game in London** - [that1quiz](https://yulialugovaya.github.io/ITGirls_project_that1quiz/). My part: creating *header*, *footer*, pages *gallery* and *faq*; technology stack: HTML, CSS/SCSS, JavaScript (Basics), BEM, Webpack. [Code on GitHab](https://github.com/YuliaLugovaya/ITGirls_project_that1quiz).
* teamwork: **JavaScript guide** - [JS Cheatsheet](https://yulialugovaya.github.io/js-cheatsheet/). My part: creating pages *array* and *web*; technology stack: HTML, CSS/SCSS, JavaScript (including work with API), Materialize, Webpack. [Code on GitHab](https://github.com/YuliaLugovaya/js-cheatsheet).

**********

### Education

* University: Francisk Skorina Gomel State University, Jurisprudence major
* Courses:
  * [FreeCodeCamp](https://www.freecodecamp.org/learn/javascript-algorithms-and-data-structures/): JavaScript Algorithms and Data Structures, Basic JavaScript
  * [Hexlet](https://ru.hexlet.io/courses/js-basics): Basics of JavaScript
  * [ITGirlschool](https://itgirlschool.com/frontend-developer): Front-end Development

**********

### Languages