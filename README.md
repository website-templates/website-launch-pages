# Website launch page

Placeholder page with .htaccess config for pre-launch stage

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
  
```        
* .background                      # Page background (transparent) 
    - .background_image            # Set index_bg.jpg as page background
    - .background_gradient         # Set gradient as page background 
    - .background_blur             # Add 5px blur over page background
* .overlay                         # Page overlay (transparent by default)
    - .overlay_dark                # Set half-opaque dark pattern as overlay
* .project__name                   # Page title
    - .project__name_middle        # Set 20% top margin for page title
    - .project__name_fit           # Enable FitText.js for page title
    - .project__name_shadow        # Set text shadow for page title
```

#### Examples:

* Background gradient page with title and list
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project">
        <h1 id="fit" class="project__name">ProjectName</h1>

        <ul class="project__list">
            <li class="project__item">
                <a class="project__link project__link_empty">Pages</a> 
                <ul class="project__list">
                    <li class="project__item">
                        <a href="home.html" class="project__link">Home Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">About Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Portfolio Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Blog Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Contact Page</a>
                    </li>
                </ul>
            </li>
             <li class="project__item">
                <a class="project__link project__link_empty">Blocks</a> 
                <ul class="project__list">
                    <li class="project__item">
                        <a href="button.html" class="project__link">Button</a>
                    </li>
                    <li class="project__item">
                        <a href="form.html" class="project__link">Form</a>
                    </li>
                </ul>
            </li>
        </ul>
    </main>
</div>
```

![gradient text list page](https://github.com/website-templates/website-launch-pages/blob/master/test_screenshots/gradient-list-page.jpg)

---

* Background gradient page with full-width title
```html
<div class="background background_gradient"></div>
<div class="overlay">
    <main class="project">
        <h1 id="fit" class="project__name project__name_middle">ProjectName</h1>
    </main>
</div>
```

![gradient text page](https://github.com/website-templates/website-launch-pages/blob/master/test_screenshots/gradient-text-page.jpg)

---

* Background image page with title and list
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project">
        <h1 id="fit" class="project__name project__name_shadow">ProjectName</h1>

        <ul class="project__list">
            <li class="project__item">
                <a class="project__link project__link_empty">Pages</a> 
                <ul class="project__list">
                    <li class="project__item">
                        <a href="home.html" class="project__link">Home Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">About Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Portfolio Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Blog Page</a>
                    </li>
                    <li class="project__item">
                        <a href="#" class="project__link">Contact Page</a>
                    </li>
                </ul>
            </li>
             <li class="project__item">
                <a class="project__link project__link_empty">Blocks</a> 
                <ul class="project__list">
                    <li class="project__item">
                        <a href="button.html" class="project__link">Button</a>
                    </li>
                    <li class="project__item">
                        <a href="form.html" class="project__link">Form</a>
                    </li>
                </ul>
            </li>
        </ul>
    </main>
</div>
```

![background image page](https://github.com/website-templates/website-launch-pages/blob/master/test_screenshots/background-image-list-page.jpg)

---

* Background image page with full-width title
```html
<div class="background background_image background_blur"></div>
<div class="overlay overlay_dark">
    <main class="project project_middle">
        <h1 id="fit" class="project__name project__name_middle project__name_fit project__name_shadow">ProjectName</h1>
    </main>
</div>
```

![background image page](https://github.com/website-templates/website-launch-pages/blob/master/test_screenshots/background-image-text-page.jpg)

---

## Credits
[FitText.js](https://github.com/adactio/FitText.js)

## License
[MIT](http://opensource.org/licenses/MIT)
