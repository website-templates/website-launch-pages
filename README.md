# Website launch stub

Stub page with .htaccess config for pre-lunch stage

---

##Contents
* [Page structure](#pge-structure)
* [Credits](#credits)
* [License](#license)


## Page structure 
The main part contain a few lines of markup. There was used BEM naming, so we're able to use modifiers and change page's style.

Let's check some examples:

### Background gradient stub with title and list
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project project_top">
        <h1 id="fit" class="project-name">ProjectName</h1>

        <ul class="project-pages">
            <li class="project-pages__item">
                <a href="home.html" class="project-pages__link">Home Page</a>
            </li>
        </ul>
    </main>
</div>
```

![gradient text list stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/gradient-text-list-stub.jpg)

---

### Background gradient stub with title
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project project_middle">
        <h1 id="fit" class="project-name">ProjectName</h1>
    </main>
</div>
```

![gradient text stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/gradient-text-stub.jpg)

---

### Background image stub with title
```html
<div class="background background_image"></div>
<div class="overlay overlay_dots">
    <main class="project project_middle">
        <h1 id="fit" class="project-name project-name_shadow">ProjectName</h1>
    </main>
</div>
```

![background image stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/background-image-stub.jpg)

---

## Credits
[FitText.js](https://github.com/adactio/FitText.js)

## License
[MIT](http://opensource.org/licenses/MIT)
