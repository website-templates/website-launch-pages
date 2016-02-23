# Website launch stub

Stub page with .htaccess config for pre-launch stage

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
        <h1 id="fit" class="project__name">ProjectName</h1>

        <ul class="project__list">
            <li class="project__item">
                <a href="home.html" class="project__link">Home Page</a>
            </li>
        </ul>
    </main>
</div>
```

![gradient text list stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/gradient-list-stub.jpg)

---

### Background gradient stub with full-width title
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project project_middle">
        <h1 id="fit" class="project__name">ProjectName</h1>
    </main>
</div>
```

![gradient text stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/gradient-text-stub.jpg)

---

### Background image stub with title and list
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project project_top">
        <h1 id="fit" class="project__name project__name_shadow">ProjectName</h1>

        <ul class="project__list">
            <li class="project__item">
                <a href="home.html" class="project__link">Home Page</a>
            </li>
        </ul>
    </main>
</div>
```

![background image stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/background-image-list-stub.jpg)

---

### Background image stub with full-width title
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project project_middle">
        <h1 id="fit" class="project__name project__name_fit project__name_shadow">ProjectName</h1>
    </main>
</div>
```

![background image stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/background-image-text-stub.jpg)

---

## Credits
[FitText.js](https://github.com/adactio/FitText.js)

## License
[MIT](http://opensource.org/licenses/MIT)
