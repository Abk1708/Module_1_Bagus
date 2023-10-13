# Howdy. My name is Alfath Bagus Kurnia :wave: :robot:

----

> ## Table of Contents
>
> - [My Bio](#bio)
>
> - [My Links](#links)
>
> - [My technical Skills](#skills)
>
> - [My Favorite Coding Related Sites](#sites)
>
> - [Code Examples I Have Written](#snippets)
>
> - [Week 00 Assignment Qualification](#assignment)
>

---

<a id="bio"></a>

## My Bio 👨‍💻

![It's a me](placeholder-profile-image.jpg "It's a me")

I'm a diploma fresh graduate from Jakarta State University in Electronic Engineering and currently working as a HRD clerk.

My hobby is reading novel and playing games. My favorite programming language is Javascript, HTML, and C++(although i'm still not that good with C++).

----

<a id="links"></a>

## My Links :postbox:

<p align="center">
  <a target="_blank"href="https://github.com/Abk1708"><img src="https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white" /></a>&nbsp;&nbsp;
  <a target="_blank"href="https://www.linkedin.com/in/alfath-bagus-kurnia-bab7ab1a5"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;
</p>

----

<a id="skills"></a>

## My Technical Skill :mechanic:

<p align="center">
  <img src="https://img.shields.io/badge/Visual%20Studio%20Code-0078d7.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />&nbsp;
  <img src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />&nbsp;
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" />&nbsp;
</p>


----

<a id="sites"></a>

## My Favorite Browser Coding Related Sites :globe_with_meridians: 

| Name | URL | Description |
| ---  | :---: | ----------- |
| Firefox | [![Firefox](https://img.shields.io/badge/Firefox-FF7139?style=for-the-badge&logo=Firefox-Browser&logoColor=white)](https://www.mozilla.org/id/firefox/new/) | Very recommended browser for all device including Windows for it's sparse usage of memory and cpu and overall lightweight size |
| Reddit | [![Reddit](https://img.shields.io/badge/Reddit-%23FF4500.svg?style=for-the-badge&logo=Reddit&logoColor=white)](https://www.reddit.com/r/programming) | An all around forum site where people discuss and share questions and topics about anything including programming related. |
| edX | [![edX](https://img.shields.io/badge/edX-%2302262B.svg?style=for-the-badge&logo=edX&logoColor=white)](https://home.edx.org) | A dev course site that founded by Harvard and MIT and house one of the well known courses like CS50 with it's host David J. Malan. |
| Stack Overflow |[![Stack Overflow Badge](https://img.shields.io/badge/Stack%20Overflow-F58025?logo=stackoverflow&logoColor=fff&style=flat)](https://stackoverflow.com) | Programming related forum site that looks and works exactly like Reddit. If you happened to stumble upon a problem or roadblock, then you can find most of the solution here. |
| GitHub | [![GitHub](https://img.shields.io/badge/github-%23121011.svg?style=for-the-badge&logo=github&logoColor=white)](https://github.com) | The most popular site to publish and collaborate on Git repositories. Just like Git, it offers distributed version control, source control management and additional features that can only be found in this site. |
| ChatGPT | [![ChatGPT](https://img.shields.io/badge/chatGPT-74aa9c?style=for-the-badge&logo=openai&logoColor=white)](https://chat.openai.com/) | A large language-model-based  AI chatbot developed by OpenAI. Which makes it best utilized for coding by asking the exact step for creating a certain script |

----

<a id="snippets"></a>

## Code Examples I Have Written 👾

### HTML Calculator

```html
<!DOCTYPE html>
<html>
    <head>
        <title>Calculator</title>
        <style>
            button {
                width: 100%
            }
        </style>
    </head>
    <body>
        <table>
            <tr>
                <th colspan="4"><input type="text" name="display"></th>
            </tr>
            <tr>
                <td colspan="2">
                    <button>AC</button>
                </td>
                <td>
                    <button>C</button>
                </td>
                <td>
                    <button>*</button>
                </td>
            </tr>
            <tr>
                <td>
                    <button>7</button>
                </td>
                <td>
                    <button>8</button>
                </td>
                <td>
                    <button>9</button>
                </td>
                <td>
                    <button>/</button>
                </td>
            </tr>
            <tr>
                <td>
                    <button>4</button>
                </td>
                <td>
                    <button>5</button>
                </td>
                <td>
                    <button>6</button>
                </td>
                <td>
                    <button>+</button>
                </td>
            </tr>
            <tr>
                <td>
                    <button>1</button>
                </td>
                <td>
                    <button>2</button>
                </td>
                <td>
                    <button>3</button>
                </td>
                <td>
                    <button>-</button>
                </td>
            </tr>
            <tr>
                <td>
                    <button>+-</button>
                </td>
                <td>
                    <button>0</button>
                </td>
                <td>
                    <button>.</button>
                </td>
                <td>
                    <button>=</button>
                </td>
            </tr>
        </table>
    </body>
</html>
```

### Read .txt Files On Javascript

```js
const fs = require('fs');

const catCallback = (err, cat) => {
    if(err) {
        console.log('Invalid data type');
        return;
    }
    console.log(cat);
};

fs.readFile('notes.txt', 'utf8', catCallback);
```

### Server Initialization In Javascript Using Hapi

```js
const Hapi = require('@hapi/hapi');
const routes = require('./routes');

const init = async () => {
  const server = Hapi.server({
    port: 5000,
    host: 'localhost',
  });

  server.route(routes);

  await server.start();
  console.log(`Server running on ${server.info.uri}`);
};

init();

```

----

<a id="assignment"></a>

## Week 00 Assignment Qualifications 📋

- [X] Create the fundamental Markdown structure for your responsive website.
- [x] Emphasize the utilization of proper Markdown semantics for each element.
- [x] Develop the core content of your website, including headers, paragraphs, and images.
- [x] Initialize a GitHub repository for your project and push your initial Markdown code into it.

----
