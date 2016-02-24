# Website launch stub

Stub page with .htaccess config for pre-launch stage

---

##Contents
* [Page structure](#pge-structure)
    - [Options](#options)
    - [Examples](#examples) 
* [Credits](#credits)
* [License](#license)


## Page structure 
The main part contain a few lines of markup. There was used BEM naming, so we're able to use modifiers and change page's style.

#### Options
There you can find classnames of the markup blocks and elements that can be customized using related modifiers:
          
* `.background`                      # Page background (transparent) 
    - `.background_image`            # Set index_bg.jpg as page background
    - `.background_gradient`         # Set gradient as page background 
    - `.background_blur`             # Add 5px blur over page background
* `.overlay`                         # Page overlay (transparent by default)
    - `.overlay_dark`                # Set half-opaque dark pattern as overlay
* `.project__name`                   # Page title
    - `.project__name_middle`        # Set 20% top margin for page title
    - `.project__name_fit`           # Enable FitText.js for page title
    - `.project__name_shadow`        # Set text shadow for page title


#### Examples:

* Background gradient stub with title and list
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project">
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

* Background gradient stub with full-width title
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project">
        <h1 id="fit" class="project__name project__name_middle">ProjectName</h1>
    </main>
</div>
```

![gradient text stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/gradient-text-stub.jpg)

---

* Background image stub with title and list
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project">
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

* Background image stub with full-width title
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project project_middle">
        <h1 id="fit" class="project__name project__name_middle project__name_fit project__name_shadow">ProjectName</h1>
    </main>
</div>
```

![background image stub](https://github.com/website-templates/website-launch-stubs/blob/master/test_screenshots/background-image-text-stub.jpg)

---

## Credits
[FitText.js](https://github.com/adactio/FitText.js)

## License
[MIT](http://opensource.org/licenses/MIT)
