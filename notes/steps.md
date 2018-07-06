# Scaffolding
* Add `index.html` with HTML structure
* Add `styles` folder
* Add `reset` and `main` stylesheets and link them to `index.html`

# Planning
* Determine sections of the page
![Youtube layout](youtube_layout.png)
* Add those sections to the HTML
  * Use classes for each element. This keeps our CSS separate from our markup (HTML). We can make changes to the HTML later, and as long as we use the same class names we won't have to make changes to the CSS (e.g. if we need to change the `main` tag to a `div` or `section`)

# Layout
* Add temporary background colors to your elements so you can see what the default layout is
* Use grid to make the sections fill the correct spaces

# Building the sections

## Header
* List the pieces that we'll be adding to the header
* Replace each part with an element

## Nav
* Add `div`s for the 7 sections
* Give the `div`s class names: `.sidebar_section` which we'll use for all of the styles each section has in common, and modifier classes for the section-specific styles
* Let's add the modifier names to the classes and add placeholder text to each div
  * Naming things is hard (Google it. It's true). Try to come up with a good name, don't worry if it's not a perfect name.
* Let's make the last div a `footer`. This way the browser knows that this is where the traditional footer stuff is.
  * Remember how we started off using class names in our styles instead of elements? Changing the `div` to a `footer` is an example of why. If we'd already started creating styles, then later realized we needed to use a different, better-suited element, we wouldn't have to change our CSS as well.
