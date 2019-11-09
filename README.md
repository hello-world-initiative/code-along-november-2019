# Travel Salmon - An HTML and CSS Project

These are the project files for our project - Travel Salmon, a fake company I made up, whose website we'll be building.

## Getting started

If you have `git` installed, you can clone this project using one of the URLs above:

```
git clone https://github.com/hello-world-initiative/code-along-november-2019.git

- or -

git clone git@github.com:hello-world-initiative/code-along-november-2019.git    # if you have SSH keys
```

If you don't have `git` installed, if you're using Windows and don't have `git-bash`, or you're not comfortable with `git` yet, you can download the files by clicking **Clone or Download** above, then choosing **Download ZIP**. Make sure you unzip the archive you download - your computer will probably have software that will let you do this.

## What's in the project

Included in the project files are a few things:

- **index.html** - This is the HTML structure of our site. I've already filled out everything we need for the code-along, but I encourage you to look through it and see if you can figure out why I made the choices I did. A big part of learning to code is not just writing code, but understanding what other people have written. If you like, you can change things around and make your own version of the site.
- **css/** - This is where our CSS will live. I included a starter file, `styles-starter.css`, that we'll use to build up our site's design during the code-along. I also have a "finished" version in `styles-final.css`. We'll be using [Font Awesome 4.7](https://fontawesome.com/v4.7.0/) for some icons, and I've included their CSS file as well so we don't have to rely on a CDN to make sure our icons load.
- **fonts/** - The fonts I included are dependencies for Font Awesome. The icons we're using are actually web fonts, so the Font Awesome CSS refers to the files in this folder so that it can display properly. We won't be touching this folder, but this is where you would add your own custom web fonts if you wanted to host them yourself. For our custom fonts, we'll stick to the Google Fonts CDN.
- **images/** - These are the images we'll be using, plus a few extras I included so you can experiment with different designs. There are some black and white, as well as full color (you'll see why as we work through the CSS). Feel free to experiment and swap out the images to see how they affect the overall look of the site. All images are from [Unsplash](https://unsplash.com/), with the exception of the Travel Salmon logo, which I designed myself a couple years ago. Unsplash is a great resource for free, high quality images that you can use in your own projects, so if you're not familiar with them, I encourage you to see what kinds of resources they offer.

### LICENSE

The license file deserves a section of its own - this is something a lot of courses don't cover, but it's extremely important in open source software. The type of license in your project determines how other people can use it. Open source is about permitting others to use your code in their own projects, and the license tells them exactly what they can and can't do with it. For example, some licenses require that the person using your code credits you as the original creator. Other licenses say whether you can or can't modify the original source code.

I've chosen the MIT License, which is one of the more permissive and open options. Basically what it means is that anyone can take this code and use it for themselves, as long as they retain a copy of _my_ license (which credits the Hello World Initiative) and include it in copies of any software they distribute which uses my code.

Licenses are a big topic and aren't always easy to understand, but it's important to be familiar with them. For further reading, check out [this guide from the Open Source Initiative](https://opensource.org/licenses).

## Getting started

As I mentioned above, there are two CSS files we'll be using: `styles-starter.css` and `styles-final.css` in the CSS folder.

To illustrate how the site will look when it's done, I'm linking the final version in the HTML. To see the "finished" site, you can find the `index.html` file in your file broser (explorer on Windows, finder on Mac) and open it in your web browser.

Once you have a look around, go back to your text editor, open up the HTML file, and change this line:

```
<link rel="stylesheet" href="css/styles-final.css" />
```

Change the name of the CSS file from `styles-final.css` to `styles-starter.css`. If you refresh the page in your browser, you'll notice that most of the styles are gone, aside from some basic defaults that I've included to get us started.

## A note on class names

If you look through the HTML, you'll probably notice that my class names look a bit weird. For example:

```
<ul class="nav__list">
  <li class="nav__list-item"><a class="nav__link" href="#">About</a></li>
  <li class="nav__list-item"><a class="nav__link" href="#">Photos</a></li>
  <li class="nav__list-item"><a class="nav__link" href="#">Careers</a></li>
  <li class="nav__list-item"><a class="nav__link" href="#">Log in</a></li>
</ul>
```

Why all the underscores and long names?

There is actually a good reason for this, and it's called [BEM - Block Element Modifier](http://getbem.com/). BEM is a methodology for writing CSS that helps you keep your code organized and reusable. Does it make the HTML a little ugly? Yes, in most cases it does. But in larger projects, it is key to have a naming convention that allows you to minimize the amount of CSS you write so that your website will load faster.

My use of BEM in this project is fairly loose. I'm not following every single one of their methods in naming my classes, but I wanted to introduce this concept for everyone to explore on their own and consider for their own projects.

BEM is one of many different CSS methodologies, so if you don't find it useful, you don't have to use it. Another popular convention is [SMACSS - Scalable and Modular Architecture for CSS](http://smacss.com/). Like most things in tech, it's not important which one you use. What's important is knowing that these things exist, what they're used for, and why they can be helpful in larger projects.

## Questions?

Feel free to ask! I'll be available on our [Discord](https://discord.gg/CEGxS5k) to help with any problems you run into after we're done today, or you can ask in person if you're attending the meetup. Remember that code can always be improved or made more efficient - this project tries to follow best practices, but there are hundreds of other ways to acheive these same goals. If you see something in my code that doesn't make sense, it doesn't necessarily mean you're not getting it - maybe you're just thinking of a different solution than the one I did and that's great.
