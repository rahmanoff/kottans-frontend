# kottans-frontend

Kottans - 2022 FrontEnd Course  

---

## GIT Basics

- [x] Done! :tada:

<details>

<summary>Screenshoots:</summary>

- screen 1 - oursera Week 1:

![screen 1 - ](task_git_collaboration/git-collaboration2.jpg)

- screen 2 - Corsera Week 2:

![screen 2 - ](task_git_collaboration/git-collaboration3.jpg)

- screen 3 - Udacity:

![screen 5 - ](task_git_collaboration/git-collaboration6.jpg)

</details>

---

## Linux CLI, and HTTP

- [x] Done! :tada:

I had some knowledge about shell, terminal, bash and commands before. It was a good oportunity to repeat.
Knowing of such commands give you more control of your machine and helps do cli tasks quicker.

<details>

<summary>Screenshoots:</summary>

- screen for Quiz 1:

![screen 1 - ](task_linux_cli/linux-cli-http1.jpg)

- screen for Quiz 2:

![screen 2 - ](task_linux_cli/linux-cli-http2.jpg)

- screen for Quiz 3:

![screen 3 - ](task_linux_cli/linux-cli-http3.jpg)

- screen for Quiz 4:

![screen 4 - ](task_linux_cli/linux-cli-http4.jpg)

</details>

---

## GIT Collaboration

- [x] Done! :tada:

Did some Git Collaboration before, but it was all around 'git init', 'git clone', 'git pull' and 'git push'. Now I feel more comfortable with branches and commits "adventures".

<details>

<summary>Screenshoots:</summary>

- screen 1 - Coursera Week 3:

![screen 1 - ](task_git_collaboration/git-collaboration7.jpg)

- screen 2 - Coursera Week 4:

![screen 2 - ](task_git_collaboration/git-collaboration8.jpg)

- screen 3:

![screen 3 - ](task_git_collaboration/git-collaboration4.jpg)

- screen 4:

![screen 4 - ](task_git_collaboration/git-collaboration5.jpg)

</details>

<details>

<summary>Git Commands:</summary>

- git remote -v - List remote repos verbosely

- git remote show origin - Describes a single remote

- git branch -r - List remote branches

- git log origin/main

- git log -p

- git checkout -b 'name' - Create branch 'name' and checkout to it

- git push -u origin 'name' - Push branch 'name' in origin repo

- git push --delete origin 'name' - Delete origin branch 'name'

- git branch -d 'name' - Delete local branch 'name'

- git rebase -i 'branch' - Squash Changes in one commit (pick/squash/drop)

- git push -f - Force Push to change origin

- git commit -a --amend - Change previous commit

</details>

---

## Intro to HTML and CSS

- [x] Done! :tada:

Most of information was not new for me. But it was good opportunity to remind and did some structure.

<details>

<summary>Screenshoots:</summary>

- screen 1 - Coursera Week 1:

![screen 1 - ](task_html_css_intro/task_html_css_intro1.jpg)

![screen 2 - ](task_html_css_intro/task_html_css_intro2.jpg)

- screen 2 - Coursera Week 2:

![screen 3 - ](task_html_css_intro/task_html_css_intro3.jpg)

![screen 4 - ](task_html_css_intro/task_html_css_intro4.jpg)

- screen 3 - codeacademy HTML:

![screen 5 - ](task_html_css_intro/task_html_css_intro5.jpg)

- screen 4 - codeacademy CSS:

![screen 6 - ](task_html_css_intro/task_html_css_intro6.jpg)

</details>

<details>

<summary>To remember:</summary>

```text
html:

'<' = &lt;
'>' = &gt;
'&' = &amp;
'copyright' = &copy;
'non breakong space' = &nbsp;
```

**css:**

Styling: inline, internal, external

:nth-child(number)
Last Declaration Wins!
Most Specific Selector Combination Wins!
Style | ID | Class, pseudo-class-attribute | Number of Elements
text-transform: capitalize;

12-Column Grid Responsive Layout can be divided by 1,2,3,4,5,12

```html
<meta name='viewport' content='width=device-width, initial-scale=1'>
```

**Selectors**: type, class, id, attributes, pseudo-class.
**Specificity**: id, class, type.
**Best practice** - type, class, id.
**Chaining**: h2.special - for every 'h2' with class 'special'.

'li h4' is more specific than 'h4'!

**Border** - width (px or thin, medium, thick), style (none, doted, solid and 7 more), color (# or 140 buil-in).

**Overflow** - hidden, scroll, visible.

**Visibility** - hidden, visible, collapse.

**Position** - static (default), relative, absolute, fixed, sticky.
Relative - top, bottom, right, left.
Absolute - top, bottom, right, left inside parent.
Fixed - top, bottom, right, left, like sticky header.
Static, Relative, Sticky - in flow of document.
Fixed and Absolut - out of flow of document.

**Display** - inline, block, inline-block.

Float - left, right.

Clear: left, right, both, none.

HSL - Hue, Saturation, Lightness

Hue: red = 0, green = 120, blue = 240


Bootstrap Grid:

![Bootstrap Grid 1 - ](task_html_css_intro/bootstrap1.jpg)

![Bootstrap Grid 1 - ](task_html_css_intro/bootstrap2.jpg)

</details>

---

## Responsive Web Design

- [x] Done! :tada:

- FLexBox Demo - [Link](https://rahmanoff.github.io/flex)
- Grid Demo - [Link](https://rahmanoff.github.io/grid)

<details>

<summary>Screenshoots:</summary>

- screen 1 - FlexBox Froggy:

![screen 1 - ](task_responsive_web_design/task_responsive_web_design1.jpg)

- screen 2 - Grid Garden:

![screen 2 - ](task_responsive_web_design/task_responsive_web_design2.jpg)

</details>

<details>

<summary>To remember:</summary>

Modern CSS - FLexbox, Grid, Multicol.

```text
img {
    max-width: 100%;
    display: block;
}
```

**Media queries based on vieport size**:
- width (min-width, max-width)
- height (min-height, max-height)
- orientation
- aspect-ratio

**Media Queries basrd on device capability**:
- hover
- pointer
- any-hover
- any-pointer

**Breakpoints**.
Classic theory - column should contain 70 to 80 characters per line.

- FLEX -

**Flex-direction**:
row (default),
row-reverse,
column,
column-reverse.

**Justify-content** (horizontal):
flex-start (default),
flex-end,
center,
space-between,
space-around,
space-evenly.

**Align-items** (vertical, determines how the items as a whole are aligned within the container):
flex-start,
flex-end,
center,
baseline,
stretch (default).

For individual item (or class) - **Align-self**:
flex-start,
flex-end,
center,
baseline,
stretch.

**Flex-wrap**:
nowrap (default),
wrap,
wrap-reverse.

**Align-content** (determine the spacing between lines, when there is only one line align-content has NO effect):
flex-start,
flex-end,
center,
space-between,
space-around,
space-evenly,
stretch (default).

- GRID - 

**grid-template-columns**: 30% minmax(150px, 1fr) auto;
'fr can't be min!'
**grid-template-rows**: 30% 50% auto

```css
grid-template-areas: 'header header'
                      aside content'
.grid-header {
    grid-area: header;
}
```

and so on

grid-area: grid-row-start / grid-column-start / grid-row-end / grid-column-end;

grid-template-columns: repeat(8, 12.5%);

mixed:
grid-template-columns: 100px 3em 40%;

grid-template: 1fr 50px / 20% 1fr;

</details>

---

## HTML & CSS Practice

- [ ] ToDo!

**Hooli Style PopUp**

[Demo](https://rahmanoff.github.io/hooli-style-popup)

[Code](https://github.com/rahmanoff/hooli-style-popup)

---

## JS Basics

- [ ] ToDo!

- Basic Algorithm Scripting

- Functional Programming

- Algorithm Scripting Challenges

<details>

<summary>Screenshoots:</summary>

- screen 1 - Coursera - Introduction to JavaScript:

![screen 1 - ](task_js_basics/task_js_basics1.jpg)

![screen 2 - ](task_js_basics/task_js_basics2.jpg)

- screen 2 - freeCodeCamp - Basic JavaScript

![screen 3 - ](task_js_basics/task_js_basics3.jpg)

- screen 3 - freeCodeCamp - ES6:

![screen 4 - ](task_js_basics/task_js_basics4.jpg)

- screen 4 - freeCodeCamp - Basic Data Structures:

![screen 5 - ](task_js_basics/task_js_basics5.jpg)

</details>

<details>

<summary>To remember:</summary>

**JS Data Types** (6 primitives and 1 Object)

**Object** = collection of name + value pairs.

**Primitive** = single, immutble value.

**Boolean**: true or false.

**Undefined**: no value has never been set. var x, console.log(x) = undefined.

**Null**: no value.

**Number**: double-precision 64-bit floating point.

**String**: sequnce of characters.

**Symbol**: from ES6.

**false** || null || undefined || "" || 0 || NaN

**true** && "hello" && 1 && -1 && "false"

Boolean(null) = false

```JS
let comapany = new Object();
company.name = "Facebook";
let stockPropName = "stock of company";
company[stockPropkName] = 110;
```

```JS
let facebook = {
    name: 'Facebook',
    ceo: {
        firstName: 'Mark',
        favColor: 'blue'
    },
    'stock of company': 110
}
```

function = Object

In JS:
PRIMITIVES are passed by VALUE,
OBJECTS are passed by REFERENCE.

```JS
// Function constructors
function Circle(radius) {
    this.radius = radius;
};
Circle.prototype.getArea = function () {
    return Math.PI * Math.pow(this.radius, 2);
}

let myCircle = new Circle(10);
```

```JS
// Object literals and 'this'
let literalCircle = {
    radius: 10,

    getArrea: function () {
        let self = this;
        console.log(this);

        let increaseRadius = function () {
            self.radius = 20;
        };
        increaseRadius();
        console.log(this.radius);

        return Math.PI * Math.pow(this.radius, 2);
    };
};
```

```JS
// Immediately Invoked Function Expression - IIFE
(function () {
    console.log('Hello JS-World!');
})();
```

```JS
// Arrays
let array = new Array();
let array = [];

Add items begin & end:
array.unshift(); // to the beginning;
array.push(); // to the end;


Remove items begin & end:
array.shift(); // from the beginning
array.pop(); // from th end;

Remove somewhere in array:
array.splice(numStartIndex, numItemsToDelete);

Remove and Add somewhere in array:
array.splice(numStartIndex, numItems ToDelete, itemToAdd1, itemToAdd2, itemToAdd3,..., itemToAddN);

Copy Array Items to Ner Array Using slice():
array.slice(firstIndex, stopIndex); // Original array stays untoched

Copy Array with Spread operator:
let thisArray = [true, true, undefined, false, null];
let thatArray = [...thisArray]; // Copy all from thisArray

Array Iteration methods:
every();
forEach();
map();
```

```JS
Add Key-Value Pairs to JS Object:
const tekkenCharacter = {
    player: 'Hwoarang',
    fightingStyle: 'Tae Kwon Doe',
    human: true
};

tekkenCharacter.origin = 'South Korea';
or
tekkenCharacter['hair color'] = 'dyed orange';
```

```JS
Delete property from Object:
delete foods.apples
```

```JS
Check if Object has a Property:
users.hasOwnProperty('Alan');
'Alan' in users;
```

```JS
for in statement:
for (let user in users) {
    console.log(user);
}
```

```JS
Generate an Array of All Object Keys with Object.keys():
return Object.keys(obj);
```


</details>

---

## DOM––

- [ ] ToDo!

---

## Building a Tiny JS World (pre-OOP)

- [ ] ToDo!

---

## Object oriented JS

- [ ] ToDo!

---

## OOP exercise - practice

- [ ] ToDo!

---

## Offline Web Applications

- [ ] ToDo!

---

## Memory pair game — real project

- [ ] ToDo!

---

## Website Performance Optimization

- [ ] ToDo!

---

## Friends App - real project

- [ ] ToDo!

---