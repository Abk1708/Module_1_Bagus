# Howdy. My name is Alfath Bagus Kurnia :wave: :robot:

----

> ## Content
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
<a id="bio"></a>

## My Bio

----

![It's a me](placeholder-profile-image.jpg "It's a me")

I'm a diploma fresh graduate from Jakarta State University in Electronic Engineering and currently working as a HRD clerk.

My hobby is reading novel and playing games. My favorite programming language is Javascript, HTML, and C++(although i'm still not that good with C++).

<a id="links"></a>

## My Links

----

* Github : [@Abk1708](https://github.com/Abk1708).
* LinkedIn :[alfathbaguskurnia](https://www.linkedin.com/in/alfath-bagus-kurnia-bab7ab1a5/)

<a id="skills"></a>

## My Technical Skill

 ----

1. VS Code
2. Javascript
3. NodeJs
4. Postman
5. Markdown

<a id="sites"></a>

## My Favorite Coding Related Sites

----

| Name | URL | Description |
| ---  | :---: | ----------- |
| W3School | [https://w3schools.com](https://www.w3schools.com/) | A web dev site that offer a lot of module for a wide variety of programming language. |
| edX | <https://home.edx.org> | A dev course site that founded by Harvard and MIT and house one of the well known courses like CS50 with it's host David J. Malan. |
| Stack Overflow | <https://stackoverflow.com/> | Programming related forum site that looks and works exactly like Reddit. If you happened to stumble upon a problem or roadblock, then you can find most of the solution here. |
| GitHub | <https://github.com/> | The most popular site to publish and collaborate on Git repositories. Just like Git, it offers distributed version control and source control management and additional features that can only be found in this site. |

<a id="snippets"></a>

## Code Examples I Have Written

----

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

<a id="assignment"></a>

## Week 00 Assignment Qualifications

- [X] Create the fundamental Markdown structure for your responsive website.
- [x] Emphasize the utilization of proper Markdown semantics for each element.
- [x] Develop the core content of your website, including headers, paragraphs, and images.
- [ ] Initialize a GitHub repository for your project and push your initial Markdown code into it.
