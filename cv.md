# Evgeny Zalogin
### Junior (trainee) Frontend Developer
---
## Сontacts
Phone: +7-922-267-97-00 <br>
E-mail: [evg.zalogin@gmail.com](mailto:evg.zalogin@gmail.com "Написать письмо") <br>
Telegram: [@evg-zlg](https://t.me/evg_zlg "Написать в телеграм")
---
## Brief information about me
My goal is to learn how to use Frontend development tools to create useful things. <br>
At the same time, it is important that no one gets hurt :)

My entire work experience (more than 10 years) is related to sales and project management in the field of engineering systems (IT infrastructure, security systems, climate, electrical). <br>
I have an incomplete higher education related to development and business reengineering, in which I studied Delphi, MSSQL, algorithms, mathematics, economics, business process modeling. <br>

Some time ago, I was drawn back to development. <br>
I tried various directions, settled on Frontend, because you can immediately see the result, the toolkit is easily configured, and the endless potential for developing any applications.

### Hard-skills: 
* HTML5, use of template engine (pug) in component architecture with ui-kit, BEM;
* CSS3, SAAS/SCSS - flex, media queries, selectors, adaptive, responsive;
* development according to the layout of figma; 
* js - interactive on the page, interaction with DOM, algorithmic tasks at level 6-5 kyu codewars;
* familiarity with the React library;
* experience using webpack, parcel;
* experience with git (commit, push, GitHUB repository);
* general principles of operation of NodeJS, npm, node_modules, package.json;
* experience in using task managers: planfix, bitrix24, trello;
* a lot of experience in formulating tasks, clarifying requirements, developing documents, writing letters, drafting proposals.

### Soft-skills:
* the ability to hear the interlocutor and understand what he needs (in most cases);
* negotiation and communication skills, developed empathy;
* as a consequence of the above - understanding of bussiness value;
* trainability;
* teamwork at different levels: performer, administrator, leader, cleaning lady - the main thing is to get things done;
* sense of humor.
---
## Code example 
### Convert string to camel case (kata from codewars).
Complete the method/function so that it converts dash/underscore delimited words into camel casing. The first word within the output should be capitalized only if the original word was capitalized (known as Upper Camel Case, also often referred to as Pascal case).

#### Examples
`"the-stealth-warrior"` gets converted to `"theStealthWarrior"` <br>
`"The_Stealth_Warrior"` gets converted to `"TheStealthWarrior"`

#### Solution

```
function toCamelCase(str){
  let strArr = [];
  if (str) {
    if (str.includes("-")) {
      strArr = str.split("-");
    } else if (str.includes("_")) {
      strArr = str.split("_");
      } else return str;
    result = strArr[0];
    for (let i = 1; i < strArr.length; i++) {
      result += (strArr[i][0].toUpperCase() + strArr[i].slice(1));
    };
    return result;
  } else return "";
}
```
## Courses and pet-projects 
1. Tutorial layout "Travel" from the course "JavaScript/Front-end. Stage 0"

![image](https://user-images.githubusercontent.com/85534817/188379086-9c64b1f2-8e1a-430c-a67c-ff75183fd0ec.png) <br>
[Link to github pages](https://evg-zlg.github.io/rsschool-travel/)

2. I needed a timer for circuit training, I made it and still use it. Used React to see what it is.

![image](https://user-images.githubusercontent.com/85534817/188381131-81965f67-a60c-4ea6-a166-76aedd4d0019.png)<br>
[Link to github pages](https://evg-zlg.github.io/timer/)

3. Decided to see what NextJS is. My wife is engaged in weaving products from paper vines. I do something like that.
![image](https://user-images.githubusercontent.com/85534817/189103221-603f09e8-4b55-4cfa-b355-a6bd0458e68f.png)
![image](https://user-images.githubusercontent.com/85534817/189103284-683bc8de-a1e4-440f-b00f-728af75d131a.png)
<br>
[Link to vercel.app](https://ecodecor.vercel.app/)

## Languages:
* Russian - Nativ
* English - Elementary
