---
layout: post
author: Redouane Chabane
---

Hi and welcome to this presentation of my small game engine called "Crescent".

# The planning

Before starting any programming project, it is a good habbit to plan what is the goal of the project, what will our software look like and which technologies should we use? etc.
The more planning we can do in early stages, the better and easier the development will be.

## Graphics API and programming language

There are 3 majors graphics APIs : Direct3D, Vulkan, OpenGL.
Direct3D and Vulkan are really powerful, and give you a large control of GPU programming. However, it should be mentioned that they are significantly harder to use compared to OpenGL, and it’s extra complexity often means longer development times.

We are not planning to develop a highly performant, multithreaded software. In fact, this is never the goal of a small project made by one person. (Unless you're willing to spend years building such software, in that case you must consider the risks and benefits. 99% of the time, it is not worth it.)

At this point, OpenGL stands out as the most simple API to learn and use.
Now, because OpenGL is, exactly that, an API, it requires a programming language to work and should be compatible with a vast majority of languages (ports/wrappers). 
Since the OpenGL API is available through a C interface, C++ is actually a strong candidate to use and build our project. Not only that, but also because of the third party libraries that we will be using to make our life easier when programming with OpenGL.

## Third party libraries

We will be using the following:

| Library/Framework  | Description                                                                            |
| :----:| :-------------------------------------------------------------------------------------:|
| GLM                | a math library, built exactly for OpenGL |
| GLFW               | an api for window, surfaces creation |
| GLEW               | a library to load and access opengl extensions based on the selected version |

#### Sample heading 4
##### Sample heading 5
###### Sample heading 6

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod.

## Lists

Unordered:

- Fusce non velit cursus ligula mattis convallis vel at metus[^2].
- Sed pharetra tellus massa, non elementum eros vulputate non.
- Suspendisse potenti.

Ordered:

1. Quisque arcu felis, laoreet vel accumsan sit amet, fermentum at nunc.
2. Sed massa quam, auctor in eros quis, porttitor tincidunt orci.
3. Nulla convallis id sapien ornare viverra.
4. Nam a est eget ligula pellentesque posuere.

## Blockquote

The following is a blockquote:

> Suspendisse tempus dolor nec risus sodales posuere. Proin dui dui, mollis a consectetur molestie, lobortis vitae tellus.

## Thematic breaks (<hr>)

Mauris viverra dictum ultricies[^3]. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **You can put some text inside the horizontal rule like so.**

---
{: data-content="hr with text"}

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. **Or you can just have an clean horizontal rule.**

---

Mauris viverra dictum ultricies. Vestibulum quis ipsum euismod, facilisis metus sed, varius ipsum. Donec scelerisque lacus libero, eu dignissim sem venenatis at. Etiam id nisl ut lorem gravida euismod. Or you can just have an clean horizontal rule.

## Code

Now some code:

```
const ultimateTruth = 'follow middlepath';
console.log(ultimateTruth);
```

And here is some `inline code`!

## Tables

Now a table:

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned | $1600 |
| col 2 is      | centered      |   $12 |
| zebra stripes | are neat      |    $1 |

## Images

![theme logo](http://www.abhinavsaxena.com/images/abhinav.jpeg)

This is an image[^4]

---
{: data-content="footnotes"}

[^1]: this is a footnote. You should reach here if you click on the corresponding superscript number.
[^2]: hey there, don't forget to read all the footnotes!
[^3]: this is another footnote.
[^4]: this is a very very long footnote to test if a very very long footnote brings some problems or not; hope that there are no problems but you know sometimes problems arise from nowhere.
